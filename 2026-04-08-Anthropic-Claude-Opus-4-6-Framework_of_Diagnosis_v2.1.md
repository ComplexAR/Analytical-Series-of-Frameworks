# Framework of Diagnosis
*A Comprehensive Taxonomy for Determining What Is Happening, Why, and What to Do Next—To a Decision-Relevant Standard*

## Document Information
- Series: Analytical Series of Frameworks
- Version: v2.1
- Date: 2026-04-08
- Status: Draft
- Operating Guide Compatibility: Analytical Series Operating Guide v2.5
- Prompt Discipline Ruleset: Operating Guide "Prompt Discipline Rules (Canonical)" (see OG v2.5, §D.3)
- Run Mode Terminology: Rapid Run Mode / Investigative Run Mode (see Operating Guide §D.10.1)
- Framework Execution Depth Terminology: Full Depth Framework Execution / Light Depth Framework Execution (see Operating Guide §D.10.1)
- Tiered Hiddens Scan Model: Tier 1 (six-category visibility audit) / Tier 2 (structured deepening) / Tier 3 (full-spectrum escalation) (see Operating Guide §D.6.10)
- Targeted Hiddens Discovery Scans: Thirteen mechanism-specific cross-framework scans (see Operating Guide §7.5)
- Group (Primary): G5 — Epistemics & error-control (Epistemics)
- Group (Secondary): G2 — Structure, dependencies & mechanism (Mechanism)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Incident triage; problem diagnosis; audit and investigation; risk analysis; transformation and change; operational improvement; governance and accountability; clinical/engineering/policy diagnostic work
- Primary Audience: Executives; incident and operations leaders; risk/compliance; investigators/auditors; analysts; architects/engineers; programme leaders; policy designers
- Dependencies / Key Inputs: Situation framing; evidence set; system and boundary map; timeline/history; stakeholder map; incentives/power map; constraints/resources; governance and decision rights; prior incidents and learning artefacts
- Primary Outputs: Working and confirmed diagnoses; explicit differential set; diagnostic map (meta-categories + types); quality scorecard; interface risk map; hiddens source register; Hiddens shortlist and escalation triggers; decision/intervention implications; learning loop updates
- Change Log (brief): Rewrite for v2.0 alignment with Master Template v2.3; updated all OG references from v1.5 to v2.5; expanded §1.6 with Tier 2 Hiddens crosswalk, Targeted Scans routing, and full Information Requests schema; added Introduction section (four subsections); updated Document Information with Tiered Hiddens Scan Model and Targeted Hiddens Discovery Scans fields; expanded §1.4 with Stage assignment, Framework Index pointer, and Iteration loop statement; added Group and Stage columns to §7.3 framework integration list (all 36 canonical frameworks); updated §8 with Tier 2 structured deepening guidance and Targeted Scans escalation trigger; updated §11.2 pointer to OG v2.5; expanded all thin sections; preserved all content; 750+ lines.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What is happening in this case, why is it happening, what is likely next, and what should be done—given uncertainty, time pressure, and stakes?** |
| Addresses | Premature closure; over-reliance on familiar patterns; evidence distortion; role/power filtering of truth; misdiagnosis under time pressure; failure to link diagnosis to decisions; lack of calibration and learning. |
| Gap Filled | Many frameworks describe systems, risks, or causes; this framework structures the *act of knowing*—how to form and test explanations that are usable for decisions. |
| Complements | Evidence; Situations; Systems; Causation; Risk; Time; Scale; Incentives; Power; Governance; Decisions; Interventions; Learning & Adaptation; Hiddens; Beliefs; Metrics; Competencies. |
| Key Characteristics | Multi-lens by default; differential-maintaining; evidence-aware; action-oriented; learning-calibrated; explicit about error and uncertainty. |
| Main Contributions | Six meta-categories of diagnostic approach; thirty core diagnosis types; process architecture phases; evidence and context taxonomy; diagnostic errors and blindspots; diagnostic quality dimensions; diagnosis interfaces (evidence/decision/learning); application protocol; principles; glossary and document control. |

---

# Introduction

## What is Diagnosis?

Diagnosis is the disciplined act of determining what is happening in a case and why, to a standard that is **relevant to the decisions that must be made**. It is not merely a classification exercise—it is an active process of forming, testing, and revising explanations under uncertainty. Good diagnosis is not only about correctness; it is also about **timeliness, explainability, robustness to uncertainty, and actionability**. A diagnosis that is accurate but arrives too late to matter fails its purpose. A diagnosis that is correct but unintelligible to decision-makers is useless. A diagnosis that is internally consistent but brittle to new evidence cannot guide action.

In real settings, diagnosis occurs under constraints: incomplete evidence, time pressure, organisational politics, asymmetric stakes, and the need to act before full understanding arrives. This framework treats diagnosis as a **multi-lens activity**. Classifications, causal explanations, functional assessments, relational dynamics, prognostic trajectories, and contextual fit all contribute distinct diagnostic value. A single-lens diagnosis is structurally fragile: it may be fast but wrong, correct but unusable, or coherent but politically filtered.

## Why does Diagnosis matter for Hiddens work?

Because diagnostic practice is highly vulnerable to systematic visibility failures—framing, distortion, fragmentation, latency, and narrative stabilisation—diagnosis is a primary site of Hiddens operation. Misdiagnosis is itself a Hidden—a reality-relevant factor that remains invisible to decision-makers until late consequences reveal the error.

This framework surfaces several families of hiding mechanisms:

**Framing capture** (Hidden-8) operates when diagnostic boundaries foreground certain levers and hide others. A problem is framed as "technical malfunction"; in truth it is "systemic design failure" or "cultural norm mismatch." Each frame enables different actions and suppresses different concerns.

**Narrative stabilisation** (Hidden-6 Distortion morphing into narrative coherence) occurs when an early diagnosis becomes "the official story" and contrary evidence is downweighted or excluded. Social and organisational pressures select a coherent narrative, often aligned to incentives, power, or legitimacy needs.

**Channel myopia** (part of Hidden-14 Fragmentation) arises when diagnostic evidence is over-concentrated in one access point (metrics dashboards, senior managers, technical logs) while alternative signals remain invisible or disconnected.

**Temporal blindness** (Hidden-15 Latency, Hidden-7 Mirage) allows situations to evolve and diagnoses to become stale without timely revision. A manageable risk becomes chronic overload. An early misdiagnosis cascades into wrong interventions.

**Positional filtering** (Hidden-21) means that what is visible depends on role and access. Frontline reality differs from head-office understanding. Diagnosis captured by one stakeholder's position systematically distorts for all others.

Without this framework, these Hiddens remain latent. With the framework, diagnosis becomes a repeatable, testable discipline that flags error risks early and enables deliberate multi-lens synthesis.

## What does this framework produce?

The framework operationalises diagnosis through six core elements:

