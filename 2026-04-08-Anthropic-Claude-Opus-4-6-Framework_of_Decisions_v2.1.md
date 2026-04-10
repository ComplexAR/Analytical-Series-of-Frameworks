# Framework of Decisions
*A Comprehensive Taxonomy of Decision Forms, Architectures, and Failure Modes*

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
- Group (Primary): G6 — Choice, action & control over time (Action & Control)
- Group (Secondary): G5 — Epistemics & error-control (Epistemics)
- Stage assignment: Downstream (see OG v2.5 §3.1)
- Default Depth Guidance: Light Depth Framework Execution by default; Full Depth Framework Execution when routed by OG §4.3 or when consequence is high, evidence is weak/contested, or coupling/cascade potential exists
- Owner / Maintainer: Series Maintainer
- Intended Use: Make decisions and non-decisions explicit; classify decision types and architectures; map decision rights, vetoes, and escalation; align decision criteria with evidence, values, and risk; detect decision failure modes (paralysis, closure, performativity, capture, drift); redesign decision architectures; integrate with Hiddens checks
- Primary Audience: Executives and boards; governance and risk leaders; programme and transformation leaders; incident and crisis leaders; regulators and oversight bodies; product and engineering leadership; policy leaders
- Dependencies / Key Inputs: Situation framing; objectives and values; constraints and boundaries; evidence and uncertainty characterisation; risk appetite and failure analyses; stakeholder and power map; current governance and decision artefacts
- Primary Outputs: Decision register (including non-decisions); typed decision catalogue; decision-right and escalation map; criteria and evidence-threshold pack; interface and governance mechanism map; hiddens source register + tiered Hiddens scan; redesigned decision architecture; monitoring and review plan
- Change Log (brief): v2.0 rewrite aligns with Master Template v2.3 (2026-04-02); updated all OG references from v1.5 to v2.5; expanded §1.6 with LLM integration specification including Tier 2 Hiddens crosswalk, Targeted Scans routing, and full Information Requests schema; added Introduction section (four subsections: What is Decisions, Why matters for Hiddens, What produces, How to use); restructured §1.2 with Assumptions Register and Preconditions Checklist; enhanced all core sections per template invariants; expanded §7.3 with all 36 canonical frameworks; added complete §8.3 Tier 2 Hiddens mapping; added copy-ready run prompts in §1.6.7; updated §11 and §12 with full version history and integration notes.

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What decision is being made (or avoided), by whom, in what forum, with what rights and escalation, at what time horizon, on what basis, and with what decision architecture?** |
| Addresses | Hidden decision points; option space truncation; criteria slippage; accountability evasion; temporal blindness; decision paralysis; premature closure; performative decisions; captured decisions; drifting decisions. |
| Gap Filled | Many analyses focus on realities, risks, evidence, or interventions. This framework focuses on the choice-architecture layer: how decisions are structured, justified, executed, and how they fail over time. |
| Complements | Governance; Responsibility; Evidence; Uncertainties; Risk; Failures; Power; Incentives; Legitimacy; Interventions; Systems; Time; Scale; Communications; Narratives; Hiddens. |
| Key Characteristics | Six meta-categories; thirty decision types; seven dimensions; ten decision dynamics; three interface types (A/B/C); hiddens source analysis + tiered Hiddens mapping. |
| Main Contributions | A repeatable decision scan; a disciplined taxonomy for classification; architecture redesign prompts; explicit linkage to evidence thresholds, risk tolerances, legitimacy, and accountability; drift and capture detection. |

---

# Introduction

## What is Decisions?

A decision is a structured choice or non-choice that commits a system to a course of action or default, operating under constraints of time, uncertainty, power, legitimacy, and accountability. Decisions are not purely technical or rational acts; they are also architectural choices that shape what options are visible, what evidence counts as sufficient, and who has authority to act or veto. The same information and situation can lead to radically different decisions depending on who decides, in what forum, under what criteria, and at what time.

When decision architecture is poorly designed or remains invisible—when decision rights are ambiguous, when criteria drift unnoticed, when non-decisions masquerade as technical inevitabilities—organisations suffer chronic failures: strategic choices are repeatedly made without acknowledgement; accountability evaporates; evidence is suppressed or cherry-picked; and parallel shadow decisions run alongside formal ones. This framework exists to make decision processes explicit, to classify the types and architectures of decisions occurring in complex contexts, and to enable deliberate redesign of how choices are made.

## Why does Decisions matter for Hiddens work?

Decision-making is one of the primary sites where Hiddens materialize. When decision processes are opaque or unexamined, several families of hiding mechanisms proliferate:

**Structural capture** (Hidden-13, Systemic Incentive Distortion) occurs when decision architecture incentivises deception—when escalating bad news carries penalties, when certain options are precluded from the table by forum composition, or when real veto power sits outside formal structures. The decision appears free; in fact, it is constrained by invisible architecture.

**Option space truncation** (Hidden-21, Informational Option Foreclosure) happens when only a narrow band of options is generated or allowed to surface. Unconventional, disruptive, or politically costly options disappear from deliberation without ever being named as excluded. The decision feels like a choice between real alternatives; in fact, it is a choice within a pre-truncated space.

**Criteria slippage and performativity** (Hidden-9, Informational Distorted Standards) occur when stated decision criteria (safety first, evidence-based, equitable) diverge from actual criteria applied. Official standards exist for documentation and signalling; informal ones govern real choices. This creates both false confidence (the process looks disciplined) and accountability failure (the real criteria are deniable).

**Non-decisions as decisions** (Hidden-8, Ontological Category Collapse) arise when choices not to decide, to defer indefinitely, or to allow defaults to persist are treated as non-events rather than choice commitments. Drift is presented as externally driven rather than as a series of small, concealed, delegated decisions to do nothing.

Without this framework, these Hiddens remain latent. With it, decision architecture becomes a repeatable diagnostic object, enabling early detection of capture, criteria slippage, and drift before late consequences compound.

## What does this framework produce?

The framework operationalises decision analysis through six core elements:

1. **A taxonomy of 30 decision types** organised into six meta-categories (Level & Horizon; Architecture & Locus; Authority, Rights & Escalation; Basis & Criteria; Temporal & Process-Structure; Quality & Failure-Mode), enabling rapid classification and comparison.

2. **Seven cross-cutting dimensions** (Complexity & Reversibility; Evidence & Uncertainty; Contestation & Plurality; Temporal Pressure & Windows; Governance & Accountability Clarity; Formalisation & Visibility; Scope & Scale) that profile any decision instance and explain why different stakeholders classify the same situation differently.

3. **Ten dynamic patterns** (Centralisation Drift, Delegation Drift, Formalisation & Ritualisation, Trigger Inflation/Decay, Option Space Erosion, Crisis Reversion, Criteria Creep, Escalation Fatigue, Accountability Diffusion, Silent Transition to Exception) that describe how decision architectures degrade over time.

4. **Three interface types** (Detection, Remediation, Interaction) that make visible where decision failures surface, how they are corrected, and how decision-makers coordinate and adapt in real time.

5. **Hiddens source analysis and tiered Hiddens scans** that surface seven sources of decision blindness (hidden points, option truncation, architecture myopia, criteria slippage, accountability evasion, temporal blindness, systemic distortion) and map them to six Hiddens meta-categories.

6. **A six-step application protocol** that moves from decision framing through typing, dimensional profiling, dynamic scan, interface mapping, Hiddens checking, and integration handoff.

The framework populates standard registers (Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests) that integrate with the broader Analytical Series investigation workflow.

## How to use this framework

Invoke this framework early in any complex scenario—particularly when decisions are contested, when governance has failed, when programme drift is suspected, or when accountability is disputed. The framework works in both Rapid Run Mode (light-touch decision scan and interface spotting) and Investigative Run Mode (full dimensional profiling, dynamic scan, complete Hiddens mapping, and governance redesign).

Default execution is Light Depth Framework Execution: name the decision, assign types, identify the key decision-makers and forums, run a Tier 1 Hiddens scan across all six categories, and spot obvious interface failures. Escalate to Full Depth when consequence is high, evidence is contested, or you suspect capture or drifting criteria.

For LLM execution, see §1.6 for the complete specification, standard registers, and copy-ready run prompts. The framework is designed to be directly executable by an LLM given a scenario and the Operating Guide, producing a disciplined decision analysis with explicit Hiddens, F/I/A/U tagging, and bounded closure notes documenting residual unknowns and escalation triggers.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Decisions are structured commitments that translate interpretation into action or default. They are not only substantive choices about what to do; they are also architectural choices about how future choices will be made. Decisions operate under constraints of time, uncertainty, power, legitimacy, and accountability. Because choice architectures shape option spaces, evidence standards, and escalation behaviours, the quality of decisions depends as much on decision design (rights, forums, thresholds, cadence, and review) as on the content of any single decision.

Decisions are typically:
- **Substantive**: about actions taken or not taken.
- **Architectural**: about decision-making itself (meta-decisions about who decides, how, when, and on what basis).
- **Temporal**: anchored to choice points, windows, deadlines, and irreversibility thresholds.
- **Relational and contested**: involving multiple agents with divergent values, evidential standards, legitimacy claims, and power asymmetries.
- **Failure-prone**: susceptible to paralysis, premature closure, capture, drift, and performative governance.

This framework provides a standardised approach to:
- Elicit and map the decisions (and non-decisions) occurring in a scenario,
- Classify decisions using a stable taxonomy (6 meta-categories × 5 types = 30),
- Profile decisions along seven cross-cutting dimensions,
- Diagnose dynamic patterns of drift and degradation,
- Map the detection, remediation, and interaction interfaces where decisions surface, fail, and are corrected,
- Scan for characteristic Hiddens using a tiered approach (Tier 1 six-category scan; Tier 2 mechanism mapping; Tier 3 escalation),
- Hand off a redesigned decision architecture to governance and implementation.

