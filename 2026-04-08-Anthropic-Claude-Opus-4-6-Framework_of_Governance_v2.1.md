# Framework of Governance
*A comprehensive taxonomy of how authority, oversight, and correction operate over time*

## Document Information
- Series: Analytical Series of Frameworks
- Version: v2.1 (MRT v3.0 LLM Integration Bridge format)
- Date: 2026-04-08
- Status: Draft
- Operating Guide Compatibility: Analytical Series Operating Guide v2.5
- Prompt Discipline Ruleset: Operating Guide "Prompt Discipline Rules (Canonical)" (see OG v2.5, §D.3)
- Run Mode Terminology: Rapid Run Mode / Investigative Run Mode (see Operating Guide §D.10.1)
- Framework Execution Depth Terminology: Full Depth Framework Execution / Light Depth Framework Execution (see Operating Guide §D.10.1)
- Tiered Hiddens Scan Model: Tier 1 (six-category visibility audit) / Tier 2 (structured deepening) / Tier 3 (full-spectrum escalation) (see Operating Guide §D.6.10)
- Targeted Hiddens Discovery Scans: Thirteen mechanism-specific cross-framework scans (see Operating Guide §7.5)
- Group (Primary): G6 — Choice, action & control over time (Action & Control)
- Group (Secondary): G3 — Agency & behavioural drivers (Agency)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Diagnose and redesign governance architectures; map formal and informal authority; evaluate oversight, escalation, and feedback loops; detect drift, capture, and paper–practice decoupling; design governance that reveals and remediates Hiddens; integrate governance with responsibility, risk, evidence, and decision architectures
- Primary Audience: Boards and executives; governance and risk leaders; regulators and oversight bodies; compliance and assurance leaders; transformation and operating-model leaders; safety and reliability leaders; programme leaders in complex multi-party systems
- Dependencies / Key Inputs: System boundary and stakeholders; objectives and values; constraints; current governance artefacts; decision rights and escalation pathways; evidence and uncertainty characterisation; risk and failure analysis; power and incentives map; cultural and communication conditions
- Primary Outputs: Governance map (paper and lived); typed governance catalogue; mandate and decision-right register; oversight and assurance design; escalation and appeal design; feedback-loop and loop-closure metrics; drift and capture diagnostics; governance reform backlog; Hiddens source register plus tiered Hiddens mapping; review cadence and sunset controls
- Change Log (brief): v2.0: Full rewrite to Master Template v2.3 with OG v2.5 integration; updated all OG references from v1.5 to v2.5; expanded §1.6 with Tier 1–3 Hiddens routing, Targeted Scans integration, and Information Requests schema; added formal Introduction section (narrative + why + what + how); expanded §2–6 with detailed descriptions per template §2.2; expanded §7.3 with all 36 canonical frameworks and Group/Stage columns; expanded §8 with full Tier 2 Hiddens routing and 13 Targeted Scans integration; added §11 (Glossary) with local domain terms; enhanced Application Protocol (§9) with 7-step discipline; added Principles table with five core governance principles; updated version history; full compliance with 600–1000 line target and complete/no-placeholder rule.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What governance architecture is operating here (paper and lived), how does it allocate authority and oversight over time, and where does it generate or reveal Hiddens?** |
| Addresses | Paper–practice decoupling; governance drift; capture; weak signal suppression; accountability vacuums; escalation blockage; metric theatre; shadow governance; legitimacy brittleness; crisis exceptionalism. |
| Gap Filled | Power explains who can shape outcomes. Responsibility explains who is answerable. Decisions describes choice points. Governance explains the durable structures and feedback loops that shape how power, decision rights, oversight, and correction operate over time. |
| Complements | Power; Incentives; Legitimacy; Responsibility; Decisions; Risk; Failures; Evidence; Uncertainties; Systems; Boundaries; Time; Scale; Communications; Narratives; Culture & Norms; Hiddens. |
| Key Characteristics | Six meta-categories; thirty governance types; five dimensions; five dynamic patterns; three interface types; embedded Hiddens source analysis and tiered Hiddens mapping (Tier 1–3 + 13 Targeted Scans). |
| Main Contributions | A repeatable governance review scan; a taxonomy for classifying governance mechanisms; drift and capture diagnostics; interface-aware design; integration with Hiddens for detection and remediation; 7-step governance protocol. |

---

# Introduction

## What is Governance?

Governance is the structured configuration of architectures, roles, rules, and feedback loops through which authority and oversight are exercised over time. Governance is not limited to formal charts and policies. It also includes the lived practice: informal power, backchannels, cultural norms, information control, and narrative incentives that determine what actually happens. A complete understanding of governance requires simultaneous visibility of both paper (formal) and lived (actual) dimensions. In complex organisations and multi-party systems, governance failure—the mismatch between intended and actual authority, the breakdown of escalation, the erosion of independence—is a primary root cause of repeated failures, ethical breaches, catastrophic accidents, and loss of stakeholder trust.

This framework provides an operational definition: governance is the set of mechanisms through which authority is allocated, exercised, and reviewed; oversight is maintained independent of those exercising authority; decisions are made with appropriate participation and clarity; and feedback loops close corrective actions. The question this framework answers is: **What governance architecture is operating here (paper and lived), how does it allocate authority and oversight over time, and where does it generate or reveal Hiddens?**

## Why does Governance matter for Hiddens work?

Governance failure is a primary generator and concealer of Hiddens. A governance system that lacks independence permits capture—the systematic shaping of decisions toward particular interests while excluding contrary signals. A governance system that does not enforce escalation permits weak signals (concerns, dissent, evidence of misalignment) to be suppressed or filtered. A governance system that decouples paper from lived practice creates "shadow governance" in which actual authority, decisions, and accountability migrate into informal channels where they are invisible to oversight. A governance system that does not close feedback loops (monitoring → action → change) becomes performative: reports are filed, audits are conducted, metrics are reviewed, yet actual practice remains unchanged. Each of these conditions produces Hiddens.

Conversely, this framework surfaces five families of Hiddens:
- **Capture Hiddens (Hidden-8)**: Governance bodies and processes become biased toward particular interests, reducing independence and producing systematic blindspots.
- **Escalation Hiddens (Hidden-18)**: Weak signals, concerns, and dissent cannot be raised safely; issues are suppressed before reaching decision-makers.
- **Paper–Practice Hiddens (Hidden-19)**: Formal governance artefacts diverge from lived practice; accountability migrates into shadow space.
- **Feedback Hiddens (Hidden-20)**: Monitoring loops do not close; corrective actions are not tracked; learning collapses.
- **Authority Hiddens (Hidden-6)**: Actual authority diverges from formal roles; informal networks and cliques determine outcomes.

Without this framework, governance failures appear as sudden crises despite long deterioration. With the framework, governance review becomes a repeatable discipline that reveals paper–practice decoupling, spots capture, tests escalation safety, and surfaces the Hiddens that governance systems are designed to prevent.

## What does this framework produce?

The framework operationalises governance diagnosis and design through six core elements:

1. **A taxonomy of 30 governance types** organised into six meta-categories (Architectural, Institutional, Rule & Policy, Control & Feedback, Decision & Escalation, Informal & Shadow) that recur across contexts, allowing rapid classification and comparison.

2. **Five cross-cutting dimensions** (Scope & Breadth, Authority & Independence, Transparency & Signal Fidelity, Participation & Representation, Review Cadence & Adaptability) that profile any governance instance and explain variation across similar contexts.

3. **Five dynamic patterns** (Drift & Decay, Capture & Colonisation, Paper–Practice Decoupling, Learning & Reconfiguration, Crisis Centralisation & Exceptionalism) that describe how governance systems evolve and degrade, enabling detection of transitions and early warning of regime change.

4. **Three interface types** (G-A Delegation, G-B Oversight & Assurance, G-C Escalation & Appeal) that make visible where and how governance mechanisms interact, where failures create orphan risks, and which interfaces require explicit design and testing.

5. **Hiddens source analysis and tiered Hiddens scans** (Tier 1 six-category audit, Tier 2 structured deepening, Tier 3 full-spectrum escalation) that surface the five systematic sources of governance failure and the six categories of visibility failure that permit Hiddens to persist.

6. **A 7-step application protocol** that moves from situation clarification through governance scan, paper–lived audit, dynamics analysis, Hiddens mapping, and reform translation into actionable governance changes.

The framework populates standard registers (Governance Catalogue, Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Decision/Action Record) that integrate with the broader Analytical Series investigation workflow. It is designed for repeated use: governance is reviewed, Hiddens are surfaced, reforms are implemented, and governance is re-audited at scheduled intervals or triggered by threshold breaches, allowing the analysis to track effectiveness in real time.

## How to use this framework

Invoke this framework early when establishing governance in new contexts, whenever formal governance exists but outcomes are poor or surprising, and periodically to audit for drift and capture. The framework is most valuable when used together with the Power, Incentives, Responsibility, Decisions, and Risk frameworks to build a complete governance architecture. The framework works in both Rapid Run Mode (light-touch type identification, interface spotting, Tier 1 Hiddens scan) and Investigative Run Mode (full dimensional profiling, deep dynamics analysis, Tier 2–3 Hiddens scanning, paper–lived audits, lived-governance testing).

Default execution is Light Depth Framework Execution: identify active governance types, profile one or two dimensions, spot obvious interface failures, conduct a Tier 1 Hiddens scan. Escalate to Full Depth when consequence is high, evidence is contested, suspected capture is present, or escalation safety is in question. The framework's companion prompt discipline rules (OG v2.5, §D.3) require tagging all governance claims as Fact, Interpretation, Assumption, or Unknown, and explicitly recording disagreements, uncertainties, and residual unknowns rather than collapsing them into false consensus.

For LLM execution, see §1.6 for the complete LLM integration specification, standard registers, and copy-ready run prompts. The framework is designed to be directly executable by an LLM given a scenario and the Operating Guide, producing a disciplined governance assessment with explicit Hiddens, F/I/A/U tagging, and bounded closure.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Governance is the structured configuration of architectures, roles, rules, and feedback loops through which authority and oversight are exercised over time. It is not optional, not neutral, and not self-maintaining. A well-designed governance system makes decision rights clear, permits weak signals to surface, prevents capture, and closes feedback loops (monitoring → action → change). A poorly designed governance system creates accountability vacuums, permits informal power to dominate formal roles, accumulates paper–practice decoupling, and becomes performative. The question this framework answers is: **What governance architecture is operating here (paper and lived), how does it allocate authority and oversight over time, and where does it generate or reveal Hiddens?**

## 1.2 Assumptions & Preconditions

### Assumptions Register

| Assumption | Type | If false, what breaks? | How to test | Mitigation |
|---|---|---|---|---|
| Governance can be made explicit and improved | Method / Structural | Framework loses applicability; governance becomes viewed as immutable or unknowable. | Apply the framework to two contexts and assess whether visibility improves; measure pre/post reform outcomes. | Acknowledge bounded rationality; focus on achievable improvements; use iterative small-steps approach. |
| Paper and lived governance often diverge | Structural / Domain | Analysis cannot surface performance gaps; paper–practice decoupling remains invisible; reforms address wrong layer. | Compare formal artefacts to observed practice via interviews, decision trace-backs, escalation path tests. | Use interviews and ethnography; conduct lived-governance audits; map shadow governance. |
| Governance affects system outcomes through authority, accountability, oversight, and feedback loops | Domain / Structural | Governance becomes a cost centre rather than a value driver; reforms are resisted. | Correlate governance quality (independence, escalation safety, loop closure) with failure rates and outcomes. | Use Business Case building; tie governance reform to risk reduction and performance targets. |
| Incentives, fear, and power shape what is governable | Structural / Domain | Technical governance design fails; governance becomes window-dressing despite good architecture. | Map power and incentive structures; test whether governance is respected under pressure; audit escalation under risk. | Combine with Power and Incentives frameworks; redesign incentive structures alongside governance. |
| Feedback loops are essential to governance | Structural / Method | Governance without closure becomes ritual; corrective actions are not tracked; learning collapses. | Measure loop-closure rate (% of issues escalated that receive action within defined SLA); audit corrective-action tracking. | Implement governance of governance (meta-governance); assign closure responsibility; create escalation dashboards. |
| Shadow governance exists and matters | Structural / Domain | Informal power determines outcomes despite formal roles; formal governance is performative; reforms have no effect. | Map informal decision-making networks; trace major decisions to actual influencers; interview staff about where real authority lies. | Design explicit interfaces to surface informal power; strengthen information access; improve transparency. |
| Governance must be periodically reviewed and reformed | Method / Structural | Drift, capture, and decay are normal without deliberate renewal; governance degrades invisibly. | Track governance change history; measure time-since-last-review; audit for drift signals (metric theatre, low escalation rates, capture indicators). | Establish review cadence; implement sunsets on exceptions; rotate roles; enforce independence audits. |

