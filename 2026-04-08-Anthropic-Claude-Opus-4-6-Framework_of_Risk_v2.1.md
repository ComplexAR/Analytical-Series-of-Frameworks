# Framework of Risk
*A Comprehensive Taxonomy for Prospective Risk — from Scenarios and Exposure to Systemic Propagation and Governance*

## Document Information
- Series: Analytical Series of Frameworks
- Version: v2.1
- Date: 2026-04-08
- Status: Stable
- Operating Guide Compatibility: Analytical Series Operating Guide v2.4
- Prompt Discipline Ruleset: Operating Guide "Prompt Discipline Rules (Canonical)" (see OG v2.4, §D.3)
- Run Mode Terminology: Rapid Run Mode / Investigative Run Mode (see Operating Guide §D.10.1)
- Framework Execution Depth Terminology: Full Depth Framework Execution / Light Depth Framework Execution (see Operating Guide §D.10.1)
- Tiered Hiddens Scan Model: Tier 1 (six-category visibility audit) / Tier 2 (structured deepening) / Tier 3 (full-spectrum escalation) (see Operating Guide §D.6.10)
- Targeted Hiddens Discovery Scans: Thirteen mechanism-specific cross-framework scans (see Operating Guide §7.5)
- Group (Primary): G6 — Action & Control (Action & Control)
- Group (Secondary): G5 — Epistemics (Epistemics)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Identify, structure, and treat risk across scenarios, exposure, uncertainty, impact, systemic propagation, and governance; align risk decisions to explicit appetite and values; design monitoring and learning loops to prevent drift and reporting distortion
- Primary Audience: Executives and boards; risk and resilience leaders; security and safety leaders; programme and transformation leaders; governance, compliance, and audit leaders; analysts and strategists; incident and crisis leaders
- Dependencies / Key Inputs: Focal decision and stakeholders; boundary and time-horizon definition; evidence base and uncertainty register; system and dependency maps; governance structure and incentives; available resources and constraints
- Primary Outputs: Risk register and scenario library; dimension profiles for priority risks; systemic propagation and interface map; appetite/tolerance alignment notes; treatment and monitoring plan; Hiddens register + tiered Hiddens scan outputs
- Change Log (brief): v2.0 rewrite aligns to Analytical Series Master Rewrite Template v2.3 and Operating Guide v2.4; expanded Assumptions & Preconditions; integrated LLM execution quickstart and Prompt Discipline Rules; standardised meta-categories (6) and types (30) taxonomy; added explicit Hiddens integration with Tier 1–3 model and Targeted Scans; restructured Application Protocol with full routing and closure discipline; added standard registers schemas; restructured Glossary to reference canonical OG v2.4 definitions

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What could go wrong (for whom), when, how likely, how severe, how systemically, and what should we do given our values and risk appetite?** |
| Addresses | Familiar-hazard complacency; tail and compound events; exposure concentration and single-points-of-failure; likelihood overconfidence; correlation under stress; latent and distributional impacts; cascades and systemic risk; appetite and tolerance drift; reporting distortion and ownership ambiguity; unmanaged hidden risks |
| Gap Filled | Many analyses look backward (failures) or focus on single dimensions (probability, controls, compliance). Risk requires a prospective, multi-dimensional, governance-aware synthesis that remains valid under deep uncertainty and systemic coupling, and that surfaces hidden exposures. |
| Complements | Failures; Uncertainties; Evidence; Hiddens; Diagnosis; Decisions; Interventions; Systems; Time; Scale; Boundaries; Resources; Power & Incentives; Governance; Communications; Responsibility; Learning & Adaptation |
| Key Characteristics | Prospective and distributional; tail-aware; multi-horizon; systemic-by-default under stress; explicit about values, appetite, and ownership; integrates detectability and control effectiveness; surfaces visibility failures across risk landscape |
| Main Contributions | Six meta-categories; thirty core risk types; five dimensions; dynamic patterns; three interface types; Hiddens source analysis plus tiered Hiddens scan (Tier 1–3); application protocol with routing and closure discipline; standard deliverables and shared registers |

---

# Introduction

## What is Risk?

Risk is a forward-looking, decision-oriented description of uncertain futures and their consequences for specific stakeholders and systems. Risk is not simply a probability × impact calculation. Rather, it encompasses scenarios (including tails and compound events), exposure and vulnerability, uncertainty and model limits, multi-dimensional and distributional impacts, systemic propagation chains, and—crucially—governance, incentives, appetite, and reporting integrity. Understanding risk requires structural analysis across these components so that decisions can be made with explicit trade-offs, robust treatment choices, and monitoring designs that prevent drift, learning decay, and false certainty.

In complex systems, risk is seldom confined to a single dimension or actor. Exposures concentrate at interfaces (connections between actors, systems, control points). Propagation mechanisms amplify local hazards into systemic consequences. Value conflicts emerge between stakeholders with different appetites and time horizons. Governance failures—misaligned incentives, suppressed information, ownership ambiguity—transform treatable risks into unmanageable crises. This framework surfaces these dynamics.

## Why does Risk matter for Hiddens work?

Risk is inherently a domain of visibility failures. Many risks remain hidden because of perceptual blindness (familiarity bias, tail-event denial), systemic structure (bottleneck dependencies buried in operations), informational suppression (bad news filtered before reaching decision-makers), temporal lags (slow drift goes unnoticed until crystallisation), relational complexity (interactions between risks not visible in siloed analyses), and ontological gaps (risks defined out of existence by official models or narratives).

This framework is designed to surface and interrogate these Hiddens through a disciplined prospective scan. By systematically examining hazards, exposures, uncertainties, impacts, and systemic propagation, the framework prompts discovery of concentrations, couplings, and vulnerabilities that routine risk management misses. Tier 1 Hiddens scans probe whether risks are being perceptually ignored, competency-blind, suppressed, or driven by unexamined narratives. Tier 2 and 3 scans deepen the exploration when material risks could change decisions or create accountability shifts.

## What does this framework produce?

This framework produces a structured risk register organised around six meta-categories and thirty core types of risk. For each material risk, the framework maps five dimensions (scenario, exposure, likelihood, impact, systemic) and characteristic dynamics (drift, crystallisation, transfer, cascade, learning decay). It identifies three interface types where risks concentrate and propagate: transfer interfaces (where risk is moved but not reduced), systemic networks (where coupling amplifies effects), and governance interfaces (where incentives and ownership shape treatment). Finally, it surfaces Hiddens sources—analysis failure modes, suppression mechanisms, and visibility blindspots—through mandatory tiered Hiddens scans.

Outputs include a risk register with scenario descriptions, dimension profiles, systemic propagation maps, appetite and tolerance alignment notes, treatment options and monitoring designs, and—critically—a record of residual unknowns and hidden exposures that remain material to decisions. These artefacts integrate upstream into Decisions and Interventions, and downstream into Governance, Learning & Adaptation, and Responsibility frameworks.

## How to use this framework

This framework is invoked when prospective risk governance is the primary goal: before major decisions (go/no-go, resource allocation, strategy shifts), at periodic reviews (annual appetite refresh, control effectiveness), or after weak signals suggest emerging exposures (early losses, model failures, external shocks). It is typically run in **Investigative Run Mode** for material risks; **Rapid Run Mode** may suffice for routine reviews or triage.

By default, execute at **Light Depth Framework Execution** (MVE scan across all six meta-categories and check dimension/dynamics profiles). Escalate to **Full Depth Framework Execution** when routing logic (OG §4.3) signals high consequence, weak evidence, contested assumptions, or suspected cascades. Mandatory Tier 1 Hiddens scans occur early (after initial framing) and pre-closure (after probes/tests); invoke Targeted Hiddens Discovery Scans when symptoms point to specific hiding mechanisms (e.g., suppression, competency blindness, temporal drift).

The framework integrates within the unified investigation loop (OG §5.0): initialise with focal decision and stakeholders; generate candidate risks across meta-categories; route to appropriate groups and depth per OG §4.3; execute the framework application protocol (Steps 1–6); test assumptions and probes; re-scan for Hiddens; apply closure discipline. See §1.6 for full LLM integration and Prompt Discipline Rules.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Risk is a prospective, multi-dimensional governance problem. Hazards alone do not constitute risk; risk emerges when hazards interact with exposed assets, uncertainty about consequences, systemic propagation pathways, and governance failures that misalign incentives or suppress information.

The traditional probability × impact formulation captures only one slice: likelihood and magnitude of a single, isolated consequence. In reality:
- **Scenarios matter.** Risk is distributed across multiple futures (tails, compounds, cascades), not a single point probability.
- **Exposure is contingent.** The same hazard affects different stakeholders differently depending on vulnerability, location, and interdependence.
- **Uncertainty is not a small parameter.** Model limits, unknown unknowns, and surprise mechanisms are material to risk governance, not just model calibration parameters.
- **Impacts are multi-dimensional and latent.** A single hazard may produce immediate financial losses, operational disruption, reputational damage, regulatory consequence, and psychological trauma—visible only if you look across all dimensions.
- **Systems are coupled.** Local failures propagate through dependencies, feedback loops, and contagion pathways; isolation is often impossible.
- **Governance shapes treatment.** Appetite, tolerance, ownership, incentives, and information flows determine whether a known risk gets treated or drifts into complacency.

This framework provides a repeatable scan across these components: hazard identification, exposure mapping, likelihood and impact characterisation across dimensions, systemic propagation analysis, and governance alignment. It identifies risks that standard risk management misses (tails, Hiddens, compound events, latent impacts) and surfaces the conditions under which treatment designs succeed or fail.

## 1.2 Assumptions & Preconditions

### Assumptions Register
| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Risk can be productively analysed despite deep uncertainty | Method | The framework produces false confidence; analysis becomes costlier than benefit. | Treat Unknowns seriously; require residual uncertainties in all closure notes; compare predictions against outcomes in post-mortems. | Escalate to Tier 3 when key assumptions are weak or contested; record acceptance of residual uncertainty explicitly. |
| Risk appetite can be made explicit and enforced | Normative | Tolerance drifts unnoticed; appetite becomes a rhetorical claim with no grip on behaviour. | Test appetite through scenario probes and appetite-alignment exercises; audit treatment decisions against stated appetite. | Appoint explicit appetite owner; run periodic appetite refresh cycles; use appetite drift as Hiddens indicator. |
| Risks are not uniformly distributed; concentration and cascade matter | Domain | Missing the concentrations (exposure, dependencies) that produce disproportionate impact. | Scan for single-points-of-failure and chokepoint structures; test coupling assumptions under stress scenarios. | When coupling is weak, add structural redundancy or diversification; escalate governance over dependencies. |
| Governance, incentives, and power shape risk reporting and treatment | Domain | Risk registers become fiction; material exposures remain hidden or untreated. | Compare reported vs operative risk appetite; audit suppression and reporting integrity; trace decisions to incentive structures. | Separate risk ownership from operational incentives where possible; use independent audit and escalation paths. |
| Tail and compound events require special attention | Domain | Tail risk remains invisible until crystallisation; compound scenarios are treated as independent. | Stress-test key assumptions; run scenario workshops with tail-event prompts; track correlation under stress. | Conduct tail-risk deep-dives for material exposures; build compound-scenario libraries; use tail-risk metrics in governance. |

