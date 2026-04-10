# Framework of Incentives
*A Six-Layer Taxonomy for Diagnosing Motivation, Misalignment, and Behavioral Response*

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
- Group (Primary): G3 — Agency & behavioural drivers (Agency)
- Group (Secondary): G2 — Structure, dependencies & mechanism (Mechanism)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Diagnose what motivates action (and inaction) across roles, organisations, platforms, and systems; identify incentive misalignment, gaming, and perverse outcomes; design incentive-aware governance and interventions; anticipate behavioural responses and adaptation
- Primary Audience: Executives; strategists; programme leaders; governance and compliance leaders; risk and resilience leaders; investigators/auditors; policy and regulatory designers; product/platform leaders; transformation and change leaders
- Dependencies / Key Inputs: Focal decision/problem statement; actor/stakeholder map; operational process and system maps; KPI/measurement regime; governance and accountability model; performance data and narratives; timeline of incentive changes
- Primary Outputs: Incentive inventory (6×5 types); incentive profiles (five dimensions); incentive dynamics map; interface hotspot map; hiddens source register + tiered Hiddens scan outputs; intervention and governance design implications
- Change Log (brief): v2.1 update: Replaced §1.6 with MRT v3.0 LLM Integration Bridge format (1.6.1 Extract pointer, 1.6.2 Near-neighbour disambiguation table with 5 analytical distinctions from adjacent frameworks, 1.6.3 10-item Routing triggers list). All other sections preserved from v2.0. (Revised: Anthropic Claude Opus 4.6)

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | What motivates action here, for whom, and in which direction, given the configuration of incentives? |
| Addresses | Intrinsic vs extrinsic motivation; positive vs negative incentives; aligned vs misaligned incentives; perverse incentives; incentive structures; moral hazard; principal–agent problems |
| Gap Filled | Values capture what matters; Personas capture typical motivational styles; but the systematic structure of incentives—how rules, payoffs, norms, and information jointly shape behaviour—is not otherwise mapped |
| Complements | Agents; Personas; Values; Power; Resources; Processes; Situations; Diagnosis; Causation; Intervention; Governance |
| Key Characteristics | Relational, context-dependent, multi-sourced, often partly hidden or misperceived; inherently dynamic and subject to drift, misalignment, and crowding-in/crowding-out effects |
| Main Contributions | Six meta-categories and thirty core incentive types; five cross-cutting dimensions; twelve dynamic patterns; five interface types; hiddens sources analysis; tiered Hiddens cross-check protocol; application protocol; principles; complete glossary |

---

# Introduction

## What is Incentives?

Incentives are structured patterns of anticipated consequences that make some actions more attractive, salient, or viable than others for particular agents in particular situations. They are the practical bridge between values (what matters), personas (typical motivational profiles), power (what shapes possibility), and resources (what can be deployed), as experienced from specific perspectives and enacted by specific agents within concrete situations and processes.

Where Values asks "What matters here, to whom, and why?" and Personas asks "What kind of motivational profile does this agent typically have?", the Framework of Incentives asks: Given what matters and what is possible, **what do agents actually have reason to do?** Incentives convert abstract value structures, persona tendencies, and power configurations into local motivational gradients—perceived payoffs, risks, and obligations that bias behaviour in one direction rather than another.

This framework explicitly addresses intrinsic versus extrinsic motivation, positive versus negative incentives, aligned versus misaligned incentives, perverse incentives, incentive structures, moral hazard, and principal–agent problems. It fills a critical gap in the series: values and personas describe content of motivation and typical motivational styles, but structured incentives—how rules, contracts, norms, and information flows jointly pull behaviour—are not otherwise systematically mapped.

## Why does Incentives matter for Hiddens work?

Incentive structures are powerful visibility-failure generators. When incentives are misaligned with stated goals, they create systematic distortion (Hidden-6): what is sayable and measurable diverges from what is true. Gaming and metric optimisation produce mirages (Hidden-7): apparent alignment and performance become artefacts of incentives rather than real improvement. Framing (Hidden-8) selects which incentives count (often financial/compliance), excluding identity, status, and option-value incentives that dominate real behaviour.

Secret incentives (Hidden-11) are concealed—unofficial targets, political pressures, side-deals—making behaviour appear irrational under the official model. Fragmentation (Hidden-14) splinters incentives across silos, creating coordination failures and system-level harm. Ghost incentives (Hidden-17) persist as legacy arrangements long after their original rationale disappears, and positional invisibility (Hidden-21) means different roles face different incentive experiences.

Without this framework, these hiddens remain latent. With it, incentive analysis becomes a disciplined, testable mechanism for surfacing distortion, gaming, and misalignment before they cascade into failure.

## What does this framework produce?

This framework operationalises incentive analysis through six core elements:

1. **A taxonomy of 30 incentive types** organised into six meta-categories (structural/role-based, material/transactional, informational/cognitive, social/relational, normative/identity, temporal/optionality) that recur across contexts and enable rapid initial classification.

2. **Five cross-cutting dimensions** (source of motivation, valence & mode, alignment, scope & level, transparency & awareness) that profile any incentive and explain why different agents classify the same incentive differently.

3. **Twelve dynamic patterns** (crowding out/in, feedback & habit formation, threshold & tipping effects, drift & goal displacement, path dependence & lock-in, incentive cascade, regime shift, adaptation & workaround formation, equity perception lag, reference point instability, attention capture, substitution & migration) that describe how incentives evolve and interact.

4. **Five interface types** (contractual & principal–agent, regulatory & compliance, platform & algorithmic, relational & reputation-based, mission & narrative) that make visible where incentive failure concentrates and how interventions can be targeted.

5. **Hiddens source analysis and tiered Hiddens scans** (Tier 1 six-category visibility audit, Tier 2 default mapping layer covering 13 hidden types, Tier 3 full-spectrum escalation) that surface systematic sources of incentive misreading.

6. **A seven-step application protocol** that moves from incentive mapping through meta-category scan, dimensional characterisation, dynamics analysis, interface mapping, Hiddens checking, and redesign/intervention.

The framework populates standard registers (Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests) that integrate with the broader Analytical Series investigation workflow.

## How to use this framework

Invoke this framework whenever behaviour persists despite policy or training, performance looks good on dashboards but outcomes are poor (suspect gaming), accountability is unclear and blame-shifting is likely, incentives are mediated by platforms or algorithms, or the system is drifting over time due to legacy targets.

The framework works in both Rapid Run Mode (light-touch incentive scan and type-mapping) and Investigative Run Mode (deep dimensional profiling, full Hiddens scanning, multi-level evidence synthesis). Default execution is Light Depth Framework Execution: assign incentive types, profile key dimensions, spot obvious interfaces, run a Tier 1 Hiddens scan. Escalate to Full Depth when consequence is high, evidence is contested, gaming is suspected, or multi-level coordination is required.

For LLM execution, see §1.6 for the complete LLM integration specification, standard registers, and copy-ready run prompts. The framework is designed to be directly executable by an LLM given a scenario and the Operating Guide, producing a disciplined incentive analysis with explicit Hiddens, F/I/A/U tagging, and bounded closure.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Incentives are structured patterns of anticipated consequences that make some actions feel more or less attractive (including rewards, sanctions, status effects, identity coherence, optionality, and time-based payoffs) **for particular agents in particular situations**. They are the practical bridge between values (what matters), personas (typical motivational styles), power (what shapes possibility), and resources (what can be deployed).

The Framework of Incentives provides a systematic way to map, characterise, and redesign incentive landscapes. Where the Framework of Values asks "What matters here, to whom, and why?" and the Framework of Personas asks "What kind of motivational profile does this agent typically have?", the Framework of Incentives asks: **"Given what matters and what is possible, what do agents actually have reason to do?"** Incentives convert abstract value structures, persona tendencies, and power configurations into local motivational gradients—perceived payoffs, risks, and obligations that bias behaviour in one direction rather than another.

This framework explicitly addresses intrinsic versus extrinsic motivation, positive versus negative incentives, aligned versus misaligned incentives, perverse incentives, incentive structures, moral hazard, and principal–agent problems. It fills a gap in the series: values and personas describe content of motivation and typical motivational styles, but structured incentives—how rules, contracts, norms, and information flows jointly pull behaviour—are not otherwise systematically mapped.

