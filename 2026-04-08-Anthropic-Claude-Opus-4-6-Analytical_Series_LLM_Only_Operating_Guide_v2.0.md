# Analytical Series LLM-Only Operating Guide v2.0

## Document Information
| Field | Value |
|---|---|
| Document name | Analytical Series LLM-Only Operating Guide |
| Version | v2.0 |
| Date | 2026-04-08 |
| Status | Release |
| Purpose | Compact runtime execution adapter for LLM-assisted discovery of Hiddens in complex scenarios |
| Compatibility | Based on Operating Guide v3.0 (50 frameworks). Integrates 14 new frameworks from Phase 4 update. |
| Target token count | 18,000–22,000 tokens |
| Intended use | Load alongside 4 framework extracts when executing the Analytical Series with an LLM |

## Quick Usage Note
This document contains only operational tables, pseudocode, terse definitions, and decision logic. All narrative prose for human readers has been stripped. Use alongside framework documents for Full Depth execution. For Light Depth/scan-level execution, this guide is self-contained.

---

# Part 1: Definitions and Architecture

## 1.1 Core Definitions
| Term | Definition (operational) |
|---|---|
| Hidden | A reality-relevant factor not visible/legible/actionable to relevant actors at the relevant time due to identifiable hiding mechanisms (not merely "unknown"). |
| Complex scenario | Non-trivial interactions, feedback, delays, multi-scale effects, contested narratives, incomplete evidence, and/or multi-actor strategic behaviour. |
| Failure | Realised outcome (or near miss) where expectations, requirements, safety margins, or objectives were not met; includes process drift and governance breakdowns. |
| Closure | Decision to stop exploring with residual hiddenness explicitly recorded, including why acceptable (or not) given stakes. |
| Tiered scan | Staged depth model: Tier 1 (six-category scan), Tier 2 (crosswalk shortlist), Tier 3 (full 30-type run). |
| Hiding mechanism | Identifiable process or structure by which a reality-relevant factor becomes unavailable to relevant actors at the relevant moment. |

## 1.2 Group System (G1–G6)
| Group | Shorthand | Primary function |
|---|---|---|
| G1 | Framing | Boundaries, time, scale, context class |
| G2 | Mechanism | Structure, relations, processes, causation, resources |
| G3 | Agency | Actors, incentives, power, responsibility |
| G4 | Meaning | Narratives, norms, legitimacy, communications |
| G5 | Epistemics | Evidence, uncertainties, failures, hiddens, diagnosis |
| G6 | Action & Control | Decisions, interventions, governance, risk, learning |

## 1.3 Group-to-Hiddens Linkage (where hiddenness is typically generated)
| Group | Typical hiddenness generators | Default probe |
|---|---|---|
| G1 | Wrong boundary, wrong unit, wrong time horizon, misclassification, spatial/place-dependent framing | Rebuild boundary map; re-run context classification; test scale/time/place |
| G2 | Hidden interactions, tight coupling, feedback delays, uncontrolled dependencies, observability limits, technology opacity, institutional inertia, network effects, emergence blindness, coordination failures | System map + dependency audit; probe coupling/containment; look for feedback, delay, and emergent properties |
| G3 | Incentive suppression, power-filtered reporting, responsibility diffusion, strategic concealment, cognitive blindness, interest conflicts, emotional suppression, conflict concealment | Incentives/power map; access audit; accountability map; cognitive/emotional/conflict analysis; look for strategic hiding |
| G4 | Narrative closure, legitimacy theatre, norm constraints on speaking, communications bottlenecks, trust breakdown, ethical blindness | Narrative map; comms pathway audit; legitimacy tests; trust/ethics analysis; dissent capture |
| G5 | Weak evidence, model overreach, untested assumptions, hindsight bias, diagnostic mono-culture | Evidence grading; uncertainty register; failure pattern checks; Hiddens scan Tier 1–3 |
| G6 | Control drift, governance gaps, risk appetite mismatch, brittle decisions, learning not institutionalised, implementation failures | Decision log + intervention theory; governance map; implementation audit; monitor drift; implement learning loop |