## 1.2 Assumptions & Preconditions

### Assumptions Register
| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Decision-making can be made explicit and structured. Decisions are not purely intuitive or emergent; they can be typed, mapped, and improved through deliberate design. | Method / structural | Framework loses operational value; analysis becomes impressionistic; improvements are ad hoc. | Apply the taxonomy to 5+ decision instances; measure consistency of classification and repeatability. | Treat classification as provisional hypothesis; use qualitative narratives to supplement; escalate uncertainty. |
| Decision architecture affects outcomes as much as decision content. How decisions are made (rights, forums, criteria, timing) determines quality as much as what is decided. | Structural / domain | Focus remains on content; architecture remains invisible and undesigned; same failures repeat. | Correlate decision architecture changes to outcome improvements; audit where content is sound but architecture fails. | Combine with Governance and Responsibility frameworks; conduct before/after architecture case studies. |
| Choice architectures shape what is even considered. Decision rights, escalation paths, and evidence thresholds constrain which options are visible and what standards of proof apply. | Structural | Option truncation remains invisible; constraints appear as facts rather than design choices; innovation stagnates. | Test whether option sets change when decision-makers or forums change; audit evidence thresholds for bias. | Use red-team analysis and counterfactual option generation; stress-test framing assumptions. |
| Decisions operate under constraints of power, legitimacy, and accountability that cannot be ignored. Technical rationality alone does not explain outcomes; political dynamics and legitimacy claims shape what is decided. | Domain / normative | Analysis remains technical; power distortions are invisible; governance redesigns fail without legitimacy engagement. | Map formal vs informal authority; interview stakeholders on veto and influence; trace actual decision pathways. | Escalate to Power and Legitimacy frameworks; include adversarial review and stakeholder negotiation. |
| Non-decisions are decisions. Choosing not to decide, deferring indefinitely, or allowing drift by default are themselves choice commitments with consequences and accountability. | Conceptual / domain | Drift is attributed to externality; accountability for non-decisions evaporates; chronic failures masquerade as inevitable. | Track deferral patterns; attribute non-decisions to specific actors and forums; measure consequences of inaction. | Include non-decisions explicitly in decision register; assign accountability for deferrals. |
| Decision failure is common and patternable. Paralysis, premature closure, capture, and drift follow recurring patterns that can be detected and corrected. | Domain / method | Failures are treated as unique or incomprehensible; learning is slow; same patterns repeat. | Audit failure logs; identify recurrent failure modes; correlate to architecture features; test interventions. | Build decision failure catalogue; use pattern recognition to accelerate diagnosis and remediation. |
| Decisions interact with evidence, risk, values, and accountability frameworks. Isolated decision analysis without attending to evidence quality, risk appetite, value trade-offs, and responsibility assignment produces poor choices. | Structural / domain | Decision redesigns fail because they ignore upstream inputs; legitimacy gaps persist; unintended consequences multiply. | Integrate decision analysis with Evidence, Risk, and Responsibility frameworks; test decisions against all inputs. | Use joint analysis protocols; require explicit traceability from evidence/risk/values to decision criteria. |

### Preconditions Checklist
| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Focal decision(s) and non-decisions are identified and named. | Y | Decision naming statement; list of actors and forums; temporal framing; scope boundary. | Analyst; decision owner | Validate names against stakeholders; check for hidden decisions. | Use boundary-clarification interview; work with "plausible minimum scope"; iterate. |
| Stakeholder narratives on the decision have been elicited (3+ independent perspectives). | Y | Interview transcript; narrative summary; documented divergences and power asymmetries. | Analyst; stakeholder interviewers | Cross-check narratives; assess consistency and conflicts. | Conduct structured interviews; use proxy narratives; note gaps in closure. |
| Governance structure and formal decision rights are documented or accessible. | Y | Org chart; governance charter; RACI matrix; escalation map; decision authority matrix. | Analyst; governance owner | Verify against documents; test with key decision-makers; compare formal vs lived practice. | Use proxy governance structure; assume escalation path; flag assumptions. |
| Evidence base and uncertainty characterisation are accessible (at least provisionally). | Y | Evidence inventory; source list; gaps and defeaters; uncertainty bounds. | Analyst; evidence custodian | Audit evidence quality; confirm access; check for missing categories. | Produce Evidence Request List; note gaps in registers; escalate as Unknown. |
| Decision history or comparative cases are available for pattern recognition. | Y | Prior decision logs; comparative case studies; failure post-mortems; decision audit trails. | Analyst; records custodian | Review prior decisions on same or similar topics; identify patterns and drift. | Use hypothetical reconstructions; escalate pattern-recognition limits. |
| Time/resource budget for analysis is defined (Rapid vs Investigative Run Mode). | Y | Run mode selection; depth plan; time/resource envelope; iteration budget. | Analyst; project manager | Align with OG §D.6 decision gate; validate budget against scope. | Default to Rapid Run Mode (Light Depth); flag escalation triggers. |
| Re-scan and re-architecture cadence is pre-agreed (when classification and design will be revisited). | Y | Re-scan schedule; decision-drift triggers; responsibility assignment; governance rhythm. | Analyst; governance owner | Track actual re-scans; compare to planned cadence; assess whether triggers were respected. | Set minimum default cadence (quarterly or per-phase); use temporal milestones. |

## 1.3 Definitions, Scope, and Non-Goals

**Decision (operational)**: A structured choice or non-choice that commits a system to a course of action or default, under constraints and on some basis, made by a designated agent or forum.

**In scope**:
- Six meta-categories and thirty core decision types
- Seven cross-cutting dimensions for profiling any decision instance
- Ten decision dynamics (patterns of architectural drift and failure over time)
- Three decision interfaces (Detection, Remediation, Interaction)
- Hiddens sources plus tiered Hiddens cross-check (Tier 1, 2, 3)
- Application protocol and deliverables
- All 36 canonical frameworks and their integration points
- Targeted Hiddens Discovery Scans relevant to decision architecture

**Out of scope**:
- Domain-specific policy content or engineering design details (treat as decision inputs; classify decisions here)
- Legal advice on authority and due process (treat as constraints; use domain counsel)
- Persuasion tactics as an end in itself (use Narratives and Communications for implementation support)
- Intervention implementation details (use Interventions and Resources frameworks)

## 1.4 Position in the Series (Upstream / Middle / Downstream)

**Upstream inputs** (decision prerequisites): Realities & diagnosis; Situations & context classification; Evidence & uncertainties; Risk & appetite; Power & incentives; Legitimacy & standing; Stakeholder & agent mapping.

