# Framework of Systems – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Systems |
| Primary group | G2 — Structure, dependencies & mechanism (Mechanism) |
| Secondary group | G1 — Framing & scope-setting (Framing) |
| Stage | Core |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Systems framework maps the causal structure of a scenario as a system: identifies components, stocks, flows, feedback loops, delays, and leverage points; classifies system types across six meta-categories (Stocks & Flows, Feedback Loops, Delays, Boundaries, Hierarchy, Adaptation); analyzes system behavior (balancing, reinforcing, oscillation, phase transition); and surfaces system-level Hiddens (loose coupling masking dependencies, delays creating instability, feedback loops generating unintended consequences). It populates the Evidence Ledger, Causation workspace, and Risk Register with system-level leverage analysis and cascade risk assessment, enabling identification of intervention points and cascade failures.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Systems when… | Use neighbour instead when… |
|---|---|---|
| Causation | You need to analyze system-level causal structures, feedback loops, and delays; focus is on stocks/flows and emergent system behavior. | You need to analyze causal mechanisms independent of system structure; focus is on cause-effect relationships and intervention logic. |
| Boundaries | You need to identify system boundaries and what defines system membership; focus is on structural system definition. | You need to classify boundary types and governance; focus is on boundary properties independent of system structure. |
| Processes | You need to understand how activity flows through system structure; focus is on system-enabled or system-constrained processes. | You need to analyze task sequences and workflow design; focus is on activity patterns independent of supporting system. |
| Relations | You need to map relationships as causal dependencies within system structure; focus is on structural coupling. | You need to analyze relationship types and dynamics; focus is on relational properties independent of system causal structure. |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Stocks & Flows | Level/Stock, Flow, Rate, Accumulation, Depletion, Balance Point | What quantities accumulate or deplete; what regulates their flow? |
| II. Feedback Loops | Reinforcing Loop, Balancing Loop, Delay-Coupled Loop, Oscillating Loop, Threshold Loop, Paradoxical Loop | What feedback loops drive system behavior; are they balancing or destabilizing? |
| III. Delays & Lags | Information Delay, Decision Delay, Material Delay, Causal Delay, Adaptive Lag | What delays exist between sensing and response; do they destabilize the system? |
| IV. Boundaries & Coupling | System Boundary, Input, Output, Coupling Strength, Loose Coupling, Tight Coupling | How is the system bounded; how does it couple with external systems? |
| V. Hierarchy & Nesting | Level, Component, Subsystem, Nested Structure, Hierarchical Dependency, Emergence | What hierarchical levels exist; how do lower levels support higher? |
| VI. Adaptation & Learning | Homeostasis, Setpoint Adjustment, Learning Loop, Adaptation, Bifurcation, Regime Shift | How does the system maintain stability; at what point does it reorganise? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Reinforcing Loop Runaway | System accelerates out of control; quantity grows exponentially; linear interventions fail to stabilize. | Reinforcing feedback loop; gain > 1; no balancing feedback to stabilize; exponential growth unstoppable by proportional response. | Crisis; overshoot; collapse; emergency intervention required; hard stop needed. |
| Balancing Loop Oscillation | System oscillates around setpoint; swings amplify if delays are long; hunting behavior; instability from overshoot and correction. | Balancing feedback with significant delay; controller overshoots; correction lags sensing; next correction compounds previous overshoot. | Instability; oscillations amplify; system approaches bifurcation; sensitivity to parameter changes. |
| Loose Coupling Masking Dependence | Components appear independent; tight coupling undetected; failure propagates when tested; invisible dependencies emerge. | Coupling strength low in normal operation; coupling becomes critical under stress; interdependencies not mapped; complexity hides coupling. | Cascade failures; system fragility; surprises during crises; prevention opportunity missed. |
| Delay-Induced Instability | System destabilizes due to lag between cause and response; feedback responses arrive too late; corrections overshoot. | Sensing lag, decision lag, or implementation lag separates cause from effect; feedback loop gain becomes unstable across lag. | Oscillation, overshoot, collapse; system becomes unstable despite adequate feedback; long-lag effects invisible. |
| Threshold & Bifurcation | System stable until threshold is crossed; rapid phase transition; old equilibrium becomes unstable; new regime emerges. | System has multiple stable states; external forcing pushes past bifurcation point; hysteresis means return path different. | Tipping point; system shift; resilience loss; prior equilibrium unreachable; new controls required. |
| Perverse Effect & Counter-Intuitive Behavior | Intervention designed to solve problem makes it worse; causal intuition inverted by system structure. | Intervention addresses symptom not root cause; breaks stabilizing loop; removes negative feedback; amplifies reinforcing loop. | Crisis deepens; trust in control erodes; unintended consequences from well-meant action. |
| Loose-Tight Coupling Fragility | System couples tightly to specific elements; alternative structures unavailable; brittleness when tight-coupling point fails. | Specialization and optimisation create tight coupling; redundancy removed for efficiency; alternatives not maintained. | Single point of failure; cascade collapse; loss of resilience; recovery slow. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What system structure features are salient vs invisible from common positions; what coupling is below attention threshold? |
| II (Systemic) | How do feedback loops, delays, and thresholds create system-level behavior; what are the unintended consequences of system structure? |
| III (Informational) | What information about system structure is available vs hidden; what measurement blindspots exist; what delays obscure feedback? |
| IV (Temporal) | What are the timescales of different feedback loops and delays; how do mismatched timescales destabilize the system? |
| V (Relational) | Who controls which leverage points; whose control is limited by system structure; what power asymmetries are hidden by system explanation? |
| VI (Ontological) | What system boundaries and entities are assumed vs contestable; what alternative system conceptualizations are foreclosed? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Coupling Invisibility (interdependencies between components hidden until stress test)
- Delay-Induced Instability (lags between cause and effect create counterintuitive system behavior)
- Feedback Loop Unawareness (reinforcing or balancing loops operate undetected)
- Threshold Blindness (system approaching bifurcation point with no visible warning)
- Leverage Point Blindness (high-leverage intervention points not recognized)
- Perverse Effect (interventions exacerbate rather than ameliorate due to system structure)
- System Fragility (tight coupling creates brittleness; loose coupling masks dependencies)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Counterintuitive or perverse system behavior | Framework of Causation; Framework of Hiddens | Causal structure audit; system dynamicsal modelling | Map feedback loops and delays; test model predictions against behavior. |
| Coupling failure or cascade risk | Framework of Risk; Framework of Interventions | Coupling strength assessment; redundancy design; mode failure analysis | Identify tight-coupling points; design redundancy; plan cascade mitigation. |
| Threshold/tipping point detection | Framework of Time; Framework of Risk | Threshold location mapping; early warning system design; bifurcation analysis | Identify approach to bifurcation; install threshold monitoring; design graduated response. |
| Intervention backfire or unintended consequence | Framework of Interventions; Framework of Learning | Causal loop analysis; simulation of intervention effects | Trace causal pathways of intervention; test for reinforcing loop amplification. |
| System instability or oscillation | Framework of Causation; Framework of Evidence | Delay and feedback analysis; parameter sensitivity testing | Identify problematic delays; test system stability across parameter range. |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify system components and boundaries; sketch major flows (stocks, rates, accumulation).
2. Identify 3–5 salient feedback loops (reinforcing or balancing); assess whether loops are stabilizing or destabilizing.
3. Note major delays or lags; assess whether delays destabilize feedback loops.
4. Run Tier 1 Hiddens scan: touch all six meta-categories; flag obvious coupling invisibility, counterintuitive behavior, or threshold proximity.
5. Shortlist 2–3 highest-consequence system-level risks (coupling failure, perverse effect, bifurcation); flag for escalation if control is uncertain.

