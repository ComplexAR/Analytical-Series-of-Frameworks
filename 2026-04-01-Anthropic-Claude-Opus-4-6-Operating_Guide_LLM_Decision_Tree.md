# Operating Guide v1.9 — LLM-Navigable Compact Decision Tree

## Machine-readable navigation aid
- Purpose: Allow an LLM to determine which Operating Guide sections to invoke, in what order, at what depth, for any scenario.
- Format: Each node has an ID, preconditions, actions, outputs, and successor pointers. The LLM traverses from START by evaluating preconditions and following successor pointers.
- Companion: Appendix D Orchestrator Prompts (§D.9) provide paste-ready execution prompts. This tree provides the routing logic that selects and sequences them.

---

## Invariant layer (active at every node)

These sections are not traversed once — they are **continuously active** constraints and must be checked at every decision point.

| Invariant | Section | Rule |
|---|---|---|
| Hiddens Tier 1 scan | §7.1 | Must fire at least twice: early (after framing) and pre-closure. Assume hiddens exist. |
| Hiddens Micro-Protocol | §7.2 | Every shortlisted hidden must be dimensionally profiled and assigned detection + remediation interfaces. |
| Tier 3 escalation | §7.3 | Escalate if: high consequence, adversarial concealment, persistent disagreement, repeat failure, cascade suspicion. |
| Closure discipline | §7.4 | Every exit must record: residual unknowns, acceptability rationale, monitoring plan, ownership, learning hook. |
| Prompt discipline | §D.3 PD-01–PD-10 | Tag all claims F/I/A/U. Do not invent facts. Separate observation from interpretation. Evidence provenance required. Default to hiddenness. No premature closure. |
| Operating principles | §10 | Mandatory constraints: visibility-first, proportionality, explicit residual unknowns. |

---

## Decision tree nodes

```
NODE: START
  id: N0
  preconditions: Scenario or case question has been received.
  actions:
    1. Read §1.1 (core premise): visibility failures are the target.
    2. Check §1.2 preconditions checklist: case question defined? Owner named? Timebox agreed? Access audited?
    3. Load §2.1–2.2 (group system G1–G6 and Group-to-Hiddens linkage).
    4. If LLM-assisted: load §D.7 system instruction block; activate F/I/A/U tagging.
    5. Create baseline artefacts per §6.1: Coverage Matrix, Evidence Ledger, Hiddens Register, Hypothesis/Test Backlog.
  outputs: Case statement, preconditions status, baseline artefact shells.
  successors: → N1 (speed gate)
```

```
NODE: SPEED_GATE
  id: N1
  preconditions: N0 complete.
  actions:
    1. Evaluate §4.1 use-case routing table: match scenario to use case.
    2. Evaluate §D.6.1 mode definitions:
       - Time ≤ 180 min OR need is stabilisation/triage → RAPID
       - Time > 180 min AND need is explanation/accountability/prevention → INVESTIGATIVE
    3. Record mode selection with rationale per §D.6.7.
  outputs: Mode selection (RAPID | INVESTIGATIVE) with rationale.
  successors:
    IF mode = RAPID → N2R (rapid protocol)
    IF mode = INVESTIGATIVE AND failure occurred → N2I_POST (post-failure protocol)
    IF mode = INVESTIGATIVE AND no failure → N2I_PRE (proactive protocol)
```

```
NODE: RAPID_PROTOCOL
  id: N2R
  preconditions: Mode = RAPID.
  actions:
    Execute §5.1 steps 0–6 in sequence:
      Step 0: Case question + timebox [G1] → case statement
      Step 1: Tier 1 Hiddens scan [§7.1, G5] → scan table + shortlist
      Step 2: Boundaries, time horizon, scale [G1] → boundary map
      Step 3: System structure + dependencies [G2] → system sketch
      Step 4: Evidence quality + key gaps [G5] → evidence register + uncertainty register
      Step 5: Immediate risks + stabilisation [G6] → risk shortlist + actions
      Step 6: Decide depth + plan [G6] → investigation plan + owners
    At each step: apply §D.3 PD-01–PD-10; tag F/I/A/U; populate §6 artefacts.
    §D.6.4 No-Early-Exclusion Rule: every group gets at least a light scan.
  outputs: Rapid protocol artefact set per §D.4.2.
  gate_question: At Step 6 — commit to Rapid closure, or escalate?
  successors:
    IF commit → N3 (routing gate, then N4 loop for any remaining execution)
    IF escalate → N1 (re-enter speed gate as INVESTIGATIVE)
```

