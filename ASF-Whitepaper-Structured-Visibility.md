# The Analytical Series of Frameworks: A Structured Methodology for Discovering Hiddens in Complex Scenarios

**Working Paper — April 2026**

---

## Abstract

Complex failures — in organisations, infrastructure, governance, and socio-technical systems — are driven less by a lack of intelligence than by structured invisibilities: realities that are hidden from relevant actors by identifiable mechanisms. Existing investigative methodologies address fragments of this problem. The Rumsfeld Matrix classifies knowledge states but provides no tools for changing visibility conditions. The Swiss cheese model identifies layered defences but not what hides latent conditions from view. The principal-agent framework addresses strategic information asymmetry but not systemic or ontological invisibility. None offers a comprehensive, mechanism-based taxonomy of hiding, a multi-lens coverage model that prevents single-framework closure, or a protocol designed for execution with large language models.

This paper introduces the Analytical Series of Frameworks (ASF), a structured analytical toolkit of 50 frameworks organised into six groups, designed to discover, uncover, and understand *hiddens* — visibility failures caused by identifiable mechanisms — in social, socio-technical, and technical scenarios. The paper defines the concept of hiddens and distinguishes it from the more familiar notion of "unknowns"; describes the ASF's architecture, including its 3-tier document system and supporting instruments; explains how the ASF is used by analysts working alone, with LLMs, and within the Claude Cowork environment; and describes the ASF's self-validation methodology, in which LLMs generate test scenarios with planted hiddens to identify gaps in the framework's own analytical coverage. A worked example demonstrates the ASF applied to a healthcare system failure, showing how cross-framework analysis surfaces hiding mechanisms that no single investigative lens would reveal.

---

## 1. Introduction: The Problem of Structured Invisibility

When complex systems fail, the post-mortem almost invariably reveals that the critical information was available somewhere — in a log, a report, a complaint, a near-miss record — but was not visible, not legible, not shareable, or not acted upon in time. The 2008 financial crisis, the Boeing 737 MAX disasters, the Grenfell Tower fire, the repeated failures of healthcare patient safety systems: in each case, investigations found not an absence of data but a failure of visibility. Signals were present but unprocessed. Metrics were tracked but distorted. Warnings were issued but suppressed. Patterns were emergent but invisible at the scale where decisions were made.

These are not random failures. They are produced by identifiable mechanisms: incentive structures that suppress reporting, measurement systems that distort what they claim to represent, narrative closure that makes anomalies invisible, boundary choices that exclude the relevant variables, legacy constraints that persist after their original rationale is forgotten, and conceptual frameworks that cannot represent what they have not yet imagined. The Analytical Series of Frameworks calls these structured visibility failures *hiddens*.

The distinction between a hidden and a mere unknown is foundational. An unknown is a knowledge state: the analyst does not yet know X. A hidden is a visibility condition: under current constraints, X is not reliably observable, inspectable, or measurable for the relevant observer, due to identifiable mechanisms. The difference is operational. An unknown calls for retrieval — research, access requests, data collection. A hidden calls for visibility redesign — changing the measurement, governance, or conceptual conditions that prevent reliable seeing. Treating hiddens as unknowns leads to the default response of "collect more data," which fails precisely when the system structure prevents reliable seeing regardless of data volume.

This paper introduces the ASF as a new contribution to the field of structured analytical investigation. It explains the ASF's architecture and operational use, positions it against existing approaches to investigating unknowns and invisibility, describes its integration with large language models as investigative partners, and presents its self-validation methodology. The purpose is to give prospective users — analysts, investigators, researchers, and decision-makers — a complete understanding of how the ASF and its supporting documents are used to discover, uncover, and understand hiddens in any given scenario.

---

## 2. Background: Existing Approaches to Investigating Unknowns and Hiddens

The problem of structured invisibility is not new. Multiple disciplines have developed frameworks for thinking about what is not known, what is hidden, and why investigations miss what matters. The ASF draws on this intellectual heritage while addressing gaps that no single existing approach fills. This section surveys the principal existing methodologies and identifies what remains unaddressed.

### 2.1 The Rumsfeld Matrix and Epistemic Categorisation

The most widely cited framework for reasoning about unknowns is the four-quadrant matrix popularised by Donald Rumsfeld in 2002, though the concepts had been in use within US defence procurement since the late 1960s. The matrix classifies information into known knowns (things we know we know), known unknowns (gaps we have identified), unknown unknowns (things we do not know we do not know), and — as Slavoj Žižek added — unknown knowns (things we know but refuse to acknowledge). The matrix is valuable as a first-order epistemic categorisation. It forces analysts to admit that their knowledge has boundaries and that some of those boundaries are themselves invisible. Its widespread adoption in strategic planning, risk management, and intelligence analysis testifies to its intuitive power.

However, the Rumsfeld Matrix classifies *states of knowledge* without providing mechanisms for *why* things are unknown or tools for *how* to change visibility conditions. It tells the analyst that unknown unknowns exist but offers no taxonomy of the mechanisms that produce them, no protocol for detecting them, and no remediation strategy beyond general vigilance. The ASF goes further by asking not merely "is this known?" but "what mechanism is hiding it, by what causal pathway, and what would change the visibility conditions?" Where the Rumsfeld Matrix provides a 2×2 epistemic map, the ASF provides a 30-type taxonomy of hiding mechanisms, a five-dimensional profiling system, and an operational detection and remediation protocol.

### 2.2 The Johari Window and Positional Blind Spots

The Johari Window, developed by Joseph Luft and Harrington Ingham in 1955, models awareness using four quadrants: the open area (known to self and others), the blind spot (known to others but not to self), the hidden area (known to self but concealed from others), and the unknown area (unknown to both). The model's contribution lies in its recognition that visibility is positional — what is visible depends on who is looking — and that blind spots and deliberate concealment are structurally distinct phenomena requiring different responses. Expanding the open area requires different strategies depending on whether the barrier is a blind spot (requiring feedback) or a hidden area (requiring disclosure).

