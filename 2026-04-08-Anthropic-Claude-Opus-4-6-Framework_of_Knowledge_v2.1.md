# Framework of Knowledge
*A Comprehensive Taxonomy of How Knowledge Is Created, Stored, Transferred, Validated, Lost, and Governed—and What Fails When Knowledge Architecture Is Not Explicit*

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
- Group (Primary): G5 — Epistemics & error-control (Epistemics)
- Group (Secondary): G4 — Meaning, interpretation & social order (Meaning)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, knowledge loss or hoarding is suspected, tacit knowledge concentration creates single points of failure, or knowing-doing gaps persist despite adequate information
- Owner / Maintainer: Series Maintainer
- Intended Use: Systematically identify, classify, and profile knowledge assets and knowledge system dynamics in any situation; map where knowledge resides and in what form; expose knowledge creation, transfer, and validation pathways; diagnose knowledge loss, fragmentation, hoarding, and obsolescence; surface tacit knowledge dependencies and knowing-doing gaps; translate knowledge analysis into diagnosis, intervention design, governance, and risk work
- Primary Audience: Executives; investigators and auditors; risk and resilience teams; programme and transformation leaders; knowledge management professionals; organisational learning leads; policymakers; strategists; analysts and researchers; technology and architecture leads
- Dependencies / Key Inputs: Situation narrative and boundaries; stakeholder map and expertise inventory; evidence base; system and process maps; power and incentive configuration; governance and decision rights; cultural and normative context; time horizon and personnel dynamics; existing knowledge repositories and documentation
- Primary Outputs: Knowledge register (meta-categories → types); five-dimension knowledge profiles; knowledge stock-and-flow map; knowledge dynamics assessment; interface map (creation/exchange/governance); hiddens source and Hiddens register; knowledge strategy and intervention plan; integration handoffs to Decisions/Interventions/Governance/Learning & Adaptation
- Change Log (brief): v2.1 (2026-04-08) — MRT v3.0 LLM Integration Bridge format applied to §1.6; LLM Extract pointer and near-neighbour disambiguation; routing triggers for LLM orchestration. v2.0 (2026-04-06) — Full alignment with Master Rewrite Template v2.3 and Operating Guide v2.5; expanded Hiddens integration (Tier 1–3 scans, 13 Targeted Discovery Scans); enhanced LLM execution specs (§1.6); comprehensive framework integration (§7.3); all 36 canonical frameworks mapped; 7-step rapid protocol included; increased coverage from ~700 lines to ~900 lines with expanded dynamics, targeted scans routing, and information request specification

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| **Primary Question** | **What does this system know, where does that knowledge reside, how is it created and transferred, what knowledge is being lost or hoarded, and where does the gap between what is known and what is acted upon generate risk?** |
| **Addresses** | Institutional amnesia; brain drain; tacit knowledge concentration creating single points of failure; knowledge silos; knowing-doing gaps; knowledge hoarding for power; knowledge obsolescence; false confidence in codified knowledge; loss of embedded and embodied expertise; failure to translate individual knowledge into organisational capability |
| **Gap Filled** | The series covers how we come to know (Evidence), what we believe (Beliefs), what we don't know (Uncertainties), and how we learn (Learning & Adaptation), but lacks a systematic treatment of knowledge itself as a structural object — something that is created, codified, stored, transferred, validated, degraded, lost, hoarded, and contested. Without an explicit knowledge map, analyses routinely underestimate tacit knowledge dependencies, misdiagnose knowledge transfer failures, and overlook the political economy of who controls what is known. |
| **Complements** | Evidence; Beliefs; Learning & Adaptation; Resources; Communications; Power; Systems; Processes; Culture & Norms; Agents; Governance; Hiddens; Diagnosis; Decisions; Interventions; Risk; Metrics |
| **Key Characteristics** | Six meta-categories covering creation, content, storage, transfer, validation, and governance; 30 core types; five profiling dimensions; twelve dynamics; three interface types; stock-and-flow orientation; tacit/explicit-aware; governance-integrated; knowing-doing gap-aware; tiered Hiddens cross-check integrated |
| **Main Contributions** | Six meta-categories; thirty core knowledge types; five knowledge dimensions; twelve knowledge dynamics; three interface types; five hiddens sources; series-standard application protocol with concrete deliverables; integration with all 36 canonical frameworks; targeted Hiddens discovery routing and Tier 2/3 escalation guidance |

