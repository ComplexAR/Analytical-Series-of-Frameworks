# Framework of Diagnosis – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Diagnosis |
| Primary group | G5 — Epistemics & error-control (Epistemics) |
| Secondary group | G3 — Causation & systems (Causation) |
| Stage | Middle |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Diagnosis framework applies structured causal inference and root-cause analysis logic to move from observed symptoms or problems to defensible causal claims about root mechanisms. It classifies diagnostic reasoning types through six meta-categories and thirty core types, profiles diagnostic inference across five dimensions (evidence base, causal model, competing hypotheses, confidence calibration, reversibility), maps ten dynamics of how diagnoses form and persist, and surfaces diagnosis-specific visibility failures via tiered Hiddens scans. It enables hypothesis prioritisation by mechanism plausibility and evidence support, drives evidence gathering toward most-diagnostic tests, and produces decision-ready causal claims with explicit confidence calibration and remaining uncertainties.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Diagnosis when… | Use neighbour instead when… |
|---|---|---|
| Causation | You need to identify root mechanisms explaining symptoms and evaluate competing causal hypotheses; focus on inference logic and evidence weight | You need to map causal structures, test counterfactuals, and model intervention effects; focus on causal mechanisms independent of symptom explanation |
| Evidence | You need to assess what evidence supports causal claims and what Unknowns remain; focus on evidence-to-claim links | You need to inventory evidence types and weight overall support for focal claim; focus on evidence independent of causal logic |
| Failures | You need to identify cognitive or inferential failures contributing to misdiagnosis; focus on error mechanisms in diagnostic reasoning | You need to classify cognitive error types independent of diagnosis context; focus on error types in general |
| Systems | You need to trace how root causes couple with system structure and feedback loops that sustain them; focus on causal embedding in system | You need to analyse system dynamics and leverage points; focus on structure independent of root causality |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Diagnostic Information Types | Chief Complaint/Symptom, Historical Antecedent, Pattern Signature, Threshold Trigger, Outcome Consequent | What information forms the basis of diagnosis? |
| II. Causal Inference Pathways | Mechanism Explanation, Temporal Sequence, Analogical Precedent, Exclusion-by-Rule, Negative Evidence Chain | What form of causal reasoning supports this diagnosis? |
| III. Evidence Integration & Hypothesis Testing | Evidence Accumulation, Competing-Hypothesis Elimination, Threshold Testing, Disconfirming Test, Null-Result Interpretation | How is evidence marshalled to support or eliminate causal hypotheses? |
| IV. Root-Cause Embedding & System Coupling | Proximal Cause, Systemic Root, Structural Embedding, Incentive-Driven Cause, Coupled Multi-Factor Causality | Is the root cause an individual/discrete event or system property? |
| V. Diagnosis Persistence & Revision | Initial Diagnosis, Hypothesis Protection, Reframing, Diagnosis Reversal, Meta-Diagnosis | How stable is the diagnosis and what would cause revision? |
| VI. Diagnostic Confidence & Closure | High-Confidence Diagnosis, Provisional Diagnosis, Residual-Uncertainty Diagnosis, Differential Diagnosis, Non-Closure | How confident should we be in this diagnosis given evidence and Unknowns? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature | Mechanism | Consequence |
|---|---|---|---|
| Anchoring on initial hypothesis | Early diagnosis shapes subsequent evidence interpretation; disconfirming evidence reinterpreted to fit initial diagnosis; alternative hypotheses not seriously considered | Cognitive bias toward consistency; sunk cost in initial framing; social commitment to diagnosis | Persevering diagnosis despite contrary evidence; missed true root causes; prolonged mismanagement |
| Premature closure | Diagnosis declared complete despite substantive Unknowns or competing hypotheses not adequately tested | Pressure to decide; cost of continued investigation; confidence illusion; authority closure signal | Confident-but-wrong diagnosis; interventions fail because wrong root cause targeted; post-failure accountability confusion |
| Hypothesis multiplication without discrimination | Multiple competing hypotheses retained without clear prioritisation or discrimination; investigation scattered; no clear winner emerges | Difficulty of real root-cause analysis; pressure to appear balanced; lack of decisive evidence; investigation fatigue | Indecision; drift toward "more research needed"; lost opportunity for timely intervention; analysis paralysis |
| Evidence reinterpreted in light of new information | Same evidence reread with new frame; apparent support for hypothesis shifts as context changes; instability without new evidence | Framing shifts; paradigm changes; recontextualisation; new information provides new lens | Apparent diagnosis stability masks actual fragility; susceptibility to reinterpretation; confidence insufficient for stakes |
| Competing-diagnosis suppression | Alternative diagnoses surfaced but actively suppressed; majority diagnosis protected through selective attention and dismissive language | Consensus enforcement; retaliation risk for challenging diagnosis; power stakes in diagnosis; investment in current treatment | False consensus; minority diagnosis remains unexamined; opportunity for early course correction lost |
| Root-cause substitution | Diagnosis of proximal cause accepted when systemic root is unaddressed; solving for symptom management without root-cause remedy | Individual-level bias; systemic-cause attribution difficulty; power protection of system; sunk costs in proximal treatment | Recurrent symptoms despite treatment; root cause persists; long-term dysfunction; intervention fatigue and failure |
| Diagnosis-driven intervention failure | Intervention succeeds technically but fails to resolve problem because diagnosis was incomplete; reveals misdiagnosis | Intervention targeted proximal cause not root; root cause persists; system regenerates problem; coupled causes not addressed | Post-intervention failure; diagnosis loses credibility; sunk costs in intervention; escalated problem |
| Differential-diagnosis collapse | Competing diagnoses not maintained; single diagnosis treated as certain; alternatives dismissed rather than carried forward | Pressure for closure; cognitive load of maintaining alternatives; authority enforcement of single diagnosis | Risk of missing alternative if primary diagnosis inadequate; reduced flexibility for adaptive management |
| Diagnostic consensus distortion | Apparent consensus on diagnosis masks private doubt; group enforces diagnosis despite private uncertainty; public and private differ | Conformity pressure; retaliation risk for dissent; psychological safety erosion; identity stakes in diagnosis | Silent knowledge that diagnosis may be wrong; lost opportunity to revise; brittleness of shared approach |
| Systemic root-cause invisibility | Diagnosis focuses on individual or proximal cause while systemic root remains invisible; system carries on producing problem despite individual interventions | Individual-level bias; system-level causality difficulty; structural change cost; power protection of system | Individual-focused interventions fail; system generates new problems; root cause persists; cycle repeats |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question |
|---|---|
| I (Perceptual) | What symptoms or diagnostic information are being missed; what observable phenomena are unnoticed due to attention or salience bias? |
| II (Systemic) | How are systemic root causes embedded in structures, procedures, or incentive regimes; what is institutional rather than individual causality? |
| III (Informational) | What diagnostic information is gated, unavailable, or transformed in ways that hide causality; what measurement systems miss cause signals? |
| IV (Temporal) | What temporal patterns would reveal root cause but are not being tracked; what lag between cause and effect obscures causality? |
| V (Relational) | Who knows alternative diagnoses but remains silent; what dissent is suppressed; what power stakes protect current diagnosis? |
| VI (Ontological) | What diagnostic paradigm or framework makes certain root causes unthinkable; what causal models are foreclosed by current frame? |