The Johari Window's limitations for analytical investigation are its interpersonal scope and its lack of mechanism specificity. It was designed for self-help and group dynamics, not for investigating systemic failures or socio-technical scenarios. It does not address the mechanisms by which systems — as distinct from individuals — produce and maintain invisibility, nor does it provide a detection or remediation protocol. The ASF's Category V (Relational Hiddens) addresses the positional dynamics the Johari Window identifies, but extends them from interpersonal awareness to multi-actor, multi-scale systems, and integrates them within a comprehensive taxonomy that also covers perceptual, systemic, informational, temporal, and ontological hiding mechanisms.

### 2.3 Agnotology and the Production of Ignorance

Robert Proctor's concept of agnotology — the study of culturally produced ignorance — provides a critical lens on how ignorance is not merely the absence of knowledge but an actively manufactured product. Agnotology examines how industries, institutions, and political actors create doubt, suppress evidence, amplify noise, and construct narratives that prevent understanding. The tobacco industry's decades-long campaign to manufacture uncertainty about the health effects of smoking is the canonical case. Agnotology demonstrates that some hiddens are not accidental but adversarial: they are produced by agents who benefit from others' inability to see clearly.

The ASF's Category III (Informational Hiddens) directly addresses agnotological territory, with types including Secrets (intentional withholding), Echoes (amplification without independence), Noise (signal corruption), Fragmentation (distributed information that cannot be integrated), and Latency (information that arrives too late). But the ASF extends beyond agnotology's focus on deliberate manufacture. It recognises that ignorance is also produced structurally (by systems, models, and measurement regimes), temporally (by legacy, forgetting, and projection), relationally (by position and scale), and ontologically (by the limits of current conceptual frameworks). The ASF's agency dimension — which scores each hidden from Natural through Accidental, Negligent, and Deliberate to Adversarial — captures the full spectrum from innocent systemic failure to active deception.

### 2.4 Accident Investigation: The Swiss Cheese Model and Systemic Failure Analysis

James Reason's Swiss cheese model of accident causation, developed in 1990, likens organisational defences to slices of Swiss cheese with randomly distributed holes. An accident occurs when holes in multiple defensive layers momentarily align, permitting a hazard trajectory to pass through. The model distinguishes active failures (unsafe acts directly linked to the accident) from latent conditions (systemic weaknesses that lie dormant until activated). It has been enormously influential in aviation, healthcare, nuclear safety, and engineering, and its core insight — that accidents result from systemic alignment failures, not single root causes — remains foundational.

The Swiss cheese model's limitation, from a hiddens perspective, is that it describes the mechanics of defensive failure but does not systematically address what *hides* the latent conditions from view before the accident. Why were the holes in the cheese not visible? What mechanisms prevented the organisation from seeing the alignment risk? The model's layer metaphor is essentially one-dimensional (depth of defence) and does not capture the multi-mechanism, multi-dimensional nature of visibility failure. The ASF is designed to work both prospectively (before failure) and retrospectively (after failure), and its 30-type taxonomy provides the granularity needed to classify the specific hiding mechanisms that allowed latent conditions to persist undetected. Where Reason's model asks "how did the defences fail?", the ASF asks "what prevented the organisation from seeing that the defences had holes, and what mechanisms sustained that invisibility?"

### 2.5 The Principal-Agent Problem and Information Asymmetry

Economics provides the principal-agent framework for analysing situations where one party (the agent) acts on behalf of another (the principal) under conditions of information asymmetry. The framework identifies two specific types of structured hiddenness: hidden information (adverse selection — the agent has characteristics the principal cannot observe) and hidden action (moral hazard — the agent takes actions the principal cannot monitor). Solutions include incentive alignment, monitoring, signalling, and screening. The framework's contribution is its rigorous analysis of how rational self-interest, combined with information asymmetry, produces predictable patterns of concealment and distortion.

The ASF incorporates principal-agent dynamics within its treatment of G3 (Agency) frameworks — particularly Incentives, Power, and the new Interests and Conflict frameworks — and within Category III (Informational Hiddens, especially Secrets and Distortion). But it extends well beyond the bilateral, rational-actor assumptions of classical principal-agent theory. The ASF addresses hiddens that arise from cognitive limits (Category I — Perceptual), systemic measurement distortion (Category II — Systemic), historical legacy and forgetting (Category IV — Temporal), emergent properties invisible at any single scale (Category V — Relational), and conceptual boundaries that prevent the question from being formulated (Category VI — Ontological). These are not addressed by the economics of information asymmetry.

### 2.6 Systems Thinking and Complexity Science

The systems thinking tradition — from Peter Senge's mental models and learning disabilities, through Donella Meadows' leverage points, to John Sterman's system dynamics — provides essential intellectual infrastructure for understanding how feedback loops, delays, nonlinear interactions, and emergence produce unintuitive behaviour and confound conventional investigation. Meadows' observation that the most powerful leverage points in a system are often the least visible is a direct statement about structured hiddenness. Sterman's demonstration that mental models systematically misrepresent dynamic complexity explains why analysts can be confident and wrong simultaneously.

The ASF incorporates these insights through its G2 (Mechanism) group, which includes frameworks for Systems, Processes, Causation, Resources, and — new in the expanded 50-framework series — Emergence, Networks, Technology, Institutions, and Coordination. The ASF's treatment of systemic hiding mechanisms (Category II — Systemic Hiddens) and relational/scalar invisibility (Category V — Relational Hiddens) draws directly on complexity science. But systems thinking alone does not provide a comprehensive visibility governance layer. It explains *how* systems produce unexpected outcomes but does not offer a taxonomy of *what* is hidden, a protocol for *detecting* specific hiding mechanisms, or a closure discipline that makes residual hiddenness explicit. The ASF wraps systems thinking insights within a structured operational framework designed for repeatable investigation.

### 2.7 Synthesis: What Is Missing

Each of the approaches reviewed above captures a genuine slice of the hiddenness problem. The Rumsfeld Matrix provides epistemic categorisation; the Johari Window contributes positional awareness; agnotology addresses manufactured ignorance; the Swiss cheese model reveals layered defensive failure; principal-agent theory analyses strategic concealment; and systems thinking illuminates dynamic complexity. No analyst who ignores these traditions will see clearly.

