# Framework of Scale
*A Comprehensive Taxonomy for Understanding How Size, Reach, Complexity, and Non-Linear Scale Effects Shape Systems, Risk, and Intervention Design*

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
- Group (Primary): G1 — Framing & scope-setting (Framing)
- Group (Secondary): G2 — Structure, dependencies & mechanism (Mechanism)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, scale transition is imminent, or non-linearity could alter decisions
- Owner / Maintainer: Series Maintainer
- Intended Use: Diagnosis; risk analysis; architecture/operating-model design; governance and policy design; transformation/change; capacity planning; incident prevention; intervention design and evaluation
- Primary Audience: Executives; transformation leaders; architects/engineers; operations leaders; risk/compliance; auditors/investigators; analysts; policy designers
- Dependencies / Key Inputs: Situation framing; evidence set; system/boundary map; resource and capacity data; governance/decision rights; incentives; time horizons/cadence; stakeholder/ecosystem map
- Primary Outputs: Scale characterisation across six meta-categories; identification of thresholds, regimes, and non-linear effects; scale-appropriate governance and intervention design; Hiddens register capturing scale-driven visibility failures; integration with Governance, Decisions, Interventions frameworks
- Change Log (brief): Rewrite for v2.0 alignment with Master Template v2.3; updated all OG references from v1.4 to v2.5; expanded §1.6 with Tier 2 Hiddens crosswalk, Targeted Scans routing, and full Information Requests schema; added Introduction section (four subsections); updated §7 with all 36 canonical frameworks and Group/Stage columns; expanded §8 with Targeted Scans family matrix and Tier 2 routing logic; updated §11 with OG v2.5 pointer; added §12 version history entry for v2.0.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **How does this system change—in structure, cost, risk, and capability—as it grows; where are the critical thresholds and regime shifts; and what governance, architecture, and intervention choices fit this scale?** |
| Addresses | Scale blindness (ignoring non-linear effects); regime assumption failures (treating scale transitions as continuous); aggregation bias (tails hidden in averages); scale mismatch in governance and coordination design; underestimation of coordination overhead and complexity. |
| Gap Filled | The Framework of Dimensions clarifies *levels* of analysis; this framework clarifies *size dynamics* and scale-dependent non-linearities that change what is possible, safe, and governed at each scale. Scale awareness enables appropriate intervention design, risk management, and governance alignment. |
| Complements | Situations (scale determines response mode); Systems (scale affects structural coupling and feedback); Evidence (aggregation bias); Hiddens (scale-driven visibility failures); Governance (who governs at which scale); Interventions (scale-appropriate design); Risk (scale concentration and tail risk). |
| Key Characteristics | Six meta-categories; thirty core types; five cross-cutting dimensions; explicit threshold and regime-transition mapping; non-linear dynamics and effects modelling; integration with Hiddens as a mandatory cross-check. |
| Main Contributions | Standardised scale-effects taxonomy; visibility of thresholds and regime shifts; scale-aware governance model; detection of scale-driven failures and misalignments; interconnection with the 36-framework series to prevent single-scale closure. |

---

# Introduction

## What is Scale and Scale Effects?

Scale is not merely "size"—it is a multi-dimensional property that determines how systems change as they grow. When an organisation doubles in headcount, the number of possible pairwise interactions increases four-fold. When a regional operation goes national, regulatory complexity multiplies. When load approaches capacity, performance becomes non-linear and brittle. These are not incidental; they are fundamental scale effects that determine whether an intervention that worked at one scale fails catastrophically at another.

This framework defines scale across six complementary dimensions: absolute magnitude and capacity; geographic and population reach; structural complexity and coupling density; returns-to-scale and performance curves; thresholds and regime transitions; and scalability and modularity. It makes these effects explicit and traceable so that decision-makers, architects, and risk managers can ask: "What changes as we grow? Where are the dangerous thresholds? What governance, design, and monitoring fit this scale?"

Scale matters because most significant failures involve a scale mismatch: applying routine procedures to a crisis (scale in consequence but treating as normal); deploying centralised governance when distributed autonomy is needed; designing for average cases and ignoring tail events; assuming linear relationships when thresholds exist. By making scale explicit, this framework helps prevent these misalignments.

## Why does Scale matter for Hiddens work?

Scale failures are themselves Hiddens—visibility failures caused by identifiable mechanisms. Several families of hiding mechanisms operate at the scale level:

**Aggregation bias** masks tails in averages. An organisation's average customer-satisfaction score is "acceptable," yet 10% of customers experience catastrophic failure. A supply chain's mean lead time is stable, yet tail volatility is increasing. These hidden tails dominate risk and legitimacy.

**Regime blindness** occurs when scale transitions are treated as continuous. A system is stable at 80% capacity utilisation, but at 95% utilisation, it switches to a chaotic regime. Decision-makers assuming linearity miss the threshold and remain unprepared.

**Coordination opacity** emerges as scale increases. At ten people, communication is transparent. At one hundred, hidden silos and rework loops become systemic. The coordination burden becomes invisible until it causes cascades.

**Complexity creep** hides growing coupling and fragility. Systems that were understandable at one scale become opaque at the next. Hidden dependencies propagate failures at scale.

**Non-linear threshold effects** (part of Temporal Hiddens and Threshold Hiddens) fail to be detected because linear models dominate planning. A tipping point arrives unrecognised until it materialises as crisis.

This framework surfaces these Hiddens by making scale mechanisms explicit and operationalising their detection through the tiered Hiddens scan (Tier 1 aggregate health / Tier 2 scale-specific mechanisms / Tier 3 detailed threshold mapping).

## What does this framework produce?

The framework operationalises scale analysis through six core elements:

1. **A taxonomy of 30 scale types** organised into six meta-categories (Magnitude; Scope; Structural Complexity; Returns-to-Scale; Thresholds & Regimes; Scalability & Modularity) that recur across contexts.

2. **Five cross-cutting scale dimensions** (Absolute Magnitude, Geographic/Population Reach, Structural Coupling, Cost/Performance Curves, Threshold Sensitivity) that profile how a system evolves as it scales.

3. **Dynamics patterns** (escalation through thresholds, saturation and collapse, regime transitions, learning curves, critical mass effects) that describe how systems change qualitatively as scale increases.

4. **Threshold and regime mapping** that makes explicit where critical thresholds lie, how to detect approach, and what leading indicators signal regime transition.

5. **Hiddens source analysis and tiered Hiddens scans** that surface the four systematic sources of scale-driven visibility failure (aggregation, threshold blindness, coordination opacity, complexity opaqueness) and the six categories of scale-driven visibility failure (perceptual, systemic, informational, temporal, relational, structural).

6. **A scale-appropriate governance protocol** that moves from scale characterisation through threshold identification, regime mapping, scale-matched governance design, and integration into decision and intervention workflows.

The framework populates standard registers (Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests) that integrate with the broader Analytical Series investigation workflow. It is designed for repeated use: scale position is assessed, decisions are made, and scale is monitored at scheduled intervals or triggered by threshold approach, allowing the analysis to track evolution in real time.

## How to use this framework

Invoke this framework early when designing systems, interventions, or governance structures for scale; during transitions to new scale regimes (geographic expansion, headcount changes, capacity planning); when investigating why an intervention that worked at one scale fails at another; or as a mandatory component of post-failure work where scale mismatch is suspected.

The framework works in both Rapid Run Mode (quick scale characterisation, obvious threshold spotting, regime-mismatch checking) and Investigative Run Mode (detailed threshold mapping, non-linear effects modelling, multi-scale governance design). Default execution is Light Depth Framework Execution: assign scale types, profile absolute magnitude and reach, identify obvious thresholds, run Tier 1 Hiddens scan. Escalate to Full Depth when consequence is high, evidence is weak/contested, scale transition is imminent, or non-linearity could change decisions (e.g., capital allocation, governance structure, risk tolerance).

For LLM execution, see §1.6 for the complete LLM integration specification, standard registers, and copy-ready run prompts. The framework is designed to be directly executable by an LLM given a scenario and the Operating Guide, producing disciplined scale analysis with explicit Hiddens, F/I/A/U tagging, and bounded closure.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Scale is a fundamental property that determines how systems change as they grow. A system that is safe at 1,000 units may be catastrophically fragile at 10,000. An architecture that works in one geographic region may create governance nightmares at global scale. An intervention that succeeds with a pilot team may fail in an organisation-wide rollout because coordination overhead becomes diseconomy.

