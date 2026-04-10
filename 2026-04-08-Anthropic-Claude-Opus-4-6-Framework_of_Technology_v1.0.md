# Framework of Technology
*A Comprehensive Taxonomy for Understanding Designed Artefacts, Technical Systems, Affordances, Embedded Assumptions, and Their Sociotechnical Effects*

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
- Group (Primary): G2 — Mechanism, dependencies & systems (Mechanism)
- Group (Secondary): None
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, embedded assumptions are contested, or sociotechnical coupling is tight
- Owner / Maintainer: Series Maintainer
- Intended Use: Technology risk and opportunity analysis; platform and algorithm bias assessment; sociotechnical system design and failure analysis; infrastructure and critical system analysis; digital transformation planning; responsible technology implementation; policy and governance design for technical systems; post-incident and harm analysis involving technology
- Primary Audience: Technology leaders and architects; executives overseeing digital transformation; risk and compliance officers; product and platform owners; AI/ML safety and responsible technology teams; policy designers; regulators and assurance functions; operations and security leaders; investigators and auditors
- Dependencies / Key Inputs: System and process maps; evidence and incident history; stakeholder and user mapping; power and incentive analysis; governance and decision-rights mapping; communication and narrative analysis; time, scale, and boundary framing; risk and failure scenarios; Framework of Hiddens v2.0 (visibility audit layer); Framework of Systems v2.0 (structural complement); Framework of Resources v2.0 (constraints on what technologies enable); Framework of Processes v2.0 (how technologies shape activity flows)
- Primary Outputs: Technology type classification and artefact taxonomy; embedded values and assumptions map; affordance and constraint analysis; technical vs sociotechnical failure signature; power and control distribution map; visibility failure sources (algorithmic opacity, infrastructural invisibility, assumed neutrality); interface ownership and governance requirements; Hiddens shortlist and escalation triggers; detection and remediation design options; monitoring and adaptation plan
- Change Log (brief): Initial creation v1.0 as part of 2026-04-08 Analytical Series rewrite project; first-generation comprehensive technology analysis framework; 6 meta-categories (30 types), 5 dimensions, 10 dynamics patterns, 3 interfaces, full Hiddens integration per MRT v3.0

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What designed artefacts, systems, platforms, algorithms, and protocols are in play; what affordances and constraints do they embed; what values, assumptions, and power distributions are hidden in their design; and how do these reshape what is visible, possible, and invisible in this scenario?** |
| Addresses | Design determinism invisibility; algorithmic bias masking; infrastructural invisibility through ubiquity; black-box opacity and non-legibility; embedded values treated as technical neutrality; affordances blindspots (what the technology makes easy becomes the default, what it makes hard disappears); power distribution concealed as technical necessity; user assumptions baked into design that remain invisible to users themselves; path dependencies and lock-in concealed as technical constraints |
| Gap Filled | Many analyses focus on what technology *enables* (capabilities, efficiency gains) but miss what it *forecloses, assumes, and embeds*. Systems analysis addresses structure but not designed artefacts. Institutions analysis addresses rules but not the material artefacts that enforce or subvert those rules. Technology analysis specifically addresses how designed objects shape possibility and distribute power. |
| Complements | Systems (structure and feedback); Processes (activity flows and sequences); Resources (affordances and constraints on action); Institutions/Governance (rules and authority); Power (who controls and benefits); Culture & Norms (values and assumptions); Evidence (data quality, measurement, bias); Hiddens (visibility failures in technical design) |
| Key Characteristics | Design-centric; affordance-explicit; power-aware; value-embedded; sociotechnical (not purely technical); black-box-sensitive; infrastructure-aware; assumption-surfacing; compatibility with AI/ML and algorithmic systems; aligned with Framework of Hiddens on technical opacity and embedding |
| Main Contributions | Six meta-categories (30 core technology types); five cross-cutting technology dimensions; ten dynamic patterns (obsolescence, lock-in, emergent coupling, etc.); three interface types (user-facing affordances, systemic effects, governance/control); technology-specific Hiddens source analysis with black-box opacity and value-embedding mechanisms; application protocol for technology diagnosis, risk assessment, and redesign; integration with responsible technology and AI governance frameworks |

---

# Introduction

## What is Technology?

Technology is not simply a tool—it is a designed artefact, system, platform, algorithm, or protocol that shapes what is possible, visible, and invisible. A technology encodes choices: about how to solve a problem, who can use it and how, what data it consumes and produces, what it makes easy and what it makes hard, whose interests it serves. These choices are then embedded, repeated, and often rendered invisible through ubiquity or opacity. When a user interface nudges attention toward one outcome and away from another, when an algorithm decides creditworthiness in ways even its creators cannot fully explain, when a database schema omits entire categories of human experience, when a network effect tips a market toward a single platform—these are not simply convenient tool choices. They are sociotechnical realities with power effects.

This framework provides practitioners with a structured diagnostic lens: identify what technologies are active; classify their types and affordances; surface the values and assumptions embedded in their design; locate where they distribute power (who controls, who benefits, who is constrained); map the visibility failures they create (black-box opacity, infrastructural invisibility, false neutrality claims); and detect where they are reshaping what is possible, visible, and invisible in the scenario. Because technology analysis is uniquely vulnerable to its own blindnesses—the myth of technical neutrality, the illusion that design choices are inevitable, the invisibility of what infrastructure makes impossible—the framework includes a mandatory tiered Hiddens cross-check that uncovers where the technology analysis itself is fragile.

## Why does Technology matter for Hiddens work?

Technology is one of the primary hiding mechanisms in complex scenarios. Hidden values and assumptions embedded in technical design (algorithms encode bias; interfaces embody assumptions about users that are invisible to those users) operate at a different level than human secrecy or deliberate concealment. The designer of a loan algorithm may have no intent to discriminate, yet the algorithm may systematically deny credit to certain groups because the training data, the feature selection, or the optimization target embeds structural inequality. Infrastructural invisibility (technology becomes invisible through ubiquity—it shapes what is possible without being noticed as a constraint) occurs because the technical substrate is so familiar that it disappears from analysis. Black-box opacity (technical systems whose internal workings are not legible to users, investigators, or even operators) creates a zone where harms can accumulate without detection. Affordance blindspots (what a technology makes easy becomes the default; what it makes hard becomes invisible as a choice that could be otherwise) mean that entire possible actions are excluded from consideration simply because the technology does not support them or makes them prohibitively difficult.

These Hiddens operate across multiple Hiddens meta-categories simultaneously. Perceptual (what is not seen), Systemic (what emerges from interaction of design and use), Informational (what the technology does and does not measure), Temporal (what becomes locked-in over time), Relational (who controls and who is controlled), and Ontological (what categories and possibilities the technology recognizes or forecloses). This framework pairs with the Framework of Hiddens to surface these systematic failures in understanding technology's effects. By mapping affordances, surfacing embedded assumptions, identifying who controls the technology and who benefits from its design choices, and locating zones of opacity and invisibility, technology analysis reveals what remains hidden when only functional capability and efficiency are examined.

## What does this framework produce?

The framework operationalises technology analysis through six core elements:

1. **A taxonomy of 30 technology types** organised into six meta-categories (Foundational Technologies, Interface & User-Facing Systems, Data & Information Management, Algorithmic & Decision Systems, Infrastructure & Coupling, Meta-Technologies & Governance) that recur across domains and enable rapid classification and comparison.

2. **Five cross-cutting dimensions** (User Agency & Affordance Shape, Technical Opacity & Legibility, Power Distribution & Control, Embedded Values & Assumptions, Lock-in & Path Dependency) that profile any technology system and explain why different actors perceive different constraints and opportunities.

3. **Ten dynamics patterns** (Obsolescence & Replacement, Lock-in & Network Effects, Emergent Coupling & Sociotechnical Drift, Algorithmic Amplification of Bias, Infrastructure Invisibility & Assumed Neutrality, Feature Creep & Scope Drift, Measurement Gaming & Proxy Drift, Vendor Dependency & Switching Cost, Cascading Failure & Fragility, Designed Obsolesce & Planned Degradation) that describe recurring technology failure and lock-in patterns.

4. **Three interface types** (User-Facing Affordances & Constraints, Systemic Effects & Coupling, Governance & Control Levers) that make visible where technologies interact, clash, or nest—zones of high risk and opportunity.

5. **Hiddens source analysis and tiered Hiddens scans** that surface eight systematic sources of technology-analysis blindness (Design Determinism Invisibility, Black-Box Opacity, Neutrality Myth, Affordance Blindspots, Infrastructure Invisibility, Embedding Assumptions Invisibility, Power Distribution Concealment, Lock-in Concealment) and map them to the six Hiddens meta-categories.

6. **A six-step application protocol** that moves from technology inventory through type classification, affordance mapping, dimensional profiling, dynamic/risk analysis, and governance design, producing standard registers (Hiddens, Evidence, Hypothesis/Test Backlog, Information Requests) that integrate with the broader Analytical Series workflow.

The framework populates shared registers (Group Coverage Matrix, Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog) that enable hand-off to downstream frameworks (Decisions, Interventions, Governance, Risk, Responsibility).

## How to use this framework

Invoke this framework when technology is a plausible factor in the scenario (systems are digital or algorithm-driven, platforms mediate activity, data systems shape what is visible, infrastructure couples activities, decisions are made by automated systems, or harm/risk involves technical design choices). The framework works in both Rapid Run Mode (lightweight technology inventory and affordance scan) and Investigative Run Mode (deep dimensional analysis, full Hiddens scanning, stress testing against failure scenarios).

Default execution is Light Depth Framework Execution: list the focal technologies, assign types from the 30-type taxonomy, profile one or two critical dimensions (often User Agency & Affordance Shape and Technical Opacity), spot obvious interface risks, run a Tier 1 Hiddens scan (all six meta-categories touched lightly, with focus on design-embedded values and black-box opacity). Escalate to Full Depth when consequence is high, evidence is contested, embedded assumptions are challenged, tight sociotechnical coupling exists, or past technology implementations have produced unintended harms.

For LLM execution, see §1.6 for the complete LLM integration specification. The framework is designed to be directly executable by an LLM given a scenario, the Operating Guide, and the six core elements, producing disciplined technology maps with explicit Hiddens, F/I/A/U tagging, affordance analysis, and bounded closure.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Technology is a designed artefact, system, platform, algorithm, or protocol that shapes what is possible, visible, and invisible in a given scenario. Technologies are not neutral tools; they encode choices about how to solve problems, who can use them and how, what data they consume and produce, what they make easy (affordances) and what they make hard (constraints). These choices are embedded, repeated at scale, often rendered invisible through ubiquity or technical opacity, and frequently treated as inevitable technical necessities when in fact they are contingent design decisions.

Technology analysis asks: What designed artefacts are active? What affordances and constraints do they create? What values, assumptions, and power distributions are embedded in their design? Where do they create blindspots or hide information? What becomes possible, invisible, or impossible as a result of their presence? How are users and other stakeholders affected, and who benefits from the design choices made?