But none of these approaches, alone or in combination, provides all five of the elements required for a comprehensive investigation of structured invisibility: (a) a mechanism-based taxonomy that classifies *how* things are hidden, not merely *whether* they are known; (b) a multi-lens coverage model that prevents the false confidence of single-framework closure; (c) a detection and remediation protocol that converts classified hiddens into actionable investigation moves; (d) a reflexive self-application discipline that turns the framework's own visibility assumptions into objects of investigation; and (e) a structured interface for LLM-assisted execution that makes the framework scalable, repeatable, and auditable. The Analytical Series of Frameworks is designed to provide all five.

---

## 3. Defining Hiddens: The Central Concept

The concept of *hiddens* is the organising principle of the entire Analytical Series. This section provides a formal treatment, building on the distinction introduced in Section 1 and the comparative context established in Section 2.

### 3.1 Operational Definition

A hidden is defined as: *a reality-relevant factor whose presence, structure, or implications are not available to the analyst or agent in the relevant moment, due to identifiable hiding mechanisms*. Three elements of this definition are load-bearing. First, "reality-relevant" anchors the concept to factors that matter for the decision, investigation, or situation at hand — not all information gaps are hiddens. Second, "not available ... in the relevant moment" specifies that hiddenness is temporal and contextual: a factor may be visible at one time and hidden at another, visible to one actor and hidden from another. Third, "identifiable hiding mechanisms" is the distinguishing feature: a hidden is not merely absent from awareness but is made unavailable by a causal process that can, in principle, be named, classified, and acted upon.

### 3.2 The Foundational Guardrail: Hidden Does Not Equal Unknown

The single most important conceptual discipline in the ASF is the distinction between a hidden and an unknown. An unknown is a knowledge state — the analyst does not yet know X. A hidden is a visibility condition — the system structure prevents reliable observation of X, regardless of effort, unless the visibility conditions are changed. This is not a philosophical nicety; it determines the entire response posture.

When a factor is merely unknown, the correct response is retrieval: research, access requests, direct measurement, document discovery. When a factor is hidden, retrieval alone will fail because the system structure — the measurement regime, the incentive architecture, the boundary definitions, the conceptual apparatus — prevents reliable seeing. The correct response is visibility redesign: changing the instrumentation, governance, incentives, or conceptual framework that produces the invisibility. A KPI that is reported every quarter may appear "known," but if the underlying reality is systematically distorted by Goodhart effects, selection bias, and boundary mis-specification, the number exists while trustworthy visibility does not. The ASF classifies this as a hidden (specifically, a Distortion — Type 6 in the taxonomy), not as an unknown.

Collapsing this distinction turns the ASF into a generic information-gathering method ("collect more data") and destroys its function as a visibility governance layer. The operational test is simple: if the missing information is readily accessible with ordinary effort, it is primarily unknown — retrieve it. If the system prevents reliable observation even with effort, or yields systematically biased signals, it is hidden — change the visibility conditions.

### 3.3 The Six Meta-Categories

The ASF's taxonomy of hiddens is organised into six meta-categories, each corresponding to a fundamentally distinct family of hiding mechanisms. They are ordered by increasing epistemic difficulty and decreasing eliminability:

Category I, Perceptual Hiddens, addresses failures at the interface between reality and awareness. These include blindspots (real signals not observed despite availability), hallucinations (false patterns asserted without underlying reality), inattention (signals within the field of view but not cognitively processed), saturation (critical cues submerged by volume), and habituation (persistent conditions that cease to be noticed). The diagnostic cue is "we didn't see it" despite the signal being present.

Category II, Systemic Hiddens, addresses distortions produced by measurement, modelling, and interpretive systems. These include distortion (systematic directional bias in methods or institutions), mirages (coherent but fundamentally wrong explanatory pictures), framing effects (boundary choices that render some realities invisible), aggregation (summaries that conceal variance and outliers), and model blindness (what the model excludes cannot be reasoned about within it). The diagnostic cue is that conclusions depend heavily on methods and framing.

Category III, Informational Hiddens, addresses failures in information channel structure. These include secrets (intentional withholding), echoes (prominence through repetition rather than validity), noise (true signals obscured by irrelevant or false information), fragmentation (the complete picture exists nowhere), and latency (information that arrives too late). The diagnostic cue is information asymmetry and unreliable provenance.

Category IV, Temporal Hiddens, addresses hiding mechanisms rooted in history and time. These include shadows (uncomfortable truths maintained by denial), ghosts (legacy constraints that persist after original rationale is forgotten), amnesia (knowledge once held but lost), projection (future misread because it is assumed to resemble the present), and anachronism (present reality forced into outdated categories). The diagnostic cue is conspicuous non-discussion and path dependency.

Category V, Relational Hiddens, addresses visibility failures produced by position, connection, and scale. These include positional blindness (visibility contingent on network position), scalar invisibility (phenomena visible only at different levels of analysis), emergent invisibility (system properties not inferable from parts), contextual loss (meaning destroyed by isolation), and perspectival limits (systematic invisibility from a given viewpoint). The diagnostic cue is that different stakeholders perceive incompatible realities.

Category VI, Ontological Hiddens, addresses the limits of conception and knowability themselves. These include unknown unknowns (phenomena for which no conceptual slot exists), unknowables (inherently unpredictable or irreducible phenomena), paradigm boundaries (phenomena that sit outside the current framework of understanding), category absences (existing instances that cannot be classified with available typologies), and the ineffable (phenomena that are experientially real but cannot be articulated). The diagnostic cue is persistent anomaly with no available category, or consistent predictive failure.

### 3.4 The Five Cross-Cutting Dimensions

Every hidden instance, regardless of its meta-category, can be profiled along five dimensions that determine how it should be investigated and what response it warrants. The *mechanism* dimension identifies the causal pathway (absence, false presence, distortion, concealment, or boundary). The *reducibility* dimension assesses whether the hidden can be eliminated, reduced, managed, or only accepted (ranging from eliminable to irreducible). The *detectability* dimension assesses ease of surfacing (from obvious to invisible). The *agency* dimension identifies whether the hidden arises naturally, accidentally, negligently, deliberately, or adversarially. And the *consequence* dimension assesses severity if the hidden persists (from negligible to catastrophic). These five dimensions prevent one-dimensional response: a hidden that is detectable but irreducible calls for robustness, not investigation; a hidden that is adversarial and high-consequence calls for protective measures, not just measurement redesign.

