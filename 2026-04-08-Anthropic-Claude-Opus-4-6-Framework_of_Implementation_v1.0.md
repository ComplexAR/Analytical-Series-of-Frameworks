# Framework of Implementation
*A Comprehensive Taxonomy of the Operational Translation of Decisions, Plans, and Policies into Practice*

## Document Information
- Series: Analytical Series of Frameworks
- Version: v1.0
- Date: 2026-04-08
- Status: Draft
- Operating Guide Compatibility: Analytical Series Operating Guide v2.5
- Prompt Discipline Ruleset: Operating Guide "Prompt Discipline Rules (Canonical)" (see OG v2.5, §D.3)
- Run Mode Terminology: Rapid Run Mode / Investigative Run Mode (see Operating Guide §D.10.1)
- Framework Execution Depth Terminology: Full Depth Framework Execution / Light Depth Framework Execution (see Operating Guide §D.10.1)
- Tiered Hiddens Scan Model: Tier 1 (six-category visibility audit) / Tier 2 (structured deepening) / Tier 3 (full-spectrum escalation) (see Operating Guide §D.6.10)
- Targeted Hiddens Discovery Scans: Thirteen mechanism-specific cross-framework scans (see Operating Guide §7.5)
- Group (Primary): G6 — Action & Control (Choice, action & control over time)
- Group (Secondary): G2 — Mechanism (Structure, dependencies & mechanism)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Map operational reality against policy intent; surface implementation gaps and drift; diagnose resistance, capacity constraints, and adaptation mechanisms; design implementation strategies with monitoring and adaptation; detect compliance theatre and shadow implementation; build implementation capacity and feedback loops; manage portfolio implementation risk
- Primary Audience: Programme and transformation leaders; operations executives; implementation teams; policy makers; change managers; risk and assurance leaders; middle management and frontline supervisors; incident response leaders
- Dependencies / Key Inputs: Policy or intervention specification; current operational practice; capacity and resource status; stakeholder perspectives and incentives; evidence of compliance and outcome; constraint mapping; risk and failure context
- Primary Outputs: Implementation gap inventory; resistance mechanisms catalogue; capacity constraint register; adaptation and workaround inventory; compliance-practice audit; implementation dynamics assessment; monitoring and feedback design; risk register and escalation triggers; Hiddens source register plus tiered Hiddens mapping
- Change Log (brief): v1.0: Initial write to Master Template v3.0 with OG v2.5 integration; six meta-categories with 30 core types (Sequencing & Ordering, Capacity & Resources, Resistance & Compliance, Workarounds & Adaptations, Feedback & Monitoring, Portfolio & Tempo); five dimensions; ten dynamic patterns; three interface types; full Tier 1–3 Hiddens integration with 13 Targeted Scans; §1.6 LLM Integration Bridge populated; §7.3 integration questions for all 36 canonical frameworks; expanded Introduction section; expanded Application Protocol

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What is actually happening in the gap between what was decided and what is being done, and what does that gap conceal?** |
| Addresses | Implementation gaps and drift; compliance theatre; street-level adaptation; passive non-compliance; capacity bottlenecks; resistance invisibility; decision-implementation divergence; workarounds hardening into shadow systems; coordination failure in multi-party implementation; unintended consequences and cascade effects |
| Gap Filled | Interventions describes what actions are designed to do. Decisions describes what was chosen. Implementation describes what actually happens when those actions are executed in context—the sequencing, capacity, resistance, adaptation, feedback, and portfolio dynamics that determine whether intent translates into outcome. |
| Complements | Interventions; Decisions; Governance; Learning and Adaptation; Risk; Processes; Capacity; Power; Incentives; Communication; Evidence; Uncertainties; Failures |
| Key Characteristics | Six meta-categories; thirty core types; five cross-cutting dimensions; ten dynamic patterns; three interface types (Implementation-Intervention, Implementation-Governance, Implementation-Evidence); embedded Hiddens source analysis and tiered Hiddens mapping (Tier 1–3 + 13 Targeted Scans) |
| Main Contributions | Repeatable implementation health check; taxonomy of implementation failure modes; early warning signals for implementation drift; gap-to-risk translation; interface-aware monitoring design; integration of implementation reality with governance and learning loops; structured resistance and capacity diagnostics |

---

# Introduction

## What is Implementation?

Implementation is the operational translation of decisions, policies, plans, and interventions into actual practice. It is the gap between what was decided and what is being done. Implementation is not automatic, not frictionless, and not neutral. The same policy executed with strong capacity and light resistance in one context may fail catastrophically in another due to bottlenecks, coordination failures, passive resistance, or the emergence of workarounds that subtly invert intent. A complete understanding of implementation requires simultaneous visibility of: (1) the formal specification (what was decided), (2) the operational reality (what is actually happening), (3) the gap between them (divergence, adaptation, and drift), (4) the mechanisms driving that gap (capacity, resistance, feedback, coordination), and (5) what is hidden by that gap (unintended consequences, equity impacts, second-order effects).

Implementation failure is not primarily a matter of low intent or overt rebellion. Frontline implementers are often conscientious and competent. Implementation failure occurs because: policies assume capacity that does not exist; policies do not account for existing incentive structures; implementation is not monitored, so drift is never detected; feedback loops are absent, so learning is disabled; resistance takes subtle forms (workarounds, gaming, re-interpretation) that feel like compliance but invert intent; and portfolios of changes interact in ways that override individual logic. This framework provides an operational definition: **Implementation is the process through which decisions and interventions are operationalised into sustained practice, and the examination of what happens in that process to intent, scope, fidelity, outcome, and adaptation over time.**

## Why does Implementation matter for Hiddens work?

Implementation is a primary generator and revealer of Hiddens. Implementation gaps are not random noise—they are systematic, often driven by intentional adaptation to unacknowledged constraints. A policy that assumes compliance without monitoring generates Hiddens: actual practice diverges quietly while formal reporting shows compliance. A change that is rolled out without capacity generates Hiddens: frontline workers develop workarounds that work locally but create system-wide fragmentation. A policy that triggers resistance generates Hiddens: resistance is expressed not through open opposition but through passive non-compliance, re-interpretation, and shadow workarounds that are invisible to oversight. A portfolio of overlapping initiatives generates Hiddens: their interactions are not predicted, monitored, or corrected, producing cascade effects that appear chaotic when in fact they were deterministic consequences of invisible implementation conflicts.

Conversely, this framework surfaces eight families of Hiddens:

- **Compliance Theatre Hiddens (Hidden-9)**: Formal compliance is reported while actual practice continues unchanged. Staff appear to comply while implementing old processes in new language.
- **Capacity Blindness Hiddens (Hidden-21)**: Insufficient capacity is not reported upward; frontline workers absorb overload silently or adopt workarounds that degrade quality invisibly.
- **Street-Level Adaptation Hiddens (Hidden-22)**: Frontline staff adapt policies to local context without approval or visibility; intent is gradually reinterpreted and drift goes undetected.
- **Resistance Invisibility Hiddens (Hidden-23)**: Active resistance is rare; passive non-compliance is common but invisible—staff simply do not follow through, and reporting systems show on-paper compliance.
- **Decision-Implementation Divergence Hiddens (Hidden-24)**: Decisions are interpreted differently across contexts; implementation variance is not surfaced; learning is disabled because diagnosis of divergence is missing.
- **Cascade and Interaction Hiddens (Hidden-25)**: Implementation of one change triggers second-order effects that override the primary logic; these interactions are not monitored or designed.
- **Unintended Consequence Hiddens (Hidden-26)**: Implementation achieves stated outcomes while generating negative impacts elsewhere in the system; these impacts are not surfaced because monitoring is outcome-siloed.
- **Equity and Differential Impact Hiddens (Hidden-27)**: Implementation affects different populations differently; these differential impacts are not monitored and equity degradation occurs invisibly.

Without this framework, implementation gaps appear as individual failures or laziness. With the framework, implementation becomes a diagnosable system: gaps have mechanisms, mechanisms have locations (sequencing, capacity, resistance, adaptation, feedback, portfolio), locations can be monitored, and monitoring feeds back into design adjustment and learning.

## What does this framework produce?

The framework operationalises implementation diagnosis and design through six core elements:

1. **A taxonomy of 30 implementation types** organised into six meta-categories (Sequencing & Ordering, Capacity & Resources, Resistance & Compliance, Workarounds & Adaptations, Feedback & Monitoring, Portfolio & Tempo) that recur across contexts, allowing rapid classification and comparison of implementation mechanisms.

2. **Five cross-cutting dimensions** (Scope & Coverage, Fidelity & Drift, Tempo & Sequencing, Capacity & Constraint, Monitoring & Feedback) that profile any implementation instance and explain variation across similar contexts.

3. **Ten dynamic patterns** (Phased Roll-Out Momentum, Capacity Exhaustion & Overload, Silent Adaptation, Resistance Activation, Monitoring Decay, Feedback Loop Collapse, Decision-Implementation Drift, Cascade & Interaction, Workaround Hardening, Crisis Reversion) that describe how implementation evolves over time, enabling detection of regime transitions and early warning of implementation breakdown.

4. **Three interface types** (I-A Intervention-to-Implementation, I-B Implementation-to-Governance, I-C Implementation-to-Evidence) that make visible where and how implementation mechanisms interact with design, oversight, and learning, where failures create orphan risks, and which interfaces require explicit design and testing.

5. **Hiddens source analysis and tiered Hiddens scans** (Tier 1 six-category audit, Tier 2 structured deepening, Tier 3 full-spectrum escalation) that surface the eight systematic sources of implementation failure and the six categories of visibility failure that permit Hiddens to persist.

6. **An application protocol** that moves from implementation clarification through gap analysis, resistance diagnosis, capacity audit, dynamics scanning, Hiddens mapping, and implementation redesign into actionable implementation changes.

The framework populates standard registers (Implementation Inventory, Gap Register, Resistance & Adaptation Catalogue, Capacity & Constraint Register, Implementation Risk Register, Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog) that integrate with the broader Analytical Series investigation workflow. It is designed for repeated use: implementation is reviewed, Hiddens are surfaced, design adjustments are made, monitoring is intensified, and implementation is re-assessed at scheduled intervals or triggered by threshold breaches, allowing the analysis to track drift in real time.

## How to use this framework

Invoke this framework when a policy, intervention, or major change is approved and operational execution begins. Use it to establish baseline implementation health before drift becomes embedded. Use it periodically to detect deviation from intended practice. Use it when outcomes are disappointing despite approval and design appearing sound—implementation dynamics often explain the gap. The framework is most valuable when used together with the Interventions, Governance, Learning and Adaptation, Risk, and Evidence frameworks to understand the full cycle from decision through to outcome.

The framework works in both Rapid Run Mode (quick gap identification, simple capacity check, Tier 1 Hiddens scan) and Investigative Run Mode (full dimensional profiling, deep dynamics analysis, Tier 2–3 Hiddens scanning, live-practice audits, resistance and adaptation testing). Default execution is Light Depth Framework Execution: identify active implementation types, assess one or two dimensions, spot obvious interface failures, conduct a Tier 1 Hiddens scan. Escalate to Full Depth when consequence is high, evidence is contested, suspected drift is present, or compliance-practice decoupling is in question.

For LLM execution, see §1.6 for the complete LLM integration specification, standard registers, and copy-ready run prompts. The framework is designed to be directly executable by an LLM given a scenario and the Operating Guide, producing a disciplined implementation assessment with explicit Hiddens, F/I/A/U tagging, and bounded closure.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Implementation is the translation of decisions and designs into operational reality. It is neither automatic nor transparent. The distance between intent (what was decided) and outcome (what actually happens) is populated by mechanisms: sequencing decisions, capacity constraints, resistance and adaptation by implementing actors, workarounds that emerge from local pressures, feedback loops that either close learning or leave blindspots, and portfolio interactions that override individual change logic. A well-designed implementation process makes these mechanisms visible, surfaces resistance before it hardens, monitors fidelity without creating compliance theatre, maintains feedback loops to enable course correction, and manages portfolio interactions. A poorly designed implementation process creates opacity: compliance is reported while practice diverges; capacity constraints are absorbed silently by frontline workers; resistance takes subtle forms (re-interpretation, selective compliance, workarounds) that appear from a distance to be adaptation when they are in fact inversion of intent; feedback loops break or become performative; and portfolio interactions create cascade effects that appear chaotic.

The question this framework answers is: **What is actually happening in the gap between what was decided and what is being done, and what does that gap conceal?**

## 1.2 Assumptions & Preconditions

### Assumptions Register

