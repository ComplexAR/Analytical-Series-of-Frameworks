# Framework of Systems
*A Comprehensive Taxonomy for Understanding Systems, Their Structures, Feedbacks, Boundaries, and Leverage Points*

## Document Information

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
- Group (Primary): G2 — Structure, dependencies & mechanism (Mechanism)
- Group (Secondary): G5 — Epistemics & error-control (Epistemics)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: System diagnosis and redesign; incident and failure analysis; risk and resilience analysis; governance and operating-model design; critical infrastructure analysis; ecosystem and platform analysis; policy and regulatory design; transformation planning
- Primary Audience: Executives; operations and engineering leaders; risk/compliance; investigators/auditors; architects; programme/transformation leaders; policy designers; regulators and assurance functions
- Dependencies / Key Inputs: Situation framing; system/boundary maps; evidence and incident history; stakeholder map; incentives and power map; governance/decision rights; time/scale characteristics; risk scenarios and failure history; Framework of Hiddens v4.5 (visibility audit layer)
- Primary Outputs: System statement and boundary assumptions; system type classification; structure/flow/feedback maps; dimension profiles; archetype match and leverage-point shortlist; interface ownership and governance requirements; Hiddens shortlist and escalation triggers; intervention and monitoring plan
- Change Log (brief): MRT v3.0 LLM Integration Bridge update: §1.6 rewritten to canonical Bridge format with LLM Extract pointer, near-neighbour disambiguation, and routing triggers (v2.1); simplified from full LLM integration section to streamlined extract-based execution model; all other sections preserved from v2.0.
## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What is the focal system, how is it structured, what feedbacks govern its behaviour over time, where are the boundaries, and where are the highest-leverage intervention points?** |
| Addresses | Component myopia; boundary errors; linear thinking in non-linear systems; ignoring delays and thresholds; misidentifying leverage points; treating governance as external rather than structural; failing to see system-of-systems cascades. |
| Gap Filled | Many analyses focus on parts, events, or single causes. Systems analysis explains how **structure + feedback + boundary choices** generate behaviour and why some interventions backfire. |
| Complements | Causation; Diagnosis; Risk; Time; Scale; Governance; Responsibility; Incentives; Power; Evidence; Hiddens; Learning & Adaptation; Interventions. |
| Key Characteristics | Boundary-explicit; feedback-centric; multi-scale; leverage-point oriented; compatible with socio-technical and ecosystem settings. |
| Main Contributions | Six meta-categories and thirty core system types; five cross-cutting system dimensions; five systemic dynamics archetypes; three interface types; hiddens source analysis and tiered Hiddens cross-check; application protocol and principles. |

---

# Introduction

## What is Systems and Structural Analysis?

A system is not merely a collection of parts—it is an organised set of elements whose relations, feedbacks, and boundaries jointly determine behaviour over time. Systems display emergent properties: patterns that cannot be understood by analysing components in isolation. When a supply chain fails to optimise despite every warehouse improving locally, when a safety intervention paradoxically increases risk-taking, or when a governance restructure produces chaos years later, the culprit is often not incompetence but hidden system structure. Systems analysis addresses this blind spot by making explicit the structure, feedback loops, delays, constraints, and boundary choices that generate observed behaviour.

This framework provides practitioners and organisations with a structured diagnostic lens: classify what kind of system you are analysing; map its structure and feedback loops; identify where behaviour is locked in by design rather than by people; locate the high-leverage points where small structural changes produce large effects; and detect where classic system archetypes (Limits to Growth, Fixes that Fail, Tragedy of the Commons) are creating failure patterns. Because systems analysis is vulnerable to its own blindnesses—boundary myopia, measurement distortion, latency in feedback perception—the framework includes a mandatory tiered Hiddens cross-check that uncovers where the analysis itself is fragile.

## Why does Systems matter for Hiddens work?

System-level Hiddens operate across multiple hiding mechanisms simultaneously. Fragmentation (Hidden-14) allows critical feedback loops to span organisational silos, so no single role has visibility of the full loop. Latency (Hidden-15) makes cause and effect appear disconnected, creating misattribution and repeat learning failures. Aggregation (Hidden-9) collapses local hotspots into average metrics that falsely suggest control. Distortion (Hidden-6) aligns metrics to convenient targets, which then drive behaviour that contradicts system-level goals. These Hiddens conspire to create what systems theorists call "model blindness" (Hidden-10): confident but wrong structural theories that persist despite repeated intervention failures.

This framework pairs with the Framework of Hiddens v4.5 to surface these systematic failures in understanding. By mapping feedback loops, identifying where control is slow relative to system dynamics, exposing measurement blindspots, and locating unowned interfaces, systems analysis reveals what remains hidden when only component-level and agent-level analysis is applied. The tiered Hiddens scan (Tier 1 scan across all six Hiddens meta-categories, Tier 2 shortlisting and depth, Tier 3 full-spectrum investigation) becomes a disciplined way to move from confident-but-fragile models to robust understanding.

## What does this framework produce?

The framework operationalises systems analysis through six core elements:

1. **A taxonomy of 30 system types** organised into six meta-categories (Structural–Constitutive, Dynamic–Feedback, Information–Control, Adaptive–Learning, Socio-Technical, Meta-Systems & Systems-of-Systems) that recur across domains and enable rapid classification and comparison.

2. **Five cross-cutting dimensions** (Openness & Boundary Permeability, Coupling & Interdependence, Feedback & Nonlinearity Profile, Adaptivity & Learning Capacity, Observability & Controllability) that profile any system and explain why different actors perceive different constraints and opportunities.

3. **Five dynamics archetypes** (Limits to Growth, Fixes that Fail, Shifting the Burden, Tragedy of the Commons, Success to the Successful) that describe recurring failure patterns and signal where structural intervention is urgent.

4. **Three interface types** (Boundary & Environment, Flow/Coupling & Feedback, Control/Governance & Leverage) that make visible where systems interact, clash, or nest—zones of high risk and opportunity for leverage.

5. **Hiddens source analysis and tiered Hiddens scans** that surface seven systematic sources of systems-analysis blindness (Component Myopia, Boundary Mis-Specification, Feedback Blindness, Static Snapshot Bias, Actor-Centric Reduction, Leverage-Point Illusion) and map them to the six Hiddens meta-categories (I–VI).

6. **A six-step application protocol** that moves from system framing through structure/feedback mapping, typing, dimensional profiling, archetype/risk analysis, and leverage design, producing standard registers (Hiddens, Evidence, Hypothesis/Test Backlog, Information Requests).

The framework populates shared registers (Group Coverage Matrix, Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog) that integrate with the broader Analytical Series workflow and enable hand-off to downstream frameworks (Decisions, Interventions, Governance, Risk, Learning & Adaptation).

## How to use this framework

Invoke this framework when system-level factors are plausible (coordination across components, tight coupling, non-linear dynamics, boundary disputes, cascades, or failures despite repeated fixes). The framework works in both Rapid Run Mode (light-touch system scan and leverage shortlist) and Investigative Run Mode (deep dimensional profiling, full Hiddens scanning, stress testing against scenarios).

Default execution is Light Depth Framework Execution: sketch the focal system and boundaries, assign types from the 30-type taxonomy, profile the most consequential one or two dimensions, spot obvious interfaces, run a Tier 1 Hiddens scan (all six meta-categories touched lightly). Escalate to Full Depth when consequence is high, evidence is contested, tight coupling or cascade risk is suspected, or past interventions have backfired due to hidden system effects. The framework's companion Prompt Discipline rules (OG v2.5, §D.3) require tagging all system type and structure claims as Fact, Interpretation, Assumption, or Unknown, and explicitly preserving uncertainties rather than collapsing them into false consensus.

For LLM execution, see §1.6 for the complete LLM integration specification, canonical Prompt Discipline Rules pointers, standard registers, and copy-ready run prompts. The framework is designed to be directly executable by an LLM given a scenario, the Operating Guide, and the six core elements, producing disciplined system maps with explicit Hiddens, F/I/A/U tagging, leverage analysis, and bounded closure.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

A system is not simply a collection of parts; it is an organised set of elements whose **relations, feedbacks, and boundaries** jointly determine behaviour over time. Systems display emergent properties—patterns that cannot be understood by analysing components in isolation. Many failures and risks arise not because any single component fails, but because interactions, incentives, delays, and boundary choices generate non-obvious cascades. Interventions designed at the component or individual level often fail because they ignore the structural forces that keep undesired behaviour in place.