### 3.5 Why Hiddens Are Central to the ASF

The Framework of Hiddens is not one framework among fifty. It is the backbone discipline of the entire series — the canonical visibility layer that governs the reliability of every other framework's output. Every framework in the ASF includes a mandatory Hiddens cross-check (Section 8 of every framework document) that asks: what visibility failures might undermine this framework's conclusions? This design is bidirectional. In the forward direction, other frameworks surface candidate hiddens through their analytical work — an incentive analysis may reveal reporting suppression, a boundary analysis may reveal excluded variables, a narrative analysis may reveal premature closure. In the backward direction, the Framework of Hiddens validates and governs these outputs by classifying what is hidden, why, and what detection and remediation moves are warranted.

This reflexive architecture means the ASF is, by design, self-questioning. It does not claim to see everything; it claims to make its residual blindness explicit, governable, and auditable. The highest-order test of the ASF — the meta-validation test described in Section 7 — applies the framework to itself, asking: what hiddens exist in this framework's own approach to finding hiddens?

---

## 4. The Architecture of the ASF

### 4.1 Fifty Frameworks, Six Groups

The ASF comprises 50 analytical frameworks organised into six groups, each providing a distinct analytic function. G1 (Framing) establishes the investigation container: what situation is this, what are its boundaries, what scales and time horizons apply, what realities and dimensions are relevant. Its eight frameworks — Situations Context Classification, Boundaries, Dimensions, Realities, Scale, Time, Space and Place, and Scenarios — ensure that the problem is correctly scoped before analysis begins. G2 (Mechanism) models structure and propagation: how the system works, what depends on what, how failure spreads, what emerges from interaction. Its nine frameworks — Systems, Relations, Processes, Causation, Resources, Emergence, Networks, Technology, Institutions, and Coordination — provide the structural backbone. G3 (Agency) identifies who acts, why, with what power, and under what constraints. Its nine frameworks — Agents, Personas, Incentives, Power, Responsibility, Competencies, Cognition, Interests, Emotions, and Conflict — map the human and organisational dynamics that drive both action and concealment. G4 (Meaning) explains how norms, narratives, legitimacy, and communication shape what can be seen, said, and done. Its eight frameworks — Culture and Norms, Perspectives, Narratives, Communications, Legitimacy, Values, Ethics, and Trust — capture the interpretive layer. G5 (Epistemics) controls evidence quality, uncertainty, failure patterns, and visibility itself. Its eight frameworks — Beliefs, Evidence, Uncertainties, Failures, Hiddens, Diagnosis, Metrics, and Knowledge — are the series' self-correcting epistemic machinery. G6 (Action and Control) converts understanding into decisions, interventions, governance, risk treatment, and learning. Its six frameworks — Decisions, Interventions, Governance, Risk, Learning and Adaptation, and Implementation — ensure that analysis leads to action with appropriate controls.

The group system is a coverage model, not a taxonomy of reality. Its purpose is to prevent single-lens closure — the false confidence that comes from seeing clearly through one analytic lens while remaining blind through others. Every investigation is required to touch all six groups at minimum at Light Depth, with selected groups receiving Full Depth treatment based on routing logic. This ensures that an investigation does not, for example, produce a thorough causal model (G2) while ignoring the incentive structures that suppress reporting (G3) or the narratives that make anomalies invisible (G4).

### 4.2 The Three-Tier Document Architecture

Each of the 50 frameworks exists in three documentary forms, designed for different users and contexts. This architecture solves a practical problem: individual framework documents average approximately 25,000 tokens each. Loading multiple full documents simultaneously into an LLM's context window for execution is impractical within current limits.

Tier 1 consists of the Full Framework Documents — comprehensive, human-readable reference documents of approximately 25,000 tokens each. These contain the complete taxonomy of types, dimensions, dynamics, interfaces, crosswalk with all other frameworks, Hiddens source analysis and cross-check, and application protocol. They are produced using the Master Rewrite Template (MRT), which standardises structure across all 50 frameworks: six meta-categories, five types per category (30 core types), five cross-cutting dimensions, dynamic patterns, three interface types, and a mandatory Hiddens cross-check. These documents serve human analysts and provide the source material from which the other tiers are derived.

Tier 2 consists of LLM Execution Extracts — compact operational interfaces of approximately 5,000 to 8,000 tokens each. These are designed to be loaded into an LLM's context at runtime alongside the LLM-Only Operating Guide. Each extract contains an operational definition, a near-neighbour disambiguation table (distinguishing this framework from its closest relatives), a condensed taxonomy, condensed dynamics, compact Hiddens cross-check prompts, an LLM execution protocol, and cross-framework routing pointers. The extracts are produced using the LLM Execution Extract Template (LLMET), which defines eight mandatory sections. This tier makes simultaneous multi-framework execution feasible: a system prompt plus the LLM-Only Operating Guide plus four extracts consumes approximately 80,000 to 120,000 tokens, well within current context window limits.

Tier 3 consists of Operating Guides — the series-level orchestration doctrine. There are two versions: the Full Operating Guide (approximately 240,000 tokens), which provides the complete human-readable doctrine including routing logic, protocols, quality controls, and governance; and the LLM-Only Operating Guide (approximately 20,000 tokens), a compact execution adapter that strips all narrative prose and retains only operational tables, pseudocode, decision logic, and terse definitions. The LLM-Only Operating Guide is the runtime companion loaded alongside Tier 2 extracts during LLM execution.

### 4.3 The Supporting Instruments

Three additional instruments complete the ASF's operational infrastructure. The Operating Guide provides the routing decision tree that converts scenario features into a minimum group coverage plan with Full Depth and Light Depth allocations. It defines three protocols (Rapid, Post-Failure, and Proactive), the iterative investigation loop, the tiered Hiddens scan model, thirteen targeted Hiddens discovery scans, prompt discipline rules, the output contract specifying required artefacts, and closure discipline.

The Master Rewrite Template provides the structural standard that every framework document conforms to. It enforces the canonical architecture of 30 types across six meta-categories, five dimensions, dynamics, interfaces, and the mandatory Hiddens cross-check. This ensures structural consistency across all 50 frameworks and makes cross-framework analysis reliable.

