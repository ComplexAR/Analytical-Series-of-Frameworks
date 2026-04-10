# ASF Rewrite Project Brief v1.0
**Date:** 2026-04-08
**Status:** Active — ready for Phase 1 execution
**Prepared by:** Claude Sonnet 4.6 (Cowork session, 2026-04-08)

---

## Purpose of This Document

This brief captures all decisions made in the planning conversation of 2026-04-08. A new Cowork session should read this document first before undertaking any project work. It contains everything needed to proceed without reconstructing prior analysis.

---

## What the ASF Is

The Analytical Series of Frameworks (ASF) is a structured analytical toolkit of 36 frameworks (expanding to 50) organised into 6 groups (G1–G6), designed to discover and uncover hiddens — visibility failures caused by identifiable mechanisms — in social, socio-technical, and technical scenarios. The primary execution mode is LLM-assisted analysis governed by the Operating Guide.

---

## Why This Rewrite Is Happening

Two problems identified through systematic analysis:

**Problem 1 — Analytical gaps.** The current 36-framework series has 14 significant gaps, particularly for surfacing hiddens. The 14 new frameworks address these gaps.

**Problem 2 — Token/context window constraint.** Individual framework documents average ~25,000 tokens each. Loading multiple simultaneously for Full Depth LLM execution is impractical within a 200,000-token context window. A 3-tier document architecture solves this.

---

## The 50 Frameworks

### Original 36 (files exist, need §1.6 update only)

| Group | Frameworks |
|---|---|
| G1 (Framing) | Situations Context Classification, Boundaries, Dimensions, Realities, Scale, Time |
| G2 (Mechanism) | Systems, Relations, Processes, Causation, Resources |
| G3 (Agency) | Agents, Personas, Incentives, Power, Responsibility, Competencies |
| G4 (Meaning) | Culture and Norms, Perspectives, Narratives, Communications, Legitimacy, Values |
| G5 (Epistemics) | Beliefs, Evidence, Uncertainties, Failures, Hiddens, Diagnosis, Metrics, Knowledge |
| G6 (Action & Control) | Decisions, Interventions, Governance, Risk, Learning and Adaptation |

### 14 New Frameworks (need authoring)

| Group | New Frameworks | Priority for authoring |
|---|---|---|
| G1 (Framing) | Space and Place | 4th batch |
| G2 (Mechanism) | Emergence, Networks, Institutions, Technology, Coordination | 1st batch (Technology, Institutions, Emergence); 2nd batch (Networks); 4th batch (Coordination) |
| G3 (Agency) | Interests, Emotions, Conflict, Cognition | 2nd batch (Cognition); 3rd batch (Interests, Emotions, Conflict) |
| G4 (Meaning) | Ethics, Trust | 3rd batch |
| G6 (Action & Control) | Implementation, Scenarios | 4th batch |

**Authoring order rationale:** Most analytically novel first (Technology, Institutions, Emergence), then near-neighbour disambiguation-heavy (Cognition, Networks, Trust), then closely related to existing frameworks (Interests, Emotions, Conflict, Ethics), then operationally grounded (Coordination, Space and Place, Implementation, Scenarios).

---

## 3-Tier Document Architecture

### Tier 1 — Full Framework Documents
- ~25,000 tokens each (human-readable comprehensive reference)
- Produced using the Master Rewrite Template (MRT)
- 50 documents total (36 existing + 14 new to author)
- NOT loaded into LLM context during execution — too large
- Used by human analysts and as source for extract generation

### Tier 2 — LLM Execution Extracts
- ~5,000–8,000 tokens each (compact operational LLM interface)
- Produced using the new LLM Execution Extract Template (LLMET)
- 50 extracts total (one per framework)
- Loaded into LLM context at runtime alongside the LLM-Only Operating Guide
- Contains: operational definition, near-neighbour disambiguation, condensed taxonomy, condensed dynamics, Hiddens cross-check prompts, LLM execution protocol, cross-framework routing

### Tier 3 — Operating Guides
- **Full Operating Guide** (~62,000 tokens): Human-readable orchestration doctrine. Currently v2.5. Needs v3.0 update for 50 frameworks. NOT used directly in LLM execution context.
- **LLM-Only Operating Guide** (~15,000–18,000 tokens): NEW document. Compact execution adapter for LLMs. Contains routing decision tree, pseudocode, prompt discipline rules, output contract, orchestrator prompts, framework index, group-to-hiddens linkage. Strips all narrative prose.

**Runtime context budget (for reference):** System prompt (~12k) + LLM-Only OG (~16k) + 4 extracts at 6k each (~24k) + scenario + history + output ≈ ~80–120k tokens. Well within 200k limit.

---

## 4-Phase Implementation Plan

### Phase 1 — Foundation Documents (DO THIS FIRST)
These three documents must exist before any other work begins. They define structural standards everything else conforms to.

**Deliverable 1: Updated MRT (v2.3 → v3.0)**
- Single change: replace §1.6 (LLM Use & Operating Guide Integration) with a lightweight LLM Integration Bridge
- Bridge section contains three things only:
  1. Pointer to the framework's LLM execution extract
  2. Near-neighbour disambiguation table (2–4 nearest frameworks; "use this when... / use X instead when...")
  3. Routing trigger list (scenario features that should direct analysis to this framework)