This framework provides a structured way to:
- define the focal system and its boundaries,
- classify the system type(s) in play,
- map structure, flows, and feedbacks,
- identify key dimensions that determine system fragility or resilience,
- recognise common archetypal dynamics and failure patterns,
- locate actionable leverage points for redesign, and
- run a mandatory tiered Hiddens cross-check for non-trivial work.

Because systems analysis is vulnerable to visibility failures (fragmentation, distortion, latency, model blindness), the framework explicitly pairs with **Framework of Hiddens v4.5** as the series-standard visibility audit layer. Tier 1 and Tier 2 checks provide fast coverage for routine systems work; Tier 3 escalation means running the full 30-type Hiddens scan plus detection/remediation mapping and interaction analysis.

## 1.2 Assumptions & Preconditions

Systems work often fails because implicit dependency claims are left untested: boundaries are assumed rather than argued; feedbacks are treated as linear; control and information flows are taken as transparent; and "the system" is mistaken for a static diagram rather than a dynamic, governed reality. The tables below surface the most consequential assumptions and preconditions that sit beneath systems mapping and leverage analysis. If a high-impact assumption is weak or contested, treat it as an **uncertainty** and decide whether to reduce, hedge, robustify, or preserve options. If an assumption may be strategically suppressed or distorted, run an explicit **Hiddens** scan and consider escalation.

### Assumptions Register (recommended)
| Assumption | Type (method / structural / domain / normative) | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| The analysis is anchored to a focal decision/question, time horizon, and stakes. | Method | "System" becomes unbounded; leverage claims cannot be prioritised; maps become decorative. | Require a 1-page decision/situation brief; record horizon, reversibility, and error-costs. | Timebox a minimum viable system map; maintain a decision-linked leverage shortlist. |
| A workable system boundary can be specified for the purpose (even if contested and permeable). | Structural | Misattribution and orphan risks: key drivers sit outside the boundary; interventions target the wrong scope. | Boundary-challenge prompts; interface inventory; test whether out-of-bound factors explain residuals. | Use nested boundaries; maintain an explicit boundary-assumptions log; revisit after interventions. |
| Major stocks/flows/constraints can be identified to a "good enough" level. | Method | Feedback reasoning degrades into storytelling; monitoring cannot be instrumented. | Build an element inventory; validate against operational data and frontline walkthroughs. | Start with coarse-grain stocks/flows; iterate by highest consequence gaps first. |
| Feedback loops and delays are discoverable in the available time and evidence. | Method | Linear models mispredict; leverage points are misidentified; oscillations and rebounds surprise. | Look for oscillation signatures, lagged correlations, and control actions with delayed effects. | Assume delays by default; design interventions with monitoring and stop rules; run scenario tests. |
| Observability and access are sufficient to validate key parts of the map (or gaps can be made explicit). | Domain | "Unknowns" are mislabelled as "known"; dashboards create mirage; governance acts on fiction. | Evidence inventory with provenance; compare multiple observers (roles) and multiple sources. | Tag low-visibility areas as hiddens; invest in instrumentation and independent verification. |
| Control/governance structures can be represented as part of the system (not external). | Structural | Governance goes unexamined; failures are blamed on "people" rather than control architecture. | Map decision rights, escalation paths, and control loops alongside technical structure. | Use Governance/Decisions frameworks for detail; include at least a minimal control loop map here. |
| Multi-scale interactions can be handled with explicit levels (micro/meso/macro) and handoffs. | Structural | Composition/division fallacies; local optimisation breaks global performance; cross-scale cascades are missed. | Identify levels and handoffs; test for cross-level constraints and feedback. | Maintain a multi-scalar map; prioritise interfaces where cross-level coupling is strongest. |
| The 30-type taxonomy provides adequate baseline coverage (extensions are documented and mapped). | Structural | Category absence forces misclassification and brittle interventions. | Track "none-of-the-above" frequency and recurring edge cases. | Extend taxonomy per Section 3.7; map extensions back to nearest canonical type; version-control changes. |

### Preconditions Checklist (recommended)
| Precondition | Required? (Y/N) | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Focal decision/situation brief exists (scope, stakes, horizon, success criteria). | Y | Decision brief; situation framing note | Decision owner | To be verified per case | Run a 30–60 minute scoping session; proceed with provisional tags. |
| Initial system boundary statement exists (in/out; interfaces; time window). | Y | Boundary statement; context map | Lead analyst | To be verified per case | Use Boundaries/Situations to produce a minimum boundary definition. |
| Element inventory exists for key components/agents/resources/variables. | Y | Element list; architecture diagrams; stakeholder list | System owner / architect | To be verified per case | Start with "top 20" elements by consequence; iterate from incident logs and SME interviews. |
| Access paths to core evidence sources are identified (data, logs, documents, SMEs). | Y | Evidence inventory; access approvals | Evidence owner / data steward | To be verified per case | Document access gaps as candidate hiddens; use indirect indicators; escalate for approval. |
| A cadence and time horizon is set (system tempo, review points, re-scan triggers). | Y | Analysis plan; monitoring cadence | Programme lead | To be verified per case | Timebox to Tier 1 map + highest-risk interfaces; schedule re-scan once evidence improves. |
| Escalation route exists for high-stakes hiddens or systemic risk (Tier 3 trigger). | Y | Escalation policy; sponsor named | Governance owner | To be verified per case | Define ad-hoc escalation path; record triggers and decision rights. |

## 1.3 Definitions, Scope, and Non-Goals
- **System (operational)**: a set of interacting elements organised by structure and feedback, with boundaries, inputs/outputs, and characteristic behaviour over time.
- **Boundary**: the conceptual or physical line separating system from environment for a given purpose (often contested and permeable).
- **Leverage point**: a place in the system where a small change produces a large effect (often structural, not parameter-level).

In scope:
- Six meta-categories and 30 canonical system types
- Five cross-cutting system dimensions
- Five common systemic archetypes and leverage patterns
- Three interface types (boundary, feedback, control/governance)
- Hiddens sources and tiered Hiddens scan protocol

Out of scope (by design):
- Full domain-specific modelling methods (e.g., full system dynamics simulations) beyond diagnostic use
- Full intervention catalogues (Interventions framework)
- Full accountability allocation (Responsibility framework)