The primary output of this framework is an incentive inventory across all six meta-categories; profiles of priority incentives using five dimensions; identification of common dynamics and failure modes (gaming, moral hazard, crowding effects); interface hotspot analysis; hiddens source register with tiered scans; and redesign options integrated with diagnostic findings, causal models, and intervention planning.

## 1.2 Assumptions & Preconditions

### Assumptions Register

| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Agents are motivated by consequences they anticipate, not merely what objectively exists | Domain | Incentive analysis becomes moot; agents appear irrational or untrackable | Behaviour-first analysis: compare actions against stated vs observed incentive structures; test for salience bias | Expand inquiry to include non-incentive drivers (taboos, norms, emergencies); mark gaps |
| Incentive structures can be made explicit and mapped systematically across six meta-categories | Method | Some incentives remain permanently opaque; analysis incomplete or misleading | Pilot mapping exercise; test completeness against multi-role stakeholder interviews | Accept partial visibility; use Hiddens scan to flag concealed incentives; iterate |
| Incentives interact and evolve dynamically (crowding effects, drift, path dependence) | Structural | Static metric snapshots become sufficient; interventions appear straightforward when vulnerable to adaptation | Time-series analysis of behaviour/metrics; scenario testing of incentive changes | Build feedback loops and monitoring into governance; plan for adaptive responses |
| Incentive misalignment, gaming, and perverse incentives are detectable patterns, not random noise | Method | Failure diagnosis becomes impossible; systemic problems appear unavoidable | Pattern analysis (Goodhart effects, unintended consequences); compare formal rules to actual behaviour | If patterns unclear, escalate to Hiddens Tier 2/3 for distortion, mirage, and secret incentives |
| Multi-source incentives (structural, material, social, normative, temporal) are sufficiently independent to analyse separately | Structural | Framework output becomes non-actionable; cannot redesign specific types without unintended spillovers | Segment interventions by incentive type; test independence; monitor cross-type interactions | Track feedback and adaptation; use systems lens for coupling dynamics |

### Preconditions Checklist

| Precondition | Required | Evidence / artefact | Owner | Verification | Workaround if unmet |
|---|---|---|---|---|---|
| Clear definition of actors, roles, and decision points | Y | Role map; process flow; stakeholder inventory | Sponsor | Confirm scope and actors with stakeholders | Use inferred actor list from secondary sources; mark gaps and iterate |
| Availability of KPIs, metrics, dashboards, performance measurement regime | Y | Performance frameworks; dashboards; audit reports; incentive schedules | Records owner | Baseline metric inventory before detailed mapping | Build metrics hypotheses table; flag gaps; request access to baseline |
| Access to compensation, contract, incentive policy documentation | Y | Pay scales; bonus structures; contracts; performance agreements; job descriptions | HR / procurement | Inventory formal incentives; identify undocumented ones | Use interviews and stakeholder accounts; mark confidentiality constraints |
| Multi-level evidence collection (frontline, supervisory, executive perspectives) | Y | Availability of interviews or historical records across levels | Sponsor | Conduct ≥3 distinct level interviews or secure records | Segment analysis by accessible levels; triangulate with artefacts; note gaps |
| Capacity to iterate incentive analysis based on emerging contradictions | Y | Project timeline and team capability for re-analysis | Project lead | Allocate time for hypothesis testing and revision | Plan single-cycle analysis with sensitivity ranges; highlight uncertainties |

## 1.3 Definitions, Scope, and Non-Goals

**In scope:**
- Six incentive meta-categories and thirty core incentive types
- Five cross-cutting dimensions for profiling incentives
- Common incentive dynamics (gaming, crowding effects, adverse selection, drift, path dependence)
- Five high-leverage interface types where incentive failure concentrates
- Hiddens source analysis + tiered Hiddens cross-check (Tier 1, Tier 2, Tier 3 escalation)
- Integration with Diagnosis, Causation, Interventions, and Governance frameworks

**Out of scope** (handled by adjacent frameworks):
- Full causal mechanism modelling (Causation; Systems)
- Full accountability allocation (Responsibility; Governance)
- Full uncertainty quantification (Uncertainties)
- Full intervention catalogue (Interventions)

## 1.4 Position in the Series

**Upstream dependencies:** Realities; Systems; Boundaries; Time; Scale; Culture & Norms; Power; Evidence; Agents; Personas; Values

**This framework's role (Midstream):** Incentive identification, profiling, dynamics and interface mapping; alignment diagnosis; gaming risk assessment

**Downstream consumers:** Decisions; Interventions; Governance; Responsibility; Risk; Learning & Adaptation; Diagnosis (root causes of persistent behaviour)

**Group assignment:** G3 — Agency & behavioural drivers (Primary); G2 — Structure, dependencies & mechanism (Secondary)

## 1.5 Crosswalk Summary

| Cluster | Representative frameworks | Gap this framework fills |
|---|---|---|
| Power, incentives, behaviour | Power; Culture & Norms; Legitimacy | Systematic incentive scan (structural→temporal) plus dynamics and interface patterns to prevent naive 'change the metric' interventions |
| Governance & accountability | Governance; Responsibility; Decisions; Interventions | Incentive impact analysis for governance designs; identification of misalignment, gaming risk, and perverse incentives before rollout |
| Systems & context | Systems; Scale; Time; Boundaries; Realities | Where incentive gradients arise from structure (interfaces, scarcity, optionality), and how incentives change across scales and time |
| Epistemics & failure control | Evidence; Failures; Hiddens; Diagnosis; Uncertainties | Detection of incentive-related hiddens (esp. hidden/denied incentives), mandatory Hiddens cross-check for distortion, secrecy, and positional invisibility |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Incentives_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Incentives when… | Use neighbour instead when… |
|---|---|---|
| Power | Diagnosing who controls incentive design, changes reward structures, or redistributes behavioural outcomes; analysing power to set/modify incentive rules themselves. | Analysing abstract power distribution, bargaining power, and dependency relationships independent of incentive structure; studying control over resources, decisions, or agency. |
| Culture & Norms | Identifying normative incentives, identity-based motivation, and how shared values drive behaviour; analysing where incentives reinforce or violate group norms. | Analysing group norms, taboos, and value systems independent of specific incentive consequences; studying cultural narratives and shared meanings; examining legitimacy frameworks. |
| Agents | Determining which agents face which incentives; mapping heterogeneous responses to the same incentive structure across roles. | Analysing agent capabilities, constraints, and strategy-selection without reference to incentive structures; studying rational choice or bounded rationality in abstraction. |
| Governance | Identifying incentive design flaws, perverse outcomes, and need for control/monitoring; designing governance interventions to align incentives. | Analysing formal authority structures, decision rights, and accountability hierarchies independent of reward/penalty levers; studying compliance frameworks and institutional rules. |
| Decisions | Recognising incentive constraints on what options appear available or attractive to decision-makers; showing why decisions persist despite stated policy. | Analysing choice sets, framing effects, and deliberation processes independent of background incentive structures; studying information access and sensemaking. |

### 1.6.3 Routing triggers
- Behaviour persists despite policy, training, or stated expectations
- Performance metrics show improvement but outcomes remain poor (suspected gaming)
- Accountability is unclear and blame-shifting is prevalent
- Incentives are mediated by platforms, algorithms, or automated systems
- System is drifting over time toward unintended outcomes despite stable formal rules
- Stakeholders attribute failures to insufficient willpower rather than structural incentive misalignment
- Perverse incentives are suspected but denied or invisible in formal documentation
- Principal–agent failures are recurring (delegation, outsourcing, contractor relationships)
- Gaming, workarounds, or shadow metrics coexist with official KPIs
- Multi-level or cross-silo coordination is breaking down

---


# 2. Meta-Categories of Incentives

## 2.1 Meta-Categories Table