```
NODE: POST_FAILURE_PROTOCOL
  id: N2I_POST
  preconditions: Mode = INVESTIGATIVE; failure or near-miss has occurred.
  actions:
    Execute §5.2 phases 1–11:
      Phase 1 (Frame): Classify situation; set boundaries [G1]
      Phase 2 (Frame): Tier 1 Hiddens scan [§7.1, G5]
      Phase 3 (Model): System/relations/process maps [G2]
      Phase 4 (Model): Causal hypotheses + alternative mechanisms [G2/G5]
      Phase 5 (Agency): Actors, incentives, power, responsibility [G3]
      Phase 6 (Meaning): Narratives, comms, norms, legitimacy [G4]
      Phase 7 (Epistemics): Evidence grading, uncertainties, investigation failure risks [G5]
      Phase 8 (Synthesis): Diagnosis with residual hiddenness [G5 + §7.2]
      Phase 9 (Convert): Decisions, interventions, governance, risk [G6]
      Phase 10 (Assure): Detection/remediation interfaces [§7.2 + G6]
      Phase 11 (Learn): Learning loop, drift indicators [G6]
    §7.5 Targeted Scans: may be invoked at any phase where Tier 1 symptoms point to a specific mechanism (see N5).
  outputs: Full investigative artefact set per §D.4.2.
  successors: → N3 (routing gate, invoked at Phase 2 and re-checked at Phase 8)
```

```
NODE: PROACTIVE_PROTOCOL
  id: N2I_PRE
  preconditions: Mode = INVESTIGATIVE; no failure; high-stakes decision or change pending.
  actions:
    Execute §5.3 steps 1–6:
      Step 1: Change intent + assumptions [G1/G6]
      Step 2: Tier 1 Hiddens scan (change-induced mechanisms) [§7.1, G5]
      Step 3: Dependency + coupling impacts [G2]
      Step 4: Incentives/power + comms integrity [G3/G4]
      Step 5: Monitoring, buffers, escalation rules [G6]
      Step 6: Governance + ownership [G6]
  outputs: Proactive protocol artefact set per §D.4.2.
  successors: → N3 (routing gate, invoked at Step 2)
```

```
NODE: ROUTING_GATE
  id: N3
  preconditions: Tier 1 scan complete; scenario features observable.
  actions:
    1. Traverse §4.3.1 decision tree:
       BRANCH A — Has a materially consequential failure occurred?
         YES → Minimum: G1+G2+G5 DEEP
           A1: Evidence weak/contested? YES → Deepen G5 (Evidence, Uncertainties, Diagnosis, Failures)
           A2: Coupling/cascade? YES → Deepen G2 (Systems, Relations, Processes + Risk)
           A3: Incentives/power/concealment? YES → Add G3 DEEP
           A4: Narratives contested/"too clean"? YES → Add G4 DEEP
           A5: Recommendations change controls? YES → Add G6 DEEP
           A6: Adversarial intent? YES → Full G1–G6 DEEP; Tier 3 Hiddens (§7.3)
         NO → Branch B
       BRANCH B — High-stakes decision or change pending?
         YES → Minimum: G1+G2+G5+G6 DEEP
           B1: Multi-stakeholder conflict? YES → Add G3 DEEP
           B2: Narrative/legitimacy disputes? YES → Add G4 DEEP
           B3: High novelty/tight time? YES → Deepen G2+G5
         NO → Low-stakes/exploratory: G1+G5 light + one domain group deep
    2. Produce §4.3.2 output contract:
       - Routing statement (which branch nodes triggered, why)
       - Minimum group coverage set
       - Full Depth Framework Execution list + rationale
       - Light Depth Framework Execution list + rationale
       - Escalation triggers (conditions that would force expansion)
    3. Map groups to specific frameworks using §3.2.
  outputs: Routing statement, coverage plan, depth plan, escalation triggers.
  successors: → N4 (execution loop)
```