---

# Introduction

## What is Knowledge?

Knowledge is not information, and it is not belief. Information is a signal—structured data available to a receiver. Belief is a propositional attitude—an agent's holding-as-true of a content. Knowledge is something more specific and more consequential: it is structured, validated, contextualised understanding that enables effective action. An organisation can have abundant information and still lack knowledge because no one has synthesised it into actionable understanding. It can hold strong beliefs and still lack knowledge because the beliefs are untested or wrong. And it can possess genuine knowledge and still fail to act on it—the knowing-doing gap that Pfeffer and Sutton identified as one of the most persistent and costly failures in organisational life.

This framework treats knowledge as an analytic object with two fundamental properties. First, knowledge has **stock** characteristics: it accumulates, resides somewhere (in people, in teams, in documents, in tools, in routines, in culture), takes specific forms (tacit, explicit, embedded, embodied, encultured), and can be inventoried. Second, knowledge has **flow** characteristics: it is created through research, experience, dialogue, and crisis; it moves (or fails to move) across boundaries through apprenticeship, articulation, codification, and internalisation; it is validated through empirical test, peer review, and practical use; and it degrades through neglect, personnel departure, and environmental change. A knowledge map is therefore both a snapshot (what is known, where, in what form) and a dynamic model (what is being created, transferred, lost, validated, or rendered obsolete).

## Why Does Knowledge Matter for Hiddens Work?

Knowledge failures generate systematic invisibilities. The most consequential insight from knowledge management is Michael Polanyi's observation that "we know more than we can tell." Tacit knowledge—the skill of the experienced surgeon, the judgment of the veteran investigator, the sense of timing of the skilled negotiator—is real, consequential, and stubbornly resistant to codification. Most organisations dramatically underestimate their dependence on tacit knowledge because, by definition, tacit knowledge is invisible to the documentation and reporting systems that organisations use to track what they know.

Six families of Hiddens operate in the knowledge domain:

**Knowledge-practitioner divergence** (Hidden-14) occurs when formal documentation claims knowledge that practitioners no longer possess, or when documented procedures diverge from what experienced practitioners actually do. When a senior engineer retires, the procedures remain but the judgment vanishes.

**Tacit knowledge invisibility** (Hidden-6) makes invisible the skill of the experienced practitioner. Most organisations cannot see this knowledge; therefore, they cannot plan for its loss, replicate it, or manage the risk when key people depart.

**Knowledge silos and boundary opacity** (Hidden-19) arise when knowledge circulates within closed networks but does not cross boundaries. A discovery made in one team never reaches another team that could use it. Sales knowledge about customer needs doesn't reach product; frontline knowledge of actual failure modes doesn't reach designers.

**Knowing-doing gaps** (Hidden-12) occur when knowledge exists but is not applied—not because knowledge is unavailable but because incentives, authority, or trust structures prevent action. Frontline workers know the rules are broken; management knows the rules are broken; yet the rules persist unchanged.

**Knowledge hoarding as rational strategy** (Hidden-18) happens when control over knowledge confers power. In organisations with competitive promotion or resource allocation, holding knowledge tight is a rational way to maintain advantage. These Hiddens are often invisible until trust breaks down and knowledge transfer stalls.

**Knowledge loss through latency** (Hidden-15 Latency) allows critical knowledge to degrade without visible warning signs. Training systems slowly fill with falsehoods; embedded knowledge is forgotten as old hands retire; the organisation operates on procedures that no longer match reality. The gap is invisible until crisis reveals it.

Without explicit knowledge mapping and Hiddens scans, these failures accumulate: critical dependencies go unmapped; knowledge loss is not detected until too late; hoarding is rationalised as "expertise"; codification efforts invest in the wrong things; and organisations ossify around outdated knowledge. This framework corrects these failures by making knowledge visible, testable, and governable.

## What Does This Framework Produce?

This framework produces six primary artefacts:

1. **Knowledge Register and Profiles:** A systematic inventory of knowledge assets across all six meta-categories (creation, content, storage, transfer, validation, governance) with dimensional profiles (codifiability, embeddedness, validation status, accessibility, criticality).