Because technologies operate at multiple levels simultaneously—as functional systems (what they compute or automate), as power systems (who controls them and for whose benefit), as epistemic systems (what they measure, what they assume, what they make invisible), and as sociotechnical systems (how they reshape human behaviour, institutions, and possibilities)—the framework must address all four. A loan algorithm is simultaneously a computational system (calculates credit decisions), a power system (controls access to capital), an epistemic system (what it measures as creditworthiness may systematically exclude certain populations), and a sociotechnical system (changes how credit decisions are made, who can appeal them, and what data is collected about applicants).

The framework pairs with **Framework of Hiddens** as the critical visibility audit layer. Technology is uniquely generative of Hiddens: design choices are invisible to users unless explicitly surfaced; algorithms are opaque even to their creators; infrastructure invisibility through ubiquity means the substrate is not analysed; affordance blindspots mean that impossible actions are not even conceived of; power distribution is disguised as technical necessity; embedded values are claimed as neutral objectivity. Tier 1 and Tier 2 Hiddens checks provide fast detection of these patterns; Tier 3 escalation means running the full technology Hiddens analysis with mechanism mapping, detection design, and remediation strategy.

## 1.2 Assumptions & Preconditions

Technology analysis often fails because implicit assumptions are left untested: technologies are treated as independent artefacts rather than sociotechnical systems; design choices are treated as inevitable rather than contingent; the boundaries of the technology system are poorly defined; the distribution of power and control is assumed rather than mapped; embedded assumptions are taken as universal rather than culturally specific; and evidence of harms is discounted because the technology is claimed to be neutral or objective.

### Assumptions Register
| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| The focal technology can be bounded and distinguished from its sociotechnical context. | Structural | Analysis treats technology as isolated; sociotechnical coupling effects are missed; feedback loops and emergent harms go undetected. | Map the technology's inputs and outputs; identify feedback loops with social processes (user behaviour, institutions, norms); test whether removing the technology would change the system significantly. | Accept provisional boundary; mark coupling dependencies as Unknowns; escalate for Hiddens scan (Tier 2–3) if tight coupling is suspected. |
| Design choices are knowable or at least documentable through design intent statements, code review, or designer interviews. | Method | Black-box opacity remains; embedded assumptions are not surfaced; design intent diverges from actual effect and is difficult to detect. | Request design documentation; interview designers and product owners; analyse code/algorithms if accessible; compare design intent to actual user behaviour and outcomes. | Document gaps in design knowledge; run behavioural/outcome analysis instead; treat as Unknown and flag for Hiddens escalation. |
| Technology artefacts can be classified within a stable taxonomy (6×5). | Structural | Category confusion; interventions target wrong technology class; analysis loses comparability and replicability. | Test taxonomy against diverse cases (legacy systems, cloud platforms, algorithms, hardware, protocols, governance tech); track "none-of-above" frequency; refine extensions while maintaining canonical mapping. | Use domain-specific extensions; maintain explicit mapping back to canonical 30 types; version governance. |
| Technical affordances and constraints are stable and can be accurately assessed. | Method | Affordance analysis is outdated when actual features change; updates and patches alter what is easy/hard; user workarounds or hacks create de facto affordances different from design intent. | Document version/release date of technology assessment; track feature changes and updates; test actual user workflows against design affordances; identify workarounds and shadow practices. | Update assessment before closure; flag version dependencies as Assumptions in Evidence Ledger; recommend monitoring for drift. |
| Embedded values and assumptions in technology design are identifiable and distinct from emergent effects. | Epistemic | Design intent vs actual effect divergence is large; we cannot cleanly assign responsibility for harms; interventions based on intent may miss actual harms. | Conduct impact analysis (who is actually affected, how, in what distribution); compare to design intent; document divergences; identify whether divergence is unintended consequence or reveals contested design intent. | Treat as Unknown; flag as high-consequence Hiddens; escalate for deeper investigation; prioritise remediation of actual harms regardless of intent. |
| Power and control distribution can be mapped through explicit governance and authority structures. | Method | Shadow power and informal control networks are missed; invisible authority through technical design is not detected; de facto control differs from de jure authority. | Map formal authority and governance; identify actual decision-makers and veto-holders; analyse who uses/interacts with technology vs who controls it; interview operators and users about informal practice; track divergence from policy. | Accept gaps in power mapping; flag as Hiddens candidates; conduct ethnographic or interview-based power analysis; escalate if control mismatches governance. |
| Harms from technologies are observable and measurable in a timely way. | Practical | Harms accumulate silently; delayed harms are not detected until acute; measurement systems do not capture harm signatures relevant to marginalised populations. | Design early-warning indicators for potential harms; collect disaggregated outcome data; establish feedback loops with affected populations; monitor for drift in outcomes and unintended side effects. | Accept lag and surprise in harm detection; build more redundancy and safety margins into systems; escalate monitoring cadence; commit to periodic re-assessment. |

### Preconditions Checklist
| Precondition | Required? | Evidence | Owner | Verification | Workaround |
|---|---|---|---|---|---|
| Focal technologies and their boundaries are identified. | Y | Technology inventory; version/release information; system architecture or integration maps; scope statement. | Product/technology owner | Verify at Start-of-Run; check completeness against stakeholder interviews. | Build inventory through discovery interviews; use org charts and system diagrams; accept provisional boundaries; mark gaps as Unknowns. |
| Design intent and documentation are available or reconstructable. | Conditional | Design documents, product roadmaps, RFP/requirements, designer interviews, code comments, architecture diagrams. | Product owner / architect / engineering lead | Request design artefacts; conduct designer interviews; review code or algorithm documentation if accessible. | If unavailable, use behavioural/outcome analysis instead; treat design intent as Unknown; flag as Hiddens candidate. |
| User and stakeholder mapping is complete enough to identify affected populations. | Y | User/persona list; stakeholder map; usage patterns; distribution of access and impact. | Product owner / UX research / operations | Verify through user interviews, telemetry, usage data, or proxy indicators. | Use sampling or interviews to identify representative affected populations; mark population coverage gaps as Unknowns. |
| Evidence of actual impact (both intended and unintended) is available or can be gathered. | Conditional | Outcome data; incident/harm reports; user feedback; audit results; third-party testing/certification. | Operations / product / compliance | Request outcome data; design probes to collect missing data (surveys, testing, incident forensics). | Document gaps in impact visibility; escalate as Hiddens (what is not measured is invisible). |
| Escalation path for contested or high-stakes technology decisions exists. | Y | Escalation policy; sponsor; dispute resolution process; governance body. | Governance owner / sponsor | Test path with a scenario before analysis starts. | Define ad-hoc escalation; record contested assumptions; flag for governance redesign. |
| Hiddens analysis scope (Light/Full, Tier depth) is agreed. | Y | Routing decision output (OG §4.3); technology risk assessment. | Lead analyst | Confirm with sponsor before running Tier 2–3. | Default to Tier 1 Light Depth; escalate if residual unknowns could change decisions or accountability. |

## 1.3 Definitions, Scope, and Non-Goals

**Definition of Technology**: Designed artefacts, systems, platforms, algorithms, protocols, and infrastructures created by humans to perform functions, shape behaviour, or manage information. Technologies are not neutral—they encode choices about how to solve problems, who can use them, what they make easy or hard, and whose interests they serve. Technology analysis examines how designed artefacts shape what is possible, visible, and invisible; distribute power and control; embed values and assumptions; and create or foreclose possibilities.

**In scope**:
- Six meta-categories and thirty core technology types (canonical 6×5 taxonomy)
- Five cross-cutting technology dimensions (user agency, opacity, power distribution, embedded values, lock-in)
- Technology dynamics patterns (10 core patterns: obsolescence, lock-in, coupling, amplification, invisibility, feature creep, gaming, vendor dependency, fragility, planned degradation)
- Affordances and constraints analysis (what the technology makes easy/hard, possible/impossible)
- Embedded values and assumptions mapping
- Power and control distribution (who controls, who benefits, who is constrained)
- Technical opacity and black-box analysis (algorithmic systems, opaque decision processes)
- Infrastructure and systemic coupling effects
- Hiddens sources, tiered Hiddens scans (Tier 1–3), and Targeted Hiddens Discovery Scans (OG §7.5)
- Responsible technology and governance design
- Monitoring, audit, and adaptation strategy

**Out of scope**:
- Detailed technical implementation and code-level analysis (use Systems and Engineering frameworks)
- Full financial and business model analysis (use Resources and Incentives frameworks)
- Detailed governance and accountability allocation (see Governance and Responsibility frameworks)
- Vendor selection and procurement process (use Decisions and Interventions frameworks)
- Domain-specific technical standards and compliance (use relevant industry and assurance standards as inputs)

**Common confusions ("Technology is not …")**:
- Not only software; includes hardware, platforms, protocols, and algorithmic systems
- Not synonymous with "automation"; technology shapes human behaviour and possibility, not just automates tasks
- Not neutral tools; all design encodes choices and values
- Not purely technical problems; technology is always sociotechnical (embedded in social practices, institutions, and power relationships)
- Not separate from culture and institutions; technology and society are co-constitutive
- Not inevitably progressive; technological change creates winners and losers, enables and forecloses possibilities

## 1.4 Position in the Series (Upstream / Middle / Downstream)

**Upstream (signals/understanding)**: Situations (context and constraints); Evidence and Diagnosis (what is known); Systems (structure and feedback); Processes (activity flows); Time and Scale (relevant horizons and magnitudes); Boundaries (what is in/out); Causation (how things work).

