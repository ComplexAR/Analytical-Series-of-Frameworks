# Analytical Series Operating Guide
**Discovering, Uncovering, and Understanding Hiddens in Complex Scenarios (including post-failure work)**

## Document Information
| Field | Value |
|---|---|
| Document name | Analytical Series Operating Guide |
| Version | v3.0 |
| Date | 2026-04-08 |
| Status | Release |
| Primary purpose | Provide a standardised, protocol-driven method for applying the Analytical Series of Frameworks to discover, uncover, and understand **Hiddens** in complex scenarios, including investigations where failure may have occurred. |
| Intended users | Analysts, investigators, risk owners, programme leaders, auditors/assurers, incident response leads, policy/strategy teams, and facilitators running multi-stakeholder sensemaking. |
| Primary audience | Practitioners using the frameworks (not readers studying them as theory). |
| Scope | How to select, sequence, combine, and govern the 50 frameworks; how to run tiered Hiddens scans; how to produce and manage standard artefacts; how to determine closure with residual hiddenness explicitly recorded. |
| Out of scope | Domain-specific technical methods (e.g., forensics tooling, specialised engineering calculations) except where required to define interfaces and evidence standards. |
| v3.0 changes | Integrates 14 new frameworks (Technology, Institutions, Emergence, Cognition, Networks, Trust, Interests, Emotions, Conflict, Ethics, Coordination, Space and Place, Implementation, Scenarios); updates group-to-hiddens linkage (§2.2) and framework-to-group mapping (§3.2) with 14 new rows; updates routing decision tree (§4.3) with new frameworks at decision nodes; adds glossary section §11.8 with operational definitions of all 14 new frameworks. |
| Dependencies / known couplings | Each framework document follows the Master Rewrite Template; the Framework of Hiddens provides the canonical Tier 1–3 scan and the “visibility-first” integration layer. |

## At-a-Glance: Core Premise Summary
| Question | Answer (operational) |
|---|---|
| What is the series for? | To improve the *quality of seeing* in complex scenarios by systematically discovering **Hiddens** (visibility failures caused by mechanisms) and converting them into **detectable, governable, and remediable** realities. |
| Why group the frameworks? | Grouping provides a coverage model that prevents “single-lens closure” (e.g., only mechanism, only governance, only narrative) and makes Hiddens discovery repeatable. |
| What is the default workflow? | **Frame (G1) → Model (G2/G3/G4) → Control epistemics (G5) → Decide/act (G6)** with a mandatory **Hiddens Tier 1 scan** early and repeatedly. |
| What is the minimum for post-failure work? | Minimum substantive coverage of **G1 + G2 + G5**, plus at least one of **G3 or G4**, and **G6** if recommendations change controls/governance/interventions. |
| When do we escalate to a full Hiddens run? | High consequence, adversarial concealment, persistent disagreement/inconsistent evidence, repeat failure after intervention, or strong cascade/feedback suspicion. |

---

# Introduction

## What is the Analytical Series of Frameworks?

The Analytical Series is a collection of 50 structured analytical frameworks organised into six groups (G1–G6), each providing a distinct lens for examining complex scenarios. The frameworks span framing and scope-setting (G1), structural and causal modelling (G2), agency and behavioural drivers (G3), meaning-making and social order (G4), epistemics and error-control (G5), and action, governance, and learning (G6). Each framework contains a standardised taxonomy of types, dimensions, dynamics, and interfaces, together with a mandatory Hiddens cross-check that connects it to the series' central organising concept: structured visibility failures.

The series exists because complex scenarios — whether failures, high-stakes decisions, organisational crises, systemic risks, or contested change programmes — routinely go wrong not because of bad luck or bad actors alone, but because **important realities are not visible, not legible, not shareable, or not acted upon in time**. These visibility failures are not random. They are produced by identifiable mechanisms: incentive suppression, narrative closure, boundary errors, evidence corruption, temporal drift, positional blindness, and many others. The series calls these **Hiddens** — realities that are hidden from the relevant actors, at the relevant time, by identifiable hiding mechanisms.

The 50 frameworks do not compete with each other. They are complementary lenses, each designed to surface a different family of hiding mechanisms. Using one framework alone risks "single-lens closure" — the false confidence that comes from seeing clearly through one lens while remaining blind through the others. The group system (G1–G6) is a coverage model that prevents this by ensuring every investigation touches all six analytic functions, even if only lightly.

## What is this Operating Guide?

This Operating Guide is the series-level operating doctrine. It does not replace the individual framework documents — each framework has its own taxonomy, dynamics, interfaces, and application protocol. Instead, this guide provides the **orchestration layer** that tells a practitioner or an LLM:

**Which frameworks to use:** The routing decision tree (§4.3) takes scenario features as input — Has a failure occurred? Is evidence contested? Are incentives or power dynamics in play? Are narratives "too clean"? — and produces a minimum group coverage plan with explicit Full Depth and Light Depth allocations.

**In what order:** Three protocols (§5.1 Rapid, §5.2 Post-Failure, §5.3 Proactive) provide phased sequences that move from framing through modelling, agency, meaning, and epistemics to decisions and governance. All three execute within a single iterative loop (§5.0) that enforces repeated Hiddens scanning and evidence-gated closure.

**At what depth:** The guide distinguishes two run modes — Rapid Run Mode (60–180 minutes, coverage-first, stabilisation-oriented) and Investigative Run Mode (days to weeks, selective depth on routed frameworks, evidence-gated) — and two execution depths — Full Depth Framework Execution (populate core tables, develop mechanisms, expand tests) and Light Depth Framework Execution (scan-level, high-signal candidates only). The distinction between run mode and execution depth is a key terminological discipline: a Rapid run can still include targeted depth on a few frameworks, and an Investigative run does not mean running every framework deeply.

**With what quality controls:** The anti-theatre rule (§8.2) requires every major claim to be backed by evidence (or an explicit gap), an uncertainty statement, a hiddenness check, and an owner. The prompt discipline rules (§D.3 PD-01 to PD-10) enforce F/I/A/U tagging on all claims, prevent premature closure, and require residual hiddenness to be made explicit rather than quietly omitted.

**How to close:** Closure is not "we ran out of time" or "we feel done." Closure requires explicit residual unknowns (what remains hidden and why), an acceptability rationale (why proceeding is acceptable given the stakes), a monitoring plan (what signals would change the decision), ownership (who watches and who acts), and a learning hook (when and how the case will be revisited). If these conditions are not met, the output is non-closure with explicit requirements for what would be needed to close.

## How to use this guide to discover and uncover Hiddens

Whether you are a human practitioner or an LLM executing the series, the operating rhythm is the same:

**Start with the scenario, not the frameworks.** The guide is designed to be entered with a case question, a scenario description, available evidence, and constraints (including timebox). It is not a textbook to be read front-to-back; it is a protocol to be executed against a specific situation.

**Select a run mode.** If you have 60–180 minutes and need stabilisation, triage, or next-best-actions, use Rapid Run Mode (§5.1). If you have days to weeks and need explanation, accountability, or recurrence prevention, use Investigative Run Mode (§5.2 for post-failure, §5.3 for proactive). The mode selection gate (§D.9.2) provides the paste-ready prompt for this decision.

**Run the Tier 1 Hiddens scan early.** Before modelling, before agency analysis, before narrative review — run the six-category visibility audit (§7.1). Assume Hiddens exist. This scan is required at least twice: once early and once pre-closure. It is the single most important discipline in the entire series because it forces you to ask "what are we not seeing?" before the analytical momentum of the other frameworks creates false confidence.

**Route, then execute.** Use the routing decision tree (§4.3) to determine which groups and frameworks need Full Depth versus Light Depth attention. Execute the routed frameworks, producing the standard artefacts (Hiddens Register, Evidence Register, Group Coverage Matrix, Hypotheses & Tests Backlog) as you go. Tag every claim F (Fact), I (Interpretation), A (Assumption), or U (Unknown).

**Test, don't narrate.** For every Unknown, produce a probe or test or information request. Prefer discriminating tests (what would we observe if this hypothesis is true versus false?) over narrative elaboration. The anti-theatre rule and PD-05 enforce this discipline.

**Re-scan and iterate.** After execution, re-run the Tier 1 scan with updated knowledge. If new hiddenness classes emerge, update the routing and loop back. If Tier 1 symptoms point to a specific hiding mechanism, invoke the targeted scans (§7.5) to pursue it through its causal chain across 3–5 frameworks.

**Close with explicit residual hiddenness.** When stop conditions are met (§5.0.4), produce closure artefacts per §7.4. When they are not met, produce non-closure with explicit requirements. Never close silently — the residual unknowns are as important a deliverable as the findings.

## For LLM execution

The Operating Guide is designed to be directly executable by an LLM. Appendix D provides the complete LLM execution infrastructure: a standard system instruction block (§D.7), paste-ready orchestrator prompts for each run mode (§D.9.2–D.9.4), prompt discipline rules (§D.3), an output contract specifying required artefacts (§D.4), and a machine-navigable decision tree (§D.11) with 8 nodes, preconditions, actions, outputs, and successor pointers. An LLM given this Operating Guide and a scenario can execute the full investigation workflow — from mode selection through routing, execution, quality controls, and closure — without any external document, producing a disciplined analysis with F/I/A/U tagging, explicit Hiddens, and bounded closure.

For Full Depth Framework Execution (populating a framework's core tables with its specific taxonomy of types, dimensions, dynamics, and interfaces), the individual framework documents should be provided in context alongside this guide. The Operating Guide routes the LLM to the right frameworks; the framework documents provide the analytical content that populates the tables. §D.12.2 provides the detailed executability assessment.

---

# 1. Core Premise and Operating Model

## 1.1 Core Premise (narrative)
Complex scenarios fail not only because “bad things happen”, but because **important realities are not visible, not legible, not shareable, or not acted upon in time**. The Analytical Series is designed to make those visibility failures discoverable by:
- enforcing **explicit framing** (what is in/out, at what scale, over what time),
- modelling **structure and propagation** (how the system works and how failure spreads),
- surfacing **agency and incentives** (who can see, who can act, who benefits from silence),
- identifying **meaning-making and legitimacy dynamics** (how narratives and norms filter signals),
- controlling **epistemics and error** (evidence quality, uncertainty, bias, and failure patterns),
- converting insights into **decisions, interventions, governance, and learning**.

The Framework of **Hiddens** is the series’ canonical “visibility audit layer”. It is used bidirectionally:
- **Forward (constructive):** use other frameworks to identify likely hiding mechanisms; then run Hiddens to test whether important realities may still be invisible.
- **Backward (diagnostic):** use Hiddens to identify hiding mechanisms; then select other frameworks to explain causes, drivers, and interventions.

## 1.2 Assumptions and Preconditions
### Assumptions Register (recommended)
| ID | Assumption | Why it matters | Failure mode if false | Test / probe |
|---|---|---|---|---|
| A1 | The scenario can be bounded enough to work on. | Without boundaries, exploration becomes unfinishable and responsibility is unclear. | Endless scope creep; no closure. | Produce a boundary map; agree exclusions; create a parking lot register. |
| A2 | Evidence and access will be “good enough” for the intended decision stakes. | Stakes determine required scan depth and evidence burden. | False confidence; unjustified closure. | Evidence quality grading; uncertainty register; escalation rules. |
| A3 | Key stakeholders can be engaged (or their absence is explicitly handled). | Many hiddens are relational/positional and require perspective rotation. | One-sided narratives; power-filtered reality. | Stakeholder map; access audit; dissent capture protocol. |
| A4 | Remediation levers are at least partly in scope. | Discovering hiddens without action pathways can still be valuable but must be framed as disclosure/robustness work. | “Findings theatre” and repeated failure. | Intervention feasibility check; governance handoff plan. |

### Preconditions Checklist (recommended)
| Preconditions | Status (Y/N/Partial) | Notes / mitigation if partial |
|---|---:|---|
| Defined case question (what decision or learning will this inform?) |  |  |
| Named owner for the investigation/analysis |  |  |
| Time horizon and timebox agreed (Rapid Run Mode vs deep run) |  |  |
| Access to key data sources (or explicit access gaps recorded) |  |  |
| Ability to run at least Tier 1 Hiddens scan and record residual unknowns |  |  |
| Safe channel for dissent / whistle signals (if needed) |  |  |

## 1.3 Definitions, Scope, and Non-Goals
| Term | Definition (operational) |
|---|---|
| Hidden | A reality-relevant factor that is **not visible/legible/actionable** to the relevant actors at the relevant time **due to identifiable hiding mechanisms** (not merely “unknown”). |
| Complex scenario | A scenario with non-trivial interactions, feedback, delays, multi-scale effects, contested narratives, incomplete evidence, and/or multi-actor strategic behaviour. |
| Failure | A realised outcome (or near miss) where expectations, requirements, safety margins, or objectives were not met; includes process drift and governance breakdowns. |
| Closure | A decision to stop exploring **with residual hiddenness explicitly recorded**, including why it is acceptable (or not) given stakes. |
| Tiered scan | A staged depth model for Hiddens work: Tier 1 (six-category scan), Tier 2 (crosswalk shortlist), Tier 3 (full 30-type run). |

Non-goals:
- This guide does not require “complete knowledge” before action. It requires **explicit residual unknowns** and deliberate treatment (detection, robustness, governance).
- This guide does not mandate one sequencing for all problems. It mandates **minimum coverage and explicit rationale** for deviations.

## 1.4 Position in the Series
This guide is a **series-level operating doctrine**. Individual framework documents provide:
- definitions and taxonomies,
- dynamics and interfaces,
- hiddens source analysis and Hiddens cross-check prompts,
- application protocols and standard deliverables.

This guide provides:
- group-based navigation (G1–G6),
- standard playbooks (post-failure, proactive risk/change, strategy),
- selection logic (what to run deeply vs lightly),
- shared artefact schemas,
- governance rules for repeatability and refinement.

---

# 2. Group System (G1–G6) and What Each Group “Sees”

## 2.1 Group Glossary (longhand + shorthand)
| Group | Longhand label | Shorthand label | Primary analytic function |
|---|---|---|---|
| G1 | Framing & scope-setting | Framing | Establish the “case container”: boundaries, time/scale, context class, and what counts as relevant. |
| G2 | Structure, dependencies & mechanism | Mechanism | Model structure and propagation: systems, relations, processes, resources, causation. |
| G3 | Agency & behavioural drivers | Agency | Identify actors, roles, incentives, power, and responsibility distribution. |
| G4 | Meaning, interpretation & social order | Meaning | Explain how norms, narratives, legitimacy, and communications shape perception and action. |
| G5 | Epistemics & error-control | Epistemics | Control evidence quality, uncertainty, failure patterns, hiddenness, and diagnostic synthesis. |
| G6 | Choice, action & control over time | Action & Control | Convert insight into decisions, interventions, governance, risk treatment, and learning cycles. |

## 2.2 Group-to-Hiddens linkage (operational)
Use this table to anticipate **where hiddenness is likely generated** and what to probe first.

| Group | Typical hiddenness generators (examples) | Common “symptoms” | Default probe |
|---|---|---|---|
| G1 | Wrong boundary, wrong unit of analysis, wrong time horizon, misclassification of situation type, spatial/place-dependent framing | “We’re solving the wrong problem”; repeated surprises at edges; location blindness | Rebuild boundary map; re-run context classification; test scale/time/place assumptions |
| G2 | Hidden interactions, tight coupling, feedback delays, uncontrolled dependencies, observability limits, technology opacity, institutional inertia, network effects, emergence blindness, coordination failures | Cascades, unexplained oscillation, fragile equilibria, system surprises | System map + dependency audit; probe coupling/containment; look for feedback, delay, and emergent properties |
| G3 | Incentive suppression, power-filtered reporting, responsibility diffusion, strategic concealment, cognitive blindness, interest conflicts, emotional suppression, conflict concealment | “Everyone knew but nobody acted”; silence; denial; blame games; motivation misalignment | Incentives/power map; access audit; accountability map; cognitive/emotional/conflict analysis; look for strategic hiding |
| G4 | Narrative closure, legitimacy theatre, norm constraints on speaking, communications bottlenecks, trust breakdown, ethical blindness | Overconfidence; story dominance; ritual compliance; fractured meaning-making | Narrative map; comms pathway audit; legitimacy tests; trust/ethics analysis; dissent capture |
| G5 | Weak evidence, model overreach, untested assumptions, hindsight bias, diagnostic mono-culture | Conflicting accounts; false certainty; repeated investigative failure | Evidence grading; uncertainty register; failure pattern checks; Hiddens scan Tier 1–3 |
| G6 | Control drift, governance gaps, risk appetite mismatch, brittle decisions, learning not institutionalised, implementation failures | Recurrence; “fix” without effect; slow degradation; gap between policy and practice | Decision log + intervention theory; governance map; implementation audit; monitor drift; implement learning loop |

---

# 3. Framework Index by Group (initial assignment for navigation)

## 3.1 Stage definitions (for routing)
| Stage | Meaning |
|---|---|
| Upstream | Establishes the container: classification, scope, resolution, and what is considered relevant. |
| Middle | Builds explanations: structure, actors, meaning, and epistemics to produce defensible understanding. |
| Downstream | Converts understanding into choices, control, and institutional change. |
| Cross-cutting | Applies across stages; typically invoked repeatedly (e.g., Hiddens, Evidence). |

## 3.2 Framework-to-Group mapping (v3.0)
This mapping is for navigation and minimum coverage. It is not a claim of exclusivity. (50 frameworks total; 14 new in v3.0 marked with †)

| Framework | Primary group | Secondary group (optional) | Stage |
|---|---|---|---|
| Boundaries | G1 (Framing) | G2 (Mechanism) | Upstream |
| Dimensions | G1 (Framing) | G5 (Epistemics) | Upstream |
| Realities | G1 (Framing) | G4 (Meaning) | Upstream |
| Scale | G1 (Framing) | G2 (Mechanism) | Upstream |
| Scenarios † | G1 (Framing) | G5 (Epistemics) | Upstream |
| Situations Context Classification | G1 (Framing) | G5 (Epistemics) | Upstream |
| Space and Place † | G1 (Framing) | G4 (Meaning) | Upstream |
| Time | G1 (Framing) | G2 (Mechanism) | Upstream |
| Causation | G2 (Mechanism) | G5 (Epistemics) | Middle |
| Coordination † | G2 (Mechanism) | G3 (Agency) | Middle |
| Emergence † | G2 (Mechanism) | G5 (Epistemics) | Middle |
| Institutions † | G2 (Mechanism) | G4 (Meaning) | Middle |
| Networks † | G2 (Mechanism) | G3 (Agency) | Middle |
| Processes | G2 (Mechanism) | G6 (Action & Control) | Middle |
| Relations | G2 (Mechanism) | G3 (Agency) | Middle |
| Resources | G2 (Mechanism) | G6 (Action & Control) | Middle |
| Systems | G2 (Mechanism) | G5 (Epistemics) | Middle |
| Technology † | G2 (Mechanism) | G6 (Action & Control) | Middle |
| Agents | G3 (Agency) | G2 (Mechanism) | Middle |
| Cognition † | G3 (Agency) | G5 (Epistemics) | Middle |
| Competencies | G3 (Agency) | G2 (Mechanism) | Middle |
| Conflict † | G3 (Agency) | G4 (Meaning) | Middle |
| Emotions † | G3 (Agency) | G5 (Epistemics) | Middle |
| Incentives | G3 (Agency) | G6 (Action & Control) | Middle |
| Interests † | G3 (Agency) | G4 (Meaning) | Middle |
| Personas | G3 (Agency) | G4 (Meaning) | Middle |
| Power | G3 (Agency) | G4 (Meaning) | Middle |
| Responsibility | G3 (Agency) | G6 (Action & Control) | Middle |
| Communications | G4 (Meaning) | G5 (Epistemics) | Middle |
| Culture and Norms | G4 (Meaning) | G3 (Agency) | Middle |
| Ethics † | G4 (Meaning) | G5 (Epistemics) | Middle |
| Legitimacy | G4 (Meaning) | G6 (Action & Control) | Middle |
| Narratives | G4 (Meaning) | G6 (Action & Control) | Middle |
| Perspectives | G4 (Meaning) | G5 (Epistemics) | Middle |
| Trust † | G4 (Meaning) | G5 (Epistemics) | Cross-cutting |
| Values | G4 (Meaning) | G6 (Action & Control) | Middle |
| Beliefs | G5 (Epistemics) | G4 (Meaning) | Middle |
| Diagnosis | G5 (Epistemics) | G2 (Mechanism) | Middle |
| Evidence | G5 (Epistemics) |  | Cross-cutting |
| Failures | G5 (Epistemics) | G2 (Mechanism) | Cross-cutting |
| Hiddens | G5 (Epistemics) |  | Cross-cutting |
| Knowledge | G5 (Epistemics) | G4 (Meaning) | Cross-cutting |
| Metrics | G5 (Epistemics) | G6 (Action & Control) | Cross-cutting |
| Uncertainties | G5 (Epistemics) |  | Cross-cutting |
| Decisions | G6 (Action & Control) | G5 (Epistemics) | Downstream |
| Governance | G6 (Action & Control) | G3 (Agency) | Downstream |
| Implementation † | G6 (Action & Control) | G2 (Mechanism) | Downstream |
| Interventions | G6 (Action & Control) | G2 (Mechanism) | Downstream |
| Learning and Adaptation | G6 (Action & Control) | G5 (Epistemics) | Downstream |
| Risk | G6 (Action & Control) | G5 (Epistemics) | Downstream |

---

# 4. Selection and Sequencing Logic (table-first)

## 4.1 Use-case routing table
| Use case | Default objective | Minimum framework coverage | Typical timebox | Default escalation triggers |
|---|---|---|---:|---|
| Post-failure investigation (full) | Explain what happened, why it was not seen/acted on, and what prevents recurrence | G1+G2+G5 mandatory; add G3 or G4; include G6 for control/governance changes | Days–weeks | High consequence; strategic concealment; inconsistent evidence; repeat failure; cascade suspicion |
| Post-failure Rapid Run Mode (rapid) | Stabilise understanding and prioritise next tests/containment | Tier 1 Hiddens + boundary + system sketch + evidence gaps + immediate risk | 60–180 min | If Rapid Run Mode cannot explain key discontinuities or stakes are high |
| Pre-change risk review | Identify hidden interactions and governance gaps before intervention | G1+G2+G5 + G6 | Hours–days | Tight coupling; unknown dependencies; novelty; high stakes |
| Strategy / policy / transformation | Build a defensible theory of change under uncertainty | G1+G2+G3+G4+G5 + G6 | Days–months | Stakeholder contestation; metric disputes; feasibility constraints; contradictory evidence |

## 4.2 Depth selection (run deeply vs lightly)
| Decision | Guidance |
|---|---|
| Which frameworks to run deeply? | Run deeply where (a) consequence is high, (b) evidence is weak/contested, (c) incentives/power may distort reporting, or (d) the system shows coupling/cascade potential. |
| Which to run lightly? | Run lightly where stakes are low, mechanisms are stable/known, and the Hiddens scan suggests low hiddenness and low consequence. Record rationale. |
| What is “good enough”? | “Good enough” is defined by **decision stakes**, not by curiosity. Closure requires explicit residual unknowns, detection interfaces, and governance handoff where needed. |

---



## 4.3 Compact routing decision tree (scenario features → minimum group coverage + deep/light)

This decision tree is an **operational routing aid**. It complements the routing tables above by converting a scenario’s observable features into:
- **minimum group coverage** (G1–G6) required before closure, and
- a default **deep vs light** framework selection plan.

**Rules of use**
- Use this tree at **Start-of-Run** and **Pre-Closure**.
- When in doubt, bias toward **more coverage** and record why.
- The tree routes **analysis effort**, not “truth”. All conclusions remain subject to the canonical Prompt Discipline Rules.

### 4.3.1 Decision tree (compact)
```text
START
├─ A. Has a materially consequential failure (or near-miss) occurred?
│   ├─ YES → Minimum groups: G1 + G2 + G5 (DEEP)  [post-failure baseline]
│   │   ├─ A1. Is evidence weak, contradictory, or contested?
│   │   │   ├─ YES → Deepen: Evidence + Uncertainties + Diagnosis (+ Failures); tighten provenance; expand tests.
│   │   │   └─ NO  → Maintain baseline; proceed to A2–A6 as applicable.
│   │   ├─ A2. Is coupling/cascade/propagation suspected (multiple interacting causes or cascading impacts)?
│   │   │   ├─ YES → Deepen: Systems + Relations + Processes + Technology + Networks + Emergence + Coordination (+ Risk); perform coupling/containment checks.
│   │   │   └─ NO  → Light scan G2 beyond baseline (confirm no hidden coupling).
│   │   ├─ A3. Are incentives, power, responsibility, or strategic concealment plausible?
│   │   │   ├─ YES → Add group: G3 (DEEP)  [Agents, Cognition, Conflict, Competencies, Emotions, Incentives, Interests, Personas, Power, Responsibility]
│   │   │   └─ NO  → Light scan G3 (document rationale).
│   │   ├─ A4. Are narratives/legitimacy/communications materially contested or “too clean”?
│   │   │   ├─ YES → Add group: G4 (DEEP)  [Communications, Culture and Norms, Ethics, Legitimacy, Narratives, Perspectives, Trust, Values]
│   │   │   └─ NO  → Light scan G4 (document rationale).
│   │   ├─ A5. Will recommendations change controls, governance, or operating model?
│   │   │   ├─ YES → Add group: G6 (DEEP)  [Decisions, Governance, Implementation, Interventions, Learning & Adaptation, Risk]
│   │   │   └─ NO  → Light scan G6 (ensure residual unknowns are governable).
│   │   └─ A6. Is adversarial intent or intentional concealment plausible?
│   │       ├─ YES → Expand to full G1–G6 (DEEP on G3+G4); escalate Hiddens to Tier 3; apply stricter evidence rules.
│   │       └─ NO  → Proceed with groups selected above.
│   └─ NO → Proceed to B (pre-failure / pre-change / ambiguous)
└─ B. No failure, but a high-stakes decision or change is pending?
    ├─ YES → Minimum groups: G1 + G2 + G5 + G6 (DEEP)  [pre-change baseline]
    │   ├─ B1. Multi-stakeholder conflict or contested incentives?
    │   │   ├─ YES → Add G3 (DEEP); include Emotions, Interests, Conflict, Cognition; otherwise G3 light scan.
    │   ├─ B2. Narrative/legitimacy disputes or communication fragility?
    │   │   ├─ YES → Add G4 (DEEP); otherwise G4 light scan.
    │   └─ B3. High novelty / unknown dependencies / tight time constraints?
    │       ├─ YES → Deepen G2 (Systems/Processes/Relations/Emergence/Scenarios) and strengthen G5 (Uncertainties/Evidence); increase tests.
    └─ NO → Low-stakes / exploratory: run G1 + G5 light + one domain-relevant group deep; record limits.
```

### 4.3.2 Decision tree output contract (what the LLM must produce)
| Output | Required content |
|---|---|
| Routing statement | Which branch nodes were triggered (A1–A6 / B1–B3) and why |
| Minimum group coverage | Explicit set of groups required for this run before closure |
| Full Depth Framework Execution list | Explicit list of frameworks to run deeply (with rationale) |
| Light Depth Framework Execution list | Explicit list of frameworks to scan lightly (with rationale) |
| Escalation triggers | Conditions that would force expansion to additional groups or Tier 3 Hiddens |

### 4.3.3 Default deep vs light mapping (starter)
| Scenario routing result | Deep (run fully) | Light (scan-level) |
|---|---|---|
| Post-failure baseline | Boundaries/Space and Place/Time/Scale/Situations; Systems/Causation/Coordination/Emergence/Networks/Relations/Processes/Technology; Evidence/Failures/Uncertainties/Diagnosis/Hiddens | Remaining frameworks not selected by A3–A6 |
| Pre-change baseline | Boundaries/Dimensions/Realities/Scenarios/Space and Place/Situations; Coordination/Emergence/Networks/Processes/Relations/Resources/Systems/Technology; Evidence/Uncertainties/Hiddens; Decisions/Governance/Implementation/Interventions/Risk | Remaining frameworks not selected by B1–B3 |
| Full-spectrum (adversarial concealment) | Full G1–G6 including all 50 frameworks; deep G3+G4 (Conflict, Cognition, Emotions, Interests + Ethics, Trust); Tier 3 Hiddens | None (only if timeboxed; otherwise full) |


# 5. Standard Protocols (protocol-driven)


## 5.0 Iterative investigation loop (algorithmic control)

This section defines the **single repeatable loop** used across all run modes. It prevents premature narrative closure by enforcing:
- register-first execution,
- repeated Tier 1 Hiddens scanning (early + pre-closure),
- evidence-gated confidence,
- explicit residual unknowns when bounded closure is necessary.

### 5.0.1 The loop (overview)
| Loop phase | Objective | Mandatory artefacts updated | Primary “gate” question |
|---|---|---|---|
| Initialise | Establish the case question, boundaries, timebox, and discipline | Group Coverage Matrix; Evidence Ledger (empty baseline); Hiddens Register (empty baseline) | Do we have a coherent question and boundary? |
| Generate | Produce initial candidate Hiddens and hypotheses | Tier 1 Hiddens scan; Hypothesis/Test Backlog | What could be hidden given the situation type? |
| Route | Select minimum group coverage and Full Depth Framework Execution / Light Depth Framework Execution plan | Routing statement + Full Depth Framework Execution / Light Depth Framework Execution plan | What must be examined before closure? |
| Execute | Run selected frameworks (deep) and scan remaining (light) | Framework tables; all registers | What did we learn and what remains unknown? |
| Test | Convert Unknowns into probes/tests and request artefacts | Hypothesis/Test Backlog; Evidence Ledger | What would disconfirm our current story? |
| Re-scan | Re-run Tier 1 Hiddens scan with updated knowledge | Tier 1 scan (second pass); updated Hiddens Register | Are we still missing a class of hiddenness? |
| Decide | Close (bounded) or escalate (expand coverage / Tier 3) | Closure statement; Residual Unknowns; Escalation recommendation | Are closure criteria met for the decision at hand? |

### 5.0.2 Pseudocode (LLM-executable)
```text
1) Create baseline artefacts: Coverage(G1–G6), Evidence Ledger, Hiddens Register, Hypothesis/Test Backlog.
2) Run Tier 1 Hiddens scan (assume hiddens exist) → generate initial candidate hiddens + hypotheses.
3) Route using Section 4.3 decision tree → set minimum group coverage + Full Depth Framework Execution / Light Depth Framework Execution plan.
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
     - If not met: produce non-closure output with explicit requirements to close, or escalate to Tier 3 Hiddens/full G1–G6.
```

### 5.0.3 Iteration triggers (when to loop again)
| Trigger | Meaning | Required response |
|---|---|---|
| Contradictory evidence | Competing accounts or data conflict | Preserve disagreement; propose disambiguation tests; update Evidence Ledger |
| “Too clean” story | Single-cause narrative without tests | Add disconfirming hypotheses; strengthen G5; re-scan Tier 1 |
| High-impact Unknown | A residual unknown could change decisions/accountability | Escalate coverage (add groups) or elevate to Tier 3 Hiddens |
| New artefacts arrive | Logs, interviews, metrics, policies provided | Re-run Execute → Test → Re-scan phases |
| Governance implications | Recommendations alter controls or accountability | Add/strengthen G6 and ensure Decision Record includes residual unknowns |

### 5.0.4 Stop conditions (bounded closure)
Bounded closure is permitted only when:
- the **decision timebox** requires an output, and
- the **Evidence Ledger** supports key claims at the required confidence level, and
- **Residual Unknowns** are explicit, prioritised, and assigned owners/actions, and
- the remediation plan includes **detection interfaces** for the top residual hiddens.

If these conditions are not met, output must be **non-closure** with explicit close-out requirements.


## 5.1 Rapid Rapid Run Mode Protocol (60–180 minutes)
| Step | Objective | Primary groups | Minimum artefacts | Gate / decision |
|---:|---|---|---|---|
| 1 | Establish the case question and timebox | G1 | Case statement | Proceed / stop |
| 2 | Run Tier 1 Hiddens scan (assume hiddens exist) | G5 | Tier 1 scan table + shortlist | Escalate? |
| 3 | Sketch boundaries, time horizon, and scale | G1 | Boundary map + time/scale note | Re-scope? |
| 4 | Sketch system structure and dependencies | G2 | System sketch + dependency list | Containment needed? |
| 5 | Capture evidence quality and key gaps | G5 | Evidence register + uncertainty register | Escalate? |
| 6 | Identify immediate risks and stabilisation actions | G6 | Risk shortlist + immediate actions | Hand off / continue deep run |
| 7 | Decide investigation depth and plan | G6 | Investigation plan + owners | Commit / pause |

## 5.2 Post-Failure Hidden Discovery Protocol (full)
| Phase | Step | Objective | Primary groups | Key frameworks (typical) | Standard outputs |
|---|---:|---|---|---|---|
| Frame | 1 | Classify situation; set boundaries, time/scale, and objectives | G1 | Situations, Boundaries, Time, Scale, Dimensions, Realities | Case statement; boundary map; scope decisions |
| Frame | 2 | Run Tier 1 Hiddens scan and identify “likely hiding mechanisms” | G5 | Hiddens | Tier 1 scan; initial hidden shortlist |
| Model | 3 | Build system/relations/process maps and dependency audits | G2 | Systems, Relations, Processes, Resources | System map; dependency register; coupling notes |
| Model | 4 | Build causal hypotheses and alternative mechanisms | G2/G5 | Causation, Failures | Hypothesis set; alternative explanations |
| Agency | 5 | Map actors, incentives, power, responsibility distribution | G3 | Agents, Incentives, Power, Responsibility, Personas | Stakeholder map; incentives/power map; accountability map |
| Meaning | 6 | Map narratives, comms pathways, norms, legitimacy dynamics | G4 | Narratives, Communications, Culture & Norms, Legitimacy, Perspectives, Values | Narrative map; comms audit; legitimacy tests |
| Epistemics | 7 | Grade evidence, record uncertainties, identify investigation failure risks | G5 | Evidence, Uncertainties, Failures | Evidence register; uncertainty register; bias/failure checks |
| Synthesis | 8 | Produce a diagnosis with explicit residual hiddenness | G5 | Diagnosis + Hiddens | Diagnosis statement; residual unknowns; confidence rating |
| Convert | 9 | Translate into decisions, interventions, governance and risk controls | G6 | Decisions, Interventions, Governance, Risk, Learning & Adaptation | Decision record; intervention portfolio; governance changes; KRIs |
| Assure | 10 | Define detection/remediation interfaces for high-consequence hiddens | G5/G6 | Hiddens + Risk + Governance | Detection plan; remediation plan; monitoring cadence |
| Learn | 11 | Install learning loop and prevent drift | G6 | Learning & Adaptation | Learning plan; after-action cadence; drift indicators |

## 5.3 Proactive “Hidden Exposure” Protocol (pre-change / high-stakes)
| Step | Objective | Primary groups | Outputs |
|---:|---|---|---|
| 1 | Define change intent and success/constraint assumptions | G1/G6 | Change statement; assumptions register |
| 2 | Run Tier 1 Hiddens scan focused on change-induced hiding mechanisms | G5 | Tier 1 scan + shortlist |
| 3 | Model dependency and coupling impacts | G2 | Dependency audit; containment design |
| 4 | Run incentives/power and comms integrity checks | G3/G4 | Incentive distortion risks; comms pathway safeguards |
| 5 | Define monitoring, buffers, and escalation rules | G6 | KRIs; triggers; rollback/containment plan |
| 6 | Confirm governance and ownership | G6 | Decision rights; review cadence |

---

# 6. Standard Artefacts Library (schemas and minimum fields)

## 6.1 Artefact index
| Artefact | Primary purpose | Owner (default) | Produced in | Used by |
|---|---|---|---|---|
| Case statement | Define the question, stakes, scope, and timebox | Case owner | G1 | All |
| Boundary map | Make scope explicit; prevent drift | Facilitator/analyst | G1 | All |
| System map | Show components, interfaces, flows, dependencies | Systems analyst | G2 | Risk/Diagnosis/Interventions |
| Dependency register | Identify upstream/downstream coupling and common-mode risks | Systems analyst | G2 | Risk/Governance |
| Stakeholder map | Identify perspectives, access, and positional visibility | Investigator | G3/G4 | Hiddens/Comms/Governance |
| Evidence register | Track claims, sources, quality, and gaps | Investigator | G5 | Diagnosis/Risk |
| Uncertainty register | Track uncertainty type, magnitude, and reducibility | Investigator | G5 | Diagnosis/Decisions |
| Hiddens register | Track suspected/confirmed hiddens and hiding mechanisms | Investigator | G5 | All |
| Diagnosis statement | Explain best current theory; include residual unknowns | Lead analyst | G5 | Decisions/Interventions |
| Decision record | Log choices, rationale, trade-offs, and confidence | Decision owner | G6 | Governance/Learning |
| Intervention portfolio | Set of actions with theories of change and monitoring | Programme lead | G6 | Governance/Risk |
| Governance map | Decision rights, oversight, escalation, assurance cadence | Governance owner | G6 | Risk/Learning |

## 6.2 Minimum field schemas (recommended)
### Hiddens Register (minimum)
| Field | Description |
|---|---|
| Hidden ID | Local identifier |
| Description | What is hidden (in plain language) |
| Meta-category (I–VI) | Perceptual/Systemic/Informational/Temporal/Relational/Ontological |
| Hiding mechanism | How it stays hidden (channel, incentive, coupling, latency, etc.) |
| Consequence | Impact if true / if unaddressed |
| Detectability | How it could be detected (signals, tests, data access) |
| Reducibility | Can it be reduced/removed, or only managed/robustified? |
| Owners | Who can act on detection/remediation |
| Status | Suspected / Investigating / Confirmed / Managed / Closed (with rationale) |
| Residual risk | What remains even if addressed |

### Evidence Register (minimum)
| Field | Description |
|---|---|
| Claim | What is being asserted |
| Source | Where it comes from |
| Type | Data, testimony, document, observation, model output |
| Quality rating | High/Medium/Low with rationale |
| Bias risks | Incentive/power/narrative distortion risks |
| Dependencies | What assumptions it depends on |
| Tests | How to corroborate or falsify |

---

# 7. Hiddens Integration Discipline (invariant)

## 7.1 Tier 1 Hiddens Six-Category Scan (required early and repeated)
| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|
| I Perceptual | Attention/observation limits are universal | Missed obvious signals; selective noticing | Fresh-eyes review; workload/attention audit; “what are we not looking at?” |
| II Systemic | Methods/models exclude realities | Frame disputes; metric/proxy distortions | Reframe exercise; proxy review; calibration/validity checks |
| III Informational | Channels are structured and political | Silence, noise, fragmentation | Channel audit; access audit; integration review; timeliness check |
| IV Temporal | History embeds constraints and blinders | Legacy effects; slow drift | Historical reconstruction; assumption dating; scenario stress tests |
| V Relational | Position determines visibility | Stakeholder blindspots | Perspective rotation; multi-level analysis; network mapping |
| VI Ontological | Category absence/predictability limits | Anomalies without language | Anomaly log; “new category” proposals; robustness-by-design |

## 7.2 Embedded Hiddens Micro-Protocol (standard prompts)
1) Run the Tier 1 scan across all six Hiddens meta-categories (assume hiddens exist).  
2) For shortlisted hiddens, rate **mechanism, reducibility, detectability, agency, and consequence**.  
3) Assign at least one **detection** and one **remediation** interface per high-consequence hidden; map interaction chains.  
4) Run a hiddens source analysis and record unresolved unknowns.

