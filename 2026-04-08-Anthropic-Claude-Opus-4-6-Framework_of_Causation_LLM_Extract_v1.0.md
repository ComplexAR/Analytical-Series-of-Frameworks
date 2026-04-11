# Framework of Causation – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Causation |
| Primary group | G2 — Structure, dependencies & mechanism (Mechanism) |
| Secondary group | G5 — Epistemics & error-control (Epistemics) |
| Stage | Core |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Causation framework models causal mechanisms in a scenario by identifying variables, mechanisms, and causal relationships across six meta-categories (Deterministic, Probabilistic, Agentic, Emergent, Systemic, Reflexive); characterizes causation along five dimensions (strength, temporal lag, scope, reversibility, manipulability); analyzes causal patterns (common cause, confounder, mediation, moderation); and surfaces causal Hiddens (hidden confounders, bidirectional causation, mechanism invisibility, non-linear interaction). It populates the Causation workspace, Evidence Ledger, and Hypothesis/Test Backlog with causal diagrams, intervention logic, and causal-validity threats, enabling identification of root causes and intervention leverage.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Causation when… | Use neighbour instead when… |
|---|---|---|
| Systems | You need to model causal mechanisms and feedback loops; focus is on cause-effect relationships and mechanisms. | You need to analyze system-level structure, emergence, and non-linear dynamics independent of specific causal mechanisms. |
| Time | You need to map temporal causal sequences and delays; focus is on temporal causation logic. | You need to analyze temporal dynamics and time-dependent phenomena independent of specific causal mechanisms. |
| Evidence | You need to design tests to validate causal claims; focus is on causal validity threats. | You need to audit evidence quality, provenance, and contradiction independent of causation. |
| Hiddens | You need to surface hidden confounders or mechanisms; focus is on causal visibility. | You need to analyze all six Hiddens meta-categories without focusing specifically on causation. |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Deterministic Causation | Mechanical Cause, Necessity, Sufficiency, Logical Implication, Physical Law, Constraint | What must happen; what rules out alternatives? |
| II. Probabilistic Causation | Stochastic Cause, Conditional Probability, Risk Factor, Protective Factor, Dose-Response, Statistical Association | What makes an outcome more or less likely? |
| III. Agentic Causation | Intention, Decision, Choice, Volition, Deliberation, Action-to-Effect | What did agents choose and why; how did choice cause outcome? |
| IV. Emergent Causation | Phase Transition, Threshold Effect, Tipping Point, Self-Organization, Nonlinear Interaction, Collective Behavior | What emerges from interaction that cannot be reduced to components? |
| V. Systemic Causation | Feedback Loop, Circular Causation, Mutual Causation, Bidirectional Effect, Reflexive Effect, Systemic Constraint | What causal loops and circular relationships drive outcomes? |
| VI. Reflexive Causation | Measurement Affecting Reality, Expectation Shaping Outcome, Self-Fulfilling Prophecy, Observer Effect, Participatory Causation | How does analysis and intervention shape what they measure? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Hidden Confounder | Apparent cause is actually spurious; third variable causes both; intervention targeting apparent cause fails. | Real cause is unmeasured or overlooked; focus narrows to salient variable; confounder is plausible alternative explanation. | Intervention ineffective; wrong target; missed root cause; cost wasted. |
| Bidirectional Causation | A causes B; B also causes A; cycle runs; direction of causation ambiguous; feedback loop. | Variables are mutually dependent; separation of cause/effect is conceptual not actual; simultaneity or feedback. | Intervention ambiguity; root cause elusive; intervention may destabilize; cycle may be self-reinforcing. |
| Mechanism Invisibility | Cause and effect are linked but mechanism is opaque; black box; no understanding of how cause produces effect. | Mechanism operates at unmeasured level or timescale; knowledge specialization hides mechanism; complexity obscures link. | Intervention misalignment; transfer to different context fails; brittleness if conditions change. |
| Threshold & Non-linear Causation | Effect absent until threshold crossed; then rapid change; cause-effect relationship is non-linear; linear models fail. | System has tipping point; phase transition; bifurcation; or multiplicative interaction; threshold lower than expected in some contexts. | Surprises at threshold crossing; linear extrapolation fails; preventive intervention ineffective below threshold. |
| Interaction & Moderation | Effect of A depends on level of B; moderation hides main effects; causes interact; univariate analysis misleading. | Heterogeneous effects; context-dependent causation; mechanism operates differently in different conditions; interaction unmeasured. | Main-effect intervention fails; context-dependent redesign needed; universal intervention inappropriate. |
| Mediation & Indirect Effect | A causes C indirectly through B; direct effect small; understanding mechanism requires identifying mediator. | Causal chain; B is mechanism linking A and C; path-dependent causation; direct intervention may miss mechanism. | Intervention targeting A may be ineffective if it doesn't affect B; mechanism understanding needed for transfer. |
| Reverse Causation & Outcome Bias | B causes A (reverse of apparent direction); or outcome-dependent reasoning causes reverse causal inference. | Temporal order ambiguous; simultaneity or feedback; or narrative bias in causal inference; hindsight bias drives reverse causation. | Root cause misidentified; intervention targets wrong direction; causal logic inverted. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What causal mechanisms or confounders are salient vs invisible from common positions? |
| II (Systemic) | How do causal mechanisms couple with institutions and systems; what feedback loops and circular causation are unmapped? |
| III (Informational) | What causal evidence is available vs missing; what data gaps prevent causal validity testing? |
| IV (Temporal) | What temporal lags in causation hide the cause-effect link; what long-lag mechanisms are unmeasured? |
| V (Relational) | Whose causal narrative is dominant; whose causal theories are suppressed; what power asymmetries hide alternative causal explanations? |
| VI (Ontological) | What causal categories are not yet conceivable; what emergent causal mechanisms are unnameable? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Hidden Confounder (spurious causation; third variable causes both apparent cause and effect)
- Bidirectional Causation (cause and effect loop; direction ambiguous)
- Mechanism Invisibility (link known but how it works is opaque)
- Non-linear Threshold (cause-effect relationship has tipping point; linear models fail)
- Interaction & Moderation (effect of A depends on B; heterogeneous effects)
- Mediation & Mechanism (A causes C indirectly through B; pathway matters)
- Reverse Causation (B causes A, not vice versa; temporal order ambiguous)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Intervention ineffective or backfire | Framework of Systems; Framework of Evidence | Confounder and mechanism audit; experimental design | Test for hidden confounders; clarify mechanism; run randomized trial. |
| Causal mechanism opaque | Framework of Hiddens; Framework of Evidence | Mechanism decomposition; process tracing; qualitative evidence | Study mechanism in detail; trace causal pathway; interview actors. |
| Nonlinear or threshold effect | Framework of Evidence; Framework of Risk | Threshold location mapping; dose-response testing; bifurcation analysis | Identify threshold; test nonlinearity; design contingent interventions. |
| Bidirectional causation or feedback loop | Framework of Systems; Framework of Causation | Causal loop mapping; simultaneity testing; system dynamics modelling | Model feedback loop; test for bidirectionality; design for loop structure. |
| Heterogeneous treatment effects | Framework of Evidence; Framework of Diagnosis | Effect-modifier testing; subgroup analysis; contextual analysis | Identify moderators; assess context-dependence; design customized interventions. |
| Reverse causation or outcome bias | Framework of Evidence; Framework of Learning | Temporal ordering validation; design for temporal primacy; outcome-independent selection | Validate temporal order; use prospective design; control for outcome bias. |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal outcome and candidate causes; sketch initial causal hypotheses (A → outcome).
2. For each hypothesis, ask: What is the mechanism? What confounders could explain the association?
3. Run Tier 1 Hiddens scan: touch all six meta-categories; flag obvious hidden confounders, bidirectional causation, or mechanism invisibility.
4. Shortlist 2–3 highest-consequence causal Unknowns (hidden confounder, mechanism, nonlinearity); note if causal validity is uncertain; flag for escalation.