**Middle (this framework's role)**: Identify what technologies are in play, what they afford and constrain, what values and assumptions they embed, what power distributions they create, and what visibility failures they generate. Translate understanding of situation, causation, and systems into a technology-aware map that reveals design effects and sociotechnical risks.

**Downstream (action/governance)**: Decisions (choices about technology adoption, redesign, replacement); Interventions (technology-aware change levers); Governance (control, authority, accountability); Responsibility (who is accountable for technology choices and harms); Risk (resilience, contingency, redundancy in technology systems); Learning & Adaptation (technology evolution and renewal strategy).

**Group assignment (Primary)**: G2 — Mechanism, dependencies & systems (Mechanism Group)
**Group assignment (Secondary)**: None
**Stage assignment**: Middle (consumes Upstream understanding; feeds Downstream decisions and governance)
**Run mode selection**: Rapid Run Mode for technology inventory and affordance scan; Investigative Run Mode for high-stakes design choices, embedded assumption contestation, tight sociotechnical coupling, or harm analysis (per OG §D.9.2)
**Operating Guide routing**: Apply decision logic at Start-of-Run and Pre-Closure (OG §4.3) to set minimum group coverage and per-framework Full Depth / Light Depth plan
**Non-conflation invariant**: Do not conflate Run Mode with Framework Execution Depth (OG §D.10.1)
**Iteration loop**: Execute within OG §5.0 (Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close)
**Framework Index**: This framework is one of 36 in the Analytical Series; Technology occupies G2 (see OG §3.2 for complete Framework-to-Group mapping)

## 1.5 Crosswalk Summary
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|---|
| Framing & scope | Situations; Boundaries; Dimensions; Scale; Time | What context matters; what is in/out scope; relevant magnitudes and horizons; temporal lags and windows. | What technologies are in play; what do they afford and constrain; what becomes visible/invisible/impossible because of them? |
| Mechanism & understanding | Systems; Relations; Processes; Causation; Evidence; Diagnosis | How things work; causal chains and feedback; what evidence supports claims; where understanding is weak. | How do technology designs shape causal chains; what assumptions are embedded in technical systems; where do technology effects diverge from design intent; what evidence gaps hide harm or bias? |
| Agency & motivation | Agents; Personas; Incentives; Power; Competencies; Responsibility | Who acts; what drives decisions; who has power; who is responsible; what capacities exist. | What technologies do different agents control; who designs and governs technologies; how do technical affordances shape what agents can do; whose interests are served by design choices. |
| Meaning & legitimacy | Culture & Norms; Perspectives; Narratives; Communications; Legitimacy; Values | What is taken as real; whose voice is heard; what narratives dominate; what is valued. | What values are embedded in technology design; what narratives claim technical neutrality when design is actually value-laden; whose perspectives are excluded from design; how does technology reshape meaning and legitimacy. |
| Epistemics & visibility | Beliefs; Evidence; Uncertainties; Failures; Hiddens; Knowledge; Metrics | What is known/unknown/hidden; what evidence is trusted; where knowledge is fragmented. | What does technology measure and not measure; what knowledge does technology create and foreclose; where are black-box opacity and design-embedded assumptions invisible; what harms are unmeasured or undetected. |
| Action & governance | Decisions; Interventions; Governance; Risk; Learning & Adaptation | How are choices made; what levers exist for change; who decides; how is risk managed; how do we learn. | How do technology design choices constrain or enable decisions; how are technologies governed and who is accountable; how do we detect harms and adapt; what are the lock-in and path-dependency risks. |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Technology_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Technology when… | Use neighbour instead when… |
|---|---|---|
| Systems | Analysing how designed artefacts, algorithms, and platforms shape affordances, constraints, and what is possible/visible; embedding of design choices and values. | Analysing abstract structure, feedback loops, and non-linear dynamics independent of design choices; studying emergent patterns from component interactions; analysing governance structure. |
| Processes | Analysing how technology shapes activity sequences, workflows, and behaviour; how affordances change what workflows are possible. | Analysing activity flows and sequences independent of technology substrate; studying process efficiency and sequencing; examining interaction protocols or work practices that are technology-independent. |
| Resources | Analysing what resources technology makes available, easy, or hard to access; constraints on action due to technical design. | Analysing resource allocation, fungibility, and renewal independent of technical system; examining capacities and feasibility; studying resource depletion and bottleneck dynamics. |
| Institutions/Governance | Analysing rules and governance embedded in technology design; how technology enforces or subverts institutional rules. | Analysing formal governance structures, authority, and decision-rights; studying rules and compliance frameworks; examining institutional design for authority alignment. |
| Power | Analysing who controls technology design, who benefits from design choices, and how technology redistributes power and agency. | Analysing abstract power distribution and influence independent of technology; studying bargaining power and dependency relationships; examining agency and who can affect outcomes. |

### 1.6.3 Routing triggers
- Scenario involves digital systems, platforms, algorithms, or data systems
- Design choices appear to have cascading or hidden effects
- Technology is claimed to be neutral but stakeholders dispute this claim
- Bias, harm, or unintended consequences are associated with a technical system
- Lock-in or vendor dependency is a concern
- Infrastructure is opaque or not fully understood
- User affordances or constraints are limiting outcomes
- Technical feasibility is contested
- Responsible technology or AI governance is a requirement
- Harm investigation involves algorithm or platform design

---

# 2. Meta-Categories of Technology

## 2.1 Meta-Categories Table
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Foundational Technologies | What underlying computational, material, or mechanical substrates enable other technologies? | Physical layers, computational primitives, power systems, materials, basic protocols | Hardware, semiconductors, networking infrastructure, databases, cryptographic primitives, quantum systems |
| II | Interface & User-Facing Systems | How do technologies present possibilities and constraints to users? What affordances do they create? | User agency, interaction design, accessibility, perception, what is easy/hard to do | User interfaces, dashboards, APIs, accessibility features, command-line tools, physical controls, voice interfaces |
| III | Data & Information Management | How do technologies collect, store, process, and expose information? What do they measure and what do they hide? | Data architecture, measurement, information flows, knowledge representation, epistemic effects | Databases, data pipelines, analytics platforms, knowledge graphs, measurement systems, audit trails, logging infrastructure |
| IV | Algorithmic & Decision Systems | How do technologies make decisions or recommendations? What logic is embedded and how transparent is it? | Decision automation, optimization, prediction, recommendation, opacity, bias, learning systems | Machine learning models, decision trees, optimization algorithms, ranking systems, recommendation engines, automated control systems |
| V | Infrastructure & Coupling | How do technologies create interdependencies and systemic effects? What are the network effects and feedback loops? | Systemic coupling, network effects, scaling, bottlenecks, cascade risk, standards and interoperability | Cloud infrastructure, platforms, standard protocols, supply chains, network effects, critical dependencies |
| VI | Meta-Technologies & Governance | How are technologies governed, monitored, and evolved? What technologies manage other technologies? | Governance artefacts, monitoring, audit, policy enforcement, technology lifecycle, versioning and updates | Governance platforms, monitoring and observability systems, policy automation, compliance frameworks, versioning systems, update mechanisms |

## 2.2 Meta-Category Descriptions

### I. Foundational Technologies
- **Definition**: The underlying computational, material, or mechanical substrates that enable higher-level technologies. These are the infrastructure of infrastructure—silicon, electricity, networking, storage, cryptography, basic protocols.
- **Diagnostic cues**: Foundational technologies become visible when they fail or become scarce (power outages, chip shortages, internet connectivity loss); when they scale and create bottlenecks (bandwidth constraints, storage limits); when they become sites of geopolitical competition (semiconductor manufacturing, data centres); when they determine what is technically feasible upstream.
- **Typical failure mode**: Foundational technologies are often invisible (assumed reliable and abundant) until disruption occurs; their constraints limit what is possible at higher layers; decisions made assuming abundant resources (compute, bandwidth, storage) fail when foundational capacity becomes constrained.

### II. Interface & User-Facing Systems
- **Definition**: The designed systems and presentations through which users interact with technology. These are the boundary between human agency and technical system—what users can perceive, manipulate, and do.
- **Diagnostic cues**: Interfaces become visible through user feedback (confusion, workarounds, abandonment); through accessibility gaps (who cannot use this? who struggles?); through affordance blindspots (what actions are hard or impossible?); through nudges and dark patterns (what does the design encourage/discourage?).
- **Typical failure mode**: Interface design becomes invisible to designers (they know how it works); assumptions about user knowledge, ability, and context are baked into design and go unquestioned; affordances and constraints shape user behaviour without user awareness; dark patterns or manipulation can be defended as "standard practice" or "user error".

### III. Data & Information Management
- **Definition**: The systems that collect, store, process, integrate, and expose data and information. These systems determine what is measured, counted, visible, and analysable.
- **Diagnostic cues**: Data systems become visible through data quality problems (errors, gaps, inconsistencies); through measurement games (what gets measured gets managed, often in ways that diverge from intent); through access asymmetries (who can see what data?); through what is conspicuously absent (what is not measured?).
- **Typical failure mode**: What is measured is assumed to be what matters; what is not measured disappears from analysis and decision-making; data quality and measurement assumptions are invisible until crisis; power over who can access and interpret data is concealed in technical access controls; proxy drift (the metric drifts from what it originally measured).

### IV. Algorithmic & Decision Systems
- **Definition**: Technologies that embed decision logic, optimization, prediction, or learning. These systems automate or augment human judgment.
- **Diagnostic cues**: Algorithmic systems become visible through outcomes (who gets approved? who gets sorted to the bottom?); through opacity (how was this decision made? can we explain it?); through distributional bias (are outcomes proportional across groups?); through adversarial examples (are there edge cases or exploitable quirks?); through goal misalignment (does optimizing for this metric actually produce desired outcomes?).
- **Typical failure mode**: Algorithms are treated as objective or neutral despite being trained on biased data or optimizing for metrics that diverge from actual goals; opacity prevents detection of bias or malfunction; the algorithm is treated as source of truth rather than as provisional model subject to error; deployment scales harms beyond initial training context.

### V. Infrastructure & Coupling
- **Definition**: Shared platforms, standards, and interconnections that create network effects and systemic dependencies. These are the systems that couple activities and create cascade risk.
- **Diagnostic cues**: Infrastructure becomes visible through disruption (what breaks if this goes down?); through network effects (does value increase as more people use it?); through switching costs (how hard is it to move to an alternative?); through standardization (how much does this constrain alternatives?); through governance questions (who controls the infrastructure?).
- **Typical failure mode**: Infrastructure is assumed to be stable and infinitely scalable; systemic coupling creates cascade risk that is not fully modelled; switching costs create lock-in that constrains alternatives; network effects concentrate power; governance of shared infrastructure is unclear or contested.

### VI. Meta-Technologies & Governance
- **Definition**: Technologies that manage, monitor, govern, and evolve other technologies. These are governance artefacts—policies automated in code, monitoring systems, audit trails, versioning and update mechanisms.
- **Diagnostic cues**: Meta-technologies become visible through governance disputes (who decides about updates? what is the rollback process?); through monitoring failures (what is not observed?); through control asymmetries (who can change this?); through policy enforcement (does the technical system enforce policy or subvert it?).
- **Typical failure mode**: Governance technologies are designed but not actually used or are designed by those with technical power but not by those who are governed; monitoring and audit are assumed to be comprehensive when significant activities may be invisible; update and rollback processes are not tested until crisis; policy is embedded in code without stakeholder input or contestation.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- Canonical baseline: 6 meta-categories × 5 types = 30 core types.
- This framework: 30 types. No deviation from baseline.
- Mapping back to baseline: All 30 types map directly to the canonical 6×5 structure.

## 3.1 Types (Category I: Foundational Technologies)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 1 | Computational Primitives & Hardware | The physical substrate (processors, memory, silicon, semiconductors) that performs computation. | Bottlenecks manifest as performance degradation; failures are abrupt (crashes, errors); constraints are physical (power, heat, latency). | Assumed infinite capacity leads to overcommitment; failures are attributed to software when root cause is hardware constraint; geopolitical dependencies in manufacturing are hidden. |
| 2 | Power & Energy Systems | Infrastructure that provides electrical power and manages energy consumption. | Failures are visible as complete outages; efficiency becomes visible during scarcity; dependencies are often hidden in supply chain and data centre location. | Assumed reliability masks cascading risk from concentrated suppliers; energy consumption of computation is invisible (embodied carbon, water usage); power cuts are treated as external shocks rather than design constraints. |
| 3 | Networking Infrastructure | Physical and logical systems (cables, routers, protocols, standards) that enable communication. | Latency, packet loss, and bandwidth become visible during congestion; topology and bottlenecks are often not mapped; DNS and routing failures are system-wide. | Network effects and topology are assumed stable; single points of failure are hidden in redundancy assumptions; international routing and sovereignty questions are invisible. |
| 4 | Storage & Persistence Systems | Databases, file systems, data warehouses, and other systems that persist data. | Storage capacity becomes visible during fullness; corruption and data loss become visible when they occur; access patterns and query performance become visible through monitoring. | Assumed reliability masks backup and recovery weaknesses; data model assumptions are invisible to users; storage costs scale non-linearly and surprise planners; data retention and deletion policies are often undefined. |
| 5 | Cryptographic & Security Primitives | Mathematical and computational foundations for encryption, authentication, verification. | Become visible through breach (assumption of security broken); standards become visible when they are deprecated (e.g., SHA-1); key management challenges emerge as systems scale. | Cryptography is treated as solve-all despite being narrow (secrecy, not truth-finding); key rotation and management are often forgotten; cryptographic assumptions are brittle (single broken primitive can cascade). |

## 3.2 Types (Category II: Interface & User-Facing Systems)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 6 | Direct Manipulation & Interaction Paradigms | Design patterns through which users manipulate or control systems (menus, buttons, sliders, gestures, voice commands). | Become visible through user feedback (confusion, errors, workarounds); accessibility gaps reveal assumption divergence; dark patterns/nudges shape behaviour subtly. | Design assumptions about user knowledge/ability are invisible to designers; affordances shape behaviour without user awareness; manipulation can be defended as standard practice. |
| 7 | Information Presentation & Visualization | How information is displayed to users (dashboards, charts, tables, alerts, notifications). | Become visible through user interpretation failures; through missing information (what is conspicuously absent?); through nudging (what is emphasized vs buried?). | Visualizations are assumed objective despite encoding designer choices; omissions in display shape what is considered; defaults (e.g., chart axes) invisibly shape interpretation. |
| 8 | Accessibility & Inclusive Design | Features that enable users with different abilities to use the technology. | Become visible when users cannot use the system; absent when assumed irrelevant; manifest through legal/regulatory requirements. | Accessibility is often treated as add-on rather than fundamental; excluded populations are often marginalised; accessibility testing is often insufficient. |
| 9 | Authentication & Authorization Systems | Technologies that verify who users are and what they can access. | Become visible through login/access failures; through permission disputes; through account takeovers. | Assumptions about user identity and uniqueness are often invisible; delegation and shared accounts create accountability gaps; authorization is often too coarse-grained. |
| 10 | APIs & Integration Points | The interfaces through which systems connect to other systems and applications. | Become visible through integration failures; through breaking changes (API updates); through version mismatches. | API design assumptions are invisible to users; backward compatibility is often assumed but not guaranteed; rate limits and costs are often hidden. |

## 3.3 Types (Category III: Data & Information Management)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 11 | Data Collection & Measurement Systems | Systems that collect, log, and measure data about activity, state, users, environment. | Become visible through data quality issues; through measurement bias; through privacy violations. | What is measured is assumed to be what matters; measurement overhead is invisible; bias in collection is often not detected; consent and notice about collection are often insufficient. |
| 12 | Data Integration & Fusion | Systems that combine data from multiple sources into unified views. | Become visible through data conflicts; through integration failures; through inconsistent views. | Assumptions about data quality and consistency are invisible; schema mismatches are often hidden; lineage and provenance are often not tracked. |
| 13 | Knowledge Representation & Ontologies | Schemas, taxonomies, and data models that structure how information is categorised and related. | Become visible through inability to represent something (what is conspicuously absent?); through categorization disputes. | Design choices about categories are invisible (e.g., gender as binary, address as single location); missing categories mean missing information; ontologies encode assumptions about what exists and matters. |
| 14 | Analytics & Aggregation Systems | Systems that analyse data to find patterns, trends, correlations. | Become visible through spurious correlations; through aggregation hiding bottlenecks; through statistical fallacies. | Aggregation hides outliers and variation; statistical significance is confused with practical significance; causation is confused with correlation. |
| 15 | Audit Trails & Forensic Records | Systems that log and record activities for compliance, forensics, and accountability. | Become visible when audits fail; when logs are lost; when they are incomplete or gamed. | Logging is assumed comprehensive when activities can be invisible; log tampering is often not detected; retention policies are often undefined; who can access logs is often unclear. |

## 3.4 Types (Category IV: Algorithmic & Decision Systems)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 16 | Machine Learning Models & Training Systems | Systems that learn decision rules from data through statistical optimization. | Become visible through distributional bias in outcomes; through drift (model performance degrades over time); through adversarial examples. | Training data bias is invisible to model; model objectives are often proxies rather than true goals; drift and degradation are often not monitored; retraining decisions are often reactive rather than proactive. |
| 17 | Optimization & Resource Allocation Algorithms | Systems that find solutions to constrained optimization problems (scheduling, routing, allocation). | Become visible when solutions are suboptimal or unexpected; when constraints are violated; when tradeoffs diverge from stated objectives. | Objectives are assumed aligned with actual goals; edge cases and constraint violations are often not detected; solutions are treated as optimal when only locally optimal; fairness and distributional consequences are often ignored. |
| 18 | Ranking & Recommendation Systems | Systems that order options or suggest items to users based on predicted preference or relevance. | Become visible through user dissatisfaction or divergence (recommendations don't match user goals); through feedback loops (popular items get more recommendations). | Ranking metrics are assumed to align with user goals; feedback loops and self-fulfilling prophecies are invisible; diversity and serendipity can be optimised away; power to rank is often invisible. |
| 19 | Decision Support & Rule-Based Systems | Systems that augment or automate human judgment through rules, logic, or structured processes. | Become visible when rules fail or produce unintended consequences; when transparency is required; when rule conflicts emerge. | Rules are assumed to cover all cases; exceptions are often not handled; hard-coded business logic makes change difficult; who sets and updates rules is often unclear. |
| 20 | Predictive & Forecasting Systems | Systems that extrapolate from historical data to predict future states or events. | Become visible when predictions fail; when distribution shift occurs; when prediction horizon exceeds training data scope. | Assumed stationary means future is modelled as past; training data biases are invisible; uncertainty is often not quantified; prediction confidence is often miscalibrated. |

## 3.5 Types (Category V: Infrastructure & Coupling)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 21 | Platforms & Digital Ecosystems | Shared digital infrastructure that others build upon (cloud platforms, app stores, social media platforms). | Become visible through network effects (value increases as more adopt); through power concentration (platform controls terms); through switching costs. | Network effects are assumed benign; platform power over complementors is invisible; terms of service are not negotiated; lock-in is not fully appreciated until migration time. |
| 22 | Standards & Interoperability Protocols | Shared specifications (technical standards, data formats, communication protocols) that enable interoperability. | Become visible through incompatibility; through mandatory adoption (standards setting power); through lock-in effects. | Standards are assumed neutral when they encode design choices; power to set standards is invisible; incompatibility with alternatives is often not appreciated. |
| 23 | Supply Chain & Vendor Dependencies | Systems that depend on external suppliers for critical components or capabilities. | Become visible through disruption; through single points of failure; through vendor lock-in. | Dependencies are often not fully mapped; single points of failure are hidden in redundancy assumptions; vendor power is not fully appreciated until disruption. |
| 24 | Network Effects & Feedback Loops | The dynamics where system value increases with adoption or where actions reinforce themselves. | Become visible through growth acceleration or collapse; through market concentration. | Feedback loops are assumed benign; positive feedback can lead to tipping points and irreversibility; power concentration from network effects is invisible. |
| 25 | Scaling & Capacity Limits | The physical and economic constraints that limit how much a technology can scale. | Become visible through performance degradation or outages; through cost explosion at scale. | Assumed linearity masks non-linear scaling costs; bottlenecks are hidden until they bind; feasibility assumptions are not stress-tested. |

## 3.6 Types (Category VI: Meta-Technologies & Governance)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 26 | Governance Platforms & Policy Automation | Technologies that enforce policies, govern access, and make governance decisions (permission systems, policy engines, compliance automation). | Become visible through policy violations; through access disputes; through exemption requests. | Policies are assumed enforced when they may be subverted; shadow systems and workarounds are invisible; who sets and changes policies is often unclear. |
| 27 | Monitoring, Observability & Alerting Systems | Technologies that observe system state, detect anomalies, and alert operators. | Become visible through monitoring blindspots (what is not observed?); through alert fatigue; through missed incidents. | Assumed comprehensiveness masks gaps; observability is often biased toward performance rather than harms; alerts can be drowned out by noise. |
| 28 | Versioning, Updates & Change Management | Technologies and processes that manage changes, updates, and version transitions. | Become visible through breaking changes; through upgrade failures; through rollback difficulties. | Updates are assumed backward compatible when they are not; testing is often insufficient; rollback plans are often not tested; users are not always notified of changes. |
| 29 | Configuration & Feature Management | Systems that allow customization, feature flags, and parameter tuning after deployment. | Become visible through configuration sprawl (too many options to manage); through feature flag debt; through misconfiguration. | Configuration assumptions are invisible to operators; incompatible configurations are not always caught; technical debt in feature flags accumulates. |
| 30 | Audit, Compliance & Certification Systems | Technologies and processes that verify conformance to standards, policies, regulations. | Become visible through audit failures; through compliance violations; through certification questions. | Audits are assumed comprehensive when significant activities can be hidden; audit is often reactive rather than continuous; gaming and superficial compliance are possible. |

## 3.7 Extending the Taxonomy
| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | 30 types across 6 meta-categories (canonical 6×5). |
| Domain-specific refinement | Refine types for domain-specific technologies (e.g., biotechnology, quantum, AI/ML governance), but maintain mapping to canonical 30. Preserve comparability by explicit type mapping. |
| Preserving mappability | When extending, ensure every new type maps to a canonical type (substitution), refines a canonical type (specialization), or combines multiple canonical types (composition). Do not exceed 40 types without explicit deviation discussion. |
| Structural invariants | Maintain six meta-categories. Do not collapse or recombine meta-categories without documented deviation and mapping. |
| Periodic reassessment | Reassess every 12–18 months as new technology patterns emerge. Consider Tier 2 Hiddens deepening if new types are frequently identified. |
| Versioning & governance | New types should be proposed, reviewed for canonical mapping, tested in real scenarios, and then incorporated with version number update (e.g., v1.0 → v1.1). Major structural changes warrant major version bump (v1.0 → v2.0). |

---

# 4. Cross-Cutting Dimensions of Any Technology

## 4.1 Dimensions Table
| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| 1. User Agency & Affordance Shape | Extent to which the technology affords user choice and control vs constrains or nudges behavior in particular directions. What does the technology make easy/hard/possible/impossible for users? | Spectrum from high agency (users can accomplish many goals) to low agency (predetermined paths, limited options); identifies affordances (easy actions) and constraints (hard/impossible actions). | Interview users about what they can/cannot do; identify designed pathways vs alternatives; check for escape hatches or workarounds; observe actual usage patterns vs intended use. | Reveals whether technology empowers or constrains; identifies where user goals diverge from design intent; highlights opportunities for user manipulation or dark patterns; explains user satisfaction or abandonment. |
| 2. Technical Opacity & Legibility | Extent to which the technology's internal workings, decision logic, and behaviour are transparent or opaque to users, operators, and even designers. How explainable are its actions? | Spectrum from transparent (code readable, logic auditable, decisions explainable) to black-box opaque (internal logic hidden, decisions unexplainable even by creators); includes documentation, code access, interpretability. | Request design documentation and code; ask operators/creators how the system works; check if algorithm behaviour can be explained; test whether unexpected outcomes can be debugged; assess third-party auditability. | Reveals where harms could accumulate undetected; shows where diagnosis is difficult; identifies where operators/users must trust without understanding; highlights audit and accountability risks. |
| 3. Power Distribution & Control | Extent to which the technology is controlled by one entity, distributed among multiple stakeholders, or subject to user control. Who makes decisions about the technology? Who can modify it? Who benefits from its design? | Spectrum from highly concentrated (single vendor/operator controls; others have no say) to distributed (multiple stakeholders share control); includes decision-making power, modification power, veto power, benefit distribution. | Map who has authority over technology changes; identify who makes design decisions vs who operates it vs who uses it; examine who profits from deployment; check whether affected populations have voice in design/governance. | Reveals asymmetries in power; identifies who is accountable; shows where governance is misaligned with power; highlights where lock-in and vendor dependency create vulnerability. |
| 4. Embedded Values & Assumptions | Extent to which the technology encodes particular values, worldviews, and assumptions in its design. What does the technology take as given or normal? | Spectrum from multiple values recognized (inclusive design, diverse user models) to singular values embedded (universal design assumptions, market-driven optimization, technical neutrality claimed); includes design choices about goals, metrics, categories, trade-offs. | Ask designers about their design choices and assumptions; examine what categories/options are included/excluded; test design against diverse user contexts; look for whose worldview is assumed universal. | Reveals where technology is not neutral; shows whose interests are served; identifies where cultural specificity is masked as universality; highlights where assumptions may not hold. |
| 5. Lock-in & Path Dependency | Extent to which switching away from the technology is easy or costly. Are alternatives available? How much would changing cost? | Spectrum from low lock-in (easy to switch, alternatives available, low switching costs) to high lock-in (no alternatives, switching prohibitively costly, network effects or data lock-in); includes switching costs, data portability, alternative availability. | Assess cost of switching to alternative (time, money, training); check data portability (can data move?); survey market concentration (are alternatives available?); examine network effects (is value locked to this network?). | Reveals vulnerability to vendor changes; shows where choices can become irreversible; highlights where lock-in creates leverage for unwanted changes; identifies where contingency planning is needed. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | Obsolescence & Replacement | Technology becomes outdated or is superseded; older technology is abandoned; rapid platform shifts. | Newer technology offers superior functionality or lower cost; user preferences shift; standards change; investment cycle drives replacement. | Disrupts dependent systems; strands investments; skills become obsolete; migration costs are often underestimated; data loss or loss of access during transitions. | Build modular systems with interface contracts; maintain data portability; plan migration paths; avoid premature lock-in to immature technologies; maintain legacy system support during transitions. |
| 2 | Lock-in & Network Effects | Once technology is adopted, switching becomes prohibitively costly; network effects reinforce adoption; switching costs grow with scale. | Data lock-in (data is not portable); network effects (value increases with adoption); complementary investments (training, integration); switching costs exceed benefits of switching. | Creates vulnerability to vendor changes (price increases, forced updates); prevents better alternatives from being adopted; concentrates power; reduces competitive pressure on incumbent. | Negotiate data portability; build open standards support; maintain alternative skill sets; periodically re-assess switching costs; design architecture to minimize switching costs. |
| 3 | Emergent Coupling & Sociotechnical Drift | Over time, social practices, institutions, and technologies become tightly coupled; changes to one require changes to others; unintended consequences emerge. | Users adapt practices to technology affordances; institutions change policy/process to match technology; feedback loops amplify coupling; small unintended effects compound. | Changes become brittle and difficult; unintended consequences cascade; resilience decreases; adaptation becomes harder; crisis response becomes necessary when flexible response would have been better. | Design for loose coupling; maintain alternative practices/processes; periodic re-assessment of sociotechnical assumptions; monitor for emergent effects; maintain flexibility in institutions. |
| 4 | Algorithmic Amplification of Bias | Machine learning systems trained on historical data amplify existing biases; distributional bias in training data leads to biased decisions; feedback loops reinforce bias. | Training data reflects historical discrimination; optimization metrics don't account for fairness; feedback loops reinforce (popular items get more training signal); scale amplifies small biases. | Harms accumulate at scale; bias is invisible to designers trained on "objective" data; affected populations are not consulted; deployment at scale causes systemic discrimination. | Audit training data for bias; measure distributional fairness across subpopulations; include affected populations in design; use fairness constraints in optimization; monitor outcomes post-deployment; establish feedback mechanisms for harm reporting. |
| 5 | Infrastructure Invisibility & Assumed Neutrality | As infrastructure becomes ubiquitous, it disappears from analysis and is treated as neutral/inevitable. Assumptions about its reliability, neutrality, or benignity go unexamined. | Ubiquity makes infrastructure invisible (water is not considered when it is abundant); claims of technical neutrality mask value choices; assumptions are inherited rather than questioned. | Hidden infrastructure failures become catastrophic; neutral claims mask power distribution; alternatives are not considered; design choices that could be otherwise are treated as inevitable. | Make infrastructure visible and its assumptions explicit; periodically audit "neutral" technical systems for embedded values; maintain awareness of alternatives; design redundancy and graceful degradation. |
| 6 | Feature Creep & Scope Drift | Over time, additional features are added; scope expands beyond original design; system becomes larger, more complex, harder to maintain. | Each feature seems individually justified; cumulative effects are not tracked; sunk costs make it hard to say no; market pressures or competitive features drive additions. | Complexity reduces reliability; performance degrades; unintended interactions increase; maintenance costs increase; original purpose becomes obscured. | Maintain strict feature prioritization; regularly audit feature usage; build modular architecture to isolate effects; periodically remove unused features; establish complexity budgets. |
| 7 | Measurement Gaming & Proxy Drift | Systems optimized for measured metrics drift away from actual goals; metrics are gamed; proxies diverge from what they were supposed to measure. | Metric becomes optimization target; short-term gaming is easier than long-term goal achievement; feedback loops reinforce metric over actual goal; measurement is imperfect proxy. | System optimizes wrong target; actual performance diverges from reported performance; incentives misaligned with actual goals; accounting is real while business fails. | Use multiple metrics; include leading indicators (not just lagging); include qualitative feedback; audit metric definitions; adjust metrics based on evidence of gaming; tie accountability to outcomes not metrics. |
| 8 | Vendor Dependency & Proprietary Escalation | Dependency on vendor increases over time; vendor increases prices, forces upgrades, changes terms; switching becomes impossible; vendor captures increasing share of value. | Switching costs increase; vendor has monopoly power; path dependency traps customer; vendor faces competitive pressure and raises prices to extract more value. | Organization becomes dependent on vendor's decisions; vendor can force unwanted changes; costs increase; negotiating power decreases; alternatives are no longer viable. | Maintain competitive bidding; negotiate long-term price stability; require data portability; keep skills current with alternatives; periodically evaluate switching costs; diversify vendor dependency. |
| 9 | Cascading Failure & Fragility | Systems become fragile over time; small failures cascade; resilience decreases; critical failures become more likely. | Tight coupling increases; redundancy is eliminated to reduce costs; feedback loops amplify shocks; monitoring is insufficient for early warning. | Single failure propagates widely; crisis response becomes necessary; system recovery is slow; opportunity for prevention is missed. | Build redundancy at critical junctures; maintain loose coupling; design graceful degradation; monitor early-warning signals; maintain manual overrides and workarounds. |
| 10 | Designed Obsolescence & Planned Degradation | Technology is designed to fail, become outdated, or lose support; vendors intentionally limit lifespan to drive replacement cycles. | Vendor wants repeat purchases; technical lock-in is intentional; updates are unavailable; repairability is designed out; software support is limited. | Drives replacement cycles and e-waste; increases total cost of ownership; creates environmental impact; forces continued vendor dependency. | Demand right to repair; support open standards and data portability; avoid proprietary formats; plan for post-vendor-support scenarios; advocate for design durability. |

---

# 6. Interface Types

## 6.1 Interface Types Table
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | User-Facing Affordances & Constraints | The designed interactions through which users exercise agency, make choices, and accomplish goals. What can users do, not do, or do with difficulty? | What affordances does this interface create? What actions are easy/hard/impossible? What are the dark patterns or nudges? What user goals are supported/unsupported? | User interfaces, menus, forms, buttons, accessibility features, command-line options, workflow designs, interaction paradigms |
| B | Systemic Effects & Coupling Interfaces | The points where technology couples with other social, institutional, or technical systems; where effects ripple beyond intended scope; where feedback loops emerge. | Where does this technology interact with other systems? What are the unintended consequences? Where are the positive/negative feedback loops? What cascades if this fails? | Platform network effects, data integration points, workflow dependencies, ecosystem interactions, infrastructure coupling, governance enforcement points |
| C | Governance & Control Levers | The points where governance decisions are made about the technology: who can access it, what policies govern it, how it is modified, who is accountable. | Who controls this technology? Who decides about updates, access, policy? How is governance exercised? Where are the accountability gaps? Who is affected but has no voice? | Permission systems, audit trails, change management processes, compliance mechanisms, policy automation, escalation paths, governance bodies |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links
- **Inputs expected**: Situation framing (Situations, Boundaries); evidence and diagnosis (Evidence, Diagnosis); system structure and processes (Systems, Processes); resource constraints (Resources); power and incentive structures (Power, Incentives); meaning and values (Culture & Norms, Narratives, Values); governance (Governance); time and scale (Time, Scale); hiddens (Hiddens).
- **Outputs provided**: Technology type classification and affordance mapping; embedded values and assumptions surface; power distribution analysis; technical opacity and black-box risk assessment; sociotechnical coupling and feedback loops; interface ownership and governance design; Hiddens candidates; monitoring and adaptation strategy; decision inputs for technology governance, replacement, redesign, or harm remediation.

## 7.2 Crosswalk Table
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|---|
| Systems | System structure, feedback loops, boundaries, leverage points | Technology design choices that shape structure and feedback; technical leverage points and constraints | Mapping how technology choices determine system behaviour and feasibility of redesign |
| Processes | Activity sequences, workflows, dependencies, bottlenecks | How technology affordances shape what workflows are possible; where technology constrains or enables process redesign | Identifying how process redesign depends on technology affordances and constraints |
| Resources | Resource constraints, feasibility, capacity | What resources technology requires and creates; affordances in resource use/sharing; constraints on allocation | Assessing feasibility of technology deployment; identifying resource bottlenecks that technology could address or create |
| Power | Power distribution, agency, control, veto points | Who controls technology design/deployment; power effects of technology affordances; who is constrained by design | Understanding whose interests are served by technology choices; locating power asymmetries in technology governance |
| Institutions/Governance | Formal rules, policies, decision authority | How technology enforces or subverts institutional rules; what governance is needed to manage technology effects | Designing governance structures that align with technology power distribution |
| Causation | Causal mechanisms, chains, feedback | How technology causally mediates outcomes; what effects are technical vs social; where causation is assumed but not proven | Distinguishing technical mechanisms from social effects; identifying where technology design shapes causal chains |
| Evidence | Evidence quality, gaps, bias risks | What evidence is available about technology performance and harms; measurement biases in technology performance assessment | Identifying gaps in evidence about technology effects; designing evidence collection for harm detection |
| Hiddens | Hidden factors, visibility failures, mechanisms | Which hiding mechanisms are active in technology design/deployment (black-box, design assumptions, value embedding, infrastructure invisibility) | Targeted analysis of technology-specific Hiddens; designing detection and remediation |

## 7.3 Integration Questions by Framework
| Framework (from OG v2.5 §3.2 canonical list) | Group | Stage | Integration questions (what Technology should ask / check) | Outputs / artefacts to pull in | Notes |
|---|---|---|---|---|---|
| Situations Context Classification | G1 | Upstream | What is the situation type, and how does it shape what technologies are relevant? How do temporal and spatial features affect technology applicability? | Situation framing, scenario timeline, spatial scope, complexity markers | Technology solutions must fit situation type; urgency affects technology viability |
| Boundaries | G1 | Upstream | Where are system boundaries? What is in/out of scope for technology analysis? Are there governance or jurisdictional boundaries that constrain technology use? | Boundary statement, stakeholder map, authority limits, geographic/regulatory scope | Technology effects may cross stated boundaries; governance jurisdiction affects viability |
| Dimensions | G1 | Upstream | What are the relevant dimensions of the scenario? How do scale, complexity, and time horizon affect technology choices? | Dimension profiles, scale analysis, temporal framing | Technology scalability and timing must match scenario dimensions |
| Realities | G1 | Upstream | What is taken as real or true in this scenario? How do different stakeholders construct reality? How might technology change what is considered real? | Reality constructions, stakeholder interpretations, assumptions | Technology can reshape reality constructions (e.g., what data systems count as real changes what is believed) |
| Scale | G1 | Upstream | At what scale(s) does the scenario operate? How does technology performance vary across scales? | Scale analysis, scaling constraints, bottlenecks | Technology that works at small scale may not scale; scaling costs and effects must be assessed |
| Time | G1 | Upstream | What is the relevant time horizon for decisions? How do technology deployment timelines and technology lifecycles align? | Timeline, decision windows, technology maturity timeline | Technology deployment duration and ROI period must fit decision timeline |
| Agents | G3 | Upstream | Who are the focal agents? What are their objectives? How do technology affordances shape what agents can accomplish? | Agent list, objectives, capabilities, constraints | Technology affordances enable/constrain what agents can do; misalignment creates failure |
| Personas | G3 | Upstream | Who are the users? What are their contexts, goals, constraints, mental models? How well does technology design match user personas? | User personas, use cases, user mental models, accessibility needs | User persona mismatch to technology design predicts poor adoption and unintended consequences |
| Incentives | G3 | Upstream | What incentives drive behaviour? How do technology affordances shape incentive effects? Do incentives align with technology design intent? | Incentive structure, motivation analysis, alignment/misalignment | Misaligned incentives can drive gaming, workarounds, or abandonment despite good technology design |
| Power | G3 | Upstream | Who has power? How does technology concentrate or distribute power? Are power structures reflected in governance? | Power distribution, control points, veto holders | Technology design reflects and can amplify power asymmetries; governance must reflect actual power |
| Responsibility | G3 | Upstream | Who is responsible for what outcomes? Does responsibility align with control and power? How does technology affect accountability? | Responsibility matrix, accountability structure, authority-responsibility alignment | Accountability gaps emerge when technology is controlled by those not responsible for outcomes |
| Competencies | G3 | Upstream | What capabilities and skills are needed? Does the organization/team have them? Are they being built/trained? | Skills inventory, training needs, expertise gaps | Technology deployment requires competencies; gaps predict failure or unintended consequences |
| Culture and Norms | G4 | Upstream | What are the organisational values and norms? Do they align with technology design choices? How might technology reshape culture? | Cultural values, norms, informal practices, change readiness | Technology that contradicts culture will be rejected or subverted; technology can reshape culture over time |
| Perspectives | G4 | Upstream | What are different stakeholders' views of the technology? Who sees benefits vs risks? Are diverse perspectives included in design? | Stakeholder perspectives, disagreements, concerns, trust levels | Missing stakeholder perspectives predict adoption failures and unintended harms |
| Narratives | G4 | Upstream | What stories are told about the technology? What harms/benefits are highlighted/hidden? Are claims evidence-based? | Narrative analysis, claim substantiation, conflicting narratives | Narratives shape adoption; false narratives mask risks; missing narratives hide harms |
| Communications | G4 | Upstream | How is information about the technology communicated? To whom? What is hidden or not communicated? | Communication map, audience, transparency level | Poor communication predicts adoption failures; hidden information enables harm accumulation |
| Legitimacy | G4 | Upstream | Is the technology perceived as legitimate? By whom? On what basis? How are legitimacy challenges being handled? | Legitimacy assessment, contestation, basis of legitimacy, trust levels | Lack of legitimacy predicts resistance; false legitimacy claims enable concealment of problems |
| Values | G4 | Upstream | What values are embedded in technology design? Do they align with stakeholder values? Whose values are excluded? | Value analysis, alignment assessment, value conflicts | Value misalignment predicts rejection or unintended consequences; exclusion of values predicts margin alienation |
| Beliefs | G5 | Upstream | What do stakeholders believe about the technology's effects? Are beliefs evidence-based? What is believed wrongly? | Belief inventory, evidence for/against, confidence levels, misconceptions | False beliefs drive poor decisions; belief in neutrality masks value-laden design |
| Evidence | G5 | Upstream | What evidence exists about technology effects? What is the quality? What evidence gaps exist? What is contested? | Evidence inventory, quality assessment, gaps, disagreements, provenance | Evidence gaps hide harms; low-quality evidence masks risks; contested evidence signals need for investigation |
| Uncertainties | G5 | Upstream | What is uncertain about the technology's effects? How are uncertainties being managed? What should we be wrong about? | Uncertainty inventory, sensitivity analysis, contingencies, escalation triggers | Unmanaged uncertainties predict surprises; overconfidence despite uncertainty predicts failure |
| Failures | G5 | Upstream | Have similar technologies failed before? What are the failure signatures? What early warnings exist? | Failure case history, patterns, early-warning signs, lessons learned | Technology failure patterns should inform risk assessment; ignoring history predicts repeat failure |
| Hiddens | G5 | Upstream | What is hidden about the technology's design, effects, governance, or harms? How are hiddens being detected and managed? | Hiddens register, detection mechanisms, remediation options, monitoring | Technology is uniquely generative of Hiddens; mandatory tiered Hiddens analysis is required |
| Diagnosis | G5 | Upstream | What is the diagnosis of technology's role in the current situation? What problems does technology create/solve? | Diagnostic findings, root causes, technology contribution to problems | Proper diagnosis requires technology analysis to distinguish technical causes from social causes |
| Metrics | G5 | Upstream | What metrics are used to evaluate technology success? Are they gaming-resistant? Do they measure actual goals? | Metrics list, gaming risks, proxy validity, goal alignment | Metrics shape incentives; poor metrics drive technology in wrong direction; gaming and drift are likely |
| Knowledge | G5 | Upstream | What is known about the technology? By whom? Who is excluded from knowledge creation? | Knowledge inventory, expertise distribution, knowledge asymmetries, excluded populations | Asymmetric knowledge enables concealment; excluding populations misses harms |
| Decisions | G6 | Downstream | What decisions must be made about the technology? Who decides? What are the decision-critical unknowns? | Decision requirements, decision-makers, decision windows, information needs | Technology analysis must feed decision inputs; identify decision-critical unknowns and escalation triggers |
| Interventions | G6 | Downstream | What interventions are possible to address technology risks or harms? What are the preconditions and costs? | Intervention options, feasibility, prerequisites, timeline, side effects | Technology analysis identifies what interventions are needed; Interventions framework designs how |
| Governance | G6 | Downstream | How is the technology governed? Who has authority? How are decisions made? Is governance adequate? | Governance structure, decision authority, accountability, adequacy assessment | Technology governance must reflect technology power; governance gaps predict problems |
| Risk | G6 | Downstream | What are the risks from this technology? How are they being managed? What contingencies exist? | Risk register, mitigation options, residual risks, contingencies | Technology analysis identifies risk sources; Risk framework designs mitigation |
| Learning and Adaptation | G6 | Downstream | How does the organization learn from technology deployment? How are lessons captured and applied? | Learning mechanisms, feedback loops, adaptation capacity, history of learning/non-learning | Technology is evolving; organizations must learn and adapt or lock-in to outdated solutions |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---:|---|---|---|
| 1 | Design Determinism Invisibility | Assumption that technology design choices are inevitable, technically necessary, or universal rather than contingent, chosen, and culturally specific. Analysis treats "this is how technology works" as fact rather than design choice. | Surface the decision space: what design alternatives existed? What assumptions did designers make about users, goals, constraints? What would a different design look like? Identify where design could have been otherwise. |
| 2 | Black-Box Opacity | Algorithmic systems, machine learning models, and complex systems whose internal workings are not legible to users, operators, or even creators. Harms accumulate in opacity; bias and malfunction cannot be diagnosed. | Request design documentation, code access, algorithm explanation. Conduct interpretability analysis (can decisions be explained?). Test for unexpected behaviour and edge cases. Design external audits and third-party testing. Establish interpretability requirements in governance. |
| 3 | Affordance Blindspots | Analysis assumes technology enables all possible user actions when actually it only affords certain actions and forecloses others. What is hard or impossible disappears from consideration as a choice that could be otherwise. | Conduct affordance analysis: what can users do, not do, do with difficulty? Interview users about their goals vs what the technology allows. Identify workarounds and shadow practices (what do users do to work around constraints?). Design alternative interaction paradigms. |
| 4 | Infrastructure Invisibility | Infrastructure becomes invisible through ubiquity; assumptions about its reliability, neutrality, and benignity go unexamined. Failures are catastrophic because assumptions are unwarranted. | Make infrastructure explicit: what are the assumptions about uptime, reliability, capacity, fairness? What would happen if these assumptions were violated? Design monitoring and graceful degradation. Maintain awareness of alternatives and switching costs. |
| 5 | Embedding Assumptions Invisibility | Values, worldviews, and normative choices are baked into technology design but treated as technical or neutral. The technology enforces assumptions without users knowing it. | Identify design assumptions: about users (age, ability, language, culture, mental model), about goals (what counts as success?), about categories (what gets counted and how?), about trade-offs (what is optimized for?). Ask whose assumptions these are and whose are excluded. Identify marginalized perspectives. |
| 6 | Power Distribution Concealment | Power to control, modify, and benefit from technology is distributed asymmetrically but claimed to be neutral or delegated. Control concentration is hidden behind technical necessity claims. | Map actual control: who decides about updates, access, policy? Who profits? Who is constrained? Who is excluded from governance? Compare to formal authority structure. Identify veto holders and gatekeepers. Document power asymmetries. |
| 7 | Lock-in Concealment | As lock-in increases over time (switching costs, data lock-in, network effects), it becomes less visible but more consequential. Path dependency is treated as inevitable rather than a choice that was made. | Assess switching costs and alternatives regularly. Maintain awareness of data portability and switching capacity. Design modular architecture and open standards support. Periodically stress-test assumptions about reversibility. Document lock-in factors. |
| 8 | Measurement & Bias Blindness | Technology systems make decisions based on data; data contains biases from collection and representation; optimization metrics don't account for fairness; poor measurement means harms are invisible. | Audit training data for representation and bias. Measure outcomes across subpopulations (are results proportional?). Examine optimization metrics for fairness implications. Test for proxy drift (does metric still measure what it did?). Establish independent outcome monitoring. Include affected populations in harm assessment. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)
| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|
| I. Perceptual | Design choices are not visible to users; affordances and constraints are not obvious; assumptions about users are invisible to designers | Users report confusion, workarounds, abandonment; feature usage diverges from design intent; user feedback is dismissed as error rather than design mismatch | Interview users about affordances and constraints; observe actual behaviour vs intended use; analyse support tickets and error patterns; conduct accessibility audits |
| II. Systemic | Technology couples with social systems, institutions, processes in ways that are not fully modelled; emergent effects arise from interaction; feedback loops are not anticipated | Unintended consequences emerge; small changes have large effects; crisis response becomes necessary; resilience declines; system becomes brittle | Map technology interaction with other systems; identify feedback loops; stress-test against scenarios; analyse incident history for unintended effects |
| III. Informational | Measurement systems don't capture what matters; data quality is poor; what is not measured is invisible; metrics are gamed; algorithms are opaque; training data is biased | Outcomes diverge from metrics; reported performance differs from actual; bias is not detected until crisis; algorithm behaviour is unexplainable; data quality problems emerge | Audit data quality; compare reported metrics to actual outcomes; test algorithms for bias; measure across subpopulations; establish independent outcome monitoring |
| IV. Temporal | Technology lock-in increases over time and becomes less visible; path dependency creates irreversibility; design assumptions drift from reality; obsolescence is approaching; technical debt accumulates | Switching costs increase unexpectedly; change becomes harder; accumulated technical debt slows development; assumptions are found to be violated; surprises emerge about what was "inevitable" | Periodically assess switching costs and reversibility; monitor technical debt; audit design assumptions; stress-test against future scenarios; plan for technology evolution |
| V. Relational | Power is concentrated but claimed to be neutral; control is asymmetric; excluded populations are not heard; informal power networks are not visible; vendor dependency grows | Governance disputes; users excluded from design; governance decisions are made without input from affected populations; vendor changes terms unilaterally; protests are dismissed | Map actual power and control; identify gatekeepers and veto-holders; include affected populations in governance; document governance asymmetries; assess accountability |
| VI. Ontological | Categories and representations in technology foreclose certain possibilities; what is not representable disappears; dominant frames exclude marginal populations; alternatives are not conceivable | Certain outcomes become impossible (by design of categories); populations whose identity doesn't fit categories are excluded; alternatives are not even conceived of; design is claimed to be universal when culturally specific | Audit categories and representations for inclusivity; identify what cannot be represented; examine who is excluded by schema; design more inclusive representations; test with diverse populations |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)
| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability | Agency | Consequence | Detection interface(s) (Type A) | Remediation interface(s) (Type B) | Interaction notes (Type C) |
|---|---|---|---|---|---|---|---|---|
| TECH_HID_001: Algorithmic bias in training data | H | Training data reflects historical discrimination; optimization metrics don't account for fairness; scale amplifies bias | M | Designer/deployer does not recognise bias (assumed objectivity); affected populations cannot access model internals; external auditors depend on data access | H: Systemic discrimination at scale; marginalised populations systematically disadvantaged; unfair outcomes persist due to technical obscurity | User outcome analysis (disaggregate by demographic group); third-party audit of training data and model behaviour; test for disparate impact | Rebalance training data; add fairness constraints to optimisation; create appeals process; establish independent oversight | Effective remediation requires governance (appeals process, oversight) not just technical fix |
| TECH_HID_002: Black-box opacity in ML decision making | H | Algorithm logic is not legible even to creators; model explanations are post-hoc and unreliable; decisions cannot be audited | M–H | Operators and users cannot explain decisions; creators claim neutrality without full understanding; external auditors cannot access internals | H: Harms accumulate undetected; malfunctions cannot be diagnosed; accountability is diffused; appeals are impossible if reasons cannot be explained | Inspect decision explanations (SHAP, LIME); test with edge cases; conduct forensic analysis of decisions; require explainability in design | Redesign for interpretability (e.g., rule-based systems, constrained complexity); require human-in-loop for high-stakes decisions; establish appeals process | Black-box cannot be remediated purely technically; must be paired with governance (appeals, oversight, human judgment) |
| TECH_HID_003: Infrastructure dependency invisibility | M | Systems depend on shared platforms/services whose failure is not fully modelled; switching costs are not fully appreciated; resilience is assumed | M–H (depends on platform criticality) | Operators assume platform will remain stable and terms will not change; organisations don't maintain switching capacity; market concentration hides vendor risk | M–H: Disruption if platform changes terms, becomes unstable, or fails; lock-in prevents switching to better alternative; vendor power grows unobserved | Periodically assess switching costs and alternatives; monitor platform health and vendor stability; test failover capacity; track vendor changes | Reduce dependency (build alternative integrations); invest in switching capacity; negotiate long-term contracts and portability; diversify vendor dependency | Governance (contract negotiation, diversification strategy) is primary remediation; technical portability is necessary but insufficient |
| TECH_HID_004: User affordance mismatch | M | Users' mental models and goals diverge from what technology affords; design assumes universal user but users are diverse; constraints are invisible | L (becomes visible through user complaints) | Designers assume user will adapt; users adapt through workarounds or abandon system; design iteration is slow; user feedback is dismissed as error | M: Adoption failures; user frustration; workarounds create new risks; system is not used as intended; user errors are blamed rather than design | Observe actual user behaviour; collect user feedback and support tickets; A/B test alternative affordances; conduct user testing with diverse populations | Redesign interactions to match user mental models; add configurability; provide escape hatches for expert users; improve error messages | Co-design with users and affected populations; maintain feedback loops; rapid iteration on affordances |
| TECH_HID_005: Measurement gaming and metric drift | M | System is optimised for measured metric; metric diverges from actual goal; short-term optimisation of metric harms long-term outcome; gaming is incentivised | L–M (becomes visible through performance divergence) | Operators/managers don't notice divergence immediately; incentives reward gaming; metric is treated as truth; actual goal slips out of view | M: Reported success masks actual failure; incentives drive system in wrong direction; accounting looks good while business fails; resources are wasted | Compare metric to actual outcomes; audit metric definitions for gaming vulnerability; monitor for proxy drift; collect qualitative feedback | Use multiple metrics including leading indicators; include qualitative feedback; audit metric definitions; adjust metrics based on evidence of gaming; link accountability to outcomes not metrics | Governance (metric design, multi-metric dashboards, outcome accountability) is primary; technical monitoring is supporting control |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)
1) Run the Tier 1 scan across all six Hiddens meta-categories (early pass; assume Hiddens exist) (OG §7.1).
2) Shortlist candidate Hiddens; for each, rate: mechanism, reducibility, detectability, agency, consequence (OG §7.2).
3) Assign at least one detection interface and one remediation interface per high-consequence Hidden; map interaction chains (OG §7.2).
4) Run the hiddens source analysis and record unresolved Unknowns/Hiddens.
5) If Tier 1 symptoms point to a specific hiding mechanism (e.g., Black-Box Opacity, Design Assumptions Invisibility, Affordance Blindspot, Measurement Gaming), invoke the appropriate Targeted Hiddens Discovery Scan (OG §7.5; select using Triage Matrix at §7.5.3).
6) After executing the framework protocol and any available tests/probes, re-run Tier 1 (pre-closure pass) and note deltas.
7) Produce Residual Unknowns (with mechanism + impact + next probe) and apply the Escalation Rule (§8.5) if any residual could change decisions, accountability, or remediation priorities. Produce closure artefacts per OG §7.4.