## 7.3 Escalation Rule (Tier 3 – full Hiddens run)
Escalate to a full scan (including a full type-level run and detection/remediation matrix) if any apply:
- High consequence (safety, regulatory, existential, severe harm potential)
- Adversarial context / strategic concealment likely
- Persistent disagreement or inconsistent evidence
- Repeat failures despite prior interventions
- Strong suspicion of cascades/reinforcement across hidden types

## 7.4 Closure discipline (recorded residual hiddenness)
| Closure item | Required content |
|---|---|
| Residual unknowns list | What remains uncertain/hidden and why |
| Acceptability rationale | Why proceeding is acceptable given stakes (or why it is not) |
| Monitoring plan | What signals would change the decision/diagnosis |
| Ownership | Who watches, who acts, and escalation pathways |
| Learning hook | When and how the case will be revisited |

---


## 7.5 Targeted Hiddens Discovery Scans (optional diagnostic layer)

## 7.5.1 Purpose and Relationship to Existing Infrastructure

### Narrative introduction

The Analytical Series already provides robust general-purpose machinery for discovering Hiddens: the Tier 1 Six-Category Scan sweeps across all hiding mechanism families, the Micro-Protocol profiles and remediates what is found, and the Tier 3 escalation rule deepens the search when stakes demand it. These tools work well as a detection **net** — they ensure nothing is skipped.

But experienced investigators know that hiding mechanisms are not random. They follow patterns: power structures suppress inconvenient signals along predictable pathways; gradual drift exploits the gap between governance tempo and operational change; dominant narratives crowd out disconfirming evidence through identifiable social dynamics. When an analyst recognises the *signature* of a specific hiding mechanism, they need a more focused tool — one that pursues that mechanism through its causal chain rather than sweeping broadly.

This section provides that tool: thirteen **Targeted Hiddens Discovery Scans**, each designed to follow a specific hiding mechanism through the frameworks most relevant to how that mechanism operates. If the Tier 1 scan is a net and the Tier 3 escalation is a deep dive, a Targeted Scan is a **spear** — a focused pursuit guided by mechanism knowledge.

The section is structured for two audiences. The **narrative introductions** and scan definitions serve human analysts who need to understand the rationale, judge applicability, and exercise professional discretion. The **LLM Execution Adapter** (§7.5.8) provides the mechanical precision — pseudocode, gate questions, minimum output tables, and F/I/A/U tagging — that allows an LLM to execute any scan reliably and produce outputs consistent with Appendix D's prompt discipline rules.

### What this section adds

The Tier 1 Six-Category Scan (§7.1) and Embedded Hiddens Micro-Protocol (§7.2) provide a **general-purpose detection net**: they sweep across all six Hiddens meta-categories and flag candidate hiddens for dimensional profiling, detection, and remediation. The three standard protocols (§5.1–5.3) embed these scans at phase gates within broader investigative sequences. The Group-to-Hiddens Linkage Table (§2.2) identifies what each group typically generates.

This section adds a **targeted diagnostic layer**: thirteen purpose-built cross-framework routing patterns, each designed to pursue a specific **hiding mechanism** through the frameworks most relevant to that mechanism, in a sequence that follows how the mechanism actually operates.

### When to use
Targeted Hiddens Discovery Scans are **optional** and are invoked when:
- The Tier 1 scan produces symptoms that point toward a specific hiding mechanism (use the Triage Matrix at §7.5.3), or
- Scenario features or stakeholder accounts suggest a particular pattern of hiddenness (e.g., "everyone knew but nobody spoke up" → Suppression Scan), or
- A prior investigation or post-mortem identified a hiding mechanism class that recurred and was not caught by general-purpose scanning, or
- The analyst's professional judgement identifies a plausible hiding pathway that warrants targeted pursuit.

### When NOT to use
- As a substitute for the mandatory Tier 1 scan (§7.1). Targeted scans supplement; they do not replace.
- As a substitute for minimum group coverage (§4.1–4.3). The routing decision tree governs what must be covered; targeted scans govern how specific hiding mechanisms are pursued within that coverage.
- When time constraints prevent adequate execution. A poorly executed targeted scan can create false confidence. If the timebox is tight, record the scan as a recommended follow-up rather than running it superficially.

### Relationship to existing sections
| Existing section | Relationship to §7.5 |
|---|---|
| §7.1 Tier 1 Six-Category Scan | Tier 1 is the **trigger source**: its symptoms and shortlist feed into the Triage Matrix (§7.5.3) to select which targeted scan(s) to invoke. |
| §7.2 Embedded Hiddens Micro-Protocol | Each targeted scan **terminates** with the Micro-Protocol: shortlisted hiddens are dimensionally profiled, assigned detection/remediation interfaces, and entered into the Hiddens Register. |
| §7.3 Escalation Rule (Tier 3) | A targeted scan may **produce** escalation triggers (e.g., discovering adversarial concealment during a Suppression Scan). Standard Tier 3 escalation rules apply. |
| §7.4 Closure discipline | Targeted scan outputs feed into closure artefacts: residual unknowns, monitoring plans, and ownership assignments. |
| §5.0 Iterative investigation loop | Targeted scans fit within the Execute phase of the loop. They may also trigger Re-scan if findings alter the routing statement. |
| §5.1–5.3 Standard protocols | Targeted scans can be invoked at any phase gate where Tier 1 symptoms point to a specific mechanism. They are most commonly invoked during the Model, Agency, Meaning, or Epistemics phases. |
| §2.2 Group-to-Hiddens linkage | The linkage table identifies hiddenness generators per group. Targeted scans **chain** across groups to follow a hiding mechanism's full causal pathway. |
| §4.3 Compact routing decision tree | The routing tree determines minimum coverage. Targeted scans operate **within** that coverage to intensify pursuit of specific mechanisms. A targeted scan finding may expand minimum coverage (e.g., a Suppression Scan finding may trigger A3 → add G3 DEEP). |
| Appendix D — LLM Execution Mode | The LLM Execution Adapter (§7.5.8) is designed to comply with all Appendix D prompt discipline rules, including F/I/A/U tagging (PD-02), evidence provenance (PD-04), and non-premature closure (PD-08). |

---

## 7.5.2 Scan Catalogue (thirteen targeted scans)

### Narrative introduction

The thirteen scans are organised into four families based on the primary domain of the hiding mechanism they target. This grouping is for navigation only — many scans cross domains, and the Scan Interaction Map (§7.5.5) shows where mechanisms compound.

**Family A — Social and organisational hiding (Scans 1, 5, 8, 11):** These scans target mechanisms where human agency, social structures, or belief systems actively or passively prevent information from reaching those who need it. The hiding is sustained by power, incentives, norms, legitimacy dynamics, or cognitive/identity structures.

**Family B — Structural and systemic hiding (Scans 3, 6, 9, 12):** These scans target mechanisms where the analytical frame, system architecture, measurement regime, or capability distribution makes certain realities invisible. The hiding is not driven by anyone's intent but by how the system is structured.

**Family C — Temporal hiding (Scans 2, 7):** These scans target mechanisms where time itself is the hiding agent — gradual change that falls below detection thresholds, or institutional memory that decays faster than problems recur.

**Family D — Action-induced hiding (Scans 10, 13):** These scans target mechanisms where omission (failure to exercise duties) or action (the intervention itself) creates or sustains hiddenness.

Each scan definition provides:
- **Investigative question** — the specific question the scan pursues
- **Target mechanism** — the hiding mechanism class it is designed to detect
- **Route** — the ordered framework sequence, with the primary group(s) each framework belongs to
- **At each step** — the specific analytical action and what it contributes to the chain
- **Typical entry symptoms** — Tier 1 findings or scenario features that suggest invoking this scan
- **Primary Hiddens meta-categories addressed** — which of the six Hiddens meta-categories (I–VI) the scan is most likely to surface
- **Standard output** — what the scan produces before handoff to the §7.2 Micro-Protocol

For LLM execution, each scan also has a corresponding entry in the LLM Execution Adapter (§7.5.8) providing pseudocode, gate questions, minimum output tables, and depth triggers.

---

### Scan 1: Suppression Scan
**Family:** A — Social and organisational hiding

**Investigative question:** Who benefits from silence, and what systems enforce it?

**Target mechanism:** Deliberate or structurally incentivised concealment — things hidden because actors with power or aligned incentives actively or passively prevent disclosure.

**Route:** Power (G3) → Incentives (G3) → Culture & Norms (G4) → Communications (G4) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Power | Map who can shape what is visible; identify gatekeepers, agenda-setters, and information controllers. | Identifies **who** has the capacity to suppress. |
| 2 | Incentives | For each power-holder, map what they gain from non-disclosure and what they lose from transparency. | Identifies **why** suppression is motivated — the payoff structure. |
| 3 | Culture & Norms | Identify norms that make speaking up costly, taboo topics, euphemisms, and silence spirals. | Identifies the **social enforcement** that sustains suppression beyond individual actors. |
| 4 | Communications | Map the channels through which signals travel; identify bottlenecks, filters, and dead zones. | Identifies **where** suppressed information is blocked, delayed, or degraded in transit. |
| 5 | Hiddens | Classify the resulting hiddens by type; profile dimensionally; assign detection and remediation. | Produces the **Hiddens Register entries** with mechanism, consequence, and action plan. |

**Typical entry symptoms:** Silence where there should be signal; "everyone knew but nobody said anything"; speaking-up incidents followed by retaliation or marginalisation; reporting lines that bypass key stakeholders; information asymmetry between levels; Tier 1 scan flags on meta-categories III (Informational) and V (Relational).

**Primary Hiddens meta-categories addressed:** III (Informational), V (Relational), I (Perceptual — attention shaped by power).