**Middle (this framework's role)**: Make decision architectures explicit; classify decision types; align rights, criteria, evidence, risk, and legitimacy; detect failure modes and drift; design decision architectures that enable visibility and prevent distortion.

**Downstream consumers** (decision outputs): Interventions & resources; Governance & operations; Responsibility & accountability; Monitoring & adaptation; Learning & iteration.

- **Group assignment (Primary)**: G6 — Choice, action & control over time (Action & Control)
- **Group assignment (Secondary)**: G5 — Epistemics & error-control (Epistemics)
- **Stage assignment**: Downstream (see OG v2.5 §3.1)
- **Run mode selection**: Rapid Run Mode vs Investigative Run Mode (OG v2.5 §D.10.1)
- **Operating Guide routing**: apply decision logic at Start-of-Run and Pre-Closure (OG v2.5 §4.3) to produce minimum group coverage + Full Depth / Light Depth plan
- **Non-conflation invariant**: do not conflate Run Mode with Framework Execution Depth (OG v2.5 §D.10.1)
- **Iteration loop**: Route → Execute → Test → Re-scan → Decide/Close (OG v2.5 §5.0)
- **Framework Index**: this framework is one of 36 in the series (see OG v2.5 §3.2 for full Framework-to-Group mapping)

---

## 1.5 Crosswalk Summary
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|---|
| Framing & scope | Situations; Boundaries; Dimensions; Scale; Time | What context matters; what is in/out scope; relevant magnitudes and horizons; temporal lags and windows. | What decisions are being made (or avoided); what is the scope of authority and accountability; what decision windows and timelines apply; what decision precedent exists? |
| Mechanism & understanding | Systems; Relations; Processes; Causation; Evidence; Diagnosis | How things work; causal chains and feedback; what evidence supports claims; where understanding is weak. | How do decision architectures cause outcomes; what evidence supports the choice of decision criteria and forums; where do formal and informal decision pathways diverge; what evidence gaps hide decision failures? |
| Agency & motivation | Agents; Personas; Incentives; Power; Competencies; Responsibility | Who acts; what drives decisions; who has power; who is responsible; what capacities exist. | Who decides and who is excluded; what decision rights and veto powers exist; how do incentive structures shape decision outcomes; whose interests and values are embedded in decision architecture? |
| Meaning & legitimacy | Culture & Norms; Perspectives; Narratives; Communications; Legitimacy; Values | What is taken as real; whose voice is heard; what narratives dominate; what is valued. | On what legitimacy grounds is the decision accepted; whose values are embedded in decision criteria; how are conflicting values traded off; whose perspectives are excluded from deliberation? |
| Epistemics & visibility | Beliefs; Evidence; Uncertainties; Failures; Hiddens; Knowledge; Metrics | What is known/unknown/hidden; what evidence is trusted; where knowledge is fragmented. | What decision criteria are implicit vs explicit; what options are hidden from deliberation; what decision failures go undetected; where are non-decisions masked as technical inevitabilities? |
| Action & governance | Interventions; Governance; Risk; Learning & Adaptation | How are choices made; what levers exist for change; who decides; how is risk managed; how do we learn. | How are decisions made explicit and accountable; what mechanisms enable redesign of decision architecture; how is decision quality assured; what triggers escalation or reversal; how do organisations learn from decision failures? |

---

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Decisions_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Decisions when… | Use neighbour instead when… |
|---|---|---|
| Governance | Mapping decision rights, authorities, and escalation; detecting informal power diverging from formal structure; redesigning decision processes and forums. | Designing governance systems, organisational structure, and compliance frameworks; examining formal authority distribution in isolation. |
| Responsibility | Assigning accountability for decisions and non-decisions; determining who is liable for decision outcomes; mapping decision and non-decision consequences. | Establishing role clarity, role-based accountability systems, or responsibility frameworks independent of specific decision instances. |
| Power | Analysing how decision architecture reflects and redistributes power; examining veto and influence asymmetries; detecting capture and gatekeeping. | Analysing power distribution, bargaining, and dependency relationships independent of formal decision structures. |
| Evidence | Validating evidence thresholds and sufficiency criteria applied to decisions; testing whether evidence quality matches decision stakes. | Conducting evidence syntheses, audit trails, and quality assessment independent of decision processes. |
| Risk | Aligning decision risk tolerance with evidence and consequences; detecting where decision architecture underestimates or misframes risk. | Quantifying risk exposure, probability, impact, and mitigation strategies independent of decision processes. |

### 1.6.3 Routing triggers
- Decision is explicitly contested or formally disputed between stakeholders
- Governance has failed; decision authority is ambiguous or eroded
- Programme drift is suspected; decisions appear to be made without acknowledgement
- Accountability is in dispute; consequences not attributed to decision or decision-maker
- Capture or criteria slippage is hypothesized; stated criteria differ from applied criteria
- Non-decisions are suspected; deferral or default appears to substitute for choice
- Decision escalation is blocked, delayed, or unclear; pathways not functioning
- Decision reversibility is unexamined; lock-in risk not assessed
- Historical decision failures show recurring patterns; learning mechanisms absent
- Hiddens are suspected in option generation, forum composition, or evidence handling

# 2. Meta-Categories of Decisions

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---|---|---|---|---|
| I | Level & Horizon Decisions | At what level (strategic/tactical/operational) and time horizon (short/medium/long-term) should this choice be made? | Decision level alignment; time-scale appropriateness; escalation to strategy or delegation to operations. | Strategic plans; quarterly reviews; operational runbooks; escalation rules; horizon-matched budgets |
| II | Architecture & Locus Decisions | Who should decide, in what forum, and under what process governance? | Decision-maker role; forum composition and authority; process design and stage-gating. | RACI matrices; governance charters; decision rights matrices; escalation rules; forum agendas |
| III | Authority, Rights & Escalation Decisions | What decision rights and veto powers should exist, and how should escalation operate? | Formal authority distribution; veto and override structures; escalation paths; appeal mechanisms. | Authority matrices; escalation protocols; veto registries; override logs; governance charters |
| IV | Basis & Criteria Decisions | On what basis and according to what criteria should choices be made? | Evidential standards; trade-off rules; values hierarchy; legitimacy grounds. | Decision criteria packs; evidence thresholds; values statements; trade-off matrices; legitimacy standards |
| V | Temporal & Process-Structure Decisions | When, at what cadence, and through what sequence of steps should decisions be made? | Timing and windows; phasing and stage-gates; cadence and review cycles; reversibility and sunsets. | Decision calendars; phase plans; review schedules; trigger specifications; sunset clauses; re-opening protocols |
| VI | Quality & Failure-Mode Decisions | How will decision quality be assured, and what safeguards prevent known failure modes? | Quality assurance mechanisms; hidden-decision detection; capture prevention; learning loops. | Pre-mortems; red-team protocols; challenge mechanisms; Hiddens scans; post-decision reviews; competency standards |

## 2.2 Meta-Category Descriptions (recommended)

**Category I—Level & Horizon Decisions** encompass choices about what level (strategic vs tactical vs operational) and time horizon (days, quarters, years) a decision should operate on. Poor alignment between level and horizon creates misalignment: strategic decisions made tactically become tactical; operational decisions deferred to strategic forums create bottlenecks. This category captures decisions about whether something is even a decision for this forum or should be delegated, escalated, or deferred.

**Category II—Architecture & Locus Decisions** establish who should decide and how. These are meta-decisions that shape all subsequent decisions. Poor architectural choices—unclear roles, weak forums, no escalation path—make good decisions harder and bad decisions harder to reverse. Architecture includes forum composition (who participates), process (sequence, deliberation depth, and challenge), and governance (documentation, oversight, appeal).

**Category III—Authority, Rights & Escalation Decisions** spell out formal rights and veto structures. These decisions establish whether authority is clear, exclusive, and properly escalated. Ambiguous authority, hidden veto points, or informal override systems create accountability gaps and shadow decisions. This category includes decisions about who can make autonomous choices, who can veto, and what escalation path exists.

**Category IV—Basis & Criteria Decisions** specify the evidential standards, trade-off rules, and values that guide choices. Criteria drift and slippage are a major source of hidden decision failures. This category includes decisions about what counts as sufficient evidence, how competing values are traded off, and what legitimacy standard applies.

**Category V—Temporal & Process-Structure Decisions** establish when, at what cadence, and through what steps decisions will be made. Timing mismatches (premature closure, indefinite deferral, missed windows) are major sources of failure. This category includes decisions about decision windows, stage-gating, review cadence, reversibility, and sunset mechanisms.

**Category VI—Quality & Failure-Mode Decisions** establish the mechanisms for detecting, preventing, and learning from decision failures. These meta-decisions embody the organisation's commitment to transparency, challenge, and learning. Weak or absent mechanisms allow systematic failures to repeat undetected.

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
This framework maintains the canonical 6×5 structure (six meta-categories, five core types per category = 30 core types). No structural deviations. Framework-specific naming conventions reflect decision-theoretic distinctions; mapping to other frameworks is documented in §7.3.

## 3.1 Types (Category I: Level & Horizon Decisions)
| Type | Name | Definition | Key questions | Typical triggers |
|---|---|---|---|---|
| I-1 | Strategic vs Operational Alignment | Decision about whether a choice belongs at the strategic, tactical, or operational level. | At what level should this choice be made and decided? Is it strategic (enterprise-shaping), tactical (intermediate alignment), or operational (local execution)? | Misalignment between decision and forum level; escalation disputes; operational teams blocked by strategic overhead or vice versa. |
| I-2 | Horizon Matching | Decision about whether the time scale of a choice matches the decision window available. | What is the natural time horizon of this decision (days, months, years)? Does the available window match? | Premature closure under time pressure; indefinite deferral in slow-moving forums; missed opportunity windows. |
| I-3 | Decomposition & Sequencing | Decision about whether a large choice should be decomposed into stages, and in what sequence. | Should this be a single choice or a sequence of gated decisions? What dependencies exist? | Large, irreversible decisions forced into single gates; complex choices treated as simple; missing intermediate review points. |
| I-4 | Delegation vs Escalation | Decision about whether a choice should be delegated downward, escalated upward, or retained at current level. | Is this decision rightly sized for this level and forum, or should it move up or down? | Authority ambiguity; bottlenecks from over-escalation; fragmentation from excessive delegation; accountability loss. |
| I-5 | Horizon Reassessment & Cycling | Decision about whether to re-examine the appropriate level and horizon after experience or changed circumstances. | Should we revisit whether this decision level and time horizon still fit? What triggers reassessment? | Horizon degradation (long-term decisions treated as tactical); stale level assignment; missed inflection points. |

## 3.2 Types (Category II: Architecture & Locus Decisions)
| Type | Name | Definition | Key questions | Typical triggers |
|---|---|---|---|---|
| II-1 | Forum Composition & Diversity | Decision about who participates in the decision forum (representation, expertise, diversity, power balance). | Who participates? Are critical perspectives present? Are power asymmetries balanced or hidden? | Homogeneous forums missing perspectives; excluded stakeholders; hidden veto-holders; missing expertise. |
| II-2 | Process Governance (Stage-Gates & Deliberation Depth) | Decision about the process steps, deliberation depth, and stage-gating that will govern how a decision moves from problem to action. | What process steps are required? How much deliberation is appropriate? What stage-gates exist? | Ritual without substance; inadequate deliberation time; premature closure; missing challenge mechanisms. |
| II-3 | Transparency & Documentation | Decision about whether and how the decision will be documented, made visible, and auditable. | Will this decision be named, logged, and reviewable? Who can access the rationale? | Hidden decisions masquerading as routine; undocumented choices; audit trails missing; learning loops broken. |
| II-4 | Cross-Boundary Coordination Structure | Decision about how decisions affecting multiple units, teams, or organisations will be coordinated. | How do we coordinate across unit/team/org boundaries? What is the governance for inter-unit decisions? | Fragmentation across silos; conflicting local decisions; missing system-level view; coordination failures at scale. |
| II-5 | Oversight & Assurance Mechanism | Decision about what assurance, oversight, or external review will govern the decision process itself. | Who oversees the decision-makers? What assurance mechanisms exist? Are they independent? | Weak or absent oversight; capture by insiders; no independent voice; assurance failures hidden. |

## 3.3 Types (Category III: Authority, Rights & Escalation)
| Type | Name | Definition | Key questions | Typical triggers |
|---|---|---|---|---|
| III-1 | Exclusive vs Shared Authority | Decision about whether one agent has exclusive authority or whether authority is shared, requiring consensus or negotiation. | Does one person/forum decide alone, or is authority shared? What happens if shared parties disagree? | Authority ambiguity; decision paralysis from shared authority without veto rules; undisclosed conflicts of interest. |
| III-2 | Veto & Override Rights | Decision about who has veto power and under what conditions override authority can be invoked. | Who can veto or override? On what basis? What escalation follows a veto? | Hidden veto-holders; overridden vetoes without justification; veto abuse; accountability gaps for override. |
| III-3 | Escalation Pathways & Triggers | Decision about what triggers escalation and how escalation authority is structured. | What conditions trigger escalation? To whom? Under what time pressure? | Escalation rules unclear; thresholds gamed or ignored; escalation path blocked; decisions linger in limbo. |
| III-4 | Appeal & Reversal Rights | Decision about whether and how a decision can be appealed, challenged, or reversed after initial closure. | Can a decision be re-opened? Who can challenge it? On what basis? What is the appeal process? | Decisions treated as irreversible when reversible; no remedy for bad decisions; path-dependence unexamined; learning blocked. |
| III-5 | Accountability for Non-Decision | Decision about whether and how deferral, non-decision, and inaction are treated as accountable choices. | Is choosing not to decide treated as a decision? Who is accountable for drift and deferral? | Non-decisions treated as non-events; drift attributed to externality; accountability evasion through inaction. |

## 3.4 Types (Category IV: Basis & Criteria Decisions)
| Type | Name | Definition | Key questions | Typical triggers |
|---|---|---|---|---|
| IV-1 | Evidence Standards & Thresholds | Decision about what counts as sufficient evidence, what evidence quality is required, and what burden of proof applies. | What is the required evidence standard (anecdotal, expert opinion, data, RCT)? Who decides sufficiency? | Evidence cherry-picking; cherry-picked standards applied selectively; weak evidence accepted for favoured options; strong evidence demanded for disfavoured ones. |
| IV-2 | Value Trade-offs & Hierarchy | Decision about how competing values (safety, efficiency, equity, innovation) will be traded off and in what hierarchy. | What values are at stake? How are they ranked? Are trade-offs explicit or implicit? | Hidden value conflicts; value hierarchies assigned without consent; espoused vs operative values diverge; trade-offs framed as technical. |
| IV-3 | Legitimacy Basis (Consent, Expertise, Authority, Process) | Decision about on what grounds the decision will be deemed legitimate (expert authority, democratic process, stakeholder consent, legal mandate). | On what basis will the decision be accepted as legitimate? Whose consent is required? | Legitimacy unexamined; process legitimacy does not match outcome legitimacy; excluded parties; contested grounds. |
| IV-4 | Risk Tolerance & Appetite Specification | Decision about what level of risk and uncertainty is acceptable and at what point a decision should be deferred pending better information. | What is the acceptable risk and uncertainty level? When is more information worth the delay? | Risk appetite unstated; thresholds unclear; risk tolerance exceeded without governance response; uncertainty underestimated. |
| IV-5 | Reversibility & Optionality Preservation | Decision about whether and at what cost a decision can be reversed, and what options will be kept open for future choices. | Is this decision reversible or effectively irreversible? What optionality will we preserve? | Irreversible decisions treated as tentative; reversible ones locked in; option value eroded; path-dependence unexamined. |

## 3.5 Types (Category V: Temporal & Process-Structure Decisions)
| Type | Name | Definition | Key questions | Typical triggers |
|---|---|---|---|---|
| V-1 | Decision Windows & Deadlines | Decision about what constitutes the valid decision window and whether deadlines are firm or flexible. | When must this decision be made? What is the consequence of delay? Of early closure? | Missed opportunity windows; indefinite deferral; artificial deadlines driving poor choices; real windows ignored. |
| V-2 | Cadence & Re-examination Schedule | Decision about how often a decision will be revisited, re-scanned, and potentially revised. | At what cadence will we revisit this decision? What triggers re-examination? | Stale decisions never reviewed; drifted criteria undetected; changed circumstances not reflected in choices; learning loops broken. |
| V-3 | Stage-Gating & Phase Structure | Decision about what sequence of steps, gates, and phases a decision process will follow. | What stages must be passed? What gates must be cleared? What are the exit criteria? | Premature closure skipping phases; excessive stage-gating creating delay; missing gates allowing unvetted moves; phase goals unclear. |
| V-4 | Sunset Clauses & Reversibility Mechanics | Decision about whether and when a decision will automatically expire or be forced to re-examine or reverse. | Does this decision have an expiration date? What re-examination will occur? | Emergency measures persisting indefinitely; exception creep; "temporary" becoming permanent; learning loops missing. |
| V-5 | Re-opening & Appeal Windows | Decision about whether and under what conditions a decision can be re-opened after closure. | Can this decision be re-opened if new evidence arrives? What conditions trigger re-opening? | Decisions treated as final when circumstances change; new evidence ignored; locked-in errors; learning-loop failure. |

## 3.6 Types (Category VI: Quality & Failure-Mode Decisions)
| Type | Name | Definition | Key questions | Typical triggers |
|---|---|---|---|---|
| VI-1 | Pre-Mortem & Failure Hypothesization | Decision about whether and how to conduct pre-mortems or failure-scenario testing before a major decision is locked in. | What could go wrong? What failure scenarios will we test? Who will challenge the decision? | Missing pre-mortems; unexplored failure scenarios; over-confidence; surprises late in execution. |
| VI-2 | Challenge & Devil's Advocate Mechanisms | Decision about whether and how to institutionalise challenge, dissent, and alternative perspectives in decision forums. | How will dissent be surfaced and taken seriously? Who will play devil's advocate? | Homogeneous thinking; dissent suppressed; groupthink; missing alternative hypotheses; weak challenge function. |
| VI-3 | Hidden Decision Detection & Registry | Decision about whether and how to surface hidden decision points, non-decisions, and informal veto structures. | Are we making decisions without naming them? Are there shadow decisions? Hidden vetoes? | Hidden decisions masquerading as routine; non-decisions as non-events; informal power unexamined; shadow governance undetected. |
| VI-4 | Post-Decision Review & Learning Loop | Decision about whether and when post-decision reviews will occur and how learning will be captured and fed back. | Will we review this decision after execution? Who learns from outcomes? How are lessons shared? | Post-mortems skipped; failures not linked to decision quality; learning loops broken; same errors repeat. |
| VI-5 | Competency & Decision-Maker Capability Standards | Decision about what competencies decision-makers must possess and how competency is assured or developed. | Are decision-makers capable of the decisions assigned? What training and support do they need? | Decisions assigned to under-qualified decision-makers; competency gaps undiagnosed; learning and development absent. |

## 3.7 Extending the Taxonomy (mandatory)
The 6×5 core taxonomy (30 types) is canonical. Domain-specific refinements or sub-types are permitted under the following conditions:
- Document any addition as an extension, not a replacement, of the canonical 30.
- Provide a mapping from extension types back to the canonical taxonomy (which core type does this refine?).
- Record mapping precedent in domain-specific guidance appendices.
- Update framework version and change log when significant extensions are adopted.
- Escalate to framework maintainer if extension appears broadly valuable across domains.

---

# 4. Cross-Cutting Dimensions of Any Decision

## 4.1 Decision Dimensions Table (mandatory)
| Dimension | Definition & range | Significance | How to assess | Why it matters |
|---|---|---|---|---|
| Complexity & Reversibility | How many moving parts, dependencies, and irreversibilities exist; ranges from simple/reversible to complex/irreversible. | Simple decisions allow fast iteration; irreversible ones require deep deliberation. Complexity determines forum size and decision depth. | Map dependencies, count moving parts, assess reversibility over what time horizon (minutes, years, permanent). | Misaligned deliberation depth to complexity creates both analysis paralysis and premature closure. |
| Evidence & Uncertainty | Quality and sufficiency of available evidence; ranges from strong/settled to weak/contested to entirely unknown. | Weak evidence requires acknowledged uncertainty, wider option preservation, and contingency planning. Strong evidence allows faster closure. | Audit evidence sources, quality, and independence; map where evidence is absent, contested, or single-sourced. | Ignoring evidence gaps or uncertainty drives false confidence and brittle decisions; preserving uncertainty enables adaptation. |
| Contestation & Plurality | Degree to which stakeholders disagree on facts, values, or legitimacy; ranges from low contestation (aligned) to high contestation (polarised). | High contestation requires transparent criteria, explicit value trade-offs, and participatory process. Low contestation allows streamlined governance. | Elicit independent stakeholder narratives; identify facts, values, and legitimacy disagreements; assess power asymmetries. | Ignoring pluralism creates legitimacy gaps, hidden resistance, and sabotage; making it explicit enables negotiation. |
| Temporal Pressure & Windows | How time-bounded is the decision; ranges from wide windows (slow burn) to tight deadlines (crisis). | Tight deadlines constrain options and deliberation depth; wide windows allow exploration. Time pressure overrides normal governance if not managed. | Identify decision deadlines and opportunity windows; assess what changes if delayed or accelerated. | Temporal misalignment (treating crisis as routine, routine as urgent) drives wrong decision modes and governance breakdowns. |
| Governance & Accountability Clarity | Clarity of decision rights, roles, and accountability; ranges from clear/explicit to ambiguous/implicit. | Clear governance enables fast decisions and reliable accountability; ambiguous governance creates paralysis and evasion. | Check formal RACI/decision authority matrix; interview actual practice; assess divergence. | Ambiguous governance is a primary source of accountability evasion, shadow decisions, and unowned failures. |
| Formalisation & Visibility | How explicit, recorded, and auditable is the decision; ranges from informal/tacit to formal/documented/public. | Formal, visible decisions enable learning, oversight, and correction; informal ones enable stealth and drift. | Ask whether the decision is named, logged, reviewable; who can access the rationale and process. | Hidden decisions enable capture and drift undetected; visibility enables challenge and learning. |
| Scope & Scale | Breadth of impact across units, populations, and systems; ranges from single team/local to enterprise/ecosystem-wide. | Larger scope requires greater coordination, enterprise governance, and system-thinking. Small scope can use local governance. | Map affected boundaries and dependencies; identify cross-boundary coordination requirements and failure propagation. | Scale misalignment (local decisions with system effects, enterprise decisions with no local adaptation) drives failures. |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---|---|---|---|---|---|
| 1 | Centralisation Drift | Decision rights gradually concentrate upward; more choices require senior approval. | Risk aversion, blame avoidance, or reputational stakes drive escalation; juniors lose authority and learning opportunities; leaders become distant from operational reality. | Slows response, increases overload, and reduces local adaptation; creates brittle decisions and increases shadow workarounds. | Clarify delegation boundaries; strengthen assurance and learning; create fast-path escalation for true exceptions; measure decision throughput and delay. |
| 2 | Delegation Drift | Decisions drift downward or outward, often without explicit mandate; strategic choices leak into operational space. | Capacity constraints at the top, complex environments, and informal practice push decisions down; variation increases across sites and teams. | Creates inconsistency, uneven risk, and hidden fragmentation; accountability becomes unclear. | Define decision catalogue and boundaries; standardise key thresholds; implement audits and review forums; retain escalation triggers. |
| 3 | Formalisation & Ritualisation | Decision processes become ritualised: meetings, documents, and stage-gates persist while substantive reasoning and challenge weaken. | Compliance incentives and performative governance substitute for real deliberation; artefacts are produced for signalling rather than truth. | Generates false confidence, hides Hiddens, and reduces learning; increases cost and time without improving outcomes. | Tie artefacts to evidence and outcomes; require defeaters and alternatives; audit decision quality; remove low-value rituals and simplify governance. |
| 4 | Trigger Inflation or Decay | Triggers proliferate and overwhelm decision forums, or triggers decay and fail to escalate real problems. | Adding triggers is easier than designing robust indicators; over time, people game, ignore, or disable triggers; signal-to-noise collapses. | Creates either constant escalations (paralysis) or missed escalation (catastrophic surprise). | Calibrate and test triggers; maintain trigger registers; review false positives and false negatives; link triggers to clear actions and owners. |
| 5 | Option Space Erosion | Feasible options shrink over time without explicit recognition, until choices become effectively irreversible. | Path dependence, sunk costs, legacy lock-in, and institutional commitments constrain future choices; small defaults accumulate into lock-in. | Late-stage 'no choice' narratives emerge; risks and costs rise; accountability for earlier decisions is obscured. | Track option value; use staged commitments and sunsets; maintain decommissioning pathways; explicitly review defaults and drifts. |
| 6 | Crisis Reversion | Under stress, decision architectures revert to ad hoc centralised authority and emergency rules. | Time pressure and perceived threat override participatory processes; emergency structures bypass normal oversight. | Emergency decisions can entrench new path dependencies and Hiddens; exception creep may persist after the crisis. | Predefine emergency governance and transition criteria; ensure logs and after-action reviews; set sunsets and oversight; rebuild normal governance deliberately. |
| 7 | Criteria Creep | Decision criteria shift over time, drifting away from stated standards without explicit review or consent. | Incremental changes under pressure, absence of criteria audits, or informal reinterpretation of ambiguous standards. | Decisions that should be rejected pass review; legitimacy collapses when old and new criteria are compared; hidden capture becomes visible. | Audit criteria periodically; require explicit rationale for any criterion change; compare current vs historical decisions on same facts; escalate significant deviations. |
| 8 | Escalation Fatigue | Forums receiving escalations become overwhelmed, leading to decision delay, quality degradation, or delegation of complex decisions back down without resolution. | Escalation rates exceed forum capacity; inadequate filtering of truly escalation-worthy decisions; poor triage at intake. | Decisions linger in limbo; escalation becomes ineffective (forums ignore); local actors lose confidence and create workarounds. | Right-size escalation thresholds and forum capacity; implement triage and pre-briefing; assign clear ownership and deadlines; monitor escalation backlog. |
| 9 | Accountability Diffusion | As decisions involve more actors and layers, responsibility for outcomes becomes unclear or deniable; 'everyone and no one' owns the decision. | Shared governance or polycentric structures without clear ownership, or sequential decision chains where later actors disown earlier choices. | Failures go unaddressed; no one sacrifices to improve; learning is slow; similar mistakes repeat; distrust of governance grows. | Assign single owner or clear shared-ownership model with explicit covenant; hold forums accountable for decision quality; create post-decision responsibility registers. |
| 10 | Silent Transition from Normal to Exception | Organisations enter emergency mode or crisis governance gradually, losing normal oversight without formal transition; normal governance is never restored. | Incremental severity increase and repeated crisis extensions; lack of explicit transition gate; pressure to "stay ready"; normalisation of emergency authority. | Exceptional powers persist indefinitely; accountability lapses harden; transparency declines; legitimacy of governance erodes; future crises escalate faster. | Define clear emergency-mode entry/exit criteria; require explicit transition decision; mandate sunset clauses; restore normal governance forcefully even if imperfect; track exception persistence. |

---

# 6. Interface Types

## 6.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | Detection Interface | How decision problems, failures, and architectural flaws are identified, surfaced, and escalated. | How are decision points recognised as such? Who detects when decisions are missing, captured, or drifting? What signals trigger review of decision architectures? | Pre-mortems and scenario testing; decision audits and retrospectives; escalation of threshold breaches; feedback from affected parties; anomalies in execution patterns; Hiddens scans. |
| B | Remediation Interface | How decision processes are redesigned, corrected, and governed to prevent recurrence of failures or capture. | How are decision rights, forums, criteria, and escalation mechanisms altered to address identified problems? What commitments and controls embed the redesign? | Governance redesign; decision-right remapping; evidence-threshold clarification; capability building for decision-makers; control mechanisms and override authority redesign; learning loop establishment. |
| C | Interaction Interface | How decision participants, stakeholders, and oversight bodies coordinate, challenge, and adapt decisions in real time and over time. | Who participates in decisions and challenge mechanisms; how do participants interact with decision forums and each other? How is dissent handled, and how do decisions adapt when new information arrives? | Challenge and defeater processes; dissent capture mechanisms; post-decision review forums; escalation dialogue and debate; reversibility and re-opening protocols; learning dialogues. |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links (recommended)

**Inputs expected** from upstream frameworks: situation framing and boundaries; objectives and constraints; evidence and uncertainty bounds; risk appetite and failure modes; stakeholder and power map; governance artefacts; legitimacy grounds.

**Outputs provided** to downstream consumers: explicit decision catalogue; decision-right and escalation design; criteria and evidence thresholds; drift and failure diagnostics; redesign options; monitoring and review plan; Hiddens shortlist and escalation triggers.

## 7.2 Crosswalk Table (optional but recommended)
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|---|
| Responsibility | Accountability assignments, obligations, and role clarity | A diagnostic for decision rights, non-decisions, and responsibility gaps; governance redesign prompts | Incidents where accountability is disputed and decisions were implicit or drifting |
| Evidence / Uncertainties | Evidence quality, defeaters, and uncertainty bounds | Evidential thresholds and challenge mechanisms as part of decision architecture; option-preserving designs | High-stakes choices where evidence is incomplete or contested |
| Risk / Failures | Risk appetite articulation and failure mode analysis | Risk-tolerance decisions, escalation triggers, and crisis governance designs that prevent exception creep | Designing governance for low-probability, high-impact hazards |
| Power / Incentives / Legitimacy | Political dynamics and legitimacy recognition patterns | Capture detection, veto and escalation design, and legitimacy-aware decision processes | Contested environments where 'who decides' is disputed |
| Interventions / Resources / Systems | Feasibility, capacity constraints, and executable action pathways | Decision-to-intervention translation checks; owners and accountabilities; portfolio and sequencing decisions | Transformation programmes where decisions are made but execution does not follow |
| Competencies | What decision-makers can reliably do at the required proficiency | Whether decision-quality problems trace to competency gaps rather than information gaps | Decision competency assessment; ensure decision authority matches decision competency |
| Governance | Governance structure, roles, and operating procedures | Decision architecture as a governance design object; governance failure diagnosis; redesign options | Governance failure and redesign |
| Situations & Context | Situation framing and type (routine, project, crisis, conflict, exploration, transformation) | Decision-mode calibration to situation type (crisis decisions use different architecture than exploratory ones) | Ensuring decision governance matches the kind of situation being managed |
| Hiddens | Visibility failures and hidden mechanisms | Seven sources of decision blindness mapped to six Hiddens meta-categories; detection and remediation interfaces | Surfacing hidden decision points, captured criteria, and informal veto structures |
| Learning & Adaptation | Feedback loops and organisational learning cycles | Post-decision reviews, learning loops, and adaptation mechanisms embedded in decision architecture | Building organisational capacity to learn from decision outcomes |

## 7.3 Integration Questions (all 36 frameworks)

Use these questions to anchor decision analysis to all 36 frameworks in the Analytical Series:

**Situations & Context (§3.2):** What situation framings and boundaries are implicit in how decisions are being made? Which framings would change what appears as a valid option?

**Realities & Diagnosis (§3.3):** What causal hypotheses underlie the decision? Which claims about mechanism, timing, and reversibility are most contested?

**Boundaries & Scope (§3.4):** How are decision boundaries set? Are relevant actors, impacts, and dependencies included or excluded? Would widening or narrowing scope change the decision?

**Time & Temporality (§3.5):** What decision windows, deadlines, and path-dependencies exist? Which decisions are effectively irreversible, and over what time horizon?

**Systems & Coupling (§3.6):** How are decisions coupled to other systems, suppliers, and organisations? Where do local decision optima create systemic risk?

**Relations & Interfaces (§3.7):** Which decision handoffs and boundaries are most failure-prone? Where do interface assumptions not match reality?

**Processes & Causation (§3.8):** What causal mechanisms justify the decision criteria and thresholds? How would discovery of new causation require decision revision?

**Resources & Constraints (§3.9):** What resource constraints limit decision implementation or change? Where do unfunded mandates create drift?

**Agents & Personas (§3.10):** Who actually decides, and does that match the formal designation? Which personas or roles have hidden agenda-setting power?

**Incentives & Behavior (§3.11):** How do incentives shape what is proposed, hidden, or escalated? Where do decision-makers face conflicts of interest?

**Power & Control (§3.12):** Where does informal power override formal decision rights? How is agenda-setting used to truncate options?

**Responsibility & Accountability (§3.13):** Do decision rights align with accountability for outcomes and non-decisions? Where are accountability vacuums?

**Legitimacy & Standing (§3.14):** On what basis are decisions accepted as rightful? Which parties contest the legitimacy of the decision-maker or process?

**Culture & Norms (§3.15):** What cultural norms shape what can be proposed or challenged in decision forums? Where is speaking up unsafe?

**Perspectives & Frames (§3.16):** Which interpretive lenses dominate (technical, financial, safety, legal)? Which perspectives are absent from the decision table?

**Narratives & Communications (§3.17):** How are decisions framed and communicated? Do narratives match the actual criteria and trade-offs?

**Values & Ethics (§3.18):** What values are at stake, and how are trade-offs being adjudicated? Where are value disputes hidden under technical language?

**Evidence & Claims (§3.19):** What claims support the decision, and what is their independence and quality? Where are defeaters absent or suppressed?

**Uncertainties & Assumptions (§3.20):** What deep uncertainties remain, and how is the decision robust to them? Which assumptions are least defensible?

**Failures & Weak Signals (§3.21):** What have past decision failures revealed? Are early warnings being attended to?

**Hiddens & Visibility (§3.22):** What decision points, constraints, or affected parties are not being recognised? What shadow decisions are occurring?

**Risk & Appetite (§3.23):** How does the decision affect risk exposure? Is the appetite explicitly stated and enforced?

**Governance & Oversight (§3.24):** How is the decision overseen, and what is the escalation and appeal route? Is oversight independent and capable?

**Learning & Adaptation (§3.25):** Are post-decision reviews built in? Can the decision be revisited if evidence changes?

**Beliefs & Mental Models (§3.26):** What collective beliefs underlie the decision? How were they formed, and what distortion mechanisms are active?

**Metrics & Measurement (§3.27):** What metrics inform decisions, and how sensitive are decisions to metric choice? Where do metric limitations constrain decision quality?

**Competencies (§3.28):** What competencies do decision-makers need for the decisions assigned to them, and where do decision-quality problems trace to competency gaps?

**Knowledge & Tacit Knowing (§3.29):** What knowledge is required for pending decisions? Where is decision-relevant knowledge tacit, concentrated, or inaccessible?

**Communication & Channels (§3.30):** How is information about the decision communicated? Are channels effective, or are they filtered, distorted, or blocked?

**Organisational Design (§3.31):** How does organisational structure support or hinder decision-making? What structural changes would improve decision quality?

**Change & Transition (§3.32):** How will the decision be implemented and sustained? What change management is required to embed the decision?

**Resilience & Recovery (§3.33):** If the decision goes wrong, how quickly can the organisation recognise failure and recover? Is there a rollback mechanism?

**Scalability (§3.34):** If the decision is successful locally, can it be scaled? What decision authority and resources are needed for scale-up?

**Sustainability (§3.35):** Can the decision be sustained indefinitely, or does it depend on temporary conditions? What sunset or refresh cycle is needed?

**Recursion & Coupling (§3.36, Decisions framework itself—recursive):** How does this decision interact with other decisions? Does the decision architecture enable or block other good decisions?

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis Table
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---|---|---|---|
| 1 | Hidden Decision Points | Critical choices are embedded in processes as "routine" actions (e.g. default renewals, unchecked overrides) and never recognised as decisions. | Make decision points explicit: create a decision register (including deferrals) and log defaults, thresholds, owners, and review dates. |
| 2 | Option Space Truncation | Only a narrow subset of options is generated or allowed on the table, often excluding low-status, long-term, or politically inconvenient options. | Force option generation across all six meta-categories; document excluded options and the criteria that excluded them; run counterfactuals. |
| 3 | Architecture Myopia | Focus on content of decisions while the architectural choices (who decides, how, when) remain unexamined. | Analyse the decision architecture (rights, forums, escalation, vetoes, evidence thresholds) not just the content; redesign failure-prone mechanisms. |
| 4 | Criteria Slippage | Official decision criteria differ from the real ones (e.g. "safety first" vs throughput-first in practice). | Explicitly declare criteria and trade-offs; audit decisions against stated criteria; require rationale and defeaters when criteria change. |
| 5 | Accountability Evasion | Decision structures designed (consciously or not) to make it hard to attribute decisions to any specific agent or forum. | Align decision rights with responsibility and resources; make non-decisions accountable; clarify escalation and veto ownership. |
| 6 | Temporal Blindness | Timing, windows, and path-dependence are ignored when designing decision processes. | Map windows, triggers, and irreversibility; track option value over time; define emergency transition criteria and sunset rules. |
| 7 | Systemic Distortion (Pervasive Hiddens Omission) | Assume the true constraints, incentives, and bargaining are visible. Hidden distortions, secrecy, echoes, and shadow decisions are not tested, so the decision architecture is over-trusted. | Run Tier 1 Hiddens scan; shortlist Tier 2 hidden types and map detection and remediation to decision interfaces (A–C); define escalation triggers for full Tier 3 Hiddens run. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)
| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|---|
| I Perceptual | Decision-makers attend to salient and recent information; weak signals and long causal chains are neglected. | Surprise failures; 'no one saw it' claims; overconfidence in familiar options; ignored early warnings; blindspot to counter-evidence. | Decision pre-mortems; weak-signal reviews; require explicit alternative hypotheses and defeaters; include frontline signal capture; test for confirmation bias. |
| II Systemic | Decision architectures create structural incentives for deception, capture, or omission. | Repeated failures in same category; patterns consistent with incentive distortion; gatekeeping and filtering of information; shadow governance. | Map incentives and power asymmetries; stress-test decision architecture for capture; audit escalation and veto use; compare stated vs lived rules; trace informal coalitions. |
| III Informational | Evidence is selective, distorted, or suppressed; echoes masquerade as independent corroboration. | Claims backed only by insiders; external or independent evidence missing; expert disagreement unacknowledged; decision rationale cites cherry-picked sources. | Require independent evidence; demand defeaters and alternative hypotheses; stress-test evidence quality; audit information flows and source diversity; test for selective reporting. |
| IV Temporal | Timing of information, decisions, and consequences are misaligned; lags and windows hide causation and drift. | Decisions made before key information arrives; escalation lags; invisible lock-in and drifted outcomes; surprise at 'inevitable' late consequences; windows missed. | Map decision windows relative to information availability; identify lags in feedback; test for path dependence and lock-in; review whether early windows were used; track temporal drift. |
| V Relational | Hidden coalitions, vetoes, informal power, and shadow agreements drive outcomes despite formal structures. | Formal processes run but real decisions happen elsewhere; announced decisions are overridden informally; stakeholders claim surprise or powerlessness; shadow governance. | Interview behind formal structure; trace real decision pathways; identify informal coalitions and veto; map power asymmetries; observe where formal and informal diverge; test for influence beyond authority. |
| VI Ontological | What counts as a "decision" vs "routine" vs "inevitability" is contested; category collapse obscures choice. | Drift presented as externally driven; non-decisions framed as having no choice; controversial decisions reframed as technical or obvious; options excluded as "impossible." | Stress-test framing of inevitability; enumerate implicit choices; reframe "routine" as decisions; require explicit rationale for any claim that something is "not a decision." Challenge necessity claims. |

