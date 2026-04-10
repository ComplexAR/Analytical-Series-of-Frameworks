# Framework of Communications
*A Comprehensive Taxonomy of How Information Flows Through Systems—and How to Diagnose and Redesign Communication Architecture for Reliability, Trust, and Learning*

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
- Group (Primary): G4 — Meaning, interpretation & social order (Meaning)
- Group (Secondary): G3 — Agency & legitimacy (Agency)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Map and diagnose communication architectures; classify communication types; profile communication dimensions; analyse communication dynamics and interfaces; identify hiddens and hidden flows; redesign channels, protocols, and feedback loops for reliability, legitimacy, and learning
- Primary Audience: Executives; strategists; programme and transformation leaders; incident and crisis leaders; risk and resilience leaders; communications leaders; product and technical leaders; governance and compliance leaders; investigators and auditors
- Dependencies / Key Inputs: Focal decision or question; stakeholder and role map; channel inventory (formal + informal); artefacts and logs (documents, tickets, telemetry); governance and incentive context; time horizons and escalation requirements
- Primary Outputs: Communication architecture map; type register and dimension profile; dynamics and interface analysis; hiddens source register + tiered Hiddens scan outputs; redesign and governance plan; monitoring metrics (signal quality, latency, understanding, correction rate)
- Change Log (brief): Rewrite for Master Template v2.3 alignment; updated all OG references from v1.5 to v2.5; added Introduction section (four subsections); expanded §1.6 with Tier 2 Hiddens crosswalk, Targeted Scans routing, and Information Requests schema; updated Document Information with Tiered Hiddens Scan Model and Targeted Hiddens Discovery Scans fields; expanded §1.4 with Stage assignment, Framework Index pointer, and Iteration loop statement; added Group and Stage columns to §7.3 framework integration list (all 36 canonical frameworks); expanded §8 with Tier 2 structured deepening guidance and Targeted Scans escalation trigger; updated §11.2 pointer to OG v2.5; preserved all thirty communication types and core operational content.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **How does information actually move (and fail to move) through this system, and what redesign levers improve reliability, trust, and action?** |
| Addresses | Channel myopia; content-only focus; missing feedback loops; drift and distortion; overload; shadow channels; boundary translation failures; adversarial misinformation; dashboards detached from lived reality. |
| Gap Filled | Other frameworks describe what exists, who acts, or what is true. Communications provides the connective tissue: the channels, encodings, protocols, and dynamics that determine whether reality is perceived, coordinated on, and learned from. |
| Complements | Culture & Norms; Narratives; Perspectives; Power; Incentives; Hiddens; Evidence; Failures; Systems; Time; Scale; Boundaries; Diagnosis; Decisions; Governance; Learning & Adaptation. |
| Key Characteristics | Six meta-categories; thirty communication types; five dimensions; ten dynamic patterns; three interface types; hiddens source analysis + tiered Hiddens cross-check; 7-step application protocol. |
| Main Contributions | A repeatable communications scan; system-level architecture mapping; diagnostics for amplification/decay/drift/feedback/shadowing; design levers for governable communication and learning; triage and escalation criteria. |

---

# Introduction

## What is Communications?

Communication is the patterned movement of meaning-bearing signals between agents through channels, encodings, interaction structures, and governance rules. It is not merely "messages sent"—it encompasses the medium and its affordances, who can speak to whom, how feedback works, what is recorded and what is lost, which flows become formal records and which become shadow systems, and how authority shapes what can be said or heard. Many failures that appear to be "bad decisions," "poor leadership," or "inadequate expertise" are in fact fundamentally failures of communication: the right information did not reach the right actor in the right form at the right time, or it arrived distorted, unactionable, or perceived as illegitimate.

This framework provides a systematic anatomy of communication systems: the channels that carry signals, the encodings that represent meaning, the interaction structures that connect senders and receivers, the protocols and governance that make communication accountable, the persuasion strategies and signals that shape beliefs, and the hidden filtering mechanisms that suppress or amplify messages. Without this lens, communication appears as a transparent service—either it "works" or it doesn't. With this framework, communication becomes an observable and designable system property.

## Why does Communications matter for Hiddens work?

Communication failures concentrate several families of hiding mechanisms:

**Signal filtering and amplification** (Hidden-5, Hidden-13) operate at every boundary—across roles, channels, systems, and time. Information is compressed, translated, filtered for salience or policy compliance, or amplified through reputational risk. What reaches senior leadership is often the inverse of what frontline staff know. What survives organisational boundaries is shaped by gatekeepers' incentives and politics. Channels appear neutral; in fact, they are selective.

**Format distortion and translation loss** (Hidden-11, Hidden-20) arise because different encodings make different realities interpretable or invisible. A dashboard metric optimises for speed; it hides distributional variance and context. A narrative arc is emotionally compelling; it hides counterfactuals. A technical specification is precise; it hides user friction. The richer and more defensible the message, the more hidden the alternatives that had to be excluded.

**Shadow channels and informal networks** (Hidden-14, Hidden-3) emerge when formal channels fail—they are not dysfunctions but adaptations. Yet they bypass audit, governance, and escalation. What appears to leadership as a unified decision-making process is in fact a fragmented shadow network where real coordination happens outside the formal structure. When investigations probe these shadows, the full extent of organisational parallel processing becomes visible.

