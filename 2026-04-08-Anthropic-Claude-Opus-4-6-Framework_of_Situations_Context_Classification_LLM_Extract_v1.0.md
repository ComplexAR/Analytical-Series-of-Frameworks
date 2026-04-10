# Framework of Situations and Context Classification – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Situations and Context Classification |
| Primary group | G1 — Framing & scope-setting (Framing) |
| Secondary group | G5 — Epistemics & error-control (Epistemics) |
| Stage | Upstream |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

A situation is a structured context in which agents perceive, decide, and act—not merely a set of facts but a configuration shaped by constraints, incentives, and time. This framework classifies situations into six meta-categories and thirty types, profiles them along five dimensions (structural order, valence, uncertainty, agency, temporality), and maps three interface types where situations interact. It populates Hiddens Register and Evidence Ledger with situation narratives, type hypotheses, dimensional profiles, and hidden-risk signatures; drives re-typing cadence and identifies transition thresholds; and surfaces framing conflicts (Hidden-8) and contextual blindness (Hidden-24) by making competing situation interpretations explicit.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Situations when… | Use neighbour instead when… |
|---|---|---|
| Time | You need to classify *what kind* of situation this is and what response mode fits. | You need to determine *how long* it will unfold or what temporal horizons constrain it (use Time). |
| Realities | You are mapping *how agents perceive and classify* the situation across roles and frames. | You need to identify *which reality-layers are misaligned* (substrate/experience/representation/institution/normativity) (use Realities). |
| Systems | You are establishing *whether to treat as routine/project/exploratory/crisis/conflict/transformational*. | You need to understand *the causal structure and feedback mechanisms* within the situation (use Systems). |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question |
|---|---|---|
| I Routine | Operational Steady State, Cyclical/Seasonal, Maintenance & Degradation Prevention, Monitoring & Early Warning, Incremental Improvement & Optimisation | Are goals, methods, and outcomes stable and recurring, requiring primarily maintenance and incremental improvement? |
| II Project/Design | Implementation & Delivery, Design & Engineering, Transition & Rollout, Scaling & Replication, Integration & Interfacing | Are goals reasonably clear but pathways require design, planning, and coordinated execution? |
| III Exploratory | Problem-Finding & Framing, Opportunity Scanning, Hypothesis-Driven Inquiry, Prototyping & Experimentation, Sensemaking Under Ambiguity | Are goals, constraints, or problem definitions unclear, contested, or evolving, requiring exploration and learning? |
| IV Crisis/Disruption | Acute Incident & Emergency, Fast-Window Opportunity, Cascade & Systemic Failure, External Shock & Discontinuity, Stabilisation & Recovery | Are volatility, time pressure, and high stakes forcing rapid action and damage limitation? |
| V Conflict/Plurality | Stakeholder Conflict, Adversarial & Competitive Interaction, Negotiation & Bargaining, Coalition-Building & Alignment, Governance & Coordination Failure | Are multiple agents, interests, and values creating contestation and mutual constraint requiring negotiation or authority? |
| VI Transformational | Strategic Inflection Point, Identity & Role Reconfiguration, Boundary Redrawing, Paradigm & Frame Shift, Situation Redesign | Are identities, boundaries, rules, or interpretive frameworks themselves in motion, requiring deliberate navigation or redesign? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Escalation & destabilisation | Routine or project contexts shift to crisis; tempo compresses; thresholds dominate. | Latent risk + trigger + depleted buffers; feedback loops amplify; attention saturates. | Misclassification delays containment; cascades follow unmanaged volatility. |
| Crystallisation from exploration | Exploratory contexts converge toward project/design as evidence accumulates and options narrow. | Uncertainty reduces; goals stabilise; governance shifts from learning to execution. | Premature delivery locks in wrong frame; endless exploration erodes legitimacy. |
| Pluralisation & politicisation | Conflicts emerge as agents contest framing, valence, and control; technical issues become political. | Distributional effects, legitimacy disputes, power asymmetries drive divergent narratives. | Ignoring plurality triggers resistance and governance failure; requires negotiation/authority. |
| Drift & chronicisation | Situation slowly shifts regime without clear trigger (e.g., manageable risk → chronic overload). | Small degradations accumulate; incentives normalise deviation; monitoring is gamed. | Delayed recognition creates brittle systems; interventions become expensive and disruptive. |
| Transformation & redesign | Identity, boundaries, frames change; situation itself becomes object of design. | Strategic inflection points, boundary redrawing, paradigm shifts reshape action space and legitimacy. | Legacy playbooks fail; lock-in dominates; coordination becomes redesign problem. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question |
|---|---|
| I Perceptual | Are salient incidents crowding out structural drift signals, creating false confidence in classification? |
| II Systemic | Are routines, dashboards, or incentives stabilising a particular preferred classification while suppressing alternative readings? |
| III Informational | Are evidence silos or gating mechanisms preventing shared ground truth on what situation we are actually in? |
| IV Temporal | Are classifications becoming stale as situations evolve, with old playbooks persisting despite regime shift? |
| V Relational | Are power-laden framing disputes suppressing dissent or alternative situation narratives? |
| VI Ontological | Are emergent or novel situations failing to fit existing categories, creating blind spots? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Framing capture (Hidden-8): situation labels foreground certain levers and hide others; frames enable/suppress actions
- Contextual blindness (Hidden-24): situation type varies by scale, agent role, temporal horizon; asymmetries go unrecognised
- Positional bias (Hidden-21): different roles and perspectives see fundamentally different situations from the same events
- Temporal drift (Hidden-7, Hidden-15): situations evolve without reclassification; old classifications persist beyond validity
- Valence myopia (Hidden-25): single lens collapses true uncertainty and distributional difference in threat/opportunity
- Misclassification cascade (Hidden-derived): wrong situation type triggers inappropriate governance, analysis, and intervention

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Framing dispute active; agents disagree on situation type | Power; Perspectives; Governance | Stakeholder process | Run multi-agent situation-naming workshop; surface dissent explicitly. |
| Situation has drifted; classification is stale | Time; Realities; Diagnosis | Monitoring/re-typing | Trigger forced re-typing; compare old vs new classification; audit why drift was missed. |
| Crisis misclassified as routine | Systems; Diagnosis; Risk | Incident response | Rapid re-type to Crisis/Disruption; escalate tempo and governance; activate incident protocols. |
| Hidden exception/edge case in boundary | Boundaries; Systems; Evidence | Scope review | Surface exceptions; test boundary fit; escalate to full Boundaries framework. |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Elicit primary situation narrative(s) from 2+ stakeholder perspectives; note divergences.
2. Assign initial situation type(s) using meta-categories (I–VI) and diagnostic questions.
3. Profile 2–3 most salient dimensions (structural order, valence, agency) using indicative values.
4. Identify obvious transitions, overlaps, or framing conflicts at boundaries between types.
5. Tag classification as Fact/Interpretation/Assumption/Unknown per Prompt Discipline rules.