1. **A taxonomy of 30 diagnosis types** organised into six meta-categories (Classificatory, Causal, Functional, Relational, Prognostic, Contextual), enabling rapid identification of what kind of explanation is being attempted and where blindspots may hide.

2. **A process architecture** with eight diagnostic phases (Presentation, History, Examination, Investigation, Differential, Synthesis, Verification, Revision) that structure the flow from observation to action to learning.

3. **Evidence and context taxonomy** that specifies evidence types (signs, symptoms, test results, historical patterns, contextual factors) and their diagnostic pitfalls, enabling quality calibration.

4. **Diagnostic quality dimensions** (accuracy, timeliness, explainability, robustness, actionability) that operationalise the decision-relevance standard and enable quality scorecarding.

5. **Three interface types** (Evidence, Decision, Learning) that make visible the boundary conditions between diagnosis and the systems it serves.

6. **Hiddens source analysis and tiered Hiddens scans** that surface the six systematic sources of diagnostic failure (Premature Closure, Pattern Dominance, Channel Myopia, Feedback Starvation, Base-Rate Neglect, Political Capture) and enable systematic cross-checking.

The framework populates standard registers (Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests) that integrate with the broader Analytical Series investigation workflow. It is designed for revision: diagnoses are formed and tested, decisions are made, outcomes are tracked, and the diagnosis is updated as new evidence emerges, enabling the analysis to track evolution in real time.

## How to use this framework

Invoke this framework whenever diagnosis is needed to reduce decision-critical uncertainty, when competing diagnoses exist, or when diagnostic error could cascade into worse harm. It is most valuable early in incident response (to establish what must be prioritised), during major decision gates (to validate whether our understanding still holds), and when interventions fail to produce expected effects (often a signal of misdiagnosis). The framework works in both Rapid Run Mode (light-touch differential generation and Tier 1 Hiddens check) and Investigative Run Mode (deep evidence synthesis, full Hiddens scanning, multi-stakeholder narrative reconciliation).

Default execution is Light Depth Framework Execution: frame the diagnostic question, inventory evidence, generate differentials using the 30-type taxonomy, run a Tier 1 Hiddens scan, and form a working diagnosis with explicit uncertainty. Escalate to Full Depth when consequence is high, evidence is contested, multiple stakeholders disagree on diagnosis, or you are detecting patterns of diagnostic failure. The framework's companion prompt discipline rules (OG v2.5, §D.3) require tagging all diagnostic claims as Fact, Interpretation, Assumption, or Unknown, and explicitly recording disagreements, uncertainties, and residual unknowns rather than collapsing them into false consensus.

For LLM execution, see §1.6 for the complete LLM integration specification, standard registers, and copy-ready run prompts. The framework is designed to be directly executable by an LLM given a scenario and the Operating Guide, producing a disciplined diagnosis with explicit Hiddens, F/I/A/U tagging, bounded closure, and learning hooks.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Diagnosis is the disciplined act of determining what is happening in a case and why, to a standard that is **relevant to the decisions that must be made**. Good diagnosis requires:

- **Multiple lenses**, not single-lane thinking: classification, causation, function, relations, trajectory, and context all matter.
- **Explicit differentials**, maintaining plausible alternatives and must-not-miss hypotheses until evidence converges.
- **Evidence-aware reasoning**, distinguishing signs, symptoms, test results, patterns, and contextual factors, and calibrating confidence to evidence quality.
- **Decision coupling**, linking diagnosis to actionable interventions and monitoring, not to abstract explanations.
- **Timeliness**, recognising that delayed diagnosis can be as harmful as wrong diagnosis.
- **Revisability**, treating diagnoses as versioned and explicitly updatable as conditions change.
- **Learning**, capturing diagnostic misses and successes to improve future diagnostic practice.

## 1.2 Assumptions & Preconditions

### Assumptions Register (Diagnosis-specific)
| Assumption | Type | If false, what breaks? | How to test | Mitigation |
|---|---|---|---|---|
| Diagnostic approaches can be classified across six meta-categories and applied in multi-lens mode. | Method | Single-lens diagnosis produces brittle conclusions; multi-lens misalignment goes undetected. | Apply all six lenses to pilot cases; audit for divergence and integration. | Use explicit multi-lens protocol; document where lenses diverge and why. |
| Evidence can be assembled and ranked to support differential diagnosis and testing of competing hypotheses. | Method | Premature closure; confirmation bias; untested alternatives. | Maintain differential diagnosis register; require explicit hypothesis testing. | Pair with Evidence framework; use adversarial/red-team review. |
| Diagnostic standards can be specified prior to analysis and calibrated to decision stakes and reversibility. | Normative | Standards drift; post-hoc rationalisation of conclusions. | Require diagnostic brief with standards at start; audit for consistency. | Lock standards until explicit revision gate; document all revisions and rationale. |
| Causation can be distinguished from correlation and from mere description, with explicit causal hypothesis testing. | Method | Causal overreach; spurious correlations treated as mechanisms. | Require causal mapping and counterfactual testing; document mechanism strength. | Pair with Causation and Systems frameworks; use process-tracing and mechanism tests. |
| Diagnostic error patterns and hiddens sources can be identified and controlled via detection, correction, and prevention interfaces. | Method | Errors are repeated; learning is not embedded in process. | Run diagnostic failure scan; audit for recurring error types. | Pair with Failures framework; implement detection and correction loops. |
| Organisational and political context shapes diagnosis; dissenting views and power effects can be made visible. | Structural | Consensus diagnosis masks real disagreement; politically filtered diagnosis hides truth. | Elicit multiple stakeholder diagnoses; track dissent and power effects. | Pair with Perspectives and Power/Incentives frameworks; use protected dissent protocols. |
| Diagnosis must be revisited as new evidence emerges and conditions change; provisional diagnoses can be updated. | Temporal | Stale diagnoses drive wrong decisions; diagnostic learning is not captured. | Document diagnostic evolution; audit for timely re-diagnosis triggers. | Create diagnosis update cadence; embed into decision and learning loops. |

### Preconditions Checklist
| Precondition | Required? | Evidence | Owner | Status |
|---|---|---|---|---|
| Focal problem statement is clear (what is the case, what is unknown, what is at stake). | Y | Problem statement / decision brief | Decision owner | TBV |
| Evidence base is inventoried (what is known, what is missing, what is contested). | Y | Evidence summary / Evidence framework output | Evidence owner | TBV |
| System boundary and context are defined (what is in/out of scope, what constraints apply). | Y | Boundary statement / System map | Lead analyst | TBV |
| Timeline and historical context are available (prior incidents, trends, precedents). | N | Timeline / incident history / context brief | Historian / KM lead | TBV |
| Stakeholder and power map is available (who knows what, whose interests are served by which diagnosis). | N | Stakeholder map / power analysis | Programme lead | TBV |
| Diagnostic standards and decision reversibility are clear (what evidence would settle the diagnosis). | Y | Diagnostic brief with standards | Governance owner | TBV |
| Multi-lens diagnostic protocol will be followed (not single-lens). | Y | Protocol agreement / multi-lens plan | Lead analyst | TBV |
| Time and resources are allocated for appropriate diagnostic depth (Light or Full). | Y | Schedule; resourcing plan | Sponsor | TBV |

