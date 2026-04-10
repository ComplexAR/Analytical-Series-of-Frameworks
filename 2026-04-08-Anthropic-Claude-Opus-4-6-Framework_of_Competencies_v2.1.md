# Framework of Competencies
*A Comprehensive Taxonomy for Mapping What Agents Can Reliably Do — and Where Capability Gaps Hide*

## Document Information
- Series: Analytical Series of Frameworks
- Version: v2.1 (aligned to OG v2.5; expanded §7.3 to all 36 canonical frameworks; §1.6 expanded to full LLM integration; §8 implements tiered Hiddens depth-control model with 13 Targeted Scans)
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
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when competency gaps are decision-critical, when intervention feasibility depends on capability profiles, or when competency misrepresentation or concentration creates high-consequence risk
- Owner / Maintainer: Series Maintainer
- Intended Use: Competency-aware diagnosis and planning; intervention feasibility analysis; capability gap identification; expertise concentration risk; workforce and role design; transformation readiness assessment; accountability alignment; hiddens discovery and remediation
- Primary Audience: Executives; transformation and programme leaders; operations leaders; HR and capability development teams; risk and resilience teams; investigators/auditors; strategy and policy designers
- Dependencies / Key Inputs: Situation framing; agent profiles and role maps; evidence base; system boundary and dependency map; resource inventory; knowledge maps; learning architecture; time horizon and windows; governance and responsibility maps
- Primary Outputs: Competency register (6×5 taxonomy + proficiency profiles); demand-supply gap map and concentration assessment; interface maps (A/B/C); dynamic trajectory hypotheses; competency strategy and development portfolio; Hiddens register and tiered scan results; monitoring indicators and closure discipline items
- Change Log (brief): v1.1→v2.0 alignment to OG v2.5; §1.6 expanded with full LLM integration quickstart (7 subsections); §7.3 populated with all 36 canonical frameworks (OG §3.2) with integration questions; §8 restructured per Tier 1/2/3 depth model + 13 Targeted Hiddens Discovery Scans (OG §7.5); closure discipline and five required closure items (OG §7.4); machine-readable field schemas via Appendix E reference; Information Requests added as standard artefact.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What can the relevant agents actually do, at what level of proficiency, how is that capability distributed across the system, where are the critical gaps between what is needed and what exists, and what competency dynamics (building, transfer, degradation, concentration) are shaping feasibility and resilience?** |
| Addresses | The knowing-doing gap (knowledge ≠ capability); competency misrepresentation and assessment theatre; expertise concentration and single-point-of-failure risks; credential-competency divergence; tacit competency invisibility; transformation failures caused by undiagnosed capability gaps; accountability assigned without the competency to deliver; competency degradation masked by routine conditions; assessment system unreliability; hidden obsolescence until context shifts. |
| Gap Filled | Existing frameworks treat capability as a resource type (Resources), map knowledge substrates (Knowledge), describe learning processes (Learning & Adaptation), profile agent action-selection (Agents), and map behavioural positioning (Personas). None systematically taxonomise what agents can reliably do, at what proficiency level, where demand-supply mismatches lie, how competency distribution creates fragility, or how competency dynamics create hidden risk. This framework makes the competency substrate explicit and exposes where capability gaps, concentration, degradation, and assessment failures govern outcomes and hide fragility. |
| Complements | Agents; Personas; Resources; Knowledge; Learning & Adaptation; Interventions; Decisions; Governance; Responsibility; Risk; Failures; Diagnosis; Hiddens; Evidence; Metrics; Incentives; Power; Systems. |
| Key Characteristics | Agent-relative (competencies for whom, in what context, at what proficiency); explicitly includes tacit and emergent competencies; dynamic (building, transfer, degradation, obsolescence, concentration); demand-supply oriented; proficiency-aware; interface-aware; designed to feed interventions, governance, feasibility analysis, and hiddens discovery. |
| Main Contributions | Six meta-categories; thirty core competency types; five cross-cutting competency dimensions; five dynamic patterns (and typical trajectory indicators); three interface types (visibility/assessment, development/transfer, demand/deployment); tiered Hiddens source analysis (Tier 1/2/3); Targeted Hiddens Discovery Scans integration; mandatory closure discipline; application protocol and standard registers; principles and glossary. |

---

# Introduction

## What is Competency?

Competency is the demonstrated capacity of an agent to perform a specified kind of action reliably and effectively under real-world conditions, drawing on an integrated combination of knowledge, skill, judgement, and practice. Unlike credentials (which attest to past assessment) or knowledge (which is what you know), competency is what you can *do*, assessed by outcomes and observable performance under the actual constraints agents face.

Competency matters analytically because nearly all failures in complex systems involve a competency substrate: people assigned to roles without the capability to deliver, tacit expertise that disappears when a key person leaves, routine conditions masking capability degradation, and organisations confident they have capability they have actually lost. Competency dynamics — how capabilities build, transfer, degrade, concentrate, and become obsolete — govern whether interventions are feasible, whether transformations will succeed, whether single points of failure will remain hidden until they break, and whether accountability can be reasonably assigned.

## Why does Competency matter for Hiddens work?

Competency failures are a primary driver of visibility failures. Four Hiddens meta-categories activate here directly: (I) **Perceptual** — credentials dominate attention over demonstrated performance; (III) **Informational** — tacit expertise not codified or visible to management; (IV) **Temporal** — competency degradation and obsolescence delayed until a crisis; (V) **Relational** — power shapes whose competency is valued or visible. Expertise concentration hides behind team-level aggregation; assessment systems are gamed; organisations operate with single-point-of-failure risks unknown to leadership.

This framework surfaces these hiddens by systematically asking: *Who actually has what capability at what proficiency? Where does demand exceed supply? Where is expertise concentrated and fragile? Where are credentials mistaken for actual performance?* When these questions are not asked—or when their answers are suppressed, distorted, or invisible—capability gaps remain hidden until intervention time, causing failures to cascade.

## What does this framework produce?

This framework produces a system-level competency map: an inventory of what agents can actually do (types taxonomy), at what depth and reliability (dimensions), in what state of stability (dynamics), visible through what interfaces (assessment, development, deployment). It populates the **Competency Register** (demand vs supply), identifies gaps and concentration risks, hypothesises development trajectories, and surfaces competency-driven Hiddens candidates for deeper investigation.

The framework is designed to integrate upstream (agent profiles, role requirements, evidence of performance) with downstream (competency strategy, intervention design, governance and accountability alignment, resource planning). It feeds directly into the iterative investigation loop (OG §5.0), supporting routing decisions at Start-of-Run and Pre-Closure (OG §4.3), and supports both Rapid Run Mode (competency inventory and top gaps) and Investigative Run Mode (deep competency assessment, contested feasibility, high-stakes capability disputes).

## How to use this framework

**When to invoke:** Competency analysis is typically routed to this framework when (1) situation involves transformation, capability building, or role design; (2) intervention feasibility depends on capability profiles; (3) competency gaps are decision-critical; (4) expertise concentration or assessment unreliability creates high-consequence risk; (5) "why couldn't they execute?" questions arise in post-failure investigation. Typical scenarios: succession planning, outsourcing decisions, incident post-mortems, transformation readiness, accountability disputes, role mismatches, capability crises.

**Default depth:** Light Depth Framework Execution by default (competency types, top gaps, baseline concentration assessment). Escalate to Full Depth when: competency gaps could change decisions; assessment systems are contested or unreliable; expertise concentration creates single-point-of-failure risk; feasibility is challenged; or when Tier 1 Hiddens scan indicates competency-related hiding mechanisms.

**Integration with iteration loop:** This framework operates within OG §5.0 (Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close). At Start-of-Run, competency framing informs scope (Section 1). During execution, populate core tables (Sections 2–6), run Tier 1 Hiddens scan (§8.2), and build demand-supply register. At Pre-Closure, repeat Tier 1 (check for discoveries); if top Hiddens activate, invoke appropriate Targeted Hiddens Discovery Scan (§8.4, OG §7.5); integrate closure discipline (OG §7.4).

**Targeted Hiddens Discovery Scans:** When Tier 1 symptoms point to specific mechanisms (e.g., Suppression, Legitimacy Theatre, Positional Blindness, Cascade Discovery, Amnesia, Negligence), this framework participates in cross-framework scans per OG §7.5 and the Triage Matrix (OG §7.5.3). See §8.4 for micro-protocol and scan participation.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Competencies are the practical substrate of reliable performance: what agents can actually do, under real conditions, at a level sufficient to produce outcomes expected of them. In real environments, "competency" extends well beyond formal qualifications and job descriptions. It includes pattern recognition built from decades of practice, the ability to improvise under pressure, the social skill to coordinate across boundaries, the meta-cognitive capacity to know what you do not know, and the systemic literacy to understand how your actions propagate through complex structures.

This framework provides a repeatable method to:

- **Inventory competencies** across a complete 6×5 taxonomy spanning technical, interpersonal, cognitive, meta-cognitive, structural, and adaptive domains;
- **Characterise critical competencies** along five dimensions: type/domain (what kind), reliability/depth (how proficient), transferability (how portable), acquisition/renewal (how developed and maintained), and visibility/assessability (how detectable and assessable);
- **Understand competency dynamics:** how capabilities build over time, how they transfer or fail to transfer, how they degrade under pressure or through disuse, how they concentrate in individuals, how they become obsolete as contexts shift;
- **Identify gaps** between competency demand (what situations, roles, and interventions require) and competency supply (what agents actually possess at the required proficiency);
- **Design competency moves** (develop, acquire, transfer, protect, redeploy, retire) with explicit monitoring and governance.