### 7b. Full Depth Execution (Complete framework run)

1. System structure map: identify all components, stocks, flows, rates; draw system diagram with all major connections.
2. Feedback loop inventory: identify all reinforcing and balancing loops; classify by strength (gain), timescale, and whether stabilizing or destabilizing.
3. Delay analysis: identify all significant delays (sensing, decision, implementation); assess whether delays destabilize feedback loops.
4. Coupling strength map: for each component linkage, estimate coupling strength (tight/loose); identify single points of failure.
5. Leverage point analysis: identify high-leverage intervention points (information flow, feedback loop gain, system parameters); assess feasibility of each.
6. Dynamics analysis: run system through scenarios; predict behavior (steady state, oscillation, threshold crossing); compare to observed behavior; test model.
7. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence system-level phenomenon, identify mechanism, detectability, consequence; propose system-structure tests.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add system-level Hiddens with meta-category tag; mechanism (feedback loop, delay, coupling); consequence. | After Tier 1 scan; escalate coupling failures and threshold crossing. |
| Evidence Ledger | Record system structure, feedback loops, delays, coupling strengths; note measurement quality and gaps. | After system structure mapping and feedback loop analysis. |
| Hypothesis/Test Backlog | Add hypotheses about feedback loops, system behavior, intervention effects; propose system-structure tests and simulations. | Identified system Unknowns; escalation decisions. |
| Information Requests | Request system structure data; request historical behavior for model testing; request alternative system representations. | To reduce system Unknowns; coordinate with Causation and Evidence frameworks. |

**Gate Question (pre-closure check):** Have we mapped system structure, identified feedback loops and delays, assessed coupling and leverage points, run a Tier 1 Hiddens scan, and designed system-aware interventions?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Situations Context Classification (what situation types have what system structures?)
- Boundaries (what defines system boundaries and what couples systems?)
- Scale (how do system properties vary across scales?)
- Causation (what causal mechanisms structure the system?)

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Framework of Hiddens (coupling invisibility, delay effects, threshold blindness; Tier 2 scans)
- Framework of Causation (causal mechanism design; feedback loop analysis)
- Framework of Processes (process design respecting system structure and constraints)
- Framework of Risk (cascade failure risk; threshold crossing risk; coupling risk)
- Framework of Decisions (system-aware decision architecture; intervention leverage point design)
- Framework of Interventions (system-respectful intervention design; cascade mitigation)

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Scan 1: Coupling invisibility and cascade failure detection | Identify hidden interdependencies; assess cascade potential. |
| Scan 5: Threshold and bifurcation detection | Identify system approach to tipping points. |
| Scan 7: Feedback loop and perverse effect detection | Identify reinforcing loops driving unintended escalation. |
| Scan 10: Delay-induced instability and oscillation | Identify destabilizing lags creating system hunting behavior. |

---

*LLM Execution Extract v1.0 – Systems Framework (2026-04-08) – End of Extract*