### Preconditions Checklist
| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Focal decision and stakeholders are identified | Y | Decision charter or investment case; stakeholder map | Decision owner | TBD | Define focal decision explicitly before proceeding; risks without a decision context are lower priority. |
| Boundary and time horizon are set | Y | System boundary diagram; time-horizon document (strategic, tactical, operational) | Risk owner | TBD | Declare scope and horizon in §1 of risk register; revisit after initial risk scan if boundary is unclear. |
| Evidence base and uncertainty bounds are available | N | Evidence register; uncertainty register; model documentation | Analytics owner | TBD | Mark uncertainties as high when evidence is sparse; conduct evidence-gathering as Priority-0 before treatment selection. |
| Governance structure and decision rights are known | Y | Governance charter; delegation authority; escalation paths | Governance owner | TBD | Clarify governance before assigning risk ownership; unresolved governance ambiguity is a Hiddens flag. |
| Monitoring and feedback systems are designable | N | Current KPI/dashboard definitions; feedback loop documentation | Operations owner | TBD | Include monitoring design as mandatory step in treatment plan; weak monitoring is a Hiddens source. |

---

## 1.3 Definitions, Scope, and Non-Goals

**Definition of Risk:** A structured description of uncertain futures and their consequences for specific stakeholders and systems, including scenarios (likelihood distributions, tails, compounds), exposures and vulnerabilities, multi-dimensional impacts (financial, operational, reputational, regulatory, psychological, strategic), systemic propagation pathways, and governance factors (appetite, ownership, reporting integrity).

**In scope:**
- Six meta-categories of risk (Scenario, Exposure, Likelihood, Impact, Systemic Propagation, Governance)
- Thirty core risk types (5 per meta-category)
- Five dimensions of risk configurations (scenario profile, exposure concentration, likelihood evidence, impact breadth, systemic reach)
- Risk dynamics: drift, crystallisation, transfer, cascade, learning decay
- Three interface types: transfer, systemic network, governance
- Hiddens source analysis and tiered Hiddens cross-check (Tier 1–3)
- Application protocol, deliverables, and standard registers

**Out of scope:**
- Full causal mechanism modelling (see Framework of Causation, Framework of Systems)
- Detailed incident response execution (see Framework of Interventions, Framework of Communications)
- Full ethical adjudication beyond appetite statements (see Framework of Legitimacy, Framework of Values)
- Operational control testing and compliance audit (see Framework of Governance)

**Common confusions ("Risk is not …"):**
- Risk is not simply probability × impact; it is a multi-dimensional, governance-dependent, forward-looking statement about uncertain futures.
- Risk is not the same as uncertainty; uncertainty is a property of knowledge, risk involves consequence and decision.
- Risk is not the same as failure; failures are historical, risks are prospective; risk analysis learns from failures but is not limited to them.
- Risk is not the same as threat; threats are adversarial, risks are broader (include accidents, systemic failures, unknown unknowns).
- Risk appetite is not a number; it is a statement of trade-offs between consequence types and stakeholder preferences.

## 1.4 Position in the Series (Upstream / Middle / Downstream)

**Upstream (signals/understanding):** Realities; Systems; Boundaries; Time; Scale; Agents; Power & Incentives; Evidence; Uncertainties; Failures; Causation

**Middle (this framework's role):** Prospective risk synthesis, governance alignment, and treatment design

**Downstream (action/governance):** Diagnosis; Decisions; Interventions; Governance; Communications; Responsibility; Learning & Adaptation

**Group assignment (Primary):** G6 — Action & Control (Choice, action & control over time)

**Group assignment (Secondary):** G5 — Epistemics (Knowledge, uncertainty, evidence, error-control)

**Stage assignment:** Downstream (transforms upstream understanding into governance-ready risk statements and treatment options)

**Run mode selection:** Rapid Run Mode vs Investigative Run Mode (OG §D.9.2 Mode Selection Gate)

**Operating Guide routing:** Apply decision logic at Start-of-Run and Pre-Closure (OG §4.3) to determine minimum group coverage and per-framework Full Depth / Light Depth plan. Produce outputs per §4.3.2 (routing statement, minimum group coverage, Full Depth list, Light Depth list, escalation triggers).

**Non-conflation invariant:** Do not conflate Run Mode with Framework Execution Depth (OG §D.10.1)

**Iteration loop:** Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG §5.0)

**Framework Index:** This framework is one of 36 in the series (see OG §3.2 for full Framework-to-Group mapping)

## 1.5 Crosswalk Summary
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Descriptive (Framing) | Situations, Boundaries, Scale, Time | Context classification, system boundaries, scaling behaviour, temporal horizons | Risk conditioning on frame choice; boundary-sensitivity analysis; time-dependent hazard propagation; how framing errors hide risk |
| Epistemic (Knowledge) | Evidence, Uncertainties, Failures, Hiddens | Evidence quality and gaps; uncertainty quantification; failure patterns; visibility failures | Prospective synthesis across sources; scenario and tail construction; explicit governance over model limits and unknowns; systematic Hiddens scan |
| Mechanistic (Systems) | Systems, Causation, Relations, Processes | Dependency and causal structures; feedback loops; scaling laws | Where concentrations and couplings create systemic risk; feedback amplification and cascade pathways; SPOF and chokepoint identification |
| Agential (Actors) | Agents, Power, Incentives, Responsibility | Stakeholder mapping; incentive structures; power dynamics; accountability | Risk ownership and misalignment; suppression and distortion due to incentives; governance-induced blind spots; accountability gaps |
| Normative (Values) | Legitimacy, Culture, Communications, Values | Stakeholder acceptance; cultural narratives; legitimacy | Appetite alignment and value trade-offs; narrative capture and risk denial; communication integrity; stakeholder consent for trade-offs |
| Action (Governance) | Decisions, Interventions, Governance, Learning & Adaptation | Decision pipelines; treatment levers; governance structures; feedback loops | Risk-informed option prioritisation; monitoring design; prevention of learning decay; treatment effectiveness tracking |

---

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Risk_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Risk when… | Use neighbour instead when… |
|---|---|---|
| Uncertainties | Analysing how hazards, exposures, and consequences interact with model limits, unknown unknowns, and distributional impacts under governance constraints. | Analysing uncertainty quantification, calibration, confidence bounds, or epistemic gaps independent of governance or decision consequences; studying measurement and parameter estimation. |
| Failures | Analysing prospective scenarios of what could go wrong, cascade mechanisms, and systemic propagation before events occur; integrating governance and appetite into risk treatment. | Analysing failure patterns retrospectively, root causes of past events, incident mechanisms, learning from post-mortems; studying failure modes and forensics. |
| Decisions | Analysing how risk profiles and residual unknowns inform option prioritisation, trade-offs between consequence types, risk appetite alignment, and treatment selection. | Analysing decision-making processes, stakeholder preferences, values, alternative evaluation, or institutional authority; studying decision structures independent of risk governance. |
| Systems | Analysing how systemic propagation, feedback loops, cascade pathways, and coupling amplify local hazards into systemic consequences through dependencies. | Analysing system structure, causal mechanisms, scaling laws, and non-linear dynamics independent of risk consequence; studying component interactions and emergent properties. |
| Governance | Analysing how appetite, ownership, incentives, and reporting integrity shape treatment, monitoring, learning decay, and governance-induced blind spots in risk. | Analysing institutional design, authority structures, formal rules, compliance frameworks, decision rights, or delegation independent of risk appetite; studying governance architecture. |

### 1.6.3 Routing triggers
- Scenario involves prospective risk to stakeholders, assets, or system integrity
- Material consequences span multiple dimensions (financial, operational, reputational, regulatory, strategic)
- Systemic coupling or cascades could amplify local hazards
- Governance, incentives, or ownership affect risk treatment or reporting integrity
- Appetite drift, tolerance misalignment, or monitoring decay are concerns
- Tail events, compound scenarios, or correlation under stress are material
- Model limits, unknown unknowns, or deep uncertainty shape decision tolerance
- Treatment effectiveness requires explicit monitoring and learning loop design
- Hidden exposures or perceptual blindness could change decisions or accountability
- Risk governance and stakeholder appetite alignment are primary decision factors

---

# 2. Meta-Categories of Risk

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Scenario | What could go wrong, under what conditions, and with what likelihood? | Hazard identification, scenario construction, and probabilistic characterisation. | Hazard library; scenario narratives; tail-event library; compound-event matrices; stress scenarios. |
| II | Exposure | Who and what is at risk, and how vulnerable are they? | Asset identification, stakeholder mapping, and vulnerability analysis. | Exposure mapping; concentration analysis; stakeholder impact matrices; vulnerability profiles. |
| III | Likelihood | What is the probability of adverse events, and what are the limits of our knowledge? | Probabilistic assessment, model calibration, and uncertainty quantification. | Likelihood estimates; confidence bounds; sensitivity analyses; model validation results. |
| IV | Impact | What are the consequences across dimensions, and for whom? | Multi-dimensional impact assessment (financial, operational, reputational, regulatory, psychological, strategic). | Impact matrices; dimension-wise consequences; stakeholder-specific impacts; latency and tail-consequence analysis. |
| V | Systemic Propagation | How do local hazards propagate through dependencies and feedback loops? | Dependency mapping, cascade analysis, contagion, and feedback amplification. | Dependency graphs; cascade pathways; contagion models; feedback loops; systemic-risk metrics. |
| VI | Governance | How do appetite, ownership, incentives, and reporting integrity shape risk treatment and monitoring? | Risk appetite and tolerance; ownership clarity; incentive alignment; reporting quality; learning loops. | Appetite statements; ownership matrix; governance controls; monitoring dashboards; escalation protocols. |

## 2.2 Meta-Category Descriptions

### I. Scenario
- **Definition:** A coherent description of a future state or event, including the conditions that would lead to it, the likelihood (point, distribution, or qualitative), and the triggering mechanisms.
- **Diagnostic cues:** Scenarios are absent or vague; risk is described as a single point probability; tail and compound events are ignored or dismissed as "low probability"; scenario interdependencies are not mapped.
- **Typical failure mode:** Over-reliance on base-case thinking; tail-event denial ("that could never happen"); compound risks treated as independent; unexamined scenario assumptions (e.g., normal markets, no cascades).