| Category | Meta-Category Name | Core Question | Characteristic Patterns | Illustrative Examples |
|---------:|---|---|---|---|
| I | Structural & Role-Based | How do formal roles, rules, metrics, and governance structures make some behaviours safer or more rewarding? | Compliance with job descriptions, optimisation to KPIs, avoidance of formal blame, "playing the system" rather than serving its stated purpose | Organisational hierarchies, job descriptions, performance frameworks, escalation paths, contractual responsibility allocation, governance committees |
| II | Material & Transactional | What direct financial, resource, and transactional consequences pull or push behaviour? | Chasing bonuses, gaming price signals, avoiding direct losses, rent-seeking, shifting costs to others | Salary, bonuses, commissions, penalties, clawbacks, pricing structures, cost allocations, procurement rules, reimbursement policies |
| III | Informational & Cognitive | How do information flows, uncertainty, and cognitive effort shape what feels attractive, risky, or feasible? | Responding only to salient metrics, ignoring low-visibility risks, following defaults, avoiding cognitively demanding options | Dashboards, reports, alerts, risk registers, documentation quality, search costs, defaults in systems, information asymmetries |
| IV | Social & Relational | How do status, belonging, reciprocity, and relationship maintenance motivate or constrain behaviour? | Conformity to group norms, reputation management, favour trading, reluctance to challenge powerful actors, preference for harmony | Team cultures, professional communities, alliances, informal networks, sponsorship and mentoring, "old boys' clubs", stakeholder coalitions |
| V | Normative & Identity | How do values, ethics, narratives, and self-understandings as certain kinds of people motivate or inhibit action? | Acting in line with principles, pride in professional standards, taboo avoidance, whistleblowing, heroic self-narratives | Professional codes of conduct, organisational mission statements, personal ethical commitments, identity-based roles (e.g. "guardian of safety"), taboos |
| VI | Temporal & Optionality | How do time, uncertainty about the future, and the preservation or loss of options incentivise behaviours? | Short-termism, procrastination, risk-shifting to the future, "kicking the can down the road", hoarding options | Deadlines, vesting schedules, tenure systems, probation periods, long-term contracts, exit options, cancellation clauses, irreversible investments |

---

# 3. Core Incentive Types Taxonomy

## 3.1 Structural & Role-Based Incentive Types (1–5)

| # | Type | Description | Indicative Assessment | Typical Interface |
|---|---|---|---|---|
| 1 | Role-Responsibility Incentive | Motivation to prioritise actions aligning with formal role definitions and job descriptions, in order to appear "responsible" and avoid criticism for acting outside remit | Visibility: High; Salience: High; Strength: Variable | Contractual & Principal–Agent |
| 2 | KPI / Metric Optimisation Incentive | Motivation to maximise what is measured (KPIs, SLAs, audit criteria), even when this diverges from underlying system goals (Goodhart effects and metric gaming) | Visibility: High; Salience: Very High; Strength: Strong | Regulatory & Compliance; Platform & Algorithmic |
| 3 | Turf & Authority Preservation Incentive | Motivation to protect budgets, span-of-control, and decision rights, resisting changes that might reduce status or perceived importance of role | Visibility: Medium; Salience: High; Strength: Strong | Contractual & Principal–Agent; Relational & Reputation-Based |
| 4 | Compliance & Liability Avoidance Incentive | Motivation to follow rules, processes, and documentation requirements primarily to avoid personal or organisational blame, sanctions, or litigation, rather than to improve outcomes | Visibility: High; Salience: High; Strength: Very Strong | Regulatory & Compliance; Mission & Narrative |
| 5 | Procedural Convenience Incentive | Motivation to choose actions that minimise friction within formal processes (sign-offs, approvals, documentation), even when a more burdensome path would create better outcomes | Visibility: Low; Salience: Medium; Strength: Medium | Contractual & Principal–Agent; Platform & Algorithmic |

## 3.2 Material & Transactional Incentive Types (6–10)

| # | Type | Description | Indicative Assessment | Typical Interface |
|---|---|---|---|---|
| 6 | Direct Financial Reward Incentive | Motivation driven by expected financial gains such as salary, bonuses, commissions, and profit shares, typically extrinsic and explicit | Visibility: Very High; Salience: Very High; Strength: Strong | Contractual & Principal–Agent; Mission & Narrative |
| 7 | Loss & Penalty Avoidance Incentive | Motivation to avoid direct financial losses, penalties, fines, clawbacks, or negative performance-related pay adjustments | Visibility: High; Salience: Very High; Strength: Very Strong | Regulatory & Compliance; Contractual & Principal–Agent |
| 8 | Resource Access Incentive | Motivation to act in ways that maintain or expand access to budgets, headcount, scarce assets, or privileged opportunities | Visibility: Medium; Salience: High; Strength: Strong | Contractual & Principal–Agent; Platform & Algorithmic |
| 9 | Rent-Seeking & Side-Payment Incentive | Motivation to exploit pricing, regulatory, or contractual gaps to capture surplus value (rents), often without proportional value creation | Visibility: Low; Salience: High (if exploitable); Strength: Strong (if detected) | Regulatory & Compliance; Platform & Algorithmic |
| 10 | Risk Transfer & Externalisation Incentive | Motivation to take actions that shift downside risk or cost onto others (customers, counterparties, the public sector), a core mechanism of moral hazard | Visibility: Low; Salience: Medium; Strength: Strong | Contractual & Principal–Agent; Regulatory & Compliance |

## 3.3 Informational & Cognitive Incentive Types (11–15)

| # | Type | Description | Indicative Assessment | Typical Interface |
|---|---|---|---|---|
| 11 | Information Advantage Incentive | Motivation to acquire or retain privileged information that improves bargaining position, decision quality, or personal security relative to others | Visibility: Low; Salience: High; Strength: Strong | Contractual & Principal–Agent; Relational & Reputation-Based |
| 12 | Attention & Salience Incentive | Motivation to respond primarily to issues, metrics, or signals that are made salient (e.g. via dashboards or escalations), while neglecting low-visibility risks or stakeholders | Visibility: Low; Salience: Very High; Strength: Strong | Platform & Algorithmic; Regulatory & Compliance |
| 13 | Effort-Minimisation Incentive | Motivation to choose cognitively simpler options, heuristics, or defaults to avoid the mental effort, complexity, or ambiguity of deeper analysis | Visibility: Low; Salience: High; Strength: Medium–Strong | Platform & Algorithmic; Mission & Narrative |
| 14 | Uncertainty Avoidance Incentive | Motivation to prefer options that reduce felt uncertainty (even if objectively inferior), such as over-insuring, over-specifying, or over-standardising | Visibility: Medium; Salience: Medium; Strength: Medium | Regulatory & Compliance; Contractual & Principal–Agent |
| 15 | Narrative Coherence Incentive | Motivation to favour explanations and actions that preserve a coherent story about self, organisation, or environment, even when evidence points to uncomfortable alternatives | Visibility: Low; Salience: High; Strength: Strong | Mission & Narrative; Relational & Reputation-Based |

## 3.4 Social & Relational Incentive Types (16–20)

| # | Type | Description | Indicative Assessment | Typical Interface |
|---|---|---|---|---|
| 16 | Status & Recognition Incentive | Motivation to gain or maintain prestige, respect, or visibility, including awards, promotions, and being seen as a "star performer" | Visibility: High; Salience: High; Strength: Strong | Relational & Reputation-Based; Mission & Narrative |
| 17 | Belonging & Inclusion Incentive | Motivation to act in ways that secure acceptance within valued groups and avoid exclusion, isolation, or ostracism | Visibility: Medium; Salience: High; Strength: Very Strong | Relational & Reputation-Based; Mission & Narrative |
| 18 | Reciprocity & Favour-Banking Incentive | Motivation to grant favours, leniency, or support now in expectation of future reciprocation, creating informal obligation networks | Visibility: Low; Salience: High; Strength: Medium–Strong | Relational & Reputation-Based; Contractual & Principal–Agent |
| 19 | Conflict Avoidance & Harmony Incentive | Motivation to avoid open conflict, disagreement, or escalation, even when challenge or dissent would be substantively beneficial | Visibility: Medium; Salience: High; Strength: Very Strong | Relational & Reputation-Based; Mission & Narrative |
| 20 | Network Position & Access Incentive | Motivation to cultivate connections, gatekeeping roles, or brokerage positions that provide privileged access to people, information, and opportunities | Visibility: Low; Salience: High; Strength: Strong | Relational & Reputation-Based; Contractual & Principal–Agent |

## 3.5 Normative & Identity Incentive Types (21–25)

