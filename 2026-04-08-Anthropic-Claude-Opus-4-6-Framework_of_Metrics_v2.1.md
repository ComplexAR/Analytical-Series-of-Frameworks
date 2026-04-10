# Framework of Metrics
*Designing, Governing, and Auditing Measurement Systems to Sustain Visibility and Resist Distortion*

## Document Information
- Series: Analytical Series of Frameworks
- Version: v2.1
- Date: 2026-04-08
- Status: Stable
- Operating Guide Compatibility: Analytical Series Operating Guide v2.5
- Prompt Discipline Ruleset: Operating Guide "Prompt Discipline Rules (Canonical)" (PD-01 to PD-10; see OG v2.5, §D.3)
- Run Mode Terminology: Rapid Run Mode / Investigative Run Mode (see Operating Guide §D.10.1)
- Framework Execution Depth Terminology: Full Depth Framework Execution / Light Depth Framework Execution (see Operating Guide §D.10.1)
- Tiered Hiddens Scan Model: Tier 1 (six-category visibility audit) / Tier 2 (structured deepening) / Tier 3 (full-spectrum escalation) (see Operating Guide §D.6.10)
- Targeted Hiddens Discovery Scans: Thirteen mechanism-specific cross-framework scans (see Operating Guide §7.5)
- Group (Primary): G5 — Epistemics & error-control (Epistemics)
- Group (Secondary): G6 — Choice, action & control over time (Action & Control)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or metric-incentive coupling is suspected
- Owner / Maintainer: Series Maintainer
- Intended Use: Measurement system diagnosis and design; metric governance and lifecycle management; Goodhart and distortion detection; dashboard integrity audits; indicator selection and validation; intervention monitoring design; cross-framework measurement coherence; metric void analysis
- Primary Audience: Analysts, investigators, risk owners, programme leaders, auditors/assurers, governance designers, measurement owners, performance management teams, decision-makers relying on quantitative signals, LLMs executing the Analytical Series
- Dependencies / Key Inputs: Situation framing; system boundary and dependency map; evidence base; incentives and power map; governance and decision rights; time/scale characteristics; existing metric inventories, dashboards, KPI frameworks, and collection/reporting infrastructure
- Primary Outputs: Metric register (6×5 taxonomy); dimension profiles for critical metrics; metric pathology map with interaction chains; interface map (A/B/C); dynamic trajectory analysis; metric governance and strategy recommendations; monitoring-of-monitoring design; Hiddens shortlist with detection/remediation moves; Residual Unknowns and closure discipline
- Change Log (brief): Rewrite for v2.1: MRT v3.0 LLM Integration Bridge format (§1.6). Replaced full LLM Use section with compact Bridge structure (1.6.1 Extract pointer; 1.6.2 Near-neighbour disambiguation; 1.6.3 Routing triggers). Preserved document header (v2.0) sections through §1.5. All other sections unchanged from v2.0. Updated version to v2.1, date to 2026-04-08.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What is being measured here, why was it chosen, what does the measurement system hide or distort, and how should metrics be designed, governed, and evolved to support visibility rather than undermine it?** |
| Addresses | Goodhart decay; proxy drift; dashboard theatre; metric monoculture; measurement-incentive coupling; false precision; aggregation loss; indicator obsolescence; metric capture; the gap between what is measured and what matters; metric voids; measurement-generated Hiddens |
| Gap Filled | The Analytical Series treats metrics simultaneously as a tool (every application protocol prescribes monitoring indicators) and as a risk (Goodhart effects, distortion, mirage). No existing framework systematically examines the measurement system itself — how metrics are designed, selected, validated, governed, evolved, and retired, and how they generate Hiddens across the series. |
| Complements | Evidence (data quality and provenance); Hiddens (visibility failure taxonomy); Systems (feedback loops including measurement loops); Incentives (metric-reward coupling); Governance (metric authority and oversight); Uncertainties (false precision and quantification limits); Learning & Adaptation (metric evolution and retirement); Dimensions (what can be measured); Resources (data as resource); Decisions (metrics inform choices); Diagnosis (metrics reveal patterns); Knowledge (measurement as way of knowing) |
| Key Characteristics | Cross-cutting; reflexive (applies to its own measurement and governance); measurement-system-as-object; dual-role aware (metrics as both instruments and hiding mechanisms); lifecycle-oriented; governance-integrated; designed as constructive companion to the series' existing measurement warnings |
| Main Contributions | Six meta-categories; 30 core metric types; five cross-cutting dimensions; 12 dynamic patterns; three interface types (A/B/C); Hiddens source analysis + systematic Tier 1/2/3 Hiddens scans; seven-step application protocol; five core principles; comprehensive glossary; integration with all 36 frameworks |

---

# Introduction

## What is Metrics?

A metric is not a neutral window onto reality. It is an engineered artefact—designed by someone, for some purpose, using particular instruments, within a governance context, and subject to incentives that shape what is reported, how it is interpreted, and what actions follow. The measurement system (the full apparatus of what is measured, how, by whom, with what cadence, and with what consequences) is one of the most powerful mechanisms through which realities become visible or remain hidden. This framework provides a structured method to examine measurement systems as first-class analytic objects in their own right: what is measured, what is not, why the choices were made, what hidden effects they generate, and how to design systems that reveal rather than conceal.

## Why does Metrics matter for Hiddens work?

Measurement systems are prolific generators of Hiddens. Where metrics are coupled to rewards or accountability (the metric-incentive interface), actors optimise the metric rather than the underlying reality—a Goodhart effect that produces systematic distortion. Where single metrics dominate (metric monoculture), alternative signals are suppressed and blind spots are locked in. Where metrics are outdated (zombie metrics) or disconnected from reality (proxy drift), dashboards sustain illusions while operational reality degrades undetected. Where metrics are absent (metric voids), entire domains go unmeasured and structurally invisible. The measurement system is itself a major source of the Hiddens that the Analytical Series is designed to surface.

## What does this framework produce?

This framework operationalises measurement system analysis through six core elements: (1) a taxonomy of 30 metric types organized into six meta-categories addressing design, collection, aggregation, interpretation, governance, and pathology; (2) five cross-cutting dimensions that profile any metric and explain why different stakeholders assess the same metric differently; (3) 12 dynamic patterns describing how metrics evolve, decay, and cascade; (4) three interface types (measurement-reality, metric-decision, metric-incentive) that surface where systems interact and break down; (5) Hiddens source analysis and tiered Hiddens scans (Tier 1/2/3) that surface measurement-generated visibility failures; and (6) a seven-step application protocol that moves from metric inventory through pathology scanning, dimension profiling, interface mapping, Hiddens checking, and remediation design. The framework populates standard registers (Metric Register, Pathology Map, Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests) that integrate with the broader Analytical Series workflow. It is designed for both diagnostic use (auditing existing measurement systems for pathology) and constructive use (designing new measurement systems resistant to distortion).

## How to use this framework

Invoke this framework early when metric systems are suspected of generating visibility failures; during strategy or intervention design when monitoring needs to be specified; and whenever operational reality contradicts the metric narrative (a signal of distortion or gaming). The framework works in both Rapid Run Mode (metric inventory, top pathologies, key interfaces scanned in 60–180 minutes) and Investigative Run Mode (full dimensional analysis, comprehensive Hiddens scanning, governance redesign). Default execution is Light Depth: inventory metrics, classify types, scan for active pathologies, profile 2–3 critical metrics, identify obvious interfaces, run Tier 1 Hiddens scan. Escalate to Full Depth when consequence is high, metric-incentive coupling is suspected, measurement failure has contributed to operational failure, or Tier 1 symptoms point to specific hiding mechanisms. For LLM execution, see §1.6 for the complete integration specification, standard registers, and copy-ready run prompts.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Measurement is not a neutral act. Every metric embeds design choices—what to measure, how to measure it, when to measure, who measures, how to aggregate, what counts as success. These choices are made by humans, within governance structures, subject to incentives, and often persist long after their original rationale has evaporated. The resulting measurement system is one of the most consequential technologies in modern organisations—shaping perception, driving behaviour, determining which realities are visible and which remain hidden, and often producing unintended consequences that the original designers never anticipated.

Yet measurement systems are rarely treated as first-class analytic objects deserving systematic examination. The Analytical Series warns repeatedly about measurement pathologies: Goodhart effects (metrics becoming targets and losing validity), proxy drift (metrics decoupling from what they claim to measure), aggregation loss (averaging destroying diagnostic information), dashboard theatre (reporting rituals substituting for genuine oversight), metric capture (powerful actors controlling the measurement apparatus to control the narrative), and metric voids (critical realities going unmeasured). Every framework prescribes monitoring-of-monitoring indicators as a standard deliverable. Yet without systematic guidance on how to design metrics that resist gaming, how to validate that a proxy still tracks its target, how to govern metric lifecycles, and how to recognise when a measurement system has become part of the problem, the series' own outputs remain vulnerable to the pathologies it warns about.

This framework fills that gap. It treats the measurement system as a first-class analytic object with its own taxonomy (30 core types organised into six meta-categories), dimensions (validity, sensitivity, gameability, consequentiality, transparency), dynamics (12 patterns of evolution and decay), and Hiddens profile (which visibility failures does this system generate?). It provides both diagnostic protocols (audit existing metrics for pathology) and constructive protocols (design new metrics that resist distortion). It systematically maps the three critical interfaces where measurement systems interact with reality, decisions, and incentives, and where they fail. And it integrates tightly with the Analytical Series' Hiddens discipline: measurement is not merely a tool for discovering Hiddens, it is itself a major generator of Hiddens.

## 1.2 Assumptions & Preconditions

### Assumptions Register (recommended)
| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Metrics are observer-constructed artefacts, not objective givens; every metric embeds design choices that can be examined. | Structural | Metrics are treated as self-evident truths; measurement pathologies go undiagnosed and unfixed. | For each critical metric, ask: who chose this, when, what alternatives were considered, and what was the decision logic? | Default to treating every metric as a hypothesis about what matters; test validity regularly; audit decision lineage. |
| The relationship between a metric and the reality it claims to represent can degrade over time (proxy drift, Goodhart decay) without detection. | Structural | Metrics are assumed permanently valid; stale metrics produce false confidence and hidden risks. | Track metric-reality correlation over time; monitor for behavioural adaptation to measurement; run periodic ground-truth samples. | Institute mandatory metric review cadence; include retirement criteria at metric creation; separate measurement from high-stakes reward. |
| Measurement systems are embedded in incentive and power structures that shape what is reported, emphasised, and suppressed. | Domain | Naive trust in reported numbers; systematic distortion and self-serving bias go undetected. | Compare stated incentives to metric ownership; look for patterns where reporting favours the reporter; audit measurement independence. | Pair Metrics with Incentives and Power frameworks; separate measurement authority from those being measured; enable protected reporting channels. |
| Quantification is not always appropriate; some realities resist meaningful numerical representation without loss of essential information. | Normative | False precision; qualitative signals are dismissed because they lack numbers; important uncertainties are hidden beneath statistical smoothing. | For each metric, ask: does quantification add genuine information or merely the appearance of rigour? Can this reality only be understood numerically? | Use qualitative assessment where appropriate; flag where quantification is a design choice, not a necessity; use metric baskets instead of single metrics. |
| Independent validation of metrics is possible and necessary for high-stakes measurements; metric monopolies sustain mirages. | Domain | Single-source metrics create unfalsifiable claims; gaps in validation go undetected until failure. | Count independent sources and validation points; test whether metrics can be challenged, triangulated, or cross-checked. | If independence unavailable, disclose the limitation; move to robustness/precaution approaches; use complementary indicators. |
| Metric governance (authority to create, modify, retire metrics; cadence for validation and review) can be made explicit and held accountable. | Domain | Shadow metrics proliferate; no one owns metric quality; retired metrics persist as operational ghosts; changes are untracked. | Audit metric ownership; verify whether creation/modification/retirement processes exist and are documented; check review cadence adherence. | Establish minimum metric governance even if lightweight: owner, review cadence, retirement criteria, change control log. |
| The 30-type metric taxonomy provides adequate baseline coverage across domains and intervention contexts. | Structural | Coverage gaps cause recurring measurement failures to fall outside the scan; blind spots persist. | Track "none-of-the-above" frequency across audit work; review extension requests; compare against domain-specific taxonomies. | Extend with explicit mapping back to nearest canonical type; document deviations; escalate novel types to series maintainers. |
| Measurement-generated Hiddens can be systematically discovered using the Hiddens framework and tiered scanning (Tier 1/2/3). | Structural / method | Measurement pathologies are treated as inevitable rather than diagnosable and remediable; fixes remain superficial. | Run Tier 1 Hiddens scans on metric systems; compare to operational reality; track detection rate and false-positive rate. | If detection rates are low, escalate to Tier 3; add targeted scans; strengthen evidence base; include frontline perspectives. |