**Standard output:** Suppression map (who suppresses what, through which mechanisms, with what enforcement); candidate hiddens shortlist with mechanism tags; handoff to §7.2 Micro-Protocol.

---

### Scan 2: Drift Scan
**Family:** C — Temporal hiding

**Investigative question:** What has changed so slowly that nobody noticed?

**Target mechanism:** Gradual normalised deviation — things hidden not by anyone's intent but by incremental change that falls below detection thresholds at every step.

**Route:** Time (G1) → Processes (G2) → Governance (G6) → Failures (G5) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Time | Reconstruct temporal baselines; identify slow-moving changes, accumulating deviations, and latency between cause and visible effect. | Identifies **what** has drifted and over **what period**. |
| 2 | Processes | Compare current operational practice against design intent; identify workarounds, exception-as-norm patterns, and deferred maintenance. | Identifies **where** drift has materialised in lived practice. |
| 3 | Governance | Check whether oversight cadences, metrics, and review cycles are fast enough to detect the drift; test for paper–practice decoupling. | Identifies **why** drift was not caught — governance tempo mismatch. |
| 4 | Failures | Classify the failure patterns that drift has produced or is producing; check for systematic recurrence. | Identifies the **consequences** of drift and whether it has already caused harm. |
| 5 | Hiddens | Classify the resulting hiddens; profile dimensionally; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** "It used to work but we're not sure when it stopped"; slow degradation in performance metrics; exceptions and workarounds treated as normal; deferred maintenance backlogs; audit findings that recur across cycles; Tier 1 scan flags on meta-category IV (Temporal).