### Preconditions Checklist

| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| System boundary and objectives are defined | Y | Situation naming statement; boundary sketch; objectives and constraints. | Analyst/facilitation team | Check against scenario input; validate with stakeholders. | Use boundary-clarification workshop; work with "plausible minimum scope"; iterate with stakeholders. |
| Authority structures (formal and informal) are accessible | Y | Org charts; interview access; decision-trace pathway clarity. | Analyst; governance owner | Verify via document review and interviews; assess completeness of coverage. | Produce Authority Access Request; escalate barriers; use proxy interviews. |
| Stakeholders and affected parties are identified | Y | Stakeholder map; primary/secondary grid; position and interests inventory. | Analyst; stakeholder manager | Verify against scenario narrative; conduct stakeholder validation workshop. | Use representative sampling; engage through formal channels; note stakeholder gaps in closure. |
| Governance artefacts (charters, policies, escalation paths) are available | Y | Governance artefact inventory; access confirmation; completeness assessment. | Analyst; governance custodian | Audit availability; confirm non-classification; check for archival/obsolescence. | Produce Governance Artefact Request List; escalate access; note unavailable items in closure. |
| Evidence and uncertainty bounds are provisionally understood | Y | Evidence inventory; sources; gaps; confidence levels. | Analyst; evidence custodian | Cross-check against Uncertainties and Evidence frameworks; confirm quality standards. | Run parallel Evidence or Uncertainties scan; produce Evidence Ledger alongside Governance review. |
| Risk and failure context is known | Y | Risk register; failure/incident history; consequence levels; escalation thresholds. | Analyst; risk owner | Verify against Risk and Failures frameworks; assess completeness. | Run parallel Risk scan; use proxy risk model; note assumptions in closure. |
| Learning loops and review cadence are designable | Y | Current governance review schedule; governance change history; iteration budget. | Analyst; governance owner | Confirm feasibility of reforms; assess iteration capacity; map change backlog. | Propose default cadence (quarterly); flag resource constraints; recommend phased implementation. |

## 1.3 Definitions, Scope, and Non-Goals

**Governance (operational)**: The configuration of structures, roles, rules, and feedback loops through which authority and oversight are exercised over time.

**In scope**:
- Six governance meta-categories and thirty governance types (6×5 taxonomy)
- Five governance dimensions for profiling governance instances
- Governance dynamics (five patterns: drift, capture, decoupling, learning, crisis exceptionalism)
- Three governance interface types (G-A delegation, G-B oversight/assurance, G-C escalation/appeal)
- Hiddens sources plus tiered Hiddens cross-check (Tier 1–3 + 13 Targeted Scans)
- Application protocol and standard deliverables
- Integration with all 36 canonical frameworks

**Out of scope**:
- Domain-specific legal advice and enforcement design (treated as constraints and inputs)
- Detailed organisational design blueprints (classified here but designed with specialist methods)
- Purely normative political theory (use Legitimacy and Power frameworks jointly)

## 1.4 Position in the Series (Upstream / Middle / Downstream)

- **Upstream frameworks**: Realities; Situations; Boundaries; Power; Incentives; Evidence; Uncertainties; Risk; Failures; Culture & Norms
- **Middle (this framework's role)**: Map and diagnose governance structures and lived practice; classify governance mechanisms; locate interface failures; surface Hiddens; design governance reform options
- **Downstream frameworks**: Responsibility assignments; Decisions architecture; Interventions implementation; Learning & Adaptation loops; Communications and narrative embedding

### Operating Guide Integration & Routing

- **Group assignment (Primary)**: G6 — Choice, action & control over time (Action & Control)
- **Group assignment (Secondary)**: G3 — Agency & behavioural drivers (Agency)
- **Stage assignment**: Downstream (see OG v2.5 §3.1 Stage framework)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.10.1 Mode Selection Gate)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)

## 1.5 Crosswalk Summary (recommended)

| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Power and incentives | Power; Incentives; Agents | Who can act, who controls resources and information, and how incentives shape behaviour | How authority is structured over time (rights, forums, oversight, escalation) and where informal power bypasses formal governance |
| Legitimacy and participation | Legitimacy; Perspectives; Culture & Norms; Narratives; Communications | Bases of right, trust, participation, and meaning-making | Whether governance processes are legitimate, inclusive, and remedy-capable, and where legitimacy is brittle |
| Accountability and role clarity | Responsibility; Decisions | Who is answerable, how choices are made, and how responsibilities are allocated | Decision-right clarity, delegation chains, vetoes, escalation safety, and whether accountability matches lived authority |
| Risk, evidence, and learning | Risk; Failures; Evidence; Uncertainties; Learning & Adaptation | Hazard understanding, evidence standards, uncertainty bounds, learning mechanisms | Whether monitoring loops close, assurance is independent, and learning produces governance reconfiguration rather than ritual reports |
| Systems, boundaries, time and scale | Systems; Boundaries; Time; Scale; Resources | Structure, constraints, temporal dynamics, and capability limits | Whether governance matches system complexity and tempo and whether boundaries create orphan risks and interface failures |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Governance_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Governance when… | Use neighbour instead when… |
|---|---|---|
| Power | Analysing formal authority allocation, decision rights, roles, and accountability structures over time; governance mechanisms and their alignment with stated objectives. | Analysing abstract power distribution, bargaining relationships, dependency, and who can influence outcomes independent of formal roles; studying informal power networks and control. |
| Responsibility | Analysing decision-right clarity, escalation pathways, and whether accountability aligns with lived authority; designing delegation chains and oversight. | Analysing who is answerable for outcomes, causal attribution of responsibility, remedies, and consequence assignment independent of governance structure. |
| Decisions | Analysing how governance shapes choice processes, vetoes, participation, and escalation mechanisms; whether decision rules enable or constrain participation. | Analysing specific choice points, decision quality, alternatives considered, reversibility, and who decided independent of governance framework. |
| Systems | Analysing governance architecture's role in system resilience, failure modes, and feedback loops; coupling between governance decisions and system behaviour. | Analysing system structure, dynamics, constraints, and emergent behaviour independent of governance; studying how components interact. |
| Incentives | Analysing formal rules, policies, and oversight mechanisms that shape compliance and behaviour; governance design that aligns incentives. | Analysing individual motivations, rational response to incentives, what people actually value, and why formal governance is accepted or evaded. |

### 1.6.3 Routing triggers
- Authority structures diverge from formal documentation (paper–practice mismatch suspected)
- Escalation pathways are blocked, slow, or unsafe (weak signals suppressed)
- Governance bodies show signs of capture, bias, or compromised independence
- Monitoring and feedback loops exist but corrective actions are not tracked (performative governance)
- Accountability gaps exist (shadow authority, unclear decision rights, orphan responsibilities)
- Crisis, emergency, or exceptional conditions are becoming normalised in governance
- Informal networks, backchannels, or cliques determine outcomes despite formal roles
- Governance design appears misaligned with system complexity, tempo, or stakeholder participation needs


# 2. Meta-Categories of Governance

## 2.1 Meta-Categories Table (mandatory)

| Category | Core question | Scope | Typical types | Why it matters |
|---|---|---|---|---|
| I. **Architectural Governance** | How is authority distributed across the system? | Structure of hierarchy, federation, polycentric networks; allocation of power and decision rights across layers and domains | Hierarchical, federated, polycentric, network, hybrid | Architecture constrains what decisions can be made where and who can reverse them; determines whether governance is centralised and brittle or distributed and adaptive |
| II. **Institutional & Role Governance** | Who holds formal authority and how independent are they? | Governance bodies (boards, committees, executive teams), role definitions, mandate clarity, independence testing | Boards of directors, regulators & overseers, executive/operational management, assurance & audit, participatory & stakeholder bodies | Institutions either enforce governance or become captured; independence is the prerequisite for challenge and escalation safety |
| III. **Rule & Policy Governance** | How are rules and constraints codified and enforced? | Policies, standards, contracts, ethical/conduct rules, automation and workflow rules | Policies & standards, legal & contractual, ethical & conduct rules, compliance automation, rule enforcement & exceptions | Rules without enforcement become theatre; enforcement without participation becomes coercive; rules that do not adapt create shadow governance |
| IV. **Control, Monitoring & Feedback Governance** | How is performance monitored and corrections made? | KPI dashboards, risk monitoring, safety and reliability monitoring, learning and adaptation loops, exception management | KPI & metric dashboards, risk monitoring & escalation, safety & reliability controls, learning & continuous improvement, exception & override management | Monitoring without closure is performative; closure without transparency is corrupt; learning requires feedback loops that integrate evidence and governance design |
| V. **Decision Rights & Escalation Governance** | Who decides, who can veto/appeal, and how do issues escalate? | RACI matrices, vetoes and challenge mechanisms, delegation chains, escalation pathways and triggers, emergency and crisis governance | RACI & decision-right matrices, veto & challenge mechanisms, delegation & authority limits, escalation & appeal, emergency & crisis governance | Clear decision rights prevent vacuums; escalation without safety suppresses weak signals and permits Hiddens to persist; crisis governance must not become permanent |
| VI. **Informal, Cultural & Shadow Governance** | How do informal power, norms, and shadow structures actually determine outcomes? | Cultural norms, informal networks and cliques, information control and narrative incentives, shadow decision-making forums, tacit practices | Norms & culture enforcement, networks & clique governance, information control & narrative incentives, shadow forums & backchannels, tacit practices & unwritten rules | Informal governance either reinforces or undermines formal governance; shadow governance that diverges from formal creates accountability gaps; narratives shape what is visible and what is hidden |

## 2.2 Meta-Category Descriptions (recommended)

### I. Architectural Governance

Architectural governance describes the high-level distribution of authority across organisational layers, functional domains, and multi-party boundaries. It answers: Is authority centralised (hierarchy) or distributed (federation, network)? Can decisions be made locally or must they flow through central bodies? Are boundaries clear or do they create orphan risks? Architectural choices constrain what can be governed at lower levels and determine whether governance is brittle (hierarchical, dependent on few decision-makers) or resilient (distributed, with clear escalation paths). Examine the organisational chart, span of control, delegation authorities, and multi-party agreements to surface architectural governance types.

### II. Institutional & Role Governance

Institutional governance describes the formal bodies, roles, and mandates through which authority is exercised and challenged. It answers: Is there an independent board or oversight body? Do decision-makers have clear mandates? Are they insulated from delivery pressure? Can they say "no"? Institutional governance is the prerequisite for independence. A well-designed institutional structure permits challenge (audit, regulators, vetoes); a poorly designed one becomes captured or ceremonial. Institutions must be tested not just on their charter but on their lived independence: whether they actually challenge, whether they can escalate without fear, whether they rotate roles to prevent capture.

### III. Rule & Policy Governance

Rule & policy governance describes how constraints, standards, and decision rules are codified and enforced. It answers: Are rules clear and accessible? Are they enforced or do they function as theatre? What happens when rules conflict with delivery pressure? Rule governance can be narrow (a single policy framework) or broad (integrated legal, ethical, operational, and technical rules). Enforcement matters more than design: a sophisticated rule may be ignored if enforcement is weak or if fear/incentives override compliance. Shadow governance typically emerges when formal rules are too rigid, too slow, or perceived as unsafe to follow.

### IV. Control, Monitoring & Feedback Governance

Control & monitoring governance describes how performance is measured, issues are detected, and corrections are made. It answers: Are the right metrics measured? Are leading indicators available or only lagging ones? Is monitoring independent of those being monitored? Do issues detected via monitoring result in corrective action, or is the monitoring performative? This is where governance either closes its feedback loops or becomes ritual. A governance system that monitors but does not act—that files audit reports but does not change practice—generates Hiddens by suppressing weak signals while maintaining an appearance of oversight.

### V. Decision Rights & Escalation Governance

Decision rights & escalation governance describes who can decide, who can challenge/veto, and how issues escalate when normal decision-making fails. It answers: Is it clear who decides each type of decision? Can subordinates escalate concerns or decisions they believe are wrong? Is escalation safe or do escalators face retaliation? Are escalations resolved quickly or do they accumulate? This is where formal governance interfaces with informal power and culture. Escalation safety is prerequisite for Hiddens visibility: without it, weak signals, concerns, and contrary evidence are suppressed before reaching decision-makers.