## 8.5 Escalation Rule (Tier 3 – full-spectrum Hiddens escalation)
Escalate to full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests if any apply:
- **High consequence**: Safety, fairness, regulatory, existential, severe harm potential; technology is critical infrastructure or affects vulnerable populations
- **Adversarial context**: Strategic concealment is plausible; vendor has incentive to hide problems; affected populations are not represented in governance
- **Persistent disagreement**: Stakeholders disagree about technology effects; evidence is contested; framing disputes persist despite investigation
- **Repeat failures**: Similar technologies have failed before; early warnings are being ignored; learning from prior incidents is poor
- **Strong suspicion of cascades**: Tight coupling suggests systemic effects; feedback loops could amplify harms; network effects could lead to tipping points
- **Deployment at scale**: Technology is being deployed beyond initial context; generalisation may not hold; new populations are affected
- **Lock-in concerns**: Switching costs are increasing; path dependency is becoming apparent; reversibility is decreasing; future options are closing

Tier 3 execution (per OG §D.6.10):
- Expands beyond Tier 1 categories into the full Hiddens taxonomy (full-spectrum exploration).
- Tightens controls: stronger provenance requirements, more explicit competing hypotheses, more rigorous disconfirming tests.
- When adversarial intent is plausible: adds concealment vectors and independent corroboration paths.
- When affecting vulnerable populations: includes direct testimony and participatory methods.
- May justify near-full group coverage (G1–G6) when warranted by routing decision tree branch A6 (OG §4.3).

