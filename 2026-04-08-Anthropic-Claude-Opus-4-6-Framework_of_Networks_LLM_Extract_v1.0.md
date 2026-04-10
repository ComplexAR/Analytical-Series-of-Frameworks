# Framework of Networks – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Networks |
| Primary group | G1 — Wholes (Systems, Emergence, Complexity) |
| Secondary group | G2 — Mechanism (Systems, Processes, Causation, Rules) |
| Stage | Core (Framework Group 1: Systems & Emergence) |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v1.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Networks framework identifies how nodes (agents, components, systems) are connected; classifies network topology into six meta-categories and thirty core types; maps how network structure shapes what flows where, who sees what, and how disturbances cascade; and surfaces the visibility failures (structural hole blindness, echo chamber isolation, cascade pathway invisibility, positional blindness, hub dependency invisibility, bridge-role invisibility) that prevent understanding of topology-driven behaviour. It populates the Hiddens Register, Evidence Ledger, Cascade Risk Register, and Interface Inventory with network-specific blindnesses and governance requirements, enabling downstream frameworks to design topology-aware interventions robust to cascade risk and structural fragility.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Networks when… | Use neighbour instead when… |
|---|---|---|
| Systems | Focus is on static network structure: who/what is connected to whom, topology patterns, bottlenecks, cascade pathways in the wiring. Network topology is primary question. | Focus is on system function: how components work together; system boundaries and dependencies; functional architecture rather than connection topology. |
| Emergence | Focus is on how network topology enables/constrains emergence; cascade dynamics and contagion propagation through network structure. | Focus is on non-linear dynamics and thresholds independent of specific network topology; emergence mechanisms rather than propagation pathways. |
| Power & Influence | Focus is on structural position advantages and disadvantages; who is central/peripheral, who bridges, who is isolated; positional power in network. | Focus is on who can persuade/coerce whom; influence and persuasion dynamics; power distribution independent of connection structure. |
| Communication | Focus is on network topology as structure enabling/constraining information flows; visibility asymmetry and information access inequality. | Focus is on message content, encoding, interpretation; quality and comprehension of what flows through network. |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Structural Connectivity Types | Full Mesh, Star (Hub-and-Spoke), Line (Path Graph), Tree (Hierarchical Structure), Sparse Random Graph | How are nodes directly connected; what is the basic wiring pattern; is connectivity complete, hierarchical, random, or sparse? |
| II. Centrality & Hub Architecture | Single-Hub Dominance, Multi-Hub Architecture, Distributed Connectivity (No Central Hub), Scale-Free (Preferential Attachment), Rank-Ordered Hierarchy | Where do connections concentrate; how critical are hubs; is centrality distributed or concentrated? |
| III. Clustering & Density Patterns | Dense Clustering (High Local Density, Sparse Inter-Cluster Edges), Moderate Clustering (Mixed Local Density and Bridging), Low Clustering (Sparse, Weak Community Structure), Bipartite Clustering (Two Distinct Groups), Modular Multi-Community Structure | Do nodes form tight local clusters; how dense are clusters relative to between-cluster connectivity? |
| IV. Bridging & Brokerage | Bridge Role Scarcity (Few Bridges, High Concentration), Distributed Bridging (Many Bridges, Competitive Cross-Cluster), Brokerage Specialisation (Dedicated Intermediaries), Peer-to-Peer Bridging (Direct Cross-Cluster), Gateway Architecture (Designated Controlled Entry/Exit) | How do connections span clusters; what role do bridges play; who controls cross-cluster flow? |
| V. Isolation & Fragmentation | Isolated Nodes (Pendant or Orphan Nodes), Fragmented Network (Multiple Disjoint Components), Weakly Connected with Long Diameter (Single Component, High Path Length), Lopsided Bipartite Separation, Temporal Fragmentation (Connected in Aggregate, Fragmented Over Time) | Are there nodes or groups with few/no connections; how fragmented is the network? |
| VI. Multi-Layer & Dynamic Topology | Multiplex Network (Multiple Independent Edge Types), Correlated Multi-Layer (Layers Reinforce Each Other), Temporal Rewiring (Network Structure Changes Over Time), Hierarchical Multi-Level Network (Nested or Recursive), Small-World Network (Short Average Path Length with High Clustering) | Do multiple edge types create different topologies; does topology change over time? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Contagion (Spread of Influence or Information) | Information or disturbance spreads from initiating node through network at varying speeds; roughly exponential in early phase, slowing at saturation. | Each node spreads to neighbours with some probability; speed scales with density and centrality; hubs accelerate spread. | System-wide adoption occurs rapidly; speed of spread exceeds governance response capacity; containment windows are narrow. |
| Bottleneck Activation (Flow Concentration at Chokepoint Nodes) | When demand exceeds capacity at hub or bridge, flow backs up; delays propagate backward; system-wide degradation results. | Hubs/bridges become saturated; upstream nodes queue; persistent saturation triggers disconnection or retry, amplifying problem. | Systemic degradation from local saturation; cascading failure from resource bottleneck; vulnerable to deliberate chokepoint attacks. |
| Rapid Cascade (Fast Propagation Through Hub-Dependent Network) | Failure originating at hub propagates instantaneously to all peripheral nodes; system-wide collapse occurs in single hop. | Hub-and-spoke topology: hub failure = entire network failure; cascade time minimal because all paths route through hub. | System is critically fragile; single hub failure = total network failure; redundancy is essential. |
| Slow Diffusion (Gradual Spread Through Sparse Network) | Information or disturbance spreads very slowly through sparse or fragmented network; distant nodes may never receive signal or receive it after long delay. | Low density and long average path length slow cascade; contagion stalls at sparse bridges; signal decays over long paths. | Information isolation; slow adaptation; distant nodes disconnected from source; system lacks coherence. |
| Diffusion with Decay (Weakening of Signal as It Propagates) | Message or signal attenuates as it propagates; by time it reaches distant nodes, it is degraded, distorted, or lost. | Each hop introduces noise, distortion, or selective passing; long paths amplify decay; hubs may intentionally filter or distort. | Distant nodes receive distorted signals; coordination fails due to signal loss; intentional gatekeeper filtering. |
| Hub Failure Cascade (Collapse Triggered by Loss of Hub or Multiple Hubs) | Loss of hub or simultaneous loss of multiple hubs triggers system-wide failure propagation; peripheral nodes lose connectivity and network fragments. | Hub-centric topology: hub removal breaks connectivity; multiple simultaneous hub losses fragment network into isolated components. | System fragmentation; loss of coordination; isolated islands unable to communicate; recovery requires hub restoration. |
| Bridge Severance (Loss of Connectivity Between Clusters When Bridges Are Cut) | If bridges connecting clusters are severed (deliberately or accidentally), clusters become isolated and information/resources cannot flow between them. | Bridges are often few; removal fragments network; deliberate bridge severance isolates clusters; deliberate attack vectors. | Cluster isolation; information silos; resource inequality between clusters; deliberate partition attacks. |
| Echo Chamber Lock-in (Information Isolation Within Dense Clusters) | Dense clusters with few cross-cluster bridges create information isolation; nodes within cluster receive only intra-cluster information; disconfirming information never arrives. | Dense within-cluster edges, sparse between-cluster edges, limited bridging; feedback within cluster reinforces local beliefs; external signals decay. | Belief reinforcement; epistemic isolation; group polarisation; resistance to contrary information; cluster-specific realities. |
| Oscillating Circulation (Oscillatory Flow With Phase Lag) | Information or resources circulate through network in oscillatory pattern; feedback delays cause overshooting and correction cycles; boom-bust dynamics. | Path length creates phase lag between source and destination; feedback control amplifies oscillation; no damping mechanism. | System instability; boom-bust cycles; resource mismatch between supply and demand; reduced efficiency. |
| Epidemic Burnout (Contagion Slows and Stops as Susceptible Pool Depletes) | Spread of information or disturbance slows as it reaches saturation; nodes become immune or resistant; cascade dies out; depending on saturation point, may leave portions untouched. | Early exponential spread; many susceptible nodes; as susceptible nodes get infected, spread slows; if immunity is sticky, cascade terminates. | Partial network coverage; segment of network remains uninfected; equilibrium at less than full saturation. |
| Saturation & Congestion (Network Becomes Overloaded; Quality or Speed Degrades) | Flow or demand exceeds network capacity; delays increase; quality degrades; system may become unstable or oscillate. | Capacity at nodes/edges exceeded; queues build; retry logic and feedback loops amplify congestion. | System performance degradation; potential instability and oscillation; user frustration and alternative seeking. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What network structure is invisible because nodes can only perceive what they are directly connected to; what are they structurally blind to? |
| II (Systemic) | How does network topology shape cascade pathways and bottleneck risks; what systemic fragility or cascade risk emerges from the topology? |
| III (Informational) | What information flows through the network and what does not; what information is lost, distorted, or gated at hubs or bridges; what information asymmetries exist? |
| IV (Temporal) | How does network structure change over time; are rewiring dynamics visible; what temporal fragmentation exists (connected in aggregate, fragmented in windows)? |
| V (Relational) | Who controls bridges and hubs; who has positional power through centrality or brokerage; are power asymmetries masked as technical necessity? |
| VI (Ontological) | How does network topology structure what is perceivable and what is invisible; what categories of nodes are rendered invisible or marginal by topology? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Structural Hole Blindness (actors cannot perceive what they are not directly connected to; bridges don't see their own criticality)
- Echo Chamber Isolation (dense clusters with few bridges produce epistemic isolation; disconfirming information does not arrive)
- Cascade Pathway Invisibility (failure or disturbance routes are invisible until they activate)
- Positional Blindness (different positions see radically different topologies; hub view is not objective)
- Hub Dependency Invisibility (concentration of connectivity at hubs creates fragility invisible in node-level metrics)
- Bridge-Role Invisibility (bridge roles and their value are invisible to both bridge-occupants and nodes they serve)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Network topology is unmapped or unknown | Framework of Systems; Framework of Evidence | Topology mapping + validation | Map nodes and edges; verify through multiple sources; document confidence levels; identify dark regions. |
| Hub dependency creates single-point-of-failure risk | Framework of Risk; Framework of Resilience | Hub inventory + capacity assessment + redundancy design | Identify critical nodes; assess what fails if hub is unavailable; design hub redundancy or failover. |
| Echo chamber isolation reduces information flow | Framework of Communication; Framework of Perspectives | Cross-cluster bridge assessment + information-injection testing | Assess cluster boundaries; validate whether disconfirming information reaches clusters; design bridge reinforcement. |
| Bridge roles are unrecognised and uncompensated | Framework of Responsibility; Framework of Power | Bridge identification + bridge-occupant interviews + recognition design | Make bridges explicit; ask bridge-occupants about their role; assess bridge adequacy; recognise and support bridges. |
| Cascade pathways invisible; failure surprises expected | Framework of Risk; Framework of Interventions | Cascade pathway modelling + bottleneck identification + scenario testing | Map cascade pathways; identify bottlenecks; simulate cascades under scenarios; design failure containment. |
| Positional asymmetry creates different perceived realities | Framework of Perspectives; Framework of Governance | Multi-position interviews + network-as-perceived mapping | Conduct interviews from different positions; map "network as seen from X's position"; highlight contradictions; integrate positions. |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Define focal decision or problem; clarify network scope: who/what are nodes, what edges count as connections, what time window is relevant.
2. Map node and edge inventory; collect evidence from logs, org charts, interviews, transaction records; document confidence levels (verified, inferred, suspected).
3. Classify network topology into one or more of six meta-categories (I–VI) and assign core types (1–30); profile across five dimensions: Density, Centrality Distribution, Clustering Coefficient, Resilience Profile, Visibility Asymmetry.
4. Identify hubs, bridges, clusters, and isolated nodes; assess which dynamic patterns (1–11) are active and highest-risk; note cascade pathways and bottlenecks.
5. Run Tier 1 Hiddens scan across six Hiddens meta-categories; flag obvious structural blindness (hub dependency, bridge invisibility, echo chambers); identify highest-consequence Hiddens for escalation.

### 7b. Full Depth Execution (Complete framework run)

1. Clarify focal scenario, network boundary, decision goal; confirm scope, stakeholders, time window; confirm Run Mode and routing outputs.
2. Conduct comprehensive node and edge inventory; map all nodes and edges in focal network; collect evidence from multiple sources; document confidence and gaps.
3. Classify network topology; assign types across six meta-categories (I–VI); profile all five dimensions quantitatively or qualitatively; identify structural properties (density, centrality concentration, clustering, bridges, isolated nodes).
4. Map all potential cascade pathways; identify bottlenecks and cascade-triggering conditions; model flow dynamics under scenarios (contagion, diffusion, bottleneck activation, hub failure, bridge severance, echo chamber lock-in); stress-test network.
5. Identify three interface types: Bridging (where bridges are critical), Clustering (inter-cluster friction and information barriers), Hub Governance (hub control and accountability); assess readiness and risks.
6. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence Hidden (structural hole blindness, echo chamber isolation, cascade invisibility, positional blindness, hub dependency, bridge invisibility), identify mechanism, detectability, agency, consequence.
7. Design topology-aware interventions: bridge strengthening/redundancy, hub failover, network rewiring, cluster bridging, redundancy insertion, isolation-breaking connections; specify governance for topology changes; produce monitoring and escalation plan.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add network-specific Hiddens shortlist with meta-category tag (I–VI), mechanism (structural hole blindness, cascade invisibility, etc.), detectability, consequence. | Tier 1 scan completion; escalate high-consequence/high-uncertainty Hiddens to Tier 2. |
| Evidence Ledger | Record topology classification, dimensional profiles, cascade pathway analysis, dynamic pattern assessment, evidence quality and provenance. | After topology classification and dimensional profiling; note gaps (e.g., cascade testing, hub capacity measurement). |
| Cascade Risk Register | Document cascade pathways, bottleneck inventory, hub failure consequences, bridge severance consequences, cascade-triggering scenarios. | Cascade analysis completion; contingency and recovery planning. |
| Interface Inventory | Map Bridging interfaces (where bridges are critical and under-supported), Clustering interfaces (inter-cluster friction and information barriers), Hub Governance interfaces (control and accountability structures). | Interface analysis completion. |

**Gate Question (pre-closure check):** Have we mapped focal network topology, classified into six meta-categories, assessed critical dimensions (Density, Centrality Distribution, Clustering, Resilience, Visibility Asymmetry), identified cascade pathways and bottlenecks, mapped bridges and isolated nodes, designed interface governance, run Tier 1 Hiddens scan, and escalated any high-consequence Unknowns to appropriate frameworks (Hiddens, Risk, Resilience)?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Situations Context Classification (what situation type makes which network topologies relevant?)
- Boundaries (what organizational or jurisdictional boundaries define the network scope?)
- Agents & Personas (who are the nodes; what are their capabilities and constraints?)
- Power & Influence (who has power through network position; what are influence asymmetries?)
- Communication (what types of connections/edges matter; what flows through network?)
- Evidence (what evidence exists about network topology, flows, and cascade behaviour?)

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Framework of Hiddens (network-specific Hiddens detection and remediation design)
- Framework of Risk (cascade risk, bottleneck risk, hub failure risk, bridge severance risk)
- Framework of Resilience (network redundancy, failover mechanisms, cascade containment)
- Framework of Governance (topology-aware governance; hub accountability; bridge recognition)
- Framework of Interventions (topology-aware intervention design; network rewiring; redundancy insertion)
- Framework of Communication (information flow design; bridge capacity; signal fidelity)
- Framework of Responsibility (accountability for critical nodes; bridge-occupant recognition)

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Scan 6: Network topology and cascade risk | Map network structure; identify cascade pathways; assess bottleneck and hub failure consequences; design cascade containment. |
| Scan 8: Bridge role invisibility and structural hole power | Identify bridges and structural holes; map their criticality; assess whether bridge-occupants understand their role; design bridge recognition and support. |
| Scan 13: Echo chamber and information isolation | Assess cluster boundaries; evaluate inter-cluster bridges; test whether disconfirming information crosses clusters; design information injection or bridge reinforcement. |

---

*LLM Execution Extract v1.0 – Networks Framework (2026-04-09) – End of Extract*