| Assumption | Type | If false, what breaks? | How to test | Mitigation |
|---|---|---|---|---|
| Implementation can be made visible and designed | Method / Structural | Framework loses applicability; implementation becomes viewed as immutable or unmeasurable. | Apply framework to two contexts and assess whether visibility improves; measure pre/post adjustment outcomes. | Acknowledge bounded observability; focus on high-impact mechanisms; use proxy indicators when direct observation is limited. |
| Intent and actual practice can diverge materially | Structural / Domain | Framework becomes unnecessary; implementation is assumed faithful execution. | Compare written policies to actual observed practice via interviews, direct observation, trace-backs, testing. | Use ethnographic methods; conduct live-practice audits; sample actual decisions and actions against documented policy. |
| Implementation failure has mechanisms that can be diagnosed | Domain / Structural | Implementation failures appear random or personal (laziness, incompetence); structural diagnosis is impossible. | Analyse implementation failures; map to sequencing, capacity, resistance, adaptation, feedback, or portfolio mechanisms. | Use mechanism mapping; cluster failures by type; look for patterns, not one-off failures. |
| Frontline implementers are competent and often conscientious | Domain / Structural | Failures are attributed to individual incompetence; implementation is treated as a recruitment problem rather than a system problem. | Interview frontline staff; assess capability; observe actual constraints and pressures they face. | Combine with Competencies and Agents frameworks; test staff capability separately from system design. |
| Capacity constraints matter and are often invisible | Structural / Domain | Overload is absorbed; workarounds emerge; drift is unreported; frontline workers burn out silently. | Measure available time and resources against required work; audit how time is actually allocated; measure fatigue and turnover. | Implement capacity monitoring; create safe escalation for overload; provide visible resource models. |
| Monitoring without feedback is performative | Method / Structural | Compliance is reported while practice diverges; monitoring creates theatre rather than learning. | Audit loop closure (% of monitored issues that receive action); track corrective action effectiveness. | Combine monitoring with explicit governance (G-B implementation oversight interface); ensure escalation produces action. |
| Portfolio interactions are real and often undesigned | Structural / Domain | Changes interact in surprising ways; cascade effects appear chaotic when they are deterministic. | Map implementation interdependencies; test what happens when two implementations run in parallel; audit outcome variance. | Use portfolio management discipline; build interaction models; increase monitoring when coupling is high. |
| Implementation drift is normal and must be managed | Structural / Domain | Drift is treated as failure (deviation from spec) rather than as expected variation that requires course correction. | Track implementation variance against spec over time; measure how variance increases; assess which variance is adaptation vs. drift. | Distinguish intentional adaptation from drift; monitor for drift signals; establish acceptable variance bounds. |

### Preconditions Checklist

| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Policy, intervention, or decision specification is defined | Y | Decision document; specification of intent, scope, target population, timing, success criteria | Decision maker / policy owner | Verify against scenario; validate completeness with stakeholders. | Produce Decision Clarification Summary; work with "plausible minimum spec"; iterate with sponsor. |
| Current operational practice is known | Y | Process documentation; observation notes; decision traces; operational metrics | Operations / process owner | Audit through interviews, observation, and metric collection; assess coverage. | Conduct live-practice audit; sample decisions and actions; use proxy indicators. |
| Stakeholders and implementation actors are identified | Y | Stakeholder map; implementer roster; role clarity; incentive map | Implementation sponsor / HR | Verify against scenario; conduct stakeholder validation. | Use representative sampling; engage through formal channels; note gaps in closure. |
| Capacity status is assessed | Y | Resource allocation; workload audit; capability assessment; fatigue/turnover data | Operations / HR | Verify current vs. required capacity; assess shortfall. | Conduct capacity baseline; estimate requirements; flag constraints. |
| Monitoring and evidence collection are possible | Y | Available metrics; data collection capability; frequency possible; access to data | Evidence / IT owner | Confirm data exists or can be collected; assess reliability and timeliness. | Propose proxy indicators; establish data collection baseline; note data gaps. |
| Governance interfaces for escalation and course correction exist | Y | Escalation pathways; governance forums; decision authority for course correction | Governance / programme owner | Verify escalation clarity; confirm decision authority. | Establish ad-hoc escalation forum; define decision authority; create risk register. |
| Risk context is known | Y | Risk register; failure history; consequence levels; escalation thresholds | Risk owner | Verify against Risk and Failures frameworks; assess completeness. | Run parallel Risk scan; use proxy risk model; note assumptions in closure. |
| Learning and adjustment cadence are designable | Y | Current review schedule; governance change history; iteration budget | Sponsor / programme manager | Confirm feasibility; assess iteration capacity. | Propose default cadence (monthly); flag resource constraints; recommend agile adjustment approach. |

## 1.3 Definitions, Scope, and Non-Goals

**Implementation (operational)**: The process through which decisions and interventions are operationalised into sustained practice, including the sequencing, capacity, resistance, adaptation, and feedback dynamics that shape whether intent translates into outcome.

**Implementation gap (operational)**: The distance between intended practice (as specified in decisions and designs) and actual practice (as observed in operations), including variance due to necessary adaptation, intentional resistance, unintended consequence, capacity constraint, feedback absence, and portfolio interaction.

**In scope**:
- Six implementation meta-categories and thirty core types (6×5 taxonomy)
- Five implementation dimensions for profiling implementation instances
- Implementation dynamics (ten patterns: roll-out momentum, capacity exhaustion, adaptation, resistance, monitoring decay, feedback collapse, drift, cascade, workaround hardening, crisis reversion)
- Three implementation interface types (I-A intervention-to-implementation, I-B implementation-to-governance, I-C implementation-to-evidence)
- Hiddens sources plus tiered Hiddens cross-check (Tier 1–3 + 13 Targeted Scans)
- Application protocol and standard deliverables
- Integration with all 36 canonical frameworks

**Out of scope**:
- Detailed operational procedure design (treated as input; design discipline is in Processes framework)
- Specific domain implementation procedures (e.g., clinical protocol implementation, software deployment methodology) (domain specialists address these; this framework provides meta-discipline)
- Project management mechanics and tools (assumed as infrastructure; focus is on implementation health diagnostics)

## 1.4 Position in the Series (Upstream / Middle / Downstream)