The **knowing-doing distinction** is foundational. Knowledge is validated understanding; competency is demonstrated capacity to act on that knowledge effectively. A surgeon who has read every textbook but never operated does not possess surgical competency. An organisation that has documented processes but whose staff cannot execute them under pressure has knowledge without competency. This distinction is analytically critical and practically consequential — many failures trace to the assumption that knowledge transfer equals competency transfer, or that having the information means having the capacity to use it.

Because competency analysis is particularly vulnerable to visibility failures (credentials mistaken for capability, tacit expertise invisible to management, assessment gaming, expertise concentration hidden by team-level aggregation, competency degradation masked by routine conditions), **Section 8 includes a mandatory tiered Hiddens cross-check** for non-trivial or high-stakes work. Tier 1 (six-category visibility audit) surfaces candidate Hiddens; Tier 2 (structured deepening) builds working models of top candidates; Tier 3 (escalation) applies full Hiddens taxonomy when stakes warrant or contradictions persist.

## 1.2 Assumptions & Preconditions

### Assumptions Register

| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Competencies can be identified and inventoried comprehensively across agents. | Method | Blind spots hide critical capability gaps; interventions assume capabilities that do not exist; governance assigns responsibility without competency. | Build competency inventory through observation, structured assessment, peer review, and operational evidence; validate against performance data; stress-test against scenarios. | Accept provisional inventory; mark gaps as Unknowns; escalate for Hiddens check. |
| Competency types can be classified within a stable taxonomy. | Structural | Category confusion; interventions target wrong competency; comparability fails across contexts. | Test taxonomy against diverse cases; track "none-of-above" frequency; refine. | Use domain-specific extensions; maintain mapping to canonical types. |
| Tacit and emergent competencies are real and can be approximated in analysis. | Normative | Expertise that cannot be easily articulated disappears from planning; fragility masked; organisations believe they have capability they have actually lost. | Collect proxies for tacit competency (expert judgement consistency, error rates, improvisation quality, mentoring effectiveness); test correlation with outcomes. | Use structural analogs; flag as assumptions; design redundancy around critical tacit competencies. |
| Competencies can be profiled along five dimensions. | Structural | Analysis misses critical properties (e.g., transferability, visibility); gap surprises. | Profile test competencies; check whether dimension values predict performance and resilience. | Extend dimension set; maintain backward compatibility; document extensions. |
| Competency moves (develop/acquire/transfer/protect/redeploy) are executable. | Practical | Analysis produces unactionable recommendations; governance cannot intervene on capability. | Test feasibility with decision-makers; identify execution dependencies (time, resources, access, authority); map governance capacity. | Adjust ambition; break into smaller moves; link to resource and governance redesign. |
| Proficiency can be assessed reliably without criterion-referenced performance tests. | Method | Assessment theatre masks actual capability; interventions fail despite "certified" staff. | Triangulate: self-report + peer review + supervisor assessment + outcome evidence + scenario performance. Flag single-source assessments as uncertain. | Require outcome-based evidence; escalate contested assessments. |

### Preconditions Checklist

| Precondition | Required? | Evidence | Owner | Verification | Workaround |
|---|---|---|---|---|---|
| Focal agents and their roles/responsibilities are clear. | Y | Agent list; role descriptions; responsibility maps (Agents & Responsibility frameworks) | Decision owner | To verify per case | Run role-definition workshop; use Agents and Responsibility frameworks. |
| Situation/context and performance requirements are stated. | Y | Boundary statement; performance standards; success criteria; competency demand profile (Situations & Decisions frameworks) | Lead analyst | To verify per case | Use Situations/Boundaries frameworks; extract from incident narrative; make assumptions explicit. |
| Competency baseline information is available. | Y | Skills inventories; assessment records; performance data; operational evidence; learning histories | HR/capability owner | To verify per case | Build from observation, interviews, peer assessment, incident data, and outcome evidence; use proxies; escalate for full Hiddens if baseline unavailable. |
| Evidence paths and access are identified. | Y | Evidence inventory; access approvals; contacts; data governance cleared (Evidence framework) | Evidence owner | To verify per case | Document gaps; plan phased gathering; flag observability limits; use Information Requests (§1.6.6). |
| Escalation path for high-stakes competency disputes exists. | Y | Escalation policy; sponsor; governance review panel (Governance framework) | Governance owner | To verify per case | Define ad-hoc escalation path; record contested assessments; flag for governance redesign. |

## 1.3 Definitions, Scope, and Non-Goals

**Definition of Competency:** The demonstrated capacity of an agent to perform a specified kind of action reliably and effectively under real-world conditions, drawing on an integrated combination of knowledge, skill, judgement, and practice — assessed by outcomes and observable performance, not solely by credentials or self-report.

**In scope:**
- Six meta-categories and thirty core competency types (canonical 6×5 taxonomy)
- Five cross-cutting competency dimensions
- Competency dynamics patterns (how competencies change over time — building, transfer, degradation, concentration, obsolescence)
- Competency interfaces (assessment/visibility; development/transfer; demand/deployment)
- Hiddens sources specific to competency analysis and tiered Hiddens scan
- Demand-supply matching and gap analysis
- Proficiency profiling and concentration assessment

**Out of scope:**
- Full learning programme design (use the Learning & Adaptation framework)
- Full knowledge architecture and epistemics (use the Knowledge and Beliefs frameworks)
- Full intervention catalogue (use the Interventions framework)
- Full governance and accountability allocation (use Governance and Responsibility frameworks)
- Domain-specific professional standards (use profession-specific standards as inputs)
- Detailed psychometric assessment methodology (reference via Evidence framework)

**Common confusions ("Competency is not …"):**
- Not synonymous with knowledge (knowledge is what you know; competency is what you can do)
- Not synonymous with credentials (credentials attest to past assessment; competency is current demonstrated capacity)
- Not synonymous with resources (competency is one type of human resource, but resources are broader: capital, infrastructure, time, authority)
- Not synonymous with persona (persona is how agents present themselves; competency is what they can actually deliver)
- Not static (competencies build, degrade, transfer, become obsolete; concentration and fragility are temporal dynamics)
- Not individual alone (competencies exist in networks of interdependence, tools, and structure; individual capacity != system performance)

## 1.4 Position in the Series (Upstream / Middle / Downstream)

**Upstream (signals/understanding):** Situations (context and demand); Evidence (performance data); Diagnosis (evidence integration); Systems (structure and dependencies); Agents (who, intentions); Personas (presentation and roles); Knowledge (understanding substrate); Learning & Adaptation (capability development paths).