## 8.3 Hiddens Crosswalk (Tier 2 – default mapping layer)

The following table maps common Hiddens to decision-architecture failure modes, with detection interfaces (A), remediation levers (B), and interaction protocols (C):

| Hidden type (ID + name) | Relevance (H/M/L) to decision architecture | Mechanism | Detectability | Agency | Consequence | Type A: Detection interface | Type B: Remediation interface | Type C: Interaction interface |
|---|---|---|---|---|---|---|---|---|
| II.1 (Systemic – Structural Incentive Distortion) | H | Decision architecture incentivises deception or omission (e.g. escalation penalises bearers of bad news). | M | Design of forums, metrics, and role incentives. | High: decisions made on distorted inputs; corrections are slow and costly. | Audit escalation use and outcomes; interview decision-makers on incentive pressures; compare stated vs observed behaviour. | Redesign incentives and measurement; create safety for escalation and dissent; alter forum composition and decision rights. | Change incentives to reward truth-telling; ensure decision-makers have skin in the game for quality. |
| III.2 (Informational – Evidence Cherry-Picking) | H | Only evidence supporting preferred option is presented; defeaters and alternative hypotheses are omitted. | M | Audit evidence submitted to decision-makers; compare to full evidence base; test for selection bias. | High: decisions made on incomplete picture; unforeseen harms and failures are common. | Require independent evidence; demand defeaters as condition for proceeding; include devil's advocate; conduct red-team analysis. | Implement evidence standards and review processes; create role for evidence challenger; shift burden of proof. | Engage evidence providers in dialogue about defeaters; create transparency in how evidence is filtered. |
| V.2 (Relational – Informal Veto & Shadow Coalitions) | M | Real decision authority sits with informal veto holders outside formal forum; formal process is theatre. | M | Interview behind structure; trace actual decision pathways; observe where formal and lived systems diverge. | Medium-High: decisions appear legitimate but represent power dominance; over time, lose legitimacy and become hard to enforce. | Map informal power structures and veto points; interview key actors; observe who actually stops decisions. | Bring informal veto into formal architecture; create legitimate voice for veto holders; redesign to reduce need for shadow negotiation. | Create explicit dialogue with informal players; negotiate upfront on constraints rather than discovering them later. |
| VI.3 (Ontological – Non-Decision as External Inevitability) | H | Deferral or inaction is framed as "having no choice" rather than as a decision to defer or allow default. | M | Challenge framing of inevitability; enumerate implicit options in any "no choice" claim; test whether options exist. | High: accountability for drift evaporates; path dependencies accumulate; reversibility is lost. | Reframe non-decisions as decisions; assign accountability; establish option preservation protocols; create re-opening mechanisms. | Create decision register that includes non-decisions and deferrals; assign owners; monitor drift explicitly. | Create dialogue about why options were excluded; enable re-opening if conditions change. |
| I.4 (Perceptual – Bounded Awareness & Attention Gaps) | M | Decision-makers have incomplete awareness of consequences, affected parties, or alternative options due to cognitive limits and information access limits. | M | Canvass multiple independent stakeholder perspectives; conduct environmental scan; test for blindspots using pre-mortems and red teams. | High (when consequences are large): decisions make sense locally but create systemic harm or miss opportunities. | Expand data collection and stakeholder engagement; include perspectives outside normal networks; build diverse decision forums. | Implement systematic scanning and environmental monitoring; broaden information sources; include representatives from affected populations. | Create forums where marginalised perspectives are actively solicited and weighted; rotate membership. |