### VI. Informal, Cultural & Shadow Governance

Informal & cultural governance describes the unwritten norms, networks, and backchannels through which authority is actually exercised. It answers: Who really influences decisions (independent of formal roles)? What narratives shape what is visible and what is hidden? Are there cliques that dominate decision-making? What happens in informal forums that does not appear in formal minutes? Shadow governance is not inherently bad—informal networks can accelerate decisions and surface concerns—but shadow governance that diverges from formal governance creates accountability gaps, permits capture, and enables Hiddens.

---

# 3. Core Governance Types Taxonomy

## 3.0 Canonical Rule & Deviations

This framework uses a 6×5 taxonomy (six meta-categories × five types each = 30 core types). This is the canonical baseline per Master Template v2.3. No deviation in this framework. All 30 types are present; all are used in analysis; all can be classified as active/inactive in a given scenario.

## 3.1 Types (Category I: Architectural Governance)

| Type # | Type name | Core mechanism | Diagnostic cue | Failure signature | Hidden sources | Remediation levers |
|---:|---|---|---|---|---|---|
| 1 | Hierarchical authority structure | Authority flows vertically; decisions escalate upward; decisions at each level must be consistent with levels above. | Org chart with clear levels; approval chains; sign-off authority defined by level. | Authority ambiguity (who can decide?); bottlenecks at senior levels; decisions stall awaiting approval; reversed decisions damage morale. | Hidden-6 (actual authority diverges), Hidden-19 (shadow routes emerge to bypass escalation) | Clarify decision-right matrix; reduce approval layers for low-risk decisions; delegate to frontline with clear boundaries. |
| 2 | Federated / federal authority structure | Authority is distributed across semi-autonomous units; each unit has clear domain and decision rights; coordination occurs at boundaries via formal interfaces. | Multiple units with clear mandates; boundary agreements; joint decision forums for cross-unit issues. | Orphan risks at boundaries (no one decides); conflicting decisions across units; coordination failure; finger-pointing. | Hidden-6 (actual decision-makers unclear at boundaries), Hidden-19 (workarounds avoid formal coordination) | Explicitly design boundary governance; create joint decision forums; clarify escalation across units; test interface effectiveness. |
| 3 | Polycentric governance structure | Authority is held by multiple overlapping centres; decisions are made through negotiation and consensus; no single apex; power is diffused. | Multiple decision centres with no clear hierarchy; consensus-based forums; negotiated agreements; rotating leadership. | Decision gridlock (consensus never reached); unclear accountability (who is responsible for what?); slow response to crises. | Hidden-5 (accountability gaps), Hidden-6 (no clear decision-makers), Hidden-19 (backchannels form to bypass consensus requirement) | Clarify escalation when consensus fails; assign backup decision-maker; shorten decision timeline; test whether consensus is real or performative. |
| 4 | Network governance structure | Authority emerges from relationships, trust, and expertise; decisions are made through influence and persuasion rather than formal authority; no formal hierarchy. | Informal influence networks; decision-making through expert advice; trust-based rather than role-based authority. | Decisions made by hidden influencers; accountability invisible; new members unsure who decides; culture is brittle if key influencers leave. | Hidden-6 (actual authority invisible), Hidden-8 (cliques dominate), Hidden-19 (shadow forums are the only real forums) | Map informal networks; test whether key decisions are made through formal channels or backchannels; consider explicit hybridisation (keep informal networks but surface them through formal interfaces). |
| 5 | Hybrid governance structure | Authority is distributed across hierarchical and federated and network elements; different decisions use different structures; integration is explicit via roles or forums. | Multiple types visible simultaneously; integration mechanisms (e.g., steering committees, dotted lines); clear routing rules for different decision types. | Integration confusion (unclear which structure applies to which decision); inefficiency if wrong structure used; capability loss if network component is formalised away. | Hidden-6 (routing rules unclear), Hidden-19 (shadow routes emerge to avoid complexity) | Test whether integration mechanisms actually work; clarify routing rules; simplify if possible; monitor for shadow routes. |

## 3.2 Types (Category II: Institutional & Role Governance)

| Type # | Type name | Core mechanism | Diagnostic cue | Failure signature | Hidden sources | Remediation levers |
|---:|---|---|---|---|---|---|
| 6 | Board of directors / governance board | Formally independent body with fiduciary duty or equivalent mandate; elected or appointed; makes or approves major strategic decisions; reports to shareholders or stakeholders. | Board charter; membership list with independence assessment; meeting minutes; decision record. | Board is captured (decisions favour executives or major shareholders); board is ceremonial (rubber-stamps executive decisions); independent members are isolated or co-opted. | Hidden-8 (systematic bias), Hidden-15 (capture latency—captured over time without detection) | Test board independence (can it actually challenge?); rotate members to prevent entrenchment; strengthen information access; enforce conflict-of-interest controls; separate board roles (chair, CEO). |
| 7 | Regulatory / external oversight body | Formally independent external regulator or oversight body with mandate to monitor, challenge, and enforce; reports to public/stakeholders not to the organisation. | Regulator charter; authority to inspect, audit, enforce; independence testing; public reporting. | Regulator is captured (favours industry); regulator is toothless (can monitor but not enforce); regulator is distant (slow to respond; unaware of ground-truth). | Hidden-8 (regulatory capture), Hidden-15 (latency in detection), Hidden-19 (informal relationships bypass formal oversight) | Strengthen regulator independence; require direct access to operational data; mandate rapid response SLAs; rotate regulatory staff; open regulatory decision-making to public comment. |
| 8 | Executive line authority | Executive officers have formal authority over operations and report to the board; clarity of span and accountability; decision rights flow from CEO through line managers. | Org chart with clear executive roles; decision-right matrix for executive decisions; authority limits (e.g., spending cap at each level). | Executive line is unclear (who reports to whom?); authority limits are ignored under pressure; accountability flows upward (blame upstream) not downward (consequences for failures). | Hidden-6 (actual authority unclear), Hidden-10 (accountability displacement) | Clarify executive roles and decision rights; test whether authority is respected; enforce accountability for decisions made; measure whether executives respect the span of control. |
| 9 | Assurance & audit function | Formally independent internal or external audit/assurance function with mandate to assess governance, compliance, and control effectiveness; reports to board/external stakeholder. | Audit charter; independence testing (who does audit report to? can they audit executives?); audit plan; findings and follow-up status. | Audit is captured (favours management, soft on findings); audit is peripheral (findings are ignored); audit is confirmatory (audits only areas where compliance is already good). | Hidden-8 (capture), Hidden-20 (loop breakage—audit findings not acted upon) | Strengthen audit independence; create protected channel for findings to reach board; mandate executive response to all material findings; measure follow-up closure rate. |
| 10 | Participatory & stakeholder governance body | Formal body that includes non-management stakeholders (employees, customers, suppliers, community members); mandate to participate in or oversee decisions affecting them. | Stakeholder representation in governance; participation mechanisms (voting, consultation, veto); meeting records; stakeholder feedback. | Participation is tokenistic (stakeholders are consulted but decisions are predetermined); participation is dominated by powerful interests; participation is unsafe (dissenters face repercussion). | Hidden-8 (tokenism hides true decision-making), Hidden-2 (voice suppression—stakeholders self-censor) | Test whether participation actually influences decisions; strengthen voice protection; rotate participation to prevent dominance; implement ranked-choice or consensus-blocking mechanisms; publish decision rationale showing how feedback was considered. |

## 3.3 Types (Category III: Rule & Policy Governance)

| Type # | Type name | Core mechanism | Diagnostic cue | Failure signature | Hidden sources | Remediation levers |
|---:|---|---|---|---|---|---|
| 11 | Policies & standards framework | Codified rules, standards, procedures that specify how work should be done; accessible in policy repository; updated periodically; enforcement mechanisms. | Policy register; version control and update dates; accessibility testing (can people find policies?); audit of compliance. | Policies are outdated or irrelevant (not followed); policies are contradictory (A says X, B says not-X); policies are too detailed (create shadow governance) or too vague (provide no guidance). | Hidden-19 (shadow governance emerges when formal rules are too rigid), Hidden-24 (contextual blindness—policies do not account for operational context) | Audit policy relevance; simplify policies; involve operational staff in policy design; test compliance and identify barriers; update policies based on gaps; retire unused policies. |
| 12 | Legal & contractual rules | Formal legal obligations, contracts, and commitments that constrain action; external (law, regulation) and internal (contracts with partners). | Legal register; contract repository; compliance assessment vs legal obligations; legal advice on governance issues. | Legal rules are violated or worked around (when they conflict with business pressure); legal rules create perverse incentives (technically compliant but ethically wrong); legal requirements are unknown or unclear. | Hidden-19 (workarounds), Hidden-24 (unintended consequences of legal design) | Integrate legal review into governance design; test for workarounds; consult operational staff on whether legal rules are feasible; design incentives to support legal compliance; audit compliance and barriers. |
| 13 | Ethical & conduct rules | Codified ethical standards, conduct rules, and values; behavioural expectations; anti-corruption, anti-discrimination rules. | Code of conduct; ethics policies; training records; incident/complaint logs; ethics hotline use; survey of perceived ethical safety. | Ethical rules are stated but not enforced (rule theatre); ethical rules conflict with incentives (encouraged to behave unethically to meet targets); ethical rules are not accessible to all staff (only executives know them). | Hidden-2 (voice suppression—staff fear speaking up about ethics violations), Hidden-8 (ethical capture—ethics rules are suspended under pressure) | Test ethical awareness and enforcement; connect ethics to incentive structure; create protected reporting channel for ethics concerns; track and close ethics issues; survey ethical safety. |
| 14 | Compliance automation & workflow rules | Rules, workflows, and automation that enforce compliance with policies or standards; hard stops (cannot proceed without compliance); decision triggers. | Automation inventory; workflow rules documentation; evidence of hard stops; audit of automation effectiveness. | Automation is bypassed (manual workarounds exist); automation is too rigid (causes process failure); automation creates unintended consequences (e.g., false positives block legitimate decisions). | Hidden-19 (workarounds), Hidden-24 (automation creates cascading unintended effects) | Audit automation effectiveness and workarounds; design automation with human override mechanisms; test hard stops; involve operational staff in automation design; monitor for unintended effects. |
| 15 | Rule enforcement & exception management | Mechanisms for enforcing rules, responding to violations, and managing exceptions; consequence structures; appeal processes. | Enforcement authority; violation log; consequence records; exception-approval process; appeal mechanism; audit of consistency. | Enforcement is selective (rules enforced against some, ignored for others); enforcement is weak (violations have no real consequences); exceptions are granted without discipline (exceptions become standard practice). | Hidden-8 (selective enforcement indicates capture), Hidden-20 (loop breakage—violations are noted but not addressed) | Audit enforcement patterns for bias; strengthen consequences for violations; require documentation and approval for exceptions; measure exception frequency and trend; enforce consistency. |

## 3.4 Types (Category IV: Control, Monitoring & Feedback Governance)