## 1.4 Position in the Series (Upstream / Middle / Downstream)
- **Upstream (signals/understanding)**: Situations; Realities; Boundaries; Relations; Processes; Evidence; Perspectives; Hiddens (visibility constraints).
- **Middle (this framework's role)**: Define the focal system and boundaries; classify system type(s); map structure/flows/feedbacks/control; profile key dimensions; identify leverage points and interface risks.
- **Downstream (action/governance)**: Diagnosis and causal hypotheses; Risk and failure analysis; Decisions and Interventions; Governance design; Monitoring and Learning & Adaptation.

- **Group assignment (Primary)**: G2 — Structure, dependencies & mechanism (Mechanism)
- **Group assignment (Secondary)**: G5 — Epistemics & error-control (Epistemics)
- **Stage assignment**: Middle (see OG v2.5 §3.1)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.9.2 Mode Selection Gate)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
- **Framework Index**: this framework is one of 36 in the series (see OG v2.5 §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary (recommended)
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Ontology & boundaries | Realities; Boundaries; Relations | What exists; what is in/out; how entities connect | A coherent system statement; structural map of parts and interfaces; boundary and interface risk implications |
| Change over time | Processes; Time; Scale | Trajectories, tempo, and cross-scale interactions | Feedback-loop and delay reasoning; where dynamics will amplify/dampen; where leverage points sit structurally |
| Epistemics & visibility | Evidence; Uncertainties; Hiddens (v4.5) | Evidence quality; uncertainty structure; visibility failure taxonomy | Where the system map depends on fragile observability; which hiddens threaten the model; detection/remediation ownership |
| Governance & action | Governance; Decisions; Interventions; Risk; Failures | Authority, oversight, choice points, levers, and hazard structure | System-aware governance: control loops, escalation pathways, monitoring design; intervention targeting that avoids rebound and cascade risk |


## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Systems_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Systems when… | Use neighbour instead when… |
|---|---|---|
| Causation | Analysing feedback loops, causal chains, and how structure generates behaviour over time; multi-loop reasoning; nonlinear causality; emergent effects. | Analysing single-cause hypotheses, linear event-to-outcome attribution, or immediate blame assignment; isolating isolated causal mechanisms without system loops. |
| Diagnosis | Mapping system structure, types, and feedback patterns to explain why an outcome occurred; identifying leverage points where small structural changes produce large effects. | Root-cause analysis focused on specific failure events, component blame, or immediate corrective actions; single-domain troubleshooting. |
| Risk | Identifying system archetypes that produce recurring failure patterns (Limits to Growth, Fixes that Fail, Tragedy of the Commons); cascade propagation and coupling-dependent scenarios. | Estimating probability and impact of discrete hazards; compliance-checklist risk; quantitative scenario analysis on fixed assumptions. |
| Governance | Designing control loops, decision rights, and escalation pathways as part of system structure; observability and actuation constraints on governance capacity. | Formal authority structures, policy design, or accountability allocation independent of system dynamics; incentive alignment and rule-making. |
| Processes | Analysing how system structure enables or constrains activity sequences; how feedback affects workflow design; boundaries between system and process. | Analysing activity flows independent of technical/structural substrate; process efficiency and sequencing; work-practice design. |

### 1.6.3 Routing triggers
- Focal system involves feedback loops, delays, nonlinear dynamics, or multi-component interactions
- Interventions have backfired, produced unintended side effects, or amplified the problem
- Boundary disputes exist: what is "in scope" vs "out of scope" is contested or affects outcomes
- Cascade risk or tight coupling is suspected between previously thought-independent systems
- Structural change (redesign, transformation, governance restructure) is being considered
- System behaviour is non-obvious: local optimization fails globally or policy changes have unexpected effects
- Observability or controllability is limited: dashboards may be mirage; control levers may be ineffective
- Multi-scale interactions are present: local actions aggregate to macro patterns or macro constraints feed back down
- Incumbent leverage interventions have been tried and failed despite best intentions
---

# 2. Meta-Categories of Systems

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---|---|---|---|---|
| I | Structural–Constitutive | What is this system made of, how are parts arranged, and where are the boundaries? | Components and subsystems; physical and logical boundaries; stocks, flows, and interfaces. | Machines, organisms, buildings, data architectures. |
| II | Dynamic–Feedback | What feedback loops and flow patterns govern behaviour over time? | Balancing and reinforcing loops; delays; oscillations; nonlinearities. | Climate subsystems, markets, population dynamics, inventory systems. |
| III | Information–Control | How does the system sense, decide, and adjust its behaviour? | Sensing, signalling, decision rules, control loops, observability and controllability. | Cyber-physical control systems, management control systems, nervous systems. |
| IV | Adaptive–Learning | How does the system change its own structure or rules over time? | Learning, adaptation, self-organisation, evolution, co-evolution. | Ecosystems, learning organisations, machine learning systems, innovation ecosystems. |
| V | Socio-Technical | How do human, social, and technical subsystems interact as a whole? | Interaction of people, technologies, institutions, and cultures. | Organisations, critical infrastructures, platform ecosystems, bureaucracies. |
| VI | Meta-Systems & Systems-of-Systems | How do multiple systems interact, nest, or oversee each other? | Systems-of-systems, supervisory meta-systems, cross-scale couplings. | Multilevel governance, multi-infrastructure grids, federated platforms, regulatory regimes. |

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- Canonical baseline: 6 meta-categories × 5 types = 30 core types.
- This framework: 30 types (canonical).
- Mapping back to baseline: Preserved as-is from v1.2.

## 3.1 Types (Category I: Structural–Constitutive)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 1 | Component–Assembly System | System whose primary structure is a relatively fixed assembly of discrete components with defined positions and roles (e.g., machines, engineered products, modular software). Focus on physical or logical composition. | Inventory components and interfaces; confirm how assemblies compose and where failures propagate. | Local fixes ignore interface mismatch; failures emerge at seams and assemblies. |
| 2 | Networked–Relational System | System organised as nodes and links through which resources, information, or influence flow (e.g., transport networks, communication networks, social networks). Topology strongly shapes behaviour. | Map network topology (centrality, hubs, clustering); identify critical nodes and contagion paths. | Hub failure or cascade spreads rapidly; resilience depends on topology, not just component quality. |
| 3 | Layered / Hierarchical System | System composed of levels (micro, meso, macro) with upward and downward influences (e.g., organisational hierarchies, protocol stacks, anatomical structures). Structure is tiered rather than flat. | Identify levels and handoffs (micro/meso/macro); test whether governance/controls match each level. | Cross-level mismatch causes drift: local optimisation breaks global performance. |
| 4 | Modular–Composable System | System built from semi-autonomous modules with standardised interfaces, enabling recombination, substitution, and differential scaling (e.g., microservices architectures, modular hardware, organisational units). | Assess modular boundaries, APIs, coupling; test substitutability and recomposition under stress. | Hidden coupling destroys modularity; change causes unanticipated breakage and cascade. |
| 5 | Open Environment-Embedded System | System whose boundary is permeable and tightly coupled to environmental flows (e.g., organisms, open economies, cloud-native services). Inputs and outputs are continuous and critical to viability. | Specify boundary and environment; map inputs/outputs; quantify permeability and contested edges. | Out-of-boundary externalities return as shocks; responsibility gaps and 'out of scope' failures appear. |

## 3.2 Types (Category II: Dynamic–Feedback)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 6 | Balancing / Homeostatic System | System dominated by negative feedback loops that seek to maintain variables near target values (e.g., thermostats, blood glucose regulation, inventory control). Tends toward stability within operating ranges. | Identify balancing loops and setpoints; measure delays; test robustness to disturbance. | Over-control or slow response causes oscillation; hidden setpoints drive unexpected behaviour. |
| 7 | Reinforcing / Amplifying System | System dominated by positive feedback loops that accelerate growth or decline (e.g., compound interest, viral spread, winner-takes-most markets). Small differences can snowball into large disparities. | Locate reinforcing loops; identify what grows (demand, risk, exposure); test for runaway conditions. | Unchecked reinforcement produces exponential escalation; small errors compound into major events. |
| 8 | Oscillatory / Cyclic System | System in which feedback with delays produces regular or quasi-regular cycles (e.g., business cycles, predator–prey dynamics, maintenance–failure oscillations). Stability manifests as ongoing oscillation rather than equilibrium. | Measure cycle period and drivers; identify phase relationships and damping; check seasonality. | Cyclic peaks create predictable failure windows; ignoring cadence makes incidents look random. |
| 9 | Nonlinear / Threshold System | System whose behaviour changes qualitatively when certain thresholds or tipping points are crossed (e.g., traffic flow breakdown, phase transitions, regime shifts in ecosystems). Small changes in input can trigger large changes in output. | Identify thresholds/tipping points; map hysteresis and irreversibility; test near-boundary behaviour. | Crossing a threshold flips regime; recovery is harder than prevention; late action fails. |
| 10 | Multi-Loop Interacting System | System with multiple interacting feedback loops, none of which dominates completely (e.g., complex organisations, macroeconomies, climate systems). Behaviour emerges from loop interactions and cannot be reduced to any single loop. | Map multiple interacting loops; identify dominant loops by regime; check for unintended feedback. | Interacting loops produce non-intuitive outcomes; interventions shift dominance and backfire. |

## 3.3 Types (Category III: Information–Control)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 11 | Closed-Loop Feedback-Control System | System that continuously senses its own outputs or state, compares them to a reference, and adjusts inputs accordingly (e.g., PID controllers, autopilots, many management dashboards with corrective actions). | Define controlled variable(s), sensors, actuators, and controller logic; test stability margins. | Controller tuned for normal conditions becomes destabilising under disturbance; 'control theatre' masks instability. |
| 12 | Feedforward / Anticipatory System | System that predicts disturbances or future states and adjusts pre-emptively rather than waiting for error signals (e.g., predictive maintenance, forecast-based staffing, human anticipatory control). | Identify anticipatory signals and models; test prediction validity and model drift. | Feedforward fails when models are wrong; false confidence leads to brittle decisions. |
| 13 | Decentralised / Distributed-Control System | System in which control is dispersed across multiple local controllers or agents following local rules (e.g., the internet's routing, swarms, market price mechanisms). Global behaviour arises without central command. | Map distributed agents and decision rules; test coordination mechanisms and failure containment. | Local rules create global pathologies; misaligned incentives cause emergent failure. |
| 14 | Observability-Limited System | System whose internal state is only partially visible to observers or controllers (e.g., opaque organisations, black-box AI models, underground economies). Limited observability constrains effective control and diagnosis. | Identify unobserved states and measurement gaps; test instrumentation coverage and latency. | What cannot be seen cannot be governed; surprises persist; mirage dashboards form. |
| 15 | Controllability-Limited System | System whose state can be observed but is difficult to steer because actuators, levers, or permissions are weak, slow, or fragmented (e.g., legacy infrastructures, multi-party governance with veto players). | Assess actuator authority and feasible control space; identify constraints/veto points and saturation. | Responsibility assigned without control capacity; governance cannot change key parameters. |

## 3.4 Types (Category IV: Adaptive–Learning)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 16 | Evolutionary / Selection System | System that adapts through variation, selection, and retention over populations and generations (e.g., biological evolution, competitive markets, research ecosystems). No central designer; adaptation occurs via differential survival. | Specify selection pressures and fitness criteria; identify what survives and why. | System optimises the wrong target due to incentives; maladaptive behaviours persist. |
| 17 | Learning / Updating System | System that updates internal parameters or policies based on experience (e.g., machine learning models, learning organisations, continuous improvement systems). Past performance shapes future behaviour. | Identify learning loop (observe → update → act); test data quality and update cadence. | Learning is slow or biased; repeated failures occur; adaptation becomes performative. |
| 18 | Self-Organising System | System in which macroscopic order emerges spontaneously from local interactions without central design (e.g., flocking, traffic patterns, spontaneous role differentiation). Structure is produced endogenously. | Characterise emergent order; identify local rules; test stability and robustness of self-organisation. | Self-organisation can create brittleness and lock-in; small rule changes yield large effects. |
| 19 | Co-Evolving System | System that adapts in continuous interaction with an adapting environment or other systems (e.g., host–pathogen systems, security–attacker dynamics, platform–complementor ecosystems). Feedback is mutual. | Map coupled adaptations among actors/systems; identify arms races and feedback between adaptations. | Co-evolution produces escalation and instability; interventions in one part shift pressure elsewhere. |
| 20 | Path-Dependent System | System whose current and future states are strongly shaped by past trajectories, lock-in, and irreversibilities (e.g., technology standards, institutional paths, habit formation). "History matters" beyond current conditions. | Trace historical decisions and irreversible commitments; identify lock-in and option erosion. | Past constraints ('ghosts') govern present; change becomes expensive; path dependence mistaken for necessity. |

## 3.5 Types (Category V: Socio-Technical)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 21 | Infrastructure System | Large-scale systems providing foundational services on which others depend (e.g., energy grids, water systems, transport networks, digital backbones). Typically capital-intensive, long-lived, and tightly coupled. | Map physical and digital infrastructure dependencies; test redundancy, maintenance, and failure modes. | Hidden single points of failure and legacy constraints create systemic outages. |
| 22 | Organisational System | Systems of roles, processes, technologies, and cultures oriented toward collective goals (e.g., firms, agencies, NGOs). Formal structures and informal practices jointly shape behaviour. | Map roles, decision rights, and coordination routines; test how work actually flows (not just org charts). | De facto system diverges from formal design; responsibility dumping and bottlenecks arise. |
| 23 | Policy–Regulatory System | Systems of rules, enforcement mechanisms, regulators, and regulated actors (e.g., financial regulation, environmental regimes). Outcomes depend on both formal rules and enforcement/incentive structures. | Map rule-making, enforcement, compliance loops; identify incentives and unintended consequences. | Regulatory/policy changes create second-order effects; fixes that fail and gaming behaviours appear. |
| 24 | Platform–Ecosystem System | Socio-technical systems structured around a platform that coordinates complementary participants (e.g., app stores, marketplaces, data platforms). Governance and interface design strongly shape emergent behaviour. | Map platform governance, participants, and externalities; test boundary control and ecosystem health. | Misaligned incentives trigger ecosystem collapse; runaway growth meets legitimacy limits. |
| 25 | Community–Practice System | Systems built around shared practices, norms, and identities rather than formal hierarchy (e.g., professional communities, open-source projects, epistemic communities). Social capital and norms are key mechanisms. | Assess norms, knowledge sharing, legitimacy, and onboarding; test whether practice is transferable. | Community success depends on intangible resources; fragmentation and amnesia degrade capability. |

## 3.6 Types (Category VI: Meta-Systems & Systems-of-Systems)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---|---|---|---|---|
| 26 | System-of-Systems Configuration | Assembly of operationally independent systems that retain their own purposes but cooperate for higher-order capabilities (e.g., emergency response systems, joint command structures, federated data spaces). Integration and interoperability are central challenges. | Identify constituent systems, interfaces, and coordination mechanisms; test failure propagation paths. | Local resilience does not imply global resilience; cascades emerge across interfaces. |
| 27 | Supervisory / Meta-Control System | System whose primary role is to monitor, coordinate, or constrain other systems (e.g., regulators, safety oversight bodies, meta-schedulers, governance boards). Often operates at a slower tempo and higher abstraction. | Identify meta-control layer (oversight, audit, regulation); test its independence, cadence, and authority. | Meta-control is slow or captured; governance lags reality; accountability theatre. |
| 28 | Cross-Scale Coupled System | System in which micro-, meso-, and macro-level dynamics interact strongly (e.g., financial systems, ecosystems, multi-level governance). Local actions aggregate to macro patterns that feed back down. | Map fast/slow layers and cross-scale feedback; identify aggregation and translation failures. | Fast harms outrun slow governance; cross-scale mismatch drives instability and surprise. |
| 29 | Reflexive / Self-Modeling System | System that contains explicit internal models of itself and uses them for steering (e.g., organisations with strategic intelligence functions, adaptive AI with world-and-self models, complex planning systems). | Identify internal models, assumptions, and self-monitoring; test calibration and self-deception risks. | Self-model errors create confident wrong actions; reflexivity amplifies narratives and mirages. |
| 30 | Multi-Paradigm / Hybrid System | System that combines multiple structural logics or system types (e.g., platforms that are also regulators, public–private partnerships, hybrid cloud–on-prem infrastructures). Different parts operate under different organising principles. | Identify multiple organising logics (hierarchy + market + network, etc.); map conflicts and translations. | Hybrid systems fail at interfaces; competing logics create incoherent incentives and controls. |

## 3.7 Extending the Taxonomy (mandatory)
| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | Preserve the 30-type scaffold for comparability across cases and domains. |
| Domain-specific refinement | Add subtypes under parent types (e.g., "OT control system," "market platform governance," "safety-case system-of-systems"). |
| Preserving mappability | Each subtype must specify: boundaries, dominant feedbacks/delays, control/observability constraints, scale coupling, and typical failure archetypes. |
| Structural invariants | Keep six meta-categories and the five dimensions; structural changes require major version bump. |
| Periodic reassessment | Maintain exemplars of systemic failures and successful leverage interventions; retire redundant subtypes. |
| Interoperability | Document interactions with Causation, Risk, Time, Governance, Incentives, Power, Evidence, and Hiddens. |

---

# 4. Cross-Cutting Dimensions of Any System

## 4.1 Dimensions Table (mandatory)
| Dimension | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| **Openness & Boundary Permeability** | Core question: *How open is the system's boundary to flows of matter, energy, information, and influence?* | Closed (minimal exchanges; rare flows) → Selectively Open (designed interfaces; controlled exchanges) → Semi-Open (substantial flows, some unmanaged) → Open (highly permeable, continuous coupling) → Diffuse (boundary ambiguous/contested). | State the boundary; list major inputs/outputs; rate permeability and identify unmanaged flows. | Clarifies where externalities and 'out of scope' effects re-enter; guides boundary governance and interface design. |
| **Coupling & Interdependence** | Core question: *How tightly do changes in one part propagate to others?* | Decoupled (weak interactions; local effects) → Loosely Coupled (slow propagation, damping) → Moderately Coupled (significant, manageable propagation) → Tightly Coupled (rapid spread, limited buffering, cascade risk) → Hyper-Coupled (dense, nonlinear, opaque interdependencies). | Identify critical dependencies and coupling strength; look for tight coupling with little slack and many dependencies. | Predicts cascade risk and change sensitivity; informs modularisation, buffering, and decoupling strategies. |
| **Feedback & Nonlinearity Profile** | Core question: *What mix of feedback loops and nonlinearities shapes behaviour?* | Weak-Feedback / Near-Linear (outputs ≈ proportional to inputs; linear models often suffice) → Balancing-Dominated (negative feedback; stability around targets) → Reinforcing-Dominated (positive feedback; self-accelerating growth/decline) → Mixed / Complex (multiple interacting loops; contingent on context) → Threshold / Regime-Shift-Prone (sharp transitions, hysteresis, tipping points). | List dominant reinforcing/balancing loops; identify delays and thresholds; note regime changes. | Explains 'why now' and non-intuitive behaviour; guides leverage-point selection and avoids backfiring interventions. |
| **Adaptivity & Learning Capacity** | Core question: *To what extent can the system change its own rules, structures, or parameters in response to experience?* | Non-Adaptive (fixed behaviour; no internal change except external redesign) → Parameter-Tuning (adjust parameters within fixed structure) → Policy-Adaptive (change decision rules/strategies in response to experience) → Structural-Adaptive (reconfigure modules/roles/connections) → Self-Transforming / Co-Evolutionary (alter identity and environment). | Assess whether the system senses, updates, and changes behaviour; check learning cadence and governance for change. | Distinguishes brittle systems from adaptive ones; guides investment in feedback loops, experimentation, and unlearning. |
| **Observability & Controllability** | Core question: *How well can the system's state be inferred and steered by internal or external agents?* | High Observability & Controllability (states well-sensed, effective levers exist) → Observable but Hard-to-Control (can monitor, but levers are weak/slow/fragmented) → Controllable but Hard-to-Observe (powerful levers exist, but sensing is poor/delayed) → Low Observability & Controllability (largely opaque, resistant to steering) → Black-Box / Uncontrollable (neither state nor effective levers available). | List what can be measured and influenced; identify hidden states and actuator limits; test latency and authority. | Determines whether governance can steer the system; reveals where responsibility is impossible without control. |

---

# 5. Dynamics: Five Systemic Archetypes

## 5.1 Dynamics Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---|---|---|---|---|---|
| 1 | Limits to Growth | Fast initial improvement, then plateau/decline as a hidden constraint dominates. | Reinforcing growth loop constrained by a slower balancing loop (resource, capacity, or legitimacy limit). | Over-investment, overshoot, collapse if limits are ignored. | Locate the real constraint; invest to raise the limit; avoid adding fuel without addressing capacity/legitimacy. |
| 2 | Fixes that Fail | Short-term improvement followed by rebound; dependency on the fix increases. | Short-term symptomatic fix undermines or delays fundamental solution, often via side-effects. | Dependency on quick fixes; neglect of root causes. | Expose side-effects; invest in structural solution; constrain use of symptomatic fixes. |
| 3 | Shifting the Burden | Symptoms treated repeatedly while capability to solve root cause decays. | Responsibility or effort is shifted from primary actors to secondary ones (or to future selves). | Burnout, fragility, erosion of core capability. | Make root-cause work mandatory; build capability; create governance to prevent repeated symptomatic reliance. |
| 4 | Tragedy of the Commons | Local rational use depletes shared resource; collective outcome deteriorates. | Multiple agents share a finite resource without adequate coordination or enforcement. | Resource collapse, conflict, legitimacy crises. | Define boundaries and rights; monitor usage; align incentives; introduce collective governance and enforcement. |
| 5 | Success to the Successful | Initial advantage compounds; winners keep winning; losers are starved. | Reinforcing loop allocating more resources to already successful agents or options. | Loss of diversity, fragility, under-exploration. | Rebalance resource allocation; cap runaway reinforcement; create fair access and capability-building for lagging actors. |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | Boundary & Environment Interface | Where the system exchanges matter/energy/information/authority with its environment; where 'in scope' is defined and contested. | Where are the boundaries; how permeable are they; what flows cross them; which externalities return as shocks? | Supplier/customer interfaces; regulatory perimeter; OT/IT boundary; ecosystem participation rules |
| B | Flow, Coupling & Feedback Interface | Where interactions and feedback loops create behaviour over time, including delays, thresholds, and cascades. | Which loops dominate; where are delays and thresholds; where is tight coupling creating cascade risk? | Inventory replenishment loops; demand/price feedback; incident-response escalation loops; safety interlocks |
| C | Control, Governance & Leverage Interface | Where decision rights, sensing, actuation, and accountability determine whether the system can be steered and improved. | What is observable and controllable; who has authority; what is the governance cadence; where are veto points? | Control-room operations; change-management; supervisory regulation; audit and assurance; platform governance rules |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links (recommended)
- **Inputs expected**: evidence and incident histories; system boundaries and dependencies; incentives/power and governance structure; time/scale characteristics; risk scenarios.
- **Outputs provided**: structure/feedback/boundary maps; leverage-point shortlist; interface ownership and governance requirements; system-type-specific failure hypotheses; Hiddens shortlist and escalation triggers.

## 7.2 Crosswalk Table (recommended)
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| Causation | Mechanisms, causal chains, counterfactual tests | System-level structure and feedback context for causes | Avoid single-cause narratives; explain cascades |
| Risk & Failures | Scenarios, tail risks, failure taxonomies | Propagation pathways and systemic leverage points | Design systemic controls vs component fixes |
| Time | Lags, windows, tempo, horizons | Cross-scale coupling and feedback-driven 'why now' | Diagnose oscillations and delayed harm |
| Governance & Responsibility | Decision rights, oversight, duty allocation | Where governance must intervene in structure/loops | Close responsibility gaps at interfaces |
| Power & Incentives | Who can change the system; what is rewarded | Power/incentive loops that stabilise behaviour | Prevent gaming and 'fixes that fail' |
| Evidence | Evidence integrity, data pipelines | Observability constraints; measurement design needs | Fix distortion/aggregation and mirage dashboards |
| Hiddens (v4.5) | Visibility failure taxonomy | System-specific hiding places (interfaces, delays, silos) | Run tiered scan and assign detection ownership |
| Learning & Adaptation | Learning loops and update mechanisms | System design for adaptation and unlearning | Build resilient improvement cycles |
| Competencies | What agents can reliably do at specific system nodes | Whether system-critical competency nodes are identified and redundant | Competency-aware system design; identify where competency gaps propagate |

## 7.3 Integration Questions by Framework (recommended)
| Framework | Integration questions | Outputs / artefacts to pull in | Notes |
|---|---|---|---|
| Situations Context Classification | What situation dynamics—stability, crisis, change, opportunity—characterise the focal system and its environment? How does context shape feasible interventions? | Situation trajectory and classification; urgency/reversibility/stakeholder alignment | Systems analysis reveals structural reasons for context; helps avoid symptomatic fixes. |
| Boundaries | How are the system boundaries physically, conceptually, and socially drawn? What externalities are being treated as "out of scope"? | Boundary statement with in/out interfaces; candidate multi-scalar boundaries | Systems framework asks: whose boundary is this, and what cascades across it? |
| Dimensions | At what dimensional tiers (physical, biological, cognitive, social, symbolic) does the system operate? How do tiers interact? | Dimensional tier assessment; cross-tier feedback and cascade points | Systems identifies where lower-tier constraints limit higher-tier aspirations. |
| Realities | What realities (grounding, institutional, modal, normative, process) are instantiated in the system? | Reality mix present in the system; which realities are contested or invisible | Systems asks: are rules/incentives aligned to proclaimed values, or do hidden realities contradict formal structure? |
| Scale | At what temporal and spatial scales does the system operate, and where are critical thresholds and scaling limits? | Characteristic scales, lags, growth/saturation curves, tipping points | Systems identifies cross-scale couplings where micro-level changes aggregate to macro-level surprises. |
| Time | What temporal patterns (lags, windows, reversibility) govern system behaviour? Where does delayed feedback hide consequences? | Time-lag inventory; feedback loop delays; reversible vs irreversible changes | Systems framework uses time to map feedback delay structures producing oscillation or late discovery. |
| Relations | What are the key relations (flows, dependencies, influences) between system components and between system and environment? | Relational map: stocks, flows, dependencies, interfaces | Systems "types up" relations into feedback loops, coupling patterns, and cascade pathways. |
| Processes | What core processes run inside the system, with what start/stop conditions, tempos, and failure modes? | Process inventory; activation/termination rules; process interactions | Systems identifies where process sequencing, synchronisation, or timing create bottlenecks or cascades. |
| Causation | What causal chains and counterfactual mechanisms explain observed behaviour? | Causal hypotheses and mechanisms; feedback-driven causation | Systems embeds causal claims in feedback structure and multi-loop context. |
| Agents | Which agents participate in or are embedded in the system, with what roles, capacities, and incentives? | Agent/role inventory; agency distribution; veto/amplification points | Systems asks: do agents' local incentives align with system-level goals, or do they produce emergent pathologies? |
| Personas | What are the distinguishing characteristics, needs, and mental models of key stakeholder types? | Persona profiles; stakeholder expectations; conflicting narratives | Systems identifies where personas disagree about boundaries, feedback, or feasible changes—a Hiddens source. |
| Incentives | What incentive structures shape behaviour inside the system and at its interfaces? | Incentive map: explicit rewards, informal status, power bases | Systems reveals how incentives create feedback loops that stabilise behaviour or produce "fixes that fail." |
| Power | Who can change system structure, rules, or parameters, by what right, and with what constraints? | Power distribution; veto points; change capacity/authority | Systems locates power at control loops, decision nodes, and interfaces. |
| Responsibility | Who is accountable for system-level outcomes, and where do responsibility gaps exist? | Responsibility map; ownership of feedback loops and interfaces | Systems exposes where boundaries create orphan risks and cascades spread. |
| Culture and Norms | What shared understandings, practices, and norms govern behaviour in and around the system? | Cultural norms inventory; unwritten rules; enforcement mechanisms | Systems identifies how norms shape what feedback is acknowledged and what counts as "the system." |
| Perspectives | What interpretive lenses or narratives are available, and whose perspective dominates? | Perspective inventory; contested interpretations; whose view is heard | Systems asks: do analyses from different roles reveal different feedback loops or hidden interdependencies? |
| Narratives | What stories explain system behaviour, causation, and identity? | Dominant and alternative narratives about "how we work" | Systems identifies narratives that support status quo and block alternative designs. |
| Communications | How do information flows, signalling, and communication pathways shape system behaviour? | Information flow map; latency and fidelity issues; signal-to-noise | Systems identifies where communication delays or distortion create feedback lags. |
| Legitimacy | Why do people accept the system's authority and rules? What grants legitimacy? | Legitimacy basis; sources of contestation; buy-in distribution | Systems reveals where legitimacy is fragile (e.g., built on a Hidden) and where contestation threatens intervention. |
| Values | What values drive system design and operation? Where are values in tension? | Stated values vs observed behaviour; value conflicts | Systems asks: do incentive loops support espoused values? |
| Evidence | What evidence is available to sense, monitor, and validate system behaviour and claims? | Evidence inventory with provenance; observability constraints | Systems explicitly maps observability limits and how they hide behaviour. |
| Uncertainties | What is unknown or contested about the focal system, and what does that mean for decisions? | Uncertainty inventory; unknowns by component/loop/interface | Systems prioritises uncertainties by consequence. |
| Failures | What could go wrong—and how would systemic risks propagate differently than component risks? | Failure scenarios at system level; cascade pathways | Systems maps failure propagation via tight coupling, shared resources, and feedback amplification. |
| Hiddens | What visibility failures threaten system diagnosis? | Hiddens Register and detection/remediation moves; Tier 1/2 scan output | Systems pairs explicitly with Hiddens framework to identify where the map depends on fragile observability. |
| Diagnosis | What is the root cause of the focal problem, and how do system structure and dynamics explain it? | Root-cause hypotheses with system-level mechanisms | Systems provides structural diagnosis. |
| Decisions | What decisions are being made about the system, by whom, and under what constraints? | Decision inventory; decision rights; decision-making loops | Systems maps decision loops as part of the system. |
| Interventions | What interventions are proposed or in progress, and what are the likely system-level effects? | Intervention candidates; intended and unintended consequences | Systems stress-tests interventions for backfire risk. |
| Governance | How is the system overseen, controlled, and adapted over time? | Governance structure; control loops; oversight cadence | Systems asks: is governance fast enough for the system's tempo? |
| Risk | What residual risks remain, and how do systemic risks differ from component or event risks? | Risk register; system-level risk scenarios | Systems identifies systemic risks via amplification, coupling, and delayed discovery. |
| Learning and Adaptation | How does the system learn from experience and adapt its structure or rules? | Learning loops; feedback integration cadence; adaptation rate | Systems reveals whether learning loops address root causes or just tune parameters. |
| Metrics | What metrics are used to monitor system behaviour, and do they capture the right feedback loops? | Metric inventory mapped to system components and loops | Systems asks: do metrics track leverage points or merely symptoms? |
| Beliefs | What beliefs are operative here — how were they formed, how entrenched are they? | Shared mental models; espoused-operative divergences | Use Framework of Beliefs to surface identity-protective entrenchment and belief shift barriers before closing. |
| Knowledge | Where is knowledge embedded in system architecture? Which system components depend on tacit knowledge? | Knowledge-system dependency map | Embedded knowledge is invisible until system change reveals it. |

## 7.4 All 36 Frameworks in the Series (navigation reference)
| Framework | Primary group | Secondary group | Stage |
|---|---|---|---|
| Situations Context Classification | G1 | G5 | Upstream |
| Boundaries | G1 | G2 | Upstream |
| Dimensions | G1 | G5 | Upstream |
| Realities | G1 | G4 | Upstream |
| Scale | G1 | G2 | Upstream |
| Time | G1 | G2 | Upstream |
| Systems | G2 | G5 | Middle |
| Relations | G2 | G3 | Middle |
| Processes | G2 | G6 | Middle |
| Causation | G2 | G5 | Middle |
| Resources | G2 | G6 | Middle |
| Agents | G3 | G2 | Middle |
| Personas | G3 | G4 | Middle |
| Incentives | G3 | G6 | Middle |
| Power | G3 | G4 | Middle |
| Responsibility | G3 | G6 | Middle |
| Culture and Norms | G4 | G3 | Middle |
| Perspectives | G4 | G5 | Middle |
| Narratives | G4 | G6 | Middle |
| Communications | G4 | G5 | Middle |
| Legitimacy | G4 | G6 | Middle |
| Values | G4 | G6 | Middle |
| Beliefs | G5 | G4 | Middle |
| Evidence | G5 | — | Cross-cutting |
| Uncertainties | G5 | — | Cross-cutting |
| Failures | G5 | G2 | Cross-cutting |
| Hiddens | G5 | — | Cross-cutting |
| Diagnosis | G5 | G2 | Middle |
| Decisions | G6 | G5 | Downstream |
| Interventions | G6 | G2 | Downstream |
| Governance | G6 | G3 | Downstream |
| Risk | G6 | G5 | Downstream |
| Learning and Adaptation | G6 | G5 | Downstream |
| Metrics | G5 | G6 | Cross-cutting |
| Knowledge | G5 | G4 | Cross-cutting |
| Competencies | G3 | G2 | Middle |

---

# 8. Hiddens Source Analysis & Tiered Hiddens Cross-Check (mandatory)

This section pairs with **Framework of Hiddens v4.5** as the series-standard visibility audit layer.

## 8.1 Hiddens Source Analysis (framework-specific)
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---|---|---|---|
| 1 | Component Myopia | Focusing on parts in isolation rather than on interactions and feedbacks. | Map key feedback loops and flows; use whole-system diagrams; test changes for system-wide effects. |
| 2 | Boundary Mis-Specification | Drawing system boundaries too narrowly or too broadly, or ignoring their contestation. | Make boundary assumptions explicit; analyse multiple candidate boundaries; include perspectives of affected stakeholders. |
| 3 | Feedback Blindness | Ignoring slow, indirect, or intangible feedbacks (e.g., reputation, trust, environmental effects). | Trace causal chains over time; use stock–flow and feedback maps; include lagged and soft variables. |
| 4 | Static Snapshot Bias | Treating systems as if static, analysing only current structure rather than trajectories and path dependence. | Combine structural maps with temporal analysis; explicitly consider past trajectories and future scenarios. |
| 5 | Actor-Centric Reduction | Explaining outcomes solely by individual agents' intentions or competence, neglecting system structure. | Ask "what system properties made this behaviour likely?"; redesign structures, incentives, and information flows. |
| 6 | Feedback Blindness (Delay Variant) | Treating causal relations as linear and one-way; ignoring delays and second-order effects. | Explicitly map reinforcing/balancing loops; test interventions for delayed and cross-boundary effects. |
| 7 | Leverage-Point Illusion | Optimising parameters (targets, thresholds) while leaving structure and incentives unchanged. | Prioritise structural leverage points (interfaces, feedback loops, decision rights); align incentives and responsibilities. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)
| Hiddens meta-category (I–VI) | Why it may be active in systems analysis | Typical symptoms | Default checks to run |
|---|---|---|---|
| I  Perceptual | System behaviour emerges from interactions; local salience hides interaction effects. | Component myopia; "surprise" cascades. | Interaction mapping; near-miss sampling; fresh-eyes reviews. |
| II Systemic | Simplified models and aggregated metrics fabricate stability or single-cause narratives. | Coherent wrong explanations; repeated backfires. | Model audits; disaggregation; regime-shift tests. |
| III Informational | Evidence is fragmented across subsystems and stakeholders; interfaces hide truth. | Conflicting accounts; missing interface data. | End-to-end tracing; interface audits; evidence provenance. |
| IV Temporal | Delays, drift, and path dependence make system constraints invisible until late. | Late discovery; repeat failures; "we already learned this." | Delay mapping; drift indicators; system archaeology. |
| V  Relational | Power and position determine which subsystem is visible and which narrative wins. | Scapegoating; capture; "out of scope" blame. | Multi-level inquiry; protected dissent; power–duty alignment checks. |
| VI Ontological | New system forms (hybrids, ecosystems) create failure modes with no category/owner. | Persistent anomalies; category disputes. | Category-creation workshop; external analogies; robustness planning. |

## 8.3 Hiddens Crosswalk: Tier 2 Shortlist (recommended mapping layer)
| Hidden type | Relevance | Mechanism | Detectability | Agency | Consequence | Detection interface(s) | Remediation interface(s) | Interaction notes |
|---|---|---|---|---|---|---|---|---|
| 8 Framing | H | Boundary and purpose framing selects what counts as system vs environment; creates ownerless externalities. | Medium | Mixed | High | 'What's out of frame?' review; stakeholder inclusion | Reframe and expand boundaries; assign ownership for externalities | Framing drives Boundary Mis-Specification |
| 9 Aggregation | M–H | Averaging across components/levels hides bottlenecks, hotspots, and tail-risk behaviour. | High | Structural | High | Disaggregate by subsystem, time, and scale; tail analysis | Multi-resolution dashboards; threshold monitoring | Aggregation masks cross-scale dynamics |
| 10 Model Blindness | H | System model omits key variables, loops, or constraints; produces coherent but wrong interventions. | Medium | Mixed | High | Red-team models; counterexample search; validation | Update system model; broaden variables; incorporate feedback | Model blindness + incentives → Fixes that Fail |
| 14 Fragmentation | H | The system is split across silos; no end-to-end view of interfaces and propagation exists. | High | Structural | High | End-to-end tracing; interface audits; cross-silo mapping | Assign interface owners; standardise interfaces | Fragmentation amplifies cascade risk |
| 15 Latency | M–H | Delays between cause–effect and signal–response create surprises and misattribution. | Medium | Structural | High | Lag audits; escalation-path tests; delay mapping | Shorten loops; early warning indicators | Latency increases oscillation |
| 6 Distortion | M–H | Measurement and KPI design distorts system reality; encourages local optimisation. | Medium | Structural | High | Metric audits; alternative measures; ground-truth sampling | Redesign metrics; align incentives; include system-level outcomes | Distortion supports Mirage |
| 7 Mirage | M | A stabilised illusion of performance or control supported by reporting and incentives. | Low–Medium | Mixed | High | Independent audits; adversarial testing; 'can it actually fail?' drills | Decouple incentives; strengthen assurance; transparency governance | Mirage delays structural fixes |
| 17 Ghost | M | Legacy constraints and past commitments shape present system behaviour and feasible interventions. | Medium | Structural | Medium–High | System archaeology; dependency mapping; history audit | Modernisation plan; unlearning; option recovery | Ghost constraints produce path dependence |
| 21 Positional | M–H | Different positions see different subsystems; system-level behaviour is not equally visible. | Medium | Structural | High | Multi-level inquiry; frontline sampling; observer rotation | Embed plural perspectives; safe reporting; two-key reviews | Positional invisibility drives component myopia |
| 25 Perspectival | M | Single interpretive lens collapses system plurality. | Medium | Structural | Medium–High | Perspective rotation; cross-disciplinary review | Multi-lens governance; explicit trade-offs | Perspectival lock-in sustains wrong leverage |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)
1) Run Tier 1 scan across all six Hiddens meta-categories (assume hiddens exist).
2) Shortlist relevant Hidden types (Tier 2) and rate detectability, agency, and consequence.
3) Assign at least one detection and one remediation move per high-consequence hidden; map interaction chains (e.g., Fragmentation → Latency → Mirage → Fixes that Fail).
4) Re-run systems hiddens source analysis and document residual unknowns.