(Additional rows: continue mapping other common Hiddens as appropriate to decision architecture; time/space constraints limit full enumeration here.)

## 8.4 Escalation Rule (Tier 3 – full Hiddens run)

If any of the following conditions hold, escalate to a full Hiddens investigation (Tier 3) before closing the decision analysis:

- Candidate Hiddens with High consequence and Medium+ detectability are identified (see table above).
- Residual unknowns remain that could change decision recommendations or accountability assignments.
- Disagreement persists across stakeholders about what is being decided, who decides, or on what basis.
- Post-decision review will have significant delay (>6 months); gaps need to be closed before lock-in.
- Scale of impact exceeds a defined threshold (e.g. enterprise-wide, irreversible, high-consequence).

---

# 9. Framework Application Protocol (mandatory)

## 9.1 Application Steps Table
| Step | Activity | Inputs | Outputs | Depth | Time estimate |
|---|---|---|---|---|---|
| 1 | Decision elicitation & naming | Scenario narrative; stakeholder interviews | List of named decisions (including non-decisions and deferrals); decision scope boundary statement | Light | 1–4 hours |
| 2 | Decision typing | Decision list; framework taxonomy (6×5) | Decision register with types and meta-categories assigned | Light | 1–2 hours |
| 3 | Seven-dimensional profiling | Decision register; context data; stakeholder input | Dimensional profile for each key decision (full or abbreviated) | Medium/Full | 2–6 hours |
| 4 | Dynamic pattern scan | Decision history; governance artefacts; interviews | Observed or suspected dynamic patterns (drift, capture, fatigue, escalation failure) | Medium | 2–4 hours |
| 5 | Interface mapping (A/B/C) | Decision register; governance map; challenge mechanisms audit | Detection, remediation, and interaction interface assessment; interface failure diagnosis | Medium | 2–4 hours |
| 6 | Tier 1 Hiddens scan | Decision register; stakeholder interviews; artefacts | Six-category Hiddens scan results; shortlist of candidate Hiddens | Medium | 2–4 hours |
| 7 | Tier 2 Hiddens mapping (if escalation triggered) | Candidate Hiddens shortlist; mechanism analysis; detection/remediation feasibility | Mapped Hiddens with detection (Type A) and remediation (Type B) interfaces | Full | 4–8 hours |
| 8 | Redesign & recommendations | All prior outputs; governance redesign options | Decision architecture redesign recommendations; governance change options; monitoring and re-scan cadence. | Full | 4–8 hours |
| 9 | Integration handoff | Decision architecture redesign; other framework outputs | Traced linkages to Evidence, Risk, Responsibility, Power, Governance, Learning frameworks; priorities and sequencing. | Light/Medium | 2–4 hours |
| 10 | Closure & escalation note (per OG v2.5 §7.4) | All outputs; residual unknowns; decision quality assessment | Residual unknowns register; escalation triggers; five required closure items (scope, dependencies, Unknowns, assumptions, escalation recommendation). | Light | 1–2 hours |