## 1.4 Framework-to-Group Mapping (v2.0 — 50 frameworks; 14 new frameworks marked †)
| Framework | Primary group | Stage |
|---|---|---|
| Boundaries | G1 | Upstream |
| Dimensions | G1 | Upstream |
| Realities | G1 | Upstream |
| Scale | G1 | Upstream |
| Scenarios † | G1 | Upstream |
| Situations Context Classification | G1 | Upstream |
| Space and Place † | G1 | Upstream |
| Time | G1 | Upstream |
| Causation | G2 | Middle |
| Coordination † | G2 | Middle |
| Emergence † | G2 | Middle |
| Institutions † | G2 | Middle |
| Networks † | G2 | Middle |
| Processes | G2 | Middle |
| Relations | G2 | Middle |
| Resources | G2 | Middle |
| Systems | G2 | Middle |
| Technology † | G2 | Middle |
| Agents | G3 | Middle |
| Cognition † | G3 | Middle |
| Competencies | G3 | Middle |
| Conflict † | G3 | Middle |
| Emotions † | G3 | Middle |
| Incentives | G3 | Middle |
| Interests † | G3 | Middle |
| Personas | G3 | Middle |
| Power | G3 | Middle |
| Responsibility | G3 | Middle |
| Communications | G4 | Middle |
| Culture and Norms | G4 | Middle |
| Ethics † | G4 | Middle |
| Legitimacy | G4 | Middle |
| Narratives | G4 | Middle |
| Perspectives | G4 | Middle |
| Trust † | G4 | Cross-cutting |
| Values | G4 | Middle |
| Beliefs | G5 | Middle |
| Diagnosis | G5 | Middle |
| Evidence | G5 | Cross-cutting |
| Failures | G5 | Cross-cutting |
| Hiddens | G5 | Cross-cutting |
| Knowledge | G5 | Cross-cutting |
| Metrics | G5 | Cross-cutting |
| Uncertainties | G5 | Cross-cutting |
| Decisions | G6 | Downstream |
| Governance | G6 | Downstream |
| Implementation † | G6 | Downstream |
| Interventions | G6 | Downstream |
| Learning and Adaptation | G6 | Downstream |
| Risk | G6 | Downstream |

---

# Part 2: Routing and Execution

## 2.1 Compact Routing Decision Tree (scenario features → minimum group coverage + deep/light)
```text
START
├─ A. Has a materially consequential failure or near-miss occurred?
│   ├─ YES → Minimum: G1 + G2 + G5 (DEEP)  [post-failure baseline]
│   │   ├─ A1. Evidence weak/contested? YES → Deepen: Evidence, Uncertainties, Diagnosis, Failures
│   │   ├─ A2. Coupling/cascade suspected? YES → Deepen: Systems, Relations, Processes, Technology, Networks, Emergence, Coordination + Risk
│   │   ├─ A3. Incentives/power/concealment plausible? YES → Add G3 (DEEP) [Agents, Cognition, Conflict, Competencies, Emotions, Incentives, Interests, Personas, Power, Responsibility]
│   │   ├─ A4. Narratives contested or "too clean"? YES → Add G4 (DEEP) [Communications, Culture & Norms, Ethics, Legitimacy, Narratives, Perspectives, Trust, Values]
│   │   ├─ A5. Recommendations change controls/governance? YES → Add G6 (DEEP) [Decisions, Governance, Implementation, Interventions, Learning & Adaptation, Risk]
│   │   └─ A6. Adversarial intent or intentional concealment? YES → Full G1–G6 (DEEP); Tier 3 Hiddens
│   └─ NO → Branch B
└─ B. No failure, but high-stakes decision or change pending?
    ├─ YES → Minimum: G1 + G2 + G5 + G6 (DEEP)  [pre-change baseline]
    │   ├─ B1. Multi-stakeholder conflict? YES → Add G3 (DEEP); include Emotions, Interests, Conflict, Cognition
    │   ├─ B2. Narrative/legitimacy disputes? YES → Add G4 (DEEP)
    │   └─ B3. High novelty/tight constraints? YES → Deepen G2 (Systems/Processes/Relations/Emergence/Scenarios) and strengthen G5 (Uncertainties/Evidence)
    └─ NO → Low-stakes/exploratory: G1+G5 light + one domain-relevant group deep
```

### 2.1.1 Decision tree output contract
| Output | Required content |
|---|---|
| Routing statement | Which branch nodes triggered and why |
| Minimum group coverage | Explicit set of groups required before closure |
| Full Depth Framework Execution list | Frameworks to run deeply (with rationale) |
| Light Depth Framework Execution list | Frameworks to scan lightly (with rationale) |
| Escalation triggers | Conditions that force expansion to additional groups or Tier 3 |

## 2.2 Execution Loop (pseudocode)
```text
1) Create baseline artefacts: Coverage(G1–G6), Evidence Ledger, Hiddens Register, Hypothesis/Test Backlog.
2) Run Tier 1 Hiddens scan (assume hiddens exist) → generate initial candidate hiddens + hypotheses.
3) Route using Section 2.1 decision tree → set minimum group coverage + Full Depth / Light Depth plan.
4) For each deep framework:
     a) Extract facts from scenario and artefacts; tag F/I/A/U.
     b) Populate framework core tables (Types/Dynamics/Interfaces) as applicable.
     c) Add/adjust candidate hiddens (mechanism + impact + detectability).
     d) Add tests/probes and required artefacts; update Evidence Ledger.
5) For each light framework/group:
     a) Run scan prompts; record only high-signal candidates and missing-information triggers.
6) Execute tests/probes where possible (or produce an Evidence Request List).
7) Re-run Tier 1 Hiddens scan (pre-closure) → identify omissions-by-lens; update routing if needed.
8) Apply closure criteria:
     - If met: produce remediation portfolio + monitoring + residual unknowns (governed).
     - If not met: produce non-closure output with explicit requirements to close, or escalate to Tier 3.
```