## 8.5 Escalation Rule (Tier 3 – full Hiddens run)
Escalate to a full 30-type Hiddens scan + detection/remediation matrix mapping if any apply:
- High consequence (safety, systemic resilience, regulatory exposure)
- Strong incentives to conceal, to perform compliance, or to preserve a preferred narrative
- Persistent disputes about system boundaries, interfaces, and responsibility
- Repeat failures despite multiple prior redesign attempts
- Evidence of cascades (e.g., Aggregation → Distortion → Mirage → Fixes that Fail)

---

# 9. Framework Application Protocol (mandatory)

## 9.1 Application Steps Table
| Step # | Step name | Action | Outputs / artefacts |
|---|---|---|---|
| 1 | System Framing & Boundary Choice | What is the focal system, and where do we draw provisional boundaries? — Define purpose of analysis; identify primary functions; sketch candidate boundaries; clarify environment and stakeholders. | System statement; boundary assumptions; stakeholder/environment map; initial system type shortlist. |
| 2 | Structure & Flow Mapping | What are the key components, relations, and flows? — Map components, subsystems, and networks; identify stocks, flows, and interfaces; note inputs, transformations, and outputs. | Structure map (components, subsystems, topology); flow map (stocks/flows); interface inventory. |
| 3 | Dynamics & Feedback Analysis | What feedback loops, delays, and nonlinearities drive behaviour over time? — Identify reinforcing and balancing loops; locate delays and thresholds; sketch causal loop or stock–flow diagrams. | Feedback map (loops, delays, thresholds); dominant-loop by regime notes; hypothesis list. |
| 4 | System Typing & Dimensional Characterisation | Which system types and dimensions best describe this system? — Classify the system under relevant meta-categories and types; rate it along the five dimensions. | Dimension profiles (5); observability/controllability constraints; coupling/cascade risk notes. |
| 5 | Archetype, Risk & Hiddens Source Analysis | Which archetypes, risks, and blindspots are present or emerging? — Look for canonical archetypes; scan for systemic risks; test for hiddens sources. | Archetype match (if any); leverage-point shortlist; risk/failure propagation map. |
| 6 | Leverage & Intervention Design | Where are the structurally powerful leverage points for change? — Identify parameters, feedbacks, information flows, rules, and paradigms that can be shifted; link options to Resources, Power, Incentives, Time, and Risk frameworks. | Action plan: interventions + monitoring; governance/ownership changes; learning loop and review cadence. |

