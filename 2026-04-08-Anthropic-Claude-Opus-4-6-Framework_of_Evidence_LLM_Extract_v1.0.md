# Framework of Evidence – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Evidence |
| Primary group | G5 — Epistemics & error-control (Epistemics) |
| Secondary group | None |
| Stage | Middle |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Evidence framework classifies all observations, records, measurements, test outcomes, and inferences bearing on focal claims through six meta-categories and thirty core types, profiles each evidence item across five dimensions (proximity, integrity, diagnosticity, relevance, independence), maps thirteen dynamics patterns of evidence evolution over time, and surfaces evidence-specific visibility failures via tiered Hiddens scans. It enables standards-of-proof calibration, defeater register management, chain-of-evidence tracking, and accountable synthesis grounded in explicit claim-to-support linkage rather than intuitive pattern-matching.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Evidence when… | Use neighbour instead when… |
|---|---|---|
| Diagnosis | You need to catalogue what evidence supports each claim and its strength; focus on evidence inventory, type classification, weight assessment | You need to identify root causes or explain why problems occurred; focus on causal logic and inference independent of evidence collection |
| Causation | You need to assess which causal mechanisms have evidentiary support; focus on evidence-claim relationships and method reliability | You need to map causal structures and test counterfactuals; focus on causal model architecture independent of what evidence supports it |
| Beliefs | You need to understand how beliefs filter what counts as evidence and how evidence updates or fails to update beliefs | You need to classify and profile beliefs and entrenchment mechanisms; focus on belief architecture independent of evidence |
| Hiddens | You need to surface visibility failures specific to evidence (gating, distortion, framing, positional gaps) through systematic scanning | You need to analyse all Hiddens meta-categories as a standalone inquiry; focus on complete visibility audit independent of evidence focus |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Origin & Modality | Direct Perception, Instrumented Measurement, Documentary Record, Testimony/Report, Logical Inference | Where does this evidence come from and through what pathway (sensory, technological, social, logical) does it reach us? |
| II. Inferential & Structural | Deductive, Statistical Association, Causal-Mechanistic, Analogical, Abductive/Explanatory | What form of logical inference does this evidence represent and what validity conditions does that form require? |
| III. Quality, Reliability & Weight | Source Credibility, Method Validity, Precision & Specificity, Diagnostic Power, Contextual Applicability | What is the inherent reliability and weight of this evidence given source, method, and contextual fit? |
| IV. Configuration & Coverage | Independent Convergence, Correlated/Echo, Portfolio Gaps, Boundary & Edge Cases, Null Results & Negative Evidence | How does this evidence relate to other evidence and does the portfolio adequately cover the claim space? |
| V. Conflict, Defeat & Undermining | Contradictory Observations, Rebutting Alternatives, Method/Inference Critique, Ambiguity & Equivocal Results, Bias Evidence | What evidence contradicts or undermines support for the focal claim and how should those conflicts be resolved? |
| VI. Procedural, Contextual & Burden-of-Proof | Standard-of-Proof Statement, Burden Allocation, Chain-of-Custody & Provenance, Synthesis Protocol, Reversibility Assessment | What procedural and normative factors govern how evidence should be treated and what standard of proof applies here? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Evidence accumulation on leading claim | Each new observation confirms prior hypothesis; supporting evidence accumulates; confirmation bias and selective search | Attention focuses on confirming evidence; search patterns favour consistency; incentives reward supporting findings | High confidence despite narrow evidentiary base; vulnerable to unexamined defeaters and blind spots |
| Evidence erosion over time | Supporting evidence becomes questioned, reinterpreted, or retracted; initial consensus weakens; contradictions surface | Better understanding of method limitations; longer observation windows reveal failures; replication attempts fail | Delayed revision of entrenched beliefs; sunk costs in prior decisions make adaptation difficult |
| Echo collapse (correlated sources disguise as independent) | Multiple reports appear to support claim but trace to single origin; consensus is illusory; redundancy masquerades as convergence | Single observation propagates through network; same method applied repeatedly; shared assumptions embedded across sources | Apparent weight-of-evidence inflates; source corruption affects all branches; cascade failure risk |
| Reinterpretation without new evidence | Same evidence re-read to support different claim; framing shift makes old data new meaning; paradigm change recolours facts | Narrative framing changes; new comparison standard emerges; stakeholder incentives shift interpretation | Stability illusion masks meaning shift; creates appearance of consensus despite interpretation divergence |
| Measurement decay and staleness | Evidence loses timeliness as reality evolves but belief persists; static snapshot treated as current state; signal-to-noise degrades | Monitoring ceases; new measurements show change but old beliefs remain; temporal mismatch accumulates | False confidence in outdated models; interventions based on expired baselines; drift goes undetected |
| Method reliability collapse | Measurement system calibration fails, algorithm drifts, sensor degrades, or audit reveals protocol violations | Equipment maintenance neglected; software updates unvetted; operator drift; systematic protocol departure | Evidence base corrupted; conclusions rest on invalid data; retrospective invalidation of prior decisions |
| Independence loss and interdependence growth | Initially independent evidence sources become coupled through shared methods, personnel, incentive, or infrastructure | Consolidation of systems; cost-driven shared platforms; team reorganisations; regulatory harmonisation | Apparent redundancy masks common-mode failure; shock to one source cascades to others |
| Defeater discovery lag | Contradictions exist but are not surfaced until crisis forces review; opponents sit on inconvenient findings; motivated reasoning suppresses contradictions | Active suppression through incentive structure; passive neglect through inattention; social pressure against contradiction-raising | False confidence persists until shock event; lost opportunity for early course correction; accountability confusion |
| Competing narrative encroachment | New narrative reframes same evidence to support rival claim; framing capture redirects interpretation without new evidence | Rhetorical skill and narrative coherence; stakeholder influence and media/communications amplification; incentive alignment with new narrative | Apparent evidence-base stability masks actual meaning volatility; supporters of both narratives feel equally supported |
| Standards drift | Standard of proof quietly lowers (exploratory → operational → safety-critical without explicit transition); closure criteria shift | Normalisation of deviance; fatigue with uncertainty; incentive to decide; scope creep without re-gating | Decision basis becomes weaker than nominal standard; accountability standards slip; post-hoc rationalisation of gaps |
| Boundary blindness | Evidence robust within known domain but breaks at boundaries; edge cases untested; transferability assumed without validation | Inattention to design margins; edge-case testing deferred as "lower priority"; assumption of continuity across boundary | Failure occurs at boundary; surprise when applied to new domain; resilience significantly weaker than expected |
| Proxy drift | Original proxy for focal construct chosen for expedience; metric diverges from underlying reality over time; gaming optimises metric not goal | Measurement convenience; incentive structures reward proxy; operator behaviour shifts to game proxy; loose coupling between metric and reality | System optimises proxy while goal performance diverges; accountability looks good while actual performance fails |
| Framing capture through reference point shift | Same evidence interpreted differently depending on what is treated as reference (baseline, control, comparison group); reference shift changes meaning | Rhetorical choice of comparison; historical narrative shifts; stakeholder power determines reference | Evidence meaning is contingent on frame; apparent consensus masks frame disagreement; reference changes without explicit decision |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What evidence exists but is not perceived; what observations are filtered from attention due to bounded attention, salience bias, or measurement design? |
| II (Systemic) | How does evidence collection, routing, and interpretation couple with institutional incentives; how do procedures systematically filter what evidence enters decision channels? |
| III (Informational) | What evidence is gated, classified, or selectively disclosed; what measurement systems are opaque to downstream users; what data transformations hide provenance? |
| IV (Temporal) | What evidence is based on outdated baselines; what monitoring has ceased; what temporal lags between evidence production and use mask drift? |
| V (Relational) | What evidence is accessible to some stakeholders but not others; what power asymmetries determine who has access to what information; what dissent-suppression mechanisms hide contradictions? |
| VI (Ontological) | What categories or measurement models are invisible as choices; what alternative measurement paradigms are not even conceivable within the current frame; what is treated as objective fact but reflects ontological commitment? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Gating and selective disclosure (evidence withheld, classified, or kept from decision-makers)
- Echo collapse (correlated sources disguise as independent; false weight-of-evidence)
- Measurement opacity (data transformations and method details hidden from users)
- Framing capture (evidence meaning contingent on narrative; reference point choice determines interpretation)
- Positional blindness (different stakeholders have access to different evidence and see different realities)
- Boundary blindness (evidence robust within domain but untested at boundaries)
- Measurement gaming and proxy drift (metrics optimised independent of underlying reality)
- Standard-of-proof drift (evidentiary thresholds lower silently without explicit decision)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Evidence gating or selective disclosure detected | Framework of Governance; Framework of Hiddens (Tier 2) | Access audit; information request tracking; disclosure policy review | Widen evidence access; create safe channels for dissent; audit gating decisions |
| Echo collapse suspected (apparent consensus masks single-source bias) | Framework of Hiddens (Tier 2); Framework of Beliefs (epistemic trust analysis) | Evidence source mapping; origin tracing; independence testing; sensitivity removal | Map evidence genealogy; identify true independent lines; document source dependencies |
| Measurement opacity or gaming detected | Framework of Metrics; Framework of Interventions | Measurement system audit; proxy-goal divergence analysis; gaming vulnerability assessment | Increase transparency; redesign metrics closer to goals; include leading indicators |
| Framing capture or reference-point manipulation suspected | Framework of Narratives; Framework of Perspectives; Framework of Hiddens | Narrative comparison; alternative frame testing; reference-point sensitivity analysis | Expose alternative frames; use multiple comparison points; require explicit frame choice |
| Positional evidence gaps identified | Framework of Power; Framework of Perspectives; Framework of Governance | Stakeholder information access audit; position-outcome correlation; dissent-suppression screening | Equalise information access; protect dissent; cross-position knowledge exchange |
| Boundary or edge-case blindness suspected | Framework of Risks; Framework of Realities; Framework of Systems | Boundary testing; edge-case scenario design; external validity assessment | Test at boundaries; extend evidence to new domains; challenge continuity assumptions |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal claims or decision question; list key evidence types (direct observation, measurement, document, testimony, inference) and categorise into meta-categories I–VI.
2. For each major evidence item, profile two dimensions: origin (how was it produced?) and reliability (how trustworthy?); note obvious gaps or defeaters.
3. Run Tier 1 Hiddens scan across six meta-categories; flag gating, opacity, framing, or positional gaps; note information access asymmetries.
4. Identify 2–3 highest-consequence Hiddens with detection interface and remediation pathway.
5. Shortlist 2–3 most critical missing evidence items; assess decision sensitivity to each gap.