- **Upstream frameworks**: Decisions; Interventions; Governance; Risk; Capacities; Power; Incentives; Evidence; Uncertainties
- **Middle (this framework's role)**: Map and diagnose what happens when decisions and interventions are executed; surface implementation gaps and drift; classify implementation mechanisms; locate interface failures; surface Hiddens generated by implementation opacity; design implementation health monitoring and course correction
- **Downstream frameworks**: Learning and Adaptation; Evidence and Metrics collection; Risk escalation and response; Responsibility assignment for implementation failure; Communications and narrative embedding of implementation changes

### Operating Guide Integration & Routing

- **Group assignment (Primary)**: G6 — Action & Control (Choice, action & control over time)
- **Group assignment (Secondary)**: G2 — Mechanism (Structure, dependencies & mechanism)
- **Stage assignment**: Downstream (see OG v2.5 §3.1 Stage framework)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.10.1 Mode Selection Gate)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
- **Framework Index**: this framework is one of 36 in the series (see OG v2.5 §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary

| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Decisions & design | Decisions; Interventions; Processes | What was chosen, what actions were designed, how activities should flow | What is actually happening when designs meet reality, where divergence occurs, and what causes it |
| Governance & oversight | Governance; Responsibility | Authority structures, oversight mechanisms, accountability assignments | Whether governance loops close to detect and correct implementation drift, and what implementation failures reveal about governance |
| Capacity & resources | Capacities; Resources; Power; Incentives | What resources exist, who controls them, what behaviours are rewarded and punished | Whether capacity matches implementation requirements and how incentives shape actual implementation choices |
| Evidence & learning | Evidence; Uncertainties; Learning and Adaptation | What is known, what is uncertain, how organisations update understanding | Whether implementation is monitored, how feedback reaches decision-makers, and whether learning updates design |
| Risk & consequences | Risk; Failures; Uncertainties | What can go wrong, what has gone wrong before, impact ranges | Whether implementation itself creates new risks and whether cascade interactions are designed and monitored |
| Meaning & legitimacy | Communications; Narratives; Culture & Norms; Legitimacy | How change is communicated, what stories are told, what is trusted and believed | Whether implementation narratives match operational reality or whether compliance theatre exists; trust in implementation fidelity |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Implementation_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Implementation when… | Use neighbour instead when… |
|---|---|---|
| Interventions | What actually happened when the designed intervention was executed in operations; gap between design intent and operational reality; how operators adapted design to local context | Designing the intervention itself (what actions to take, their mechanisms, expected outcomes under ideal conditions); intervention sequencing and portfolio logic |
| Governance | Why implementation divergence is not detected, escalated, or corrected; whether governance loops close to monitor and adjust implementation; how formal governance relates to lived implementation practice | Designing governance structures; allocating formal authority and oversight; governance independence and escalation pathways |
| Learning and Adaptation | Whether implementation feedback reaches learning loops; how adaptation is designed and measured; what organisations learned from implementation variance; iteration and continuous improvement cycles | Designing learning systems; evaluating learning effectiveness; building individual and organisational capability |
| Decisions | How decisions are being executed in practice; whether implementation matches decision intent; adaptation and reinterpretation at frontline | Making the decision; analysing decision quality; decision-making process design |
| Evidence | Whether implementation is monitored, what metrics exist, whether monitoring feeds back to decision-makers; how implementation gaps are surfaced in evidence | Collecting evidence; standards of proof; uncertainty quantification; evidence quality and reliability assessment |

### 1.6.3 Routing triggers
- A decision or major policy change has been approved and is now operational
- Outcomes are disappointing or surprising despite apparently sound approval and design
- Reports show compliance but operational observations suggest practice divergence
- Frontline staff describe workarounds, shortcuts, or reinterpretations of policy
- Capacity constraints are suspected but not explicitly surfaced
- Multiple overlapping changes are in flight and cascade effects are suspected
- Monitoring is absent or compliance is reported without evidence of behaviour change
- Learning loops are not closing: lessons are not reaching decision-makers

---

# 2. Meta-Categories of Implementation

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Sequencing & Ordering | In what sequence are activities being introduced, and is that sequence enabling or blocking implementation success? | Phased roll-out, timing, prerequisites, dependencies, and critical-path logic. | Implementation plans with phasing; prerequisite mapping; schedule baseline vs. actual; sequencing dependencies. |
| II | Capacity & Resources | Are the human, technical, and organisational resources sufficient to execute and sustain implementation, and where are bottlenecks? | Workforce allocation, tooling readiness, budget sufficiency, supporting infrastructure, demand-capacity alignment. | Resource allocation plans; workload audits; staffing schedules; training and transition plans; budget consumption tracking. |
| III | Resistance & Compliance | What forms of resistance (active, passive, hidden) are present, and is reported compliance reflecting actual behaviour change or theatre? | Active opposition, passive non-compliance, gaming, re-interpretation, selective compliance, performance metrics that mask non-compliance. | Resistance indicators; escalation reports; survey data on perceived change; audit of actual practice; compliance metric audits. |
| IV | Workarounds & Adaptations | What informal modifications to specified process are being used, and are they indicating capability gaps, constraint-driven necessity, or intentional deviation? | Shadow processes, local reinterpretation, temporary patches, contingencies, discretionary shortcuts, unapproved variants. | Observation notes; incident reports; staff interviews; workaround documentation; process-variance audits. |
| V | Feedback & Monitoring | What mechanisms exist to surface whether implementation is occurring as intended, and do those mechanisms produce action or just reporting? | Metrics and data collection, escalation pathways, decision-maker visibility, feedback loop closure, corrective action effectiveness. | Monitoring dashboards; metric definitions; data collection protocols; escalation logs; corrective action tracking. |
| VI | Portfolio & Tempo | How are multiple implementation initiatives sequenced and managed, and what interactions and cascade effects result from parallel implementation? | Phasing across programmes, resource contention, interaction design, portfolio prioritisation, cascade management, tempo calibration. | Portfolio maps; interdependency matrices; risk registers for interactions; resource-allocation frameworks; tempo management protocols. |

## 2.2 Meta-Category Descriptions

### I. Sequencing & Ordering
The order and timing in which changes are introduced shapes implementation success. Prerequisites that are not sequenced correctly create bottlenecks: trying to implement a new service before platform readiness causes rework. Dependencies that are not explicit create hidden blockers: a change cannot proceed until an upstream change is complete, but the dependency is not tracked, creating stalled implementation. Sequencing logic that ignores system dynamics creates instability: changes are rushed in to meet deadlines despite insufficient stabilisation of previous changes. A well-sequenced implementation moves from prerequisites through to adoption as capacity builds and feedback accumulates. A poorly sequenced implementation introduces changes without preparing the ground, creates unnecessary rework, and leaves stabilisation incomplete.

**Definition**: The order and timing of implementation activities, including prerequisite logic, dependency management, critical-path identification, and rate of change introduction.

**Diagnostic cues**: Changes introduced in wrong order; blocked activities waiting for upstream completion; rework from changes made too early; insufficient stabilisation time between phases; schedule pressure driving out-of-sequence execution.

**Typical failure mode**: Sequencing plan exists but is overridden by deadline pressure; prerequisites are documented but not enforced; dependencies are missed or not made explicit; change rate increases because early phases were inefficient, creating cascade overload.

### II. Capacity & Resources
Implementation requires resources: people with capability, tooling and systems, budget, and supporting infrastructure. Capacity that is insufficient creates bottlenecks that slow implementation and create quality shortcuts. Capacity that is misaligned (skills don't match needs, tools don't support processes, budget is misaligned with actual costs) creates inefficiency and workarounds. Capacity constraints are often not surfaced: frontline workers absorb overload, adopt shortcuts, or work off-hours, reporting on-schedule delivery while quality decays and burnout accumulates. A well-resourced implementation supplies sufficient capacity matched to need, with visibility of constraints and mechanisms to address them. A poorly resourced implementation creates hidden overload, invisible shortcuts, and gradual quality degradation.

**Definition**: The human, technical, organisational, and financial resources available to support implementation, including capability alignment, tooling readiness, budget sufficiency, and mechanisms to scale capacity.

**Diagnostic cues**: Staff report overload; timeline slips accumulate; quality shortcuts are discovered; error rates increase; staff turnover increases; workarounds multiply; off-hours work becomes normal.

**Typical failure mode**: Resource plan exists but does not include ramp-up; tooling is not ready until after implementation should start; training is insufficient or occurs too late; budget is insufficient and requests for more are denied; constraint visibility is low, so workarounds absorb overload silently.

### III. Resistance & Compliance
Change creates resistance. Resistance can be active (overt refusal, sabotage) or passive (selective non-compliance, reinterpretation, quiet continuation of old practices). Passive resistance is common and invisible: staff know the new process but continue using the old way because it is faster or familiar; reported compliance is high while actual practice continues unchanged. Gaming creates the appearance of compliance: staff perform the new process when observed but revert to old practice when unobserved. Resistance emerges from multiple sources: it may be rational (new process doesn't work for my context), political (resistance to authority imposing change), structural (incentives favour old way), or cultural (new way violates norms). Resistance that is surfaced can be addressed. Resistance that is invisible hardens into shadow systems.

**Definition**: The range of explicit and implicit responses to implementation, including active opposition, passive non-compliance, gaming, reinterpretation, selective compliance, and alignment that is performed but not genuine.

**Diagnostic cues**: Compliance reports are high but operational observations show continuation of old practice; staff describe workarounds or shortcuts; escalation reports increase; variability in compliance across sites or teams; staff interviews reveal different accounts of what is being done than formal reports suggest.

**Typical failure mode**: Resistance is treated as individual failure or defiance rather than as signal of design problem; enforcement is increased without addressing underlying drivers; compliance is monitored without verifying that monitored behaviour reflects actual practice; monitoring becomes theatre to demonstrate compliance rather than to surface truth.

### IV. Workarounds & Adaptations
When specified process encounters real-world constraints, frontline implementers adapt. Adaptation can be healthy (local problem-solving that achieves intent despite constraint) or degrading (bypassing safety controls, inverting intent, creating system-wide fragmentation). Adaptation that is visible can be reviewed and either formalised or corrected. Adaptation that is invisible becomes shadow process: the official process exists on paper while actual practice operates through informal variants. Workarounds can be temporary (until constraint is removed) or permanent (constraint is never removed, workaround becomes standard practice). Workarounds that emerge in response to capacity constraint are often sustainable locally but create system-wide fragmentation or safety risk when multiplied across contexts.

**Definition**: Informal modifications to specified implementation, including local reinterpretation, temporary patches, contingencies, shortcuts, and unapproved process variants that emerge from constraint, capability gap, or structural misalignment.

**Diagnostic cues**: Process maps do not match observed practice; staff describe "how we actually do it" differently from documented process; incident reports contain evidence of non-standard procedures; observation reveals shortcuts or variants; interviews surface informal guidance that differs from formal process.

**Typical failure mode**: Workarounds emerge due to unaddressed constraint; workaround is locally efficient but globally problematic (fragmentation, safety risk, equity impact); workaround becomes normalised and formalisation is not completed; when constraint is finally addressed, workaround persists because it is now embedded in practice and identity.

### V. Feedback & Monitoring
Implementation monitoring creates visibility. Monitoring that is designed poorly creates the appearance of implementation without detecting divergence: metrics show compliance while practice diverges; data is collected but does not reach decision-makers; escalation pathways exist on paper but are not used; corrective actions are planned but not executed. Monitoring that is designed well establishes the facts of what is happening, surfaces divergence, triggers escalation, and closes the loop: issues reach decision-makers, decisions are made, actions are taken, and monitoring confirms that actions had effect. The quality of monitoring determines whether feedback loops are real or performative.

**Definition**: The mechanisms through which implementation status is made visible, including metrics design, data collection, escalation pathways, decision-maker access, and loop closure (issue surfaced → action taken → outcome monitored).

**Diagnostic cues**: Implementation metrics exist but do not reflect actual practice; data is collected but not acted on; escalation reports are filed but issues are not resolved; management reports show on-track delivery despite operational concerns; no mechanism exists to verify that reported compliance reflects actual behaviour change.

**Typical failure mode**: Compliance metrics are optimised; staff game metrics; data collection is high-volume but low-quality; feedback reaches decision-makers only through formal channels that are slow and politicised; corrective actions are planned but not tracked; loop closure rate is low.

### VI. Portfolio & Tempo
Multiple implementation initiatives rarely run in isolation. Parallel implementations share resources, create interdependencies, and interact in ways that override individual change logic. A portfolio that is well-managed sequences initiatives to manage resource contention, makes interdependencies explicit, monitors interactions, and adjusts tempo when cascade effects appear. A portfolio that is poorly managed overloads the system: implementation teams compete for scarce resources, interdependencies create hidden blockers, interactions cause cascade failures, and tempo is maintained despite mounting pressure. Portfolio-level Hiddens include: interactions are not designed (they are hoped to be independent but turn out not to be); cascade effects appear chaotic but are actually deterministic (two implementations that interact in a specific way create a predictable failure pattern); tempo is maintained despite mounting evidence that the system is overloaded, creating brittle execution and high failure risk.

**Definition**: The management of multiple concurrent implementation initiatives as a portfolio, including sequencing, resource allocation, interdependency mapping, interaction design, cascade management, and tempo calibration.

**Diagnostic cues**: Resource contention; initiative interdependencies not mapped; unexpected interactions between parallel implementations; cascade failures that appear chaotic; tempo is maintained despite escalating error rates; high-impact failures that could have been predicted if interactions had been designed.

**Typical failure mode**: Portfolio is treated as collection of independent initiatives; interdependencies are documented but not actively managed; interactions are discovered post-hoc rather than designed; cascade effects are treated as unforeseeable rather than as natural consequences of coupling; tempo is driven by deadline pressure rather than by system capacity and interaction risk.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- Canonical baseline: 6 meta-categories × 5 types = 30 core types.
- This framework: 30 types (canonical).
- Mapping back to baseline: Not required.

## 3.1 Types (Category I: Sequencing & Ordering)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 1 | Prerequisite Sequencing | Identifying and enforcing prerequisite activities that must complete before downstream activities can proceed. | Are prerequisites explicit? Are they tracked? Do planning systems enforce or document dependencies? | Prerequisites exist on paper but are not enforced; downstream work begins before prerequisites are complete; rework cascades. |
| 2 | Phase-Gate Review | Formal checkpoints at which implementation phase completion is assessed before proceeding to next phase. | Do phase gates exist? Are they used to validate readiness or bypassed to maintain schedule? Are gate criteria known and applied? | Gates are established but overridden under schedule pressure; "passing" gates without assessing readiness; gate reviews become theatre. |
| 3 | Stabilisation Intervals | Planned duration between major change introductions to allow systems and people to stabilise and learning to accumulate. | Is stabilisation time built into plans? Is it protected or compressed? Do schedules allow for unexpected issues or rework? | Stabilisation intervals are planned but compressed; insufficient time for learning or stabilisation; next change is introduced before previous is stable. |
| 4 | Dependent Activity Blocking | Recognition and management of critical-path activities where downstream work is blocked until upstream work completes. | Are blocking dependencies identified? Is there visibility of which activities are critical-path? Are blocked activities tracked and escalated? | Blocking dependencies are not explicit; activities wait without escalation; teams are not aware why work is blocked; schedule slack is not visible. |
| 5 | Change Rate & Tempo | The pace at which implementation is being introduced relative to organisation's ability to absorb and stabilise change. | Is change rate calibrated to absorption capacity? Does the organisation adjust tempo when overload appears? Are accumulated changes being stabilised? | Change rate is driven by external deadline rather than by system capacity; tempo is maintained despite mounting errors and quality shortcuts; overload is silent. |

## 3.2 Types (Category II: Capacity & Resources)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 6 | Workforce Allocation & Sufficiency | The quantity and skill-mix of human resources allocated to implementation. | Are required skills identified? Is allocation sufficient to meet plan? Do staff have bandwidth or are they overallocated? Are skill gaps evident? | Plan assumes staffing that does not materialise; allocated staff are pulled to other priorities; skill gaps are not surfaced; overload is not reported. |
| 7 | Tooling & System Readiness | Availability and readiness of supporting tools, systems, and technical infrastructure to enable new processes. | Are tools needed for implementation identified? Are they ready before implementation starts? Do tools adequately support intended process? | Tooling is not ready until after implementation begins; tools have capability gaps; staff use workarounds because tooling is insufficient. |
| 8 | Training & Capability Development | Availability of training, mentoring, and structured capability development to equip implementation teams. | Is training available before implementation starts? Does training match actual implementation needs? Is follow-up or reinforcement available? | Training occurs too late or misses key competencies; training is generic rather than context-specific; no reinforcement or coaching during early implementation. |
| 9 | Budget & Financial Sufficiency | Availability of financial resources to cover the full cost of implementation including rework, contingency, and extended timelines. | Are true implementation costs estimated? Is budget sufficient or is it optimistic? Are cost overruns being absorbed by cutting scope or quality? | Budget is optimistic and insufficient; cost overruns force scope reduction or quality shortcuts; no contingency for rework or learning. |
| 10 | Supporting Infrastructure & Governance | Availability of supporting services (HR, IT, facilities, governance approval processes) that unblock implementation. | Are supporting services engaged? Do they have capacity for implementation demands? Are approval bottlenecks limiting implementation? | Supporting services are not engaged or have no spare capacity; approval processes are slow; infrastructure becomes a hidden bottleneck. |

## 3.3 Types (Category III: Resistance & Compliance)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 11 | Active Resistance & Opposition | Overt, deliberate actions to prevent, slow, or delegitimise implementation. | Are there explicit statements of opposition? Are there actions to block or disrupt implementation? Is resistance escalated? | Resistance is treated as personal defiance rather than as signal of design problem; opposing arguments are dismissed; escalation is punitive rather than diagnostic. |
| 12 | Passive Non-Compliance | Non-adoption of new process or continued use of old processes despite formal announcements of change. | Do staff report using new process? Do observations show old process continuing? Are there explanations for why new process is not used? | Reported compliance is high but observation shows old process; reasons for non-compliance are not surfaced; compliance metric is high while actual behaviour change is minimal. |
| 13 | Selective Compliance & Gaming | Adoption of new process in some contexts (observed, measured, high-stakes) while reverting to old process in others (unobserved, unmeasured, low-stakes). | Is new process used when observed but not when unobserved? Do staff know how to game metrics? Are there contexts where pressure to show compliance is high? | Compliance appears high in measured contexts but observed practice shows variation; staff gaming metrics; monitoring becomes theatre because staff adapt behaviour when observed. |
| 14 | Reinterpretation & Drift | Gradual reinterpretation of policy intent or process specification to align with local context, existing incentives, or staff preference. | Does implementation vary across contexts? Is variance due to legitimate adaptation or to drift? Are stakeholders aware of drift direction? | Reinterpretation is not tracked; drift accumulates; learning does not occur because drift is not named; implementation diverges from intent without visibility. |
| 15 | Legitimacy Resistance | Resistance rooted in lack of trust in policy, decision process, or decision-maker, or because change is perceived as illegitimate. | Do staff believe the change is needed? Do staff trust decision-makers? Is the change seen as aligned with organisational values? | Resistance is attributed to obstinacy rather than to legitimacy questions; legitimacy concerns are not addressed; trust is assumed rather than earned. |

## 3.4 Types (Category IV: Workarounds & Adaptations)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 16 | Temporary Bypass & Contingency | Short-term workarounds used while constraints are being resolved, intended to be temporary until permanent solution is in place. | Is the bypass temporary or indefinite? Is the constraint actively being resolved? Is there a timeline for returning to intended process? | Temporary bypass becomes permanent; constraint is never resolved; workaround becomes standard practice and formalisation is not completed. |
| 17 | Capability-Gap Workaround | Informal modification to process because staff lack capability or tools to execute process as intended. | Are capability gaps identified? Is there a plan to build capability? Are workarounds being used as a proxy for capability development? | Capability gaps are not surfaced; workarounds absorb the gap; staff do not develop intended capability because workaround works locally; system-wide capability gap persists. |
| 18 | Constraint-Driven Adaptation | Modification of process because specified process assumes conditions (capacity, resource, time, authority) that do not hold in actual context. | Are constraints identified? Are they structural (system limitation) or temporary? Is the adaptation aligned with intent despite the constraint? | Constraints are not made explicit; adaptation appears to be deviation; intent of adaptation is not documented; similar constraints in other contexts are not known. |
| 19 | Unintended Process Variant | Adoption of informal process variant that was not explicitly designed and that emerges from local problem-solving, preference, or misunderstanding. | Are variants being used? How did they emerge? Are they effective locally? Are they creating system-wide fragmentation? | Variants are hidden; they appear in incident reports but are not systematically tracked; fragmentation is increasing; learning about why variants are used is absent. |
| 20 | Normalised Workaround | Workaround that was initially temporary but has become embedded in practice and is now treated as standard process. | Was this originally a workaround? When was it intended to be temporary? Is there a plan to formalise or retire it? Is anyone trying to return to intended process? | Workaround has been in place for years; original temporary status is forgotten; no one is pushing for return to intended process or formalisation. |

## 3.5 Types (Category V: Feedback & Monitoring)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 21 | Compliance Metric Design | Metrics intended to measure whether implementation is occurring as intended. | What is being measured? Does the metric reflect actual behaviour or only reported/observed behaviour? Is metric gaming possible? | Metric measures reported compliance rather than actual behaviour change; staff can game the metric; metric compliance is high while actual practice diverges. |
| 22 | Data Collection & Quality | Mechanisms for collecting evidence of implementation status, including timeliness, accuracy, and completeness. | What data is being collected? How often? Is it accurate? Is it complete or is there selection bias? | Data is collected late; data quality is low; data is complete in some areas but missing in others; no one validates whether data matches reality. |
| 23 | Escalation Pathway & Visibility | The mechanism through which implementation issues, risks, and divergence reach decision-makers. | Do escalation pathways exist? Are they used? Do issues reach appropriate decision-level? Is visibility filtered? | Escalation pathways exist but are slow or politicised; issues are filtered before reaching decision-makers; decision-makers are not aware of problems until they become crises. |
| 24 | Corrective Action & Loop Closure | The decision and execution of actions intended to remedy implementation divergence, including tracking of effectiveness. | When issues are escalated, are decisions made quickly? Are actions taken? Is effectiveness measured? | Issues are escalated but actions are slow or absent; corrective actions are planned but not executed; no measurement of whether action had effect. |
| 25 | Feedback Loop Fidelity | The completeness of the feedback cycle: issue identified → escalated → decision made → action taken → outcome monitored. | Is every stage of the feedback loop operational? Where does the loop break? Is loop closure rate measurable? | Loop breaks at escalation, decision, action, or monitoring stage; many issues are identified but not escalated; many escalations do not lead to action; many actions are not measured. |

## 3.6 Types (Category VI: Portfolio & Tempo)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 26 | Resource Contention & Allocation | The management of shared resources across multiple concurrent implementations, including prioritisation and trade-off logic. | Are shared resources tracked? Is prioritisation clear? When work competes for resources, how is allocation decided? | Allocation is unclear; work competes without explicit prioritisation; resources are claimed by higher-profile initiatives; less visible work is starved. |
| 27 | Interdependency Mapping & Management | Explicit identification of dependencies between implementation initiatives, including sequencing and critical-path logic. | Are interdependencies mapped? Are they actively managed or just documented? Are blocked dependencies causing timeline slips? | Dependencies are not mapped; blocked work is not escalated; initiatives assume independence but are actually coupled; delays in one initiative cascade to others. |
| 28 | Interaction Design & Testing | Deliberate design and testing of how parallel implementations interact, including intended synergy and unintended conflict. | Are interactions between initiatives being designed? Is there a model of what should happen? Have interactions been tested? | Interactions are hoped to be benign but are not designed; unexpected interactions appear; cascade effects are blamed on bad luck rather than undesigned coupling. |
| 29 | Cascade Effect Recognition | Detection and management of second-order effects where one implementation change triggers unintended consequences in adjacent systems or processes. | Are cascade effects being monitored? Can the cascade path be traced? Is there a model of why cascade occurred? | Cascade effects appear random; root cause of cascade is not understood; correcting one cascade creates another; system-level interaction patterns are not learned. |
| 30 | Portfolio Tempo & Absorption | The overall pace of portfolio implementation relative to organisational absorption capacity, including mechanisms to slow or stop implementation. | Is tempo monitored? Is there a signal that the organisation is overloaded? Can tempo be adjusted if needed? | Tempo is driven by external deadline rather than by absorption capacity; organisation is overloaded but pace is maintained; people absorb overload silently; cascade failures mount. |

## 3.7 Extending the Taxonomy

| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | 30 types organised in 6 categories (5 types per category). This structure is aligned with the Analytical Series canonical model. Extensions should preserve this structure or provide explicit mapping back. |
| Domain-specific refinement | Implementations may include domain-specific types (e.g., clinical protocol implementation includes "Patient Safety Monitoring" type; software deployment includes "Rollback Procedure" type). Record domain-specific types as extensions and map them back to canonical categories. |
| Preserving mappability | When extending the taxonomy, ensure new types can be mapped back to one or more of the six canonical meta-categories. This preserves comparability across frameworks and domains. |
| Structural invariants | Do not break the six meta-category structure without explicit justification. If you have more than 30 types, organise them as nested sub-categories or mark explicitly as extensions. |
| Periodic reassessment | Review taxonomy completeness every 12 months or after 5–10 implementations. Identify frequently-used types that are not in the canonical list; consider promoting them to core taxonomy in next version. |
| Versioning & governance | Changes to the canonical 30-type taxonomy are versioned at major version increment (v2.0). Extensions and domain-specific refinements can be captured in minor versions (v1.1) without changing the core structure. |

---

# 4. Cross-Cutting Dimensions of Any Implementation

## 4.1 Dimensions Table (mandatory)
| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| 1. Scope & Coverage | The breadth of population, systems, and locations covered by implementation. | Narrow (single team/location) → Broad (organisation-wide, multi-site, multi-sector). Count of affected teams/locations/roles; % of workforce affected; number of systems touched. | What % of the organisation is affected? Is it a single-site or multi-site implementation? | Narrow scope is easier to manage but may reduce benefit; broad scope is harder to manage but may create system-wide benefit. Check whether scope is intentional or accidental. |
| 2. Fidelity & Drift | The degree to which actual implementation matches intended specification. | High fidelity (practice matches spec closely) → High drift (practice differs substantially from spec). Compare documented process to observed process; measure variance in key decision points or actions. | What % of observed practice matches the specification? What is the magnitude of largest deviation? Is drift direction or random variance? | High drift indicates problems (resistance, adaptation, constraint, misunderstanding) that need diagnosis. Drift can be intentional (good adaptation) or unintended (resistance, ignorance, constraint). |
| 3. Tempo & Sequencing | The pace of implementation introduction and the sequencing logic. | Slow roll-out (phased, months between phases) → Fast roll-out (rapid, weeks or simultaneous). Count of concurrent changes; timeline from announcement to full implementation; change rate per month. | How many changes are being introduced per week/month? How many are concurrent? Is there stabilisation time between phases? | Fast tempo is efficient but increases risk of cascade failure and quality compromise. Slow tempo reduces risk but extends time and can allow drift. Match tempo to absorption capacity. |
| 4. Capacity & Constraint | The availability of resources relative to the requirements of implementation. | Abundant (excess capacity, can absorb disruption) → Scarce (insufficient capacity, requires workarounds and shortcuts). Compare available capacity to required capacity across workforce, budget, and tooling. Measure utilisation rates and staff workload. | Are staff overallocated? Is tooling ready? Is budget sufficient? What is the utilisation rate? Are constraints being absorbed silently? | Scarce capacity forces workarounds and shortcuts that can degrade quality and create safety risk. Abundant capacity allows proper testing and learning. Capacity constraints that are not surfaced generate Hiddens. |
| 5. Monitoring & Feedback | The quality and completeness of mechanisms to surface implementation status and enable corrective action. | Weak (minimal monitoring, slow feedback, no corrective action) → Strong (comprehensive monitoring, real-time feedback, active corrective action). Count of metrics; data collection frequency; escalation pathway clarity; corrective action closure rate. | What metrics exist? How often is data collected? Does feedback reach decision-makers? Are corrective actions being taken? | Weak monitoring creates Hiddens: divergence is not detected, drift accumulates, learning is disabled. Strong monitoring enables rapid course correction and supports learning loops. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | Phased Roll-Out Momentum | Each phase completes on time and on budget; confidence grows; each phase is larger than previous. | Early phases succeed with energy and enthusiasm; success breeds visibility and support; later phases scale up because early phases worked. Later phases inherit residual issues from early phases but scale-up logic assumes clean slate. | Momentum can drive successful scaled implementation but can also mask residual issues. If early phases have unresolved workarounds, scaling-up amplifies the problems. | Monitor cumulative issues from each phase before proceeding to next; gate each phase on residual-issue closure, not just timeline achievement. |
| 2 | Capacity Exhaustion & Overload | Workload accumulates faster than completion; timelines slip; error rates increase; staff report overload; quality shortcuts emerge. | Implementation teams are fixed size but work expands (rework, scope creep, learning curve); no mechanism to increase capacity or reduce scope; team absorbs overload without escalation. | Overload hidden leads to burnout, quality degradation, and safety risk. Overload visible creates pressure to reduce scope or slow tempo. Escalating overload inverts implementation logic. | Establish capacity monitoring with escalation triggers; when utilisation exceeds threshold, trigger scope reduction or timeline extension; do not allow sustained overload to persist. |
| 3 | Silent Adaptation | Observed practice gradually diverges from specification without any formal change request or approval. | Frontline staff adapt process to local context, existing constraints, or preference; adaptation works locally and solves problems; no one surfaces the divergence formally. Over time, multiple small adaptations accumulate and implementation is materially different from specification. | Silent adaptation can mask needed changes (if adaptation is good, it should be formalised) and can mask degradation (if adaptation is work-around for unaddressed constraint). When adapted practice spreads across contexts, fragmentation increases. | Establish regular practice reviews; compare documented process to observed practice; when divergence is found, explicitly decide: formalise, constrain, or address underlying driver of adaptation. |
| 4 | Resistance Activation | Resistance that was initially low or suppressed becomes active: staff begin to openly articulate concerns, escalate issues, or slow their work. | Resistance drivers accumulate (change is not delivering promised benefit, burden is higher than expected, trust is broken); staff shift from compliance to active questioning. | Resistance activation can be healthy (issues are surfaced) or problematic (if driven by misunderstanding or low legitimacy). In either case, surfaced resistance is addressable. Suppressed resistance hardens into passive non-compliance. | When resistance activates, treat as information signal rather than defiance; investigate drivers; address underlying concerns (not just suppress opposition); rebuild legitimacy if trust is broken. |
| 5 | Monitoring Decay | Monitoring that was intensive at launch becomes less frequent, data quality degrades, escalation pathways are used less often. | Initial intensity can be difficult to sustain; competing priorities pull focus; data collection becomes routine and quality drops; escalation fatigue reduces usage. | Monitoring decay creates blind spot: implementation may still be going well, but lack of data means divergence cannot be detected. Decay often signals that early issues have been resolved and intensity can be reduced, but that judgment is made without data. | Establish baseline monitoring intensity; plan for reduction as implementation matures but only if data supports the case; do not let monitoring decay accidentally without explicit decision. |
| 6 | Feedback Loop Collapse | Issues are identified and escalated but corrective actions do not occur; escalation reports accumulate without resolution. | Decision-makers acknowledge issues but do not fund corrective actions; corrective actions are planned but competing priorities prevent execution; actions are taken but not measured, so feedback does not close. | Loop collapse is a key Hiddens generator: issues are documented but not resolved, creating false assurance (the organisation is aware) without actual improvement (the organisation is acting). Loop collapse often signals governance failure (authority to correct issues is unclear, or authority is blocked). | When loop collapse is detected, escalate to governance; clarify authority for corrective action; make decision-making faster and more visible; track corrective actions to closure; measure impact of actions. |
| 7 | Decision-Implementation Divergence | The same decision is interpreted and implemented differently across teams or contexts. | Decision is made centrally and communicated broadly; local interpretation adapts decision to context or existing practice; divergence is not detected because each context reports compliance. | Divergence creates fragmentation: the organisation is executing multiple different interpretations of a single decision, reducing coherence and system-wide benefit. When divergence is large, the organisation may not be implementing the decision at all, just maintaining appearance of implementation. | Establish decision clarification workshops; ensure all implementing teams have aligned interpretation of intent and constraints; monitor variance in implementation across contexts; periodic re-alignment if variance grows. |
| 8 | Cascade & Interaction | One implementation creates unintended consequences or amplifies/dampens another implementation. | Two implementations are executed in parallel without explicit interaction design; they are assumed independent but actually have coupling (they compete for resources, share affected staff, create contradictory incentives, or create joint third-order effects). | Cascade effects can override individual implementation logic: two reasonable changes can combine to create failure. Cascade patterns are often stable: if two implementations interact badly once, they will interact badly again unless deliberately decoupled. | Identify implementation interdependencies early; design interactions explicitly; when interdependencies are high, sequence implementations rather than running in parallel; monitor for cascade effects; when cascade appears, separate implementations or redesign interaction. |
| 9 | Workaround Hardening | Workaround that was initially temporary becomes standard practice; people forget it is a workaround and treat it as intended process; formalisation is deferred indefinitely. | Workaround solves an immediate problem; it works well enough locally; no one pushes for formalisation (the constraint may be permanent, or formalisation may be difficult); time passes and the workaround becomes normal. | Hardened workaround can mask unaddressed constraint: if the workaround were removed, the constraint would re-emerge and implementation would fail. Workaround may be degrading in ways that are not visible (safety risk, equity impact, system-wide fragmentation). | When workarounds are discovered, explicitly decide: formalise (add to standard process), retire (address underlying constraint), or constrain (use only in specified contexts). Track status of decision; when deferred, re-assess periodically. |
| 10 | Crisis Reversion | During crisis or high-pressure period, staff revert from new process to old trusted process, often without explicit approval or awareness. | New process is not yet automatic or trusted; old process is faster, more familiar, more reliable under pressure; when stress increases, people default to what works. After crisis, it can be difficult to re-establish new process because people have re-experienced the comfort of old way. | Reversion can be rational (old way is better under crisis) or problematic (new way did not fully replace old way, so old way was never really gone). When reversion occurs, it reveals trust gaps in new process or unaddressed capability/speed advantages of old process. | Design new process to be at least as fast and reliable as old process in normal conditions and under pressure; maintain enough old-way competency that reversion does not cause crisis (but design so reversion is not attractive). When reversion happens, investigate why and address drivers (speed, reliability, trust) not just suppress reversion behaviour. |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | Implementation-Intervention (I-A) | The interface where the designed intervention is being operationalised into actual practice; where design intent must be translated into operational action. | Are there mechanisms to clarify intervention intent before implementation begins? Is implementation design informed by operational reality? When implementation begins, are there channels for clarifying ambiguities in intervention design? | Intervention specification is handed to operations team; operations team reviews feasibility and raises questions; design team responds; implementation proceeds with shared understanding. OR: Intervention specification is handed to operations team; no dialogue; operations team interprets alone; gaps in understanding emerge during implementation. |
| B | Implementation-Governance (I-B) | The interface where governance mechanisms monitor implementation fidelity and escalate when divergence exceeds acceptable bounds; where governance oversight meets implementation reality. | Does governance have visibility of implementation status? Does governance have authority to halt implementation if serious divergence is detected? Are escalation pathways clear? Does governance conduct periodic live-practice audits or only review reported metrics? | Governance conducts quarterly implementation reviews using reported metrics; operations confirms all on track; governance approves continuation. OR: Governance maintains real-time dashboard of implementation metrics; when metrics diverge from plan, governance escalates to programme leader; programme leader diagnoses and course-corrects. |
| C | Implementation-Evidence (I-C) | The interface where implementation outcomes are being measured and monitored; where data about implementation effectiveness feeds back to decision-makers and learning loops. | Are the right metrics being collected to assess implementation effectiveness and fidelity? Does evidence reach decision-makers in time to enable course correction? When evidence shows problems, does it trigger investigation and action? Can the organisation learn from implementation experience? | Implementation is complete; no evidence is collected about whether it achieved intended outcomes; organisation cannot assess effectiveness. OR: During implementation, metrics are collected weekly about progress and problems; evidence reaches leadership daily; issues trigger immediate investigation; learning accumulates and informs adjustments. |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links

**Inputs expected**: 
- Intervention specification and design (from Interventions framework)
- Decision intent, scope, and success criteria (from Decisions framework)
- Current operational processes, capacity, and constraints (from Processes, Capacities, Systems frameworks)
- Governance structures, authority, and escalation pathways (from Governance framework)
- Risk context and failure modes (from Risk and Failures frameworks)
- Evidence standards, data quality, and monitoring feasibility (from Evidence, Metrics frameworks)
- Stakeholder perspectives, incentives, and resistance drivers (from Power, Incentives, Agents frameworks)
- Organisational capacity for learning and adaptation (from Learning and Adaptation framework)

**Outputs provided**:
- Implementation gap inventory and risk register (fed to Risk, Governance frameworks)
- Resistance and adaptation mechanisms (fed to Power, Incentives, Communications frameworks)
- Monitoring and feedback requirements (fed to Evidence, Metrics, Governance frameworks)
- Capacity constraints and resource needs (fed to Capacities, Resources frameworks)
- Implementation dynamics and patterns (fed to Learning and Adaptation, Risk frameworks)
- Hiddens sources and evidence of invisible practice divergence (fed to Hiddens, Evidence frameworks)

## 7.2 Crosswalk Table

| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| Interventions | Design specification, intended mechanism, expected outcomes, sequencing logic | Implementation fidelity assessment, actual mechanism vs. intended mechanism, outcome variance explanation, learning about what changes when design meets reality | Designing intervention AND assessing how well designed intervention is being executed |
| Decisions | What was decided, by whom, when, with what authority, with what constraints | How the decision is being implemented operationally, divergence between decision intent and operational practice, decision-implementation fidelity | Making a decision AND managing the transition to operationalised decision |
| Governance | Authority structures, oversight mechanisms, escalation pathways, decision-right allocation | Whether governance mechanisms are detecting implementation divergence, whether escalation pathways are functioning, governance-implementation alignment | Governing the implementation process, ensuring governance oversight closes feedback loops |
| Risk | Risk register, failure modes, consequence levels, escalation thresholds | New risks created by implementation itself, risks that emerge from interaction effects, implementation risks that need governance escalation | Understanding implementation-related risks and managing implementation risk portfolio |
| Processes | Current process documentation, process maps, procedural specifications | Implementation of process change, process fidelity during transition, process variant emergence and management | Redesigning processes AND implementing process change |
| Learning and Adaptation | Organisational learning capability, update mechanisms, adaptation discipline | What has been learned from implementation experience, whether learning is being captured, how adaptation is designed and measured | Implementing changes AND designing systems to learn from implementation experience |
| Evidence | Metrics available, data quality, timeliness, reliability | What implementation metrics exist, what data is being collected to surface implementation status and divergence | Collecting evidence about whether implementation is occurring as intended |
| Power and Incentives | Power structures, incentive systems, who benefits/loses from change | How power structures shape implementation choices, how incentives drive or resist implementation, where incentive misalignment creates implementation problems | Understanding why implementation diverges from intent (power and incentive dynamics) |
| Communications | How change is being communicated, narratives around change, legitimacy | Whether implementation narratives match operational reality, whether compliance theatre is being performed, what stories people believe about implementation | Communicating about change AND managing narrative alignment with operational reality |

## 7.3 Integration Questions by Framework

This section integrates Implementation with all 36 canonical frameworks from the Analytical Series Operating Guide v2.5 §3.2. The questions guide how to query other frameworks when implementing this one, and what outputs to expect for shared registers.

| Framework (from OG v2.5 §3.2 canonical list) | Group | Stage | Integration questions (what this framework should ask / check to integrate with Implementation) | Outputs / artefacts to pull in | Notes (interfaces, dependencies, visibility risks) |
|---|---|---|---|---|---|
| Situations | G1 Framing | Upstream | What is the operational situation into which implementation is being introduced? What contextual factors affect implementation feasibility and success? | Situation naming statement; context constraints; baseline operational state | Implementation must understand the context it is entering; situational change may affect implementation viability. |
| Context & Classification | G1 Framing | Upstream | How is the situation classified (crisis, normal operations, transition)? What operational constraints does context impose on implementation? | Context classification; operational constraints; timing windows | Implementation strategy must match context (crisis implementation is different from steady-state implementation). |
| Boundaries | G1 Framing | Upstream | What are the system boundaries within which implementation operates? Where are boundary permeabilities that create coupling with external systems? | System boundary definition; interface mapping with external systems | Implementation that crosses system boundaries requires managing boundary interfaces and external coupling. |
| Dimensions | G1 Framing | Upstream | What are the primary dimensions of the situation (scale, tempo, complexity, coupling) that affect implementation? | Dimension profile of situation | Implementation design must align with situation dimensions; misalignment creates implementation friction. |
| Realities | G1 Framing | Upstream | What is the lived operational reality (not the stated policy reality) into which implementation is being introduced? | As-is operational practice; gap between stated and lived reality | Implementation must account for lived reality, not just stated policy; ignoring lived reality creates resistance and workarounds. |
| Scale | G1 Framing | Upstream | At what scale is implementation occurring (team, department, organisation, multi-organisation)? What scaling challenges arise? | Scale level; number of affected entities; geographic spread | Implementation challenges increase with scale; single-site implementation is fundamentally different from multi-site; scaling creates interaction and coordination complexity. |
| Time | G1 Framing | Upstream | What is the time horizon for implementation? What temporal constraints or opportunities exist? What is the acceptable timeline? | Temporal window; critical dates; acceptable timeline range | Implementation tempo must align with time horizons; external deadlines drive implementation choices; temporal pressure affects quality. |
| Systems | G2 Mechanism | Upstream | What are the key systems that implementation must integrate with or change? What are system interdependencies and coupling? | System map; interdependencies; integration points | Implementation of one system affects coupled systems; system-level impacts must be designed and monitored. |
| Relations & Dependencies | G2 Mechanism | Upstream | What are the key dependencies and relations that implementation must navigate? Where are critical interdependencies? | Dependency map; critical relations; integration requirements | Implementation must make explicit and manage dependencies; unmanaged dependencies become hidden blockers. |
| Processes | G2 Mechanism | Upstream | What are the current processes that implementation will change? What is the process redesign? How will process transition be managed? | Current process documentation; redesigned process; process transition plan | Implementation of process change requires understanding both current and future state; transition design is critical. |
| Causation | G2 Mechanism | Middle | What is the causal theory of how implementation will change outcomes? How will the designed intervention produce the intended effect? | Causal theory / logic model; mechanism chain from implementation to outcome | Implementation must be designed with explicit causal logic; if causal theory is weak, implementation success is unlikely. |
| Resources & Capacity | G2 Mechanism | Upstream | What resources are available for implementation? What is the capacity constraint? What demand-capacity alignment exists? | Resource inventory; capacity assessment; demand-capacity gap | Implementation failure often traces to capacity insufficiency; resource constraints must be explicit and managed. |
| Agents | G3 Agency | Upstream | Who are the implementers? What capability and incentives do they have? What is their role in implementation success? | Implementer roster; capability assessment; role clarity; incentive map | Implementers are not passive channels; their capability, incentives, and agency shape implementation; this must be designed. |
| Personas | G3 Agency | Upstream | What are the key personas of people who will implement or be affected by implementation? What are their perspectives and incentive structures? | Persona definitions; perspective mapping; incentive profiles | Implementation must account for persona variation; one-size-fits-all implementation fails for personas with different constraints and incentives. |
| Incentives | G3 Agency | Middle | What incentives do implementers face? Are incentives aligned with implementation intent? Where are misalignments? | Incentive structure; alignment analysis; misalignment drivers | Incentive misalignment is a primary driver of implementation divergence; must be explicitly diagnosed and addressed. |
| Power | G3 Agency | Middle | What is the power structure affecting implementation? Who can block or enable implementation? Where are power imbalances? | Power map; influence network; power holder perspectives | Power imbalances affect implementation; resistance may be rational given power position; must be designed into implementation strategy. |
| Responsibility & Accountability | G3 Agency | Middle | Who is accountable for implementation success? What are the responsibility assignments? Are they clear and credible? | Responsibility assignments; accountability structure; clarity assessment | Implementation failure often reflects unclear accountability; responsibility assignments must be explicit and matched to authority. |
| Competencies | G3 Agency | Upstream | What competencies are required for implementation? What is the competency gap? How will competency be developed? | Competency requirements; current competency assessment; development plan | Implementation requires specific competencies; gaps must be addressed through training, hiring, or simplification of implementation design. |
| Culture & Norms | G4 Meaning | Middle | What are the cultural norms and practices that implementation must navigate? Where are cultural alignments and misalignments? | Culture assessment; norm mapping; alignment analysis | Implementation that violates cultural norms faces hidden resistance; must either change norms, adjust implementation, or manage cultural friction explicitly. |
| Perspectives & Meaning | G4 Meaning | Middle | How do different stakeholders interpret the change? What meanings are assigned to implementation? | Stakeholder perspective map; meaning assignments | Different meaning assignments create different implementation realities; conflicting meanings lead to divergent implementation; must surface and address meaning conflicts. |
| Narratives | G4 Meaning | Middle | What stories are being told about implementation? Are narratives aligned with operational reality? Where is narrative-reality divergence? | Narrative map; narrative-reality audit; compliance theatre assessment | Narratives shape implementation behaviour; when narratives diverge from reality (compliance theatre), implementation fidelity breaks. |
| Communications | G4 Meaning | Middle | How is implementation being communicated? Are communications clear, timely, consistent? Do communications reach all affected parties? | Communications plan; clarity assessment; reach assessment | Implementation communications shape understanding, resistance, and engagement; poor communications create ambiguity and resistance. |
| Legitimacy | G4 Meaning | Middle | Is the change perceived as legitimate? Do stakeholders believe the decision was made correctly? Is there trust in leadership? | Legitimacy assessment; trust audit; decision-process perceived fairness | Lack of legitimacy is a driver of passive non-compliance; legitimacy must be earned through decision process, not just asserted. |
| Values | G4 Meaning | Middle | What values are at stake in implementation? Are value conflicts present? | Value alignment assessment; value conflict identification | Value conflicts (e.g., speed vs. safety, efficiency vs. equity) shape implementation choices; must be explicit and managed. |
| Beliefs | G5 Epistemics | Upstream | What beliefs do implementers and stakeholders hold about the change? Are beliefs aligned with evidence? | Belief inventory; belief-evidence alignment; belief persistence assessment | Implementation decisions are shaped by beliefs; false or outdated beliefs drive poor implementation choices; must surface and correct beliefs. |
| Evidence | G5 Epistemics | Upstream | What evidence exists about implementation approaches? Is evidence available to guide implementation design? | Evidence inventory; quality assessment; relevance to current context | Implementation should be evidence-informed; lack of evidence may require caution or experimentation. |
| Uncertainties | G5 Epistemics | Upstream | What are the key uncertainties affecting implementation? How are uncertainties being managed? | Uncertainty register; uncertainty drivers; uncertainty management approach | Uncertainties about implementation approach, feasibility, or context should be explicit; uncertainties must be reduced or managed. |
| Diagnosis & Analysis | G5 Epistemics | Middle | What diagnostic analysis has been done to understand why the current situation exists? Does diagnosis inform intervention design and implementation approach? | Diagnosis output; diagnosis quality assessment; diagnosis-design linkage | Implementation should be based on sound diagnosis; weak diagnosis often leads to implementation that addresses symptoms rather than root causes. |
| Hiddens | G5 Epistemics | Middle | What visibility failures exist in understanding implementation? What is hidden from decision-makers, implementers, or oversight? | Hiddens register; visibility failure assessment; hidden-risk inventory | Implementation creates new Hiddens (compliance theatre, silent adaptation, capacity blindness); these must be surfaced and managed. |
| Failures & Resilience | G5 Epistemics | Middle | What failure modes are possible during implementation? What could go wrong? How can resilience be designed? | Failure mode analysis; resilience design; cascade risk assessment | Implementation creates risks of new failure modes; these must be anticipated and designed for; resilience must be built into implementation design. |
| Metrics & Measurement | G5 Epistemics | Middle | What metrics are being used to assess implementation status and outcomes? Are metrics reliable and valid? | Metric definitions; data quality assessment; validity audit | Implementation metrics drive behaviour; poor metrics create gaming and theatre; metrics must be thoughtfully designed. |
| Knowledge & Learning | G5 Epistemics | Downstream | What is being learned from implementation experience? Is learning being captured and fed back to decision-makers? | Learning register; feedback loop status; learning effectiveness assessment | Implementation should generate learning that informs future improvements; learning loops must be designed and maintained. |
| Decisions | G6 Action & Control | Upstream | What decision was made that triggered implementation? Is the decision specification clear? Has the decision been communicated? | Decision document; decision clarity assessment; communication status | Implementation executes a decision; clarity and communication of decision intent are prerequisites to faithful implementation. |
| Interventions | G6 Action & Control | Middle | What interventions have been designed? Are intervention specifications clear? What is the implementation design? | Intervention specification; implementation design; design adequacy assessment | Implementation operationalises interventions; clarity of intervention specification is critical to implementation fidelity. |
| Governance | G6 Action & Control | Middle | What governance mechanisms oversee implementation? Are escalation pathways clear? Does governance close feedback loops? | Governance map; escalation pathway clarity; feedback loop closure assessment | Governance oversight of implementation should ensure divergence is detected, escalated, and corrected; governance must be designed into implementation. |
| Risk | G6 Action & Control | Middle | What risks exist for implementation failure? What is the risk management approach? How are risks being monitored? | Risk register; risk drivers; risk management plan | Implementation creates risks; risks must be identified and managed; monitoring should trigger escalation when risk thresholds are exceeded. |
| Learning and Adaptation | G6 Action & Control | Downstream | How is the organisation adapting its understanding and approach based on implementation experience? What feedback loops support learning and adaptation? | Learning loop status; adaptation rate; feedback effectiveness | Implementation should trigger learning and adaptation; learning loops must close to enable course correction and future improvement. |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)

| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---:|---|---|---|
| 1 | Compliance-Practice Decoupling | Reported compliance metrics are high while observation reveals actual practice continues unchanged or has drifted significantly. Analysis assumes reported compliance reflects actual behaviour change; actual behaviour is not verified. | Conduct live-practice audits; compare observed practice to documented process; when divergence is found, explicitly map what is happening; do not rely on reported compliance metrics alone; use sampling to verify metrics. |
| 2 | Capacity Blindness | Insufficient capacity is not surfaced; frontline workers absorb overload without reporting it or adopt workarounds that locally solve the problem while creating system-wide fragmentation. Analysis does not measure or ask about workload and capacity; overload is invisible to decision-makers. | Establish workload monitoring with escalation triggers; ask staff directly about capacity; measure time allocation and utilisation rates; when overload is detected, trigger scope reduction or timeline extension; do not allow silent overload absorption. |
| 3 | Silent Adaptation Invisibility | Street-level workers adapt specified process to local context, existing constraints, or preference without formal approval; adaptation emerges from local problem-solving and spreads through informal channels; divergence is not tracked as deliberate change. Analysis treats process as static specification and does not monitor for emergence of variants; informal adaptation is not visible to oversight. | Conduct regular practice reviews comparing documented process to observed practice; when divergence is found, investigate: is it deliberate adaptation addressing unmet constraint, or is it drift away from intent? Explicitly decide for each variant: formalise, constrain, or address underlying driver. |
| 4 | Resistance Invisibility | Active resistance is rare; passive non-compliance is common. Resistance is expressed through continued use of old processes, quiet non-adoption, re-interpretation of new process to match old way, or selective compliance. Resistance is not escalated because it does not manifest as explicit opposition. Analysis assumes non-adoption indicates lack of understanding or capacity, not resistance. | Ask staff directly about barriers to adoption; listen for explanations that indicate resistance (doesn't make sense, don't trust it, doesn't work here); create safe channels to surface resistance; when resistance is found, address drivers (legitimacy, incentive, capability, constraint) rather than suppress behaviour. |
| 5 | Feedback Loop Absence | Issues are identified and escalated but do not reach decision-makers; escalation reports are filed but do not trigger corrective actions; corrective actions are taken but are not measured. Loop breaks at any stage, creating apparent accountability (issues are documented) without actual impact (issues are addressed). Analysis assumes escalation pathways are functional when they are not; does not track loop closure. | When Tier 1 scan identifies escalation pathway, test it: trace a recent implementation issue through the pathway to see if it was escalated, if decision was made, if action was taken, if outcome was measured. If loop breaks, escalate governance failure separately. |
| 6 | Interaction & Cascade Blindness | Multiple implementations running in parallel interact in ways that are not predicted or designed. Interactions appear chaotic but are actually deterministic consequences of coupling. Analysis treats each implementation independently; does not model or monitor interdependencies; cascade effects are discovered post-hoc as failures. | Map implementation interdependencies explicitly; build interaction models of what should happen when two implementations run in parallel; monitor for cascade patterns; when cascade is detected, trace root cause back to specific interaction; use this to inform portfolio sequencing and interaction design. |
| 7 | Unintended Consequence Blindness | Implementation achieves stated outcomes (process is implemented, metrics improve) while generating negative impacts elsewhere in the system (safety risk, equity impact, workload shift, unintended behaviour). Negative impacts are not monitored because monitoring is outcome-siloed. Analysis focuses on whether target metric improves and misses second-order effects. | When implementation is designed, map potential second-order effects; design monitoring to surface these effects; when implementation is executed, monitor across multiple dimensions (not just target metric); periodically review for unintended consequences; surface them in evidence and governance. |
| 8 | Portfolio Overload Concealment | Multiple overlapping implementations create system-wide overload; workload is unsustainable; quality is degrading; error rates are increasing; people are burning out. Overload is not surfaced because: (a) each implementation reports its metrics as on track, (b) overload is absorbed by people working off-hours or cutting corners, (c) aggregate workload is not tracked at portfolio level. Analysis looks at individual implementations and does not aggregate workload across portfolio. | Establish portfolio-level workload monitoring; track cumulative demand against total available capacity; when utilisation exceeds sustainable level (e.g., >80%), trigger portfolio-level action: defer some implementations, reduce scope, extend timelines, or add resources; do not allow sustained overload to persist silently. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)

| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|
| I  Perceptual | Decision-makers and implementers have different understanding of what is being implemented; shared reality is absent. | Reported compliance is high but observation shows practice divergence; staff describe "how we really do it" differently from documented process; different sites implement same decision differently. | Compare documented implementation to observed implementation across multiple sites; interview implementers about what they understand; surface and map different interpretations. |
| II Systemic | Implementation creates structural coupling that produces unintended consequences; interactions between implementations are not designed; cascade effects are deterministic but appear chaotic. | Cascade failures when two implementations run together; seemingly unrelated changes interact badly; portfolio overload is not tracked; resource contention is not visible. | Map implementation interdependencies; model what should happen when implementations run in parallel; test models against observed outcomes; trace cascade failures back to specific interactions. |
| III Informational | Feedback loops are absent or broken; escalation pathways do not function; issues are not surfaced; monitoring is performative (metrics reported but disconnected from reality). | Escalation reports are filed but action does not occur; monitoring metrics show on-track while operational reality shows problems; corrective actions are planned but not executed. | Test escalation pathways: trace recent issues through pathway; assess if escalation reached decision-maker, if decision was made, if action was taken; map where loops break. |
| IV Temporal | Implementation timeline is optimistic; drift is gradual and unnoticed until problem is acute; early phases are assumed to be stable but residual issues are not resolved before scaling up. | Each phase completes on schedule but later phases inherit unresolved issues from earlier phases; cumulative rework is not tracked; decision to proceed to next phase is made without assessing residual-issue closure. | After each phase, conduct residual-issue closure assessment before gating to next phase; do not gate on timeline alone; track cumulative issues that are deferred. |
| V  Relational | Power imbalances shape implementation; those who benefit resist less; those who lose resist more; resistance is suppressed through authority rather than addressed through problem-solving; trust is broken. | Resistance appears to be from specific groups; no open dialogue about implementation problems; escalations about barriers are dismissed; some staff are engaged while others are withdrawn. | Map power structures; who benefits and loses from implementation; interview different stakeholder groups; assess trust in leadership; when resistance emerges, address drivers (concerns, incentives, legitimacy) not just suppress behaviour. |
| VI Ontological | Implementation is being done in the name of one narrative (e.g., "efficiency", "safety") while actually serving a different purpose (e.g., cost cutting, control); stated goals diverge from actual goals; meaning gap creates resistance and compliance theatre. | Stated implementation goal diverges from actual implementation design; implementation is perceived as "really about" something unstated; staff implement the letter of the requirement while avoiding the spirit. | Make implementation purpose explicit; surface any divergence between stated and actual goals; when goal divergence is found, address it: either change actual goals to align with stated goals, or be honest about actual goals and build legitimacy for them. |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)

| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability | Agency | Consequence | Detection interface(s) (Type A) | Remediation interface(s) (Type B) | Interaction notes (Type C) |
|---|---|---|---|---|---|---|---|---|
| Hidden-9: Compliance Theatre | H | Reported compliance masks actual practice divergence; staff appear to comply while implementation continues unchanged | Readily detectable through practice audits; appears easily but is often delayed because effort is required to verify beyond metrics | Implementer agency (willing non-compliance, re-interpretation) and decision-maker agency (willing belief in metrics without verification) | High: implementation has no effect while resources are consumed and confidence is false | Practice audits; staff interviews; decision trace-backs; observation of actual work | Governance oversight; Tier 1 feedback loop; strengthened escalation when practice divergence is found | Compliance theatre persists when oversight relies on metrics alone; requires live-practice verification. |
| Hidden-21: Capacity Blindness | H | Insufficient capacity is not reported; frontline workers absorb overload or develop workarounds; overload is invisible to decision-makers | Detectable through workload monitoring, staff interviews, fatigue and turnover metrics, error-rate increases | Implementer agency (willingness to absorb overload without reporting) and decision-maker agency (not asking about capacity) | High: burnout, quality degradation, safety risk, and error accumulation; overload is sustainable for some time before breaking visibly | Workload audits; capacity monitoring with escalation triggers; fatigue and turnover metrics; staff interviews | Capacity governance; scope reduction or timeline extension when overload is detected; transparent capacity monitoring | Capacity blindness often coexists with compliance theatre: on-time delivery is reported while people are overloaded. |
| Hidden-22: Street-Level Adaptation | H | Frontline staff adapt implementation to local context without visibility; adaptation spreads through informal channels; drift accumulates | Detectable through practice reviews comparing documented to observed process; appears progressively as divergence grows | Implementer agency: adaptive problem-solving, local constraint response, preference optimisation | Medium to High depending on direction of adaptation: healthy adaptation addresses unmet constraint and should be formalised; degrading adaptation masks unaddressed constraint or inverts intent | Practice reviews; process-variance audits; staff interviews about actual workflow | Explicit governance of variants: formalise, constrain, or address underlying driver; periodic re-alignment | Adaptation is often healthy locally but fragments implementation system-wide; requires explicit review. |
| Hidden-23: Resistance Invisibility | H | Passive non-compliance is common; staff do not explicitly oppose but quietly do not adopt new process; resistance is not surfaced | Detectable through practice audits and staff interviews; appears when trust is low or legitimacy is questioned | Implementer agency: rational evaluation of new process (doesn't work, doesn't fit, doesn't make sense) and communication barrier (unsafe to raise concerns openly) | Medium to High depending on reason for resistance: if resistance reflects design problem, it is valuable signal; if resistance reflects legitimate barrier, it requires design adjustment | Staff interviews with trust-building; practice audits; decision trace-backs; escalation of barriers | Address drivers of resistance: legitimacy questions, incentive misalignment, capability gaps, constraint recognition; do not suppress behaviour without addressing drivers | Passive non-compliance is often more persistent than active resistance because it feels like compliance but is not. |
| Hidden-24: Decision-Implementation Divergence | M | Same decision is interpreted differently across contexts; implementation varies; divergence is not detected because each context reports compliance | Detectable through multi-site implementation review; appears when implementation is geographically dispersed or involves multiple distinct teams | Implementer agency: local reinterpretation of decision to fit context; decision-maker agency: not clarifying decision intent upfront | Medium: implementation becomes fragmented; organisation executes multiple interpretations of a single decision; coherence and system-wide benefit are reduced | Multi-site audits; decision clarification workshops; implementation variance sampling; periodic re-alignment | Decision clarification workshops before implementation; agreement on critical decision elements that must be preserved; periodic re-alignment if variance grows | Divergence often emerges from ambiguity in original decision; requires up-front clarification and ongoing alignment. |
| Hidden-25: Cascade and Interaction Effects | H | Parallel implementations interact in ways that are not predicted or designed; cascade effects override individual implementation logic | Detectable through portfolio-level monitoring and interdependency modelling; appears when interactions are first engaged (during parallel execution) | Both implementer and decision-maker agency: interactions are rarely intentional; they emerge from coupling that was not anticipated | High: cascade effects can override individual implementation logic; two sound changes can combine to create failure; failure patterns are stable and will repeat if coupling is not addressed | Portfolio-level monitoring; interdependency mapping; interaction models; cascade detection through outcome variance | Portfolio sequencing to separate high-coupling implementations; interaction design for unavoidable coupling; portfolio-level governance | Cascade effects are often blamed on bad luck; are actually deterministic consequences of undesigned coupling. |
| Hidden-26: Unintended Consequences | M to H | Implementation achieves stated outcomes while generating negative impacts elsewhere (safety, equity, workload, behaviour); impacts are not monitored because monitoring is outcome-siloed | Detectable through multi-dimensional monitoring capturing second-order effects; appears over time as implementation matures | Primarily decision-maker agency: design does not account for second-order effects; may include implementer agency if workarounds are creating new problems | Medium to High depending on consequence: implementation may achieve target metric while degrading safety, equity, or system resilience | Multi-dimensional monitoring; second-order-effect scanning during design; periodic impact reviews across multiple dimensions | Consequence mapping during design; monitoring design that captures second-order effects; incident review when unintended consequences appear | Unintended consequences often emerge from siloed thinking (e.g., optimising for speed without monitoring safety). |
| Hidden-27: Equity and Differential Impact | M to H | Implementation affects different populations differently; equity impacts are not monitored; equity degradation occurs invisibly | Detectable through equity-disaggregated monitoring and impact reviews; appears when monitoring is aggregated rather than disaggregated | Can be intentional (some populations are deliberately disadvantaged) or unintentional (design doesn't account for population differences); often decision-maker agency (not asking whether impacts vary) | Medium to High depending on severity of differential impact: even unintentional equity degradation is problematic | Equity-disaggregated monitoring; equity impact assessment during design; periodic equity reviews | Equity-conscious design: ask explicitly how implementation affects different populations; disaggregate monitoring; surface and remediate equity impacts | Equity impacts are often invisible when monitoring is aggregated; requires explicit attention. |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)

1) Run the Tier 1 scan across all six Hiddens meta-categories (early pass; assume Hiddens exist) (OG v2.5 §7.1). When conducting an implementation assessment, assume that compliance theatre, capacity blindness, silent adaptation, and resistance invisibility are present unless explicitly ruled out. Scan all six categories even if early assessment suggests only some are active.

2) Shortlist candidate Hiddens; for each, rate: mechanism, reducibility, detectability, agency, consequence (OG v2.5 §7.2). Focus on the eight systematic implementation Hiddens (compliance theatre, capacity blindness, street-level adaptation, resistance invisibility, decision-implementation divergence, cascade effects, unintended consequences, equity impacts). For each, assess likelihood, severity, and detectability.

