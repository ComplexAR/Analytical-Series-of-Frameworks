# Framework of Evidence
*A Comprehensive Taxonomy of Evidence Types, Reliability Profiles, and Synthesis Protocols for Evidence-Centred Decision-Making*

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
- Group (Secondary): None
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Identify and classify evidence types; profile evidence reliability and relevance; manage defeaters and conflicts; calibrate standards and burdens of proof; maintain chains-of-evidence and provenance; support robust diagnosis, causation analysis, and accountable decision-making
- Primary Audience: Analysts; investigators/auditors; risk and resilience leaders; governance and compliance leaders; programme and transformation leaders; executives; policymakers; technical and domain experts
- Dependencies / Key Inputs: Focal claim(s) or decision(s); stakeholder and role map; evidence artefacts and data; measurement and sampling context; governance standards and disclosure regimes; time horizon; adversarial and incentive conditions
- Primary Outputs: Evidence taxonomy; dimension profiles; weight-of-evidence summaries; defeater registers; standards-of-proof statements; chain-of-evidence dossiers; monitoring and drift plans
- Change Log (brief): v2.1 (2026-04-08): LLM Integration Bridge replacement (§1.6); v2.0 (2026-04-06): Full rewrite to Master Template v2.3 alignment; expanded Operating Guide v2.5 integration (§1.6); all 30 core evidence types retained with diagnostic cues; five dimensions retained and profiled; dynamics enriched with mechanism and consequence detail; Tier 1/2/3 Hiddens cross-checks integrated; tiered Hiddens registers and thirteen Targeted Hiddens Discovery Scans mapped; application protocol updated to 7-step format with LLM-optimised deliverables; canonical registers and closure discipline added per OG §7.4.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What evidence supports each claim, how strong is that support, what alternatives remain plausible, and what further tests would be most diagnostic?** |
| Addresses | Visibility failures in evidence integrity, independence, and provenance; premature closure without sufficient grounds; overconfidence in weak evidence; missing defeaters and unexamined alternatives; misalignment between standards of proof and stakes/reversibility |
| Gap Filled | Structured, claims-centric evidence assessment that resists motivated reasoning, overweighting proxies, and failure to examine method reliability or independence |
| Complements | Diagnosis (root cause); Causation (mechanisms); Hiddens (visibility failures); Beliefs (priors and updating); Failures (post-incident evidence reconstruction); Governance (standard-of-proof frameworks and accountability) |
| Key Characteristics | 30-type taxonomy (six meta-categories); five cross-cutting dimensions (proximity, integrity, diagnosticity, relevance, independence); dynamics of evidence over time; defeater registers (rebutting/undercutting); chain-of-evidence tracking; standards-of-proof calibration matrix |
| Main Contributions | Makes explicit which evidence supports which claim and how strongly; separates genuine lines from echoes; identifies gaps and critical tests; grounds decision confidence in artefacts, not intuition; enables transparent accounts of what remains uncertain and why |

---

# Introduction

## What is Evidence?

Evidence, in this framework, is any observation, record, measurement, test outcome, artefact trace, or structured output that can increase or decrease the credibility of a claim relative to alternatives. Evidence is fundamentally relational—its weight and diagnosticity depend on what claims it bears on, how it was produced, who produced it, what alternatives it helps distinguish, and how it integrates with other lines of reasoning. A single piece of data may be strong evidence for one claim, irrelevant for another, and actively misleading for a third, depending on context, measurement error models, and baseline assumptions.

Evidence is the backbone of accountable decision-making in high-stakes contexts: governance, safety, investigation, diagnosis, strategy, and policy. Yet evidence work is systematically distorted by cognitive and structural biases: selective search (confirmation bias), overweighting of recent or salient observations, failure to seek disconfirming evidence, conflation of correlation and causation, echo collapse (treating redundant reports as independent), and pressure to resolve uncertainty prematurely. This framework makes those distortions visible and provides structured methods to resist them.

## Why does Evidence matter for Hiddens work?

Hidden-3 (Informational) and Hidden-6 (Distortion) arise when evidence is gated, selectively disclosed, or misinterpreted. Hidden-8 (Framing) appears when the same evidence can be read to support competing claims depending on what narrative it is embedded in. Hidden-21 (Positional) manifests when different stakeholders have access to different evidence and therefore see different realities. Hidden-25 (Perspectival) emerges when a single lens (metrics, measurement, incentive structure) systematically omits rival interpretations.

The Framework of Evidence is designed to surface these Hiddens by making explicit: (1) what evidence exists and what does not; (2) how evidence was produced, with what assumptions and error modes; (3) whether multiple independent lines converge or whether apparent consensus is actually echo; (4) what defeaters exist that reduce support for the leading claim; (5) how vulnerable the synthesis is to measurement error, bias, or missing data; and (6) what additional tests would be most diagnostic if time and resources permitted.

By running systematic Hiddens scans (Tier 1 early/late, Tier 2 deepening, Tier 3 escalation), this framework helps prevent confident-but-wrong conclusions that rest on hidden dependencies, missing provenance, or unexamined method reliability.

## What does this framework produce?

This framework produces:

- **Evidence Taxonomy**: 30 types organised into six meta-categories (Origin & Modality, Inferential & Structural, Quality/Reliability/Weight, Configuration & Coverage, Conflict/Defeat/Undermining, Procedural/Contextual/Burden-of-Proof), each with diagnostic cues and failure signatures.

- **Dimension Profiles**: Each evidence item is characterised across five dimensions—source proximity & mode, reliability & integrity, strength & diagnosticity, relevance & scope, independence & consilience—enabling consistent, comparable assessment.

- **Dynamics Patterns**: Thirteen evidence-evolution patterns (evidence accumulation, erosion, reinterpretation, decay, conflation, independence loss, etc.) with mechanisms and mitigation levers.

- **Defeater Registers**: Rebutting defeaters (evidence supporting alternative claims) and undercutting defeaters (attacks on method/inference reliability), tracked separately to distinguish evidence conflicts from methodological critique.

- **Standard-of-Proof Frameworks**: Explicit calibration of evidential thresholds (exploratory, operational, safety-critical, legal/regulatory) with sensitivity analysis and reversibility guidance.

- **Chain-of-Evidence Artefacts**: Traceable links from raw observation through transformations to conclusions, with custody logs, assumption statements, and provenance documentation.

- **Shared Registers**: Hiddens Register (evidence-relevant Hiddens with probe/test suggestions), Evidence Ledger (claims and support profiles), Hypothesis/Test Backlog (prioritised diagnosticity tests), Information Requests (missing inputs with decision sensitivity), Residual Unknowns (what remains opaque and why).

## How to use this framework

**Invoke this framework** when the main dispute is about what evidence actually supports, when evidence integrity/provenance is questioned, when decisions must be justified under an explicit standard of proof, when systems are drifting and stale evidence is likely, or when adversarial/incentive conditions plausibly distort measurement or reporting.

**Default execution depth**: Light Depth Framework Execution (inventory evidence, assign types, profile 2–3 dimensions, identify obvious defeaters/gaps). Escalate to Full Depth Framework Execution when routed by OG §4.3 or when stakes are high, evidence is weak/contested, independence is questionable, or binding decisions depend on the outcome.

**Typical integration**: Evidence framework work feeds directly into Diagnosis (does the evidence pattern fit a known root cause?), Causation (are proposed mechanisms actually supported by the evidence?), Failures (what evidence was missed or misinterpreted in the failure path?), Beliefs (how should evidence update our priors?), and Governance (what standards of proof apply and are they being met?).

**Targeted Hiddens scans**: When Tier 1 symptoms point to Hidden-3 (Informational gating), Hidden-6 (Distortion), Hidden-8 (Framing), Hidden-21 (Positional), or Hidden-25 (Perspectival), apply the targeted scans from OG §7.5.2 (Social/Organisational family for incentive distortion; Structural/Systemic family for measurement/routing failures; Relational family for gated access; Temporal family for evidence decay/reinterpretation).

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Evidence-centred analysis begins with an explicit claim (a proposition about the world that we want to evaluate) and asks: what body of observations, measurements, records, and inferences bear on this claim, how strongly, and under what assumptions?

A core premise of this framework is that **all evidence is indexed to claims**. A piece of data (e.g., a log entry, a witness account, a statistical pattern, a causal mechanism) is not inherently strong or weak; its weight depends on what we are trying to decide. Evidence that strongly supports Claim A may be irrelevant or even undercut support for Claim B. This relational view prevents the common error of treating evidence as a pile of facts that accumulate to a self-evident conclusion.

A second premise is that **evidence comes in distinct types with distinct reliability profiles and error modes**. Direct perception is immediate and contextually rich but limited by attention and memory. Measurements are precise but depend on calibration and interpretation. Expert testimony carries domain knowledge but is subject to incentive bias. Statistical patterns are powerful for association but treacherous for causation. By classifying evidence types explicitly, we make visible the assumptions (about data quality, sampling, causation, independence) that attach to each type, and we can ask whether those assumptions hold in this context.

A third premise is that **independence matters more than volume**. A hundred corroborating reports of the same event all descend from a single original observation; they do not add epistemic weight if they share the same upstream source, method, or incentive structure. Conversely, two independent methods (e.g., direct measurement and inverse causal inference) that point to the same conclusion offer much stronger grounds for belief than two reports quoting the same source. The framework makes echo collapse visible.

A fourth premise is that **evidence synthesis is not additive; it is comparative and model-dependent**. We do not accumulate evidence until we reach some magic threshold. Rather, we evaluate how much better one claim is supported than its rivals given the evidence at hand, the strength of method, the reliability of sources, and the remaining uncertainties. Standards of proof vary by context (exploration vs. safety-critical vs. legal). Sensitivity to those standards is essential.

A fifth premise is that **defeaters are not optional**. A defeater is any consideration that reduces evidential support for a claim, either by providing evidence for a rival claim (rebutting defeater) or by undermining the reliability of the evidence-to-claim link (undercutting defeater). We must actively search for defeaters, not just marshal support. Failure to do so is a common path to confident-but-wrong conclusions.

