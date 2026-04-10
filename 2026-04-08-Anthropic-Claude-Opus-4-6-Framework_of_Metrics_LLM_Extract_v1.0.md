# Framework of Metrics – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Metrics |
| Primary group | G5 — Epistemics & error-control (Epistemics) |
| Secondary group | G7 — Governance & accountability (Governance) |
| Stage | Middle |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Metrics framework classifies all forms of measurement, quantification, and performance tracking through six meta-categories and thirty core types, profiles metrics across five dimensions (validity, reliability, responsiveness, gaming-vulnerability, goal-alignment), maps ten dynamics of how metrics drift from goals and enable gaming, and surfaces metric-specific visibility failures via tiered Hiddens scans. It enables explicit metric-goal alignment testing, metric validity and reliability auditing, gaming-vulnerability assessment, and multi-metric dashboards that prevent single-metric optimisation from degrading actual performance. It populates Evidence Ledger, Information Requests, and Hypothesis/Test Backlog with metric-design and metric-validation requirements.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Metrics when… | Use neighbour instead when… |
|---|---|---|
| Evidence | You need to assess reliability and validity of measurements and data systems; focus on measurement quality and method | You need to weight evidence supporting focal claims; focus on evidence strength independent of measurement systems |
| Diagnosis | You need to identify whether metrics correctly signal root causes or mask them; focus on metric-diagnosis alignment | You need to identify actual root causes; focus on causal inference independent of metric reliability |
| Risk | You need to design metrics and KPIs that surface tail-risk and low-probability high-consequence events; focus on metric coverage of risk space | You need to quantify probability and impact of specific risks; focus on risk calculation independent of measurement design |
| Governance | You need to audit metrics for alignment with institutional incentives and accountability structures; focus on metric-governance coupling | You need to design governance structures and accountability regimes; focus on governance independent of specific metrics |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Measurement Modalities | Direct Observation & Count, Instrumented Measurement, Proxy Indicator, Aggregated/Composite, Qualitative/Subjective | How is performance being measured and what are the measurement assumptions? |
| II. Metric Coverage & Granularity | High-Level Outcome Metric, Process Metric, Leading Indicator, Lag Indicator, Boundary/Edge-Case Metric | What aspects of performance are measured and what is unmeasured? |
| III. Metric Validity & Reliability | Face-Validity Metric, Criterion-Valid Metric, Construct-Valid Metric, Reliable/Stable Metric, Measurement-Error Profile | Is the metric actually measuring what we intend to measure? |
| IV. Metric Responsiveness & Sensitivity | Fast-Response Metric, Slow-Response Metric, Threshold-Sensitive Metric, Noisy/High-Variance Metric, Insensitive/Flat Metric | How quickly does the metric respond to actual changes in performance? |
| V. Gaming & Perverse-Incentive Vulnerability | Gaming-Resistant Metric, Gaming-Vulnerable Metric, Metric-Gaming-Detection Capacity, Incentive-Aligned Metric, Perverse-Incentive Risk | Is the metric resilient to gaming or does optimisation diverge from goal? |
| VI. Metric Integration & Multi-Metric Frameworks | Single Metric, Portfolio/Dashboard, Correlated Metric Set, Independent Metric Set, Metric-Outcome Alignment Validation | Are multiple metrics integrated to prevent single-metric capture? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature | Mechanism | Consequence |
|---|---|---|---|
| Metric-goal divergence | Metric optimisation proceeds while actual goal performance degrades; reported success masks real failure | Proxy becomes target; gaming easier than goal achievement; feedback loops reward gaming; monitoring misses divergence | Institutional performance appears strong on metric while real performance fails; post-failure surprise and accountability confusion |
| Metric gaming and optimisation | System behaviour reorganises to optimise for metric independent of goal relevance; metric becomes decoupled from outcome | Incentive structure rewards metric optimisation; gaming easier than goal achievement; creativity in meeting letter not spirit | Goal performance collapses despite metric success; visible before large-scale failure if monitoring adequate; high waste of effort |
| Gaming-blindness in governance | Gaming evident to operators but invisible to governance layer; governance sees metric success; operators know goal is not being met | Information asymmetry; operators incentivised to hide gaming; governance assumes metric accurately reflects goal; measurement opacity | Delayed detection of gaming and divergence; governance decisions made on false signal; institutional resilience undermined |
| Metric creep and proliferation | Initial metric expanded; similar metrics added; metric portfolio becomes unwieldy; maintenance and interpretation burden grows | Cost-benefit not evaluated; incentive to avoid single-metric risk creates over-correction; institutional inertia | Management attention diluted; data becomes noise; original intent obscured; metric portfolio becomes unmaintainable |
| Metric desensitisation | As metric variance in normal range, sensitivity and attention atrophy; changing threshold expectations; anomaly detection capability erodes | Habituation and cognitive adaptation; costs of false alerts; incentive to raise anomaly thresholds; monitoring fatigue | Early warning lost; tail-event detection capability degraded; surprise when unusual occurs |
| Proxy validity erosion | Metric was valid proxy for outcome when designed; context changes or new confounding factors emerge; metric continues as if still valid | Assumption checked at design time but not revisited; institutional inertia; cost of metric redesign; path dependency | Metric continues signalling success even as outcome fails; false signal until large-scale failure forces recognition |
| Measurement system drift | Calibration specifications slowly violated; operator technique deviates; upgrades introduce bias; metric becomes invalid over time without explicit invalidation | Maintenance deferred; calibration drift undetected; operator technique varies; formal checking becomes routine; threshold exceeded gradually | Metric validity erodes invisibly; decisions rest on invalid data; post-hoc invalidation of prior decisions; accountability confusion |
| Gaming-feedback escalation | Operators discover gaming; governance responds with metric tightening; operators invent new gaming; metric complexity increases; arms race escalates | Incentive misalignment creates persistence; metric tightening triggers new gaming; control costs spiral; sophistication of gaming increases | Metric system becomes brittle and unmaintainable; governance loses control; eventual metric system collapse or abandonment |
| Outcome attribution confusion | Metric changes but causality to intervention or system change unclear; metric attributed to intervention but driven by external factor | Temporal coincidence misread as causality; missing confounding factors; lack of control conditions; incentive to claim credit | Wrong interventions credited; learning fails; sunk costs in ineffective interventions; opportunity cost of foregone effective interventions |
| Balanced-scorecard erosion | Multiple-metric approach designed to prevent single-metric gaming; over time, governance defaults to single favoured metric; balance erodes; single-metric gaming re-emerges | Cognitive load of managing multiple metrics; incentive to simplify; consensus around one metric; sunk costs in single metric | Balanced-scorecard protection against gaming lost; system reverts to single-metric vulnerability; cycle repeats |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question |
|---|---|
| I (Perceptual) | What performance dimensions are not being measured; what is observable but unmeasured; what measuring blinds attention to unmeasured reality? |
| II (Systemic) | How do metric systems embed incentive structures that encourage gaming; what institutional procedures normalise metric-gaming? |
| III (Informational) | What measurement data is not visible to downstream users; what data transformations hide provenance; what gaming is undetected? |
| IV (Temporal) | What metric lags hide real-time performance deterioration; what fast-moving changes are invisible to slow metrics? |
| V (Relational) | Who knows metrics are gaming but remains silent; what retaliation risk suppresses honesty about metric validity; what knowledge asymmetries exist? |
| VI (Ontological) | What metric paradigm forecloses measurement of alternative values; what is unmeasurable within current metric frame? |