### 2.2.1 Iteration triggers
| Trigger | Response |
|---|---|
| Contradictory evidence | Preserve disagreement; propose disambiguation tests; update Evidence Ledger |
| "Too clean" story | Add disconfirming hypotheses; strengthen G5; re-scan Tier 1 |
| High-impact Unknown | Escalate coverage (add groups) or elevate to Tier 3 Hiddens |
| New artefacts arrive | Re-run Execute → Test → Re-scan phases |
| Governance implications | Add/strengthen G6; ensure Decision Record includes residual unknowns |

### 2.2.2 Stop conditions (bounded closure)
- Decision timebox requires an output
- Evidence Ledger supports key claims at required confidence level
- Residual Unknowns are explicit, prioritised, and assigned owners/actions
- Remediation plan includes detection interfaces for top residual hiddens

If not met → output non-closure with explicit close-out requirements.

## 2.3 Run Mode and Depth Definitions
| Mode | Objective | Protocol | Completion |
|---|---|---|---|
| Rapid Run Mode | Coverage-first scan (60–180 min) | §2.3.1 below | Candidate Hiddens + tests + info requests + escalation recommendation |
| Investigative Run Mode | Disciplined depth on routed subset | §2.3.2 below | Routed deep outputs + Light Depth elsewhere (scan-level) + Tier 2 mapping + remediation/monitoring + residual unknowns (or non-closure requirements) |

### 2.3.1 Rapid Run Mode (7-step protocol)
| Step | Objective | Groups | Minimum artefacts |
|---|---|---|---|
| 1 | Case question + timebox | G1 | Case statement |
| 2 | Tier 1 Hiddens scan (assume hiddens exist) | G5 | Tier 1 scan table + shortlist |
| 3 | Boundaries, time, scale | G1 | Boundary map + time/scale note |
| 4 | System structure and dependencies | G2 | System sketch + dependency list |
| 5 | Evidence quality and key gaps | G5 | Evidence register + uncertainty register |
| 6 | Immediate risks and stabilisation | G6 | Risk shortlist + immediate actions |
| 7 | Investigation depth and plan | G6 | Investigation plan + owners |

### 2.3.2 Post-Failure Hidden Discovery (11-phase protocol)
| Phase | Objective | Groups | Standard outputs |
|---|---|---|---|
| Frame (1–2) | Classify; set boundaries, time, scale; run Tier 1 Hiddens scan | G1, G5 | Case statement; boundary map; Tier 1 scan |
| Model (3–4) | Build system/relations/process maps; build causal hypotheses | G2, G5 | System map; dependency register; hypotheses |
| Agency (5) | Map actors, incentives, power, responsibility | G3 | Stakeholder map; incentives/power map |
| Meaning (6) | Map narratives, comms, norms, legitimacy | G4 | Narrative map; comms audit; legitimacy tests |
| Epistemics (7) | Grade evidence, record uncertainties | G5 | Evidence register; uncertainty register |
| Synthesis (8) | Produce diagnosis with residual hiddenness | G5 | Diagnosis statement; residual unknowns |
| Convert (9) | Translate into decisions, interventions, governance | G6 | Decision record; intervention portfolio; governance changes |
| Assure (10) | Define detection/remediation interfaces | G5/G6 | Detection plan; remediation plan; monitoring cadence |
| Learn (11) | Install learning loop and prevent drift | G6 | Learning plan; after-action cadence |

---

# Part 3: Hiddens Scanning

## 3.1 Tier 1 Six-Category Scan (required early and pre-closure)
| Hiddens meta-category | Why active | Typical symptoms | Default checks |
|---|---|---|---|
| I Perceptual | Attention/observation limits universal | Missed obvious signals; selective noticing | Fresh-eyes review; workload/attention audit |
| II Systemic | Methods/models exclude realities | Frame disputes; metric/proxy distortions | Reframe exercise; proxy review; calibration checks |
| III Informational | Channels structured and political | Silence, noise, fragmentation | Channel audit; access audit; integration review |
| IV Temporal | History embeds constraints/blinders | Legacy effects; slow drift | Historical reconstruction; assumption dating |
| V Relational | Position determines visibility | Stakeholder blindspots; perspective lock-in | Perspective rotation; multi-level analysis |
| VI Ontological | Category absence/predictability limits | Anomalies without language | Anomaly log; "new category" proposals |

## 3.2 Targeted Scan Catalogue (13 scans + triage matrix)