- Target: ~300–500 tokens when completed (vs. current §1.6 which is much larger)
- Source file: `2026-04-02-Anthropic-Claude-Opus-4-6-Analytical_Series_Master_Rewrite_Template_v2.3_Operating_Guide_v2.4_Aligned.md`
- Output: `2026-04-08-Anthropic-Claude-Opus-4-6-Analytical_Series_Master_Rewrite_Template_v3.0.md`
- Model: Opus sub-agent

**Deliverable 2: New LLM Execution Extract Template (LLMET)**
- Entirely new document, no existing equivalent
- Target: <2,000 tokens for the template itself (so it can be provided in context during extraction)
- Defines 8 mandatory sections every extract must contain:
  1. Operational header (framework name, group, stage, OG compatibility, token budget ceiling)
  2. Single-paragraph operational definition (what it is, primary question, registers populated)
  3. Near-neighbour disambiguation table (2–4 nearest frameworks with explicit distinctions)
  4. Condensed core taxonomy (meta-categories and types, table form only — no prose)
  5. Condensed dynamics (key patterns, table form only)
  6. Compact Hiddens cross-check prompts (scan questions by meta-category I–VI, primary hiding mechanisms, detection/remediation interface pointers)
  7. LLM execution protocol (Light Depth vs Full Depth actions, registers to update, gate question)
  8. Cross-framework routing pointers (upstream inputs, downstream handoffs, targeted scans that invoke this framework)
- Output: `2026-04-08-Anthropic-Claude-Opus-4-6-Analytical_Series_LLM_Execution_Extract_Template_v1.0.md`
- Model: Opus sub-agent

**Deliverable 3: New LLM-Only Operating Guide**
- Derived from current Operating Guide v2.5 by extraction and compression
- Target: 15,000–18,000 tokens
- INCLUDE (from v2.5): §4.3 compact routing decision tree, §5.0.2 pseudocode loop, §D.3 prompt discipline rules (table form), §D.4 output contract, §D.9 canonical orchestrator prompts, §D.11 machine-navigable decision tree, §3.2 framework index, §2.2 group-to-hiddens linkage, §1.3 core definitions (compact), §7.1 Tier 1 six-category scan, §7.5.2 scan catalogue (scan definitions and gate questions only), §7.5.3 triage matrix, §D.6 run mode definitions (tables only), key glossary terms (§11, compact)
- EXCLUDE: all narrative introductions, version history (§12), governance section (§9), operating principles (§10 — merge key points into definitions), Appendices A/B/C, extended §7.5 narrative, §1.1/§1.2 (keep only §1.3 definitions), §5.1–5.3 step-by-step protocols (keep pseudocode only), §6 artefact schemas (move minimal versions to output contract section)
- Based on current 36 frameworks; will need Phase 4 update for 50 frameworks
- Output: `2026-04-08-Anthropic-Claude-Opus-4-6-Analytical_Series_LLM_Only_Operating_Guide_v1.0.md`
- Model: Opus sub-agent

### Phase 2 — Framework Updates and New Authoring (parallel after Phase 1)

**2a. Update §1.6 in all 36 existing framework documents**
- For each document: replace current §1.6 with the LLM Integration Bridge from updated MRT
- Mechanical work — read each document, extract near-neighbour disambiguation content and routing triggers, populate bridge
- Source content within each document: §1.3 (Definitions and Common Confusions → definition and "not…" distinctions), §1.5 (Crosswalk Summary → near-neighbour frameworks and what this one adds), §1.6.1 (LLM Execution Quickstart → routing triggers and best-fit scenarios)
- Process in batches of 3–4 per session
- Model: Sonnet adequate
- Source files: `2026-04-06-Anthropic-Claude-Opus-4-6-Framework_of_[Name]_v2.0.md`
- Output naming: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_[Name]_v2.1.md`

**2b. Author 14 new full framework documents**
- Use updated MRT (v3.0) as template
- Each document ~25,000 tokens
- Model: Opus sub-agent for each (intellectually demanding)
- Authoring batches:
  - Batch 1: Technology, Institutions, Emergence (most novel)
  - Batch 2: Cognition, Networks, Trust
  - Batch 3: Interests, Emotions, Conflict, Ethics
  - Batch 4: Coordination, Space and Place, Implementation, Scenarios
- Output naming: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_[Name]_v1.0.md`

### Phase 3 — LLM Execution Extract Generation (after Phase 1 + Phase 2)

**3a. Pilot extract**
- Generate the Hiddens framework extract first
- Validate against a real scenario to confirm the LLMET produces an effective execution interface
- Fix any LLMET structural gaps before proceeding
- Model: Opus sub-agent