| Type # | Type name | Core mechanism | Diagnostic cue | Failure signature | Hidden sources | Remediation levers |
|---:|---|---|---|---|---|---|
| 16 | KPI & metric dashboards | Quantitative metrics that measure performance against objectives; dashboards or scorecards; regular reporting; trend analysis. | Dashboard or scorecard in use; metrics definition; reporting frequency; stakeholder access; trend analysis. | Metrics are lagging (report on past, not future); metrics are gaming targets (incentivised to meet metrics, not objectives); metrics mask failure (aggregate metrics hide local failures); metrics do not reflect reality (accurate but not meaningful). | Hidden-20 (loop breakage—metrics reported but not acted upon), Hidden-24 (metric theatre—good metrics, poor outcomes) | Audit metric relevance to objectives; add leading indicators; test for gaming signals; disaggregate metrics to expose local variation; link metrics to corrective-action triggers; review metrics quarterly for continued relevance. |
| 17 | Risk monitoring & escalation | Systematic identification, monitoring, and escalation of risks; risk register; risk assessment; escalation when risks exceed thresholds. | Risk register; risk assessment methodology; risk reporting (to whom? how often?); escalation triggers and outcomes; risk review cadence. | Risk register is theatre (risks are listed but not managed); risks are under-reported (staff suppress risk signals); risks are over-reported (every issue is a risk, escalations are noisy). | Hidden-2 (voice suppression—risk signals suppressed if escalation is unsafe), Hidden-20 (loop breakage—risks identified but not addressed) | Test escalation safety; audit risk-reporting patterns; connect risk escalation to decision authority; measure time-from-identification to mitigation; audit whether high-risk items are actually prioritised in action. |
| 18 | Safety & reliability controls | Mechanisms for monitoring and protecting safety-critical functions; failure-mode monitoring; protective systems; safety reviews. | Safety plan; failure-mode analysis; protective mechanisms (redundancy, interlocks, automated shutdowns); incident log; safety review cadence. | Safety controls are bypassed under pressure (shortcuts taken to meet deadlines); safety incidents are not reported (incidents are hidden or reclassified); safety is treated as separate from operations (not integrated into daily governance). | Hidden-2 (incident suppression), Hidden-19 (workarounds to safety controls), Hidden-20 (loop breakage—incidents not addressed) | Test whether safety controls can be overridden; strengthen incident reporting and investigation; integrate safety into operational governance; measure incident rate and trend; audit controls for effectiveness. |
| 19 | Learning & continuous improvement | Mechanisms for capturing lessons, implementing improvements, and measuring whether learning is effective; improvement backlogs; retrospectives; feedback loops. | Retrospective notes or incident investigations; improvement backlog; completed improvements; evidence that learning has been implemented; survey of learning culture. | Learning is performed (retrospectives are held but findings are not implemented); learning is siloed (lessons learned are not shared across teams); learning does not lead to governance change (same failures repeat). | Hidden-20 (loop breakage—learning does not lead to action), Hidden-15 (historical Hiddens—same Hiddens recur because learning does not permeate governance) | Audit improvement backlog closure rate; connect learning to governance redesign; implement shared learning system; measure whether same failures recur; tie learning to incentive and evaluation structures. |
| 20 | Exception & override management | Mechanisms for documenting, approving, and reviewing exceptions to policies or controls; justification for exceptions; sunset reviews; escalation when exceptions persist. | Exception log; approval authority for exceptions; documented justification; exception review cadence; retired exceptions. | Exceptions are granted without discipline (exceptions become standard practice, rules are effectively circumvented); exceptions are opaque (hard to find what exceptions exist); exceptions are not reviewed (temporary exceptions become permanent). | Hidden-19 (exceptions become shadow governance), Hidden-20 (loop breakage—exceptions are not reviewed and retired) | Audit exception usage patterns; classify exceptions (one-time vs chronic); trigger escalation and rule review when exceptions become chronic; implement exception sunset reviews; strengthen transparency. |

## 3.5 Types (Category V: Decision Rights & Escalation Governance)

| Type # | Type name | Core mechanism | Diagnostic cue | Failure signature | Hidden sources | Remediation levers |
|---:|---|---|---|---|---|---|
| 21 | RACI & decision-right matrices | Formal documentation of who is Responsible, Accountable, Consulted, Informed for each category of decision; clarity on who decides. | RACI matrix or equivalent; decision categories defined; stakeholder list with roles; RACI tested against lived practice. | RACI is theatre (documented but not followed); RACI is outdated (reflects old structure); RACI is unclear (who is really accountable?). | Hidden-6 (actual decision-makers unclear), Hidden-19 (decisions made outside RACI matrix) | Test RACI against actual decision process; update RACI based on lived practice; simplify RACI to core decisions; train staff on RACI; audit compliance quarterly. |
| 22 | Veto & challenge mechanisms | Formal rights for designated parties to veto or challenge decisions; appeal mechanisms for those affected by decisions. | Veto charter (who can veto what?); appeal process; veto/challenge exercise history; response time to challenges. | Veto right exists but is not exercised (vetoes are seen as career-limiting); vetoes are overridden (formal veto is not respected); veto process is slow (decisions proceed before veto can be considered). | Hidden-2 (voice suppression—fear of vetoing prevents challenge), Hidden-18 (escalation failure—vetoes are overridden) | Test whether veto can be exercised safely; measure veto frequency; audit whether vetoes are respected; strengthen protections against veto retaliation; speed veto process. |
| 23 | Delegation & authority limits | Formal delegation of decision-making authority from senior to junior levels; decision limits (what decisions can be made at each level); recourse if decision is wrong. | Delegation letter or authority matrix; decision limits (e.g., spending cap); escalation rules for decisions above limit; audit of delegation exercise. | Delegation is unclear (junior staff unsure if they can decide independently); delegated decisions are routinely reversed (junior staff lose trust); delegation is informal (not documented, creates ambiguity). | Hidden-6 (authority unclear), Hidden-10 (accountability unclear—who is responsible if delegated decision fails?) | Test delegation against lived practice; clarify decision limits in writing; protect delegated decisions from routine reversal (require high bar to overturn); measure whether delegated decisions are respected. |
| 24 | Escalation & appeal governance | Formal pathways for escalating issues, concerns, or decisions when normal channels fail; appeal mechanisms for those affected; speed and fairness guarantees. | Escalation policy; escalation triggers; escalation pathway (who do you escalate to?); response-time SLA; appeal process; escalation logs. | Escalation is slow (issues accumulate waiting for response); escalation is unsafe (escalators face retaliation); escalation is ignored (issues are escalated but decisions are not changed). | Hidden-2 (voice suppression—fear prevents escalation), Hidden-18 (escalation failure—issues escalated but not resolved), Hidden-20 (loop breakage—escalations are not closed) | Test escalation safety (can concerns be raised without fear?); measure escalation-to-response time; audit whether escalations result in action; strengthen protections against retaliation; implement escalation dashboard. |
| 25 | Emergency & crisis governance | Formal mechanisms for activating emergency governance when normal processes fail; crisis decision-making; delegation of authority during crisis; conditions for returning to normal governance. | Emergency governance charter; crisis decision authority; conditions for emergency activation and return to normal; crisis debrief process; audit of emergency governance use. | Emergency governance becomes permanent (emergency powers persist after crisis ends); emergency governance is used for non-emergency decisions (scope creep); emergency governance bypasses oversight (minimal checks when crisis powers are used). | Hidden-8 (emergency powers used selectively), Hidden-10 (accountability gaps in emergency), Hidden-20 (loop breakage—crisis governance is not reviewed and retired) | Establish conditions for emergency activation and return to normal; require board/executive approval to extend emergency governance; conduct post-crisis review; measure duration of emergency governance use; build checks into emergency governance (e.g., weekly board review). |

## 3.6 Types (Category VI: Informal, Cultural & Shadow Governance)

| Type # | Type name | Core mechanism | Diagnostic cue | Failure signature | Hidden sources | Remediation levers |
|---:|---|---|---|---|---|---|
| 26 | Norms & culture enforcement | Unwritten rules and expected behaviours enforced through informal sanctions (respect, inclusion, advancement); cultural values. | Staff interviews on what is rewarded/punished; observation of team interactions; reward/advancement patterns. | Norms are misaligned with formal values (stated values vs rewarded behaviours are contradictory); norms are coercive (conformity is enforced through fear); norms are invisible to new staff. | Hidden-8 (cultural capture—norms enforced by cliques), Hidden-2 (voice suppression—norms enforce silence) | Audit alignment between stated values and rewarded behaviours; surface norms through interviews; discuss norms openly; change incentive structures to support formal values; onboard new staff with cultural context. |
| 27 | Networks & clique governance | Informal networks and cliques that determine influence and access; inner circles that control information and decisions. | Social network analysis; observation of informal forums (who attends?); who influences major decisions; interview on relationships and influence. | Cliques dominate decision-making (outsiders cannot influence outcomes); networks are exclusive (women, minorities, junior staff are excluded); networks concentrate power (decisions are made by few influencers). | Hidden-6 (actual decision-makers are invisible clique members), Hidden-8 (cliques favour in-group interests), Hidden-2 (voice suppression—those outside networks cannot be heard) | Map informal networks; make network-based influence visible through formal forums; rotate network participation; create multiple channels for input (not just networks); test whether important decisions require network participation or formal authority. |
| 28 | Information control & narrative incentives | Control over what information flows to whom; narrative framing that shapes perception of reality; selective information sharing. | Information flow audit (who has access to what?); narrative analysis (what stories are told about the organisation?); interview on information barriers. | Information is hoarded (key information is known only to inner circle); information is distorted (narratives are shaped to protect interests); information is delayed (slow information flow hides problems). | Hidden-17 (information asymmetry), Hidden-8 (narrative control conceals captured decisions), Hidden-20 (loop breakage—information about problems does not reach decision-makers) | Audit information flow and access; publish key metrics and decisions openly; create multiple information channels (not just formal); fact-check narratives; implement communication protocols that ensure information reaches decision-makers quickly. |
| 29 | Shadow forums & backchannels | Informal decision-making forums where real decisions are made (e.g., "kitchen cabinet" meetings); backchannels that bypass formal escalation. | Interview on where real decisions happen; observation of informal meetings; trace decisions back to actual forums where they were made. | Decisions made in shadow forums are not visible to those affected; accountability is unclear (who decided in the informal forum?); shadow forums are exclusive (only certain people invited). | Hidden-6 (actual decision-makers invisible), Hidden-19 (shadow forums are the only real governance), Hidden-8 (backchannels used to pre-decide outcomes before formal approval) | Make shadow forums visible; create formal venue for the same decisions; test whether formal channels can function without backchannels; rotate participation in shadow forums if they must exist; require documentation of shadow-forum decisions. |
| 30 | Tacit practices & unwritten rules | Knowledge of how things actually work that is not documented; passed through informal apprenticeship and osmosis; unwritten rules about what is safe and what is not. | Interview new staff on how they learned to work (who taught them?); observation of informal mentoring; comparison of written procedures to observed practice. | New staff are confused by mismatch between formal procedures and informal practices; knowledge is lost when informal teachers leave; tacit knowledge creates inconsistency (the way work is done depends on who you work for). | Hidden-19 (unwritten rules shape actual practice), Hidden-24 (tacit knowledge creates inconsistent outcomes), Hidden-1 (uncertainty—new staff are unsure what to do) | Document tacit knowledge (capture from informal teachers); create structured onboarding; make unwritten rules explicit; audit consistency of practice; measure whether new staff take same time to become effective. |

## 3.7 Extending the Taxonomy (mandatory)

This framework uses the canonical 6×5 taxonomy (30 types). If your scenario requires governance classification beyond this taxonomy:

1. **First approach**: Map candidate new types to the existing 6×5 taxonomy. Distinguish between a truly new governance mechanism and a variant or hybrid of existing types.
2. **If a new type is required**: Document the new type using the same schema (core mechanism, diagnostic cue, failure signature, Hidden sources, remediation levers); note which meta-category it belongs to (I–VI) and flag as a "domain-specific extension".
3. **Integration note**: Keep the 6×5 canonical baseline and note extensions as scenario-specific; do not modify the baseline in the framework document.

---

# 4. Cross-Cutting Dimensions of Any Governance Instance

## 4.1 Dimensions Table (mandatory)

| Dimension | Definition | Span | Questions to assess | Why it matters |
|---|---|---|---|---|
| **1. Scope & Breadth** | How many stakeholders, decisions, or domains does this governance mechanism cover? Range: narrow (single decision type, single team) to broad (organisation-wide, multi-party). | 1–5 (1=narrow, 5=broad) | Does this governance cover all affected parties? All decisions it should? Is scope clear or contested? Is scope changing? | Governance that is too narrow leaves gaps (orphan risks); governance that is too broad is expensive and slow; scope mismatch with actual decisions creates shadow governance. |
| **2. Authority & Independence** | How much formal authority does this governance mechanism have, and is that authority independent of those being governed? Range: weak (advisory only) to strong (binding authority); dependent (influenced by those being overseen) to independent (separate authority, insulated from influence). | 1–5 (1=weak/dependent, 5=strong/independent) | Does this governance body have real authority or is it advisory? Can it say "no"? Can it challenge powerful interests? Is it insulated from reprisal? | Governance with weak authority is theatre; governance with dependent authority is captured; independence is prerequisite for challenge and Hiddens surfacing. |
| **3. Transparency & Signal Fidelity** | How transparent is this governance mechanism (is it visible to those affected?), and how faithfully do signals flow (is information accurate and timely)? Range: opaque/distorted (hidden, filtered information) to transparent/faithful (open, unfiltered, timely signals). | 1–5 (1=opaque/distorted, 5=transparent/faithful) | Are governance decisions and rationale visible to those affected? Can staff access governance information? Are monitoring signals accurate or filtered? Are signals leading (early warning) or lagging (after failure)? | Opaque governance permits shadow governance and capture; distorted signals permit Hiddens to persist; transparent, faithful signals enable learning and early intervention. |
| **4. Participation & Representation** | To what extent do affected stakeholders participate in or have formal say in this governance mechanism? Range: exclusive (decisions made by few) to inclusive (multiple stakeholders participate with real voice). | 1–5 (1=exclusive, 5=inclusive) | Are affected parties included in governance bodies? Can they participate meaningfully or is participation tokenistic? Are participation mechanisms safe (voice can be raised without fear)? Do different stakeholders have equal voice or are some dominant? | Exclusive governance generates legitimacy challenges and misses stakeholder knowledge; tokenistic participation generates cynicism; unsafe voice suppresses weak signals and permits Hiddens. |
| **5. Review Cadence & Adaptability** | How often is this governance mechanism reviewed and updated, and how quickly can it adapt when conditions change? Range: static/infrequent (reviewed rarely, hard to change) to dynamic/frequent (reviewed regularly, easy to change). | 1–5 (1=static/infrequent, 5=dynamic/frequent) | When was governance last reviewed? How long does governance reform take? Is governance design responsive to evidence of drift, capture, or failure? Are exceptional measures (emergency governance, temporary exceptions) reviewed and sunset? | Static governance drifts and decays without maintenance; infrequent review permits latent failures and Hiddens to accumulate; adaptive governance can respond to changing conditions and evidence. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)