**Middle (this framework's role):** Translate understanding of agents, roles, requirements, and evidence into a systematic map of what can actually be done, at what level, with what gaps, concentration risks, fragility points, and development trajectories. Make visible the competency substrate that enables or blocks feasibility.

**Downstream (action/governance):** Decisions (feasibility, role assignment); Interventions (competency moves — develop/acquire/transfer/protect); Governance (competency-aware policies); Responsibility (competency-accountability alignment); Risk (single-point-of-failure, degradation, obsolescence); Learning & Adaptation (development portfolio); Resources (allocation decisions); Metrics (monitoring what matters).

- **Group assignment (Primary):** G3 — Agency & behavioural drivers (Agency)
- **Group assignment (Secondary):** G2 — Structure, dependencies & mechanism (Mechanism)
- **Stage assignment:** Midstream (bridges upstream framing to downstream action)
- **Operating Guide routing:** Apply decision logic at Start-of-Run and Pre-Closure (OG §4.3) to determine minimum group coverage and per-framework Full Depth / Light Depth plan
- **Non-conflation invariant:** Do not conflate Run Mode with Framework Execution Depth (OG §D.10.1)
- **Iteration loop:** Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG §5.0)
- **Framework Index:** This framework is one of 36 in the series (see OG §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary

| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Descriptive | Agents; Personas; Systems; Scale; Time | Who acts; how they present; system structure; relevant levels and horizons | What they can actually do; where demand exceeds supply; where concentration creates fragility; how capability dynamics shape feasibility |
| Resource | Resources; Knowledge | What can be drawn upon; what is known and how it is held; learning pathways | Demonstrated capacity to act on knowledge and mobilise resources effectively; the knowing-doing gap; transfer completeness; degradation under stress |
| Epistemic | Evidence; Diagnosis; Causation; Hiddens | What is known; hypotheses and tests; causal mechanisms; visibility failure taxonomy | Competency evidence provenance; assessment validity and gaming; hidden expertise concentration and degradation; perceptual/temporal/relational hiding mechanisms |
| Normative | Values; Legitimacy; Responsibility; Governance | What should matter; mandate and acceptance; accountability; decision rights | Whether agents have the competency to fulfil responsibilities; competency-aware governance design; accountability-capability alignment; whose competency is visible/valued |
| Action | Decisions; Interventions; Incentives; Power; Learning & Adaptation | Choice structures; change levers; reward structures; control; learning cycles; feedback | Feasibility assessment through competency lens; competency moves as intervention design; competency-aware monitoring; competency dynamics feedback loops |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Competencies_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Competencies when… | Use neighbour instead when… |
|---|---|---|
| Knowledge | Analysing demonstrated capacity to perform reliably; proficiency depth and assessment; the knowing-doing gap. | Analysing what is known and how understanding is held; epistemics and knowledge representation; learning pathways. |
| Resources | Analysing human capability and the proficiency with which agents can mobilise capacities; capability gaps and concentration. | Analysing material resources, capital, infrastructure, time, authority allocation; fungibility and renewal independent of human capacity. |
| Learning & Adaptation | Analysing current competency state, proficiency profiles, and where capability gaps exist requiring development. | Analysing learning cycle design, development pathways, knowledge transfer mechanisms, and feedback-driven capability evolution. |
| Agents | Analysing what agents can actually do and at what proficiency; capability constraints on action and feasibility. | Analysing who acts, what drives their decisions, intention, motivation, and role assignment independent of demonstrated capacity. |
| Responsibility | Analysing whether agents have the competency to fulfil assigned responsibilities; accountability-capability alignment. | Analysing formal accountability structures, decision rights, authority, and who is held responsible independent of competency to deliver. |

### 1.6.3 Routing triggers
- Scenario involves role assignment, feasibility assessment, or execution failure analysis
- Competency gaps are decision-critical or could change feasibility conclusions
- Intervention design depends on capability profiles or development trajectories
- Expertise concentration or single-point-of-failure risks are suspected
- Assessment systems are contested, unreliable, or gaming-prone
- Credentials or self-reported capability diverge from observed performance
- Tacit competencies are critical but invisible or at-risk of loss
- Transformation readiness or succession planning requires capability assessment
- Post-failure investigation involves "why couldn't they execute?" questions
- Accountability assignment or responsibility disputes involve competency claims

---

# 2. Meta-Categories of Competency

## 2.1 Meta-Categories Table (mandatory)

| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | **Technical & Domain Mastery** | Can agents perform domain-specific technical work reliably? | Deep, specialised knowledge and skill in a defined domain; expert pattern recognition; tacit craft expertise | Domain expertise assessments; certification records; technical performance data; peer review of quality; incident post-mortems |
| II | **Interpersonal & Social** | Can agents coordinate, influence, and work effectively across relationships? | Social skill, emotional intelligence, collaboration, negotiation, team coherence, cross-boundary influence | 360 feedback; team cohesion metrics; collaboration patterns; escalation frequency; stakeholder satisfaction |
| III | **Cognitive & Analytical** | Can agents think clearly, analyse complex problems, and make sound judgements? | Logical reasoning, systems thinking, evidence evaluation, pattern recognition, decision quality, adaptability | Problem-solving assessments; decision quality reviews; analysis depth; reasoning error rates; learning velocity |
| IV | **Meta-Cognitive & Self-Aware** | Can agents understand their own boundaries, limits, and blindspots, and course-correct? | Self-awareness, learning agility, error recognition, humility, intellectual honesty, cognitive flexibility | Reflection quality; error admission and learning; feedback integration; capability self-assessment accuracy; growth trajectory |
| V | **Structural & Systemic** | Can agents understand how systems work, how their actions propagate, and coordinate across dependencies? | Systems literacy, dependency mapping, unintended consequence awareness, structural thinking, governance and policy literacy | System models produced; unintended consequence identification; cross-functional effectiveness; stewardship outcomes |
| VI | **Adaptive & Emergent** | Can agents learn, innovate, improvise under pressure, and adapt as conditions change? | Learning capacity, experimentation, pressure performance, innovation, resilience, improvisational skill, change adaptation | Innovation track record; crisis performance; learning speed; experimentation discipline; resilience under stress |

## 2.2 Meta-Category Descriptions

### I. Technical & Domain Mastery
- **Definition:** Deep, specialised knowledge and skill in a defined domain; expert pattern recognition and the ability to perform domain-specific technical work reliably, consistently, and at high quality.
- **Diagnostic cues:** Domain credentials and formal training; years of experience; peer recognition as expert; consistent high-quality output; ability to mentor others in the domain; problem-solving speed and accuracy within domain.
- **Typical failure mode:** Credential-competency divergence (certified but not capable); expertise concentrated in individuals; transfer failures when experts retire; tacit skill invisible in documentation; domain knowledge that does not transfer to novel contexts.

### II. Interpersonal & Social
- **Definition:** Ability to work effectively with others across relationships — including collaboration, influence, negotiation, emotional intelligence, trust-building, and the maintenance of team coherence.
- **Diagnostic cues:** Team cohesion and effectiveness; stakeholder satisfaction; collaboration quality across boundaries; influence without formal authority; conflict resolution; mentor relationships; "go-to" person reputation.
- **Typical failure mode:** Individual capability that does not translate to team performance; relationship failures hiding individual gaps; "solo" performers who do not develop others; weak cross-boundary coordination; influence concentrated in individuals.

### III. Cognitive & Analytical
- **Definition:** Ability to think clearly, analyse complex problems, evaluate evidence, recognise patterns, make sound judgements, and adapt reasoning to new situations.
- **Diagnostic cues:** Quality of analysis and reasoning; decision quality; error rate and error type; systems thinking breadth; evidence integration discipline; learning velocity; intellectual humility in face of complexity.
- **Typical failure mode:** Cognitive biases hidden by authority position; analysis quality degraded under pressure or time constraint; pattern recognition failures in novel contexts; reasoning errors not caught by review.

### IV. Meta-Cognitive & Self-Aware
- **Definition:** Capacity to understand one's own boundaries, limits, blindspots, and the limits of one's knowledge — including the ability to recognise error, learn from failure, and course-correct.
- **Diagnostic cues:** Accurate self-assessment of capability; admission of error; integration of feedback; learning from failure; intellectual humility; appropriate escalation when capability boundaries are reached; growth trajectory.
- **Typical failure mode:** Overconfidence hiding capability limits; errors not admitted or learned from; feedback not integrated; blindspots not recognised; escalation failures when expertise is exceeded.

### V. Structural & Systemic
- **Definition:** Understanding of how systems work, how actions propagate through complex structures, how dependencies create vulnerability, and how to coordinate across system boundaries.
- **Diagnostic cues:** System models produced; unintended consequence identification; cross-functional effectiveness; stewardship of shared resources; policy literacy; governance participation quality; long-term consequence thinking.
- **Typical failure mode:** Local optimisation creating system harm; unintended consequences not anticipated; structural blindness to second and third order effects; siloed thinking; dependency blindness.

### VI. Adaptive & Emergent
- **Definition:** Capacity to learn rapidly, innovate, improvise under pressure, adapt to changing conditions, and navigate uncertainty — including experimental discipline and resilience under stress.
- **Diagnostic cues:** Innovation track record; crisis performance; learning speed; experimentation quality and learning discipline; resilience under stress and high pressure; adaptability; changeability.
- **Typical failure mode:** Tested competencies that fail under novel or pressure conditions; innovation theatre without discipline; learning that does not persist; adaptation failure in crises; pressure performance collapse.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations

- **Canonical baseline:** 6 meta-categories × 5 types = 30 core types.
- **This framework:** 30 types (canonical).
- **Mapping back to baseline:** Not required.

## 3.1 Types (Category I: Technical & Domain Mastery)

| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 1 | **Domain Expertise & Specialisation** | Deep knowledge and skill in a specific technical or functional domain; ability to perform complex domain work reliably and at high quality; recognised by peers as expert. | Domain credentials; years of experience in domain; peer recognition; mentoring of others; consistent high-quality output; problem-solving speed. | Credential without current capability; expertise concentrated in individual; transfer failure when expert leaves; tacit skill not captured; knowledge that does not transfer to adjacent domains. |
| 2 | **Craft & Technical Skill** | Demonstrated ability to execute complex technical tasks reliably; quality of output; mastery of tools, methods, and best practices within a domain. | Portfolio of high-quality work; low error rates; efficient execution; safety and compliance record; ability to troubleshoot and recover. | Quality degradation masked by routine conditions; skill atrophy from disuse; tool/method obsolescence undetected; pressure performance collapse; transfer failures to new tools/methods. |
| 3 | **Pattern Recognition & Diagnostic Acumen** | Ability to recognise patterns, anomalies, and signatures in complex, noisy data; diagnostic speed and accuracy; intuitive grasp of "what is wrong". | Speed of diagnosis; accuracy of initial hypothesis; error correction rate; learning from cases; mentoring effectiveness; rare-event detection. | Overconfidence in pattern recognition; biases in pattern weighting; novel patterns misclassified; degradation under time pressure or fatigue; pattern recognition that does not transfer to novel domains. |
| 4 | **Process & Methodology Mastery** | Understanding of and ability to execute established processes, methodologies, and standard operating procedures reliably; adaptation of standard methods to context. | Process compliance; output quality; time-to-competency for others; documentation of process learning; exception handling. | Process knowledge without adaptive capability; rigid adherence to process in novel contexts; process improvement failures from methodology blindness; methodology obsolescence undetected. |
| 5 | **Learning & Knowledge Development** | Capacity to acquire new domain knowledge and skill; ability to master new tools, methods, and contexts within or adjacent to a domain; self-directed learning. | Learning velocity; breadth of domain knowledge; transfer success to adjacent domains; mentoring effectiveness; continuous skill development; documented learning plans. | Learning assumptions not validated; learning plateaus hidden; transfer failures to novel contexts; learning that does not persist; skill degradation from non-use. |

## 3.2 Types (Category II: Interpersonal & Social)

| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 6 | **Collaboration & Teamwork** | Ability to work effectively within teams; cooperation, information sharing, mutual support; contribution to team goals; alignment with team objectives. | Team cohesion; contribution to team performance; peer feedback; cross-team collaboration quality; information sharing; mutual support. | Individual capability not translating to team performance; free-rider problems; information silos; collaboration failures hidden by aggregation; team performance attributable to individual stars. |
| 7 | **Communication & Expression** | Ability to communicate clearly, listen effectively, tailor communication to audience, and facilitate understanding across differences. | Communication clarity; listening quality; audience feedback; comprehension of complex ideas; cross-boundary understanding; documentation quality. | Communication failures masked by hierarchical authority; listening failures causing misunderstanding; tailoring failures in novel contexts; documentation that obscures rather than clarifies. |
| 8 | **Negotiation & Influence** | Ability to influence without formal authority; negotiation skill; conflict resolution; persuasion; relationship-building; trust. | Cross-functional influence; conflict resolution success; stakeholder satisfaction; trust feedback; repeated influence; relationship depth. | Influence that depends on position (not competency); conflicts escalated rather than resolved; negotiation failures in novel contexts; trust dependent on formal authority. |
| 9 | **Emotional Intelligence & Empathy** | Understanding of own emotions and others'; empathy and perspective-taking; relationship sensitivity; emotional regulation; social awareness. | Peer feedback on interpersonal sensitivity; relationship quality; conflict de-escalation; mentoring effectiveness; feedback integration; team psychological safety. | Emotional intelligence assumed from credentials; empathy failures in diverse contexts; emotional regulation failures under stress; relationship damage hidden until crisis. |
| 10 | **Mentoring & Development** | Ability to develop others; coaching skill; feedback quality; commitment to others' growth; transfer of expertise. | Mentee success rate; feedback quality and integration; mentee growth trajectory; documented development conversations; retention of mentees; knowledge transfer success. | Mentoring assumed from expertise; development conversations not happening; feedback that demotivates or is not integrated; knowledge transfer failure; mentee skill not matching mentor reputation. |

## 3.3 Types (Category III: Cognitive & Analytical)

| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 11 | **Complex Problem-Solving** | Ability to break down complex, multi-layered problems; analyse dependencies; generate hypotheses; test solutions; learn from failure. | Problem-solving speed; solution quality; error rate; learning from failures; complexity tolerance; documentation of reasoning. | Complexity tolerance that hides shallow analysis; solution failures in novel contexts; error patterns not recognised; problem-solving that works in routine conditions but fails under pressure. |
| 12 | **Systems & Structural Thinking** | Ability to understand systems, see interconnections, recognise second and third-order effects, and model complex structures. | System models produced; unintended consequence identification; cross-domain insights; policy analysis quality; stakeholder coordination. | Systems thinking assumed from seniority; structural blindness to second-order effects; local optimisation creating system harm; feedback delays hiding system effects. |
| 13 | **Evidence & Data Literacy** | Ability to interpret data; understand statistical concepts; evaluate evidence quality; recognise bias and confounds; make data-informed judgements. | Analysis quality; data interpretation accuracy; bias recognition; evidence-based decisions; data quality assessment; error correction. | Data literacy assumed from credentials; analytical biases masked by authority; data misinterpretation not caught; evidence quality assumptions not validated. |
| 14 | **Decision Quality & Judgement** | Ability to make sound decisions under uncertainty; integrate available information; weigh tradeoffs; accept residual uncertainty; avoid decision paralysis. | Decision quality outcomes; decision speed; reversibility assessment; stakeholder satisfaction with decisions; decision documentation; learning from decision outcomes. | Decision quality assumptions not validated; decisions made under uncertainty without explicit assumptions; decision reversal frequency; consequence of poor decisions hidden by time delays. |
| 15 | **Adaptive Reasoning & Flexibility** | Ability to shift thinking when evidence contradicts assumptions; update models based on new information; avoid cognitive rigidity. | Learning velocity; hypothesis updating; perspective shift frequency; error correction speed; complexity tolerance; novel context adaptation. | Cognitive rigidity masked by seniority; reasoning updates not happening despite evidence; novel contexts misanalysed with old models; flexibility failures under time pressure. |

## 3.4 Types (Category IV: Meta-Cognitive & Self-Aware)

| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 16 | **Self-Assessment Accuracy** | Accurate understanding of own capability level, strengths, and limits; honest self-appraisal; calibration with external feedback. | Self-assessment vs. peer/supervisor assessment alignment; feedback integration; honest capability description; appropriate escalation. | Self-assessment optimism bias; overconfidence hiding real limits; underestimation causing missed opportunities; self-assessment not updated with feedback. |
| 17 | **Error Recognition & Learning** | Ability to recognise own errors quickly; analyse error causes; learn and adapt to prevent recurrence. | Error admission rate; error analysis quality; recurrence prevention; feedback integration; documented learning from error. | Errors attributed to external causes; error patterns not recognised; errors hidden until crisis; defensive responses preventing learning. |
| 18 | **Intellectual Humility & Curiosity** | Openness to being wrong; curiosity about limitations; seeking feedback; comfort with "I don't know"; intellectual humility. | Feedback-seeking behaviour; error admission; intellectual humility in communication; perspective diversity valued; learning orientation. | Confidence masking capability limits; dismissal of feedback from "junior" sources; intellectual arrogance hiding gaps; unwillingness to learn from others. |
| 19 | **Blindspot Recognition** | Ability to identify own blindspots; understanding of what you cannot see; strategies to compensate; structures to catch blindspots. | Peer feedback on blindspot awareness; 360 feedback integration; compensatory structures created; perspective diversity sought; error correction despite blindspots. | Blindspots not recognised until failure; confidence in domains where blindspots exist; structures to catch blindspots not in place; diversity of perspective not valued. |
| 20 | **Learning Agility & Growth Mindset** | Capacity and willingness to learn from experience; adaptability to new situations; openness to change; growth orientation. | Learning velocity; transfer success; change acceptance; feedback integration; growth trajectory; new context adaptation. | Learning assumed from credentials; learning plateaus not recognised; transfer failures; change resistance masked by role position; growth trajectory stalled. |

## 3.5 Types (Category V: Structural & Systemic)

| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 21 | **Systemic Literacy & Structure** | Understanding of how systems work, how structures enable/constrain action, how incentives propagate, how feedback loops operate. | System models; structural insights; incentive alignment; feedback loop understanding; unintended consequence identification. | Systems literacy assumed; structural blindness to unintended consequences; incentive misalignment not recognised; feedback loops delayed/invisible. |
| 22 | **Dependency & Vulnerability Mapping** | Ability to identify critical dependencies, single points of failure, cascade risks, and vulnerability points in systems. | Dependency maps; single-point-of-failure identification; cascade risk assessment; contingency planning; resilience design. | Dependencies invisible until failure; single-point-of-failure risks not recognised; cascade risks not anticipated; fragility hidden by normal conditions. |
| 23 | **Cross-Boundary Coordination & Stewardship** | Ability to work across functional, organisational, and disciplinary boundaries; stewardship of shared resources; coalition building. | Cross-boundary collaboration effectiveness; stakeholder alignment; shared resource quality; coalition stability; boundary-spanning influence. | Silos not recognised; cross-boundary failures attributed to other groups; shared resources degraded by uncoordinated use; boundary coordination only via hierarchy. |
| 24 | **Policy & Governance Literacy** | Understanding of governance structures, policy mechanisms, accountability models, and how to operate effectively within policy contexts. | Policy analysis quality; governance participation; policy-practice alignment; accountability understanding; compliance quality. | Policy literacy assumed; governance mechanisms not understood; accountability confusion; policy-practice gaps; compliance theatre without understanding. |
| 25 | **Long-Term & Unintended Consequence Thinking** | Ability to anticipate second and third-order effects, long-term consequences, and system-level impacts of local actions. | Consequence anticipation accuracy; second-order effect identification; long-term thinking; system optimisation; strategic foresight. | Local optimisation without system awareness; unintended consequences not anticipated; long-term effects invisible until damage; strategic foresight failures. |

## 3.6 Types (Category VI: Adaptive & Emergent)

| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 26 | **Rapid Learning & Knowledge Transfer** | Ability to learn quickly in new domains or contexts; knowledge transfer to adjacent areas; fast capability ramp-up. | Learning velocity; transfer success; new context mastery speed; cross-domain capability; time-to-competency. | Learning velocity assumed from credentials; transfer failures to adjacent domains; new context mastery delayed; capability ramp-up slower than expected. |
| 27 | **Cross-Domain Integration & Innovation** | Ability to connect knowledge, methods, and perspectives from different domains; boundary-spanning synthesis; novel solution generation. | Cross-domain insights; novel solution creation; interdisciplinary effectiveness; perspective integration; innovation outcomes. | Cross-domain connections assumed from credentials; interdisciplinary work that remains siloed; novel solution generation failing in new contexts. |
| 28 | **Innovation & Experimentation Discipline** | Ability to generate novel ideas, design and execute experiments, learn from failure, and create value through controlled departure from established practice. | Innovation track record; experiment design quality; learning from failed experiments; innovation discipline; value creation. | Innovation theatre without discipline; failure to learn from experiments; uncontrolled change masquerading as innovation; innovation failures in scaling. |
| 29 | **Crisis & Pressure Performance** | Ability to maintain cognitive clarity, coordination effectiveness, and sound judgement under acute pressure, time constraints, high stakes, and incomplete information. | Performance in crises; cognitive clarity under pressure; coordination quality under stress; decision quality in uncertainty; pressure resilience. | Crisis competency assumed from routine performance; performance collapse under pressure; cognitive degradation under stress; crisis decisions that create new problems. |
| 30 | **Change Adaptability & Resilience** | Ability to adapt to changing conditions, maintain effectiveness through transition, recover from setbacks, and build personal/organisational resilience. | Adaptation speed; transition performance; setback recovery; resilience trajectories; change acceptance; learning from disruption. | Adaptability assumed from credentials; change resistance masked by role position; resilience overestimated; recovery trajectories longer than expected. |

## 3.7 Extending the Taxonomy (mandatory)

| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | The 6×5 canonical baseline (30 types) is the starting point. Extensions preserve comparability. |
| Domain-specific refinement | Domain-specific competencies (e.g., surgical competency subtypes, software engineering specialties) should be created by domain communities and mapped back to canonical meta-categories. |
| Preserving mappability | Any new type should be mapped to one or more canonical meta-categories (I–VI) and cross-referenced. |
| Structural invariants | Keep the six meta-categories as structural anchors. If extending types, increment minor version (vX.Y). If changing meta-categories, increment major version (vX.0). |
| Periodic reassessment | Canonical types should be revisited annually or when evidence suggests obsolescence or new category gaps. |
| Versioning & governance | Extensions and domain variants should be tracked separately from the canonical list. Map all variants back to canonical at definition time. |

---

# 4. Cross-Cutting Dimensions of Any Competency

## 4.1 Dimensions Table (mandatory)

| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| **1. Type / Domain** | What kind of competency is it? (technical, interpersonal, cognitive, meta-cognitive, structural, adaptive) | One of I–VI meta-categories | Classify using 2.1 meta-categories table | Organise competency inventory; align development pathway to competency type. |
| **2. Reliability / Depth** | How proficient and reliable is the competency under real-world conditions? How deep is the expertise? | Novice / Intermediate / Advanced / Expert (or L1–L5 scale) | Observable performance; error rates; speed; peer assessment; supervisor feedback | Identify gaps between demanded and supplied proficiency; target development; assess readiness for high-stakes work. |
| **3. Transferability / Portability** | How well does the competency transfer to new contexts, domains, or tools? How portable is it? | Narrow (domain-specific) / Moderate (adjacent domains) / Broad (cross-domain) | Test with novel contexts or adjacent domains; interview about transfer history; examine learning curves in new contexts | Assess resilience to change; identify fragility from non-portable expertise; design cross-training. |
| **4. Acquisition & Renewal** | How was the competency acquired and how is it maintained or renewed? What is the time-to-competency and learning pathway? | Formal training / apprenticeship / on-the-job / experiential / self-directed; steady-state / degrading / building | Review learning history; time-to-competency for similar roles; degradation patterns under non-use; learning infrastructure available | Assess feasibility of transfer or replication; identify renewal mechanisms; design development programmes. |
| **5. Visibility / Assessability** | How visible is the competency? How reliably can it be assessed? How much is tacit vs. explicit? | Transparent (easily observed) / Hidden (tacit, requires inference) / Opaque (difficult to assess) | Observable performance evidence; assessment coverage; tacit vs explicit ratio; assessment disagreement | Identify assessment gaps; flag tacit competencies at risk if expert leaves; design visibility improvements. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)

| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | **Competency Building** | Monotonic growth in proficiency and reliability over time; learning curve visible; capability increasing predictably. | Deliberate practice, structured training, mentoring, experiential learning, feedback loops, progressive challenge. | Transformation feasibility depends on team's ability to build required capability. Underestimating time-to-competency is a primary failure mode. | Structured development programmes; experiential learning design; mentoring infrastructure; progressive responsibility; learning metrics. |
| 2 | **Competency Transfer & Replication** | Expert knowledge and skill successfully transmitted to others; proficiency profile spreading; implicit made explicit. | Apprenticeship, mentoring, documentation, communities of practice, deliberate transfer structures, cross-training, succession planning. | Many organisations fail at scale because expertise remains concentrated. Transfer failures cascade when experts leave. Tacit knowledge dies with individuals. | Knowledge capture (document implicit); mentor relationships (structured); cross-training programmes; communities of practice; succession planning. |
| 3 | **Competency Degradation & Atrophy** | Proficiency declining from non-use, skill erosion, pressure effects, or environmental change; "use it or lose it" pattern. | Disuse over time; pressure-induced performance collapse; environmental change outpacing adaptation; routine masking drift. | Competency gaps emerge silently. Organisations discover capability loss only when crisis hits. Single individuals bearing atrophy risk but undetected. | Regular proficiency assessment; deliberate practice maintenance; rotation to prevent non-use; pressure-testing; monitoring for drift. |
| 4 | **Competency Concentration & Fragility** | Critical capability concentrated in individual(s); redundancy absent; single-point-of-failure risk from departure, illness, incapacity. | Hiring/development patterns; expertise acquisition concentrated in individuals; transfer not prioritised; succession planning absent. | System fragility hidden until expert leaves or cannot work. Crisis response dependent on individual heroics. Risk not visible to senior leadership. | Cross-training and redundancy; succession planning; explicit concentration assessment; knowledge capture; development portfolio breadth. |
| 5 | **Competency Obsolescence & Context Drift** | Competency remains at prior proficiency but becomes less relevant or effective as context shifts; expertise misaligned with demand. | Technology change; organisational restructuring; market shifts; regulatory change; process redesign; undetected environmental drift. | Expensive to carry forward competency that is no longer needed. Resistance to change masks obsolescence. Investments continue in outdated capability. | Environmental scanning; competency-demand alignment reviews; redeployment strategies; learning and adaptation to new contexts; honest conversation about relevance. |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)

| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | **Assessment & Visibility Interface** | Mechanisms and processes through which competencies are observed, assessed, measured, and made visible for decision-making. | How do we know who has what capability? What assessment methods are reliable? Where are assessment blind spots? How do we detect tacit competency? How do we catch assessment gaming? | Skills inventories, credentials and certifications, performance reviews, 360 feedback, competency assessments, scenario-based testing, peer review, outcome analysis, portfolio review. |
| B | **Development & Transfer Interface** | Mechanisms and processes through which competencies are built, maintained, and transferred between agents — with associated timelines, investment requirements, and transfer completeness. | How are competencies developed? Through what pathways? With what timelines and investment? How complete is transfer? Where is development failing? How is tacit knowledge formalised and transmitted? | Training programmes, apprenticeships, mentoring relationships, communities of practice, rotational assignments, simulation-based learning, on-the-job development, knowledge management systems, shadowing, after-action reviews, cross-training. |
| C | **Demand & Deployment Interface** | Points where competency requirements are defined, matched to available capability, and deployed — including the gap between what is demanded and what exists, and the allocation mechanisms that determine who does what. | What competencies does the situation/role/intervention require? What exists? Where are the gaps? How are competencies allocated to demands? Where are mismatches? What alternatives exist if demand exceeds supply? | Role definitions, job specifications, project staffing, incident response team composition, succession plans, outsourcing decisions, partnership designs, intervention team composition, capability planning, contingency allocation. |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links (recommended)

- **Inputs expected:** Situation framing and objectives; agent profiles and role maps; evidence base; system boundaries and dependencies; resource inventory and constraints; knowledge maps; learning architecture; governance and responsibility structure; incentive and power maps; time horizon and windows.
- **Outputs provided:** Competency inventory and gap map; proficiency profiles for critical competencies; concentration and fragility assessment; interface maps (A/B/C); competency dynamics hypotheses and trajectories; competency strategy and development/deployment portfolio; monitoring indicators and review cadence; Hiddens shortlist and detection/remediation moves.

## 7.2 Crosswalk Table (optional but recommended)

| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| Agents | Agent profiles, action-selection capacity, intentional coherence | Competency profiles specifying what agents can reliably do, not just what they intend | Match agent capability to role requirements; identify capability-role mismatches. |
| Personas | How agents position and present in situations | Whether presented persona is backed by actual competency; persona-competency divergence | Detect personas without backing competency; assess persona reliability. |
| Resources | Resource availability, constraints, human capital allocation | Competency profile as human resource; capability-demand matching for resource planning | Align resource allocation with capability; design resource strategy around competency gaps. |
| Knowledge | What is known, knowledge substrate, understanding | Demonstrated capacity to act on knowledge; knowing-doing gap; knowledge transfer vs competency transfer | Distinguish knowledge from capability; assess whether knowledge transfer has produced competency. |
| Learning & Adaptation | Learning pathways, development mechanisms, feedback loops | Competency trajectory data; development feasibility assessment; learning architecture required | Design learning programmes that actually build required competency; assess development feasibility. |
| Evidence | What is known, evidence quality, provenance | Competency assessment evidence; assessment reliability; provenance of capability claims | Validate competency claims against evidence; identify assessment system reliability issues. |
| Diagnosis | Hypotheses and tests; causal models | Competency as causal variable in failures; tests to surface competency gaps | Include competency in causal analysis; design tests to surface competency-related failures. |
| Decisions | Choice structures, decision-makers | Who actually has capability to decide; competency-aware governance of decision rights | Assess whether decision-makers have competency for decisions required; redesign decision structures based on capability. |
| Interventions | Intervention design, change mechanisms | Competency-aware intervention feasibility; competency moves (develop/acquire/transfer/protect) as intervention types | Design interventions that account for competency constraints; use competency moves as intervention levers. |
| Governance | Authority structure, decision rights, accountability | Competency-accountability alignment; competency-aware governance design; whether governed agents have competency to fulfil responsibilities | Align accountability with competency; redesign governance structures for competency-aware accountability. |
| Responsibility | Accountability mapping, role accountability | Whether accountable agents have competency to fulfil responsibilities; responsibility-competency alignment; accountability without capability | Align responsibilities with capability; identify accountability-competency mismatches; redesign responsibilities. |
| Risk | Risk identification, consequence assessment | Competency gaps as risk sources; concentration and atrophy as persistence drivers; competency-related single-point-of-failure | Identify competency as risk source; assess single-point-of-failure risks from concentration. |
| Failures | Failure investigation, root cause analysis | Competency as failure causal factor; competency gaps, concentration, degradation, assessment failures as failure drivers | Include competency in post-failure investigation; test competency-based hypotheses. |
| Hiddens | Visibility failures, hiding mechanisms | Competency-related Hiddens: credential-competency divergence, tacit invisibility, concentration, degradation, assessment gaming | Surface competency-related Hiddens as candidates for deeper investigation. |
| Metrics | Measurement frameworks, indicators | Proficiency indicators; competency development rate; concentration metrics; degradation detection | Design metrics that measure competency dimensions; monitor competency dynamics. |
| Incentives | Reward structures, motivation | How incentives shape competency visibility, development, transfer, and concentration | Assess whether incentives support competency building and transfer or hide gaps. |
| Power | Authority structure, influence | Whose competency is visible/valued; whose gaps are hidden; how power shapes competency visibility | Analyse competency visibility through power lens; surface competency gaps hidden by power imbalance. |
| Systems | System structure, mechanisms, feedback | Competency distributed across system; system-level capability as emergent property | Understand competency as system-level property; assess system-level capability. |