**Feedback loop closure failures and temporal distortion** (Hidden-7, Hidden-15) allow misunderstandings to persist and diverge. When error correction is slow, weak, or asymmetric (frontline learns leader's mistakes quickly; leaders never learn of frontline workarounds), the organisation operates on a stale shared model. Cascades of small misalignments compound into regime change that formal reporting never detects.

**Persuasion and narrative capture** (Hidden-9, Hidden-8) mean that communication shapes not just what is known but what is credible and worth acting on. A narrative told repeatedly becomes "common sense"; alternatives become invisible. A trusted narrator's framing determines what subsequent facts will be assimilated into. Communication is not neutral carrier of pre-existing truth; it is constitutive of what counts as true for purposes of action.

Without this framework, these Hiddens remain latent. With it, communication architecture becomes a field for systematic diagnosis: where are the bottlenecks? Where does signal decay fastest? Which interfaces generate most distortion? Which feedback loops are broken? Which channels are shadow, and why? Where is persuasion operating without transparency?

## What does this framework produce?

The framework operationalises communication diagnosis through six core elements:

1. **A taxonomy of 30 communication types** organised into six meta-categories (Channel & Medium, Encoding & Representation, Interaction-Structure, Protocol & Governance, Persuasion & Signalling, Hidden Flows & Feedback), enabling rapid classification of communication patterns.

2. **Five cross-cutting dimensions** (multiplicity, signal-to-noise, latency, correctness/understanding, governability) that profile any communication pattern and explain why the same channel produces different outcomes for different users or at different times.

3. **Ten dynamic patterns** (Amplification, Decay, Drift, Feedback Correction, Shadowing, Encoding Loss, Authority Asymmetry, Legitimacy Crisis, Correction Lag, Cascading Silence) that describe how communication changes over time and under stress.

4. **Three interface types** (Channel Interface, Translation Interface, Authority Interface) that identify zones where signals are most likely to fail or distort.

5. **Hiddens source analysis and tiered Hiddens scans** that surface the four systematic sources of communication-based visibility failure (channel blindspots, encoding collapse, protocol gaps, feedback failure) and mechanism-specific detection approaches.

6. **A seven-step application protocol** that moves from channel mapping through type classification, dimensional profiling, dynamics analysis, interface diagnosis, Hiddens scanning, and integration into design and governance plans.

The framework populates standard registers (Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests) that integrate into the broader Analytical Series workflow. It produces artefacts (channel maps, type registers, dimension profiles, interface maps, redesign options) that enable informed diagnosis and targeted intervention.

## How to use this framework

Invoke this framework whenever:
- a decision or action depends on information flowing reliably between roles or systems,
- failures occur repeatedly despite good faith and adequate resources (often communication is the root),
- organisations describe themselves as suffering from "silos" or "misalignment" (communication architecture is the mechanism),
- crises expose gaps between what was reported and what was known in the field (communication protocol failure),
- stakeholders claim competing pictures of what "actually happened" (often a communication/framing/encoding issue, not a factual dispute).

Default execution is Light Depth Framework Execution: inventory the focal channels, classify 3–5 critical types, identify obvious interfaces and dynamics, run a Tier 1 Hiddens scan. Escalate to Full Depth when consequence is high, evidence is weak, multiple channels are contested, or you are diagnosing a cascade or compound failure.

The framework works in both Rapid Run Mode (triage channel failures in an incident) and Investigative Run Mode (systematic architecture redesign). It integrates naturally with diagnosis, systems analysis, and governance frameworks. For LLM execution, see §1.6 for the complete specification, standard registers, and copy-ready prompts. The framework is designed for direct executable application given a focal scenario, organisational context, and the Operating Guide.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise
Communication is the patterned movement of information between agents through channels, encodings, interaction structures, and governance rules. It is not only "messages sent": it includes the medium and the representation, who can speak to whom, how feedback works, what is recorded, what is filtered, and which flows become shadow systems. Many failures that look like "bad decisions" are communication failures: the right information did not reach the right actor in the right form at the right time, or it arrived distorted, unactionable, or illegitimate.

This framework provides a repeatable approach to:
- inventory formal and informal communication channels and media,
- classify communication types using a stable taxonomy (6 meta-categories × 5 types = 30),
- profile communication flows along five cross-cutting dimensions,
- analyse communication dynamics (patterns of amplification, decay, drift, feedback, shadowing),
- map interfaces where communication is most likely to fail (channel boundaries, encoding transitions, authority asymmetries),
- scan for characteristic Hiddens (filtering, distortion, delay, strategic silence),
- identify redesign levers for reliability, trust, and learning, and
- integrate communication insights into broader governance and intervention planning.

## 1.2 Assumptions & Preconditions

### Assumptions Register (recommended)
| Assumption | Type (method / structural / domain / normative) | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Communication architecture is observable and diagnosable like any system property | Structural | Analysis remains impressionistic; improvements aren't trackable. | Map channels; test feedback; measure latency and accuracy; compare before/after redesign. | Combine interviews with logs/data; test hypotheses against ground truth; use telemetry to validate. |
| Signal quality, latency, and feedback completeness are primary diagnostics | Method | Misses governance, encoding, and trust issues that shape effectiveness. | Measure signal-to-noise, correctness rates, decision latency, correction cycle times. | Use multi-dimensional profiling; include legitimacy, understanding, and trust; add Power/Culture/Hiddens scans. |
| Communication failures concentrate at interfaces (across roles, systems, channels) | Structural | Treats comms as uniform; misses specific failure hotspots. | Map interfaces (Type A–C); test failure rates at boundaries; trace signal decay at transitions. | Apply interface-specific diagnostics and redesigns; strengthen weakest links first. |
| Shadow channels and informal networks emerge when formal channels fail | Structural | Underestimates informal coordination costs and risks. | Probe for shadow workflows and backchannels; test escalation paths; interview frontline staff. | Map and legitimise appropriate informal channels; formalize critical workarounds; provide governance. |
| Contexts with high stakes and weak feedback are vulnerable to communication drift and misalignment | Normative | Downplays latency and correction loop risks; over-confident in broadcasting. | Assess feedback loop completeness; stress-test understanding; audit latency in crisis modes. | Escalate to full Hiddens protocol when high-consequence decisions depend on communication. |
| Encoding choices (dashboards, narratives, formats, abstractions) hide as much as they reveal | Structural | Treats information as pre-made facts; misses how representation shapes perception. | Compare interpretations across user types; test comprehension; document encoding failures. | Use multiple encodings for critical signals; invest in error-control and context. |
| Communication governance failures amplify other risks | Structural | Treats governance as bureaucratic overhead; underestimates trust and coordination cost. | Audit protocol compliance; assess correction cycle effectiveness; measure escalation responsiveness. | Strengthen governance design; test under stress; integrate with Power/Incentives. |

### Preconditions Checklist (recommended)
| Precondition | Required? (Y/N) | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Focal decision or question (what comms need to serve?) | Y | Decision charter; stakeholder requirements; incident timeline | Sponsor / facilitator | Agreed and documented | Use highest-stakes communication challenge as focal point. |
| Channel inventory (formal and shadow) | Y | Communications audit; network map; telemetry of flow; log analysis | Comms owner / IT / analyst | Inventory compiled; gaps identified | Start with formal channels; discover shadows during interviews; use proxy data. |
| Evidence of communication failures (past incidents, metrics, feedback) | Y | Incident logs, escalation trails, feedback from stakeholders, post-mortems | Risk / Quality owner | Data collected and compiled | Conduct structured stakeholder interviews on comms friction and workarounds. |
| Governance and decision rights (who owns channels; who can change them?) | Y | Policy documents, authority map, process flows, RACI matrix | Governance owner | Model documented and verified | Clarify early with sponsor and governance owner; map de facto decision rights. |
| Time and resources for architecture mapping and testing | Y | Project schedule, facilitation resources, budget for diagnostics | Sponsor / PM | 20–40 hours allocated minimum for Light Depth; 60–120 hours for Full Depth | Begin with critical channels; expand scope incrementally; use proxy facilitation. |
| Access to channel logs, data, and technical infrastructure | Y | Log access confirmed; telemetry availability; technical team availability; data governance approval | IT / Data owner | Access provisioned and tested | Combine logs with interview-based mapping; sample data if full access unavailable; note limits. |
| Stakeholder availability for interviews and workshops | Y | Interview schedule confirmed; workshop participants identified; calendar blocks | Analyst / Comms owner | Interviews and workshops scheduled | Use email prompts and asynchronous feedback; conduct one-on-one interviews as fallback. |

## 1.3 Definitions, Scope, and Non-Goals
- **Communication (operational)**: The end-to-end process by which meaning-bearing signals are produced, transmitted, received, interpreted, acted upon, and fed back, shaping shared models and coordinated action.
- **In scope**:
  - Six meta-categories and thirty core communication types
  - Five dimensions for profiling communication flows
  - Ten key dynamics (patterns of change over time)
  - Three interface types where failures concentrate
  - Hiddens source analysis + tiered Hiddens cross-check
  - Application protocol and standard deliverables
- **Out of scope**:
  - Full causal modelling of underlying mechanisms (use Causation/Systems)
  - Full persuasion ethics and legitimacy adjudication (use Legitimacy/Culture & Norms; still integrate here where comms integrity matters)
  - Full adversarial security doctrine (use Risk/Governance; still integrate here where comms security and integrity matter)

## 1.4 Position in the Series (Upstream / Middle / Downstream)
- **Upstream**: Agents; Systems; Boundaries; Time; Scale; Power & Incentives; Culture & Norms; Perspectives; Evidence
- **Middle (this framework's role)**: Communication architecture mapping, diagnostics, and redesign levers
- **Downstream**: Diagnosis; Decisions; Interventions; Governance; Responsibility; Learning & Adaptation; Risk
- **Group assignment (Primary)**: G4 — Meaning, interpretation & social order (Meaning)
- **Group assignment (Secondary)**: G3 — Agency & legitimacy (Agency)
- **Stage assignment**: Middle (see OG v2.5 §3.1)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.9.2 Mode Selection Gate)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
- **Framework Index**: this framework is one of 36 in the series (see OG v2.5 §3.2 for the full Framework-to-Group mapping)

## 1.5 Crosswalk Summary (recommended)
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Meaning and sensemaking | Communications; Culture & Norms; Narratives; Perspectives | How meaning is produced, shared, contested, and stabilised across groups | A concrete inventory of channels/encodings/protocols and a design discipline for feedback, translation, and governability. |
| Power, incentives, and legitimacy | Power; Incentives; Legitimacy; Governance; Responsibility | Who can speak, who is heard, and how authority and rewards shape communication | How communicative power is exercised through channels (broadcast, censorship, signalling) and how to redesign for accountability and trust. |
| Epistemic quality and error control | Evidence; Failures; Hiddens; Uncertainties; Diagnosis | Standards for truth claims, failure patterns, visibility limits, and structured diagnosis | Where truth degrades (noise, distortion, drift) and how to instrument correction loops and provenance. |
| Systems and operations | Systems; Time; Scale; Boundaries; Learning & Adaptation | Dependencies, horizons, cross-level interactions, and improvement loops | Communication architecture as a system property; dynamics (amplification/decay) and redesign levers for operational reliability. |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Communications_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Communications when… | Use neighbour instead when… |
|---|---|---|
| Culture & Norms | Diagnosing how information flows through channels and encoding/representation shapes shared understanding | Analysing meaning production, cultural values, and identity formation independent of information flow; studying how worldviews form and persist |
| Narratives | Analysing how repeated messaging and framing affect what counts as real or credible; understanding narrative pathways through channels | Analysing narrative arc, character development, and story logic independent of distribution mechanism; studying how narratives are constructed or contested |
| Power | Analysing how communicative power is exercised (who controls channels, who is silenced, how authority shapes what is heard) | Analysing abstract power distribution, bargaining dynamics, and dependency relationships independent of communication channels; studying agency and decision-rights |
| Evidence | Analysing where signal degrades (noise, distortion, drift) and how communication protocol affects truth claims and provenance | Analysing standards for what constitutes evidence, burden of proof, and epistemic warrant independent of how information is transmitted |
| Governance | Analysing communication protocols, escalation rules, and feedback mechanisms embedded in governance design | Analysing formal authority structure, decision-rights allocation, and accountability mechanisms independent of communication architecture |

### 1.6.3 Routing triggers
- Decision or action depends on information flowing reliably between roles or systems
- Communication failure symptoms (misalignment, competing narratives, silos, gaps between reported and field reality)
- Channel bottlenecks or signal loss prevent decision-makers from receiving critical information
- Feedback loops are slow, broken, or asymmetric (one direction learns; other does not)
- Message distortion through encoding collapse, format mismatch, or relay chains obscures reality
- Shadow channels and informal workarounds indicate formal channels have failed
- Stakeholders have competing pictures of what happened (communication/framing issue suspected)
- Escalation or error correction mechanisms are absent or non-functional
- Governance or protocol violations are concentrated in communication flows
- Crisis or time-pressure scenarios reveal communication architecture fragility


---

# 2. Meta-Categories of Communications

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---|---|---|---|---|
| I | Channel & Medium | Through what channels and media does information travel, and what do they enable or suppress? | Channels as the 'plumbing' of information: where messages can physically, socially, or digitally move. | channel inventory; comms architecture diagrams; meeting maps; telemetry/log maps; channel risk assessment |
| II | Encoding & Representation | How is information encoded/represented, and what is lost, emphasised, or made illegible by the representation? | The representational layer: language, formats, abstractions, and error controls that determine interpretability. | glossaries; templates; dashboards; model/metric definitions; data schemas; visualisations; encoding standards |
| III | Interaction-Structure | How are senders and receivers connected (dyadic, broadcast, networked), and what does that imply for coordination and feedback? | Topology and cadence of exchange: who talks to whom, when, and with what feedback and amplification dynamics. | stakeholder network maps; broadcast plans; collaboration patterns; meeting cadences; incident comms timelines |
| IV | Protocol & Governance | What rules, norms, and technical/organisational protocols govern communication, and how do they shape reliability and accountability? | Governance and control: protocols, records, escalation routes, and cultural norms that make comms governable. | RACI/decision rights; audit trails; incident playbooks; approvals; comms policies; cultural norms audits |
| V | Persuasion & Signalling | How does communication shape beliefs, preferences, and behaviour through persuasion, narrative, and signalling? | Influence layer: persuasion strategies, narrative structures, and signalling mechanisms that shape interpretation. | message testing; narrative maps; reputation audits; stakeholder sentiment; signalling analysis; comms ethics reviews |
| VI | Hidden Flows & Feedback | What information flows and feedback loops are obscured, deprioritised, or operating outside formal systems? | The shadow layer: informal networks, workarounds, filter evasion, and mechanisms that enable or suppress truth-seeking. | informal network maps; bypass routes; shadow protocol inventories; escalation failure analysis; correction loop audits |

## 2.2 Meta-Category Descriptions (recommended)

### I. Channel & Medium
- **Definition**: The physical, social, technical, or organisational structures through which signals move. Includes synchronous (face-to-face, calls, live chats) and asynchronous (email, documents, logs) channels; formal (email systems, meeting protocols) and informal (hallway conversations, backchannel messaging); push (broadcast), pull (request), and reactive (escalation response) patterns.
- **Diagnostic cues**: Channel congestion or silence; signals reaching wrong recipients or not reaching at all; medium mismatch (using email for real-time decisions; using synchronous meetings for purely informational updates); channel-specific failure rates (one channel loses critical data consistently).
- **Typical failure mode**: Channel myopia (assuming formal channels carry all important information; ignoring shadow channels); medium-message mismatch (format prevents comprehension); channel overload (too many signals, critical ones buried); dead channels (formally designated but not used).

### II. Encoding & Representation
- **Definition**: How information is structured, formatted, abstracted, or symbolised for transmission. Includes language choices, metric selection, narrative framing, abstraction level, visual design, and error-control mechanisms (checksums, replication, redundancy).
- **Diagnostic cues**: Stakeholders interpret the same encoded message differently; dashboards hide important variation; narratives are emotionally compelling but factually incomplete; technical specs are precise but unactionable for users; abstract models fail when applied to ground truth.
- **Typical failure mode**: Encoding collapse (rich context squeezed into metrics or abstractions); format rigidity (one encoding for all audiences); translation loss (encoding fails at system or scale boundaries); narrative capture (repeated framing becomes "common sense").

### III. Interaction-Structure
- **Definition**: The topology and cadence of exchange: who talks to whom, when, in what order, with what feedback loops and amplification/dampening effects. Includes dyadic (one-to-one), broadcast (one-to-many), networked (many-to-many), and hierarchical structures.
- **Diagnostic cues**: Information flows in one direction only (broadcast without feedback); feedback loops are slow or asymmetric (frontline learns of leader mistakes quickly; leaders never learn frontline workarounds); coordination happens outside formal structures; some stakeholders are structurally excluded from critical conversations.
- **Typical failure mode**: Feedback failure (corrections never return to source); amplification asymmetry (some signals are amplified, others dampened, based on politics rather than merit); unidirectional broadcasts (announcement treated as decision despite lack of understanding confirmation).

### IV. Protocol & Governance
- **Definition**: The rules, standards, norms, and technical controls that govern how communication should operate. Includes escalation protocols, approval requirements, record-keeping standards, rotation of power, and accountability mechanisms.
- **Diagnostic cues**: Protocol breaches are tolerated or hidden; escalations follow unofficial channels; records are incomplete or unreliable; cultural norms suppress dissent or honest error reporting; decision rights are ambiguous.
- **Typical failure mode**: Protocol-reality gap (official procedures differ from actual practice); weak correction mechanisms (errors go undetected or unreported); single points of failure (one gatekeeper controls critical flows); governance creates perverse incentives (shoot-the-messenger culture prevents bad news from surfacing).

### V. Persuasion & Signalling
- **Definition**: How communication shapes beliefs, preferences, and sense of legitimacy through narrative, reputation, authority, and strategic messaging. Includes explicit persuasion (arguments, appeals), narrative framing (which story becomes canonical), and signalling (inference from what is (not) said, who says it, when).
- **Diagnostic cues**: Decisions are based on "story" more than evidence; a single trusted narrator's framing reshapes interpretation of facts; stakeholders infer intent from absence (silence signals refusal); reputation effects are path-dependent (early impression is sticky despite contradicting evidence).
- **Typical failure mode**: Narrative capture (one frame dominates; alternatives become invisible); authority capture (trusted narrator's credibility insulates their claims from questioning); persuasion without transparency (influence tactics are invisible to audiences).

### VI. Hidden Flows & Feedback
- **Definition**: Information flows and feedback loops that operate outside or in tension with formal systems. Includes shadow channels (informal workarounds), deprioritised flows (information available but not acted on), suppressed feedback (corrections that never propagate), and filter evasion mechanisms.
- **Diagnostic cues**: Formal organisation chart does not map to actual decision flows; critical information reaches leadership through informal networks only; frontline staff have developed workarounds to formal procedures; escalation failures (critical alerts don't reach decision-makers); correction loops are broken (feedback doesn't generate action).
- **Typical failure mode**: Shadow system complexity (parallel processing creates coordination costs); governance blindness (formal systems don't see shadow flows); cascade risk (shadow system failure causes cascade failure because formal system is atrophied).

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- **Canonical baseline**: 6 meta-categories × 5 types = 30 core types.
- **This framework**: 30 types. No deviation from baseline.
- **Mapping back to baseline**: Full alignment with Analytical Series canonical structure.

## 3.1 Types (Category I: Channel & Medium)
| # | Type | Description (1–3 sentences) | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 1 | Synchronous Co-Located | Face-to-face meetings, shared physical space, real-time exchange. Highest bandwidth, full sensory context; highest coordination cost. | Used for high-stakes or emotionally charged topics; decision-makers physically absent; remote workers structurally excluded. | Physical distance exclusion; side conversations dominate; informal power shapes floor access. |
| 2 | Synchronous Distributed | Calls, video conferences, instant messaging, live collaboration. Real-time without shared space; asynchronous latency; medium-dependent dropout. | Preferred for coordination; technical glitches cause information loss; camera-off creates asymmetry; some participants multitask. | Technical failures unmask who was actually listening; side-channel communication bypasses record. |
| 3 | Asynchronous Document-Based | Email, shared documents, wikis, recorded decision trails. Slow but auditable; creates searchable record; allows async contribution; prone to version confusion. | Used for decisions where speed is not critical; official version of truth disputes; email threads as primary decision-making. | Document fragmentation (info scattered across versions/threads); email shadows actual decision-making; records become stale. |
| 4 | Formal Broadcast | Published announcements, newsletters, all-hands addresses, organisational policy updates. Uni-directional, reaches many simultaneously, difficult to confirm understanding. | Used for announcements management assumes all heard; no feedback loop; senior leadership surprises by what they didn't know staff knew. | Announcement treated as decision without understanding check; opposite interpretation by different groups; no mechanism to surface misunderstanding. |
| 5 | Escalation & Alert | Incident pages, alert systems, emergency codes, critical-priority messages. Designed for high-stakes urgency; prone to alarm fatigue and override. | Used for critical issues; alert systems frequently triggered; escalation sometimes bypassed; unclear protocols. | Alarm fatigue suppresses attention; escalation authority not distributed; critical alerts buried in noise. |

## 3.2 Types (Category II: Encoding & Representation)
| # | Type | Description (1–3 sentences) | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 6 | Metric & Dashboard | Quantified summaries, performance indicators, data visualisations, scorecards. Enables trend spotting and comparison; hides tail events and distributional variance; selects what gets measured. | Dashboard widely consulted; stakeholders dispute what metrics mean; metrics don't match lived experience. | Goodhart's law (metrics become targets); variance hidden; context-collapse (single metric represents complex reality); metric gaming. |
| 7 | Narrative & Story | Causal stories, organisational history, case studies, exemplars, metaphor-based reasoning. Emotionally compelling; memorable; shapes what counts as relevant; excludes counternarratives. | Story repeated reliably across organisation; emotional resonance drives decisions; alternative stories are suppressed or dismissed. | Narrative path-dependency (early story is sticky); single narrative dominates despite counterfactual evidence; alternatives become invisible. |
| 8 | Technical Specification | Detailed design documents, code documentation, procedural manuals, API contracts. Precise and implementable; inaccessible to non-specialists; easily becomes stale; misses user experience. | Specification exists but differs from what was implemented; user friction not captured in spec; specification written post-hoc as fiction. | Implementation-spec drift (document doesn't match code); user experience ignored; non-specialists uninformed. |
| 9 | Abstract Model & Framework | Conceptual models, strategic frameworks, reference architectures, decision trees. Enables reasoning across domains; risks oversimplification and misapplication; hides what doesn't fit model. | Model widely used; corner cases keep appearing; model breaks predictably under stress; map-territory gap widening. | Model reification (model treated as reality); edge cases dismissed; model-breaking scenarios treated as anomalies not model failure. |
| 10 | Visual & Sensory | Charts, diagrams, audio, colour, layout, visual prominence, spatial arrangement. High cognitive bandwidth; enables rapid intuition; easily misinterpreted; language-independent but culturally dependent. | Different stakeholders interpret same visual differently; visual hierarchy drives attention (danger highlighted, safe areas look risky). | Visual interpretation asymmetry (what looks dangerous to expert looks normal to novice); colour blindness and accessibility barriers. |

## 3.3 Types (Category III: Interaction-Structure)
| # | Type | Description (1–3 sentences) | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 11 | Dyadic Exchange | One-to-one conversations, personal relationships, mentoring, bilateral negotiation. High trust potential; low scalability; vulnerable to personality fit. | Key relationships drive decisions; disruption of single relationship cascades; mentor-mentee dependency; relationship-based trust overrides process. | Relationship-driven decision-making; loss of key person causes cascades; implicit knowledge dies with person. |
| 12 | Broadcast & Cascade | Messages sent down hierarchy, from leader to team, amplified through chain; serial relay with distortion risk. Fast distribution; high distortion risk; no feedback until many steps downstream. | Message interpreted differently by different relay levels; each relay rewrites slightly; distortion accumulates. | Cascade distortion (message unrecognisable at bottom); relay points become bottlenecks; feedback loops don't work up-stream. |
| 13 | Networked Coordination | Many-to-many mesh, collaborative platforms, consensus-building, collective sensemaking. Enables diverse input; slow to converge; coordination overhead; vulnerable to freeloading and dominance. | Coordination slower than hierarchy but more robust; over-reliance on particular connectors; under-engagement by periphery. | Hub dependency (network breaks if connector is removed); passive nodes don't contribute; dominance despite nominal equality. |
| 14 | Asymmetric Feedback | Information flows more easily in one direction than the other; frontline → leadership is slow/filtered, leadership → frontline is broadcast. Scales upward; information loss downward; creates perception gaps. | Leader surprised by what frontline knows; field staff unaware of strategic context; feedback channels don't carry corrective capacity. | Strategic blindness (leader makes decision on false model of field); field cynicism (feedback is heard but not acted on). |
| 15 | Excluded Participation | Some stakeholders are structurally excluded from key conversations. Creates parallel conversations and shadow decision-making; introduces coordination problems. | Key stakeholders surprised by decisions; outsider groups develop alternative narratives; repeated conflicts over "why wasn't I consulted." | Legitimacy crisis (excluded groups delegitimise decisions); coordination failure (excluded stakeholders block implementation). |

## 3.4 Types (Category IV: Protocol & Governance)
| # | Type | Description (1–3 sentences) | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 16 | Formal Escalation Protocol | Defined paths for urgent issues: incident classification, escalation criteria, authority routing, timelines. Ensures critical issues reach decision-makers; risks bureaucracy and delay; vulnerable to perverse incentives. | Protocol exists but is bypassed; classification disputes (is this a P1 or P2?); escalation takes longer than the situation. | Protocol becomes fiction (real escalation is informal); misclassification (incidents underreported to avoid accountability); false positive fatigue. |
| 17 | Approval & Clearance | Sign-offs, gatekeeping, review cycles, formal authority requirements. Ensures quality and responsibility; creates bottlenecks and delay; vulnerable to rubber-stamping. | Approvals routine; decisions made before approval (approval is theatre); clearance requirements seen as bureaucratic. | Approval becomes rubber-stamp (authority not exercised); bottleneck delays decisions; organisational shadow-approval (real decision elsewhere). |
| 18 | Audit & Accountability | Records, trails, logging, inspection, post-action review. Creates accountability; enables learning from failures; risks defensive documentation. | Records exist but tell different story than lived experience; audit-driven behaviour (documentation focus over substance). | Record-reality gap (official story vs what actually happened); defensive documentation (records optimised for legal, not truth). |
| 19 | Cultural Norm & Taboo | Informal rules about what can be said, who speaks in what context, what topics are safe/dangerous. Stabilises culture; suppresses dissent and error reporting; vulnerable to homogenisation. | Some topics are never discussed in group settings; errors are hidden; bad news doesn't surface; divergent voices are subtle. | Silence (no one speaks against consensus); error concealment (mistakes are hidden to protect relationships); groupthink. |
| 20 | Rotation & Power-Sharing | Mechanisms that distribute authority over time or across roles (term limits, co-leadership, consensus). Prevents entrenchment; reduces expertise accumulation; vulnerable to knowledge loss. | Frequent leadership changes; institutional knowledge held in few individuals; transitions cause information gaps. | Transition cascades (change of leader causes information loss); knowledge bottlenecks around exiting individuals. |

## 3.5 Types (Category V: Persuasion & Signalling)
| # | Type | Description (1–3 sentences) | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 21 | Authority & Source Credibility | Decisions shaped by who makes the claim, not just what the claim is. Enables delegation and scalability; vulnerable to authority capture and status quo bias. | Disagreement is resolved by "who said it" not "what they said"; same claim accepted from authority, rejected from peer. | Authority capture (powerful person's claim is accepted despite weak evidence); dissent suppressed (lower-status challengers ignore themselves). |
| 22 | Reputation & Trust History | Repeated credibility judgements based on past performance; path-dependent trust evolution. Enables learning from patterns; sticky despite contradicting evidence; vulnerable to first-impression effects. | Reputation-based decisions override current evidence; reputation recovery is difficult; past success suppresses questioning. | Reputation stickiness (early success insulates from questioning; early failure is permanent mark); halo/horn effects. |
| 23 | Narrative Frame & Story | The story chosen to explain events shapes what is seen as problem, opportunity, or normal. Emotionally resonant stories drive perception more than facts. | Organisational narrative is stable and widely repeated; alternative interpretations are silenced; narrative persists despite contradicting evidence. | Narrative capture (one frame dominates thinking); narrative brittleness (contradicting evidence causes sudden frame-shift rather than incremental update). |
| 24 | Signalling & Inference | Information inferred from what is said, how it's said, and what is not said. Enables interpretation beyond explicit content; vulnerable to misinterpretation and strategic ambiguity. | Silence is interpreted as agreement/disagreement; tone is interpreted as confidence; who speaks and who doesn't drives inferences. | Inference error (silence misinterpreted as assent when it was confusion); tonal misinterpretation creates false confidence. |
| 25 | Persuasion Tactic & Appeal | Explicit influence attempts: logical argument, emotional appeal, social proof, scarcity, reciprocity. Enables mobilisation; can override critical thinking; vulnerable to manipulation. | Decisions driven by appeal more than evidence; same tactic repeatedly used; audience develops resistance or dependence. | Persuasion habituation (repeated appeals become invisible); manipulation (influence tactics become visible and undermine trust). |

## 3.6 Types (Category VI: Hidden Flows & Feedback)
| # | Type | Description (1–3 sentences) | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 26 | Shadow Channel & Informal Network | Workarounds to formal channels that emerge when formal channels fail; backchannel communications; phone calls that bypass official channels. Adaptations to friction; enable real work to proceed; create coordination complexity and governance gaps. | Critical decisions made in hallway conversations, private messages; formal channels are slow or gatekeeping; staff know "real process" differs from official process. | Parallel coordination (multiple decision processes); governance blindness (formal system doesn't see real flows); cascade vulnerability (loss of informal connector). |
| 27 | Suppressed or Deprioritised Feedback | Information available but not acted on; feedback channels exist but feedback is ignored or punished. Organisational can't hear its own signals; vulnerability grows unseen. | Feedback surveys show consistent themes that are not addressed; suggestion systems exist but are unresponsive; repeated issues resurface. | Feedback fatigue (staff stop providing feedback when it's ignored); learning failure (organisation unable to absorb its own signals). |
| 28 | Filter Evasion & Workaround | Techniques to bypass filtering, gatekeeping, or suppression. Enables important information to surface; creates governance gaps and trust issues. | Staff develop ways to communicate outside official channels; information "leaks" appear; workarounds become shadow protocols. | Governance crisis (official authority is bypassed); escalation of trust (workarounds become primary communication). |
| 29 | Correction Loop Failure | Mechanisms for detecting and correcting errors are weak, slow, or ineffective. Misunderstandings persist and compound. | Errors persist because feedback loops are broken; same mistakes recur; corrections take too long to prevent damage. | Cascade of small errors (correction lag allows errors to compound); repeated failures despite past learning. |
| 30 | Strategic Silence & Information Withholding | Deliberate choice not to communicate; keeping information hidden for perceived advantage. Creates visibility failures; vulnerable to discovery. | Critical information withheld from decision-makers; some stakeholders remain deliberately uninformed; "need to know" restrictions. | Blind decisions (made without full information); discovery cascades (withheld information surfaces and delegitimises previous decisions). |

---

# 4. Cross-Cutting Dimensions of Any Communication Pattern

## 4.1 Dimensions Table (mandatory)
| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| 1. **Multiplicity** | How many separate communication instances of this type are running in parallel? Single, few (2–5), many (6–20), extensive (20+)? | Single (point communication) – Few – Many – Extensive | Count active instances; assess coordination burden. | High multiplicity = coordination overhead; risk of gaps between instances. |
| 2. **Signal-to-Noise** | What proportion of channel capacity is signal vs noise, distraction, false alarms? | High noise (signal < 10%) – Mixed (10–50%) – Clear (50–90%) – Low noise (> 90%) | Sample messages; assess relevance; count false positives. | High noise reduces effectiveness; low noise enables action. |
| 3. **Latency** | How long between signal production and reception/understanding? Account for medium, relay steps, processing time. | Immediate (< 1 min) – Short (1–60 min) – Medium (1–24 hr) – Long (> 1 day) | Measure clock time from event to awareness; account for time zones, relay delays. | High latency allows drift; misalignment compounds. |
| 4. **Correctness & Understanding** | What proportion of receivers understand the intended meaning accurately? | Poor (< 30%) – Fair (30–60%) – Good (60–90%) – Excellent (> 90%) | Test comprehension; compare interpretations across receivers; assess action-alignment. | Low understanding = misjudged action; feedback failure. |
| 5. **Governability** | How much can the communication pattern be observed, measured, and steered? | Ungovernable (hidden/opaque) – Weakly governed (partial visibility) – Governed (observable/steerable) – Highly governed (auditable/controlled). | Check availability of logs/records; ability to change protocol; transparency to oversight. | Low governability = drift risk; high governability = control but may create formalism. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | Amplification | Some signals are repeated, rebroadcasted, or resonated with across channels; others are suppressed or ignored. | Social amplification (attractive ideas spread faster), network effects (hubs amplify specific signals), incentive-driven amplification (rewarded messages are repeated). | Determines what becomes organisational "truth" regardless of actual importance; can concentrate power and suppress dissent. | Diversify information sources; reduce reliance on hubs; audit amplification bias. |
| 2 | Decay | Signals degrade, lose detail, or lose credibility as they propagate. Each relay introduces distortion; older messages are treated as less relevant. | Relay distortion (each step rewrites), forgetting (older signals fade from attention), version proliferation (multiple versions of "truth" circulate). | Information degrades as it propagates; decisions become detached from ground truth; latency creates stale models. | Reduce relay steps; strengthen feedback loops; audit for distortion. |
| 3 | Drift | Shared understanding diverges over time without explicit conflict; parties operate on different models without realising. | Decoupled evolution (different groups interpret same signal differently), temporal compression (context fades, leaving only signal), absent correction loops. | Coordinated action becomes impossible; decisions by one group invalidate decisions by another; cascade risk grows. | Strengthen periodic re-synchronisation; explicitly share mental models; audit alignment regularly. |
| 4 | Feedback Correction | Mechanisms through which errors are detected and corrected propagate back to source. Includes both mechanical (checksums) and social (error reporting). | Error detection (finding gap between intended and actual), correction transmission (sending fix back to source), correction acceptance (source acts on fix). | Determines whether organisations can learn and adapt; weak feedback = compounding errors; strong feedback = resilience. | Establish feedback loops at each interface; reduce latency of error detection; reward error reporting. |
| 5 | Shadowing | Important communication shifts from formal to informal channels; governance loses visibility. | Friction with formal channel (slow, gatekeeping, bureaucratic), social opportunity cost (formal compliance reduces bandwidth), incentive asymmetry (informal messaging rewarded, formal punished). | Governance becomes fiction; real decisions unmapped; coordination costs rise; cascade risk when shadow system fails. | Reduce friction with formal channels; legitimise appropriate informal comms; maintain visibility into shadows. |
| 6 | Encoding Loss | Details, context, or nuance is lost as information is encoded for transmission. | Abstraction (detail collapsed into summary), format rigidity (rich context squeezed into fixed fields), lossy compression (some information must be discarded). | Critical context may be hidden; decisions based on incomplete information; misunderstandings compound when context is missing. | Use multiple encodings for critical info; preserve context/metadata; enable encoding questions/clarifications. |
| 7 | Authority Asymmetry | Information flows more easily in one direction based on power or status. Upward channels filter for "good news," downward channels broadcast without feedback. | Power dynamics (subordinates filter for boss's preferences), risk asymmetry (bearing cost of bad news), gatekeeping (authority controls what is relayed). | Leadership operates on filtered reality; field understands strategy but doesn't correct strategy; drift and misalignment compound. | Establish protected channels for bad news; reduce risk for messengers; create feedback loops from field to strategy. |
| 8 | Legitimacy Crisis | Communications from certain sources or channels are no longer trusted; audience discounts the message regardless of content. | Betrayed expectations (repeated failures cause loss of trust), power asymmetry (audience believes source is acting in self-interest), manipulation discovery (hidden influence tactics exposed). | Messages from delegitimised source are ignored or inverted (opposite action taken); communication becomes dysfunctional. | Restore predictability and alignment; reduce hidden influence; rebuild trust through transparency. |
| 9 | Correction Lag | Time between error creation and error correction is too long; decisions made and acted on before correction arrives. | Detection latency (error isn't noticed for days/weeks), transmission latency (correction takes time to propagate), processing latency (correction isn't acted on immediately). | Errors compound; damage from error is larger than if correction arrived faster; learning is slow. | Reduce detection latency (real-time monitoring); reduce transmission latency (multiple channels); prioritise corrections. |
| 10 | Cascading Silence | Suppression of one communication channel triggers suppression of others; self-reinforcing silence. | Fear contagion (once one person is punished for speaking, others self-silence), network effects (critical mass of silence makes dissent impossible), social proof (silence appears to indicate agreement). | Silence becomes complete; dissent and error reporting vanish; vulnerability grows unseen. | Protect first speakers; diversify communication channels; explicit invitation for dissent; reward error-reporting. |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | **Channel Interface** | Boundary between two communication channels or media; information must transition across different affordances and potentially different audience/access controls. | Does the translation succeed? Is information lost or distorted at the boundary? Who controls the boundary? | Transition from email (asynchronous, creates record) to phone call (synchronous, ephemeral); from verbal conversation to formal document; from instant messaging to incident log. |
| B | **Translation Interface** | Boundary between different encodings or representations of the same information; same meaning must be expressed in different formats. | Does the translation preserve essential meaning? What details are lost in translation? Can the audience reverse the translation if they need to? | Dashboard metric encoding business rule into number; narrative framing of technical problem; visualisation of complex data; jargon-to-plain-language translation. |
| C | **Authority Interface** | Boundary where communication crosses levels of hierarchy, authority, or legitimacy; same message may have different perceived authority depending on source or audience. | Who believes the message? Whose version of "truth" is credible to whom? Is authority used to silence or amplify? | Information from frontline to leadership vs leadership to frontline; peer communication vs authority directive; formal vs informal source; in-group vs out-group speaker. |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links (recommended)
- **Inputs expected from**: Agents (who communicates); Evidence (what is known/unknown); Power (who has authority); Incentives (what rewards communication/silence); Culture & Norms (what is acceptable to say); Situations (what type of situation demands what communication); Governance (who is responsible for communication).
- **Outputs provided to**: Diagnosis (communication failures are often root causes); Decisions (decisions are only as good as the information available); Interventions (redesigning communication is a primary lever); Learning & Adaptation (feedback loops enable learning); Risk (communication gaps create vulnerability).

## 7.2 Crosswalk Table (optional but recommended)
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| **Situations** | What kind of context (crisis vs routine vs exploratory) demands what communication pattern. | Communication architecture as a dimension of situation type (routine has different comms than crisis). | Situation typing + comms redesign: routine situations can use lean formal channels; crisis situations need bandwidth + redundancy. |
| **Evidence** | What evidence is available about communication effectiveness (logs, metrics, stakeholder feedback). | How evidence moves through organisation; evidentiary standards that communication must meet. | Post-failure investigation: what evidence reached decision-makers? What was filtered? What channels failed? |
| **Power & Incentives** | Who has authority to change communication; what incentives drive communication behaviour. | How communication power is exercised (who can broadcast, who is heard, whose silence is consequential). | Communication redesign requires addressing incentives and power: if speaking truth is punished, formal channels will be shadowed. |
| **Culture & Norms** | What is culturally acceptable to communicate; what taboos limit expressability. | Communication as culture-shaping mechanism: narratives shape what cultures become. | Organisational culture change often requires shifting communication norms (moving from "shoot the messenger" to "reward the reporter"). |
| **Hiddens** | What visibility failures are operating; what hiding mechanisms apply. | Communication as Hiddens mechanism: channels that filter, distort, delay, or suppress create visibility failures. | Hiddens work must include communication diagnosis: where is information being filtered, and why? |
| **Diagnosis** | Root-cause analysis of failures; communication as a diagnostic lens. | Communication-specific diagnostics: is the failure a channel issue, encoding issue, protocol issue, or feedback issue? | Post-incident investigation should ask: what communication failed, at what interface, and what mechanism caused the failure? |
| **Decisions** | Decision quality depends on information quality; information quality depends on communication. | Communication architecture determines what information reaches decision-makers and in what form. | Decision improvement requires communication improvement: better decisions come from better information flow and understanding. |
| **Governance** | Governance structures that control communication (protocols, escalations, approvals, accountability). | Communication governance as accountability mechanism: who is responsible for what is communicated, to whom, and when. | Communication redesign is often governance redesign: changing escalation paths, approval structures, or accountability for communication accuracy. |
| **Learning & Adaptation** | Learning requires feedback; feedback is communication. | Communication patterns determine organisational learning capacity (strong feedback loops enable learning; weak feedback loops suppress it). | Organisational learning improvement often requires redesigning feedback loops and communication channels. |

## 7.3 Integration Questions by Framework (recommended)

**Rules and note:** This section lists all 36 canonical frameworks in the Analytical Series, organised by Group and Stage per OG v2.5 §3.1–§3.2. Framework order follows the canonical list in the Operating Guide. When applying this framework, use §7.3 as a checklist to ensure integration across the series.

| Framework | Group | Stage | Key integration question for Communications | Status |
|---|---|---|---|---|
| **1. Agents** | G1 | Upstream | Who are the agents in this communication system? What is their role, perspective, and stake in the communication? | — |
| **2. Systems** | G2 | Upstream | What larger systems contain and shape this communication? How do system boundaries, feedback loops, and dynamics constrain communication architecture? | — |
| **3. Realities** | G2 | Upstream | What ground truths or factual claims is this communication meant to convey? How does the communication either align with or distort those realities? | — |
| **4. Evidence** | G5 | Upstream | What evidence is available about communication patterns, effectiveness, and failures? What artefacts (logs, transcripts, metrics) document communication? | — |
| **5. Boundaries** | G1 | Middle | Where are the boundaries of the communication system? How do communications cross organisational, system, or role boundaries, and where do they fail? | — |
| **6. Time** | G2 | Middle | What is the temporal character of this communication (synchronous vs asynchronous, event vs sustained, latency and feedback lags)? How does time shape communication effectiveness? | — |
| **7. Scale** | G2 | Middle | At what scales is communication happening? How does communication differ at individual, team, organisational, and inter-organisational scales? | — |
| **8. Power** | G3 | Middle | How is power distributed in this communication system? Who has authority to speak, to be heard, to suppress? How does power shape what is communicated? | — |
| **9. Incentives** | G3 | Middle | What incentives shape communication behaviour? Are people rewarded for honesty or for telling a preferred story? For escalating or for suppressing bad news? | — |
| **10. Causation** | G2 | Middle | What causal claims are being made in this communication? How well are they grounded in evidence? What alternatives are not being discussed? | — |
| **11. Culture & Norms** | G4 | Middle | What cultural norms shape what can be communicated and how? What is taboo? What is the organisational norm for escalation, dissent, and error reporting? | — |
| **12. Values & Legitimacy** | G4 | Middle | What values are being communicated? What claims are treated as legitimate, and by whom? How does communication shape legitimacy judgements? | — |
| **13. Narratives** | G4 | Middle | What stories are told about this situation? Which narratives are dominant and which are suppressed? How do narratives shape interpretation of events? | — |
| **14. Perspectives** | G4 | Middle | How do different agents interpret the same communication differently? What mental models are in play? Where do perspectives diverge? | — |
| **15. Uncertainties** | G5 | Middle | What is unknown in this situation? How is uncertainty communicated? What risks are introduced by unknown unknowns? | — |
| **16. Situations & Context Classification** | G1 | Upstream | What kind of situation is this (routine, crisis, exploration, conflict, transformation)? Does the communication architecture fit the situation type? | — |
| **17. Diagnosis** | G6 | Middle | What are the symptoms of communication dysfunction? How can communication failures be diagnosed (root cause vs symptom)? | — |
| **18. Failures** | G5 | Middle | What communication failures have occurred? What patterns repeat? What mechanisms drive failure? | — |
| **19. Hiddens** | G5 | Middle | What is hidden in this communication system? What visibility failures, filtering mechanisms, and suppression techniques are operating? | — |
| **20. Risk** | G6 | Downstream | What risks are created by communication failures? What cascades could result from broken feedback loops or information gaps? | — |
| **21. Decisions** | G6 | Middle | What decisions depend on this communication? How does information quality affect decision quality? What decisions are made without adequate communication? | — |
| **22. Interventions** | G6 | Downstream | How can communication architecture be redesigned (channel changes, encoding improvements, protocol fixes, feedback loop strengthening)? | — |
| **23. Governance** | G6 | Downstream | What governance changes are needed to make communication more reliable and accountable? Who is responsible for communication quality? | — |
| **24. Responsibility** | G3 | Downstream | Who is accountable for communication failures? How should responsibility be distributed? What recourse exists for communication harm? | — |
| **25. Learning & Adaptation** | G6 | Downstream | How can communication be improved through learning loops? What feedback does the organisation collect about communication effectiveness, and how is it acted on? | — |
| **26. Resilience & Robustness** | G6 | Downstream | How resilient is this communication architecture to disruption? What redundancy exists? How well does it degrade under stress? | — |
| **27. Resources** | G2 | Upstream | What resources (time, budget, attention, tools) are allocated to communication infrastructure? Are resources adequate for the communication demands? | — |
| **28. Relationships** | G3 | Middle | How do communication patterns shape relationships between agents? How do relationships affect communication? | — |
| **29. Meaning & Interpretation** | G4 | Middle | How is meaning produced, shared, and contested in this communication system? What makes certain interpretations stick while others are discounted? | — |
| **30. Conflicts & Negotiation** | G3 | Middle | How is conflict expressed and managed through communication? What happens when agents dispute facts or frames? How are disputes resolved? | — |
| **31. Compliance & Accountability** | G6 | Downstream | What communication is required by governance, audit, or legal frameworks? How well is compliance monitored and enforced? | — |
| **32. Strategy & Direction** | G6 | Middle | How is strategic direction communicated? How well do frontline staff understand organisational strategy? How does strategy feedback loop from field to leadership? | — |
| **33. Change & Transformation** | G1 | Downstream | How is organisational change communicated? How do communication patterns shift during transformation? | — |
| **34. Coordination & Synchronisation** | G3 | Middle | How do agents coordinate action through communication? What synchronisation mechanisms exist? Where does coordination fail? | — |
| **35. Trust & Credibility** | G4 | Middle | How is trust in communication (and communicators) established and maintained? What erodes trust? How is credibility recovered after breach? | — |
| **36. Attention & Salience** | G5 | Middle | What determines what information is attended to? What makes certain signals salient while others are ignored? How does attention shape organisational awareness? | — |

---

# 8. Hiddens Source Analysis & Hiddens Cross-Check

## 8.1 Four Systematic Sources of Communication-Based Visibility Failure (mandatory)

### Source 1: Channel Blindspots
**What is hidden**: Information that doesn't fit any available channel; information about the channels themselves (structural gaps, slow channels, missing links); informal alternatives to formal channels.

**Why it is hidden**: Formal channels are designed for expected flows; unexpected or edge-case information has no place to go. Shadow channels emerge but are not visible to governance. Channel capacity limits force selection of what flows.

**Mechanisms**: Channel-specific (some info can only flow through certain channels; if that channel is missing or fails, the info is stranded). Gap-based (information about the channel system itself is rarely communicated, so blindspots persist). Visibility-capacity trade-off (transparency about channel limits is itself a channel-capacity cost).

**Detectability**: Moderate to High. Interview frontline staff about "how does the info really get out?"; compare formal channels to actual flows (via logs/observation); probe for workarounds and shadow channels.

**Remediation levers**: Audit channels for coverage gaps; create redundancy for critical signals; legitimise shadow channels that work; reduce friction with formal channels.

### Source 2: Encoding Collapse
**What is hidden**: Context, nuance, alternatives, and uncertainty that cannot fit into standard encodings; the lossy compression inherent in every representation.

**Why it is hidden**: Efficiency demands abstraction; exact replication of ground truth is not scalable or actionable. Each encoding optimises for some purposes while suppressing others. What is hidden by the encoding is usually not made visible.

**Mechanisms**: Format-driven (fixed-field encodings exclude what doesn't fit). Abstraction-driven (summaries hide variation and tail events). Narrative-driven (story structures foreground some causal links and background others). Visual-driven (colour, layout, prominence shape interpretation).

**Detectability**: High. Compare interpretation across users of the same encoding; test comprehension; ask "what is this encoding hiding?"; look for "but actually..." reframes by domain experts.

**Remediation levers**: Use multiple encodings for critical info; preserve raw data alongside summaries; annotate encodings with what is hidden; enable encoding questions/reversals.

### Source 3: Protocol Gaps
**What is hidden**: Situations that don't fit existing protocols; power asymmetries in protocol design and enforcement; incentives that reward non-compliance; gaps between protocol and practice.

**Why it is hidden**: Protocols are designed for routine; non-routine situations are orphaned. Protocol-reality gaps are often hidden to avoid scandal (official procedure differs from actual practice). Incentive structures that reward protocol-breaking are often implicit.

**Mechanisms**: Gap-based (protocol is written for standard cases; exceptions go unaddressed). Performance-based (protocol compliance creates perverse incentives; actual work happens outside protocol). Authority-based (protocol-breaking is tolerated if authority approves).

**Detectability**: High. Audit protocol compliance vs actual practice; interview staff about when they follow vs skip protocol; look for pattern of exceptions that become routine.

**Remediation levers**: Expand protocols to cover common exceptions; reduce perverse incentives in protocol; align actual work with formal process; escalate protocol-practice gaps as governance issues.

### Source 4: Feedback Failure
**What is hidden**: Errors, misunderstandings, and unintended consequences that are not detected or corrected in time; information about whether communication actually succeeded (did the recipient understand?).

**Why it is hidden**: Feedback loops are often weak or asymmetric. Upward feedback is filtered for "good news". Correction loops are slow relative to decision speed. Communication is often treated as one-way broadcast.

**Mechanisms**: Detection failure (errors are not noticed until late or not at all). Transmission failure (feedback reaches some but not original source). Acceptance failure (feedback arrives but is not acted on).

**Detectability**: Moderate. Look for repeated errors or misunderstandings; measure correction-cycle latency; ask "how do you know the message was understood?"; check whether feedback loops function bidirectionally.

**Remediation levers**: Establish feedback loops at each interface; reduce latency between error and correction; reward error-reporting; make confirmation of understanding mandatory for critical comms.

---

## 8.2 Tier 1 Hiddens Scan (mandatory; run at least twice per scenario)

**Tier 1 objective**: Rapid visibility audit across the four Hiddens sources. Not comprehensive diagnosis, but diagnostic triage: which sources are active? Where is visibility poorest?

**Tier 1 execution** (target: 30–60 minutes for Light Depth):

1. **Channel audit** (5–10 min): Map formal and informal channels in play. Are there channels that should exist but don't? Are shadows operating? Ask: "How does critical information actually get to decision-makers?"

2. **Encoding review** (5–10 min): Identify the primary encodings (dashboards, narratives, specs, models). For 2–3 critical pieces of information, ask: "What is this encoding hiding?" Sample interpretation across users.

3. **Protocol-practice gap check** (5–10 min): Identify the key protocol (escalation, approval, reporting). Ask: "Does practice match protocol?" Where is it bypassed? Why?

4. **Feedback loop test** (5–10 min): Pick one critical communication path. Trace: Can errors in this path be detected? How long does correction take? Does feedback propagate back to source?

5. **Triage summary** (5–10 min): Rank the four sources by visibility concern. Mark any that warrant Tier 2 or Targeted Scans escalation.

---

## 8.3 Tier 2 Hiddens Deepening (Investigative Run Mode; optional)

**Tier 2 objective**: Structured investigation of the top 2–3 Hiddens sources identified in Tier 1. Deeper evidence collection and mechanism diagnosis.

**Tier 2 execution** (target: 2–4 hours for Investigative depth):

For each Hiddens source marked for deepening:

- **Mechanism deep-dive**: Which specific mechanism (filtering, distortion, latency, suppression) is operating? Collect evidence (logs, transcripts, metrics).
- **Detectability assessment**: How easily is this Hidden detected by existing oversight? What signals would make it visible?
- **Consequence estimate**: What decisions or actions depend on this Hidden remaining hidden? What is the consequence if it surfaces?
- **Remediation options**: What would it take to close this Hidden? Cost-benefit of closure vs living with the risk?

Populate the Hiddens Register (§1.6.6) with detailed entries for each source under Tier 2 investigation.

---

## 8.4 Tier 3 Escalation (if residual unknowns could change decisions)

**Tier 3 objective**: Full-spectrum Hiddens investigation. Run when Tier 1 and Tier 2 expose high-consequence visibility failures and existing evidence is insufficient to close the analysis.

**Tier 3 is escalation**: Typically involves bringing in independent investigators, running formal audits, conducting interviews with protected anonymity, or triggering formal governance processes.

See OG v2.5 §7.3 and §D.6.10 for Tier 3 criteria and escalation protocol.

---

## 8.5 Targeted Hiddens Discovery Scans

**When to invoke**: When Tier 1 scan identifies symptoms of a specific hiding mechanism (see OG v2.5 §7.5 for the thirteen mechanism-specific scans).

**Framework-specific scans** (cross-framework, invoked from this framework when communication-based Hiddens are suspected):

- **Scan 1: Signal Filtering** (applies to Channel, Protocol, Feedback mechanisms)
- **Scan 2: Strategic Silence** (applies to Protocol, Hidden Flows, Authority mechanisms)
- **Scan 3: Distortion & Relay** (applies to Encoding, Interaction-Structure mechanisms)
- **Scan 4: Translation Loss** (applies to Encoding, Channel Interface mechanisms)
- **Scan 5: Amplification Bias** (applies to Persuasion, Dynamics mechanisms)
- **Scan 7: Temporal Drift** (applies to Feedback, Dynamics mechanisms)
- **Scan 9: Authority Capture** (applies to Persuasion, Authority Interface mechanisms)

See OG v2.5 §7.5.2 for full Targeted Scans catalogue and §7.5.3 for Triage Matrix (symptom → appropriate scan).

---

# 9. Application Protocol (7-step process)

## Step 1: Focal Decision & Channel Inventory
- **Input**: Scenario, focal decision or question, stakeholder/role map.
- **Process**: Define what communication is focal (what channels does the focal decision depend on?). Inventory formal and informal channels. Estimate flow volumes and users.
- **Output**: Channel inventory table; focal-decision-to-channel mapping.

## Step 2: Type Classification
- **Input**: Channel inventory from Step 1.
- **Process**: For 3–5 critical channels, assign types from Section 3 taxonomy. Profile each channel against the five dimensions (Section 4).
- **Output**: Type classification table; dimension profiles.

## Step 3: Dynamics & Pattern Analysis
- **Input**: Type classifications; temporal information (when channels are used, how they change over time).
- **Process**: Identify which dynamic patterns (Section 5) are active in this system. Which directions is it changing? Which patterns are problematic?
- **Output**: Dynamics pattern summary; risk/opportunity implications.

## Step 4: Interface Diagnosis
- **Input**: Channel inventory; types and dynamics from Steps 1–3.
- **Process**: Map interfaces (Section 6) where information transitions (e.g., from channel A to B, across role boundaries, between encoding systems). For each interface, assess failure risk.
- **Output**: Interface map; interface risk assessment.

## Step 5: Hiddens Source Analysis & Tier 1 Scan
- **Input**: All prior outputs; scenario context.
- **Process**: Run Tier 1 Hiddens scan across the four sources (§8.1–8.2). Identify which sources are active and highest-risk.
- **Output**: Hiddens Register with Tier 1 entries; triage for Tier 2 or Targeted Scans if needed.

## Step 6: Integration with Downstream Frameworks
- **Input**: All outputs from Steps 1–5.
- **Process**: Use Section 7 integration crosswalk (§7.2–7.3) to connect communication insights to other frameworks (Decisions, Governance, Interventions, etc.). What decisions are enabled/constrained by the communication architecture?
- **Output**: Integration notes; downstream handoff points; governance/decision implications.

## Step 7: Redesign & Governance Plan
- **Input**: All prior outputs; identified Hiddens and interface risks.
- **Process**: For each critical issue (failed interface, hidden feedback loop, etc.), propose redesign options. Map governance ownership (who is responsible for communication quality?). Set monitoring metrics (signal quality, latency, understanding, correction rate).
- **Output**: Redesign options summary; governance plan; monitoring dashboard proposal.

---

# 10. Principles & Execution Discipline

## 10.1 Core Principles

1. **Observability over Assumption**: Communication architecture is observable. Prefer data (logs, metrics, behaviour) over narratives about how communication "should" work.

2. **Interface-First Diagnosis**: Failures concentrate at interfaces (channel transitions, encoding shifts, authority boundaries). Start diagnosis there.

3. **Feedback-Loop Primacy**: Organisations that survive and learn have strong feedback loops. Weak feedback = drift and cascade vulnerability.

4. **Shadow Channel Reality**: Shadow channels are not dysfunctions to eliminate but adaptations to friction. Understand them before formalising.

5. **Multiplicity of Truth**: The same communication can be differently "true" for different users/contexts. Plurality of valid interpretations is a feature, not a bug (within limits). Singular-truth assumptions create brittle systems.

6. **Governability as Design**: Communication is only improvable if it is observable and steerable. Ungovernable communication remains forever opaque.

---

## 10.2 Execution Discipline (Prompt Discipline)

See §1.6.3 and OG v2.5 §D.3 for canonical Prompt Discipline Rules (PD-01 through PD-10). In brief:

- **PD-01 (Fact vs Interpretation)**: Tag claims as Fact (verifiable), Interpretation (reasonable but debatable), Assumption (accepted for proceeding), Unknown.
- **PD-02 (Provenance)**: Document where claims come from. Quote sources; distinguish direct evidence from hearsay.
- **PD-03 (Alternatives)**: Explicitly surface alternative explanations; don't prematurely collapse to single narrative.
- **PD-04 (Residual Unknowns)**: Record what remains unknown. Never claim full closure.
- **PD-05 (Disagreement)**: Where stakeholders disagree, document the disagreement rather than resolving it by authority.

---

# 11. Glossary of Terms (framework-specific)

## 11.1 Core terms (framework-specific; single source of truth)

| Term | Definition |
|---|---|
| **Channel** | A physical, social, technical, or organisational structure through which signals move; includes medium (sync/async, formal/informal) and affordances. |
| **Encoding** | How information is structured, formatted, or symbolised for transmission; includes language, metrics, narrative, abstraction level. |
| **Signal** | A meaning-bearing transmission; includes content, timing, source, medium, and metadata. |
| **Signal-to-Noise Ratio** | The proportion of channel capacity used by relevant (actionable, meaningful) content vs irrelevant or false-positive content. |
| **Feedback Loop** | A mechanism by which output of a system (or communication) is returned as input, enabling error detection and correction. |
| **Latency** | Time between signal production and reception/understanding/action. High latency allows drift; low latency enables coordination. |
| **Interface** | A boundary where information transitions between channels, encodings, or authority structures; high-risk zone for distortion and loss. |
| **Shadow Channel** | An informal communication mechanism that emerges when formal channels fail; operates outside governance and audit but carries real information. |
| **Protocol** | Formal rules governing how communication should operate; includes escalation paths, approvals, record-keeping, and accountability. |
| **Encoding Loss** | Information degradation or detail loss as information is transformed for transmission; lossy compression inherent in every encoding. |
| **Drift** | Divergence of shared understanding over time without explicit conflict; parties operate on different models without realising. |
| **Correction Lag** | Time delay between error detection and error correction; long lags allow errors to compound and damage to grow. |
| **Authority Asymmetry** | Information or feedback flowing more easily in one direction (downward, to authority) than the other (upward, challenging authority). |
| **Legitimacy Crisis** | Loss of trust in communications from certain sources or channels; audience discounts messages regardless of content. |
| **Cascading Silence** | Self-reinforcing suppression of communication; once suppression begins, fear and social proof prevent correction. |
| **Persuasion** | Influence attempts that shape beliefs and preferences; includes logical argument, emotional appeal, signalling, reputation. |
| **Strategically Withheld Information** | Deliberate choice not to communicate; information suppressed for perceived advantage. |
| **Hiddens Source** | One of four systematic mechanisms that create visibility failures in communication: channel blindspots, encoding collapse, protocol gaps, feedback failure. |

---

## 11.2 Core execution terms (pointer; do not restate)
- See **Analytical Series Operating Guide**, v2.5:
  - Core execution terms (mandatory): **§D.10.1**
  - Artefact terms (mandatory): **§D.10.2**
  - Full Operating Guide glossary: **§11** (§11.1–§11.9)
  - Targeted Hiddens Discovery Scans glossary: **§7.5.6** (also §11.7)

---

# 12. Document Control (recommended; mandatory for "Stable" status)

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| v2.0 | 2026-04-06 | Rewrite for Master Template v2.3 alignment; updated all OG references from v1.5 to v2.5; added Introduction section (four subsections); expanded §1.6 with Tier 2 Hiddens crosswalk, Targeted Scans routing, and Information Requests schema; updated Document Information with Tiered Hiddens Scan Model and Targeted Hiddens Discovery Scans fields; expanded §1.4 with Stage assignment, Framework Index pointer, and Iteration loop statement; added Group and Stage columns to §7.3 framework integration list (all 36 canonical frameworks); expanded §8 with Tier 2 structured deepening guidance and Targeted Scans escalation trigger; updated §11.2 pointer to OG v2.5; preserved all thirty communication types and core operational content; added 7-step application protocol (§9); enhanced principles and execution discipline (§10). (Revised: Anthropic Claude Opus 4.6) |
| v1.2 | 2026-03-28 | Standardised rewrite to series format; expanded §5.1 Dynamic Patterns Table to include 10 communication-specific patterns (added 5 new: Encoding Loss, Authority Asymmetry, Legitimacy Crisis, Correction Lag, Cascading Silence); reformatted to Analytical Series master template; preserved six meta-categories and thirty types; expanded descriptions to remove truncation; added standardised dimension and dynamics tables; expanded Section 8 with mandatory tiered Hiddens cross-check; added principles, document control, and appendices. (Revised: Anthropic Claude Opus 4.6) |
| v1.1 | 2026-03-15 | Minor updates; added clarification on framework compatibility with Operating Guide v1.5. |
| v1.0 | 2026-02-01 | Original framework; six meta-categories, thirty types; five dimensions; dynamic patterns; interface model; hiddens integration. |

## 12.2 Integration Notes (optional)
Use this framework whenever:
- a decision or action depends on information flowing reliably between roles or systems,
- failures occur repeatedly despite good faith and adequate resources (often communication is the root cause),
- organisations describe themselves as suffering from "silos" or "misalignment" (communication architecture is the mechanism),
- crises expose gaps between what was reported and what was known in the field (communication protocol failure),
- stakeholders claim competing pictures of what "actually happened" (often a communication/framing/encoding issue, not a factual dispute),
- feedback loops are broken and learning is stalled (communication is the enabler of learning).

Treat Section 8 (Hiddens cross-check) as mandatory in high-stakes contexts and whenever classification relies on dashboards, gatekeepers, or contested narratives.

---

*End of Document*
