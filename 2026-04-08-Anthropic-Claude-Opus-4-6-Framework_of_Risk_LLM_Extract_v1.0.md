# Framework of Risk – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Risk |
| Primary group | G6 — Action & control (Action & Control) |
| Secondary group | None |
| Stage | Downstream (Control) |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Risk framework classifies hazards, failure modes, and consequences through six meta-categories and thirty core types, profiles risk across five dimensions (probability, impact, detectability, controllability, cascade potential), maps ten dynamics of how risks evolve and hide, and surfaces risk-specific visibility failures via tiered Hiddens scans. It enables explicit risk inventory, tail-risk and low-probability-high-consequence event identification, cascade and coupling analysis, risk-control mechanism design, and transparent risk acceptance decisions. It supports both quantitative probabilistic risk assessment and qualitative scenario-based risk analysis, enabling decision-making under uncertainty with explicit risk trade-offs and residual risk acceptance.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Risk when… | Use neighbour instead when… |
|---|---|---|
| Uncertainties | You need to identify and characterise what could go wrong; focus on adverse consequence space and failure scenarios | You need to characterise what is unknown about states/mechanisms/futures; focus on Unknown structure independent of risk |
| Interventions | You need to assess risks and unintended consequences of specific interventions; focus on intervention-specific risk profile | You need to design what an intervention will do and how it works; focus on intervention mechanism independent of risk |
| Governance | You need to design controls, oversight, and escalation as risk-mitigation mechanisms; focus on risk governance | You need to design authority, accountability, and transparency structures; focus on governance independent of specific risk context |
| Diagnosis | You need to understand failure mechanisms and cascade pathways; focus on how failures occur and propagate | You need to identify root causes of current problems; focus on causality independent of failure mode scenarios |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Hazard Types | Natural Hazard, Technical Hazard, Human-Factor Hazard, Organisational Hazard, Systemic-Coupling Hazard | What type of adverse event could occur and what would trigger it? |
| II. Failure Modes & Cascade | Single-Point Failure, Cascading Failure, Common-Cause Failure, Feedback-Loop Amplification, Network Cascade | How could the system fail and would failure cascade to other domains? |
| III. Probability & Distribution | Known-Probability Risk, Estimated-Probability Risk, Tail-Risk/Low-Probability, Black-Swan/Unprecedented, Uncertainty-Dominated Risk | How likely is this adverse event and is probability well-characterized or deeply Unknown? |
| IV. Impact & Consequence | Local Impact, System-Level Impact, Reversibility-High Impact, Existential Impact, Compounding Impact | What would be the consequences if this adverse event occurred? |
| V. Controllability & Mitigation | Preventable Risk, Mitigable Risk, Manageable Risk, Acceptable Risk (with controls), Uncontrollable Risk | What controls or mitigation mechanisms exist and how effective are they? |
| VI. Detection & Adaptation | Early-Warning Detectability, High-Detectability Risk, Low-Detectability Risk, Latent-Failure Risk, Rapid-Escalation Risk | How detectable is this risk and how quickly would escalation occur? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature | Mechanism | Consequence |
|---|---|---|---|
| Risk normalisation and controls decay | Risk initially managed with active controls; controls become routine; maintenance atrophies; risk re-emerges dormant | Habituation and normalisation; cost deferral; monitoring fatigue; absence of recent incident; incentive to reduce vigilance | Controls fail when risk triggers; surprise when dormant risk manifests; capacity for detection and response degraded |
| Tail-risk blindness | Low-probability high-consequence events not planned for; focus on expected-case scenarios; tail events treated as impossible | Base-rate bias; optimism bias; difficulty of tail-event planning; incentive to ignore small-probability threats | Rare events not prepared for; surprise asymmetry (bad surprises > good surprises); resilience concentrated in wrong outcomes |
| Risk coupling and correlation | Risks appear independent but share common causes; risks correlated; shock to one triggers multiple failure modes simultaneously | Common infrastructure dependencies; shared assumptions; economic correlation; systemic coupling | Single-event cascade; multiple-failure simultaneity; resilience insufficient for compound risk; recovery from multi-factor failure harder |
| Black-swan surprise and post-hoc "unforseeable" claims | Unprecedented event occurs; claimed as unforeseeable; post-hoc rationalisation; actual foreseeable signals missed | Novelty bias (unprecedented treated as unforeseeable); failure of weak signals to trigger escalation; risk blind spots | Repeated black-swan "surprises" that share common precursors; institutional learning blocked; accountability disputes |
| Risk cascade and amplification | Initial small risk triggers protective responses which amplify initial risk; feedback loops amplify rather than dampen | Panic responses; rational local responses create irrational system response; herding dynamics; feedback amplification | Controlled risk spirals into uncontrolled cascade; initial response effectiveness decreases; system overshoots and undershoots |
| Monitoring complacency and gap | Monitoring systems drift from critical parameters; early warning mechanisms disabled; gap between monitored and actual risk | Monitoring perceived as low value; signals ignored until crisis; false reassurance from monitoring; cost reduction pressure | Risk escalates undetected; early intervention window closes; response must be crisis-mode; post-hoc "we didn't know" claims |
| Scenario blindness and missing failure modes | Known-failure-mode planning; genuinely novel failure modes not anticipated; risk register captures known risks only | Difficulty of unknown-failure-mode identification; anchoring on prior failure scenarios; incentive to focus on known risks | Novel failure occurs; unplanned responses; post-hoc hindsight bias ("we should have seen it"); repeated novel failures from same blindspot |
| Control effectiveness degradation | Control mechanisms effective initially; effectiveness erodes through wear, drift, or operator adaptation; degradation unmonitored | Control maintenance deferred; effectiveness monitoring sporadic; operator shortcuts normalise; incentive misalignment | Control fails when needed; false assurance from belief control is effective; degradation invisible until failure occurs |
| Risk transfer and moral hazard | Risk transferred to different party; insured party reduced incentive for risk reduction; moral hazard emerges | Insurance or hedging creates incentive misalignment; risk transfer creates hidden-incentive problem; transfer not complete | Transferred party accumulates risk beyond capacity; transferred party fails; original risk borne by unanticipated party |
| Risk acceptance threshold drift | Risk acceptance initially clear; tolerance level increases; "acceptable" risk grows; threshold erosion invisible | Normalisation of deviance; cost pressure; incident-free period creates confidence increase; institutional tolerance growth | Acceptance threshold exceeds actual risk tolerance; crisis occurs in accepted-risk zone; post-crisis accountability confusion; reset and learning failure |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question |
|---|---|
| I (Perceptual) | What failure modes or hazards are not anticipated; what risk signals are being missed due to attention or monitoring gaps? |
| II (Systemic) | How do systemic couplings and feedback loops create cascade risk; what common-cause failures are unrecognised? |
| III (Informational) | What risk information is not accessible; what monitoring data is hidden or not acted upon; what early warnings are suppressed? |
| IV (Temporal) | What long-term tail risks are discounted or invisible; what trend changes would reveal growing risk but are not monitored? |
| V (Relational) | Who is aware of risk but remains silent due to retaliation risk or psychological safety concerns; what dissent about risk is suppressed? |
| VI (Ontological) | What risk paradigm or model forecloses certain failure modes; what is treated as impossible within current frame? |

