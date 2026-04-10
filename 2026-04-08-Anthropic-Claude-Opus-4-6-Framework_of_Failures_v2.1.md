# Framework of Failures
*A Comprehensive Taxonomy of Analytical Failure Types — Detection, Correction, Prevention, and the Systemic Dynamics of Error*

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
- Intended Use: Provide a structured failure scan across ontology, structure, time/causality, logic, cognition, and social interpretation; characterise failures by severity/detectability/correctability/systematicity/contagion; analyse failure dynamics; map detection/correction/prevention interfaces; integrate failure prevention into governance and learning cycles; surface meta-failures in failure-detection itself
- Primary Audience: Executives; strategists; analysts; investigators/auditors; risk and resilience leaders; programme and transformation leaders; policymakers; technical leads and domain experts; review and assurance teams; LLM-based analysis systems
- Dependencies / Key Inputs: Scenario or case description; claims, evidence, and causal hypotheses; boundaries and scope; stakeholder roles and perspectives; governance and incentive structure
- Primary Outputs: Failure register (30-type taxonomy); dimension profiles; failure interaction/dynamics map; detection/correction/prevention interface assignments; Hiddens register; meta-failure audit; prevention controls and quality gates; closure discipline outputs
- Change Log (brief): v2.1 (2026-04-08): MRT v3.0 LLM Integration Bridge format (§1.6); streamlined Bridge with LLM Extract pointer, Near-neighbour disambiguation table, and Routing triggers; preserves all other sections unchanged. v2.0 (2026-04-06): Full rewrite to OG v2.5 alignment; expanded LLM integration (§1.6); Tiered Hiddens scans with thirteen Targeted Discovery Scans; Prompt Discipline Rules (Canonical) integration; six-category Hiddens Tier 1 scan (§8.2); Hiddens Crosswalk (§8.3); Micro-Protocol (§8.4); escalation rules (§8.5); 7-step application protocol (§9); canonical 30-type consolidated list; expanded assumptions and preconditions; operational closure discipline.



## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What kinds of analytical failures are possible in this scenario, and how can we detect, correct, and prevent them?** |
| Addresses | Invisible errors, premature closure, systematic blind spots, cascading failures, reinforcing error loops, hidden failures in failure-detection itself |
| Gap Filled | Complements Evidence (provenance/quality), Diagnosis (reasoning/hypothesis), and Decisions (criteria/governance) by adding failure taxonomy and meta-analysis (failure-analysis can fail) |
| Complements | Evidence, Diagnosis, Beliefs, Hiddens, Decisions, Learning & Adaptation, Competencies, Systems & Time, and all remaining frameworks in the series (36 total) |
| Key Characteristics | 30-type taxonomy across 6 meta-categories (ontological, structural, temporal, logical, cognitive, social); 5 cross-cutting dimensions (severity/detectability/correctability/systematicity/contagion); 5 dynamic patterns (cascading, reinforcing, masking, compensating, accumulating); 3 interface types (detection, correction, prevention) |
| Main Contributions | Operationalises failure analysis into a reusable scan; makes error blindness detectable; enables prevention via interface-mapped controls; integrates Hiddens meta-categories to surface undetectable failures; closes gap between post-mortem and governance reform |

---

# Introduction

## What is Analytical Failure?

Analytical failure occurs whenever inference, interpretation, evidence handling, boundary-setting, or causal attribution diverges from reality in ways that matter for decisions and outcomes. Failures are not merely the absence of success; they are systematic, repeatable, often invisible patterns of error that persist despite intelligence, good intent, and careful work. They arise from ontological mistakes (naming the wrong thing), structural errors (wrong levels of analysis, boundary confusions), temporal blindness (dynamic processes treated as fixed states), logical flaws (circular reasoning, false dichotomies), cognitive biases (confirmation, anchoring, overconfidence), and social distortions (projection, stereotyping, false consensus). In complex scenarios—especially those involving high stakes, incomplete information, contested evidence, or misaligned incentives—failures multiply, interact, and hide each other. Without a systematic framework to detect them, failures remain operational long after decisions have been made and remediation windows have closed.

## Why Does Analytical Failure Matter for Hiddens Work?

Failures are themselves a major hiding mechanism. When analysis fails silently (the analyst is unaware of the error), the failure is invisible. When failure-detection itself fails (auditors overlook errors, quality gates are gamed, or false confidence suppresses scrutiny), hidden failures become institutionalised. This framework directly surfaces **Meta-Hiddens** (Hiddens meta-category VI — Ontological): unrepresentable failures, category absences, and the blind spots in failure-detection systems themselves. By running Tier 1 Hiddens scans alongside failure identification, this framework detects not only the failures themselves but also the mechanisms that hide them (distortion, perceptual blindness, systemic incentives that reward false certainty, relational hierarchies that suppress dissent). Integrated with the thirteen Targeted Hiddens Discovery Scans, failure analysis becomes a primary remediation tool: surface the failure → identify why it was hidden → address both the failure and its hiding mechanism → embed prevention into governance.

## What Does This Framework Produce?

This framework produces six core artefacts: (1) a **Failure Register** populated via a 6-category scan (30 failure types); (2) **Dimension Profiles** characterising each failure's severity, detectability, correctability, systematicity, and contagion (enabling risk prioritisation); (3) a **Failure Dynamics Map** showing cascades, reinforcement, masking, compensation, and accumulation patterns; (4) **Interface Maps** (Detection / Correction / Prevention) assigning responsibility and quality gates; (5) a **Hiddens Register** (framework view) with candidate hidden failures, mechanisms, and remediation levers; and (6) a **Meta-Failure Audit** testing whether the failure analysis itself is hidden or systematic. These artefacts integrate with the Hiddens Register (series-wide), Evidence Ledger, Hypothesis/Test Backlog, and Information Requests to form the standard registers used across Analytical Series investigations. Outputs feed upstream to Diagnosis (root-cause work) and downstream to Learning & Adaptation (post-mortem protocols), Decisions (quality gates), and governance reform (prevention controls).

## How to Use This Framework

This framework is invoked whenever high-stakes analysis is at risk of silent failure: in executive reviews where confidence is high but evidence is weak; in repeated incidents suggesting masking or reinforcement; in post-mortems where superficial fixes leave deeper patterns untouched; or in investigations where stakeholder views conflict about "what went wrong" (indicating category disputes or level confusions). Routing decision (OG §4.3) determines whether Light Depth (scan-level MVE on all 6 categories + quick dimension check) or Full Depth (detailed type inventory, dynamics analysis, Tier 2 Hiddens shortlist, prevention interface mapping) is warranted. Default is Light Depth; escalate to Full Depth when consequence is high, evidence is weak/contested, or coupling/cascade risk exists. This framework is always executed within the unified loop (OG §5.0: Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close) and requires Tier 1 Hiddens scan at minimum (§8.2). Targeted Hiddens Discovery Scans (OG §7.5) are triggered when Tier 1 symptoms point to specific mechanisms (social/organisational, structural/systemic, temporal, or action-induced hiding).

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (Narrative)

The fundamental premise of this framework is that analytical failure is inevitable, diverse, and systematic rather than random. Failure is not exceptional; it is structural to all reasoning under uncertainty and complexity. However, failures are not equal. Some are obvious and easily corrected; others are subtle, invisible, and deeply embedded in methods, incentives, or cultural norms. The framework's core contribution is to operationalise failure analysis—to make error diagnosis and prevention as systematic as hypothesis testing or evidence review. Rather than treating failure as post-mortem ("what went wrong?"), the framework enables prospective analysis ("what could fail and how do we prevent it?") and meta-analysis ("is our failure-detection system itself failing?").

The taxonomy of 30 failure types (6 meta-categories × 5 types) provides a common language for naming failures precisely. The five dimensions (severity, detectability, correctability, systematicity, contagion) enable risk prioritisation and interventions matched to failure characteristics. The five dynamic patterns (cascading, reinforcing, masking, compensating, accumulating) expose how failures interact and compound over time. The three interface types (detection, correction, prevention) map failures onto actionable controls and governance levers. And the Hiddens integration directly surfaces failures that hide themselves—through perceptual blindness, systemic incentives, information distortion, temporal lag, positional invisibility, or ontological absence.

In practice, this framework transforms failure-detection from an art (requiring domain expertise and intuition) into a structured method (replicable, teachable, automatable). It prevents closure on incomplete failure analysis. It enables learning systems to extract maximum value from failures (not just "don't do that again" but "what was the failure mechanism, and what control prevents recurrence?"). It shifts organisational culture from blame-seeking (scapegoating) to systemics (understanding how structures generate repeated failures). And it provides LLM-based analysis systems with a canonical failure taxonomy and integration protocol compatible with the Analytical Series' standard Hiddens infrastructure.

## 1.2 Assumptions & Preconditions