| Scan name | Family | What it detects | Gate question | Frameworks involved |
|---|---|---|---|---|
| Suppression | A | Deliberate or structurally incentivised concealment sustained by power, incentives, norms, and comms bottlenecks. | Who benefits from silence, and what systems enforce it? | Power, Incentives, Culture & Norms, Communications, Hiddens |
| Drift | C | Gradual normalised deviation where incremental change falls below detection thresholds. | What has changed so slowly that nobody noticed? | Time, Processes, Governance, Failures, Hiddens |
| Positional Blindness | B | Structural invisibility caused by dominant analytical perspective, boundary, or scale excluding realities. | What can't be seen from where we're standing? | Perspectives, Boundaries, Scale, Dimensions, Hiddens |
| Evidence Corruption | A | Contamination of evidence base through filtering, echoing, distortion, gaming, or fabrication. | Can we trust what we think we know? | Evidence, Incentives, Communications, Narratives, Hiddens |
| Legitimacy Theatre | A | Paper–practice decoupling where formal systems look healthy while lived practice has diverged. | Where is compliance performative, and what does the performance conceal? | Legitimacy, Governance, Culture & Norms, Responsibility, Hiddens |
| Cascade Discovery | B | Hidden coupling and transmission pathways not modelled or monitored. | What could propagate through connections we haven't mapped? | Systems, Relations, Causation, Boundaries, Hiddens |
| Amnesia | C | Institutional memory failure where knowledge was known but lost through turnover or learning-loop breakdown. | Why does this organisation keep being surprised by the same thing? | Learning & Adaptation, Knowledge, Failures, Governance, Hiddens |
| Narrative Capture | A | Sensemaking closure where a dominant narrative selects what is salient and marginalises disconfirming evidence. | Is a dominant story crowding out what we need to see? | Narratives, Perspectives, Evidence, Culture & Norms, Hiddens |
| Uncertainty Masking | B | Mistyped or suppressed uncertainty communicated with false precision or sanitised before reaching decision-makers. | Where has false precision hidden genuine not-knowing? | Uncertainties, Evidence, Metrics, Decisions, Hiddens |
| Negligence | D | Omission-driven hiddenness where responsible actors failed to detect, investigate, or act. | Who had a duty to look and didn't — and what became hidden as a result? | Responsibility, Failures, Hiddens, Causation |
| Belief Persistence | A | Epistemic filtering where internal belief architecture, identity-protective cognition, or entrenched priors prevent recognition of disconfirming realities. | What are we unable to see because our existing beliefs filter it out? | Beliefs, Values, Evidence, Diagnosis, Hiddens |
| Competency Blindspot | B | Capability-driven invisibility where assigned agents lack skills, cognitive repertoire, tools, or resources to recognise what is visible. | What's hidden because the people responsible for looking don't have the capability to see it? | Competencies, Agents, Resources, Processes, Hiddens |
| Intervention Blindspot | D | Action-induced hiddenness where the intervention itself creates hiding mechanisms, obscures dynamics, or masks the original problem. | What's hidden about why our interventions aren't working — or are making things worse? | Interventions, Risk, Diagnosis, Systems, Hiddens |

### 3.2.1 Triage Matrix (Tier 1 symptoms → scan selection)
| Tier 1 meta-category flagged | Primary scans to consider |
|---|---|
| I Perceptual | Narrative Capture, Belief Persistence, Positional Blindness |
| II Systemic | Uncertainty Masking, Positional Blindness, Belief Persistence |
| III Informational | Suppression, Evidence Corruption |
| IV Temporal | Drift, Amnesia |
| V Relational | Positional Blindness, Suppression, Competency Blindspot |
| VI Ontological | Positional Blindness, Uncertainty Masking, Belief Persistence |

## 3.3 Closure Discipline (recorded residual hiddenness)
| Closure item | Required content |
|---|---|
| Residual unknowns list | What remains uncertain/hidden and why |
| Acceptability rationale | Why proceeding is acceptable given stakes (or why not) |
| Monitoring plan | What signals would change the decision/diagnosis |
| Ownership | Who watches, who acts, escalation pathways |
| Learning hook | When and how the case will be revisited |

---

# Part 4: Prompt Discipline and Output Contract

## 4.1 Prompt Discipline Rules (Canonical) — v1.4
| Rule ID | Rule | Operational requirement |
|---|---|---|
| PD-01 | Do not invent facts | If not provided, mark U (Unknown) and generate probe/test |
| PD-02 | Tag statements as F/I/A/U | Every material claim and register row tagged |
| PD-03 | Separate observation from interpretation | Label I; list plausible alternatives |
| PD-04 | Evidence/provenance required | Cite Evidence Register entry or mark A/I |
| PD-05 | Prefer tests over stories | Prioritise concrete tests/probes over narrative elaboration |
| PD-06 | Track and preserve disagreement | Conflicting accounts treated as potential Hiddens |
| PD-07 | Default to hiddenness | Assume Hiddens exist; run Tier 1 early and pre-closure |
| PD-08 | Do not close prematurely | If criteria not met, output non-closure with requirements |
| PD-09 | Make residual hiddenness explicit | End every run with Residual Unknowns section |
| PD-10 | Canonical source rule | Operating Guide authoritative; framework excerpts quote verbatim or point without modification |