---

# 9. Framework Application Protocol (mandatory)

## 9.1 Application Steps Table
| Step # | Step name | Action | Outputs / artefacts |
|---:|---|---|---|
| 1 | Technology Inventory & Situation Clarification | Identify all focal technologies in the scenario; clarify what decisions must be made about them; scope the analysis (all technologies vs priority subset). Request situation framing from upstream frameworks (Situations, Boundaries, Time, Scale). | Technology inventory (list with versions, dates); situation framing; decision requirements; scope statement; routing decision from OG §4.3 |
| 2 | Meta-Category & Type Scan | Classify each focal technology against the 30-type taxonomy (Category I–VI, Types 1–30). Note whether any technologies don't fit the taxonomy and why. | Type classification for each technology; mapping rationale; extensions needed; notes on fitness of classification |
| 3 | Affordance & Constraint Mapping | For each focal technology, map what it makes easy (affordances), hard (constraints), and impossible. Identify where user goals diverge from design intent. Conduct accessibility and inclusivity audit. | Affordance maps (user mental model vs design intent); constraint lists; accessibility findings; identified divergences and workarounds |
| 4 | Dimensions Profiling | Profile each technology against the five cross-cutting dimensions (User Agency, Technical Opacity, Power Distribution, Embedded Values, Lock-in). Identify which dimensions are most consequential. | Dimension profiles for each focal technology; dimensionality rationale (which dimensions matter most?); comparative analysis across technologies |
| 5 | Dynamics & Interface Analysis | Map the dynamic patterns active in this technology ecosystem (obsolescence cycles, lock-in, coupling, bias amplification, etc.). Identify Interface A (user affordances), Interface B (systemic effects), Interface C (governance). | Dynamics pattern shortlist (which patterns are active?); interface mapping; coupling and feedback loop analysis; governance structure |
| 6 | Hiddens Source Analysis & Tier 1 Scan | Run the eight-item hiddens source analysis and Tier 1 six-category scan. Identify high-consequence Hiddens candidates. If symptoms point to specific mechanism, invoke Targeted Hiddens Discovery Scan (OG §7.5). Determine escalation to Tier 2 or Tier 3. | Hiddens Register (framework view); Tier 1 scan results; Targeted Scan results (if invoked); escalation recommendation; decision on Tier 2/3 depth |
| 7 | Interface & Governance Design | For each high-consequence Hidden, assign detection interfaces (Type A: how will harms be detected?), remediation interfaces (Type B: how will problems be addressed?), governance interfaces (Type C: who decides, how?). Map interaction chains. | Detection design for each high-consequence Hidden; remediation strategy; governance structure; accountability assignment; monitoring plan |