### Preconditions Checklist (recommended)
| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---:|---|---|---|---|
| Focal decision/situation brief exists (scope, stakes, horizon, success criteria). | Y | Decision brief; situation framing note | Decision owner | To be verified per case | Run a 30–60 minute scoping session; proceed with provisional tags. |
| Inventory of existing metrics, KPIs, dashboards, and reporting systems is accessible. | Y | Metric inventory; dashboard catalogue; KPI register; reporting calendar. | Metric owner / data team | To be verified per case | Build provisional inventory from available dashboards and reports; mark gaps and access limitations. |
| Incentive and governance structures around measurement are identifiable and can be mapped. | Y | Incentive map; governance charter; metric ownership register; decision-rights matrix. | Governance owner / HR | To be verified per case | Run a fast Incentives/Power scan focused on measurement; treat as evolving and incomplete. |
| Access to underlying data (not just reported numbers) is available or can be requested. | N | Data dictionaries; source system access; ETL documentation; data lineage map. | Data engineering / analytics | To be verified per case | Work with reported outputs; flag source-access gaps as candidate Hiddens; request access as evidence. |
| Stakeholders who use, produce, and are affected by metrics can be engaged for interview/validation. | Y | Stakeholder list; interview access; meeting calendar. | Programme lead | To be verified per case | Use proxy interviews and document review; note perspective gaps; plan follow-up engagement. |
| A shared register format exists for metric findings and governance decisions. | Y | Register template; tooling; review/approval workflow. | PMO / governance | To be verified per case | Use the minimum deliverable pack (Section 9) in a shared document; establish lightweight change control. |
| Time and resourcing are available for appropriate scan depth per Operating Guide routing. | Y | Resourcing plan; calendar holds; sponsor commitment. | Sponsor | To be verified per case | Timebox to Tier 1 + highest-risk pathologies; escalate if warranted; plan phased deepening. |
| Remediation levers are in-scope (metric redesign, governance changes, incentive restructuring, data access). | N | Intervention catalogue; authority map; change control process. | Operations / transformation lead | To be verified per case | If levers are out-of-scope, focus on disclosure, robustness, and governance handoff. |

## 1.3 Definitions, Scope, and Non-Goals

- **Metric (operational definition)**: A specified, repeatable measurement applied to an aspect of a system, process, agent, or outcome, producing a quantitative or qualitative signal intended to inform understanding, comparison, or action. Includes its definition, instrument, collection method, aggregation rules, reporting chain, governance context, and decision linkage.

- **Measurement System**: The full socio-technical apparatus through which metrics are designed, collected, aggregated, reported, interpreted, acted upon, governed, and retired. Includes instruments, data pipelines, dashboards, reporting structures, incentive couplings, governance arrangements, and feedback loops to operational systems.

- **In scope**:
  - Design, selection, validation, and governance of metrics as analytic objects
  - Metric pathologies (Goodhart decay, proxy drift, aggregation loss, false precision, dashboard theatre, metric capture, metric voids)
  - Relationship between metrics and Hiddens generation across the Analytical Series
  - Constructive guidance for designing metrics that resist distortion and support visibility
  - Metric lifecycle management (creation, validation, monitoring, evolution, retirement)
  - Metric-incentive coupling and its effects on behaviour and reporting
  - Measurement-induced risk and unintended consequences
  - Dashboard integrity and the distinction between reporting theatre and genuine oversight

- **Out of scope (by design)**:
  - Domain-specific statistical methods, instrument calibration, and technical tooling (these are inputs, not the analytic object)
  - Full evidence quality assessment (use Evidence framework)
  - Full uncertainty quantification methodology (use Uncertainties framework)
  - Full incentive system design (use Incentives framework)—though metric-incentive coupling is in scope
  - Full dashboard UI/UX design—though dashboard integrity as a visibility concern is in scope

- **Common confusions ("Metrics is not …")**:
  - "Metrics" is not "Evidence": Evidence asks whether data is reliable; Metrics asks why *this* data is being collected at all and what the collection system hides.
  - "Metrics" is not "Dimensions": Dimensions catalogues modes of existence and axes of variation; Metrics examines the socio-technical apparatus that measures along those axes.
  - "Metrics" is not "Resources": Resources treats data as one resource type among many; Metrics treats the measurement system as a first-class analytic object.
  - "Metrics" is not "Uncertainties": Uncertainties addresses the limits of knowledge; Metrics addresses how measurement systems create, sustain, or resolve those limits through design choices and governance.

## 1.4 Position in the Series (Upstream / Middle / Downstream)

- **Upstream (signals/understanding)**: Situations (what context determines measurement needs); Boundaries (what is in/out of measurement scope); Dimensions (what axes of variation exist to be measured); Evidence (what data is available and its quality); Systems (what feedback loops include measurement); Hiddens (what visibility failures exist); Knowledge (what counts as knowing)