This framework provides a systematic approach to:
- characterise the current scale position across six complementary dimensions (magnitude, reach, complexity, effects, thresholds, scalability),
- identify critical thresholds and regime transition points where behaviour changes qualitatively,
- map scale-dependent non-linearities (economies and diseconomies, network effects, congestion, tipping points),
- diagnose scale-mismatch failures (applying wrong governance, ignoring thresholds, overlooking coordination burden),
- design scale-appropriate interventions, governance structures, and monitoring regimes, and
- scan for scale-driven Hiddens (aggregation bias, regime blindness, coordination opacity, complexity creep, threshold invisibility).

The framework integrates with the Analytical Series' central concern with visibility failures: scale effects are often hidden—in averages, in regime assumptions, in coordination burdens that remain invisible until they cause cascades. By making scale mechanisms explicit and operationalising their detection, the framework enables decision-makers to see what matters before scale mismatch causes failure.

## 1.2 Assumptions & Preconditions

### Assumptions Register (recommended)
| Assumption | Type (method / structural / domain / normative) | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Scale can be measured and tracked across multiple dimensions simultaneously | Domain / method | Single-dimensional views dominate; blind spots in other dimensions cause misalignment. | Run multi-dimensional scale profile; compare across teams/business units; track divergence. | Adopt a single dominant dimension as proxy; escalate when proxy diverges from others; add qualitative assessment. |
| Thresholds and regime transitions are identifiable and can be predicted (or at least detected early) | Domain / method | Organisations cross thresholds unprepared; surprises dominate; response is reactive rather than anticipatory. | Historical data on threshold crossing; leading indicators; stress testing; regime-specific metrics. | Shorten monitoring cadence; use conservative buffer thresholds; escalate on pattern changes; accept reactive response. |
| Scale effects are largely consistent across domains (e.g., governance challenges scale similarly in hospitals and tech companies) | Domain / structural | Framework loses transferability; each domain requires bespoke knowledge. | Test taxonomy on 3+ diverse domains; assess consistency of high-order patterns. | Create domain-specific scale curves and threshold tables; map to canonical types; note domain caveats. |
| Non-linear effects matter enough to warrant explicit modelling (i.e., linear approximations often mislead) | Domain / normative | Organisations ignore threshold risks and operate near brittle regimes; cascade failures surprise. | Correlate scale parameter changes to outcome changes; test linearity assumption; model non-linear scenarios. | Adopt linear models for stability/trend but flag tail risks separately; heighten alert thresholds near suspected regimes. |
| Scale misalignment (e.g., centralised governance at distributed scale) is a material root cause of failure | Structural / domain | Scale awareness provides no operational leverage; framework becomes academic exercise. | Post-failure reviews: diagnose whether scale mismatch was present; assess causal contribution; test intervention. | Treat scale analysis as complementary rather than primary; combine with Agency, Governance, Incentives frameworks. |
| Scalability and modularity are engineering/architectural choices that have observable consequences | Structural / domain | Scalability becomes a nice-to-have rather than a determinant of success at scale. | Design reviews: assess modularity, coupling, elasticity; correlate to actual scaling outcomes; track rework. | Build scalability into non-functional requirements; make architecture reviews mandatory pre-scale; establish monitoring. |

### Preconditions Checklist (recommended)
| Precondition | Required? (Y/N) | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Focal scale concern is defined (what is scaling, what are the fear dimensions?) | Y | Scale concern statement; list of dimensions in scope. | Analyst/programme owner | Confirm scope with stakeholders; check that all relevant dimensions are included. | Work with "most salient dimension" assumption; flag other dimensions as residual unknowns. |
| Current scale position is known (magnitude, reach, complexity, regime estimate) | Y | Scale snapshot table; data sources; confidence levels. | Analyst; data custodian | Verify via multiple sources (headcount data, transaction logs, geographic presence); mark confidence. | Build a scale hypothesis table; collect data proactively; note inference risk. |
| Scale history/trajectory is available (how did we get here, at what pace?) | Y | Timeline of scale changes; growth rate curves; inflection points. | Analyst; historical records | Reconstruct from financial/operational data; interview long-serving staff; look for phase changes. | Use current position as baseline; assume linear extrapolation; be conservative about future thresholds. |
| Known thresholds or regime transitions (from domain knowledge, design specs, or prior incidents) are listed | Y | Threshold register; design margins; incident reports; vendor specs. | Analyst; domain expert; risk owner | Validate thresholds against evidence; stress-test margin assumptions; test whether they hold at other scales. | Start with conservative estimates; use industry benchmarks; escalate uncertainty in Unknowns register. |
| Governance and decision rights by scale are defined (who decides at what scale?) | Y | Governance-by-scale map; decision authority matrix; escalation paths. | Analyst; governance owner | Test against org chart; validate with decision-makers; check for gaps/overlaps. | Use implicit hierarchy as proxy; escalate governance misalignments as Unknowns. |
| Re-assessment cadence for scale position is pre-agreed (monitoring triggers, review intervals) | Y | Scale monitoring plan; triggering conditions; review schedule. | Analyst; operations owner | Check alignment with business rhythm (budgets, plans, milestones); validate feasibility. | Default to quarterly reviews; add event-triggered re-assessment; build into governance cycle. |

## 1.3 Definitions, Scope, and Non-Goals
- **Scale**: A multi-dimensional property describing how a system changes as it grows across magnitude, reach, complexity, effects, thresholds, and scalability.
- **Scale effect**: A change in cost, performance, risk, or behaviour that is caused by growing size, reach, or complexity—including non-linear and threshold effects.
- **Regime**: A qualitative operational mode (e.g., linear/stable, threshold-approaching, chaotic, saturation, critical-mass, tail-risk-dominated) associated with a scale range.
- **Threshold**: A point or range of scale at which behaviour changes qualitatively (e.g., loss of transparency, shift to cascade risk, onset of saturation, achievement of critical mass).
- **In scope**:
  - Six meta-categories and thirty core scale types
  - Five cross-cutting dimensions of scale
  - Dynamics and threshold patterns
  - Scale-appropriate governance design
  - Hiddens source analysis + tiered Hiddens cross-check
  - Integration with 36-framework series
- **Out of scope**:
  - Domain-specific engineering (e.g., capacity calculations, performance modelling) except where they feed scale type identification
  - Full governance/decision design (use Governance and Decisions frameworks)
  - Full intervention/capability design (use Interventions framework)