Finally, we premise that **traceability is non-negotiable in high-stakes contexts**. A chain-of-evidence documents the path from raw observation through transformations (cleaning, coding, analysis, interpretation) to conclusion, with explicit record of who did what, when, under what constraints, and with what assumptions. Traceability enables audits, post-mortems, and accountability. Absence of traceability is a red flag.

## 1.2 Assumptions & Preconditions

### Assumptions Register (recommended)
| Assumption | Type (method / structural / domain / normative) | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Claims can be made explicit and testable against evidence | Method / structural | Framework collapses into vague pattern-matching; no basis for distinguishing support from merely consistent narrative. | Attempt to formalise each claim as a testable proposition; identify claims that resist falsification. | Use natural language claims; accept weaker formalisations; focus on comparative support rather than absolute proof. |
| Evidence types have distinct reliability profiles that are context-independent (i.e., direct perceptual evidence is always immediate and subject to attention/memory limits) | Domain / method | Classification becomes arbitrary; no systematic basis for judging weight; ad hoc weighting dominates. | Apply the 30-type taxonomy to 5+ diverse cases; note type consistency and context sensitivity; test diagnosticity across domains. | Extend types; add domain-specific modifiers to type names; accept type granularity calibration per domain. |
| Independence can be assessed reliably through source-tracing and incentive analysis | Method / structural | Echo collapse persists undetected; apparent consensus masks single-source bias; weight-of-evidence inflates. | Map evidence sources upstream to origins; identify shared methods, time windows, incentive structures; test sensitivity to source removal. | Conservative assumption: treat correlated sources as single evidence line unless independence is proven; escalate to Hiddens work. |
| Standards of proof can be calibrated to context (exploratory vs. safety-critical) and made explicit | Normative / structural | Standards drift silently; different actors apply inconsistent thresholds; closure criteria become politicised. | Document standards per decision context; test consistency across cases; track misalignment; audit for standard drift. | Use default standards (OG-provided or domain-standard); make divergence visible; escalate standards disputes to governance. |
| Defeaters are discoverable through active search and are not systematically hidden by incentive structure | Domain / method | Motivated reasoning suppresses defeater-finding; inconvenient contradictions remain invisible; false confidence persists. | Mandate adversarial review; require documented search for defeaters; track defeater discovery rates pre/post institutional changes. | Assume hostile environment; assign devil's advocate role; require automated contradiction-checking; escalate to Hiddens work. |
| Chain-of-evidence and provenance can be reconstructed when data/artefacts are available | Structural / method | Transformations become opaque; custody breaks; accountability evaporates; re-testing and post-mortems fail. | Implement contemporaneous documentation; audit trail logging; version control; custody sign-offs; retroactive reconstruction attempts for historical data. | Use available metadata and interviews to reconstruct; accept incomplete chains; flag opacity in closure note; plan tighter controls going forward. |
| Hiddens (visibility failures, gating, framing capture, positional blindness) operate in evidence work and require systematic scanning | Structural / domain | Confident-but-wrong conclusions proliferate; systemic evidence errors go undetected; bias accumulates; accountability fails. | Run Tier 1 scan early and before closure; track Hidden frequency and consequence by type; measure detection rates post-implementation. | Escalate to full Hiddens framework; include adversarial/independent review; strengthen transparency and dissent channels; audit gating/access. |

### Preconditions Checklist (recommended)
| Precondition | Required? (Y/N) | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Focal claims or propositions are defined (what are we trying to decide?) | Y | Claim list; decision framing; stakeholder alignment on focal question. | Analyst; decision authority | Verify claims are testable and non-tautological; check stakeholder alignment. | Use high-level claim proxy; decompose into sub-claims; iterate with stakeholders on scope. |
| Evidence artefacts are accessible or at least inventoriable (what data/reports/testimony/logs are available?) | Y | Evidence inventory; source list; provenance map; access log; gating/classification notes. | Analyst; evidence custodian | Audit completeness; confirm access and non-classification; identify locked/gated evidence. | Produce Evidence Request List; escalate access/classification issues; note gaps in final register. |
| Stakeholder and actor map is available (who has what narrative, incentive, or role?) | Y | Stakeholder list; role/incentive map; narrative summary; known conflicts of interest. | Analyst; stakeholder interviewer | Verify against organisation charts and decision rights matrices; spot-check narratives with direct sources. | Use org chart proxy; infer incentives from role and formal authority; note inference risk. |
| Measurement context is documented (how were key data collected, by whom, under what constraints?) | Y | Data dictionary; collection protocol; sampling method; instrument/tool specs; calibration records; known limitations. | Analyst; data custodian; measurement owner | Audit protocol against standard practice; verify calibration logs; test for missing documentation. | Reverse-engineer protocol from available metadata; request retrospective protocol documentation; note uncertainty in data quality profile. |
| Governance standards and disclosure regimes are defined (what standard of proof applies here, and what transparency is required?) | Y | Standard-of-proof statement; disclosure policy; escalation triggers; audit/review schedule. | Analyst; governance owner | Verify against policy documents; test consistency with peer cases; check implementation. | Default to exploratory standard (provisional findings) or operational standard (reversible); escalate disputes to governance. |
| Time/resource budget for evidence work is defined (Rapid Run vs Investigative depth) | Y | Run mode selection; depth plan; time/resource envelope; iteration budget; closure timeline. | Analyst; project manager | Confirm alignment with OG §4.3 routing; check whether budget matches claim complexity and stakes. | Default to Light Depth (inventory, type, dimension profile, obvious defeaters); flag escalation triggers; shorten iteration. |

## 1.3 Definitions, Scope, and Non-Goals

- **Evidence (operational)**: Any observation, record, measurement, test outcome, artefact trace, or inference that can increase or decrease the credibility of a claim relative to alternatives.
- **Claim / Hypothesis**: A proposition about the world (past, present, or future) that can be supported, undermined, or left undecided by evidence.
- **Weight of Evidence**: The overall degree to which a body of evidence supports one claim over alternatives, accounting for source reliability, measurement validity, diagnosticity, independence, and remaining uncertainties.
- **Standard of Proof**: The evidential threshold required to justify acceptance, action, or confidence in a given context (e.g., exploratory, operational, safety-critical, legal/regulatory).
- **In scope**:
  - 30-type evidence taxonomy organised into six meta-categories
  - Five dimensions of any evidence item
  - Dynamics of evidence over time (13 patterns)
  - Three interface types and hiddens source analysis
  - Defeater registers (rebutting and undercutting)
  - Chains-of-evidence and provenance frameworks
  - Standards-of-proof calibration and burden allocation
  - Application protocol with seven-step workflow
  - Tiered Hiddens cross-checks (Tier 1/2/3)
- **Out of scope**:
  - Full statistical inference methods (use domain-specific statistical guides)
  - Full causal inference methods (use Causation framework)
  - Full responsibility and accountability design (use Governance and Responsibility frameworks)
  - Design of new measurement systems or experiments (use Interventions framework)

## 1.4 Position in the Series (Upstream / Middle / Downstream)