## 9.2 Standard Deliverables
- **Minimum deliverable (1–2 pages)**: Technology inventory and type classification; top 3–5 Hiddens candidates with detection/remediation; key decision inputs and escalation triggers.
- **Full deliverable pack**: All tables from §2–7 populated; Tier 1 and Tier 2 Hiddens analysis; governance and monitoring design; closure artefacts (residual unknowns, acceptability rationale, ownership, learning hook).
- **Monitoring indicators**: Outcome metrics across subpopulations; black-box performance monitoring; user satisfaction and affordance gap tracking; governance audit; lock-in and switching-cost monitoring; technical debt accumulation; early-warning indicators for design assumption violations.

### Canonical shared registers (Operating Guide v2.5 aligned; mandatory for LLM use)
| Shared register / artefact | Required | Notes (how this framework contributes) | OG reference |
|---|---:|---|---|
| Group Coverage Matrix (G1–G6) | Yes | Record which groups were examined at Full Depth vs Light Depth; note gaps. Technology is G2 (Mechanism); ensure G1 (Situations/scope), G4 (Values/Norms), G5 (Evidence/Hiddens), G6 (Decisions/Governance) are also covered. | OG §D.4.1, Appendix A, Appendix E §E.2 |
| Hiddens Register | Yes | Populate candidate Hiddens specific to technology analysis (black-box opacity, design assumptions, affordance blindspots, infrastructure invisibility, power concealment, lock-in concealment, measurement gaming, embedding assumptions). Include mechanisms, detectability, consequence, probes/tests, owners, status. | OG §6.2, §D.4.1 |
| Evidence Register (Evidence Ledger) | Yes | Track key claims about technology design, performance, fairness, and harms; source, quality, bias risks, dependencies, gaps. Emphasise evidence about unintended consequences, user affectedness, distributional effects. | OG §6.2, §D.4.1 |
| Hypotheses & Tests Backlog | Yes | Convert technology Unknowns into discriminating tests/probes (e.g., audit algorithm for bias; test user affordances; assess switching costs; measure lock-in factors; probe design assumptions). | OG §D.4.1, Appendix E §E.3 |
| Information Requests | Yes | Explicit list of missing inputs needed to reduce decision-critical technology Unknowns (e.g., algorithm documentation, training data audit results, user testing results, outcome data disaggregated by population). | OG §D.10.2, Appendix E §E.4 |
| Residual Unknowns + Closure note | Yes | State what remains unknown about technology and why; include: (1) residual unknowns list, (2) acceptability rationale, (3) monitoring plan, (4) ownership, (5) learning hook. Include escalation recommendation if material. | OG §7.4, §D.3.5 |
| Investigation Plan (post-harm) | Conditional | Required when technology harms have occurred or harm potential is high and concealment is plausible. Includes scope, evidence to gather, timeline, roles, escalation path. | OG §D.4.1, Appendix B |
| Decision Record (if recommending changes) | Conditional | Required when proposing technology changes (redesign, replacement, governance redesign, harm remediation, decommissioning). Includes evidence basis, alternatives considered, residual unknowns, accountability. | OG §D.4.1, Appendix C |