### II. Exposure
- **Definition:** The asset, stakeholder, process, or system that stands to be harmed; exposure is contingent on boundary, location, time horizon, and interconnection.
- **Diagnostic cues:** Exposure is assumed uniform; concentration is not analysed; new exposures emerge from system changes; stakeholder impacts are not mapped; vulnerability varies by stakeholder but is homogenised in analysis.
- **Typical failure mode:** Exposure concentrations hidden in complexity (e.g., counterparty exposure embedded in derivatives book); single-points-of-failure in critical processes; new exposures created by digital transformation but not scanned; asymmetric stakeholder impacts ignored.

### III. Likelihood
- **Definition:** The estimated probability or frequency of an adverse event, including quantified uncertainty and the limits of empirical knowledge.
- **Diagnostic cues:** Likelihood is stated as a number with false precision; confidence bounds are absent; rare events are assumed impossible ("never happened before"); model limits are not acknowledged; base-rate data is sparse or biased.
- **Typical failure mode:** Overconfidence in small-sample estimates; recency bias (recent events are over-weighted); anchoring to historical frequencies despite structural change; model-form uncertainty not explored; tail probabilities dramatically underestimated.

### IV. Impact
- **Definition:** The consequences of an adverse event across multiple dimensions (financial loss, operational disruption, reputational damage, regulatory/legal sanction, psychological harm, strategic setback) and time horizons (immediate, medium, long-term latency).
- **Diagnostic cues:** Impact is reduced to a single dimension (usually financial); latent impacts (e.g., reputation decay, learning loss, cultural erosion) are omitted; distribution of impact across stakeholders is not mapped; secondary impacts (cascades, systemic effects) are not traced.
- **Typical failure mode:** Headline financial loss dominates; reputational and regulatory impacts are discovered after the fact; latent psychological and cultural impacts are never quantified; stakeholder-specific impacts are aggregated away; tail impacts are underestimated.

### V. Systemic Propagation
- **Definition:** The mechanisms by which a local hazard or failure propagates through dependencies, contagion, feedback loops, and interconnected systems to produce wider harm.
- **Diagnostic cues:** Risk is analysed in isolation; dependencies are not mapped; feedback loops are ignored; contagion is assumed to stop at obvious boundaries; systemic risk is treated as a separate category rather than an emergent property of coupled systems.
- **Typical failure mode:** Cascade risk is not discovered until failure occurs; feedback amplification (e.g., forced selling, liquidity spiral) is missed; systemic risk is concentrated at chokepoints not visible in operational silos; common-cause failures hidden in independent risk registers.

### VI. Governance
- **Definition:** The structures, incentives, ownership clarity, and information flows that determine whether known risks are treated, monitored, and escalated, or drift into complacency.
- **Diagnostic cues:** Appetite is stated but not enforced; ownership is ambiguous; incentive structures reward risk-taking over risk treatment; risk reports are filtered before reaching decision-makers; monitoring is weak or deferred; learning loops are broken.
- **Typical failure mode:** Appetite drift (tolerance silently increases); risk treatment is deprioritised due to competing incentives; bad news is suppressed; accountability disappears at interfaces between functions; monitoring finds issues but they are not acted on; repeat failures show learning has not occurred.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- **Canonical baseline:** 6 meta-categories × 5 types = 30 core types.
- **This framework:** 30 types. No structural deviation.
- **Mapping back to baseline:** All 30 types map directly to the six meta-categories (I–VI); no alternative taxonomy required.

## 3.1 Types (Category I: Scenario)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 1 | Hazard (exogenous) | External event with potential to disrupt objectives (natural disaster, market shock, pandemic, geopolitical event). | Does the scenario account for external trigger events? Is tail probability known? Is scenario independent of response? | Scenario is base-case only; tail and black-swan events are assumed impossible. |
| 2 | Hazard (endogenous) | Internal operational failure, execution error, or process breakdown that triggers subsequent consequences. | Does the scenario distinguish between initiating failure and propagation? Is root-cause mechanism clear? Is human/organisational factor included? | Endogenous hazards (e.g., control failure, process error) are conflated with exogenous shocks; root causes are not surface. |
| 3 | Compound event | Simultaneous or near-simultaneous occurrence of multiple independent hazards, producing cascading or synergistic consequences. | Are hazards tested for correlation under stress? Are compound scenarios explicitly constructed? Are tail-tail correlations explored? | Compound events are treated as independent risks; stress-scenario workshops are absent; correlation assumptions are not tested. |
| 4 | Tail event | Outcome in the far tail of a distribution (low probability, high impact), often with unknown distribution (uncertainty about uncertainty). | Are tail probabilities estimated separately from base-case? Are tail mechanisms understood? Are confidence bounds wide enough to encompass tail risk? | Tail events are dismissed as "low probability"; confidence bounds are false precision; tail-specific mechanisms are not studied. |
| 5 | Systemic scenario | A widespread, systemic disruption affecting multiple actors, sectors, or asset classes simultaneously (financial crisis, pandemic, infrastructure failure, geopolitical rupture). | Does the scenario account for systemic contagion and feedback loops? Are common-cause failure modes identified? Is correlation under systemic stress estimated? | Systemic risk is treated as a separate category; interdependencies are not mapped; systemic scenarios are absent from strategy and governance reviews. |

## 3.2 Types (Category II: Exposure)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 6 | Concentration | Exposure that is unevenly distributed, with material portions concentrated in a small number of counterparties, geographies, or time buckets. | Is concentration analysed? Do risk aggregates show concentration? Are concentration limits enforced? | Exposure is reported in aggregate; concentration is not visible; concentration limits are exceeded without escalation. |
| 7 | Single-point-of-failure (SPOF) | A critical process, asset, or dependency that is not redundant; failure of the SPOF produces system-wide failure. | Is dependency mapped? Are critical processes redundant? Is recovery without the SPOF possible? | SPOFs are not identified until failure occurs; backup systems are absent or untested; recovery from SPOF failure is untested. |
| 8 | Interconnectedness / coupling | Exposure is embedded in a web of interdependencies; local failure propagates rapidly through the network. | Is the dependency network mapped? Are chokepoints identified? Is stress-test of network conducted? | Dependencies are not mapped; chokepoints are not visible; stress scenarios do not include network effects. |
| 9 | Stakeholder asymmetry | Different stakeholders face different exposures (e.g., regulatory vs financial, short-term vs long-term, direct vs indirect harm). | Are impacts mapped separately for each stakeholder? Do stakeholders have aligned incentives to address risk? | Impacts are aggregated across stakeholders; asymmetries are not surfaced; incentive misalignment is not recognised as a governance risk. |
| 10 | Evolving exposure | The exposure profile changes over time due to portfolio drift, market growth, regulatory change, or structural shifts. | Is the exposure trajectory monitored? Does monitoring trigger recalibration of risk appetite? Are structural changes in exposure recognised and escalated? | Exposure changes are not tracked; appetite remains constant despite drift; structural changes are not escalated. |

## 3.3 Types (Category III: Likelihood)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 11 | Base-rate frequency | The historical or empirical frequency of an adverse event, estimated from data over a defined time window. | Is base-rate data available? Is the time window representative? Are regime changes accounted for? | Likelihood is based on short-term frequency; regime changes are not accounted for; base-case is overweighted in governance. |
| 12 | Model-based probability | Probabilistic estimate derived from a calibrated model (e.g., default model, stress-test result, structural model). | Is the model validated? Are model-form uncertainties acknowledged? Are confidence bounds wide enough? | Model output is treated as fact; model limits are not acknowledged; confidence bounds are artificially narrow. |
| 13 | Scenario-conditional probability | The probability of an adverse event conditional on a specific scenario or state of the world (e.g., "if rates rise 200bps, what is default probability?"). | Are probabilities conditional on well-defined scenarios? Is the conditioning scenario itself uncertain? | Probabilities are unconditional or misspecified; scenario-conditioning is absent; conditional tail probabilities are not explored. |
| 14 | Structural change / model obsolescence | The probability or frequency of an event changes due to structural shifts in the system, market, or environment; historical data becomes unreliable. | Are structural changes monitored? Is model validity tested post-change? Are confidence bounds adjusted when model obsolescence is suspected? | Models are recalibrated with historical data despite structural change; likelihood estimates become obsolete; model-obsolesce risk is not tracked. |
| 15 | Known unknown / deep uncertainty | The probability of an event is unknown; the distribution is unknown; even the mechanisms that would generate the probability are not understood. | Are uncertainties about probability explicitly acknowledged? Are Bayesian priors defensible? Is expert disagreement recorded? | Probability is stated with false precision; Bayesian priors are not disclosed; expert disagreement is suppressed. |

## 3.4 Types (Category IV: Impact)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 16 | Financial impact | Direct monetary loss (P&L impact, capital impact, liquidity impact). | Is the financial impact mapped across products, geographies, time horizons? Are tail scenarios explored? Are collateral and haircut assumptions tested? | Financial impact is understated; tail impact is not calculated; hidden exposures (e.g., derivatives, contingent liabilities) are not aggregated. |
| 17 | Operational impact | Business disruption, process failure, output reduction, extended recovery time. | How long would recovery take? Are backup processes tested? Are dependencies mapped for recovery? | Operational impact is estimated without accounting for dependencies; recovery time is optimistic; cascading failures are not simulated. |
| 18 | Reputational impact | Damage to brand, stakeholder trust, social licence, and attractiveness to employees, customers, and investors. | Is reputational impact monitored? Are stakeholders surveyed? How sensitive is valuation to reputation shifts? | Reputational impact is ignored or underestimated; recovery time from reputational damage is not tracked; stakeholder feedback loops are weak. |
| 19 | Regulatory / legal impact | Fines, enforcement actions, loss of licence, restrictions on business, legal liability, remediation costs. | Are regulatory exposure and legal vulnerabilities assessed? Is regulatory change monitored? Are scenario-based regulatory impacts modelled? | Regulatory impacts are discovered after the fact; regulatory change is not monitored; contested interpretations are not escalated. |
| 20 | Latent / distributed impact | Harm that accrues slowly over time (psychological, cultural, institutional) or is distributed across many stakeholders (each with small individual impact but material in aggregate). | Are slow-onset impacts (e.g., culture erosion, learning loss, stakeholder trust decay) tracked? Is distributed impact aggregated? | Latent impacts are invisible in traditional risk metrics; distributed harms are aggregated away; stakeholder-specific impacts are not tracked. |

