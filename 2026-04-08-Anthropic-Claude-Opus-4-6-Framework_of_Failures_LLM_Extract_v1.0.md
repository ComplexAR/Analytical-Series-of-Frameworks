# Framework of Failures – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Failures |
| Primary group | G5 — Epistemics & error-control (Epistemics) |
| Secondary group | None |
| Stage | Middle |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Failures framework classifies cognitive, inferential, and epistemic error types through six meta-categories and thirty core failure modes, profiles each failure across five dimensions (triggering mechanism, perceptual signature, reasoning stage, persistence, consequence), maps twelve dynamics patterns of how failures propagate and entrench, and surfaces failure-driven visibility failures via tiered Hiddens scans. It enables post-incident failure reconstruction, identifies which failure modes are likely in context, and designs interventions targeting root mechanisms (cognitive bias, motivation, priors, attention, social proof) rather than symptoms.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Failures when… | Use neighbour instead when… |
|---|---|---|
| Beliefs | You need to understand cognitive failure mechanisms as error manifestations; focus on failure types and their root causes | You need to map belief architecture and entrenchment; focus on belief formation and persistence mechanisms |
| Evidence | You need to trace how evidence was misinterpreted, misweighted, or ignored in failure path; focus on evidence-specific error types | You need to assess what evidence supports focal claims; focus on evidence strength independent of failure context |
| Causation | You need to analyse causal reasoning errors (false causality, reversed causality, confounding); focus on inference error mechanisms | You need to map causal structures and test counterfactuals; focus on actual mechanisms independent of error types |
| Diagnosis | You need to identify cognitive failures contributing to diagnostic error or mis-attribution; focus on error types and their consequences | You need to identify root causes using causal logic; focus on what actually caused the problem |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Attention & Perception Failures | Inattentional Blindness, Salience Bias, Normalisation of Deviance, Availability Bias, Signal-Detection Failure | What should have been noticed but was missed due to attention limitations or bias? |
| II. Memory & Inference Failures | Hindsight Bias, Reconstruction Failure, False Memory, Confabulation, Anchoring | What was misremembered or reconstructed incorrectly, affecting inference? |
| III. Causal Reasoning Failures | Correlation-Causation Confusion, Reverse Causality Error, Confounding Variable, Post-Hoc Reasoning, Base-Rate Neglect | What causal claims were made without adequate causal reasoning or controls? |
| IV. Probabilistic Reasoning Failures | Overconfidence, Overestimation of Small Probabilities, Underestimation of Large Probabilities, Regression-to-Mean Neglect, Conjunction Fallacy | What probability judgements were miscalibrated or violated basic logic? |
| V. Motivated Reasoning & Bias | Confirmation Bias, Motivated Skepticism, Defensive Reasoning, Dissonance Minimisation, Hypothesis Protection | What evidence was selectively sought or interpreted to protect preferred beliefs? |
| VI. Social & Institutional Failures | Groupthink, Conformity Pressure, Authority Deference, Diffused Responsibility, Organisational Learning Failure | What was the social or institutional contribution to the failure (not just individual cognitive error)? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature | Mechanism | Consequence |
|---|---|---|---|
| Failure cascade | Single failure triggers subsequent failures; error compounds as intervention attempts fail; cascade accelerates | Sunk costs anchor in failed approach; cognitive commitment deepens; organisational pressure to protect prior decisions | Exponential impact growth; intervention timing critical; late correction much more costly |
| Normalisation of deviance | Small deviations from standard become accepted as normal; boundary between acceptable and unacceptable erodes gradually | Incremental change makes shift invisible; organisational routines adapt to deviation; incentive to accept deviation; habituation | Dramatic failure surprises; brittleness increases invisibly; recovery from normalised deviance requires disruption |
| Institutional entrenchment | Failure root cause embedded in structures, procedures, incentives, or role definitions rather than individual cognition; persists despite turnover | Systems and procedures codify error-prone assumptions; incentive structures reward the error; structural change is costly | Individual-level interventions fail; blame shifts to person rather than system; institutional learning requires structural change |
| Hindsight bias distortion | Post-failure reconstruction misidentifies root causes by treating outcome as inevitable in hindsight; alternative paths appear unrealistic | Outcome knowledge shapes causal attribution; narrative closure pressure; incentive to explain failure as foreseeable | Wrong causal model adopted; ineffective preventive measures; escalating blame and accountability conflicts |
| Sunk-cost anchoring | Prior investment in failed approach creates reluctance to change despite evidence it is failing; escalation to commit | Cognitive commitment; institutional sunk costs; reputational stakes in prior decision; incentive to avoid admitting error | Throwing good resources after bad; extended failure duration; delayed course correction; larger total loss |
| Defensive strategy hardening | As failure evidence accumulates, defenders become more committed, generate rationalisations more elaborate, and suppress contradictions more vigorously | Cognitive dissonance and identity threat; organisational rank and authority stakes; power defence; social proof among defenders | Apparent consensus masking active suppression; early intervention becomes impossible; defensive coalition hardens |
| Echo cascade | Initial false belief or failed interpretation propagates through network as sources quote each other; false consensus emerges; correction blocked by network inertia | Network propagation of initial error; source dependence; social proof; incentive to maintain consistency across network | Systemic belief in false claim; correction requires breaking multiple dependencies; network-wide correction difficult |
| Overconfidence expansion | Confidence exceeds evidence quality; despite evidence of failure, confidence persists or increases; defensive reasoning expands confidence | Motivated reasoning; identity stakes; organisational pressure to project certainty; cognitive bias in confidence calibration | Under-preparedness for failure; delayed recognition; plans unstressed; resilience insufficient for actual variability |
| Attribution error persistence | Failure attributed to external circumstances or bad luck rather than internal mechanisms; accountability deflected; learning prevented | Fundamental attribution error; incentive to protect self or institution; defensive narrative; external locus of control | Systemic root causes unaddressed; failure repeats; organisational learning blocked; accountability confusion |
| Learning failure and repetition | Failure analysis incomplete or not acted upon; systematic lesson extraction fails; same failure repeats despite prior incident | Institutional memory loss; analysis not connected to practice change; incentive to move past failure; rootcause vs symptom confusion | Pattern of repeated failures; increasing brittleness; credibility loss; escalating external oversight needed |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What warning signs were present but not perceived; what did observers miss due to inattention, salience bias, or normalisation of deviance? |
| II (Systemic) | How do institutional structures, incentives, or procedures embed failure-prone assumptions; what systemic contributors to failure are invisible as such? |
| III (Informational) | What evidence of failure risk existed but was not accessed, was gated, or was suppressed; what measurement systems missed early signals? |
| IV (Temporal) | What temporal patterns or leading indicators of failure were visible but interpreted differently; what trend changes were not recognised? |
| V (Relational) | Who knew what was going wrong but remained silent due to psychological safety concerns or retaliation risk; what dissent was suppressed? |
| VI (Ontological) | What paradigm or mental model made certain failure modes unthinkable; what was outside the frame of plausible failure types? |