**3b. Generate 36 extracts from existing framework documents**
- Read each full framework document, apply LLMET, produce extract
- Process in batches
- Model: Sonnet adequate for existing frameworks
- Output naming: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_[Name]_LLM_Extract_v1.0.md`

**3c. Generate 14 extracts from new framework documents**
- Same process as 3b
- Model: Opus for new frameworks (more complex disambiguation content)

### Phase 4 — Operating Guide Integration (after all framework documents complete)

**4a. Update full Operating Guide (v2.5 → v3.0)**
- §3.2: Add 14 new framework entries to framework-to-group mapping
- §2.2: Review G3 internal structure (grows to 9 frameworks; consider internal routing)
- §4.3: Assess whether new routing branches needed (Technology and Institutions introduce new hiding mechanism families)
- §7.5: Assess whether new targeted scans warranted; update existing scan routes to incorporate new frameworks where relevant
- §11: Add definitions for all 14 new frameworks
- Model: Opus (complex structural reasoning)

**4b. Update LLM-Only Operating Guide (v1.0 → v2.0)**
- Update §3.2 framework index, §4.3 routing tree, §2.2 group-to-hiddens linkage
- Mechanical update following 4a
- Model: Sonnet adequate

---

## Model Routing Strategy

| Task | Model | Reason |
|---|---|---|
| 14 new full framework documents | Opus sub-agent | Original analytical synthesis, 25k token consistency |
| Updated MRT | Opus sub-agent | Sets structural standard for all new documents |
| LLMET design | Opus sub-agent | Sets structural standard for all 50 extracts |
| LLM-Only Operating Guide creation | Opus sub-agent | Complex extraction/compression judgment |
| Full OG update (routing tree, scans) | Opus sub-agent | Complex structural reasoning across full architecture |
| 36 §1.6 updates | Sonnet | Pattern-following, mechanical |
| 36 extracts from existing frameworks | Sonnet | Template-following against clear source material |
| 14 extracts from new frameworks | Opus sub-agent | More complex disambiguation for novel frameworks |
| Architectural design conversations | Opus (main session) | Switch main session model for design work |
| Batch file operations | Sonnet | Mechanical |

**Configuration:** Cowork runs Sonnet as default. Opus sub-agents spawned within sessions using the Agent tool (model: "opus"). Switch main session model to Opus for architectural design conversations only.

---

## Key Source Files

All files in the workspace folder `Analytical Series of Frameworks/`:

| File | Purpose |
|---|---|
| `2026-04-02-...-Operating_Guide_v2.5.md` | Full Operating Guide (source for Phase 1 LLM-Only OG and Phase 4 update) |
| `2026-04-02-...-Master_Rewrite_Template_v2.3_...md` | Current MRT (source for Phase 1 MRT update) |
| `2026-04-06-...-Framework_of_[Name]_v2.0.md` (×36) | Current framework documents (source for Phase 2a updates and Phase 3b extracts) |
| `2026-04-01-...-Operating_Guide_LLM_Decision_Tree.md` | Supplementary decision tree reference |
| `2026-04-07-ASF-Test-Protocol-v1.0.md` | Test protocol (review before Phase 3 pilot) |

---

## Phase 2b Supplement: Analytical Scope for the 14 New Frameworks

This section provides the per-framework analytical grounding needed to author each new framework document. A new session authoring any of these frameworks should read its entry here before beginning, alongside the updated MRT and the most relevant existing near-neighbour framework documents.

Each entry covers: primary analytical question, core definition, key near-neighbour distinctions (the most important for preventing LLM conflation), and primary hiding mechanisms the framework is designed to surface.

---

### 1. Technology (G2 — Mechanism)

**Primary analytical question:** What technological systems, affordances, constraints, and embedded assumptions shape what is possible, visible, and invisible in this scenario?

**Core definition:** Technology analyses how designed artefacts, systems, platforms, algorithms, protocols, and infrastructures shape social possibility, embed values and assumptions, distribute power, and create or foreclose analytical visibility. It covers hardware, software, platforms, and the sociotechnical assemblages they form. Technology is not abstract structure (that is Systems) nor allocation of inputs (that is Resources) — it is specifically about designed artefacts and their social, political, and epistemic effects.

**Key near-neighbour distinctions:**
- vs. Systems: Systems models abstract components, flows, and feedback; Technology specifically addresses designed artefacts and the hidden values, affordances, and power structures embedded in their design
- vs. Processes: Processes covers how activities flow; Technology covers the designed substrate that enables or constrains those flows and embeds assumptions about who uses them and how
- vs. Resources: Resources covers what is available for use and how it is allocated; Technology covers what technical systems make possible or impossible regardless of availability
- vs. Institutions: Institutions covers rules and norms; Technology covers designed artefacts — the two interact (technology embeds and enforces institutional rules) but are analytically distinct

**Primary hiding mechanisms:**
- Hidden values and assumptions embedded in technical design (algorithms encode bias; interfaces embody assumptions about users that are invisible to those users)
- Black box opacity (technical systems whose internal workings are not legible to users, investigators, or even operators)
- Infrastructural invisibility (technology becomes invisible through ubiquity — it shapes what is possible without being noticed as a constraint)
- Affordance blindspots (what a technology makes easy becomes the default; what it makes hard becomes invisible as a choice that could be otherwise)
- Power distribution concealed as technical neutrality (who controls, designs, and benefits from technology is hidden behind claims of technical objectivity)

---

### 2. Institutions (G2 — Mechanism)

**Primary analytical question:** What formal and informal rules, norms, and conventions structure behaviour in this scenario, and what do they make invisible?

**Core definition:** Institutions are the formal and informal rules, norms, conventions, and enforcement mechanisms that structure social behaviour over time. Includes laws, regulations, organisational procedures, professional norms, and the unwritten rules that "everyone knows." Distinct from Culture and Norms (shared values and identity practices) and from Governance (formal decision-making authority) — Institutions covers the structural rule environment that constrains behaviour regardless of values, and independently of who formally holds authority.

**Key near-neighbour distinctions:**
- vs. Governance: Governance covers formal decision rights and oversight structures; Institutions covers the broader rule environment — including informal rules — that constrains even formal governance actors
- vs. Culture and Norms: Culture covers shared values and identity-based practices that people follow because they believe in them; Institutions covers structural rules (formal and informal) that constrain behaviour regardless of personal values, often through enforcement mechanisms
- vs. Systems: Systems covers functional interdependencies between components; Institutions covers the rule-based constraints that structure how those systems operate and who can change them
- vs. Coordination: Coordination covers the dynamic process of actors aligning action; Institutions covers the stable rule structures that make certain forms of coordination possible or impossible

**Primary hiding mechanisms:**
- Informal institutions that are never written down but powerfully constrain behaviour ("that's just how things work here")
- Institutional logics so embedded they are invisible as constraints rather than choices — actors cannot imagine alternatives
- Rule-practice gaps (what the formal institution prescribes versus what actually happens in practice — the gap is systematically hidden)
- Institutional lock-in (path dependencies that foreclose options without actors recognising the foreclosure as a choice)
- Cross-institutional conflicts hidden by formal compliance with each individual institution

---

### 3. Emergence (G2 — Mechanism)

**Primary analytical question:** What system-level properties, behaviours, and outcomes in this scenario arise from component interactions that are not predictable from those components individually?

**Core definition:** Emergence analyses how complex systems produce properties, behaviours, and outcomes at the system level that cannot be predicted from or reduced to the properties of individual components. Covers non-linear dynamics, tipping points, cascade effects, self-organisation, and path-dependent lock-in. Distinct from Systems (which models structure and components) by focusing specifically on what arises from interactions that was not in any component — the unexpected, threshold-crossing, qualitatively new behaviour.

**Key near-neighbour distinctions:**
- vs. Systems: Systems models components, interfaces, and flows; Emergence focuses on what arises from those interactions that is not predictable from the components — the non-linear, threshold-crossing, or qualitatively novel behaviour that Systems analysis alone would miss
- vs. Causation: Causation traces mechanism chains (A causes B); Emergence addresses phenomena where outcomes cannot be traced to a single causal chain but arise from interaction effects between multiple causes simultaneously
- vs. Processes: Processes covers how activities flow in sequence; Emergence covers what happens when processes interact in ways that produce qualitatively different dynamics than any individual process would produce
- vs. Risk: Risk estimates probability distributions over known outcome types; Emergence addresses outcomes that were not in the probability distribution — genuinely novel system-level phenomena

**Primary hiding mechanisms:**
- Non-linearity blindspots (linear analysis systematically misses threshold effects and tipping points)
- Reductionist invisibility (analysing components individually makes system-level emergent properties invisible — they only exist at the aggregate level)
- Temporal mismatch (emergence often unfolds over time scales that do not match investigation timeframes — the process is invisible because it is too slow or too fast)
- Cascade invisibility (initial small changes that will cascade are not identifiable as significant from local observation at the time)
- Ontological novelty (genuinely emergent phenomena may lack existing analytical categories — there is no language for what is appearing)

---

### 4. Cognition (G3 — Agency)

**Primary analytical question:** What mental models, cognitive biases, heuristics, and reasoning processes shape what actors perceive, attend to, and conclude in this scenario?

**Core definition:** Cognition analyses how agents' mental processes — mental models, heuristics, cognitive biases, attention allocation, and bounded rationality — shape what they perceive, what they miss, and what conclusions they reach. Its distinctive contribution is addressing hiddens that are hidden from actors themselves due to how their minds work, not merely hiddens hidden from external observers. An actor's mental model of a system determines what anomalies are even visible to them.

**Key near-neighbour distinctions:**
- vs. Beliefs: Beliefs covers what agents hold to be true (the content of mental states); Cognition covers the processes by which beliefs are formed, updated, and applied — the mechanics of reasoning and perception that determine which beliefs are even entertained
- vs. Personas: Personas covers stable behavioural patterns and role-based profiles observable from the outside; Cognition covers the internal mental processes that produce those patterns
- vs. Emotions: Emotions covers affective states that drive behaviour; Cognition covers information-processing and reasoning processes — the two interact (affect shapes cognition) but are analytically distinct
- vs. Knowledge: Knowledge covers what agents know and how knowledge is created and distributed; Cognition covers how agents process and reason with what they know, including systematic errors in that processing

**Primary hiding mechanisms:**
- Confirmation bias (actors selectively notice evidence that confirms existing beliefs, making disconfirming evidence invisible)
- Availability heuristic (recent or salient events dominate judgment, making less available but relevant realities functionally invisible)
- Expert blind spots (experts cannot see what they take for granted; novices cannot see what they lack knowledge to notice — different but complementary blindness)
- Mental model lock-in (an actor's mental model of a system determines what anomalies are even visible to them — anomalies outside the model are invisible)
- Framing effects (how a choice or situation is presented shapes what is seen — what the current framing makes invisible is a systematic source of hiddens)

---

### 5. Networks (G2 — Mechanism)

**Primary analytical question:** How does the topology of connections between actors or components shape information flow, influence, vulnerability, and visibility in this scenario?

**Core definition:** Networks analyses how the structural pattern of connections between actors, nodes, or components shapes what flows where, who has influence, where vulnerabilities concentrate, and what is visible from which position. Its distinctive contribution relative to Relations is topological focus — not the character of individual connections but how the overall pattern of connectivity produces structural properties (centrality, clustering, bridging, isolation) that shape outcomes.

**Key near-neighbour distinctions:**
- vs. Relations: Relations analyses the nature and quality of specific connections (trust, power, dependency); Networks analyses the topological structure of the connection pattern as a whole — what structural positions (central hub, bridge, isolate, dense cluster) exist and what properties those positions produce regardless of the quality of any individual connection
- vs. Systems: Systems models functional components and flows; Networks models the connection topology that shapes how those flows travel, concentrate, or are blocked
- vs. Agents: Agents identifies who acts and what capacities they have; Networks reveals how structural position shapes what those agents can see, hear, and influence regardless of their individual capacities
- vs. Power: Power analyses the capacity to shape others' behaviour; Networks reveals how structural position creates or removes power in ways not visible from individual dyadic relationships

**Primary hiding mechanisms:**
- Structural hole blindness (actors do not see what they are not connected to, and do not see the value or risk of their own bridging position)
- Echo chamber dynamics (dense clustering means disconfirming information never reaches certain nodes — structural isolation produces epistemic isolation)
- Cascade pathways (the routes by which failure, information, or contagion propagates are invisible until they activate)
- Positional blindness (actors see the world from their network position and systematically miss what adjacent or distant positions see)
- Hub dependency invisibility (concentration of connectivity at hubs creates systemic fragility that is invisible in node-level analysis)

---

### 6. Trust (G4 — Meaning)

**Primary analytical question:** Who trusts whom, on what basis, and what does that pattern of trust and distrust make possible or invisible in this scenario?

**Core definition:** Trust analyses the mechanisms by which actors extend confidence to other actors, institutions, and information sources, and the consequences of that extension for cooperation, delegation, and visibility. Covers interpersonal trust, institutional trust, epistemic trust (trusting knowledge sources), and the dynamics of trust building, maintenance, and breakdown. Distinct from Legitimacy (socially accepted authority) and Relations (general character of connections) — Trust specifically covers the confidence-under-vulnerability mechanism.

**Key near-neighbour distinctions:**
- vs. Legitimacy: Legitimacy covers whether actors accept authority as valid and justified; Trust covers whether actors are willing to be vulnerable to others' actions — they overlap but legitimacy is about perceived right to act, trust is about willingness to depend
- vs. Relations: Relations covers the general character and quality of connections; Trust is a specific mechanism within a relation — confidence extension under conditions of vulnerability — that may or may not characterise any given relation
- vs. Incentives: Incentives covers reward/punishment structures that motivate behaviour; Trust covers willingness to cooperate that persists even when incentive structures alone would not support it — and can be destroyed by making incentive structures too explicit
- vs. Culture and Norms: Culture covers shared values and practices; Trust covers specific dyadic or institutional confidence mechanisms that vary significantly within a shared cultural context

**Primary hiding mechanisms:**
- Trust asymmetries (A trusts B but B does not trust A — creates invisible structural dependencies and information flow restrictions)
- Misplaced trust (confidence extended to actors or institutions that do not warrant it conceals actual risks and substitutes social relationship for evidence)
- Epistemic trust chains (information is trusted because its source is trusted, hiding the independent question of whether that source is reliable)
- Trust deficits (where distrust exists, information sharing is suppressed even when sharing would serve both parties — the distrust is the hiding mechanism)
- Institutional trust substitution (formal trust in institutions substitutes for evaluating actual trustworthiness, hiding performance gaps behind reputational halo)

---

### 7. Interests (G3 — Agency)

**Primary analytical question:** What do the actors in this scenario fundamentally need or want beneath the positions they have stated?

**Core definition:** Interests analyses what agents fundamentally need, want, or care about at a level beneath their stated positions, demands, or preferences. Covers material interests (security, resources, welfare), procedural interests (recognition, fairness, voice), and identity interests (belonging, dignity, coherence). Its distinctive contribution relative to Incentives is addressing more foundational and often unstated motivations — what agents actually care about, not just what they are rewarded or punished for.

**Key near-neighbour distinctions:**
- vs. Incentives: Incentives covers the transactional reward/punishment structures that shape behaviour in the moment; Interests covers what agents fundamentally need or want — which may conflict with their immediate incentives (an agent's interest in safety may conflict with their incentive to report optimistically)
- vs. Values: Values covers normative commitments about what matters; Interests covers what agents actually need or want regardless of what they profess to value — the two can conflict significantly
- vs. Emotions: Emotions covers affective states; Interests covers the underlying substantive concerns (security, recognition, belonging) that persist beyond momentary affect and generate those affective states when engaged or threatened
- vs. Agents: Agents identifies who actors are and what capacities they have; Interests identifies what they fundamentally want beneath stated positions

**Primary hiding mechanisms:**
- Strategic concealment (actors hide true interests behind stated positions to preserve negotiating advantage — the gap between position and interest is deliberately hidden)
- Interests-positions confusion (stated positions are taken as interests, hiding the actual motivational structure and foreclosing resolution that would address the underlying need)
- Conflicting interests within actors (an actor's material interests conflict with their identity interests — neither surface cleanly in behaviour or statements)
- Organisational interest aggregation (individual interests are hidden behind the stated interest of the organisation they represent)
- Unconscious interests (actors are not always aware of their own fundamental interests, making them hidden from themselves as well as from observers)

---

### 8. Emotions (G3 — Agency)

**Primary analytical question:** What affective states are driving, shaping, or suppressing behaviour in this scenario, and what are they making visible or invisible?

**Core definition:** Emotions analyses how affective states — fear, anger, grief, solidarity, shame, pride, anxiety, resentment — drive behaviour, shape perception, influence decision-making, and structure social dynamics in ways that are typically unacknowledged or suppressed. Addresses emotions both as analytical objects that explain behaviour and as hiding mechanisms in their own right (suppressed or unacknowledged emotion conceals what is actually driving events).

**Key near-neighbour distinctions:**
- vs. Incentives: Incentives covers rational reward structures; Emotions covers affective drivers that operate alongside, against, or independently of incentive logic and frequently explain apparently irrational behaviour that incentive analysis cannot account for
- vs. Cognition: Cognition covers information processing and reasoning; Emotions covers affective states that shape what agents attend to, how they reason, and what they are willing to consider — affect shapes cognition but is analytically distinct from it
- vs. Interests: Interests covers what agents fundamentally want; Emotions covers the affective states that arise when interests are engaged, threatened, or fulfilled — emotions are often the signal that an interest is at stake
- vs. Culture and Norms: Culture covers shared emotional norms (what feelings are appropriate to express); Emotions covers the actual affective states that may conflict sharply with cultural display rules

**Primary hiding mechanisms:**
- Rationalisation (emotional drivers are explained away with rational justifications, hiding the actual motivational source and foreclosing interventions that address the emotion)
- Suppression norms (cultural or organisational norms make certain emotions unspeakable, creating enforced emotional blindspots — the emotion drives behaviour but cannot be named)
- Collective denial (groups collectively suppress uncomfortable emotions — grief, fear, shame — making them invisible in official accounts while they continue to shape behaviour)
- Affective framing (the emotional valence attached to options or actors shapes perception in ways not acknowledged as emotional — appears as rational judgment)
- Emotional contagion invisibility (emotional states spread through groups and shape collective behaviour but are not visible in any individual's stated rationale)

---

### 9. Conflict (G3 — Agency)

**Primary analytical question:** What contestation, adversarial dynamics, and competing interests are active or latent in this scenario, and what do they conceal?

**Core definition:** Conflict analyses contestation between actors — including open conflict, suppressed conflict, structural conflict, and competitive dynamics — and the consequences for what becomes visible or invisible. Covers overt disputes, latent tensions, structural incompatibilities, collective action failures, and adversarial strategic behaviour. Distinct from Power (capacity to shape outcomes) by focusing on the relational dynamics of contestation itself, including conflicts between actors of similar power and structural conflicts with no single powerful actor.

**Key near-neighbour distinctions:**
- vs. Power: Power covers who has the capacity to shape what happens; Conflict covers the relational dynamics of contestation between actors — including near-equals and structural conflicts where no individual actor is "the" powerful one
- vs. Interests: Interests identifies what actors fundamentally want; Conflict analyses what happens when those interests are incompatible and actors act on that incompatibility in their behaviour
- vs. Incentives: Incentives covers reward structures; Conflict covers the adversarial dynamics that emerge when incentive structures are incompatible or zero-sum — when one actor's gain requires another's loss
- vs. Agents: Agents identifies who acts and with what capacity; Conflict analyses the relational patterns of opposition between those agents

**Primary hiding mechanisms:**
- Latent conflict suppression (structural conflicts that have not yet surfaced are invisible until they erupt — surfacing them is often costly, so they remain hidden)
- Conflict reframing (what is an interest conflict is framed as a technical disagreement or misunderstanding, hiding the adversarial structure and blocking appropriate responses)
- False consensus (suppressed disagreement appears as agreement; the conflict is hidden beneath the surface of apparent cooperation)
- Competitive intelligence dynamics (in adversarial contexts, actors strategically conceal their actual positions, capabilities, and intentions)
- Structural conflict invisibility (conflicts built into institutional or system design appear as "just how things work" rather than as contestable choices)

---

### 10. Ethics (G4 — Meaning)

**Primary analytical question:** What normative assumptions, moral claims, and questions of fairness and justice are embedded in this scenario, and which are hidden or unacknowledged?

**Core definition:** Ethics is the framework for normative analysis — identifying, surfacing, and evaluating the moral claims, ethical assumptions, and questions of fairness and justice embedded in a scenario. Distinct from Values (which descriptively maps what actors actually value) by engaging the prescriptive question of what ought to be valued and what constitutes fair, right, or just action. Covers distributive justice, procedural fairness, rights and duties, and the ethical assumptions embedded in technical and institutional designs.

**Key near-neighbour distinctions:**
- vs. Values: Values describes what actors actually hold as important (descriptive — what is valued); Ethics engages normative analysis of what ought to be valued, what is fair, what rights are at stake (prescriptive — what should be valued)
- vs. Legitimacy: Legitimacy covers whether authority is socially accepted as valid; Ethics covers whether that acceptance is warranted on moral grounds — they can diverge (legitimate but unethical; ethical but not yet legitimate)
- vs. Responsibility: Responsibility covers how accountability is assigned and distributed; Ethics covers the normative framework that should govern how responsibility is assigned and what obligations arise from it
- vs. Culture and Norms: Culture covers shared moral conventions within a group; Ethics covers the evaluation of those conventions against normative standards that may transcend group membership

**Primary hiding mechanisms:**
- Value-neutral framing (technical, legal, or procedural framing hides embedded normative choices as if they were mere facts or technical necessities)
- Ethical blind spots in design (the moral assumptions built into systems, algorithms, and policies are invisible because they were never made explicit during design)
- Distributional invisibility (who bears costs and who receives benefits is hidden in aggregate or efficiency framing — the ethical distribution question disappears)
- Procedural compliance concealing rights violations (complying with procedure hides what rights are actually at stake and whether they are being respected)
- Normalisation of harm (repeated exposure to harmful outcomes normalises them, hiding their ethical character and making moral challenge seem disproportionate)

---

### 11. Coordination (G2 — Mechanism)

**Primary analytical question:** How are actors managing or failing to manage the alignment of their actions in this scenario, and what coordination failures are hidden?

**Core definition:** Coordination analyses how multiple actors align their actions — whether through explicit mechanisms, shared conventions, market signals, hierarchical instruction, or common knowledge — and why coordination succeeds or fails. Addresses coordination problems, coordination mechanisms, and coordination costs. Distinct from Governance (formal authority structures) and Institutions (rule environment) by focusing specifically on the alignment problem itself and the variety of solutions to it.

**Key near-neighbour distinctions:**
- vs. Governance: Governance covers formal authority and decision rights; Coordination covers the alignment problem that governance is one solution to — but coordination can happen through many mechanisms (norms, markets, conventions, mutual adjustment) without formal authority
- vs. Institutions: Institutions covers the rule environment that structures behaviour; Coordination covers the dynamic process of actors actually aligning their actions, which institutions support but do not substitute for
- vs. Processes: Processes covers the flow of activities within a designed system; Coordination covers whether and how actors are managing the interdependencies between their separate processes
- vs. Relations: Relations covers the character and quality of connections; Coordination covers the functional alignment or misalignment of actions across those connections

**Primary hiding mechanisms:**
- Assumed coordination (actors assume coordination is occurring that is not — the gap between assumed and actual alignment is invisible until it produces failure)
- Silent misalignment (actors are working at cross-purposes without visible conflict because the misalignment has not yet produced a detectable failure)
- Coordination cost invisibility (the effort required to maintain coordination is absorbed by specific actors and not visible in aggregate accounts of performance)
- Failed coordination reframed as individual failure (coordination failures are attributed to individual incompetence or bad faith rather than structural coordination problems, hiding the systemic cause)

---

### 12. Space and Place (G1 — Framing)

**Primary analytical question:** How does the geographic, spatial, and place-based dimension of this scenario shape what is possible, who has access, and what is visible?

**Core definition:** Space and Place analyses how geographic location, physical spatial relationships, and the social meaning of specific places shape opportunity, access, power distribution, and visibility. Covers both objective spatial constraints (distances, terrain, infrastructure) and the social construction of place (what different locations mean to different actors, how place-based identity shapes behaviour). The spatial complement to the Time framing framework — together they establish the full spatiotemporal container for a scenario.

**Key near-neighbour distinctions:**
- vs. Time: Time covers the temporal dimension of framing; Space and Place covers the spatial dimension — they are symmetric framing frameworks. Together they establish the spatiotemporal container. Use both for full framing.
- vs. Boundaries: Boundaries covers analytical scope decisions about what is inside/outside the analysis (an analytical choice); Space and Place covers the physical and social geography of the scenario as an analytical object in its own right
- vs. Scale: Scale covers the level of analysis (micro/meso/macro, individual/system); Space and Place covers where phenomena are located and how location shapes them — distinct from the question of analytical resolution
- vs. Systems: Systems covers functional interdependencies; Space and Place covers how those interdependencies are shaped and constrained by physical geography and place-meaning

**Primary hiding mechanisms:**
- Geographic privilege blindness (actors at advantaged locations do not see the constraints faced by actors at disadvantaged locations)
- Place-based invisibility (what happens in certain locations is systematically less visible to decision-makers located elsewhere — distance creates analytic blindspots)
- Spatial displacement of costs (costs of decisions are borne in locations distant from where decisions are made, hiding the distributional impact)
- Territorial framing (how territorial boundaries are drawn determines what is in scope and what is rendered invisible — a spatial version of the Boundaries hiding mechanism)

---

### 13. Implementation (G6 — Action & Control)

**Primary analytical question:** What is happening in the gap between what was decided and what is actually being done, and what does that gap conceal?

**Core definition:** Implementation analyses the operational translation of decisions, policies, and plans into actual practice — and the gaps, distortions, resistances, and adaptations that occur in that translation. Covers sequencing, capacity, resistance, workarounds, and the political economy of execution. Distinct from Interventions (which designs the action to be taken) and Decisions (which governs the choice) — Implementation focuses on what happens during and after execution, when the decision meets operational reality.

**Key near-neighbour distinctions:**
- vs. Interventions: Interventions covers the design and specification of actions to be taken; Implementation covers what happens when those actions are actually executed — the gap between design intent and operational enactment
- vs. Processes: Processes covers how activities flow in designed systems; Implementation covers the political and operational dynamics of putting new activities into practice against existing structures, incentives, and capacities
- vs. Governance: Governance covers formal oversight and accountability structures; Implementation covers the operational reality of how those structures function in execution — where formal governance meets actual behaviour
- vs. Learning and Adaptation: Learning covers how organisations update their understanding and practice; Implementation covers the execution mechanics that determine whether intended change actually takes hold at all

**Primary hiding mechanisms:**
- Compliance theatre (actors perform compliance without changing underlying practice — the gap between stated and actual behaviour is hidden behind procedural conformance)
- Street-level adaptation (front-line actors adapt plans to local conditions in ways not visible to decision-makers — implementation diverges from design invisibly)
- Resistance invisibility (resistance is expressed through passive non-compliance rather than explicit opposition, making it difficult to detect or address)
- Capacity gap concealment (insufficient capacity to implement is not reported upward, producing apparent compliance with no actual execution)
- Decision-implementation drift (the gap between what was decided and what is implemented widens gradually, with each step small enough not to trigger escalation)

---

### 14. Scenarios (G6 — Action & Control)

**Primary analytical question:** What alternative futures are possible or plausible for this scenario, and what do current framings make invisible by treating one future as inevitable?

**Core definition:** Scenarios constructs and reasons across alternative possible futures — not just the most likely future but the range of plausible futures including surprising, discontinuous, and uncomfortable ones. Distinct from Risk (which estimates probability distributions over outcomes within a known possibility space) by operating where the possibility space itself is uncertain or contested. Used primarily to surface hidden assumptions about the future embedded in current analysis and planning.

**Key near-neighbour distinctions:**
- vs. Risk: Risk estimates probability distributions over known outcome types within a defined possibility space; Scenarios operates where the possibility space is itself uncertain — used when the current model of what outcomes are possible may be wrong, not just when probabilities are uncertain
- vs. Uncertainties: Uncertainties covers types and levels of uncertainty about current and future states; Scenarios uses those uncertainties productively to construct structured alternative futures that can be reasoned about collectively
- vs. Decisions: Decisions covers the choice logic at a decision point; Scenarios frames the future contexts in which decisions will play out — the alternative futures across which decisions should be tested for robustness
- vs. Learning and Adaptation: Learning covers how understanding updates based on experience; Scenarios covers how to reason about futures before experience is available — anticipatory rather than retrospective

**Primary hiding mechanisms:**
- Future-as-continuation bias (treating the most likely near-term future as the only future, hiding discontinuities, tipping points, and structural change)
- Scenario selection bias (scenarios are constructed to confirm existing strategy rather than challenge it — the challenging scenarios are not built)
- Normalcy bias (scenarios including discontinuous change are dismissed as extreme, hiding the genuine possibility of radical change)
- Single-future framing (planning around one future makes the full range of actual possibilities invisible and produces fragility)
- Hidden assumptions about what is possible (scenarios reveal that what is treated as impossible or inevitable is actually a choice — current framings embed these assumptions invisibly)

---

## Instructions for New Session

1. Read this brief in full before beginning any work
2. Confirm current folder state with `ls` to verify source files are present
3. For Phase 1: read the current MRT and the first 300 lines of the Operating Guide to orient before spawning sub-agents
4. Spawn Opus sub-agents for each Phase 1 deliverable in order (MRT update first, then LLMET, then LLM-Only OG)
5. Save outputs to the workspace folder with the naming conventions above
6. Do not begin Phase 2 until all three Phase 1 deliverables are complete and reviewed

---

*Brief prepared from planning conversation of 2026-04-08. All decisions reflect that conversation.*
