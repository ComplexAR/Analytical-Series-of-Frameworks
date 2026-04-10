# Framework of Scenarios – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Scenarios |
| Primary group | G3 — Uncertainty & Futures (Possibility, uncertainty, futures) |
| Secondary group | G1 — Context (Situations, context, framing) |
| Stage | Core (Framework Group 3: Uncertainty & Futures) |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v1.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Scenarios framework constructs plausible alternative futures by systematically varying key drivers and assumptions. It classifies scenarios into six meta-categories and thirty core types; maps five cross-cutting dimensions (scope, causation, timeline, reversibility, surprise); identifies eight dynamic patterns that shape scenario evolution; and surfaces Hiddens by making strategy assumptions explicit and testing robustness across discontinuous futures. It populates the Scenarios Register, Assumptions Register, Robustness Assessment, and Hiddens Register across 50 frameworks, enabling downstream frameworks to test strategy resilience and discover vulnerability modes.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Scenarios when… | Use neighbour instead when… |
|---|---|---|
| Risk | You need to construct plausible alternative futures and stress-test strategy across them; focus is on possibility space and scenario coherence. | You need to estimate probability and impact of specific risks; focus is on likelihood assessment and quantitative risk analysis. |
| Uncertainties | You need to map out alternative futures created by varying key assumptions; focus is on assumption-space exploration. | You need to inventory what is unknown and structure uncertainty taxonomy; focus is on sources and types of uncertainty independent of futures construction. |
| Decisions | You need to test whether a decision remains robust across multiple possible futures; focus is on robustness and adaptability. | You need to analyse a specific decision; focus is on the choice logic and outcomes independent of alternative futures. |
| Causation | You need to trace causal chains and feedback loops that produce different scenario outcomes; focus is on mechanism and dynamics. | You need to establish causal relationships in general; focus is on how causation works independent of specific scenarios. |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Continuity Scenarios | Trend-projection continuity, Institutional persistence, Competitive-position persistence, Regulatory continuity, User/market continuity | What happens if past patterns and structures continue unchanged into the future? |
| II. Cyclical Scenarios | Market cycle phase transition, Technology adoption cycle, Political/policy cycle, Commodity price cycle, Competitive cycle | What happens if recurring cycles continue to operate, but at different phases, amplitudes, or frequencies? |
| III. Transformative Scenarios | Market structure transformation, Technology displacement, Organizational form transformation, Institutional legitimacy shift, Value proposition transformation | What happens if fundamental structures or organizing principles shift and institutions restructure? |
| IV. Discontinuous Scenarios | Confidence collapse, Supply chain rupture, Geopolitical realignment, Technology failure or disruption, Regime shift or tipping point | What happens if causal chains break, tipping points are crossed, or non-linear effects appear? |
| V. Adversarial Scenarios | Competitive predation, Hostile regulation or policy, Supply chain sabotage or defection, Coordinated attack or boycott, Insider sabotage or breach | What happens if intelligent adversaries deliberately act against organizational interests? |
| VI. Counterfactual Scenarios | Alternative history, Alternate founder/leader choice, Alternate strategic decision, Alternate market structure, Alternate external condition | How would current state be different if one key assumption about past or present were changed? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Slow-then-sudden | Change undetectable for extended period, then accelerates non-linearly into rapid transformation. | Early phase invisible due to slow accumulation; tipping point reached; phase shift occurs. | Early warning systems miss slow phase; by the time signals appear, response options are constrained. |
| Oscillating/cycling | Change oscillates between states without clear directional trend; cycle phase and amplitude vary. | Recurring patterns operate; phase shifts but overall structure persists; systems return to prior behavior. | Strategies optimized for one phase become brittle when cycle shifts; false confidence when in familiar prior phase. |
| Accelerating/decelerating | Change accelerates or decelerates over time; rate of change varies. | Feedback loops amplify or dampen; initial conditions shape trajectory; forcing function increases or decreases. | Linear extrapolation seriously mis-estimates where change will be; acceleration underestimated or overestimated. |
| Lock-in/irreversibility | Change becomes increasingly locked-in or path-dependent; early choices constrain later choices. | Sunk costs accumulate; switching costs increase; alternatives become unavailable or unaffordable. | Early decisions have outsized impact; reversibility is lost; flexibility decreases; options preservation critical. |
| Contagion/cascade | Change in one system triggers change in adjacent systems; effects amplify through networks. | Coupling between systems high; disruption cascades; feedback loops reinforce; system behavior shifts together. | Isolated risk assessment misses cascade potential; seemingly independent risks become correlated. |
| Bifurcation/divergence | Two distinct futures diverge from common present; which emerges depends on which side of threshold system lands. | Tipping point reached; system crosses threshold; behavior changes qualitatively; path splits. | Small differences lead to large outcome differences; interventions near bifurcation have outsized impact. |
| Emergence/self-organization | Order or coordination emerges without centralized direction; novel patterns appear from distributed actors. | Simple rules at local level; distributed interaction; coordination emerges without central direction. | Centralized control strategies become ineffective; must work with emergent order; harder to predict specific outcomes. |
| Hysteresis/non-reversibility | System behavior differs depending on path taken to current state; return to prior state does not restore prior behavior. | History matters; transitions are irreversible at the system level; learning or lock-in prevents return. | Going backward is not an option; past transitions have lasting effects; current state is path-dependent. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What assumptions about the future is current strategy treating as inevitable facts rather than as contingent assumptions? |
| II (Systemic) | Are scenario interdependencies and feedback loops between scenarios being modelled, or are scenarios treated as independent? |
| III (Informational) | Are weak signals and early indicators of scenario transitions being monitored, or would transition only become obvious in hindsight? |
| IV (Temporal) | Is the timeline for scenario evolution being treated as linear when it might be slow-then-sudden; are lock-in effects on reversibility being considered? |
| V (Relational) | Whose interests are served by hoping one scenario will not occur; who benefits from believing current strategy will remain robust? |
| VI (Ontological) | Does strategy assume one narrative about what the future is about, while alternative narratives suggest different futures? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Future-as-continuation bias (treating past patterns as guaranteed to continue)
- Normalcy bias (treating current structures as inevitable or nearly inevitable)
- Tail-risk dismissal (treating discontinuous scenarios as impossible or too extreme)
- Assumption invisibility (strategy assumptions treated as facts not contingencies)
- Scenario clustering around "most likely" (avoiding true diversity by clustering scenarios around linear extrapolation)
- Blindness to tipping points and lock-in (not recognizing irreversibility and path dependence in scenarios)
- Weakness-signal blindness (early indicators of scenario transition not recognised or dismissed)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Strategy assumes future is continuation of past trends | Framework of Risk; Framework of Uncertainties | Scenario robustness testing against discontinuity | Construct explicit discontinuous scenarios; test strategy resilience; identify failure modes. |
| Key strategy assumptions are invisible and unexamined | Framework of Assumptions; Framework of Evidence | Assumption articulation in scenario construction | Make assumptions explicit in each scenario; audit which assumptions strategy depends on; stress-test assumptions. |
| Signals of scenario transition are not being monitored | Framework of Evidence; Framework of Learning & Adaptation | Early indicator development and monitoring | Identify leading indicators for each scenario type; establish monitoring and escalation triggers. |
| Lock-in effects are not recognised; strategy assumes reversibility | Framework of Risk; Framework of Decisions | Path-dependence analysis; reversibility assessment | Map lock-in effects in each scenario; identify points of no return; assess recovery costs from alternative futures. |
| Scenario diversity is lost to clustering around "most likely" | Hiddens scan across 50 frameworks | Discontinuity forcing and robustness testing | Force construction of discontinuous and discomforting scenarios; test strategy across full scenario diversity. |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify 2–3 key uncertainties or drivers that shape alternative futures (market, technology, regulation, geopolitics, etc.).
2. For each uncertainty, construct rapid 2×2 or 3×3 scenario matrix varying key drivers; brief narrative label for each scenario.
3. Classify each scenario by meta-category (Continuity, Cyclical, Transformative, Discontinuous, Adversarial, Counterfactual).
4. Test current strategy against scenario matrix: in which scenarios does strategy succeed, become brittle, or fail?
5. Run Tier 1 Hiddens scan: flag which scenarios organization seems most uncomfortable with; surface hidden assumptions.