### 6b. Primary Hiding Mechanisms

- Normalisation of deviance (small boundary erosions invisible until failure)
- Institutional entrenchment (failure root causes in structures, not individuals)
- Hindsight bias distortion (post-hoc causal misattribution)
- Defensive reasoning and consensus distortion (suppression of contradiction)
- Attribution error persistence (external locus prevents learning)
- Silent knowledge (observers aware but not speaking due to safety/retaliation)
- Measurement/monitoring blindness (early signals not detected)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Normalisation of deviance evident | Framework of Culture & Norms; Framework of Governance | Boundary audit; deviation trend analysis; norm strength assessment | Re-establish clear boundaries; increase monitoring sensitivity; reward dissent on boundary violations |
| Institutional failure mechanism identified | Framework of Governance; Framework of Systems | Structural analysis; incentive audit; procedure redesign | Redesign structures/incentives/procedures to prevent mechanism; implement structural redundancy |
| Silent knowledge detected (observers knew but didn't speak) | Framework of Culture & Norms; Framework of Governance | Anonymous feedback; dissent-suppression assessment; retaliation-risk audit | Strengthen psychological safety; establish protected dissent channels; remove retaliation incentives |
| Post-failure attribution error | Framework of Diagnosis; Framework of Learning & Adaptation | Competing hypothesis testing; counterfactual analysis; systemic root-cause analysis | Apply rigorous causal analysis; test external vs internal attribution; design systemic corrections |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal failure or failure pattern; classify into meta-categories (attention/perception, memory/inference, causal reasoning, probabilistic reasoning, motivated reasoning, social/institutional).
2. Surface early warning signs that were missed; trace attention, salience, and normalisation-of-deviance factors.
3. Run Tier 1 Hiddens scan: check for silent knowledge, institutional embeddedness, paradigm blindness, measurement gaps.
4. Identify 2–3 most consequential failure mechanisms with detection interface.
5. Flag any institutional or systemic root causes for escalation to Governance/Systems frameworks.

### 7b. Full Depth Execution (Complete framework run)

1. Reconstruct failure timeline and causal chain; identify where decision/reasoning departed from best available evidence or logic.
2. Classify all identified failures into six meta-categories and thirty core types; profile each across five dimensions (mechanism, signature, stage, persistence, consequence).
3. Analyse failure dynamics: identify cascades, normalisation patterns, institutional entrenchment, defensive escalation, learning failures.
4. Assess contribution of cognitive factors (attention, memory, reasoning, probability, motivation) vs institutional factors (structures, incentives, procedures, roles).
5. Map silent knowledge: identify who knew or could have known failure was likely but didn't speak; assess retaliation risk and psychological safety.
6. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence failure mechanism, identify detection interface (how to surface early) and remediation interface (how to prevent).
7. Document systemic root causes and recommend structural vs individual-level interventions; distinguish hindsight-bias-distorted causal claims from actual root mechanisms.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add failure-related Hiddens (normalisation, institutional embedding, silent knowledge, paradigm blindness); mechanism; detectability | After Tier 1 scan; escalate high-consequence to Tier 2 |
| Hypothesis/Test Backlog | Propose tests to distinguish cognitive vs systemic failures; test competing root-cause hypotheses | For ambiguous failure mechanisms |
| Information Requests | Request access to pre-failure monitoring data, communication records showing silent knowledge, organisational procedures and incentive designs | To support root-cause analysis and prevent-recurrence design |

**Gate Question (pre-closure check):** Have we reconstructed failure timeline, classified failures (meta-categories I–VI), distinguished cognitive from institutional contributors, identified silent knowledge and suppressed signals, run Tier 1 Hiddens scan, and escalated systemic/structural root causes to appropriate frameworks (Governance, Systems, Culture & Norms)?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs

- Beliefs (entrenched beliefs and defensive reasoning contributing to failure)
- Evidence (evidence missed, misweighted, or ignored in failure path)
- Causation (competing causal hypotheses for failure root causes)
- Culture & Norms (social enforcement and silence spirals enabling failure)
- Power & Incentives (incentive structures rewarding failure-prone behaviour)

### 8b. Downstream Handoffs

- Framework of Diagnosis (identifying actual root causes beneath hindsight-bias distorted narratives)
- Framework of Governance (structural redesign to prevent failure recurrence)
- Framework of Learning & Adaptation (post-failure learning loops and institutional memory)
- Framework of Risk (failure modes as precursor to risk management)
- Framework of Interventions (remediation design targeting failure mechanisms)

### 8c. Targeted Scans

| Targeted Scan | Role of this framework |
|---|---|
| Normalisation of Deviance Scan (Family A, Scan 2) | Surface boundary erosion and deviance normalisation; audit against baseline standards |
| Silent Knowledge & Suppressed Dissent Scan (Family B, Scan 2) | Identify observers who knew failure was likely but remained silent; assess retaliation risk |
| Institutional Learning Failure Scan (Family C, Scan 3) | Identify systemic barriers to extracting and implementing lessons; test learning transfer |

---

*LLM Execution Extract v1.0 – Failures Framework (2026-04-08) – End of Extract*