3) Assign at least one detection interface and one remediation interface per high-consequence Hidden; map interaction chains (OG v2.5 §7.2). For example: compliance theatre can be detected through practice audits (I-A interface: implementer-to-implementation observation) and remediated through governance oversight (I-B interface: governance escalation when theatre is detected).

4) Run the hiddens source analysis and record unresolved Unknowns/Hiddens (§8.1 above). When auditing implementation, do not assume what is not seen is absent; explicitly record what visibility failures prevent detection of each major Hidden category.

5) If Tier 1 symptoms point to a specific hiding mechanism, invoke the appropriate Targeted Hiddens Discovery Scan (OG v2.5 §7.5; select using Triage Matrix at §7.5.3). For example: if compliance-theatre symptoms appear, run "Suppression" scan (Family A) to understand whether theatre is unintentional (metrics are not well-designed) or intentional (staff are deliberately gaming metrics to appear compliant). If capacity-blindness symptoms appear, run "Competency Blindspot" scan (Family B) to assess whether capacity is blindness or active concealment.

6) After executing the framework protocol and any available tests/probes, re-run Tier 1 (pre-closure pass) and note deltas. Compare early Tier 1 results to pre-closure Tier 1 results. If new Hiddens have appeared or severity has increased, record as evidence of previously-hidden activity. This delta-scan often reveals which Hiddens were present early but not surfaced until testing moved from metrics review to live practice.