| # | Type | Description | Indicative Assessment | Typical Interface |
|---|---|---|---|---|
| 21 | Integrity & Principle-Consistency Incentive | Motivation to act in accordance with personal or professional principles, even at material cost, in order to preserve self-respect and coherence with one's values | Visibility: Medium; Salience: High; Strength: Strong–Very Strong | Mission & Narrative; Contractual & Principal–Agent |
| 22 | Professional Role-Identity Incentive | Motivation to behave in ways that fit the identity of being a "good engineer", "responsible clinician", "trusted advisor", or analogous professional persona | Visibility: High; Salience: High; Strength: Strong | Mission & Narrative; Relational & Reputation-Based |
| 23 | Moral Licensing & Compensatory Incentive | Motivation to allow questionable behaviour in one domain because of perceived moral "credit" earned in another (e.g. "we do so much good that this corner-cutting is acceptable") | Visibility: Low; Salience: Medium–High; Strength: Medium | Mission & Narrative; Relational & Reputation-Based |
| 24 | Taboo & Boundary-Respect Incentive | Motivation to avoid crossing hard normative boundaries or taboos (e.g. safety breaches, corruption), regardless of short-term gain | Visibility: High; Salience: Very High; Strength: Very Strong | Mission & Narrative; Regulatory & Compliance |
| 25 | Purpose & Meaning Incentive | Motivation to choose actions that reinforce a sense of meaningful contribution or alignment with a larger mission, beyond financial or social rewards | Visibility: Medium; Salience: High; Strength: Strong | Mission & Narrative; Contractual & Principal–Agent |

## 3.6 Temporal & Optionality Incentive Types (26–30)

| # | Type | Description | Indicative Assessment | Typical Interface |
|---|---|---|---|---|
| 26 | Short-Term Outcome Incentive | Motivation focused on near-term outcomes (quarterly results, immediate wins, crisis containment), often at the expense of long-term resilience or optimisation | Visibility: High; Salience: Very High; Strength: Very Strong | Contractual & Principal–Agent; Regulatory & Compliance |
| 27 | Long-Term Accumulation Incentive | Motivation to act for long-run benefit (compounding returns, reputation over time, capability building), even when short-term costs are high | Visibility: Medium; Salience: Medium–High; Strength: Strong | Contractual & Principal–Agent; Mission & Narrative |
| 28 | Optionality Preservation Incentive | Motivation to keep options open, delay irreversible commitments, and maintain flexibility under uncertainty | Visibility: Low; Salience: High; Strength: Strong | Contractual & Principal–Agent; Platform & Algorithmic |
| 29 | Intertemporal Shift Incentive | Motivation to pull benefits forward and push costs, risks, or liabilities into the future (for successors, other departments, or future selves) | Visibility: Low; Salience: High; Strength: Strong | Contractual & Principal–Agent; Regulatory & Compliance |
| 30 | Irreversibility & Sunk-Cost Incentive | Motivation to continue with or escalate a chosen path because of sunk investments, perceived irreversibility, or fear of loss of face if reversed | Visibility: Low; Salience: High; Strength: Medium–Strong | Contractual & Principal–Agent; Mission & Narrative |

---

# 4. Cross-Cutting Dimensions

## 4.1 Five Dimensions of Any Incentive

| Dimension | Description | Indicative spectrum | Assessment method | Analytic use |
|---|---|---|---|---|
| **Source of Motivation** | Whether motivation arises internally (alignment with values, identity, interest) or is driven by external pressure (reward, penalty, obligation) | Intrinsic ← → Extrinsic | Stakeholder interview; behaviour under reward removal; revealed preference testing | Determines robustness: intrinsic survives policy change; extrinsic vulnerable to removal or substitution |
| **Valence & Mode** | Whether the incentive pulls behaviour toward a goal (positive) or away from an avoided state (negative); and whether simple (binary) or complex (graduated) | Positive, simple ← → Negative, complex | KPI audit; performance contract review; behaviour mapping | Negative incentives are often stronger but more fragile; complexity improves fidelity but increases opacity |
| **Alignment** | Degree to which the incentive supports desired outcomes or undermines them | Aligned ← → Perverse | Outcome audit; behaviour-outcome correlation; unintended consequence scan | High misalignment is a flag for gaming, distortion, and need for urgency in remediation |
| **Scope & Level** | Whether the incentive applies at individual, team, organisational, or ecosystem level; and whether it spans boundaries or is siloed | Dyadic ← → Ecosystem-wide | Governance mapping; incentive structure audit; integration scan | Mis-scoped incentives (e.g. individual bonuses with team outputs) are notorious generators of gaming and coordination failure |
| **Transparency & Awareness** | Degree to which the incentive is explicitly stated, understood, and acknowledged by agents and principals | Explicit & conscious ← → Hidden & denied | Stakeholder interviews; incentive register comparison to stated policy; behaviour-incentive gap analysis | Opaque or denied incentives escape management and become sources of hidden distortion, gaming, and principal–agent failure |

---

# 5. Incentive Dynamics Patterns

## 5.1 Twelve Dynamic Patterns

| # | Pattern | Signature mechanism | Why it matters | Typical mitigation |
|---|---|---|---|---|
| 1 | Crowding Out | External incentive undermines intrinsic motivation; agents shift from "I want to do this" to "I only do this if paid" | Erodes ethical commitment and discretionary effort; increases control costs and rigidity | Re-balance incentive portfolio; maintain intrinsic framing; avoid pure transactional framing of normative work |
| 2 | Feedback & Habit Formation | Repeated reward creates habit and expectation; incentive effects compound or diminish with repetition | Can lock in behaviour (good) but also brittle habits (bad) if reward is removed or environment changes | Vary timing and mode of reinforcement; couple with capability building; monitor for brittleness |
| 3 | Threshold & Tipping Effects | Incentive has no effect until a threshold is crossed, then behaviour shifts sharply; or small incentive change tips system into new state | Leads to sudden, unexpected shifts in behaviour; risk of cascade failure if threshold is breached | Map thresholds explicitly; design incentives to avoid critical thresholds; build monitoring for early warning |
| 4 | Drift & Goal Displacement | Incentive structure remains while underlying goal changes; agents continue optimising to obsolete target | Performance looks good on old metrics but outcomes fail; creates false confidence and waste | Periodic revalidation of incentive-goal alignment; couple metrics to outcome proxies; retire obsolete KPIs on schedule |
| 5 | Path Dependence & Lock-In | Early choices about incentive structure constrain later options; costly to change even when misaligned | Prevents adaptation and locks in perverse incentives; change becomes politically difficult and expensive | Design reversibility into incentive contracts; sunset clauses and explicit re-authorization gates; monitor lock-in risk |
| 6 | Incentive Cascade | Incentive change at one level triggers unintended changes at another level (e.g. CEO bonus design affects frontline gaming) | Can amplify or invert intended effects across organisational levels; creates coupling and hidden risks | Map incentive interfaces across levels; stress-test cascade scenarios; separate incentives where appropriate |
| 7 | Regime Shift | Gradual changes in context or incentive structure reach a tipping point and system behaviour shifts into new regime | Shifts often surprise decision-makers; recovery from some regimes is difficult or impossible | Monitor leading indicators; run scenario analysis; maintain option value to reverse course early |
| 8 | Adaptation & Workaround Formation | Agents learn how to achieve incentive payoffs while subverting or circumventing underlying objectives | Creates "shadow economy" of unmeasured work and concealed behaviour; true outcomes diverge from reported | Look for workaround economies and shadow KPIs; incorporate qualitative signals; scan for ingenious non-compliance |
| 9 | Equity Perception Lag | Agents perceive incentive change as unfair even if objectively sensible; moral outrage persists even after re-balancing | Can trigger exit, sabotage, or norm violation despite rational appeal of new incentive; erodes trust | Invest in fairness framing and stakeholder dialogue; grandfather legacy arrangements where possible; be transparent about trade-offs |
| 10 | Reference Point Instability | Agents' perception of what is a "gain" or "loss" shifts with reference point; same incentive feels different at different status levels | Identical incentive produces opposite behavioural response depending on starting point; non-linear effects | Profile reference points for different cohorts; design incentives relative to salient reference points, not absolute levels |
| 11 | Attention Capture | High-salience incentive (e.g. bonus) captures attention and distorts priority-setting; low-visibility risks and values go neglected | Can produce system failure in low-salience domains even while high-salience domain performs well | Balance incentive salience; create counter-incentives or monitoring for low-visibility risks; pair metrics with narrative |
| 12 | Substitution & Migration | Agent substitutes one incentive source for another (e.g. moves from one pay scheme to another); or migrates effort to domain with higher incentive yield | Can render intended incentive ineffective if substitution is available; can drain effort from important but low-incentive domains | Scan for substitute incentive sources; design interfaces to couple high-yield and necessary-but-low-yield domains |

---

# 6. Interface Types

## 6.1 Five Interface Types Where Incentive Failure Concentrates