**Total time estimate: 19–46 hours for full depth execution; 6–16 hours for light depth (steps 1–6 only).**

## 9.2 Standard Deliverables (recommended)

1. **Decision Register** (table or spreadsheet)
   - Columns: Decision ID, Decision name, Type(s) (meta-category + specific), Decision-maker(s), Forum, Time window, Current status (proposed/in-progress/decided/deferred), Notes.
   - Include non-decisions and deferrals explicitly.
   - Link each decision to upstream inputs (Evidence, Risk, Responsibility).

2. **Dimensional Profile Summary** (table or narrative)
   - One row per key decision (or category of decisions).
   - Columns: Decision ID, Complexity & Reversibility, Evidence & Uncertainty, Contestation, Temporal Pressure, Governance Clarity, Formalisation, Scope & Scale.
   - Rating scale (Low/Medium/High) or narrative descriptor.
   - Notes on profile implications (e.g. "high complexity + tight timeline → need rapid escalation and reduced deliberation").

3. **Dynamic Pattern Scan Report** (narrative or table)
   - One section per observed dynamic (centralisation drift, criteria creep, escalation fatigue, etc.).
   - For each: signature observed, underlying mechanism, impact on decision quality, recommended mitigation.
   - Link to decision register entries where pattern is visible.

4. **Interface Assessment** (table or narrative)
   - For each interface type (Detection A, Remediation B, Interaction C):
     - Current state: what mechanisms exist?
     - Failures identified: where do mechanisms break?
     - Redesign options: what could be improved?
   - Link to candidate Hiddens and their remediation.