## 1.3 Definitions, Scope, and Non-Goals

**Definitions (operational):**
- Diagnosis: structured determination of what is happening and why, to a decision-relevant standard.
- Working diagnosis: provisional diagnosis used to guide immediate action, explicitly subject to revision.
- Confirmed diagnosis: diagnosis supported by sufficient convergent evidence and/or successful verification over time.
- Differential diagnosis: structured list of alternative explanations, ranked and ruled in/out.

**In scope:**
- Diagnostic approaches (six meta-categories) and diagnosis types (30)
- Process architecture and evidence collection under uncertainty
- Diagnostic error patterns, hiddens sources, and controls
- Diagnostic quality dimensions and interfaces to decision and learning
- Tiered Hiddens mapping as a systematic cross-check
- Evidence taxonomy, measurement pitfalls, and confidence calibration
- Multi-stakeholder and multi-perspective diagnostic synthesis

**Out of scope (by design):**
- Full domain-specific clinical/engineering/policy playbooks (Competencies framework addresses gaps)
- Full causal modelling (Causation framework provides deeper mechanism taxonomy)
- Full governance method (Governance/Responsibility specify the broader duty system)
- Intervention design (Interventions framework structures what to do after diagnosis)

## 1.4 Position in the Series (Upstream / Middle / Downstream)