- **Middle (this framework's role)**: Examine the measurement system itself—what is measured, how, by whom, with what governance, what pathologies, and what hidden-generating effects. Produce a metric register, pathology map, and constructive metric design and governance guidance. Bridge between evidence generation (upstream) and decisions/interventions (downstream).

- **Downstream (action/governance)**: Decisions (what metrics inform choices); Interventions (monitoring design for interventions); Governance (metric authority and oversight cadence); Risk (metric-induced risk); Learning & Adaptation (metric evolution and retirement); Incentives (metric-reward coupling redesign); Responsibility (who is accountable for metric integrity)

- **Group assignment (Primary)**: G5 — Epistemics & error-control (Epistemics)
- **Group assignment (Secondary)**: G6 — Choice, action & control over time (Action & Control)
- **Stage assignment**: Cross-cutting (see OG v2.5 §3.1)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.9.2 Mode Selection Gate)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
- **Framework Index**: this framework is one of 36 in the series (see OG v2.5 §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary (recommended)
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Descriptive | Systems; Relations; Processes; Resources; Time; Scale | Structure, flows, dependencies, resource substrates, and temporal/scale characteristics | Which parts of the system are measured and which are not? How do measurement feedback loops interact with operational feedback loops? What resource (data, attention, trust) does the measurement system consume? What timescales do metrics capture and what temporal patterns go invisible? |
| Epistemic | Evidence; Uncertainties; Hiddens; Diagnosis; Beliefs; Knowledge | Data quality, uncertainty structure, visibility failures, diagnostic synthesis, belief formation, and ways of knowing | How does the measurement system itself generate evidence gaps, false certainties, and visibility failures? Where does quantification create the illusion of knowledge? How do metrics shape and entrench beliefs? What knowledge is possible given the metrics available? |
| Normative | Values; Culture & Norms; Legitimacy; Narratives; Perspectives; Responsibility | Value priorities, cultural constraints, legitimacy bases, dominant stories, interpretive lenses, and accountability structures | What values are embedded in metric choices? How do metrics create or destroy legitimacy? Which narratives do dashboards support or suppress? Whose perspective is encoded in the measurement system? Who is responsible for metric integrity and what happens when measurement fails? |
| Action | Decisions; Interventions; Governance; Risk; Incentives; Learning & Adaptation | Choice frameworks, intervention design, oversight, risk treatment, reward structures, and learning cycles | How should metrics be designed to support good decisions without distorting behaviour? What metric governance prevents pathology? How should metric-incentive coupling be managed? When should metrics be retired and what replaces them? How does measurement capability evolve with organisational learning? |

---

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Metrics_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Metrics when… | Use neighbour instead when… |
|---|---|---|
| Evidence | Analysing what data exists, whether it is reliable, provenance, quality gaps. | Analysing the purpose and design of the data collection itself, who chose what to measure, incentives embedded in measurement choice. |
| Systems | Analysing feedback loops, causal chains, dynamical behaviour, non-linear effects. | Analysing what feedback loops are measured and which are invisible; which system states are quantified and which go unobserved. |
| Incentives | Analysing reward structures, agent motivation, behaviour change mechanisms. | Analysing how metrics create incentive distortion; metric-reward coupling; gaming and Goodhart decay; measurement as accountability mechanism. |
| Governance | Analysing authority, decision rights, oversight structures, accountability. | Analysing who controls measurement apparatus; metric ownership and review cadence; governance of the measurement system itself. |
| Hiddens | Analysing visibility failures, what is unknown or obscured, detection mechanisms. | Analysing measurement systems as generators of Hiddens; how metrics sustain illusions or conceal realities; what measurement design choice hides. |
| Dimensions | Cataloguing modes of existence, axes of variation, what can exist/differ. | Analysing why *this* axis is measured, why alternatives are excluded, what measurement choice foregrounds/backgrounds. |

### 1.6.3 Routing triggers
- Metric inventory is missing or stale; no clear ownership of active KPIs or dashboards
- Reported metrics contradict operational reality; numbers look fine but practice deteriorates
- Gaming or metric optimisation suspected; actors distorting behaviour to achieve metric targets
- Goodhart decay detected; metric-reality decoupling over time; proxy no longer tracks target
- Incentive coupling likely; measurement tied to reward, promotion, performance rating, or accountability
- Dashboard theatre concern; reporting rituals substitute for genuine oversight; no action follows data
- Metric voids exist; critical realities go unmeasured; gaps in monitoring coverage
- Aggregation masking; averaging hides hotspots, tails, outliers, or distributional risk
- Measurement latency or reporting delay suspected; dashboards lag operational reality
- Metric monoculture; single metric dominates narrative; alternative signals suppressed
- Governance gaps; no process for metric creation, validation, review, or retirement
- Post-failure review where measurement system contributed to delayed detection

---

# 2. Meta-Categories of Metrics

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Design & Selection | What is being measured, why was it chosen, and what does the choice of metric include or exclude? | Metric definition, proxy selection, operationalisation of abstract concepts, coverage and omission. | KPI definitions; metric catalogues; proxy specifications; operationalisation protocols; measurement need statements. |
| II | Collection & Instrumentation | How is the measurement actually performed, with what instruments, methods, and data pipelines? | Instrument fidelity, sampling methods, data pipelines, collection cadence, calibration, measurement error, observer effect. | Sensors and instruments; survey instruments; data pipelines; ETL processes; sampling protocols; calibration records; collection logs. |
| III | Aggregation & Representation | How are raw measurements combined, summarised, and presented for interpretation? | Aggregation rules, index construction, dashboard design, visualisation choices, information loss, temporal smoothing. | Dashboards; composite indices; scorecards; league tables; summary statistics; visual encodings; reports. |
| IV | Interpretation & Use | How are metric outputs interpreted, integrated into decisions, and acted upon? | Threshold-setting, target-setting, comparison frames, narrative coupling, decision integration, behaviour change. | Performance targets; benchmarks; traffic-light systems; balanced scorecards; metric-linked decision rules; action triggers. |
| V | Governance & Accountability | Who owns, controls, validates, and can modify or retire metrics? | Metric authority, ownership, review cadence, audit rights, modification governance, retirement protocols, compliance. | Metric charters; ownership registers; review boards; audit protocols; retirement criteria; change control processes; compliance calendars. |
| VI | Pathology & Failure | How do metrics fail, degrade, distort, or become weaponised over time? | Goodhart effects, proxy drift, gaming, capture, false precision, metric obsolescence, measurement-induced harm, cascade effects. | Metric autopsy reports; gaming evidence; proxy validation failures; measurement-induced perverse outcomes; metric retirement triggers; failure logs. |

## 2.2 Meta-Category Descriptions (recommended)

### I. Design & Selection
Metrics in this category address the foundational choices that determine what is measured and what is not. Every metric begins as a design decision—someone selects an aspect of reality to quantify, chooses an operationalisation, and implicitly declares everything else "not measured here." Design choices embed assumptions about what matters, what can be captured, and what counts as success or failure. The most consequential Hiddens often originate at this stage: the thing that was never measured, the proxy chosen for convenience rather than validity, the definition that quietly excludes edge cases, the threshold that separates acceptable from unacceptable without clear rationale.

- **Diagnostic cues**: For each critical metric, ask: who chose this, when, why, and what alternatives were explicitly considered and rejected? If these questions cannot be answered confidently, design assumptions are hidden.
- **Typical failure mode**: Metric measures what is convenient rather than what matters; operationalisation drifts from the original concept; coverage gaps leave critical realities unmeasured; voids accumulate.

### II. Collection & Instrumentation
Metrics in this category address the practical apparatus of measurement—instruments, sensors, surveys, data pipelines, sampling methods, and collection cadences. Even a well-designed metric can produce misleading signals if the collection system introduces bias, latency, observer effects, or systematic error. Instrumentation pathologies include: calibration drift (instruments become less accurate over time), sampling bias (who/what is measured vs. not measured), pipeline corruption (data transforms that distort values), observer effect (measurement changes the measured), latency (delays between phenomenon and report), and missing granularity (averaging across important variation).

- **Diagnostic cues**: Trace the path from phenomenon to reported figure. Look for gaps, transformations, assumptions, and deviations. Ask: how accurate is the collection process, how latent is the reporting, what could cause systematic bias?
- **Typical failure mode**: Collection method introduces hidden biases; pipeline corrupts or smooths signals; latency hides rapid changes; sampling misses important subgroups.

### III. Aggregation & Representation
Metrics in this category address how raw measurements are combined, summarised, and presented for human interpretation and decision-making. Even accurate collection can produce misleading conclusions if aggregation destroys diagnostic information. Aggregation pathologies include: averaging (which hides distributions, tails, and outliers), indexing (which weighs components invisibly), dashboard design (which can highlight some signals and bury others), temporal smoothing (which hides trends and reversals), and visualisation choices (which shape what "looks normal").

- **Diagnostic cues**: For each aggregated metric, ask: what information is destroyed by this aggregation? What would we see if we disaggregated? Are outliers and tails visible? Does the dashboard design privilege certain signals?
- **Typical failure mode**: Aggregation hides hotspots, tail risks, and heterogeneity; dashboards stabilise preferred narratives despite variation; temporal smoothing hides transitions.

### IV. Interpretation & Use
Metrics in this category address what happens after the number is produced—how the metric is interpreted, integrated into decisions, and coupled to actions or consequences. Even an accurate metric can distort behaviour if the interpretation process is naive. Interpretation pathologies include: target-setting without validation (targets decoupling from reality), threshold-setting without testing (thresholds placed arbitrarily), narrative closure (single metric becomes "the story" rather than one signal among many), metric-incentive coupling (metrics linked to rewards, penalties, or career consequences), and decision-rule coupling (metric automatically triggers actions).

- **Diagnostic cues**: For each critical metric, ask: what actions does this metric trigger? Are those actions what we intended? Is the metric linked to rewards or accountability? Do we test whether the metric-decision link still works?
- **Typical failure mode**: Metric-incentive coupling causes optimisation of the metric rather than the underlying reality (Goodhart effect); thresholds are arbitrary and never revisited; narrative closure around a single metric suppresses alternative signals.

### V. Governance & Accountability
Metrics in this category address the governance arrangements around measurement—who owns metrics, who can create/modify/retire them, how often they are reviewed, and what authority and accountability structures keep measurement integrity high. Governance pathologies include: unowned metrics (no one is responsible), shadow metrics (informal metrics used operationally but not tracked), zombie metrics (outdated metrics that persist despite being useless), metric capture (powerful actors control the measurement apparatus to control the narrative), and metric proliferation (too many metrics causing signal degradation).

- **Diagnostic cues**: For each metric, identify the owner, the last review date, the creation rationale, and whether retirement criteria exist. If these are unclear or missing, governance is weak.
- **Typical failure mode**: Metrics persist past relevance; no one is responsible for validity; measurement systems drift without oversight; powerful actors control what is measured and how it is reported.

### VI. Pathology & Failure
Metrics in this category address how metrics degrade, distort, fail, and sometimes become weaponised. Unlike the other five categories (which describe measurement systems that are working as intended), this category captures systematic failures and decay. Pathology types include: Goodhart decay (metrics losing validity due to high-stakes coupling), proxy drift (proxies decoupling from targets), gaming (actors manipulating the metric without improving the underlying reality), capture (measurement system weaponised for power/narrative control), false precision (numbers implying certainty that doesn't exist), metric voids (systematic absence of measurement), and zombie metrics (outdated metrics persisting past usefulness).

- **Diagnostic cues**: Compare metric signals to independent operational reality; look for evidence of gaming; check whether proxies still track their targets; ask whether metrics are outdated or weaponised.
- **Typical failure mode**: Metrics produce false confidence; dashboard theatre substitutes for genuine oversight; measurement system becomes a liability rather than an asset.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- **Canonical baseline**: 6 meta-categories × 5 types = 30 core types.
- **This framework**: 30 types. No deviation from baseline.
- **Mapping back to baseline**: N/A (full conformance to canonical 6×5 structure).

## 3.1 Types (Category I: Design & Selection)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 1 | Direct Measurement | Measures the phenomenon itself, without proxying; directly observed or instrumented. | Ask: "Are we measuring the thing itself or a substitute?" If direct, this is simplest but requires the phenomenon to be observable. | Assumes observability; misses tacit or delayed phenomena; requires instrumentation access. |
| 2 | Proxy Metric | Measures a correlated, observable variable as stand-in for a harder-to-measure target; validity depends on correlation persistence. | Ask: "What is the proxy assumption here? How is it validated? Does the proxy still track the target?" | Proxy drift (correlation decays); target changes but proxy does not; proxy optimisation without target improvement (Goodhart). |
| 3 | Composite / Index Metric | Combines multiple sub-metrics into a single score using weights, formulas, or models; loses granularity for integration. | Ask: "What are the components? How are they weighted? Does the index weight match the importance to decisions?" | Aggregation loss (destroys diagnostic information); opaque weighting (hidden assumptions); index becomes target rather than summary. |
| 4 | Threshold / Binary Metric | Converts continuous variable into categorical signal (e.g., "compliant" / "non-compliant"); discretises for decision-making. | Ask: "Where is the threshold placed? Was it tested? Does it still divide the world as intended?" | Threshold placed arbitrarily (never tested); populations near threshold are unstable; discrete jumps hide smooth transitions. |
| 5 | Absence / Null Metric | Defined by what is not measured; the metric void—an explicit recognition that measurement is absent in this domain. | Ask: "What important things are we not measuring? Why? What accumulates when left unmeasured?" | Structural invisibility (unmeasured domain accumulates risk); known voids may be deliberate hiding; no governance of what should fill the void. |

## 3.2 Types (Category II: Collection & Instrumentation)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 6 | Automated / Sensor Metric | Collected by automated instruments (sensors, probes, APIs) without human intermediation; provides fidelity but susceptible to calibration drift. | Ask: "When was the instrument last calibrated? What is the measurement error? What observer effects are present?" | Calibration drift (instrument becomes less accurate); sensor failures go undetected; observer effect (measurement changes measured); technical obsolescence. |
| 7 | Self-Report / Survey Metric | Based on subjective reports from measured entities (people, organisations); cheaper but subject to reporting bias, social desirability, and intentional distortion. | Ask: "Are respondents incentivised to distort? Is the survey validated? How do responses compare to independent observation?" | Reporting bias (respondents lie to avoid consequences or please); social desirability (people report what looks good); systematic distortion by measured group. |
| 8 | Observational / Audit Metric | Collected by independent observation or inspection (third party, audit, direct observation); adds cost but improves credibility. | Ask: "Is the observer truly independent? Are they trained? What is inter-rater reliability? Does observation change behaviour?" | Observer bias (what the observer pays attention to shapes the metric); observer effect (observation changes behaviour); cost and latency of independent audits. |
| 9 | Derived / Calculated Metric | Computed from other metrics through formulas or models; inherits quality from inputs but adds modelling assumptions. | Ask: "What is the derivation formula? What data inputs drive it? What assumptions underpin the model? Has the model been validated?" | Model assumptions may be wrong or outdated; formula bugs or changes go undetected; metric becomes optimised without improving underlying drivers. |
| 10 | Sampled / Estimated Metric | Based on sampling rather than exhaustive measurement; reduces cost but introduces sampling error and bias. | Ask: "What is the sample size? Is it representative? What is the sampling error? Has sampling changed over time?" | Sampling bias (sample not representative of population); sampling error (small samples have large confidence intervals); scope creep (sample frame changes). |

## 3.3 Types (Category III: Aggregation & Representation)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 11 | Average / Central Tendency Metric | Summarises distribution by its centre (mean, median, mode); simple and intuitive but destroys information about spread and tails. | Ask: "What is the distribution shape? Are there outliers or bimodal patterns? Would disaggregation reveal important subgroup differences?" | Averaging destroys tail visibility (hides outliers and extreme risks); bimodal distributions become invisible; masks heterogeneity. |
| 12 | Rate / Ratio Metric | Normalises a quantity by a reference value (e.g., defect rate, incidents per million hours); enables comparison across units. | Ask: "What is the denominator? Is it stable? Does the denominator choice affect the story (e.g., incidents per transaction vs. per employee)?" | Denominator changes (numerator stays same but ratio changes); ratio can be gamed by changing denominator; loses absolute magnitude. |
| 13 | Ranking / League Table Metric | Converts absolute values to ordinal positions; supports competition but loses information about magnitude and gaps. | Ask: "Is the ranking meaningful? Are gaps between positions significant? Does ranking incentivise zero-sum thinking?" | Rankings suppress ties and near-ties; small changes in score produce large ranking swings; ranking can be gamed if not robustly tied to underlying reality. |
| 14 | Trend / Time-Series Metric | Tracks a variable over time; reveals direction and momentum. | Ask: "What is the time interval? Is the series smoothed? Are there seasonal or cyclical patterns? Where does the trend begin?" | Smoothing hides transitions; choice of starting point affects trend narrative; seasonal patterns create false impressions; trend reversal delayed by latency. |
| 15 | Dashboard / Scorecard Metric | Curated collection of metrics for integrated visual summary; supports multi-lens viewing but can create narrative closure through design choice. | Ask: "What metrics are included? What is excluded? How is visual space allocated? Does the design privilege certain signals?" | Dashboard theatre (visually compelling but disconnected from operational reality); hidden metrics (important metrics excluded from view); colour/layout influences interpretation. |

## 3.4 Types (Category IV: Interpretation & Use)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 16 | Target / Goal Metric | Coupled to a specific numerical target; drives behaviour but vulnerable to Goodhart effects if target is decoupled from underlying reality. | Ask: "How was the target set? Is it validated against reality? What happens at the target threshold? Is the target gamed?" | Goodhart decay (metric optimised without target improvement); cliff effects (incentives change at thresholds); targets persist past relevance. |
| 17 | Benchmark / Comparison Metric | Used primarily for comparison against peers, standards, or historical baselines; contextualises absolute values. | Ask: "Are the comparators appropriate and similar? Does comparison hide important contextual differences? Do organisations game comparisons?" | Benchmark gaming (organisations improve metric without improving underlying reality); comparators diverge over time; context differences hidden. |
| 18 | Leading Indicator | Intended to provide early warning of future states before they fully materialise; valuable but epistemically fragile—lead time and correlation often assumed, not tested. | Ask: "What is the lead time? Is the correlation validated? What changed in the system that might break the correlation?" | Correlation breaks; lead time assumption invalid (leading indicator becomes lagging); early warnings go unheeded; false positives erode credibility. |
| 19 | Lagging Indicator | Captures outcomes after they have occurred; definitive but late—by the time the signal appears, the problem has already manifested. | Ask: "How late is the lag? Are there interventions possible at lag time? Does latency matter for your decision?" | Late detection (by the time signal shows, problem is entrenched); may be useful for retrospective learning but not prospective action. |
| 20 | Diagnostic / Root-Cause Metric | Designed to explain why something is happening; intended to surface causal mechanisms rather than just outcomes. | Ask: "What causal mechanism does this metric reveal? Has the mechanism been validated? Can the metric be gamed by changing the mechanism?" | Causal mechanism assumed, not tested; metric can be improved without improving mechanism; breaks when system changes. |

## 3.5 Types (Category V: Governance & Accountability)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 21 | Compliance / Regulatory Metric | Mandated by regulation or standards; externally required but may not align with organisational priorities or actual risk. | Ask: "Is this metric required by regulation? Does compliance with the metric ensure compliance with the underlying intent? Could compliance be gamed?" | Compliance theatre (metric is met but intent is not); regulatory risk persists despite metric compliance; gaming compliance without managing underlying risk. |
| 22 | Accountability / Attribution Metric | Used to assign credit, blame, or responsibility; high-stakes coupling creates strong Goodhart effects and gaming incentives. | Ask: "What behaviour does this metric incentivise? Is the metric gamed? Are there unintended consequences of the accountability coupling?" | Goodhart decay (optimisation of metric without improvement in what it measures); scapegoating (accountability assigned based on metric despite other factors); perverse outcomes. |
| 23 | Audit / Assurance Metric | Verified by independent party for assurance; adds cost and latency but improves credibility and reduces gaming. | Ask: "Is the auditor truly independent? What is the audit cadence? Are audit findings acted upon? Does auditing have power to enforce change?" | Audit independence compromised (auditor aligned with auditee); audit findings ignored; audit theatre (audits performed but findings suppressed); latency of audit reduces value. |
| 24 | Lifecycle / Maturity Metric | Tracks lifecycle stage or maturity level; intended to guide development and investment decisions. | Ask: "What defines maturity progression? Is progression tied to realistic effort and resources? Does maturity metrics drive premature escalation?" | Maturity progression forced (stages rushed through); maturity metrics becomes target rather than diagnostic; premature transition to higher maturity. |
| 25 | Shadow / Informal Metric | Used operationally but not formally recognised or governed; provides real-time signal but lacks governance and may sustain hidden realities. | Ask: "What informal metrics are actually driving decisions? Are they documented? Do they contradict official metrics? Why do they exist?" | Shadow metrics sustain alternative realities; lack of governance means no validation or retirement; shadow/official metric divergence signals reality-metric decoupling. |

## 3.6 Types (Category VI: Pathology & Failure)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 26 | Goodhart Metric | Has become an optimisation target and decoupled from the reality it claims to represent; metric-incentive coupling causes systematic distortion. | Ask: "Is this metric linked to rewards or accountability? Do people game it? Does metric improvement match underlying reality improvement?" | Systematic distortion (metric improves, reality doesn't); gaming (metric achieved without underlying progress); Goodhart decay accelerates under pressure. |
| 27 | Zombie Metric | Persists despite being useless; outdated, irrelevant, or never validated; wastes resources and creates noise. | Ask: "When was this metric last reviewed? Is it still tied to any decision? Why does it persist? Who owns it?" | Metrics persist past relevance; unmaintained metrics accumulate; effort spent on zombie metrics detracts from useful measurement. |
| 28 | Weaponised Metric | Deliberately manipulated to serve particular interests; measurement system becomes a tool of power rather than truth. | Ask: "Who benefits from this metric? Has the metric been deliberately manipulated? Does the metric serve a political agenda rather than decision-making?" | Deliberate distortion; measurement system becomes tool of power; trust in measurement system collapses; hidden realities entrench. |
| 29 | Mirage Metric | Produces a stable, reassuring signal disconnected from operational reality; sustained by reporting conventions, smoothing, and dashboard design. | Ask: "Does this metric contradict other signals of operational reality? Do frontline reports contradict the metric? Is the metric stable while reality changes?" | Stable false signal (dashboard shows all is well while operations deteriorate); detection delayed by signal stability; belief in mirage persists despite contradictory evidence. |
| 30 | Metric Void | Systematic absence of measurement in a domain that matters; structural invisibility created by non-measurement. | Ask: "What important things are not measured? Why? What would happen if we tried to measure them? What accumulates in the void?" | Structural invisibility (unmeasured domain accumulates risk); deliberate non-measurement may conceal problems; void-filling may be resisted by beneficiaries of invisibility. |

## 3.7 Extending the Taxonomy (mandatory)
| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | The 30-type taxonomy (6 meta-categories × 5 types) is the canonical baseline. Extensions should map back to this baseline to preserve series interoperability. |
| Domain-specific refinement | Domain-specific frameworks may add subtypes or domain-specific variants (e.g., healthcare metrics, financial metrics, environmental metrics). Extensions should be labelled as domain variants and mapped back to the canonical types. |
| Preserving mappability | Any extension must preserve the ability to map back to the canonical 30 types. If a domain metric does not map cleanly, trigger a series review and consider whether the extension is a genuine innovation or a relabelling of existing types. |
| Structural invariants | Do not alter the six meta-categories without a major version change and explicit justification in the "Document Information" section. The meta-categories represent fundamental distinctions about measurement systems and should be stable. |
| Periodic reassessment | Monitor for extension requests. Every major series version, reassess whether the 30-type taxonomy needs structural changes. Track "none-of-the-above" frequency to detect coverage gaps. |
| Versioning & governance | Extensions are tracked as minor versions (v2.1, v2.2) or domain variants. Major changes to the structure (changing meta-categories or number of types) trigger major version changes (v3.0) and require explicit approval from the series maintainer. |

---

# 4. Cross-Cutting Dimensions of Any Metric

## 4.1 Dimensions Table (mandatory)
| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| 1. Validity | Does the metric measure what it claims to measure? Is the metric-reality link sound and stable? | Decoupled (metric no longer tracks target) → Weakly validated (assumed but not tested) → Validated (tested recently) → Continuously validated (monitored). | For each metric, ask: "When was this last validated against ground truth? What evidence exists? Has proxy drift occurred? Does metric track intended target?" | Validity determines whether the metric is trustworthy as a signal; decoupling is a primary Goodhart risk. Escalate to Full Depth if validity is weak. |
| 2. Sensitivity | How responsive is the metric to real changes in the underlying phenomenon? Does the metric detect important signals or does it remain stable despite changes? | Insensitive (metric stable despite change) → Lag-responsive (metric eventually responds) → Real-time responsive (metric responds quickly). | Ask: "When real change occurred, did the metric change at comparable speed? Are there lags? Does the metric react to noise?" | Sensitivity trades off against noise; too sensitive and metric is volatile; too insensitive and metric is late. Match sensitivity to decision tempo. |
| 3. Gameability | How easy is it to improve the metric without improving the underlying reality? Can actors manipulate the metric without addressing the real problem? | Highly gameable (easily improved without reality change) → Moderately gameable (some scope for gaming) → Resistant to gaming (gaming requires solving the underlying problem). | Ask: "What is the easiest way to improve this metric without improving what it measures? How common is that gaming? Could it be detected?" | High gameability increases Goodhart risk, especially when coupled to incentives. Use complementary metrics or separate measurement from reward. |
| 4. Consequentiality | How much does this metric matter to decisions, resource allocation, and outcomes? Is it decision-critical or decorative? | Decorative (metric collected but not used) → Decision-informing (metric considered in decisions) → Decision-critical (metric drives decisions) → Outcome-determining (metric coupled to rewards/penalties). | Ask: "What decisions does this metric drive? Are those the decisions you want driven? Is the metric linked to consequences for the measured entity?" | High consequentiality amplifies Goodhart risk; high-stakes metrics need independent validation and complementary signals. Low-consequentiality metrics can be decorative wastes of effort. |
| 5. Transparency | How clear is the metric to users and stakeholders? Can the measured entity understand the metric, know how it is produced, and understand why changes occur? | Opaque (users don't understand how metric is produced) → Translucent (method partially clear) → Transparent (method is clear, formula is available) → Participatory (measured entity is involved in metric design). | Ask: "Can stakeholders understand how this metric is produced? What data goes into it? Can they predict whether their actions will improve it?" | Transparency enables gaming (understood metrics are more easily manipulated) but also enables contestation and improvement. Opacity protects metric from gaming but reduces legitimacy. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | Goodhart Decay | Metric improves steadily under reward coupling, but operational reality stagnates or degrades. | High-stakes coupling causes actors to optimise the metric instead of the underlying phenomenon; metric and reality diverge. | Systematic distortion undermines decision-making; policy/intervention based on improving metric fails. | Separate measurement from reward; use complementary metrics; validate metric regularly; retire metrics when gaming evident. |
| 2 | Proxy Drift | Proxy and target were once correlated, but correlation weakens over time due to environmental change or regime shift. | System changes (new technology, new behaviour, new constraints) break the assumption underlying the proxy. | Metric stops tracking intended target; false confidence persists until operational failure reveals the decoupling. | Validate proxy-target correlation periodically; build multiple proxies; monitor for proxy-validity signals; retire proxies when drift confirmed. |
| 3 | Aggregation Creep | Metrics grow coarser over time as organisations aggregate sub-metrics into indices; diagnostic power decreases. | Organisations add metrics, reducing space for new ones; response is to aggregate multiple metrics into summary index; coarsening accelerates. | Aggregation destroys detail needed for diagnosis; decision-makers lose visibility into drivers; false consensus around single summary. | Maintain granular metrics alongside aggregates; disaggregate periodically to check what's hidden; cap total metric count. |
| 4 | Metric Proliferation | Total metric count grows without retirement; signal-to-noise ratio decreases; measurement fatigue increases. | New problems demand new metrics; old metrics never retired; each department adds their own metrics; no governance of metric lifecycle. | Effort diluted across too many metrics; important signals lost in noise; measurement burden becomes unsustainable. | Institute metric budget (cap on total metric count); mandatory retirement criteria for every new metric; regular metric pruning. |
| 5 | Metric Capture | Powerful actor gains control of the measurement apparatus and uses it to shape narrative and protect position. | Entity being measured controls measurement system (or influences it); measurement system reflects what is convenient rather than what is true. | Measurement system becomes tool of power rather than truth; alternative realities suppressed; institutionalised deception. | Independent measurement; separated measurement authority from measured entity; transparency in measurement methods; dissent channels. |
| 6 | Dashboard Theatre | Reporting system becomes ritualised; dashboards produce visually compelling narratives that diverge from operational reality. | Reporting effort grows; dashboards become end product rather than means to action; stability of dashboard narrative matters more than accuracy. | False confidence in system state; leadership unaware of degradation; decisions made on narrative rather than reality. | Independent operational audits; frontline reality checks against dashboard; disaggregation of aggregate metrics; escalation routes for contradictions. |
| 7 | Zombie Metrics | Metric persists despite being outdated, irrelevant, or invalidated; continues to consume resources and create noise. | Original purpose no longer relevant; metric never formally retired; inertia keeps collection going; no owner accountable for retirement. | Effort wasted on collecting and maintaining metrics that don't matter; noise increases; measurement integrity questioned. | Mandatory metric review cadence; explicit retirement criteria for every metric; regular "zombie hunts" to identify and retire obsolete metrics. |
| 8 | Reporting Latency | Delay between phenomenon and metric report increases over time; detection of problems delayed; response window narrows. | Systems grow more complex; more steps in data pipeline; more aggregation; batch processing rather than real-time. | Problems accumulate undetected; interventions arrive too late; temporal Hiddens (Hidden-15 Latency) entrench. | Real-time monitoring where possible; reduce pipeline steps; create fast-path reporting for high-stakes signals; complement slow metrics with leading indicators. |
| 9 | Metric Ossification | Metric definitions become rigid; unable to adapt to changing context or new understanding; metric and reality diverge. | Metric embedded in systems, policy, contracts; changing it requires approval from many parties; resistance to change grows. | Metric becomes anachronistic; reality changes but metric definition doesn't; metric retroactively fails without adaptation. | Design metrics with evolution in mind; include sunset/review clauses at creation; lightweight governance enabling rapid iteration. |
| 10 | Threshold Drift | Thresholds that define acceptable/unacceptable gradually shift without explicit decision or validation. | Pressure to show improvement causes thresholds to be quietly adjusted upward (or downward); drift is not formally acknowledged. | Performance improves on paper but underlying reality hasn't changed; metric loses discriminating power. | Explicit governance of threshold changes; public changelog of threshold modifications; regular threshold re-validation. |
| 11 | Leading Indicator Decay | Leading indicator was once predictive of future state; predictive power decreases as system changes. | System dynamics change (new technology, new behaviour, new constraints) breaking the lead relationship. | Early warning system fails; problems once detected early now arrive without warning; response tempo can't adapt. | Validate lead relationships periodically; monitor correlation between leading indicator and actual outcomes; retire predictors when validity decays. |
| 12 | Metric Monoculture | Single metric or metric type dominates; alternative signals suppressed; blind spots locked in. | Simplicity drives adoption; dominant metric becomes "the story" that organisation tells itself; complementary metrics marginalised. | Organisation becomes blind to risks that the dominant metric doesn't capture; cascades and surprises follow; false confidence. | Use metric baskets rather than single metrics; ensure complementary signals (e.g., leading and lagging, quantitative and qualitative); explicit scanning for what the dominant metric hides. |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | Measurement-Reality Interface | Where the metric connects to the reality it claims to measure. This is where proxy drift, validity loss, and decoupling occur. | Does the metric still track the phenomenon? Has the phenomenon changed in ways the metric doesn't capture? Can the metric be gamed without changing reality? | Proxy (metric stands in for harder-to-measure target); proxy drift (correlation weakens); validity loss (metric stops tracking); gaming without reality improvement (Goodhart). |
| B | Metric-Decision Interface | Where the metric informs a decision or shapes behaviour. This is where interpretation, threshold-setting, narrative closure, and decision-rule coupling occur. | How is the metric interpreted? What decision does it drive? Is that decision what we want driven? What would happen if the metric signalled differently? | Target-setting (metric linked to goal); decision-rule coupling (metric automatically triggers action); interpretation bias (metric read through preferred narrative). |
| C | Metric-Incentive Interface | Where the metric is coupled to consequences (rewards, penalties, accountability, career impact). This is where Goodhart effects are strongest. | Is this metric linked to consequences? For whom? What behaviour change does the coupling incentivise? Is the gaming incentive high? | Goodhart coupling (metric becomes target when incentivised); gaming (metric improved without reality improvement); distortion (reporting bias when measured entity is incentivised). |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links (recommended)
- **Inputs expected**: Situation framing (what context determines measurement needs); System boundaries and dependencies (what parts of the system should be measured); Evidence base (what data is available and how reliable); Incentives and power structure (what incentives drive distortion); Decision rights and governance (who has authority over measurement); Temporal characteristics (what time horizons matter).

- **Outputs provided**: Metric register and classification; Pathology map and remediation moves; Dimension profiles for critical metrics; Metric governance and strategy recommendations; Hiddens shortlist tied to measurement system; Validated monitoring design for interventions; Measurement-induced risk assessment.

## 7.2 Crosswalk Table (optional but recommended)
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| Evidence | Data quality, provenance, reliability assessment | Assessment of measurement-induced evidence gaps, false precision risks, evidence corruption via measurement | Metric audit: ground-truth validation of whether metrics track evidence quality correctly. |
| Hiddens | Visibility failure taxonomy and scan protocols | Measurement-specific Hiddens sources, metric-generated Hiddens, measurement pathology Hiddens | Use Metrics to identify how measurement system generates Hiddens; use Hiddens framework to surface measurement pathologies. |
| Incentives | Power structure, reward structure, incentive alignment | Metric-incentive coupling analysis, Goodhart risk assessment, redesign recommendations | Design metrics resistant to Goodhart effects; audit whether metric incentives align with organisational goals. |
| Systems | System structure, dependencies, feedback loops | Measurement feedback loops, cascade risks via metrics, metric-system-behaviour coupling | Audit whether measurement system accurately reflects system behaviour; identify hidden feedback loops in measurement systems. |
| Governance | Authority structure, decision rights, oversight cadence | Metric governance design, metric authority assignment, review cadence recommendations | Design governance that prevents metric capture and maintains measurement integrity; separate measurement from those measured. |
| Learning & Adaptation | Learning mechanisms, adaptation patterns, feedback processes | Metric evolution protocols, learning loops built into metric governance, metric retirement and replacement | Design metrics that enable learning and evolution; avoid metric ossification; treat metrics as hypotheses to be tested. |
| Uncertainties | Uncertainty quantification, limits of knowledge | Where quantification is inappropriate, false precision risks, limits to measurement | Combine quantitative metrics with uncertainty estimates; avoid false precision; use qualitative assessment where measurement adds no value. |
| Diagnosis | Diagnostic synthesis, root-cause analysis, causal models | Diagnostic metrics that surface causal mechanisms, hidden-cause detection via metrics | Use metrics to diagnose root causes; avoid metrics that hide causal mechanisms; measure drivers, not just outcomes. |
| Knowledge | Ways of knowing, epistemology, knowledge claims | Measurement as way of knowing, measurement limits, alternatives to quantification | Recognise metrics as one way of knowing; complement measurement with other ways of knowing. |
| Decisions | Decision frameworks, decision criteria | How metrics inform decisions, decision-metric alignment, metric design for decision support | Design metrics that support the decisions they inform; audit whether metrics align with decision structure. |
| Dimensions | Axes of variation, modes of existence | What dimensions can be measured, dimensionality of what is measured, measurement granularity | Ensure measurement covers dimensions that matter; avoid over-aggregation that destroys dimensional visibility. |

## 7.3 Integration Questions by Framework (recommended)

| Framework (from OG v2.5 §3.2 canonical list) | Group | Stage | Integration questions (what this framework should ask / check) | Outputs / artefacts to pull in | Notes |
|---|---|---|---|---|---|
| Situations Context Classification | G1 | Upstream | What situation type is this, and what measurement needs does it imply? Does the measurement system reflect the situation type or contradict it? | Situation type hypothesis, dimensional profile, interface map | Metrics should align with situation type; misalignment signals framing issues. |
| Boundaries | G1 | Upstream | What is in/out of scope for measurement? Does the measurement boundary match the problem boundary? Are measurement voids in critical areas? | Boundary map, scope decisions | Measurement scope should align with problem scope; voids at boundaries are common hiding places. |
| Dimensions | G1 | Upstream | What dimensions can and should be measured? Does the measurement system cover decision-relevant dimensions? | Dimension catalogue, dimensional profile | Metrics should cover dimensions that matter; avoid measuring only convenient dimensions. |
| Realities | G1 | Upstream | What realities are being measured vs. not measured? Does the measurement system reflect the range of realities? | Reality taxonomy, measurement coverage | Measurement voids often exclude less convenient realities; explicit mapping prevents selective blindness. |
| Scale | G1 | Upstream | What scales of measurement matter (individual, team, organisation, system)? Does measurement capture cross-scale effects? | Scale analysis, cross-scale metrics | Metrics at one scale may hide dynamics at another; design metrics across scales relevant to decisions. |
| Time | G1 | Upstream | What time horizons matter? Do metrics capture temporal patterns or smooth over them? | Temporal analysis, leading/lagging indicator mix | Temporal misalignment (measuring at wrong timescale) is a common source of misreading; match metric cadence to decision tempo. |
| Systems | G2 | Middle | What system feedback loops exist? Do metrics capture system behaviour or only components? | System map, feedback loops, coupling analysis | Metrics that miss feedback loops miss system behaviour; measure system outputs, not just component outputs. |
| Relations | G2 | Middle | What relationships among actors/components does measurement affect? Can measurement distort relations? | Relationship map, measurement impacts on relations | Measurement systems affect the relations they measure; observer effect is a relational phenomenon. |
| Processes | G2 | Middle | What processes are being measured? Do metrics capture process quality or only outputs? | Process map, process quality metrics | Process metrics can be gamed more easily than outcome metrics; combine both. |
| Causation | G2 | Middle | What causal mechanisms should be measured? Do metrics reveal causes or only correlates? | Causal hypotheses, causal metric design | Metrics often measure correlates, not causes; design diagnostic metrics that reveal mechanism. |
| Resources | G2 | Middle | What resources does the measurement system consume? Is measurement cost-effective? | Resource accounting, measurement ROI | Measurement systems consume resources (data, attention, storage, governance); audit whether ROI justifies cost. |
| Agents | G3 | Middle | Who are the agents being measured? What incentives do they face? Can measurement be gamed by agents? | Agent map, incentive analysis | Agents are active; they respond to measurement; account for gaming behaviour in metric design. |
| Personas | G3 | Middle | Who uses the metrics? What information do different personas need? Do dashboards serve different personas? | Persona analysis, dashboard user needs | Different users need different metrics; single dashboard may serve all poorly. |
| Incentives | G3 | Middle | What incentive structures exist around measurement? Is metric linked to rewards? What gaming does it incentivise? | Incentive map, metric-incentive coupling analysis, Goodhart risk assessment | Incentive-coupled metrics need special governance; validate regularly; separate measurement from reward. |
| Power | G3 | Middle | Who controls the measurement apparatus? Is measurement capture by powerful actors occurring? | Power map, measurement control analysis | Power over measurement is power over narrative; audit whether measurement is captured. |
| Responsibility | G3 | Middle | Who is responsible for metric integrity? Who is accountable if metrics distort? | Responsibility map, metric governance | Responsibility for metric integrity should be explicit; ghost ownership enables gaming. |
| Competencies | G3 | Middle | What competencies are needed to use metrics well? Are users trained in reading metrics with appropriate scepticism? | Competency analysis, user training assessment | Metric literacy is not universal; support users in interpreting metrics without naive belief. |
| Culture and Norms | G4 | Middle | What cultural norms shape measurement choices? What does the measurement system communicate about what matters? | Culture analysis, norm impacts on measurement | Culture shapes what is measured and how it is interpreted; measurement system encodes and reinforces cultural values. |
| Perspectives | G4 | Middle | What perspectives exist on what should be measured? Do different roles/departments want different metrics? | Perspective mapping, stakeholder narratives | Perspectives on measurement are often power-laden; make explicit which perspectives the measurement system privileges. |
| Narratives | G4 | Middle | What narratives does the measurement system support? Does the metric "tell a story"? Can the story be contested? | Narrative analysis, metric narratives | Metrics become stories; single-metric narratives close off alternatives; design for narrative plurality. |
| Communications | G4 | Middle | How are metrics communicated? What is lost or distorted in communication? | Communications audit, metric communication analysis | Metric communication is not neutral; how metrics are presented shapes interpretation. |
| Legitimacy | G4 | Middle | Does the measurement system have legitimacy? Do stakeholders trust the metrics? | Legitimacy assessment, trust analysis | Measurement legitimacy depends on perceived independence and validity; gaming erodes legitimacy. |
| Values | G4 | Middle | What values are embedded in the measurement system? What priorities does measurement encode? | Value analysis, measurement value alignment | Measurement systems encode values (what's measured vs. not measured); explicit value mapping prevents hidden values. |
| Beliefs | G5 | Middle | What beliefs underpin the metrics? Are metric-based beliefs tested? | Belief analysis, validation of metric-based beliefs | Metrics shape beliefs; unvalidated metric-based beliefs can persist and drive decisions. |
| Evidence | G5 | Cross-cutting | What evidence supports the metrics? Are metrics valid? Are there contradicting signals? | Evidence quality grading, evidence gaps, contradicting evidence | Metrics are evidence; audit whether they are good evidence; look for contradicting evidence. |
| Uncertainties | G5 | Cross-cutting | What uncertainties exist in the metrics? Are uncertainties quantified or hidden? | Uncertainty quantification, confidence intervals | Metrics often hide rather than reveal uncertainties; make uncertainties explicit. |
| Failures | G5 | Cross-cutting | How do metrics fail? What are the failure modes? | Failure analysis, metric failure modes | Metrics fail (Goodhart, proxy drift, gaming, capture); analyse failure modes and mitigations. |
| Hiddens | G5 | Cross-cutting | What visibility failures does the measurement system generate? What Hiddens are measurement-specific? | Hiddens scan results, measurement-generated Hiddens | Metrics both reveal and hide; systematic Hiddens analysis prevents false confidence. |
| Diagnosis | G5 | Middle | Can metrics diagnose root causes? Or do they only measure symptoms? | Diagnostic metric analysis, causal mechanism measurement | Diagnostic metrics should reveal causes; outcome-only metrics can misguide interventions. |
| Knowledge | G5 | Cross-cutting | What does the measurement system enable us to know? What knowledge claims can metrics support? | Knowledge claims, epistemological limits | Metrics are ways of knowing; recognise their limits and complement with other ways of knowing. |
| Decisions | G6 | Downstream | What decisions do metrics inform? Is the metric-decision link sound? | Decision-metric mapping, decision analysis | Metrics should inform the decisions they are designed for; misaligned metrics distort decisions. |
| Interventions | G6 | Downstream | What monitoring design does the intervention need? Are success criteria metric-based? | Intervention monitoring design, success criteria | Intervention monitoring should measure mechanism and outcome; ensure success metrics are sensitive to intervention effects. |
| Governance | G6 | Downstream | What governance structure keeps metrics valid? Who is accountable for metric integrity? | Governance design, metric governance charter, accountability structure | Weak governance enables gaming and metric capture; strong governance requires authority independent from those measured. |
| Risk | G6 | Downstream | What risks does the measurement system create (Goodhart effects, gaming, false confidence)? | Risk analysis, metric-induced risk, risk mitigation | Metrics generate risk; audit measurement-induced risks alongside measurement benefits. |
| Learning and Adaptation | G6 | Downstream | Do metrics enable learning and adaptation? Or do they lock in initial beliefs? | Learning loop assessment, metric evolution, metric retirement protocols | Metrics should support learning; avoid metric ossification; design for metric evolution and retirement. |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---:|---|---|---|
| 1 | Design Invisibility | Metric choices (what to measure, why, how) are made early and then become invisible—the design rationale is lost, the alternatives are forgotten, and the metric persists past its relevance. | Maintain design documentation: who chose this metric, when, why, what alternatives were considered. Revisit design decisions periodically. Retire metrics whose original rationale no longer applies. |
| 2 | Proxy Decay Without Detection | Proxy and target were correlated, but the correlation weakens as the system changes. The proxy persists because proxy-target validation is not performed regularly. | Validate proxy-target correlation on a defined cadence. Use multiple proxies instead of single proxy. Monitor for divergence signals. Retire proxies when drift confirmed. |
| 3 | Incentive-Driven Distortion | Metrics linked to high-stakes consequences are optimised by actors rather than measuring underlying reality (Goodhart effect). This distortion is not detected because people are reluctant to report gaming. | Separate measurement authority from the entity being measured. Use complementary metrics so gaming one doesn't game all. Validate metrics against independent ground truth. Enable protected reporting of gaming. |
| 4 | Aggregation Amnesia | Aggregation destroys diagnostic information, and the destruction is not noticed because aggregate metrics are stable and satisfy reporting needs. Disaggregation would reveal hotspots and outliers. | Maintain granular metrics alongside aggregates. Disaggregate periodically to check what's hidden. Publish distributions, not just means. Highlight tails and outliers, not averages. |
| 5 | Governance Vacuum | No one is accountable for metric validity, review cadence, or retirement. Outdated metrics persist; shadow metrics proliferate; changes go untracked. | Assign explicit owners and reviewers for each metric. Establish review cadences and retirement criteria. Track metric changes in a changelog. Hold governance meetings for metric lifecycle. |
| 6 | Threshold Drift | Thresholds that define acceptable/unacceptable drift gradually without formal decision or re-validation. Metric appears to improve while underlying reality hasn't changed. | Govern threshold changes formally. Require public changelog of threshold modifications. Validate thresholds periodically. Make threshold changes explicit, not silent. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)

| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|---|
| I  Perceptual | Salient metrics dominate perception; alternative signals go unnoticed. Metric "tells a story" that overrides contradictory signals. | "The numbers look good" despite operational concerns. Frontline worries dismissed because metrics are positive. Narrative closure around metric story. | Ask: "What contradicts this metric?" "What stories do people tell when they disagree with the metric?" "What signals go unnoticed because the metric dominates?" Spot for contradiction in operational reality. |
| II Systemic | Measurement feedback loops distort system behaviour (observer effect, metric-incentive coupling effects). Stabilised dashboards hide system dynamics. | System behaves differently when measured. Measurement produces unexpected consequences. Metric-driven behaviour differs from metric intent. | Ask: "How does measurement change behaviour?" "What gaming or adaptation occurs?" "Do systems show signs of measurement-induced strain?" Audit for observer effects and unintended consequences. |
| III Informational | Data is suppressed, filtered, or unavailable. Measurement gaps leave domains structurally invisible. Reported metrics differ from underlying data. | "The data isn't available." Access to measurement underlying data is restricted. Shadow metrics exist because official channels are gated. Reported metrics differ from source data. | Ask: "Can we access the underlying data?" "What measurement gaps exist?" "Are shadow metrics being used because official metrics are unavailable?" Audit for measurement access and data suppression. |
| IV Temporal | Reporting latency hides rapid changes. Temporal smoothing masks transitions. Metric cadence mismatches decision tempo. | Problems emerge between reporting cycles. Changes are detected too late. Temporal patterns are hidden by aggregation across time. Metric appears stable while reality changes rapidly. | Ask: "How latent is the metric?" "What temporal patterns are smoothed over?" "How frequent is reporting compared to decision tempo?" Audit for temporal Hiddens. |
| V  Relational | Different roles see different metrics. Power-laden framing of measurement advantages some stakeholders over others. Measurement instrumentalised for control. | Different teams report different metrics for the same phenomenon. Managers see a metric that frontline workers don't see (positional blindness). Measurement used to control narrative. | Ask: "Who sees what metrics?" "What do different roles measure?" "Is measurement instrumentalised for power?" Audit for relational and positional Hiddens. |
| VI Ontological | Metrics reify (make real) concepts that are actually fluid or contested. Measurement assumes a reality that does not exist. Metrics embody implicit ontology that is not examined. | "Quality" is measured as if it's a single thing; but quality is multivalent and contested. "Productivity" is measured; but what productivity means varies by role. Metrics assume categories that are not universal. | Ask: "Does this metric assume categories or definitions that are contested?" "What is measured vs. what is real?" "Are the metric categories the only way to see this phenomenon?" Audit for ontological assumptions. |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)

| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability | Agency | Consequence | Detection interface(s) (Type A) | Remediation interface(s) (Type B) | Interaction notes (Type C) |
|---|---|---|---|---|---|---|---|---|
| H-3 Secret (measurement suppression) | M | Data withheld or restricted from decision-makers; measurement performed but results not shared. | Medium | Entity being measured controls access; gating reflects power interests. | Medium–High (decision-makers unaware of measured reality) | Audit data access; compare internal vs reported metrics; interview frontline for shadow metrics. | Separate measurement authority from measured entity; enable protected reporting channels; audit data completeness. | Feeds into Systemic and Relational Hiddens if widespread. |
| H-4 Inference (untested proxy assumption) | H | Metric assumed to measure one thing; actually measures a proxy. Proxy-target link assumed, not tested. | Medium–High (validation would reveal it) | Often unintentional; metric designer may not have tested proxy validity. | High (metric-driven decisions based on false assumption) | Proxy-target validation study; compare proxy with direct measurement of target; monitor for drift. | Validate proxies on cadence; use multiple proxies; retire proxies when drift confirmed; measure targets directly where possible. | Interacts with metric decay dynamics; may be masked by Goodhart effects if proxy is incentivised. |
| H-6 Distortion (measurement-induced) | H | Collection method, aggregation method, or interpretation of metric distorts the signal. | Medium (independent audits would reveal it) | Often technical/unintentional; but sometimes deliberate. | High (decisions based on distorted signal) | Ground-truth sampling against metrics; independent measurement audit; disaggregation analysis. | Improve collection methods; reduce aggregation loss; increase transparency in calculation; validate against independent sources. | Interacts with H-7 Mirage (distortion masked by reporting stability). |
| H-7 Mirage (measurement-created illusion) | H | Metric produces stable, reassuring signal disconnected from operational reality. Dashboard sustains illusion despite contradictory ground truth. | Medium (operational reality checks would reveal it) | Often structural (measurement system design, aggregation, smoothing); can be deliberate. | High (false confidence in system state; decisions made on narrative) | Operational audits; frontline reality checks; disaggregation of aggregate metrics; compare dashboard to on-ground experience. | Independent operational checks; escalation routes for contradictions; disaggregate to hide differences; reduce reporting smoothing. | Feeds into Perceptual and Systemic Hiddens; can cascade with H-8 Framing (metric becomes "the story"). |
| H-8 Framing (metric choice foregrounds/hides) | H | Metric choice foregrounds some realities and hides others. Metric defines what counts, what is visible, what matters. | Medium (alternative metrics would reveal what's hidden) | Deliberate or structural; often reflects power to define what is measured. | High (what is not measured is invisible; metric becomes defining frame) | "What would we measure if we wanted to see X?" analysis; alternative metric design; stakeholder perspective mapping. | Explicit metric void analysis; design complementary metrics; enable stakeholder input on measurement priorities; plural metrics rather than single frame. | Interacts with H-25 Perspectival (different roles want different metrics); feeds into H-21 Positional if measurement advantage is unequal. |
| H-9 Aggregation (averaging hides tail risk) | H | Aggregation across entities hides hotspots, outliers, and tail risks. Average looks good while distribution has dangerous tails. | Medium (disaggregation would reveal it) | Structural to aggregation process; often unintentional but sometimes convenient. | Medium–High (tail risks missed; decisions made on average that ignores outliers) | Disaggregation analysis; distribution visualisation; focus on tails and percentiles, not means; outlier audit. | Publish distributions, not just means; disaggregate by relevant subgroup; highlight extremes; use complementary percentile metrics. | Interacts with H-11 Theory/Model if aggregation embeds assumptions about what drives the metric. |
| H-11 Theory/Model (untested implicit model) | H | Metric embeds causal model that may be wrong. Metric assumes "if X improves, Y will follow"; but causal link may not hold. | Medium (testing model against reality would reveal it) | Designer's implicit mental model embedded in metric definition. | High (interventions based on metric improve metric but not underlying outcome) | Test metric-outcome relationship; monitor whether metric improvement correlates with actual outcomes; model audit. | Make implicit model explicit; test causal assumptions; use diagnostic metrics that measure drivers, not just outcomes. | Interacts with H-4 Inference and H-6 Distortion (faulty model, faulty proxy). |
| H-15 Latency (reporting delays hide rapid change) | M | Reporting delays, collection cadence, or smoothing hide rapid changes. Problem emerges between reporting cycles. | Low–Medium (latency is measurable; but often accepted as tradeoff) | Structural to data pipeline; reflects batch processing vs real-time. | Medium (delayed detection = narrow response window) | Measure reporting latency; compare metric update frequency to decision tempo; run real-time pilots. | Reduce reporting latency for critical metrics; create fast-path reporting; use leading indicators to offset lag. | Feeds into H-7 Mirage (latency masks transitions, sustaining illusion of stability). |
| H-17 Ghost (zombie metrics persisting past relevance) | M | Legacy metric persists despite being outdated, irrelevant, or invalidated. Continues to consume resources and create noise. | High (zombie status is observable) | No one accountable for retirement; inertia; metric definition embedded in systems/policy. | Low–Medium (wasted effort, noise) | Metric age audit; purpose-reality check (does this metric still inform a real decision?); orphan metric identification. | Implement mandatory metric review; explicit retirement criteria; regular "zombie hunts"; governance process for retirement. | Interacts with H-27 Zombie in pathology taxonomy (Type 27). |
| H-21 Positional (different roles see different metrics) | M | Different roles see different metrics; asymmetric visibility. Leadership sees aggregates; frontline sees granularity. Measurement advantage unequal. | Medium (role-based access audit would reveal it) | Structural to role differentiation and information governance. | Medium (decisions made on incomplete information due to role limits; coordination failures) | Role-based information audit; compare what different roles see; identify information asymmetries. | Ensure role-appropriate metrics (not one size fits all); design dashboards for multiple personas; transparency about information asymmetries. | Feeds into H-25 Perspectival (different roles want different metrics). |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)

1) Run Tier 1 scan across all six Hiddens meta-categories (early pass; assume Hiddens exist) (OG v2.5 §7.1).
2) Shortlist candidate Hiddens; for each, rate: mechanism, reducibility, detectability, agency, consequence.
3) Assign at least one detection interface (Type A) and one remediation interface (Type B) per high-consequence Hidden; map interaction chains (e.g., Distortion → Mirage → Framing → delayed detection).
4) Run Hiddens source analysis (§8.1) and record unresolved Unknowns/Hiddens.
5) After executing the framework protocol and any available tests/probes, re-run Tier 1 (pre-closure pass) and note deltas.
6) Produce Residual Unknowns (with mechanism + impact + next probe) and apply Escalation Rule (below) if any residual could change decisions, accountability, or remediation priorities.