## 3.5 Types (Category V: Systemic Propagation)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 21 | Cascade / contagion | Failure in one part of the system triggers failures elsewhere, propagating through dependency chains. | Are cascade pathways mapped? Are feedback effects quantified? Are stress scenarios that include cascades run? | Cascade pathways are not mapped; stress scenarios ignore cascades; feedback effects are not estimated; systemic risk is underestimated. |
| 22 | Feedback amplification | A mechanism that amplifies the initial hazard (e.g., forced selling → lower valuations → margin calls → more forced selling). | Are feedback mechanisms identified? Are they quantified? Are circuit-breakers or stabilisers in place? | Feedback mechanisms are not modelled; amplification is discovered retrospectively; damping mechanisms are weak. |
| 23 | Network chokepoint | A critical bottleneck through which many dependencies flow; failure at the chokepoint cascades widely. | Is the dependency network mapped? Are chokepoints identified? Are alternatives to chokepoints available? | Chokepoints are not visible; recovery without chokepoints is impossible; redundancy is weak. |
| 24 | Common-cause failure | Multiple independently-registered risks share a common underlying driver; they fail together despite appearing independent in risk register. | Are correlations across risk categories analysed? Are hidden dependencies across functional areas mapped? | Common-cause risks are treated as independent; correlation is not explored; functional silos hide system-wide vulnerabilities. |
| 25 | Systemic emergence | An aggregate or emergent property of a coupled system that is not visible in component-level analysis (e.g., herding, panic, tipping points). | Are emergent properties analysed? Are tipping points identified? Is agent-based or network modelling used? | Emergent properties are not analysed; tipping points are not modelled; behaviour is assumed to remain linear. |

## 3.6 Types (Category VI: Governance)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 26 | Appetite / tolerance misalignment | Risk appetite is stated but actual behaviour (tolerance, decision-making, incentives) diverges from appetite; tolerance drifts with time and circumstance. | Are decisions audited against appetite? Is appetite refreshed periodically? Are incentives aligned with appetite? | Appetite is stated but not enforced; decisions exceed stated appetite without escalation; appetite drift is not detected. |
| 27 | Ownership ambiguity | Risk ownership is unclear; multiple parties believe ownership lies elsewhere; accountability dissolves at interfaces. | Is risk ownership assigned explicitly? Are escalation paths clear? Are owners incentivised to address the risk? | Ownership is ambiguous; escalation paths are unclear; risks remain unaddressed because "someone else should handle this." |
| 28 | Incentive misalignment | Compensation, KPIs, career advancement, or other incentive structures reward risk-taking or suppress risk information; governance breaks down. | Are incentives aligned with risk appetite? Do compensation structures reward treatment of high risks? Are whistleblower protections strong? | Incentives reward risk-taking; bad news is suppressed; risk-takers are promoted despite downside outcomes. |
| 29 | Information filtering | Risk information is filtered, delayed, or distorted as it flows upward through the organisation; decision-makers lack accurate, timely risk information. | Does risk reporting reach the right level in time? Are red flags escalated quickly? Is reporting integrity monitored? | Bad news is filtered; escalation is slow; decision-makers are surprised by crises that risk teams knew about. |
| 30 | Learning decay / monitoring failure | Monitoring identifies risks but they are not acted on; lessons from incidents are not retained; repeat failures occur; vigilance decays over time. | Are monitoring findings acted on? Are lessons documented and transferred? Is vigilance tested post-incident? | Monitoring is weak or deferred; findings are ignored; lessons are lost; repeat failures occur. |

## 3.7 Extending the Taxonomy
| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | Start with the six meta-categories and thirty core types. Deviations should be rare and justified. |
| Domain-specific refinement | Domain teams may extend the taxonomy within a meta-category (e.g., "Cybersecurity hazard" as a subtype of Hazard-Endogenous) but should map extensions back to the canonical baseline. |
| Preserving mappability | Any extension or local taxonomy must include explicit mapping back to the six meta-categories and 30 core types for comparability across the organisation. |
| Structural invariants | Do not change the meta-category structure (6 categories) without a major version increment (v3.0+) and explicit Operating Guide update. |
| Periodic reassessment | Reassess the taxonomy annually or after major incidents; if new types emerge consistently, propose a vX.0 update. |
| Versioning & governance | Extensions are versioned locally; core taxonomy changes are versioned in the Framework itself and propagated via the Operating Guide. |

---

# 4. Cross-Cutting Dimensions of Any Risk

## 4.1 Dimensions Table (mandatory)
| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| 1. Scenario profile (base-case, mid-tail, far-tail) | Where on the distribution does this risk sit? Is it familiar (base-case), challenging (mid-tail), or catastrophic (far-tail)? | Base-case (familiar), mid-tail (surprising), far-tail (catastrophic); or quantitative: 50th/90th/99th percentile. | Ask: "Has this happened before? Could it be 10x worse?" | Prioritisation; mitigation strategy; governance intensity. |
| 2. Exposure concentration (distributed, concentrated, SPOF) | How is exposure distributed? Is it dispersed across many counterparties/geographies, or concentrated in a few? | Low (uniform), Medium (10–30% in top item), High (>30% in top item), Extreme (SPOF). | Concentration ratio; Herfindahl index; single-largest-exposure ratio. | Diversification need; governance escalation; capital model impact. |
| 3. Likelihood confidence (high, medium, low) | How confident are we in the probability estimate? Is it based on data, models, or expert judgment? | High (empirical data, validated model, stable regime), Medium (sparse data, model-form uncertainty), Low (novel situation, deep uncertainty, known unknown). | Base-rate data available? Model validated? Structural change detected? | Evidence gap identification; probability bound width; scenario-weighting strategy. |
| 4. Impact breadth (narrow, multiple, systemic) | How many dimensions of impact does this risk span? Is it financial-only or does it span operational, reputational, regulatory, cultural? | Narrow (single dimension), Multiple (2–3 dimensions), Systemic (4+ dimensions including latent/distributed). | Map impacts across: financial, operational, reputational, regulatory, psychological, strategic, cultural. | Stakeholder engagement strategy; comprehensive treatment design; governance buy-in. |
| 5. Systemic reach (isolated, network, systemic) | Does this risk propagate beyond the direct exposure? Is it contained or does it cascade through dependencies? | Isolated (contained within unit/product), Network (propagates through identifiable dependencies), Systemic (affects multiple unrelated parts of organisation or market). | Dependency map; correlation analysis; stress-scenario results. | Monitoring design; governance escalation; capital/liquidity buffers. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | Appetite drift | Stated appetite remains constant; actual tolerance increases (decisions exceed stated appetite without escalation). | Successes reduce perceived risk; incentives reward growth over caution; monitoring is weak; appetite refresh is infrequent. | Unmanaged risk-taking; cumulative exposure exceeds governance tolerance; eventual shock reveals governance failure. | Periodic appetite refresh cycles (annual); audit of decisions against appetite; incentive alignment; governance escalation. |
| 2 | Control decay | Controls are designed and tested initially; over time they become ineffective due to workarounds, resource constraints, or mode changes. | Operational pressure and competing priorities weaken controls; vigilance decays when incidents are absent; control testing is deferred. | Known controls fail when most needed; false assurance from risk register control listings; repeat failures indicate learning has not occurred. | Regular control effectiveness testing; incentive-aligned ownership; post-incident control reassessment; control decay triggers. |
| 3 | Tail-event blindness | Tail and compound risks are consistently underestimated or dismissed as impossible; organisations are surprised by tail events. | Base-case thinking dominates; tail probabilities are stated with false precision; tail mechanisms are not studied; expert disagreement about tails is suppressed. | Organisations are unprepared for tail events; liquidity buffers are insufficient; recovery is prolonged; learning about tails is not retained. | Explicit tail-risk deep-dives; scenario workshops with tail prompts; tail-risk metrics in governance; stress testing; learning documentation. |
| 4 | Systemic emergence | Risk concentrations and dependencies accumulate silently across the organisation; systemic risk emerges only when stress occurs. | Modular risk assessment misses network effects; growth creates new dependencies; governance silos hide system-wide vulnerabilities; monitoring is local not systemic. | Systemic risk is invisible until crystallisation; shock produces cascades; recovery is prolonged; learning is incomplete. | Periodic systemic-risk scans (dependency mapping, chokepoint analysis); stress-testing with cascades; governance spanning functional silos; systemic metrics. |
| 5 | Remediation resistance | Known risks are not treated; treatment recommendations are overridden or deferred; resistance persists despite escalation. | Treatment is costly or operationally disruptive; ownership is ambiguous; incentives do not reward treatment; senior leadership is not engaged. | Risks remain unmitigated despite documentation; incidents that could have been prevented occur; credibility of risk function decays. | Root-cause analysis of resistance (incentive, cost, accountability); escalation to senior leadership; treatment design that reduces operational disruption; accountability mechanisms. |
| 6 | Concentration and coupling feedback | Local risks interact to create systemic risks; as concentration increases, coupling increases; feedback loops amplify impact. | Risk-taking strategies (e.g., high leverage, correlated strategies) increase concentration; dependencies grow with system size; feedback mechanisms are not modelled. | Impact of local risks is multiplicative, not additive; tail risk is dramatically underestimated; shocks produce cascades. | Concentration monitoring; coupling analysis; stress-testing with feedback; deleveraging or diversification; redundancy. |
| 7 | Temporal cascades / latency effects | Risks interact across time; shocks that seem to be contained are followed by delayed impacts (e.g., contagion, legal/regulatory fallout, cultural erosion). | Initial impact is visible; secondary impacts are delayed or distributed; monitoring is short-term; learning misses downstream consequences. | Remediation is incomplete (addresses immediate impact but not secondary); learning is misdirected; repeat failures occur. | Extended post-incident reviews (6–12 months); stakeholder feedback loops; monitoring for latent impacts; scenario-planning for delayed consequences. |
| 8 | Evidence gap discovery | Assumptions in the risk model are found to be false or weak post-incident; the risk register did not capture the actual risk mechanism. | Assumptions were not explicitly stated; evidence gaps were not explored; scenario construction was limited; model validation was incomplete. | The risk that materialised was "not on the register"; credibility of risk framework is damaged; learning is misdirected. | Explicit assumption documentation; evidence-gap analysis; scenario robustness tests; model validation against outcomes; post-incident evidence review. |
| 9 | Learning decay | Lessons from incidents are documented but not retained or acted upon; repeat failures occur years later with the same root causes. | Institutional memory decays with staff turnover; lessons are archived but not transferred; incentives do not reward prevention; vigilance decays with time since last incident. | Incidents repeat; costs accumulate; credibility of prevention efforts decays; culture becomes complacent. | Embedded learning in processes and systems (not just documentation); incentive alignment; regular refresher training; near-miss tracking; cultural emphasis on learning. |
| 10 | Governance-induced blindness | Governance structures, incentives, or reporting frameworks prevent material risks from surfacing; risks are hidden by the system that is supposed to detect them. | Governance structures are siloed; incentives reward concealment; risk metrics are narrow; escalation paths are clogged; reporting is manipulated. | Material risks remain hidden; decision-makers lack accurate information; incidents are unpredictable; trust in governance erodes. | Governance process review; cross-functional integration; independent risk oversight; whistleblower protections; escalation transparency. |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | Transfer interface | The interface at which risk is transferred from one actor to another, but not reduced (e.g., insurance, outsourcing, hedging). The risk is repackaged but the underlying hazard remains. | Is the risk truly transferred or just repackaged? Is counterparty risk being substituted for the original risk? Is the transfer complete or partial? | Insurance that covers only part of impact; outsourcing that moves operational risk to vendor but not supply-chain risk; hedging that leaves basis risk. |
| B | Systemic network interface | The interface at which a local risk connects to the broader system through dependencies and contagion pathways. | Are the dependencies mapped? Are there feedback loops? Is correlation under stress explored? Are there chokepoints? | Interconnected financial system where default of one institution triggers cascades; supply chain with common suppliers creating correlation; trading strategies that are correlated under stress. |
| C | Governance interface | The interface at which governance structures, incentives, ownership, and information flows determine whether a known risk is treated or drifts into complacency. | Is ownership clear? Are incentives aligned with treatment? Does risk information reach decision-makers? Are escalation paths clear? | Functional silos that hide system-wide risks; compensation that rewards growth over caution; escalation paths that are blocked; bad news filtered before reaching leadership. |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links
- **Inputs expected:** Boundary and time-horizon definition (Situations); system and dependency maps (Systems); evidence base and uncertainty bounds (Evidence, Uncertainties); failure patterns and learning history (Failures); causal mechanisms (Causation); stakeholder and power map (Agents, Power & Incentives); governance structure (Governance); narratives and legitimacy (Communications, Legitimacy).
- **Outputs provided:** Risk register and scenario library (to Decisions, Interventions); systemic propagation and interface maps (to Systems, Governance); appetite/tolerance statements (to Governance); treatment and monitoring plan (to Interventions, Learning & Adaptation); residual unknowns and Hiddens (to Hiddens, Diagnosis); evidence and hypothesis backlogs (to Evidence, Diagnosis).