### 6b. Primary Hiding Mechanisms

- Metric-goal divergence (metric optimisation masking outcome failure)
- Gaming invisibility (operators gaming but governance unaware)
- Proxy validity erosion (outdated proxy continuing as if valid)
- Measurement system drift (calibration violation not detected)
- Outcome attribution confusion (metric change attributed to wrong cause)
- Silent knowledge about gaming (operators aware but not reporting)
- Metric insensitivity (low responsiveness misses early signals)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Metric-goal divergence suspected | Framework of Metrics (full analysis); Framework of Diagnosis | Goal-metric alignment audit; outcome tracking vs metric tracking comparison | Redesign metric closer to goal; add outcome verification; increase monitoring frequency |
| Gaming detected or suspected | Framework of Governance; Framework of Incentives | Gaming vulnerability assessment; incentive-structure audit; operator interviews (anonymous) | Redesign metric to resist gaming; modify incentive structure; increase measurement transparency |
| Proxy validity in question | Framework of Metrics (validity audit) | Correlation analysis (metric vs outcome); confounding-factor screening; proxy-redesign testing | Test proxy validity; redesign if inadequate; transition to direct outcome measurement |
| Measurement system drift | Framework of Metrics (system audit) | Calibration audit; operator-technique audit; specification compliance check | Implement calibration schedule; operator retraining; formal specification enforcement |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal metrics (top 3–5) used for performance assessment; classify by modality (direct count, instrumented, proxy, composite, qualitative).
2. For each metric, test: Is this metric valid (measures what we intend)? Is it responsive (updates when performance changes)? Is it gaming-vulnerable?
3. Run Tier 1 Hiddens scan: check for metric-goal divergence, gaming invisibility, proxy invalidity, measurement opacity.
4. Design simple validity test (does metric track actual outcome) and gaming-vulnerability test (could operators game it undetected).
5. Flag any high-gaming-vulnerability metrics for governance redesign; note metrics that are insensitive to outcome.