## 9.2 Standard Deliverables (recommended)
- **Minimum deliverable (1–2 pages)**:
  - System statement and boundary assumptions
  - System type classification (top active types)
  - Key structure/flow/feedback maps (1–2 diagrams) and dimension profile
  - Archetype match (if any) and leverage-point shortlist (3–5)
  - Hiddens shortlist (8–12) with detection/remediation moves
  - Intervention and monitoring plan (owners + cadence)

- **Full deliverable pack**:
  - Interface ownership model and governance changes
  - Cross-scale coupling analysis (fast/slow layers) with thresholds and delays
  - System-of-systems cascade map and resilience plan
  - Learning loop design (post-mortems, playbook updates, model calibration)

### Canonical shared registers (Operating Guide aligned; mandatory for LLM use)
| Shared register / artefact | Required | Notes (how this framework contributes) |
|---|---:|---|
| Group Coverage Matrix (G1–G6) | Yes | Record which groups were examined at Full Depth vs Light Depth; note gaps. For Systems: typically primary coverage in G2 (structure/mechanism); partial coverage in G5 (observability/evidence integrity). |
| Hiddens Register | Yes | Populate candidate Hiddens relevant to system-level visibility: feedback blindness, latency, fragmentation, mirage, boundary mis-specification, model blindness. Include probes/tests and remediation levers. |
| Evidence Ledger | Yes | Track key claims about system structure, feedback loops, delays, and coupling. Record evidence quality and gaps; prioritise testing delays and cross-scale feedback. |
| Hypothesis/Test Backlog | Yes | Convert system-level Unknowns into testable probes: hypothesis about feedback loop dominance, coupling strength, lag length, threshold location, etc. |
| Residual Unknowns + Closure note | Yes | State what remains hidden about the system, why it is hidden, and what it would take to surface it. Include escalation recommendation if systemic risks or governance gaps depend on these unknowns. |
| Investigation Plan (post-failure) | Conditional | Required when failure occurred, cascade was observed, or harm potential is high. Maps investigation to system-level mechanisms. |
| Decision/Action Record (if recommending changes) | Conditional | Required when proposing interventions, governance redesign, or monitoring setup. Records what system-level changes are being targeted, why they are expected to work, and what feedback/delays make success harder. |