### 6b. Primary Hiding Mechanisms

- Tail-risk blindness (low-probability high-consequence events not planned; focus on expected case)
- Common-cause failure invisibility (risks appear independent but share causes; cascade not anticipated)
- Monitoring gap and signal suppression (early warnings missed or suppressed; monitoring complacency)
- Control-effectiveness invisibility (controls degrade unmonitored; false assurance of protection)
- Black-swan surprise (unprecedented event claimed unforeseeable; actual signals missed)
- Risk-transfer moral hazard (incentive misalignment from insurance/hedging; hidden risk)
- Scenario blindness (known-failure planning misses novel failure modes)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Tail-risk blindness | Framework of Risk (tail-risk assessment); Framework of Uncertainties | Scenario analysis; low-probability-event planning; resilience design for tail events | Design for tail-risk scenarios; include low-probability high-consequence events in planning |
| Common-cause failure or coupling | Framework of Systems; Framework of Risk | Coupling analysis; correlation assessment; failure-mode analysis for compound risk | Map system couplings; identify common-cause failures; design for decoupling or redundancy |
| Monitoring gap | Framework of Governance (monitoring redesign); Framework of Risk | Monitoring audit; critical-parameter identification; early-warning-signal design | Widen monitoring to critical parameters; reduce signal-to-noise; strengthen early warning |
| Control effectiveness drift | Framework of Governance; Framework of Risk (control audit) | Control-effectiveness testing; wear/drift assessment; maintenance schedule verification | Regular control-effectiveness auditing; scheduled maintenance; reduce complacency |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal domain or scenario; list 5–10 high-consequence failure modes or hazards.
2. For each hazard, estimate: probability (known, estimated, or Unknown), impact (scale of consequence), detectability (how obvious is risk before failure).
3. Run Tier 1 Hiddens scan: check for tail-risk blindness, common-cause failures, monitoring gaps, control-effectiveness complacency.
4. Identify 2–3 highest-risk hazards; assess cascade potential (would failure cascade to coupled systems).
5. Flag any high-probability high-impact or high-consequence low-probability risks for escalation to governance and mitigation design.