**Primary Hiddens meta-categories addressed:** IV (Temporal), II (Systemic — methods/models that don't track drift), I (Perceptual — habituation to degraded conditions).

**Standard output:** Drift register (what drifted, from what baseline, over what period, with what governance gap); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 3: Positional Blindness Scan
**Family:** B — Structural and systemic hiding

**Investigative question:** What can't be seen from where we're standing?

**Target mechanism:** Structural invisibility caused by vantage point — things hidden because the dominant analytical perspective, boundary definition, or scale of observation excludes them.

**Route:** Perspectives (G4) → Boundaries (G1) → Scale (G1) → Dimensions (G1) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Perspectives | Inventory whose view dominates the analysis; identify excluded, marginalised, or under-represented vantage points. | Identifies **who** is looking and whose view is missing. |
| 2 | Boundaries | Check whether the system boundary excludes relevant realities; test for boundary artefacts (problems that exist at the boundary but are invisible from inside). | Identifies **what** the boundary definition cuts off. |
| 3 | Scale | Test whether the chosen level of analysis (micro/meso/macro) misses phenomena that exist at other levels; check for cross-scale effects. | Identifies **what scale** of reality is invisible from the current resolution. |
| 4 | Dimensions | Check for missing analytical axes — dimensions of variation that are not being tracked or measured at all. | Identifies **which categories of difference** are absent from the analysis. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Repeated surprises from "outside" the established frame; stakeholders who describe a fundamentally different reality; cross-boundary disputes; scale-dependent disagreements (e.g., local vs. system-level views contradict); Tier 1 scan flags on meta-categories V (Relational) and VI (Ontological).

**Primary Hiddens meta-categories addressed:** V (Relational), VI (Ontological), II (Systemic — frame/model exclusions).

**Standard output:** Positional blindness map (which perspectives dominate, what boundaries exclude, what scales miss, what dimensions are absent); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 4: Evidence Corruption Scan
**Family:** A — Social and organisational hiding

**Investigative question:** Can we trust what we think we know?

**Target mechanism:** Contamination of the evidence base — things hidden because evidence has been filtered, echoed, distorted, gamed, or fabricated, producing false confidence.

**Route:** Evidence (G5) → Incentives (G3) → Communications (G4) → Narratives (G4) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Evidence | Audit source quality, independence, and defeaters; test for echo (non-independent evidence circulating as if independent) and survivorship bias (missing disconfirming evidence). | Identifies **what** may be wrong with the evidence base. |
| 2 | Incentives | Check whether reporting actors have reason to distort, omit, or fabricate; identify gaming, Goodhart effects, and metric manipulation. | Identifies **why** evidence may be corrupted — the motivational gradient. |
| 3 | Communications | Map where evidence is filtered, aggregated, translated, or delayed in transmission; identify bottlenecks that lose fidelity. | Identifies **where** corruption enters the evidence chain. |
| 4 | Narratives | Examine whether a dominant story is selecting which evidence gets attention and which is sidelined or discredited. | Identifies the **interpretive filter** that amplifies some evidence and suppresses other. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Evidence that is "too clean" or too perfectly aligned with the dominant narrative; conflicting accounts from different sources or levels; metrics that show improvement while outcomes worsen; single-source dependence for key claims; Tier 1 scan flags on meta-categories III (Informational) and II (Systemic).

**Primary Hiddens meta-categories addressed:** III (Informational), II (Systemic — method/model distortion), I (Perceptual — selective attention shaped by narrative).

**Standard output:** Evidence integrity assessment (which evidence is non-independent, incentive-distorted, narrative-filtered, or channel-degraded); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 5: Legitimacy Theatre Scan
**Family:** A — Social and organisational hiding

**Investigative question:** Where is compliance performative, and what does the performance conceal?

**Target mechanism:** Paper–practice decoupling — things hidden behind formal systems that look healthy while lived practice has diverged, creating a false sense of assurance.

**Route:** Legitimacy (G4) → Governance (G6) → Culture & Norms (G4) → Responsibility (G3) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Legitimacy | Check whether authority claims and compliance assertions are substantively justified or ritualistic; identify legitimacy scripts and legitimacy borrowing. | Identifies **where** legitimacy is performative rather than substantive. |
| 2 | Governance | Map paper governance against lived governance; identify decoupling (policies that exist but are not followed), shadow governance, and metric theatre. | Identifies the **structural gap** between what is documented and what actually happens. |
| 3 | Culture & Norms | Identify where "looking compliant" is the real norm rather than "being safe/effective"; check for sanctions against those who surface non-compliance. | Identifies the **cultural enforcement** that sustains theatre — why people maintain the performance. |
| 4 | Responsibility | Check whether accountability is real or ceremonial; identify responsibility gaps (duties without enforcement) and responsibility silence (duties that are never invoked). | Identifies **who is nominally accountable** and whether accountability mechanisms have teeth. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Audit results consistently clean but operational outcomes poor; compliance without improvement; "tick-box" culture; cynicism about governance processes; Tier 1 scan flags on meta-categories II (Systemic — model/method performance theatre) and III (Informational — filtered reporting).

**Primary Hiddens meta-categories addressed:** II (Systemic), III (Informational), V (Relational — what the governed know that the governor does not).

**Standard output:** Paper–practice decoupling register (where formal systems diverge from lived practice, sustained by what cultural and accountability mechanisms); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 6: Cascade Discovery Scan
**Family:** B — Structural and systemic hiding

**Investigative question:** What could propagate through connections we haven't mapped?

**Target mechanism:** Hidden coupling and transmission pathways — things hidden because the system has interactions, feedback loops, or cross-boundary transmission paths that are not modelled or monitored.

**Route:** Systems (G2) → Relations (G2) → Causation (G2) → Boundaries (G1) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Systems | Map feedback loops, dependencies, and buffering/containment mechanisms; identify tight coupling and common-mode failure potential. | Identifies the **structural pathways** through which effects could propagate. |
| 2 | Relations | Map the actual channels through which information, resources, authority, and effects flow between components; identify unexpected or undocumented connections. | Identifies the **relational pathways** that may carry cascading effects. |
| 3 | Causation | Trace causal mechanisms; test whether assumed containment holds; check for non-linear effects and threshold behaviour. | Tests whether **causal assumptions** about isolation and independence are valid. |
| 4 | Boundaries | Check whether critical transmission paths cross the boundaries drawn for the analysis; identify boundary artefacts that create false separation. | Identifies **where the boundary definition** may be hiding propagation paths. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Failures that "shouldn't have been connected"; surprise propagation across supposedly independent systems; fragile equilibria; unexplained oscillation or amplification; Tier 1 scan flags on meta-categories II (Systemic) and IV (Temporal — delayed feedback).

**Primary Hiddens meta-categories addressed:** II (Systemic), IV (Temporal), VI (Ontological — phenomena that emerge only at the coupled-system level).

**Standard output:** Coupling and propagation map (what is connected to what, through which mechanisms, with what containment gaps); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 7: Amnesia Scan
**Family:** C — Temporal hiding

**Investigative question:** Why does this organisation keep being surprised by the same thing?

**Target mechanism:** Institutional memory failure — things hidden because they were once known but were lost through turnover, restructuring, archive failure, or learning-loop breakdown.

**Route:** Learning & Adaptation (G6) → Knowledge (G5) → Failures (G5) → Governance (G6) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Learning & Adaptation | Check whether post-incident findings were retained, distributed, and acted on; identify learning loops that are designed but not closed. | Identifies **whether** the organisation learns from its own history. |
| 2 | Knowledge | Examine whether what was once known is still accessible to those who need it; identify knowledge loss through turnover, siloing, or format decay. | Identifies **what** has been lost and through **which mechanism**. |
| 3 | Failures | Classify recurrence patterns; check whether the same failure type has occurred before and whether prior remediation held. | Identifies **whether** the failure is genuinely novel or a repeat masked by memory loss. |
| 4 | Governance | Check whether review cadences, handover mechanisms, and documentation standards preserve visibility across personnel changes and time. | Identifies the **governance gaps** that allow institutional memory to decay. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Recurrent failures with "lessons learned" reports from each prior occurrence; new personnel encountering "known" problems as if for the first time; post-mortems that repeat recommendations from years prior; Tier 1 scan flags on meta-category IV (Temporal — legacy and historical residue).

**Primary Hiddens meta-categories addressed:** IV (Temporal), III (Informational — knowledge inaccessibility), II (Systemic — method/model not designed for retention).

**Standard output:** Institutional memory failure register (what was known, when it was lost, through which mechanism, with what recurrence evidence); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 8: Narrative Capture Scan
**Family:** A — Social and organisational hiding

**Investigative question:** Is a dominant story crowding out what we need to see?

**Target mechanism:** Sensemaking closure — things hidden because a compelling narrative selects what is salient, assigns causation, and marginalises disconfirming evidence, producing confident but incomplete understanding.

**Route:** Narratives (G4) → Perspectives (G4) → Evidence (G5) → Culture & Norms (G4) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Narratives | Identify the dominant narrative(s); classify by type; map the narrative ecology (dominance, contestation, absence). | Identifies **what story** is shaping sensemaking and action. |
| 2 | Perspectives | Check which vantage points the dominant narrative privileges and which it excludes; identify perspective lock-in. | Identifies **whose reality** the narrative reflects and whose it erases. |
| 3 | Evidence | Test whether the evidence base actually supports the dominant account; check for sidelined disconfirming evidence and echo dynamics. | Tests whether the narrative is **evidence-grounded** or evidence-selecting. |
| 4 | Culture & Norms | Check whether challenging the narrative is socially safe; identify norms that protect the story (loyalty, optimism, consensus pressure). | Identifies the **social enforcement** that sustains narrative capture. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** High confidence without proportionate evidence; alternative explanations dismissed rather than tested; dissenters marginalised or "not invited back"; single-cause explanations for complex events; Tier 1 scan flags on meta-categories I (Perceptual — selective attention) and II (Systemic — frame/model dominance).

**Primary Hiddens meta-categories addressed:** I (Perceptual), II (Systemic), III (Informational — evidence selection), V (Relational — excluded perspectives).

**Standard output:** Narrative capture assessment (which story dominates, what it excludes, whether evidence supports it, and what cultural mechanisms protect it); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 9: Uncertainty Masking Scan
**Family:** B — Structural and systemic hiding

**Investigative question:** Where has false precision hidden genuine not-knowing?

**Target mechanism:** Mistyped or suppressed uncertainty — things hidden because uncertainty has been quantified when it should not have been, communicated with false precision, or sanitised before reaching decision-makers.

**Route:** Uncertainties (G5) → Evidence (G5) → Metrics (G5) → Decisions (G6) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Uncertainties | Classify what kind of not-knowing is present (reducible, irreducible, deep, contested, emergent); check for category errors (e.g., deep uncertainty treated as quantifiable risk). | Identifies **what** is uncertain and whether the uncertainty type is correctly recognised. |
| 2 | Evidence | Check whether precision claims are supported by the evidence base; test for false independence and survivorship bias. | Tests whether the **evidence warrants** the confidence being expressed. |
| 3 | Metrics | Examine whether measurement proxies have been confused with the phenomena they represent; check for Goodhart effects and proxy worship. | Identifies **where measurement** creates an illusion of knowledge. |
| 4 | Decisions | Check whether decision-makers received honest uncertainty ranges or sanitised/compressed numbers; test for false-precision in decision briefs. | Identifies **where** uncertainty was lost in the chain from analysis to decision. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Dashboards that show green while outcomes deteriorate; models that produce precise numbers from sparse or contested inputs; decision briefs without uncertainty ranges; "false certainty" language ("we know that…" without evidence grading); Tier 1 scan flags on meta-categories II (Systemic — method overreach) and VI (Ontological — irreducible not-knowing treated as data gap).

**Primary Hiddens meta-categories addressed:** II (Systemic), VI (Ontological), I (Perceptual — precision creates false comfort).

**Standard output:** Uncertainty masking register (where precision is false, what uncertainty type is misclassified, where decision-makers received sanitised inputs); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 10: Negligence Scan
**Family:** D — Action-induced hiding

**Investigative question:** Who had a duty to look and didn't — and what became hidden as a result?

**Target mechanism:** Omission-driven hiddenness — things hidden not because anyone concealed them and not because they are structurally invisible, but because someone who had a responsibility to detect, investigate, or act failed to discharge that duty.

**Route:** Responsibility (G3) → Failures (G5) → Hiddens (G5) → Causation (G2)

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Responsibility | Map who had duties of care, detection, escalation, and oversight relevant to the scenario; identify responsibility gaps and responsibility silence. | Identifies **who should have looked** and whether those duties were clearly assigned. |
| 2 | Failures | Classify the failure pattern that resulted from the omission; distinguish willful blindness from reckless disregard, ordinary carelessness, systemic inattention, and resource-constrained neglect. | Identifies **how** the omission manifested and what **type** of failure it produced. |
| 3 | Hiddens | Classify what became hidden as a result; profile dimensionally; assign detection and remediation. | Identifies **what** was missed and how to make it visible going forward. |
| 4 | Causation | Trace the causal chain from omission to consequence; test whether earlier detection would have changed outcomes. | Establishes the **causal link** between the duty failure and the resulting harm or risk. |

**Typical entry symptoms:** "Nobody was watching"; near-misses that escalated because monitoring was absent or nominal; assigned reviewers who did not review; controls that existed on paper but were never tested; Tier 1 scan flags on meta-categories III (Informational — channel not monitored) and I (Perceptual — attention not directed).

**Primary Hiddens meta-categories addressed:** I (Perceptual), III (Informational), V (Relational — role-based visibility gaps).

**Standard output:** Negligence register (which duties were owed, by whom, what was missed, and what causal consequence followed); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

---

### Scan 11: Belief Persistence Scan
**Family:** A — Social and organisational hiding

**Investigative question:** What are we unable to see because our existing beliefs filter it out before it reaches conscious analysis?

**Target mechanism:** Epistemic filtering — things hidden not by external suppression or structural invisibility but by the internal belief architecture of the analysts, decision-makers, or organisation. Identity-protective cognition, entrenched prior beliefs, collective false consensus, and espoused-operative divergence prevent disconfirming realities from being recognised even when evidence is available.

**Route:** Beliefs (G5) → Values (G4) → Evidence (G5) → Diagnosis (G5) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Beliefs | Map the operative beliefs (not just espoused beliefs) shaping interpretation; identify formation mechanisms, entrenchment level, and identity-protective dynamics; check for collective distortion patterns (groupthink, pluralistic ignorance, Abilene paradox). | Identifies **what beliefs** are filtering perception and whether they are entrenched or revisable. |
| 2 | Values | Check whether sacred or inviolable values make certain conclusions emotionally or politically unthinkable; identify where value commitments have fused with factual beliefs (making evidence irrelevant to belief revision). | Identifies **which conclusions are off-limits** and why — the normative shield around certain beliefs. |
| 3 | Evidence | Test whether the evidence base has been unconsciously filtered by belief-consistent selection; check for confirmation bias in evidence gathering, weighting, and interpretation; identify disconfirming evidence that exists but has been discounted or ignored. | Tests whether **evidence is being used to update beliefs** or to confirm them. |
| 4 | Diagnosis | Check whether the diagnostic process itself is trapped in a familiar pattern; test for premature closure, anchoring on initial hypotheses, and failure to maintain a differential. | Tests whether the **act of diagnosing** is reproducing the belief rather than testing it. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Strong consensus without rigorous testing; evidence that should have updated views but didn't; "we've always done it this way" as justification; emotional or defensive reactions to alternative hypotheses; identity-laden language around factual claims ("that's not who we are"); Tier 1 scan flags on meta-categories I (Perceptual — belief-shaped attention) and II (Systemic — model/method entrenchment).

**Primary Hiddens meta-categories addressed:** I (Perceptual), II (Systemic), V (Relational — whose beliefs dominate), VI (Ontological — category absence sustained by belief).

**Standard output:** Belief persistence assessment (which operative beliefs are filtering perception, through what entrenchment mechanisms, with what relationship to available evidence, and what diagnostic patterns they sustain); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

**Relationship to Scan 8 (Narrative Capture):** Narrative Capture targets the *story* that shapes collective sensemaking. Belief Persistence targets the deeper *cognitive and identity structures* that make certain stories unchallengeable. Narrative Capture asks "what story dominates?"; Belief Persistence asks "why can't we revise the beliefs that sustain it?" Run Narrative Capture first if the symptom is story dominance; run Belief Persistence first if the symptom is resistance to evidence.

---

### Scan 12: Competency Blindspot Scan
**Family:** B — Structural and systemic hiding

**Investigative question:** What's hidden because the people responsible for looking don't have the capability to see it?

**Target mechanism:** Capability-driven invisibility — things hidden not because anyone suppresses them or because the system is structurally complex, but because the agents assigned to detect, investigate, or act lack the skills, cognitive repertoire, tools, or resources to recognise what is in front of them.

**Route:** Competencies (G3) → Agents (G3) → Resources (G2) → Processes (G2) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Competencies | Map the competency demand (what detection, diagnostic, and intervention skills the scenario requires) against competency supply (what the assigned agents actually possess at the required proficiency); identify critical gaps, concentration risks, and tacit-competency invisibility. | Identifies **what capabilities are missing** and where demand-supply mismatches are most consequential. |
| 2 | Agents | Check whether the right agents are positioned in the right roles with the right access and mandate; identify role-competency mismatches and single-point-of-expertise risks. | Identifies **who** is looking and whether their role positioning matches the capability the scenario demands. |
| 3 | Resources | Test whether detection and investigation are adequately resourced — instruments, data access, time, specialist support, analytical tools; identify resource starvation that constrains observation even when competence exists. | Identifies **whether capability can be exercised** given the resources available. |
| 4 | Processes | Check whether operational workflows create the conditions for competent observation (time to think, access to signals, structured review) or whether they crowd it out (overload, fragmentation, procedural rigidity). | Identifies **whether process design** enables or prevents competent detection. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Detection failures despite good access to data; "we didn't recognise it as significant"; credential-competency divergence (qualifications don't match real skills); expertise concentration in one or two individuals; high turnover in critical detection roles; Tier 1 scan flags on meta-categories I (Perceptual — attention not competent) and V (Relational — positional mismatch).

**Primary Hiddens meta-categories addressed:** I (Perceptual), II (Systemic — method/tool inadequacy), V (Relational — role-capability mismatch).

**Standard output:** Competency blindspot register (what capabilities are required, what is available, where critical gaps exist, and how process/resource constraints compound the gap); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

**Relationship to Scan 10 (Negligence):** Negligence targets *duty failure* — someone had the responsibility and didn't discharge it. Competency Blindspot targets *incapacity* — someone may be diligently trying but can't see what they lack the expertise to recognise. Run Negligence first if the symptom is "nobody was watching"; run Competency Blindspot first if the symptom is "they were watching but missed it."

---

### Scan 13: Intervention Blindspot Scan
**Family:** D — Action-induced hiding

**Investigative question:** What's hidden about why our interventions aren't working — or are making things worse?

**Target mechanism:** Action-induced hiddenness — things hidden because the act of intervening creates new hiding mechanisms, obscures the real dynamics, or masks the original problem rather than solving it. This includes interventions that change the system's observability, misdiagnoses that persist because "implementation failure" is blamed instead, and side effects that are not monitored.

**Route:** Interventions (G6) → Risk (G6) → Diagnosis (G5) → Systems (G2) → **Hiddens (G5)**

| Step | Framework | Action | Contribution to chain |
|---|---|---|---|
| 1 | Interventions | Inventory current and recent interventions; check whether each intervention's theory of change matches the actual causal mechanism it targets; identify interventions that have been applied but never evaluated, or that have been repeated despite evidence of ineffectiveness. | Identifies **what actions have been taken** and whether their design logic is sound. |
| 2 | Risk | Examine whether the intervention has generated new risks that aren't being monitored; check for side effects, rebound effects, resistance, and displacement (the problem moves rather than resolves). | Identifies **what new problems** the intervention may have created or masked. |
| 3 | Diagnosis | Check whether the original diagnosis was correct; test whether intervention failure is being attributed to "implementation problems" when the real issue is misdiagnosis; check for anchoring on the original explanation despite disconfirming evidence from intervention outcomes. | Tests whether the **underlying explanation** is still valid or whether intervention failure is itself diagnostic evidence. |
| 4 | Systems | Check whether the intervention has changed the system's behaviour in ways that alter its observability — new feedback loops, changed incentive structures, displaced attention, or modified information flows that make the original problem harder to see. | Identifies **whether the intervention changed what is visible** as well as what it was intended to change. |
| 5 | Hiddens | Classify; profile; assign detection and remediation. | Produces Hiddens Register entries. |

**Typical entry symptoms:** Interventions that "should have worked" but didn't; problems that reappear in different forms after being "fixed"; declining metrics that plateau after intervention without reaching targets; new problems emerging in the wake of a change programme; repeated restructurings with similar outcomes; Tier 1 scan flags on meta-categories II (Systemic — intervention changed system behaviour) and IV (Temporal — delayed or masked consequences).

**Primary Hiddens meta-categories addressed:** II (Systemic), IV (Temporal), I (Perceptual — intervention creates false comfort), VI (Ontological — new phenomena emerge from the intervention itself).

**Standard output:** Intervention blindspot register (which interventions may be masking or creating hiddenness, through what mechanisms, with what evidence of ineffectiveness or side effects); candidate hiddens shortlist; handoff to §7.2 Micro-Protocol.

**Relationship to Scan 10 (Negligence) and Scan 2 (Drift):** Intervention Blindspot targets problems *created by action*, while Negligence targets problems *created by omission* and Drift targets problems *created by gradual change*. These three scans together cover the full temporal spectrum of action-related hiding: what we didn't do (Negligence), what changed slowly while we weren't watching (Drift), and what our response itself made invisible (Intervention Blindspot).

---

### 7.5.2.14 Frameworks not assigned as scan steps

Three of the 50 frameworks do not appear as explicit steps in any scan. This is by design:

**Situations Context Classification (G1)** classifies the type of scenario (post-failure, pre-change, adversarial, etc.) and is a precondition for scan selection, not a scan step. It informs which scans to invoke via the Triage Matrix (§7.5.3) and is already embedded in the Operating Guide's routing logic (§4.3).

**Personas (G3)** provides motivational profiles for agents. It strengthens scans that involve agent behaviour (particularly the Suppression Scan, Belief Persistence Scan, and Competency Blindspot Scan) but does not anchor a distinct hiding mechanism. It is recommended as an **augmentation** at the agent-analysis steps of those scans when the scenario involves key individuals whose motivational profiles are decision-relevant.

**Realities (G1)** maps the layers of reality present in a scenario (substrate, experience, representation, institution, normativity, possibility, process). It strengthens the Positional Blindness Scan and Legitimacy Theatre Scan by adding a check for **reality-layer confusion** (e.g., treating a metric as the system, or a policy as the practice). It is recommended as an **augmentation** at the boundary/framing steps of those scans when category confusion is suspected.

---

## 7.5.3 Triage Matrix: Tier 1 Symptoms → Targeted Scan Selection

### Narrative introduction

After running the mandatory Tier 1 Six-Category Scan (§7.1), the analyst will have a shortlist of candidate hiddens with meta-category flags and preliminary symptoms. The question then becomes: *which targeted scan should I reach for?* The Triage Matrix answers this by connecting Tier 1 outputs and scenario features to the most appropriate scan(s).

The matrix is a **selection aid**, not a constraint. It encodes the most common symptom-to-mechanism mappings, but experienced analysts may identify scan needs that the matrix does not capture. When in doubt, run the scan — the cost of a false positive (a scan that finds nothing) is low, while the cost of a false negative (a hiding mechanism that persists because no scan was run) can be high.

**Rules of use:**
- Run after (or alongside) the Tier 1 scan.
- Multiple scans may be indicated; prioritise by consequence and available time.
- If three or more scans are indicated, consider whether Tier 3 escalation (§7.3) is warranted instead.
- Record the selection rationale in the routing statement (§4.3.2).

### Primary selection: by Tier 1 meta-category flags

| Tier 1 meta-category flagged | Primary scan(s) to consider | Secondary scan(s) if symptoms overlap |
|---|---|---|
| I Perceptual (missed obvious signals; selective noticing) | Narrative Capture Scan; Belief Persistence Scan; Positional Blindness Scan | Suppression Scan (if attention is shaped by power); Uncertainty Masking Scan (if precision creates false comfort); Competency Blindspot Scan (if observers lack expertise) |
| II Systemic (frame disputes; metric/proxy distortions) | Uncertainty Masking Scan; Positional Blindness Scan; Belief Persistence Scan | Legitimacy Theatre Scan (if metrics are performative); Cascade Discovery Scan (if model exclusions hide coupling); Intervention Blindspot Scan (if prior interventions changed system behaviour) |
| III Informational (silence, noise, fragmentation) | Suppression Scan; Evidence Corruption Scan | Negligence Scan (if channels exist but are unmonitored); Amnesia Scan (if information was once available); Competency Blindspot Scan (if receivers lack interpretive capability) |
| IV Temporal (legacy effects; slow drift) | Drift Scan; Amnesia Scan | Cascade Discovery Scan (if delayed feedback is suspected); Negligence Scan (if monitoring duty was owed); Intervention Blindspot Scan (if past interventions masked the drift) |
| V Relational (stakeholder blindspots) | Positional Blindness Scan; Suppression Scan; Competency Blindspot Scan | Narrative Capture Scan (if dominant perspective shapes the narrative); Legitimacy Theatre Scan (if governance excludes key stakeholders) |
| VI Ontological (anomalies without language) | Positional Blindness Scan; Uncertainty Masking Scan; Belief Persistence Scan | Cascade Discovery Scan (if emergent phenomena are suspected); Narrative Capture Scan (if category absence is sustained by story dominance) |

### Secondary selection: by scenario features

| Scenario feature | Scan(s) to consider |
|---|---|
| Post-failure with "everyone knew" pattern | Suppression Scan + Negligence Scan |
| Post-failure with recurrence (same failure type has occurred before) | Amnesia Scan + Drift Scan |
| Regulated environment with clean audits but poor outcomes | Legitimacy Theatre Scan + Drift Scan |
| High-stakes decision with sparse or contested evidence | Evidence Corruption Scan + Uncertainty Masking Scan |
| Multi-stakeholder conflict with fundamentally different accounts | Positional Blindness Scan + Narrative Capture Scan |
| Complex system with surprise propagation or cascading failure | Cascade Discovery Scan + Drift Scan |
| Adversarial context or suspected strategic concealment | Suppression Scan + Evidence Corruption Scan |
| Transformation or change programme that stalled | Legitimacy Theatre Scan + Narrative Capture Scan + Intervention Blindspot Scan |
| Slow-onset crisis ("boiling frog") | Drift Scan + Uncertainty Masking Scan + Negligence Scan |
| New leadership or personnel encountering "known" problems as novel | Amnesia Scan + Negligence Scan |
| Strong consensus without rigorous testing; defensiveness about core assumptions | Belief Persistence Scan + Narrative Capture Scan |
| Detection failures despite good data access and formal monitoring | Competency Blindspot Scan + Negligence Scan |
| Interventions that "should have worked" but didn't, or new problems appearing after a fix | Intervention Blindspot Scan + Drift Scan + Cascade Discovery Scan |
| Expertise concentrated in a few individuals; recent key departures | Competency Blindspot Scan + Amnesia Scan |

---

## 7.5.4 Execution Protocol

### Narrative introduction

This section tells you *how* to run a targeted scan once you have selected one. The protocol is designed to be lightweight — it imposes only the minimum discipline needed to produce consistent, auditable outputs. The heavy analytical work happens within each scan step using the designated framework's own tools and tables.

The protocol has six steps: select, execute, converge, check escalation, check interaction, and feed into closure. For LLM execution, §7.5.8 provides the mechanical detail (pseudocode, gate questions, output tables) that makes each step deterministic.

### Step-by-step execution
| Step | Action | Artefact updated |
|---|---|---|
| 1 | **Select scan(s)** using the Triage Matrix (§7.5.3) or analyst judgement. Record selection rationale. | Routing statement (§4.3.2) |
| 2 | **Execute scan steps** in sequence. At each step, use the designated framework at Light Depth or Full Depth as warranted by stakes and available time. Record findings in framework-specific registers. Tag all material claims F/I/A/U per Appendix D (PD-02). | Framework tables; Evidence Register; intermediate notes |
| 3 | **Converge on Hiddens.** At the final step (Hiddens), classify all candidate hiddens surfaced during the scan. Apply the §7.2 Micro-Protocol: rate mechanism, reducibility, detectability, agency, and consequence; assign detection and remediation interfaces. | Hiddens Register |
| 4 | **Check for escalation triggers.** If findings meet any criterion in §7.3, escalate to Tier 3. | Escalation recommendation |
| 5 | **Check for cross-scan interaction.** If findings suggest a second hiding mechanism is active (e.g., a Suppression Scan reveals that the suppressed information was also subject to Drift), consult the Scan Interaction Map (§7.5.5) and invoke the additional scan or record it as a recommended follow-up. | Routing statement update or follow-up register |
| 6 | **Feed outputs into closure.** Ensure all candidate hiddens are entered into the Hiddens Register with status, owners, and residual risk. Feed into §7.4 closure artefacts. | Hiddens Register; Closure artefacts |

### Output contract (what a completed targeted scan must produce)
| Output | Required content | Appendix D rule |
|---|---|---|
| Scan selection rationale | Which scan was invoked and why (Tier 1 symptoms, scenario features, or analyst judgement) | PD-04 (provenance) |
| Framework-step findings | Key findings at each step in the routing chain, each tagged F/I/A/U (brief; not a full framework run unless Full Depth was warranted) | PD-02 (tagging), PD-03 (observation vs interpretation) |
| Candidate hiddens shortlist | Hiddens surfaced, with mechanism tag, meta-category, preliminary consequence rating, and F/I/A/U tag | PD-07 (default to hiddenness) |
| §7.2 Micro-Protocol outputs | Dimensional profiles, detection/remediation interfaces, and interaction chains for high-consequence hiddens | PD-09 (residual hiddenness) |
| Cross-scan notes | Whether findings suggest additional scans or Tier 3 escalation | PD-08 (non-premature closure) |
| Residual unknowns | What the scan could not resolve and why (access, time, or irreducibility); each tagged U with proposed probe/test | PD-01, PD-09 |

---

## 7.5.5 Scan Interaction Map

### Narrative introduction

Hiding mechanisms rarely operate alone. Suppression creates the conditions for evidence corruption. Drift is sustained by legitimacy theatre. Narrative capture masks positional blindness. When you run one scan and find something, the interaction map tells you which other scan to consider running next — not because the first scan failed, but because hiding mechanisms compound.

Think of the interaction map as a *follow-up guide*: "If Scan X found Y, also consider Scan Z, because the mechanisms are linked." This prevents the common failure mode where a targeted investigation correctly identifies one hiding mechanism but misses the second mechanism that sustains it.

| If this scan finds... | Consider also running... | Because... |
|---|---|---|
| Suppression Scan → active concealment by power-holders | Evidence Corruption Scan | Concealed information often flows through corrupted evidence channels. |
| Suppression Scan → cultural enforcement of silence | Narrative Capture Scan | Silence norms are typically sustained by a narrative that justifies them. |
| Drift Scan → governance tempo too slow to detect change | Legitimacy Theatre Scan | Slow governance often coexists with performative compliance that masks the drift. |
| Drift Scan → operational workarounds normalised | Negligence Scan | Normalised workarounds may indicate unmonitored duties. |
| Positional Blindness Scan → excluded perspectives | Suppression Scan | Perspective exclusion may be structurally enforced, not merely accidental. |
| Evidence Corruption Scan → non-independent evidence echoing | Narrative Capture Scan | Echo dynamics are frequently sustained by a dominant narrative that privileges the echoed account. |
| Legitimacy Theatre Scan → paper–practice decoupling | Drift Scan | Theatre often begins as drift before becoming entrenched. |
| Legitimacy Theatre Scan → ceremonial accountability | Negligence Scan | Ceremonial accountability implies duties are assigned but not discharged. |
| Cascade Discovery Scan → hidden coupling across boundaries | Positional Blindness Scan | Coupling may be invisible because the boundary definition separates connected components. |
| Amnesia Scan → recurrent failure despite prior post-mortems | Legitimacy Theatre Scan | Recurrence after "lessons learned" may indicate learning-theatre rather than genuine learning. |
| Uncertainty Masking Scan → false precision in decision briefs | Evidence Corruption Scan | False precision often rests on corrupted or non-independent evidence. |
| Negligence Scan → monitoring duty owed but not discharged | Suppression Scan | Non-monitoring may be incentivised rather than merely negligent. |
| Belief Persistence Scan → identity-protective entrenchment | Narrative Capture Scan | Entrenched beliefs typically generate and sustain protective narratives. |
| Belief Persistence Scan → collective false consensus | Suppression Scan | False consensus can be sustained by social pressure that suppresses dissent. |
| Belief Persistence Scan → espoused-operative divergence | Legitimacy Theatre Scan | Stating one belief while acting on another is a form of paper–practice decoupling. |
| Competency Blindspot Scan → critical capability gaps | Negligence Scan | Capability gaps may indicate that responsibility was assigned without ensuring the competence to discharge it. |
| Competency Blindspot Scan → expertise concentration | Amnesia Scan | Concentrated expertise is vulnerable to knowledge loss when key individuals leave. |
| Competency Blindspot Scan → resource starvation | Suppression Scan | Systematic under-resourcing of detection may be incentivised rather than accidental. |
| Intervention Blindspot Scan → misdiagnosis persisting | Belief Persistence Scan | If the diagnosis is wrong but the organisation cannot let go of it, belief entrenchment may be sustaining the misdiagnosis. |
| Intervention Blindspot Scan → side effects not monitored | Negligence Scan | Unmonitored side effects imply monitoring duties were not discharged. |
| Intervention Blindspot Scan → intervention changed system observability | Cascade Discovery Scan | Changed observability may have created new hidden coupling or masked existing feedback loops. |

---

## 7.5.6 Glossary Additions (for §11)

### Narrative introduction

These terms are specific to the targeted scan infrastructure and should be added to the Operating Guide's main glossary (§11) when §7.5 is integrated.

| Term | Definition |
|---|---|
| Targeted Hiddens Discovery Scan | A purpose-built cross-framework routing pattern that pursues a specific hiding mechanism through its causal chain across multiple frameworks and groups. Optional diagnostic layer; supplements but does not replace the mandatory Tier 1 scan. |
| Triage Matrix | A selection aid that connects Tier 1 scan symptoms and scenario features to the most appropriate targeted scan(s). |
| Hiding mechanism | The identifiable process or structure by which a reality-relevant factor becomes unavailable to the relevant actors at the relevant moment. Each targeted scan is designed to pursue a specific mechanism class. |
| Scan Interaction Map | A table of common interactions between hiding mechanisms, used to identify when one targeted scan's findings should trigger a second scan. |
| Scan family | A grouping of scans by the primary domain of the hiding mechanism they target: A (Social and organisational), B (Structural and systemic), C (Temporal), D (Action-induced). |
| Gate question | A decision point within a scan step that determines whether to proceed, exit early, or redirect. Used in the LLM Execution Adapter to prevent hollow execution when a scan step finds nothing material. |
| Scan augmentation | The optional inclusion of a framework (Situations, Personas, or Realities) that is not a primary scan step but strengthens a specific step when the scenario warrants it. |

---

## 7.5.8 LLM Execution Adapter (Appendix D compliance layer)

### Narrative introduction

The scan definitions in §7.5.2 tell a human analyst *what to look for and why*. This section tells an LLM *exactly how to execute each scan step mechanically* — what tables to produce, what tags to apply, what questions to answer before proceeding, and what constitutes "enough" to advance or exit. It exists because LLMs need operational specificity that human analysts supply from professional judgement.

The adapter is structured as follows:

**Universal scan pseudocode** (§7.5.8.1) provides the algorithmic skeleton that applies to all 13 scans. It encodes the select → execute → gate → converge → escalate → close sequence with F/I/A/U tagging, evidence provenance, and branching logic at every step.

**Per-step minimum output table** (§7.5.8.2) defines the minimum table schema that every scan step must produce. This ensures consistent, auditable outputs regardless of which scan is run.

**Gate questions** (§7.5.8.3) provide the decision point at each step that determines whether to proceed, exit early, or redirect. Without gate questions, an LLM will dutifully continue through all steps even when a step finds nothing, producing hollow output that creates false confidence.

**Depth triggers** (§7.5.8.4) specify when a scan step warrants Full Depth versus Light Depth execution, translating the Operating Guide's general depth logic (§4.2) into scan-specific criteria.

**Appendix D compliance checklist** (§7.5.8.5) maps each adapter element to the specific prompt discipline rule it implements, ensuring traceability.

### 7.5.8.1 Universal scan pseudocode (LLM-executable)

```text
TARGETED_SCAN(scan_id, scenario_context, tier1_outputs):

  ## PHASE 1: SELECT
  1) Record scan_id and selection rationale (Tier 1 symptom, scenario feature, or analyst judgement).
  2) Tag selection rationale as F/I/A:
       F if triggered by documented Tier 1 findings,
       I if inferred from scenario features,
       A if based on analyst/user judgement (flag as testable).
  3) Determine depth_default:
       IF scenario has high consequence OR adversarial context OR contested evidence
         THEN depth_default = Full Depth
         ELSE depth_default = Light Depth

  ## PHASE 2: EXECUTE STEPS (loop through scan route)
  4) FOR step_number = 1 TO (number_of_steps - 1):
       ## The final step is always Hiddens convergence (handled in Phase 3)

       a) IDENTIFY the framework for this step from the scan definition.

       b) DETERMINE step depth:
            IF depth_default = Full Depth → use Full Depth
            ELSE check scan-specific depth triggers (§7.5.8.4):
              IF any trigger fires → use Full Depth for this step
              ELSE → use Light Depth

       c) EXECUTE the framework action specified in the scan definition.
            - Extract relevant facts from scenario and available artefacts.
            - Populate the Per-Step Minimum Output Table (§7.5.8.2).
            - Tag EVERY row F/I/A/U per Appendix D (PD-02).
            - For each I or A entry, note at least one alternative interpretation.
            - For each U entry, generate an information request or probe/test.

       d) APPLY GATE QUESTION (§7.5.8.3) for this scan and step:
            IF gate answer = NO (nothing material found):
              Record: "[Scan name], Step [N]: No material findings. Gate: [question]. Answer: No."
              IF this is Step 1 of the scan:
                EXIT scan. Record: "[Scan name]: Exited at Step 1 — no material basis to continue.
                Residual note: mechanism not detected given available evidence; mark as U if
                scenario stakes warrant future re-check."
              ELSE:
                SKIP to next step (the mechanism may still be active downstream in the chain).
            IF gate answer = YES:
              PROCEED to next step.
            IF gate answer = REDIRECT:
              Record redirect rationale; invoke the indicated alternative scan; EXIT this scan.

       e) CHECK for cross-scan signals:
            IF findings at this step match a row in the Scan Interaction Map (§7.5.5):
              Record the interaction signal and the suggested follow-up scan.
              Do NOT invoke the follow-up scan now — queue it for Phase 5.

  ## PHASE 3: CONVERGE ON HIDDENS
  5) Collect all candidate hiddens surfaced across steps.
  6) For each candidate hidden, apply the §7.2 Micro-Protocol:
       a) Classify by Hiddens type (from 30-type taxonomy).
       b) Assign meta-category (I–VI).
       c) Rate on five dimensions: mechanism, reducibility, detectability, agency, consequence.
       d) Tag each dimension rating F/I/A/U.
       e) Assign at least one detection interface and one remediation interface per
          high-consequence hidden.
       f) Map interaction chains (how this hidden relates to other hiddens found).
  7) Enter all classified hiddens into the Hiddens Register.

  ## PHASE 4: CHECK ESCALATION
  8) Apply §7.3 Escalation Rule:
       IF any criterion met (high consequence, adversarial, persistent disagreement,
          repeat failure, cascade suspicion):
         Record escalation recommendation with rationale.

  ## PHASE 5: CHECK CROSS-SCAN INTERACTION
  9) Review all queued interaction signals from Phase 2(e).
  10) For each signal:
        IF the follow-up scan has not already been run in this session:
          Recommend it (or invoke it if within timebox).
        ELSE:
          Record: "Follow-up scan already completed; check for compound findings."

  ## PHASE 6: PRODUCE OUTPUT
  11) Produce the Output Contract (§7.5.4):
        - Scan selection rationale (F/I/A tagged)
        - Framework-step findings (per-step tables, all F/I/A/U tagged)
        - Candidate hiddens shortlist (classified, profiled, with detection/remediation)
        - §7.2 Micro-Protocol outputs
        - Cross-scan notes (queued interactions and recommendations)
        - Residual unknowns (each tagged U with proposed probe/test)
  12) Feed outputs into §7.4 Closure artefacts.

END TARGETED_SCAN
```

### 7.5.8.2 Per-step minimum output table (required at every scan step)

Every scan step must produce at least one instance of this table. If a step finds nothing material, produce a single row recording that finding with tag U or A.

| Field | Description | F/I/A/U tag required? |
|---|---|---|
| Step ID | Scan name + step number (e.g., "Suppression-S1") | No |
| Framework | Which framework was used at this step | No |
| Depth | Light Depth or Full Depth (with rationale if Full Depth) | No |
| Finding ID | Local identifier for this finding (e.g., "SUP-S1-01") | No |
| Finding | What was found (plain language) | Yes |
| Evidence basis | What evidence supports this finding (source, type, quality) | Yes |
| Mechanism contribution | How this finding contributes to the hiding mechanism chain | Yes |
| Candidate hidden (if any) | Preliminary hidden to carry forward to Hiddens convergence | Yes |
| Alternative interpretation | At least one alternative explanation for I or A findings | Yes (for I/A) |
| Information request | What additional evidence would strengthen or disconfirm this finding | Yes (for U) |
| Gate answer | YES / NO / REDIRECT for this step's gate question | No |

### 7.5.8.3 Gate questions (by scan and step)

Gate questions are the decision points that prevent hollow execution. At each step, the LLM must answer the gate question before proceeding. If the answer is NO at Step 1, exit the scan (the mechanism is not detectably active). If NO at a later step, skip to the next step (partial chains are possible). If REDIRECT, exit and invoke the indicated scan.

| Scan | Step 1 gate | Step 2 gate | Step 3 gate | Step 4 gate |
|---|---|---|---|---|
| 1. Suppression | Did Step 1 identify ≥1 actor with both capacity and plausible motive to suppress? | Do the identified power-holders have incentive structures that reward non-disclosure? | Are there cultural norms or social costs that enforce silence beyond individual incentive? | Are there channel bottlenecks, filters, or dead zones where suppressed signals would be blocked? |
| 2. Drift | Did Step 1 identify ≥1 slow-moving change or baseline deviation? | Has operational practice diverged from design intent in ways consistent with the temporal drift? | Is governance tempo too slow to have detected the drift at its actual rate? | Has the drift produced or contributed to identifiable failure patterns? |
| 3. Positional Blindness | Did Step 1 identify ≥1 excluded or under-represented perspective? | Does the system boundary exclude realities that the missing perspective(s) would see? | Does the chosen scale of analysis miss phenomena visible at other levels? | Are there analytical dimensions (axes of variation) that are not being tracked? |
| 4. Evidence Corruption | Did Step 1 identify ≥1 evidence quality concern (echo, non-independence, survivorship, fabrication)? | Do reporting actors have incentive structures that could motivate the identified corruption? | Are there channel points where evidence fidelity degrades during transmission? | Is a dominant narrative selecting which evidence gets attention? |
| 5. Legitimacy Theatre | Did Step 1 identify ≥1 legitimacy claim that appears ritualistic rather than substantive? | Does paper governance diverge from lived governance in areas related to the ritualistic claims? | Do cultural norms reward "looking compliant" over substantive performance? | Is accountability ceremonial (duties assigned but never enforced or tested)? |
| 6. Cascade Discovery | Did Step 1 identify ≥1 feedback loop, tight coupling, or common-mode failure potential? | Are there relational channels that could carry cascading effects beyond what is modelled? | Do causal assumptions about containment hold under stress, or are there non-linear thresholds? | Do critical propagation paths cross the analysis boundary? |
| 7. Amnesia | Did Step 1 identify ≥1 learning loop that is designed but not closed, or findings not retained? | Has knowledge been lost through turnover, siloing, or format decay in ways relevant to the scenario? | Has the same or similar failure occurred before? | Do governance mechanisms preserve visibility across personnel changes and time? |
| 8. Narrative Capture | Did Step 1 identify a dominant narrative with disproportionate influence on sensemaking? | Does the narrative privilege certain perspectives and exclude others? | Does the evidence base support the narrative, or has disconfirming evidence been sidelined? | Are there social costs to challenging the narrative? |
| 9. Uncertainty Masking | Did Step 1 identify ≥1 uncertainty that is miscategorised or under-reported? | Does the evidence base warrant the precision being claimed? | Have measurement proxies been confused with the phenomena they represent? | Did decision-makers receive honest uncertainty ranges? |
| 10. Negligence | Did Step 1 identify ≥1 duty of care, detection, or oversight that was owed? | Did the duty-holder fail to discharge the identified duty? | Did the failure to look result in identifiable hiddens? | — (Step 4 is Causation: always proceed if Step 3 found hiddens) |
| 11. Belief Persistence | Did Step 1 identify ≥1 operative belief with entrenchment indicators or identity-protective dynamics? | Do sacred or inviolable values make certain conclusions politically or emotionally unthinkable? | Has evidence been filtered by belief-consistent selection (confirmation bias in gathering or weighting)? | Is the diagnostic process reproducing the belief rather than testing it? |
| 12. Competency Blindspot | Did Step 1 identify ≥1 critical demand-supply gap in detection or diagnostic capability? | Are the agents in detection/oversight roles mismatched to the capability the scenario demands? | Are detection/investigation resources adequate (instruments, time, data access, specialist support)? | Do operational workflows enable or crowd out competent observation? |
| 13. Intervention Blindspot | Did Step 1 identify ≥1 intervention whose theory of change may not match the actual causal mechanism? | Has the intervention generated new risks or side effects that are not being monitored? | Is the original diagnosis still valid, or is "implementation failure" masking misdiagnosis? | Has the intervention changed the system's observability? |

### 7.5.8.4 Depth triggers (scan-specific)

These triggers override the default Light Depth setting and escalate a scan step to Full Depth. They supplement the general depth logic in §4.2.

| Condition | Applies to which scans | Effect |
|---|---|---|
| Adversarial concealment is plausible | Suppression, Evidence Corruption | All steps Full Depth |
| Scenario involves safety, regulatory, or existential consequence | All scans | All steps Full Depth |
| Step 1 identifies ≥3 candidate findings | Any scan | Remaining steps Full Depth |
| Evidence at this step is contested or contradictory | Any scan | This step Full Depth |
| Incentive/power structures suggest strategic distortion | Suppression, Evidence Corruption, Legitimacy Theatre, Belief Persistence | Steps involving Incentives, Power, or Culture Full Depth |
| Recurrence pattern detected (same failure type has occurred before) | Drift, Amnesia, Negligence, Intervention Blindspot | All steps Full Depth |
| Competency gap is decision-critical (single-point-of-expertise, credential-competency divergence) | Competency Blindspot | Steps 1–2 Full Depth |
| Intervention failure pattern detected (repeated restructurings, problems reappearing in different forms) | Intervention Blindspot | All steps Full Depth |

### 7.5.8.5 Appendix D compliance checklist

This table maps each adapter element to the specific Appendix D prompt discipline rule it implements, ensuring that LLM execution of targeted scans is fully compliant with the Operating Guide's canonical requirements.

| Adapter element | Implements rule(s) | How |
|---|---|---|
| F/I/A/U tagging on all output table rows | PD-02 (Tag statements) | Every finding, candidate hidden, and dimension rating is tagged |
| Alternative interpretation field | PD-03 (Separate observation from interpretation), PD-06 (Preserve disagreement) | Forces explicit alternatives for all I/A findings |
| Evidence basis field | PD-04 (Evidence/provenance required) | Links every finding to its evidence source |
| Information request field for U entries | PD-01 (Do not invent facts), PD-05 (Prefer tests over stories) | Converts unknowns into actionable probes/tests |
| Gate questions with early exit | PD-08 (Do not close prematurely — prevents hollow completion theatre) | Stops the scan when there is no material basis to continue |
| Residual unknowns in output contract | PD-09 (Make residual hiddenness explicit) | Forces explicit residual unknowns at scan completion |
| Default-to-hiddenness in scan design | PD-07 (Default to hiddenness) | Every scan assumes the target mechanism may be active |
| Cross-scan interaction signals | PD-06 (Track and preserve disagreement) | Compound mechanisms are flagged rather than collapsed |
| Depth triggers | §4.2 depth logic, PD-04 (evidence-gated confidence) | Escalates depth when evidence conditions demand it |
| Canonical output contract format | §D.4 (Output contract) | Scan outputs match the series-standard deliverable schema |

---

# 8. Quality Controls and Failure-Safe Practices

## 8.1 Quality controls checklist (recommended)
| Control | Purpose | How to implement |
|---|---|---|
| Alternative explanations | Prevent single-cause closure | Maintain at least 2–3 competing hypotheses until evidence collapses them |
| Evidence grading | Prevent confidence inflation | Rate evidence quality and dependency assumptions |
| Incentive/power audit | Prevent distorted accounts | Run G3 map early; protect dissent channels |
| Narrative audit | Prevent story dominance | Separate “story” from “support”; track disconfirming evidence |
| Boundary regression test | Prevent scope drift | Re-check boundaries at each phase gate |
| Drift detection | Prevent slow degradation being missed | Track exceptions/waivers, deferred maintenance, control test realism |
| Escalation discipline | Avoid under-scanning | Apply Tier 3 triggers; document decisions not to escalate |

## 8.2 Minimum “anti-theatre” rule
Every major claim in a diagnosis must be backed by:
- at least one evidence entry (or explicit “evidence gap”),
- an uncertainty statement (where relevant),
- a hiddenness check (“could this be hidden or distorted?”),
- and an owner for follow-up if the claim materially affects decisions.

---

# 9. Governance of the Series (repeatability and evolution)

## 9.1 Roles (recommended)
| Role | Responsibilities |
|---|---|
| Series steward | Owns the operating doctrine, group glossary, and integration rules |
| Framework maintainer | Owns a framework document; ensures template compliance |
| Reviewer | Performs consistency checks and “Hiddens realism” audits |
| Practitioner community | Supplies cases, failure lessons, and extension proposals |

## 9.2 Change control (recommended)
| Change type | Examples | Process |
|---|---|---|
| Non-substantive | Typos, formatting | Maintainer edit; log in document control |
| Substantive content | New archetype, new protocol gate | Reviewer required; version note; update crosswalks |
| Taxonomy extension | New type/dimension/interface | Follow “Extending the Taxonomy” rules; add rationale; add examples; update indexes |
| Group label refinement | Longhand/shorthand wording changes | Keep IDs stable (G1–G6); update group glossary; record compatibility note |


## 9.3 Canonical source rule (LLM prompt discipline)
The **Operating Guide** is the authoritative source for LLM prompt discipline and output contracts.

**Rule:** Framework excerpts must either (a) quote the canonical excerpt verbatim, or (b) point to it without modification. Any changes are made in the Operating Guide first, then propagated mechanically to framework documents.

---

# 10. Operating Principles (mandatory)

## 10.1 Principles table
| Principle | Meaning in practice |
|---|---|
| Visibility-first | Treat hiddenness as a primary object, not an afterthought. |
| Minimum coverage | Avoid single-lens closure; meet minimum group coverage for the stakes. |
| Residual unknowns are deliverables | Closure requires explicit residual hiddenness and ownership. |
| Evidence over confidence | Confidence must be justified by evidence quality and uncertainty treatment. |
| Mechanism plus agency | Explanations must consider both system propagation and actor incentives/power. |
| Robustness over perfection | When irreducible hiddenness exists, design for robustness and monitoring. |
| Learning is a control | Institutionalise learning to prevent drift and recurrence. |

---

# 11. Glossary

This glossary defines all terms that carry specific operational meaning within the Analytical Series Operating Guide. Terms are grouped by domain. For LLM execution semantics (run modes, framework execution depths, artefact schemas), see also §D.10.

## 11.1 Core definitions (§1.3)

| Term | Definition |
|---|---|
| Hidden | A reality-relevant factor that is not visible, legible, or actionable to the relevant actors at the relevant time due to identifiable hiding mechanisms (not merely "unknown"). |
| Complex scenario | A scenario with non-trivial interactions, feedback, delays, multi-scale effects, contested narratives, incomplete evidence, and/or multi-actor strategic behaviour. |
| Failure | A realised outcome (or near miss) where expectations, requirements, safety margins, or objectives were not met; includes process drift and governance breakdowns. |
| Closure | A decision to stop exploring with residual hiddenness explicitly recorded, including why it is acceptable (or not) given stakes. |
| Hiding mechanism | The identifiable process or structure by which a reality-relevant factor becomes unavailable to the relevant actors at the relevant moment. Each targeted scan is designed to pursue a specific mechanism class. |

## 11.2 Group system and coverage (§2–§4)

| Term | Definition |
|---|---|
| Group (G1–G6) | A navigation layer indicating the primary analytic function of a framework: G1 Framing, G2 Mechanism, G3 Agency, G4 Meaning, G5 Epistemics, G6 Action & Control. |
| Minimum group coverage | The minimum set of groups (G1–G6) that must be substantively examined before closure. Prevents single-lens closure. Determined by §4.3 routing decision tree. |
| Routing statement | An explicit record of which routing branches were triggered, why, and the resulting group coverage and depth allocation plan. Required output of the §4.3 decision tree. |
| Depth selection | The decision of which frameworks to run at Full Depth versus Light Depth, based on consequence, evidence quality, incentive/power distortion risk, and coupling/cascade potential (§4.2). |

## 11.3 Run modes and execution depth (§D.6; see also §D.10)

| Term | Definition |
|---|---|
| Run Mode | The overall whole-run execution posture selected after the scenario is provided: Rapid Run Mode or Investigative Run Mode. |
| Rapid Run Mode | A timeboxed (60–180 min), coverage-first run to surface candidate Hiddens, evidence gaps, and next-best probes/tests; ends with an escalation recommendation. Uses §5.1 protocol. |
| Investigative Run Mode | A disciplined investigative run with selective Full Depth Framework Execution on a routed subset, Light Depth Framework Execution elsewhere; iterative and evidence-gated. Uses §5.2 or §5.3 protocol. |
| Full Depth Framework Execution | Full execution of a framework: populate core tables, develop mechanisms, expand tests, integrate evidence, produce structured outputs. Used on the routed subset. |
| Light Depth Framework Execution | Scan-level execution of a framework: identify high-signal hits, candidate Hiddens, contradictions, and missing-information triggers without full table population. Used on remaining groups to prevent omission-by-lens. |
| No-Early-Exclusion Rule | Do not exclude lenses early. Touch all groups at least at Light Depth before prioritisation or closure; allocate depth after the sweep. Prevents process-induced hiddens (§D.6.4). |

## 11.4 Protocols and loop control (§5)

| Term | Definition |
|---|---|
| Iterative investigation loop | The single repeatable cycle used across all run modes: Initialise → Generate → Route → Execute → Test → Re-scan → Decide. Prevents premature narrative closure (§5.0). |
| Rapid Run Mode Protocol | The 7-step timeboxed protocol (§5.1): case question → Tier 1 scan → boundaries → system sketch → evidence gaps → risk/stabilisation → depth/plan. |
| Post-Failure Hidden Discovery Protocol | The 11-phase investigative protocol (§5.2): Frame → Model → Agency → Meaning → Epistemics → Synthesis → Convert → Assure → Learn. |
| Proactive "Hidden Exposure" Protocol | The 6-step pre-change protocol (§5.3): change intent → Tier 1 scan → dependency audit → incentives/comms check → monitoring → governance. |
| Iteration trigger | A condition that requires re-entry into the execution loop: contradictory evidence, "too clean" story, high-impact Unknown, new artefacts arriving, or governance implications (§5.0.3). |
| Stop condition | The criteria that must all hold for bounded closure: timebox requires output, Evidence Ledger supports claims, residual unknowns are explicit and assigned, and detection interfaces exist for top residual hiddens (§5.0.4). |
| Bounded closure | Closure permitted only when all stop conditions are met. Requires explicit residual unknowns, ownership, and monitoring triggers. If not met, output must be non-closure (§5.0.4, §D.3.5). |
| Non-closure | The required output when closure criteria are unmet: what is known, what remains hidden, why it remains hidden, and what would be required to close (§D.3.5, PD-08). |

## 11.5 Artefacts (§6; see also §D.10.2)

| Term | Definition |
|---|---|
| Case statement | Defines the question, stakes, scope, and timebox. Produced in G1; used by all subsequent work. |
| Boundary map | Makes scope explicit; prevents drift. Produced in G1. |
| System map | Shows components, interfaces, flows, and dependencies. Produced in G2. |
| Dependency register | Identifies upstream/downstream coupling and common-mode risks. Produced in G2. |
| Stakeholder map | Identifies perspectives, access, and positional visibility. Produced in G3/G4. |
| Evidence register (Evidence Ledger) | Claim-to-evidence table recording source, quality, dependencies, and bias risks. Produced in G5. |
| Uncertainty register | Tracks uncertainty type, magnitude, and reducibility. Produced in G5. |
| Hiddens register | Structured register of suspected/confirmed Hiddens with mechanisms, detectability, consequence, owners, and status. Produced in G5. |
| Diagnosis statement | Explains best current theory with residual unknowns. Produced in G5. |
| Decision record | Logs choices, rationale, evidence basis, trade-offs, confidence, residual Hiddens, and monitoring. Produced in G6. |
| Intervention portfolio | Set of actions with theories of change and monitoring. Produced in G6. |
| Governance map | Decision rights, oversight, escalation, and assurance cadence. Produced in G6. |
| Group Coverage Matrix | G1–G6 table indicating what was examined, key findings, candidate Hiddens, and next tests. Required in all runs. |
| Hypotheses & Tests Backlog | Differential hypotheses with disconfirming tests, discriminators, required evidence, and status. |
| Information Requests | Explicit list of missing inputs needed to reduce decision-critical Unknowns, with why and expected discriminator value. |
| Investigation Plan | Workstreams, owners, frameworks, inputs/outputs, timeboxes, risks/Hiddens to watch. Recommended for non-trivial runs. |

## 11.6 Hiddens integration discipline (§7)

| Term | Definition |
|---|---|
| Tiered scan | A staged depth model for Hiddens discovery: Tier 1 (six-category scan), Tier 2 (crosswalk shortlist), Tier 3 (full 30-type run). |
| Tier 1 (Hiddens) — Six-Category Scan | Six-category visibility audit across meta-categories I–VI. Mandatory early and pre-closure (minimum twice per run). Assumes hiddens exist (§7.1). |
| Tier 2 (Hiddens) — Crosswalk Shortlist | Structured deepening of top Hiddens: mechanism chain, location, persistence drivers, discriminators, detection/remediation interfaces. Focuses on top candidates, not all types (§7.2). |
| Tier 3 (Hiddens) — Full 30-Type Run | Escalation: full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests. Triggered only by escalation conditions (§7.3). |
| Hiddens meta-category I (Perceptual) | Attention and observation limits; missed obvious signals; selective noticing. |
| Hiddens meta-category II (Systemic) | Methods and models exclude realities; frame disputes; metric/proxy distortions. |
| Hiddens meta-category III (Informational) | Channels are structured and political; silence, noise, fragmentation. |
| Hiddens meta-category IV (Temporal) | History embeds constraints and blinders; legacy effects; slow drift. |
| Hiddens meta-category V (Relational) | Position determines visibility; stakeholder blindspots. |
| Hiddens meta-category VI (Ontological) | Category absence and predictability limits; anomalies without language. |
| Embedded Hiddens Micro-Protocol | The standard 4-step process applied to every shortlisted hidden: Tier 1 scan → rate dimensions (mechanism, reducibility, detectability, agency, consequence) → assign detection and remediation interfaces → record unresolved unknowns (§7.2). |
| Escalation Rule (Tier 3) | The criteria for escalating to a full Hiddens run: high consequence, adversarial concealment, persistent disagreement, repeat failure, cascade suspicion (§7.3). |
| Detection interface | A designed method to make a hidden detectable (instrumentation, access, tests, reporting pathways). |
| Remediation interface | A designed method to reduce or manage a hidden’s consequence (decoupling, buffers, governance controls). |
| Residual hiddenness | The set of hiddens/unknowns that remain after a bounded analysis; must be recorded and governed as deliverables, not omissions. |
| Closure discipline | The required items at every closure: residual unknowns list, acceptability rationale, monitoring plan, ownership, and learning hook (§7.4). |

## 11.7 Targeted Hiddens Discovery Scans (§7.5)

| Term | Definition |
|---|---|
| Targeted Hiddens Discovery Scan | A purpose-built cross-framework routing pattern that pursues a specific hiding mechanism through its causal chain across multiple frameworks and groups. Optional diagnostic layer; supplements but does not replace the mandatory Tier 1 scan. |
| Scan family | A grouping of scans by the primary domain of the hiding mechanism they target: A (Social and organisational), B (Structural and systemic), C (Temporal), D (Action-induced). |
| Triage Matrix | A selection aid that connects Tier 1 scan symptoms and scenario features to the most appropriate targeted scan(s) (§7.5.3). |
| Scan Interaction Map | A table of common interactions between hiding mechanisms, used to identify when one targeted scan’s findings should trigger a second scan (§7.5.5). |
| Gate question | A decision point within a scan step that determines whether to proceed, exit early, or redirect. Used in the LLM Execution Adapter to prevent hollow execution when a scan step finds nothing material (§7.5.8.3). |
| Depth trigger | A condition that overrides the default Light Depth setting and escalates a scan step to Full Depth (§7.5.8.4). |
| Scan augmentation | The optional inclusion of a framework (Situations, Personas, or Realities) that is not a primary scan step but strengthens a specific step when the scenario warrants it. |
| Suppression Scan (Scan 1) | Family A. Pursues deliberate or structurally incentivised concealment. Route: Power → Incentives → Culture & Norms → Communications → Hiddens. |
| Drift Scan (Scan 2) | Family C. Pursues gradual normalised deviation below detection thresholds. Route: Time → Processes → Governance → Failures → Hiddens. |
| Positional Blindness Scan (Scan 3) | Family B. Pursues structural invisibility caused by vantage point. Route: Perspectives → Boundaries → Scale → Dimensions → Hiddens. |
| Evidence Corruption Scan (Scan 4) | Family D. Pursues contamination of the evidence base. Route: Evidence → Incentives → Communications → Narratives → Hiddens. |
| Legitimacy Theatre Scan (Scan 5) | Family A. Pursues paper–practice decoupling. Route: Legitimacy → Governance → Culture & Norms → Responsibility → Hiddens. |
| Cascade Discovery Scan (Scan 6) | Family B. Pursues hidden coupling and transmission pathways. Route: Systems → Relations → Causation → Boundaries → Hiddens. |
| Amnesia Scan (Scan 7) | Family C. Pursues institutional memory failure. Route: Learning & Adaptation → Knowledge → Failures → Governance → Hiddens. |
| Narrative Capture Scan (Scan 8) | Family A. Pursues sensemaking closure by dominant narrative. Route: Narratives → Perspectives → Evidence → Culture & Norms → Hiddens. |
| Uncertainty Masking Scan (Scan 9) | Family B. Pursues mistyped or suppressed uncertainty. Route: Uncertainties → Evidence → Metrics → Decisions → Hiddens. |
| Negligence Scan (Scan 10) | Family D. Pursues omission-driven hiddenness. Route: Responsibility → Failures → Hiddens → Causation. |
| Belief Persistence Scan (Scan 11) | Family A. Pursues epistemic filtering by belief architecture. Route: Beliefs → Values → Evidence → Diagnosis → Hiddens. |
| Competency Blindspot Scan (Scan 12) | Family B. Pursues capability-driven invisibility. Route: Competencies → Agents → Resources → Processes → Hiddens. |
| Intervention Blindspot Scan (Scan 13) | Family D. Pursues action-induced hiddenness. Route: Interventions → Risk → Diagnosis → Systems → Hiddens. |

## 11.8 New frameworks (v3.0 additions)

| Framework | Operational Definition |
|---|---|
| Cognition | Identifies how agents' mental processes—mental models, cognitive biases, heuristics, attention allocation, bounded rationality, and reasoning structures—shape what is perceived, attended to, and concluded. Classifies cognitive processes into six meta-categories and thirty core types; maps how cognitive processes produce systematic perception gaps and judgment errors; surfaces visibility failures created by model-based blindness, attention limits, and heuristic-driven errors. |
| Conflict | Identifies what contestation, adversarial dynamics, and competing interests are active, latent, or strategically concealed in a scenario. Classifies conflict into six meta-categories and thirty core types spanning forms of contestation, conflict triggers, escalation patterns, suppression mechanisms, strategic conflict behaviour, and resolution pathways. Maps escalation and suppression dynamics; surfaces latent opposition hidden by false consensus, reframing, or hierarchy-imposed silence. |
| Coordination | Identifies how multiple actors manage or fail to manage the alignment of their actions through explicit protocols, hierarchical direction, market signals, shared conventions, information systems, and trust networks. Classifies coordination mechanisms into six meta-categories and thirty core types; maps how coordination mechanisms fail through scope gaps, reliability degradation, and cost invisibility; surfaces visibility failures created by assumed coordination, silent misalignment, and orphan risks. |
| Emergence | Identifies what genuinely new, non-reducible, system-level phenomena arise from interactions of components. Classifies them into six meta-categories and thirty core types; surfaces visibility failures (aggregation blindness, temporal mismatch, reductionist model assumptions, category absence, intervention paradox) that prevent early detection and appropriate response; maps detection, intervention, and adaptation interfaces that account for emergence characteristics. |
| Emotions | Identifies what affective states—fear, anger, grief, pride, shame, solidarity, despair, awe, and others—are driving behaviour, shaping perception, and structuring social dynamics in a scenario. Classifies emotions into six meta-categories (thirty core types spanning primary emotions, secondary social emotions, self-evaluative emotions, moral emotions, and existential emotions); maps their intensity, visibility, action readiness, and suppression mechanisms; surfaces emotional suppression norms and hiding mechanisms that render emotions opaque to decision-makers. |
| Ethics | Systematically surfaces and analyses what normative assumptions, moral claims, and questions of fairness, justice, rights, and duties are embedded in a scenario. Classifies ethical considerations into six meta-categories and thirty core types; maps value-neutral framing that conceals normative choices, distributional invisibility, and ethical blind spots; surfaces what ought to be valued and whether acceptance is warranted on moral grounds. |
| Implementation | Diagnoses what actually happens when decisions, interventions, and policies are operationalised into practice. Classifies implementation mechanisms into six meta-categories and thirty core types; maps five cross-cutting dimensions (scope, fidelity, tempo, capacity, monitoring); identifies ten dynamic patterns that surface how implementation diverges from intent; surfaces eight systematic Hiddens families (compliance theatre, capacity blindness, street-level adaptation, resistance invisibility, decision-implementation divergence, cascade effects, unintended consequences, equity impacts). |
| Institutions | Identifies and maps the formal and informal rules, norms, conventions, and enforcement mechanisms that structure behaviour in a scenario. Classifies them into six meta-categories and thirty core types; diagnoses gaps between prescribed and actual practice, institutional lock-in, informal capture, and cross-institutional conflicts; surfaces visibility failures (invisible informal rules, embedded logics, rule-practice gaps, institutional lock-in, informal capture) that Hiddens analysis must remediate. |
| Interests | Identifies what agents fundamentally need, want, or care about beneath their stated positions and demands. Classifies interests into six meta-categories (material, procedural, identity, relational, temporal, institutional) with thirty core types; profiles them across five cross-cutting dimensions (materiality level, consciousness, sustainability, scope, transparency); maps interest conflicts and coalitions; surfaces the hidden interests that explain behaviour diverging from stated positions, negotiation failures, and persistent resistance. |
| Networks | Identifies how nodes (agents, components, systems) are connected. Classifies network topology into six meta-categories and thirty core types; maps how network structure shapes what flows where, who sees what, and how disturbances cascade; surfaces visibility failures (structural hole blindness, echo chamber isolation, cascade pathway invisibility, positional blindness, hub dependency invisibility, bridge-role invisibility) that prevent understanding of topology-driven behaviour. |
| Scenarios | Constructs plausible alternative futures by systematically varying key drivers and assumptions. Classifies scenarios into six meta-categories and thirty core types; maps five cross-cutting dimensions (scope, causation, timeline, reversibility, surprise); identifies eight dynamic patterns that shape scenario evolution; surfaces Hiddens by making strategy assumptions explicit and testing robustness across discontinuous futures. |
| Space and Place | Maps how geographic location, spatial relationships, infrastructure connectivity, place-meaning, and territorial governance shape what is materially possible, who has access to opportunities and resources, what visibility gaps hide, and how costs and benefits are distributed across locations. Classifies spatial phenomena into six meta-categories and thirty core types; maps five cross-cutting dimensions (scale, connectivity, visibility, place-meaning intensity, territorial contestedness); surfaces Hiddens families (geographic privilege blindness, spatial cost displacement, place-invisibility, territorial framing effects, infrastructure vulnerability, place-meaning erasure). |
| Technology | Identifies what designed artefacts, systems, platforms, algorithms, and protocols shape a scenario. Classifies them into six meta-categories and thirty core types; maps their affordances, constraints, and embedded values; surfaces visibility failures (black-box opacity, infrastructural invisibility, design assumptions treated as neutral) they create. Populates Hiddens Register with technology-specific blindnesses including design determinism invisibility, affordance blindspots, infrastructure invisibility, and measurement/bias blindness. |
| Trust | Identifies patterns of confidence and dependence that actors extend to each other, institutions, and information sources. Classifies trust mechanisms into six meta-categories and thirty core types operating across three registers: interpersonal (individual relationships), institutional (organisations and systems), and epistemic (knowledge sources). Maps trust basis portfolios, asymmetries, and recovery capacity; surfaces visibility failures created by trust-based information filtering, cascade-collapse risks, and trust-halo misalignment. |

## 11.9 Quality controls (§8)

| Term | Definition |
|---|---|
| Anti-theatre rule | The requirement that every major claim in a diagnosis must be backed by at least one evidence entry (or explicit evidence gap), an uncertainty statement, a hiddenness check ("could this be hidden or distorted?"), and an owner for follow-up (§8.2). Prevents structurally complete-looking outputs with thin evidential foundations. |

## 11.10 Prompt discipline and F/I/A/U tagging (§D.3; see also §D.10.1)

| Term | Definition |
|---|---|
| Prompt Discipline Rules | The 10 canonical rules (PD-01 to PD-10) governing all LLM-assisted analysis: do not invent facts, tag F/I/A/U, separate observation from interpretation, require evidence provenance, prefer tests over stories, preserve disagreement, default to hiddenness, do not close prematurely, make residual hiddenness explicit, canonical source rule (§D.3.1). |
| F/I/A/U tagging | The mandatory labelling system for all material claims and register rows: F (Fact), I (Inference), A (Assumption), U (Unknown). Required by PD-02 (§D.3.2). |
| Fact (F) | Directly observed, documented, or explicitly provided in the scenario or attached artefacts. |
| Inference (I) | A reasoned conclusion drawn from facts; must note uncertainty and alternatives if material. |
| Assumption (A) | An unverified claim adopted temporarily to proceed; must be testable and flagged as such. |
| Unknown (U) | Not provided or not currently observable/confirmable; must generate a probe/test or information request. |
| Evidence provenance | The requirement that any confidence statement must cite an Evidence Register entry with source type and identifier, or be marked A/I. If evidence is weak, limitations must be stated and next-best evidence proposed (PD-04, §D.3.3). |
| Canonical source rule | The Operating Guide is authoritative for prompt discipline and output contracts. Framework excerpts must either quote the canonical excerpt verbatim or point to it without modification. Changes are made in the Operating Guide first, then propagated mechanically (PD-10, §9.3). |

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v3.0 | 2026-04-08 | Integrated 14 new frameworks (Technology, Institutions, Emergence, Cognition, Networks, Trust, Interests, Emotions, Conflict, Ethics, Coordination, Space and Place, Implementation, Scenarios): updated document header with v3.0 designation, date 2026-04-08, and changelog; expanded §3.2 Framework-to-Group mapping from 36 to 50 frameworks maintaining alphabetical order within groups and marking new frameworks with †; updated §2.2 Group-to-Hiddens linkage with expanded hiddenness generators for all groups reflecting new frameworks; updated §4.3 routing decision tree (A2–A5, B1, B3) to include new frameworks at each decision node; updated §4.3.3 default deep/light mapping table to include new frameworks; added new glossary section §11.8 with one-line operational definitions of all 14 new frameworks extracted from their LLM Extract documents; renumbered subsequent glossary sections (§11.8 Quality controls → §11.9, §11.9 Prompt discipline → §11.10); updated framework count from 36 to 50 throughout document including lines 14, 34, 38, 909, 2520, 2700. (Revised: Anthropic Claude Opus 4.6) |
| v2.5 | 2026-04-03 | Renumbered §5.1 Rapid Protocol steps from 0–6 to 1–7 (establishing the case question is an action, not a precondition); updated all cross-references (§D.11 node N2R, Appendix G static rendering, §11.4 glossary, depth×speed matrix). Updated HTML companion to v2.5 (Tier 2 labels made explicit at §7.2 references; §D.11/§D.12 added to Appendix D node; PD-10 corrected to "Canonical source rule"; Introduction reference added to entry node). (Revised: Anthropic Claude Opus 4.6) |
| v2.4 (Draft) | 2026-04-02 | Added Introduction section between the At-a-Glance summary and §1, covering: what the Analytical Series is and why it exists (36 frameworks, 6 groups, visibility failures as the organising concept); what the Operating Guide does within the series (orchestration layer for routing, sequencing, depth, quality controls, and closure); how to use the guide to discover Hiddens (operational rhythm from scenario entry through Tier 1 scanning, routing, execution, testing, re-scanning, and bounded closure); and LLM execution guidance (self-contained protocol-level execution, with framework documents needed for Full Depth). (Revised: Anthropic Claude Opus 4.6) |
| v2.3 (Draft) | 2026-04-02 | Added §D.12 Architectural Notes and Design Rationale: §D.12.1 explains why the Operating Guide's structure (invariant layers, iterative loops, lookup tables, cross-cutting constraints) cannot be represented as a single decision tree and why §D.11 serves as a routing spine instead; §D.12.2 provides an LLM-executability assessment documenting what the Operating Guide can execute self-contained (protocol-level: routing, Tier 1 scans, artefact production, quality controls, closure) versus what requires external framework documents (Full Depth Framework Execution using individual framework taxonomies). (Revised: Anthropic Claude Opus 4.6) |
| v2.2 (Draft) | 2026-04-02 | Expanded Appendix G from a reference stub into a full static Markdown rendering of the Visual Decision Tree (§G.4–G.12): invariant layer table, 5 phases with all node details, cross-cutting LLM governance, post-investigation governance, and usage notes. Operating Guide is now self-contained; HTML companion file retained for interactive use. Fixed §D.10 positioning (was after Appendix E header; moved to correct sequence D.9 → D.10 → D.11). Fixed 3 incorrect scan names in HTML companion (Family B: Frame Blindness → Positional Blindness, Measurement Distortion → Cascade Discovery, Evidence Corruption → Uncertainty Masking) and restored Evidence Corruption to Family D. (Revised: Anthropic Claude Opus 4.6) |
| v2.1 (Draft) | 2026-04-02 | Added §D.11 LLM-Navigable Compact Decision Tree (8 nodes, invariant layer, traversal summary, section-to-node mapping, depth×speed matrix) to Appendix D; added Appendix G Visual Decision Tree as reference to the interactive HTML companion file. (Integrated: Anthropic Claude Opus 4.6) |
| v2.0 (Draft) | 2026-04-02 | Consolidated §11 Glossary: expanded from 12 terms to ~80 terms organised into 9 subsections (Core definitions, Group system, Run modes, Protocols, Artefacts, Hiddens discipline, Targeted scans, Quality controls, Prompt discipline); added all §1.3 core definitions, all 13 scan names with routes, all 6 Hiddens meta-categories, anti-theatre rule, F/I/A/U tag definitions, and cross-references to §D.10. (Revised: Anthropic Claude Opus 4.6) |
| v1.9 (Draft) | 2026-04-01 | Integrated §7.5 Targeted Hiddens Discovery Scans (v2.0) into the Operating Guide: 13 cross-framework routing patterns organised into 4 families covering 33/36 frameworks; narrative introductions for human readers; LLM Execution Adapter with pseudocode, gate questions, per-step output tables, F/I/A/U tagging, and depth triggers; triage matrix; scan interaction map; glossary additions. (Integrated: Anthropic Claude Opus 4.6) |
| v1.7 (Draft) | 2026-03-29 | Added Framework of Knowledge (G5 Epistemics / G4 Meaning / Stage: Cross-cutting) to §3.2 Framework-to-Group mapping; updated series count from 34 to 35 frameworks throughout. Knowledge integration rows added to all 34 existing frameworks' §7.3 tables. (Revised: Anthropic Claude Opus 4.6) |
| v1.6 (Draft) | 2026-03-28 | Added Framework of Metrics (G5 Epistemics / G6 Action & Control / Stage: Cross-cutting) to §3.2 Framework-to-Group mapping; updated series count from 33 to 34 frameworks throughout. (Revised: Anthropic Claude Opus 4.6) |
| v1.5 (Draft) | 2026-03-27 | Added Framework of Beliefs (G5 Epistemics / G4 Meaning / Stage: Middle) to §3.2 Framework-to-Group mapping; updated series count from 32 to 33 frameworks throughout. (Revised: Anthropic Claude Sonnet 4.6) |
| v1.4 (Draft) | 2025-12-18 | Added Shallow/Deep mode selection gate; replaced Rapid Run Mode with Rapid Run Mode; added Canonical Orchestrator Prompts for Rapid Run Mode and Investigative Run Mode with Phase numbering starting at 1; clarified coverage without exhaustiveness and No-Early-Exclusion Rule; retained escalation logic for full-spectrum runs (A6) and mandatory pre-closure re-scan; added consolidated operator mental model for Rapid Run Mode vs Investigative Run Mode and Tier 1–3 depth control; terminology refactor to prevent conflation (Rapid Run Mode / Investigative Run Mode; Full Depth / Light Depth Framework Execution); added invariant line; added Appendix D glossary. |
| v1.0 (Draft) | 2025-12-17 | First full version of the series-level operating guide: group system G1–G6, standard protocols, artefact schemas, and Hiddens integration discipline. |
| v1.1 (Draft) | 2025-12-17 | Added canonical Prompt Discipline Rules, canonical output contract, and the canonical source rule to prevent fragmentation across framework excerpts. |
| v1.2 (Draft) | 2025-12-17 | Added compact routing decision tree (scenario features → minimum group coverage + deep/light) and a unified iterative investigation loop (algorithmic control) to reduce variance and premature closure. |
| v1.3 (Draft) | 2025-12-17 | Added “Orchestrator Prompt (Canonical) — v1.2” (standard + Rapid Run Mode/Investigative Run Mode/post-failure variants) with built-in compliance self-check; placed in Appendix D as audited operating doctrine. |

## 12.2 Integration Notes (optional)
- This guide is designed to be compatible with the Master Rewrite Template’s invariant Hiddens cross-check sections and protocol-driven deliverables.
- The framework-to-group mapping is an initial navigation assignment and should be refined based on practitioner feedback and case learning.

---

## Appendices (optional but recommended)

### Appendix A — Group Coverage Matrix (template)
| Group | Substantively examined? (Y/N/Partial) | Key findings | Suspected hiddens | Next tests |
|---|---:|---|---|---|
| G1 |  |  |  |  |
| G2 |  |  |  |  |
| G3 |  |  |  |  |
| G4 |  |  |  |  |
| G5 |  |  |  |  |
| G6 |  |  |  |  |

### Appendix B — Investigation Plan (template)
| Workstream | Owner | Frameworks | Inputs | Outputs | Timebox | Risks / hiddens to watch |
|---|---|---|---|---|---:|---|
| Framing |  |  |  |  |  |  |
| Mechanism |  |  |  |  |  |  |
| Agency |  |  |  |  |  |  |
| Meaning |  |  |  |  |  |  |
| Epistemics |  |  |  |  |  |  |
| Action & Control |  |  |  |  |  |  |

### Appendix C — Decision Record (template)
| Field | Content |
|---|---|
| Decision |  |
| Options considered |  |
| Rationale |  |
| Key assumptions |  |
| Evidence basis |  |
| Uncertainties |  |
| Residual hiddens |  |
| Monitoring / triggers |  |
| Owner / review date |  |
---

# Appendix D — LLM Execution Mode (Adapter Layer)

## D.1 Purpose
This appendix defines the **authoritative, versioned standard** for using LLMs with the Analytical Series of Frameworks to discover, uncover, and understand **Hiddens** in complex scenarios (including post-failure investigations). It provides a single “truth discipline” so that outputs are comparable, auditable, and resistant to premature narrative closure.

## D.2 Ruleset identification and applicability
| Field | Value |
|---|---|
| Ruleset name | Prompt Discipline Rules (Canonical) |
| Ruleset version | **v1.4** |
P25-12-18 |
| Applies to | All LLM-assisted uses of the Analytical Series (Rapid Run Mode, Investigative Run Mode, post-failure investigation, adversarial concealment-aware analysis) |
| Primary objective | Convert hiddenness into explicit unknowns + tests + evidence acquisition, then into controlled decisions/interventions where appropriate |
| Relationship to frameworks | Framework documents may include a short excerpt, but **must not alter these canonical rules** |

## D.3 Prompt Discipline Rules (Canonical) — Version 1.4
### D.3.1 Canonical rules (table-first)
| Rule ID | Rule | Operational requirement (what the LLM must do) | Minimum artefact impact |
|---|---|---|---|
| PD-01 | **Do not invent facts** | If a datum is not provided, do not fabricate it. Record as **U (Unknown)** and generate an information request and/or probe/test to surface it. | Hiddens Register, Evidence Register, Hypotheses & Tests |
| PD-02 | **Tag statements as F/I/A/U** | Every material claim and every register row must include a tag: **F** Fact, **I** Inference, **A** Assumption, **U** Unknown. Do not downgrade a claim’s uncertainty level without new evidence. | All registers and decision outputs |
| PD-03 | **Separate observation from interpretation** | Distinguish “what is observed/reported” from “what it means.” Where interpretation is required, label as **I** and list plausible alternatives. | Evidence Register, Diagnosis outputs |
| PD-04 | **Evidence/provenance required for confidence** | Any confidence statement must cite an Evidence Register entry (or be marked **A/I**). If evidence is weak, state limitations explicitly and propose the next-best evidence to obtain. | Evidence Register, Closure discipline |
| PD-05 | **Prefer tests over stories** | When uncertain, prioritise proposing concrete tests, probes, or falsifiers over elaborating explanatory narratives. | Hypotheses & Tests, Investigation Plan |
| PD-06 | **Track and preserve disagreement** | Conflicting accounts are treated as potential Hiddens until resolved. Record contradictions, identify who benefits from each version, and propose resolution steps. | Evidence Register, Hiddens Register |
| PD-07 | **Default to hiddenness in complex scenarios** | Assume Hiddens exist. Run the Tier 1 scan early and re-run at phase gates (after mechanism mapping, after stakeholder mapping, before closure). | Group Coverage Matrix, Hiddens Register |
| PD-08 | **Do not close prematurely** | If closure criteria are not met, output a **non-closure**: what is known, what remains hidden, why it remains hidden, and what would be required to close. | Closure statement + Residual Unknowns |
| PD-09 | **Make residual hiddenness explicit** | End every run with a Residual Unknowns section, each item linked to: mechanism, impact, detectability, and next action. | Residual Unknowns |
| PD-10 | **Canonical source rule** | The Operating Guide is authoritative. Framework excerpts must either (a) quote the canonical excerpt verbatim, or (b) point to it without modification. Changes are made here first and propagated mechanically. | Governance + template compliance |

### D.3.2 F/I/A/U tagging definitions (required)
| Tag | Meaning | Allowed usage | Example (generic) |
|---|---|---|---|
| **F** | Fact | Directly observed, documented, or explicitly provided in the scenario prompt or attached artefacts. | “System X logged error code Y at 02:14.” |
| **I** | Inference | Reasoned conclusion drawn from facts; must note uncertainty and alternatives if material. | “The timing suggests the failure propagated from subsystem A.” |
| **A** | Assumption | Unverified claim adopted temporarily to proceed; must be testable and flagged as such. | “Assume patch Z was applied to all nodes.” |
| **U** | Unknown | Not provided or not currently observable/confirmable; must generate a probe/test or information request. | “Exact coupling path between services is unknown.” |

### D.3.3 Evidence and provenance requirements (minimum standard)
| Item type | Provenance requirement | Where recorded |
|---|---|---|
| Key factual claims (F) | Source type + identifier (log excerpt, email, report, interview, metric, ticket, policy, etc.) | Evidence Register |
| Inferences (I) | Explicit link to supporting facts + uncertainty note | Evidence Register + Hypotheses & Tests |
| Assumptions (A) | Rationale + test plan + expiry/review trigger | Assumptions Register + Hypotheses & Tests |
| Unknowns (U) | Mechanism of hiddenness + proposed probe/test + required artefact | Hiddens Register + Information Requests |
| Decisions / recommendations | Decision record with evidence basis + residual unknowns + risk note | Decision Record + Residual Unknowns |

### D.3.4 Handling missing information (U) (decision discipline)
| If the analysis needs… | And it is not in the prompt… | Then the LLM must… |
|---|---|---|
| A value to populate a register field | Missing | Mark **U**, add an information request, propose a probe/test, and proceed using ranges/branches if needed. |
| A stakeholder intention/motive | Missing | Mark **U**, propose interview questions and triangulation sources; do not assert motive as fact. |
| A causal mechanism | Under-determined | Maintain multiple hypotheses; propose discriminating tests; avoid single-root-cause closure. |
| A control/governance fact | Not evidenced | Mark **U** and request policy, audit, and “work-as-done” artefacts; treat “paper controls” as unverified until sampled. |

### D.3.5 Closure criteria and Residual Unknowns (mandatory)
| Closure element | Minimum requirement |
|---|---|
| Evidence basis | Material claims linked to Evidence Register; weak points explicitly flagged |
| Competing hypotheses | At least one alternative hypothesis considered for each high-impact claim |
| Hiddens coverage | Tier 1 scan completed at least twice (early + pre-closure); Tier 2 mapping for top Hiddens |
| Residual Unknowns | Listed with mechanism, impact, detectability, owner, and next action |
| Non-closure option | If criteria unmet: produce non-closure with explicit close-out requirements |

## D.4 Output contract (deliverables)
### D.4.1 Required registers and checklists (canonical minimum)
| Deliverable | Required in all modes? | Notes / minimum content |
|---|---:|---|
| Group Coverage Matrix (G1–G6) | Yes | At least: coverage status, key questions, major gaps |
| Hiddens Register | Yes | At least: candidate hidden, mechanism, impact, detectability, F/I/A/U, probe/test, required artefact |
| Evidence Register (Evidence Ledger) | Yes | At least: claim, evidence, quality, gaps, next evidence |
| Hypotheses & Tests Backlog | Yes | At least: hypothesis, observations if true/false, test, priority, dependencies |
| Investigation Plan | Recommended (all modes); Required (post-failure) | Sequenced actions, owners, timing, artefacts requested |
| Decision Record | Required when recommendations are made | Includes evidence basis and residual unknowns |

### D.4.2 Minimum tables per run mode
| Run mode | Minimum outputs (tables) | Typical use |
|---|---|---|
| **Rapid Rapid Run Mode** | Coverage Matrix + Hiddens Register + Evidence Register + Hypotheses/Tests (top 5–10) | Fast sensemaking, identify what is most hidden/most dangerous |
| **Investigative Run Mode analysis** | All canonical deliverables + expanded hypotheses/tests + deeper Tier 2 mapping | Complex systems analysis, multiple stakeholders, ambiguity |
| **Post-failure investigation** | All canonical deliverables + Investigation Plan + Decision Record (if actions proposed) + explicit non-closure option | Incident/accident inquiry, high stakes, potential culpability |

## D.5 Routing logic (minimum group coverage + deep/light selection)
This appendix provides the **canonical routing summary**. Detailed routing tables and depth guidance are in **Section 4** (including the compact decision tree in **Section 4.3**).

### D.5.1 Minimum group coverage rules (canonical)
| Scenario feature | Minimum group coverage (must include) | Rationale (Hiddens lens) |
|---|---|---|
| Any materially consequential failure | **G1 + G2 + G5** | Prevent misframing, mechanism-only closure, and weak epistemics |
| Multi-stakeholder conflict or incentives suspected | Add **G3** | Power/incentive filters commonly produce concealment and distortion |
| Narrative conflict / contested legitimacy / communications breakdown | Add **G4** | Story and signalling systems generate mirage/echo and reporting failure |
| Recommendations include controls/governance changes | Add **G6** | Drift, control reality gap, and implementation failures are key hidden generators |
| Adversarial or intentional concealment plausible | **G1–G6** (full) | Hiddenness likely strategic and multi-layered |

### D.5.2 Deep vs light framework selection (canonical)
Use the depth logic from **Section 4.2**. As a minimum:
- Run **deep** on the frameworks in the *minimum group coverage* set for the scenario.
- Run **light** (scan-level) on the remaining groups to prevent omission-by-lens.
- Escalate to Tier 3 (full Hiddens run) when: high stakes + low evidence quality + contested accounts, or repeated near-miss patterns.



### D.5.3 Compact routing decision tree (canonical pointer)
- **Canonical decision tree:** Section **4.3** (Compact routing decision tree).
- **Required use:** Apply at **Start-of-Run** and **Pre-Closure** for all materially consequential cases.
- **Minimum output:** Routing statement + minimum group coverage + Full Depth Framework Execution / Light Depth Framework Execution plan (per 4.3.2).


## D.6 Run modes (Rapid Run Mode vs Investigative Run Mode + post-failure overlay)
This Operating Guide uses two primary depth modes, selected **after the scenario is provided** (see §D.9.2 Mode Selection Gate).

### D.6.1 Mode definitions
| Mode | Objective | Primary protocol reference | Typical completion condition |
|---|---|---|---|
| Rapid Run Mode | Coverage-first scan: surface candidate Hiddens, evidence gaps, and next-best probes; prevent premature narrative closure | §5.1 + §5.0 (light application) | Top Hiddens + tests/probes + information requests + escalation recommendation delivered |
| Investigative Run Mode | Disciplined depth: selective deep execution on a routed subset, Light Depth Framework Execution elsewhere (scan-level/MVE), repeated Tier 1 scans, evidence-gated reasoning, and deeper mapping for top Hiddens | §5.0 + §5.2/§5.3 as applicable | Deep on minimum group coverage + routed frameworks; scan-level across remaining groups; remediation + monitoring + residual unknowns delivered (or non-closure with requirements) |

### D.6.2 Canonical clarification: “coverage without exhaustiveness”
**No.** The Canonical Orchestrator Prompt (Investigative Run Mode) **must not** require cycling through all frameworks in the series as default behaviour.

The Operating Guide’s design intent is **coverage without exhaustiveness**:
- Run **deep** only on the frameworks required by **minimum group coverage** and the **routing decision tree** for the specific case.
- Run **light (scan-level)** across the remaining groups/frameworks to prevent omission-by-lens, without fully populating every taxonomy/table.
- Iterate using the unified loop (**Route → Execute → Test → Re-scan → Decide/Close**) and expand coverage only when triggers fire.

### D.6.3 What “Investigative Run Mode” means in this operating model
“Investigative Run Mode” refers to **depth of reasoning and discipline**, not “run every framework”:
- expanded hypotheses and discriminating tests,
- deeper Tier 2 mapping for top Hiddens,
- evidence-gated confidence and explicit residual unknowns.

### D.6.4 No-Early-Exclusion Rule (lens inclusion, depth Rapid Run Mode)
To prevent process-induced hiddens, apply a **No-Early-Exclusion Rule**:
- Every group (G1–G6) is executed at least once at **scan-level** before prioritisation or closure.
- Depth is allocated **after** the Light Depth Framework Execution sweep (scan-level/MVE), based on what the scan reveals (impact, plausibility, detectability, decision sensitivity), not on premature assumptions.

### D.6.5 When a near-full sweep is warranted
A “full-spectrum” run (close to all groups, potentially many frameworks) is reserved for specific routing outcomes—most notably when **adversarial intent / intentional concealment is plausible (decision tree A6)**—and for escalation triggers such as:
- high stakes + low evidence quality + contested accounts,
- repeated “too clean” narratives or contradictory evidence,
- high-impact residual unknowns (decision-critical),
- governance implications where recommendations change controls/accountability (adds G6 deep).

### D.6.6 Practical implication for orchestration (minimum Investigative Run Mode contract)
A correct Investigative Run Mode run produces (at minimum):
- a routing statement,
- minimum group coverage,
- a Full Depth Framework Execution / Light Depth Framework Execution plan (what goes Full Depth Framework Execution vs Light Depth Framework Execution, and why),
then executes deeply on that subset and Light Depth Framework Execution elsewhere (scan-level/MVE).

This prevents single-lens closure while avoiding performative completeness.




### D.6.7 Why Rapid Run Mode and Investigative Run Mode exist (necessity + benefits)
This Operating Guide includes **Rapid Run Mode** and **Investigative Run Mode** to eliminate two recurrent operator/LLM failure modes that otherwise degrade Hiddens discovery.

**Failure mode 1 — Exhaustiveness-by-default (noise-induced blindspots):**
- “Deep” is misread as “run everything,” producing high-volume outputs with weak evidence discipline, low test density, and contradiction sprawl.
- Result: the analysis becomes operationally unfinishable and paradoxically **less** reliable, because discriminating tests and provenance controls are overwhelmed.

**Failure mode 2 — Omission-by-lens (process-induced hiddens):**
- “Triage” is misread as “skip lenses,” leading to early exclusion of groups/frameworks and premature narrative closure.
- Result: the analysis itself becomes a generator of Hiddens (hiddenness caused by the method).

**What the modes add to the analytical approach (operational benefits):**
1) **Explicit depth governance:** depth is allocated deliberately instead of drifting into either exhaustiveness or omission.
2) **Stable comparability:** outputs are standardised by mode and tier expectations (auditable, repeatable runs).
3) **Protected lens coverage:** scan-level touch across all groups prevents omission-by-lens, even under time constraints.
4) **Evidence-first execution:** both modes enforce evidence provenance, uncertainty management, and disconfirming tests.
5) **Controlled escalation:** Tier 1–3 scans provide a clear escalation ladder (when to deepen, and why).