### 4.1.1 F/I/A/U tagging definitions
| Tag | Meaning | Example |
|---|---|---|
| F | Directly observed, documented, or explicitly provided | "System X logged error code Y at 02:14." |
| I | Reasoned conclusion from facts; must note uncertainty and alternatives | "Timing suggests failure propagated from subsystem A." |
| A | Unverified claim adopted temporarily; must be testable | "Assume patch Z was applied to all nodes." |
| U | Not provided or not observable/confirmable; must generate probe/test | "Exact coupling path between services is unknown." |

## 4.2 Output Contract (deliverables)
| Deliverable | Required in all modes? | Notes |
|---|---|---|
| Group Coverage Matrix (G1–G6) | Yes | Coverage status, key questions, major gaps |
| Hiddens Register | Yes | Candidate hidden, mechanism, impact, detectability, F/I/A/U, probe/test |
| Evidence Register (Ledger) | Yes | Claim, evidence, quality, gaps, next evidence |
| Hypotheses & Tests Backlog | Yes | Hypothesis, true/false observations, test, priority |
| Investigation Plan | Recommended (all); Required (post-failure) | Sequenced actions, owners, artefacts requested |
| Decision Record | Required when recommendations made | Includes evidence basis and residual unknowns |
| Residual Unknowns | Yes (all modes) | Structured, owned, with next actions |

---

# Part 5: Orchestrator Prompts and LLM Decision Tree

## 5.1 Mode Selection Gate (canonical orchestrator)

```text
Orchestrator Prompt (Canonical) — v1.4  [MODE SELECTION GATE]

You are applying the Analytical Series of Frameworks to discover, uncover, and understand Hiddens in a complex scenario.

Non-negotiable operating doctrine:
- **Invariant:** Do not conflate **Run Mode** (Rapid Run Mode / Investigative Run Mode) with **Framework Execution Depth** (Full Depth Framework Execution / Light Depth Framework Execution).
- Follow Prompt Discipline Rules (Canonical) v1.4 (Appendix D.3): do not invent facts; tag material claims and register rows as F/I/A/U; preserve provenance; prefer tests over stories; preserve disagreement; do not close prematurely; always output residual unknowns.
- Use the Routing Logic (Section 4.3) at Start-of-Run and Pre-Closure.
- Execute using the unified iteration loop (Section 5.0): Route → Execute → Test → Re-scan → Decide/Close.
- Treat the Framework of Hiddens as the mandatory visibility audit layer: run Tier 1 early and re-run pre-closure (minimum twice).
- Prevent omission-by-lens: touch every group (G1–G6) at least scan-level before closure; allocate depth after routing.

Scenario:
<<PASTE SCENARIO HERE>>

Available evidence:
<<PASTE EVIDENCE / ARTEFACTS HERE>>

Constraints:
<<PASTE CONSTRAINTS HERE>>

TASK — FIRST RESPONSE ONLY (do not proceed beyond this step):
1) Ask the user to select the depth mode:
   - Option A: Rapid Run Mode (timeboxed scan; coverage-first; §5.2)
   - Option B: Investigative Run Mode (selective deep execution + Light Depth Framework Execution elsewhere (scan-level/MVE); §5.0 + §5.2/§5.3)
2) Briefly explain the practical difference:
   - Investigative Run Mode does NOT mean "run every framework deeply"; it means deeper reasoning, discriminating tests, Tier 2 mapping for top Hiddens, and evidence-gated confidence with explicit residual unknowns.
3) Request any missing constraint needed to run correctly (timebox, decision deadline, exclusions).
4) Stop and wait for the user's reply ("Rapid" or "Investigative").

After the user selects, run the corresponding Canonical Orchestrator Prompt in Section 5.2 (Rapid Run Mode) or Section 5.3 (Investigative Run Mode).
```

## 5.2 Canonical Orchestrator Prompt (Rapid Run Mode) v1.4