```
NODE: EXECUTION_LOOP
  id: N4
  preconditions: Routing statement and depth plan exist.
  actions:
    Execute §5.0 iterative loop:
    WHILE stop_conditions NOT met:
      1. EXECUTE_DEEP: For each Full Depth framework (§5.0.2 step 4):
         a) Extract facts; tag F/I/A/U
         b) Populate core tables (Types/Dynamics/Interfaces)
         c) Add/adjust candidate hiddens
         d) Add tests/probes; update Evidence Ledger
      2. EXECUTE_LIGHT: For each Light Depth framework (§5.0.2 step 5):
         a) Run scan prompts; record high-signal candidates only
         b) If escalation condition met → upgrade to Full Depth
      3. CHECK_TARGETED_SCANS: → N5 (evaluate whether §7.5 scans are warranted)
      4. TEST: Execute probes/tests or produce Evidence Request List (§5.0.2 step 6)
         - Every U-tagged item must generate a probe/test (PD-01, PD-05)
      5. RE_SCAN: Re-run Tier 1 Hiddens scan with updated knowledge (§5.0.2 step 7, §7.1)
         - If new hiddenness classes found → update routing → loop
      6. QUALITY_CHECK: Apply §8 controls:
         - Alternative explanations maintained? (§8.1)
         - Evidence graded? (§8.1)
         - Anti-theatre rule satisfied? (§8.2)
      7. EVALUATE_STOP: Check §5.0.4 stop conditions (all must hold):
         a) Timebox requires output
         b) Evidence supports claims at required confidence
         c) Residual unknowns are explicit, prioritised, assigned
         d) Detection interfaces exist for top residual hiddens
    IF iteration_trigger fires (§5.0.3):
      - Contradictory evidence → preserve disagreement; propose tests; loop
      - "Too clean" story → add disconfirming hypotheses; strengthen G5; loop
      - High-impact Unknown → escalate coverage or Tier 3; loop
      - New artefacts arrive → re-execute + re-test + re-scan; loop
      - Governance implications → add/strengthen G6; loop
  outputs: Updated registers, framework tables, Hiddens Register.
  successors:
    IF stop conditions met → N6 (closure)
    IF escalation required → N3 (re-route with expanded coverage)
```

```
NODE: TARGETED_SCAN_EVALUATION
  id: N5
  preconditions: Tier 1 scan has produced symptoms; execution is in progress.
  actions:
    1. Check: do Tier 1 symptoms, scenario features, or stakeholder accounts point to a specific hiding mechanism?
    2. If YES: consult §7.5.3 Triage Matrix:
       PRIMARY selector: Hiddens meta-category of the symptom (I–VI)
       SECONDARY selector: Scenario features (14 feature types)
       → Matrix returns recommended scan(s) from the catalogue of 13
    3. Select scan(s). Execute per §7.5.4 execution protocol:
       Step 1: Select (confirm scan applies via investigative question)
       Step 2: Execute scan steps in sequence (3–5 frameworks per scan)
       Step 3: Converge findings into §7.2 Micro-Protocol
       Step 4: Record cross-scan signals (§7.5.5 interaction map: 21 interactions)
    4. If LLM-assisted: use §7.5.8 adapter:
       - §7.5.8.1 Universal pseudocode
       - §7.5.8.3 Gate questions (4 per scan, 52 total) — exit early if no material basis
       - §7.5.8.2 Per-step minimum output table (11 fields)
       - §7.5.8.4 Depth triggers (8 conditions for Light → Full escalation)
    5. Check §7.5.5 Scan Interaction Map: do findings trigger a second scan?
  scan_catalogue:
    Family A (Social/organisational):
      Scan 1: Suppression Scan — Power (G3) → Incentives (G3) → Culture & Norms (G4) → Communications (G4) → Hiddens (G5)
      Scan 5: Legitimacy Theatre Scan — Legitimacy (G4) → Governance (G6) → Culture & Norms (G4) → Responsibility (G3) → Hiddens (G5)
      Scan 8: Narrative Capture Scan — Narratives (G4) → Perspectives (G4) → Evidence (G5) → Culture & Norms (G4) → Hiddens (G5)
      Scan 11: Belief Persistence Scan — Beliefs (G5) → Values (G4) → Evidence (G5) → Diagnosis (G5) → Hiddens (G5)
    Family B (Structural/systemic):
      Scan 3: Positional Blindness Scan — Perspectives (G4) → Boundaries (G1) → Scale (G1) → Dimensions (G1) → Hiddens (G5)
      Scan 6: Cascade Discovery Scan — Systems (G2) → Relations (G2) → Causation (G2) → Boundaries (G1) → Hiddens (G5)
      Scan 9: Uncertainty Masking Scan — Uncertainties (G5) → Evidence (G5) → Metrics (G5) → Decisions (G6) → Hiddens (G5)
      Scan 12: Competency Blindspot Scan — Competencies (G3) → Agents (G3) → Resources (G2) → Processes (G2) → Hiddens (G5)
    Family C (Temporal):
      Scan 2: Drift Scan — Time (G1) → Processes (G2) → Governance (G6) → Failures (G5) → Hiddens (G5)
      Scan 7: Amnesia Scan — Learning & Adaptation (G6) → Knowledge (G5) → Failures (G5) → Governance (G6) → Hiddens (G5)
    Family D (Action-induced):
      Scan 4: Evidence Corruption Scan — Evidence (G5) → Incentives (G3) → Communications (G4) → Narratives (G4) → Hiddens (G5)
      Scan 10: Negligence Scan — Responsibility (G3) → Failures (G5) → Hiddens (G5) → Causation (G2)
      Scan 13: Intervention Blindspot Scan — Interventions (G6) → Risk (G6) → Diagnosis (G5) → Systems (G2) → Hiddens (G5)
  outputs: Targeted scan findings, candidate hiddens, cross-scan signals.
  successors: → N4 (return to execution loop with enriched findings)
```