### 7b. Full Depth Execution (Complete framework run)

1. Identify key uncertainties and drivers through research, stakeholder interviews, weak signal analysis; build uncertainty inventory.
2. For each uncertainty, construct full scenario narrative (500–2,000 words per scenario): explicit drivers, causal logics, key events, implications, assumptions made visible.
3. Map five dimensions for each scenario: Scope (local/regional/national/transnational); Causation (drivers, feedback loops, tipping points); Timeline (speed and phases); Reversibility (recovery costs); Surprise (discontinuity from current expectations).
4. Analyse dynamic patterns: identify which patterns (slow-then-sudden, cascade, lock-in, etc.) are active in each scenario.
5. Create scenario implications canvas for current strategy: where does strategy succeed, become brittle, fail, require adaptation?
6. Map three interfaces: Scenario-to-Risk (plausible futures inform risk analysis); Scenario-to-Evidence (what data would signal scenario transition); Scenario-to-Decision (robustness of key decisions).
7. Run Tier 1 + Tier 2 Hiddens scan: for each uncomfortable scenario, identify mechanism, detectability, agency, consequence; assign detection and remediation interfaces; document Unknowns.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Scenarios Register | Add scenario narratives, classification (meta-category + type), dimension profiles, dynamic patterns active, strategy robustness assessment. | After scenario construction and analysis. |
| Assumptions Register | Record explicit assumptions embedded in each scenario; track which assumptions strategy depends on. | After scenario construction; escalate critical assumptions to governance. |
| Robustness Assessment | Strategy performance across scenarios; brittleness points; failure modes; required adaptations for each scenario. | After strategy testing; escalate high-risk failure modes. |
| Uncertainties Register | Key drivers and uncertainties; leading indicators for scenario transitions; monitoring triggers. | After driver identification; establish monitoring. |
| Hiddens Register | Scenario-specific Hiddens: hidden assumptions, invisible transitions, lock-in effects, discomfort-driven blindness. | After Tier 1 scan; escalate high-consequence Hiddens to Tier 2. |