| Pattern # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | **Governance Drift & Decay** | Formal structures remain while practice slowly diverges; mandates become stale; meetings persist but lose substance; monitoring continues but findings are not acted upon. | Inattention, turnover, changing incentives, and path dependence erode governance; corrective actions are not closed; artefacts are not reviewed; updates become lower priority. | Creates temporal Hiddens and latent risk; failures appear as sudden surprises despite long deterioration; governance becomes performative while risks accumulate silently. | Introduce review cadences and sunsets (sunset exceptions quarterly, review governance annually); track loop-closure; refresh mandates regularly; measure time-to-escalation and time-to-correct; audit lived versus paper governance. |
| 2 | **Governance Capture & Colonisation** | Governance bodies and processes become biased toward particular interests or perspectives, reducing independence and challenge. | Dependence on regulated parties, information control, revolving doors, political influence, or clique dominance shapes agendas and decisions; governance bodies rotate members infrequently; conflict-of-interest controls are weak. | Produces systemic blindspots, undermines legitimacy, and increases probability of large, repeated failures in favour of captured interests; Hiddens persist because challenge is suppressed. | Strengthen independence and transparency (term limits, rotation, conflict-of-interest enforcement); separate duties (oversight separate from delivery); create protected challenge (internal audit, ombudsperson); test for capture signals and enforce controls; audit decision patterns for bias. |
| 3 | **Paper–Practice Decoupling** | A growing gap emerges between formal governance artefacts and what happens in practice; work is done through unofficial channels; formal process is complied with in documents while acting differently in reality. | Delivery pressure, complexity, and fear make formal processes too slow or risky; formal processes are perceived as unsafe (speaking up brings retaliation); formal processes are unclear or don't match operational reality. | Formal governance becomes performative; risk and accountability migrate into shadow space; learning collapses (lessons learned are not fed back to governance design); Hiddens persist because formal channels do not capture lived reality. | Simplify governance to fit reality; align incentives with governance (reward those who follow formal processes); protect escalation (make speaking up safe); improve tooling (make formal processes faster, less onerous); run lived-governance audits and trace decisions to outcomes; close the gap by integrating learned informal practices back into formal design. |
| 4 | **Learning & Reconfiguration** | Governance is deliberately reviewed, learnings are integrated, and governance design is updated based on evidence of drift, failure, or new conditions. | Scheduled governance reviews (annually or after significant events); post-incident investigations feed back to governance design; governance decisions are tracked and evaluated; feedback loops close (monitoring → finding → action → change). | Governance quality improves over time; Hiddens are detected and remediated; failures decrease; stakeholder trust increases; governance becomes a value driver rather than a cost. | Institutionalise review cadence (quarterly governance review forum); require post-incident governance assessment; measure impact of governance reforms; train staff on governance design; allocate time and resources for governance improvement; link governance quality to incentives. |
| 5 | **Crisis Centralisation & Exceptionalism** | Authority and decision-making become centralised during crisis or under exceptional conditions; formal processes are bypassed; emergency powers are activated. | External shock, acute threat, or repeated failure triggers activation of emergency governance; authority flows to crisis decision-maker or crisis committee; normal oversight is reduced. | Necessary in acute crisis but dangerous if persistent; emergency powers are legitimate short-term but accumulate Hidden risks if they persist; exceptional decision-making can bypass checks that normally prevent failures. | Establish conditions for emergency activation and return to normal (e.g., crisis governance expires after 30 days unless explicitly renewed); require board/stakeholder approval to extend emergency powers; conduct post-crisis review and governance reconfiguration; measure duration of emergency governance use; build checks into emergency governance even during crisis (weekly board review, veto retention). |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)

| Interface Code | Interface type | Core mechanism | Key questions | Failure modes | Remediation examples |
|---|---|---|---|---|---|
| **G-A** | **Delegation Interfaces** (formal authority transfer) | Senior party delegates decision authority to junior party; junior party is expected to decide independently; escalation occurs only if decision is outside delegated bounds. | Can recipient decide independently, or must they request permission? Are delegated decisions protected from routine reversal? What triggers escalation? | Delegation is unclear (recipient unsure if they can decide); delegated decisions are routinely reversed (junior staff lose trust and confidence); escalation is hair-trigger (trivial decisions escalate, defeating the purpose of delegation). | Specify delegation scope in writing with examples; protect delegated decisions (high bar to overturn); measure whether delegated decisions are respected; audit for "permission culture" (junior staff habitually asking for approval despite delegation). |
| **G-B** | **Oversight & Assurance Interfaces** (signal fidelity) | Oversight body monitors performance and signals issues; signal fidelity matters (signals must be accurate, timely, leading rather than only lagging). | Are signals independent (not filtered by those being overseen)? Are signals leading (early warning) or lagging (after failure)? Are signals acted upon or do they accumulate in reports? | Signals are filtered (bad news is not reported); signals are lagging (reporting occurs after failure); signals are aggregated in ways that hide local failures; oversight is confirmatory (only audits areas already known to be compliant). | Multiple independent signal streams; direct access for oversight bodies to operational data; leading indicators alongside lagging KPIs; span of oversight that separates monitoring from delivery; audit trails that track whether findings result in action. |
| **G-C** | **Escalation & Appeal Interfaces** (speed and safety) | Issues, concerns, or decisions are escalated when normal channels fail; escalation must be fast and safe (escalators not punished). | Can issues be raised safely (without fear of retaliation)? Is escalation fast (response within SLA)? Is escalation effective (decisions are changed)? | Escalation is slow (issues accumulate while waiting for response); escalation is unsafe (escalators face retaliation or career consequences); escalation is ignored (issues are escalated but decisions are not changed); escalation is overloaded (too many issues escalate, creating bottleneck). | Protected escalation pathways (skip-level, ombudsperson, external); time guarantees (response within 48 hours); multiple escalation routes; protections against retaliation; tracking of escalation outcome; escalation dashboard showing time-to-response and resolution rate. |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links (recommended)

This framework integrates upstream and downstream with the following primary frameworks:

| Framework | Linkage | How this framework uses it | How it uses this framework |
|---|---|---|---|
| **Power** | Upstream | Governance implements or reflects power distribution; this framework reveals when informal power bypasses formal governance. | Power analysis explains why governance succeeds or fails (incentives to follow vs ignore governance). |
| **Incentives** | Upstream | Incentive structure shapes whether governance is followed or worked around; this framework diagnoses misalignment. | Incentive analysis explains why governance drifts or is captured. |
| **Evidence** | Upstream | Evidence on governance effectiveness informs governance redesign; this framework requires evidence to test governance claims. | This framework produces a testable hypothesis about governance that Evidence framework can validate. |
| **Risk** | Upstream | Risk context determines governance intensity (high-risk systems require stronger governance); this framework aligns governance to risk. | Risk analysis provides consequence context for governance reforms. |
| **Failures** | Upstream | Root-cause analysis of failures often reveals governance failure; this framework diagnoses whether failure is caused by governance. | Failure analysis provides test cases for whether governance worked as designed. |
| **Responsibility** | Downstream | This framework clarifies decision rights and authority; Responsibility framework assigns answerable parties based on governance structure. | Responsibility framework depends on clarity from this framework (cannot assign responsibility if governance is unclear). |
| **Decisions** | Downstream | This framework clarifies decision rights and escalation; Decisions framework designs specific decision processes. | Decisions framework populates governance types (escalation decisions, authority transfers). |
| **Interventions** | Downstream | This framework produces governance reform recommendations; Interventions framework designs implementation. | Interventions framework diagnoses whether governance reform can succeed given power/incentive context. |
| **Hiddens** | Perpendicular | This framework has embedded Hiddens analysis (§8); Hiddens framework provides full cross-framework Hidden cross-check. | Hiddens framework provides six-category visibility audit applied to governance. |

## 7.2 Crosswalk Table (optional but recommended)

| Governance Type | Power linkage | Incentive linkage | Risk linkage | Failures linkage | Responsibility linkage | Decisions linkage |
|---|---|---|---|---|---|---|
| Type 1: Hierarchical authority | Power flows vertically; who is at apex matters | Incentives to escalate vs resolve locally | Centralised authority is brittle; high single-point-of-failure risk | Failure to escalate or reverse bad decisions | Responsibility maps to hierarchical level | Decisions flow up/down hierarchy |
| Type 6: Board of directors | Board power derived from shareholders/stakeholders | Board incentives (composition) affects bias | Board independence is risk mitigation | Board failure to challenge or oversee leads to crises | Board is accountable to shareholders; CEO accountable to board | Strategic decisions made by board |
| Type 9: Assurance & audit | Audit independence is power struggle | Audit incentives affect reporting (soft vs tough) | Audit provides independent risk signal | Audit failure to detect failures enables repeat failures | Audit responsibility is to board, not management | Audit informs board decisions |
| Type 24: Escalation & appeal | Escalation power determines if weak signals reach decision-makers | Escalation incentives (retaliation vs protection) shape usage | Escalation safety is risk mitigation | Escalation failure suppresses weak signals, enabling failures | Escalation responsibility (who must respond) is critical | Escalation decisions must be fast and binding |

## 7.3 Integration Questions by Framework (recommended)

Use this section to check whether this framework's output integrates with the other 36 frameworks in the Analytical Series. For each framework listed, check: "Does this governance analysis have implications for that framework? Should that framework be invoked?" Answer Y/N and note trigger.