```
NODE: CLOSURE
  id: N6
  preconditions: All §5.0.4 stop conditions met.
  actions:
    1. Apply §7.4 closure discipline:
       - Residual unknowns list (what, why)
       - Acceptability rationale (why proceeding is acceptable given stakes)
       - Monitoring plan (signals that would change the decision)
       - Ownership (who watches, who acts, escalation pathways)
       - Learning hook (when and how the case will be revisited)
    2. Produce §D.4 output contract artefacts:
       RAPID mode minimum: Hiddens Register, Evidence Register, Coverage Matrix, Risk shortlist, Investigation plan
       INVESTIGATIVE mode minimum: All of the above + Hypothesis/Test Backlog, Decision Record, Intervention portfolio, Governance changes, Learning plan
    3. Final §8 quality check:
       - Anti-theatre rule (§8.2): every major claim backed by evidence, uncertainty, hiddenness check, and owner
    4. Record in §9 governance:
       - Case added to practitioner repository
       - Any taxonomy extensions or protocol amendments flagged per §9.2 change control
  outputs: Closure statement, final registers, residual unknowns, monitoring plan, learning plan.
  successors: → END (or → N4 if closure is revoked by new information)
```

```
NODE: NON_CLOSURE
  id: N7
  preconditions: §5.0.4 stop conditions NOT met; escalation or non-closure required.
  actions:
    1. Produce non-closure output with explicit requirements to close.
    2. Options:
       a) Expand group coverage (add groups per §4.3.1 branch logic)
       b) Upgrade Light → Full Depth on specific frameworks
       c) Escalate Hiddens to Tier 3 (§7.3): full 30-type run + detection/remediation matrix
       d) Escalate Rapid → Investigative Run Mode (→ N1 re-entry)
       e) Invoke §7.5 Targeted Scans if specific mechanism now suspected (→ N5)
    3. Record escalation rationale and updated routing statement.
  outputs: Non-closure statement, escalation rationale, updated routing.
  successors: → N3 (re-route) or → N4 (re-execute with expanded scope)
```

---

## Traversal summary (LLM quick-reference)

```text
N0 (START)
 │
 ▼
N1 (SPEED GATE) ──────────────────────────────┐
 │                                              │
 ├─ RAPID ─────→ N2R (§5.1, 6 steps)           │
 │                 │                            │
 │                 ├─ commit → N3 → N4 ──┐      │
 │                 └─ escalate ──────────┘      │
 │                                     │        │
 ├─ INVEST+FAIL → N2I_POST (§5.2, 11 phases)   │
 │                 └──────→ N3 → N4 ──┐ │       │
 │                                     │ │      │
 └─ INVEST+PRE ─→ N2I_PRE (§5.3, 6 steps)      │
                   └──────→ N3 → N4 ──┘ │       │
                                    │    │      │
                   ┌────────────────┘    │      │
                   ▼                     │      │
                  N4 (EXECUTION LOOP) ◄──┘      │
                   │                            │
                   ├─ check scans? → N5 (§7.5)  │
                   │                 └─→ N4     │
                   │                            │
                   ├─ stop met? → N6 (CLOSURE)  │
                   │              └─→ END       │
                   │                            │
                   └─ stop NOT met? → N7        │
                                      │         │
                                      ├─→ N3    │
                                      ├─→ N4    │
                                      └─→ N1 ──┘

INVARIANT LAYER (active at ALL nodes):
  §7.1 Tier 1 scan (early + pre-closure)
  §7.2 Micro-Protocol (every candidate hidden)
  §7.3 Tier 3 escalation triggers
  §7.4 Closure discipline (every exit)
  §D.3 PD-01–PD-10 (all LLM outputs)
  §10 Operating Principles (all work)
```