## 8.5 Escalation Rule (Tier 3 – full Hiddens run)

Escalate to full 30-type Hiddens scan + detection/remediation matrix mapping if any apply:

- **High consequence**: Safety, regulatory exposure, financial materiality, existential risk
- **Metric-incentive coupling with high-stakes rewards or penalties**: Strong Goodhart risk; gaming likely
- **Persistent disagreement** about whether metrics reflect reality: Suggests underlying Hiddens
- **Evidence that metrics have been weaponised or captured** by interested parties: Measurement integrity compromised
- **Repeat failures despite "good metrics"**: Measurement system may be part of the problem
- **Strong suspicion of cascading metric pathologies**: Goodhart → Mirage → Dashboard Ossification → late crisis detection

---

# 9. Framework Application Protocol (7-step; mandatory)

## 9.1 Seven-Step Application Protocol

| Step # | Step name | Action | Outputs / artefacts |
|---:|---|---|---|
| 1 | Situation & Goal Clarification | What measurement system is under examination, and why? Define the purpose of the metric audit or design. Identify focal decision, system, or problem. Clarify stakeholders, time horizon, and stakes. Confirm Run Mode and routing per Operating Guide. | Case statement; scope boundaries; stakeholder map; purpose statement (audit vs design vs both); Run Mode and routing confirmation; preliminary metric inventory scope. |
| 2 | Metric Inventory & Meta-Category Scan | What metrics exist (or are proposed), and which meta-categories are relevant? Build or review the metric inventory. Classify existing metrics across the six meta-categories. Identify metric voids (what should be measured but isn't). Map metric ownership and governance status. | Metric inventory table (name, definition, owner, category, collection method, reporting chain, governance status); meta-category coverage map; initial metric void list; unmeasured-domain analysis. |
| 3 | Type Mapping & Pathology Scan | What metric types are in play, and what pathologies are active or emerging? Classify each critical metric by type (Types 1–30). Scan for active pathologies (Goodhart decay, proxy drift, aggregation loss, false precision, dashboard theatre, metric capture, zombie metrics). Assess gameability for incentive-coupled metrics. | Metric type classification; pathology map with severity (H/M/L) and mechanism; Goodhart risk assessment for incentive-coupled metrics; pathology interaction chains. |
| 4 | Dimensions & Dynamics Profiling | How does each critical metric score on the five dimensions, and what dynamic patterns are operating? Rate critical metrics along five dimensions (validity, sensitivity, gameability, consequentiality, transparency). Identify active dynamic patterns (Goodhart decay, proxy drift, metric monoculture, aggregation creep). Map metric lifecycle stage. | Dimension profiles for critical metrics (scored across five dimensions); dynamics assessment (which patterns are active); lifecycle stage map; metric health scorecard; dynamic interaction risks. |
| 5 | Interfaces + Hiddens Source Analysis | Where are the key interfaces, and what measurement-generated Hiddens are present? Map Type A (measurement-reality), Type B (metric-decision), and Type C (metric-incentive) interfaces for critical metrics. Run Hiddens Source Analysis (§8.1) and Tier 1 scan (§8.2). Shortlist high-consequence Hiddens. | Interface maps (A/B/C) for critical metrics; Hiddens Source Analysis output; Tier 1 Hiddens scan results; detection and remediation moves; Tier 2 Hidden candidates for Investigative runs. |
| 6 | Metric Strategy, Governance & Recommendations | What should be changed, and how? Design metric improvements (redesign, replacement, retirement, new metrics). Specify metric governance (ownership, review cadence, retirement criteria, change control). Produce monitoring-of-monitoring indicators. Link to Decisions, Interventions, Governance, and Learning frameworks. | Metric strategy document (redesign/replace/retire/create with justification); governance recommendations with owners and cadence; monitoring-of-monitoring design; metric void-filling plan; Residual Unknowns and Closure Note. |
| 7 | Integration Handoff & Closure | How does this metric work integrate with the broader investigation? Hand off outputs to relevant frameworks (Decisions, Interventions, Governance, Risk, Learning). Produce Residual Unknowns with acceptability rationale, monitoring plan, ownership, and learning hook. Record closure status and escalation recommendation. | Integration handoff summary; Residual Unknowns statement; Closure Note (per OG v2.5 §7.4 closure discipline); escalation recommendation if needed; next-step assignments and review cadence. |

## 9.2 Standard Deliverables (recommended)

**Minimum deliverable (1–2 pages)**:
- Metric inventory and meta-category coverage
- Top 5–8 metric pathologies with severity and recommended action
- Dimension profiles for the 3–5 most critical metrics
- Hiddens shortlist (8–12) with detection/remediation moves
- Metric governance recommendations (owners + cadence)
- Residual Unknowns and closure status

**Full deliverable pack**:
- Complete metric register (all active metrics classified by type)
- Full pathology map with interaction chains
- Interface analysis (A/B/C) for all critical metrics
- Metric lifecycle plan (creation standards, validation protocols, review cadence, retirement criteria)
- Metric-incentive coupling analysis and separation recommendations
- Metric void analysis (what is not measured and why it matters)
- Dashboard integrity assessment (design, narrative, coverage)
- Monitoring-of-monitoring design (who watches the measurement watchers?)
- Measurement-induced risk assessment (Goodhart effects, gaming risks, false confidence risks)
- Recommended metric governance charter (roles, authority, process, cadence)

**Monitoring indicators** (embedded in recommended metrics):
- Metric-reality correlation for critical proxies (validation cadence)
- Goodhart decay indicators for incentive-coupled metrics (metric improvement vs reality improvement)
- Metric proliferation rate and retirement rate (balance)
- Dashboard-operational-reality divergence signals (independent audits)
- Metric governance compliance (review cadence adherence, ownership currency)
- Time since last metric validation for each critical metric
- Metric monoculture risk (concentration on single metric or metric type)

### Canonical shared registers (Operating Guide aligned; mandatory for LLM use)
| Shared register / artefact | Required | Notes (how this framework contributes) |
|---|---:|---|
| Group Coverage Matrix (G1–G6) | Yes | Record which groups were examined at Full Depth vs Light Depth; note gaps. For Metrics: typically primary coverage in G5 (epistemics/measurement integrity); significant coverage in G6 (metric governance and decision integration). |
| Hiddens Register | Yes | Populate candidate Hiddens generated by the measurement system (Goodhart decay, proxy drift, aggregation loss, dashboard theatre, metric capture, measurement absence). Include probes/tests and remediation levers. |
| Evidence Ledger | Yes | Track key claims about metric validity, reliability, integrity. Record evidence quality and gaps; prioritise testing proxy-target relationships and metric-incentive interactions. |
| Hypothesis/Test Backlog | Yes | Convert metric-related Unknowns into testable probes (proxy validity, Goodhart decay, aggregation effects, gaming behaviour, etc.). Prioritise tests that would change metric governance or intervention monitoring design. |
| Information Requests | Yes | Explicit list of missing inputs needed to reduce decision-critical Unknowns about measurement (access to underlying data, proxy-target data, ground-truth samples, gaming evidence, etc.). |
| Residual Unknowns + Closure note | Yes | State what remains hidden about the measurement system, why it is hidden, and what it would take to surface it. Include escalation recommendation if metric integrity concerns depend on these unknowns. |
| Investigation Plan (post-failure) | Conditional | Required when measurement system failure contributed to operational failure. Maps investigation to metric-level mechanisms (which metric types, pathologies, interfaces are implicated). |
| Decision/Action Record (if recommending changes) | Conditional | Required when proposing metric redesign, governance changes, or incentive restructuring. Records what metric-level changes are being targeted, why they are expected to work, and what dynamic patterns may resist the change. |

---

# 10. Framework Principles (5 core; mandatory)

## 10.1 Principles Table
| Principle name | Description |
|---|---|
| 1. Metrics are designed artefacts, not neutral windows | Every metric embeds design choices (proxy selection, threshold placement, aggregation rules, temporal framing, definition boundary) that should be examined, documented, and periodically re-evaluated. Treat every metric as a hypothesis about what matters, not a fact about reality. Challenge the design regularly. |
| 2. What is not measured is structurally invisible | The most consequential metric pathology is often absence—the unmeasured domain that accumulates risk, suffers neglect, or escapes governance. Metric analysis must always include void analysis: what important things have no metric, and why? |
| 3. Separate measurement from reward | Metric-incentive coupling is the primary driver of Goodhart decay and systematic distortion. Where metrics must be linked to consequences, use metric baskets (multiple complementary metrics), rotating indicators (preventing gaming of same metric), and independent validation to maintain measurement integrity. |
| 4. Govern metrics as assets with lifecycles | Metrics should be created with purpose statements, validation protocols, review cadence, and explicit retirement criteria. Metric governance (ownership, modification authority, retirement authority) should be explicit and exercised. Unowned metrics are ungoverned metrics; zombie metrics persist without governance. |
| 5. Assume measurement generates Hiddens | Measurement systems do not merely observe—they shape perception, behaviour, narrative, incentive response, and decision-making. Use the Hiddens cross-check to identify where the measurement system itself is creating or sustaining visibility failures. The question is not "does our measurement system generate Hiddens?" but "which Hiddens is it generating?" |

---

# 11. Glossary (local domain terms; comprehensive; mandatory for Stable status)

## 11.1 Local domain glossary
| Term | Definition |
|---|---|
| Metric | A specified, repeatable measurement applied to an aspect of a system, process, agent, or outcome, producing a quantitative or qualitative signal intended to inform understanding, comparison, or action. Includes its definition, instrument, collection method, aggregation rules, reporting chain, governance context, and decision linkage. |
| Measurement System | The full socio-technical apparatus through which metrics are designed, collected, aggregated, reported, interpreted, acted upon, governed, and retired. Includes instruments, data pipelines, dashboards, reporting structures, incentive couplings, and governance arrangements. |
| Proxy Metric | A metric that measures a correlated, observable variable as a stand-in for a harder-to-measure target. All proxies carry validity assumptions that can degrade over time. |
| Proxy Drift | The gradual decoupling of a proxy metric from the target variable it was designed to represent, often due to environmental change, regime shift, or behavioural adaptation. |
| Goodhart's Law | "When a measure becomes a target, it ceases to be a good measure." The principle that metrics lose validity when coupled to high-stakes incentives because actors optimise the metric rather than the underlying phenomenon. |
| Goodhart Decay | The dynamic process by which a metric progressively loses its validity due to Goodhart effects—the ongoing degradation of metric-reality correlation under incentive pressure. |
| Goodhart Risk | The risk that a metric coupled to high-stakes consequences will be optimised rather than maintained as an accurate signal. Quantified by (a) how gameable the metric is, (b) how high the stakes are, and (c) whether monitoring for gaming exists. |
| Dashboard Theatre | The practice of producing visually compelling metric summaries that create an illusion of oversight and control without corresponding operational reality. A stabilised mirage sustained by reporting conventions, smoothing, and design choice. |
| Metric Monoculture | Over-reliance on a single metric or metric type to the exclusion of complementary signals, creating vulnerability to the specific blind spots of that metric. Metric monoculture locks in organisational blindness. |
| Metric Capture | A state where a powerful actor gains control over the measurement apparatus—defining what is measured, how, by whom—and uses that control to shape narrative and protect position rather than surface truth. |
| Metric Void | A systematic absence of measurement in a domain that matters—an entire class of phenomena goes unmeasured, creating structural invisibility. Voids are often deliberate (reflecting power interests) or convenient (reflecting measurement difficulty). |
| Metric Lifecycle | The stages a metric passes through from conception and design through implementation, validation, active use, degradation, and retirement. Each stage has characteristic risks and governance requirements. |
| False Precision | A metric that implies a level of accuracy or certainty that is not supported by the underlying data, methodology, or epistemic conditions. Numbers that look precise but are not—false confidence. |
| Aggregation Loss | The destruction of diagnostic information through the process of combining individual measurements into summary statistics. Every aggregation step removes detail that may have been decision-relevant. Examples: averaging (which hides distributions), indexing (which hides weights), grand totals (which hide breakdowns). |
| Leading Indicator | A metric intended to provide early warning of future states before they fully materialise. Epistemically fragile (correlation between indicator and future state often assumed, not tested) but high-value when valid. Subject to decay as system changes. |
| Lagging Indicator | A metric that captures outcomes after they have occurred. Definitive but late—by the time a lagging indicator signals a problem, the problem has already manifested. Useful for retrospective learning but not prospective action. |
| Metric Budget | A deliberate cap on the number of active metrics in a system, designed to prevent metric proliferation and maintain signal-to-noise ratio. |
| Metric Retirement | The deliberate, governed removal of a metric from active use, including cessation of collection, reporting, decision integration, and system embedding. Distinct from simply stopping collection. |
| Separation of Measurement from Reward | A governance principle that the entity or process producing a metric should be independent from the entity whose performance is being measured by that metric. The primary structural defence against Goodhart effects. |
| Ground-Truth Sampling | The practice of periodically checking metric outputs against direct, independent observation of the underlying reality, to detect drift, distortion, decoupling, or gaming. |
| Metric Validity | The degree to which a metric measures what it claims to measure. Validity is dynamic—a metric can be valid in one context and invalid in another; validity can degrade over time as the phenomenon or context changes. |
| Metric Reliability | The consistency and reproducibility of a measurement. A metric can be reliable (consistent) but not valid (not measuring what it claims). |
| Metric Gamification | The phenomenon where actors learn to optimise the metric without improving the underlying reality. May be deliberate or unintentional. |
| Zombie Metric | A metric that persists despite being outdated, irrelevant, or invalidated. Continues to consume resources and create noise. |
| Metric Pathology | Any systematic failure or distortion in a metric or measurement system (Goodhart decay, proxy drift, gaming, capture, false precision, metric void, etc.). |
| Observability Assumption | The assumption that a phenomenon is directly observable and measurable. Violation of this assumption (when phenomena are tacit, delayed, or latent) often drives proxy use. |
| Responsiveness (metric) | How quickly a metric responds to real changes in the underlying phenomenon. Responsiveness must match decision tempo; a slow metric cannot support fast decisions. |
| Threshold | A value that defines the boundary between acceptable and unacceptable performance. Thresholds are often arbitrary and rarely re-validated. |
| Metric Design | The process of selecting what to measure, how to measure it, how to aggregate, and how to report. Design choices determine what is visible and what is hidden. |
| Metric Governance | The explicit assignment of authority and accountability for metric creation, modification, validation, and retirement. Includes ownership, review cadence, change control, and escalation processes. |
| Measurement Independence | The degree to which the measurement system is independent from the system/entity being measured. Low independence increases gaming and distortion risk. |
| Metric Literacy | The ability to interpret metrics with appropriate scepticism, understanding what the metric does and does not measure, recognising pathologies, and avoiding naive belief. |

## 11.2 Core execution terms (pointer; do not restate)
- See **Analytical Series Operating Guide**, v2.5, Appendix D §D.10.1 and §D.10.2.

---

# 12. Document Control (recommended; mandatory for Stable status)

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v1.0 | 2026-03-28 | Initial creation as a framework in the Analytical Series. Fills the systematic measurement gap identified across the series. 6 meta-categories, 30 core metric types, 5 dimensions, 12 dynamic patterns, 3 interface types, full Hiddens cross-check, 6-step application protocol, principles, and glossary. (Created by: Anthropic Claude Opus 4.6) |
| v2.0 | 2026-04-06 | Rewrite for alignment with Master Rewrite Template v2.3 and Operating Guide v2.5. Added Introduction section (four subsections: What is Metrics, Why it matters for Hiddens, What does it produce, How to use). Expanded §1.6 LLM integration with Tier 2 Hiddens crosswalk, Targeted Scans routing, Information Requests schema, and full operating guide references. Expanded §7.3 integration table to include all 36 frameworks per OG v2.5 §3.2 (canonical framework list). Expanded §8 Hiddens with framework-specific sources (§8.1), comprehensive Tier 2 deepening (§8.3), and explicit escalation rule for Tier 3. Strengthened metric pathology catalogue in §3 with clear failure/hidden-risk signatures for all 30 types. Added standalone 7-step application protocol in §9 with clear step-by-step guidance. Enhanced glossary (§11) with 35+ terms covering metrics, pathologies, governance, and Hiddens integration. Updated all OG references from v1.5 to v2.5. Full structural conformance to Master Rewrite Template v2.3 including Document Information format, At-a-Glance table, mandatory sections (Introduction, 1.1–1.6, 2–8, 9–12), staged Hiddens depth model (Tier 1/2/3), and integration with 36-framework canonical list. ~850 lines; complete, no placeholders. (Rewritten by: Anthropic Claude Opus 4.6) |

## 12.2 Integration Notes (optional)
Use this framework whenever:
- measurement systems are suspected of generating or sustaining visibility failures,
- "the numbers looked fine" but the outcome was bad,
- metric-incentive coupling may be distorting behaviour and reporting,
- dashboards tell a story that contradicts operational experience,
- intervention monitoring needs to be designed,
- metric governance is weak, absent, or captured,
- measurement proliferation has degraded signal-to-noise ratio,
- a critical domain appears to have no metrics (metric void),
- post-failure investigation identifies metrics as a contributing factor,
- operational reality contradicts metric signals (suspected mirage or proxy drift).

The Framework of Metrics serves as the constructive companion to the series' existing measurement warnings. Where other frameworks note that "metrics can distort" or "Goodhart effects exist," this framework provides the taxonomy, protocol, governance guidance, and remediation moves to diagnose and address those pathologies systematically. It is designed to be used repeatedly—as a diagnostic audit tool when problems emerge, as a design guide when creating new measurement systems, and as a governance framework when strengthening measurement integrity and preventing decay.

---

## Appendix A: Consolidated 30-Type Reference Table (single view)

| # | Type name | Meta-category | Brief description | Key Hiddens risk |
|---:|---|---|---|---|
| 1 | Direct Measurement | I. Design & Selection | Measures the phenomenon itself, without proxying. | Assumes observability; misses tacit/delayed phenomena. |
| 2 | Proxy Metric | I. Design & Selection | Measures a correlated variable as stand-in for harder target. | Proxy drift (correlation decays). |
| 3 | Composite / Index Metric | I. Design & Selection | Combines multiple sub-metrics into single score. | Aggregation loss (destroys diagnostic info). |
| 4 | Threshold / Binary Metric | I. Design & Selection | Converts continuous variable into categorical signal. | Threshold placed arbitrarily; populations near threshold unstable. |
| 5 | Absence / Null Metric | I. Design & Selection | Systematic absence of measurement in a domain. | Structural invisibility; measurement void. |
| 6 | Automated / Sensor Metric | II. Collection & Instrumentation | Automated instrument collection. | Calibration drift; instrument failure; observer effect. |
| 7 | Self-Report / Survey Metric | II. Collection & Instrumentation | Subjective reports from measured entities. | Reporting bias; social desirability; intentional distortion. |
| 8 | Observational / Audit Metric | II. Collection & Instrumentation | Independent observation or inspection. | Observer bias; observer effect; audit latency and cost. |
| 9 | Derived / Calculated Metric | II. Collection & Instrumentation | Computed from other metrics via formulas/models. | Model assumptions may be wrong; formula bugs; inherited errors. |
| 10 | Sampled / Estimated Metric | II. Collection & Instrumentation | Based on sampling, not exhaustive measurement. | Sampling bias; sampling error; non-representative sample. |
| 11 | Average / Central Tendency Metric | III. Aggregation & Representation | Summarises distribution by centre. | Averages hide distributions, tails, outliers; masks heterogeneity. |
| 12 | Rate / Ratio Metric | III. Aggregation & Representation | Normalises quantity by reference value. | Denominator changes; ratio gaming; loses absolute magnitude. |
| 13 | Ranking / League Table Metric | III. Aggregation & Representation | Converts absolute values to ordinal positions. | Small score changes produce large ranking swings; gaming of rankings. |
| 14 | Trend / Time-Series Metric | III. Aggregation & Representation | Tracks variable over time. | Smoothing hides transitions; starting point bias; seasonal patterns. |
| 15 | Dashboard / Scorecard Metric | III. Aggregation & Representation | Curated collection for integrated visual summary. | Dashboard theatre; hidden metrics; design privileges certain signals. |
| 16 | Target / Goal Metric | IV. Interpretation & Use | Coupled to specific numerical target. | Goodhart decay; cliff effects; targets persist past relevance. |
| 17 | Benchmark / Comparison Metric | IV. Interpretation & Use | Used for comparison against peers/standards. | Benchmark gaming; context differences hidden. |
| 18 | Leading Indicator | IV. Interpretation & Use | Early warning of future states. | Correlation breaks; lead time assumption invalid. |
| 19 | Lagging Indicator | IV. Interpretation & Use | Captures outcomes after occurrence. | Late detection; narrow response window. |
| 20 | Diagnostic / Root-Cause Metric | IV. Interpretation & Use | Designed to explain why something is happening. | Causal mechanism assumed, not tested; breaks when system changes. |
| 21 | Compliance / Regulatory Metric | V. Governance & Accountability | Mandated by regulation or standards. | Compliance theatre; gaming compliance without managing risk. |
| 22 | Accountability / Attribution Metric | V. Governance & Accountability | Used to assign credit, blame, or responsibility. | Goodhart decay (high-stakes coupling); scapegoating; perverse outcomes. |
| 23 | Audit / Assurance Metric | V. Governance & Accountability | Verified by independent party. | Audit independence compromised; findings ignored; audit theatre. |
| 24 | Lifecycle / Maturity Metric | V. Governance & Accountability | Tracks lifecycle stage or maturity level. | Maturity forced (stages rushed); premature transition. |
| 25 | Shadow / Informal Metric | V. Governance & Accountability | Used operationally but not formally governed. | Shadow/official metric divergence signals reality-metric decoupling. |
| 26 | Goodhart Metric | VI. Pathology & Failure | Metric has become optimisation target; decoupled from reality. | Systematic distortion; gaming; metric improves, reality doesn't. |
| 27 | Zombie Metric | VI. Pathology & Failure | Persists despite being useless. | Wasted resources; metric accumulation; noise increases. |
| 28 | Weaponised Metric | VI. Pathology & Failure | Deliberately manipulated to serve interests. | Deliberate distortion; measurement becomes tool of power. |
| 29 | Mirage Metric | VI. Pathology & Failure | Produces stable signal disconnected from operational reality. | Stable false signal; delayed detection; belief in mirage persists. |
| 30 | Metric Void | VI. Pathology & Failure | Systematic absence of measurement in a domain. | Structural invisibility; accumulating risk; deliberate concealment. |

---

**End of Framework of Metrics v2.0**