### Assumptions Register
| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Failures can be named and categorised using a universal taxonomy. | Structural / Method | Framework becomes non-communicable; teams talk past each other using different failure languages. | Scan 5–10 real failure cases; test whether all errors fit the 30-type taxonomy; identify any persistent "miscellaneous" failures. | Create supplementary categories; update taxonomy; validate via learning loop. |
| Failure taxonomy is domain-universal (applies across technical, organisational, policy, and strategic domains). | Domain | Framework loses transferability if failure types are domain-specific. | Apply framework to cases from 3+ different domains; check whether 30 types capture all observed errors. | Develop domain-specific taxonomies; maintain core mapping. |
| Failures are detectable (no failure is inherently undetectable). | Methodological | Detection interfaces become impossible to design. | Test whether Tier 1 scan + targeted discovery scans surface blind failures; run independent reviews and compare. | Accept Residual Unknowns (§7.4); escalate unknowns with high consequence to governance/monitoring. |
| Detected failures are correctible (at least in principle). | Methodological | Intractable failures force acceptance rather than action. | Classify failures by correctability dimension; test correction designs before implementation. | Build redundancy and robustness; shift from correction to prevention/containment. |
| Systematic failures trace to methods, incentives, or structures—not solely to individual incompetence. | Normative | Framework becomes a scapegoating tool. | Check whether failures recur across teams/people despite turnover. | Integrate Competencies framework (root cause); distinguish competency from system failure. |
| Failure-detection can itself fail (meta-failure is real). | Reflexive | Framework becomes blind to its own blindness. | Run Tier 1 Hiddens scan on every failure analysis (invariant §8.4); escalate if detection mechanism is compromised. | Tier 3 escalation (full Hiddens run); governance review of detection governance. |
| Stakeholder perspectives on "what failed" should be treated as evidence, not dismissed. | Normative | Dominant views suppress dissent; failure analysis becomes propaganda. | Collect failure registers from multiple roles; compare and record disagreements; trace to framing, authority, or access differences. | Positional sampling (Hiddens scan); protected disclosure channels. |

### Preconditions Checklist
| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Scenario/case description (time window, key actors, initial claims) | Yes | Narrative + timeline | Investigation lead | Check at Initialise stage | Produce scenario document before framework execution |
| Evidence artefacts (documents, data, records, testimonies) | Yes | Evidence register | Evidence owner | Check pre-execution | Produce Evidence Request List (IR-focused); proceed with Unknowns tagged |
| Scope boundaries (in/out; definitions of "failure" for this case) | Yes | Boundary decision record | Investigation lead | Check pre-execution | Run explicit boundary-setting workshop; escalate disputed boundaries to governance |
| Failure claim(s) to investigate (specific hypothesis or open scan) | Yes | Initial failure register or scan trigger | Sponsoring leader | Check at Route stage | Start with Light Depth scan of all 6 categories |
| Access to multiple perspectives (frontline, peer, leadership roles) | Conditional | Positional register | Investigation lead | Check pre-execution | Compensate with anonymous channels; triangulate with evidence |
| Governance context (incentives, KPIs, decision authorities) | Conditional | Governance map | Programme owner | Check Route stage | Build as part of analysis; escalate if distortion suspected |

## 1.3 Definitions, Scope, and Non-Goals

**Definition of Analytical Failure:** A failure is a divergence between inference/interpretation and reality (as best evidenced) that is material for decisions or outcomes. Failures range from individual errors (one analyst misreads a data point) to systemic errors (entire organisations systematically misclassify a phenomenon because of incentives or method flaws).

**In scope:**
- Ontological failures (misidentification, omission, conflation, reification, category mistakes)
- Structural failures (level confusion, composition/division fallacies, boundary errors, over-abstraction)
- Temporal failures (static bias, correlation/causation confusion, genetic fallacy, post hoc fallacy, hindsight bias)
- Logical failures (false dichotomy, infinite regress, premature closure, circular reasoning, non sequitur)
- Cognitive failures (confirmation bias, anchoring, availability bias, overconfidence, motivated reasoning)
- Social failures (projection, false consensus, fundamental attribution error, stereotyping, mind-reading error)
- Hidden failures (failures that hide themselves through perceptual, systemic, informational, temporal, relational, or ontological mechanisms)
- Meta-failures (failures in failure-detection, category neglect, dimension neglect, blindness to blindness)

**Out of scope:**
- Intentional deception or fraud (except where hidden failure enables deception to persist)
- Purely technical bugs or implementation errors (unless they create analytical failures)
- Value disagreements or political disputes (except where framing disputes hide boundary/level confusions)
- Competency gaps in individuals (unless they are systematic or masked by structures)

**Common confusions ("Failure is not ..."):**
- Failure is not the same as incompetence (competent people make systematic errors via bad methods or incentives).
- Failure is not the same as bad luck or external shocks (failures are recurring patterns, not one-off surprises).
- Failure is not the same as disagreement (disagreement may reflect positional knowledge; failure is objective divergence from reality).
- Failure is not the same as missed learning (frameworks can be learned; failure is present even if unlearned from).

## 1.4 Position in the Series (Upstream / Middle / Downstream)

**Upstream (signals/understanding):**
- Situations (context classification and boundary definition)
- Evidence (provenance, quality, bias assessment)
- Diagnosis (hypothesis generation and testing)
- Beliefs (root mechanisms of cognitive failures and their persistence)
- Hiddens (visibility failure taxonomy; enables detection of hidden failures)