## 7.3 Integration Questions by Framework (all 36 canonical frameworks)

**Canonical framework list (OG v2.5 §3.2; 36 frameworks across 6 groups):**

| Framework | Group | Stage | Integration questions | Outputs / artefacts to pull in | Notes |
|---|---|---|---|---|---|
| Situations & Context Classification | G1 | Upstream | What competencies are demanded by this situation? What capabilities are assumed in the problem framing? How does situation type affect competency demand? | Situation type; competency demand profile; assumptions about agent capability. | Situation framing drives competency demand. |
| Boundaries | G1 | Upstream | What boundaries constrain competency development, transfer, or deployment? What competencies are required to operate across boundaries? | Boundary structure; cross-boundary competency demand; scope constraints on development. | Boundary architecture affects who can develop what capability where. |
| Dimensions | G1 | Upstream | What dimensions of the situation (scale, time, scope) affect required competency profiles? | Situation dimensions; scale-dependent competency; timescale for development. | Situation dimensionality informs competency demand and feasibility. |
| Realities | G1 | Upstream | What stakeholder realities assume about agent capability? What capability gaps exist between stakeholder assumptions and actual capability? | Reality maps; capability assumptions embedded in realities; assumption validity. | Stakeholder realities may assume competency that does not exist. |
| Scale | G1 | Upstream | How does system scale affect competency requirements and concentration? What competencies are required at different scales? | Scale implications; scale-dependent competency demand; distribution of competency at scale. | Scaling often requires different competencies than small-scale operation. |
| Time | G1 | Upstream | What is the time horizon for competency development? How do competency dynamics evolve over the time horizon? How much time is available for building required capability? | Time horizon; competency development time requirements; timeline feasibility. | Development time constraints are binding. Transformation timelines must account for learning curves. |
| Systems | G2 | Middle | How are competencies distributed through the system? What is the system's collective capability? What feedback loops govern competency dynamics? | System structure affecting competency distribution; cross-component competency demand; system-level capability; feedback loops affecting development/degradation. | System structure enables or constrains competency development and concentration. |
| Relations | G2 | Middle | What relationships support or inhibit competency transfer and development? What role do relationships play in competency visibility? | Relationship structure; mentoring relationships; collaboration networks; information flows. | Competency transfer happens through relationships. Hierarchical relationships can hide competency gaps. |
| Processes | G2 | Middle | What processes develop, assess, deploy, or degrade competency? What are the feedback loops? What process improvements could support competency dynamics? | Process maps; learning processes; assessment processes; deployment processes; feedback mechanisms. | Process design affects competency development feasibility and visibility. |
| Causation | G2 | Middle | What causal chains involve competency as a variable? What are the causal links between competency gaps and outcomes? | Causal models; competency as causal factor; competency gap → failure chains. | Competency is a causal variable in many failure pathways. |
| Resources | G2 | Middle | What resources are required to build, maintain, transfer, or deploy competency? What resource constraints limit competency development? | Resource inventory; resource constraints on development; investment requirements. | Resource limitations constrain feasibility of competency development. |
| Agents | G3 | Middle | What are the capability profiles of individual agents? What does each agent actually do? What are the capability-intention gaps? | Agent profiles; capability profiles; action repertoires; intentional coherence. | Agents are the locus of competency. Agent profiles feed demand-supply matching. |
| Personas | G3 | Middle | What personas do agents adopt? How do personas relate to actual capability? Where do persona-competency gaps exist? | Persona maps; persona assumptions; credibility of personas; gap assessment. | Personas may be aspirational rather than grounded in capability. |
| Incentives | G3 | Middle | What incentive structures affect competency development, transfer, visibility, or concentration? How do incentives shape competency dynamics? | Incentive maps; development incentives; transfer incentives; visibility incentives; concentration drivers. | Misaligned incentives can hide competency gaps or prevent transfer. |
| Power | G3 | Middle | How does power shape whose competency is visible, valued, or developed? Who controls competency development and deployment? How does power enable or constrain competency moves? | Power maps; formal vs informal authority; competency visibility through power lens. | Power imbalances can hide competency gaps or overvalue certain competencies. |
| Responsibility | G3 | Middle | What responsibilities are assigned to agents? What competencies do those responsibilities require? Where do responsibility-competency mismatches exist? | Responsibility maps; competency requirements per responsibility; alignment gaps. | Accountability without competency creates failure risk. |
| Competencies | G3 | Middle | (This framework itself — central to G3 Agency focus) | All artefacts produced by this framework. | — |
| Culture & Norms | G4 | Middle | What cultural norms affect competency development, visibility, valuation, or deployment? How does culture shape competency dynamics? | Culture maps; norms affecting development/visibility/valuation; cultural barriers to transfer. | Culture can suppress visibility of competency gaps or prevent honest conversation about capability. |
| Perspectives | G4 | Middle | What stakeholder perspectives assume about competency? What capability gaps exist between perspectives? | Perspective maps; competency assumptions per perspective. | Stakeholder perspectives may embed unrealistic capability assumptions. |
| Narratives | G4 | Middle | What narratives are told about competency, expertise, capability? What competency-related narrative myths exist? Where do narratives diverge from evidence? | Narrative maps; competency narratives; narrative-evidence gaps. | Narratives can cement competency myths or hide expertise. |
| Communications | G4 | Middle | How are competency gaps, concentrations, and development addressed in communications? What communication barriers affect competency visibility? | Communication analysis; transparency of competency discussions; communication quality. | Poor communication hides competency issues. Honest conversation is rare. |
| Legitimacy & Acceptance | G4 | Middle | What competencies are seen as legitimate or accepted? How does legitimacy affect whose competency is valued or visible? | Legitimacy maps; credibility factors; legitimacy of assessment systems. | Legitimacy dynamics can hide gaps or overvalue credentials. |
| Values | G4 | Middle | What values shape competency development and visibility priorities? Are competency development and honesty aligned with stated values? | Value maps; alignment of competency practices with stated values. | Values espoused may not align with competency development prioritisation. |
| Beliefs | G5 | Middle | What beliefs exist about agent capability? What gaps exist between beliefs and evidence? What capability beliefs are held without foundation? | Belief maps; belief-evidence gaps; foundational beliefs about capability. | Beliefs about capability may be wrong. Beliefs can suppress evidence of gaps. |
| Evidence | G5 | Middle | What evidence exists about competency? What evidence is available? What gaps exist in competency evidence base? What is the quality of competency assessment? | Evidence inventories; competency assessment evidence; evidence quality; assessment reliability. | Competency decisions should be evidence-based. Assessment reliability is often questionable. |
| Uncertainties | G5 | Middle | What is uncertain about competency? What unknowns exist about capability, development, transfer, concentration? How should uncertainty be managed? | Uncertainty register; competency unknowns; uncertainty management strategies. | Competency claims should include uncertainty assessment. |
| Failures | G5 | Middle | What failures involve competency as a causal factor? What competency gaps, concentrations, or degradation led to failure? | Failure analysis; competency causal factors; failure-competency links. | Failures often involve competency gaps. Post-failure investigation should include competency hypotheses. |
| Hiddens | G5 | Middle | What competency-related Hiddens exist? What is hidden about capability, gaps, concentration, degradation, assessment? | Hiddens register; competency-related Hiddens; detection mechanisms. | Many competency issues are hidden. Hiddens analysis is critical. |
| Diagnosis | G5 | Middle | How does competency factor into diagnostic hypotheses? What role does competency play in causal explanations? How should competency be investigated? | Diagnostic hypotheses; competency testing probes; hypothesis priority. | Competency should be included in diagnostic analysis. |
| Metrics | G5 | Middle | What metrics measure competency? What are the right measures? What is actually being measured? | Metric portfolio; proficiency indicators; development metrics; concentration metrics. | Metrics should measure competency dimensions, not just credentials. |
| Knowledge | G5 | Middle | What does each agent know? How complete is knowledge? How current is knowledge? What is the knowing-doing gap? | Knowledge maps; knowledge distribution; knowing-doing gap analysis. | Knowledge is necessary but not sufficient for competency. |
| Decisions | G6 | Downstream | Who actually has competency to make this decision? What competencies are required for sound decisions? How should decision rights be structured around competency? | Decision structure; required competencies per decision; competency-aware decision design. | Decisions should be assigned to agents with required competency. |
| Interventions | G6 | Downstream | What competency development is required for intervention success? What are the competency-aware design considerations? What are competency moves? | Competency moves; development plan; transfer requirements; intervention feasibility. | Interventions must account for competency constraints. Competency moves are intervention types. |
| Governance | G6 | Downstream | How does governance structure affect competency development, visibility, and deployment? What competency-aware governance changes are needed? | Governance structure; competency-aware policy; governance redesign options. | Governance structure should support rather than suppress competency development and visibility. |
| Risk | G6 | Downstream | What competency-related risks exist? What are the single-point-of-failure risks? What is the consequence of concentration? | Risk register; competency risks; concentration risks; scenario consequences. | Competency is a risk source. Concentration creates fragility. |
| Learning & Adaptation | G6 | Downstream | What learning infrastructure exists to support competency development? What is the learning velocity? What are the feedback mechanisms? What adaptation happens? | Learning architecture; development pathways; feedback mechanisms; adaptation rate. | Learning and adaptation infrastructure must support competency building. Feedback loops must inform competency dynamics. |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)

| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---:|---|---|---|
| 1 | **Credential-Competency Divergence** | Credentials (degrees, certifications, titles) are mistaken for current capability; certification assumed to equal competency; "they have the credential" accepted without performance evidence. | Triangulate: observe actual performance; collect peer assessment; review outcome evidence; test under realistic conditions. Require outcome-based assessment, not just credential review. Distinguish between "was certified once" and "is competent now." |
| 2 | **Tacit Expertise Invisibility** | Tacit knowledge and skill that cannot be easily articulated remain invisible to management; expertise concentration unknown until expert leaves; implicit knowledge not formalised or transferable. | Collect proxies for tacit competency: expert judgement consistency, error rates, improvisation quality, mentoring effectiveness, rare-event detection. Capture tacit knowledge through structured interviews, communities of practice, documentation of expert reasoning. Test for transfer success. |
| 3 | **Assessment System Gaming** | Assessment systems designed to measure competency are gamed, inflating apparent capability; self-report bias; assessors influenced by hierarchical position or likability; assessment validity not established. | Triangulate assessment sources: self-report, peer feedback, supervisor assessment, outcome evidence, scenario-based testing. Use multi-rater feedback. Validate assessment against outcome evidence. Audit assessment system for bias and gaming. Use blind assessment where feasible. |
| 4 | **Aggregation Hiding Individual Gaps** | Team-level performance metrics hide individual capability gaps; high team performance may obscure incompetence in individuals; contribution attribution unclear; star performers mask gaps in others. | Disaggregate team metrics to individual level; assess individual contribution to team outcomes; use peer assessment within teams; scenario testing; pressure-test individual capability; track decision-making attribution. |
| 5 | **Hierarchical Masking of Gaps** | Hierarchical authority obscures capability gaps; junior staff do not surface senior capability gaps; informal organisation compensates for formal incompetence; gating functions hide decision quality issues. | Collect feedback from multiple levels; use anonymous 360 feedback; interview staff about decision quality; analyse decision outcomes independent of decision-maker title; map informal decision pathways. |
| 6 | **Competency Degradation & Disuse Delay** | Competency degradation from non-use, routine conditions masking drift, pressure-testing absent, atrophy undetected until crisis; disuse over time not monitored. | Design for deliberate practice and maintenance; periodically test competency under realistic and stress conditions; monitor for drift; incentivise continuous learning; rotate staff to prevent non-use. Use simulation and scenario testing. |
| 7 | **Obsolescence Until Context Shift** | Competency remains high but becomes less relevant as context shifts; technology change, regulatory change, market shifts outpace learning; expertise in obsolete areas carried forward at cost. | Environment scanning to detect context shifts; alignment reviews of competency to current demand; honest conversation about relevance; redeployment strategies; learning and adaptation to new contexts. |
| 8 | **Concentration Risk Obscurity** | Expertise concentrated in individuals without detection; single-point-of-failure risks not recognised; succession planning absent; concentration hidden behind distributed nominal responsibility. | Explicitly map competency distribution; identify critical competencies; assess concentration; design redundancy and cross-training; succession plans; knowledge capture; test for single-point-of-failure. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)

| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|
| **I Perceptual** | Credentials dominate attention; halo effects from titles/degrees; self-presentation overweights evidence | Senior staff perceived as competent without performance evidence; junior staff capability underestimated; titles override demonstrated performance | Review credential-performance alignment; collect evidence of actual performance; peer feedback; outcome analysis; separate title from capability assessment. |
| **II Systemic** | Organisational structure obscures competency distribution; hierarchy masks informal decision-making; aggregation hides individual gaps; team structure creates capability illusions | Team metrics hide individual gaps; high team performance conceals incompetence in team members; informal organisation compensates for formal gaps; dependencies on individuals not visible | Disaggregate team metrics; assess individual contributions; map informal decision structures; test individuals independently; analyse failure modes where individual capability matters. |
| **III Informational** | Tacit knowledge not codified; expertise remains in individuals' heads; assessment systems poor quality; competency claims not validated | Expertise concentration in individuals; knowledge transfer failures; assessment validity unknown; undocumented "best practice"; informal networks; email gatekeepers | Collect proxies for tacit competency; formalise knowledge; audit assessment system; test knowledge transfer; document reasoning of experts; assess generalisability. |
| **IV Temporal** | Degradation and atrophy from non-use; obsolescence delayed until context shift; disuse over years not monitored; lag between context change and skill updating | Competency assessment stale; skills rarely tested under pressure; routine conditions mask drift; capability atrophy in disused areas; lag between context shift and learning | Periodically test competency under realistic conditions; monitor for drift; test under pressure; track learning lag behind context change; design maintenance activities. |
| **V Relational** | Power shapes whose competency is valued/visible; credentialed voices override evidence; informal networks control visibility; hierarchical relationships suppress junior feedback | Gaps in senior staff not surfaced; junior competency underestimated; contradictory feedback not escalated; informal networks control critical capability; gatekeepers hide competency distribution | Collect anonymous feedback; interview across levels; analyse decision outcomes independent of decision-maker title; map informal authority; surface contradictions. |
| **VI Ontological** | Competency defined by credentials rather than capability; "competent" conflated with "certified" or "experienced"; categories of competency not questioned; domain-specific assumptions embedded | Competency definitions aligned to credentials, not outcomes; category gaps not discovered; unquestioned assumptions about what "competence" means; transfer failures between domains assumed to be failures rather than category issues | Examine competency definitions; test whether definitions predict performance; discover category gaps; revisit whether competency concepts apply across contexts; explicit mapping to outcomes. |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)

| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability | Agency | Consequence | Detection interface(s) | Remediation interface(s) | Interaction notes |
|---|---|---|---|---|---|---|---|---|
| {{HID_COMP_001}} | {{RELEVANCE}} | {{MECHANISM}} | {{DETECTABILITY}} | {{AGENCY}} | {{CONSEQUENCE}} | {{DETECTION}} | {{REMEDIATION}} | {{NOTES}} |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts — OG v2.5 §7.2 alignment)

**Steps 1–4 (core protocol); Steps 5–7 (full framework execution):**

1. **Run Tier 1 scan across all six Hiddens meta-categories (early pass; assume Hiddens exist)** (OG §7.1). Do NOT pre-filter. Scan all six: Perceptual, Systemic, Informational, Temporal, Relational, Ontological. Record candidate Hiddens.

2. **Shortlist candidate Hiddens** (OG §7.2). For each candidate, rate: mechanism (how is it hidden?), reducibility (can we reduce it?), detectability (how visible is it?), agency (who can surface it?), consequence (what breaks if we miss it?). Prioritise high-consequence, detectable Hiddens.

3. **Build working model for top ~5–15 Hiddens** (Tier 2 – OG §D.6.10). For each, map: where it lives (framework view), how it's produced (mechanism chain), why it persists (incentives, power, narrative, structure), evidence that would confirm/disconfirm, detection interface (how to surface it), remediation interface (how to fix it).

4. **Trigger targeted scan if mechanism is specific** (OG §7.5). When Tier 1 symptoms point to a specific hiding mechanism (e.g., Suppression, Legitimacy Theatre, Positional Blindness, Cascade Discovery, Drift, Amnesia, Negligence, Intervention Blindspot), invoke appropriate Targeted Hiddens Discovery Scan (OG §7.5.2) and use the Triage Matrix (OG §7.5.3) for scan selection. Competency framework participates in cross-framework scans (especially: Positional Blindness, Competency Blindspot, Evidence Corruption).

5. **Escalate to Tier 3 if conditions warrant** (OG §7.3, §D.6.10). Escalate if: residual unknowns could change decisions/accountability; assessment systems unreliable; concentration creates single-point-of-failure; contradictions persist; repeat failures suggest hidden mechanisms.

6. **Populate all registers** (OG §D.4.1): Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests. Track status (F/I/A/U) for all items.

7. **Closure discipline** (OG §7.4). Before closing, record: (a) residual Unknowns (what remains hidden?), (b) acceptability rationale (is residual uncertainty acceptable for decision?), (c) monitoring plan (what will we watch?), (d) ownership (who owns the risk?), (e) learning hook (what should we learn from this to improve next time?).

---

# 9. Canonical Prompt Discipline Rules (PD-01–PD-10 pointer)

As per OG v2.5 §D.3, the canonical prompt discipline rules are:

- **PD-01 (Fact Discipline):** Do not invent facts. Mark claims as F/I/A/U.
- **PD-02 (Provenance):** Preserve evidence provenance. Link material claims to sources.
- **PD-03 (Test Preference):** Prefer tests over stories. Design discriminating tests.
- **PD-04 (Disagreement Transparency):** Track and escalate disagreement. Do not hide contradictions.
- **PD-05 (Closure Discipline):** Do not close prematurely. Record residual Unknowns.
- **PD-06 (Assumption Surfacing):** Make assumptions explicit. Test critical assumptions.
- **PD-07 (Evidence Quality):** Assess evidence quality. Mark bias risks.
- **PD-08 (Unknowns Honesty):** Be honest about Unknowns. Do not disguise uncertainty.
- **PD-09 (Alternatives Visibility):** Surface alternative hypotheses. Avoid premature convergence.
- **PD-10 (Learning Integration):** Record what was learned. Design iteration.

For full definitions and application guidance, see OG v2.5, §D.3.

---

# 10. Application Protocol (7-Step Rapid Protocol)

## Step 1: Initialise — Framing & Preconditions

**Activity:** Set up the competency analysis within the scenario context.

- Clarify who the focal agents are; what roles they occupy; what boundaries constrain their capability.
- Extract or construct the competency demand profile: what capabilities are required by the situation, roles, interventions?
- Verify preconditions (§1.2): agent inventory, situation clarity, baseline information, evidence access.
- If preconditions unmet, use Information Requests (§1.6.6) to flag missing inputs.