The HTML Companion Compact Decision Tree provides a machine-navigable version of the routing decision tree with eight nodes, preconditions, actions, outputs, and successor pointers. It enables an LLM to traverse the routing logic programmatically during execution, reducing the risk of routing errors in complex scenarios.

### 4.4 The Operating Rhythm

The ASF operates through a single iterative loop, used across all run modes: Initialise (establish case question, boundaries, and discipline), Generate (produce initial candidate hiddens via Tier 1 scan), Route (select minimum group coverage and depth plan), Execute (run selected frameworks), Test (convert unknowns into probes with discriminating tests), Re-scan (re-run the Tier 1 Hiddens scan with updated knowledge), and Decide (close with explicit residual hiddenness, or escalate). This loop enforces two critical disciplines. First, the Tier 1 Hiddens scan is required at least twice — early (before the analytical momentum of framework execution creates false confidence) and pre-closure (to catch what the analysis itself may have introduced or missed). Second, closure is never silent: it requires explicit residual unknowns, an acceptability rationale, a monitoring plan, ownership, and a learning hook.

Two run modes govern timebox and depth. Rapid Run Mode (60 to 180 minutes) is coverage-first and stabilisation-oriented: scan all groups lightly, target depth where initial signals warrant, and produce a prioritised action list. Investigative Run Mode (days to weeks) provides selective depth on routed frameworks with evidence-gated closure: multiple loop iterations, expanded testing, and comprehensive register population. Within either mode, individual frameworks are executed at Full Depth (populate core tables, develop mechanisms, expand tests) or Light Depth (scan-level, high-signal candidates only), as determined by the routing decision tree.

---

## 5. Using the ASF as an Investigative Tool

### 5.1 The Analyst Working Alone

A human analyst using the ASF follows the iterative loop described in Section 4.4, guided by the Full Operating Guide. The analyst enters with a scenario — a failure to investigate, a decision to inform, a risk to assess — and begins by framing the situation using G1 frameworks to establish boundaries, scale, time horizon, and context classification. Before proceeding to detailed analysis, the analyst runs the Tier 1 Hiddens scan: a six-category visibility audit that asks, for each meta-category, whether there are signals of hidden perceptual gaps, systemic distortions, informational pathologies, temporal residues, relational blindness, or ontological limits. This scan is deliberately early because the ASF's central discipline is to assume hiddens exist and look for them before the analytical momentum of framework execution creates premature confidence.

The analyst then consults the routing decision tree, which converts observable scenario features into a minimum group coverage plan. If a failure has occurred, evidence is contested, and incentive structures may distort reporting, the tree routes the analyst to deep execution of G1, G2, G3, and G5, with G4 and G6 at light or deep depending on narrative contestation and governance implications. The analyst works through the routed frameworks, populating the standard registers — the Hiddens Register (candidate hiddens with their type, mechanism, detectability, agency, consequence, and owner), the Evidence Ledger (claims with supporting and contradicting evidence, quality assessments, and gaps), and the Hypothesis/Test Backlog (unknowns converted into probes with discriminating tests). Every claim is tagged F (Fact — verified with evidence), I (Interpretation — inference from evidence), A (Assumption — taken as given but unverified), or U (Unknown — gap requiring investigation).

The anti-theatre rule operates throughout: no major claim survives without an evidence base, an uncertainty statement, a hiddenness check, and an assigned owner. This prevents the common failure mode of investigations that produce confident narratives unsupported by adequate evidence — what the ASF calls "findings theatre."

At pre-closure, the analyst re-runs the Tier 1 scan with updated knowledge, checks whether the investigation has introduced new hiddens or revealed classes of hiddenness missed in the initial scan, and produces closure artefacts: explicit residual unknowns (what remains hidden and why), an acceptability rationale (why proceeding is justified given the stakes), a monitoring plan (what signals would change the conclusion), ownership (who watches and who acts), and a learning hook (when and how the case will be revisited).

### 5.2 The Analyst Working with an LLM

The ASF's 3-tier document architecture is specifically designed for LLM-assisted analysis. The analyst-LLM partnership model is asymmetric: the LLM executes the protocol, the analyst provides scenario knowledge, judgment, and quality control. This division leverages the LLM's strengths — systematic protocol adherence, comprehensive taxonomy traversal, consistent register population, and the ability to hold and traverse large structured documents — while retaining the human analyst's domain expertise, contextual judgment, and ability to validate claims against ground truth.

In practice, the analyst loads the LLM-Only Operating Guide and the relevant Tier 2 extracts (typically four to six frameworks selected by routing) into the LLM's context. The analyst provides the scenario description, constraints, and available evidence. The LLM executes the iterative loop: running the Tier 1 scan, applying the routing decision tree, executing the routed frameworks at the appropriate depth, populating the standard registers with F/I/A/U tagging, generating discriminating tests for unknowns, and producing closure artefacts. The prompt discipline rules (PD-01 through PD-10) enforce output quality: no claims without provenance, no premature closure, no conflation of interpretation with fact, explicit residual unknowns in every output.

The LLM's output is not a finished investigation. It is a structured first draft — a disciplined analytical scaffold that surfaces candidate hiddens, proposes detection moves, and makes its assumptions explicit. The analyst reviews, validates against domain knowledge, challenges the F/I/A/U tagging, identifies where the LLM has treated assumptions as facts or missed contextual nuance, and iterates. This human-in-the-loop design is deliberate: the ASF does not trust any single analytic agent (human or machine) to see clearly alone.

### 5.3 The LLM as Investigative Partner in Claude Cowork

Claude Cowork provides a particularly effective environment for ASF execution because of three capabilities that align with the ASF's architectural requirements. First, the persistent document repository: Cowork allows the analyst to store all 50 framework documents, all 50 LLM execution extracts, both operating guides, the Master Rewrite Template, and the Compact Decision Tree in a workspace folder that persists across sessions. This means the LLM can read any source document at execution time, enabling Full Depth framework execution when the Tier 2 extracts need to be supplemented with the complete taxonomy from a Tier 1 document.