### 7b. Full Depth Execution (Complete framework run)

1. Inventory all available evidence (observations, measurements, documents, testimony, reports, artefacts); document source, method, provenance, access status.
2. Classify each evidence item into meta-categories and core types; profile across five dimensions (proximity, integrity, diagnosticity, relevance, independence); document assumptions.
3. Map defeaters: search actively for contradictions, rebutting alternatives, and method critiques; distinguish rebutting (supports rival claim) from undercutting (attacks reliability) defeaters.
4. Analyse evidence dynamics: identify patterns (accumulation, erosion, echo collapse, reinterpretation, decay, drifting standards, framing capture); assess consequence of each.
5. Assess independence: trace evidence sources to origins; identify correlated/echoed evidence; map true independent lines; test sensitivity to source removal.
6. Run Tier 1 + Tier 2 Hiddens scan: for each meta-category, identify high-relevance Hiddens; develop detection interface (how to surface) and remediation interface (how to address).
7. Calibrate standard-of-proof; allocate burden; produce weight-of-evidence summary; document chain-of-evidence; generate residual Unknowns and escalation assessment.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add evidence-specific Hiddens (gating, opacity, framing, positional gaps); meta-category tag; mechanism; detectability; consequence | After Tier 1 scan; escalate high-consequence to Tier 2 |
| Evidence Ledger | Record focal claims, evidence items, types, dimension profiles, defeaters, independence assessment, weight-of-evidence rating, standard-of-proof applied | After evidence classification and analysis |
| Hypothesis/Test Backlog | Propose diagnostic tests to reduce top Unknowns; prioritise by decision sensitivity; note evidence gaps most critical to decision | For all identified Unknowns and remaining defeater gaps |
| Information Requests | Request access to gated evidence; request source documentation and provenance; request method validation and sensitivity analysis | To support independent lines and reduce information asymmetries |