7) Produce Residual Unknowns (with mechanism + impact + next probe) and apply the Escalation Rule (§8.5) if any residual could change decisions, accountability, or remediation priorities. When an implementation assessment concludes, explicitly list what is still unknown about implementation fidelity, capacity, resistance, adaptation, or feedback loops. For each Unknown, specify the mechanism that prevents knowing it and the next probe that would resolve it.

## 8.5 Escalation Rule (Tier 3 – full-spectrum Hiddens escalation)

Escalate to full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests if any apply:

- **High consequence**: Implementation failure could affect safety, regulatory compliance, existential risk, or severe stakeholder harm
- **Concealment plausible**: Compliance theatre is suspected, active concealment is possible, power imbalances create incentive to hide problems
- **Contradictions persist**: Reported metrics diverge from operational observations and divergence cannot be explained by sampling error or honest misunderstanding
- **Cascades suspected**: Implementation is part of a portfolio and cascade effects are plausible; interactions have not been explicitly designed or tested
- **Repeat failure pattern**: Similar implementation has failed before in similar way; failure pattern should have been detected but was not; Hiddens from past failure are recurring
- **Evidence weak or contested**: Data about implementation status is low-quality, controversial, or based on reported metrics without verification; stakes are high enough that weak evidence is unacceptable