**Selection rule (operator-facing):**
- Choose **Rapid Run Mode** when you need a rapid, timeboxed output that surfaces candidate Hiddens and the next-best evidence actions.
- Choose **Investigative Run Mode** when you need a defensible diagnosis and remediation options under uncertainty, or when stakes demand deeper testing and governance implications are likely.

#### D.6.7.1 Mode selection guidance (decision table)
| Condition | Default mode | Rationale |
|---|---|---|
| Unknown problem shape; need to avoid premature closure | Rapid Run Mode | Produces a ranked Hidden shortlist + probes without over-committing to a story |
| Tight timebox (≤ 3 hours) or early triage of an investigation portfolio | Rapid Run Mode | Maximises coverage and actionable next steps; preserves escalation logic |
| High consequence (safety/security/legal/mission-critical) | Investigative Run Mode | Requires evidence-gated confidence, differential hypotheses, and deeper mapping |
| Post-failure investigation where “why it was not seen” matters | Investigative Run Mode | Requires iterative testing + governance/control implications and residual unknown governance |
| Evidence weak/contested; contradictory accounts | Investigative Run Mode (or Shallow→Deep) | Shallow can surface the discriminator set; Deep executes tests and tightens provenance |
| Concealment/adversarial intent plausible (routing A6) | Investigative Run Mode with escalation | May justify near-full-spectrum coverage and Tier 3 Hiddens escalation |
| Recommendations will change controls/accountability/governance | Investigative Run Mode | Requires Decision Record, governance mapping, and monitored residual unknowns |
| Operator explicitly wants “next actions only” | Rapid Run Mode | Output contract emphasises probes, info requests, escalation recommendation |