### 7b. Full Depth Execution (Complete framework run)

1. Elicit and synthesise narratives from 3+ independent stakeholder perspectives; document conflicts and asymmetries.
2. Assign primary + secondary situation types; justify with diagnostic cues.
3. Profile all five dimensions with evidence-based rationales; document contested readings.
4. Map three interface types: transitions (escalation/crystallisation paths), overlaps (nested situations), framing (who frames what and why).
5. Identify dynamic patterns in play (escalation/drift/pluralisation/transformation).
6. Run Tier 1 Hiddens scan (six-category sweep); escalate Hidden types to 6c interface.
7. Specify re-typing cadence and threshold triggers; produce Hiddens shortlist and mitigation actions.
8. Hand off to downstream frameworks (Diagnosis, Decisions, Interventions, Risk, Governance).

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add entries for framing conflicts, positional asymmetries, temporal drift risks. | At completion of 6a scan; escalate critical Hiddens to full framework. |
| Evidence Ledger | Record situation narratives, diagnostic cues, dimensional profile evidence, typing uncertainty. | Document source, confidence level, and dissenting views for each classification element. |
| Hypothesis/Test Backlog | Add hypotheses on situation type validity; create tests for transitions and drift. | Propose re-typing trigger thresholds; specify what evidence would falsify current classification. |
| Information Requests | Flag narrative gaps, evidence shortfalls, and stakeholder access barriers. | Note missing perspectives, data access constraints, and authority/governance gaps. |

**Gate Question (pre-closure check):** If this situation were to transition to a different type (escalate, crystallise, pluralise, drift, or transform), would that change trigger a material shift in governance, analysis, or response? What leading indicators would flag that transition?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Agents: stakeholder narratives and role maps
- Evidence: data and artefacts that ground situation narratives
- Systems: structural and feedback patterns that enable/constrain situation type
- Time: temporal horizons, pacing, and windows affecting situation character
- Scale: magnitude and complexity effects shaping situation properties

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Diagnosis: situation type guides diagnostic hypothesis generation and root-cause selection
- Decisions: situation type determines decision rights, tempo, and governance structure
- Interventions: situation type governs which intervention patterns are feasible and appropriate
- Risk: situation type and dynamics drive risk taxonomy and monitoring cadence
- Governance: situation type shapes decision authority, escalation, and oversight structure
- Learning & Adaptation: situation transitions signal need for learning cycle adjustment

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Framing Conflict Scan | Situate competing frames in meta-categories; reveal Hidden-8 Framing capture. |
| Transition & Threshold Scan | Identify escalation, crystallisation, pluralisation, drift, and transformation paths. |
| Contextual Blindness Scan | Expose Hidden-24: same situation appears different across scales, roles, agents. |
| Misclassification Risk Audit | Test whether current situation type remains valid; audit re-typing cadence adherence. |

---

*Extract complete. Ready for LLM execution with Operating Guide v2.5.*