When any of these conditions apply, escalate implementation assessment from Tier 2 (structured deepening) to Tier 3 (full-spectrum escalation). Tier 3 includes: stronger evidence standards (multiple independent data sources, direct observation), disconfirming tests (attempts to falsify claims that implementation is proceeding as intended), active probing of Hiddens (asking directly about compliance theatre, capacity constraint, resistance), and production of refined Hiddens register with higher confidence and stronger discrimination between scenarios.

---

# 9. Application Protocol: Implementation Assessment in Seven Steps

## 9.1 Step 1: Implementation Clarification

**Objective**: Establish shared understanding of what is being implemented, the intended specification, and the baseline operational state.

**Activities**:
- Clarify the decision, intervention, or policy that is being implemented; confirm decision intent and success criteria
- Define the target population, systems, and locations affected by implementation
- Assess current operational baseline: what is the state before implementation begins?
- Identify key stakeholders and implementation actors; understand their perspectives on change
- Establish implementation timeline and key milestones

**Artefacts produced**: Implementation Clarification Summary; Decision Intent Statement; Baseline Operational Snapshot; Stakeholder Map

**Success criteria**: All parties have aligned understanding of what is being implemented, why, and what success looks like. Baseline is documented. Stakeholders are identified.

## 9.2 Step 2: Gap Analysis and Fidelity Audit

**Objective**: Understand the distance between intended specification and actual operational practice; surface compliance-practice divergence.

**Activities**:
- Compare documented specification (how implementation is supposed to work) to observed practice (how implementation is actually working)
- Assess implementation fidelity: how closely does observed practice match specification?
- Identify variants, workarounds, and adaptations that have emerged
- Investigate reasons for divergence: is it legitimate adaptation, unintended drift, or hidden resistance?
- Map scope and coverage: what % of the target population is affected? Is there geographic or demographic variation?

**Artefacts produced**: Gap Register; Implementation Variance Map; Fidelity Assessment; Workaround & Adaptation Inventory; Coverage Analysis

**Success criteria**: Key gaps are identified and mapped; practitioners understand the sources of divergence (adaptation vs. drift vs. resistance); coverage is quantified.

## 9.3 Step 3: Resistance and Adaptation Diagnosis

**Objective**: Surface explicit and implicit resistance; understand adaptation drivers; diagnose whether problems are capability gaps, constraint-driven, or intentional resistance.

**Activities**:
- Conduct staff interviews focused on barriers, concerns, and reasons for non-adoption or workarounds
- Surface passive resistance (what is not being done) and selective compliance (what is done when observed vs. unobserved)
- Investigate each workaround: is it addressing an unmet need (legitimate adaptation) or masking an unaddressed constraint?
- Map resistance drivers: legitimacy, incentive misalignment, capability gaps, constraint recognition
- When legitimate adaptation is found, explicitly decide: formalise as standard process, constrain to specific contexts, or address underlying driver