#### D.6.7.2 Non-negotiable invariants (apply in both modes)
- Tier 1 Hiddens scan is run **at least twice** (early + pre-closure).
- **Invariant:** Do not conflate **Run Mode** (Rapid Run Mode / Investigative Run Mode) with **Framework Execution Depth** (Full Depth Framework Execution / Light Depth Framework Execution).
- All material claims and register rows are tagged **F/I/A/U**.
- Missing information is recorded as **Unknown**, generating probes/tests and information requests.
- Closure is **bounded**: residual unknowns are explicit, owned, and monitored.


### D.6.8 Operational behaviour by mode (what the LLM actually does)
This subsection provides the consolidated operator mental model for how the LLM behaves in each mode, and how Tier 1–3 Hiddens scans function as depth controls.

| Mode | Primary purpose | What the LLM prioritises | Typical Tier usage | Completion output |
|---|---|---|---|---|
| Rapid Run Mode | Coverage-first scan to prevent premature closure | Candidate Hiddens, evidence gaps, next-best probes/tests, escalation recommendation | Tier 1 twice (early + pre-closure); Tier 2 optional for top 1–3 if timeboxed | Top Hiddens shortlist + probes/tests + information requests + residual unknowns + “stay shallow vs go deep” |
| Investigative Run Mode | Disciplined depth on routed subset + Light Depth Framework Execution elsewhere (scan-level/MVE) | Evidence-gated hypotheses, discriminating tests, selective deep execution, remediation/detection design | Tier 1 twice (mandatory); Tier 2 for top Hiddens; Tier 3 only when triggers fire | Routed deep outputs + Light Depth Framework Execution sweep (scan-level/MVE) + Tier 2 mapping + remediation/monitoring + residual unknowns (or non-closure requirements) |