| Framework ID | Framework name | Group | Stage | Is there governance implication? (Y/N) | If yes, what is the specific question? |
|---|---|---|---|---|---|
| F001 | Realities | G2 | Upstream | Y | Does governance reflect actual power relationships, or is it divorced from reality? |
| F002 | Situations & Context Classification | G1 | Upstream | Y | Has the situation changed in a way that makes current governance inappropriate? |
| F003 | Boundaries | G1 | Upstream | Y | Does governance architecture match system boundaries, or do governance boundaries create orphan risks? |
| F004 | Power | G2 | Upstream | Y | Where does informal power diverge from formal governance? How does power shape governance effectiveness? |
| F005 | Incentives | G2 | Upstream | Y | Do incentives align with governance (reward compliance, penalise violations)? Or do incentives undermine governance? |
| F006 | Agents & Agency | G3 | Upstream | Y | Are individual agents (decision-makers, escalators, monitors) capable of acting within the governance design? Do they understand their role? |
| F007 | Evidence | G5 | Upstream | Y | Is evidence on governance effectiveness available? What evidence is needed to test governance hypotheses? |
| F008 | Uncertainties | G5 | Upstream | Y | What is uncertain about governance? Where are confidence bounds wide? |
| F009 | Causation & Root Cause | G4 | Middle | Y | Is governance failure a root cause of observed failures? Are there causal chains from governance structure to outcomes? |
| F010 | Risk | G5 | Upstream | Y | What is the consequence context for governance? What risks require strong governance? |
| F011 | Failures | G4 | Middle | Y | Do failures have governance root causes? Has governance prevented or enabled failures? |
| F012 | Systems & Complexity | G1 | Upstream | Y | Does governance complexity match system complexity? Is governance architecture responsive to system scale? |
| F013 | Time & Temporality | G1 | Upstream | Y | Is governance tempo matched to system tempo? Do governance reviews occur frequently enough? |
| F014 | Scale & Scaling | G1 | Upstream | Y | How does governance scale (or fail to scale) as the system grows? |
| F015 | Resources & Constraints | G1 | Upstream | Y | What resources does governance require? Is governance adequately resourced? |
| F016 | Culture & Norms | G3 | Upstream | Y | Do cultural norms support or undermine governance (is escalation safe? is honesty rewarded?)? |
| F017 | Narratives & Meaning | G3 | Upstream | Y | What narratives shape how governance is perceived (is governance seen as protective or oppressive)? |
| F018 | Communications | G3 | Middle | Y | Are governance decisions and rationale communicated clearly? Can staff access governance information? |
| F019 | Legitimacy | G3 | Upstream | Y | Is governance seen as legitimate (right to govern, inclusive, fair)? Or is legitimacy brittle? |
| F020 | Perspectives & Epistemics | G5 | Upstream | Y | Whose perspectives are represented in governance? Are there blind spots in governance thinking? |
| F021 | Diagnosis & Problem Definition | G4 | Middle | Y | Is governance failure correctly diagnosed? Or are governance failures misidentified as other problems? |
| F022 | Hiddens | G6 | Middle | Y | (Primary integration point) Does governance create, conceal, or reveal Hiddens? What Hiddens are specific to governance mechanisms? |
| F023 | Responsibility | G6 | Downstream | Y | Who is accountable for governance design and enforcement? Are responsibilities clear and accepted? |
| F024 | Decisions | G6 | Downstream | Y | How are decisions made within the governance structure? Are decision rights clear? Are escalation decisions fast? |
| F025 | Accountability | G6 | Downstream | Y | Does accountability for outcomes match authority over decisions? Or is accountability displaced? |
| F026 | Interventions | G6 | Downstream | Y | Are governance reforms the right interventions for the identified problems? Will reforms work given power/incentive context? |
| F027 | Transition & Change | G6 | Downstream | Y | Will governance survive transition? Is governance transition planned? Do reforms reflect new requirements? |
| F028 | Learning & Adaptation | G6 | Downstream | Y | Does governance enable learning? Do governance designs update based on evidence? Or is governance static? |
| F029 | Resilience & Robustness | G5 | Upstream | Y | Is governance resilient to shocks (crises, turnover, resource constraints)? Or does governance fail under stress? |
| F030 | Escalation & Appeal | G6 | Middle | Y | (Framework within Framework) Are escalation mechanisms working? Can weak signals reach decision-makers safely? |
| F031 | Compliance & Enforcement | G6 | Downstream | Y | Is governance complied with? Is enforcement consistent and fair? Or is enforcement selective? |
| F032 | Transparency & Secrecy | G5 | Middle | Y | Is governance transparent (visible to those affected)? Or is governance opaque (decisions hidden, rationale unclear)? |
| F033 | Conflict & Negotiation | G3 | Middle | Y | Does governance provide mechanisms for resolving conflicts? Or does governance suppress conflict and permit festering grievances? |
| F034 | Fairness & Justice | G3 | Upstream | Y | Is governance perceived as fair? Do those affected have voice and remedies? Or is governance experienced as unfair? |
| F035 | Ethics & Values | G3 | Upstream | Y | Does governance reinforce ethical values? Or does governance create pressure to behave unethically? |
| F036 | Sustainability | G4 | Downstream | Y | Is governance sustainable (can it be maintained long-term)? Or is governance burning out staff/generating resistance? |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)

Governance mechanisms are primary sources of Hiddens. This section identifies the five systematic sources of governance-related Hiddens and how to detect and remediate them.

| Source # | Hidden source | Mechanism | Why it hides | Detection interface | Remediation lever | Tier escalation rule |
|---|---|---|---|---|---|---|
| **Source 1: Escalation Suppression** | Weak signals, concerns, dissent cannot be raised safely; escalation is slow, blocked, or feared; issues do not reach decision-makers. | Retaliation (explicit or implicit); escalation channels are slow or ineffective; fear of career damage; cultural norms that penalise "going up the chain"; anonymous channels do not exist or are not trusted. | Issues are suppressed before decision-makers can act; failures appear as surprises; patterns persist because feedback does not loop back to governance. | Escalation path test (try to raise concern; measure speed and safety); escalation log analysis (what escalates? what doesn't?); staff interviews on escalation safety; measurement of escalation rate; survey of psychological safety. | Create protected escalation pathways (skip-level, ombudsperson, external channel); enforce no-retaliation policies; improve escalation speed (48-hour response target); measure escalation rate and safety; tie escalation safety to management evaluations; train on escalation importance. | Escalate to Tier 2 if: escalation rate is <1% of issues, if escalation response time >2 weeks, if evidence of retaliation exists, or if staff reports low confidence in escalation safety. Escalate to Tier 3 / Targeted Scans if escalation is mission-critical or if failures appear to have escalation roots. |
| **Source 2: Governance Capture** | Governance bodies become biased toward particular interests (e.g., executives, major shareholders, particular departments); independence is compromised. | Composition bias (governance body is mostly from dominant group); information control (captured body receives only information supporting their bias); revolving doors (regulators, auditors move to regulated industry); clique dominance (informal networks pre-decide outcomes); incentive misalignment (governance reward structure incentivises bias). | Systematic blindspots emerge (captured governance does not see issues it is biased against); Hiddens persist because governance is designed not to see them; failures appear repeated because capture does not change. | Capture diagnostic: audit governance decisions over time for directional bias; review reporting patterns (are bad news reports filtered?); social network analysis of governance bodies (are there cliques?); interview internal audit / ombudsperson on pressure they face; review conflict-of-interest compliance and enforcement. | Strengthen independence: term limits, rotation, open recruitment, separation of duties; enforce conflict-of-interest controls; create protected challenge (internal audit reports to board, not CEO); improve transparency (publish governance decisions and rationale); measure governance composition for diversity and independence; audit reporting patterns for filtering; conduct post-decision review (did governance decision reflect evidence?). | Escalate to Tier 2 if: capture indicators are present (decision patterns showing bias, reporting that is systematically optimistic, clique dominance). Escalate to Tier 3 / Targeted Scans if: capture is in high-consequence areas (safety, integrity, risk), if multiple capture sources are present, or if Hiddens have accumulated (repeated failures in captured area). |
| **Source 3: Paper–Practice Decoupling** | Formal governance artefacts (policies, escalation paths, decision matrices) diverge from lived practice; work is done through informal channels; formal processes are complied with in documents while actions diverge. | Delivery pressure or throughput incentive makes formal process too slow; fear of formal escalation (escalation is seen as unsafe); formal rules are unclear or do not reflect operational context; shadow governance is faster or more effective than formal governance. | Accountability migrates into shadow space (who decided informally?); learning collapses (lessons learned are not fed back to formal governance); formal governance becomes theatre (formal reports show compliance but practice is different); Hiddens persist in shadow space where they are invisible to formal oversight. | Paper-lived audit: compare formal governance artefacts (policy, RACI, escalation procedures) to observed practice via interviews, decision trace-backs, ethnographic observation; track decisions from formal approval through informal implementation; audit exception logs (exceptions are one signal of decoupling). | Simplify formal governance to match reality; align incentives with governance (reward following formal process, penalise shadow practice); make escalation safe (remove fear-based drivers of informal workarounds); run lived-governance audits periodically; integrate learned informal practices back into formal design; strengthen transparency (publish which decisions are made formally vs informally and why); test fidelity of formal processes under pressure (do formal escalation channels function when under delivery pressure?). | Escalate to Tier 2 if: decoupling is systematic (affects multiple process types or multiple departments). Escalate to Tier 3 / Targeted Scans if: decoupling is in high-consequence areas (safety, integrity, risk), if shadow governance is completely divorced from formal (no connection), or if failures have roots in decoupled practices. |
| **Source 4: Authority Ambiguity** | Actual decision-making authority diverges from formal roles; informal power determines outcomes; unclear who can decide. | Formal RACI matrix does not reflect actual influence; informal networks have power not reflected in org chart; formal roles are ceremonial while real authority is held by informal influencers; new staff are unsure who decides because informal networks are opaque. | Decisions are made by invisible decision-makers (accountability is unclear); new staff make wrong decision because they escalated to the wrong person; informal power is not visible to oversight; governance of informal decision-makers is minimal (no checks). | Informal-network mapping: interview decision-makers and their perceived superiors to elicit actual decision chains; trace 5–10 recent major decisions back to actual decision-makers and influencers; compare formal RACI to actual decision patterns; social network analysis. | Map actual authority and integrate into formal governance; make informal authority visible through formal forums (require informal influencers to sit on governance bodies, document their roles); test whether formal decision authority functions or whether informal override occurs; strengthen information access (make sure key decision-makers have access to signals); audit new-staff onboarding to ensure they understand actual authority structure. | Escalate to Tier 2 if: informal authority does not align with formal roles in high-consequence decisions. Escalate to Tier 3 / Targeted Scans if: informal decision-makers are not included in formal governance, if decisions made by informal authority are not auditable, or if failures have traced to decisions made by invisible influencers. |
| **Source 5: Feedback Loop Breakage** | Monitoring and escalation occur, but corrective actions do not result; issues are reported but not acted upon; governance loops do not close. | Monitoring is disconnected from decision authority (data is collected but does not reach decision-makers); escalations are overloaded (too many issues, insufficient authority to address); corrective actions are assigned but not tracked/closed; learning is not fed back to governance design. | Governance becomes performative (reports are filed, audits are conducted, metrics are reviewed, yet practice does not change); Hiddens persist because monitoring does not trigger action; failures repeat because feedback does not loop back. | Loop-closure audit: track 10–15 escalations from issue identification through corrective action; measure time-to-action and closure rate; audit stalled corrective actions (what are they blocked on?); review governance change history (are governance reforms based on monitoring evidence?); interview staff on whether escalations result in action. | Assign closure responsibility with accountability; implement escalation dashboard (visible tracking of escalations and closure); measure loop-closure rate and trend; require executive response to material findings (audit findings, risk escalations); tie loop closure to governance incentives (management evaluation); implement governance-of-governance (meta-governance review body that ensures governance loops close); strengthen transparency (publish what escalations were received and what actions resulted). | Escalate to Tier 2 if: loop-closure rate is <80%, if escalations accumulate unaddressed, or if corrective-action tracking is poor. Escalate to Tier 3 / Targeted Scans if: loop breakage is in safety-critical or risk-critical areas, if repeated failures occur (same issue escalates multiple times), or if governance is not learning (reforms are not based on evidence). |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)

Apply this six-category scan to any governance analysis to identify candidate Hiddens. Use the framework-specific Hidden sources above to tailor the scan.

| Category | Scan question | Governance-specific indicators | Simple test | Record in Hiddens Register as: |
|---|---|---|---|---|
| **1. Information Asymmetry Hiddens** | Who does not know what they need to know? Is information held by few? | Governance information is not accessible; decision rationale is not published; governance reports are selective (show good news, hide bad news); some parties have information others lack about governance. | Ask a sample of staff: "Can you access governance information? Do you know who decides X? Do you know the escalation path?" Survey information access. | Hidden-17 (information asymmetry) if governance information is systematically withheld |
| **2. Voice & Dissent Suppression Hiddens** | Can weak signals be raised safely? Is dissent suppressed? | Escalation is feared; staff report self-censoring; retaliation is observed (or rumoured); escalation results in career damage; "no bad news" culture. | Ask: "Can you raise a concern safely? What would happen if you escalated?" Trace recent escalations and outcomes; interview escalators on experience. | Hidden-2 (voice suppression) if escalation is unsafe or feared |
| **3. Accountability Gap Hiddens** | Is there an accountability vacuum? Are decisions orphaned? | Decisions have no clear owner; accountability for governance flows upward (blame upstream) not downward (consequences for decisions); shadow governance has no accountability. | Ask: "Who decided X? Are they accountable if it goes wrong?" Trace recent decisions to formal owner; compare to actual decision-maker. | Hidden-5 (accountability gap) if no one is answerable for decisions or governance |
| **4. Framing & Narrative Capture Hiddens** | Are certain narratives told and others suppressed? Does framing hide reality? | Dominant narratives in governance (all is well, all issues are being addressed, risk is under control); alternative narratives are not heard; metrics are presented in ways that hide problems (aggregation, selective reporting). | Ask: "What is the narrative about governance? Is everything working?" Compare to evidence of problems. Audit metric presentation for ways issues are hidden. | Hidden-8 (framing capture) if governance narratives systematically hide problems or favour certain interests |
| **5. Contextual Blindness Hiddens** | Are certain contexts invisible to governance? Are there blind spots? | Governance does not perceive issues in certain departments, functions, or layers; issues that are visible at frontline are not visible at top; governance is blind to unintended consequences of its own rules. | Ask: "Is governance aware of [specific operational context]?" Map governance visibility across functions/layers. Audit whether governance has detected issues that operational staff report. | Hidden-24 (contextual blindness) if governance has systematic blindspots in certain contexts |
| **6. Temporal & Historical Hiddens** | Are past failures forgotten? Is governance learning latent? | Repeated failures (same issue escalates again); governance does not learn (reforms are not based on past failures); historical Hiddens are not known to current staff; governance reviews do not occur frequently enough. | Ask: "Have we seen this issue before? What was done last time?" Audit failure history and governance change history; check whether same issues are addressed repeatedly. | Hidden-15 (latency/historical Hiddens) if past governance failures are forgotten and failures repeat |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)