**Artefacts produced**: Resistance & Adaptation Catalogue; Resistance Driver Map; Adaptation Decision Log; Legitimacy Assessment

**Success criteria**: Major sources of resistance and adaptation are identified; drivers are diagnosed; decisions are made about how to handle adaptation (formalise, constrain, address driver).

## 9.4 Step 4: Capacity and Constraint Audit

**Objective**: Assess whether resources and capacity are sufficient to execute and sustain implementation; surface constraints and overload.

**Activities**:
- Audit workforce allocation: is staffing sufficient and allocated to implementation activities?
- Assess tooling readiness: are supporting systems and tools available and adequate?
- Map skill and capability gaps: what training and capability development is required?
- Measure workload and utilisation: are staff overallocated? Is overload being absorbed without escalation?
- Identify structural constraints: what systemic factors limit implementation (budget, approval processes, supporting services)?

**Artefacts produced**: Capacity & Constraint Register; Resource Allocation Audit; Workload Assessment; Capability Gap Analysis; Budget Consumption Tracking

**Success criteria**: Capacity status is clear; constraints are named; overload (if present) is surfaced; decisions are made about resource allocation adjustments.

## 9.5 Step 5: Dynamics Analysis and Risk Identification

**Objective**: Understand how implementation is evolving over time; surface dynamic patterns that indicate success or degradation; identify implementation-specific risks.

**Activities**:
- Assess which of the ten dynamic patterns are present: phased-roll-out momentum, capacity exhaustion, silent adaptation, resistance activation, monitoring decay, feedback-loop collapse, decision-implementation divergence, cascade effects, workaround hardening, crisis reversion
- For each active pattern, assess severity and trajectory: is it early stage or entrenched?
- Map portfolio interactions: if multiple implementations are running in parallel, what coupling exists? Are cascade effects being designed and monitored?
- Identify implementation-specific risks: what could go wrong? What would be visible if risk were materialising?
- Assess whether implementation is on a trajectory toward success or toward failure

**Artefacts produced**: Dynamics Assessment; Implementation Risk Register; Portfolio Interaction Map; Cascade Risk Analysis; Trajectory Assessment

**Success criteria**: Major dynamic patterns are identified; active risks are named; portfolio coupling is mapped; trajectory is assessed.

## 9.6 Step 6: Hiddens Mapping and Evidence Audit

**Objective**: Surface visibility failures that may be preventing detection of implementation problems; verify that monitoring and feedback loops are functional.

**Activities**:
- Run Tier 1 Hiddens scan across all six categories; identify which Hiddens may be active
- Focus on implementation-specific Hiddens: compliance theatre, capacity blindness, street-level adaptation, resistance invisibility, decision-implementation divergence, cascade effects, unintended consequences, equity impacts
- Test escalation and feedback pathways: when issues are identified, do they reach decision-makers? Are corrective actions taken?
- Audit monitoring and evidence: are the right metrics being collected? Do metrics reflect actual practice? Can metrics be gamed?
- Assess whether Hiddens are masking implementation problems that should be escalated

**Artefacts produced**: Hiddens Register (Tier 1); Evidence Audit; Feedback Loop Assessment; Escalation Pathway Test Results; Visibility Failure Inventory

**Success criteria**: Major visibility failures are identified; feedback loops are tested and status is clear; evidence collection is assessed; Hiddens that could change decisions are surfaced.

## 9.7 Step 7: Recommendations, Closure, and Escalation

**Objective**: Produce actionable recommendations for implementation adjustment, governance escalation, and monitoring enhancement; document residual unknowns and next probes.

**Activities**:
- Synthesise findings from Steps 1–6 into coherent picture of implementation status, gaps, and risks
- Produce implementation recommendations: what adjustments should be made? (sequencing, capacity, resistance drivers, workarounds, feedback loops, portfolio timing)
- Identify governance escalation triggers: what issues require governance oversight and decision-making?
- Design or strengthen monitoring: what indicators should be tracked? What escalation rules should trigger action?
- Document residual unknowns: what is still unclear? What next probes would resolve unknowns?
- Specify closure scope: what questions have been answered? What are the limits of this assessment?

**Artefacts produced**: Implementation Health Summary; Recommendation Log; Governance Escalation Triggers; Monitoring & Feedback Design; Residual Unknown Register; Closure Statement

**Success criteria**: Recommendations are specific and actionable; governance escalation is clear; monitoring is designed; unknowns are explicit; closure is bounded.

---

# 10. Standard Registers and Output Schema

The Implementation framework populates the following registers that integrate with the Analytical Series standard output schema and the shared Hiddens/Evidence/Risk registers:

1. **Implementation Inventory**: Catalogue of identified implementation types (from 3.1–3.6 taxonomy) with active/inactive status and mechanism summary

2. **Gap Register**: Structured inventory of divergences between intended and actual implementation, including magnitude, drivers, and consequence

3. **Resistance & Adaptation Catalogue**: Inventory of resistance mechanisms and adaptations, classified by type (active opposition, passive non-compliance, gaming, reinterpretation) with drivers and remediation approach

4. **Capacity & Constraint Register**: Inventory of resource sufficiency, constraints, bottlenecks, and overload indicators with risk assessment

5. **Implementation Risk Register**: Implementation-specific risks (gap realization, adaptation cascades, monitoring failure, feedback-loop collapse) linked to Hiddens and governance escalation

6. **Implementation Dynamics Assessment**: Profile of implementation against the five dimensions (scope, fidelity, tempo, capacity, monitoring) and mapping of active dynamic patterns (ten patterns from §5.1)

7. **Hiddens Register (Implementation Layer)**: Eight implementation-specific Hiddens (compliance theatre, capacity blindness, street-level adaptation, resistance invisibility, decision-implementation divergence, cascade effects, unintended consequences, equity impacts) with mechanism, detectability, agency, and remediation interface

8. **Evidence Ledger**: Standard registers for evidence quality, data reliability, metrics validity, and feedback-loop status (shared across all frameworks)

9. **Hypothesis/Test Backlog**: Proposed tests to reduce uncertainty about implementation fidelity, capacity, resistance, and feedback effectiveness

10. **Decision/Action Record**: Governance decisions made during assessment and corrective actions taken in response to findings

---

# 11. Integration with the Analytical Series Operating Guide v2.5

This Framework of Implementation is designed to execute within the Analytical Series Operating Guide v2.5 infrastructure and discipline. Key integration points:

- **Prompt Discipline Rules (OG v2.5 §D.3)**: All implementation claims must be tagged as Fact (F), Interpretation (I), Assumption (A), or Unknown (U). Do not collapse uncertainties into false consensus.

- **Run Mode Selection (OG v2.5 §D.10.1)**: The framework works in both Rapid Run Mode (Light Depth execution, ~2–4 hours for gap scan and Tier 1 Hiddens) and Investigative Run Mode (Full Depth execution, ~6–12 hours for comprehensive gap analysis, capacity audit, dynamics assessment, Tier 2 Hiddens).

- **Tiered Hiddens Scan (OG v2.5 §D.6.10)**: Tier 1 (mandatory, all frameworks) runs early and again pre-closure across all six Hiddens categories. Tier 2 (standard in Investigative Run Mode) deepens top ~5–15 implementation Hiddens with mechanism chains, detectability assessment, and remediation interface design. Tier 3 (escalation-triggered) runs when high consequence, concealment plausibility, contradictions persist, cascades are suspected, or repeat-failure patterns appear.

- **Targeted Hiddens Discovery Scans (OG v2.5 §7.5)**: When Tier 1 symptoms point to specific hiding mechanisms, invoke appropriate scan. For implementation: "Suppression" scan (Family A) when compliance theatre is suspected; "Competency Blindspot" scan (Family B) when capacity blindness appears; "Drift" scan (Family C) when gradual divergence is evident; "Negligence" or "Intervention Blindspot" scan (Family D) when unintended consequences appear.

- **Standard Output Schema (OG v2.5 §7.4)**: Implementation assessment must produce outputs in the canonical schema: Fact Register (observations, tested claims), Interpretation Register (analyst inference), Assumption Register (dependencies), Unknown Register (residual unknowns with next probes), Hiddens Register (visibility failures), Evidence Ledger (quality/reliability), Hypothesis/Test Backlog (testable propositions), and Closure Statement (scope, limits, escalations).

- **Closure Discipline (OG v2.5 §7.4)**: At assessment closure, explicitly state: What questions have been answered? What are the limits of evidence? What Hiddens remain? What escalations are required? What is the next probe for each residual Unknown?

---

# Conclusion: Implementation as Visibility and Discipline

Implementation is where decisions meet reality. The distance between intent and outcome is populated by mechanisms that can be made visible and managed: sequencing logic, capacity constraints, resistance dynamics, adaptation and workaround emergence, monitoring and feedback loops, and portfolio interactions. A framework for implementation provides:

1. **Visibility**: Making gaps, drift, resistance, adaptation, and feedback loops visible so they can be diagnosed and addressed
2. **Diagnosis**: Understanding what is actually happening and why, not just what is reported or assumed
3. **Discipline**: Establishing repeatable protocols for implementation assessment, gap analysis, capacity audit, dynamics monitoring, and Hiddens scanning
4. **Learning**: Closing feedback loops so implementation experience feeds back into decision-making and future improvements
5. **Governance**: Enabling governance oversight to detect and correct implementation divergence in real time

Without implementation visibility, compliance theatre hardens, capacity constraints are absorbed invisibly, resistance takes subtle forms, adaptation spreads uncontrolled, feedback loops break, and cascade effects appear chaotic. With implementation visibility, these mechanisms become diagnosable and manageable. This framework provides the discipline to achieve that visibility.

---

## Appendix: Glossary of Implementation Terms

**Adaptation**: Modification of specified process to fit local context, existing constraints, or resource availability. Can be healthy (addresses unmet need) or degrading (masks unaddressed constraint or inverts intent).

**Capacity constraint**: Shortage of human, technical, financial, or organisational resources relative to implementation requirements. Often invisible when absorbed by frontline workers without escalation.

**Cascade effect**: Unintended consequence of one implementation that affects or amplifies/dampens another implementation. Deterministic but often appears chaotic if interactions are not designed.

**Compliance theatre**: Reported compliance that masks actual practice divergence; appears to comply while implementation continues unchanged.

**Decision-implementation divergence**: Same decision interpreted and implemented differently across teams or contexts; fragmentation reduces system-wide benefit.

**Feedback loop**: Cycle of monitoring implementation status, escalating issues to decision-makers, making decisions, taking corrective actions, and measuring whether actions had effect. When complete, enables learning and course correction. When incomplete (breaks at any stage), creates blind spots.

**Implementation drift**: Gradual, often unnoticed divergence between intended and actual implementation; grows over time without visibility and can become entrenched.

**Implementation gap**: Distance between intended specification and actual practice, including variance due to adaptation, resistance, constraint, feedback absence, and portfolio interaction.

**Monitoring decay**: Reduction in monitoring intensity, data quality, or escalation usage over time; creates blind spots even if implementation remains sound.

**Passive non-compliance**: Failure to adopt new process or continued use of old process despite formal announcement of change; expressed through quiet non-adoption rather than active opposition.

**Resistance (active)**: Overt, deliberate actions to prevent, slow, or delegitimise implementation.

**Resistance (passive)**: Non-adoption of new process or continued use of old way without explicit opposition; harder to detect and address than active resistance.

**Sequencing**: The order and timing of implementation activities, including prerequisite logic, dependency management, and rate of change introduction.

**Street-level adaptation**: Informal modification of specified process by frontline implementers in response to local conditions, emerging constraints, or discovered capability gaps.

**Workaround**: Informal alternative path used when specified process encounters bottleneck, constraint, or capability gap. Can be temporary (until constraint is removed) or permanent (constraint never addressed, workaround becomes standard).

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v1.0 | 2026-04-08 | Initial draft. Full framework authored from scratch using MRT v3.0. 30 core types across 6 meta-categories, 5 cross-cutting dimensions, dynamic patterns, interface types, Hiddens analysis (Tier 1/2/3), application protocol, and integration with all 36 canonical frameworks. |

## 12.2 Integration Notes
- Operating Guide compatibility: v2.5
- Master Rewrite Template: v3.0
- Prompt Discipline Ruleset: OG §D.3 (PD-01 through PD-10)
- LLM Execution Extract: to be generated in Phase 3 using LLMET v1.0
- Next milestone: v1.1 stable (after operational validation and pilot extract generation)

---

**End of Framework of Implementation v1.0**