### 7b. Full Depth Execution (Complete framework run)

1. Inventory all metrics in use; classify by meta-category and core type; profile each across five dimensions (validity, reliability, responsiveness, gaming-vulnerability, goal-alignment).
2. For each metric, design and conduct validity test: does metric actually track intended outcome; what is correlation to outcome?
3. Assess gaming vulnerability: could operators optimise metric independent of goal; what gaming strategies are possible; are gaming early-warning indicators in place?
4. Test proxy reliability (if applicable): has context changed since proxy was selected; are confounding factors emerging; how much metric-outcome divergence is tolerable?
5. Analyse metric dynamics: identify metric-creep, desensitisation, or gaming-feedback escalation patterns; assess metric system brittleness.
6. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence Hiddens, design detection interface (how to surface gaming, divergence, invalidity) and remediation (metric redesign, incentive realignment, governance change).
7. Produce multi-metric dashboard (if single-metric system) or rebalance existing dashboard; design outcome verification; establish metric-validity review schedule.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Evidence Ledger | Record metric classifications, validity assessments, gaming-vulnerability profiles, outcome correlations | After metric analysis |
| Hypothesis/Test Backlog | Propose most-diagnostic tests for metric validity and gaming vulnerability; design outcome monitoring trials | For metrics with high validity uncertainty or gaming risk |
| Information Requests | Request outcome data to test metric validity; request gaming-detection monitoring; request measurement system audit | To support validity and gaming assessments |

**Gate Question (pre-closure check):** Have we inventoried metrics, assessed validity and gaming-vulnerability for each, run Tier 1 Hiddens scan for metric-goal divergence and gaming-blindness, designed outcome verification tests, and escalated high-gaming-vulnerability or invalid metrics to governance redesign?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs

- Goals/Outcomes (what are we actually trying to achieve; what is success?)
- Evidence (measurement validity and reliability evidence)
- Governance (accountability and governance frameworks shaping metrics)
- Incentives (incentive structures creating gaming vulnerabilities)
- Hiddens (what Hiddens affect metric validity or enable gaming?)

### 8b. Downstream Handoffs

- Framework of Governance (metric governance, metric-review scheduling, gaming prevention)
- Framework of Incentives (incentive-structure redesign to align with metrics)
- Framework of Learning & Adaptation (metric-validity learning loops and updating)
- Framework of Risk (metrics for tail-risk and low-probability event detection)

### 8c. Targeted Scans

| Targeted Scan | Role of this framework |
|---|---|
| Measurement Gaming & Proxy-Drift Scan (Family C, Scan 4) | Surface metric-goal divergence, gaming vulnerability, proxy validity; identify gaming-feedback escalation |
| Incentive-Metric Alignment Scan (Family B, Scan 4) | Identify misalignment between incentive structures and metric designs; assess gaming vulnerability |

---

*LLM Execution Extract v1.0 – Metrics Framework (2026-04-08) – End of Extract*