**Middle (this framework's role):**
- Takes inputs from Situations, Evidence, Diagnosis, and Hiddens
- Scans for failure across all 6 meta-categories using the 30-type taxonomy
- Characterises failures by 5 dimensions and identifies dynamic interactions
- Maps failures to detection/correction/prevention interfaces
- Identifies hidden failures and meta-failures via Tier 1 Hiddens scan
- Outputs integrated failure register and prevention strategy

**Downstream (action/governance):**
- Decisions (quality gates, escalation rules, decision templates)
- Learning & Adaptation (post-mortem protocols, calibration, debiasing)
- Competencies (failure patterns trace to capability gaps)
- Systems & Time (feedback loops and systemic failure mechanisms)
- Responsibility & Governance (prevention controls, accountability structures, audit design)

**Group assignment (Primary):** G5 — Epistemics & error-control (Epistemics)
**Group assignment (Secondary):** G2 — Structure, dependencies & mechanism (Mechanism)
**Stage assignment:** Midstream (transforms evidence and diagnosis into failure characterisation; feeds governance)
**Run mode selection:** Light Depth for triage/MVE; Investigative Run Mode for high-stakes failure analysis
**Operating Guide routing:** Apply decision logic at Start-of-Run and Pre-Closure (OG §4.3)
**Non-conflation invariant:** Do not conflate Run Mode with Framework Execution Depth (OG §D.10.1)
**Iteration loop:** Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG §5.0)
**Framework Index:** This framework is one of 36 in the series (see OG §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary

| Cluster | Representative frameworks | What they provide to this one | What this framework adds / asks |
|---|---|---|---|
| Descriptive & Foundational | Situations, Realities, Systems, Time, Scale, Relations, Processes, Dimensions | Scenario/case definition; boundary; temporal and relational context; structural constraints | What failures could occur in this configuration? How do failures interact across levels and time? |
| Epistemic & Evidence | Evidence, Diagnosis, Beliefs | Provenance, quality, testing discipline; hypothesis generation and validation; root cognitive mechanisms | What evidence failures (selectivity, distortion, omission) occurred? What belief-level mechanisms generated these errors? |
| Analytical Control | Hiddens, Decisions | Visibility failure taxonomy; detection/remediation patterns; decision architecture and criteria | Which failures were hidden and why? How do failures alter decision quality and governance integrity? |
| Action & Learning | Learning & Adaptation, Responsibility & Governance, Competencies | Learning cycles; improvement protocols; accountability structures; capability mapping | What controls prevent recurrence? How do failures trace to competency gaps vs systemic structures? What learning extracts maximum value? |


## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Failures_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Failures when… | Use neighbour instead when… |
|---|---|---|
| Evidence | Analysing what kinds of error distorted evidence collection, selection, or interpretation; provenance failures; measurement bias. | Analysing evidence quality, provenance, and reliability independent of analytical error; studying trustworthiness of sources; examining chain of custody. |
| Diagnosis | Analysing how causal hypotheses became wrong; reasoning failures in root-cause attribution; circular or premature closure in diagnosis. | Analysing how to generate and test hypotheses correctly; studying causal inference methods; examining hypothesis strength and sufficiency. |
| Hiddens | Analysing how failures hide themselves (perceptual blindness, distortion, systemic incentive to suppress, positional invisibility); meta-failures in failure-detection itself. | Analysing what information is missing or invisible independent of analytical error; studying visibility barriers and information gaps; examining what makes things hard to see. |
| Beliefs | Analysing how cognitive biases and mental models generate systematic error patterns; root mechanisms of persistent false beliefs. | Analysing how beliefs form and persist; studying rationality and justification; examining doxastic coherence and update rules. |
| Decisions | Analysing failures in decision quality that stem from failure-analysis blindness; how failure-detection gaps compromise governance. | Analysing decision criteria, authority, and quality gates; studying choice architecture; examining decision governance and escalation rules. |

### 1.6.3 Routing triggers
- Scenario involves high-stakes analysis with weak/contested evidence
- Repeated incidents suggest masking, reinforcement, or systematic failure pattern
- Stakeholder perspectives conflict about "what went wrong" (category disputes, level confusion)
- Strong incentives to suppress or distort failure reporting exist
- Silent failures (undetected errors) are suspected despite care and competence
- Culture/method/incentive-driven systematic failures are suspected (not individual incompetence)
- Failure-detection system itself may be blind or compromised (meta-failure)
- Causal attribution is contested; boundaries/levels are unclear
- Post-mortem suggests superficial fixes leaving deeper patterns untouched
- Prevention controls need to be mapped and embedded in governance

# 2. Meta-Categories of Analytical Failure

## 2.1 Meta-Categories Table (Mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Ontological Failures | What are we counting and calling things? | What exists; how things are classified and named | Entities, boundaries, distinctions; naming; referents |
| II | Structural Failures | What are the relationships and levels? | How entities are related, composed, and organised across levels | Levels (micro/macro), boundaries, composition, hierarchy, system structure |
| III | Temporal Failures | What is the timing and causation? | How things change; cause and effect; sequence and dynamics | Timelines, causation, feedback, regime change, lag, path dependence |
| IV | Logical Failures | Do the inferences follow? | Reasoning validity; argument form; conclusion justification | Logic chains, premises, warrants, inference rules, stopping rules |
| V | Cognitive Failures | What are the mental/perceptual biases? | Systematic psychology biases; heuristic errors; limitations in human inference | Confirmation bias, anchoring, overconfidence, motivated reasoning, availability |
| VI | Social Failures | What are the interpersonal distortions? | How social context, role, and relationship distort understanding | Projection, stereotyping, attribution errors, mind-reading, consensus distortion |

## 2.2 Meta-Category Descriptions

### I. Ontological Failures
- **Definition:** Failures in what is counted as real, how it is named, and what distinctions matter.
- **Diagnostic cues:** Persistent confusion; category disputes; repeated "miscellaneous" or unnameable problems; disagreement on boundaries.
- **Typical failure mode:** Things are named wrong, left out, conflated, treated as real that are abstract, or categorised at the wrong level; map diverges from territory.

### II. Structural Failures
- **Definition:** Failures in understanding levels of analysis, composition, and organisation.
- **Diagnostic cues:** Explanations at the wrong level (micro blamed for macro outcomes, or vice versa); boundary shift changes conclusions; inconsistency across levels.
- **Typical failure mode:** Properties are attributed to wrong level; wholes are treated as sums of parts or vice versa; boundaries exclude what matters.

### III. Temporal Failures
- **Definition:** Failures in understanding time, change, causation, and sequence.
- **Diagnostic cues:** Snapshots treated as movies; past assumed predictable in hindsight; correlation taken as causation; lags missed.
- **Typical failure mode:** Dynamic processes are treated as fixed; causation is inferred from proximity without mechanism; contingency is rewritten as inevitability.

### IV. Logical Failures
- **Definition:** Failures in inference form and reasoning validity.
- **Diagnostic cues:** Conclusions that don't follow; forced dichotomies; circular support; infinite regress; unwarranted generalisation.
- **Typical failure mode:** Reasoning is formally invalid; assumptions are smuggled in; stopping rules are violated; alternatives are excluded without justification.

### V. Cognitive Failures
- **Definition:** Failures due to systematic psychological biases and heuristic limitations.
- **Diagnostic cues:** Beliefs persist despite disconfirming evidence; people are overconfident; recent/vivid examples dominate; first numbers anchor estimates.
- **Typical failure mode:** Evidence is sought to confirm, not test; uncertainty is underestimated; initial impressions resist update; reasoning follows incentives.

### VI. Social Failures
- **Definition:** Failures due to social context, role, and interpersonal distortion.
- **Diagnostic cues:** Dissent is suppressed; one perspective dominates despite evidence; others' mental states are assumed without inquiry; group norms override evidence.
- **Typical failure mode:** One's own views are projected onto others; group stereotypes override individual evidence; leaders' views go unchallenged; role creates invisible evidence.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- **Canonical baseline:** 6 meta-categories × 5 core types = 30 types total.
- **This framework:** 30 types (canonical alignment).
- **Mapping back to baseline:** Fully mapped; see Appendix A.

## 3.1 Types (Category I: Ontological Failures)
| # | Type | Description | Typical analytic symptom | Common mitigation |
|---|---|---|---|---|
| 1 | Misidentification | Mistaking one entity, condition, or phenomenon for another—naming the wrong 'thing' and building analysis on the wrong referent. | Analysis is internally sound but answers the wrong question; conclusions don't match evidence when cross-checked. | Boundary test: what would this entity look like if it were different? Triangulation: compare multiple sources. |
| 2 | Omission | Failing to include a materially relevant entity, factor, or constraint in the ontology of the case; the map is incomplete. | "Surprising" outcomes when evidence emerges that was invisible in the original analysis; asymmetric discovery of factors. | Comprehensive inventory; stakeholder/role-based scan; "what could we be missing?" prompts. |
| 3 | Conflation | Collapsing distinct entities or categories into one, obscuring differences that matter for explanation or action. | One-size-fits-all solution fails; subgroups respond differently; diversity within category is high. | Taxonomy review; test whether dimension treatment is homogeneous; disaggregate and re-analyse. |
| 4 | Reification | Treating abstractions, models, or metrics as if they were concrete realities; confusing representation with substrate. | Map/model/metric is defended despite empirical divergence; "that's what the data say" overrides observation. | Validity check: does the measure capture what it claims? Substrate check: what is being measured? |
| 5 | Category Mistake | Applying a concept or explanation appropriate to one kind of thing to a different kind of thing (asking the wrong kind of question). | Explanatory framework is coherent but answers the wrong kind of question; comparison is inapt. | Type check: is this explanation appropriate for this kind of phenomenon? Analogy audit. |

## 3.2 Types (Category II: Structural Failures)
| # | Type | Description | Typical analytic symptom | Common mitigation |
|---|---|---|---|---|
| 6 | Level Confusion | Mixing levels of analysis (micro/macro, individual/system) and attributing properties or causes at the wrong level. | Explanations are off-level: why the organisation failed is blamed on individual error, or individual behaviour is explained as system causation. | Explicit level-mapping; test whether the same claim holds at different levels; multi-level analysis. |
| 7 | Composition Fallacy | Assuming what is true of parts is true of the whole; projecting micro-properties to macro-outcomes without justification. | Micro-level findings are overgeneralised; emergent properties are missed; "people are like this so organisations are too." | Scale-up validity check; test emergent properties; integration analysis. |
| 8 | Division Fallacy | Assuming what is true of the whole is true of parts; projecting macro-properties to individual components or cases. | Macro-level generalisations are applied uniformly; subgroup variation is ignored; exception handling is poor. | Disaggregation; heterogeneity test; within-group variance analysis. |
| 9 | Boundary Error | Drawing system/problem boundaries incorrectly—excluding what matters or including what is irrelevant—leading to mis-scoped conclusions. | Boundary changes reverse conclusions; inclusion/exclusion appears arbitrary; definition is contested. | Boundary sensitivity test; stakeholder alignment on boundaries; record boundary decisions. |
| 10 | Over-abstraction | Generalising or compressing too far from concrete particulars; losing crucial context, constraints, and heterogeneity. | General framework fails on particular cases; context-dependent factors are invisible; exceptions accumulate. | Concreteness test; case-level validation; context mapping. |

## 3.3 Types (Category III: Temporal Failures)
| # | Type | Description | Typical analytic symptom | Common mitigation |
|---|---|---|---|---|
| 11 | Static Bias | Treating a dynamic process as a fixed state; relying on snapshots and missing drift, feedback, and regime changes. | Stale assumptions; dynamics are invisible; inflection points are missed; course corrections fail. | Time-window expansion; repeated measurement; change detection; lag analysis. |
| 12 | Correlation/Causation Confusion | Interpreting association as causation; failing to test causal direction, confounding, and mechanism. | Post hoc reasoning: "B followed A, so A caused B" without causal evidence; confounders are uncontrolled. | Causal diagram; confounder audit; mechanism test; temporal precedence check. |
| 13 | Genetic Fallacy | Judging validity or meaning solely by origin; assuming the source determines current truth or value. | Good ideas are dismissed because of their origin; bad ideas are accepted because they came from authority. | Source-content separation; origin-independent re-evaluation. |
| 14 | Post Hoc Fallacy | Assuming temporal sequence implies causality; 'after therefore because' without causal evidence. | Timing alone is treated as evidence of causation; alternative hypotheses are not tested. | Timing test for necessity/sufficiency; mechanism test; alternative causation. |
| 15 | Hindsight Bias | Overstating past predictability; rewriting uncertainty as inevitability and under-learning from contingency. | "We should have known"; past is rewritten as obvious; learning extracts false lessons about predictability. | Pre-decision documentation; counterfactual analysis; uncertainty reconstruction. |

## 3.4 Types (Category IV: Logical Failures)
| # | Type | Description | Typical analytic symptom | Common mitigation |
|---|---|---|---|---|
| 16 | False Dichotomy | Presenting only two options when more exist; forcing complex reality into an either/or frame. | Both/and solutions are excluded; nuance is forced into binary choice; middle ground is missing. | Option enumeration; three-plus-one test; reframe as spectrum. |
| 17 | Infinite Regress | Demanding an endless chain of justifications of the same kind; refusing legitimate stopping rules or primitives. | Justification is never sufficient; explanations cannot be grounded; inquiry is paralysed. | Legitimate stopping rule; primitive acceptance; basis legitimacy. |
| 18 | Premature Closure | Ending inquiry too early; settling on the first plausible answer and neglecting alternatives and disconfirming evidence. | Questions are closed before disconfirming evidence is examined; alternative hypotheses are not generated. | Hypothesis enumeration; disconfirming evidence search; mandatory alternative testing. |
| 19 | Circular Reasoning | Using the conclusion as a premise (explicitly or implicitly); failing to provide independent support. | Assumptions and conclusions are mutually reinforcing; independence is missing. | Premise-conclusion audit; independence test; alternative grounds. |
| 20 | Non Sequitur | Drawing conclusions that do not logically follow from premises; invalid inference steps or missing warrants. | Reasoning steps have gaps; warrants are implicit; conclusions outrun premises. | Logical form check; warrant inventory; step-by-step review. |

## 3.5 Types (Category V: Cognitive Failures)
| # | Type | Description | Typical analytic symptom | Common mitigation |
|---|---|---|---|---|
| 21 | Confirmation Bias | Seeking, interpreting, and recalling evidence in ways that favour prior beliefs; under-testing one's own hypotheses. | Evidence is read to support; contradictions are minimised; one's own hypotheses are under-tested. | Disconfirming evidence search; outside-view audit; pre-mortem. |
| 22 | Anchoring | Over-weighting initial information or early estimates; insufficient adjustment when new evidence arrives. | Initial numbers dominate; updates are insufficient; anchors persist despite new information. | Anchor-free estimation; independent estimation; adjustment sensitivity check. |
| 23 | Availability Bias | Judging likelihood or importance by ease of recall; over-weighting vivid, recent, or salient examples. | Vivid examples dominate probability estimation; rare recent events loom large; base rates are ignored. | Base-rate integration; frequency vs vividness audit. |
| 24 | Overconfidence | Excessive certainty relative to evidence; underestimating error bars, uncertainty, and base rates. | Confidence is high despite low evidence quality; error bars are too narrow; surprises are "unforeseeable." | Calibration; pre-mortem; uncertainty quantification. |
| 25 | Motivated Reasoning | Reasoning toward preferred conclusions; identity, incentives, or emotions shape inference and standards of proof. | Standards of proof vary by preference; disliked conclusions face higher bars; tribalism is high. | Preference-independence test; double-blind evidence review; incentive audit. |

## 3.6 Types (Category VI: Social Failures)
| # | Type | Description | Typical analytic symptom | Common mitigation |
|---|---|---|---|---|
| 26 | Projection | Assuming others think, want, or perceive as you do; importing one's own mental model into others' heads. | Stakeholder motivation is misread; surprise when others act differently; empathy is assumed. | Ask, don't assume; role-based sample; mental model audit. |
| 27 | False Consensus | Overestimating how widely shared one's beliefs/preferences are; mistaking a local norm for a general norm. | Local agreement is generalised; dissent is underestimated; surprises when broader views differ. | Positional sampling; dissent search; norm-scope audit. |
| 28 | Fundamental Attribution Error | Explaining others' behaviour by traits while underweighting situational constraints and incentives. | Failure is attributed to incompetence rather than incentives/constraints; person-blame overweighs system factors. | Situation inventory; incentive audit; capability vs system distinction. |
| 29 | Stereotyping | Applying group-level assumptions to individuals; ignoring within-group variation and context-specific cues. | Individual variation is missed; group defaults dominate; exceptions are ignored. | Individual-level audit; within-group variance check; cue sensitivity. |
| 30 | Mind-Reading Error | Claiming knowledge of others' intentions or beliefs without evidence; inferring mental states beyond what signals justify. | Motivation is assumed without evidence; signals are over-interpreted; private mental states are inferred. | Evidence requirement; inference gap mapping; ask directly. |

---

# 4. Cross-Cutting Dimensions of Any Failure

## 4.1 Dimensions Table (Mandatory)
| Dimension | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| Severity | How serious is the failure (impact on conclusions and decisions)? | **Catastrophic** – Completely invalidates the analysis; fundamental error that undermines everything. **Severe** – Major error with significant impact on conclusions. **Moderate** – Meaningful error that affects some conclusions but not all. **Minor** – Small error with limited impact on overall analysis. **Negligible** – Trivial error with no practical effect on conclusions. | Estimate how much the failure would change conclusions and decisions; test with counterfactual 'if corrected, what changes?' reasoning. | Prioritises detection and correction effort; sets escalation thresholds; shapes governance response. |
| Detectability | How easy is the failure to detect in practice? | **Obvious** – Immediately apparent on inspection; easy to spot. **Visible** – Detectable with ordinary care and attention. **Subtle** – Requires deliberate effort or expertise to detect. **Hidden** – Very difficult to detect; easily overlooked even with effort. **Invisible** – Cannot be detected without special techniques or perspectives. | Assess who can see it (generalist vs specialist), whether it is visible in artefacts, and what tests reveal it reliably. | Selects assurance methods and review depth; shapes monitoring and sampling strategy; drives Hiddens check. |
| Correctability | How easy is the failure to correct once detected? | **Trivial** – Can be corrected immediately with no difficulty. **Easy** – Straightforward to correct with modest effort. **Moderate** – Requires significant work to correct but achievable. **Difficult** – Very hard to correct; may require fundamental revision. **Intractable** – Cannot be corrected within current framework or approach. | Determine whether correction is local (edit/patch) or structural (rebuild model, reframe boundary); estimate cost/time/feasibility. | Guides whether to fix now, redesign process, or build robustness/redundancy/controls. |
| Systematicity | Is the failure one-off or systematic (repeatable) in the approach? | **Random** – Isolated, random error with no pattern. **Occasional** – Occurs sometimes but without consistent pattern. **Recurrent** – Happens regularly in similar circumstances. **Systematic** – Built into the approach or method; predictable and repeatable. **Structural** – Inherent in the framework or perspective being used. | Look for patterns across cases/teams; examine whether methods, incentives, or culture reproduce the failure. | Determines whether to treat as incident (one-off fix) vs governance problem (prevention control); informs prevention design. |
| Contagion | Does the failure spread and trigger additional failures? | **Isolated** – Affects only one specific point; does not spread. **Local** – Affects nearby or related conclusions only. **Spreading** – Propagates to affect multiple parts of analysis. **Pervasive** – Infects most or all of the analysis. **Cascading** – Triggers additional failures in chain reaction. | Trace dependency chains: does one failure distort evidence, reasoning, or interpretation elsewhere? Check for cascades. | Supports dynamic analysis and sequencing: break contagion early to avoid compounding error; guides correction priority and sequencing. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (Mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---|---|---|---|---|---|
| 1 | Cascading | One failure triggering additional failures; error avalanches | Interaction between failure types through dependencies in evidence, inference, representation, incentives, and interpretation. Wrong initial classification cascades into wrong causal diagnosis, which cascades into wrong interventions. | Creates nonlinear damage: one mistake generates many downstream errors; correction cost rises rapidly with time delay; early intervention has high leverage. | Break dependency chains; add early warning tests; require independent validation at choke points; design serial validation gates. |
| 2 | Reinforcing | Failures strengthening each other; mutual resistance to correction | Interaction between failure types where evidence gathering, interpretation standards, and outcome measurement are mutually supporting. Confirmation bias reinforces reification; motivated reasoning reinforces overconfidence; false consensus reinforces social failures. | Locks teams into stable failure modes; evidence and incentives align to resist correction; vicious cycles amplify. | Introduce adversarial review; diversify sources of evidence; separate incentives from measurement; enforce refutation discipline; multi-perspective analysis. |
| 3 | Masking | One failure hiding another; surface errors concealing deeper problems | Interaction where one failure prevents visibility of another. Example: Boundary error masks level confusion; static bias masks causal misattribution; presentation hides category mistakes. | Makes superficial fixes ineffective because deeper failures remain hidden; repeated 'mystery' reoccurrence; root cause is never found. | Peel layers: fix surface symptoms then run deeper diagnostics; use root-cause analysis and cross-check with Diagnosis framework; multi-layer audit. |
| 4 | Compensating | Failures cancelling out; right answers for wrong reasons | Interaction where multiple errors partially offset. Wrong premises + wrong inference direction = correct conclusion; omission offset by conflation; overconfidence offset by underweighting key evidence. | Produces right answers for wrong reasons; creates fragile success that breaks in new contexts; later surprises when compensating errors are corrected independently. | Validate by mechanism, not only output; test across contexts and edge cases; look for brittle correlations and hidden cancellations; mechanism transparency. |
| 5 | Accumulating | Small failures adding up; death by a thousand cuts | Interaction where many small/tolerable errors jointly distort outcomes. Small biases compound; minor omissions accumulate; occasional systematic errors integrate into major distortions. | Many small failures jointly shift outcomes; hard to attribute but materially distorts decisions over time; not visible at any single point. | Implement quality gates at each step; sample systematically and track small deviations; periodic holistic audits; trend monitoring; cumulative impact analysis. |

---

# 6. Interface Types

## 6.1 Interface Types Table (Mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| Type A | Detection Interfaces | Where failures become visible or can be tested; evidence and logic checks. | What tests would falsify this inference? What evidence is missing? Where are the weakest warrants? Who can see what we cannot? | Peer review; red team; audit trails; alternative model comparison; boundary and level checks; anomaly detection; disaggregation and re-aggregation; triangulation. |
| Type B | Correction Interfaces | Where detected failures can be addressed and fixed (patch vs redesign). | Is this failure locally correctable or structurally embedded? What must change—data, model, incentives, boundary, governance? | Revise model; extend ontology; adjust boundaries; redesign KPIs; retrain; change incentives; update definitions; add missing entities; rebuild causal diagram. |
| Type C | Prevention Interfaces | Where failures can be prevented before they occur (process and governance design). | Which quality gates prevent recurrence? What checklists, training, or governance controls institutionalise prevention? | Standard review gates; pre-mortems; calibration and debiasing programmes; documentation and decision templates; segregation of duties; independent assurance; metric redesign; disclosure requirements; learning protocols. |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links
- **Inputs expected:** a boundary-defined problem; evidence and claims (with provenance); causal hypotheses; stakeholder narratives; governance and incentive context; prior framework outputs (Situations typing, Evidence quality, Diagnosis hypotheses).
- **Outputs provided:** Failure register and prioritisation; failure dynamics map; interface map (detection/correction/prevention assignments); prevention controls and quality gates integrated into decision and governance processes; Hiddens register and meta-failure audit; escalation triggers and closure discipline.
- **Downstream consumers:** Decisions (gate design, escalation rules, governance reform), Learning & Adaptation (post-mortem protocols, debiasing, calibration), Responsibility & Governance (control design, audit protocols), Competencies (capability gap analysis).

## 7.2 Crosswalk Table (Recommended)
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| **Situations** | Situation classification; boundaries; context-specific factors that constrain or shape failure likelihood. | Failure modes specific to this situation type (e.g., "high-urgency situations are prone to premature closure"). | Situation-specific failure prevention checklist. |
| **Evidence** | Provenance, quality, and validation standards for claims underlying failure analysis. | Failure-mode prompts for evidence misuse (confirmation, anchoring, omission, reification, distortion). | Assurance reviews of executive decision briefs; evidence quality audits. |
| **Diagnosis** | Structured diagnostic reasoning and hypothesis testing; root-cause methods. | Failure scan and meta-failure audit to reduce diagnostic tunnel vision and premature closure. | Root-cause analysis after repeated incidents; failure-aware diagnosis design. |
| **Hiddens** | Visibility failure taxonomy; detection/remediation patterns for hidden knowledge. | Failure-classification lens for how hidden dynamics generate analytic errors and false confidence. | Investigations where data are incomplete, distorted, or politically managed. |
| **Beliefs** | Root mechanisms underlying cognitive failure types (Cognitive Dissonance, Identity-Protective Cognition, Belief Perseverance, Epistemic Trust). | Downstream analytical error-mode classifications produced by belief-level mechanisms; failure register for post-failure belief audits. | Post-failure investigation where cognitive failure modes need root mechanism explanation. |
| **Decisions** | Decision architecture and criteria, including escalation and accountability. | Prevention interfaces and quality gates that reduce systematic decision error; failure-aware decision template design. | Designing robust decision templates and governance controls; decision-making under uncertainty. |
| **Learning & Adaptation** | Feedback loops, learning cycles, capability development, and calibration methods. | Failure taxonomy for post-mortems and learning priorities; debiasing and calibration practices. | Institutionalising learning from near-misses and performance drift; post-failure improvement. |
| **Competencies** | What agents can reliably do; where gaps, degradation, and concentration exist. | Whether failure patterns trace to competency gaps, misrepresentation, or degradation. | Root cause analysis: competency dimensions of failure; distinguish competency vs system failure. |
| **Systems & Time** | Structural/temporal maps and causal dynamics; feedback loops and regime changes. | Boundary/level/temporal failure prompts and tests to prevent mis-scoping and misattribution. | Complex system interventions where naive causality claims are common; system-of-systems analysis. |
| **All 36 frameworks** | Context, constraints, and input claims from their outputs. | Failure-check lens for applying each framework: where does this framework commonly fail? What blind spots are structural? | Every framework execution should include failure-blindness check; integrate failure-awareness into series discipline. |

## 7.3 Series Integration Questions (All 36 Frameworks)

Use these questions to probe how Failures interacts with the full Analytical Series:

1. **Situations** — What is the focal situation and its time horizon? What failures have occurred or could occur in this situation type?
2. **Realities** — What does reality show about what went wrong? What evidence supports or contradicts the failure diagnosis?
3. **Systems** — What structural dependencies and feedback loops generate failures? Are systemic sources identified?
4. **Time** — What temporal patterns and lags drive failure recurrence? Are legacy residues constraining correction?
5. **Scale** — At what levels do failures propagate? Are scale-induced failures (emergence, level mismatch) recognised?
6. **Relations** — How do entity interactions and coordination gaps create failures? Are relational failures mapped?
7. **Processes** — What process variations and sequence errors produce failures? Are phase transitions and bottlenecks understood?
8. **Dimensions** — What are the critical but unmeasured dimensions that enable failures? Are proxy confusions driving errors?
9. **Perspectives** — Whose view determines what counts as failure? Are dissenting views on failure suppressed?
10. **Evidence** — What evidence gaps and quality issues enabled failures to persist? Was confirmation bias or selective evidence gathering active?
11. **Diagnosis** — What root-cause chains were missed? Did diagnosis prematurely close on wrong mechanisms?
12. **Beliefs** — What belief-level mechanisms (cognitive dissonance, identity protection) made failure-correction psychologically costly?
13. **Hiddens** — What hiding mechanisms enabled failures? Were distorted metrics, suppressed dissent, or positional invisibility active?
14. **Decisions** — What decision criteria or escalation rules enabled failures to persist? Were governance gates bypassed?
15. **Learning** — What prevented learning from prior similar failures? Are post-mortems institutionalised?
16. **Competencies** — Were failures rooted in competency gaps or degradation, or in structural/systemic causes?
17. **Responsibility** — Who is accountable for failure detection and prevention? Are accountability structures clear?
18. **Governance** — What controls could prevent recurrence? How are prevention controls integrated into operations?

---

# 8. Hiddens Source Analysis & Cross-Check (Mandatory)

## 8.1 Hiddens Source Analysis (Framework-Specific)
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---|---|---|---|
| 1 | Failure Blindness | Not looking for failure at all; assuming analysis is sound. | Deliberate failure-seeking; systematic scan across all categories. |
| 2 | Category Neglect | Ignoring whole categories of failures (e.g., only checking logic, never checking social or cognitive failures). | Systematic scan across all six meta-categories (§3.0–3.6). |
| 3 | Dimension Neglect | Focusing on some failure dimensions only (e.g., severity) and ignoring others (detectability, systematicity, contagion). | Characterisation across all five dimensions (§4.1); prioritisation includes multi-dimension risk. |
| 4 | Meta-Failure Blindness | Failing in failure-detection itself; the failure-analysis process is biased or incomplete. | Reflexive application to own processes; Tier 1 Hiddens scan on failure analysis itself. |
| 5 | Hiddens Omission | Failure analysis assumes visibility and honest reporting; hidden constraints, distortion, and positional invisibility remain untested, leading to 'clean' failure registers that miss the real drivers. | Run Tier 1 Hiddens scan (§8.2) for any non-trivial failure review; shortlist Tier 2 hidden types (§8.3) and attach detection/correction/prevention actions per §8.4. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – Invariant)
| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|
| **I Perceptual** | Failure detection depends on noticing weak signals and anomalies; many failures are subtle or normalised. | 'No issues found'; over-reliance on summaries; weak-signal neglect; thin evidence trails; failures appear only after escalation. | Independent review; disaggregation of aggregate data; anomaly baselining; 'what would falsify this?' prompts; multi-perspective scan. |
| **II Systemic** | Methods and incentives systematically generate recurring failures (Goodhart, proxy worship, ritual compliance). | Same failures repeat across projects/teams; KPI theatre; predictable errors aligned with incentives; ritual compliance without substance. | Assumption and metric audits; method validation; governance review; incentive analysis; feedback loop mapping. |
| **III Informational** | Information is withheld, amplified, corrupted, fragmented, or delayed; failures are therefore misdiagnosed. | Conflicting accounts; missing provenance; late discoveries; 'surprise' errors after decisions; information bottlenecks. | Access mapping; provenance checks; triangulation; integration registers; lag analysis; information flow audit. |
| **IV Temporal** | Failures emerge through drift, legacy residues, and delayed effects; snapshots miss process. | Stale assumptions; legacy lock-in; hindsight narratives; misattributed causality; slow accumulation unmeasured. | Time-window/lag mapping; legacy archaeology; repeated re-estimation; path dependence review; temporal anomaly detection. |
| **V Relational** | Different roles see different failures; power shapes which failures are reportable. | Frontline vs leadership disagreement; suppressed dissent; politicised certainty; scapegoating; fear-induced silence. | Positional sampling; protected disclosure; perspective mapping; facilitated review; psychological safety audit. |
| **VI Ontological** | Some failures cannot be represented in existing categories; they appear as 'miscellaneous' or vanish from registers. | Persistent confusion; repeated exceptions; category disputes; unnameable problems; failures that don't fit the schema. | Taxonomy gap review; new-category creation; outside expertise; representational experiments; exception analysis. |

## 8.3 Hiddens Crosswalk (Tier 2 – Default Mapping Layer)
| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability | Agency | Consequence | Detection interface(s) (A/B/C) | Remediation interface(s) (A/B/C) | Interaction notes |
|---|---|---|---|---|---|---|---|---|
| 1 Blindspot | H | Failure exists but is not noticed or surfaced; weak signals missed; normalised deviance. | Medium | Mixed (structural + individual) | High | **A:** anomaly scans; independent review; disaggregation; weak-signal protocols. | **B:** expand sensing; add checklists; rotate reviewers; early-warning system design. | Blindspot often underlies Omission and Premature Closure failures. |
| 6 Distortion | H | Metrics/incentives distort analysis; failure is 'managed' rather than corrected; Goodhart's Law. | Medium | Structural | High | **A/C:** metric and incentive audits; proxy validation; outcome vs metric comparison. | **C:** redesign KPIs; separate measurement from rewards; independent assurance; outcome verification. | Feeds confirmation bias, reification, and mirage certainty; systematic failure generator. |
| 7 Mirage | M–H | Coherent but wrong narrative resists correction despite evidence; narrative lock-in. | Low–Medium | Mixed (structural + individual) | High | **A:** adversarial testing; alternative models; disconfirming evidence hunt; narrative pressure-testing. | **B/C:** break reinforcing loops; institutionalise refutation; diverse interpretation forum. | Common in reinforcing failure dynamics; prevents learning from contradictory evidence. |
| 8 Framing | H | Problem framed to exclude options/evidence; false dichotomies and boundary errors become 'reasonable'. | Medium | Mixed (structural + individual) | High | **A:** compare alternative framings; record omitted realities/variables; reframing workshop. | **B/C:** facilitated reframing; explicit boundary decisions; dissent protection; frame rotation. | Maps to False Dichotomy, Over-abstraction, Level Confusion; frames persist even when contradicted. |
| 11 Secret | M | Key information is withheld; failure analysis is forced to infer under missing data. | Low–Medium | Deliberate | High | **A:** access mapping; discrepancy checks; whistleblower channels; protected disclosure. | **C:** disclosure governance; safe-to-say design; audit rights; transparency requirements. | Often creates masking and hindsight narratives; prevents failure-correction. |
| 14 Fragmentation | M–H | Information is distributed and unintegrated; local truths do not cohere into a correct global picture. | High | Structural | Medium–High | **A:** integration audits; inconsistency checks across units; missing-link analysis. | **C:** shared registers; interface owners; common cadence/taxonomy; information federation. | Drives boundary and level confusions; sustains accumulation dynamic. |
| 21 Positional | H | Different roles see different failures; 'official' analysis ignores positional evidence; hierarchy suppresses frontline knowledge. | Medium | Structural | High | **A:** positional sampling; compare registers by role; frontline interviews; role rotation. | **C:** governance requiring multi-level evidence; protected dissent; role-based validation gates. | Maps to social failures (projection, false consensus) and masking. |
| 25 Perspectival | M | Single lens dominates; alternative interpretations and tests are excluded; paradigm lock-in. | Medium | Structural | High | **A:** multi-lens review; devil's advocate; structured debate; alternative hypothesis tournament. | **C:** plural evidence standards; role rotation; decision templates requiring multiple views; methodological pluralism. | Often stabilises confirmation bias, premature closure. |
| 29 Category Absence | M | No category exists to name the failure; it is forced into the wrong bucket or ignored. | Medium | Structural | Medium–High | **A/B:** repeated exceptions; 'miscellaneous' clustering; taxonomy gap review; outside expertise. | **B/C:** create/update categories; update training and artefacts; representational innovation. | Creates persistent confusion and recurring errors; blocks learning. |

## 8.4 Embedded Hiddens Micro-Protocol (Standard Prompts)

1. **Tier 1 scan (invariant):** Run mandatory scan across all six Hiddens meta-categories (§8.2); assume hiddens exist (don't ask "are there hiddens?" ask "which ones?").
2. **Tier 2 shortlist (default in Full Depth):** For each high-consequence or recurring failure, identify relevant hidden types from §8.3 and rate detectability, agency, consequence.
3. **Interface assignment:** Assign at least one Detection (Type A) and one Prevention/Correction (Type B/C) move per high-consequence hidden; map to the Remediation interfaces in §8.3.
4. **Meta-failure audit (reflexive):** Re-run failure-detection meta-failures (§8.1 items 1–4); record whether failure analysis itself is biased, incomplete, or systematic.
5. **Record residuals:** Output Residual Unknowns (OG §7.4); do not close prematurely on visible failures if hidden mechanisms remain untested.

## 8.5 Escalation Rule (Tier 3 – Full Hiddens Run)

Escalate to a full 30-type Hiddens scan + detection/remediation mapping (Tier 3, per OG §7.3 and §D.6.10) if any of the following apply:

- **High consequence:** Failure affects safety, systemic resilience, regulatory exposure, or irreversible harm.
- **Adversarial conditions:** Strong incentives to conceal/distort evidence; whistleblower risk; retaliation concerns.
- **Persistent disagreement:** Stakeholders disagree on boundaries, levels, causation, or "what failed"; disputes are unresolved.
- **Repeated failures despite 'fixes':** Same failure recurs despite attempted corrections; suggests reinforcing/masking dynamics.
- **Evidence of distortion:** KPI certainty despite weak mechanisms; compliance theatre; narrative lock-in despite contradictory evidence.
- **Meta-failure detected:** Failure-detection process itself is compromised (ignored evidence, suppressed dissent, gamed metrics).

---

# 9. Framework Application Protocol (Mandatory)

## 9.1 Seven-Step Protocol (Operationalised)

### Step 1: Initialisation & Precondition Check
- **Input:** Scenario, boundaries, key claims, stakeholder roles, governance context.
- **Actions:** (1) Verify preconditions (§1.2 Preconditions Checklist); (2) Identify missing inputs and produce Information Requests; (3) Record assumptions; (4) Define scope (in/out); (5) Establish time window.
- **Output:** Initialisation note; precondition status; scenario document; Information Requests list.
- **Gating:** Proceed to Step 2. If critical preconditions unmet, escalate or compensate with fallbacks.

### Step 2: Failure Scan (All Six Meta-Categories)
- **Input:** Scenario, evidence artefacts, diagnostic hypotheses, stakeholder narratives.
- **Actions:** (1) Run Light Depth scan across all 6 meta-categories (§3.1–3.6; all 30 types); (2) For each failure type, ask: "Is this failure present/possible in this case?" (3) Tag status: F (Fact confirmed), I (Inferred but untested), A (Assumed/hypothetical), U (Unknown); (4) Populate Failure Register (§1.6.6); (5) Record evidence and gaps.
- **Output:** Populated Failure Register with top risks identified; Evidence Ledger entries; Unknowns backlog.
- **Gating:** Proceed to Step 3 if Light Depth complete. For Full Depth: expand type descriptions, add mechanism details, populate all dimension cells (§4.1).

### Step 3: Dimensional Characterisation & Prioritisation
- **Input:** Identified/candidate failures (from Step 2 register).
- **Actions:** (1) For each failure, assess all five dimensions (§4.1: severity, detectability, correctability, systematicity, contagion); (2) Estimate risk impact = severity × (1 – detectability); (3) Note correctability to guide sequencing; (4) Check for systematic patterns (recurrence signal); (5) Identify contagion (cascading risk); (6) Rank by risk and replaceability.
- **Output:** Dimension profiles for all failures; Risk-ranked failure list; Prioritisation matrix.
- **Gating:** Proceed to Step 4; use rankings to guide interface mapping priorities.

### Step 4: Dynamics Analysis & Interaction Mapping
- **Input:** Prioritised failure list; dimension profiles; system/process context.
- **Actions:** (1) For each top-ranked failure, trace dependencies: what does it distort upstream/downstream? (2) Identify interaction patterns (§5.1: cascading, reinforcing, masking, compensating, accumulating); (3) Map failure interaction chains; (4) Identify breakpoints (where to intervene early); (5) Test for contagion (does early correction prevent downstream errors?); (6) Document dynamics in Failure Interaction Map.
- **Output:** Failure Interaction/Dynamics Map; Breakpoint analysis; Sequencing recommendations for correction.
- **Gating:** Use dynamics map to guide interface mapping (Step 5) and prevention design (Step 6).

### Step 5: Interface Mapping (Detection → Correction → Prevention)
- **Input:** Top-ranked failures; dynamics map; governance context.
- **Actions:** (1) For each failure, map Detection Interface (Type A) — "how is this failure revealed?" (2) Map Correction Interface (Type B) — "how is this failure fixed?" (3) Map Prevention Interface (Type C) — "how is recurrence prevented?"; (4) Assign ownership and quality gates; (5) Estimate effort and feasibility; (6) Record in Failure Register (§1.6.6 columns: Detection/Correction/Prevention interface types); (7) Link to governance/decision processes.
- **Output:** Interface Map; Detection/Correction/Prevention action plan; Governance integration points; Ownership assignments; Quality gate design.
- **Gating:** Proceed to Step 6. Use interface map to design Step 6 governance reforms.

### Step 6: Tier 1 Hiddens Scan & Meta-Failure Audit
- **Input:** Complete failure analysis from Steps 1–5; failure register; interface map.
- **Actions:** (1) Run mandatory Tier 1 Hiddens scan across all six categories (§8.2); ask "why was this failure hidden?"; (2) Cross-reference Hiddens meta-categories against failure analysis — which hiding mechanisms enabled failures to persist?; (3) For high-consequence failures, shortlist Tier 2 hidden types (§8.3) and assign remediation interfaces; (4) Run reflexive meta-failure audit (§8.1): is our failure-detection process itself biased, incomplete, or systematic?; (5) Assess whether Tier 3 escalation is triggered (§8.5).
- **Output:** Hiddens Register (framework view); Meta-failure audit findings; Tier 2 shortlist (if applicable); Escalation recommendation (if applicable).
- **Gating:** If Tier 3 trigger detected, escalate now (full Hiddens run, §8.5). Otherwise, proceed to Step 7.

### Step 7: Residual Unknowns, Closure Discipline & Learning Hook
- **Input:** Integrated outputs from Steps 1–6; failure register; interface map; Hiddens register.
- **Actions:** (1) Identify Residual Unknowns: what remains hidden, untested, or unknown after analysis? (2) For each Unknown, assess: Is the uncertainty acceptable for decision-making? What would change our decision if resolved? (3) Record Closure Note per OG §7.4 (five required items: residual unknowns, acceptability rationale, monitoring plan, ownership, learning hook); (4) Design Monitoring Indicators to detect if hidden failures emerge or corrections fail; (5) Assign Learning Hook (how do we extract learning from this failure?); (6) Produce standard deliverables (§1.6.5).
- **Output:** Residual Unknowns summary; Closure Note (per OG §7.4); Monitoring plan; Learning artefacts; Final Failure Register and supporting tables; Escalation recommendation (if applicable).
- **Gating:** Closure sign-off only after all five closure items (OG §7.4) are recorded. If residual unknowns are decision-critical, escalate to sponsor/governance rather than closing.

## 9.2 Standard Deliverables (Recommended)

**Minimum deliverable (Light Depth; 1–2 pages):**
- Failure register (6-category scan) with top 3–5 risks by severity/detectability/contagion.
- Dimension profiles for top failures (severity/detectability/correctability/systematicity/contagion).
- Dynamics note (where cascades, masking, reinforcement likely; breakpoints identified).
- Detection/Correction/Prevention interface actions and owners (1–2 per top risk).
- Hiddens shortlist (Tier 1 scan results; candidate hidden mechanisms).
- Escalation trigger check (Tier 3 escalation warranted? Yes/No; rationale).

**Full deliverable pack (Investigative Run Mode; 4–8 pages + appendices):**
- Integrated Failure Register (populated per §1.6.6; all relevant types; dimension profiles; dynamics interactions).
- Failure Interaction/Dynamics Map (cascades, reinforcing loops, masking chains, breakpoints).
- Detection/Correction/Prevention Interface Plan (assignments, quality gates, governance integration, metrics).
- Integrated assurance plan (peer review, red team, audit cadence, testing protocol).
- Prevention controls embedded in governance (quality gates, templates, training, escalation rules, accountability).
- Monitoring indicators and verification tests for corrections.
- Learning artefacts (post-mortems, calibration metrics, updated checklists, taxonomy updates).
- Hiddens Register and Meta-Failure Audit (Tier 1 + Tier 2 shortlist; remediation levers).
- Residual Unknowns and Closure Note (per OG §7.4; five required items).
- Escalation recommendation and next-steps plan (if applicable).

---

# 10. Framework Principles (Mandatory)

## 10.1 Principles Table
| Principle name | Description |
|---|---|
| 1. Failure Realism | Failure is always possible; no analysis is immune from error. Assume it exists; don't ask whether, ask which. |
| 2. Failure Pluralism | Failures come in many kinds; different types require different strategies. No universal fix; diversity of controls. |
| 3. Productive Failure | Failure can be generative; properly handled, it drives progress. Extract learning; don't just blame. |
| 4. Systemic Sensitivity | Failures interact and compound; analysis must be systemic. Trace cascades, mask, reinforcement. |
| 5. Reflexive Application | The framework applies to itself; failure-detection can fail. Meta-audit; don't assume cleanness. |

---

# 11. Glossary (Mandatory for Stable Status)

## 11.1 Local Domain Glossary
| Term | Definition |
|---|---|
| Accumulating dynamic | A failure dynamic where many small failures add up over time to produce significant cumulative distortion without any single point being obviously wrong. |
| Anchoring | A cognitive failure of over-relying on initial information; insufficient adjustment from starting points when new evidence arrives. |
| Availability bias | A cognitive failure of judging probability by ease of recall; overweighting vivid or recent examples over base-rate data. |
| Boundary error | A structural failure of drawing system/problem boundaries wrongly; including what should be excluded or excluding what should be included. |
| Cascading / Contagion | A dynamic pattern where one failure triggers additional failures in chain reaction; an exponential damage pattern. |
| Cascading dynamic | A failure dynamic where one failure triggers additional failures; error avalanches; dependency chains amplify. |
| Catastrophic (severity) | A dimensional value where a failure completely invalidates the analysis or decision. |
| Category mistake | An ontological failure of applying concepts or explanations from one kind of thing to a different kind of thing (asking the wrong kind of question). |
| Category neglect | A meta-hiddens source involving ignoring whole categories of failures. |
| Circular reasoning | A logical failure of assuming what one is trying to prove; using conclusion as premise. |
| Cognitive failures | One of the six meta-categories. Failures concerning psychological biases, heuristic errors, and limitations in human inference. |
| Compensating dynamic | A failure dynamic where failures cancel each other out; right answers for wrong reasons; fragile success. |
| Composition fallacy | A structural failure of inferring that wholes have properties because parts have them; micro-to-macro error. |
| Confirmation bias | A cognitive failure of seeking evidence to support existing beliefs while ignoring disconfirming evidence. |
| Conflation | An ontological failure of treating distinct things as identical; collapsing important distinctions. |
| Contagion | One of the five failure dimensions. Whether the failure spreads to affect other parts of analysis. |
| Correctability | One of the five failure dimensions. How easy the failure is to correct once detected. |
| Correction interface | An interface type (Type B) where detected failures can be addressed and fixed. |
| Detectability | One of the five failure dimensions. How easy the failure is to detect. |
| Detection interface | An interface type (Type A) where failures become visible or can be tested. |
| Difficult (correctability) | A dimensional value where a failure is very hard to correct; requires fundamental revision. |
| Dimension neglect | A meta-hiddens source involving focusing on some failure dimensions while ignoring others. |
| Division fallacy | A structural failure of inferring that parts have properties because wholes have them; macro-to-micro error. |
| Easy (correctability) | A dimensional value where a failure is straightforward to correct with modest effort. |
| Failure blindness | A meta-hiddens source involving not looking for failure at all; assuming analysis is sound. |
| Failure dynamics | Characteristic ways failures interact over time: cascading, reinforcing, masking, compensating, accumulating. |
| Failure pluralism | One of the five framework principles. Recognition that failures come in many irreducible kinds. |
| Failure realism | One of the five framework principles. Recognition that failure is always possible. |
| False consensus | A social failure of overestimating how much others share one's views; mistaking a local norm for a general norm. |
| False dichotomy | A logical failure of presenting only two options when more exist; forcing complex reality into either/or frame. |
| Fundamental attribution error | A social failure of over-attributing others' behaviour to character/trait rather than situational constraints and incentives. |
| Genetic fallacy | A temporal failure of evaluating things by their origins rather than current properties. |
| Hidden (detectability) | A dimensional value where a failure is very difficult to detect even with effort. |
| Hindsight bias | A temporal failure of believing past events were more predictable than they actually were. |
| Infinite regress | A logical failure requiring an endless chain of explanations with no natural stopping point. |
| Intractable (correctability) | A dimensional value where a failure cannot be corrected within the current framework or approach. |
| Invisible (detectability) | A dimensional value where a failure cannot be detected without special techniques or perspectives. |
| Isolated (contagion) | A dimensional value where a failure affects only one specific point and does not spread. |
| Level confusion | A structural failure of mixing up levels of analysis or description and attributing causes at the wrong level. |
| Local (contagion) | A dimensional value where a failure affects nearby or related conclusions only. |
| Logical failures | One of the six meta-categories. Failures concerning reasoning, inference, and argument validity. |
| Masking dynamic | A failure dynamic where one failure hides another; surface errors conceal deeper problems. |
| Meta-failure blindness | A meta-hiddens source involving failing to recognise failures in failure-detection itself; blindness to blindness. |
| Mind-reading error | A social failure of claiming to know others' mental states without adequate evidence. |
| Minor (severity) | A dimensional value where a failure has limited impact on overall analysis. |
| Misidentification | An ontological failure of taking one thing for another; mistaking what something is. |
| Moderate (correctability) | A dimensional value where a failure requires significant work to correct but is achievable. |
| Moderate (severity) | A dimensional value where a failure affects some conclusions but not all. |
| Motivated reasoning | A cognitive failure of reasoning toward desired conclusions rather than following evidence impartially. |
| Negligible (severity) | A dimensional value where a failure has no practical effect on conclusions. |
| Non sequitur | A logical failure of drawing conclusions that do not follow from premises; invalid inference. |
| Obvious (detectability) | A dimensional value where a failure is immediately apparent on inspection. |
| Occasional (systematicity) | A dimensional value where a failure occurs sometimes but without consistent pattern. |
| Omission | An ontological failure of failing to include a materially relevant entity/factor; the map is incomplete. |
| Ontological failures | One of the six meta-categories. Failures concerning what exists, how it is classified, and what distinctions matter. |
| Over-abstraction | A structural failure of moving too far from concrete particulars; losing important detail and context. |
| Overconfidence | A cognitive failure of excessive certainty in judgments; underestimating uncertainty and error bars. |
| Pervasive (contagion) | A dimensional value where a failure infects most or all of the analysis. |
| Post hoc fallacy | A temporal failure of assuming that because B followed A, A caused B without causal evidence. |
| Premature closure | A logical failure of stopping inquiry too soon; settling on first plausible answer before exploring alternatives. |
| Prevention interface | An interface type (Type C) where failures can be prevented before they occur via governance and process design. |
| Productive failure | One of the five framework principles. Recognition that failure can be generative and drive progress. |
| Projection | A social failure of attributing one's own characteristics, beliefs, or perceptions to others. |
| Random (systematicity) | A dimensional value where a failure is an isolated error with no pattern or repetition. |
| Recurrent (systematicity) | A dimensional value where a failure happens regularly in similar circumstances; pattern exists. |
| Reflexive application | One of the five framework principles. Recognition that failure analysis can itself fail; meta-audit required. |
| Reification | An ontological failure of treating abstractions, models, or metrics as if they were concrete realities. |
| Reinforcing dynamic | A failure dynamic where failures strengthen each other; mutual resistance to correction; vicious cycles. |
| Severe (severity) | A dimensional value where a failure is a major error with significant impact on conclusions. |
| Severity | One of the five failure dimensions. How serious the failure is for decisions and outcomes. |
| Social failures | One of the six meta-categories. Failures concerning interpersonal understanding and social distortion. |
| Spreading (contagion) | A dimensional value where a failure propagates to affect multiple parts of analysis. |
| Static bias | A temporal failure of treating dynamic phenomena as fixed; seeing snapshots rather than movies. |
| Stereotyping | A social failure of applying group characteristics to individuals without justification; ignoring individual variation. |
| Structural (systematicity) | A dimensional value where a failure is inherent in the framework/method; built-in, not incidental. |
| Structural failures | One of the six meta-categories. Failures concerning levels, composition, boundaries, and organisation. |
| Subtle (detectability) | A dimensional value where a failure requires deliberate effort or expertise to detect. |
| Systematic (systematicity) | A dimensional value where a failure is built into the approach; predictable, repeatable, culture-dependent. |
| Systematicity | One of the five failure dimensions. Whether the failure is one-off or systematic/structural. |
| Systemic sensitivity | One of the five framework principles. Recognition that failures interact and compound; cascade risk is real. |
| Temporal failures | One of the six meta-categories. Failures concerning time, change, dynamics, and causation. |
| Trivial (correctability) | A dimensional value where a failure can be corrected immediately with no difficulty. |
| Visible (detectability) | A dimensional value where a failure is detectable with ordinary care and attention. |
| Correlation/Causation confusion | A temporal failure of inferring causation from correlation without testing causal direction or confounders. |

## 11.2 Core Execution Terms (Pointer; Do Not Restate)
- See **Analytical Series Operating Guide**, v2.5, Appendix D, **§D.10 — Glossary of Core Execution Terms**.
- F/I/A/U tagging (Fact, Inferred, Assumed, Unknown): **OG §D.3.2**
- Run Mode definitions (Rapid vs Investigative): **OG §D.10.1**
- Depth definitions (Full vs Light): **OG §D.10.1**
- Hiddens meta-categories (I–VI): **OG §6.1**

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v2.0 | 2026-04-06 | Full rewrite to OG v2.5 alignment. Expanded LLM integration (§1.6 with all subsections and standard schemas). Added Tiered Hiddens scans (§8: Tier 1 six-category scan §8.2, Tier 2 Hiddens Crosswalk §8.3, Tier 3 escalation §8.5). Added seven-step application protocol (§9.1). Integrated Prompt Discipline Rules (Canonical) and machine-readable field schemas (OG Appendix E). Expanded assumptions and preconditions (§1.2). Canonical 30-type consolidated list (Appendix A). Operational closure discipline (Step 7, §9.1; per OG §7.4). Framework executed within unified iteration loop (OG §5.0). All 36 frameworks integration questions (§7.3). v2.0 status: Draft. Authored by: Anthropic Claude Opus 4.6. |
| v1.1 | 2026-03-27 | Cross-reference update: Framework of Beliefs integration; §7.2 crosswalk added. Series count updated from 32 to 33 frameworks. Standardised rewrite per Analytical Series template v1.5. Status: Draft. Authored by: Anthropic Claude Sonnet 4.6. |
| v1.0 | 2025-12-15 | Standardised rewrite to Analytical Series master template; clarified tables and outputs; expanded Hiddens cross-check; added appendices and audit checklist; minor language tightening. Status: Draft. |
| v0.8 (source) | 2025-12-05 | Initial: 6×5 failure taxonomy; 5 dimensions; failure dynamics; interfaces; hiddens sources; application protocol; principles; glossary. Status: Draft (working). |

## 12.2 Integration Notes (Optional)
**Use this framework whenever:**
- Outputs are high-stakes and partially irreversible (decisions that are hard to undo).
- Teams are overconfident or repeatedly surprised (pattern suggests systematic failure).
- Disputes persist about "what matters," boundaries, levels, or causal claims (framing conflicts).
- Organisational incentives appear to reward certainty over truth (distortion risk).
- Post-mortems are producing superficial fixes without prevention (masking dynamics suspected).
- Silent failures are suspected (analysed work is unquestioned; scrutiny is low).
- Governance reform is planned (prevention controls design).

---

# Appendix A — Consolidated 30-Type List (Single View)

| # | Meta-category | Type | Description |
|---|---|---|---|
| 1 | I. Ontological Failures | Misidentification | Mistaking one entity, condition, or phenomenon for another—naming the wrong 'thing' and building analysis on the wrong referent. |
| 2 | I. Ontological Failures | Omission | Failing to include a materially relevant entity, factor, or constraint in the ontology of the case; the map is incomplete. |
| 3 | I. Ontological Failures | Conflation | Collapsing distinct entities or categories into one, obscuring differences that matter for explanation or action. |
| 4 | I. Ontological Failures | Reification | Treating abstractions, models, or metrics as if they were concrete realities; confusing representation with substrate. |
| 5 | I. Ontological Failures | Category Mistake | Applying a concept or explanation appropriate to one kind of thing to a different kind of thing (asking the wrong kind of question). |
| 6 | II. Structural Failures | Level Confusion | Mixing levels of analysis (micro/macro, individual/system) and attributing properties or causes at the wrong level. |
| 7 | II. Structural Failures | Composition Fallacy | Assuming what is true of parts is true of the whole; projecting micro-properties to macro-outcomes without justification. |
| 8 | II. Structural Failures | Division Fallacy | Assuming what is true of the whole is true of parts; projecting macro-properties to individual components or cases. |
| 9 | II. Structural Failures | Boundary Error | Drawing system/problem boundaries incorrectly—excluding what matters or including what is irrelevant—leading to mis-scoped conclusions. |
| 10 | II. Structural Failures | Over-abstraction | Generalising or compressing too far from concrete particulars; losing crucial context, constraints, and heterogeneity. |
| 11 | III. Temporal Failures | Static Bias | Treating a dynamic process as a fixed state; relying on snapshots and missing drift, feedback, and regime changes. |
| 12 | III. Temporal Failures | Correlation/Causation Confusion | Interpreting association as causation; failing to test causal direction, confounding, and mechanism. |
| 13 | III. Temporal Failures | Genetic Fallacy | Judging validity or meaning solely by origin; assuming the source determines current truth or value. |
| 14 | III. Temporal Failures | Post Hoc Fallacy | Assuming temporal sequence implies causality; 'after therefore because' without causal evidence. |
| 15 | III. Temporal Failures | Hindsight Bias | Overstating past predictability; rewriting uncertainty as inevitability and under-learning from contingency. |
| 16 | IV. Logical Failures | False Dichotomy | Presenting only two options when more exist; forcing complex reality into an either/or frame. |
| 17 | IV. Logical Failures | Infinite Regress | Demanding an endless chain of justifications of the same kind; refusing legitimate stopping rules or primitives. |
| 18 | IV. Logical Failures | Premature Closure | Ending inquiry too soon; settling on the first plausible answer and neglecting alternatives and disconfirming evidence. |
| 19 | IV. Logical Failures | Circular Reasoning | Using the conclusion as a premise (explicitly or implicitly); failing to provide independent support. |
| 20 | IV. Logical Failures | Non Sequitur | Drawing conclusions that do not logically follow from premises; invalid inference steps or missing warrants. |
| 21 | V. Cognitive Failures | Confirmation Bias | Seeking, interpreting, and recalling evidence in ways that favour prior beliefs; under-testing one's own hypotheses. |
| 22 | V. Cognitive Failures | Anchoring | Over-weighting initial information or early estimates; insufficient adjustment when new evidence arrives. |
| 23 | V. Cognitive Failures | Availability Bias | Judging likelihood or importance by ease of recall; over-weighting vivid, recent, or salient examples. |
| 24 | V. Cognitive Failures | Overconfidence | Excessive certainty relative to evidence; underestimating error bars, uncertainty, and base rates. |
| 25 | V. Cognitive Failures | Motivated Reasoning | Reasoning toward preferred conclusions; identity, incentives, or emotions shape inference and standards of proof. |
| 26 | VI. Social Failures | Projection | Assuming others think, want, or perceive as you do; importing one's own mental model into others' heads. |
| 27 | VI. Social Failures | False Consensus | Overestimating how widely shared one's beliefs/preferences are; mistaking a local norm for a general norm. |
| 28 | VI. Social Failures | Fundamental Attribution Error | Explaining others' behaviour by traits while underweighting situational constraints and incentives. |
| 29 | VI. Social Failures | Stereotyping | Applying group-level assumptions to individuals; ignoring within-group variation and context-specific cues. |
| 30 | VI. Social Failures | Mind-Reading Error | Claiming knowledge of others' intentions or beliefs without evidence; inferring mental states beyond what signals justify. |

---

# Appendix B — Failure Audit Checklist (One-Page Reference)

| Check | Prompt |
|---|---|
| Ontology check | Have we enumerated all relevant entities, factors, and constraints? What could be omitted, conflated, or misidentified? Are we reifying abstract models as concrete? |
| Boundary check | What is in/out? Who benefits from the chosen boundary? What changes if boundary shifts? Are boundaries contested? |
| Level check | Are claims at the correct level (micro/macro/system)? Are we committing composition/division errors? Do findings hold across levels? |
| Causality check | What would distinguish causation from correlation here? What confounders exist? Is post-hoc reasoning active? |
| Logic check | Do conclusions follow from premises? Are we forcing dichotomies, circularity, non sequiturs, or infinite regress? |
| Bias check | What would disconfirm our favoured view? Are we anchored, overconfident, motivated by incentives, or selection-biased in evidence? |
| Social check | Which stakeholder views are missing or suppressed? Are we projecting, stereotyping, or mind-reading? Is dissent safe? |
| Dynamics check | Could failures be masking or reinforcing? Where could cascades occur? What are the breakpoints? |
| Interface check | What are the detection tests, correction moves, and prevention controls? Who owns them? |
| Hiddens check | Tier 1 scan completed; Tier 2 shortlist attached; Tier 3 triggers defined. Is failure-detection itself hidden or systematic? |

---

**END OF DOCUMENT**

*Framework of Failures v2.0 — Operational, 2026-04-06*
*Analytical Series of Frameworks — Opus 4.6 Edition*
*OG v2.5 Aligned | Full Depth Framework Execution Capable | LLM-Navigable | Closure Discipline Compliant*