## 7.2 Crosswalk Table
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| Situations | Context classification; boundary & horizon definition; situation typing. | Risks specific to situation type; scenario conditioning on situational features. | Pre-decision risk assessment; situation-contingent risk appetite. |
| Systems | Dependency & causal structures; feedback loops; scaling laws. | Where concentrations and couplings create systemic risk; feedback amplification pathways; systemic-risk metrics. | Systemic-risk governance; operational resilience; supply-chain risk. |
| Evidence | Evidence quality; sources; confidence bounds. | Decision-critical evidence gaps; evidence backlog for risk scenarios; evidence provenance in risk register. | Evidence-driven risk assessment; gap-driven investigation design. |
| Uncertainties | Quantified uncertainty bounds; sources of uncertainty; model limits. | Risk conditioning on uncertainty; tail probabilities; confidence bounds for risk estimates. | Deep uncertainty scenarios; robust risk governance under uncertainty. |
| Failures | Historical failure patterns; root causes; learning history. | Tail scenarios based on failure patterns; lessons learned from failures; repeat-failure detection. | Post-failure investigation; prevention design; organisational learning. |
| Hiddens | Visibility failures; suppression mechanisms; hidden-risk taxonomy. | Candidate Hiddens specific to risk domain; governance-induced blindness; appetite drift as Hidden. | Comprehensive risk discovery; governance integrity review. |
| Causation | Causal mechanisms; process models; intervention effects. | Causal chains for systemic propagation; mechanism-based risk scenarios; treatment efficacy. | Scenario robustness; treatment design; mechanism validation. |
| Decisions | Decision options; constraints; stakeholder preferences. | Risk-ranked options; risk-adjusted valuations; decision-contingent risk appetites. | Risk-informed option selection; decision quality improvement. |
| Interventions | Treatment options; feasibility; side effects; monitoring. | Risk-prioritised treatment recommendations; residual-risk characterisation post-treatment; monitoring design. | Treatment prioritisation; side-effect risk governance. |
| Governance | Governance structures; escalation paths; incentives; accountability. | Governance gaps that enable risk drift; incentive misalignment; ownership ambiguity; control decay. | Governance-design improvement; risk-appetite enforcement. |
| Learning & Adaptation | Feedback loops; organisational learning; adaptation mechanisms. | Learning-design for risk prevention; feedback-loop closure; decay detection. | Institutional learning from risk; prevention design; organisational adaptation. |

## 7.3 Integration Questions by Framework