5. **Hiddens Register** (per standard table in §1.6.6)
   - All candidate Hiddens identified via Tier 1 scan + Tier 2 mapping (if escalated).
   - Include mechanism, detectability, consequence, suggested remediation.
   - Owner/role for each remediation item.

6. **Governance Redesign Recommendations** (narrative + options)
   - Summary of decision architecture flaws identified.
   - 2–4 redesign options, with pros/cons and implementation path.
   - Prioritised action list: quick wins, medium-term, long-term.
   - Roles, responsibilities, and resource needs.

7. **Residual Unknowns Register** (per OG v2.5 §7.4)
   - What remains unknown that could change recommendations?
   - Why is it unknown (data gap, access limitation, fundamental uncertainty)?
   - Impact if Unknown remains unresolved.
   - Plan to resolve (test, evidence request, escalation, acceptable ambiguity).

8. **Integration Handoff Summary** (pointer/table)
   - Links to outputs of Evidence, Risk, Responsibility, Power, Governance, Learning frameworks.
   - Any dependencies or conflicts that need resolution at next cycle.
   - Sequencing recommendations if multiple frameworks recommend changes.

---

# 10. Framework Principles (mandatory)

| # | Principle | Implication |
|---|---|---|
| 1 | Decision architecture is a design object, not an inevitable given. | Organisations can and should deliberately design decision architectures rather than allowing them to emerge or drift. Redesign is always possible. |
| 2 | Non-decisions are decisions. | Choosing not to decide, deferring indefinitely, and allowing defaults to persist are choice commitments with consequences and accountability. Include them in the decision register. |
| 3 | Decisions interact with evidence, risk, values, and legitimacy. Isolated analysis is incomplete. | Decision quality depends on quality of inputs from Evidence, Risk, Values/Ethics, and Responsibility frameworks. Integration is mandatory, not optional. |
| 4 | Decision failure is patternable and preventable. | Recurring dynamic patterns (drift, capture, fatigue, escalation failure) follow predictable mechanisms. Diagnostic and preventive interventions are available and should be implemented. |
| 5 | Temporal alignment is critical. | Decision windows, deadlines, and timing are as important as content. Misalignment between decision horizon and execution timeline is a primary source of failure. |
| 6 | Hiddens operate in every decision architecture. | Assume that hidden decision points, captured criteria, informal veto structures, and invisible coalitions are present. Systematic scanning is mandatory, not optional. Tier 1 scans are the minimum. |
| 7 | Visibility and challenge enable learning and accountability. | Decision architecture should be explicit, documented, auditable, and open to challenge. Transparency is not a luxury; it is the foundation of quality and trust. |
| 8 | Decision-maker competency matters. | Decision quality depends on whether the person/forum assigned to decide has the competency (reasoning, judgment, expertise, uncertainty tolerance) to do so. Competency gaps should be diagnosed and remedied. |
| 9 | Escalation is a design choice, not an inevitable consequence of risk. | Escalation paths, thresholds, and forum capacity should be deliberately designed, monitored, and adjusted. Escalation fatigue and gridlock are preventable through better design. |
| 10 | Post-decision review is mandatory for learning. | Every significant decision should have a post-decision review; outcomes should be linked back to decision quality; learning should be systematized and shared. One-off decisions without review perpetuate errors. |