Second, the sub-agent architecture: Cowork can spawn specialised sub-agents with different model configurations for different tasks. The ASF's model routing strategy uses this capability deliberately — Opus-class models for intellectually demanding tasks like authoring new frameworks, designing templates, and making complex architectural decisions; Sonnet-class models for mechanical tasks like batch updates, extract generation from existing documents, and register population. This matches the ASF's own distinction between work requiring deep analytical synthesis and work requiring consistent protocol execution.

Third, the iterative session model: ASF investigations are rarely completed in a single conversation. Cowork's persistent workspace means that an analyst can conduct a Rapid Run Mode investigation in one session, review the outputs, and return in a subsequent session for Investigative Run Mode deepening — with all prior artefacts (Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog) available for continuation. The LLM reads the prior session's outputs and picks up the investigation where it left off, maintaining register continuity and analytical coherence across sessions.

The analyst-Cowork workflow for a typical ASF investigation proceeds as follows. The analyst provides the scenario description and available evidence. Cowork loads the LLM-Only Operating Guide and executes mode selection and routing. The analyst reviews and adjusts the routing plan. Cowork loads the relevant Tier 2 extracts, executes the routed frameworks, and populates the registers. The analyst reviews the Hiddens Register, challenges the F/I/A/U tagging, and provides additional domain knowledge. Cowork re-runs the Tier 1 scan, produces closure artefacts or identifies where escalation is needed. The analyst makes the final closure or non-closure decision.

---

## 6. Validation: Testing the ASF with LLM-Generated Scenarios

### 6.1 The Core Problem: Testing a Visibility Instrument

Testing whether a framework reliably finds invisible things poses an epistemological challenge: you cannot straightforwardly test an instrument for finding what is invisible by looking for what is visible. If the test scenarios contain only visible issues, a framework that misses hiddens will still appear to work. If the test scenarios are real-world cases, the true set of hiddens is itself unknown (that being the nature of hiddens), so there is no reference answer against which to score.

The ASF resolves this through a planted hiddens methodology: scenarios are constructed with deliberate hiddens at known locations, types, and mechanisms. A reference answer specifies exactly what the ASF is expected to find. A separate LLM instance runs the ASF blind — without access to the reference answer — and the output is scored against it. This creates a controlled experiment in which the independent variable is the ASF's analytical machinery and the dependent variable is its ability to surface the planted hiddens.

### 6.2 The Test Architecture

The ASF's test protocol defines three test types, each addressing a different analytical capability. Unit Tests present scenarios in which one specific framework is the critical lens for finding a planted hidden. The pass criterion is that the correct framework activates, the hidden is classified with the correct mechanism type, and at least one discriminating detection probe is proposed. Integration Tests present scenarios in which no single framework is sufficient — two or more frameworks must be combined and their outputs connected. These test the ASF's ability to avoid single-lens closure, the very failure mode the group system is designed to prevent. The pass criterion is that the routing selects the required frameworks, the cross-framework connection is made explicit, and the hidden is surfaced in the combined output rather than missed in the gaps between framework outputs.

The most structurally important test is the Meta-Validation Test, in which the ASF is given a description of itself as the scenario. The question is: what hiddens exist in this framework's approach to finding hiddens? This tests reflexivity — the ASF's ability to turn its analytical machinery on its own assumptions, boundaries, and blind spots. The pass criterion requires identification of at least one hidden in each of the six groups, classification using the 30-type taxonomy, and production of a non-defensive residual unknowns log. This test operationalises the reflexive discipline described in Section 3.5: the ASF does not claim immunity from the visibility failures it is designed to surface.

Every test is scored on five dimensions: coverage (was the planted hidden found?), mechanism accuracy (was the hiding mechanism correctly classified?), framework routing (was the correct framework activated?), detection probe quality (was a discriminating probe proposed — one that would produce different results if the hidden exists versus if it does not?), and remediation quality (was a mechanism-specific, actionable remediation proposed?). A maximum score of 10 per hidden, with a pass threshold of 7 out of 10, provides a quantitative measure of analytical capability that can be tracked across versions, configurations, and test scenarios.

### 6.3 The Role of the LLM in Validation

The LLM serves dual roles in the validation process: scenario constructor and test executor. As constructor, the LLM generates scenarios from a coverage matrix that ensures all 50 frameworks are exercised across the test bank, with planted hiddens designed to require specific frameworks and specific mechanism classifications. As executor, a separate LLM instance (with no access to the reference answers) runs the ASF protocol against each scenario and produces the standard registers. The scoring is then performed against the planted hiddens reference.

This creates a scalable, repeatable test infrastructure that a human analyst alone could not sustain. The coverage matrix can be extended as the ASF expands, new scenarios can be generated to test specific failure modes, and regression testing (re-running the full test bank after framework modifications) can be automated. The planted hiddens methodology also provides a precision control: the test protocol tracks false positives (hiddens identified by the ASF that are not in the reference answer and not evidenced from the scenario text). Each false positive deducts from the test score, preventing inflation through over-identification. Hiddens that are not in the reference answer but are well-evidenced from the scenario text are flagged as bonus findings, rewarding genuine analytical discovery beyond the planted set.

### 6.4 Identifying Gaps and Driving Improvement

Test results feed directly into the ASF's development cycle. When a planted hidden is missed, the failure analysis asks: was the correct framework available? Did the routing logic select it? Was the taxonomy adequate to classify the mechanism? Was the detection heuristic sufficient? Each failure mode points to a different corrective action — adding a framework, adjusting routing triggers, extending a taxonomy, or strengthening a detection protocol. When false positive rates are high for a particular framework, it indicates over-sensitivity that may need recalibration of activation thresholds.

The meta-validation test produces a qualitatively different kind of feedback. By applying the ASF to itself, it surfaces structural limitations that no external test scenario can reveal: paradigm assumptions built into the taxonomy, boundary choices that exclude relevant phenomena, cultural biases in the detection heuristics, and reflexive failures where the act of classifying hiddens introduces new ones. These findings do not "fix" the ASF in any final sense — they make its residual limitations explicit, documentable, and governable. This is consistent with the ASF's core philosophy: the goal is not omniscient visibility but disciplined, auditable visibility with explicit residual blindness.

---

## 7. Worked Example: The ASF Applied to a Healthcare Patient Safety Failure