| Type | Description | Key questions | Examples | Typical failure modes |
|---|---|---|---|---|
| **Contractual & Principal–Agent** | Formal contractual relationships where one party (principal) relies on another (agent) to act on their behalf, but incentives and information diverge | Is alignment of payoffs, information, and risk exposure sufficient? Are side-deals or gaming opportunities available? Is oversight adequate? | Vendor contracts, employment agreements, agency relationships, outsourced services, M&A earnouts | Moral hazard (agent insulated from downside), adverse selection (hidden types attracted), hidden actions (gaming/side-deals) |
| **Regulatory & Compliance** | Interfaces where regulation or compliance regime defines what is required; agents optimise to regulation rather than underlying intent | Does regulation capture intent? Are perverse incentives to comply rather than perform embedded in the rule? Are unintended loopholes available? | Health & safety, environmental, anti-corruption, financial crime, data protection, quality assurance | Compliance theatre (following letter not spirit), regulatory arbitrage (exploiting gaps), burden-shifting to externals |
| **Platform & Algorithmic** | Interfaces mediated by platforms or algorithms that shape incentives through design: ranking algorithms, recommendation engines, automated enforcement, feedback loops | Does the algorithm align incentive gradients with system goals? Are feedback loops stable or amplifying? Are gaming opportunities detectable and prevented? | Social media algorithms, pricing engines, performance management systems, dispatch/allocation algorithms | Emergent gaming (many small acts exploit algorithm), feedback amplification (algorithm reinforces distortion), opacity (designers can't predict effects) |
| **Relational & Reputation-Based** | Interfaces governed by informal reputation, status, and relational obligation; incentives are socially mediated rather than contractual | How are status and belonging maintained? What happens if formal and informal incentives diverge? Who controls the informal "rules"? | Team cultures, professional networks, sponsorship relationships, informal hierarchies, coalition politics | Positional invisibility (different experience by role), suppressed dissent (informal sanctions for truth-telling), insider–outsider dynamics |
| **Mission & Narrative** | Interfaces where incentives are framed through organisational mission, professional purpose, ethical commitment, or shared narrative; identity and meaning are primary drivers | Is the mission compelling and coherent? Do incentive structures support mission alignment or contradict it? Who can be heard challenging the narrative? | Non-profit missions, professional codes, organisational values statements, civic purpose, whistleblowing ethics | Mission–incentive misalignment (pursue mission despite poor incentives or abandoned mission for incentive payoff), moral licensing (hide behind mission to excuse corner-cutting) |

---

# 7. Incentive Integration with Adjacent Frameworks

## 7.1 Cross-Framework Usage (Summary)

**All 36 canonical frameworks** are listed below with their relationship to Incentives:

| # | Framework | Primary group | How incentives interact |
|---|---|---|---|
| 1 | Realities & Assumptions | G1 | What is materially true constrains incentive possibility; what actors believe about reality shapes perceived incentive payoffs |
| 2 | Systems & Process Interdependencies | G2 | Incentive structures embed coupling; local incentive optimisation creates system-level harm; feedback loops amplify gaming |
| 3 | Relations & Connectivity | G2 | How incentives flow across network; who benefits from and who pays for incentive outcomes; network position determines incentive experience |
| 4 | Processes & Causal Pathways | G2 | How incentives drive process variation; where incentive changes in one process cascade to others |
| 5 | Resources & Capability | G2 | Incentive structures determine resource allocation and capability investment; poor incentives starve capability |
| 6 | Causation & Attribution | G2 | False causation claims can mask true incentive drivers; incentive misalignment is a causal mechanism |
| 7 | Situations & Context Classification | G1 | Different situation types carry different incentive structures; crisis vs routine have different operative incentives |
| 8 | Boundaries & Scope | G1 | Boundary definition determines who bears incentive costs/benefits; boundary crossing reveals incentive conflicts |
| 9 | Dimensions & Scales | G1 | Incentives change across scales; individual incentive conflicts with team or organisational level |
| 10 | Time & Sequencing | G1 | Temporal incentive structures (deadlines, vesting, irreversibility) shape path dependence and urgency |
| 11 | Agents & Actor Types | G3 | Who agents are constrains which incentive types are operative; different agent types respond differently |
| 12 | Personas & Motivational Profiles | G3 | Persona shapes how same incentive is experienced; incentive effectiveness depends on persona fit |
| 13 | Power & Influence Bases | G3 | Who can design and change incentives; power asymmetry suppresses honest revelation of true incentives |
| 14 | Responsibility & Accountability | G3 | Incentive structure determines accountability assignment; misalignment creates blame-shifting |
| 15 | Culture & Norms | G4 | Cultural norms shape which incentives are socially acceptable; norm violation is its own sanction |
| 16 | Perspectives & Interpretations | G4 | Different perspectives interpret same incentive differently; power shapes which interpretation dominates |
| 17 | Narratives & Meaning-Making | G4 | Narrative framing makes certain incentives visible and others invisible; incentive reframing changes narrative |
| 18 | Communications & Information Flows | G4 | How incentives are communicated affects salience and understanding; information asymmetries distort incentive effects |
| 19 | Legitimacy & Social Standing | G4 | Legitimacy impacts which incentives are accepted; illegitimate incentives trigger resistance even if powerful |
| 20 | Evidence & Claim Quality | G5 | Incentive claims require evidence; F/I/A/U tagging prevents overconfidence in inferred incentives |
| 21 | Failures & Failure Patterns | G5 | Incentive misalignment is a failure pattern; gaming and moral hazard are failure-adjacent |
| 22 | Uncertainties & Unknown Unknowns | G5 | Hidden incentives are a primary source of unknown unknowns; incentive analysis reduces residual uncertainty |
| 23 | Hiddens & Visibility Gaps | G5 | Incentive structures are a major source of hiddens (distortion, mirage, secret, positional invisibility) |
| 24 | Diagnosis & Root-Cause Analysis | G5 | Perverse incentives are often the root cause; diagnosis without incentive analysis is incomplete |
| 25 | Decisions & Decision-Making | G6 | How incentive structures shape who decides what; incentive conflicts block good decisions |
| 26 | Interventions & Change Levers | G6 | Incentive redesign is a primary intervention lever; understanding incentives is key to predicting intervention success |
| 27 | Governance & Institutional Design | G6 | Governance structures define incentive landscape; good governance integrates incentive management |
| 28 | Risk & Resilience | G6 | Incentive structures shape risk-taking and resilience-building; misaligned incentives generate tail risk |
| 29 | Learning & Adaptive Capacity | G6 | Incentives determine who learns and what knowledge is shared; poor incentives suppress learning and adaptation |
| 30 | Values & Mission | G5 | Values and mission shape normative incentives; misalignment between values and structural incentives is a major distortion source |
| 31 | Beliefs & Belief Distortion | G4 | Incentives shape what beliefs are entrenched and defended; belief-protective incentives resist evidence |
| 32 | Competencies & Capability | G2 | Incentive structures shape competency development; poor incentives reward theatre over substance |
| 33 | Metrics & Measurement | G5 | Incentive coupling to metrics is the core Goodhart mechanism; metrics are incentive targets, not neutral measures |
| 34 | Knowledge & Knowledge Management | G2 | Incentive structures determine knowledge sharing vs hoarding; knowledge incentives are often invisible |
| 35 | (Framework TBD) | — | — |
| 36 | (Framework TBD) | — | — |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Incentive Hiddens Source Analysis

| # | Generator Name | Pattern | Remedy |
|---|---|---|---|
| 1 | Principal–Agent Misalignment | Assuming agents' incentives are automatically aligned with principals' goals, ignoring divergent payoffs, risk exposures, and time horizons | Explicitly map payoffs and risks for each party; redesign contracts, oversight, and information flows to align interests |
| 2 | Moral Hazard & Risk Externalisation | Underestimating how insulation from downside risk encourages excessive risk-taking or neglect of long-term harms | Trace who actually bears which risks and costs; introduce skin-in-the-game, clawbacks, or shared-risk mechanisms |
| 3 | Perverse Metric Optimisation | Focusing on hitting numerical targets while ignoring the underlying purpose those metrics were meant to proxy (Goodhart's Law) | Revisit metric design; combine quantitative and qualitative indicators; regularly test for unintended behaviours |
| 4 | Single-Dimension Incentive Focus | Analysing only financial incentives and neglecting social, identity, informational, or temporal incentives that dominate real behaviour | Scan across all six incentive meta-categories; explicitly document social, identity, and temporal drivers alongside financial ones |
| 5 | Static Incentive Assumption | Treating incentives as fixed rather than dynamic, missing how they evolve with learning, regime changes, and shifting expectations | Incorporate temporal analysis; review incentive structures periodically; examine scenario shifts and legacy effects on behaviour |

## 8.2 Tier 1 Hiddens Six-Category Scan (mandatory)

Run this scan for every incentive analysis. Assume hidden incentives exist.

| Hiddens meta-category | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|---|
| **I Perceptual** | Incentives often operate as background conditions; analysts may not notice the true reward/punishment structure shaping behaviour | Surprise at gaming; repeated non-compliance; dismissal of frontline rationality; over-reliance on stated motivations | Behaviour-first mapping; compare stated vs revealed preferences; test "what must be true for this to be rational?" |
| **II Systemic** | Incentives are embedded in institutional structure, KPIs, and accountability mechanics that systematically bias behaviour | Goodhart effects; risk transfer; blame avoidance; local optimisation; compliance theatre | Incentive–KPI audit; principal–agent analysis; governance review; map side-effects and externalities |
| **III Informational** | Information about incentives and performance is filtered, distorted, or withheld; official reporting diverges from reality | Inconsistent stories; missing provenance; selectively reported metrics; silent exceptions; late discoveries | Provenance checks; triangulate data sources; audit trails; whistleblowing channels; anomaly detection |
| **IV Temporal** | Incentives drift and accumulate path dependence; what was once sensible becomes perverse over time | Legacy KPI lock-in; policy lag; reward cycles that outrun learning; persistent workarounds | Timeline of incentive changes; lag analysis; drift indicators; periodic incentive revalidation gates |
| **V Relational** | Status, belonging, and power determine which incentives can be voiced; some incentives are socially unsafe to admit | Denial of status games; suppressed dissent; "everyone knows" dynamics; politicised performance metrics | Positional sampling; facilitated interviews; protected dissent; power mapping; stakeholder coalition analysis |
| **VI Ontological** | The organisation lacks categories to represent incentives beyond money/compliance; moral and identity incentives become invisible | Persistent misunderstanding; "motivation" treated as simple; misclassification of value conflicts as performance issues | Expand incentive vocabulary using this taxonomy; treat culture/identity incentives as first-class; test alternative framings |

## 8.3 Tier 2 Hiddens Crosswalk (default mapping layer)

Run Tier 2 when Tier 1 identifies elevated risk. Map each hidden type to detection interfaces and remediation levers.

| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability (H/M/L) | Agency (Structural/Deliberate/Intrinsic) | Consequence (H/M/L) | Detection interface(s) | Remediation interface(s) | Interaction notes |
|---|---|---|---|---|---|---|---|---|
| 6 Distortion | H | Incentive signals and reporting are systematically biased by rewards/punishments; what is sayable and measurable diverges from what is true | Medium | Structural | High | Platform & Algorithmic; Regulatory & Compliance; Contractual & Principal–Agent | Regulatory & Compliance; Contractual & Principal–Agent; Mission & Narrative | Often co-occurs with KPI optimisation and compliance theatre; treat metrics as incentives, not neutral measurements |
| 7 Mirage | H | Apparent alignment and performance is an artefact of incentives (gaming, performative compliance), producing false confidence and 'green dashboards' | Low–Medium | Mixed | High | Regulatory & Compliance; Platform & Algorithmic | Regulatory & Compliance; Mission & Narrative | Stress-test with independent evidence and outcome-based measures; look for divergence between narrative and lived reality |
| 8 Framing | H | The problem definition selects which incentives 'count' (often financial/compliance), excluding identity, status, and option-value incentives | Medium | Mixed | High | Mission & Narrative; Relational & Reputation-Based | Mission & Narrative; Contractual & Principal–Agent | Reframe using the six meta-categories; explicitly document excluded incentive classes and their risks |
| 11 Secret | H | True incentives are concealed (e.g., unofficial targets, political pressures, side-deals), so behaviour appears irrational under the official incentive model | Low–Medium | Deliberate | High | Contractual & Principal–Agent; Regulatory & Compliance; Relational & Reputation-Based | Contractual & Principal–Agent; Regulatory & Compliance | Use protected disclosures, audit rights, and provenance requirements; treat unexplained behaviour as a 'secret incentive' candidate |
| 14 Fragmentation | H | Incentives differ across silos and are not integrated; local optimisation produces system-level harm and coordination failure | High | Structural | High | Contractual & Principal–Agent; Platform & Algorithmic; Regulatory & Compliance | Contractual & Principal–Agent; Mission & Narrative | Build an incentive register by role/unit; map conflicts and externalities; align incentives at interfaces, not only within functions |
| 16 Shadow | M–H | Untracked work, informal practices, and 'off-the-books' incentives shape real outcomes but remain outside official measurement and governance | Medium | Structural | Medium–High | Relational & Reputation-Based; Platform & Algorithmic | Mission & Narrative; Regulatory & Compliance | Look for workaround economies and 'shadow KPIs'; incorporate qualitative signals and frontline evidence |
| 17 Ghost | M–H | Legacy incentives and historical arrangements continue to shape behaviour after their original rationale has disappeared | High | Structural | Medium–High | Contractual & Principal–Agent; Regulatory & Compliance | Contractual & Principal–Agent; Mission & Narrative | Run temporal archaeology; retire obsolete KPIs and mandates; revalidate incentive rationales periodically |
| 19 Projection | H | Analysts assume other actors share their motivations (e.g., safety, service, optimisation), misreading rational responses to incentives | Medium | Intrinsic | High | Relational & Reputation-Based; Mission & Narrative | Mission & Narrative; Contractual & Principal–Agent | Use stakeholder interviews and revealed-preference tests; separate stated values from operative incentives |
| 21 Positional | H | Different roles and power positions face different incentives; 'one incentive scheme' is experienced differently across the organisation | Medium | Structural | High | Contractual & Principal–Agent; Relational & Reputation-Based | Contractual & Principal–Agent; Mission & Narrative | Profile incentives by role and exposure; ensure protected dissent where admitting incentives is socially unsafe |
| 23 Emergent Invisibility | M–H | System-level outcomes arise from many local incentives and interactions; no single actor 'intended' the result | Low–Medium | Structural | Medium–High | Platform & Algorithmic; Regulatory & Compliance | Regulatory & Compliance; Mission & Narrative | Use systems mapping and multi-level evidence; avoid single-agent blame; monitor leading indicators for emergent drift |
| 24 Contextual | H | Incentives change meaning and effect across contexts; a policy that works in one setting fails or becomes perverse in another | High | Structural | High | Regulatory & Compliance; Mission & Narrative | Contractual & Principal–Agent; Mission & Narrative | Segment contexts; define boundary conditions; avoid global rollouts without local incentive validation |
| 25 Perspectival | M–H | A single disciplinary lens dominates (e.g., economics-only), excluding social, identity, and legitimacy incentives | Medium | Structural | Medium–High | Mission & Narrative; Relational & Reputation-Based | Mission & Narrative | Require at least one contrasting perspective (e.g., culture/legitimacy) for major incentive design decisions |
| 29 Category Absence | M–H | The organisation lacks vocabulary to represent certain incentives (status, identity, taboo), so they become invisible and unmanaged | Medium | Structural | Medium–High | Mission & Narrative; Relational & Reputation-Based | Mission & Narrative | Adopt this taxonomy and maintain an incentive glossary; treat social and normative incentives as first-class |

## 8.4 Embedded Hiddens Micro-Protocol

1. Run Tier 1 scan across all six Hiddens meta-categories (assume hidden incentives exist).
2. Shortlist Tier 2 hidden types (especially Distortion, Mirage, Framing, Secret, Fragmentation, Positional, Ghost/Shadow) and rate detectability, agency, consequence.
3. Assign at least one detection and one remediation move per high-consequence hidden; anchor actions to the five interface types.
4. Re-run hiddens sources; define monitoring indicators and escalation triggers.

## 8.5 Escalation Rule (Tier 3 – full Hiddens run)

Escalate to a full Hiddens scan + detection/remediation mapping if any apply:
- High consequence (safety, systemic resilience, major regulatory exposure, irreversible harm)
- Strong incentives to conceal true objectives (political, reputational, financial)
- Evidence of widespread KPI gaming or dashboard 'green mirages'
- Significant power asymmetry suppressing honest disclosure
- Complex platforms/algorithms mediating behaviour at scale

---

# 9. Framework Application Protocol (mandatory)

## 9.1 Seven-Step Rapid Protocol

| Step | Name | Action | Typical inputs | Typical outputs | Duration |
|---|---|---|---|---|---|
| 1 | Incentive Mapping | Identify key agents, actions, decision points; map visible rewards, penalties, expectations for each, including informal and identity-based incentives | Actor map, process flow, policy documents | Preliminary incentive inventory (rough, unordered) | 1–2 hours |
| 2 | Meta-Category Scan | Systematically scan across the six meta-categories (structural, material, informational, social, normative, temporal) to surface overlooked incentives | Preliminary inventory, stakeholder interviews | Complete incentive inventory (all six categories populated) | 2–4 hours |
| 3 | Dimensional Characterisation | Characterise salient incentives along key dimensions: intrinsic vs extrinsic, positive vs negative, aligned vs misaligned, scope and level, transparency | Complete inventory, dimension framework, evidence | Priority incentive profiles (five dimensions, 5–10 incentives) | 2–4 hours |
| 4 | Dynamics & Pattern Analysis | Analyse how incentives interact over time, including crowding-out, drift, path dependence, known hiddens (moral hazard, principal–agent) | Incentive profiles, timeline of changes, behaviour data | Dynamics patterns identified; early-warning indicators proposed | 2–4 hours |
| 5 | Interface & Failure-Mode Mapping | Map incentive failure concentration points across five interface types; identify which failures are most likely, highest-consequence | Incentive inventory, interface types framework, governance map | Interface hotspots prioritised; failure mode risk register | 1–3 hours |
| 6 | Hiddens Tier 1 & Tier 2 Scans | Run Tier 1 six-category scan and shortlist Tier 2 hidden types; assign detection and remediation moves | Evidence register, behaviour data, organisational history | Hiddens Register; Tier 2 mapping; escalation recommendation | 3–6 hours |
| 7 | Redesign & Intervention Options | Generate options to adjust, rebalance, or reframe incentives (including non-monetary levers); integrate with diagnostic, causal, and intervention planning | All prior outputs, Interventions framework, Governance framework | Intervention options with predicted behaviour response; governance and control recommendations | 2–6 hours |

## 9.2 Standard Deliverables

**Minimum (1–2 pages):**
- Incentive inventory across all six meta-categories (with evidence notes)
- Profiles for priority incentives using the five dimensions
- Top dynamics/failure modes (gaming, moral hazard, crowding effects)
- Interface hotspots and monitoring plan
- Hiddens shortlist with assigned owners/actions

**Full deliverable pack:**
- Incentive register by role/unit/platform with stated vs revealed mapping
- Governance and measurement redesign notes (what to reward, how to audit, counter-metrics)
- Intervention implications (levers, expected adaptation, unintended consequences)
- Drift and revalidation cadence (time-based control plan)
- Residual unknowns and closure note

## 9.3 Shared Registers

### 9.3.1 Incentive Register by Role/Unit/Platform
| Role / Unit / Platform | Incentive type(s) (from I–VI) | Stated value | Revealed/actual behaviour | Gaming detected? (Y/N) | Owner | Revalidation cadence | Notes |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

### 9.3.2 Uncertainty & Evidence Gaps Register
| Topic / claim | Status (F/I/A/U) | Confidence (H/M/L) | Evidence quality | Next evidence needed | Escalation if unresolved | Notes |
|---|---|---|---|---|---|---|
| | | | | | | |

### 9.3.3 Hiddens & Mitigation Log
| Candidate Hidden (ID + type) | Manifestation / mechanism | Detectability (H/M/L) | Assigned to | Detection method / cadence | Mitigation | Status | Notes |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

---

# 10. Framework Principles (mandatory)

| Principle Name | Description |
|---|---|
| **Incentives Made Explicit** | Treat incentives as a first-class object of analysis rather than an implicit background assumption; write down who has what to gain or lose from which actions. |
| **Multi-Source Motivation** | Assume behaviour is shaped by a blend of material, structural, social, identity, informational, and temporal incentives; avoid reducing motivation to money alone. |
| **Alignment and Ethics Awareness** | Continuously ask whether incentives are aligned with stated goals, values, and societal interests; identify and address perverse incentives and moral hazard. |
| **Dynamic and Context-Sensitive Use** | Analyse how incentive structures evolve over time, across contexts, and across personas; revisit incentive analysis as situations, agents, and realities change. |
| **Integration with Diagnosis & Intervention** | Use incentive analysis alongside diagnosis, causation, power, and resources frameworks to design interventions that are behaviourally and politically viable. |

---

# 11. Glossary & Operating Guide Alignment

## 11.1 Glossary Table

| Term | Definition |
|---|---|
| **Incentive** | A structured pattern of anticipated consequences that makes some actions more attractive, salient, or viable than others for an agent in a given situation. |
| **Incentive Structure** | The overall configuration of incentives (across all meta-categories and dimensions) acting on agents within a system or situation. |
| **Intrinsic Motivation** | Motivation arising from inherent interest, enjoyment, or alignment with personal values and identity, rather than from external rewards or punishments. |
| **Extrinsic Motivation** | Motivation driven primarily by external rewards, sanctions, or structures such as pay, penalties, status, or formal recognition. |
| **Positive Incentive** | An incentive that operates mainly through promised or expected gains (rewards, benefits, opportunities, recognition). |
| **Negative Incentive** | An incentive that operates mainly through threatened or expected losses (penalties, sanctions, exclusion, loss of privilege). |
| **Perverse Incentive** | An incentive that systematically encourages behaviour that undermines stated goals, values, or social welfare, often as an unintended side effect of design. |
| **Principal–Agent Problem** | A situation where a principal relies on an agent to act on their behalf but the agent's incentives, information, or risk exposure diverge from the principal's interests. |
| **Moral Hazard** | A specific form of misaligned incentive in which an actor is partially or fully insulated from the downside of their actions, encouraging excessive risk-taking or negligence. |
| **Adverse Selection** | A situation where an incentive structure attracts participants with hidden characteristics that make undesirable outcomes more likely. |
| **Crowding Out / Crowding In** | The process by which external incentives undermine (crowding out) or reinforce (crowding in) intrinsic motivation and ethical commitment. |
| **Incentive Alignment** | The degree to which incentives support desired behaviours and outcomes in line with system goals and values. |
| **Incentive Drift** | Gradual divergence between an incentive's original purpose and its actual behavioural effects over time. |
| **Optionality** | The value associated with retaining the ability to choose among multiple future actions or states, often incentivising flexibility and reversibility. |
| **Meta-Category of Incentives** | One of six high-level groupings (structural, material, informational, social, normative, temporal) used in this framework to organise and analyse incentive types. |
| **Goodhart's Law** | When a measure becomes a target, it ceases to be a good measure—i.e. when incentives couple to metrics, gaming and metric distortion become inevitable. |
| **Gaming** | The practice of achieving incentive targets by exploiting loopholes, shortcuts, or circumventing underlying objectives rather than pursuing genuine improvement. |

## 11.2 Operating Guide Alignment & Pointer

This framework uses the terminology and governance model defined in the Analytical Series Operating Guide v2.5:
- **Prompt Discipline Rules**: Operating Guide §D.3
- **Run Mode terminology**: Operating Guide §D.10.1 (Rapid Run Mode vs Investigative Run Mode)
- **Framework Execution Depth**: Operating Guide §D.10.1 (Full Depth vs Light Depth)
- **Group assignment logic**: Operating Guide §4.3 (Start-of-Run and Pre-Closure routing)
- **Unified iteration loop**: Operating Guide §5.0 (Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close)
- **Tiered Hiddens scanning**: Operating Guide §D.6.10 (Tier 1 / Tier 2 / Tier 3)
- **Targeted Hiddens Discovery Scans**: Operating Guide §7.5 (thirteen mechanism-specific cross-framework scans)
- **Closure discipline**: Operating Guide §7.4 (five required closure items)

---

# 12. Document Control

## 12.1 Version History

| Version | Date | Changes |
|---|---|---|
| v2.0 | 2026-04-06 | Major rewrite for Operating Guide v2.5 alignment. Added comprehensive Introduction section (four subsections: what, why, what produces, how to use). Updated §1.6 LLM Use & Integration with Tier 2 Hiddens crosswalk, Targeted Scans routing, full Information Requests schema. Expanded all core tables (§2–§7) with enhanced content and narrative. Added complete §8 Hiddens source analysis with Tier 1 six-category scan, Tier 2 default mapping layer covering all 13 identified hidden types, embedded Tier 3 escalation rules. Expanded §9 Framework Application Protocol to seven-step rapid protocol with comprehensive standard deliverables and shared registers. Enhanced §10 Principles section. Added §11 Operating Guide alignment with v2.5 pointers. Added §12 Document Control with version history. Added Appendix with canonical 30-type consolidated list and mapping worksheet. Full document 800–1100 lines, complete with no placeholders. Cross-references to all 36 canonical frameworks added in §7.1. (Revised: Anthropic Claude Opus 4.6) |
| v1.2 | 2026-03-28 | Remediation: Added §3.7 guidance on domain subtypes, registers, measurement, temporal archaeology. Expanded §4.1 Cross-Cutting Dimensions to five substantive dimensions with assessment methods. Added §5.1 Dynamic Patterns Table (12 patterns). Expanded §6.1 Interface Types (five types) with detailed failure modes. All content substantive and incentive-specific. (Revised: Anthropic Claude Opus 4.6) |

---

# Appendix A — Canonical 30-Type Consolidated List

| # | Meta-category | Incentive type | Description | Source |
|---|---|---|---|---|
| 1 | Structural & Role-Based | Role-Responsibility Incentive | Motivation to prioritise actions that align with formal role definitions and job descriptions, in order to appear "responsible" and avoid criticism for acting outside remit. | Meta-category I, type 1 |
| 2 | Structural & Role-Based | KPI / Metric Optimisation Incentive | Motivation to maximise what is measured (KPIs, SLAs, audit criteria), even when this diverges from underlying system goals (Goodhart effects and metric gaming). | Meta-category I, type 2 |
| 3 | Structural & Role-Based | Turf & Authority Preservation Incentive | Motivation to protect budgets, span-of-control, and decision rights, resisting changes that might reduce status or perceived importance of role. | Meta-category I, type 3 |
| 4 | Structural & Role-Based | Compliance & Liability Avoidance Incentive | Motivation to follow rules, processes, and documentation requirements primarily to avoid personal or organisational blame, sanctions, or litigation, rather than to improve outcomes. | Meta-category I, type 4 |
| 5 | Structural & Role-Based | Procedural Convenience Incentive | Motivation to choose actions that minimise friction within formal processes (sign-offs, approvals, documentation), even when a more burdensome path would create better outcomes. | Meta-category I, type 5 |
| 6 | Material & Transactional | Direct Financial Reward Incentive | Motivation driven by expected financial gains such as salary, bonuses, commissions, and profit shares, typically extrinsic and explicit. | Meta-category II, type 1 |
| 7 | Material & Transactional | Loss & Penalty Avoidance Incentive | Motivation to avoid direct financial losses, penalties, fines, clawbacks, or negative performance-related pay adjustments. | Meta-category II, type 2 |
| 8 | Material & Transactional | Resource Access Incentive | Motivation to act in ways that maintain or expand access to budgets, headcount, scarce assets, or privileged opportunities. | Meta-category II, type 3 |
| 9 | Material & Transactional | Rent-Seeking & Side-Payment Incentive | Motivation to exploit pricing, regulatory, or contractual gaps to capture surplus value (rents), often without proportional value creation. | Meta-category II, type 4 |
| 10 | Material & Transactional | Risk Transfer & Externalisation Incentive | Motivation to take actions that shift downside risk or cost onto others (customers, counterparties, the public sector), a core mechanism of moral hazard. | Meta-category II, type 5 |
| 11 | Informational & Cognitive | Information Advantage Incentive | Motivation to acquire or retain privileged information that improves bargaining position, decision quality, or personal security relative to others. | Meta-category III, type 1 |
| 12 | Informational & Cognitive | Attention & Salience Incentive | Motivation to respond primarily to issues, metrics, or signals that are made salient (e.g. via dashboards or escalations), while neglecting low-visibility risks or stakeholders. | Meta-category III, type 2 |
| 13 | Informational & Cognitive | Effort-Minimisation Incentive | Motivation to choose cognitively simpler options, heuristics, or defaults to avoid the mental effort, complexity, or ambiguity of deeper analysis. | Meta-category III, type 3 |
| 14 | Informational & Cognitive | Uncertainty Avoidance Incentive | Motivation to prefer options that reduce felt uncertainty (even if objectively inferior), such as over-insuring, over-specifying, or over-standardising. | Meta-category III, type 4 |
| 15 | Informational & Cognitive | Narrative Coherence Incentive | Motivation to favour explanations and actions that preserve a coherent story about self, organisation, or environment, even when evidence points to uncomfortable alternatives. | Meta-category III, type 5 |
| 16 | Social & Relational | Status & Recognition Incentive | Motivation to gain or maintain prestige, respect, or visibility, including awards, promotions, and being seen as a "star performer". | Meta-category IV, type 1 |
| 17 | Social & Relational | Belonging & Inclusion Incentive | Motivation to act in ways that secure acceptance within valued groups and avoid exclusion, isolation, or ostracism. | Meta-category IV, type 2 |
| 18 | Social & Relational | Reciprocity & Favour-Banking Incentive | Motivation to grant favours, leniency, or support now in expectation of future reciprocation, creating informal obligation networks. | Meta-category IV, type 3 |
| 19 | Social & Relational | Conflict Avoidance & Harmony Incentive | Motivation to avoid open conflict, disagreement, or escalation, even when challenge or dissent would be substantively beneficial. | Meta-category IV, type 4 |
| 20 | Social & Relational | Network Position & Access Incentive | Motivation to cultivate connections, gatekeeping roles, or brokerage positions that provide privileged access to people, information, and opportunities. | Meta-category IV, type 5 |
| 21 | Normative & Identity | Integrity & Principle-Consistency Incentive | Motivation to act in accordance with personal or professional principles, even at material cost, in order to preserve self-respect and coherence with one's values. | Meta-category V, type 1 |
| 22 | Normative & Identity | Professional Role-Identity Incentive | Motivation to behave in ways that fit the identity of being a "good engineer", "responsible clinician", "trusted advisor", or analogous professional persona. | Meta-category V, type 2 |
| 23 | Normative & Identity | Moral Licensing & Compensatory Incentive | Motivation to allow questionable behaviour in one domain because of perceived moral "credit" earned in another (e.g. "we do so much good that this corner-cutting is acceptable"). | Meta-category V, type 3 |
| 24 | Normative & Identity | Taboo & Boundary-Respect Incentive | Motivation to avoid crossing hard normative boundaries or taboos (e.g. safety breaches, corruption), regardless of short-term gain. | Meta-category V, type 4 |
| 25 | Normative & Identity | Purpose & Meaning Incentive | Motivation to choose actions that reinforce a sense of meaningful contribution or alignment with a larger mission, beyond financial or social rewards. | Meta-category V, type 5 |
| 26 | Temporal & Optionality | Short-Term Outcome Incentive | Motivation focused on near-term outcomes (quarterly results, immediate wins, crisis containment), often at the expense of long-term resilience or optimisation. | Meta-category VI, type 1 |
| 27 | Temporal & Optionality | Long-Term Accumulation Incentive | Motivation to act for long-run benefit (compounding returns, reputation over time, capability building), even when short-term costs are high. | Meta-category VI, type 2 |
| 28 | Temporal & Optionality | Optionality Preservation Incentive | Motivation to keep options open, delay irreversible commitments, and maintain flexibility under uncertainty. | Meta-category VI, type 3 |
| 29 | Temporal & Optionality | Intertemporal Shift Incentive | Motivation to pull benefits forward and push costs, risks, or liabilities into the future (for successors, other departments, or future selves). | Meta-category VI, type 4 |
| 30 | Temporal & Optionality | Irreversibility & Sunk-Cost Incentive | Motivation to continue with or escalate a chosen path because of sunk investments, perceived irreversibility, or fear of loss of face if reversed. | Meta-category VI, type 5 |

---

**End of Document**

---

*This Framework of Incentives v2.0 is aligned with the Analytical Series Master Rewrite Template v2.3 and the Analytical Series Operating Guide v2.5. For updates, corrections, or integration questions, contact the Series Maintainer.*