---

# 10. Framework Principles (mandatory)

## 10.1 Principles Table
| Principle name | Description |
|---|---|
| 1. Design Choices Are Contingent, Not Inevitable | All technologies encode choices about how to solve problems, who can use them, what they make easy or hard. These are contingent human decisions, not technical necessities. The principle requires analysing what alternatives existed and why particular choices were made. |
| 2. Values Are Embedded, Not Neutral | Technology is never neutral. Values, assumptions, and worldviews are embedded in design. This principle requires surfacing what values are embedded, whose values are excluded, and whether embedded values align with stakeholder values. |
| 3. Harms Must Be Detected and Remedied | Technology creates both intended and unintended effects. This principle requires designing detection mechanisms for harms (especially to marginalised populations), creating remediation pathways, and establishing accountability. |
| 4. Power Distributions Shape and Are Shaped by Technology | Technology design reflects and can amplify power asymmetries. This principle requires explicitly mapping who controls technology, who benefits from design choices, and whether governance reflects actual power distribution. |
| 5. Hiddens Are Expected and Must Be Systematically Surfaced | Technology creates unique hiding mechanisms (black-box opacity, design assumption invisibility, infrastructure invisibility, affordance blindspots). This principle requires mandatory tiered Hiddens analysis and treating identified Hiddens as evidence not anomalies. |