- Upstream (signals/understanding): Situations; Evidence; Systems; Causation; Time; Scale; Realities; Dimensions; Perspectives
- Middle (this framework's role): Synthesise inputs into diagnostic hypotheses and conclusions with explicit uncertainty and residual hiddenness
- Downstream (action/governance): Decisions; Interventions; Governance; Responsibility; Risk; Learning & Adaptation

**Group assignment (Primary):** G5 — Epistemics & error-control (Epistemics)
**Group assignment (Secondary):** G2 — Structure, dependencies & mechanism (Mechanism)
**Stage assignment:** Middle (diagnosis is the epistemic hub connecting sensing to action)
**Run mode selection:** Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.10.1)
**Operating Guide routing:** Apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
**Non-conflation invariant:** Do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
**Iteration loop:** Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
**Framework Index:** This framework is one of 36 in the series (see OG v2.5 §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary (recommended)
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Descriptive | Situations, Realities, Systems, Processes | Situation typing; observable states; structural/causal maps; process flows | Diagnostic interpretation; what do these signals mean? What is the integrating explanation? |
| Epistemic | Evidence, Uncertainties, Hiddens, Beliefs, Metrics | Evidence quality; uncertainty specification; visibility barriers; cognitive mechanisms; proxy validity | Differential maintenance; hypothesis testing discipline; meta-diagnosis (where is our diagnosis weak?) |
| Normative | Values, Governance, Responsibility, Legitimacy, Accountability | Values and norms operative; governance structures and duties; authority and legitimacy; accountability lines | Who is responsible for diagnosis? What standard applies? Is the diagnosis politically safe or necessary? |
| Action | Causation, Decisions, Interventions, Risk, Time, Resources | Causal hypotheses and mechanisms; decision options; intervention levers; risk scenarios; feasibility; resource constraints | Causal diagnosis; actionable diagnosis; diagnosis linked to specific levers; scenario dependency. |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Diagnosis_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Diagnosis when… | Use neighbour instead when… |
|---|---|---|
| Evidence | Multiple competing explanations exist and must be tested to reduce decision-critical uncertainty. | Evidence quality, provenance, and confidence calibration are the sole focus; hypothesis generation is not needed. |
| Situations | What is happening requires multi-lens explanation (causal + functional + relational + contextual) beyond pure situation typing. | Situation typing and framing are sufficient; deeper causal or relational diagnosis is not required. |
| Systems | Understanding how designed artefacts, structures, and dependencies operate is needed to diagnose causation and functional fit. | Systems structure alone is the goal; diagnosis and actionability are not required. |
| Causation | Proximal mechanisms, root causes, and causal pathways must be tested and distinguished from correlation. | Full causal modelling, counterfactual depth, or mechanism taxonomy beyond diagnostic necessity is the goal. |
| Power & Incentives | Relational diagnosis must account for who benefits from which diagnosis; political filtering of truth is suspected. | Power distribution and incentive structure independent of diagnostic filtering is the focus. |

### 1.6.3 Routing triggers
- Diagnosis is needed to reduce decision-critical uncertainty under time pressure and incomplete evidence
- Multiple stakeholders disagree on "what is happening" or competing diagnoses are actively contested
- Incident triage: must rapidly determine type, urgency, and routing to appropriate expertise
- Failed intervention: prior actions did not produce expected effects; misdiagnosis is suspected
- Diagnostic momentum suspected: an early diagnosis has locked in despite disconfirming evidence
- Repeat failures indicate diagnosis failure, not only execution failure; root explanation needed
- Evidence is contested, fragmented, or politically filtered; multi-perspective reconciliation required
- High-consequence decision required; diagnostic quality audit (accuracy/timeliness/robustness) is mandatory
- Premature closure risk: must surface must-not-miss hypotheses and alternatives before action
- Hiddens or distortion suspected: framing capture, narrative stabilisation, or channel myopia may hide truth

---

# 2. Meta-Categories of Diagnosis (Six Approaches)

## 2.1 Meta-Categories Table (mandatory)
| # | Meta-category | Core question | Primary diagnostic approach | Focus | Typical artefacts/examples |
|---|---|---|---|---|---|
| I | Classificatory | What category or type does this belong to? | Taxonomy matching; pattern recognition; differential classification. | Naming and categorising the focal phenomenon; enabling appropriate playbooks. | Classification decision trees; differential sets; type criteria. |
| II | Causal | What is causing or driving this? | Mechanism identification; counterfactual testing; process-tracing. | Determining root/proximal/contributing causes; breaking chains. | Causal maps; mechanism hypotheses; counterfactual tests; strength assessments. |
| III | Functional | What is this thing for, and is it working as designed? | Design specification testing; functional fit assessment; performance audit. | Whether a system/process is serving its intended purpose; misalignment diagnosis. | Design specifications; performance data; functional fit assessments. |
| IV | Relational | How do entities interact, and what misalignments, conflicts, or coordination failures exist? | Power/incentive mapping; structural dependency analysis; relation diagnosis. | Detecting breakdowns in relationships, incentives, and coordination. | Stakeholder maps; power/incentive analyses; coordination failure diagnoses. |
| V | Prognostic | What is likely to happen next, and on what trajectory? | Time series analysis; scenario modelling; early warning; trend extrapolation. | Determining future states and consequence pathways given current conditions. | Scenarios; trajectory models; early warning indicators; leading indicators. |
| VI | Contextual | What environmental and normative factors constrain or enable this? | Context scoping; boundary analysis; structural constraint mapping. | Determining what is in/out of scope; what constraints apply; what is taken as given. | Boundary statements; context maps; constraint registers; assumption audits. |

## 2.2 Meta-Category Descriptions (recommended)

### I. Classificatory Diagnosis
Determining what category or type a phenomenon belongs to. This is the fastest form of diagnosis and is often the entry point ("it's a hardware failure, not a software bug"). Classificatory diagnosis enables quick routing to appropriate playbooks and expertise. Risk: over-reliance on pattern matching without deeper causal or contextual investigation.

### II. Causal Diagnosis
Determining what is causing the situation—root causes, proximal mechanisms, contributing factors, and chain-of-causation. Causal diagnosis answers "why is this happening?" and is essential for durable intervention. Risk: confusing causation with correlation; overstating mechanism certainty; treating systemic causes as individual failures.

### III. Functional Diagnosis
Determining whether something is working as designed and performing its intended function. This includes systems, processes, roles, and relationships. Functional diagnosis bridges classification (what is it?) and causation (why is it not working?). Risk: accepting design specifications as immutable rather than questioning whether the design itself is adequate.

### IV. Relational Diagnosis
Determining how entities interact and what coordination failures, conflicts, or incentive misalignments exist. This includes power dynamics, stakeholder positions, and alignment problems. Relational diagnosis is often the missing lens in technical analyses. Risk: attributing relational failures to individual competency or character rather than systemic structure.

### V. Prognostic Diagnosis
Determining what is likely to happen next—trajectory, scenario, and consequence pathways. Prognostic diagnosis is essential for risk assessment and intervention prioritisation. Risk: extrapolating from limited data; ignoring regime change and tipping points; treating best-case scenarios as likely.

### VI. Contextual Diagnosis
Determining what environmental, organisational, political, and normative constraints are operative. Contextual diagnosis answers "what is the landscape in which this situation sits?" and flags what is taken as given vs what is changeable. Risk: treating context as immutable; failing to recognise when context has shifted.

---

# 3. Thirty Core Diagnosis Types

## 3.1 Diagnosis Types Table (core reference)
| Meta-cat. | Type # | Diagnosis type | Description | Key questions | Red flags |
|---|---|---|---|---|---|
| I. Classificatory | 1 | Type/Category Match | The phenomenon belongs to a known category enabling playbook routing. | Does the pattern fit? Are all key features present? Is there a standard response? | Premature type matching; ignoring atypical features; wrong category selected. |
| I. Classificatory | 2 | Novel/Unclassified | The phenomenon does not fit known categories; new categorisation may be needed. | What makes this atypical? What new categories might apply? Has the landscape changed? | Treating novel cases as familiar; refusing to name new phenomena. |
| I. Classificatory | 3 | Hybrid/Multi-Type | The phenomenon exhibits features of multiple categories; multiple diagnoses are valid. | Which types are present? How do they interact? What is primary vs secondary? | False choice between alternatives; ignoring the hybrid nature. |
| I. Classificatory | 4 | Misclassification | An earlier, stuck diagnosis is wrong; the case has been mislabeled and routed incorrectly. | What evidence contradicts the earlier classification? What is the correct type? How did mislabeling persist? | Diagnosis momentum; fear of admitting earlier errors; sunk-cost thinking. |
| I. Classificatory | 5 | Type Transition | The phenomenon is changing type (routine → crisis; stable → degrading; technical → socio-political). | What evidence signals a type shift? What is the new type emerging? What triggers the transition? | Missing transition signals; stale classifications as situations drift. |
| II. Causal | 6 | Root Cause | A fundamental cause, often structural or historical, that explains the current state. | What is the deepest level of causation? What structural pattern drives recurrence? | Stopping at proximal causes; attributing systemic failures to individual error. |
| II. Causal | 7 | Proximal Cause | An immediate trigger or direct driver, distinct from root cause. | What directly precipitated this? What was the last straw? | Confusing proximal and root; treating symptoms as causes. |
| II. Causal | 8 | Contributing Factor | A factor that worsens, amplifies, or enables the main cause but is not itself sufficient. | What made the cause more damaging? What amplified the effect? | Dismissing minor factors; over-aggregating small effects. |
| II. Causal | 9 | System/Process Failure | A breakdown in a designed system or process, often due to poor design, absence of control, or degradation. | What process failed? Was it designed adequately? Was the failure in design or execution? | Treating process failures as individual lapses; failure to improve the process. |
| II. Causal | 10 | Absence of Cause | The expected cause is not present; something is happening that should not happen, or something usual is missing. | What was expected but is absent? What explains the puzzle? | Over-specification of absence; treating null results as proof of nothing. |
| III. Functional | 11 | Design Misfit | The system is not fit for its stated purpose; design is inadequate or assumptions have changed. | Does the design match the requirement? Has the context changed? What is the gap? | Blaming operation/execution rather than design; treating design as immutable. |
| III. Functional | 12 | Operational Deviation | The system is operating outside design parameters; execution has drifted from specification. | What is the deviation? Why is it happening? Is it justified or error? | Tolerance creep; normalising drift; accepting deviation as unavoidable. |
| III. Functional | 13 | Interface Failure | The dysfunction is at a boundary between subsystems or roles, not within them. | Where do entities meet and fail? What is lost in the handoff? | Blaming one side; ignoring the interface structure. |
| III. Functional | 14 | Latency / Timing Mismatch | The system components operate at incompatible timescales; inputs arrive too early or too late. | What is out of sync? What is the required cadence? What is the actual cadence? | Treating timing as a minor issue; ignoring cascade triggers. |
| III. Functional | 15 | Inadequate Feedback | The system lacks feedback loops necessary for self-correction or learning. | What should be measured and fed back? What feedback is missing? Why? | Treating feedback as optional; under-investing in measurement. |
| IV. Relational | 16 | Incentive Misalignment | Individuals or groups are optimising for metrics/rewards that do not align with desired outcomes. | What are people actually optimising for? What behaviour does this create? How is it misaligned? | Assuming people are evil rather than systemically misaligned; dismissing incentive leverage. |
| IV. Relational | 17 | Power Asymmetry / Dominance | One party has disproportionate control; others are dependent or subordinate; true consent or buy-in is absent. | Who holds power? How is it used? What is the impact on others' agency? | Treating power as immoral rather than structural; ignoring structural dominance. |
| IV. Relational | 18 | Coordination Failure | Multiple entities are not adequately integrated; their actions are misaligned, duplicative, or contradictory. | What should be coordinated? What is the coordination problem? Why can't they align? | Blaming individuals rather than the coordination structure; over-complexity of alignment. |
| IV. Relational | 19 | Role Confusion / Overlap | Roles or responsibilities are ambiguous, overlapping, or contested; unclear who is accountable. | What is the expected role structure? What is the actual structure? Where is ambiguity? | Accepting vagueness as necessary; under-documenting roles. |
| IV. Relational | 20 | Relationship Breakdown | Trust, communication, or cooperation has degraded between parties; repair may be possible or relationships may be irreparable. | What was the relationship? What broke it? Is repair possible? | Assuming relationships cannot be repaired; investing in repair without structural change. |
| V. Prognostic | 21 | Trend / Trajectory | The situation is on a clear trajectory (improving, degrading, cyclical); extrapolation and scenario planning follow. | What is the direction and rate? What are leading indicators? What are the endpoints? | Extrapolating from limited data; ignoring inflection points and regime change. |
| V. Prognostic | 22 | Tipping Point / Cascade | The situation is approaching a threshold beyond which dynamics change dramatically. | What is the threshold? How close are we? What triggers a cascade? | Treating non-linearity as unlikely; under-weighting tail scenarios. |
| V. Prognostic | 23 | Cycle / Recurrence | The situation is repeating a known pattern; prior cycles can inform prediction. | What is the cycle? What are the phases? What breaks the cycle? | Treating each instance as novel; ignoring institutional memory. |
| V. Prognostic | 24 | Uncertainty / Emergence | The future state is radically uncertain and cannot be predicted from current conditions; emergence may occur. | What is unknowable? What are the uncertainties? What could emerge? | Over-confidence in prediction; under-weighting genuine Knightian uncertainty. |
| V. Prognostic | 25 | Scenario Plurality | Multiple distinct futures are plausible depending on decisions, events, or context changes; no single prediction is adequate. | What are the scenarios? What are the triggers? What are the implications? | False certainty; dismissing alternative scenarios. |
| VI. Contextual | 26 | Constraint / Boundary | External constraints limit what is possible; they are structural and difficult to override. | What is constrained? By what? Is the constraint really external or can it be changed? | Treating constraints as immutable when they are actually changeable. |
| VI. Contextual | 27 | Assumption / Paradigm | The situation rests on unstated assumptions about how things work; changing the assumption changes everything. | What is assumed to be true? Is it actually true? What changes if we drop the assumption? | Treating assumptions as facts; failing to test paradigm assumptions. |
| VI. Contextual | 28 | Norm / Cultural | Norms, values, or cultural patterns are driving or constraining behaviour; changing norms requires different approaches. | What norms are operative? Are they adaptive? Can they change? How? | Treating norms as immutable; under-estimating cultural leverage. |
| VI. Contextual | 29 | Resource / Capacity | Resources are insufficient or poorly allocated; scarcity is the binding constraint. | What resources are needed? What is available? What is the gap? Can it be closed? | Assuming scarcity is absolute; under-estimating reallocation leverage. |
| VI. Contextual | 30 | Boundary Shift | What was previously out-of-scope has become in-scope, or vice versa; the situation itself has been redefined. | What is the new boundary? What crossed it? What are the implications? | Resisting boundary expansion; under-recognising domain shifts. |

---

# 4. Process Architecture (Diagnostic Phases)

## 4.1 Diagnostic Process Phases Table (recommended)
| Phase | Key question | Typical activities | Common risks of error | Hiddens operative |
|---|---|---|---|---|
| 1. Presentation | What is initially apparent? | Capture first reports, visible signs, complaints, alerts, anomaly flags. | Anchoring on the first story; framing by the loudest stakeholder; availability bias. | Hidden-8 (Framing); Hidden-21 (Positional); Hidden-24 (Contextual Blindness). |
| 2. History | How did this arise over time? | Timeline reconstruction, prior events, changes, exposures, interventions. | Selective memory; neglect of base rates and background conditions; post-hoc storytelling. | Hidden-15 (Latency); Hidden-7 (Mirage); Hidden-23 (Narrative). |
| 3. Examination | What can be observed systematically now? | Structured observation, measurement, inspection, mapping of states. | Confirmation bias in what is examined; over-reliance on one channel; measurement error. | Hidden-6 (Distortion); Hidden-14 (Fragmentation); Hidden-13 (Noise). |
| 4. Investigation | What tests or probes are needed? | Designing and running tests, experiments, simulations, targeted inquiries. | Over-testing or under-testing; choosing tests that cannot discriminate; false positives/negatives. | Hidden-10 (Model Blindness); Hidden-17 (Performance Theatre). |
| 5. Differential | What are the main possibilities? | Listing hypotheses, ranking by likelihood and risk, planning rule-in/out. | Premature narrowing; failure to include must-not-miss hypotheses; confirmation bias. | Hidden-8 (Framing); Hidden-25 (Perspectival); Hidden-10 (Model Blindness). |
| 6. Synthesis | What best explains the evidence? | Integrating evidence, reconciling conflicts, forming a working diagnosis. | Overfitting a favourite story; ignoring disconfirming evidence; narrative momentum. | Hidden-6 (Distortion); Hidden-23 (Narrative); Hidden-21 (Positional). |
| 7. Verification | How can this be confirmed or falsified? | Follow-up tests, trial interventions, stress tests, cross-checks. | Diagnosis momentum; resistance to revising a labelled case; confirmation bias. | Hidden-15 (Latency); Hidden-11 (Secret). |
| 8. Revision | How should the diagnosis change over time? | Updating diagnoses with new evidence; documenting changes; learning. | Lock-in; failing to revisit assumptions; weak feedback into practice. | Hidden-14 (Fragmentation); Hidden-4 (Concealment); Hidden-3 (Inattention). |

---

# 5. Evidence and Context Taxonomy

## 5.1 Diagnostic Dynamics (recommended)

| Pattern | Description | Causes | Consequence | Remedy |
|---|---|---|---|---|
| Iterative hypothesis refinement | Differential narrows over cycles; hypotheses updated with evidence; explicit 'working' vs 'confirmed' status. | Diagnosis progresses by cycling between hypothesis generation, evidence gathering, and synthesis; revisions should be expected and governed. | Prevents premature closure; enables learning; supports action under uncertainty. | Use explicit differentials; time-box investigation loops; require disconfirming evidence checks. |
| Escalation and triage under time pressure | Shift from depth to speed; reliance on heuristics; risk of missed/misclassified cases increases. | High tempo compresses evidence collection and synthesis; triage decisions dominate and may become sticky. | Determines whether action arrives before harm escalates; shapes error profile. | Define must-not-miss red flags; escalation SLAs; second-look checkpoints after stabilisation. |
| Information filtering and narrative stabilization | A story becomes 'the official diagnosis'; contrary evidence is downweighted or excluded. | Social and organisational pressures select a coherent narrative, often aligned to incentives, power, or legitimacy needs. | Locks in wrong explanations and weak interventions; drives scapegoating. | Independent review; protected dissent channels; evidence provenance and adversarial testing. |
| Diagnostic drift and baseline shift | What counts as 'normal' changes over time; anomalies become routine; detection thresholds creep. | Repeated exposure and operational pressure normalise deviations; measurement and attention adapt to the new baseline. | Creates latent risk accumulation and late discovery; degrades governance. | Baseline audits; periodic recalibration; near-miss sampling; drift indicators. |
| Learning loops and calibration over time | Back-testing, outcome tracking, and feedback update the diagnostic playbook; error rates fall. | Systems improve when diagnostic outcomes are measured, reviewed, and used to update criteria, models, and training. | Avoids institutional amnesia; increases robustness and trust. | Outcome tracking; post-mortems; library of exemplars; governance for playbook updates. |

## 5.2 Evidence Types and Pitfalls (recommended)
| Evidence type | Description | Typical sources | Diagnostic pitfalls | Mitigation |
|---|---|---|---|---|
| Signs | Objective, observable indicators. | Instrument readings, logs, physical findings, behavioural traces, metrics. | Mis-calibrated instruments; misperception; ignoring base rates; measurement error. | Triangulation; baseline audits; calibration checks; alternative instrumentation. |
| Symptoms | Subjective reports of experience. | Stakeholder narratives, complaints, self-reports, "how it feels". | Framing effects; exaggeration or minimisation; cultural coding; incentive distortion. | Multiple perspectives; protected dissent; separating observation from interpretation. |
| Test results | Elicited evidence from designed probes. | Clinical tests, simulations, load tests, audits, surveys, experiments. | False positives/negatives; test validity; misinterpretation; publication bias. | Repeat tests; sensitivity/specificity documentation; blinding where possible. |
| Historical patterns | Temporal and situational context. | Timelines, past incidents, version history, maintenance logs, policy changes. | Post-hoc storytelling; hindsight bias; ignoring structural trends; selective memory. | Document contemporaneously; use records; timeline triangulation; base-rate analysis. |
| Contextual factors | Environmental and system conditions. | Organisational structure, incentives, norms, regulation, markets, physical environment. | Treating context as fixed; ignoring hidden constraints and power; system boundaries. | Context mapping; constraint audit; stakeholder mapping; scenario analysis. |

---

# 6. Diagnostic Quality Dimensions

## 6.1 Quality Dimensions Table (mandatory)
| Quality dimension | Definition | How to assess | Why it matters | Typical failure mode |
|---|---|---|---|---|
| Accuracy | Does the diagnosis correctly represent what is actually happening? | Test against outcome; independent review; mechanism validation; base-rate calibration. | Wrong diagnosis drives wrong interventions and wasted effort. | Over-confidence in diagnosis; ignoring disconfirming evidence. |
| Timeliness | Is the diagnosis reached early enough to matter for decision-making? | Compare time-to-diagnosis with decision window; check for early-warning signals missed. | Late diagnosis is useless; early diagnosis enables prevention. | Rushing to early diagnosis vs waiting for full certainty. |
| Explainability | Can the diagnosis be understood, explained, and reproduced by others? | Check clarity of reasoning; document assumptions; test narrative comprehension. | Unexplainable diagnoses cannot be acted on, learned from, or challenged. | Over-technical language; narrative gaps; hidden assumptions. |
| Robustness | Does the diagnosis hold up under stress, new evidence, or reasonable alternative scenarios? | Stress-test against counter-evidence; check sensitivity to key assumptions; scenario test. | Fragile diagnoses collapse when conditions change or new data arrives. | Over-fitting to current data; ignoring uncertainty; single-lens bias. |
| Actionability | Does the diagnosis enable specific, feasible interventions with predicted outcomes? | Map diagnosis → causal pathway → intervention lever → expected effect. | Un-actionable diagnosis is academic; actionable diagnosis guides change. | Over-specificity (false precision); under-specificity (no clear action); disconnect from levers. |

---

# 7. Interface Types

## 7.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | Evidence Interface | How observations and data enter diagnosis. | What evidence exists? How strong is it? How was it generated? How is it biased? | Telemetry, logs, interviews, sampling plans, chain-of-custody, evidence admissibility rules, data provenance. |
| B | Decision Interface | How diagnoses link to choices and risks. | What decisions depend on this? What risk if we are wrong or late? What levers become available? | Triage decisions, escalation calls, resource allocation, intervention selection under uncertainty, monitoring plans. |
| C | Learning Interface | How diagnostic practice improves over time. | How often are we wrong? What patterns in misdiagnosis? What learning is captured? | Post-mortems, calibration reviews, playbook updates, training, metric redesign, outcome tracking. |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---|---|---|---|---|
| 1 | Premature Closure | Closing the case too early and locking in a favourite explanation; stopping at "good enough" rather than optimal. | Standard "second look" points; explicit working vs confirmed diagnoses; require evidence thresholds before closure. |
| 2 | Pattern Dominance | Letting familiar patterns override conflicting evidence; recognising only what fits existing templates. | Structured checklists; require explicit "does not fit" notes; red-team against pattern matching. |
| 3 | Channel Myopia | Over-reliance on one evidence channel (metrics, stories, technical telemetry, etc.); tunnel vision. | Multi-source evidence reviews; cross-functional incident reviews; mandatory perspective rotation. |
| 4 | Feedback Starvation | Lack of robust outcome feedback to diagnostic systems; learning loops not embedded. | Track diagnostic outcomes; audit misdiagnoses; feed learning back into practice; calibration audits. |
| 5 | Base-rate and denominator neglect | Misinterpreting frequency, risk, or anomaly strength because base rates and denominators are unspecified or wrong. | Require base-rate statements; use calibrated priors; report rates with denominators and confidence bounds. |
| 6 | Political capture of diagnosis | Diagnosis becomes aligned to institutional comfort, power, or reputational protection rather than truthfulness. | Independent governance; protected dissent; evidence provenance audits; rotate reviewers; separate explanation from blame. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)
| Hiddens meta-category (I–VI) | Why it may be active in diagnosis | Typical symptoms | Default checks to run |
|---|---|---|---|---|
| I Perceptual | Attention and salience bias what is noticed and recorded. | Weak signals missed; "obvious in hindsight"; salient features over-weighted. | Coverage audit; near-miss sampling; fresh-eyes review; reverse-brainstorm. |
| II Systemic | Models/frames create false coherence; aggregation hides tails; simplification obscures mechanisms. | Stable wrong story; repeated surprises; tidy narrative despite messy reality. | Alternative framings; disaggregation; scenario tests; model audit. |
| III Informational | Evidence is filtered, fragmented, delayed, or concealed. | Conflicting accounts; missing logs; late escalation; access barriers. | Source-independence tests; access audits; chain-of-custody review; triangulation. |
| IV Temporal | Drift and delayed harm are under-analysed; history is forgotten; latency masks causation. | Repeat failures; "new" old problems; drift not detected until crisis. | Timeline reconstruction; drift indicators; retrieval drills; leading indicator audit. |
| V Relational | Power and position filter whose evidence counts; some voices are marginalised. | HQ vs frontline disagreement; scapegoating; blame assigned by power not logic. | Multi-level inquiry; safe disclosure channels; perspective rotation; political mapping. |
| VI Ontological | New phenomena lack categories, so hypotheses never form; conceptual gaps prevent naming. | Persistent anomalies; inability to name mechanism; "we've never seen this before." | Category-creation workshop; external analogies; robustness planning; mental model audit. |