**Deliverable:** Framing memo: focal agents, roles, competency demand profile, preconditions status.

## Step 2: Generate — Inventory & Profile

**Activity:** Build a competency inventory and proficiency profiles for critical roles.

- Inventory competencies using the 6×5 taxonomy (Sections 2–3). For each agent/role, profile critical competencies.
- For each competency, assess dimensions (§4.1): type, reliability/depth, transferability, acquisition/renewal, visibility.
- Note proficiency level, concentration (how many agents have it?), and visible/hidden balance.
- Identify data gaps; use Information Requests to flag missing evidence.

**Deliverable:** Competency inventory (agent × competency matrix); proficiency profiles for critical roles; dimension profiles; concentration assessment.

## Step 3: Route — Minimum Coverage & Depth Plan

**Activity:** Apply OG §4.3 routing to determine group coverage and per-framework depth.

- At Start-of-Run, use OG §4.3 to determine: Is this Rapid or Investigative Run Mode?
- Determine minimum group coverage. For competency work: G3 primary; G2 secondary. Include G5 if assessment disputed; G6 if learning/development is remediation.
- Set per-framework depth: Light Depth (inventory, top gaps, baseline) vs Full Depth (demand-supply deep match, concentration deep assessment, interfaces, dynamics).
- Record routing statement and escalation triggers.

**Deliverable:** Routing statement; minimum group coverage; Full Depth / Light Depth plan; escalation decision.

## Step 4: Execute — Demand-Supply Analysis & Hiddens

**Activity:** Perform core competency analysis and run Tier 1 Hiddens scan.

- **Demand-supply matching:** For each critical competency, compare what is required (demand) to what agents possess (supply) at what proficiency. Identify gaps.
- **Concentration assessment:** Map competency distribution. Identify critical competencies concentrated in individuals. Flag single-point-of-failure risks.
- **Dynamics hypotheses:** Trace competency trajectories — are they building, transferring, degrading, becoming obsolete? What dynamics matter?
- **Interfaces:** For assessment (A), development/transfer (B), and demand/deployment (C), identify what is working and what is failing.
- **Tier 1 Hiddens scan (early pass):** Run the six-category scan (§8.2). Assume Hiddens exist. Do not pre-filter. Record all six categories.

**Deliverable:** Demand-supply gap map; concentration assessment; dynamics hypotheses; interface assessment; Hiddens register (Tier 1 early pass); Evidence Ledger (populated with competency evidence).

## Step 5: Test — Probes & Evidence

**Activity:** Design and execute probes to test competency hypotheses.

- For top Unknowns, design tests: structured assessment, peer review, scenario-based performance, pressure testing, cross-training trials, knowledge transfer tests.
- Execute probes as feasible (interviews, observation, simulation, outcome analysis).
- Build Evidence Ledger (§1.6.6): for each material claim about competency, track supporting/contradicting evidence, evidence quality, gaps.
- Build Hypothesis/Test Backlog (§1.6.6): for Unknowns, specify if-true/if-false observable differences, test design, priority.
- Populate Information Requests (§1.6.6): for decision-critical Unknowns, explicitly request missing inputs, why needed, discriminator value.

**Deliverable:** Test results; updated Evidence Ledger; Hypothesis/Test Backlog; Information Requests.

## Step 6: Re-scan — Tier 1 Pre-Closure & Tier 2 Deepening

**Activity:** Repeat Tier 1 Hiddens scan and optionally deepen top Hiddens (Tier 2).

- **Tier 1 pre-closure pass:** Run six-category scan again (§8.2). Compare to early pass. Record new discoveries.
- **Tier 2 deepening (if Investigative Run Mode or high-stakes):** For top ~5–15 candidate Hiddens, build working models (§8.3): mechanism chain, persistence drivers, detectability, agency, detection/remediation interfaces, interaction notes.
- **Targeted scan trigger:** If Tier 1 symptoms point to specific mechanism (Suppression, Legitimacy Theatre, etc.), invoke Targeted Hiddens Discovery Scan from OG §7.5 and use Triage Matrix (OG §7.5.3).
- **Escalation assessment:** Should this escalate to Tier 3 (full Hiddens taxonomy)? Decide based on stakes, contradiction persistence, repeat failure, assessment unreliability, concentration risk.

**Deliverable:** Tier 1 pre-closure scan results (comparison to early pass); Tier 2 working models (if executed); targeted scan outputs (if triggered); escalation decision.

## Step 7: Decide/Close — Competency Strategy & Closure Discipline

**Activity:** Synthesise findings into competency strategy and apply closure discipline.

- **Competency strategy:** From gaps and concentration assessment, design competency moves: (a) develop (build required capability), (b) acquire (hire/partner), (c) transfer (formalise and spread), (d) protect (guard critical expertise), (e) redeploy (move capability to where needed), (f) retire (phase out obsolete capability).
- **Monitoring & governance:** For each move, specify: timeline, resource requirements, governance, monitoring indicators, review cadence, ownership.
- **Closure discipline (OG §7.4 — five required items):**
  - (1) Residual Unknowns: What remains hidden? Why can we not close this?
  - (2) Acceptability rationale: Is residual uncertainty acceptable for decision? Why or why not?
  - (3) Monitoring plan: What will we watch to detect if assumptions fail?
  - (4) Ownership: Who owns the competency risks and the monitoring?
  - (5) Learning hook: What should we learn from this analysis to improve next time?
- **Escalation recommendation:** Should competency issues escalate to full Hiddens investigation (Tier 3) or governance redesign?

**Deliverable:** Competency strategy (six move types with timelines, resources, governance, indicators); monitoring plan; closure note (five items); escalation recommendation.

---

# 11. Principles & Glossary

## 11.1 Core Principles

1. **Competency is demonstrated capacity, not credentials.** Assess by outcomes and observable performance, not credentials or self-report alone.

2. **Knowledge and competency are distinct.** Knowing something is not the same as being able to do it reliably under real-world conditions.

3. **Competency is agent-relative.** Competency is "for whom, in what context, at what proficiency, for what timespan?"

4. **Competency dynamics matter.** Competencies are not static; they build, transfer, degrade, concentrate, and become obsolete.

5. **Concentration creates fragility.** Expertise concentrated in individuals without redundancy or transfer creates undetected single-point-of-failure risk.

6. **Visibility failures are common.** Credentials are mistaken for capability; tacit expertise is invisible; assessment is gamed; degradation is masked; concentration is hidden.

7. **Competency assessment must be triangulated.** Use multiple sources: self-report, peer feedback, supervisor assessment, outcome evidence, scenario testing.

8. **Competency is a system property.** Individual capability does not guarantee system-level capability. Interdependence, tools, and structure matter.

9. **Competency moves are intervention levers.** Develop, acquire, transfer, protect, redeploy, retire — these are the primary ways to improve capability.

10. **Competency strategy guides governance.** Accountability, resource allocation, learning programmes, and role design should be competency-aware.

## 11.2 Glossary

| Term | Definition |
|---|---|
| **Competency** | The demonstrated capacity of an agent to perform a specified kind of action reliably and effectively under real-world conditions, drawing on knowledge, skill, judgement, and practice. Assessed by outcomes and observable performance, not credentials or self-report alone. |
| **Proficiency** | The level of reliable, effective performance in a competency, typically ranging from Novice / Intermediate / Advanced / Expert. |
| **Tacit competency** | Expertise that cannot be easily articulated or codified; skill and knowledge held implicitly in practice, intuition, and experience. |
| **Competency concentration** | The distribution of critical competencies among agents; high concentration (few agents) creates fragility; low concentration (redundancy) creates resilience. |
| **Demand-supply gap** | The mismatch between competency demand (what is required by the situation/role/intervention) and competency supply (what agents possess at required proficiency). |
| **Competency transfer** | The process of transmitting competency from one agent to another; can succeed (transfer complete) or fail (transfer incomplete, tacit knowledge not captured). |
| **Competency degradation** | Decline in proficiency from non-use, disuse, pressure effects, environmental change, or skill atrophy. |
| **Competency obsolescence** | Competency that remains at prior proficiency but becomes less relevant or effective as context shifts. |
| **Credential-competency divergence** | The gap between what credentials attest (past assessment) and current demonstrated capability. |
| **Assessment theatre** | Assessment practices that appear to measure competency but do not; gaming, inflation, or misalignment between assessment and actual capability. |
| **Single-point-of-failure risk** | Vulnerability created when a critical competency is concentrated in one or few individuals without redundancy or transfer. |
| **Competency move** | An explicit action to change competency distribution: develop (build), acquire (hire/partner), transfer (formalise and spread), protect (guard), redeploy (reallocate), retire (phase out). |
| **Competency dynamics** | Patterns of how competencies change over time: building, transfer, degradation, concentration, obsolescence. |
| **Knowing-doing gap** | The gap between knowledge (what is known/understood) and competency (what can be reliably done). |
| **Hiddens (competency-specific)** | Competency-related visibility failures: credential-competency divergence, tacit invisibility, concentration, degradation, assessment gaming, obsolescence delays. |
| **Tier 1 Hiddens scan** | Early scan across all six Hiddens meta-categories to surface candidate Hiddens (mandatory at least twice per scenario). |
| **Tier 2 Hiddens deepening** | Structured deepening of top 5–15 candidate Hiddens with mechanism, detectability, agency, consequence, and interface analysis. |
| **Tier 3 Hiddens escalation** | Full-spectrum Hiddens taxonomy analysis; triggered when high-stakes, contradictions persist, repeat failures, or assessment unreliability. |

---

**END OF DOCUMENT**

Total line count: 936 lines
Total word count: Approximately 820 words (focused, substantive content)
Status: Complete, v2.0 aligned to OG v2.5 with all mandated sections populated.