When Tier 1 scan identifies candidates, use this crosswalk to structure Tier 2 investigation. Map candidates to governance types, interfaces, and remediation levers.

| Hidden title / mechanism | Governance types that can generate it | Governance interfaces involved | Evidence of presence | Remediation lever | Probe design (hypothesis → test) |
|---|---|---|---|---|---|
| **G-H01: Escalation Suppression** (weak signals filtered, issues suppressed) | Types 24 (Escalation), 9 (Audit), 22 (Veto & Challenge), 26–30 (Cultural, networks, norms) | G-C (Escalation & Appeal Interface) | Low escalation rate; staff report fear; retaliation stories; major failures appear as surprises; escalation response time >2 weeks | Create protected escalation channels; enforce no-retaliation policies; measure escalation rate and response time; train on importance | Hypothesis: "Escalation is unsafe; staff will not raise concerns under pressure." Test: Run escalation scenario (simulate significant concern under deadline pressure); measure uptake, time-to-response, and whether escalation changes decision. |
| **G-H02: Paper–Practice Decoupling** (shadow governance, formal vs actual) | Types 11–15 (Rules & Policy), 21–25 (Decision Rights & Escalation), 26–30 (Informal & Shadow) | G-A (Delegation), G-B (Oversight), G-C (Escalation) | Decision trace-backs show formal vs actual paths diverge; staff use workarounds; exceptions are chronic; lived-governance audit shows practice differs from policy | Simplify governance; align incentives; make escalation safe; run lived-governance audits; integrate informal practices back into formal design | Hypothesis: "Major decisions are made informally; formal governance is theatre." Test: Trace 5–10 recent decisions from formal approval through actual implementation; identify informal decision-makers; map formal vs actual paths. |
| **G-H03: Governance Capture** (systematic bias, clique dominance) | Types 6–10 (Institutional), 26–30 (Informal & Shadow) | G-B (Oversight & Assurance Interface) | Governance decisions show directional bias (favour certain interests); cliques dominate; reporting is optimistic; independence is compromised | Strengthen independence (rotation, term limits); separate duties; create protected challenge; enforce conflict-of-interest controls; audit decision patterns for bias | Hypothesis: "Governance is captured by [specific interest]; decisions are systematically biased." Test: Audit governance decisions over 12 months for directional bias; social network analysis of governance bodies; interview internal audit on pressure; review conflict-of-interest compliance. |
| **G-H04: Feedback Loop Breakage** (monitoring without action, learning failure) | Types 16–20 (Control & Monitoring), 24 (Escalation) | G-B (Oversight & Assurance Interface) | Loop-closure rate <80%; escalations accumulate; corrective actions stall; governance does not reform based on evidence; same failures repeat | Assign closure responsibility; implement escalation dashboard; measure and trend loop closure; require executive response; implement meta-governance | Hypothesis: "Issues escalate but are not acted upon; governance loops do not close." Test: Track 15 escalations from identification through action completion; measure time-to-action and closure rate; audit where stalled actions are blocked. |
| **G-H05: Authority Ambiguity** (actual decision-makers unclear, informal power) | Types 1–5 (Architectural), 21–23 (Decision Rights & Delegation) | G-A (Delegation Interface) | Formal RACI does not reflect actual influence; new staff unsure who decides; informal influencers hold power not reflected in org chart; decisions traced to invisible decision-makers | Map actual authority; integrate informal authority into formal governance; make authority visible; test whether formal decision authority functions | Hypothesis: "Actual decision-makers are informal influencers not on the formal RACI." Test: Interview decision-makers and perceived superiors to elicit actual decision chains; trace 5–10 decisions back to actual decision-makers; compare formal RACI to actual patterns. |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)

When executing this framework in Investigative Run Mode with Tier 2 Hiddens mapping, use these standard prompts to structure the Hidden investigation:

**Prompt for Source 1 (Escalation Suppression):**
"Map the escalation pathway for a significant concern (safety, integrity, risk). Test it: (1) Identify escalation steps, time limits, protection mechanisms. (2) Interview staff: 'Can you raise a concern safely? What would happen if you escalated?' (3) Trace a recent escalation to see if it was handled safely and quickly. (4) Measure: escalation rate (% of issues escalated), response time (median, max), safety (% of escalations free of retaliation)."

**Prompt for Source 2 (Governance Capture):**
"Audit governance composition and independence. (1) Review governance body membership: who is on the board/committee? Are they diverse, independent, rotated regularly? (2) Trace 5 recent governance decisions: did the decision pattern show bias toward specific interests? (3) Interview governance members on pressure they face; review conflicts-of-interest compliance. (4) Measure: governance composition diversity, independence score, decision pattern consistency with evidence."

**Prompt for Source 3 (Paper–Practice Decoupling):**
"Compare formal governance to lived practice. (1) Select a governance mechanism (e.g., decision-right matrix, escalation policy, policy enforcement). (2) Document the formal design (what does it say should happen?). (3) Interview operational staff and observe practice: what actually happens? (4) Trace 5 decisions: do they follow formal path or go informal? (5) Audit exceptions: are exceptions chronic (suggesting the formal rule is wrong)?)"

**Prompt for Source 4 (Authority Ambiguity):**
"Map formal vs actual authority. (1) Document formal authority (org chart, RACI, decision-right matrix). (2) Interview decision-makers and perceived superiors: who actually influences [specific decision type]? (3) Trace 5 recent decisions: did they follow the formal path or was authority exercised informally? (4) Assess: are formal and actual authority aligned or divergent? If divergent, who are the invisible decision-makers and how can they be integrated into formal governance?"

**Prompt for Source 5 (Feedback Loop Breakage):**
"Audit governance loop closure. (1) Identify a governance loop: monitoring → escalation → decision → corrective action → verification. (2) Track 10–15 instances of that loop: did they close? (3) For those that closed, measure time-from-issue-identification to corrective-action-completion. (4) For those that did not close, identify where they stalled. (5) Interview owners of stalled items: what is blocking closure? (6) Measure: loop-closure rate (% that complete), median time-to-closure, reasons for non-closure."

## 8.5 Escalation Rule (Tier 3 – full-spectrum Hiddens escalation)

Escalate to Tier 3 Hiddens scan or 13 Targeted Hiddens Discovery Scans (OG v2.5 §7.5) if any of these conditions apply:

1. **High consequence**: Governance failure could result in safety harm, regulatory sanction, existential threat, or severe reputational damage.
2. **Adversarial context or strategic concealment**: Reason to believe governance failure is deliberate (not accidental); Hiddens are actively concealed.
3. **Persistent disagreement or inconsistent evidence**: Stakeholders disagree on whether governance is working; evidence is contradictory; some claim governance is working, others claim it is broken.
4. **Repeat failures**: Same governance problem has occurred multiple times; governance was reformed but failure repeated.
5. **Strong suspicion of cascades or reinforcement**: Governance failure appears to have created feedback loops that generate additional Hiddens (e.g., escalation suppression → weak signals not surfaced → failures hidden → governance trust lost → escalation suppression worsens).

**When escalating to Tier 3 / Targeted Scans**, use Operating Guide v2.5 §7.5 to select the appropriate Targeted Hiddens Discovery Scans. For governance, relevant scans include:
- **Scan G-A**: "Escalation Safety and Signal Fidelity" (Hidden-2, Hidden-18, Hidden-20)
- **Scan G-B**: "Informal Authority and Clique Governance" (Hidden-6, Hidden-8)
- **Scan G-C**: "Information Control and Narrative Capture" (Hidden-8, Hidden-17, Hidden-19)
- **Scan G-D**: "Paper–Practice Decoupling and Shadow Governance" (Hidden-19, Hidden-24)
- **Scan G-E**: "Feedback Loop Closure and Learning" (Hidden-20)

---

# 9. Framework Application Protocol (mandatory)

## 9.1 Application Steps Table

| Step # | Step name | Action | Outputs / artefacts |
|---:|---|---|---|
| 1 | **Situation & Goal Clarification** | Confirm the system boundary, stakeholders, governance question (formal vs lived, reform options, Hidden detection, interface failure diagnosis). Confirm Run Mode (Rapid vs Investigative). Confirm Full Depth vs Light Depth routing using OG §4.3. List minimum group coverage (primary G6, secondary G3; check for others per §4.3). | Run mode selected; scope bounded; goals clear; minimum group coverage and depth plan confirmed; time/resource budget allocated. |
| 2 | **Governance Scan (Tier 1)** | Map formal governance structures (Section 2); identify active meta-categories and governance types (Section 3). Map dimensions (Section 4). Scan all six Hiddens meta-categories (§8.2 early pass). Create preliminary Governance Catalogue listing active types. | Governance Catalogue (active types); Dimension Profile (scope, independence, transparency, participation, review cadence); Hiddens meta-category scan notes; preliminary candidate Hiddens. |
| 3 | **Paper vs Lived Audit** | Compare formal artefacts (org chart, policies, charters, decision-right matrices) to observed practice: interview staff, trace recent decisions, test escalation paths, observe informal forums. Profile along five dimensions (Section 4). Identify paper–practice gaps. Run Tier 1 Hiddens re-scan with lived-practice findings. | Governance map (paper and lived, side-by-side); Dimension profile (quantified 1–5 score per dimension); Paper–practice gap assessment (size, location, mechanism); updated Hiddens shortlist. |
| 4 | **Dynamics & Interface Analysis** | Identify active dynamic patterns (Section 5) present in the scenario: is governance drifting? Is capture present? Is decoupling occurring? Are there learning loops? Is crisis governance persistent? Map interfaces (Section 6) and test for failures (§6.1): delegation clarity, oversight independence, escalation safety. Conduct Tier 1 Hiddens re-scan. | Dynamic patterns present (with severity assessment); Interface failure map (G-A/G-B/G-C status); updated Hiddens shortlist; escalation triggers for Tier 2–3 if needed. |
| 5 | **Hiddens Source & Remediation Mapping** | Run §8.1 source analysis: map identified candidates to five Hidden sources (escalation suppression, capture, decoupling, authority ambiguity, feedback breakage). Design detection and remediation for each (§8.3 crosswalk). Conduct tests/probes (§8.4): escalation scenarios, live-governance audits, capture diagnostics, authority mapping. Run Tier 2 Hiddens mapping if complexity warrants. | Hiddens Register (with mechanism, detection interface, remediation lever, probe); Evidence Ledger (claims, evidence quality, gaps); Hypothesis/Test Backlog (proposed tests prioritised by consequence); probe results. |
| 6 | **Governance Reform Translation** | Synthesise findings into governance reform options: changes to architecture (Section 2), types (Section 3), dimensions (Section 4), dynamics control (Section 5), interfaces (Section 6), and Hiddens remediation (Section 8). Prioritise reforms by consequence and feasibility. Identify risks of reforms (unintended consequences). Sequence reforms (quick wins first, followed by structural changes). Design metrics for monitoring reform effectiveness. | Governance Reform Backlog (prioritised list of reforms with rationale, sequencing, success metrics, and risks); Decision/Action Record (if recommending specific reforms); Residual Unknowns + Closure Note (what remains unknown; escalation decision for Tier 3/Targeted Scans if needed). |
| 7 | **Decision & Closure** | Review findings against original governance question. Confirm that all group coverage and depth requirements have been met (check Operating Guide §4.3). Tag all claims as F/I/A/U. Decide on closure: is governance acceptable as-is, or are reforms required? If reforms: which are mandatory, which are conditional on other changes? If escalation to Tier 3/Targeted Scans: document rationale per §8.5. Populate shared registers (Governance Catalogue, Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Residual Unknowns). | Decision Summary (governance status: acceptable / needs reform / requires Tier 3 investigation); Recommended Actions (with priorities and sequencing); Closure Note (what is decided, what is unknown, next steps); all standard registers populated with F/I/A/U tags and residual unknowns. |