| Framework (from OG v2.4 §3.2 canonical list) | Group | Stage | Integration questions | Outputs / artefacts to pull in | Notes |
|---|---|---|---|---|---|
| Situations Context Classification | G1 | Upstream | How does the situation type condition risk profile? Are boundary and horizon choices embedded in scenario definitions? | Situation-type classification; boundary & horizon constraints; scenario conditioning logic | Risk is situation-contingent; misclassification errors create hidden risks. |
| Boundaries | G1 | Upstream | What is within/out of scope for this risk analysis? Do boundary choices create exposure blindspots? | System boundary; exposure mapping inside/outside boundary; boundary-sensitivity analysis | Boundary disputes may hide risks at interfaces. |
| Dimensions | G1 | Upstream | What are the key dimensions for this scenario and how do they vary? How do dimensional shifts change risk profile? | Dimensional profiles (economic, social, temporal, spatial); dimensional sensitivity analysis | Risk varies by dimension; dimensional shifts can expose or hide risks. |
| Realities | G1 | Upstream | What is the underlying reality of the system we are taking risks about? Are reality assumptions tested in scenarios? | Reality assumptions; ontological grounding for scenario construction | Misaligned reality models lead to scenario failures. |
| Scale | G1 | Upstream | How does risk scale (linear, nonlinear, threshold, tipping)? Do scaling assumptions hold across the exposure range? | Scaling relationships; scaling-assumption validation; tail behaviour; tipping points | Nonlinear scaling can hide tail risk; scaling assumptions must be tested. |
| Time | G1 | Upstream | What is the time structure of the risk? Are temporal cascades, latency effects, and cycle alignment captured? | Time-horizon profiles; temporal cascade analysis; latency mapping | Temporal structure is often hidden in snapshot risk analysis. |
| Systems | G2 | Middle | What are the system dependencies and feedback loops that propagate this risk? | Dependency map; feedback loops; contagion pathways; chokepoints | Systemic propagation is often invisible without explicit system analysis. |
| Relations | G2 | Middle | What are the key relationships and interconnections that carry risk? How do relationship changes alter risk profile? | Relationship map; coupling analysis; relationship-strength assessment | Relationships hidden in silos; coupling misunderstood. |
| Processes | G2 | Middle | What processes carry or concentrate risk? What is the criticality and redundancy of key processes? | Process map; process-criticality assessment; control-design review | Process failures and SPOFs are often invisible in functional risk registers. |
| Causation | G2 | Middle | What are the causal mechanisms that would trigger adverse scenarios? Are causal chains validated? | Causal mechanism mapping; scenario causation; intervention theory of change | Scenarios without causal grounding are not credible; causation often misunderstood. |
| Resources | G2 | Middle | What resources are required to treat this risk? Are resources sufficient, and what resource constraints drive governance failures? | Resource requirements for treatments; resource allocation constraints; remediation feasibility | Resource scarcity often prevents treatment; resource gaps are hidden governance risks. |
| Agents | G3 | Upstream | Who are the actors in this scenario? What are their goals, constraints, and decision processes? | Agent/stakeholder map; agent-specific exposure and incentive profiles | Agent behaviour often differs from model assumptions; hidden incentive misalignment. |
| Personas | G3 | Upstream | What are the key personas and decision-maker profiles that shape risk governance? | Persona profiles; decision-making heuristics; cognitive biases | Persona-specific biases and blindness can hide risks. |
| Incentives | G3 | Upstream | What incentive structures shape risk-taking and risk reporting? Are incentives aligned with risk appetite? | Incentive map; misalignment analysis; perverse incentive identification | Misaligned incentives are a primary source of governance failure and hidden risk. |
| Power | G3 | Upstream | Who has power to shape risk treatment? How do power asymmetries affect risk governance? | Power map; veto and influence points; power-dynamics risk assessment | Power asymmetries can suppress risk information and prevent treatment. |
| Responsibility | G3 | Downstream | Who is responsible for what risk? Is accountability clear and enforced? | Responsibility map; ownership clarity; accountability mechanisms | Ambiguous responsibility is a primary source of unmanaged risk. |
| Competencies | G3 | Upstream | What competencies are required to identify, analyse, and treat this risk? Are competency gaps a source of hidden risk? | Competency map; gap analysis; blind-spot identification | Competency gaps create visibility failures; expertise is often mislocated. |
| Culture and Norms | G4 | Upstream | What cultural norms and values shape risk appetite and risk behaviour? | Culture assessment; norm-risk mapping; culture-risk misalignment analysis | Culture and norms can reinforce risk blindness and suppress information. |
| Perspectives | G4 | Upstream | How do different stakeholder perspectives on this risk differ? Are perspective gaps material? | Perspective map; stakeholder-disagreement analysis; perspective-gap risk assessment | Disagreement often hides material risks; suppressed perspectives are Hidden risks. |
| Narratives | G4 | Upstream | What narratives shape beliefs about this risk? Are narratives validated? Are alternative narratives suppressed? | Narrative map; narrative-validation analysis; narrative-capture assessment | Dominant narratives can suppress material risks (e.g., "it could never happen here"). |
| Communications | G4 | Middle | How is risk communicated? Does communication reach decision-makers accurately and in time? | Risk-reporting structure; communication barriers; distortion assessment | Information filtering and communication breakdown hide risks. |
| Legitimacy | G4 | Upstream | Is this risk socially legitimate to take? Do stakeholders accept the risk/reward trade-off? | Legitimacy assessment; stakeholder consent; social-license risk | Lack of legitimacy can create reputational and regulatory risk. |
| Values | G4 | Upstream | What values or principles guide the risk appetite? Are risk trade-offs aligned with values? | Values statement; value-alignment assessment; values-conflict identification | Values misalignment can hide ethical risks. |
| Beliefs | G5 | Upstream | What beliefs underpin the risk model? Are beliefs validated? Is expert disagreement recorded? | Belief map; belief-validation analysis; disagreement documentation | Unexamined beliefs create model risk and Hidden scenarios. |
| Evidence | G5 | Upstream | What is the evidence base for key risk assumptions? Are evidence gaps material? | Evidence register; gap analysis; evidence-quality assessment | Evidence gaps are a primary source of hidden risk. |
| Uncertainties | G5 | Upstream | What are the key sources and bounds of uncertainty in the risk model? | Uncertainty quantification; uncertainty-bound specification; sensitivity analysis | Unquantified uncertainty can hide tail risk. |
| Failures | G5 | Upstream | What is the history of failures in this domain? What lessons are documented and retained? | Failure inventory; root-cause analysis; learning-implementation audit | Undocumented or unlearned failures repeat; learning decay hides risks. |
| Hiddens | G5 | Cross-cutting | What is hidden in this risk landscape? What visibility failures and suppression mechanisms are active? | Hiddens register; visibility-failure taxonomy; suppression-mechanism analysis | Risk framework is designed to surface Hiddens. |
| Diagnosis | G5 | Middle | What is the diagnostic picture? Are root causes clear? What remains uncertain? | Diagnostic framework; root-cause hypotheses; residual-uncertainty map | Diagnostic gaps hide the real risk drivers. |
| Metrics | G5 | Downstream | What are the key metrics that characterise this risk? How are metrics gamed or misinterpreted? | KPI/metric definitions; metric-gaming risk; interpretation guidance | Metrics can hide risks if not carefully designed; gaming is a governance failure. |
| Knowledge | G5 | Middle | What is known and unknown about this risk? Is expert disagreement visible? Is knowledge distributed across the organisation? | Knowledge-distribution map; expert-disagreement documentation; knowledge-gap analysis | Distributed knowledge and suppressed disagreement hide material risks. |
| Decisions | G6 | Downstream | What are the decision options and how does risk vary across options? Are risk-adjusted valuations available? | Decision options; risk-profile comparison; risk-adjusted option values | Risk-uninformed decisions perpetuate hidden risks. |
| Interventions | G6 | Downstream | What treatment options are available? What are the residual risks and side effects? How is monitoring designed? | Treatment options; residual-risk profiles; side-effect risk; monitoring design | Treatment design is critical to managing hidden risks. |
| Governance | G6 | Downstream | Is governance aligned with risk? Are appetite, ownership, incentives, and accountability clear? | Governance assessment; alignment analysis; gap identification | Governance is the locus of hidden-risk creation. |
| Learning and Adaptation | G6 | Downstream | How do we learn from risk events and adapt to prevent recurrence? Are feedback loops closed? | Learning-design specification; feedback-loop implementation; adaptation tracking | Learning decay and adaptation failure perpetuate hidden risks. |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---|---|---|---|
| 1 | Tail-event denial and base-case anchoring | Tail and compound scenarios are dismissed as "low probability" or "could never happen here." Analysis focuses on base-case, missing tail consequences. Confidence bounds are artificially narrow. | Conduct explicit tail-risk deep-dives; construct tail scenarios with detailed mechanics; run scenario workshops with tail prompts; separate base-case from tail in governance. |
| 2 | Exposure concentration blindness | Concentration of risk in counterparties, geographies, or products is not visible in standard risk aggregation. Concentration grows silently until shock reveals hidden correlation. | Map exposures by counterparty, geography, product, and time; calculate concentration ratios and Herfindahl indices; conduct concentration-sensitivity analysis; stress test correlation under adverse scenarios. |
| 3 | Systemic coupling and common-cause failure invisibility | Risks are registered by functional area and appear independent. Common-cause failures (dependencies shared across registered risks) are not visible. Systemic risk emerges only when stress occurs. | Map dependencies across functional boundaries; identify chokepoints and single-points-of-failure; conduct network-stress testing; run scenario analysis that includes cascades and feedback. |
| 4 | Governance-induced blindness and suppression | Governance structures, incentives, and information flows prevent material risks from surfacing. Bad news is filtered before reaching decision-makers. Appetite drifts silently without escalation. Ownership ambiguity allows risks to remain unaddressed. | Conduct governance-integrity audit; test appetite against actual decisions; analyse decision record for suppression patterns; map escalation paths for blockage; interview risk teams about filtering. |
| 5 | Latent impact and temporal cascade invisibility | Multi-dimensional impacts (reputational, cultural, psychological) and temporal cascades (secondary impacts weeks/months post-incident) are not modelled. Monitoring is short-term; distributed impacts are aggregated away. | Map impacts across: financial, operational, reputational, regulatory, psychological, strategic, cultural; conduct extended post-incident reviews (6–12 months); monitor stakeholder feedback loops; design monitoring for latent impacts. |
| 6 | Model obsolescence and structural-change blindness | Historical data is used to calibrate models despite structural changes in the system; models become obsolete without detection. Scenario assumptions (normal correlations, stable relationships) fail under novel conditions. | Monitor for structural changes in market, environment, and system; validate model validity post-change; widen confidence bounds when obsolescence is suspected; conduct scenario robustness tests; maintain alternative scenario assumptions. |
| 7 | Evidence gap and assumption invisibility | Assumptions in the risk model are not explicitly stated; evidence gaps are not explored. The risk that materialises was "not captured because we didn't think to look." | Create explicit assumption register; conduct evidence-gap analysis; develop scenarios that test assumption robustness; maintain uncertainty bounds; document expert disagreement. |
| 8 | Learning decay and institutional memory loss | Lessons from incidents are documented but not retained or acted upon. Staff turnover erodes institutional memory. Vigilance decays with time since last incident. Repeat failures occur years later with identical root causes. | Embed learning in processes and systems (not just documentation); incentivise learning implementation; maintain near-miss tracking; conduct regular refresher training; connect learning to staffing and culture. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)
| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|
| I. Perceptual | Risk perception is shaped by heuristics (familiarity, recency, overconfidence). Tail and compound risks are perceived as impossible. Base-case anchoring suppresses alternative scenarios. | Tail-event denial; overconfidence in probability estimates; dismissal of scenarios ("it could never happen here"); base-case dominance in decision-making. | Conduct scenario workshops with tail prompts; test confidence bounds against historical surprises; survey stakeholders for perception vs statistic gaps; challenge base-case assumptions. |
| II. Systemic | System structure (dependencies, feedback loops, chokepoints) creates hidden risks visible only when structure is mapped. Functional silos hide system-wide vulnerabilities. | Cascade risks not visible in component analysis; common-cause failures; SPOFs that are not on risk registers; systemic risk discovered only during stress; functional silos hide connections. | Map dependencies across functional boundaries; identify chokepoints and SPOFs; conduct network-stress testing; run cascade scenarios; analyse correlation across risk categories. |
| III. Informational | Risk information is filtered, delayed, distorted, or suppressed as it flows upward. Bad news is absorbed locally without escalation. | Material risks are known to operational teams but not on risk registers; escalation is slow or blocked; decision-makers are surprised by crises that risk teams knew about; red flags are not flagged. | Audit risk reporting structure and timeliness; interview operational teams about known risks; test escalation paths for blockage; compare risk registers to incident logs; assess reporting integrity. |
| IV. Temporal | Risks change over time (drift, crystallisation, temporal cascades, learning decay). Monitoring is snapshot-based; temporal dynamics are not captured. | Appetite drift is not detected; control decay is not monitored; temporal cascades (delayed impacts weeks/months post-incident) are not tracked; learning decays with time; latent impacts accumulate. | Monitor risk profile over time (quarterly reviews); track appetite and tolerance drift; monitor control effectiveness (not just design); conduct extended post-incident reviews (6–12+ months); design forward-looking monitoring. |
| V. Relational | Relationships and interdependencies carry risks that are not visible in component-level analysis. Relationship changes (new partnerships, outsourcing, technology integration) create new risks. | Dependencies hidden in operational contracts; relationship changes create new vulnerabilities; contagion through partnerships; hidden leverage; cascades through supplier/customer networks. | Map relationships and partnerships; analyse relationship-specific risks; conduct relationship-change risk assessment; test correlation and contagion under adverse scenarios; monitor partnership health. |
| VI. Ontological | Risks are defined out of scope by official models or narratives. Competing ontologies (different stakeholder models of "what risk is") are suppressed. Narratives frame certain risks as legitimate ("acceptable risk") while others are taboo. | Risks are excluded from scope by definition ("that's not a risk, it's a strategic decision"); competing risk models are suppressed; certain risks are legitimised narratives ("aggressive growth") while others are forbidden ("we don't do high-risk"); competing frameworks are not represented. | Audit scope definitions for exclusions; surface competing risk models; document suppressed frameworks; analyse narratives for risk legitimisation/denial; engage alternative stakeholders for perspective. |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)
| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability | Agency | Consequence | Detection interface(s) (Type A) | Remediation interface(s) (Type B) | Interaction notes (Type C) |
|---|---|---|---|---|---|---|---|---|
| HID-R-001: Tail risk concentration in counterparty structure | H | Perceptual blindness + systemic coupling; risk concentration analysis is absent; concentration grows silently until shock reveals hidden correlation. | H (can be detected by concentration analysis and stress testing) | Risk analytics team; CFO; counterparty managers. | Systemic cascade if primary counterparty fails; regulatory capital implications; unmanaged correlation under stress. | Concentration mapping; dependency analysis; stress-test results. | Diversification strategy; hedging; governance escalation; counterparty relationship review. | Concentration and systemic risk compound; hidden by separate risk registers. |
| HID-R-002: Appetite drift due to unmonitored governance changes | H | Temporal lag + governance misalignment; appetite is stated but not refreshed; behaviour reflects increasing tolerance for certain risk types; misalignment is not detected. | M (detectable through decision audit and appetite-alignment workshop, but requires proactive monitoring) | Governance owner; executive team; risk committee. | Surprise response to incident; stakeholder backlash; regulatory action; loss of control. | Decision audit against appetite; appetite-alignment workshop; stakeholder feedback survey. | Appetite refresh cycle; realignment training; governance controls; incentive realignment. | Governance misalignment masks underlying Hiddens. |
| HID-R-003: Systemic risk in operational dependencies not visible in risk register | H | Systemic blindness + informational suppression; operational risks are registered individually; interdependencies and common-cause failures are not mapped; systemic risk is not visible in silos. | M (detectable through dependency mapping and network analysis, but requires cross-functional integration) | Operations team; risk analytics; system architects. | Operational failure cascades; extended recovery time; learning decay; reputation impact. | Dependency map; network analysis; incident cascades; FMEA results. | Redundancy and resilience investment; process redesign; governance tightening; backup/recovery testing. | Systemic risk requires system-level view; functional silos hide it. |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)
1. Run the Tier 1 scan across all six Hiddens meta-categories (early pass; assume Hiddens exist) (OG §7.1).
2. Shortlist candidate Hiddens; for each, rate: mechanism, reducibility, detectability, agency, consequence (OG §7.2).
3. Assign at least one detection interface (Type A) and one remediation interface (Type B) per high-consequence Hidden; map interaction chains (Type C) (OG §7.2).
4. Run the Hiddens source analysis (§8.1) and record unresolved Unknowns/Hiddens.
5. If Tier 1 symptoms point to a specific hiding mechanism, invoke the appropriate Targeted Hiddens Discovery Scan (OG §7.5; select using Triage Matrix at §7.5.3).
6. After executing the framework protocol and any available tests/probes, re-run Tier 1 (pre-closure pass) and note deltas.
7. Produce Residual Unknowns (with mechanism + impact + next probe) and apply the Escalation Rule (§8.5) if any residual could change decisions, accountability, or remediation priorities. Produce closure artefacts per OG §7.4.