---

## Section-to-node mapping (which section is used where)

| Section | Node(s) | Role |
|---|---|---|
| §1 Core Premise | N0 | Framing and preconditions |
| §2 Group System | N0, N3 | Coverage model and Hiddens linkage |
| §3 Framework Index | N3 | Map groups to specific frameworks |
| §4.1 Use-case routing | N1, N3 | Match scenario to use case and coverage |
| §4.2 Depth selection | N3 | Full Depth vs Light Depth criteria |
| §4.3 Routing decision tree | N3 | Branch logic for group coverage |
| §5.0 Iterative loop | N4 | Master execution cycle |
| §5.1 Rapid protocol | N2R | 6-step rapid sequence |
| §5.2 Post-failure protocol | N2I_POST | 11-phase investigative sequence |
| §5.3 Proactive protocol | N2I_PRE | 6-step pre-change sequence |
| §6 Artefacts library | N4, N6 | Schemas for registers and deliverables |
| §7.1 Tier 1 scan | Invariant | Early + pre-closure Hiddens sweep |
| §7.2 Micro-Protocol | Invariant | Profile and remediate candidate hiddens |
| §7.3 Escalation rule | Invariant, N7 | Tier 3 trigger conditions |
| §7.4 Closure discipline | Invariant, N6 | Required closure content |
| §7.5 Targeted scans | N5 | Optional mechanism-specific pursuit |
| §7.5.3 Triage Matrix | N5 | Symptom → scan selection |
| §7.5.5 Interaction Map | N5 | Cross-scan compounding |
| §7.5.8 LLM Adapter | N5 | Pseudocode, gates, output tables |
| §8 Quality controls | N4 (step 6) | Anti-theatre rule, checklists |
| §9 Governance | N6 | Post-investigation learning and change control |
| §10 Operating Principles | Invariant | Mandatory constraints |
| §11 Glossary | All | Shared terminology |
| §D.3 Prompt Discipline | Invariant | PD-01 to PD-10 |
| §D.4 Output contract | N6 | Required deliverables per run mode |
| §D.5 Routing logic | N3 | Canonical coverage and depth rules |
| §D.6 Run modes | N1 | Mode definitions and operational sequences |
| §D.7 System instruction | N0 | LLM initialisation block |
| §D.8 Prompt pack | N2R, N2I_POST, N2I_PRE | Mode-specific paste-ready prompts |
| §D.9 Orchestrator Prompts | N1, N2R, N2I_POST, N2I_PRE | Canonical orchestrator sequences |
| Appendix E Schemas | N4, N6 | Machine-readable field definitions |
| Appendix F Worked Example | Reference | Illustrative fictional walkthrough |

---

## Depth × speed matrix (how depth modulates across modes)

| Dimension | Rapid Run Mode | Investigative Run Mode |
|---|---|---|
| Timebox | 60–180 min | Days–weeks |
| Protocol | §5.1 (6 steps) | §5.2 (11 phases) or §5.3 (6 steps) |
| Minimum coverage | Tier 1 Hiddens + boundary + system sketch + evidence gaps + risk | G1+G2+G5 mandatory + others per §4.3 routing |
| Full Depth frameworks | Typically 3–6 (high-signal only) | Typically 8–20 (per routing and stakes) |
| Light Depth frameworks | All others (scan-level) | Remaining after Full Depth selection |
| Hiddens depth | Tier 1 (standard); Tier 3 only if adversarial | Tier 1 → Tier 2 → Tier 3 as warranted |
| §7.5 Targeted Scans | Rarely (record as follow-up if time insufficient) | Invoked when Tier 1 symptoms point to mechanism |
| Artefacts | Slim set per §D.4.2 | Full set per §D.4.2 |
| Closure standard | Bounded; explicit residual unknowns | Full; detection interfaces for all high-consequence hiddens |
| Escalation path | → Investigative Run Mode | → Tier 3 / full G1–G6 DEEP |

---

## Document control
- Version: 1.0
- Date: 2026-04-01
- Companion to: Analytical Series Operating Guide v1.9
- Author: Anthropic Claude Opus 4.6