---

# 11. Glossary (local domain terms)

## 11.1 Local domain glossary
| Term | Definition |
|---|---|
| Affordance | Action made easy, possible, or encouraged by technology design. The inverse of constraint. Affordances are often invisible to designers but visible to users through experience. |
| Black-box opacity | Situation where a system's internal workings and decision-making logic are not legible or explainable to users, operators, or even creators. Common in machine learning systems and complex algorithms. |
| Constraint | Action made hard, difficult, or impossible by technology design. Constraints shape what users can do and what they cannot even conceive of. |
| Dark pattern | Design choice that nudges users toward an outcome that benefits the system operator rather than the user (e.g., hard-to-find unsubscribe button, unclear privacy settings). |
| Embedding | Process by which values, assumptions, and worldviews are built into technology design and then reproduced at scale through use. Once embedded, effects are invisible to users. |
| Governance (technology-specific) | Systems and processes that make decisions about technology: who can access it, what policies govern it, how it is modified, who is accountable for its effects. |
| Infrastructure | Shared foundational technologies (networks, platforms, standards) that others depend on. Infrastructure becomes invisible through ubiquity and assumed reliable and neutral until disruption occurs. |
| Lock-in | Situation where switching away from a technology becomes prohibitively costly due to switching costs, data lock-in, network effects, or complementary investments. Creates vulnerability and reduces options. |
| Network effects | Dynamics where the value of a technology or platform increases as more people adopt it. Can create positive feedback loops leading to market concentration and monopoly. |
| Sociotechnical system | The co-constitutive relationship between technology and social practices, institutions, norms, and power structures. Neither determines the other; they evolve together and cannot be fully separated. |
| Type (in taxonomy) | One of 30 core technology categories (e.g., Machine Learning Models, Platform APIs, Authentication Systems). Types enable rapid classification and comparative analysis. |
| Unintended consequences | Effects of technology that were not anticipated by designers or intended by governance. Often negative; can accumulate silently; become visible through harm reports or outcome analysis. |
| Vendor dependency | Situation where an organisation depends on a vendor for critical technology. Over time, vendor power increases; switching becomes costly; vendor can raise prices or force unwanted changes. |

## 11.2 Core execution terms (pointer; do not restate)
- See **Analytical Series Operating Guide**, v2.5:
  - Core execution terms (mandatory): **§D.10.1**
  - Artefact terms (mandatory): **§D.10.2**
  - Full Operating Guide glossary: **§11** (§11.1–§11.9)
  - Targeted Hiddens Discovery Scans glossary: **§7.5.6** (also §11.7)

---

# 12. Document Control

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v1.0 | 2026-04-08 | Initial creation as part of 2026-04-08 Analytical Series rewrite project; first-generation comprehensive technology analysis framework; 6 meta-categories (30 types), 5 dimensions, 10 dynamics patterns, 3 interfaces, full Hiddens integration per MRT v3.0 |

## 12.2 Integration Notes
This is the first version of the Framework of Technology for the Analytical Series. It is designed to complement and integrate with Systems (structural analysis), Processes (activity flows), and Resources (constraints and feasibility). The framework is particularly strong in surfacing design-embedded values, black-box opacity, and power distribution mechanisms that the Systems framework does not address. It pairs with the Framework of Hiddens as the critical visibility audit layer for technology-specific hiding mechanisms. This framework should be invoked when:
- Technology design choices affect what is possible in the scenario
- Algorithms or opaque systems make consequential decisions
- Lock-in or platform dependency is a factor
- Harm or risk has a technology design component
- Governance of technology is contested or unclear
- Responsible technology or AI governance is a requirement

---

## Appendices (optional)

### Appendix A. Consolidated 30-type table (single view)
See §3.1–3.6 for full 30-type taxonomy across all six meta-categories.

### Appendix B. Hiddens mechanism chains and remediation design
For detailed Tier 3 Hiddens deepening, see §8.3 Hiddens Crosswalk and OG v2.5 §7.5 Targeted Hiddens Discovery Scans.

### Appendix C. Worked example (micro-case)
Example technology analysis case studies are provided in OG v2.5 Appendix F. Technology-specific examples will be developed in v1.1 as case library grows.

### Appendix D. Technology risk assessment checklist
| Risk category | Checklist questions |
|---|---|
| Design assumptions | Have design assumptions been surfaced and validated? Are they universal or culturally specific? Who is excluded by these assumptions? |
| Embedded values | What values are embedded in design? Do they align with stakeholder values? Whose values are excluded? |
| User affordances | What can users do, not do, do with difficulty? Do affordances match user goals and mental models? Are accessibility needs met? |
| Black-box opacity | Can decision logic be explained? Is interpretability adequate for high-stakes decisions? Can external auditors assess fairness? |
| Bias and fairness | Has training data been audited for bias? Are outcomes proportional across populations? Is there a mechanism for detecting and reporting bias? |
| Lock-in and switching | How easy is it to switch to alternatives? What are switching costs? Are data portable? Is vendor dependency increasing? |
| Infrastructure coupling | What dependencies exist on shared infrastructure? What would break if infrastructure failed? How resilient is the system? |
| Governance and accountability | Who controls the technology? Is governance aligned with power? Who is accountable for harms? Is governance adequate and inclusive? |
| Monitoring and detection | What mechanisms exist to detect harms and unintended consequences? Is monitoring timely and comprehensive? Who has visibility? |
| Harm and remediation | Have potential harms been identified? Is there a remediation pathway? How are affected populations included in design and governance? |

### Appendix E. Machine-readable field schemas
See OG v2.5 Appendix E for canonical controlled enumerations, group coverage matrix, hypotheses/tests, and information requests field schemas. Framework of Technology does not deviate from these schemas.

---