### 7b. Full Depth Execution (Complete framework run)

1. Causal model: identify focal outcome, candidate causes, confounders, mediators, moderators; draw causal diagram.
2. Mechanism mapping: for each causal claim, articulate the mechanism (how does A cause outcome); assess mechanism plausibility.
3. Confounder analysis: identify plausible third variables that could explain association; assess likelihood and consequence of confounding.
4. Temporal analysis: for each causal claim, confirm temporal ordering (cause precedes effect); assess lag; identify timing window.
5. Heterogeneity analysis: assess whether effect varies by subgroup or context; identify effect modifiers; assess contextuality.
6. Validity threats audit: assess internal validity (confounding, reverse causation, selection bias, measurement error); assess external validity (generalizability).
7. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence causal claim, identify validity threats, detectability, consequence; propose causal tests.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add causal Hiddens with meta-category tag (Deterministic, Probabilistic, Agentic, Emergent, Systemic, Reflexive); mechanism; consequence. | After Tier 1 scan; escalate confounders and mechanism opacity. |
| Evidence Ledger | Record causal hypotheses, supporting/contradicting evidence, validity threats, mechanism evidence; note gaps. | After causal model and mechanism mapping. |
| Hypothesis/Test Backlog | Add causal hypotheses; design tests to validate causation (temporal ordering, mechanism, confounder control, heterogeneity). | Identified causal Unknowns; escalation decisions. |
| Information Requests | Request data for confounder measurement; request mechanism evidence (qualitative, process tracing); request heterogeneity analysis. | To reduce causal Unknowns; coordinate with Evidence framework. |

**Gate Question (pre-closure check):** Have we identified focal outcomes and candidate causes, mapped mechanisms, audited validity threats, tested for confounders and heterogeneity, run a Tier 1 Hiddens scan, and designed causally-informed interventions?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Situations Context Classification (what situation types have what causal structures?)
- Systems (what system structure generates causal mechanisms?)
- Time (what temporal lags and sequences structure causation?)
- Evidence (what evidence is available for causal claims?)

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Framework of Hiddens (hidden confounders, mechanism opacity; Tier 2 scans)
- Framework of Evidence (causal validity testing; experimental design)
- Framework of Diagnosis (root-cause analysis using validated causal models)
- Framework of Interventions (intervention logic derived from causal models)
- Framework of Risk (causal chains linking hazards to consequences)

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Scan 1: Hidden confounder and spurious causation detection | Identify third variables explaining associations. |
| Scan 3: Mechanism opacity and black-box causation | Identify causal links lacking mechanistic understanding. |
| Scan 6: Bidirectional causation and feedback loop detection | Identify circular causal relationships. |
| Scan 9: Nonlinear threshold and interaction effect detection | Identify non-additive causal relationships. |

---

*LLM Execution Extract v1.0 – Causation Framework (2026-04-08) – End of Extract*