### 6b. Primary Hiding Mechanisms

- Anchoring and hypothesis protection (initial diagnosis defended despite contrary evidence)
- Proximal-cause substitution (systemic root invisible; proximal cause mistaken for root)
- Diagnosis-driven evidence distortion (evidence interpreted to fit diagnosis rather than test it)
- Silent knowledge and dissent suppression (alternative diagnoses known but not voiced)
- Temporal pattern invisibility (causal sequences hidden by temporal distance or lag)
- Paradigm-bound diagnosis (alternative causal models outside current frame of thinkability)
- Consensus distortion (apparent agreement masks private doubt)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Systemic root cause suspected but invisible | Framework of Systems; Framework of Diagnosis (deeper analysis) | Systemic causal analysis; feedback-loop mapping; structural change design | Redesign for root-cause remediation; implement systemic intervention |
| Alternative diagnosis suppressed | Framework of Governance; Framework of Hiddens | Dissent protection; diagnosis-challenge protocols; second-opinion triggers | Establish legitimate alternative-diagnosis review; protect dissent channels |
| Premature diagnosis closure evident | Framework of Diagnosis (escalate to Full Depth) | Competing-hypothesis testing; discriminating test design; confidence calibration | Design most-diagnostic tests; delay closure until alternatives adequately tested |
| Diagnosis-intervention mismatch | Framework of Interventions; Framework of Diagnosis | Outcome monitoring; mechanism testing; causal-intervention alignment audit | Test whether intervention targets root cause; monitor outcome to reveal mismatch |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Surface focal problem or symptom; identify initial diagnosis or leading hypothesis; list competing alternative diagnoses (at least 2–3).
2. For leading hypothesis, identify 2–3 key pieces of supporting evidence and 1–2 key uncertainties or gaps.
3. Run Tier 1 Hiddens scan: check for anchoring on initial hypothesis, evidence distortion, suppressed alternatives, systemic-root invisibility.
4. For top 2 competing hypotheses, design single most-diagnostic test that would strongly favour one over the other.
5. Flag any systemic root-cause indicators for escalation to Systems or Governance frameworks.