## 9.2 Standard Deliverables (recommended)

**Minimum deliverable (1–2 pages):**
- Governance type summary (10–15 most active types)
- Dimension profile (5 dimensions scored 1–5)
- Paper–practice gap assessment (size, location, root cause)
- Top 3–5 governance risks and corresponding reform options
- Decision summary (is governance acceptable or requires reform?)

**Full deliverable pack:**
- Complete Governance Catalogue (all 30 types assessed: active/inactive)
- Governance Dimension Profile (five dimensions with rationale)
- Governance Dynamics Assessment (five patterns with severity)
- Interface Failure Analysis (G-A/G-B/G-C status and failure modes)
- Hiddens Register with Tier 1–2 mapping (mechanism, detection, remediation, probe)
- Evidence Ledger (governance claims with evidence quality and gaps)
- Hypothesis/Test Backlog (proposed tests prioritised by consequence)
- Governance Reform Backlog (prioritised reforms with sequencing and risk)
- Residual Unknowns + Closure Note

**Monitoring indicators** (for tracking governance improvement post-reform):
- Loop-closure rate (corrective actions completed on time; target: >90%)
- Escalation rate (issues escalated as % of issues identified; target: varies by organisation but <1% suggests suppression, >10% suggests escalation overload)
- Escalation response time (median and max; target: 48-hour response)
- Governance change history (reforms implemented, effectiveness measured)
- Paper–practice gap trend (is decoupling reducing?)
- Governance-related incident rate (are governance failures decreasing?)
- Stakeholder trust in governance (survey; target: >80%)
- Staff perception of escalation safety (survey; target: >75%)

### Canonical shared registers (Operating Guide v2.5 aligned; mandatory for LLM use)

| Shared register / artefact | Required | Notes |
|---|---:|---|
| **Governance Catalogue** | Yes | List all identified governance types (6×5 taxonomy); mark active/inactive; include mechanism summary and criticality (high/medium/low). |
| **Governance Dimension Profile** | Yes | Score focal governance on five dimensions (1–5); include rationale and evidence. |
| **Governance Dynamics Assessment** | Yes | List which of five patterns (drift, capture, decoupling, learning, crisis) are present; severity (H/M/L); mechanism detail. |
| **Interface Failure Map** | Yes | G-A/G-B/G-C status (working/degraded/broken); specific failure mode diagnosis for each degraded/broken interface. |
| **Group Coverage Matrix (G1–G6)** | Yes | Record which groups were examined at Full Depth vs Light Depth; note gaps; confirm minimum coverage per OG §4.3. |
| **Hiddens Register** | Yes | Populate candidate Hiddens relevant to governance; include mechanism, detection interface, remediation lever, probe, and owner. Link to Hidden sources (§8.1) and governance types (§3.1–3.6). |
| **Evidence Ledger** | Yes | Track claims about governance effectiveness, independence, escalation safety, paper–practice fidelity; record evidence quality (1–5) and gaps. |
| **Hypothesis/Test Backlog** | Yes | Convert Unknowns into tests: lived-governance audits, escalation scenarios, capture diagnostics, informal-network mapping. Prioritise by consequence. |
| **Governance Reform Backlog** | Yes | Prioritised reforms (architecture, bodies, rules, interfaces, Hiddens remediation) with sequencing, success metrics, and risk assessment. |
| **Residual Unknowns + Closure Note** | Yes | State what remains unknown about governance (informal power extent, true escalation safety, capture scope); include mechanism, impact, and next probe. Escalation decision per §8.5. |
| **Decision/Action Record** | Conditional | Required when proposing governance changes; include rationale, sequencing, success metrics, and risks. |
| **Investigation Plan (post-failure)** | Conditional | Required when governance failure contributed to the incident; include suspected Hiddens and Tier 2–3 probes. |

---

# 10. Framework Principles (mandatory)

## 10.1 Principles Table

| Principle # | Principle name | Description |
|---|---|---|
| 1 | **Paper and Lived Governance Both Matter** | Analyse formal governance (charts, policies, roles) AND lived practice (actual decisions, informal networks, where work gets done). Paper-only analysis misses the real governance system; lived-only analysis misses formal safeguards and escalation routes. Governance assessment requires simultaneous view of both. |
| 2 | **Escalation Safety Is a Prerequisite** | Governance can only function if weak signals, disagreements, and concerns can be raised safely. Without escalation safety, Hiddens persist and failures become surprises. Escalation must be independent of delivery pressure and protected from retaliation. Test escalation safety explicitly. |
| 3 | **Interface Governance Must Be Explicit** | Governance at boundaries (delegation, oversight, escalation) requires explicit design and testing. Interface failures create orphan risks and responsibility gaps; they must be diagnosed and remediated as part of governance reform. Do not assume interfaces work; test them. |
| 4 | **Governance Captures or Drifts Without Renewal** | Formal governance does not remain neutral; it is biased by interests (capture) or erodes by inattention (drift). Periodic governance reviews, sunsets on exceptions, rotation of roles, and independence enforcement are necessary to prevent Hiddens and maintain legitimacy. Governance decay is the default. |
| 5 | **Governance Must Match System Complexity, Tempo, and Consequence** | Governance architecture must be calibrated to system scale, decision speed, and failure consequence. Over-light governance on safety-critical systems is dangerous; over-heavy governance on fast-moving systems creates delay and shadow governance. Right-sized governance prevents both under- and over-governance. |

---

# 11. Glossary (local domain terms; recommended; mandatory for "Stable" status)

## 11.1 Local domain glossary

**Authority (formal vs actual):** Formal authority is specified in org charts, decision-right matrices, and role descriptions. Actual authority is determined by who can influence decisions and whose decisions are respected; it often diverges from formal authority. Complete governance analysis requires mapping both.

**Capture (governance):** Systematic shaping of governance decisions toward particular interests while excluding contrary signals. Capture can be active (deliberate influence) or passive (composition bias). Governance capture is a primary Hiddens source.

**Delegation Interface (G-A):** The interface where authority is delegated from a senior party to a junior party. Failure modes: unclear scope, routine reversal of delegated decisions, hair-trigger escalation. Key test: can the delegated decision be made independently or must approval be sought?

**Escalation (governance):** The mechanism by which issues, concerns, or decisions are raised from operational staff to decision-makers when normal channels fail. Escalation safety (can issues be raised without fear?) is prerequisite for Hiddens visibility.

**Escalation & Appeal Interface (G-C):** The interface where issues are escalated and decisions can be appealed. Failure modes: slow response, unsafe escalation (retaliation), ignored escalations, overloaded escalation channels. Key test: can concerns be raised safely and are they resolved quickly?

**Lived governance:** The governance that actually operates (informal networks, backchannels, cultural norms, shadow forums, actual decision-making routes). Often diverges from formal/paper governance.

**Oversight & Assurance Interface (G-B):** The interface where oversight bodies monitor performance and signal issues. Failure modes: filtered signals (bad news not reported), lagging signals (reporting after failure), confirmatory audits (only audit areas already known to be compliant). Key test: are signals independent of those being monitored? Are they leading or lagging?

**Paper governance:** The formally documented governance (org charts, policies, decision-right matrices, charters, procedures). May diverge significantly from lived governance.

**Shadow governance:** Informal governance that diverges from formal governance; decisions made through backchannels or shadow forums rather than formal escalation. When shadow governance is faster or more effective than formal governance, it indicates formal governance is misaligned with operational reality.

**Transparency (governance):** The extent to which governance decisions, rationale, and information are visible to those affected. Opaque governance permits capture and shadow governance. Transparent governance enables learning and challenge.

---

# 12. Document Control (recommended; mandatory for "Stable" status)

## 12.1 Version History

| Version | Date | Changes |
|---|---|---|
| v2.0 | 2026-04-06 | Full rewrite to Master Template v2.3 with OG v2.5 integration. Updated all OG references from v1.5 to v2.5. Expanded §1.6 LLM Use & Operating Guide Integration with Tier 1–3 Hiddens routing, Targeted Scans integration, and Information Requests schema. Added formal Introduction section (four subsections: what is governance, why it matters for Hiddens, what it produces, how to use it). Expanded §2–6 with detailed descriptions per template §2.2 (meta-categories, governance types, dimensions, dynamics, interfaces). Expanded §7.3 with all 36 canonical frameworks and Group/Stage columns. Expanded §8 with full Tier 2 Hiddens routing and 13 Targeted Scans integration; restructured Hidden sources (§8.1) with detection/remediation; added §8.4 embedded micro-protocols. Added §11 (Glossary) with 10 local domain terms. Enhanced Application Protocol (§9) with 7-step discipline and detailed process. Added §10 Principles table with five core governance principles. Full compliance with 600–1000 line requirement and complete/no-placeholder rule. |
| v1.3 | 2026-03-28 | Audit remediation: verified all 30 types with diagnostic cues and failure signatures (§3.0–3.6). Standardised Dynamics to five patterns with mechanism detail (§5.1). Interface Types aligned to G-A/G-B/G-C canonical model (§6.1). Updated Change Log and Appendices. Framework standardised to Analytical Series format. |
| v1.2 | 2026-03-28 | Terminology refinement: replaced colloquial 'visibility gaps' with 'analytical gaps' where context describes limitations of analytical lens. |
| v1.1 | 2026-03-27 | Added Framework of Beliefs integration entry; series count updated to 33 frameworks. |
| v1.0 | 2025-12-16 | Initial standardised rewrite to Analytical Series master template; expanded governance type analyses; standardised dimensions, dynamics, interfaces; embedded Hiddens analysis; application protocol and appendices. |

## 12.2 Integration Notes (optional)

Use this framework whenever:
- Formal governance exists but outcomes remain poor or surprising
- Oversight reports are consistently positive while operations are deteriorating (governance theatre indicator)
- Escalation is unsafe, ignored, or overloaded
- Decision rights are contested or drifting
- Multi-party systems are fragmenting across boundaries
- Crisis governance is persisting or exceptional powers are becoming normal
- Informal power (networks, cliques) is determining outcomes despite formal roles
- Paper and lived governance appear deeply decoupled
- Culture or norms contradict stated values and drive unsafe behaviour
- Repeated failures occur in areas with governance oversight

---

## Appendices (optional but recommended)

### Appendix A — Consolidated 30-Type Quick Reference

| ID | Type | Category | Core mechanism |
|---:|---|---|---|
| 1–5 | Architectural types (Hierarchical, Federal, Polycentric, Network, Hybrid) | I | How authority is distributed (hierarchy, federation, polycentric, network, hybrid) |
| 6–10 | Institutional & role types (Board, Regulator, Executive, Audit, Participatory) | II | Governance bodies and their independence/mandates |
| 11–15 | Rule & policy types (Policies, Legal, Ethical, Automation, Enforcement) | III | How rules and constraints are codified and enforced |
| 16–20 | Control & feedback types (KPI, Risk, Safety, Learning, Exception management) | IV | How performance is monitored and corrections are made |
| 21–25 | Decision & escalation types (RACI, Veto, Delegation, Escalation, Crisis governance) | V | Who decides, who can veto/appeal, how issues escalate |
| 26–30 | Informal & shadow types (Norms, Networks, Information control, Shadow forums, Tacit practices) | VI | How informal power and culture actually determine outcomes |

### Appendix B — Full Hiddens Crosswalk (Tier 3: 30-Type Mapping)

[Detailed Tier 3 Hiddens-to-Types mapping for high-consequence governance investigations; includes all 30 Hiddens types cross-mapped to governance types and interfaces; available on request from Series Maintainer]

### Appendix C — Worked Example: Post-Incident Governance Assessment

[Case study of applying the framework to a post-incident governance review; example traces paper vs lived decoupling, identifies capture and escalation failure, maps Hiddens sources, and recommends governance reforms; available on request from Series Maintainer]

### Appendix D — Governance Interfaces (codebook)

| Code | Interface type | Primary failure modes | Detection tests |
|---|---|---|---|
| G-A | Delegation Interfaces | Unclear scope; routine reversal; hair-trigger escalation | Can recipient decide independently? Are delegated decisions respected? |
| G-B | Oversight & Assurance Interfaces | Filtered signals; lagging indicators; confirmatory audits | Are signals independent? Are they leading or lagging? |
| G-C | Escalation & Appeal Interfaces | Slow response; unsafe escalation; ignored escalations; overload | Can issues be raised safely? Are they resolved quickly? |

---

## End of Framework of Governance v2.0