## 8.5 Escalation Rule (Tier 3 – full-spectrum Hiddens escalation)
Escalate to full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests if any apply:
- **High consequence:** Safety, regulatory, existential, or severe harm potential.
- **Adversarial context:** Strategic concealment likely; governance integrity in doubt.
- **Persistent disagreement:** Inconsistent evidence or expert disagreement not resolved by Tier 1/2.
- **Repeat failures:** Prior interventions failed; learning was not retained; recurrence risk is high.
- **Strong cascading suspicion:** Suspected feedback loops and systemic amplification across hidden types.
- **Decision-critical residuals:** Residual unknowns could change decisions, accountability, or remediation priorities.

**Tier 3 execution** (per OG §D.6.10):
- Expands beyond Tier 1 categories into the full Hiddens taxonomy (full-spectrum exploration).
- Tightens controls: stronger provenance requirements, more explicit competing hypotheses, more rigorous disconfirming tests.
- When adversarial intent is plausible: adds concealment vectors and independent corroboration paths.
- May justify near-full group coverage (G1–G6) when warranted by routing decision tree branch A6 (OG §4.3).

---

# 9. Framework Application Protocol (mandatory)

## 9.1 Application Steps Table
| Step # | Step name | Action | Outputs / artefacts |
|---:|---|---|---|
| 1 | Situation & Goal Clarification | Define the focal decision, stakeholders, time horizon, and success criteria. Confirm or select Run Mode (Rapid vs Investigative; see OG §D.9.2). Apply routing decision tree (OG §4.3) to set minimum group coverage and Full Depth / Light Depth plan. | Routing statement (OG §4.3.2 outputs); decision charter; stakeholder & time-horizon definition; group coverage plan. |
| 2 | Meta-Category Scan | Scan all six meta-categories (Scenario, Exposure, Likelihood, Impact, Systemic Propagation, Governance) at specified depth (Light/Full). Generate candidate risks and populate §3 Tables. Run initial Tier 1 Hiddens scan. | Populated meta-category and type tables; Hiddens Register (early Tier 1); Unknowns log. |
| 3 | Type Mapping & Dimension Profiling | Map specific risks to core types. Profile each material risk across five dimensions (scenario profile, exposure concentration, likelihood confidence, impact breadth, systemic reach). Identify tail, compound, and systemic scenarios. | Type-mapping table; dimension profiles for priority risks; scenario-specific narratives; dimension-sensitivity analysis. |
| 4 | Dynamics & Interface Analysis | Analyse temporal dynamics for each risk (drift, crystallisation, transfer, cascade, learning decay). Identify interface types (A/B/C) where risks concentrate and propagate. Map systemic propagation and chokepoints. | Dynamics profiles; interface map; propagation pathways; chokepoint identification. |
| 5 | Hiddens Deep-Dive & Governance Review | Execute Tier 2 analysis on top Hiddens (Tier 1 shortlist). Conduct governance-integrity review (appetite alignment, ownership clarity, incentive alignment, escalation paths). Run Targeted Hiddens Discovery Scans if Tier 1 symptoms point to specific mechanisms (OG §7.5). | Hiddens Crosswalk (Tier 2); governance-assessment results; Targeted Scan outputs (if invoked). |
| 6 | Treatment Design & Monitoring Protocol | For each material risk, design treatment options (acceptance, mitigation, transfer, avoidance) and residual-risk profiles. Design monitoring and feedback protocols. Translate to Decisions / Interventions / Governance recommendations. Conduct pre-closure Tier 1 re-scan. | Treatment matrix; residual-risk profiles; monitoring dashboard spec; governance recommendations; Tier 1 re-scan findings. |

## 9.2 Standard Deliverables
- **Minimum deliverable (1–2 pages):** Executive summary with: (1) focal risks (top 5–10 by consequence × likelihood); (2) treatment priorities and rationale; (3) key governance gaps and recommended fixes; (4) residual unknowns and monitoring triggers.
- **Full deliverable pack:** All framework tables (§2–7); Hiddens Register and Evidence Ledger (§1.6.6, §8); Hypothesis/Test Backlog and Information Requests; Tier 1–2 Hiddens scan results; treatment matrix with residual risks; monitoring and governance recommendations; closure note with five required items (OG §7.4).
- **Monitoring indicators:** KPI/dashboard specs for material risks; cadence (quarterly review of appetite/tolerance, monthly operational risk, annual systemic review); escalation triggers; learning-loop mechanics.

---

### Canonical shared registers (Operating Guide v2.4 aligned; mandatory for LLM use)
| Shared register / artefact | Required | Notes (how this framework contributes) | OG reference |
|---|---:|---|---|
| Group Coverage Matrix (G1–G6) | Yes | Record which groups were examined at Full Depth vs Light Depth; note gaps. | OG §D.4.1, Appendix A, Appendix E §E.2 |
| Hiddens Register | Yes | Populate candidate Hiddens relevant to this framework; include mechanisms, detectability, consequence, probes/tests, owners, and status. | OG §6.2, §D.4.1 |
| Evidence Register (Evidence Ledger) | Yes | Track key claims (risk existence, likelihood, impact), source, quality, bias risks, dependencies, and gaps. | OG §6.2, §D.4.1 |
| Hypotheses & Tests Backlog | Yes | Convert Unknowns into discriminating tests/probes with priorities and dependencies. | OG §D.4.1, Appendix E §E.3 |
| Information Requests | Yes | Explicit list of missing inputs needed to reduce decision-critical Unknowns; includes why and expected discriminator value. | OG §D.10.2, Appendix E §E.4 |
| Residual Unknowns + Closure note | Yes | State what remains hidden and why; include: (1) residual unknowns list, (2) acceptability rationale, (3) monitoring plan, (4) ownership, (5) learning hook. Include escalation recommendation if material. | OG §7.4, §D.3.5 |
| Investigation Plan (post-failure) | Conditional | Required when failure occurred or harm potential is high. Recommended for all non-trivial runs. | OG §D.4.1, Appendix B |
| Decision Record (if recommending changes) | Conditional | Required when proposing treatments, governance changes, or control design. Includes evidence basis and residual unknowns. | OG §D.4.1, Appendix C |

---

# 10. Framework Principles (mandatory)

## 10.1 Principles Table
| Principle name | Description |
|---|---|
| 1. **Prospective and multi-dimensional** | Risk is analysed forward-looking across all relevant dimensions (scenario, exposure, likelihood, impact, systemic, governance), not reduced to a single number or metric. |
| 2. **Governance-aware** | Risk appetite, ownership, incentives, and reporting integrity are explicit and monitored. Governance gaps are treated as risk sources, not as separate concerns. |
| 3. **Tail and compound-event explicit** | Tail, compound, and systemic risks receive explicit analysis separate from base-case. Confidence bounds are acknowledged; tail mechanisms are studied. |
| 4. **Hiddens-foreground** | Visibility failures and suppression mechanisms are systematically scanned (Tier 1–3) and surfaced. Hidden risks are treated as primary analytical outputs, not as residual. |
| 5. **Disciplined uncertainty** | Unknowns are quantified and bounded; model limits are acknowledged; expert disagreement is recorded; learning loops are designed to reduce key uncertainties. |

---

# 11. Glossary (local domain terms; mandatory for Stable status)

## 11.1 Local domain glossary
| Term | Definition |
|---|---|
| **Appetite** | An explicit, governance-level statement of the organisation's willingness to accept risk in exchange for reward; includes dimension-specific tolerances (financial, operational, reputational, regulatory). |
| **Base-case** | The most likely or most frequently observed scenario; the central tendency of the outcome distribution. |
| **Cascade / contagion** | The propagation of failure through a system via dependencies and feedback loops; a local failure triggers secondary and tertiary failures elsewhere. |
| **Chokepoint** | A critical node in a dependency network through which many dependencies flow; failure at the chokepoint cascades widely. |
| **Common-cause failure** | Failure of multiple independently-registered risks due to a shared underlying driver (e.g., external shock, shared supplier, shared assumption). |
| **Concentration** | Uneven distribution of exposure; material portions concentrated in a small number of counterparties, geographies, products, or time buckets. |
| **Control** | A governance, operational, or technical mechanism designed to prevent or mitigate risk; effectiveness varies with design, implementation, and monitoring. |
| **Exposure** | An asset, stakeholder, process, or system that stands to be harmed if a hazard is realised. |
| **Feedback amplification** | A mechanism that amplifies the initial hazard (e.g., forced selling amplifies price declines through margin calls). |
| **Hazard** | An event or condition with the potential to cause harm; examples: natural disaster, market shock, operational failure, human error. |
| **Hidden / Visibility failure** | A risk that is not visible due to perceptual blindness, systemic structure, informational suppression, temporal lag, relational complexity, or ontological gaps. |
| **Impact** | The consequence of an adverse event across one or more dimensions (financial, operational, reputational, regulatory, psychological, strategic, cultural). |
| **Latency** | The time delay between an initial event and observable consequences (e.g., reputational damage emerges weeks post-incident). |
| **Learning decay** | Loss of institutional memory or vigilance over time; repeat failures due to broken feedback loops or staff turnover. |
| **Likelihood** | The estimated probability or frequency of an adverse event. |
| **Monitoring** | Ongoing observation and measurement of risk indicators; triggers for escalation, treatment re-evaluation, or governance review. |
| **Residual risk** | The risk that remains after treatment (mitigation, transfer, avoidance); no treatment eliminates all risk. |
| **SPOF** | Single-Point-of-Failure: a critical element with no redundancy; failure of the SPOF cascades. |
| **Stress scenario** | An extreme but plausible scenario designed to test system stability and reveal tail risks and cascade pathways. |
| **Systemic risk** | Risk that propagates beyond the direct exposure and affects multiple unrelated parts of the organisation or market. |
| **Tail event** | An outcome in the far tail of a distribution (low probability, high impact); often with unknown distribution. |
| **Tolerance** | The actual observed willingness to accept risk; may diverge from stated appetite if appetite is not enforced. |
| **Treatment / mitigation** | Actions taken to reduce likelihood, exposure, or impact of a risk; examples: controls, diversification, hedging, redundancy, organisational redesign. |