## 1.4 Position in the Series (Upstream / Middle / Downstream)
- **Upstream**: Situations (scale affects response mode); Systems & Boundaries (scale determines structural properties); Evidence (aggregation bias); Resources (capacity and constraints at scale)
- **Middle (this framework's role)**: Make scale explicit; identify thresholds/regimes; diagnose scale mismatch and aggregation failures; integrate scale awareness into governance and intervention design
- **Downstream**: Governance (scale-appropriate structure); Decisions (scale-aware decision rights); Interventions (scale-matched design); Risk (scale concentration); Monitoring & Controls (threshold tracking)

- **Group assignment (Primary)**: G1 — Framing & scope-setting (Framing)
- **Group assignment (Secondary)**: G2 — Structure, dependencies & mechanism (Mechanism)
- **Stage assignment**: Upstream (see OG v2.5 §3.1)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.9.2 Mode Selection Gate)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
- **Framework Index**: this framework is one of 36 in the series (see OG v2.5 §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary (recommended)
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|---|
| Descriptive | Systems; Boundaries; Resources; Dimensions; Time | What exists and at what levels; constraints and capacity; temporal horizons | What changes when size changes; where limits and thresholds are; what non-linear effects emerge; scale-appropriate governance |
| Epistemic | Evidence; Diagnosis; Causation; Hiddens | What is supported and what is missing; mechanisms and root causes; visibility failures | Whether measurement/reporting is at the right scale; what is hidden by aggregation; whether thresholds are being monitored; scale-driven blindness |
| Normative | Governance; Values; Legitimacy; Responsibility; Culture | Rights, duties, and legitimacy; norms and meaning-making | Which governance structures and decision rights fit which scale regime; how scale mismatch creates coordination failures |
| Action | Decisions; Interventions; Incentives; Power; Learning | Action levers, pacing, and dependencies; change patterns | Which interventions are scale-appropriate; which create scale drift or regime shifts; how to monitor for threshold approach; scale-aware feedback loops |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Scale_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Scale when… | Use neighbour instead when… |
|---|---|---|
| Dimensions | Analysing a system's multi-level structure and component inventory (units, layers, entities). | Analysing *how much changes* when scale shifts; tracking non-linear effects on cost/risk/performance; identifying thresholds and regime transitions; diagnosing scale mismatch in governance. |
| Systems | Analysing structure, coupling, and feedback loops within or across system boundaries. | Analysing *how size changes the dynamics*; how magnitude, reach, or complexity alter what feedback loops emerge; where coordination burden becomes pathological; scale-appropriate architecture choices. |
| Resources | Analysing capacity, scarcity, constraint, and allocation independent of scale. | Analysing *how much capacity is available relative to demand*; headroom and utilisation; thresholds where saturation triggers non-linear degradation; economies/diseconomies of scale; scale-dependent bottlenecks. |
| Governance | Analysing authority, decision rights, accountability, and institutional design independent of scale. | Analysing *which governance structures fit which scale regime*; how centralised vs. distributed authority changes as scale shifts; escalation paths and decision latency; scale-driven misalignment (wrong structure for current size). |
| Situations | Analysing the context, urgency, stakeholder interests, and response mode to a problem. | Analysing *how response mode changes with scale*; whether current governance, intervention, or monitoring cadence is matched to the scale regime; whether time horizons fit the timescale of threshold approach. |

### 1.6.3 Routing triggers
- Scenario involves headcount, volume, geographic, functional, or jurisdictional expansion
- Non-linear cost, performance, or risk curves are observed or suspected
- Current scale is approaching a known threshold (capacity, regulatory, coordination, modularity)
- An intervention that worked at one scale fails at another; scale mismatch is suspected
- Governance structure, decision rights, or monitoring cadence appear mismatched to current scale
- Aggregation in reporting hides tails, outliers, or regime-specific failure modes
- Coordination burden, rework loops, or decision latency has increased unexpectedly
- Scaling runway or architectural/modularity limits are unclear
- Organisational redesign is planned; scaling implication needs testing
- Threshold crossing or regime transition is being predicted or managed

# 2. Meta-Categories of Scale

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Magnitude & Capacity Scale | How big is this in absolute terms, and how much can it process, carry, or affect? | Absolute size, throughput ceilings, utilisation, severity magnitude, exposure-at-risk. | Capacity model; utilisation ratios; severity bands; exposure/VaR; load tests; headroom analysis |
| II | Scope & Reach Scale | How wide is the footprint of this system, across places, populations, functions, and jurisdictions? | Spatial footprint, population reach, functional span, regulatory/jurisdictional reach, time horizon, ecosystem dependencies. | Footprint map; boundary/jurisdiction matrix; scope statement; population coverage; horizon definition; dependency graph |
| III | Structural Complexity & Density Scale | How complex and densely connected is this as it scales, and what coordination burdens does that create? | Component counts, interaction density, layering, heterogeneity, coordination/information overhead, coupling patterns. | Architecture/dependency graph; interaction map; heterogeneity inventory; coordination burden metrics; coupling analysis |
| IV | Returns-to-Scale & Scale Effects | What happens to cost, performance, risk, and legitimacy when we change scale? | Economies/diseconomies, network effects, congestion, saturation, spillovers/externalities, learning curves, winner-takes-most dynamics. | Unit cost curves; latency/throughput curves; network metrics; externality register; performance envelope; tail-risk profile |
| V | Thresholds, Regimes & Non-Linear Scale | Where are the scale thresholds at which behaviour changes qualitatively, and what regimes exist? | Minimum viable scale, critical mass, tipping points, phase transitions, safety thresholds, catastrophe/tail regimes, regime boundaries. | Threshold register; regime map; stress scenarios; leading indicators; phase diagrams; tail-risk model; sensitivity analysis |
| VI | Scalability, Modularity & Replicability | How easily can this be scaled or replicated, and what architectural choices enable or constrain scaling? | Upward/downward scaling, modular replication, elasticity, coupling reduction, portability, design margins, architectural decisions. | Scaling runbooks; modular interface standards; elasticity policies; portability checklist; architectural review notes; design constraint matrix |

## 2.2 Meta-Category Descriptions (recommended)
### I. Magnitude & Capacity Scale
Absolute size, throughput ceilings, utilisation, severity magnitude, and exposure-at-risk. Captures "how much is there" and "how full is it relative to limits". Helps identify when systems operate near saturation, where headroom exists, and where severity escalates.

### II. Scope & Reach Scale
How widely the system extends across geography, populations, functions, time horizons, and regulatory jurisdictions. Determines logistical complexity, compliance burden, exposure to localised constraints, and ecosystem interdependence. At broader scope, complexity and coordination burden typically grow non-linearly.

### III. Structural Complexity & Density Scale
How component count, coupling, layering, and heterogeneity increase coordination burdens and failure propagation as scale grows. Dense coupling enables functionality but propagates failures. Hierarchy helps manage complexity but increases latency and opacity. High heterogeneity increases resilience but integration overhead.

### IV. Returns-to-Scale & Scale Effects
How costs, performance, risk, and legitimacy change with scale through economies/diseconomies, network effects, congestion, and spillovers. Helps diagnose whether "bigger is better" or where diseconomies dominate. Network effects can create winner-takes-most dynamics; congestion creates non-linear degradation.

### V. Thresholds, Regimes & Non-Linear Scale
Where critical mass, tipping points, and regime shifts cause qualitative behaviour change. Includes tails and catastrophic modes where rare events dominate risk. Essential for identifying dangerous thresholds and understanding when linear models fail.

### VI. Scalability, Modularity & Replicability
How easily the system can be scaled up/down, replicated as units, adjusted elastically, and transferred across contexts. Reflects design choices (modularity, loose coupling, standardised interfaces) that enable or constrain future scaling. Influences whether scale transitions are gradual or abrupt.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- Canonical baseline: 6 meta-categories × 5 types = 30 core types.
- This framework: 30 types (canonical).
- Mapping back to baseline: Not required.

## 3.1 Types (Category I: Magnitude & Capacity Scale)
| # | Type | Description (1–3 sentences) | Diagnostic cues (optional) | Failure / hidden-risk signature (optional) |
|---|---|---|---|---|
| 1 | Volume / Quantity Scale | Total number of units, transactions, entities, or items involved (e.g., customers, messages, devices, assets). Captures absolute count and growth rate. | Track counts and growth rate; compare to baseline or competitor; note volatility. | Volume growth can mask per-unit quality decay or coordination overhead. |
| 2 | Capacity Scale | Maximum throughput, storage, or processing capacity that the system can sustain under acceptable performance and risk (e.g., transactions per second, hospital beds, MW of generation). | Identify throughput ceilings; run load tests; compare to design specs; note margin. | Unrecognised bottlenecks trigger abrupt performance collapse; overconfidence in spare capacity. |
| 3 | Intensity / Utilisation Scale | Degree of utilisation relative to capacity (e.g., load factor, occupancy rate, CPU utilisation, staffing ratio). Distinguishes lightly loaded systems from those operating near saturation. | Monitor utilisation ratios and headroom; track trend toward thresholds; flag drift. | Near-saturation operation amplifies variance, latency, error rates, and incident severity. Linearity assumption fails. |
| 4 | Impact Magnitude Scale | Absolute magnitude of effects per incident (e.g., financial loss, casualties, environmental footprint) independent of frequency. Distinguishes minor incidents from catastrophic ones. | Quantify harm/severity; define escalation bands; identify tail/catastrophic modes; model exposure. | Overfocus on frequency hides rare-but-catastrophic events; tail risk dominates at large scale. |
| 5 | Exposure-at-Risk Scale | Amount of value, critical function, or population exposed to a given hazard or failure mode at a time. Focuses on "how much is at stake" in concentrated pools. | Calculate value/population exposed; map concentration; identify single points of failure. | Exposure concentration makes tail events dominate resilience; correlated failures amplify systemic risk. |

## 3.2 Types (Category II: Scope & Reach Scale)
| # | Type | Description (1–3 sentences) | Diagnostic cues (optional) | Failure / hidden-risk signature (optional) |
|---|---|---|---|---|
| 6 | Geographic Scope Scale | Extent across physical or virtual space (local, regional, national, global; single site vs. distributed). Determines logistical complexity, latency, and exposure to geographically varying constraints. | Map geographic footprint; identify localised constraints (climate, labour, regulation); note latency/comms burden. | Localised constraints or failures propagate globally; compliance varies by region; shipping/comms latency underestimated. |
| 7 | Population / Stakeholder Scope | Number and diversity of people, organisations, or entities affected or involved. Ranges from niche groups to whole populations; shapes complexity of interests, communications, and legitimacy. | Map population served/impacted; segment vulnerability and heterogeneity; count stakeholder types. | Small per-user harms become systemic at scale; reputational risk compounds; narrative alignment becomes impossible. |
| 8 | Functional Scope Scale | Breadth of functions, services, or use-cases encompassed (single-purpose vs. multi-purpose platforms; narrow vs. end-to-end processes). Wider functional scope increases coupling and governance complexity. | Catalogue functions/products/processes; map dependencies; identify shadow systems. | Scope creep overwhelms governance; hidden interdependencies amplify failure propagation. |
| 9 | Jurisdictional & Regulatory Scope | Number and heterogeneity of legal, regulatory, or standards regimes implicated (single jurisdiction vs. multi-jurisdictional). Drives complexity of compliance, governance, and enforcement. | List jurisdictions/boundaries and applicable regimes; map conflicts and exceptions. | Jurisdiction mismatches create gaps or duplication; regulatory arbitrage tempts non-compliance; enforcement becomes fragmented. |
| 10 | Ecosystem & Dependency Scope | Extent of interdependence with other organisations, suppliers, partners, or platforms. Captures how far effects propagate through an ecosystem when scale changes. | List external dependencies; map critical suppliers/partners; model failure propagation; estimate recovery time. | Boundary mismatch creates gaps, duplication, and enforcement failure; ecosystem cascade risk underestimated. |

## 3.3 Types (Category III: Structural Complexity & Density Scale)
| # | Type | Description (1–3 sentences) | Diagnostic cues (optional) | Failure / hidden-risk signature (optional) |
|---|---|---|---|---|
| 11 | Component Count Scale | Number of distinct components, modules, subsystems, or actors within the system. Higher counts typically increase failure modes and coordination overhead. | Count components; identify dependency nodes; estimate combinatorial interaction space. | Combinatorial failure modes grow exponentially; change risk rises with component count. |
| 12 | Interaction Density Scale | Number and intensity of connections per component (degree of coupling, number of interfaces). High density enables functionality but propagates failures and complexity. | Measure interaction density (handoffs, calls, dependencies, message volume); map coupling patterns. | Dense coupling propagates faults and creates cascade risk; tight coupling resists change. |
| 13 | Layering & Hierarchical Depth Scale | Number of structural levels or layers (e.g., teams within departments; stack layers; abstraction levels). Greater depth helps manage complexity but increases latency, opacity, and information loss. | Map layers/hierarchy depth; measure decision latency; track information fidelity at each layer. | Layering increases opacity and slows feedback and response; distortion accumulates through layers. |
| 14 | Variety & Heterogeneity Scale | Diversity of component types, technologies, processes, or stakeholder groups. High variety can increase resilience and innovation but complicates integration and governance. | Inventory heterogeneity (stacks, standards, contexts, processes); map integration points. | Integration overhead and inconsistent controls create systemic gaps; standards enforcement becomes difficult. |
| 15 | Coordination & Information Load Scale | Amount of information processing, communication, and coordination effort required to keep the system functioning. Captures "managerial" or "cognitive" complexity. | Estimate coordination burden (approvals, comms load, decision points); measure meeting load and rework. | Coordination overhead becomes diseconomy; adaptation slows; decision latency increases; errors in translation accumulate. |

## 3.4 Types (Category IV: Returns-to-Scale & Scale Effects)
| # | Type | Description (1–3 sentences) | Diagnostic cues (optional) | Failure / hidden-risk signature (optional) |
|---|---|---|---|---|
| 16 | Economies-of-Scale Pattern | Pattern where unit costs or effort per unit decrease as volume increases (e.g., spreading fixed costs, bulk purchasing, standardisation). Important driver of centralisation and consolidation. | Assess fixed vs variable costs; compute unit cost curve; identify breakeven and optimal scale. | Centralisation pressures can create single points of failure; loss of local flexibility and resilience. |
| 17 | Diseconomies-of-Scale Pattern | Pattern where unit costs, risk, or delays increase with size (e.g., bureaucratic friction, coordination overhead, communication failures, quality decay). Limits benefits of "bigger is better". | Identify overhead/bureaucracy growth with scale; track workarounds and shadow systems. | Diseconomies induce workarounds, quality decay, and friction; efficiency gains plateau or reverse. |
| 18 | Network Effect Scale | Pattern where value increases non-linearly with number of connected participants (e.g., platforms, social networks). Produces winner-takes-most dynamics and strong path dependence. | Look for value increasing with participant/user count; map feedback loops; estimate critical mass. | Winner-takes-most dynamics create lock-in and power concentration; switching costs become prohibitive. |
| 19 | Congestion & Saturation Scale | Pattern where performance deteriorates as usage approaches or exceeds capacity (queues, latency, breakdowns). Distinguishes systems that degrade gracefully from those that fail abruptly. | Track congestion signals (queueing, latency, error rates, abandonment); model degradation curve. | Congestion leads to non-linear degradation and sudden collapse; customers flee; reputation damage compounds. |
| 20 | Learning & Experience Curve Scale | Pattern where performance improves (costs fall, quality rises, time-to-delivery shrinks) as cumulative volume or experience grows. Explains advantages of early movers and practice. | Map spillovers/externalities; track improvement curves; compare to competitors' learning rates. | Externalised harms and learning accumulate; incumbents gain advantage; new entrants face barrier. |

## 3.5 Types (Category V: Thresholds, Regimes & Non-Linear Scale)
| # | Type | Description (1–3 sentences) | Diagnostic cues (optional) | Failure / hidden-risk signature (optional) |
|---|---|---|---|---|
| 21 | Minimum Viable Scale | Smallest scale at which a system, organisation, or intervention is viable or self-sustaining (e.g., minimum subscriber base, minimum staffing, minimum facility size). Below this, it cannot persist without external support. | Define minimum viable scale; assess sustainability below threshold; identify hidden subsidies. | Below threshold, systems depend on hidden subsidies; scaling below minimum causes collapse. |
| 22 | Critical Mass Scale | Scale beyond which self-reinforcing dynamics emerge (e.g., sufficient users for network to sustain itself, sufficient adopters for movement visibility). Initiates positive feedback loops. | Identify critical mass conditions; model adoption curves; assess whether initiative has reached critical mass. | Initiatives stall below critical mass; takeoff can be sudden once threshold is crossed. |
| 23 | Safety / Capacity Threshold Scale | Scale at which safety margins are consumed and risk of cascading failure increases sharply (e.g., occupancy thresholds, load limits, staffing minima for safe operation). | List tipping points and leading indicators; define alert thresholds; model failure probability near margins. | Near tipping points, small changes trigger large cascades; operations become brittle. |
| 24 | Tipping Point Scale | Point at which small additional increments produce disproportionate change in state or behaviour (e.g., loss of trust, system collapse, regime change, runaway growth). Often non-obvious until crossed. | Map regimes/phase transitions; model qualitative behaviour changes; look for hysteresis and bistability. | Assuming regime continuity causes planning failure under shock; sudden switches surprise. |
| 25 | Systemic Impact / Spillover Scale | Scale at which local actions or failures become system-wide phenomena (e.g., firm-level distress to systemic crisis, project failure to organisational gridlock). Marks the boundary between idiosyncratic and systemic risk. | Model tails and catastrophe modes; estimate cascade probability; map systemic risk amplification. | Tail risks dominate at large scale; average-case reasoning fails; rare events matter most. |

## 3.6 Types (Category VI: Scalability, Modularity & Replicability)
| # | Type | Description (1–3 sentences) | Diagnostic cues (optional) | Failure / hidden-risk signature (optional) |
|---|---|---|---|---|
| 26 | Upward Scalability Capacity | Ability of a system to grow by one or more orders of magnitude without prohibitive redesign, loss of performance, or unacceptable risk increase. Reflects elastic vs. brittle architecture. | Assess vertical scaling limits; identify structural constraints; model performance at scaled volumes. | Scaling-up concentrates risk; blast radius expands; single points of failure become critical. |
| 27 | Downward Scalability Capacity | Ability to operate efficiently and safely at small scales (e.g., lightweight variants, minimum configurations, graceful degradation). Important for pilots, decentralisation, and low-resource contexts. | Assess scaling-down feasibility; identify what cannot be eliminated; test minimum viable configs. | Inability to shrink yields brittle overcapacity; scaling down often requires full redesign. |
| 28 | Modularity & Interface Standardisation | Degree to which system components can be decoupled and composed through standardised, stable interfaces. Enables independent scaling of components and reduces redesign burden. | Audit coupling patterns; identify loosely coupled modules; assess interface stability; test replaceability. | Tight coupling hides in architecture; modularity debt accumulates; interfaces drift. |
| 29 | Elasticity & Dynamic Adjustment | Ability to add/remove capacity or resources dynamically in response to demand (e.g., cloud autoscaling, staffing surge/reduction, inventory variation). Contrasts with fixed or slowly adjusting capacity. | Measure response time to demand spikes; identify lag and overshoot; test adjustment limits. | Elasticity constraints create lag; overshoot causes oscillation; under-provisioning causes outages. |
| 30 | Portability & Context Transferability | Ability to transfer a working solution across contexts (e.g., geographic regions, markets, customer segments) with minimal redesign. Reflects how domain-specific vs. universal the design is. | Assess design universality; identify context-specific components; estimate rework per context. | Context assumptions are embedded invisibly; transfer failure blamed on execution rather than design. |

## 3.7 Extending the Taxonomy (mandatory)
| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | Preserve the 6×5 structure (30 types) as the default for cross-framework comparability. |
| Domain refinement | Add domain-specific subtypes under parent types (e.g., 'transaction throughput', 'organisational headcount') and tag to parent ID. |
| Preserving mappability | Each subtype should specify: dominant meta-category/type, scale dimension profile, likely interfaces (threshold/saturation/critical mass), and expected dynamics. |
| Structural invariants | Keep six meta-categories, 30 core types, and five dimensions unless issuing a major version bump. |
| Scale monitoring cadence | Define explicit triggers for scale re-assessment; document transition thresholds and regime-change indicators. |
| Versioning & governance | Minor versions for wording/examples; major versions for taxonomy changes; record mapping notes for deviations. |

---

# 4. Cross-Cutting Dimensions of Scale

## 4.1 Dimensions Table (mandatory)
| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| Absolute Magnitude | Size measured in absolute units (headcount, revenue, transaction volume, geographic spread, entity count). Determines exposure at risk and absolute resource requirements. | **Single digit to tens** – Startup/niche; scope and headroom are obvious. **Hundreds** – Small organisation; most interactions are direct. **Thousands** – Medium scale; first coordination challenges emerge. **Tens of thousands** – Large scale; formal structures necessary. **Hundreds of thousands to millions+** – Massive scale; layers, specialisation, and opacity are endemic. | Collect size data (headcount, footprint, volume); track growth rate; compare to industry baselines. | Informs capacity model; drives governance structure complexity; determines whether transparency is feasible. |
| Geographic / Population Reach | Spatial or demographic extent (local, regional, national, global; monolithic vs. distributed). Determines logistical complexity, regulatory burden, latency, and exposure to geographically varying constraints. | **Mono-location or single region** – Low logistical complexity; constraints are local. **Multi-region (3–10 regions)** – Coordination burden emerges; some regulatory divergence. **National or continental** – Significant regulatory variation; latency and logistics are material. **Global** – Extreme complexity; regulatory arbitrage tempts; comms latency is hard constraint. | Map geographic footprint; identify jurisdictions and constraints; measure comms/logistics latency. | Drives regulatory/governance complexity; determines whether centralised control is feasible; affects monitoring/response tempo. |
| Structural Coupling Density | Degree to which components are tightly or loosely connected (measured in interaction density, shared state, serialisation points). Determines how failures propagate and how much flexibility exists. | **Loosely coupled** – Components operate independently; failures are isolated; changes are local. **Moderately coupled** – Some shared resources and dependencies; failures propagate slowly. **Tightly coupled** – Extensive shared state and interdependence; failures propagate immediately; changes are system-wide. **Hyper-coupled** – Everything depends on everything; no isolation; single points of failure are endemic. | Audit dependency graphs; measure interaction density; assess failure propagation speed. | Informs resilience strategy; determines redesign burden; indicates whether modularisation is possible. |
| Cost / Performance Scaling Curve | How unit costs, latency, or error rates scale with volume (linear, sub-linear due to economies, super-linear due to diseconomies, or non-monotonic with thresholds). Determines whether "bigger is better" or where limits hit. | **Sub-linear / improving** – Economies of scale dominate; unit cost falls as volume grows. **Linear / stable** – No strong economies or diseconomies; proportional scaling. **Super-linear / degrading** – Diseconomies dominate; unit costs rise with volume. **Non-monotonic / threshold-driven** – Multiple regimes; abrupt changes at thresholds; tail behaviour differs from average. | Collect cost and performance data across volumes; fit curves; identify threshold transitions; model tails. | Informs pricing and profitability strategy; flags where diseconomies constrain growth; identifies dangerous operating points. |
| Threshold Sensitivity & Regime Brittleness | Proximity to critical thresholds and steepness of degradation once thresholds are breached. Distinguishes systems that degrade gracefully from those that fail abruptly. | **Distant from thresholds / graceful** – Large headroom; degradation is slow and predictable; ample warning. **Approaching thresholds / brittle** – Limited headroom; degradation is non-linear; failure can be sudden. **At or beyond thresholds / crisis** – Operating in dangerous regime; high cascade risk; volatility dominates. | Identify known thresholds; estimate margin to threshold; assess degradation slope; measure threshold crossing frequency. | Determines urgency of remediation; informs governance tempo and alert thresholds; flags where architectural redesign is needed. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations (optional) |
|---|---|---|---|---|---|
| 1 | Escalation through saturation thresholds | Routine operations become crisis as utilisation approaches capacity; tempo compresses; thresholds matter acutely. | Latent slack disappears; variance amplifies near capacity; feedback loops accelerate; control authority saturates. | Misclassification as routine delays response; cascades occur when stabilisation is late; governance tempo must change. | Headroom discipline; capacity-based alert thresholds; automated escalation rules; surge capacity pre-positioned. |
| 2 | Crystallisation from exploration to scale-up | Pilot/exploratory contexts transition to scaled operations once design stabilises and demand is proven. | Design matures; demand signals solidify; coordination mechanisms formalise; governance shifts from learning to execution. | Premature scaling locks in suboptimal design; delayed scaling misses market window; governance structures become misaligned. | Explicit phase gates and success criteria; design-for-scale reviews pre-transition; post-scaling learning loops. |
| 3 | Critical mass and network effects takeoff | System value increases non-linearly once participation reaches critical mass; dynamics shift from slow growth to explosive adoption. | Positive feedback loops activate; incumbent lock-in emerges; switching costs rise; winner-takes-most dynamics kick in. | Initiatives stall below critical mass; takeoff can be sudden and hard to plan for; late entrants face insurmountable barriers. | Monitor adoption curves for inflection points; plan for post-critical-mass governance; manage lock-in risks. |
| 4 | Regime drift and stale assumptions | System gradually shifts from one regime to another (e.g., stable to chaotic, or routine to crisis-adjacent); classifications become outdated; governance misaligns. | Slow change below monitoring threshold; assumptions persist despite evidence; mental models lag reality; controls become ineffective. | Stale classifications accumulate; drift is not recognised until crisis; tempo mismatches cascade. | Periodic re-assessment cadence; independent audits; assumption audits; teach-back to spot stale thinking. |
| 5 | Diseconomy-driven workarounds and quality decay | Diseconomies emerge as scale grows; formal processes become slower and more burdensome; people create workarounds; quality decays in shadow systems. | Coordination overhead grows faster than benefit; bureaucratic friction increases; incentives diverge from formal processes. | Quality losses appear in shadow systems and are hard to measure; formal metrics show stability while real quality erodes. | Redesign processes for scale; reduce unnecessary layers; audit shadow systems regularly; measure real quality not just formal KPIs. |
| 6 | Latency accumulation through layers | Each organisational or technical layer adds decision latency and information loss; thresholds become unresponsive to change. | Information is filtered at each layer; decisions cascade through hierarchy; each level adds delay and distortion. | Response to incidents becomes dangerously slow; organisations cannot adapt fast enough; Situational awareness decays. | Flatten hierarchies where possible; add skip-level communication channels; short-circuit escalation for critical events. |

---

# 6. Interfaces and Interaction Patterns

## 6.1 Interface Types (Three Standard Patterns)
### Interface Type A: Threshold Crossing and Regime Transition
Situations where a system moves from one scale regime to a qualitatively different one. Example: moving from "routine" (stable, linear) to "threshold-adjacent" (non-linear, brittle). Decisions at these interfaces centre on timing, buffering, and governance transition. Key risks include remaining in old regime too long, overshooting into new regime unnecessarily, and misalignment of controls during transition.

**Detection cues**: Metrics approaching threshold values; behaviour changes becoming visible; incidents clustering around a critical parameter; stress tests showing non-linear degradation.

**Mitigation levers**: Leading-indicator monitoring; margin discipline; graduated governance transition; contingency triggers.

### Interface Type B: Economies/Diseconomies Crossover
Situations where a system transitions from economies-of-scale dominance to diseconomies-of-scale dominance (or vice versa). Example: a function that is cheaper when centralised becomes more expensive as it scales due to coordination overhead. Decisions centre on whether to continue scaling, segment, or redesign.

**Detection cues**: Unit costs flattening or rising despite volume growth; quality degrading; error rates increasing; customer satisfaction plateau or decline; rework and workaround volume increasing.

**Mitigation levers**: Process redesign for scale; modularity and delegation; cost structure redesign; governance decentralisation.

### Interface Type C: Ecosystem Cascade and Systemic Spillover
Situations where scale changes in one component trigger propagation through ecosystem dependencies. Example: a supplier's capacity constraint becomes a supply-chain bottleneck. Decisions centre on resilience, buffering, and ecosystem coordination.

**Detection cues**: Failures propagating beyond expected blast radius; interdependencies becoming visible only in failure; suppliers or partners signalling strain; external constraint binding earlier than expected.

**Mitigation levers**: Supplier/partner pre-coordination; inventory buffers; alternative suppliers; decoupling through modularity; ecosystem-level planning.

---

# 7. Integration with the 36-Framework Analytical Series

## 7.1 Position in Series Workflow and Canonical Framework List
This framework provides scale awareness across the Analytical Series. Below is the mapping of all 36 frameworks to their group assignment, stage (Upstream / Middle / Downstream), and how Scale integrates with each:

| # | Framework | Group | Stage | Scale integration notes |
|---|---|---|---|---|
| 1 | Situations & Context Classification | G1 | Upstream | Scale context class (routine vs crisis vs transformational); scale determines response mode and tempo |
| 2 | Evidence & Information Provenance | G5 | Upstream | Aggregation bias masking tails; sample size and representativeness at scale; measurement scale mismatch |
| 3 | Diagnosis | G2 | Middle | Scale-appropriate diagnostic depth; root cause varies by scale; aggregation effects in diagnosis |
| 4 | Agents & Actors | G3 | Upstream | Number of agents and diversity; span of control; coordination challenge; agency distribution at scale |
| 5 | Power & Incentives | G3 | Middle | Incentive distortion at scale; principal-agent problems grow with distance; alignment mechanisms scale poorly |
| 6 | Culture, Values & Norms | G4 | Middle | Cultural coherence decreases with scale; values drift in large organisations; norm enforcement becomes difficult |
| 7 | Causation & Root-Cause Analysis | G2 | Middle | Scale effects introduce non-linear causation; root causes differ at macro vs micro scales |
| 8 | Systems & Structural Modelling | G2 | Upstream | Coupling and feedback loops change with scale; system behaviour becomes emergent; control authority limits at scale |
| 9 | Boundaries & Scope Definition | G1 | Upstream | Boundary complexity grows with scope; jurisdictional and ecosystem boundaries at scale; interface management |
| 10 | Resources & Capacity | G2 | Upstream | Absolute capacity and utilisation; resource concentration risk; elasticity and dynamics |
| 11 | Time & Temporal Dynamics | G4 | Upstream | Timescales vary with scale; latency and feedback delay accumulate; synchronisation challenges at scale |
| 12 | Dimensions & Levels of Analysis | G1 | Upstream | Scale selects analysis level; micro/meso/macro mismatch; phenomena visible at one level, hidden at another |
| 13 | Governance & Decision Rights | G6 | Downstream | Scale-appropriate governance structure; centralisation vs delegation; escalation paths; authority by scale |
| 14 | Responsibility & Accountability | G6 | Downstream | Accountability diffusion at scale; responsibility gaps; agent visibility and control at scale |
| 15 | Decisions & Decision-Making | G6 | Downstream | Scale affects decision quality and speed; centralised vs distributed decision-making tradeoffs |
| 16 | Interventions & Change Design | G6 | Downstream | Scale-appropriate intervention design; pilot vs rollout; replication and transfer across contexts |
| 17 | Risk & Resilience | G5 | Middle | Tail risk and concentration; single points of failure at scale; cascade and systemic risk |
| 18 | Hiddens | G5 | Cross-cutting | Scale-driven visibility failures (aggregation, threshold blindness, coordination opacity); mandatory Hiddens scan |
| 19 | Learning & Adaptation | G6 | Downstream | Learning curves and practice effects; knowledge transfer at scale; improvement visibility |
| 20 | Legitimacy & Social License | G4 | Middle | Legitimacy diffusion at scale; stakeholder narrative alignment; fairness and equity at scale |
| 21 | Competing Narratives & Framing | G4 | Middle | Multiple framings at different scales; frame capture at scale; scale myopia |
| 22 | Failures & Post-Failure Work | G5 | Middle | Scale mismatch as root cause; failure propagation at scale; post-failure learning |
| 23 | Beliefs & Mental Models | G4 | Middle | Shared mental model complexity at scale; belief drift; espoused-operative divergence |
| 24 | Incentives & Reward Systems | G3 | Middle | Incentive distortion and misalignment at scale; gaming and Goodhart's Law effects |
| 25 | Escalation & Escalation Failure | G6 | Downstream | Escalation pathways and latency; threshold-triggered escalation; communication degradation at scale |
| 26 | Coordination & Coordination Failure | G3 | Middle | Coordination burden explodes with scale; collective action problems; tragedy-of-commons effects |
| 27 | Secrecy, Deception & Strategic Concealment | G5 | Middle | Information hiding grows at scale; asymmetric information; verification becomes difficult |
| 28 | Measurement, Metrics & KPIs | G5 | Middle | Aggregation bias in metrics; Goodhart's Law; tail-risk invisibility in aggregate metrics |
| 29 | Transparency & Information Access | G5 | Middle | Transparency breaks down at scale; information silos; asymmetric visibility |
| 30 | Assumption Auditing & Robustness Testing | G5 | Middle | Scale-dependency of assumptions; linearity assumptions fail at thresholds; stress testing at scale |
| 31 | The Framework of Scale | G1 / G2 | Upstream / Middle | *This framework* – synthesises scale across dimensions; integrates with all groups; mandatory for complex scenarios |
| 32 | Situational Appropriateness & Mode Matching | G1 | Upstream | Scale determines whether response mode fits; scale drift requires mode transition |
| 33 | Dispute Resolution & Multi-Stakeholder Alignment | G6 | Downstream | Alignment difficulty grows with scale; dispute resolution mechanisms scale poorly |
| 34 | Regulatory & Compliance Landscape | G6 | Downstream | Regulatory complexity grows with jurisdictional scope; compliance burden at scale |
| 35 | Ecosystem & External Dependency Management | G2 | Upstream | Ecosystem size and complexity; supplier/partner concentration; systemic interdependence |
| 36 | Post-Incident Review & Organisational Learning | G6 | Downstream | Learning capture and scaling at organisational level; preventing recurrence at scale |

## 7.2 Tier 2 Hiddens Micro-Protocol (Scale-Specific Mechanisms)

When Tier 1 Hiddens scan (§8.1.1) surfaces scale-driven visibility failures, escalate to Tier 2 with this framework-specific shortlist:

| ID | Tier 2 Mechanism (scale-specific) | Why hidden | How to test | OG §7.5 Targeted Scans cross-ref |
|---|---|---|---|---|
| SC-01 | Aggregation bias masking tails | Average metrics hide outliers; tail events are invisible in rolled-up reports. | Disaggregate by percentile; look for 90th+ percentile performance; run separate tail-risk analysis. | B-1 Information Filtering; B-4 Metrics Distortion |
| SC-02 | Threshold opacity (regimes untracked) | Thresholds are designed but not monitored; drift across boundaries goes unnoticed until failure. | Audit threshold definition and monitoring; test whether leading indicators are on dashboards; validate alert triggers. | B-2 Hidden Thresholds; C-2 Drift Detection Failure |
| SC-03 | Coordination burden invisibility | Coordination overhead grows with scale but is not measured or charged; burden is diffused into 'busyness' and workarounds. | Survey time-in-meeting; estimate rework fraction; measure approval delays; inventory shadow processes. | B-3 Coordination Burden; A-1 Information Bottleneck |
| SC-04 | Complexity creep in architecture | Coupling and hidden dependencies accumulate; system becomes opaque; change risk is unknown. | Audit dependency graph; measure coupling metrics; run design reviews; test impact of changes. | B-4 Architecture Blindness; B-3 Coordination Burden |
| SC-05 | Non-linearity blindness (linear models dominate) | Cost and performance models assume linearity; non-linear regimes are modelled with linear proxies; planning fails at thresholds. | Audit modelling assumptions; test linearity; collect regime-specific data; stress-test plans at high-volume scenarios. | B-2 Hidden Thresholds; C-1 Temporal Asynchrony |
| SC-06 | Cascading failure invisibility (coupling + scale) | Tight coupling + scale = rapid failure propagation; cascade risk is underestimated because incidents are rare in single-site operations. | Run cascade simulations; audit failure-propagation chains; test whether isolation mechanisms exist; measure mean time to recovery. | B-5 Coupling Opacity; C-3 Cascade Latency |

---

# 8. Hiddens Source Analysis & Hiddens Cross-Check

## 8.1 Tier 1 Hiddens Scan (Six-Category Visibility Audit)

### 8.1.1 Tier 1 Categories (mandatory, run at least twice: early and pre-closure)
| Category | Visibility failure definition | Scale-specific manifestation | Diagnostic questions | Probe/test |
|---|---|---|---|---|
| **I. Perceptual** | People/systems cannot see what is happening due to attention limits, salience bias, or lack of instrumentation. | At scale, most activity is invisible to any single observer; aggregate metrics hide local variation. | What happens outside the field of view? What tails are hidden in averages? Where does information dissipate? | Disaggregate metrics; survey across levels; run surprise audits; interview frontline actors. |
| **II. Systemic** | Structures and controls prevent visibility (compartmentalisation, authority boundaries, formal/informal separation). | At scale, formal structures create silos and information barriers; shadow systems operate unseen. | What is hidden in formal structures? What workarounds are invisible? Where do boundaries block cross-functional sight? | Audit org chart vs actual workflows; inventory shadow processes; map information barriers. |
| **III. Informational** | Evidence is gated, corrupted, or inaccessible (access control, bias, noise). | At scale, data is filtered at each layer; aggregation introduces bias; real-time visibility disappears. | What data is missing? What filters distort signals? Where is information asynchronous? | Check evidence access; audit filtering layers; test data quality; run information audits. |
| **IV. Temporal** | Events unfold faster than perception/response systems operate (latency, drift, delayed feedback). | At scale, latency accumulates through layers and channels; drift goes undetected until crisis; feedback loops are slow. | How long does information take to propagate? Where are feedback delays? How fast are critical changes? | Measure comms latency; track feedback-loop delay; identify decision-speed bottlenecks. |
| **V. Relational** | Visibility is filtered by power, position, or incentive (who sees depends on who they are and what they benefit from seeing). | At scale, positional blindness increases; incentive misalignment hides information; power shapes narrative. | Whose perspective is missing? Where do incentives suppress visibility? How does position shape what is seen? | Elicit multi-stakeholder narratives; audit incentive alignment; look for predictable omissions by role. |
| **VI. Structural** | The concepts used to make sense of the world are incomplete, contested, or absent (ontological gaps, frame mismatch). | At scale, shared mental models break down; dominant frames hide alternatives; new phenomena don't fit existing categories. | What concepts are absent? What phenomena don't fit the dominant frame? Where do different groups use different models? | Run frame comparison across stakeholders; look for phenomena that resist classification; audit mental models. |

### 8.1.2 Running the Tier 1 scan in this framework context
When executing this framework as part of a broader Analytical Series investigation:

1. **Early Tier 1 scan** (before deep analysis): Run the six-category audit with a focus on scale-specific questions:
   - *Perceptual:* What scale-level variations are hidden in aggregate reporting?
   - *Systemic:* How do silos at different scales prevent cross-scale visibility?
   - *Informational:* Where are measurement and data-collection misaligned with scale?
   - *Temporal:* How long does scale-change information take to propagate?
   - *Relational:* How does scale position shape what different actors see?
   - *Structural:* What scale regimes are not yet named or modelled?

2. **Escalate to Tier 2** (if Tier 1 flags material hiddens): Use the scale-specific Tier 2 shortlist (§8.1.2) to deepen on the most consequential mechanisms (e.g., threshold opacity, coordination burden invisibility, cascading failure risk).

3. **Targeted Scans** (if Tier 2 points to specific mechanisms): Route to OG v2.5 §7.5 Targeted Scans, prioritising:
   - **B-2 Hidden Thresholds**: Full threshold mapping, regime boundaries, proximity analysis
   - **B-4 Architecture Blindness**: Coupling deep-dive, failure-propagation modelling
   - **C-2 Drift Detection Failure**: Monitoring-regime audit, leading-indicator validation
   - **B-3 Coordination Burden**: Coordination mapping, overhead quantification, bottleneck identification

## 8.2 Example Scale Hiddens Scenarios
| Hidden ID | Situation | Likely mechanism | Detection cue | Mitigation lever |
|---|---|---|---|---|
| SCALE-01 | Utilisation approaching saturation; performance metrics still "normal" | Aggregation bias masking tail degradation; alert thresholds set too high | Error rates or latency spike before average metric breaches threshold | Real-time percentile monitoring; lower alert thresholds near regimes |
| SCALE-02 | Scale transition planning missed threshold; expansion moved from "feasible" to "requires redesign" | Non-linearity blindness; linear extrapolation of costs/coordination burden | Design reviews for scale readiness; stress testing at 2x current scale | Build scaling into architecture reviews pre-transition; model non-linearity |
| SCALE-03 | Governance structure works at regional scale but fails at global scale | Coordination overhead and decision latency accumulate through layers | Decision speed degrades; escalation paths become bottlenecks | Flatten hierarchy; short-circuit escalation for critical items; distributed authority |
| SCALE-04 | Modular replication fails when context changes (e.g., pilot works, rollout fails) | Context-specific assumptions embedded in design are invisible until transfer | Transfer failures blamed on execution; post-mortems miss design issues | Design-for-transfer reviews; explicit context assumption mapping; transfer pilots |
| SCALE-05 | Rare systemic failure occurs; was modelled as low-probability but cascade path was invisible | Coupling and feedback-loop effects underestimated; tail scenarios not stress-tested | Failures surprise; cascade is faster than expected response | Explicit cascade-path mapping; regular stress tests at tail scenarios; faster escalation triggers |

---

# 9. Application Protocol: Scale Analysis Workflow

## 9.1 Seven-Step Scale Analysis Protocol

**Step 1: Define the focal scale concern**
- What is scaling (product, organisation, deployment, user base)?
- What dimensions worry you most (magnitude, reach, complexity, effects, thresholds, scalability)?
- What is the decision this analysis must inform?

**Step 2: Characterise current scale position (multi-dimensional profile)**
- Assign scale types in each meta-category (§3: I–VI).
- Profile absolute magnitude, reach, complexity, effects, thresholds, scalability.
- Document data sources and confidence levels.
- Note asymmetries (e.g., "we have reached critical mass in users but lack organisational scale").

**Step 3: Map thresholds and regimes**
- Identify known critical thresholds (from design, domain knowledge, prior incidents).
- Estimate current proximity to thresholds.
- Define leading indicators for each threshold.
- Map qualitative regimes (stable/brittle/critical/crisis) and regime transitions.

**Step 4: Analyse scale effects (returns-to-scale and dynamics)**
- Profile cost/performance scaling curves (economies vs diseconomies vs non-monotonic).
- Identify network effects or critical-mass dynamics.
- Model expected dynamics as scale changes (saturation, cascades, diseconomy onset).
- Project future scale position and associated risks.

**Step 5: Diagnose scale-mismatch failures**
- Compare governance structure to scale (who decides at what scale? Are escalation paths clear?).
- Compare decision-rights to scale (do authorities match scale of decisions?).
- Compare intervention design to scale (was this piloted? Does it account for replication context?).
- Compare monitoring/control design to scale (are thresholds tracked? Is monitoring cadence appropriate?).

**Step 6: Run Hiddens scan (Tier 1 + Tier 2 escalation)**
- Run Tier 1 across six categories with scale-specific focus (§8.1.1).
- Escalate to Tier 2 scale-specific mechanisms (§8.1.2) if material hiddens surface.
- Populate Hiddens Register with candidate scale-driven visibility failures.
- Route to Targeted Scans (OG v2.5 §7.5) if specific mechanisms are suspected.

**Step 7: Design scale-appropriate interventions and governance**
- Specify scale-appropriate decision rights and escalation paths.
- Design governance structures for current and projected scale.
- Define threshold-monitoring regime (leading indicators, alert thresholds, re-assessment cadence).
- Specify how interventions adapt as scale changes (phased rollout, modular design, elasticity).
- Document explicit residual unknowns (what about scale remains unclear?) and acceptability rationale.

---

# 10. Standard Shared Registers

| Register | Purpose | OG reference | Updated in execution? |
|---|---|---|---|
| Hiddens Register (framework view) | Track scale-driven visibility failures; mechanisms; detectability; consequence; tests; owners. | OG v2.5 §D.4.1 | Ongoing; escalate as Tier 1 → Tier 2 → Tier 3 |
| Evidence Ledger (framework view) | Track evidence supporting/contradicting scale claims (e.g., "we have reached critical mass"; "economies of scale will dominate"); quality; gaps. | OG v2.5 §D.4.1 | Ongoing; F/I/A/U tag all claims |
| Hypothesis/Test Backlog | Convert scale unknowns into testable probes (e.g., "Is utilisation currently >80%?"; "Will diseconomies onset at 2x current scale?"). | OG v2.5 §D.4.1 | Ongoing; prioritise for early learning |
| Information Requests | Explicit missing inputs needed to reduce scale-related decision unknowns (e.g., "Current threshold proximity data"; "Supplier elasticity limits"). | OG v2.5 §D.10.2, Appendix E §E.4 | Ongoing; mark priority and expected value |
| Residual Unknowns + Closure note | Record scale questions that remain unanswered, why, acceptability of proceeding, monitoring plan, ownership, learning trigger. | OG v2.5 §7.4 | Final closure only |

---

# 11. Closure Discipline and Escalation

This framework integrates with OG v2.5 §7.4 (Closure discipline). Before declaring analysis complete:

1. **Populate all required registers** (Hiddens, Evidence, Hypotheses/Tests, Information Requests).
2. **F/I/A/U tag all key claims** (especially scale type assignments, threshold estimates, governance-fit conclusions).
3. **Record residual unknowns explicitly**:
   - What scale questions remain unanswered?
   - Why are they not answered (time, access, evidence gaps)?
   - Are they critical to the decision?
   - If critical: escalate to Tier 2 or Tier 3 Hiddens work.
4. **Define acceptability rationale**: If proceeding despite residual scale unknowns, document why it is acceptable.
5. **Specify monitoring plan**: How will scale position be monitored post-decision? What leading indicators will trigger re-assessment?
6. **Assign ownership**: Who watches scale metrics? Who triggers escalation if thresholds approach?
7. **Define learning hook**: When will this case be revisited? What will we learn?

**Escalation criteria**: Escalate to full Hiddens run (Tier 3) if:
- Scale mismatch is suspected as a root cause of failure (post-failure work).
- Threshold approach or regime transition is imminent and governance changes are needed.
- Non-linearity could materially alter decisions (e.g., capacity allocation, governance structure, risk tolerance).
- Span of control or coordination burden is at or beyond known organisational limits.
- Multiple scale-related Hiddens compound into systemic risk.

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Author | Changes |
|---|---|---|---|
| v1.0 | 2026-03-27 | Series Maintainer (Sonnet 4.6) | Initial framework: 6 meta-categories, 30 types, 5 dimensions, dynamics, interfaces, Hiddens source analysis. Operating Guide v1.4 alignment. |
| v1.1 | 2026-03-27 | Series Maintainer (Sonnet 4.6) | Cross-reference update: Framework of Beliefs integration into §7.3; series count updated to 33 frameworks. |
| v2.0 | 2026-04-06 | Series Maintainer (Opus 4.6) | Rewrite for Master Template v2.3 alignment; updated OG references from v1.4 to v2.5; expanded §1.6 with Tier 2 Hiddens crosswalk and Targeted Scans routing; added Introduction (four subsections); updated §7 with all 36 canonical frameworks and group/stage assignments; expanded §8 with Tier 2 shortlist and targeted scan family cross-references; updated closure discipline per OG v2.5 §7.4; added Information Requests standard schema; restructured for operational clarity and LLM executability. |

## 12.2 Governance and Maintenance
- **Owner**: Series Maintainer (Anthropic Claude)
- **Review trigger**: Significant changes to Operating Guide; addition of new frameworks to series; material feedback from practitioners
- **Change protocol**: Minor versions for wording/examples; major versions for structural changes to taxonomy or integration model
- **Alignment with Operating Guide**: This framework must remain aligned with OG v2.5 or later; sections §1.6.3–§1.6.7 are canonical pointers to the Operating Guide and must be updated when OG version increments

## 12.3 Key Document Cross-References
- **Operating Guide v2.5** (§3.1 Stage definitions; §4.3 Routing decision tree; §5.0 Iterative loop; §6.2 Standard artefacts; §7.4 Closure discipline; §7.5 Targeted Hiddens Discovery Scans; §D.3 Prompt Discipline Rules; §D.6.10 Tiered Hiddens Scans; §D.10.1 Core execution terms; §D.11 LLM-Navigable Decision Tree)
- **Framework of Hiddens** (Tier 1/2/3 scan methodology; Hidden definitions; visibility failure taxonomy)
- **Framework of Situations** (Scale-appropriate response mode; situation type × scale matrix)
- **Framework of Governance** (Scale-appropriate decision rights and authority structures)
- **Framework of Interventions** (Scale-matched design and replication protocols)
- **Master Rewrite Template v2.3** (Structural invariants; standard sections; deviations protocol)

---

# Appendix A: Scale-Specific Jargon Glossary

| Term | Definition (operational) | Use in this framework |
|---|---|---|
| **Economies of scale** | Pattern where unit costs decrease as volume increases (spreading fixed costs, bulk benefits, learning). Drives consolidation and centralisation. | Type 16 in §3.4; enables profitability at scale; risks include loss of resilience. |
| **Diseconomies of scale** | Pattern where unit costs, coordination burden, or error rates increase with size (bureaucracy, communication overhead, quality drift). Limits "bigger is better" assumption. | Type 17 in §3.4; manifests through coordination opacity, quality decay, workarounds. |
| **Critical mass** | Scale at which self-reinforcing dynamics emerge (e.g., network effects activate, movement becomes visible). Below critical mass, systems stall. | Type 22 in §3.5; identify for platform/network interventions; risk is stalling below threshold. |
| **Headroom** | Margin between current utilisation and maximum capacity. Large headroom = safety and flexibility; small headroom = brittleness and cascade risk. | Dimension in §4 (threshold sensitivity); monitor as leading indicator. |
| **Tipping point** | Scale at which small additional changes produce disproportionate effects (e.g., loss of trust, regime collapse, runaway growth). Often non-obvious until crossed. | Type 24 in §3.5; map explicitly; use as escalation trigger. |
| **Regime** | Qualitative operational mode (e.g., stable/linear, threshold-adjacent/non-linear, chaotic/crisis). Scale determines which regime; drift across regimes alters governance needs. | Tier 1 scan category; map in threshold register; escalation triggers when approaching regime boundary. |
| **Single point of failure** | A component or decision whose failure causes system-wide collapse (no redundancy). At scale, concentration of criticality increases single-point-of-failure risk. | Risk pattern; identify in architecture reviews; drives redundancy/modularity requirements. |
| **Cascade failure** | Failure in one component triggers failures in others through tight coupling or resource contention. At scale, cascade paths become longer and faster. | Dynamic pattern 5 in §5.1; model explicitly; design isolation and circuit-breaker mechanisms. |
| **Coupling** | Degree to which components are interdependent (loosely coupled = independent, tightly coupled = changes propagate). High coupling amplifies cascade risk at scale. | Dimension in §4 (structural coupling density); audit in architecture reviews. |
| **Modularity** | Degree to which components can be separated and composed through standardised interfaces. Enables scaling and reduces redesign burden. | Type 28 in §3.6; design principle for scalable systems. |
| **Elasticity** | Ability to add/remove capacity dynamically in response to demand (e.g., autoscaling, surge staffing). Contrasts with fixed capacity that requires redesign to change. | Type 29 in §3.6; key enabler of graceful scaling. |
| **Aggregation bias** | Phenomenon where summary statistics (averages, totals) hide outliers and distribution tails. At scale, tail risk dominates but is invisible in aggregate metrics. | Hidden mechanism SC-01 in §8.2; detection: disaggregate metrics by percentile. |
| **Threshold opacity** | Hiding mechanism where critical scale thresholds are designed but not actively monitored; drift across thresholds goes unnoticed until failure. | Hidden mechanism SC-02 in §8.2; detection: audit monitoring and alert systems. |
| **Coordination overhead** | Information processing, communication, and decision-making effort required to keep a system functioning. Grows faster than scale; becomes diseconomy. | Type 15 in §3.3, Hidden SC-03; often invisible until measured. |
| **Context transfer** | Process of applying a working solution across different contexts (geographies, markets, customer segments). Assumes design is universal; often fails when hidden assumptions are context-specific. | Type 30 in §3.6; risk: design embedded in context is not portable. |
| **Regime drift** | Slow, often-invisible shift from one qualitative operational mode to another (e.g., stable → threshold-adjacent → crisis). Monitoring cadence determines detection latency. | Dynamic pattern 4 in §5.1; Hidden mechanism C-2 Drift Detection Failure in OG v2.5 §7.5. |

---

# Appendix B: Scale Sensitivity Analysis Template

Use this template to assess sensitivity of decisions to scale-related assumptions:

```
SCALE ASSUMPTION: [What aspect of scale are we assuming? e.g., "Governance remains centralised even at 10x current headcount"]

RISK: [What goes wrong if this assumption is false?]

EVIDENCE: [What data supports this assumption?]

MONITORING: [How will we detect if this assumption is becoming invalid?]

MITIGATION: [What contingency plan kicks in if we detect drift?]

ESCALATION TRIGGER: [At what scale or performance degradation do we reconsider this assumption?]
```

---

End of Framework of Scale v2.0

**For LLM execution**: Follow the standard run prompt in §1.6.7. For human practitioners: Use the seven-step protocol in §9.1. For series integration: Refer to §7 for position among 36 frameworks.