### 7b. Full Depth Execution (Complete framework run)

1. Map diagnostic information space: identify chief complaint, historical antecedents, pattern signatures, threshold triggers, outcome consequents.
2. Enumerate all competing causal hypotheses (at least 4–6 alternatives); profile each by mechanism plausibility and evidential support.
3. Classify diagnostic reasoning type for leading hypothesis (mechanism explanation, temporal sequence, analogical precedent, exclusion, negative evidence); assess validity.
4. Evaluate evidence integration: what evidence supports each hypothesis; what disconfirms each; what Unknowns would discriminate.
5. Assess root-cause embedding: Is diagnosis anchored to proximal cause or systemic root; does system-level causality apply; are multiple factors coupled?
6. Run Tier 1 + Tier 2 Hiddens scan: for each meta-category, identify high-consequence diagnostic Hiddens; design detection (how to surface) and remediation (how to correct).
7. Produce competing-hypothesis matrix with evidence profiles, remaining tests, and confidence levels for each; prioritise by diagnostic power of next test.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hypothesis/Test Backlog | Record all competing hypotheses with evidence summary and most-diagnostic test for each; prioritise by test impact and feasibility | After hypothesis enumeration and evidence review |
| Hiddens Register | Add diagnosis-specific Hiddens; detection and remediation interfaces | After Tier 1 scan |
| Information Requests | Request diagnostic information and most-diagnostic test execution; prioritise by discriminating power | For top competing hypotheses |

**Gate Question (pre-closure check):** Have we enumerated competing hypotheses, assessed evidence for each, designed most-diagnostic discriminating tests, run Tier 1 Hiddens scan for anchoring/suppression/systemic-root-invisibility, and escalated systemic root causes to Systems/Governance frameworks?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs

- Symptoms/Problems (focal problem definition)
- Evidence (evidence supporting competing diagnoses)
- Causation (causal mechanisms and models)
- Failures (failure-specific diagnostic logic)
- Systems (system structure bearing on root-cause embedding)

### 8b. Downstream Handoffs

- Framework of Interventions (intervention design targeted to diagnosed root cause)
- Framework of Causation (deeper causal mechanism exploration)
- Framework of Systems (systemic root-cause remediation design)
- Framework of Governance (governance design for ongoing diagnosis maintenance)
- Framework of Learning & Adaptation (diagnostic learning and updating loops)

### 8c. Targeted Scans

| Targeted Scan | Role of this framework |
|---|---|
| Root-Cause Attribution Scan (Family A, Scan 1) | Surface anchoring on initial hypothesis; test competing causal hypotheses; expose suppressed alternatives |
| Systemic-Cause Invisibility Scan (Family C, Scan 1) | Identify systemic roots masked by proximal-cause focus; reveal structural causality |

---

*LLM Execution Extract v1.0 – Diagnosis Framework (2026-04-08) – End of Extract*