## 8.3 Hiddens Crosswalk (Tier 2 – default mapping layer)
| Hidden type (ID + name) | Relevance | Mechanism | Detectability | Agency | Consequence | Detection interface(s) | Remediation interface(s) | Interaction notes |
|---|---|---|---|---|---|---|---|---|
| 8 Framing | H | Scope and interpretation bias determine which hypotheses are even considered. | Medium | Mixed | High | Reframe prompts; 'what's out of frame?' review | Broaden scope; include excluded stakeholders; multiple framings. | Framing + Narrative stabilisation → Diagnosis locked in. |
| 6 Distortion | H | Measurement/method biases corrupt the evidence pipeline. | Medium | Structural | High | Calibration; alternative measurement; disaggregation. | Improve instrumentation; triangulate; redefine KPIs. | Distortion sustains misdiagnosis across cycles. |
| 10 Model Blindness | M–H | Simplified diagnostic model omits key variables or interactions. | Medium | Mixed | High | Red-team; counterexamples; model audit. | Update models; add variables; governance reset. | Model blindness sustains cognitive closure. |
| 7 Mirage | M | Self-consistent illusion stabilised by reporting and incentives. | Low–Medium | Mixed | High | Independent audits; adversarial testing; ground truth sampling. | Decouple incentives; redesign reporting; accountability shifts. | Mirage delays action and locks in direction. |
| 14 Fragmentation | M–H | Evidence is distributed across silos; no end-to-end picture exists. | High | Structural | High | End-to-end tracing; source-independence tests. | Interface ownership; shared repositories; standards. | Fragmentation increases positional disagreement. |
| 15 Latency | M–H | Delays in sensing, reporting, or escalation make diagnoses late. | Medium | Structural | High | Timeliness audit; escalation-path test. | Shorten loops; early warning indicators; automation. | Latency + Narrative → diagnosis never revisited. |
| 21 Positional | H | What is visible depends on role; frontline vs HQ see different realities. | Medium | Structural | High | Multi-level inquiry; frontline sampling. | Rotate observers; safe reporting; two-key reviews. | Positional + power → only powerful version heard. |
| 25 Perspectival | H | Single viewpoint constrains hypothesis space and interpretation. | Medium | Structural | High | Perspective rotation; external reviewers. | Embed plural perspectives; structured challenge. | Perspectival lock-in sustains premature closure. |
| 11 Secret | M | Strategic concealment blocks evidence and distorts narratives. | Medium | Adversarial | High | Access audits; chain-of-custody; privileged interviews. | Protected disclosure; sanctions; transparency governance. | Secret enables misdirection and scapegoating. |
| 13 Noise | M | Signal drowning or weaponised uncertainty impairs synthesis. | Medium | Mixed | Medium–High | Signal-to-noise review; anomaly detection. | Channel hygiene; triage; prioritisation rules. | Noise accelerates closure and creates fatigue. |