### D.6.9 Operational sequence by mode (step-by-step)

#### Rapid Run Mode (timeboxed, coverage-first)
Rapid Run Mode is a timeboxed, coverage-first scan designed to prevent premature closure and surface what matters next.

What the LLM does, in sequence:
1) **Baselines discipline + artefacts**
   - Creates (at minimum) the four required tables: **Group Coverage Matrix (G1–G6)**, **Hiddens Register**, **Evidence Register**, **Hypotheses & Tests Backlog**.
   - Adds **Information Requests** if gaps are material.
2) **Runs Tier 1 (first pass)**
   - Rapidly generates a ranked shortlist of candidate Hiddens, including mechanisms and “what would show this is true?” probes.
3) **Routes lightly (within the timebox)**
   - Applies routing logic to identify which groups/frameworks deserve “most-attended” effort *within the shallow timebox*.
4) **Performs Light Depth Framework Execution sweep (scan-level/MVE) across all groups (anti-hiddens)**
   - Touches **G1–G6** to avoid omission-by-lens.
   - Records only **high-signal** candidates, contradictions, and missing-information triggers.
5) **Runs Tier 1 again (pre-closure)**
   - Second pass explicitly asks what class of hiddenness might still be missed.
6) **Outputs next-best actions**
   - Next 5 probes/evidence requests, residual unknowns (owned), and an explicit recommendation: **stay shallow** or **escalate to deep**.

Operational norm:
- Rapid Run Mode typically uses **Tier 1 (twice)**.
- Rapid Run Mode typically does **not** perform Tier 2 mapping or Tier 3 taxonomy runs unless scope/time is explicitly expanded.

#### Investigative Run Mode (disciplined depth on a routed subset)
Investigative Run Mode is disciplined depth: selective deep execution on a routed subset, Light Depth Framework Execution elsewhere (scan-level/MVE), iterative testing, and evidence-gated confidence.

What the LLM does, in sequence:
1) **Baselines artefacts (as in shallow)**
   - Adds an **Investigation Plan** when the run is non-trivial.
   - Creates a **Decision Record** if recommendations are likely.
2) **Runs Tier 1 (first pass) + builds a differential**
   - Establishes 2–3 competing hypotheses for material outcomes (prevents single-story closure).
3) **Routes and allocates depth**
   - Produces: routing statement, minimum group coverage, and an explicit **Full Depth Framework Execution vs Light Depth Framework Execution plan** (what goes deep, and why).
4) **Executes at Full Depth on the routed subset**
   - Populates core tables where appropriate, tightens evidence provenance, expands discriminating tests/probes.
5) **Executes Light Depth Framework Execution elsewhere (scan-level/MVE) (anti-hiddens)**
   - Touches all groups to prevent omission-by-lens, but does not “fill every table”.
6) **Converts Unknowns into tests**
   - Evidence acquisition plan: owners, discriminators, expected outcomes, and what would falsify key claims.
7) **Runs Tier 1 again (pre-closure)**
   - Second pass is an explicit “what would we miss if we’re wrong?” check.
8) **Runs Tier 2 mapping for top Hiddens**
   - Designs detection and remediation interfaces for the top candidates.
9) **Escalates to Tier 3 only if triggers fire**
   - High stakes, concealment plausible, contradictions persist, cascades suspected, etc.
10) **Closes boundedly or refuses closure**
   - If closure is not justified, produces a **non-closure** output with explicit close-out requirements.

Operational norm:
- Investigative Run Mode typically uses **Tier 1 (twice)**, **Tier 2** (for top Hiddens), **Tier 3** (only by trigger).

### D.6.10 Tiered Hiddens scans as the depth-control system (Tier 1–3)

#### Tier 1 scan (mandatory visibility audit)
Tier 1 is the mandatory “visibility audit” and the primary anti-hiddens control.

What the LLM does in Tier 1:
- Scans the scenario through six meta-categories:
  - **Perceptual**
  - **Systemic**
  - **Informational**
  - **Temporal**
  - **Relational**
  - **Ontological**
- Produces a ranked shortlist of candidate Hiddens, each with:
  - the hiding mechanism (how it stays hidden),
  - consequence (why it matters),
  - detectability (what signal/test would reveal it),
  - an initial reducibility judgement (reducible vs must be managed/robustified).

Key operational rule:
- Tier 1 is run **at least twice** (early + pre-closure), in both Rapid Run Mode and Investigative Run Mode modes.

#### Tier 2 scan (structured deepening of top Hiddens)
Tier 2 is structured deepening of the top Hiddens (not an attempt to run every framework deeply).

What the LLM does in Tier 2:
- Selects a small set of top candidates (typically ~5–15, depending on scope).
- Builds a “working model” per Hidden:
  - where it lives (system layer, interface, team/process, governance),
  - how it’s produced (mechanism chain),
  - why it persists (incentives/power/comms/narratives if relevant),
  - what evidence would confirm/disconfirm it,
  - what detection interface makes it observable,
  - what remediation interface reduces harm (surface/contain/eliminate).
- Integrates duplicates and clusters by mechanism to avoid list-noise.

Where Tier 2 is used:
- Standard in Investigative Run Mode (for top Hiddens).
- Optional in Rapid Run Mode if time permits, typically “Tier 2 for the top 1–3” rather than a full Tier 2 pass.

#### Tier 3 scan (full-spectrum Hiddens escalation)
Tier 3 is the full, high-rigor Hiddens run (deep taxonomy coverage + tighter evidence discipline). It is an escalation mode.

What the LLM does in Tier 3:
- Expands beyond Tier 1 categories into the full Hiddens taxonomy (full-spectrum exploration).
- Tightens controls:
  - stronger provenance requirements,
  - more explicit competing hypotheses,
  - more rigorous disconfirming tests,
  - concealment vectors and independent corroboration paths (when adversarial intent is plausible).
- Broadens coverage toward near-full group execution only when justified (e.g., adversarial concealment branch, repeated contradictions, decision-critical residual unknowns).

Where Tier 3 is used:
- Not default for Investigative Run Mode.
- Triggered by escalation conditions (high stakes, concealment, contradictions, cascade risk, repeat failure after intervention, decision-critical residual unknowns).

### D.6.11 One practical way to think about it (operator summary)
- Rapid Run Mode answers: **“What might we be missing, and what should we do next to find out?”**  
  (Tier 1 twice + actionable probes)
- Investigative Run Mode answers: **“What’s the best current explanation that is defensible under uncertainty, what would disconfirm it, and what changes reduce recurrence?”**  
  (Tier 1 twice + Tier 2 for top Hiddens + Tier 3 only by trigger)


## D.7 Standard system instruction block (copy/paste)
Use the following as a system or operator instruction block when running an LLM-assisted analysis.

> You are applying the Analytical Series of Frameworks to discover, uncover, and understand Hiddens in a complex scenario.  
> Follow the Operating Guide Prompt Discipline Rules (Canonical) v1.4: do not invent facts; tag claims and register rows as F/I/A/U; separate observation from interpretation; preserve evidence provenance; prefer tests over stories; track disagreement; do not close prematurely; always output residual unknowns with next actions.  
> Produce outputs as Markdown tables using the Output Contract (Coverage Matrix, Hiddens Register, Evidence Register, Hypotheses & Tests; add Investigation Plan and Decision Record when applicable).  
> If information is missing, mark it Unknown and propose probes/tests and information requests.

## D.8 Prompt pack (operator-facing)
### D.8.1 Rapid Rapid Run Mode
**Prompt add-on:**
- Populate the four minimum tables (Coverage, Hiddens, Evidence, Hypotheses/Tests).  
- Limit hypotheses to the top 5–10 by (impact × plausibility × detectability leverage).  
- End with “Next 5 actions (evidence acquisition)” and “Residual Unknowns”.

### D.8.2 Post-failure hidden discovery (investigation mode)
**Prompt add-on:**
- Assume strategic distortion is possible; record conflicting accounts explicitly.  
- For each major hypothesis, list: what we would observe if true vs if false.  
- Produce a sequenced Investigation Plan with owners (roles), artefacts requested, and expected discriminators.

### D.8.3 Adversarial / concealment-aware mode
**Prompt add-on:**
- Identify who benefits from each account.  
- Add a “Concealment vectors” column to the Hiddens Register (power, incentives, reputational risk, liability, operational convenience).  
- Propose at least one independent corroboration path per high-impact claim.

### D.8.4 Intervention design mode
**Prompt add-on:**
- Convert each top Hidden into: (a) detection interface, (b) governance/control change, and (c) learning loop.  
- For each intervention, state: failure modes (including drift into failure), monitoring indicators, and residual hiddenness.

## D.9 Orchestrator Prompts (Canonical) — Version 1.4

### D.9.1 What to paste where (operator instruction)
| Field | What to paste | Notes |
|---|---|---|
| Scenario | Paste the scenario narrative under “Scenario:” | Include timeline, actors, objectives, failure/concern, constraints. |
| Available evidence | Paste artefacts under “Available evidence:” | Logs, emails, reports, interviews, metrics, policies, diagrams, tickets. If none, write “None provided”. |
| Constraints | Paste constraints under “Constraints:” | Timebox, decision deadline, scope exclusions, confidentiality, resourcing limits. |

---

### D.9.2 Orchestrator Prompt (Canonical) — v1.4  **[MODE SELECTION GATE]**
Paste this prompt when you want the LLM to **request a user choice of Rapid Run Mode vs Investigative Run Mode after the scenario is provided**.

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
   - Option A: Rapid Run Mode (timeboxed scan; coverage-first; §5.1)
   - Option B: Investigative Run Mode (selective deep execution + Light Depth Framework Execution elsewhere (scan-level/MVE); §5.0 + §5.2/§5.3)
2) Briefly explain the practical difference:
   - Investigative Run Mode does NOT mean “run every framework deeply”; it means deeper reasoning, discriminating tests, Tier 2 mapping for top Hiddens, and evidence-gated confidence with explicit residual unknowns.
3) Request any missing constraint needed to run correctly (timebox, decision deadline, exclusions).
4) Stop and wait for the user’s reply (“Rapid” or “Investigative”).

After the user selects, run the corresponding Canonical Orchestrator Prompt in Appendix D.9.3 (Rapid Run Mode) or D.9.4 (Investigative Run Mode).
```

---

### D.9.3 Canonical Orchestrator Prompt (Rapid Run Mode) — v1.4  **[Rapid Run Mode]**
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
- In shallow mode, “deep” means “most-attended” (still timeboxed). Do not fully populate every framework table.

Phase 4 — Scan-level coverage (anti-hiddens sweep)
- Run scan-level checks across all groups/frameworks (touch every lens once).
- Record only:
  - high-signal candidate Hiddens,
  - contradictions,
  - missing-information triggers,
  - immediate stabilisation risks (if applicable).

Phase 5 — Pre-closure Tier 1 re-scan + next actions
- Re-run Tier 1 scan (second pass) explicitly asking:
  “Given what we now believe, what class of hiddenness might we still be missing?”
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

---

### D.9.4 Canonical Orchestrator Prompt (Investigative Run Mode) — v1.4  **[Investigative Run Mode]**
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
- Investigative Run Mode does NOT mean “run every framework deeply”.
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
  - populate the framework’s core tables as applicable,
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

---

### D.9.5 Optional overlays (invoke by routing)
**Adversarial / concealment-aware overlay:** if concealment is plausible, add:
- who benefits from each account,
- concealment vectors per high-impact Hidden,
- independent corroboration paths per high-impact claim.

**Post-failure overlay:** if a consequential failure/near-miss occurred, strengthen:
- evidence and uncertainty discipline,
- alternative hypotheses and disconfirming tests,
- governance/control drift checks when recommendations change accountability or controls.


## D.10 Glossary (Appendix D — LLM Adapter Layer)
This glossary is authoritative for LLM execution semantics. It exists to prevent semantic drift, conflation, and inconsistent operator interpretation.

### D.10.1 Core execution terms (mandatory)
| Term | Definition (operational) | Notes / anti-confusion guardrail |
|---|---|---|
| Run Mode | The overall whole-run execution posture selected after the scenario is provided. | **Do not conflate** with Framework Execution Depth. |
| Rapid Run Mode | Formerly “Shallow-dive”. A timeboxed, coverage-first run to surface candidate Hiddens, evidence gaps, and next-best probes/tests; ends with an escalation recommendation. | Typically Tier 1 twice; Tier 2 optional for top 1–3 if timeboxed. |
| Investigative Run Mode | Formerly “Deep-dive”. A disciplined investigative run: selective Full Depth Framework Execution on a routed subset, Light Depth Framework Execution elsewhere; iterative; evidence-gated. | Typically Tier 1 twice + Tier 2 for top Hiddens; Tier 3 only by trigger. |
| Framework Execution Depth | The per-framework intensity level chosen by routing and timebox. | Applies inside either Run Mode. |
| Full Depth Framework Execution | Full execution of a framework: populate core tables as applicable; develop mechanisms; expand tests; integrate evidence; produce structured outputs. | Used on the routed subset; does not imply “all frameworks”. |
| Light Depth Framework Execution | Scan-level/MVE execution of a framework: identify high-signal hits, candidate Hiddens, contradictions, and missing-information triggers without full table population. | Used across remaining groups to prevent omission-by-lens. |
| MVE / scan-level | Minimum Viable Execution: the smallest execution that still yields meaningful signal and Hiddens candidates. | Equivalent in practice to Light Depth Framework Execution. |
| Tier 1 (Hiddens) | Six-category visibility audit (Perceptual/Systemic/Informational/Temporal/Relational/Ontological). Mandatory early and pre-closure (min twice). | Primary anti-hiddens control. |
| Tier 2 (Hiddens) | Structured deepening of the top Hiddens: mechanism chain, location, persistence drivers, discriminators, detection/remediation interfaces. | Not “run everything”; focuses on top candidates. |
| Tier 3 (Hiddens) | Escalation: full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests; may justify near-full group coverage when warranted. | Triggered only by escalation conditions. |
| Routing statement | Explicit record of routing outcomes and why: stakes, evidence quality, concealment plausibility, cascade suspicion, governance implications. | Must produce depth allocation plan. |
| Minimum group coverage | The minimum set of groups (G1–G6) that must be substantively examined before closure. | Prevents single-lens closure. |
| No-Early-Exclusion Rule | Do not exclude lenses early. Touch all groups at least Light Depth before prioritisation or closure; allocate depth after the sweep. | Prevents process-induced hiddens. |
| Bounded closure | Closure is allowed only with explicit residual unknowns, ownership, and monitoring triggers. | If not met: produce non-closure requirements. |
| Residual unknowns | Remaining uncertainties/hiddens at closure; must include why still hidden, what would change if surfaced, owners, and triggers. | Treated as deliverables, not omissions. |

### D.10.2 Artefact terms (mandatory)
| Artefact | Definition (operational) |
|---|---|
| Group Coverage Matrix | G1–G6 table indicating what was examined, key findings, candidate Hiddens, and next tests. |
| Hiddens Register | Structured register of suspected/confirmed Hiddens with mechanisms, detectability, consequence, owners, and status. |
| Evidence Register (Evidence Ledger) | Claim-to-evidence table recording source, quality, dependencies, and bias risks. |
| Hypotheses & Tests Backlog | Differential hypotheses with disconfirming tests, discriminators, required evidence, and status. |
| Information Requests | Explicit list of missing inputs needed to reduce decision-critical Unknowns; includes why and expected discriminator value. |
| Decision Record | Required if recommendations are made: decision, options, rationale, evidence basis, uncertainties, residual Hiddens, monitoring. |
| Investigation Plan | Recommended for non-trivial runs: workstreams, owners, frameworks, inputs/outputs, timeboxes, risks/Hiddens to watch. |


---

## D.11 LLM-Navigable Compact Decision Tree

### D.11.1 Purpose and format

This section provides a machine-readable navigation aid that allows an LLM to determine which Operating Guide sections to invoke, in what order, at what depth, for any scenario. Each node has an ID, preconditions, actions, outputs, and successor pointers. The LLM traverses from START by evaluating preconditions and following successor pointers.

**Relationship to other Appendix D sections:** The Orchestrator Prompts (§D.9) provide paste-ready execution prompts. The Prompt Discipline Rules (§D.3) provide the quality constraints. This decision tree provides the **routing logic** that selects and sequences them. For a visual companion, see Appendix G.

### D.11.2 Invariant layer (active at every node)

These sections are not traversed once — they are **continuously active** constraints and must be checked at every decision point.

| Invariant | Section | Rule |
|---|---|---|
| Hiddens Tier 1 scan | §7.1 | Must fire at least twice: early (after framing) and pre-closure. Assume hiddens exist. |
| Hiddens Micro-Protocol | §7.2 | Every shortlisted hidden must be dimensionally profiled and assigned detection + remediation interfaces. |
| Tier 3 escalation | §7.3 | Escalate if: high consequence, adversarial concealment, persistent disagreement, repeat failure, cascade suspicion. |
| Closure discipline | §7.4 | Every exit must record: residual unknowns, acceptability rationale, monitoring plan, ownership, learning hook. |
| Prompt discipline | §D.3 PD-01–PD-10 | Tag all claims F/I/A/U. Do not invent facts. Separate observation from interpretation. Evidence provenance required. Default to hiddenness. No premature closure. |
| Operating principles | §10 | Mandatory constraints: visibility-first, proportionality, explicit residual unknowns. |

### D.11.3 Decision tree nodes

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
    Execute §5.1 steps 1–7 in sequence:
      Step 1: Case question + timebox [G1] → case statement
      Step 2: Tier 1 Hiddens scan [§7.1, G5] → scan table + shortlist
      Step 3: Boundaries, time horizon, scale [G1] → boundary map
      Step 4: System structure + dependencies [G2] → system sketch
      Step 5: Evidence quality + key gaps [G5] → evidence register + uncertainty register
      Step 6: Immediate risks + stabilisation [G6] → risk shortlist + actions
      Step 7: Decide depth + plan [G6] → investigation plan + owners
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

### D.11.4 Traversal summary (LLM quick-reference)

```text
N0 (START)
 │
 ▼
N1 (SPEED GATE) ──────────────────────────────┐
 │                                              │
 ├─ RAPID ─────→ N2R (§5.1, 7 steps)           │
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

### D.11.5 Section-to-node mapping

| Section | Node(s) | Role |
|---|---|---|
| §1 Core Premise | N0 | Framing and preconditions |
| §2 Group System | N0, N3 | Coverage model and Hiddens linkage |
| §3 Framework Index | N3 | Map groups to specific frameworks |
| §4.1 Use-case routing | N1, N3 | Match scenario to use case and coverage |
| §4.2 Depth selection | N3 | Full Depth vs Light Depth criteria |
| §4.3 Routing decision tree | N3 | Branch logic for group coverage |
| §5.0 Iterative loop | N4 | Master execution cycle |
| §5.1 Rapid protocol | N2R | 7-step rapid sequence |
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
| Appendix G Visual Decision Tree | Reference | Interactive HTML companion |

### D.11.6 Depth × speed matrix

| Dimension | Rapid Run Mode | Investigative Run Mode |
|---|---|---|
| Timebox | 60–180 min | Days–weeks |
| Protocol | §5.1 (7 steps) | §5.2 (11 phases) or §5.3 (6 steps) |
| Minimum coverage | Tier 1 Hiddens + boundary + system sketch + evidence gaps + risk | G1+G2+G5 mandatory + others per §4.3 routing |
| Full Depth frameworks | Typically 3–6 (high-signal only) | Typically 8–20 (per routing and stakes) |
| Light Depth frameworks | All others (scan-level) | Remaining after Full Depth selection |
| Hiddens depth | Tier 1 (standard); Tier 3 only if adversarial | Tier 1 → Tier 2 → Tier 3 as warranted |
| §7.5 Targeted Scans | Rarely (record as follow-up if time insufficient) | Invoked when Tier 1 symptoms point to mechanism |
| Artefacts | Slim set per §D.4.2 | Full set per §D.4.2 |
| Closure standard | Bounded; explicit residual unknowns | Full; detection interfaces for all high-consequence hiddens |
| Escalation path | → Investigative Run Mode | → Tier 3 / full G1–G6 DEEP |


---

## D.12 Architectural Notes and Design Rationale

This section records the structural design decisions behind the Operating Guide's LLM execution infrastructure. It serves as background for implementers and maintainers, not as operational procedure.

### D.12.1 Why the Operating Guide cannot be represented as a single decision tree

The Operating Guide's structure is not a tree. It is a layered graph with invariant planes, conditional loops, and lookup tables.

The Operating Guide contains multiple structural types that resist tree representation:

**Invariant layers** (§7.1–7.4 Hiddens discipline, §D.3 prompt discipline, §10 Operating Principles) are active everywhere simultaneously — they are not visited at a single branch point but enforced as continuous constraints at every decision node.

**Reference tables** (§3.2 Framework-to-Group mapping, §4.1 use-case routing table, §6.2 artefact schemas, §11 Glossary) are looked up on demand, not traversed in sequence. A tree would need to duplicate these at every node that consults them.

**Iterative loops** (§5.0 the master cycle, §5.0.3 iteration triggers) are re-entered conditionally based on evidence state — the loop body may execute once or many times, and each iteration may change the routing. Trees are acyclic by definition; loops require graph representation.

**Cross-cutting constraints** (§D.3 PD-01 to PD-10, §8.2 anti-theatre rule) apply simultaneously to all outputs, not sequentially at designated nodes.

Forcing the full Operating Guide into a single tree would either lose content (by omitting the non-traversal material — definitions, principles, schemas, glossary terms, prompt discipline rules) or become so deeply nested that it would be harder to navigate than the document itself.

**What works instead** — and what §D.11 provides — is a decision tree that serves as the **routing and sequencing spine**, with every leaf and node pointing back to the full content in the body of the Operating Guide. The tree is the map; the Operating Guide is the territory. §D.11's 8-node architecture (N0–N7) with its invariant layer table explicitly represents the non-tree elements as annotations rather than attempting to flatten them into branches.

### D.12.2 LLM-executability assessment: what the Operating Guide provides and what it requires

The Operating Guide v2.2 is **executable at the protocol level**. An LLM given the Operating Guide and a scenario can run the full investigation workflow without any external document:

**Fully self-contained capabilities:**