---

# 10. Framework Principles (mandatory)

## 10.1 Principles Table
| Principle name | Description |
|---|---|
| Boundaries are choices with consequences | Always make boundary assumptions explicit and contestable; many failures are boundary failures (externalities, handoffs, responsibility gaps). |
| Feedback and delays dominate behaviour | Model reinforcing/balancing loops, delays, and thresholds; avoid linear explanations for non-linear systems. |
| Structure creates behaviour | Prefer structural interventions (interfaces, decision rights, incentives, information flows) over repeated parameter tuning and symptomatic fixes. |
| Work across scales and regimes | Analyse micro/meso/macro interactions and regime shifts; what works at one scale can fail at another. |
| Assume Hiddens exist | Use the tiered Hiddens scan to identify likely invisibilities (fragmentation, latency, distortion, mirage) and assign detection/remediation moves. |

---

# 11. Glossary (local domain terms)

## 11.1 Local domain glossary
| Term | Definition |
|---|---|
| System | A set of interacting elements organised by structure, relations, and feedbacks, forming a coherent whole with boundaries, inputs, outputs, and characteristic behaviour over time. |
| Subsystem | A component or subset of a system that can itself be analysed as a system with its own boundaries, inputs, outputs, and feedbacks. |
| Environment | Everything outside the system boundary that interacts with the system via inputs, outputs, disturbances, or constraints. |
| Boundary | The conceptual or physical line that distinguishes what is considered inside the system from what is outside for the purpose of analysis or design. |
| Input | Matter, energy, information, or influence entering the system from its environment. |
| Output | Matter, energy, information, or influence leaving the system into its environment. |
| Stock | An accumulation within the system (e.g., inventory, population, capital, trust) that changes over time through inflows and outflows. |
| Flow | A rate of change to a stock (e.g., production rate, birth rate, spending rate). |
| Feedback Loop | A closed causal chain where changes in a variable eventually influence that same variable, either dampening (balancing) or amplifying (reinforcing) the original change. |
| Balancing (Negative) Feedback | Feedback that counteracts deviations from a reference, tending to stabilise a variable or maintain homeostasis. |
| Reinforcing (Positive) Feedback | Feedback that amplifies deviations, leading to growth, decline, or divergence. |
| Homeostasis | The tendency of a system to maintain internal variables within certain ranges despite external or internal disturbances. |
| Emergence | System-level properties or behaviours that arise from interactions of components and are not reducible to properties of individual parts taken in isolation. |
| Self-Organisation | Process by which system structure or patterns arise spontaneously from local interactions, without central control or external design. |
| System Archetype | Recurrent configuration of structure and feedback (often including delays) that produces characteristic patterns of behaviour across many domains. |
| System-of-Systems | A configuration in which multiple distinct systems, each useful on its own, are integrated to provide additional or higher-level capabilities. |
| Meta-System | A higher-order system that monitors, governs, coordinates, or constrains other systems. |
| Coupling | Degree and character of interdependence between system components or subsystems; how strongly and quickly changes in one propagate to others. |
| Open System | System whose boundary is permeable to exchanges with its environment and whose viability depends on such exchanges. |
| Closed System | Idealised system with no exchanges across its boundary; in practice, a model that abstracts away environmental interactions for analytical convenience. |
| Observability | The extent to which a system's internal state can be inferred from available measurements or outputs. |
| Controllability | The extent to which a system's state can be steered to desired conditions through available inputs or interventions. |