## 8.4 Targeted Hiddens Discovery Scans (Tier 2 escalation routing)
When Tier 1 symptoms indicate a specific hiding mechanism from the above set, escalate to the appropriate targeted scan from OG v2.5 §7.5. Example scans:
- **Social/Organisational family:** Group-think, Consensus Bias, Pluralistic Ignorance, Abilene Paradox, Reputation Protection.
- **Structural/Systemic family:** Metric Gaming, Performance Theatre, Coupling/Cascade Dynamics, Regime Blindness, Boundary Instability.
- **Temporal family:** Drift Acceleration, Latency Amplification, Cycle Invisibility, Forgotten History, Obsolete Models.
- **Action-Induced family:** Intervention Paradox, Iatrogenic Harm, Escalation Spiral, Side-Effect Amplification, Unintended Consequences.

For scan selection, use the Triage Matrix in OG v2.5 §7.5.3.

## 8.5 Embedded Hiddens Micro-Protocol (standard prompts)
1) Run Tier 1 scan across all six Hiddens meta-categories early and again pre-closure (assume hiddens exist).
2) Shortlist relevant Hidden types (Tier 2) and rate detectability, agency, and consequence.
3) Assign detection and remediation moves for each high-consequence hidden; map interaction chains (e.g., Framing + Pattern Dominance → Narrative Stabilisation → Diagnosis Lock-In).
4) Re-run hiddens source analysis; document residual unknowns and escalation triggers.