2. **Knowledge Stock-and-Flow Map:** Explicit documentation of what is known, where it resides, in what form, and how it moves (or fails to move) through the system.

3. **Knowledge Dynamics Assessment:** Patterns of knowledge creation, loss, transfer, ossification, fragmentation, validation, and governance over time.

4. **Interface Map:** Explicit identification of creation, exchange, and governance interfaces where knowledge is synthesised, transferred, stored, and contested.

5. **Hiddens Register and Evidence Ledger:** Candidate knowledge-based visibility failures (tacit invisibilities, hoarding, loss, silos, knowing-doing gaps) with detection methods and remediation levers.

6. **Knowledge Strategy and Intervention Plan:** Actionable recommendations for knowledge mapping, tacit knowledge elicitation, transfer mechanism design, hoarding reduction, governance alignment, and risk mitigation.

These artefacts integrate with Evidence (epistemic inputs), Beliefs (propositional attitudes), Learning & Adaptation (knowledge creation processes), and Governance (knowledge control structures).

## How to Use This Framework

**When to invoke:** Whenever a focal question or decision involves knowledge creation, transfer, loss, or governance across multiple actors. Typical scenario features: personnel transitions or retirements creating capability gaps; knowledge silos preventing cross-team problem-solving; documented procedures diverging from practice; knowing-doing gaps where available knowledge is not applied; post-incident investigations where knowledge failures contributed.

**Default execution depth:** Light Depth Framework Execution by default. Apply Full Depth Framework Execution when routed by OG §4.3, or when tacit knowledge concentration, knowledge loss, knowing-doing gaps, or knowledge hoarding is suspected to be material to outcomes.

**In the iteration loop:** This framework sits mid-stream in the Analytical Series. Apply systematically after Evidence and Beliefs frameworks are drafted, and before Decisions/Interventions/Governance frameworks. Use Tier 1 Hiddens scan at least twice (early identification + pre-closure validation). If Tier 1 symptoms point to specific hiding mechanisms (e.g., tacit knowledge invisibility, knowledge hoarding as power mechanism, knowing-doing gaps rooted in incentive structures), invoke the appropriate Targeted Hiddens Discovery Scan from OG §7.5.

**For LLM execution:** See §1.6 for the full LLM integration specification, including preconditions, prompt discipline rules, routing logic, standard registers, and the 7-step rapid protocol.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Knowledge is both stock and flow. As stock, it is accumulated understanding distributed across individuals, teams, artefacts (documents, tools, models, systems), and encultured norms. As flow, it is created through practice, research, dialogue, and learning; transferred through apprenticeship, articulation, codification, and internalisation; validated through empirical test, peer review, and practical application; and lost through personnel departure, forgetting, and environmental change.

The most critical asymmetry in knowledge systems is the **tacit-explicit boundary** (Polanyi; Nonaka & Takeuchi): what practitioners can do and know far exceeds what they can articulate. This gap is the source of the greatest knowledge management failures: when organisations codify procedures and assume knowledge transfer is complete, they miss the tacit expertise on which procedures actually depend for competent execution.

This framework provides a systematic approach to:
- identify and classify knowledge assets across six meta-categories and thirty types,
- profile knowledge along five critical dimensions (codifiability, embeddedness, validation status, accessibility, criticality),
- map knowledge stock (what is where, in what form) and flow (how it moves or fails to move),
- diagnose knowledge creation, transfer, validation, and governance dynamics,
- expose tacit knowledge dependencies, knowledge-action gaps, hoarding, and loss risks, and
- integrate knowledge analysis into diagnosis, intervention design, governance, and risk work.

Without explicit knowledge analysis, organisations systematically fail to: anticipate knowledge loss when skilled personnel depart; diagnose transfer failures when knowledge is codified but not applied; distribute authority over knowledge codification and validation; align incentives for knowledge sharing versus hoarding; or maintain knowledge currency and quality across system changes.

## 1.2 Assumptions & Preconditions

### Assumptions Register (recommended)

| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Knowledge is distinguishable from information, belief, and data—and the distinction is analytically productive | Structural | Framework conflates distinct phenomena; outputs duplicate Evidence and Beliefs without adding value | Map knowledge types and contrast with adjacent frameworks in specific cases; test whether the distinction changes diagnosis or intervention recommendations | Use explicit definitions (§1.3); maintain boundaries via crosswalk (§7.3); if distinction collapses in context, document and use the relevant adjacent framework instead |
| Tacit knowledge is real, consequential, and systematically under-represented in formal knowledge systems | Structural | Framework overestimates the importance of tacit knowledge; codified knowledge is sufficient for most operational purposes | Audit whether codified procedures alone enable competent performance; test novice vs expert performance gaps in procedural domains; interview practitioners about what they know that isn't written down | If tacit knowledge is minimal in the focal domain, reduce weight on tacit types; document the finding as it is itself analytically important |
| Knowledge can be meaningfully inventoried, profiled, and managed—it is not too distributed, contextual, or ephemeral to treat as an analytic object | Method | Framework produces knowledge maps that are misleadingly precise; real knowledge is more fluid than the inventory implies | Compare knowledge register with practitioner experience; test whether the inventory predicts performance gaps; look for persistent "the knowledge we need is not on the map" signals | Treat the knowledge register as a hypothesis, not a fact; use it to direct investigation rather than as a definitive inventory; escalate to Tier 2/3 Hiddens scans if knowledge proves highly contextual |
| Knowledge transfer is not automatic—it requires specific mechanisms, absorptive capacity, and often trust, and these can be diagnosed and improved | Domain | Transfer is either impossible (pure tacit) or trivial (pure explicit); the framework adds no value to transfer analysis | Test transfer interventions for efficacy; audit whether transfer failures persist after mechanism improvement; compare transfer success rates across different mechanism designs | Use the SECI spiral as a diagnostic heuristic rather than a prescription; accept that some tacit knowledge may be non-transferable and design around it (redundancy, overlap) |
| Knowledge governance—who controls access, validation, and distribution—is never politically neutral and always shapes what knowledge is available | Normative | Knowledge is treated as a technical problem only; power dynamics in knowledge control are missed; knowledge hoarding is treated as pathological rather than rational | Map incentives for knowledge sharing vs hoarding; audit who benefits from current knowledge distribution; compare formal knowledge access with actual access patterns | Apply Power and Incentives frameworks to the knowledge domain; treat knowledge governance as a political as well as a technical challenge |
| The most consequential knowledge failures generate structured invisibilities (Hiddens) that are detectable through systematic scanning | Normative | Critical knowledge gaps are truly invisible and cannot be found by protocol; the framework produces false confidence about knowledge completeness | Positive and negative testing against historical cases; compare Hiddens scan predictions with post-incident knowledge failure findings; external review of hiddens source analysis adequacy | Escalate to Tier 3 Hiddens run for all non-trivial high-stakes analysis; maintain humility about the limits of any knowledge audit; use monitoring and re-scanning |

### Preconditions Checklist (recommended)

| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---:|---|---|---|---|
| Situation narrative and decision context defined (what knowledge-related failures or risks are the focus?) | Yes | Decision brief; scope charter; stakeholder requirements | Sponsor / Analyst | Document and agree before starting | Clarify with sponsor; scope to specific knowledge-critical decisions or domains |
| Stakeholder and expertise map (who holds what knowledge, and who depends on whose knowledge?) | Yes | Org chart; expertise inventory; dependency map; succession planning data | Facilitator / Programme manager | Preliminary map; may refine | Start with critical roles and known knowledge concentrations; snowball to discover hidden dependencies |
| Evidence base including documentation, process maps, training materials, and knowledge repositories | Yes | Prior analyses; SOPs; training curricula; knowledge bases; wikis; databases | Knowledge owner / Documentation lead | Inventory compiled | Gather available documents; note gaps; treat documentation absence as a signal of tacit knowledge dependence |
| Access to practitioners for knowledge elicitation at multiple levels (frontline, specialist, management, executive) | Recommended | Interview schedule; confidentiality agreements; elicitation protocols | HR / Facilitator | Access confirmed for initial cohort | Begin with willing participants; use structured observation and artefact analysis where interview access is limited |
| System and process context (what systems and processes depend on the knowledge being analysed?) | Yes | System maps; process documentation; incident and failure records; performance data | Operations / Architecture lead | Preliminary mapping | Apply Systems and Processes frameworks to establish context; focus knowledge analysis on high-dependency domains |
| Power and incentive configuration (who benefits from current knowledge distribution, and who benefits from knowledge hoarding?) | Recommended | Power map; incentive register; career progression data; reward structure | Risk / Governance owner | Preliminary map | Apply Power and Incentives frameworks; treat knowledge hoarding as rational behaviour given incentive structure |