## 11.2 Core execution terms (pointer; do not restate)
- See **Analytical Series Operating Guide**, v2.5, Appendix D **§D.10.1**.

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v2.0 | 2026-04-06 | Rewrite for v2.0 alignment with Master Template v2.3. Updated all OG references from v1.4/v1.5 to v2.5. Expanded §1.6 with full LLM integration specification, canonical Prompt Discipline Rules pointers (PD-01–PD-10), standard registers, and run prompts. Added Introduction section with four subsections (What is Systems, Why it matters for Hiddens, What it produces, How to use it). Updated §7.3 with all 36 canonical frameworks and Group/Stage assignments. Expanded §8 with Tier 2 Hiddens crosswalk mapping 10 key Hiddens (8, 9, 10, 14, 15, 6, 7, 17, 21, 25) to detection/remediation interfaces and interaction notes. Comprehensive dynamics section with 5 archetypes and full descriptions. All substantive content from v1.2 preserved and restructured to new template. Revised: Anthropic Claude Opus 4.6. |
| v1.2 | 2026-03-27 | Added §7.3 integration entry for Framework of Beliefs; series count updated from 32 to 33 frameworks. (Revised: Anthropic Claude Sonnet 4.6) |
| v1.1 | 2025-12-17 | Aligned to Master Rewrite Template v2 by adding Assumptions & Preconditions and series-position/crosswalk summary; updated Hiddens references to align with Hiddens v4.5; no taxonomy changes. |
| v1.0 | 2025-12-14 | Standardised rewrite to master template; added interface-type table; expanded Hiddens Source Analysis section; enriched type diagnostic cues and hidden-risk signatures; added principles and integration crosswalk; made application outputs explicit. |
| v0.1 | 2025-12-09 | Source draft created (meta-categories, 30 types, dimensions, archetypes, cross-framework links, blindspots, protocol, glossary). |