This section demonstrates the ASF in action through a compressed walkthrough of a realistic scenario, showing how cross-framework analysis surfaces hiding mechanisms that no single investigative lens would reveal.

### 7.1 The Scenario

A regional hospital reports a sustained increase in post-surgical infection rates over eighteen months. Internal quality audits have been conducted quarterly, each finding "no systemic issues." Individual cases have been attributed to patient comorbidities and normal statistical variation. A frontline nurse has raised concerns in two staff meetings about changed sterilisation protocols following a cost-reduction programme, but the concerns were minuted as "noted" with no follow-up action. External regulators have not been notified because the hospital's reported infection rates remain within the published benchmarks. A patient death triggers an external investigation.

### 7.2 Entry and Framing (G1)

The ASF investigation begins with G1 framing. Using the Situations Context Classification framework, the analyst classifies this as a post-failure, multi-stakeholder, institutionally embedded scenario with a contested evidence base. The Boundaries framework reveals a critical framing choice: the hospital's internal audits scoped their investigation to individual clinical episodes, not to systemic process changes. This boundary excluded the cost-reduction programme from the audit scope entirely — a framing effect (Type 8 — Systemic Hidden) that rendered the causal connection invisible. The Time framework identifies an eighteen-month drift period during which gradual degradation was masked by attribution to patient-level factors. The Scale framework notes that the infection rate increase is visible at the ward level but disappears in the hospital-wide aggregate, which averages it out with lower-risk departments — an aggregation hidden (Type 9).

### 7.3 Tier 1 Hiddens Scan (Early)