## 1.3 Definitions, Scope, and Non-Goals

**Knowledge (operational):** Structured, validated, contextualised understanding—held by agents or encoded in artefacts—that enables effective interpretation and action within a domain. Distinguished from information (structured data available to a receiver), data (unprocessed signals), and belief (propositional attitude that may or may not be validated).

**Tacit knowledge:** Knowledge that cannot be readily articulated, codified, or transferred through formal language—including skill, judgment, intuition, and know-how. Detectable primarily through performance and practice rather than through documentation.

**Explicit knowledge:** Knowledge that has been codified in formal language (documents, procedures, databases, formulas) and can in principle be transferred without direct personal interaction.

**Knowledge stock:** The total knowledge held by a system at a point in time, distributed across individuals, teams, institutions, artefacts, and relationships.

**Knowledge flow:** The movement of knowledge through creation, transfer, validation, application, and loss over time.

**In scope:**
- Six meta-categories and thirty core knowledge types (creation, content, storage, transfer, validation, governance)
- Five dimensions for profiling any knowledge asset (codifiability, embeddedness, validation status, accessibility, criticality)
- Twelve knowledge dynamics (patterns of creation, loss, transfer, ossification, fragmentation, and governance over time)
- Three interface types (creation, exchange, governance)
- Hiddens sources and tiered Hiddens cross-check (Tier 1–3 scans; 13 Targeted Discovery Scans)
- Application protocol and standard deliverables
- Integration with all 36 canonical frameworks

**Out of scope (by design):**
- A complete epistemology or philosophy of knowledge (the framework supports plural epistemologies)
- Full cognitive science of expertise acquisition (use as input where available; do not treat as required)
- Full catalogue of knowledge management technology solutions (the framework diagnoses knowledge; technology selection is a downstream intervention)
- Knowledge content evaluation (whether specific knowledge claims are true) — that is the domain of Evidence and Diagnosis
- Information systems architecture (the framework maps knowledge needs; system design is downstream)

**Common confusions:**
- Knowledge ≠ information (information is structured data; knowledge is validated, contextualised understanding)
- Knowledge ≠ belief (beliefs may be false, unjustified, or untested; knowledge implies some degree of validation and efficacy)
- Knowledge ≠ data (data is raw signal; knowledge requires interpretation, contextualisation, and validation)
- Tacit knowledge ≠ ignorance (tacit knowledge is real, consequential, and held by practitioners—it is simply not codified)
- Knowledge transfer ≠ communication (you can communicate a message perfectly and still fail to transfer knowledge because the recipient lacks absorptive capacity, context, or practice)
- Knowledge management ≠ document management (much of the most critical knowledge cannot be documented; managing documents is necessary but nowhere near sufficient)

## 1.4 Position in the Series (Upstream / Middle / Downstream)

**Upstream (signals/understanding):**
- Situations & Context Classification; Boundaries; Realities; Scale; Time; Evidence; Agents; Perspectives; Culture & Norms; Power; Resources

**Middle (this framework's role):**
- Map the knowledge architecture of the focal system; classify knowledge types; profile knowledge stocks across five dimensions; diagnose creation, transfer, validation, and governance dynamics; expose tacit knowledge dependencies, knowledge-action gaps, knowledge loss risks, and knowledge-based hiding mechanisms

**Downstream (action/governance):**
- Decisions; Interventions; Governance; Responsibility; Learning & Adaptation; Risk; Communications; Metrics

**Group assignment (Primary):** G5 — Epistemics & error-control (Epistemics)

**Group assignment (Secondary):** G4 — Meaning, interpretation & social order (Meaning)

**Stage:** Cross-cutting (signals and action)

**Run mode selection:** Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.9.2)

**Operating Guide routing:** Apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan

**Non-conflation invariant:** Do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)

**Iteration loop:** Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)

**Framework Index:** This framework is one of 36 in the Analytical Series (complete list at §7.3)

## 1.5 Crosswalk Summary (recommended)

| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Epistemic quality and error-control (G5) | Evidence; Beliefs; Uncertainties; Failures; Diagnosis; Hiddens; Metrics | What is known evidentially, what is believed, what is uncertain, what errors occur, what is hidden, how measurement works | Where validated knowledge actually resides; what form it takes; how it moves or fails to move; where tacit dependencies create risk; where knowledge loss, fragmentation, or hoarding undermines the epistemic system |
| Meaning and social order (G4) | Perspectives; Culture & Norms; Narratives; Values; Legitimacy; Communications | Structured viewpoints, shared meanings, enforcement norms, narrative forms, normative structures, message channels | The knowledge substrate underlying meaning-making: what practitioners actually know (vs what narratives claim); where encultured knowledge differs from codified knowledge; how knowledge boundaries create interpretation differences |
| Agency and behavioural drivers (G3) | Agents; Personas; Incentives; Power; Responsibility | Who acts, with what incentives, under what authority | What agents actually know and can do; where knowledge asymmetry creates power; how incentives drive knowledge hoarding or sharing; who is responsible for knowledge maintenance |
| Structure and mechanism (G2) | Systems; Relations; Processes; Causation; Resources | System structure, dependencies, flows, mechanisms, resource substrates | Where knowledge is embedded in system architecture; which processes depend on tacit knowledge; where knowledge loss breaks causal chains; knowledge as a critical resource with accumulation and depletion dynamics |
| Action and governance (G6) | Decisions; Interventions; Governance; Risk; Learning & Adaptation | How choices are made, interventions designed, governance structured, risks managed, learning embedded | Knowledge-based constraints on decision quality; knowledge transfer requirements for intervention success; knowledge governance architecture; knowledge loss as a risk category; knowledge creation as the output of effective learning |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Knowledge_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Knowledge when… | Use neighbour instead when… |
|---|---|---|
| Evidence | Mapping where validated knowledge resides and what form it takes; auditing knowledge validation cascades and evidence quality chains; surface epistemic dependencies on tacit validation networks | Evaluating whether specific knowledge claims are true; assessing evidence quality independently; testing hypotheses about world states; diagnosing measurement and observational bias |
| Beliefs | Exploring what practitioners and agents hold as true about knowledge assets, knowledge transfer, and knowledge governance; mapping belief asymmetries that drive hoarding or non-cooperation; surfacing encultured knowledge vs codified narrative | Mapping propositional attitudes and certainty levels; diagnosing false confidence; exploring cultural narratives and legitimacy claims; examining meaning-making without knowledge-transfer focus |
| Learning & Adaptation | Analysing knowledge creation processes, feedback loops, and how organisations translate experience into updated knowledge assets; intervention design for knowledge updating; knowledge as learning output | Diagnosing learning barriers independent of knowledge architecture; examining adaptation mechanisms; studying how agents update beliefs and mental models |
| Power | Analysing who controls knowledge access, validation authority, and distribution; knowledge hoarding as rational power strategy; how knowledge asymmetries create authority and dependency; governance mechanisms that enforce knowledge control | Analysing abstract power relationships and bargaining structures; examining authority delegation and decision rights; studying power independent of information or knowledge asymmetries |
| Systems | Analysing where knowledge is embedded in system architecture, relationships, and routines; how knowledge loss breaks causal chains; knowledge redundancy and resilience design; knowledge as critical infrastructure resource | Analysing system structure, feedback, and dynamics independent of knowledge substrate; studying emergent properties and scaling behaviour |

### 1.6.3 Routing triggers
- Scenario includes personnel transitions (retirement, departure, reorganisation) creating capability gaps
- Knowledge concentration detected in critical roles or single points of failure identified
- Tacit knowledge dependency suspected but unmapped or invisible to formal systems
- Knowing-doing gaps exist: knowledge is available but not being applied or acted upon
- Knowledge silos or boundary opacity preventing cross-team synthesis or decision-making
- Documented procedures diverge from actual practice; documentation-practice gap is material
- Knowledge loss latency suspected: knowledge degradation not visible until crisis reveals it
- Knowledge hoarding, control, or political economy of knowledge access is material to outcomes
- Governance redesign, system transition, or knowledge transfer intervention effectiveness depends on mapping knowledge assets
- Risk assessment or post-incident investigation requires understanding what knowledge failed or was unavailable

---

# 2. Meta-Categories of Knowledge