## 12.2 Integration Notes (optional)
Use this framework whenever:
- failures recur despite "fixes,"
- coordination across components or organisations is central,
- boundaries and interfaces are disputed,
- behaviour is non-linear (thresholds, oscillations, cascades),
- governance appears outpaced by operational tempo.

Treat Section 8 (Hiddens cross-check) as mandatory in high-stakes contexts and wherever models and metrics may be hiding systemic behaviour.

---

## Appendix A: Cross-Framework Link Prompts (source reference)
| Interface Target | Key Questions from a Systems View |
|---|---|
| Realities | Which realities (grounding, social-institutional, normative, modal, process) are instantiated within the system and at its boundaries? |
| Dimensions | At which dimensional tiers (physical, biological, cognitive, social, symbolic) does the system operate, and how do tiers interact? |
| Relations | What are the key relations (flows, dependencies, influences) between system components and between the system and its environment? |
| Processes | What core processes run inside the system, with what start/stop conditions, tempos, and failure modes? |
| Boundaries | Where are the system boundaries physically, conceptually, socially, legally, and temporally — and how sharp, permeable, and contested are they? |
| Agents | Which agents participate in or are embedded in the system, with what roles, capacities, and incentives? |
| Power & Legitimacy | Who can change system structure, rules, or parameters, by what right, and with what constraints? |
| Incentives | What incentive structures shape behaviour inside the system and at its interfaces, and how do they align or misalign with system-level goals? |
| Time & Scale | At what temporal and spatial scales does the system operate, and where are the critical thresholds, lags, and scaling limits? |