Before proceeding to detailed analysis, the analyst runs the six-category visibility audit. The scan produces initial signals across five of six categories: Perceptual (the quarterly audits missed the pattern — possible habituation to gradual change), Systemic (the benchmarks may be masking a real signal through aggregation), Informational (the nurse's concern was received but not acted upon — possible fragmentation), Temporal (the cost-reduction decision created a legacy constraint now invisible to current auditors), and Relational (frontline staff see the problem; management does not — positional blindness). The scan does not initially flag Ontological hiddens, though the meta-validation discipline notes this absence as itself worth monitoring.

### 7.4 Routing

The routing decision tree takes the scenario features as input. A materially consequential failure has occurred (patient death): trigger post-failure baseline (G1 + G2 + G5 deep). Evidence is contested (internal audits contradict frontline observation): deepen Evidence, Uncertainties, Diagnosis. Incentives and power may distort reporting (cost-reduction programme creates institutional pressure against acknowledging process failures): add G3 deep. Narratives are "too clean" (the internal audit finding of "no systemic issues" despite eighteen months of rising infections): add G4 deep. Recommendations will change governance and controls: add G6 deep. The routing produces a full G1–G6 investigation with deep execution on most frameworks.

### 7.5 Cross-Framework Execution

Working through the routed frameworks, the investigation surfaces a system of interacting hiddens, not a single cause:

The Incentives framework (G3) reveals that the cost-reduction programme created institutional incentives to attribute infections to patient factors rather than process changes, because acknowledging a causal link to the programme would imply the cost reduction was a mistake — with career consequences for the managers who approved it. This is a secret (Type 11 — Informational Hidden) sustained by incentive alignment.

The Communications framework (G4) reveals that the nurse's concerns were formally received but routed through a feedback mechanism that required management endorsement before escalation. The concerns were "noted" but not forwarded — a fragmentation hidden (Type 14) in which the information existed but could not reach the decision-makers who needed it.

The Metrics framework (G5) reveals that the published benchmarks against which the hospital measured its infection rates used a calculation methodology that excluded infections manifesting more than 72 hours post-discharge. A significant proportion of the infections in question manifested at 96 to 120 hours. This is a distortion hidden (Type 6 — Systemic) produced by the measurement system itself: the metric was "known" while the underlying reality was systematically invisible.

The Evidence framework (G5) reveals that the quarterly audit methodology relied on chart review rather than independent clinical observation. Chart reviews are vulnerable to documentation practices that under-record process deviations. The audit was measuring documentation compliance, not clinical reality — a model blindness hidden (Type 10) in which the audit instrument excluded the variable it needed to detect.

The Processes framework (G2), combined with the Systems framework, reveals that the cost-reduction programme's change to sterilisation protocols was implemented through a procurement change (switching to a cheaper sterilisation solution) that was classified as a "supplies procurement decision" rather than a "clinical protocol change." This classification choice meant the change was not routed through the clinical safety review process. The system boundary between procurement and clinical governance created a structural gap through which a patient-safety-relevant change passed without clinical scrutiny — a framing hidden (Type 8) produced by institutional boundary architecture.

### 7.6 The Hidden System

The worked example illustrates a central ASF principle: hiddens rarely operate in isolation. The investigation maps a hidden system in which the incentive structure (Secret, Type 11) sustains the fragmentation (Type 14) by ensuring that frontline signals are not escalated; the metric distortion (Distortion, Type 6) provides false reassurance that makes investigation seem unnecessary; the model blindness in the audit methodology (Type 10) prevents the distortion from being detected even when audits are conducted; and the institutional framing choice (Type 8) prevented the triggering event from ever entering the clinical safety review process. Addressing any one of these hiddens without addressing the others would produce an incomplete fix. The ASF's interaction mapping (Interface Type C) makes this cascade explicit and prevents the common failure of "fixing" a visible symptom while leaving the system of hiddens intact.

### 7.7 Closure

The investigation produces closure artefacts per ASF discipline. The Hiddens Register documents twelve candidate hiddens, five classified at high consequence. The Evidence Ledger records the evidence base for each claim with F/I/A/U tagging — notably, the link between the sterilisation solution change and infection rates is tagged I (Interpretation, supported by temporal correlation and mechanism plausibility, but not yet confirmed by controlled testing). The residual unknowns log records three items: whether additional departments are affected (Unknown — requires expanded chart review with corrected methodology), whether similar procurement-to-clinical boundary gaps exist elsewhere in the hospital (Unknown — requires governance audit), and whether the published benchmark's 72-hour exclusion systematically under-counts infections nationally (Unknown — requires sector-level investigation). Each residual unknown has an owner, a monitoring plan, and a learning hook.

### 7.8 What the ASF Surfaced That Single-Lens Approaches Would Miss

A traditional root cause analysis would likely identify the sterilisation solution change and stop there — a single causal chain from procurement decision to infection increase. The ASF surfaced a *system* of hiding mechanisms that sustained the invisibility for eighteen months: incentive-driven concealment, communication pathway fragmentation, metric distortion, audit model blindness, and institutional boundary architecture. The Swiss cheese model would identify the layered defensive failures but not the specific mechanisms that kept the holes invisible. The principal-agent framework would identify the incentive misalignment but not the metric distortion or the institutional framing choice. The Rumsfeld Matrix would classify the issue as an unknown unknown but provide no tools for discovering it. The ASF's contribution is the systematic traversal of all six hiding-mechanism families, the cross-framework connection that reveals the hidden system, and the explicit residual unknowns that prevent premature closure.

---

## 8. Discussion: Contribution and Limitations

The ASF makes five claims to novelty that distinguish it from the existing approaches surveyed in Section 2.

First, it provides a mechanism-based taxonomy rather than an epistemic categorisation. Where the Rumsfeld Matrix asks "is this known?", the ASF asks "what mechanism is hiding it?" The 30-type taxonomy, organised into six meta-categories with five cross-cutting dimensions, provides a vocabulary precise enough to classify specific visibility failures and actionable enough to generate targeted detection and remediation moves.

Second, it provides a multi-lens coverage model that is enforced through the group system and routing discipline. The requirement to touch all six analytic groups before closure prevents single-lens closure — the failure mode in which thorough analysis through one lens creates false confidence while other lenses remain unexamined. This is a structural defence against the very hiding mechanism (framing, Type 8) that afflicts all analytical frameworks, including the ASF itself.

Third, it provides a detection and remediation protocol — the iterative investigation loop, the tiered Hiddens scan, the targeted discovery scans, and the standard registers — that converts classified hiddens into operational investigation moves. This protocol is table-driven, register-based, and auditable, making it repeatable across analysts, scenarios, and sessions.

Fourth, it provides a reflexive self-application discipline. The mandatory Hiddens cross-check in every framework, combined with the meta-validation test, ensures that the ASF's own visibility assumptions are objects of investigation rather than unexamined axioms. The ASF does not claim to see everything; it claims to make its residual blindness explicit.

Fifth, it provides a structured interface for LLM-assisted execution. The 3-tier document architecture, the LLM-Only Operating Guide, the prompt discipline rules, and the output contract make the ASF directly executable by an LLM, creating a scalable, repeatable investigative capability that augments human analytical judgment with systematic protocol adherence.

These claims are subject to important limitations. The ASF's taxonomy is a human-designed instrument with its own paradigm assumptions; the meta-validation test can surface but not eliminate these. The quality of ASF outputs depends on the analyst's domain expertise and the quality of available evidence — the framework systematises investigation but cannot conjure information that does not exist. The LLM-assisted execution mode introduces its own visibility risks, including the LLM's tendency toward confident completion (which the prompt discipline rules are designed to constrain but cannot fully prevent) and the risk that systematic protocol adherence creates an illusion of thoroughness. The ASF has been developed iteratively across multiple LLM platforms but has not yet been validated through formal empirical studies across diverse domains — a critical next step for establishing external validity.

---

## 9. Conclusion

Complex systems fail because important realities are hidden from the people who need to see them, by mechanisms that are themselves often invisible. The Analytical Series of Frameworks provides a structured response to this problem: a 50-framework analytical toolkit organised into six groups, supported by a tiered document architecture, an operating guide with routing and quality controls, and a reflexive self-validation methodology. Its central concept — the hidden, defined as a visibility condition produced by identifiable mechanisms, distinct from a mere unknown — provides both a vocabulary and a protocol for making structured invisibility discoverable, classifiable, and governable.

The ASF does not promise complete visibility. It promises disciplined visibility with explicit residual blindness — an investigation that knows what it has not seen, why, and what would need to change for seeing to improve. In an era when large language models can serve as analytical partners capable of systematic protocol execution across large structured document sets, the ASF offers a methodology that is both human-readable and machine-executable, designed for the emerging practice of analyst-LLM collaborative investigation.

Future work should focus on four areas: formal empirical validation across diverse domains (healthcare, finance, infrastructure, governance, technology); comparative studies measuring ASF performance against established investigation methodologies on controlled scenarios; expansion of the test protocol to include adversarial red-teaming (scenarios designed to exploit known ASF weaknesses); and continued refinement of the LLM integration as model capabilities evolve, including the development of multi-agent architectures in which different LLM instances specialise in different analytical roles within the ASF's group system.

---

## References

Luft, J. and Ingham, H. (1955). "The Johari Window: A Graphic Model of Interpersonal Awareness." *Proceedings of the Western Training Laboratory in Group Development*. Los Angeles: UCLA.

Meadows, D.H. (1999). "Leverage Points: Places to Intervene in a System." *Sustainability Institute*.

Proctor, R.N. and Schiebinger, L. (eds.) (2008). *Agnotology: The Making and Unmaking of Ignorance*. Stanford University Press.

Reason, J. (1990). *Human Error*. Cambridge University Press.

Reason, J. (1997). *Managing the Risks of Organizational Accidents*. Ashgate.

Rumsfeld, D.H. (2002). US Department of Defense News Briefing, 12 February 2002. Transcript available from the US Department of Defense.

Senge, P.M. (1990). *The Fifth Discipline: The Art and Practice of the Learning Organization*. Doubleday.

Sterman, J.D. (2000). *Business Dynamics: Systems Thinking and Modeling for a Complex World*. McGraw-Hill.

Žižek, S. (2004). "What Rumsfeld Doesn't Know That He Knows About Abu Ghraib." *In These Times*, 21 May 2004.

---

*The Analytical Series of Frameworks, its Operating Guide, Master Rewrite Template, LLM Execution Extract Template, LLM-Only Operating Guide, and Compact Decision Tree are maintained as a living document set. The current version (v3.0, April 2026) comprises 50 frameworks, 50 LLM execution extracts, and supporting instruments. For access to the complete document set or inquiries about the ASF, contact the series maintainer.*