**Gate Question (pre-closure check):** Have we identified key uncertainties and constructed scenarios across all meta-categories, mapped strategy robustness across scenarios, identified brittleness points and failure modes, run a Tier 1 Hiddens scan, and escalated any high-consequence scenario risks to Risk and Decisions frameworks?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Situations/Context (provides situational framing and baseline for scenario construction)
- Uncertainties (inventories what is unknown; shapes key drivers for scenarios)
- Evidence (provides weak signal data that enables early scenario construction)
- Power & Interests (identifies who benefits from which scenarios; shapes blindness detection)
- Decisions (decision context that scenarios will stress-test)
- Systems & Causation (provides causal logic for scenario development)

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Framework of Risk (scenario identification enables risk analysis across futures; tail risks identified)
- Framework of Decisions (robustness testing of decisions across scenarios; identifies decision brittleness)
- Framework of Strategy & Alternatives (scenario implications enable strategy adaptation)
- Framework of Learning & Adaptation (scenarios enable adaptive capacity building for multiple futures)
- Framework of Uncertainties (scenarios surface which uncertainties matter most)
- Framework of Hiddens (scenario construction surfaces hidden assumptions and blindnesses)

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Scan 1: Assumption audit across 50 frameworks | Identify strategy assumptions in each framework; stress-test against scenarios that violate assumptions. |
| Scan 2: Scenario diversity and brittleness | Construct scenarios across all meta-categories; ensure diversity; identify where strategy becomes brittle. |
| Scan 3: Tail-risk and discontinuity | Force construction of tail-risk and discontinuous scenarios; identify collapse modes; assess recovery capacity. |
| Scan 4: Lock-in and reversibility assessment | Identify decisions and commitments that create lock-in; map reversibility in each scenario; identify points of no return. |
| Scan 5: Weak-signal monitoring | Develop leading indicator sets for each scenario; establish monitoring; plan escalation for scenario transition signals. |

---

*LLM Execution Extract v1.0 – Scenarios Framework (2026-04-08) – End of Extract*