## 8.6 Escalation Rule (Tier 3 – full Hiddens run)
Escalate to a full 30-type Hiddens scan + detection/remediation matrix mapping if any apply:
- High consequence (safety, systemic resilience, regulatory exposure, cascade potential).
- Strong incentives to conceal, mislead, or to perform compliance theatre.
- Persistent disagreement about "what is happening" across roles, levels, or organisations.
- Repeat failures despite multiple prior diagnostic efforts (diagnostic failure pattern).
- Evidence of cascade dynamics (Fragmentation + Latency + Narrative Stabilisation).
- Diagnosis is being politically weaponised or is driving scapegoating.

---

# 9. Application Protocol (mandatory)

## 9.1 Diagnostic Application Steps (series-standard 6-step protocol)
| Step # | Step name | Action | Outputs / artefacts |
|---|---|---|---|---|
| 1 | Frame the diagnostic question and stakes | Define what must be decided, the acceptable error/latency, and the audience. Establish scope and boundaries; specify urgency and consequence. Standard: specify diagnostic standard (accuracy? speed? explainability?). | Diagnostic question statement; stakes and urgency profile; scope/boundary definition; initial hypotheses constraints; diagnostic standard brief. |
| 2 | Collect evidence and map stakeholders | Inventory evidence types (signs, symptoms, tests, narratives, context). Map who is affected and who supplies/filters evidence; reconcile timebases and access. Assess evidence quality and identify gaps. | Evidence inventory + confidence notes; stakeholder/evidence map; evidence provenance and access notes; information gaps list. |
| 3 | Generate differentials using the 30-type taxonomy | Scan the six meta-categories and map candidate diagnosis types; maintain an explicit differential list (including must-not-miss and 'benign' options). Use systematic taxonomy search. | Differential set (mapped to meta-categories and types); 30-type classification map; "why not this diagnosis" rationale; missing-lens list. |
| 4 | Test, refine, and synthesise | Use the diagnostic process phases to gather discriminating evidence, test counterfactuals, and converge to a working diagnosis with uncertainty explicitly stated. Link causal, functional, relational, and contextual elements. | Working diagnosis + uncertainty bounds; causal/functional/relational/context notes; evidence gaps and test plan; decision implications. |
| 5 | Quality, interfaces, and Hiddens Source Analysis | Evaluate diagnostic quality dimensions; analyse interfaces (evidence/decision/learning); run hiddens sources and tiered Hiddens scan; decide on escalation. | Quality scorecard; interface risk map; hiddens source register; Hiddens shortlist with detection/remediation; escalation decision + routing. |
| 6 | Decide, intervene, and learn | Link the diagnosis to decisions/interventions and monitoring. Set review points and feedback loops; back-test outcomes; update playbooks. Document learning and close or escalate. | Decision and intervention plan; monitoring/indicator set; learning loop plan; playbook update backlog; closure note or escalation rationale. |