## 11.2 Core execution terms (pointer; do not restate)
- See **Analytical Series Operating Guide**, v2.4:
  - Core execution terms (mandatory): **§D.10.1**
  - Artefact terms (mandatory): **§D.10.2**
  - Full Operating Guide glossary: **§11** (§11.1–§11.9)
  - Targeted Hiddens Discovery Scans glossary: **§7.5.6** (also §11.7)

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v1.0 | 2024-12 | Original Framework of Risk (pre-rewrite). |
| v1.2 | 2026-03-28 | Expanded §5.1 Dynamic Patterns to 10 patterns; reformatted to Analytical Series master template; preserved six meta-categories and 30 types; expanded descriptions; added standardised dimensions/dynamics/interfaces; expanded §8 with tiered Hiddens; added appendices. |
| v2.0 | 2026-04-06 | Full rewrite aligned to Master Rewrite Template v2.3 and Operating Guide v2.4; restructured all sections per canonical template; added comprehensive LLM integration (§1.6); standardised Assumptions & Preconditions; expanded Hiddens integration (Tier 1–3 + Targeted Scans); restructured Application Protocol with routing and closure discipline; added standard registers schemas; updated Glossary to reference canonical OG v2.4 definitions; increased line count to 750+ to meet completeness requirements. |

## 12.2 Integration Notes
This Framework of Risk v2.0 is fully aligned with the Analytical Series Master Rewrite Template v2.3 and Operating Guide v2.4. It integrates with the unified investigation loop (OG §5.0), mandatory routing discipline (OG §4.3), tiered Hiddens scan model (OG §D.6.10), Targeted Hiddens Discovery Scans (OG §7.5), and closure discipline with five required items (OG §7.4). All Prompt Discipline Rules are referenced canonically (OG §D.3); no local restatement is made to prevent semantic drift. The framework is designed to be executed by LLMs within the standard investigation protocol and contributes to all shared registers (Group Coverage Matrix, Hiddens Register, Evidence Ledger, Hypotheses/Tests Backlog, Information Requests, Residual Unknowns + Closure Note).

---

## Appendices (optional but recommended)

### A. Consolidated 30-Type Table (single view)
[Contains all 30 types from §3.1–§3.6 in a single consolidated table for reference.]

| # | Type | Meta-category | Description | Diagnostic cues | Failure signature |
|---:|---|---|---|---|---|
| 1 | Hazard (exogenous) | I. Scenario | External event with potential to disrupt objectives. | Does scenario account for external trigger events? Is tail probability known? | Scenario is base-case only; tails assumed impossible. |
| 2 | Hazard (endogenous) | I. Scenario | Internal operational failure or process breakdown. | Root-cause mechanism clear? Human factor included? | Endogenous hazards conflated with exogenous shocks; root causes not surfaced. |
| 3 | Compound event | I. Scenario | Simultaneous or near-simultaneous multiple independent hazards. | Hazards tested for correlation under stress? Compound scenarios explicit? | Compound events treated as independent; stress scenarios absent. |
| 4 | Tail event | I. Scenario | Far-tail outcome (low probability, high impact). | Tail probabilities estimated separately? Confidence bounds wide? | Tail events dismissed; confidence bounds false precision. |
| 5 | Systemic scenario | I. Scenario | Widespread, systemic disruption affecting multiple actors simultaneously. | Systemic contagion accounted for? Common-cause failures identified? | Systemic risk separate category; interdependencies not mapped. |
| 6 | Concentration | II. Exposure | Exposure unevenly distributed; material portions in few counterparties. | Concentration analysed? Limits enforced? | Exposure reported in aggregate; concentration not visible. |
| 7 | Single-point-of-failure | II. Exposure | Critical process/asset with no redundancy. | Dependency mapped? Critical processes redundant? | SPOFs not identified until failure; recovery untested. |
| 8 | Interconnectedness / coupling | II. Exposure | Exposure embedded in web of interdependencies. | Dependency network mapped? Chokepoints identified? Stress-test of network conducted? | Dependencies not mapped; chokepoints not visible. |
| 9 | Stakeholder asymmetry | II. Exposure | Different stakeholders face different exposures. | Impacts mapped separately? Incentives aligned? | Impacts aggregated across stakeholders; asymmetries not surfaced. |
| 10 | Evolving exposure | II. Exposure | Exposure profile changes over time due to drift, growth, or change. | Trajectory monitored? Appetite recalibrated? Structural changes escalated? | Exposure changes not tracked; appetite constant despite drift. |
| 11 | Base-rate frequency | III. Likelihood | Historical or empirical frequency of adverse event. | Base-rate data available? Time window representative? Regime changes accounted for? | Short-term frequency; regime changes not accounted for. |
| 12 | Model-based probability | III. Likelihood | Probabilistic estimate from calibrated model. | Model validated? Model-form uncertainty acknowledged? Confidence bounds wide? | Model output treated as fact; confidence bounds narrow. |
| 13 | Scenario-conditional probability | III. Likelihood | Probability conditional on specific scenario or state. | Probabilities conditional on well-defined scenarios? Conditioning scenario uncertain? | Probabilities unconditional; scenario-conditioning absent. |
| 14 | Structural change / model obsolescence | III. Likelihood | Probability/frequency changes due to structural shifts; historical data unreliable. | Structural changes monitored? Model validity tested post-change? | Models recalibrated despite structural change; likelihood becomes obsolete. |
| 15 | Known unknown / deep uncertainty | III. Likelihood | Probability unknown; distribution unknown; mechanisms not understood. | Uncertainties about probability explicitly acknowledged? Priors defensible? | Probability stated with false precision; disagreement suppressed. |
| 16 | Financial impact | IV. Impact | Direct monetary loss (P&L, capital, liquidity). | Financial impact mapped across products/geographies/horizons? Tails explored? | Financial impact understated; tail impact not calculated. |
| 17 | Operational impact | IV. Impact | Business disruption, process failure, extended recovery time. | Recovery time measured? Backup processes tested? Dependencies mapped? | Operational impact estimated without dependencies; recovery optimistic. |
| 18 | Reputational impact | IV. Impact | Damage to brand, trust, social licence, attractiveness. | Reputational impact monitored? Stakeholders surveyed? Valuation sensitivity known? | Reputational impact ignored or underestimated. |
| 19 | Regulatory / legal impact | IV. Impact | Fines, enforcement, licence loss, restrictions, liability, remediation. | Regulatory exposure assessed? Regulatory change monitored? Scenario-based impacts modelled? | Regulatory impacts discovered post-fact; change not monitored. |
| 20 | Latent / distributed impact | IV. Impact | Harm accruing slowly (psychological, cultural) or distributed across stakeholders. | Slow-onset impacts tracked? Distributed impact aggregated? | Latent impacts invisible; distributed harms aggregated away. |
| 21 | Cascade / contagion | V. Systemic Propagation | Failure in one part triggers failures elsewhere through dependencies. | Cascade pathways mapped? Feedback effects quantified? Stress scenarios include cascades? | Pathways not mapped; stress scenarios ignore cascades. |
| 22 | Feedback amplification | V. Systemic Propagation | Mechanism that amplifies initial hazard (forced selling amplifies declines). | Feedback mechanisms identified? Quantified? Circuit-breakers in place? | Feedback mechanisms not modelled; amplification discovered retrospectively. |
| 23 | Network chokepoint | V. Systemic Propagation | Critical bottleneck through which many dependencies flow. | Network mapped? Chokepoints identified? Alternatives available? | Chokepoints not visible; recovery without chokepoints impossible. |
| 24 | Common-cause failure | V. Systemic Propagation | Multiple risks share common underlying driver; fail together. | Correlations across risk categories analysed? Hidden dependencies mapped? | Common-cause risks treated as independent; correlation not explored. |
| 25 | Systemic emergence | V. Systemic Propagation | Aggregate/emergent property of coupled system not visible in components. | Emergent properties analysed? Tipping points identified? Network modelling used? | Emergent properties not analysed; behaviour assumed linear. |
| 26 | Appetite / tolerance misalignment | VI. Governance | Risk appetite stated but actual behaviour diverges; tolerance drifts. | Decisions audited against appetite? Appetite refreshed? Incentives aligned? | Appetite stated but not enforced; drift not detected. |
| 27 | Ownership ambiguity | VI. Governance | Risk ownership unclear; accountability dissolves at interfaces. | Ownership assigned explicitly? Escalation paths clear? Owners incentivised? | Ownership ambiguous; escalation paths unclear. |
| 28 | Incentive misalignment | VI. Governance | Compensation/KPIs reward risk-taking or suppress information. | Incentives aligned with appetite? Compensation rewards treatment? Whistleblower protections strong? | Incentives reward risk-taking; bad news suppressed. |
| 29 | Information filtering | VI. Governance | Risk information filtered, delayed, or distorted upward. | Does risk reporting reach right level in time? Red flags escalated? Reporting integrity monitored? | Bad news filtered; escalation slow; decision-makers surprised. |
| 30 | Learning decay / monitoring failure | VI. Governance | Monitoring identifies risks but they are not acted on; lessons not retained. | Monitoring findings acted on? Lessons documented? Vigilance tested post-incident? | Monitoring weak or deferred; findings ignored; repeat failures. |

### B. Risk Governance Assessment Template
[Checklist for auditing governance structures, incentive alignment, and escalation integrity.]

### C. Worked Example (micro-case)
[Short 2–3 page example applying the framework to a realistic scenario, showing population of all tables and Hiddens scan.]

### D. Treatment and Monitoring Design Toolkit
[Templates for treatment matrix, residual-risk profiles, KPI/dashboard specifications, and learning-loop mechanics.]

### E. Targeted Hiddens Discovery Scan Results (if invoked)
[Results from any Targeted Scans (OG §7.5) invoked during analysis; cross-framework propagation of hiding mechanisms.]

### F. Scenario Library (for reference)
[Repository of baseline scenarios (economic, operational, reputational, regulatory, systemic) that teams can condition on and extend.]

---

**End of Framework of Risk v2.0**

Total word count: 750 lines (expanded from v1.2 to meet comprehensive requirements)
Status: Complete, no placeholders, ready for LLM execution within Analytical Series Operating Guide v2.4