### 7b. Full Depth Execution (Complete framework run)

1. Conduct comprehensive hazard identification: map all significant failure modes across six meta-categories; classify each with core type.
2. Estimate probability-impact profile for each hazard: assess whether probability is known/estimated/Unknown; assess impact and reversibility.
3. Analyse failure cascades: for each high-consequence hazard, map potential cascades to coupled systems; assess compound-failure risk.
4. Assess control effectiveness: what controls exist for each hazard; how effective are controls; what is control-maintenance status?
5. Evaluate tail-risk and low-probability-high-consequence events: design scenario-based analysis for events outside normal probability models.
6. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence or high-uncertainty risk, identify detection interface (how to surface early) and mitigation interface (how to reduce).
7. Produce risk register with probability-impact matrix; identify critical controls; recommend monitoring, mitigation, and acceptance decisions.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Risk Register | Document all hazards, failure modes, probability-impact profile, cascade potential, control status, mitigation requirements | After hazard analysis |
| Hypothesis/Test Backlog | Propose tests for control effectiveness; design early-warning-system effectiveness testing; scenario-validation tests | For high-risk hazards with Unknown probability or control effectiveness |
| Governance Documentation | Specify monitoring frequency, critical-parameter thresholds, escalation triggers, reversal authority for risk-acceptance decisions | For all high-consequence risks and risk-acceptance thresholds |

**Gate Question (pre-closure check):** Have we identified all significant hazards, assessed probability-impact, analysed cascade potential, evaluated control effectiveness, run Tier 1 Hiddens scan for tail-risk blindness and monitoring gaps, and escalated high-consequence or unknown-probability risks to governance and mitigation design?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs

- Uncertainties (Unknown probability and impact of events)
- Interventions (intervention-specific risks and unintended consequences)
- Systems (system structure and coupling affecting cascade risk)
- Technology (technology failure modes and dependencies)
- Causation (failure mechanisms and causal chains)

### 8b. Downstream Handoffs

- Framework of Governance (risk governance, controls, monitoring, escalation, acceptance decisions)
- Framework of Interventions (risk mitigation through intervention design)
- Framework of Learning & Adaptation (learning from near-misses and actual failures)
- Framework of Metrics (early-warning metrics and control-effectiveness monitoring)

### 8c. Targeted Scans

| Targeted Scan | Role of this framework |
|---|---|
| Tail-Risk & Cascade Scan (Family A, Scan 5) | Identify low-probability high-consequence events; analyse cascade pathways; assess compound-failure risk |
| Control-Effectiveness & Monitoring Scan (Family C, Scan 6) | Audit control mechanisms; test effectiveness; assess monitoring coverage and signal-quality |
| Black-Swan & Novel-Failure-Mode Scan (Family D, Scan 6) | Identify scenario blindness; test for genuinely novel failure modes; surface unplanned risks |

---

*LLM Execution Extract v1.0 – Risk Framework (2026-04-08) – End of Extract*