| Capability | Sections | What the LLM can do |
|---|---|---|
| Run mode selection | §D.6, §D.9.2 | Select Rapid or Investigative based on scenario features |
| Protocol execution | §5.1, §5.2, §5.3, §D.9.3, §D.9.4 | Execute the phased orchestrator prompts step by step |
| Routing | §4.3, §D.5, §D.11 | Traverse the decision tree to determine group coverage and depth |
| Tier 1 Hiddens scanning | §7.1 | Run the six-category visibility audit using the scan table |
| Targeted scan routing | §7.5.2, §7.5.3 | Select scans from the triage matrix and follow framework chains |
| Artefact production | §D.4, §6.1, §6.2 | Produce all required registers and tables to specification |
| Quality controls | §8.1, §8.2 | Apply the checklist and anti-theatre rule |
| Closure discipline | §7.4 | Record residual unknowns, monitoring plan, ownership, learning hook |
| Prompt discipline | §D.3 PD-01–PD-10 | Tag F/I/A/U, preserve disagreement, prevent premature closure |
| LLM adapter for scans | §7.5.8 | Execute pseudocode, gate questions, per-step output tables |

An LLM with general domain knowledge could produce a credible, disciplined investigation using just the Operating Guide. The protocol discipline, F/I/A/U tagging, and anti-theatre rule alone force more rigour than most analyses achieve.

**External dependency: individual framework documents.** The Operating Guide routes the LLM to specific frameworks (e.g., "execute Framework of Systems at Full Depth") but does not contain the internal content of the 50 individual framework documents. Each framework document carries its own taxonomy of types (typically 30 types across 6 meta-categories), dimensions tables, dynamics patterns, interface types, hiddens source analysis, crosswalk tables, integration questions, and application protocol steps.

**Practical impact of missing framework documents:**

| Execution depth | Without framework documents | With framework documents |
|---|---|---|
| Light Depth (scan-level) | Adequate — the Operating Guide's scan prompts, Tier 1 table, and routing logic provide sufficient structure for a scan-level pass | Full — framework-specific scan prompts add precision |
| Full Depth | Degraded — the LLM falls back on general domain knowledge rather than the specific structured taxonomy each framework provides; analysis is less systematic, less repeatable, and more dependent on what the LLM happens to know | Full — the framework's types, dimensions, dynamics, and interfaces drive structured, repeatable execution |
| Targeted Scans (§7.5) | Partially degraded — the Operating Guide contains the scan routes (which frameworks to chain) and gate questions, but the LLM cannot populate framework-specific tables without the framework content | Full — each step in the scan chain uses the target framework's internal structure |

**Design implication.** The Operating Guide is designed as an orchestration layer: it tells the LLM *which* frameworks to use, *in what order*, *at what depth*, *with what quality controls*. The individual framework documents provide the *analytical content* that populates the tables. This separation is intentional — it allows frameworks to be updated independently and prevents the Operating Guide from becoming an unmanageably large single document. However, it means that LLM execution at Full Depth requires the relevant framework documents to be available in context alongside the Operating Guide.

---

# Appendix E — Machine-Readable Field Schemas (recommended)



## E.1 Enumerations (controlled values)
| Field | Allowed values |
|---|---|
| Group | G1, G2, G3, G4, G5, G6 |
| Hidden status | Suspected, Investigating, Confirmed, Managed, Closed |
| Evidence type | Observation, Log/Telemetry, Document, Interview, Measurement, Expert judgement, Simulation/Model, Audit/Assurance |
| Evidence quality (suggested) | A (strong), B (moderate), C (weak), D (speculative) |
| Detectability (suggested) | High, Medium, Low, Unknown |
| Reducibility (suggested) | Reducible, Partially reducible, Irreducible (manage/robustify), Unknown |

## E.2 Group Coverage Matrix (minimum schema)
| Group | Coverage claim (what was examined) | Key candidate hiddens (IDs) | Evidence basis (IDs) | Next actions/tests | Owner |
|---|---|---|---|---|---|

## E.3 Hypotheses & Tests (minimum schema)
| Hypothesis ID | Hypothesis statement | Competing hypothesis | Key assumptions | Disconfirming test (next-best) | Evidence required | Status |
|---|---|---|---|---|---|---|

## E.4 Information Requests (minimum schema)
| Request ID | Information needed | Why it matters (which hidden/hypothesis) | Expected value | Cost/effort | Access owner |
|---|---|---|---|---|---|

---

# Appendix F — Worked Example (illustrative, fictional)

## F.1 Scenario summary (input excerpt)
A regional operations centre experiences a 6-hour outage of its monitoring and control dashboard. Operators revert to manual workarounds. Two days later, an asset trips unexpectedly, causing service disruption. Management believes the root cause is “operator error during the outage window.”

## F.2 Example outputs (abridged)

### F.2.1 Group Coverage Matrix (example)
| Group | Coverage claim (what was examined) | Key candidate hiddens (IDs) | Evidence basis (IDs) | Next actions/tests | Owner |
|---|---|---|---|---|---|
| G1 | Confirmed boundaries and timeline; defined failure criteria | H-001, H-002 | E-001 | Re-check scope for upstream dependencies | Lead investigator |
| G2 | Mapped key dependencies and failure propagation path | H-003, H-004 | E-002, E-003 | Pull telemetry for coupling points | Engineering |
| G3 | Incentives/power audit on reporting and blame dynamics | H-005 | E-004 | Confidential interviews; protect dissent | HR/Assurance |
| G4 | Narrative/communications audit on “operator error” framing | H-002, H-005 | E-004, E-005 | Separate story vs support; track contradictions | Investigation team |
| G5 | Evidence grading; uncertainty log; alternative hypotheses | H-001–H-005 | E-001–E-006 | Run disconfirming tests | Investigation team |
| G6 | Control and governance review for dashboard outage handling | H-006 | E-006 | Define KRIs/triggers; drill procedures | Ops governance |

### F.2.2 Hiddens Register (example entries)
| Hidden ID | Description | Meta-category (I–VI) | Hiding mechanism | Consequence | Detectability | Reducibility | Owners | Status | Residual risk |
|---|---|---|---|---|---|---|---|---|---|
| H-003 | Hidden coupling: dashboard outage also disabled an alarm suppression reset | Systemic | Tight coupling + undocumented dependency | Repeat trips under “normal” ops | Medium | Partially reducible | Engineering | Investigating | Some coupling may remain |
| H-005 | Reporting distortion: fear of blame suppresses disclosure of workaround deviations | Relational | Power/incentives + psychological safety deficit | Investigation misses real causes | Low | Reducible | Leadership/HR | Suspected | Some under-reporting persists |

### F.2.3 Evidence Register (example entries)
| Evidence ID | Claim supported | Evidence type | Source | Quality | Dependencies / assumptions | Notes |
|---|---|---|---|---|---|---|
| E-002 | Alarm reset did not occur after dashboard restoration | Log/Telemetry | Control system logs | B | Log integrity intact | Requires timestamp alignment |
| E-004 | Operators report informal workaround steps not documented | Interview | 3 operators | C | Social desirability bias possible | Cross-check with telemetry |

### F.2.4 Hypotheses & Tests (example)
| Hypothesis ID | Hypothesis statement | Competing hypothesis | Key assumptions | Disconfirming test (next-best) | Evidence required | Status |
|---|---|---|---|---|---|---|
| HYP-01 | Trip caused by hidden coupling after dashboard outage | Operator error during manual ops | Logs correctly represent state transitions | Reconstruct state timeline and replay | Logs + event traces | Open |

---

## Appendix F.3 Notes
This example is intentionally small. The point is format discipline: explicit hiddens, explicit evidence, explicit tests, explicit ownership, and explicit residual unknowns.

---


# Appendix G — Visual Decision Tree (Embedded Static Rendering + Interactive HTML Companion)

## G.1 Purpose

This appendix provides the full visual decision tree that shows how all Operating Guide sections are used and inter-relate during an investigation. The tree is presented below as a static Markdown rendering (§G.4–G.10) so the Operating Guide remains self-contained. For the interactive version with expandable nodes and colour coding, use the companion HTML file referenced in §G.2.

The visual tree is the human-readable companion to the LLM-navigable decision tree in §D.11. Both trees represent the same architecture; §D.11 is optimised for machine traversal (node IDs, preconditions, successor pointers) while this appendix is optimised for human comprehension (phases, visual hierarchy, narrative detail).

## G.2 Companion file (interactive version)

| Field | Value |
|---|---|
| File name | 2026-04-01-Anthropic-Claude-Opus-4-6-Operating_Guide_Compact_Decision_Tree.html |
| Format | Single-file interactive HTML (no external dependencies) |
| Intended use | Open in any web browser to navigate the Operating Guide's section flow visually |
| Relationship to §D.11 | Presents the same node structure (N0–N7) with expandable detail panels, colour-coded by function (entry, gate, execute, hiddens, quality, output) |

## G.3 Colour legend and depth key

| Colour | Function | §D.11 mapping |
|---|---|---|
| Blue | Entry / Setup | N0 (START) |
| Amber | Decision Gate | N1 (SPEED_GATE), N3 (ROUTING_GATE) |
| Green | Execute | N2R, N2I_POST, N2I_PRE, N4 (EXECUTION_LOOP) |
| Red | Hiddens (invariant) | Invariant layer (§7.1–7.5) |
| Purple | Quality / Governance | §8, §9, §10 |
| Cyan | Output / Close | N6 (CLOSURE) |
| Olive | Feedback Loop | §5.0.3 iteration triggers |

**Depth key:** Each node is tagged with its applicable run mode: **Rapid** (60–180 min), **Investigative** (days–weeks), or **Both**.

---

## G.4 Invariant layer (active across every phase)

> **§7 Hiddens Integration Discipline** runs as an invariant layer across every phase below. §7.1 Tier 1 scan fires early and repeats pre-closure. §7.2 Micro-Protocol profiles every candidate hidden. §7.3 Escalation to Tier 3 can trigger at any gate. §7.4 Closure discipline governs every exit. §7.5 Targeted Scans are optional spears invoked when Tier 1 symptoms point to a specific mechanism.

| Invariant | Section | Rule |
|---|---|---|
| Hiddens Tier 1 scan | §7.1 | Must fire at least twice: early (after framing) and pre-closure. Assume hiddens exist. |
| Hiddens Micro-Protocol | §7.2 | Every shortlisted hidden must be dimensionally profiled and assigned detection + remediation interfaces. |
| Tier 3 escalation | §7.3 | Escalate if: high consequence, adversarial concealment, persistent disagreement, repeat failure, cascade suspicion. |
| Closure discipline | §7.4 | Every exit must record: residual unknowns, acceptability rationale, monitoring plan, ownership, learning hook. |
| Prompt discipline | §D.3 PD-01–PD-10 | Tag all claims F/I/A/U. Do not invent facts. Separate observation from interpretation. Evidence provenance required. Default to hiddenness. No premature closure. |
| Operating principles | §10 | Mandatory constraints: visibility-first, proportionality, explicit residual unknowns. |

---

## G.5 Phase 1 — Entry and Framing

### G.5.1 [ENTRY] Scenario arrives — establish case container (§1, §2) — *Both*

**§1.1** Core premise: visibility failures are the target, not just "what happened." **§1.2** Check preconditions: case question defined? Owner named? Timebox agreed? Access audited? **§1.3** Scope and non-goals: explicit residual unknowns, not complete knowledge. **§2.1–2.2** Group system (G1–G6) provides the coverage model. Group-to-Hiddens linkage identifies what each group typically generates. **§10** Operating Principles are mandatory constraints throughout. **Appendix D §D.7** If LLM-assisted: paste system instruction block; set F/I/A/U tagging active.

▼

### G.5.2 [GATE] Speed gate — select run mode (§D.6, §4.1)

**Decision:** What are the time constraints and decision stakes?

**§D.6.1 Mode definitions:** (a) **Rapid Run Mode** (60–180 min): stabilise understanding, prioritise next steps. Uses §5.1 protocol. Light coverage with targeted depth. (b) **Investigative Run Mode** (days–weeks): full explanation, accountability, recurrence prevention. Uses §5.2 or §5.3 protocol. Broad coverage with selective depth.

**§D.6.7** Both modes exist because decisions have different urgency/stakes profiles. Rapid is not "worse" — it is fit-for-purpose under time pressure. **§D.6.4** No-Early-Exclusion Rule: even in Rapid, no group is excluded from at least a light scan.

**Branches from speed gate:**

#### G.5.2a [PROTOCOL] §5.1 Rapid Protocol — 7-step sequence — *Rapid*

Step 1: Case question + timebox → `G1`. Step 2: Tier 1 Hiddens scan (assume hiddens exist) → `§7.1` `G5`. Step 3: Boundaries, time horizon, scale → `G1`. Step 4: System structure + dependencies → `G2`. Step 5: Evidence quality + key gaps → `G5`. Step 6: Immediate risks + stabilisation → `G6`. Step 7: Decide depth + plan → `G6`.

**Gate at Step 7:** Commit to Rapid closure, or escalate to Investigative Run Mode. **Artefacts:** §6 minimum schemas apply (slimmed). F/I/A/U tagging required on all claims (§D.3).

#### G.5.2b [PROTOCOL] §5.2 Post-Failure Protocol — 11-phase sequence — *Investigative*

Phase 1 (Frame): Classify situation, set boundaries → `G1`. Phase 2 (Frame): Tier 1 Hiddens scan → `§7.1`. Phase 3 (Model): System/relations/process maps → `G2`. Phase 4 (Model): Causal hypotheses → `G2/G5`. Phase 5 (Agency): Actors, incentives, power, responsibility → `G3`. Phase 6 (Meaning): Narratives, comms, norms, legitimacy → `G4`. Phase 7 (Epistemics): Evidence grading, uncertainties, investigation failure risks → `G5`. Phase 8 (Synthesis): Diagnosis with residual hiddenness → `G5` + `§7.2`. Phase 9 (Convert): Decisions, interventions, governance, risk → `G6`. Phase 10 (Assure): Detection/remediation interfaces → `§7.2` + `G6`. Phase 11 (Learn): Learning loop, drift indicators → `G6`.

**§7.5 Targeted Scans** can be invoked at any phase where Tier 1 symptoms point to a specific mechanism — most commonly during Model, Agency, Meaning, or Epistemics phases.

#### G.5.2c [PROTOCOL] §5.3 Proactive Protocol — 6-step sequence — *Investigative*

Step 1: Change intent + assumptions → `G1/G6`. Step 2: Tier 1 Hiddens (change-induced mechanisms) → `§7.1` `G5`. Step 3: Dependency + coupling impacts → `G2`. Step 4: Incentives/power + comms integrity → `G3/G4`. Step 5: Monitoring, buffers, escalation rules → `G6`. Step 6: Governance + ownership confirmation → `G6`.

---

## G.6 Phase 2 — Routing and Depth Selection

### G.6.1 [GATE] Route — scenario features → group coverage + depth (§4.3, §3.2) — *Both*

**§4.3.1 Decision tree (compact):**

**Branch A — Failure occurred?** YES → Minimum: G1+G2+G5 DEEP. A1: Evidence weak/contested? → Deepen G5 frameworks. A2: Coupling/cascade? → Deepen G2 (Systems/Relations/Processes). A3: Incentives/power/concealment? → Add G3 DEEP. A4: Narratives contested/"too clean"? → Add G4 DEEP. A5: Recommendations change controls? → Add G6 DEEP. A6: Adversarial intent? → Full G1–G6 DEEP; Tier 3 Hiddens.

**Branch B — No failure, high-stakes decision pending?** YES → Minimum: G1+G2+G5+G6 DEEP. B1: Multi-stakeholder conflict? → Add G3 DEEP. B2: Narrative/legitimacy disputes? → Add G4 DEEP. B3: High novelty/tight time? → Deepen G2+G5.

**NO to both** → Low-stakes/exploratory: G1+G5 light + one domain group deep.

**§4.3.2 Output contract:** Routing statement, minimum group coverage, Full Depth list + rationale, Light Depth list + rationale, escalation triggers. **§3.2** Framework-to-Group mapping tells you which of the 50 frameworks sit in each group. **§4.2** Depth selection: run deeply where consequence is high, evidence is weak, incentives may distort, or coupling exists.

---

## G.7 Phase 3 — Iterative Execution Loop

### G.7.1 [LOOP] §5.0 Iterative investigation loop — the master cycle (§5.0) — *Both*

All three protocols (§5.1, §5.2, §5.3) execute within this single repeatable loop. The loop enforces register-first execution, repeated Hiddens scanning, evidence-gated confidence, and explicit residual unknowns.

**The loop phases are:** Initialise → Generate → Route → Execute → Test → Re-scan → Decide. **§5.0.3** Iteration triggers force re-entry: contradictory evidence, "too clean" story, high-impact unknown, new artefacts, governance implications. **§5.0.4** Stop conditions: timebox requires output AND evidence supports claims AND residual unknowns are explicit AND detection interfaces exist.

**Loop steps:**

#### G.7.1a [EXECUTE] Run Full Depth frameworks — extract, populate, discover (§5.0.2 step 4) — *Both*

For each framework on the Full Depth list: (a) Extract facts from scenario + artefacts; tag `F/I/A/U` (§D.3.2). (b) Populate framework core tables (Types / Dynamics / Interfaces). (c) Add/adjust candidate hiddens (mechanism + impact + detectability). (d) Add tests/probes; update Evidence Ledger.

**§6** Standard Artefacts: Hiddens Register, Evidence Register, Hypothesis/Test Backlog, Group Coverage Matrix. **§D.3** Prompt Discipline Rules PD-01 to PD-10 govern all outputs.

#### G.7.1b [EXECUTE] Run Light Depth frameworks — scan for high-signal candidates (§5.0.2 step 5) — *Both*

For each framework on the Light Depth list: (a) Run scan prompts; record only high-signal candidates and missing-information triggers. (b) A Light framework may escalate to Full Depth if evidence is contested, consequence is high, or coupling is discovered.

**§D.6.4 No-Early-Exclusion Rule:** Every group gets at least a light scan, even in Rapid Run Mode. Exclusion is a depth decision, not a coverage decision.

#### G.7.1c [HIDDENS] §7.1–7.5 Hiddens discipline fires within execution (§7) — *Both*

**§7.1 Tier 1 Six-Category Scan:** Required early (step 2 of loop) and repeated pre-closure (step 7). Sweeps all 6 meta-categories (I Perceptual → VI Ontological). Assume hiddens exist.

**§7.2 Micro-Protocol:** For each shortlisted hidden — rate mechanism, reducibility, detectability, agency, consequence. Assign detection + remediation interfaces. Map interaction chains.

**§7.3 Escalation to Tier 3:** Triggers: high consequence, adversarial concealment, persistent disagreement, repeat failure, cascade suspicion. Tier 3 = full 30-type run + detection/remediation matrix.

**§7.5 Targeted Scans (optional):** When Tier 1 symptoms point to a specific hiding mechanism, use the Triage Matrix (§7.5.3) to select one or more of the 13 targeted scans. Each scan routes through 3–5 frameworks in sequence, following the mechanism's causal chain. Organised into 4 families: **A** Social/organisational (Suppression, Legitimacy Theatre, Narrative Capture, Belief Persistence); **B** Structural/systemic (Positional Blindness, Cascade Discovery, Uncertainty Masking, Competency Blindspot); **C** Temporal (Drift, Amnesia); **D** Action-induced (Evidence Corruption, Negligence, Intervention Blindspot).

**§7.5.8 LLM Execution Adapter:** Pseudocode, gate questions (52 total), per-step output tables, depth triggers, Appendix D compliance.

#### G.7.1d [TEST] Convert unknowns into probes/tests — request artefacts (§5.0.2 step 6) — *Both*

Execute tests/probes where possible, or produce an Evidence Request List. **§D.3.4** Handling missing information: every `U` must generate an information request or probe/test. Do not invent facts (PD-01). **§D.3.1 PD-05:** Prefer tests over stories — test hypotheses rather than narrating around gaps.

#### G.7.1e [HIDDENS] Pre-closure Tier 1 re-scan — identify omissions-by-lens (§5.0.2 step 7, §7.1) — *Both*

Re-run Tier 1 Hiddens scan with updated knowledge. Purpose: catch hiding mechanisms that only become visible after other frameworks have run. If re-scan reveals new hiddenness classes → update routing statement and loop back to Execute phase. **§7.5.5 Scan Interaction Map:** If a targeted scan was run, check whether its findings trigger a second targeted scan (21 documented interactions).

#### G.7.1f [FEEDBACK] Iteration triggers (§5.0.3)

↻ Contradictory evidence · "too clean" story · high-impact Unknown · new artefacts · governance implications → loop back to Execute or Route.

---

## G.8 Phase 4 — Quality Controls

### G.8.1 [QUALITY] §8 Quality controls + anti-theatre rule (§8, §10) — *Both*

**§8.1 Checklist:** Alternative explanations maintained? Evidence graded? Incentive/power audit done? Narrative audit done? Boundary regression tested? Drift detection applied? Escalation discipline followed?

**§8.2 Anti-theatre rule:** Every major claim must be backed by: at least one evidence entry (or explicit gap), an uncertainty statement, a hiddenness check, and an owner for follow-up.

**§10 Operating Principles:** Mandatory constraints that govern all work — visibility-first, proportionality, explicit residual unknowns, no premature closure.

**§D.3.1 PD-08:** Do not close prematurely. PD-09: Make residual hiddenness explicit. PD-10: Produce actionable outputs.

---

## G.9 Phase 5 — Closure or Escalation

### G.9.1 [GATE] Closure gate — are stop conditions met? (§5.0.4, §7.4) — *Both*

**§5.0.4 Stop conditions (ALL must hold):** (1) Decision timebox requires an output. (2) Evidence Ledger supports key claims at required confidence. (3) Residual Unknowns are explicit, prioritised, and assigned owners/actions. (4) Remediation plan includes detection interfaces for top residual hiddens.

**If NOT met:** Output must be non-closure with explicit close-out requirements, or escalate to Tier 3 / full G1–G6.

**Branches from closure gate:**

#### G.9.1a [OUTPUT] Stop conditions MET → Produce closure artefacts (§6, §7.4, §D.4) — *Both*

**§7.4 Closure discipline:** Residual unknowns list, acceptability rationale, monitoring plan, ownership, learning hook.

**§6 Standard Artefacts:** Hiddens Register (final), Evidence Register, Group Coverage Matrix, Hypothesis/Test Backlog, Decision Record. **§D.4 Output contract:** Required registers and checklists per run mode. Rapid produces slimmer artefacts; Investigative produces full set.

**§9 Governance:** Outputs feed into series governance — change control, learning loop, case repository.

#### G.9.1b [ESCALATE] Stop conditions NOT met → Escalate or non-closure (§7.3, §4.3) — *Both*

Options: Add groups (e.g., A3 triggers → add G3 DEEP); Upgrade Light → Full Depth on specific frameworks; Escalate Hiddens to Tier 3 (full 30-type run); Escalate Rapid → Investigative Run Mode; Invoke §7.5 Targeted Scans if a specific mechanism is now suspected. → Loop back to Phase 2 (re-route) or Phase 3 (re-execute).

---

## G.10 Cross-cutting — LLM Execution Governance (Appendix D)

### G.10.1 [LLM] Appendix D — active throughout when LLM-assisted (§D.1–D.11)

**§D.2** Applies to all LLM-assisted uses (Rapid, Investigative, post-failure, adversarial).

**§D.3 Prompt Discipline Rules (PD-01 to PD-10):** PD-01: Don't invent facts. PD-02: Tag F/I/A/U. PD-03: Separate observation from interpretation. PD-04: Evidence provenance. PD-05: Prefer tests over stories. PD-06: Preserve disagreement. PD-07: Default to hiddenness. PD-08: No premature closure. PD-09: Residual hiddenness explicit. PD-10: Actionable outputs.

**§D.5** Routing logic (canonical): minimum group coverage + deep/light selection rules. **§D.6** Run mode definitions, operational sequences, tiered Hiddens depth control. **§D.8** Prompt pack: paste-ready prompts for each mode. **§D.9** Orchestrator Prompts: mode selection gate → Rapid or Investigative orchestrator. **§D.11** LLM-Navigable Compact Decision Tree: machine-readable 8-node routing aid. **§7.5.8** LLM Execution Adapter for Targeted Scans: pseudocode, 52 gate questions, output tables, depth triggers.

---

## G.11 Post-investigation — Governance and Learning

### G.11.1 [GOVERN] §9 Governance — repeatability, evolution, learning (§9, §11, §12) — *Both*

**§9.1** Roles: series steward, framework maintainer, reviewer, practitioner community. **§9.2** Change control: non-substantive → substantive → taxonomy extension → group label refinement. **§9.3** Canonical source rule: Operating Guide is authoritative for prompt discipline and output contracts. Framework excerpts point to it. **§11** Glossary: shared terminology across all sections. **§12** Document control: version history tracks all changes.

---

## G.12 Usage notes

This static rendering preserves all node content from the interactive HTML companion file but necessarily loses the expandable/collapsible interactivity and colour coding. For the full interactive experience, open the companion file (§G.2) in any modern browser. The HTML file can also be printed with all panels expanded for a static reference that includes the visual styling.