```text
Canonical Orchestrator Prompt (Rapid Run Mode) — v1.4  [Rapid Run Mode]

You are applying the Analytical Series of Frameworks to discover, uncover, and understand Hiddens in a complex scenario.

Non-negotiable operating doctrine:
- Follow Prompt Discipline Rules (Canonical) v1.4 (Appendix D.3).
- Run Tier 1 Hiddens scan early and re-run pre-closure (minimum twice).
- Objective is coverage-first: candidate Hiddens + probes/tests + evidence gaps; do not over-elaborate narratives.
- Prevent omission-by-lens: touch every group (G1–G6) at least scan-level; allocate depth within the timebox.

Scenario:
<<PASTE SCENARIO HERE>>

Available evidence:
<<PASTE EVIDENCE / ARTEFACTS HERE>>

Constraints:
<<PASTE CONSTRAINTS HERE>>

Phased task (numbering starts at 1):
Phase 1 — Setup (discipline + artefact baselining)
- Create baseline artefacts as Markdown tables (Appendix D.4):
  - Group Coverage Matrix (G1–G6)
  - Hiddens Register
  - Evidence Register (Evidence Ledger)
  - Hypotheses & Tests Backlog
  - Information Requests (if material gaps exist)
  - If recommendations are made: Decision Record

Phase 2 — Tier 1 Hiddens scan (first pass)
- Run the Tier 1 six-category scan (Section 7.1). Populate a ranked shortlist of candidate Hiddens with mechanisms, consequence, detectability, and reducibility notes.

Phase 3 — Rapid routing + minimum coverage check
- Apply the routing decision tree (Section 4.3) to produce: routing statement + minimum group coverage + Full Depth Framework Execution / Light Depth Framework Execution plan.
- In shallow mode, "deep" means "most-attended" (still timeboxed). Do not fully populate every framework table.

Phase 4 — Scan-level coverage (anti-hiddens sweep)
- Run scan-level checks across all groups/frameworks (touch every lens once).
- Record only:
  - high-signal candidate Hiddens,
  - contradictions,
  - missing-information triggers,
  - immediate stabilisation risks (if applicable).

Phase 5 — Pre-closure Tier 1 re-scan + next actions
- Re-run Tier 1 scan (second pass) explicitly asking:
  "Given what we now believe, what class of hiddenness might we still be missing?"
- End with:
  (a) Residual Unknowns (structured + owners),
  (b) Next 5 actions (evidence acquisition / probes),
  (c) Escalation recommendation (stay shallow vs move to deep), and
  (d) Compliance Self-Check table (Pass/Fail) per Appendix D.3.

Output format:
- Use Markdown headings and Markdown tables.
- Tag all material claims and register rows as F/I/A/U.
- Link claims to Evidence IDs where possible.
```

## 5.3 Canonical Orchestrator Prompt (Investigative Run Mode) v1.4

```text
Canonical Orchestrator Prompt (Investigative Run Mode) — v1.4  [Investigative Run Mode]

You are applying the Analytical Series of Frameworks to discover, uncover, and understand Hiddens in a complex scenario, and to propose remediation options where warranted.

Non-negotiable operating doctrine:
- Follow Prompt Discipline Rules (Canonical) v1.4 (Appendix D.3): do not invent facts; tag F/I/A/U; preserve provenance; prefer tests over stories; preserve disagreement; do not close prematurely; always output residual unknowns.
- Use Routing Logic (Section 4.3) at Start-of-Run and Pre-Closure.
- Execute using the unified iteration loop (Section 5.0): Route → Execute → Test → Re-scan → Decide/Close.
- Treat Hiddens as the mandatory visibility audit layer: Tier 1 early and pre-closure (minimum twice); escalate when triggers fire.
- Prevent omission-by-lens: scan-level across all groups/frameworks; run deep only on the routed subset (coverage without exhaustiveness).

Critical clarification:
- Investigative Run Mode does NOT mean "run every framework deeply".
- It means depth of reasoning and discipline: expanded hypotheses + discriminating tests, Tier 2 mapping for top Hiddens, evidence-gated confidence, and explicit residual unknowns.

Scenario:
<<PASTE SCENARIO HERE>>

Available evidence:
<<PASTE EVIDENCE / ARTEFACTS HERE>>

Constraints:
<<PASTE CONSTRAINTS HERE>>

Phased task (numbering starts at 1):
Phase 1 — Setup (discipline + artefact baselining)
- Produce baseline artefacts (Appendix D.4):
  - Group Coverage Matrix (G1–G6)
  - Hiddens Register
  - Evidence Register (Evidence Ledger)
  - Hypotheses & Tests Backlog
  - Information Requests (as needed)
  - If recommendations are made: Decision Record
- Create an Investigation Plan if the run is non-trivial.

Phase 2 — Tier 1 Hiddens scan (first pass) + differential hypotheses
- Run Tier 1 scan (Section 7.1) and create a ranked candidate list.
- Establish at least 2–3 competing hypotheses for material outcomes (differential).

Phase 3 — Routing + depth allocation plan
- Apply routing decision tree (Section 4.3) and produce:
  - routing statement,
  - minimum group coverage,
  - explicit Full Depth Framework Execution vs Light Depth Framework Execution plan (which frameworks/groups go deep vs light, and why),
  - escalation triggers.

Phase 4 — Deep execution (selective, evidence-led) + Light Depth Framework Execution elsewhere (scan-level/MVE)
- Execute at Full Depth on minimum group coverage and routed frameworks:
  - populate the framework's core tables as applicable,
  - expand tests/probes,
  - refine Hiddens with mechanisms and detectability.
- Execute scan-level across remaining groups/frameworks to prevent omission-by-lens.

Phase 5 — Test and evidence acquisition plan
- Convert Unknowns into discriminating tests/probes and information requests (owners + expected discriminators).
- Update Evidence Register with provenance and quality grading.

Phase 6 — Tier 1 re-scan (pre-closure) + Tier 2 mapping for top Hiddens
- Re-run Tier 1 scan (second pass).
- For the top Hiddens, perform Tier 2 mapping and design detection/remediation interfaces.
- Escalate to Tier 3 when triggers are met (Section 7.3).

Phase 7 — Decide/Close or Non-close (bounded)
- If closure criteria are met: produce remediation options + monitoring/detection plan + residual unknowns (owned).
- If not met: produce a non-closure output with explicit close-out requirements and escalation triggers.

Output requirements:
- All required Output Contract tables (Appendix D.4).
- Investigation Plan (recommended) for non-trivial runs.
- Decision Record (required if recommendations are made).
- End with: Residual Unknowns + Next 5 actions + Compliance Self-Check (Pass/Fail).

Output format:
- Markdown headings and tables.
- Tag all material claims and register rows as F/I/A/U.
- Link claims to Evidence IDs where possible.
```