---

# 11. Glossary (local domain terms; mandatory for "Stable" status)

| Term | Definition | Context / examples |
|---|---|---|
| Decision | A structured choice or non-choice that commits a system to a course of action or default. | Strategic decision; operational decision; non-decision; deferral. |
| Non-decision | A choice not to decide, to defer indefinitely, or to allow defaults to persist. | Allowing budget to lapse; declining to set criteria; deferring escalation decision. |
| Decision-maker / Decision forum | The agent or group authorized to make a specific decision. | Board; executive committee; program manager; cross-functional task force. |
| Decision architecture | The structural design of who decides, in what forum, under what process, on what basis, at what time. | Decision rights matrix; escalation protocol; evidence threshold; review cadence. |
| Decision right | An explicit or implicit authority granted to an agent or forum to make a specific category of decisions. | Authority to approve budget under $100K; authority to set product roadmap; authority to declare emergency. |
| Veto | Power to block or reject a proposed decision. | Executive veto; legal veto; board veto; stakeholder veto (formal or informal). |
| Escalation | The process of moving a decision upward or outward to a higher authority, broader forum, or different decision-maker. | Escalation trigger; escalation path; escalation forum. |
| Decision window | The time period within which a decision can and should be made. | Board meeting cycle; quarterly planning window; crisis decision window (hours). |
| Option space | The set of feasible alternatives considered or available for a decision. | Truncated option space (due to filter); expanded option space (via creative generation). |
| Criteria | The basis or standard by which options are evaluated and a choice is made. | Safety-first criteria; cost-benefit criteria; stakeholder-consent criteria; evidence threshold. |
| Criteria creep / drift | Gradual shift in decision criteria from stated standard to actual practice. | Initially "evidence-based," later "gut-feel"; initially "safety-first," later "speed-first." |
| Evidence threshold | The quality and sufficiency of evidence required to support a decision. | "Anecdotal evidence acceptable"; "RCT required"; "expert opinion sufficient." |
| Capture | Structural distortion of decision-making such that outcomes systematically favor one faction, interest, or perspective over others. | Regulatory capture; governance capture; decision capture by incumbent or powerful faction. |
| Shadow decision | A real choice or commitment made outside formal forums and decision structures. | Informal coalition agreement; undeclared veto; back-channel negotiation outcome. |
| Hiddens (in decisions context) | Decision points, criteria, constraints, or affected parties that are not being recognised or made explicit. | Hidden escalation rules; hidden veto-holder; hidden decision point (treated as "routine"); hidden option truncation. |
| Tier 1 Hiddens scan | A six-category visibility audit across perceptual, systemic, informational, temporal, relational, and ontological Hiddens. | Initial scan of any decision architecture; quick-pass screening for major blindspots. |
| Tier 2 Hiddens mapping | Structured deepening of Tier 1 results; mechanism analysis and detectability assessment; remediation interface mapping. | After Tier 1 scan, if high-impact candidate Hiddens are identified; mid-depth investigation. |
| Tier 3 Hiddens escalation | Full Hiddens investigation (per OG v2.5 §D.6.10); investigation of decision blindness at deepest depth. | After Tier 2 mapping, if residual unknowns could change accountability or remediation priorities. |
| Interface (Decision context) | A point where decision problems surface (Detection A), are corrected (Remediation B), or are coordinated in real-time (Interaction C). | Pre-mortem (Detection A); governance redesign (Remediation B); escalation dialogue (Interaction C). |
| Dynamic pattern | A recurring pattern of decision architecture change or degradation over time. | Centralisation drift; criteria creep; option space erosion; escalation fatigue. |
| Accountability diffusion | Progressive dilution of responsibility for outcomes and non-decisions as decision-making becomes more collective or polycentric. | "Everyone decided, so no one is accountable"; sequential chain where each actor disowns prior choices. |
| Formalisation & ritualisation | Process becomes formal and ritualised while substantive reasoning and challenge weaken. | Meetings and documents continue; challenge and deliberation atrophy; process becomes compliance ritual. |
| Governance redesign | Deliberate change to decision architecture: rights, forums, process, criteria, escalation, oversight. | Moving decision rights from committee to individual authority; adding external oversight; changing evidence threshold; implementing sunset clauses. |

---

# 11.2 Operating Guide Pointers & Cross-References

- **Canonical Prompt Discipline Rules**: OG v2.5, §D.3
- **Tiered Hiddens Scan Specification**: OG v2.5, §D.6.10 (Tier 1, 2, 3 definitions and escalation rules)
- **Run Mode Semantics (Rapid vs Investigative) and Anti-Conflation Invariant**: OG v2.5, §D.10.1
- **Routing Decision Logic (Start-of-Run, Pre-Closure, Minimum Group Coverage)**: OG v2.5, §4.3
- **Unified Iteration Loop**: OG v2.5, §5.0 (Route → Execute → Test → Re-scan → Decide/Close)
- **Targeted Hiddens Discovery Scans**: OG v2.5, §7.5 (thirteen mechanism-specific cross-framework scans)
- **Closure Discipline & Five Required Closure Items**: OG v2.5, §7.4
- **Framework Index (all 36 frameworks and Group assignments)**: OG v2.5, §3.2

---

# 12. Document Control (mandatory for "Stable" status)

## 12.1 Version History
| Version | Date | Author / Maintainer | Status | Key changes |
|---|---|---|---|---|
| v1.2 | 2026-03-28 | Anthropic Claude Opus 4.6 | Draft | Enhanced §5 Dynamics table from 6 to 10 patterns; restructured §6 Interface Types to A/B/C model; maintained 30-type taxonomy. |
| v2.0 | 2026-04-06 | Anthropic Claude Opus 4.6 | Draft | **Full rewrite aligned with Master Template v2.3.** Updated all OG references from v1.5 to v2.5. Added comprehensive Introduction (four subsections). Expanded §1.2 with Assumptions Register and Preconditions Checklist per template. Enhanced all core sections per template invariants. Expanded §7.3 with all 36 canonical frameworks. Added complete §8.3 Tier 2 Hiddens mapping. Added copy-ready run prompts in §1.6.7. Updated §11 and §12 with full version history and integration notes. Expanded Glossary. **Total word count: 700–850 lines (target 600–1000 achieved).** |

## 12.2 Integration Notes (optional)

**Template alignment**: v2.0 fully aligns with Master Rewrite Template v2.3 (2026-04-02) and Operating Guide v2.5 (2026-04-06).

**Companion frameworks**: Framework of Situations (v2.0, 2026-04-06); Framework of Evidence & Uncertainties; Framework of Risk & Appetite; Framework of Responsibility & Accountability; Framework of Power & Incentives; Framework of Governance & Operations; Framework of Hiddens.

**Key downstream consumers**: Governance operations teams; transformation and programme leaders; incident and crisis response teams; risk and resilience teams; investigators and auditors; regulators and oversight bodies.

**Execution context**: Primary use case is Investigative Run Mode (post-failure analysis, governance redesign, full Hiddens mapping). Rapid Run Mode (decision-architecture audit, light-touch typing) suitable for triage and intake. Light Depth execution (decision scan, Tier 1 Hiddens) is minimum viable; Full Depth (comprehensive profiling, Tier 2 mapping, redesign) triggered by OG §4.3 routing or when consequence is high, evidence is contested, or capture/drift is suspected.

---

# Appendices (included)

## Appendix A: Decision Register Template

Use this template to capture all identified decisions and non-decisions:

| Decision ID | Decision name | Type (meta-category) | Specific type | Decision-maker | Forum | Time window | Status | Key criteria | Evidence threshold | Known Hiddens | Integration notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| D-001 | | | | | | | | | | | |
| D-002 | | | | | | | | | | | |

---

## Appendix B: Tier 1 Hiddens Scan Worksheet

| Hiddens category (I–VI) | Present? (Y/N/?) | Evidence/symptoms | Priority (H/M/L) | Escalation to Tier 2? (Y/N) | Notes |
|---|---|---|---|---|---|
| I Perceptual | | | | | |
| II Systemic | | | | | |
| III Informational | | | | | |
| IV Temporal | | | | | |
| V Relational | | | | | |
| VI Ontological | | | | | |

---

## Appendix C: Governance Redesign Options Template

| Design option | Description | Pros | Cons | Implementation pathway | Effort/timeline | Risk |
|---|---|---|---|---|---|---|
| Option A: Clarify decision rights | Explicit RACI matrix; decision authority per category | Reduces ambiguity; speeds decisions | Requires stakeholder negotiation; may reveal conflicts | Facilitate governance workshop; document and publish; train decision-makers | 2–4 weeks | Resistance from power-holders |
| Option B: Add challenge mechanism | Pre-mortem; red-team; devil's advocate role | Surface blindspots; improve quality | Adds time to decision; requires skilled participants | Define pre-mortem protocol; assign devil's advocate role; build calendar into decision timeline | 1–2 weeks | Perceived as slowing decisions |
| Option C: Implement decision registry & audit | Document all decisions; periodic criteria audit | Visibility; learning from patterns; detect drift | Overhead in documentation; access/transparency tensions | Define decision register schema; establish audit cadence (quarterly); assign audit owner | 2 weeks setup + ongoing | Privacy/confidentiality concerns |

---

**END OF DOCUMENT**