## 9.2 Standard Deliverables (recommended)
**Minimum deliverable (2–3 pages):**
- Working diagnosis + explicit uncertainty and confidence bounds
- Differential set (incl. must-not-miss) mapped to meta-categories and types
- Evidence plan (what to collect next and why) with provenance notes
- Quality scorecard (accuracy/timeliness/explainability/robustness/actionability)
- Hiddens shortlist (6–12) with detection/remediation moves
- Decision implications (what actions now; what monitoring; what review point)

**Full deliverable pack:**
- Full process-architecture log (phases completed, evidence gathered, revisions, decision points)
- Diagnostic source register and controls executed
- Calibration pack: back-testing and learning-loop updates
- Governance and responsibility updates for escalation, monitoring, and learning
- Multi-perspective diagnostic synthesis (where stakeholders agree/disagree, power effects noted)

---

# 10. Framework Principles (mandatory)

## 10.1 Principles Table
| Principle name | Description |
|---|---|
| 1. Multiple Lenses, One Decision | Apply several diagnostic approaches (classificatory, causal, functional, relational, prognostic, contextual) to reach a working diagnosis that is robust and multi-perspectival. Single-lens bias produces fragile conclusions. |
| 2. Explicit Differentials | Always maintain a visible list of plausible alternatives, including must-not-miss diagnoses and "it might be nothing" options; avoid premature closure through deliberate hypothesis generation and testing. |
| 3. Proportional Depth & Effort | Match diagnostic depth (Light/Full) and time allocation to stakes, reversibility, evidence quality, and cost of delay; avoid over-analysis on trivial cases and under-analysis on high-stakes cases. |
| 4. Evidence-Aware Skepticism | Demand sufficient evidence and mechanism clarity appropriate to decision stakes; accept residual uncertainty where further investigation is not cost-justified or time-feasible; distinguish fact from interpretation. |
| 5. Revisability as a Feature | Treat diagnoses as versioned and explicitly revisable as new evidence emerges or conditions change; reward justified diagnosis changes rather than punishing them as failures; embed learning. |
| 6. Action Coupling | Link diagnosis to specific, feasible interventions with clear causal pathways and predicted outcomes; avoid diagnosis-for-diagnosis'-sake; keep diagnosis decision-oriented. |
| 7. Transparency & Accountability | Make diagnostic reasoning visible; record assumptions and uncertainties; separate explanation from blame; enable challenge and learning; track who diagnosed and what happened. |

---

# 11. Glossary (local domain terms)

## 11.1 Local domain glossary
| Term | Definition |
|---|---|
| Diagnosis | The structured act of determining what is happening in a case and why, to a decision-relevant standard. |
| Working diagnosis | A provisional diagnosis used to guide immediate action, explicitly labelled as subject to revision. |
| Confirmed diagnosis | A diagnosis supported by sufficient convergent evidence and/or successful verification over time. |
| Differential diagnosis | A structured list of alternative explanations to be considered, ranked, and ruled in/out. |
| Meta-diagnosis | Assessment of the diagnostic process itself, including quality, biases, politics, and reliability. |
| Signs | Objective, observable indicators relevant to diagnosis. |
| Symptoms | Subjective experiences or reports relevant to diagnosis. |
| Test | A designed probe or procedure that elicits evidence relevant to a diagnosis. |
| Premature closure | Stopping the diagnostic process too soon after finding a plausible explanation. |
| Diagnosis momentum | The tendency of an initial diagnosis to propagate uncritically through records, systems, or organisations. |
| Overdiagnosis | Labelling conditions or problems that would not cause harm and do not warrant intervention. |
| Underdiagnosis | Systematic failure to identify conditions or problems that do warrant attention. |
| Red-flag condition | A possibility that is unlikely but too dangerous to miss, and therefore must be actively ruled out. |
| Diagnostic quality | Conformity to the five quality dimensions: accuracy, timeliness, explainability, robustness, actionability. |
| Interface (diagnostic) | A boundary or zone of interaction between diagnosis and evidence systems, decision-makers, or learning loops. |
| Diagnostic drift | Gradual shift in what counts as normal; thresholds creep; anomalies become routine; detection erodes. |
| Diagnostic feedback loop | A system for tracking diagnostic outcomes, identifying errors, and updating diagnostic criteria/models. |

## 11.2 Core execution terms (pointer; do not restate)
- See **Analytical Series Operating Guide**, v2.5:
  - Core execution terms (mandatory): **§D.10.1**
  - Artefact terms (mandatory): **§D.10.2**
  - Full Operating Guide glossary: **§11** (§11.1–§11.9)
  - Hiddens Discovery Scans glossary: **§7.5.6** (also §11.7)

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v2.0 | 2026-04-06 | Rewrite for Master Template v2.3 alignment; updated all OG references from v1.5 to v2.5; added Introduction section (four subsections); expanded §1.6 with Tier 2 Hiddens crosswalk, Targeted Scans routing, and full Information Requests schema; updated Document Information with Tiered Hiddens Scan Model and Targeted Hiddens Discovery Scans fields; expanded §1.4 with Stage assignment, Framework Index pointer, and Iteration loop statement; added Group and Stage columns to framework integration references; updated §8 with Tier 2 structured deepening guidance and Targeted Scans escalation trigger; expanded all thin sections (Process Architecture, Evidence Taxonomy, Quality Dimensions); updated §11.2 pointer to OG v2.5; 800+ lines, complete content. (Revised: Anthropic Claude Opus 4.6) |
| v1.2 | 2026-03-28 | Series standard format; reformatted §10 Framework Principles as table; added mandatory Hiddens Source Analysis & tiered Hiddens cross-check; aligned application protocol to 6-step series standard. |
| v1.1 | 2026-03-27 | Added §7.3 integration entry for Framework of Beliefs; series count updated from 32 to 33 frameworks. |
| v1.0 | 2025-12-14 | Standardised rewrite to master template; enriched type cues and hidden-risk signatures; added mandatory Hiddens Source Analysis & tiered Hiddens cross-check; consolidated protocol to series-standard 6 steps. |

## 12.2 Integration Notes (optional)
Use this framework whenever:
- the organisation must act under uncertainty and time pressure,
- competing narratives exist about "what is happening,"
- repeat incidents suggest diagnostic failure (not only execution failure),
- evidence quality is disputed or likely distorted,
- diagnosis is politically contested or driving decisions that could cascade.

Treat Section 8 (Hiddens cross-check) as mandatory in high-stakes contexts and wherever diagnosis is politically contested or supporting high-consequence decisions.

---

*End of Document*