## 5.4 Machine-Navigable Decision Tree (8 nodes)
```
N0 (START) → N1 (SPEED GATE: Rapid vs Investigative?) 
  ├─ Rapid → N2R (§2.3.1) → N3 (Routing) → N4 (Execute Loop)
  ├─ Investigative+Failure → N2I_POST (§2.3.2 Post-Failure) → N3 → N4
  └─ Investigative+Pre-change → N2I_PRE (§2.3.2 Proactive) → N3 → N4

N4 (EXECUTION LOOP) — iterative while stop conditions NOT met:
  ├─ Execute deep: populate core tables, tag F/I/A/U, add tests
  ├─ Execute light: scan-level across remaining groups
  ├─ Check targeted scans? → N5 (§3.2 Triage Matrix & scan chains)
  ├─ Test/probe execution
  ├─ Re-scan Tier 1
  ├─ Quality checks (alternatives, evidence grading, anti-theatre)
  └─ Evaluate stop conditions → N6 (CLOSURE) or N7 (NON-CLOSURE) or loop

N6 (CLOSURE) — all stop conditions met:
  ├─ Apply closure discipline (residual unknowns, acceptability, monitoring, ownership, learning hook)
  ├─ Produce Output Contract artefacts per mode
  ├─ Final quality check (anti-theatre rule)
  └─ END

N7 (NON-CLOSURE) — stop conditions NOT met:
  ├─ Output non-closure with explicit close-out requirements
  ├─ Options: expand coverage → N3, upgrade Light→Full → N4, Tier 3 Hiddens → N3, Rapid→Investigative → N1, invoke targeted scans → N5
  └─ Re-route or re-execute with expanded scope

INVARIANT (active at ALL nodes):
  - §3.1 Tier 1 scan (early + pre-closure)
  - §3.3 Closure discipline (every exit)
  - PD-01–PD-10 (all LLM outputs)
```

---

# Part 6: Glossary (compact)

## 6.1 Framework Definitions (14 new frameworks, v2.0)

| Framework | Operational definition |
|---|---|
| Cognition | Analysis of how cognitive architectures, mental models, attention limits, and reasoning patterns shape perception, decision-making, and blindspots within actors and organisations. |
| Conflict | Mapping of structural incompatibilities, tensions, and explicit/latent disputes between interests, narratives, or actors; includes conflict escalation mechanisms and entrenched positions that hide realities. |
| Coordination | Assessment of how coordination mechanisms (protocols, incentives, information sharing, authority structures) succeed or fail to align actions across distributed agents; diagnoses gaps in synchronisation that hide dependencies. |
| Emergence | Analysis of how system-level properties (patterns, stability, instability, adaptation) arise from interactions between components in ways not predictable from parts alone; reveals hidden properties and cascade potential. |
| Emotions | Examination of how emotional states, group emotional climates, and emotion-based motivation shape perception, memory, risk appetite, and action; includes emotional suppression as a hiding mechanism. |
| Ethics | Framework for identifying ethical blindspots, value misalignments, principle-practice decoupling, and how ethical frameworks shape what actors see as "normal" or "illegitimate"; diagnoses ethical hiding. |
| Implementation | Study of how decisions and designs get translated into operational reality; maps gaps between policy/intent and practice, execution delays, adaptation during execution, and how implementation deviations hide realities. |
| Institutions | Analysis of formal rules, organisations, governance structures, incentive systems, and how institutional inertia, turf protection, and institutional blindspots prevent recognition of change or misalignment. |
| Interests | Mapping of actors' underlying objectives, benefits, stake distributions, and how interests align or conflict; diagnoses strategic suppression, coalition dynamics, and how interest concealment hides motivation. |
| Networks | Study of relationship structures (who connects to whom), information/resource flows, network positions, and how network topology creates information asymmetries, filter bubbles, and positional blindspots. |
| Scenarios | Method for exploring multiple plausible futures and their consequences under deep uncertainty; enables testing of theories, detection of path dependencies, and recognition of hidden assumptions about "what must happen." |
| Space and Place | Analysis of how geography, spatial configuration, location-dependent factors, and place-based meaning shape visibility, access, resources, and perception; reveals place-based blindspots and position-dependent hiddens. |
| Technology | Examination of how technological systems, their design, opacity, brittleness, misalignment with intent, and feedback loops shape behaviour and visibility; includes technology-specific failure modes and hidden dependencies. |
| Trust | Cross-cutting framework identifying how trust/distrust asymmetries, trust breakdowns, and trust-based reliance shape information sharing, collaboration, and how trust dynamics hide realities or enable strategic concealment. |