**Gate Question (pre-closure check):** Have we inventoried focal evidence, classified it (meta-categories I–VI, core types), assessed reliability and independence, searched for and documented defeaters, run Tier 1 Hiddens scan across all six categories, and escalated high-consequence Unknowns to appropriate frameworks (Governance, Metrics, Hiddens)?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs

- Diagnosis (focal claim definition; decision context)
- Realities (what is true or plausible in this domain; observational and measurement context)
- Causation (what causal mechanisms have been proposed; how are they tested?)
- Beliefs (what priors do stakeholders hold; how should evidence update them?)
- Power & Incentives (what incentive structures may bias evidence collection/reporting?)
- Hiddens (what visibility failures may suppress inconvenient evidence?)

### 8b. Downstream Handoffs

- Framework of Diagnosis (evidence weight assessment informs causal attribution)
- Framework of Causation (evidence of mechanisms and counterfactuals)
- Framework of Beliefs (evidence against entrenched beliefs; paradigm boundaries in evidence interpretation)
- Framework of Metrics (evidence supporting metric choice; proxy-goal alignment)
- Framework of Governance (standards-of-proof calibration; burden allocation; accountability frameworks)
- Framework of Risk (evidence of failure modes, cascades, and low-probability high-consequence events)

### 8c. Targeted Scans

| Targeted Scan | Role of this framework |
|---|---|
| Evidence Integrity Scan (Family C, Scan 2) | Surface gating, opacity, and distortion in evidence systems; audit method reliability; test for measurement gaming |
| Information Asymmetry Scan (Family B, Scan 1) | Detect positional blindness and stakeholder-specific evidence access; map who knows what and why |
| Measurement & Proxy Drift Scan (Family C, Scan 4) | Identify metric-goal divergence; assess proxy gaming vulnerability; test measurement system reliability |

---

*LLM Execution Extract v1.0 – Evidence Framework (2026-04-08) – End of Extract*