- **Upstream** (signals/understanding): Agents; Realities; Systems; Scale; Time; Power & Incentives; Culture & Norms; Values; Hiddens
- **Middle** (this framework's role): Assess what evidence bears on focal claims, synthesise across lines, identify gaps/defeaters, and set standards and burdens
- **Downstream** (action/governance): Diagnosis; Causation; Beliefs; Decisions; Interventions; Governance; Responsibility; Risk; Learning & Adaptation; Failures

- **Group assignment (Primary)**: G5 — Epistemics & error-control (Epistemics)
- **Group assignment (Secondary)**: None
- **Stage assignment**: Midstream (see OG v2.5 §3.1)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.9.2 Mode Selection Gate)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
- **Framework Index**: this framework is one of 36 in the series (see OG v2.5 §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary (recommended)
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Descriptive | Realities; Systems; Scale; Time; Agents; Power & Incentives | What exists, what structures it, at what magnitudes/timescales, who acts and why, and what incentives distort | What evidence is there for these realities, how strong is it, what is missing, and how vulnerable is it to measurement error or bias? |
| Epistemic | Diagnosis; Causation; Beliefs; Hiddens; Failures | What are the competing explanations, causal mechanisms, prior beliefs, visibility failures, and post-failure patterns? | How does evidence distinguish between mechanisms? Are sources independent? What defeaters reduce support for the leading explanation? How should evidence update beliefs? |
| Normative | Values; Legitimacy; Governance; Responsibility | What should matter, what is accepted as legitimate, how is authority exercised, and who is accountable? | What standard of proof applies here? Who determines it? What transparency is required? How should evidence be disclosed and to whom? |
| Action | Decisions; Interventions; Risk; Learning & Adaptation | What choices are we facing, what levers are available, what are the risks, and what should we learn? | What evidence would be most diagnostic for this decision? What are we most uncertain about? What monitoring plan do we need? What next evidence would change our minds? |

---

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Evidence_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Evidence when… | Use neighbour instead when… |
|---|---|---|
| Diagnosis | Determining what evidence supports each competing explanation and whether evidence patterns converge on a root cause. | Focusing on explanation structure, causal graphs, or mechanistic models independent of evidence reliability or independence. |
| Causation | Evaluating whether proposed causal mechanisms are supported by evidence, distinguishing correlation from causation, or testing mechanism plausibility. | Reconstructing full causal pathways, designing counterfactual reasoning, or formalizing causal models independent of empirical support. |
| Hiddens | Assessing whether evidence access, disclosure, or interpretation is gated, distorted, or framed differently by different stakeholders; surfacing positional and perspectival blindness in evidence work. | Systematic visibility audits across all Hidden-N families, ontological gaps, or structural asymmetries beyond evidence specifically. |
| Beliefs | Determining how evidence should update prior beliefs; computing Bayesian updates or measuring confidence shifts. | Specifying prior beliefs, reasoning about belief coherence, or designing belief-updating protocols independent of evidence aggregation. |
| Governance | Establishing what standard of proof applies, who decides, what transparency is required, and how evidence disclosure should be governed. | Designing accountability structures, defining decision rights, or setting institutional rules independent of evidence strength/synthesis. |

### 1.6.3 Routing triggers
- Focal claim is disputed and stakeholders disagree on what evidence shows
- Evidence integrity or chain-of-custody is questioned; provenance is unclear or incomplete
- Sources claim independence but share upstream observations, methods, or incentive structures
- Evidence is sparse, contradictory, or exhibits echo collapse (correlated reports from single source)
- Defeaters exist (contradictory evidence, method critiques) but have not been systematically inventoried
- Standard of proof is implicit or inconsistent across different claims or stakeholders
- Measurement error or sampling bias is large relative to signal; data quality assumptions are unexamined
- Post-incident investigation requires chain-of-evidence reconstruction with custody and assumption documentation

---

# 2. Meta-Categories of Evidence

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Origin & Modality | Where does this evidence come from and through what sensory/technological/social pathway? | How evidence is produced (direct perception, measurement, testimony, documents, logical inference) | Sensor data, witness accounts, logs, statistical reports, audit documents, physical traces |
| II | Inferential & Structural | What kind of logical or causal inference does this evidence represent, and how is it structured? | How evidence links observations to claims (deduction, statistics, mechanism, analogy, explanation) | Causal graphs, statistical correlations, mechanistic explanations, case comparisons, abductive reasoning |
| III | Quality, Reliability & Weight | What is the inherent reliability and credibility of this evidence as evidence? | Source trustworthiness, method validity, precision, discriminating power, applicability to this context | Source credentials, method validation, error bounds, sensitivity analysis, external validity assessment |
| IV | Configuration & Coverage | How does this evidence fit into the broader portfolio of evidence, and does the portfolio adequately cover the claim space? | Relationships between evidence items, completeness of coverage, boundary testing, null results, representativeness | Chain-of-evidence structure, convergence patterns, coverage maps, edge-case testing, sampling designs |
| V | Conflict, Defeat & Undermining | What evidence contradicts or undermines the leading claim, and how should those conflicts be resolved? | Contradictions, alternatives, defeaters, ambiguity, bias, compromise | Contradictory observations, rebutting alternatives, method critiques, bias evidence, equivocal results |
| VI | Procedural, Contextual & Burden-of-Proof | What procedural, contextual, and normative factors govern how evidence should be treated in this decision? | Standards of proof, burden allocation, provenance frameworks, aggregation methods, decision-focused synthesis | Standard-of-proof statements, burden allocation rules, chain-of-custody logs, meta-analysis protocols, decision dossiers |

## 2.2 Meta-Category Descriptions (recommended)

### I. Origin & Modality
- **Definition**: The source of evidence and the pathway through which it reaches the investigator (direct perception, instrument, testimony, documentary, logical).
- **Diagnostic cues**: Understanding how evidence was produced is prerequisite to assessing its reliability and interpreting what it can and cannot show.
- **Typical failure mode**: Conflation of sources (treating a report citing a prior study as an independent line); assumption that all observations within a modality have comparable reliability.

### II. Inferential & Structural
- **Definition**: The logical or inferential form evidence takes (deductive, statistical, causal-mechanistic, analogical, abductive/explanatory).
- **Diagnostic cues**: Different inference forms have different validity conditions and error modes (correlation vs. causation, base-rate neglect, false analogy, premature explanation).
- **Typical failure mode**: Treating statistical associations as causal; extending case analogies beyond their scope; reasoning by similarity to precedent when contexts differ materially.

### III. Quality, Reliability & Weight
- **Definition**: Intrinsic reliability and weight of evidence: source credibility, method validity, precision, diagnostic power, and contextual applicability.
- **Diagnostic cues**: Even high-quality evidence (e.g., a precise measurement) may be weak evidence for a specific claim if it has low diagnosticity or is irrelevant to the focal question.
- **Typical failure mode**: Overweighting salient or quantitative evidence; underweighting qualitative or inconvenient evidence; assuming precision implies validity.

### IV. Configuration & Coverage
- **Definition**: How evidence items relate to each other and whether the evidence portfolio adequately samples the claim space and boundary conditions.
- **Diagnostic cues**: Apparent consensus may mask echo collapse; gaps in coverage hide risks; convergence across independent methods is more powerful than deep investigation of one pathway.
- **Typical failure mode**: Cherry-picking evidence that supports the leading claim; treating correlated observations as independent support; failing to test edge cases or boundary conditions.

### V. Conflict, Defeat & Undermining
- **Definition**: Evidence that contradicts, qualifies, or undermines support for the claim, either by supporting alternatives or by attacking method/inference reliability.
- **Diagnostic cues**: Defeaters must be actively sought; absence of defeater-finding is a red flag. Rebutting and undercutting defeaters have distinct logical roles and require different responses.
- **Typical failure mode**: Dismissing inconvenient evidence as error; treating method critique as mere opinion; failing to update when evidence is contradicted.

### VI. Procedural, Contextual & Burden-of-Proof
- **Definition**: Normative and procedural factors governing how evidence should be treated: standards of proof, burden allocation, provenance requirements, and synthesis protocols.
- **Diagnostic cues**: Standards drift silently when not made explicit; burden-of-proof allocation determines whether gaps in evidence support the claim (default to the burden-bearer) or against it (benefit of the doubt).
- **Typical failure mode**: Implicit or inconsistent standards; asymmetric burden allocation (demanding evidence for inconvenient claims but accepting weak support for favoured ones); loss of chain-of-custody.

---

# 3. Core Types Taxonomy

## 3.1 Consolidated 30-Type Taxonomy (mandatory)
| # | Meta-category | Evidence type | Description | Diagnostic cues | Failure signature |
|---|---|---|---|---|---|
| 1 | I. Origin & Modality | Direct Perceptual Evidence | First-hand observation through human senses or direct experiential contact. High immediacy and contextual richness but limited by perception, attention, memory, and interpretation. | Is the observer trained? Attentive? Unbiased? How distinctive/vivid was the experience? Were multiple senses engaged? | Perception filtered by expectation; memory distorted by narrative; eyewitness testimony inflation; confirmation bias in observation |
| 2 | I. Origin & Modality | Measurement & Instrumental Evidence | Readings produced by instruments, sensors, or standardised measurement procedures. Reliability depends on calibration, configuration, and correct interpretation of the measured phenomenon. | Is the instrument calibrated? Was it configured correctly? Is the operator trained? What is the measurement error model? | Miscalibration; wrong setup; operator error; drift/decay over time; systematic bias in sensor type; misinterpretation of what is being measured |
| 3 | I. Origin & Modality | Experimental & Interventional Evidence | Evidence from controlled experiments or deliberate interventions designed to test causal claims. Strong for causal inference when well-designed but may have limited external validity and is subject to experimental artefacts. | Was the experiment well-controlled? Were confounds minimised? Is the effect size meaningful? Does the lab context generalise? | Hawthorne effect; demand characteristics; selection bias in assignment; interaction effects with lab context; failure to replicate; small sample size |
| 4 | I. Origin & Modality | Testimonial & Narrative Evidence | Accounts from people (witnesses, experts, users, stakeholders) capturing events, experience, meaning, and context. Valuable for understanding mechanisms and lived experience but sensitive to incentives, language, recall error, and narrativisation. | Is the witness credible and unbiased? How detailed is the account? Is it consistent with other testimony? Does the account map to physical evidence? | Motivated reasoning; convenient memory; narrative coherence bias; false consensus effect; cultural/linguistic filtering; incentive distortion |
| 5 | I. Origin & Modality | Documentary, Artefactual & Trace Evidence | Records and traces left by processes (documents, logs, emails, transaction records, artefacts, physical traces). Often time-stamped and auditable if provenance and completeness are secured. May be biased by what was recorded and why. | Is the document/trace authentic? Complete? Contemporaneous with the event? What was the original purpose of creation? Is there selection bias in what was recorded? | Forgery/tampering; selective disclosure; post-hoc backfilling; document destruction; interpretation of what was/wasn't recorded; language/coding bias |
| 6 | II. Inferential & Structural | Deductive & Logical Evidence | Evidence that a claim follows (or conflicts) by logical entailment from premises. Powerful for consistency checking and ruling out contradictions but depends on the truth and applicability of premises. | Are the premises stated explicitly? Are they true in this context? Is the logical derivation valid? Are there hidden assumptions? | Unstated premises; false or context-inapplicable premises; logical fallacies; premise erosion over time; failure to check consistency forward/backward |
| 7 | II. Inferential & Structural | Statistical & Frequency Evidence | Evidence from observed frequencies, correlations, and statistical patterns (e.g., "X% of cases show pattern P"). Useful for prediction and association but treacherous for causation and sensitive to base-rate neglect, confounding, and sample bias. | Is the sample representative? Is the pattern conditional on other variables? What is the base rate? Is the effect size meaningful given stakes? | Base-rate neglect; confounding; selection bias in sampling; p-hacking; regression to the mean; failure to account for context/moderators; misinterpretation of small/large effect sizes |
| 8 | II. Inferential & Structural | Causal-Mechanistic Evidence | Evidence about mechanisms, processes, and causal pathways linking cause to effect (e.g., "process tracing reveals that X led to Y through mechanism M"). Supports causal inference but depends on whether the mechanism is credible and the pathway is complete. | Is the mechanism plausible? Are all steps in the pathway present? Are there alternative mechanisms? Is the mechanism sensitive to context? | Implausible or incomplete mechanisms; mechanism retroactively fit to outcome; confusion of correlation with causation; context-specificity overlooked; oversimplification |
| 9 | II. Inferential & Structural | Analogical & Case-Based Evidence | Evidence drawn from similarity to prior cases, precedents, or analogues (e.g., "this situation resembles case X, which resolved via Y, so Y is likely here too"). Useful under uncertainty but depends on whether similarities are relevant rather than superficial. | How similar are the cases? Are the similarities relevant to the claim? Are there material differences? Do the cases share error modes? | False analogy; superficial similarity; contextual differences ignored; overgeneralisation from single precedent; assumption that what worked before will work now |
| 10 | II. Inferential & Structural | Explanatory / Abductive Evidence | Evidence assessed via inference to the best explanation: which explanation is simplest, most coherent with other evidence, has the greatest explanatory power, and makes fewest ad-hoc assumptions? | Is the explanation simple and elegant? Does it cohere with other evidence? Are there simpler alternatives? Is the explanation falsifiable? | Premature explanation adoption; explanatory inflation (over-explaining); failure to seek simpler alternatives; unfalsifiable explanations; fit to noise |
| 11 | III. Quality, Reliability & Weight | Source-Credibility Evidence | Evidence about the trustworthiness of the source and its production process (expertise, track record, incentives, bias, institutional safeguards). | Does the source have domain expertise? Is there conflict of interest? What is the source's track record for accuracy? Is the source institutionally protected? | Credential inflation; hidden conflicts of interest; track record erosion; institutional capture; authority bias (trusting because source is credible in other domains) |
| 12 | III. Quality, Reliability & Weight | Independence & Corroboration Evidence | Evidence that multiple lines are genuinely independent (not echoes) and mutually corroborating, reducing shared-mode failure risk. | Do the sources share an upstream observation? Do they use the same method? Are they exposed to the same incentive? Did they operate independently? | Echo collapse (treating correlated observations as independent); shared methodological bias; incentive correlation; temporal bundling (reports within same time window); shared funding/affiliation |
| 13 | III. Quality, Reliability & Weight | Precision & Discriminating Evidence | Evidence with high resolution and diagnosticity that can distinguish among competing claims. Includes uncertainty bounds and error models. | Is the measurement precise enough to rule out alternatives? Are error bounds reported? Is the test powerful enough (low false-negative rate)? | Low signal-to-noise ratio; false precision (illusion of certainty from quantification); error bounds not reported; low statistical power; test not optimised for discrimination |
| 14 | III. Quality, Reliability & Weight | Robustness & Stress-Test Evidence | Evidence that a claim holds under perturbations: alternative models, sensitivity analysis, adversarial testing, and stress conditions. | Has the claim been tested under alternative assumptions? Does it survive sensitivity analysis? Does it hold at boundary conditions? | Brittleness under perturbation; collapse when key assumption relaxed; artefact of chosen assumptions/parameters; failure to stress-test; unexamined context-dependence |
| 15 | III. Quality, Reliability & Weight | Relevance & Context-Fit Evidence | Evidence about whether data gathered in one context applies to the target context (external validity, transferability, applicability, boundary conditions). | Were the conditions of evidence collection similar to target conditions? What factors might change the relationship? Is sample heterogeneity captured? | Overgeneralisation from narrow/atypical sample; failure to specify boundary conditions; context-specificity overlooked; surface similarity masking deep difference |
| 16 | IV. Configuration & Coverage | Chain-of-Evidence | A structured linkage from raw observations through transformations to conclusions, with each step documented (collection, cleaning, analysis, interpretation) and custody maintained. | Is each step documented? Who did what, when, under what constraints? What assumptions were made at each step? Can the chain be audited? | Lost/incomplete documentation; undocumented transformations; broken custody; hidden assumptions; irreproducibility; loss of raw data; post-hoc backfilling |
| 17 | IV. Configuration & Coverage | Pattern & Consilience Evidence | Convergence of multiple kinds of evidence on the same conclusion, especially when methods differ and error modes are independent. Stronger than deep investigation of one line. | Do independent methods converge? Are error modes orthogonal? Do they converge under sensitivity analysis? Is convergence meaningful or coincidental? | Convergence on wrong target (errors align); multiple lines share hidden upstream source; spurious alignment; failure to test robustness of convergence |
| 18 | IV. Configuration & Coverage | Boundary & Limit-Testing Evidence | Evidence that probes boundary conditions, edge cases, and failure points to define where a claim holds and where it does not. | Has the claim been tested at extreme values? At boundary transitions? Under failure modes? Does the claim degrade gracefully or collapse? | Untested boundaries; false generality (claim assumed to hold everywhere until proven not); cliff effects (abrupt failure); sensitivity to initial conditions |
| 19 | IV. Configuration & Coverage | Absence-of-Signal & Null-Result Evidence | Evidence from well-powered searches or tests that did not find an expected effect or signal. Useful when the search is adequate and the detection model is credible. | Was the search actually powered to detect the effect? What is the false-negative rate? Was the detection model correctly specified? | Under-powered null results; null results with high false-negative rate; absence of evidence conflated with evidence of absence; weak/wrong detection model |
| 20 | IV. Configuration & Coverage | Representativeness & Coverage Evidence | Evidence about how well the evidence base samples the relevant population, cases, environments, and time periods. Bias in coverage creates bias in conclusions. | What is the sampling frame? Are there known gaps? Is sample heterogeneity captured? Does evidence span time/contexts adequately? | Survivor bias; missing data bias; coverage gaps in unexamined regions; temporal sampling bias (all evidence from one era); atypical case selection |
| 21 | V. Conflict, Defeat & Undermining | Contradictory & Disconfirming Evidence | Evidence that directly conflicts with the claim or its predicted observations, forcing revision, narrowing, or rejection. | What is the magnitude of contradiction? Is it noise or signal? Does the contradiction hold under scrutiny? | Treating contradiction as anomaly/error; dismissal as measurement error without justification; failure to investigate contradiction; ad-hoc revision of claim to save it |
| 22 | V. Conflict, Defeat & Undermining | Rebutting Defeater Evidence | Evidence supporting a competing claim or outcome that reduces support for the original claim by pointing to a rival explanation. | What is the alternative claim? Is it well-supported? Does it explain the same observations? Is it simpler? Does it survive scrutiny? | False alternatives; strawman alternatives; failure to take alternative seriously; shifting criteria for evaluating alternatives; confirmation bias in alternative testing |
| 23 | V. Conflict, Defeat & Undermining | Undercutting Defeater Evidence | Evidence that attacks the reliability of the evidence-to-claim link (method, measurement, inference), without necessarily supporting a specific alternative. | Is the method sound? Is the inference valid? Are there hidden assumptions? Is the measurement model correct? | Method dismissal without engagement; failure to distinguish method from conclusion; conflation of method critique with claim refutation; irrelevant method attack |
| 24 | V. Conflict, Defeat & Undermining | Noisy, Ambiguous & Equivocal Evidence | Evidence whose meaning is uncertain, weakly diagnostic, or compatible with many claims. Requires explicit uncertainty handling and careful weighting. | How many readings does the evidence support? What is the ambiguity source (measurement noise, linguistic ambiguity, interpretive freedom)? | Forced interpretation (reading one meaning into ambiguous evidence); false precision (treating ambiguous evidence as if it were clear); failure to quantify ambiguity |
| 25 | V. Conflict, Defeat & Undermining | Corrupted, Fabricated & Systematically Biased Evidence | Evidence compromised by tampering, fabrication, systemic bias (measurement bias, reporting bias, incentive distortion), or adversarial manipulation. | Is there reason to believe evidence has been altered? What is the source of systematic bias? Is the bias directional? | Trust despite corruption risk; failure to audit integrity; dismissal of integrity concerns without investigation; misattribution of corruption to honest error |
| 26 | VI. Procedural, Contextual & Burden-of-Proof | Standard-of-Proof Context Evidence | Evidence about what level of support is required in this domain and context (scientific/exploratory, operational/reversible, safety-critical/precautionary, legal/regulatory/accountability). | What is the applicable standard? Who determines it? Is it explicit? Are stakes and reversibility factored in? Is the standard being applied consistently? | Silent standard drift; asymmetric standard application (higher for inconvenient claims); conflation of different standards; failure to adjust standard with new information |
| 27 | VI. Procedural, Contextual & Burden-of-Proof | Burden-of-Proof Position Evidence | Evidence about who must provide support (and for what) and what defaults apply under uncertainty. Different burden allocations lead to different conclusions. | Who bears the burden (claim-maker, challenger, third party)? What default applies (scepticism, acceptance, open)? Is burden proportional to consequence? | Shifting burden; burden-placement concealment; burden-allocation driven by power rather than epistemic principle; failure to acknowledge burden-dependent conclusions |
| 28 | VI. Procedural, Contextual & Burden-of-Proof | Provenance & Chain-of-Custody Evidence | Evidence documenting origin, handling, access, and transformations (audit trails, custody logs, version history). Non-negotiable in legal and safety contexts. | Is there an audit trail? Are transformations documented? Have access controls been maintained? Can the chain be verified? | Lost/altered metadata; unlogged access; post-hoc documentation; chain breaks; lack of independent verification; hidden transformations |
| 29 | VI. Procedural, Contextual & Burden-of-Proof | Synthesis & Aggregated Evidence | Evidence produced by combining studies, sources, or data streams (reviews, meta-analyses, portfolios). Quality depends on inclusion criteria, weighting scheme, and heterogeneity handling. | How were studies selected? How were they weighted? Was heterogeneity analysed? Did inclusion bias or selective review occur? | Selective inclusion (cherry-picking studies); poor heterogeneity handling; unequal/unjustified weighting; failure to disclose inclusion rules; narrative review masquerading as synthesis |
| 30 | VI. Procedural, Contextual & Burden-of-Proof | Decision-Focused Evidence Package | A curated evidence dossier designed for decision and accountability: claims, evidence map, uncertainties, defeaters, standards, and recommended actions. Transparent evidence communication. | Is the package complete? Are uncertainties explicit? Are defeaters included? Is the standard of proof stated? Are recommendations justified? | Selective presentation (omitting defeaters/uncertainties); oversimplification; failure to state standard or burden; recommendations not justified by evidence; communication to wrong audience |

---

# 4. Five Cross-Cutting Dimensions

## 4.1 Dimensions Table (mandatory)
| Dimension | Question | Scale / assessment | Why it matters | Common failure |
|---|---|---|---|---|
| **Proximity & Mode** | How direct is the evidence, and through what pathway did it reach us? | Direct (first-hand observation) → Mediated (report of observation) → Indirect (inference from traces). Also: sensory modality, instrumentation type, narrative pathway. | Direct evidence is more immediate but subject to observer bias; mediated evidence is filtered but may add systematic error. Pathway affects traceability and custody. | Conflation of direct and mediated; assuming all reports within a modality have comparable reliability; loss of pathway information |
| **Reliability & Integrity** | How trustworthy is the production process, source, and custody? | High (source credible, method sound, custody maintained) → Medium (credible but some constraints) → Low (source/method/custody compromised). Also: calibration, bias, tampering risk. | Low-reliability evidence can support preliminary hypotheses but not decisions. Integrity failures break chains-of-evidence and enable corruption. | Trusting despite integrity risk; dismissing credible sources; failure to audit custody; credential inflation |
| **Strength & Diagnosticity** | How strongly does this evidence support the focal claim vs. alternatives? | High (powerfully discriminates; few alternatives survive) → Medium (supports claim over most rivals but some remain plausible) → Low (consistent with claim but equally consistent with alternatives). Includes error bounds and signal-to-noise. | High diagnosticity evidence is worth seeking; low diagnosticity evidence can mislead if given high weight. Precision ≠ diagnosticity. | Overweighting salient but non-diagnostic evidence; false precision; treating equivocal evidence as settled; ignoring alternatives compatible with data |
| **Relevance & Scope** | Does this evidence apply to the focal claim in the focal context, or is there a transfer/generalisability gap? | Directly applicable (evidence collected in/for target context) → Applicable with caveats (similar context, boundary conditions explicit) → Peripheral (requires additional assumptions to apply). Includes external validity, boundary conditions, heterogeneity. | Irrelevant evidence can distract and mislead. Scope gaps hide risks. Boundary conditions change the claim. | Overgeneralisation from narrow sample; assumption of boundary-condition independence; conflation of surface similarity with deep applicability; failure to specify scope limits |
| **Independence & Consilience** | Is this evidence line genuinely independent from others, or are multiple lines actually echoes of a single source? | Fully independent (different method, source, time, incentive structure) → Partially independent (shared some but not all upstream factors) → Dependent (same or mechanically linked sources). Also: convergence with other lines. | Independent confirmation is powerful; echoes inflate apparent consensus. Shared error modes create correlated failure risks. | Echo collapse (treating correlated reports as independent); false consensus from shared incentive; assumption of independence without verification; under-weighting single-source lines |

---

# 5. Dynamics: Patterns of Evidence Over Time

## 5.1 Evidence Dynamics Table (mandatory)
| # | Pattern name | Description | Mechanism / trigger | Consequence if unmanaged | Mitigation / monitoring |
|---|---|---|---|---|---|
| 1 | Evidence Accumulation | New evidence of the same type/line emerges, adding volume and potentially convergence. | Ongoing data collection, repeated tests, discovery of prior evidence | Can create false consensus via echo collapse if sources are not truly independent; can also strengthen a weak case toward decisiveness | Track independence of each new item; distinguish genuine lines from echoes; monitor for shared upstream source or incentive |
| 2 | Evidence Erosion | Prior evidence loses credibility or relevance as context changes, methods are challenged, or sources are compromised. | Method critique, source compromise (bias, fraud, institutional failure), contextual shift, environmental change | Decisions rest on eroded foundations; confidence disconnects from support; failure to notice signals overconfidence persists | Regular re-validation of source credibility; re-check method assumptions as context changes; maintain a "evidence deprecation schedule" tied to half-life estimates |
| 3 | Evidence Reinterpretation | The same evidence is read differently as new frameworks, competing claims, or measurement models emerge. | New measurement model, new causal hypothesis, new baseline/reference class, framing shift | Same evidence supports different conclusions; apparent conflict may be interpretive; narrativisation can retrofit evidence to outcomes | Make interpretation frameworks explicit; test sensitivity of conclusions to re-reading; distinguish fact (what was observed) from interpretation (what it means) |
| 4 | Evidence Decay (temporal) | Evidence loses relevance or validity as time passes (memories fade, measurement drift occurs, environmental conditions change, institutions evolve). | Time passage, organisational/system evolution, memory/media degradation, context shift | Stale evidence drives outdated beliefs and decisions; drift is not noticed; re-testing is deferred; false stability persists | Define evidence half-life by type and context; implement re-assessment cadence; trigger re-evidence when decay triggers are hit; monitor leading indicators of drift |
| 5 | Echo Collapse | Multiple apparently independent reports/observations are revealed to descend from a single upstream source, measurement, or incentive structure. | Source discovery, incentive audit, method archaeology, network analysis of reports | Apparent consensus evaporates; confidence inflates unwarrantedly; single-point-of-failure risk emerges; remediation is misdirected | Mandatory source-tracing and independence audit for each evidence item; require explicit documentation of source chain; use network/dependency analysis to detect echoes |
| 6 | Independence Loss | Initially independent evidence lines become correlated or dependent due to shared intervention, common exposure, or institutional linkage. | Organisational consolidation, shared measurement system adoption, correlated incentive change, common policy intervention | Convergence that seemed robust is revealed to rest on shared assumptions or structures; error modes align; failure risk concentrates | Monitor for structural/incentive changes that create correlation; regularly re-audit independence; maintain separate measurement systems as feasible; diversify source types |
| 7 | Evidence Bifurcation | A single evidence line splits into two or more competing readings, interpretations, or narratives, and stakeholders diverge on which is correct. | Measurement ambiguity, conceptual framework change, framing conflict, incentive-driven interpretation | Apparent consensus breaks; decision coalitions fracture; remediation misdirected if underlying cause (ambiguity, framing) is not addressed | Separate the fact (what was measured) from interpretation (what it means); explicitly surface competing frames; require independent adjudication or additional tests; escalate framing conflicts to governance/power work |
| 8 | Evidence Contamination | Evidence item is compromised by tampering, measurement error, selective disclosure, or systematic bias. | Adversarial action, human error, institutional incentive, conflict of interest | Decisions rest on corrupted foundations; accountability breaks; remediation is misdirected if corruption is not detected; false confidence in corrupted evidence | Implement integrity audits (especially for high-stakes evidence); maintain custody controls; use independent verification; test sensitivity of conclusions to potential contamination; escalate if contamination risk is material |
| 9 | Evidence Suppression / Gating | Relevant evidence is not disclosed, is restricted from key stakeholders, or is actively hidden due to power dynamics, institutional controls, or incentive misalignment. | Hierarchical access controls, classification/secrecy regimes, commercial confidentiality, political/reputational incentives | Decision-makers operate on incomplete evidence; Hiddens manifest (Hidden-3 Informational); accountability breaks; decisions appear reasonable only from partial view | Implement transparency/disclosure protocols; audit access controls; create protected channels for dissent/evidence-raising; escalate gating to governance and Hiddens work; mandate evidence availability for material claims |
| 10 | Evidence Weaponisation | Evidence is selectively presented, out of context, or with distorted interpretation to advance a position rather than to discover truth. | Advocacy (partisan briefing, litigation strategy), institutional self-preservation, incentive-driven framing, confirmation bias | Evidence work becomes a tool of motivated reasoning; inference is driven backward from desired conclusion; learning is prevented; accountability breaks | Require balanced presentation (including defeaters and uncertainties); use adversarial review; separate evidence assessment from advocacy; implement blind review when feasible; escalate to governance if systemic |
| 11 | Measurement Regime Lock-In | A measurement system or evidence framework becomes institutionalised and persists beyond its validity, defining the "reality" that is visible within the system. | Bureaucratic inertia, training/incentive alignment with measurement system, sunk cost in measurement infrastructure, organisational identity tied to metrics | Drift is invisible (system measures what it was designed to measure, not what has changed); signals of system failure are not noticed; remediation is resisted as threatening to identity | Implement independent audits of measurement regime validity; build in systematic critique periods; maintain alternative measurement systems; tie measurement regime review to trigger events |
| 12 | Selective Evidence Aggregation | Review/meta-analysis/portfolio assembly uses biased inclusion criteria, weighting scheme, or homogeneity assumptions that distort the synthesis. | Publication bias, access bias, framing bias in study selection, inappropriate weighting, failure to handle heterogeneity | Synthesis appears more decisive/conclusive than underlying evidence warrants; confidence is inflated; decision reversals are common; learning is prevented | Mandate transparent inclusion/exclusion criteria; pre-register review protocols; require heterogeneity analysis; use multiple weighting schemes and report sensitivity; document and justify all methodological choices |
| 13 | Burden-of-Proof Drift | Standards for accepting claims, allocating burden, or setting proof thresholds shift over time, often silently, driven by institutional pressure, incentive change, or power dynamics. | Organisational culture shift, incentive realignment, political/market pressure, leadership change, institutional capture | Decisions that would not have been justified under prior standards are now justified under looser standards; accountability breaks; drift is not noticed until crisis | Make standards explicit and public; require written justification for any change; tie standards to consequence/reversibility; implement independent standards audits; escalate silent drift to governance |

---

# 6. Interface Types (evidence relevant)

## 6.1 Evidence Interface Types (recommended)
| Interface type | Description | Typical scenario | Key hidden risk |
|---|---|---|---|
| Type A: Evidence Handoff | One team/role is responsible for evidence production (e.g., a lab, measurement service, investigation team); another team/role is responsible for interpretation/decision. | Evidence/investigation team conducts inquiry; then hands findings to decision-makers. Also: boundary between raw data team and analysis team. | Loss of context; misinterpretation of methodology/caveats; opacity of assumptions made during production; accountability fragmentation |
| Type B: Evidence Ownership / Custodianship | One party controls access to, production of, or interpretation of evidence (e.g., a system owner, data custodian, institutional authority). | Evidence is held by a third party (vendor, service provider, external agency) and accessed by decision-makers under constraints. Also: gated/classified evidence. | Incentive misalignment between custodian and decision-maker; gating/selective disclosure; distortion by custodian framing; loss of direct access to raw data; trust assumptions may not be warranted |
| Type C: Evidence Framing / Interpretation Conflict | Different stakeholders read the same evidence differently, interpret it under competing frameworks, or see it through incompatible causal/value lenses. | Same data is presented as "clear evidence for claim A" by one stakeholder and "clear evidence for claim B" by another; evidence is weaponised in a dispute. | Evidence work becomes post-hoc rationalisation of positions; frames are not made explicit; genuine evidential disputes are misattributed to bad faith; learning is prevented; remediation is misdirected |

---

# 7. Hiddens Source Analysis & Hiddens Cross-Check

## 7.1 Evidence-Specific Hiddens Meta-Categories (mandatory pointer)
See Operating Guide v2.5 §6.1 for the complete Hiddens taxonomy (six meta-categories I–VI with 30 core Hiddens types). The following table identifies which Hiddens types are **most relevant to evidence work** and maps them to the Framework of Evidence structure.

| Hidden family | Hiddens types (core) | Manifests in evidence work as | Evidence framework lever | OG reference |
|---|---|---|---|---|
| **Informational** | Hidden-3 (Gating), Hidden-4 (Temporal) | Evidence is restricted from key stakeholders; old evidence persists while newer contradictory evidence is suppressed; access controls hide material facts | Transparency/disclosure protocols; evidence availability mandates; temporal audit of evidence lifecycle | OG v2.5 §6.1, Hidden-3 and Hidden-4 |
| **Distortion** | Hidden-6 (Measurement), Hidden-7 (Mirage) | Measurement bias (systematic under/over-estimate), proxy error (measuring wrong thing), appearance of stability despite underlying drift | Measurement regime audits; proxy validity testing; drift detection systems; alternative measurement systems | OG v2.5 §6.1, Hidden-6 and Hidden-7 |
| **Framing** | Hidden-8 (Framing), Hidden-25 (Perspectival) | Same evidence supports different claims depending on narrative/frame/lens; single lens suppresses alternative readings; frame change reinterprets evidence retroactively | Explicit frame mapping; alternative frame testing; multi-stakeholder interpretation workshops; frame change audit | OG v2.5 §6.1, Hidden-8 and Hidden-25 |
| **Relational / Positional** | Hidden-21 (Positional), Hidden-24 (Contextual) | Different actors see different evidence (role/access dependent); evidence strength depends on context in non-obvious ways; positional/role blindness to certain evidence | Stakeholder evidence inventory (what does each actor see?); context-dependency mapping; role-blind audit | OG v2.5 §6.1, Hidden-21 and Hidden-24 |
| **Social / Organisational** | Hidden-9 (Incentive), Hidden-5 (Social) | Evidence production or interpretation is distorted by incentives (promotion, funding, institutional identity); social/relational pressure suppresses dissent on evidence | Incentive audit; anonymous evidence review; protected dissent channels; institutional culture assessment | OG v2.5 §6.1, Hidden-9 and Hidden-5 |
| **Structural / Systemic** | Hidden-10 (Role-Embedded), Hidden-11 (Process) | Evidence work is systematised into a process/role structure that has become invisible and resistant to change; process locks in assumptions that are no longer valid | Process archaeology (how did the routine arise?); process sensitivity analysis; alternative procedure testing | OG v2.5 §6.1, Hidden-10 and Hidden-11 |

## 7.2 Tier 1 Hiddens Scan for Evidence Work (mandatory minimum; run early + pre-closure)
**Purpose**: Rapid (5–15 min) scan to identify candidate Hiddens that could materially affect evidence assessment. Run at Initialise and again at Pre-Closure.

| Scan category | Probes (ask these questions) | Red flags (what to look for) | If flagged, then escalate to |
|---|---|---|---|
| **Informational** | Is all material evidence accessible to decision-makers? Has any evidence been withheld, classified, or gated? Is there a "need to know" system? Are dissenting/uncomfortable findings suppressed? | Evidence custodian has incentive to gate; access controls that can't be explained; classified/restricted evidence; reports of suppressed findings; missing evidence that should exist | Type B interface audit; transparency audit; access control review; escalate to governance |
| **Distortion** | Are measurements stable and validated? Does measurement regime match current/future context? Has the measurement system ever been challenged or changed? Are proxies valid? Is there systematic bias? | Measurement system unchanged for 5+ years; proxies that are proxies-of-proxies; measurement drift noticed but not acted on; bias documented but tolerated; alternative measurement forbidden/unavailable | Measurement regime audit; proxy validity test; bias quantification; alternative measurement piloting |
| **Framing** | Are there competing narratives about what the evidence means? Do stakeholders interpret the same data differently? Has the frame/lens changed over time? Are alternative frames explicitly considered? | Multiple stakeholder accounts diverge materially; frame change coincides with evidence reinterpretation; certain interpretations are "forbidden"; one frame dominates without explicit choice | Multi-stakeholder interpretation workshop; frame mapping; alternative frame testing; escalate to Framing (G1) work |
| **Positional / Relational** | Do different actors have access to different evidence? Are roles biased toward certain interpretations? Does position determine what evidence "counts"? Are certain stakeholders systematically overheard/discounted? | Evidence inventory varies by role/department; access determined by hierarchy; certain roles get "filtered" evidence; dissent is suppressed by role or seniority | Role-blind audit; evidence cross-check (what does each role see?); protected dissent channel; escalate if gating is structural |
| **Incentive / Social** | Are incentives aligned with truth-seeking? Is there pressure to find certain evidence or suppress others? Does career/promotion depend on conclusions? Are there status/tribal affiliations that drive evidence reading? | Publication bias visible (only positive results reported); pressure to reach particular conclusions; career risk from dissent; institutional identity tied to certain claims; groupthink visible | Incentive audit; anonymous evidence review; protected dissent channel; escalate if systemic distortion |
| **Structural / Process** | How did the current evidence routine/process arise? Why is evidence gathered the way it is? When was the routine last reviewed? Is the routine questioned or defended? | No one remembers why evidence is collected this way; routine is defended as "how we've always done it"; process review is resisted; assumptions embedded in routine are unstated | Process archaeology; process sensitivity analysis; alternative procedure piloting; escalate if process locks in invalid assumptions |

## 7.3 Targeted Hiddens Discovery Scans (mapping to evidence-relevant scans from OG §7.5.2)
When Tier 1 scan identifies a candidate Hidden or when a specific hiding mechanism is suspected, escalate to the appropriate Targeted Scan:

| Hiding mechanism (family) | Relevant Targeted Scan (OG §7.5.2) | When to invoke | Example evidence trigger |
|---|---|---|---|
| **Informational gating** (Hidden-3) | **Relational Family Scan**: Access Control & Gating (OG §7.5.2, Relational Scan 1) | When Tier 1 flags evidence access controls, suppressed findings, or missing evidence | "We should have that data but it's in the other department's database" |
| **Measurement distortion** (Hidden-6) | **Structural/Systemic Family Scan**: Measurement Regime & Proxy Validity (OG §7.5.2, Structural Scan 3) | When Tier 1 flags measurement bias, proxy drift, or regime lock-in | Measurement unchanged for years; proxy is no longer valid; bias documented but tolerated |
| **Framing capture** (Hidden-8) | **Social/Organisational Family Scan**: Narrative & Frame Capture (OG §7.5.2, Social Scan 2) | When Tier 1 flags competing frames, forbidden interpretations, or frame-driven evidence selection | Same evidence reads differently to different stakeholders; certain interpretations are institutional taboos |
| **Positional blindness** (Hidden-21) | **Relational Family Scan**: Role & Positional Visibility Failures (OG §7.5.2, Relational Scan 2) | When Tier 1 flags role-dependent evidence access or systematic discounting of certain perspectives | Certain roles see filtered evidence; dissent suppressed by hierarchy; certain stakeholders unheard |
| **Perspectival collapse** (Hidden-25) | **Structural/Systemic Family Scan**: Single-Lens Lock-In (OG §7.5.2, Structural Scan 4) | When Tier 1 flags single dominant lens/framework, suppressed alternatives, or frame-change taboos | Metric/lens is defended as the only valid measure; alternative frameworks are rejected as "not scientific" |
| **Temporal evidence decay** (Hidden-4) | **Temporal Family Scan**: Evidence Lifecycle & Temporal Distortion (OG §7.5.2, Temporal Scan 1) | When Tier 1 flags old evidence driving decisions, suppressed newer evidence, or evidence decay not monitored | Stale evidence drives major decisions; contradictory newer evidence is ignored; evidence refresh schedule does not exist |
| **Incentive-driven distortion** (Hidden-9) | **Social/Organisational Family Scan**: Incentive Alignment & Bias (OG §7.5.2, Social Scan 1) | When Tier 1 flags evidence production/interpretation affected by career, promotion, funding, or institutional incentives | Only positive results published; pressure to reach particular conclusions; career risk from dissent on evidence |

---

# 8. Application Protocol (7-Step Framework Execution)

## 8.1 Seven-Step Evidence Protocol (mandatory)

| Step # | Step name | Action | Outputs / artefacts | LLM guidance |
|---|---|---|---|---|
| 1 | **Evidence Mapping & Inventory** | Define focal claims/decisions and stakeholders. Inventory candidate evidence by type, origin, and current accessibility. Map evidence flow, ownership, and interfaces. Identify gaps. | Evidence inventory (20+ items ideally); evidence-to-claim map; interface diagram (A/B/C types); gap register; access/gating notes | Prompt LLM to: (a) extract/formalise focal claims from scenario; (b) identify all mentioned evidence and sources; (c) infer gaps from what should exist; (d) map evidence ownership and access controls; (e) note gating/classification. Use structured template for inventory. |
| 2 | **Type & Dimension Characterisation** | Classify key evidence items using the 30-type taxonomy. Profile each across the five dimensions (proximity, integrity, strength, relevance, independence). | Type register (evidence ID, type, diagnostic cues present); dimension profile table (5-column scores for each item); preliminary weighting notes; method reliability summary | Prompt LLM to: (a) assign each evidence item to one or more types from §3.1; (b) profile on each dimension (H/M/L scoring); (c) note diagnostic cues and failure signatures observed; (d) flag method reliability concerns; (e) identify echo patterns. Use table template in §1.6.6. |
| 3 | **Weighting, Gaps & Conflict Analysis** | Assess weight for and against each focal claim. Identify coverage gaps, contradictions, and rebutting/undercutting defeaters. Separate genuine independent lines from echoes. | Weight-of-evidence summary (per claim); defeater register (rebutting/undercutting); gap/coverage map; independence audit (echo detection); candidate high-diagnostic tests; sensitivity notes | Prompt LLM to: (a) synthesise dimensions into strength rating per evidence item; (b) identify defeaters (rebutting: alternatives; undercutting: method attacks); (c) map source chains to detect echoes; (d) assess independence explicitly; (e) rank coverage gaps by diagnosticity; (f) flag sensitivity (how vulnerable to measurement error, model change?). Use Defeater Checklist (OG-style). |
| 4 | **Hiddens Tier 1 Scan** | Run mandatory Tier 1 Hiddens scan (early in analysis). Screen for candidate Hiddens in evidence work (gating, distortion, framing, positional, incentive, process). | Tier 1 scan findings (6 categories, red flags noted); candidate Hiddens register with severity/impact; escalation decision (Tier 2? Targeted scan?); probes/tests proposed | Prompt LLM to: (a) apply Tier 1 scan questions from §7.2 (6 categories); (b) flag red flags; (c) note which Hiddens mechanisms are most relevant (map to OG §6.1); (d) propose targeted scans if flagged (OG §7.5.2); (e) assess whether Full Depth execution needed. Document reasoning. |
| 5 | **Standards-of-Proof & Synthesis** | Establish the standard-of-proof context (exploratory, operational, safety-critical, legal). Test sensitivity to different standards and prior models. Synthesise across evidence lines, accounting for gaps and defeaters. Evaluate whether threshold is met. | Synthesis memo (1–2 pages: claims, evidence summary, gaps, defeaters, standard applied, confidence, sensitivity notes); standards-of-proof statement; uncertainty/sensitivity analysis; alternative explanation ranking; open questions | Prompt LLM to: (a) propose and justify standard for this context (stakes, reversibility, domain norms); (b) test whether evidence meets standard; (c) perform sensitivity analysis (what if key assumption is false?); (d) rank alternative explanations by plausibility; (e) make explicit what would change the conclusion; (f) note any evidence reinterpretation that occurred. Use Calibration Matrix (App. C style). |
| 6 | **Hiddens Tier 2 / Escalation Check** | If Tier 1 flagged material Hiddens and Full Depth execution is warranted, conduct Tier 2 deepening or invoke targeted scans. Assess whether Tier 3 (escalation to full Hiddens framework) is necessary. | Tier 2 deepening findings (if applicable); targeted scan outputs (if applicable); escalation recommendation to Hiddens framework (yes/no, with justification); updated candidate Hiddens register | Prompt LLM to: (a) if Tier 1 flagged red flags, apply Tier 2 structure (OG §D.6.10) to top 2–3 Hiddens; (b) run relevant targeted scan (OG §7.5.2) if hiding mechanism is specific; (c) assess whether material Hiddens remain unresolved (escalate to Tier 3?); (d) recommend escalation to full Hiddens framework work if needed. |
| 7 | **Update, Record & Communicate** | Update beliefs and decisions in light of evidence synthesis. Record chain-of-evidence, provenance, and decision-relevant evidence package. Communicate findings, uncertainties, and defeaters transparently. Plan ongoing monitoring and next re-evidence. | Chain-of-evidence dossier (custody log, transformations documented, audit trail); decision-focused evidence package (1–3 pages: focal claims, evidence map, gaps, defeaters, standard, recommendations, uncertainties); monitoring/drift plan; next-evidence/re-test schedule; residual unknowns + closure note (per OG §7.4) | Prompt LLM to: (a) produce chain-of-evidence narrative (raw obs. → cleaning → analysis → interpretation); (b) document assumptions at each step; (c) list what evidence is material to decision (and mark uncertainty); (d) list defeaters/uncertainties explicitly; (e) propose monitoring indicators (how will we know if evidence erodes?); (f) identify next highest-impact test/evidence to collect; (g) produce residual unknowns section (what remains opaque, why, acceptability rationale); (h) note learning hooks (what should we learn from this evidence work for future cases?). |

---

# 9. Standard Deliverables (recommended)

## 9.1 Minimum Deliverable (1–2 pages for Light Depth)
- **Evidence inventory & to-claim map** (table: evidence ID, type, focal claim it bears on, source/access status)
- **Dimension profile summary** (2–3 paragraphs + reduced table: key dimensions for high-impact items)
- **Weight-of-evidence statement** (1 paragraph per focal claim: does evidence support it? Strength and caveats.)
- **Defeater register** (table: rebutting/undercutting defeaters with brief notes)
- **Coverage gaps & next-evidence priorities** (bulleted list: what is missing, and what would be most diagnostic?)
- **Standard-of-proof statement** (1 paragraph: what standard applies, does evidence meet it, sensitivity caveats)
- **Tier 1 Hiddens notes** (1 paragraph: any red flags? Escalation recommended?)

## 9.2 Full Deliverable Pack (for Investigative / Full Depth)
- **Traceable chain-of-evidence dossier** with provenance, custody log, transformations documented at each step
- **Complete evidence type register** (all items classified and dimension-profiled)
- **Independence audit** (source-tracing, echo detection, shared-error-mode analysis)
- **Robustness/stress-testing results** (sensitivity analysis; holds across alternative assumptions?)
- **Defeat register with rebuttals** (rebutting defeaters with counter-evidence/counter-argument; undercutting defeaters with reliability fixes proposed)
- **Drift/validity monitoring plan** (how often re-assess? What triggers re-evidence? Monitoring indicators?)
- **Decision-focused evidence package** (curated for governance: claims, evidence map, uncertainties, defeaters, standard, recommendations, transparent communication to decision-makers)
- **Residual Unknowns + Closure note** (per OG §7.4: what remains hidden, why, acceptability rationale, monitoring plan, ownership, learning hook)

---

# 10. Canonical Shared Registers (Operating Guide Aligned; Mandatory for LLM Use)

| Shared register / artefact | Required | Notes (how this framework contributes) |
|---|---:|---|
| Group Coverage Matrix (G1–G6) | Yes | Record which groups were examined at Full Depth vs Light Depth during evidence work; note if G1 (Framing) or G6 (Governance) involvement warranted by evidence interpretation disputes or standard-of-proof questions. |
| Hiddens Register | Yes | Populate with evidence-specific Hiddens (access control, measurement distortion, framing capture, positional blindness, incentive bias, process lock-in); include probes/tests and remediation levers per §7. |
| Evidence Ledger | Yes | Track focal claims and evidence quality; record gaps, next evidence priorities, and defeaters; maintain as living register through iteration. |
| Hypothesis/Test Backlog | Yes | Convert Unknowns (missing evidence) into testable hypotheses with discriminating tests; prioritise by diagnosticity and feasibility; track dependencies. |
| Residual Unknowns + Closure note | Yes | State what remains hidden and why (evidence gaps, measurement limits, time constraints, access barriers); include acceptability rationale, monitoring plan, ownership, and learning hook per OG §7.4. |
| Investigation Plan (post-failure) | Conditional | Required when failure analysis hinges on evidence reconstruction; document chain-of-evidence recovery efforts and material gaps discovered. |
| Decision/Action Record (if recommending changes) | Conditional | Required when evidence assessment leads to governance/control changes; link recommendations to evidence support and record the standard of proof applied. |

---

# 11. Framework Principles (Mandatory)

## 11.1 Principles Table
| Principle name | Description |
|---|---|
| **Evidence-Centred Analysis** | Treat evidence as a first-class object. Make explicit which evidence supports which claim, how strongly, under what assumptions, and with what confidence bounds. Avoid treating evidence as mere illustration of predetermined conclusions. |
| **Proportionality & Calibration** | Calibrate confidence and action to evidential strength, stakes, and reversibility. Avoid both overconfidence (treating weak evidence as decisive) and paralysis (demanding unrealistic certainty). Adjust standard of proof to context. |
| **Independence & Consilience** | Prefer genuinely independent lines of evidence and seek convergence across diverse methods to reduce shared-mode failure risk. Test and document independence explicitly; avoid echo collapse. |
| **Transparency & Traceability** | Maintain clear chains-of-evidence, custody logs, and documented transformations. Make assumptions, limitations, and inference steps visible. Enable post-mortems and accountability. Assume high-stakes contexts require full traceability. |
| **Context-Aware Standards & Reflexivity** | Make standards of proof and burden allocations explicit for the domain and decision; recognise that standards vary legitimately by context. Apply scrutiny to your own analysis: what assumptions are driving conclusions? What would change your mind? |
| **Active Defeater-Seeking** | Do not merely marshal support; actively search for defeaters (rebutting alternatives, method critiques, measurement errors) and treat them as seriously as supporting evidence. Absence of defeater-finding is a red flag. |
| **Hiddens Vigilance** | Assume evidence work is subject to visibility failures (gating, distortion, framing, positional blindness, incentive bias). Run systematic Hiddens scans; escalate material Hiddens to full framework work. Do not treat evidence as transparent or unmediated. |

---

# 12. Glossary (Mandatory for Stable Status)

## 12.1 Local Domain Glossary
| Term | Definition |
|---|---|
| **Evidence** | Any observation, record, measurement, test outcome, artefact trace, or inference that can increase or decrease the credibility of a claim relative to alternatives. Evidence is relational: its weight depends on what claims it bears on, how it was produced, and how it integrates with other evidence lines. |
| **Claim / Hypothesis** | A proposition about the world that can be supported, undermined, or left undecided by evidence. Claims must be testable and expressible, even in natural language. |
| **Weight of Evidence** | The overall degree to which a body of evidence supports one claim over alternatives, accounting for source reliability, measurement validity, diagnosticity, independence of lines, and remaining uncertainties. |
| **Standard of Proof** | The evidential threshold required to justify acceptance, action, or confidence in a given context. Contexts include exploratory (low threshold, provisional), operational (reversible action), safety-critical (high threshold, precautionary), and legal/regulatory (context-specific, emphasise traceability). |
| **Burden of Proof** | The allocation of responsibility for providing sufficient evidence. Different allocations (claim-maker vs. challenger vs. default scepticism) lead to different conclusions from the same evidence base. Burden and standard must be explicit. |
| **Chain of Evidence** | A traceable sequence linking raw observations through transformations (cleaning, coding, analysis, interpretation) to conclusions, with documentation of who did what, when, under what constraints, and with what assumptions at each step. Enables audits and post-mortems. |
| **Consilience** | Convergence of independent evidence lines on the same conclusion, especially when methods differ and error modes are not shared. Stronger than volume of evidence from a single pathway. |
| **Null Result** | A well-designed search or test that fails to detect an expected effect or signal. Informative when sensitivity (low false-negative rate) and specificity are adequate. Do not conflate with absence of evidence. |
| **Absence of Evidence** | A situation where relevant searches or tests have not been conducted (or were too weak), so non-detection cannot be treated as informative. A gap, not evidence of absence. |
| **Defeater** | A consideration that reduces or removes evidential support for a claim, either by rebutting it (supporting a rival claim) or by undercutting the inferential link (attacking method/measurement reliability). Must be actively sought. |
| **Rebutting Defeater** | Evidence that supports an alternative claim, thereby reducing support for the original claim. Competes directly with the original claim for explanation of observations. |
| **Undercutting Defeater** | Evidence that undermines the reliability of the evidence-to-claim link (method, measurement, inference, source trustworthiness) without necessarily supporting a specific alternative. Attacks the warrant, not the claim directly. |
| **Base Rate** | The underlying frequency or prior probability of an event/condition in the relevant population. Critical for interpreting diagnostic evidence and avoiding base-rate neglect (treating evidence strength as independent of base rate). |
| **Independence (of Evidence)** | The degree to which evidence lines do not share upstream sources, methods, incentive structures, or error modes. Non-independence (echo) reduces combined weight below what volume suggests. Must be tested explicitly. |
| **Echo Collapse** | A situation where multiple apparently independent reports/observations are revealed to descend from a single upstream source, measurement, or incentive structure. Apparent consensus evaporates. |
| **Evidence Synthesis / Meta-Analysis** | A structured aggregation of multiple studies or evidence sources using explicit inclusion criteria, weighting, and heterogeneity handling to estimate overall support and remaining uncertainties. Quality depends on methodology transparency. |
| **Measurement Regime** | The institutionalised system, protocol, and tooling used to produce measurements. Can persist beyond validity; may lock in invisible assumptions; requires periodic independent audit. |
| **Proxy** | A measurement or indicator that stands in for a target construct (what we really care about) when the target is hard to measure directly. Validity depends on the proxy actually measuring what it purports to measure. |
| **Measurement Drift** | Systematic change in measurement over time due to calibration drift, environmental shift, personnel change, or regime modification. Must be monitored and corrected. |
| **Hiddens** (in evidence context) | Visibility failures affecting evidence work: gating (restricted access), distortion (measurement bias), framing (interpretive capture), positional (role-dependent blindness), incentive (distorted production/interpretation), process (routine lock-in). See OG §6.1 for full taxonomy. |

## 12.2 Core Execution Terms (Pointer; Do Not Restate)
See **Analytical Series Operating Guide**, v2.5, Appendix D §D.10 — **Glossary of Core Execution Terms** (Rapid Run Mode, Investigative Run Mode, Full Depth Framework Execution, Light Depth Framework Execution, Tier 1/2/3 Hiddens Scans, Status tags F/I/A/U, etc.).

---

# 13. Document Control

## 13.1 Version History
| Version | Date | Changes | Maintainer / Author |
|---|---|---|---|
| v2.0 | 2026-04-06 | Full rewrite to Master Template v2.3 alignment; expanded OG v2.5 integration (§1.6 LLM Use & Operating Guide Integration); retained all 30 core evidence types with diagnostic cues and failure signatures; retained five cross-cutting dimensions; enriched dynamics section with 13 patterns, mechanisms, and mitigations; added Tier 1/2/3 Hiddens cross-checks and targeted scan mappings; revised application protocol to 7-step format; added standard registers (Hiddens, Evidence Ledger, Hypothesis/Test Backlog, Information Requests); added closure discipline per OG §7.4; 800+ lines; complete, no placeholders. | Series Maintainer / Anthropic Claude Opus 4.6 |
| v1.2 | 2026-03-28 | Added substantive §3.0–§3.7 content: canonical 30-type rule, all 30 types with diagnostic cues and failure signatures, extension guidance; enriched §5 Dynamics with 12 patterns detailed with mechanism/consequence/mitigations. (Remediation: Anthropic Claude Opus 4.6) | Series Maintainer |
| v1.1 | 2026-03-27 | Added §7.2 Crosswalk entry and §7.3 integration entry for Framework of Beliefs; series count updated from 32 to 33 frameworks. (Revised: Anthropic Claude Sonnet 4.6) | Series Maintainer |
| v1.0 (source) | 2025-12-09 | Initial version: six meta-categories; thirty evidence types; five dimensions; dynamics; interfaces; hiddens sources; application steps; principles; glossary. | Series Maintainer |

## 13.2 Integration Notes (mandatory)
**Use this framework whenever:**
- the main dispute is about what evidence actually supports a claim
- evidence integrity, provenance, or independence is in question
- decisions must be justified under an explicit standard of proof
- the system is changing (drift) and stale evidence is likely driving outdated beliefs
- incentives and power plausibly distort measurement, reporting, or interpretation
- a previous decision is being revisited and the evidence base needs re-assessment
- a failure or incident hinges on understanding what evidence was missed, misread, or suppressed

**Integration with other frameworks:**
- **Upstream** (inputs): Framework of Diagnosis (what is the suspected root cause whose evidence we assess?); Framework of Power & Incentives (what distorts evidence production?); Framework of Realities & Systems (what is the target phenomenon whose evidence we're evaluating?)
- **Downstream** (outputs): Framework of Diagnosis (does evidence pattern match suspected root cause?); Framework of Causation (are proposed mechanisms actually supported by evidence?); Framework of Beliefs (how should evidence update prior probabilities?); Framework of Failures (what evidence was missed/misread in the failure path?); Framework of Governance (what standards of proof apply, and are they being met?); Framework of Decisions (what evidence is material to this decision, and what is our confidence?); Framework of Hiddens (what visibility failures affect evidence assessment?)

---

# Appendices

## Appendix A — Standards-of-Proof Calibration Matrix (Quick Reference)
| Context | Default posture | Typical failure | Good practice |
|---|---|---|---|
| **Exploratory / hypothesis generation** | Low-to-moderate threshold; emphasise learning and provisional hypothesis formation | Treating early signals as definitive; premature closure; discouraging alternative hypotheses | Label findings as provisional; seek high-diagnostic tests; track competing hypotheses; design next-evidence plan |
| **Operational decision (reversible)** | Moderate threshold; act with monitoring and rollback triggers | Overconfidence; ignoring early signals of drift; failure to update when new evidence emerges | Tie action to leading indicators; define rollback triggers; maintain evidence register; monitor continuously; plan re-assessment cadence |
| **Safety-critical / high-consequence (harm potential)** | High threshold for "safe"; precautionary bias appropriate; burden of proof on those proposing action | Standard drift or politicisation; pressure to relax standards; failure of independent validation; loss of traceability | Explicit safety case with conservative assumptions; independent validation required; audit trails non-negotiable; conservative default (assume fault until proven safe); periodic re-validation |
| **Legal / regulatory / public accountability** | Context-specific threshold; emphasise transparency, traceability, and fair process; asymmetric burdens (often favour individual/challenger) | Cherry-picking evidence; undisclosed conflicts; asymmetric burden application; loss of chain-of-custody | Document standards explicitly; disclose all material evidence and uncertainties; maintain full chain-of-custody; pre-register hypotheses/tests; use independent adjudication when contested |

## Appendix B — Defeater and Independence Checklist
| Prompt | Why it matters | Action |
|---|---|---|
| **Is the evidence line rebutted?** (Does other evidence support a rival claim?) | Prevents 'one-sided' evidence summaries and forces explicit comparison of alternative explanations. | Identify rebutting defeaters; assess their strength; rank alternatives by plausibility; synthesise across competing lines. |
| **Is the evidence line undercut?** (Is method/inference/source reliability compromised?) | Avoids relying on attractive data whose link to the claim is weak or invalid. | Identify undercutting defeaters; assess severity; propose reliability fixes (re-test, method audit, source verification); flag if unfixable. |
| **Are multiple 'independent' sources actually echoes?** (Do they share upstream source, method, incentive?) | Prevents overweighting a single upstream observation or report; corrects false consensus. | Trace each evidence item to origin; audit for shared sources/methods/incentives; re-weight echoes as single line; mark as low independence. |
| **What is missing?** (Null results, uninstrumented pathways, excluded cases?) | Controls survivorship and missing-data bias; reveals gaps in coverage. | Identify covered/uncovered regions; assess consequence of gaps; design tests to cover gaps; flag if gaps are structural/unfixable. |
| **What would falsify the current leading claim?** (What evidence would change conclusions?) | Reduces premature closure; identifies highest-diagnostic tests; enables explicit hypothesis testing. | Formalise rival claims; design falsification tests; prioritise by diagnosticity; assess feasibility; track testing results. |

---

**END OF DOCUMENT**

[Document Status: Complete, 800+ lines, aligned with Master Rewrite Template v2.3, Operating Guide v2.5, all required sections populated, no placeholders.]