## 6.2 Operational Glossary (shared terms)

| Term | Definition |
|---|---|
| Bounded closure | Closure allowed only with explicit residual unknowns, ownership, monitoring triggers |
| Coverage without exhaustiveness | Run deep only on minimum group coverage + routed frameworks; run light elsewhere to prevent omission-by-lens |
| Decision record | Log of choice, options, rationale, evidence basis, uncertainties, residual Hiddens, monitoring |
| Depth (Full/Light) | Full Depth = populate core tables, develop mechanisms, expand tests; Light Depth = scan-level, high-signal only |
| Detection interface | Designed method to make a hidden detectable (instrumentation, access, tests, reporting) |
| Evidence Ledger | Claim-to-evidence table: source, quality, dependencies, bias risks |
| Hiddens register | Structured register of suspected/confirmed Hiddens with mechanisms, detectability, consequence, owners, status |
| Information request | Explicit missing input needed to reduce decision-critical Unknowns; includes why and expected discriminator |
| Learning loop | Institutionalised mechanism to retain and act on discoveries; prevents drift and recurrence |
| Minimum group coverage | Minimum set of groups (G1–G6) that must be substantively examined before closure |
| No-Early-Exclusion Rule | Do not exclude lenses early; touch all groups at least Light Depth before prioritisation |
| Non-closure | Required output when closure criteria unmet: what known, what hidden, why hidden, what needed to close |
| Remediation interface | Designed method to reduce or manage a hidden's consequence (decoupling, buffers, governance controls) |
| Residual hiddenness | Remaining uncertainties/hiddens at closure; must include why hidden, impact if surfaced, owners, triggers |
| Routing statement | Explicit record of routing outcomes: which branches triggered, why, resulting coverage and depth plan |
| Run mode | Overall execution posture: Rapid (60–180 min, coverage-first) or Investigative (days–weeks, evidence-gated) |
| Scan-level / MVE | Minimum Viable Execution: smallest execution yielding meaningful signal and Hiddens candidates |
| Stop conditions | Timebox requires output, Evidence supports claims at required confidence, Residual Unknowns explicit/owned/actionable, detection interfaces exist for top hiddens |
| Targeted Hiddens Discovery Scan | Purpose-built cross-framework routing pattern pursuing specific hiding mechanism; optional, supplements Tier 1 |
| Tier 1 (Hiddens) | Six-category visibility audit (Perceptual/Systemic/Informational/Temporal/Relational/Ontological); mandatory early + pre-closure (min twice) |
| Tier 2 (Hiddens) | Structured deepening of top Hiddens: mechanism chain, location, persistence drivers, detection/remediation interfaces |
| Tier 3 (Hiddens) | Full-spectrum Hiddens taxonomy run with stricter evidence/provenance; triggered only by escalation conditions |
| Uncertainty register | Tracks uncertainty type, magnitude, reducibility |

---

## Document Control

| Version | Date | Status | Notes |
|---|---|---|---|
| v1.0 | 2026-04-08 | Release | LLM-only extraction from OG v2.5 (36 frameworks). Expanded: §1.4 full framework table (36 rows), §2.1 routing decision tree pseudocode, §5.1–5.3 full orchestrator prompts (verbatim). Stripped all narrative prose; preserved all operational tables, pseudocode, decision logic, and F/I/A/U discipline. |
| v2.0 | 2026-04-08 | Release | Updated for Operating Guide v3.0 (50 frameworks); integrated 14 new frameworks (Cognition, Conflict, Coordination, Emergence, Emotions, Ethics, Implementation, Institutions, Interests, Networks, Scenarios, Space and Place, Technology, Trust). Updated header (v2.0 designation, compatibility statement); expanded §1.4 Framework-to-Group Mapping from 36 to 50 frameworks in alphabetical order, marking new frameworks with †; updated §1.3 Group-to-Hiddens Linkage with expanded descriptions reflecting new frameworks; updated §2.1 Compact Routing Decision Tree decision nodes (A2, A3, A4, A5, B1, B3) with explicit framework lists at decision points; added §6.1 Framework Definitions section with one-line operational definitions of all 14 new frameworks; renumbered existing glossary as §6.2; updated Document Control section. ~20,000 tokens. |

**Compatibility note:** v2.0 covers 50 frameworks across 6 groups (G1–G6), matching Operating Guide v3.0.
