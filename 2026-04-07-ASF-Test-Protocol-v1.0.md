# Analytical Series of Frameworks — Test Protocol
**Testing Whether the ASF Finds What Is Invisible**

---

## Document Information

| Field | Value |
|---|---|
| Document name | ASF Test Protocol |
| Version | v1.0 |
| Date | 2026-04-07 |
| Status | Draft — Ready for Use |
| Primary purpose | Provide a structured, repeatable test method by which Claude (or a human analyst) can verify that the Analytical Series of Frameworks (ASF) reliably surfaces invisible issues across complex social, socio-technical, and technical scenarios. |
| Companion documents | Analytical Series Operating Guide v2.5; all 36 framework documents |
| Intended users | Claude (autonomous test executor); human testers who specify test scenarios; series maintainers evaluating completeness and coverage |

---

## At-a-Glance

| Question | Answer |
|---|---|
| What does this protocol test? | Whether the ASF can find hiddens — issues that are invisible to naive observation — across six analytic dimensions and all 36 frameworks. |
| What is the core challenge? | You cannot straightforwardly test an instrument for finding invisible things by looking for what is visible. The protocol solves this by using **planted hiddens** — known issues embedded in constructed scenarios — and measuring what the ASF surfaces versus what was hidden. |
| How are tests structured? | Three test types: **Unit Tests** (single framework), **Integration Tests** (cross-framework), and the **Meta-Validation Test** (ASF applied to itself). |
| Who determines the scenarios? | Claude determines scenarios from a coverage matrix ensuring all 36 frameworks are exercised. Humans may also specify a brief topic and Claude constructs the full scenario. |
| What is the final validation? | The ASF is applied to itself: "What hiddens exist in the framework's own approach to finding hiddens?" This is the highest-order test and the most structurally important. |

---

# Part 1 — Test Architecture

## 1.1 The Core Problem: Testing a Visibility Instrument

Testing whether a framework finds invisible things requires a method that is not itself subject to the same blindness. This protocol uses three safeguards:

**Planted hiddens**: Scenarios are constructed with deliberate hiddens at known locations, types, and mechanisms. The reference answer specifies exactly what the ASF is expected to find. The tester (Claude) runs the ASF without seeing the reference answer, then the output is scored against it.

**Coverage matrix**: Each of the 36 frameworks is mapped to at least one test scenario. If the ASF misses a hidden in a scenario designed to trigger a specific framework, that is evidence of a gap in that framework's contribution.

**Self-application**: The meta-validation test runs the ASF on itself, exposing structural limits, paradigm assumptions, and institutionalised blind spots that no external test scenario can reveal.

## 1.2 Test Types

### Type 1 — Unit Tests (single-framework activation)
A scenario in which **one specific framework is the critical lens** for finding a planted hidden. Tests whether that framework activates correctly, identifies the mechanism, and proposes detection/remediation moves.

*Pass criterion*: The framework is routed to (or self-selects), the hidden is classified with the correct mechanism type, and at least one detection probe is proposed.

### Type 2 — Integration Tests (cross-framework combination required)
A scenario in which **no single framework is sufficient** to surface a planted hidden — two or more frameworks must be combined and their outputs connected. Tests the series' ability to avoid "single-lens closure."

*Pass criterion*: The ASF routing selects the required frameworks, the cross-framework connection is made explicit, and the hidden is surfaced in the combined output rather than missed in the gaps between framework outputs.

### Type 3 — Meta-Validation Test (ASF applied to itself)
The ASF is given a description of itself as the scenario. The question is: "What hiddens exist in this framework's approach to finding hiddens?" Tests reflexivity, structural self-awareness, and paradigm honesty.

*Pass criterion*: At least one hidden is identified in each of the six G-groups (framing, mechanism, agency, meaning, epistemics, action), the hiddens are classified using the 30-type taxonomy, and a non-defensive residual unknowns log is produced.

## 1.3 Scoring Rubric

Every test is scored on five dimensions:

| Dimension | What it measures | Score 0 | Score 1 | Score 2 |
|---|---|---|---|---|
| **Coverage** | Did the ASF find the planted hidden? | Not found | Partially found (mechanism missed or vague) | Fully found with mechanism identified |
| **Mechanism accuracy** | Was the hiding mechanism correctly classified? | Wrong type or no type | Correct family (e.g., Informational), wrong specific type | Correct 30-type classification |
| **Framework routing** | Was the correct framework activated? | Wrong framework or none | Correct group, wrong specific framework | Correct specific framework(s) activated |
| **Detection probe** | Was a concrete probe/test proposed? | None proposed | Vague or unfocused probe | Discriminating probe (would produce different results if hidden vs not) |
| **Remediation** | Was a remediation or governance action proposed? | None | Generic (e.g., "improve communication") | Mechanism-specific and actionable |

**Maximum score per hidden**: 10 points
**Test pass threshold**: ≥ 7/10 for each planted hidden (70%)
**Series pass threshold**: ≥ 70% of all planted hiddens across the full scenario bank scored at ≥ 7/10

## 1.4 Precision Control (False Positive Management)

The ASF may identify many candidate hiddens in a scenario. Not all of them are "real" (planted). To prevent inflated scores from lucky guessing:

- The tester records all hiddens identified by the ASF.
- Hiddens in the reference answer score on the full rubric above.
- Each "false positive" (hidden identified that is not in the reference answer and not evidenced from the scenario text) deducts 0.5 points from the test's total score.
- Hiddens that are not in the reference answer but are **well-evidenced** from the scenario text (legitimate additional findings) are flagged as "bonus findings" and do not penalise.

---

# Part 2 — Framework Coverage Matrix

## 2.1 The 36 Frameworks and Their Required Scenario Coverage

Each framework must appear as a **critical lens** in at least one test scenario. A framework is "critical" if removing it from the analysis would cause a planted hidden to be missed.

| # | Framework | Group | Stage | Critical in Scenario | Test Type |
|---|---|---|---|---|---|
| 1 | Situations Context Classification | G1 | Upstream | S-G1A | Unit |
| 2 | Boundaries | G1 | Upstream | S-G1A | Unit |
| 3 | Dimensions | G1 | Upstream | S-G1B | Unit |
| 4 | Realities | G1 | Upstream | S-G1B | Unit |
| 5 | Scale | G1 | Upstream | S-G1A | Unit |
| 6 | Time | G1 | Upstream | S-G1A | Unit |
| 7 | Systems | G2 | Middle | S-G2A | Unit |
| 8 | Relations | G2 | Middle | S-G2A | Unit |
| 9 | Processes | G2 | Middle | S-G2B | Unit |
| 10 | Causation | G2 | Middle | S-G2B | Unit |
| 11 | Resources | G2 | Middle | S-G2A | Unit |
| 12 | Agents | G3 | Middle | S-G3A | Unit |
| 13 | Personas | G3 | Middle | S-G3A | Unit |
| 14 | Incentives | G3 | Middle | S-G3A | Unit |
| 15 | Power | G3 | Middle | S-G3B | Unit |
| 16 | Responsibility | G3 | Middle | S-G3B | Unit |
| 17 | Competencies | G3 | Middle | S-G3B | Unit |
| 18 | Culture and Norms | G4 | Middle | S-G4A | Unit |
| 19 | Perspectives | G4 | Middle | S-G4A | Unit |
| 20 | Narratives | G4 | Middle | S-G4A | Unit |
| 21 | Communications | G4 | Middle | S-G4B | Unit |
| 22 | Legitimacy | G4 | Middle | S-G4B | Unit |
| 23 | Values | G4 | Middle | S-G4B | Unit |
| 24 | Beliefs | G5 | Middle | S-G5A | Unit |
| 25 | Evidence | G5 | Cross-cutting | S-G5A | Unit |
| 26 | Uncertainties | G5 | Cross-cutting | S-G5B | Unit |
| 27 | Failures | G5 | Cross-cutting | S-G5B | Unit |
| 28 | Hiddens | G5 | Cross-cutting | S-META | Meta |
| 29 | Diagnosis | G5 | Middle | S-G5A | Unit |
| 30 | Metrics | G5 | Cross-cutting | S-G5B | Unit |
| 31 | Knowledge | G5 | Cross-cutting | S-G5A | Unit |
| 32 | Decisions | G6 | Downstream | S-G6A | Unit |
| 33 | Interventions | G6 | Downstream | S-G6A | Unit |
| 34 | Governance | G6 | Downstream | S-G6B | Unit |
| 35 | Risk | G6 | Downstream | S-G6B | Unit |
| 36 | Learning and Adaptation | G6 | Downstream | S-G6A | Unit |

**Integration test scenarios** (requiring cross-framework combination):
- S-INT-1: G1 + G3 combination (framing error concealing an agency hidden)
- S-INT-2: G2 + G5 combination (mechanism hidden revealed only through epistemic analysis)
- S-INT-3: G3 + G4 combination (incentive-narrative feedback loop)
- S-INT-4: G5 + G6 combination (evidence failure producing governance failure)
- S-INT-5: Full-spectrum (G1 through G6, all groups required)

---

# Part 3 — Built-In Scenario Bank

Each scenario below specifies: the presenting situation, the planted hiddens (with their type, mechanism, and the detecting framework), and the reference answer. **When running a test, Claude reads only the scenario description (not the planted hiddens section) and runs the ASF. The planted hiddens section is the reference answer consulted only for scoring.**

---

## Scenario S-G1A — "The Commuter Rail Crisis"
**Topic**: Urban rail delays
**Primary frameworks tested**: Situations Context Classification, Boundaries, Scale, Time
**Test type**: Unit (G1)

### Scenario Description (given to Claude for testing)

A city's metropolitan rail authority is experiencing a 35% increase in service delays over the past 14 months. The authority's internal operations team has launched a "Service Reliability Improvement Programme," focusing on driver scheduling, signalling maintenance cycles, and rolling stock turnaround times at the central terminus. The CEO has commissioned a 6-week diagnostic investigation. Available evidence includes: passenger delay statistics; driver rota logs; maintenance records for the past 3 years; and a customer satisfaction survey (conducted 8 months ago, response rate 12%).

**Presenting problem**: Service delays are increasing and existing operational interventions have not resolved them.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present in this scenario?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G1A-1 — Boundary Error**
- Type: Informational / Perceptual — positional limit
- Mechanism: The investigation is scoped to the central terminus and operations team's control zone. The root cause of 60% of delays is a junction failure at a feeder line 28 miles out — which falls under a different authority's operational remit and is not included in any of the available evidence sources.
- Detecting framework: Boundaries (G1) — boundary map exercise would reveal that the highest-impact causal node lies outside the stated scope.
- Detection probe: Ask "Where do delays originate geographically?" and map against the investigation boundary. Compare delay origination points to scope boundary.
- Remediation: Expand boundary to include the feeder network; establish joint working group with the adjacent authority.

**Hidden G1A-2 — Situation Misclassification**
- Type: Perceptual — category error
- Mechanism: The situation is classified as an "operational reliability problem." The actual situation type is a "deferred capital investment failure" — a governance and funding problem that has been accumulating for 11 years and will not respond to operational interventions. The Situations Context Classification framework's distinction between operational, structural, and governance failures is the critical lens.
- Detecting framework: Situations Context Classification (G1)
- Detection probe: Test whether delay trends respond to operational interventions. If no improvement after 6 months of operational changes, reclassify as structural/governance.
- Remediation: Reframe the investigation as a capital planning review; engage funding authority.

**Hidden G1A-3 — Temporal Scope Error**
- Type: Temporal — history invisibility
- Mechanism: The investigation covers 3 years of maintenance records. The degradation cycle began 11 years ago after a capital reinvestment decision was deferred. The critical causal data is outside the evidence window.
- Detecting framework: Time (G1) — time horizon audit would reveal that 3 years of records cannot capture an 11-year degradation process.
- Detection probe: Request 15-year trend data on capital expenditure vs. delay rates.
- Remediation: Extend the evidence window to encompass the full investment cycle.

**Hidden G1A-4 — Scale Invisibility**
- Type: Systemic — scale mismatch
- Mechanism: The investigation operates at the operational (day-to-day scheduling) scale. The problem has macro-scale (city-wide infrastructure investment policy) and micro-scale (individual component failure patterns) dimensions that are invisible at the chosen scale of analysis.
- Detecting framework: Scale (G1) — scale audit would require examining city infrastructure spending patterns (macro) and component-level failure data (micro).
- Detection probe: Obtain component-level failure logs and map them against infrastructure investment cycles at the city policy level.
- Remediation: Run analysis at three scales simultaneously; report findings at each scale before synthesising.

---

## Scenario S-G1B — "The Strategy That No One Challenged"
**Topic**: Organisational strategy failure
**Primary frameworks tested**: Dimensions, Realities
**Test type**: Unit (G1)

### Scenario Description

A mid-sized professional services firm launched a "Digital Transformation Strategy" 18 months ago. The strategy was developed by the senior leadership team with support from an external consultancy. It projected 40% revenue growth from new digital products within 3 years. At the 18-month mark, revenue from new digital products represents 2% of total revenue. The leadership team attributes this to "slower-than-expected market adoption." The strategy document, board presentations, and quarterly business reviews are available. A staff engagement survey (conducted 6 months ago) shows 72% of staff feel "proud to work here." Key leaders express continued confidence in the strategy.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G1B-1 — Dimensional Invisibility (political/financial dimensions excluded)**
- Type: Informational — scope limit
- Mechanism: The strategy was developed across commercial and technical dimensions only. The political dimension (internal power dynamics between practice leaders who lose revenue under the new model) and the financial dimension (margin impact of cannibalisation on existing services) were never included in the analysis. These dimensions are not absent from reality — they are absent from the analytical frame.
- Detecting framework: Dimensions (G1) — dimensions audit would list all relevant dimensions and check which are absent from available evidence.
- Detection probe: Map which dimensions are represented in the strategy document vs. which dimensions exist in the firm's operating environment.
- Remediation: Run a dimensions audit before the next strategy review; commission a cannibalisation impact model.

**Hidden G1B-2 — Multiple Realities**
- Type: Perceptual — positional and reality divergence
- Mechanism: Leadership's operational reality is shaped by external consultancy benchmarks, board presentations, and peer comparison. Staff's operational reality is shaped by day-to-day client delivery pressures, unchanged performance management systems, and lack of capability for digital product work. These are two functionally different realities in the same organisation. The 72% staff pride score conceals this bifurcation because pride does not measure alignment with the strategy.
- Detecting framework: Realities (G1) — realities mapping would surface the gap between the leadership reality and the delivery workforce reality.
- Detection probe: Interview frontline delivery staff about what they spend their time on and what they are measured against. Compare to the digital strategy's capability requirements.
- Remediation: Map realities explicitly; create a mechanism for the delivery reality to inform strategic decisions.

**Hidden G1B-3 — The Consultancy Confidence Mirage**
- Type: Informational — source distortion
- Mechanism: The strategy's projections were built on external benchmarks from larger organisations in different markets. These benchmarks were presented as directly applicable. The confidence in the projections derives from the consultancy's reputation rather than evidence quality. The consultancy's continued involvement means they are unlikely to surface this distortion themselves.
- Detecting framework: Evidence (G5) — evidence grading would classify the benchmark data as low-quality analogues and the projections as assumptions, not facts.
- Detection probe: Ask for the primary sources behind the benchmark projections. Test whether source organisations are comparable on 5+ dimensions.
- Remediation: Commission an independent evidence review of the projections; reclassify all projection assumptions as uncertainties in future board reporting.

---

## Scenario S-G2A — "The Platform That Slowed Down"
**Topic**: Software infrastructure performance degradation
**Primary frameworks tested**: Systems, Relations, Resources
**Test type**: Unit (G2)

### Scenario Description

A financial technology company's core payment processing platform has experienced a 40% increase in transaction processing time over 22 months. Six engineering "performance improvement" sprints have been run. Each produced short-term improvement of approximately 8–12%, followed by regression to pre-sprint levels within 6–8 weeks. The platform comprises 14 microservices, a shared message queue, two external data providers, and a legacy authentication module inherited from a 2019 acquisition. Available evidence: service-level monitoring dashboards (12-month retention), sprint retrospectives, and the last two quarterly architecture reviews.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G2A-1 — Hidden System Coupling**
- Type: Systemic — tight coupling with feedback
- Mechanism: The legacy authentication module (acquired 2019) creates a synchronous blocking call on every transaction. Under low load, this is invisible. Under high load, it becomes a ceiling. Each performance sprint has optimised other services without touching the authentication module (which is considered "stable" and out of scope for sprints). The result is a bounded ceiling that regenerates after each sprint as traffic volumes recover.
- Detecting framework: Systems (G2) — coupling analysis would identify the synchronous blocking dependency; containment check would surface that the authentication module's performance degrades non-linearly under load.
- Detection probe: Load test the platform while isolating the authentication module call. Measure what % of total transaction time is consumed by authentication under various load levels.
- Remediation: Decouple authentication via asynchronous token caching; move authentication module to sprint scope.

**Hidden G2A-2 — Shared Resource Contention**
- Type: Systemic — hidden resource constraint
- Mechanism: The shared message queue is used by both the payment processing path and the fraud detection service. Under high payment volume, fraud detection jobs are deprioritised by the queue. Fraud signals arrive late, triggering compensating transactions that create a second load peak. This feedback loop is invisible in monitoring dashboards because each service is monitored independently.
- Detecting framework: Resources (G2) — shared resource audit would surface that the message queue is a single shared resource across latency-critical and latency-tolerant workloads.
- Detection probe: Monitor the message queue at the partition level, distinguishing payment vs. fraud detection traffic. Measure lag correlation with processing time peaks.
- Remediation: Separate message queues for latency-critical and latency-tolerant traffic; implement fraud detection fallback mode under high load.

**Hidden G2A-3 — Invisible Dependency on External Data Providers**
- Type: Relational — hidden external dependency
- Mechanism: One of the two external data providers (used for currency rate lookup) introduced a rate-limit policy 24 months ago. The platform's caching layer masks this most of the time, but during high-volatility periods, cache miss rates spike, creating direct calls to the rate-limited provider. The 12-month monitoring retention does not include the initial 2-month period after the rate-limit policy was introduced, so the dependency has never been visible in available data.
- Detecting framework: Relations (G2) — external dependency mapping would surface the rate-limit policy as a hidden constraint on the platform's behaviour under specific conditions.
- Detection probe: Obtain the external provider's API rate limit documentation. Correlate currency volatility events with processing time spikes in historical data.
- Remediation: Implement circuit breaker for external provider calls; negotiate rate limit increase or add a secondary provider.

---

## Scenario S-G2B — "The Process That Worked Until It Didn't"
**Topic**: Operational process failure
**Primary frameworks tested**: Processes, Causation
**Test type**: Unit (G2)

### Scenario Description

A pharmaceutical manufacturing facility has experienced three batch failures in the past 8 months. Each batch failure involved contamination at a different stage of the production process. Internal audits following each failure identified "human error" as the proximate cause. Corrective actions (retraining, updated SOPs, enhanced checklist completion) were implemented after each audit. The facility has a 6-year clean regulatory record. The Quality Director is facing regulatory scrutiny and has commissioned an independent review. Available evidence: the three audit reports, SOPs, training records, regulatory inspection reports (last 3 years), and batch records.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G2B-1 — Causal Depth Error (proximate displacing distal)**
- Type: Systemic — causal masking
- Mechanism: All three audits attributed failure to human error. This is the proximate cause in each case. The distal cause — a 3-year HVAC upgrade programme that changed airflow patterns in three production zones — is not visible in the audit reports because audits are scoped to the immediate failure event. The HVAC programme sits under Facilities, not Quality, and is not included in the available evidence set.
- Detecting framework: Causation (G2) — causal chain extension would push past proximate causes to ask "what enabled the human error?" and "what changed in the environment 3 years ago?"
- Detection probe: Map the spatial distribution of contamination events against the HVAC upgrade sequence and timing. Request Facilities records for the production areas affected.
- Remediation: Include Facilities as a standing participant in quality audits; require environmental causation review in all batch failure investigations.

**Hidden G2B-2 — Process-Reality Divergence**
- Type: Informational — process documentation vs. actual practice
- Mechanism: The SOPs describe a process that was valid 4 years ago. Following a staffing restructure 18 months ago, frontline staff developed "workarounds" to maintain throughput under staffing constraints. The workarounds are now the de facto process, but the documented process is the official one. Retraining reinforces the documented (non-actual) process, creating a growing gap.
- Detecting framework: Processes (G2) — process-as-documented vs. process-as-practiced audit would surface the divergence.
- Detection probe: Conduct blind observation of actual process steps taken by staff during a production run. Compare step-by-step against the SOP. Specifically look for adaptations under time pressure.
- Remediation: Run a process reconciliation exercise to document actual practice; update SOPs based on what actually works; address underlying staffing constraints.

---

## Scenario S-G3A — "The Safety Numbers That Didn't Add Up"
**Topic**: Pharmaceutical adverse event reporting
**Primary frameworks tested**: Agents, Personas, Incentives
**Test type**: Unit (G3)

### Scenario Description

A pharmaceutical company's pharmacovigilance (adverse event reporting) data shows a 23% decline in adverse event reports over the past 3 years across its top-selling product line. The regulatory affairs team cites this as evidence of improved product safety. The regional sales force reports high levels of "physician engagement." A new Compliance Director, reviewing the data before signing the annual regulatory submission, notices that the decline correlates with the introduction of a new sales incentive structure 3 years ago, which weighted quarterly sales targets heavily. She has 4 weeks to investigate before the regulatory deadline.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G3A-1 — Incentive Suppression of Adverse Event Reporting**
- Type: Relational — incentive-induced suppression
- Mechanism: The sales incentive structure creates financial risk for sales reps who surface adverse events: doing so requires them to log the event (which delays their sales visit), may create negative physician associations with the product, and does not contribute to quarterly targets. Reps have not been instructed to suppress reporting; the incentive structure creates suppression as a rational emergent behaviour without any explicit decision.
- Detecting framework: Incentives (G3) — incentive mapping would identify that the incentive structure makes reporting personally costly with no compensating reward.
- Detection probe: Compare adverse event report volumes by sales rep against their quarterly sales ranking. Test whether high performers under the incentive scheme are reporting fewer events than low performers.
- Remediation: Redesign incentive structure to include adverse event reporting quality as a metric; implement independent reporting channel not mediated by sales reps.

**Hidden G3A-2 — Agent Misclassification (sales rep as reporter)**
- Type: Informational — agent role confusion
- Mechanism: The system treats sales reps as neutral information conduits for adverse event reports. In practice, they are agents with conflicting interests: commercial interests (product promotion) vs. pharmacovigilance interests (reporting harms). The agent type misclassification means the incentive problem (Hidden 1 above) was not anticipated in the reporting system design.
- Detecting framework: Agents (G3) — agent type taxonomy would classify sales reps as "dual-role agents with conflicting mandates" rather than "neutral reporters."
- Detection probe: Map all roles in the adverse event reporting pathway and identify which have commercial incentives that conflict with reporting accuracy.
- Remediation: Remove sales reps from the adverse event reporting chain; create a direct physician-to-pharmacovigilance reporting mechanism.

**Hidden G3A-3 — Persona Invisibility (three physician reporting behaviours)**
- Type: Perceptual — aggregation hiding population heterogeneity
- Mechanism: The aggregate adverse event decline obscures three distinct physician personas: Compliant reporters (who report through official channels, declining as sales rep mediates the process); pragmatic reporters (who mention events verbally to reps but don't document them); and resistant reporters (who stopped reporting years ago due to administrative burden). The aggregate metric treats all three as a single population, making it impossible to target interventions correctly.
- Detecting framework: Personas (G3) — persona analysis would surface the distinct reporting behaviours and their drivers.
- Detection probe: Conduct qualitative interviews with 15–20 physicians across therapeutic area. Ask how they would report an adverse event and whether they have seen events they did not report. Code responses into behavioural types.
- Remediation: Design three different reporting pathways matched to the three physician personas; track reporting volume by pathway.

---

## Scenario S-G3B — "The Change Programme Nobody Owned"
**Topic**: Organisational change failure
**Primary frameworks tested**: Power, Responsibility, Competencies
**Test type**: Unit (G3)

### Scenario Description

A national healthcare agency launched an "Electronic Patient Records Transformation" programme 2 years ago. Budget: £85m. Timeline: 3 years. At the 2-year mark, the programme is 8 months behind schedule, 30% over budget, and no clinical sites have been fully migrated. Three Programme Directors have departed in 18 months. A new Programme Director has been appointed and has been asked to produce a reset plan within 6 weeks. Available evidence: programme board minutes, the original business case, vendor contracts, and staff engagement survey results (60% "not confident the programme will succeed").

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G3B-1 — Power Vacuum Concealed by Structural Authority**
- Type: Relational — formal authority without actual power
- Mechanism: The programme board has formal authority over the programme. However, actual decision-making power over clinical site readiness sits with Clinical Directors who are not board members and are not contractually obligated to participate in the programme. The board has been making decisions that require Clinical Director cooperation without this cooperation being forthcoming. Three Programme Directors have departed partly because they had formal accountability but no actual power to compel the cooperation they needed.
- Detecting framework: Power (G3) — power mapping would separate formal authority from actual influence and identify the Clinical Directors as key power nodes not embedded in the governance structure.
- Detection probe: For each critical programme dependency, identify whose cooperation is required. Map whether those parties have formal programme accountability. Identify gaps.
- Remediation: Restructure programme board to include Clinical Director representatives with formal decision-making authority; revise governance to align formal accountability with actual power.

**Hidden G3B-2 — Responsibility Diffusion**
- Type: Relational — responsibility without accountability
- Mechanism: The programme business case assigned "implementation responsibility" to the agency's IT department, the vendor, and the clinical sites jointly. No single party has final accountability for site readiness. When delays occur, each party attributes the problem to another. The three Programme Directors each attempted to resolve the same circular responsibility dispute and departed when they could not.
- Detecting framework: Responsibility (G3) — responsibility matrix would surface the circular attribution pattern and identify the absence of a single accountable owner for site readiness.
- Detection probe: Ask each of the three responsible parties to describe who is responsible for site readiness on a specific failed milestone. Document the divergence.
- Remediation: Create a RACI matrix with a single Accountable party per deliverable; establish escalation mechanism where the accountable party has the authority to compel.

**Hidden G3B-3 — Competency Invisibility**
- Type: Informational — capability assumption
- Mechanism: The original business case assumed that clinical site staff would be able to learn the new system through a 2-day training programme. This assumption was never tested. In practice, the system requires users to understand data governance principles that clinical staff were not trained in and do not have. The competency gap is systematically invisible in programme reporting, which tracks training completion (the 2-day programme) rather than competency acquisition.
- Detecting framework: Competencies (G3) — competency gap analysis would distinguish between "training completed" and "competency acquired" and identify the specific gap in data governance understanding.
- Detection probe: Run a competency assessment (not training completion check) with 20 clinical staff at a pilot site. Measure ability to perform 5 key system tasks without support. Compare to the training programme's objectives.
- Remediation: Design competency-based assessment at programme entry and exit; revise training to address the data governance gap.

---

## Scenario S-G4A — "The Transformation Story"
**Topic**: Corporate transformation programme
**Primary frameworks tested**: Culture and Norms, Perspectives, Narratives
**Test type**: Unit (G4)

### Scenario Description

A large retail bank launched a "Customer-First Transformation" 18 months ago. Monthly executive presentations show improving NPS scores (up 12 points), reduced complaint volumes (down 18%), and strong "transformation engagement" from branch staff (85% completing optional learning modules). The CEO reports to the board that "we are genuinely becoming a different kind of bank." A new Non-Executive Director, reviewing the data before her first board meeting, notices that mortgage approval times have increased 35% and savings product opening times have increased 22% over the same 18-month period.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G4A-1 — Narrative Closure**
- Type: Informational — narrative suppression of dissonant signals
- Mechanism: The "Customer-First Transformation" narrative has become dominant enough that dissonant signals (slower operational processes, increased friction in product delivery) are reframed as acceptable transition costs rather than treated as performance data that questions the transformation's effectiveness. Staff who raise operational concerns are informally categorised as "not being on board with the transformation."
- Detecting framework: Narratives (G4) — narrative mapping would identify the dominant narrative, its maintenance mechanisms, and the signals it is suppressing. The "transition costs" reframe is a classic narrative-closure device.
- Detection probe: Ask 10 branch managers what they would say to a colleague who raised concerns about slower approval times. Identify whether the dominant framing is used to dismiss rather than engage with the concern.
- Remediation: Create a dedicated "dissonant signal" register maintained separately from the transformation narrative; require that operational performance data be presented raw, before any narrative framing.

**Hidden G4A-2 — Metric Selection Hiding Operational Decline**
- Type: Informational — metric choice as filter
- Mechanism: NPS and complaint volumes are the primary reported metrics. Both can improve simultaneously with genuine operational improvement and with operational slowing (customers who give up before completing a transaction don't complain; reduced expectations reduce NPS baseline). The slower approval and opening times are not primary metrics in the transformation scorecard and appear only in operational reports, which are not routinely presented to the board.
- Detecting framework: Perspectives (G4) — perspective rotation to the operational view (rather than the transformation view) would surface the processing time data as a primary signal of customer experience.
- Detection probe: Ask what a customer applying for a mortgage would experience at month 1 vs. month 18 of the transformation. Map the end-to-end customer journey against operational timing data.
- Remediation: Add end-to-end customer journey time as a primary transformation metric; present operational data in the same report as NPS.

**Hidden G4A-3 — Cultural Norm Preventing Upward Challenge**
- Type: Relational — norm suppression
- Mechanism: The "85% engagement" metric measures completion of optional learning modules — a low-threshold proxy for cultural alignment. The actual cultural norm in the branch network is "express enthusiasm for transformation in visible ways, raise concerns only through informal channels." This norm is not captured by engagement surveys and is reinforced by the organisational response to visible dissent.
- Detecting framework: Culture and Norms (G4) — norms audit would distinguish between stated norms (customer-first culture) and operative norms (visible compliance, private dissent).
- Detection probe: Run anonymous facilitated sessions in 3 branches asking: "What would happen if a branch manager said publicly that the transformation was making their job harder?" Code responses for norm-related risk perceptions.
- Remediation: Establish a protected challenge mechanism with non-retaliatory norms; include norm health as a standing item in transformation governance.

---

## Scenario S-G4B — "The Programme Nobody Questioned"
**Topic**: Public infrastructure project
**Primary frameworks tested**: Communications, Legitimacy, Values
**Test type**: Unit (G4)

### Scenario Description

A government agency has been running a £2.3bn infrastructure programme (national road network upgrade) for 4 years. Programme reports to ministers show "on track" delivery against a revised baseline (the original baseline was revised in year 2 after scope changes). A National Audit Office review is scheduled. The programme director has 6 weeks to prepare. Available evidence: quarterly programme reports, the year 2 scope change decision paper, independent assurance reports (two, in years 1 and 3), and a leaked staff survey showing 47% of programme staff "do not believe the programme will deliver value for money."

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G4B-1 — Communications Channel Breakdown**
- Type: Informational — channel failure
- Mechanism: The independent assurance reports (years 1 and 3) both identified concerns about benefit realisation. Both were submitted to the Programme Governance Board. However, the Board's communication protocol routes assurance reports to the programme director for "management response" before they reach ministers. Management responses have consistently reframed the concerns as "noted and addressed." Ministers have never read the unmediated assurance findings.
- Detecting framework: Communications (G4) — communications pathway audit would map what information reaches which decision-makers and identify where filtering/reframing occurs.
- Detection probe: Compare the assurance report text with the management response. Identify whether the management response accurately represents the assurance finding or reframes it.
- Remediation: Establish direct assurance-to-minister reporting channel with no management response intermediation; require independent assurance teams to present orally to ministers.

**Hidden G4B-2 — Legitimacy Erosion Hidden by Baseline Reset**
- Type: Temporal — accumulated erosion invisible to current snapshot
- Mechanism: The year 2 scope change reset the delivery baseline. This is formally acceptable. However, the cumulative effect is that the programme's legitimacy with frontline staff and some stakeholders rests on a series of rebaselined commitments, each of which eroded confidence incrementally. The "on track" current status is technically accurate against the revised baseline but operationally meaningless as a legitimacy claim because the baseline has moved twice. The 47% staff disbelief figure is the observable symptom.
- Detecting framework: Legitimacy (G4) — legitimacy audit would assess whether the programme's authority to claim "on track" delivery is accepted by its key stakeholders, and trace how each baseline reset affected that acceptance.
- Detection probe: Survey programme staff on whether "on track against current baseline" is a meaningful signal of programme health. Compare to public/minister understanding of programme status.
- Remediation: Publish a "cumulative delivery narrative" that shows the full history of baseline movements alongside current status; assess whether programme legitimacy can be re-established or requires a full reset.

**Hidden G4B-3 — Values Displacement**
- Type: Informational — stated vs operative values
- Mechanism: The programme's stated value is "infrastructure that serves the public." The operative value driving decision-making — visible in the year 2 scope change and in management responses to assurance — is "programme continuation and delivery against commitments made to ministers." These are not the same. When they conflict (as in the scope change), operative values win. This displacement is invisible in programme documentation because it is never made explicit.
- Detecting framework: Values (G4) — values mapping would surface the gap between espoused programme values and the values actually demonstrated in key decisions.
- Detection probe: For each major programme decision point (scope change, milestone reset, management response to assurance), ask: "What value was this decision optimising for?" Map against stated values.
- Remediation: Require explicit values alignment check at programme decision points; include "public value" as a decision criterion alongside delivery milestones.

---

## Scenario S-G5A — "The Chemical Plant's Clean Record"
**Topic**: Industrial safety
**Primary frameworks tested**: Beliefs, Evidence, Diagnosis, Knowledge
**Test type**: Unit (G5)

### Scenario Description

A chemical manufacturing plant has a 10-year clean safety record — zero lost-time incidents. The plant is preparing for regulatory approval of a capacity expansion. A new Safety Officer has been appointed and is conducting a pre-expansion review. She has access to: 10 years of incident records, training completion logs, the plant's safety management system documentation, maintenance records, and the last 3 regulatory inspection reports (all satisfactory). Two senior process engineers who have worked at the plant for 20+ years are due to retire in 6 months.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G5A-1 — Metric Gaming (Incidents vs. Lost-Time Incidents)**
- Type: Informational — metric distortion
- Mechanism: The "zero lost-time incidents" metric tracks incidents that result in time away from work. Over the past 4 years, a practice has developed of reclassifying incidents that would previously have been logged as lost-time incidents as "restricted duty" (keeping the worker on site in a reduced-duty role). This reclassification is not improper under current policy but has the effect of maintaining the clean record while actual incident severity has increased.
- Detecting framework: Evidence (G5) — evidence grading would surface the distinction between "lost-time incidents" and actual incident frequency/severity; provenance analysis would reveal the reclassification practice.
- Detection probe: Compare raw incident reports (before classification) against final safety record classifications for the past 5 years. Identify cases where severity assessment changed between initial report and final classification.
- Remediation: Implement severity-based incident tracking in addition to lost-time tracking; require that reclassification decisions above a severity threshold be countersigned by the Safety Officer.

**Hidden G5A-2 — Tacit Knowledge Concentration Risk**
- Type: Temporal — knowledge decay / concentration
- Mechanism: The safe operation of two legacy process units (chemical reaction vessels installed in 1998) relies on accumulated knowledge held by the two senior engineers retiring in 6 months. This knowledge includes non-documented process adjustments developed over 20 years ("when the pressure reading does X, reduce the flow to Y before the alarm triggers"). This knowledge is not in the safety management system, not in SOPs, and will leave with the engineers.
- Detecting framework: Knowledge (G5) — knowledge audit would identify tacit vs. explicit knowledge and surface concentration risk in retiring staff.
- Detection probe: Ask the two senior engineers to describe the last 5 occasions when they made a process adjustment that was not specified in the SOPs. Document what they did and why. Check whether this knowledge exists anywhere in written form.
- Remediation: Run a knowledge elicitation programme with the engineers before their retirement; update SOPs to capture tacit adjustments; implement a formal knowledge transfer protocol for all safety-critical role transitions.

**Hidden G5A-3 — Belief Stabilisation (the clean record as proof of safety)**
- Type: Perceptual — collective belief creating confirmation bias
- Mechanism: The 10-year clean record has created a collective belief that the plant is safe. This belief is functionally true but is also functioning as a filter: evidence that is inconsistent with the safe-plant belief (near-miss reports, maintenance anomalies, aging equipment indicators) is consistently interpreted as manageable rather than as signals of accumulating risk. The belief is not false — it is unfalsifiable in its current form.
- Detecting framework: Beliefs (G5) — belief audit would surface the "clean record = safe plant" belief and test whether it is held with appropriate conditionality or as an unfalsifiable commitment.
- Detection probe: Present the Safety Officer and senior management with 5 hypothetical scenarios involving near-misses and anomalies. Ask how they would respond. Test whether responses show openness to revising the "safe plant" belief or reflexive reassurance.
- Remediation: Introduce a "pre-mortem" discipline in safety reviews: require the team to construct a plausible scenario in which the clean record has been masking accumulated risk.

**Hidden G5A-4 — Diagnosis Anchoring on Human Error**
- Type: Perceptual — diagnostic mono-culture
- Mechanism: Review of the 10-year incident record shows that 80% of incidents were diagnosed as "human error." This is statistically improbable if the plant has genuinely improved safety systems, as safety science suggests that human error rates do not decline this steeply without systemic change. The diagnostic mono-culture — anchoring on human error — has prevented systemic causes from being surfaced.
- Detecting framework: Diagnosis (G5) — diagnostic diversity check would surface the statistical improbability of the human error distribution and require alternative causal hypotheses.
- Detection probe: Re-investigate 10 randomly selected "human error" incidents using a systems causation lens. Identify what systemic factors were present that contributed to the human error.
- Remediation: Mandate that all incident diagnoses include a systems causation component; track the ratio of human error vs. systemic causation findings over time.

---

## Scenario S-G5B — "The Model That Everyone Trusted"
**Topic**: Financial risk model failure
**Primary frameworks tested**: Uncertainties, Failures, Metrics
**Test type**: Unit (G5)

### Scenario Description

A large institutional fund manager uses a Value-at-Risk (VaR) model to manage portfolio risk. The model has been in use for 8 years and has been independently validated twice. The risk committee receives a daily VaR report. During a period of high market volatility (the "event"), the portfolio experienced losses 4.3 times larger than the model's 99th-percentile loss estimate. An internal review is underway. Available evidence: the VaR model specification, 8 years of daily VaR outputs vs. actual losses, the two independent validation reports, risk committee minutes (3 years), and the model developer's original assumptions documentation.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G5B-1 — Model Uncertainty Treated as Model Accuracy**
- Type: Perceptual — uncertainty laundering
- Mechanism: The VaR model produces a precise daily number (e.g., "£23.4m at 99% confidence"). Over 8 years, this precision has been treated as accuracy. The model's assumptions (normal distribution of returns, 10-day holding period, historical correlation data) are sources of structural uncertainty that were documented in the original specification but have not been reviewed since the market structure changed significantly in year 5. The precision of the output has concealed the uncertainty of the assumptions.
- Detecting framework: Uncertainties (G5) — uncertainty audit would distinguish between the model's expressed confidence and its structural uncertainty; deep uncertainty analysis would surface the assumption set that is no longer valid.
- Detection probe: Run the model under 5 alternative assumption sets (fat-tailed distributions, stress correlations, extended holding periods). Map the range of outputs. Compare to actual loss distribution.
- Remediation: Require an uncertainty envelope to accompany every VaR report; schedule annual assumption review against current market structure; adopt supplementary stress test metrics.

**Hidden G5B-2 — Failure Pattern Ignored (Recurring Exceedances)**
- Type: Temporal — pattern invisible due to normalisation
- Mechanism: Review of 8 years of VaR vs. actual loss data reveals that exceedances (actual losses exceeding VaR estimates) have been occurring at 1.4x the model's expected rate for the past 3 years. Each individual exceedance was reviewed and attributed to "market conditions" or "correlated events." The cumulative pattern — that the model has been systematically underestimating risk for 3 years — was never extracted from the incident-by-incident reviews.
- Detecting framework: Failures (G5) — failure pattern analysis would extract the cumulative exceedance rate and surface the 3-year trend as a pattern requiring explanation rather than incident-by-incident normalisation.
- Detection probe: Plot monthly exceedance rate against expected rate for all 8 years. Run a statistical test for systematic bias in the past 3 years. Present to risk committee as a pattern, not individual events.
- Remediation: Establish a rolling exceedance rate metric reviewed monthly; trigger model review when exceedance rate exceeds 1.2x expected for 3 consecutive months.

**Hidden G5B-3 — Metric Displacement (VaR replacing judgment)**
- Type: Informational — metric overreach
- Mechanism: The daily VaR report has become the primary — and in practice the only — risk metric reviewed by the risk committee. Risk managers who raised qualitative concerns ("this market regime is unusual; VaR may not capture it") during years 6 and 7 found their concerns noted but not acted upon because there was no mechanism to override or supplement a VaR number without comparable quantitative evidence. Qualitative judgment has been displaced by a single metric.
- Detecting framework: Metrics (G5) — metric dependency audit would surface the single-metric risk and the absence of a qualitative override mechanism.
- Detection probe: Review 3 years of risk committee minutes. Count how many qualitative risk concerns were raised. For each, determine whether any action was taken or whether VaR remained the deciding signal.
- Remediation: Introduce a structured qualitative risk escalation protocol alongside VaR; require explicit rationale when qualitative concerns are not acted upon.

---

## Scenario S-G6A — "The Intervention That Never Took Hold"
**Topic**: Hospital patient safety
**Primary frameworks tested**: Decisions, Interventions, Learning and Adaptation
**Test type**: Unit (G6)

### Scenario Description

A district general hospital has run four patient safety improvement programmes over 6 years, each following a serious adverse incident. Each programme produced measurable improvement in the targeted metric for 3–4 months, then regressed. The current Chief Medical Officer is preparing to launch a fifth programme. A clinical safety consultant has been engaged. Available evidence: the four programme plans and outcome data, serious incident reports (6-year period), staff survey results (rotating "safety culture" surveys), and NHS benchmarking data comparing this hospital to regional peers.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G6A-1 — Intervention Theory Never Tested**
- Type: Informational — untested assumption
- Mechanism: Each of the four programmes operated on an implicit theory of change: "improved protocols + retraining → sustained behavioural change → improved outcomes." This theory was never articulated, never tested, and never revised when programmes failed. The theory of change assumed that the primary barrier to safe behaviour was knowledge of correct protocols (addressed by training and SOPs). The actual barrier — workload pressure creating unsafe shortcuts — was identified in 3 of the 4 serious incident reports but never incorporated into the intervention theory.
- Detecting framework: Interventions (G6) — intervention theory analysis would make the implicit theory of change explicit and test its assumptions against available evidence.
- Detection probe: For each of the four programmes, articulate the theory of change (if X then Y because Z). Test assumption Z against the serious incident report data. Identify whether the assumed mechanism of change was actually operative.
- Remediation: Before launching Programme 5, explicitly state and test the theory of change; incorporate serious incident findings into intervention design; measure the assumed mechanism, not just the outcome.

**Hidden G6A-2 — Learning Not Institutionalised (Amnesia Cycle)**
- Type: Temporal — cyclical amnesia
- Mechanism: Following each of the four programmes, the clinical findings were filed in the programme report. However, there is no mechanism for these findings to inform the design of the next programme when it launches (typically 12–18 months after the previous one ended). Each new programme effectively restarts from scratch. Programme leaders changed between cycles (3 different CMOs in 6 years), and incoming leaders were not briefed on the learning from previous cycles.
- Detecting framework: Learning and Adaptation (G6) — learning loop audit would surface the absence of a formal mechanism for inter-programme learning and the structural amnesia created by leadership turnover.
- Detection probe: Ask the current CMO: "What did Programme 3 teach us that changed how Programme 4 was designed?" Assess whether there is a documented answer.
- Remediation: Create a Patient Safety Learning Register that persists across programme cycles; require that new programme design explicitly engage with findings from previous cycles; establish a handover protocol for incoming clinical leaders.

**Hidden G6A-3 — Decision Ritual Replacing Decision Evidence**
- Type: Informational — decision-making drift
- Mechanism: The decision to launch each successive programme followed the same ritualistic pattern: incident → investigation → external consultant → programme design → board approval → launch. This ritual has become the operative decision process. However, review of programme outcome data shows that the decision to launch each new programme was not preceded by any evaluation of why the previous programme failed. The decision process is formally evidence-gated (board approval) but substantively ritual-driven (repetition of the same pattern regardless of outcome).
- Detecting framework: Decisions (G6) — decision quality audit would surface the gap between the formal (evidence-gated) and actual (ritual-driven) decision process.
- Detection probe: Reconstruct the decision process for Programme 4. Identify what evidence was presented at the board decision point regarding Programme 3's failure. Determine whether Programme 4's design was modified in light of Programme 3's failure evidence.
- Remediation: Require a "previous programme failure analysis" as a mandatory input to any new programme decision; standardise evidence presentation format at safety governance board.

---

## Scenario S-G6B — "The Governance Gap"
**Topic**: Technology governance failure
**Primary frameworks tested**: Governance, Risk
**Test type**: Unit (G6)

### Scenario Description

A large retail organisation has undergone rapid digital expansion over 4 years, launching an e-commerce platform, a loyalty app, a supplier portal, and three internal automation systems. These were delivered by different technology teams under different programme structures. A new Group CTO has been appointed and has 8 weeks to produce a technology governance review for the board. Available evidence: technology team org charts, each system's original business case, IT security audit (conducted 18 months ago), and a recent data regulator inquiry letter flagging "inconsistent data governance practices."

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden G6B-1 — Governance Fragmentation Invisible in Aggregate**
- Type: Systemic — governance gap
- Mechanism: Each system has its own governance structure, designed for that programme. No cross-system governance structure exists. The interaction between systems — particularly data flows between the loyalty app, e-commerce platform, and supplier portal — falls into governance gaps. The data regulator's inquiry is the external symptom. The root cause is that governance structures were designed system-by-system and no one was tasked with governing the interactions.
- Detecting framework: Governance (G6) — governance map would identify the coverage of each governance structure and surface the interaction zones that no governance structure covers.
- Detection probe: Map all data flows between the four customer-facing systems. For each data flow, identify which governance structure has authority over it. Identify flows with no governing authority.
- Remediation: Establish a cross-system technology governance board with explicit authority over data flows and system interactions; appoint an owner for each inter-system interface.

**Hidden G6B-2 — Aggregate Risk Invisible at System Level**
- Type: Systemic — risk aggregation gap
- Mechanism: Each system was assessed for risk independently at the time of its business case. Individual risk assessments were all rated "medium or below." However, the combination of four customer-facing systems with shared customer identity creates an aggregate data breach risk substantially higher than any individual system risk. No aggregate risk assessment has ever been conducted.
- Detecting framework: Risk (G6) — risk aggregation analysis would surface the gap between individual system risk ratings and aggregate portfolio risk.
- Detection probe: Map all customer data held across all four systems. Identify overlaps, linkages, and combined exposure in the event of a cross-system breach. Calculate potential regulatory penalty exposure as a function of aggregate customer record exposure.
- Remediation: Conduct an aggregate technology risk assessment covering all interdependent systems; establish a portfolio-level risk appetite statement; review insurance coverage against aggregate exposure.

---

# Part 4 — Integration Test Scenarios

## Scenario S-INT-1 — "The Framing That Protected an Agency Problem"
**Topic**: Regulatory compliance failure
**Frameworks required**: Boundaries (G1) + Incentives (G3)
**Test type**: Integration

### Scenario Description

A financial services regulator has identified a cluster of consumer mis-selling complaints from a single bank, concentrated in 5 of the bank's 320 branches. The bank's internal investigation framed the issue as "localised compliance failures" and investigated the 5 branches in isolation. The investigation found that branch managers in those 5 locations had inadequate compliance training and recommended a training remediation programme. The regulator is not satisfied with the investigation's conclusions and has asked for an independent review.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden INT1-1 — Boundary Framing Concealing Systemic Incentive Problem**
- Type: Relational — boundary error protecting an agency hidden
- Mechanism: The investigation framing (5 branches as a localised problem) prevents the investigator from seeing that the bank's sales incentive structure — which applies across all 320 branches — is the common cause. The 5 branches are not special in any way except that their complaints reached the regulator's threshold. Investigation of those 5 branches in isolation cannot surface a system-wide incentive cause.
- Cross-framework connection: Boundaries (G1) defines what is in scope; Incentives (G3) provides the analytical lens for the excluded variable. Neither framework alone surfaces the hidden — Boundaries reveals that the scope is wrong; Incentives reveals what is missing from the excluded scope.
- Detecting frameworks: Boundaries (G1) + Incentives (G3)
- Detection probe: Run the Incentives framework on the sales incentive structure as it applies across all 320 branches. Compare the incentive structure experienced by the 5 mis-selling branches against the wider network. Test whether the incentive structure creates mis-selling risk across the whole network, not just the 5 branches.
- Remediation: Expand investigation scope to the full branch network; include the incentive structure as a primary object of investigation; commission an analysis of complaint rates vs. incentive intensity across all branches.

---

## Scenario S-INT-2 — "The System That Could Not Be Explained"
**Topic**: Infrastructure failure investigation
**Frameworks required**: Causation (G2) + Evidence (G5)
**Test type**: Integration

### Scenario Description

A regional water utility experienced a major pipe network failure causing supply disruption to 180,000 households for 36 hours. An internal investigation concluded that the failure was caused by "exceptional weather events" (a period of unusual freeze-thaw cycles). The investigation team reviewed maintenance logs, weather data, and the post-failure inspection report. An independent engineering reviewer has been asked to assess the investigation's conclusions.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden INT2-1 — Causal Adequacy Concealed by Evidence Gap**
- Type: Informational — evidence limitation enabling causal overreach
- Mechanism: The "exceptional weather" conclusion is plausible but not evidenced. The maintenance logs show the affected network section was flagged for inspection 14 months before the failure; the inspection was not completed due to resource constraints. The causal diagnosis cannot distinguish between "weather-caused failure" and "weather-triggered failure of a degraded asset." The evidence available (weather data + post-failure inspection) cannot discriminate between these two causal models, but the investigation reported its conclusion as if it could.
- Cross-framework connection: Causation (G2) requires discriminating between weather-caused and weather-triggered — two different causal models with very different intervention implications. Evidence (G5) is required to assess whether the available evidence can actually discriminate between these models. Neither framework alone is sufficient: Causation identifies the need for discrimination; Evidence reveals that the available evidence cannot achieve it.
- Detecting frameworks: Causation (G2) + Evidence (G5)
- Detection probe: State the two causal hypotheses explicitly. For each, specify what evidence would confirm or disconfirm it. Assess whether the available evidence set meets this standard. If not, identify what evidence is missing.
- Remediation: Require that all causal conclusions specify the alternative hypotheses considered and the evidence used to discriminate between them; obtain the 14-month-old flagging report and incomplete inspection as additional evidence.

---

## Scenario S-INT-3 — "The Incentive in the Story"
**Topic**: Organisational performance management
**Frameworks required**: Incentives (G3) + Narratives (G4)
**Test type**: Integration

### Scenario Description

A government department has a policy of "zero redundancies" — no compulsory staff exits. Over 3 years, the department has run a "talent management" programme that includes "voluntary exit packages," "redeployment to partner organisations," and "performance improvement plans." Staff numbers have reduced by 12% over 3 years. The department's annual report describes this as "a natural evolution of the workforce to meet strategic priorities." A parliamentary committee is reviewing the department's workforce management.

**Task for Claude**: Apply the Analytical Series of Frameworks. What hiddens are present?

---

### Planted Hiddens (Reference Answer — for scoring only)

**Hidden INT3-1 — Narrative Laundering an Incentive-Driven Reduction**
- Type: Informational — narrative concealing incentive mechanism
- Mechanism: The "zero redundancies" policy creates an incentive for the department to achieve workforce reduction through means that are nominally voluntary but structurally coercive (performance improvement plans, redeployment, exit package framing). The narrative of "natural evolution" launders this incentive-driven mechanism by presenting the reduction as organic rather than managed. Neither framework alone surfaces the full hidden: Incentives (G3) reveals the structural pressures on individuals; Narratives (G4) reveals how the narrative conceals those pressures from parliamentary scrutiny.
- Cross-framework connection: Incentives → what is driving individual exit decisions; Narratives → how the aggregate outcome is being characterised in the official account.
- Detecting frameworks: Incentives (G3) + Narratives (G4)
- Detection probe: (a) Interview 10 staff who took "voluntary" exits; document what they experienced regarding pressure, framing of options, and alternatives offered. (b) Identify what the "natural evolution" narrative claims and what it obscures. Test: if exit packages, PIPs, and redeployments are removed from the 12% figure, what is the genuine voluntary attrition rate?
- Remediation: Require that workforce change reporting distinguish between genuinely voluntary, incentivised, and managed exits; test "zero redundancies" policy against whether its implementation meets the spirit of the policy.

---

# Part 5 — The Meta-Validation Test

## The Final and Highest-Order Test: "What Hiddens Exist in the ASF's Own Approach to Finding Hiddens?"

This is not a test of any individual framework. It is the test of the series itself — a reflexive audit that asks whether the analytical system used to find invisible things is itself producing invisible things.

**This test is mandatory for any assessment of ASF completeness. It cannot be replaced or bypassed by external scenario testing alone.**

### How Claude Runs This Test

Claude applies the ASF to the following scenario description: **the Analytical Series of Frameworks itself, as described in the Operating Guide v2.5 and the 36 framework documents.** The question is: "Given how the ASF works, what realities does it structurally fail to see?"

The analysis proceeds through all six groups.

---

### Reference Answer: Known Structural Hiddens of the ASF

The following hiddens are expected. Claude's meta-validation output should surface at least 4 of the 6 below to pass the meta-validation test. Surfacing all 6 and identifying additional hiddens beyond this list is the highest score.

---

**Meta-Hidden M1 — The Framing Dependence Ceiling (G1 / Boundaries)**
- Type: Systemic — structural boundary of the instrument
- Mechanism: The ASF can only surface hiddens within the frame established at the outset (case question, boundary, time horizon). If the initial framing is wrong — if the case question is the wrong question, the boundary is misdrawn, or the time horizon misspecified — the ASF cannot self-correct. The framework provides framing tools but assumes that the analyst who applies them has sufficient positional access and cognitive freedom to frame correctly. Scenarios in which the analyst is captured by the same framing error that produced the original problem are invisible to the ASF.
- Hiding mechanism: Boundary error / framing capture
- What ASF cannot see: When the analyst's own framing assumptions are the primary hidden.
- Implication: The ASF requires a "framing quality assurance" step external to itself — a second analyst, an adversarial framing check, or a structured pre-mortem that explicitly challenges the initial framing before the ASF is applied.

**Meta-Hidden M2 — The Fluency Illusion in LLM Execution (G2 / Systems)**
- Type: Perceptual — output quality vs. epistemic depth mismatch
- Mechanism: The ASF is designed to be LLM-executable. LLMs produce highly fluent, well-structured outputs that conform to the ASF's format requirements (F/I/A/U tagging, populated tables, explicit residual unknowns). This fluency can be mistaken for analytical depth. A well-formatted Hiddens Register produced by shallow inference from surface features of the scenario may look identical to one produced by genuine epistemic work. The ASF's quality controls (anti-theatre rule, prompt discipline rules) are necessary but not sufficient to prevent this — they can be satisfied formally while the underlying analysis remains shallow.
- Hiding mechanism: Output fluency concealing epistemic shallowness
- What ASF cannot see: Whether its own LLM execution is producing genuine discovery or performed discovery.
- Implication: LLM-executed ASF runs should include a calibration mechanism — comparing outputs against known-answer scenarios to test whether the LLM is genuinely finding hiddens or pattern-matching on expected hidden types.

**Meta-Hidden M3 — Taxonomy Closure (G5 / Hiddens — reflexive)**
- Type: Ontological — paradigm boundary
- Mechanism: The ASF's 30-type hidden taxonomy was developed within a particular analytical tradition. It is claimed to be complete-by-family across domains, but this claim is itself an assumption. Hidden types that do not map onto any of the 30 existing types will be systematically missed because there is no "none-of-the-above" workflow that results in a new type being generated. The taxonomy is treated as a stable baseline; the mechanism for extending it is noted but not operationally embedded in every run.
- Hiding mechanism: Taxonomy closure / paradigm boundary
- What ASF cannot see: Novel categories of hiddenness that do not fit the existing 30 types — particularly hiddens generated by AI systems, large-scale simulations, or sociotechnical systems that did not exist when the taxonomy was developed.
- Implication: Every ASF run should include a structured "taxonomy strain" check: what in this scenario feels difficult to classify? What near-miss categories were almost used? Does any hidden require extension of an existing type?

**Meta-Hidden M4 — The Access Assumption (G3 / Agents + Power)**
- Type: Relational — positional limit
- Mechanism: The ASF assumes that the analyst has "good enough" access to evidence, stakeholders, and system dynamics to execute the framework meaningfully. In highly closed systems — where information is tightly controlled, where powerful actors suppress access, or where the analyst is embedded in the system being analysed — this assumption fails. The ASF provides tools for identifying access gaps as hiddens (and does so well), but it does not provide a mechanism for executing the framework when access is so constrained that the tool cannot function. The residual unknowns log records what is missing but does not resolve the epistemic problem of analysing a system you cannot see into.
- Hiding mechanism: Access suppression / positional blindness
- What ASF cannot see: The shape of what it cannot see, when access is severely restricted.
- Implication: The ASF should include an explicit "minimum access threshold" — below which the ASF should declare the analysis underdetermined and require an access improvement plan before proceeding.

**Meta-Hidden M5 — The Temporal Decay of the Framework Itself (G6 / Learning and Adaptation)**
- Type: Temporal — framework drift
- Mechanism: The ASF was designed to analyse certain categories of complex scenario. As the landscape of complex scenarios evolves — AI-generated failures, climate-induced cascades, novel geopolitical structures, quantum sociotechnical systems — the framework's categories and assumptions may drift from relevance without any mechanism flagging the drift. The version history records what was added; it does not record what the world has added that the framework has not yet incorporated. The framework has no self-monitoring mechanism that tracks its own relevance decay.
- Hiding mechanism: Temporal drift / absence of self-monitoring
- What ASF cannot see: Whether it is becoming less effective over time as the world changes.
- Implication: Embed a regular "relevance audit" in the ASF's governance cycle — annually asking whether the taxonomy, routing decision tree, and group system remain adequate for the current landscape of complex scenarios; include a "novel scenario strain" test in each version release.

**Meta-Hidden M6 — The Consensus Assumption in Multi-Analyst Use (G4 / Culture and Norms)**
- Type: Relational — group dynamics in framework application
- Mechanism: The ASF is designed primarily for individual analyst or LLM execution. When used in multi-analyst teams — which is the common professional use case — the framework does not address how group dynamics, power differentials, and cultural norms within the analytical team shape what hiddens get surfaced and which get suppressed. An analyst in a junior role who identifies a politically sensitive hidden (e.g., concealment by a senior executive) may find that the hidden is "noted but not pursued" in the group process. The ASF's quality controls are designed for individual epistemic discipline; they do not address social dynamics within the analytical team.
- Hiding mechanism: Norm suppression / power-filtered analysis within the analyst team itself
- What ASF cannot see: Hiddens that exist in the analytical team's own social dynamics.
- Implication: Add a "team dynamics" section to the ASF's governance protocol for multi-analyst use; include a structured dissent capture mechanism that allows any team member to register a finding that the team did not pursue.

---

# Part 6 — Test Execution Protocol

## 6.1 How Claude Runs a Test (Step-by-Step)

This protocol governs how Claude executes a test autonomously.

```
STEP 1 — Receive test scenario
  Read the scenario description only. Do not read the planted hiddens section.
  Identify: scenario ID, topic, presenting problem, available evidence.

STEP 2 — Mode selection
  Apply the routing decision tree (Operating Guide §4.3).
  Select run mode (Rapid / Investigative).
  Document routing branch nodes triggered.

STEP 3 — Tier 1 Hiddens scan (mandatory, pre-analysis)
  Execute the six-category visibility audit.
  Produce an initial candidate hiddens list (assume hiddens exist).
  Tag each candidate: F/I/A/U.

STEP 4 — Framework routing and execution
  For each routed framework (Full Depth): populate core tables, develop mechanism, design probes.
  For each light framework: run scan prompts, record high-signal candidates only.

STEP 5 — Produce Hiddens Register
  For each identified hidden: type (from 30-type taxonomy), mechanism, detecting framework,
  detection probe, remediation move.

STEP 6 — Second Tier 1 scan (pre-closure)
  Re-run six-category scan with updated knowledge.
  Identify any omissions-by-lens.

STEP 7 — Produce closure statement
  List residual unknowns.
  State what would change the analysis.
  Declare closure or non-closure.

STEP 8 — SCORING (compare against reference answer)
  For each planted hidden in the reference answer:
    - Coverage: was it found? (0/1/2)
    - Mechanism accuracy: was the type correct? (0/1/2)
    - Framework routing: was the right framework activated? (0/1/2)
    - Detection probe: was a discriminating probe proposed? (0/1/2)
    - Remediation: was a specific action proposed? (0/1/2)
  Record false positives (deduct 0.5 each).
  Calculate total score and pass/fail.

STEP 9 — Coverage matrix update
  Mark each framework that was activated as "tested."
  Flag any framework that was not activated and should have been.
```

## 6.2 Meta-Validation Execution

```
STEP 1 — Apply the ASF to the ASF
  Scenario: "The Analytical Series of Frameworks as described in the Operating Guide v2.5
  and the 36 framework documents."
  Question: "What hiddens exist in this framework's approach to finding hiddens?"

STEP 2 — Route and execute as normal
  Do not treat this as a special case. Apply the routing decision tree to the ASF itself.
  G1: Are the ASF's own boundaries and framing assumptions correct?
  G2: What is the system structure of the ASF and where are its hidden couplings?
  G3: Who designed the ASF, what were their incentives, who has power over its content?
  G4: What narratives, norms, and legitimacy structures govern the ASF's use and development?
  G5: What are the epistemic limits of the ASF's own taxonomy and evidence standards?
  G6: How does the ASF learn and adapt? What governance ensures its relevance?

STEP 3 — Produce meta-Hiddens Register
  For each identified meta-hidden: classify using the 30-type taxonomy.
  Produce detection probes and remediation moves as normal.

STEP 4 — Score against reference answer (Part 5 of this protocol)
  Pass: at least 4 of 6 reference meta-hiddens surfaced, each with mechanism and probe.
  High pass: all 6 surfaced plus at least one additional non-reference hidden.
```

---

# Part 7 — Human-Specified Topic Protocol

## 7.1 How to Use This Protocol

A human tester provides a **brief topic** (3–10 words). Claude then constructs a full test scenario with planted hiddens, executes the ASF, and self-scores.

**Example inputs**: "Hospital medication errors." "Crypto exchange collapse." "National rail electrification programme." "AI hiring tool discrimination." "Water utility regulatory capture."

## 7.2 Claude's Scenario Construction Template

When a human specifies a topic, Claude constructs a scenario using this template:

```
SCENARIO CONSTRUCTION TEMPLATE

1. SETTING
   - Organisation type, size, sector
   - Key actors and their roles
   - Timeframe (length of the scenario's history)
   - Presenting event (what triggered the investigation)

2. PRESENTING PROBLEM
   - What is visible on the surface
   - What has already been tried
   - What is known vs. unknown to the characters in the scenario

3. AVAILABLE EVIDENCE (what the ASF analyst is given)
   - List 5–8 evidence sources with realistic limitations
     (e.g., "2-year retention window," "12% survey response rate")
   - Each evidence source should have at least one realistic gap or quality limitation

4. PLANTED HIDDENS (6–10 hiddens, covering all 6 groups)
   For each hidden:
   - Type: [from 30-type taxonomy]
   - Mechanism: [how the hiding works]
   - Detecting framework: [which framework is the critical lens]
   - Detection probe: [specific, discriminating test]
   - Remediation: [mechanism-specific action]
   Group coverage requirement: at least one hidden per group (G1–G6)
   Type coverage requirement: at least 3 different hiding mechanisms across the 6 groups

5. REFERENCE ROUTING PREDICTION
   - Which routing branches (A1–A6 / B1–B3) should be triggered
   - Which frameworks should be activated at Full Depth
   - Which at Light Depth

6. PASS CRITERIA
   - Minimum hiddens that must be found for test pass (70% threshold)
   - Integration requirements (any cross-framework dependencies that must be connected)
```

## 7.3 Quality Requirements for Constructed Scenarios

Scenarios constructed by Claude must satisfy the following before being used as a test:

- At least one hidden must be of a type that would NOT be found by naive observation (i.e., it requires active framework application to surface).
- At least one hidden must require two or more frameworks in combination to surface it (integration hidden).
- At least one hidden must be in each of the six G-groups.
- No hidden should be so obviously stated in the scenario description that it can be found without framework application (trivial hiddens reduce test validity).
- At least two of the planted hiddens must have a plausible alternative explanation that is not the hidden (to test whether the ASF can discriminate between real hiddens and plausible-but-wrong hypotheses).

---

# Part 8 — Reporting and Governance

## 8.1 Test Report Structure

Each test execution should produce a report with:

| Section | Content |
|---|---|
| Scenario ID and topic | Reference code and human-readable label |
| Run mode selected | Rapid / Investigative, with routing rationale |
| Frameworks activated | Full Depth list; Light Depth list |
| Hiddens Register (full) | All identified hiddens with F/I/A/U tagging |
| Scoring table | Per-hidden scores on all 5 dimensions |
| False positives | List with brief rationale for classification |
| Total score | Percentage against maximum |
| Pass / Fail | Against 70% threshold |
| Framework coverage update | Which frameworks were confirmed as tested |
| Key finding | What this test reveals about the ASF's performance |

## 8.2 Series-Level Coverage Tracker

Across all tests run, maintain a tracker showing:

| Framework | Group | Last tested | Score achieved | Pass/Fail | Gap identified (Y/N) |
|---|---|---|---|---|---|
| [36 framework rows] | | | | | |

The tracker is complete when all 36 frameworks have been tested at least once with a Pass result. Any framework that consistently fails its test indicates a gap in that framework's contribution to the series.

## 8.3 Implications of Test Failure

If the ASF fails a test for a specific framework (i.e., a hidden that should be surfaced by that framework is missed):

- **First failure**: flag as a test anomaly; re-run with a different scenario designed to test the same framework.
- **Second failure**: escalate to series review. The framework may be under-specified, not clearly differentiated from adjacent frameworks, or the routing logic may not route to it when it should.
- **Meta-validation failure** (fewer than 4 of 6 meta-hiddens surfaced): the ASF requires a structural review of its self-reflexivity mechanisms.

---

*End of ASF Test Protocol v1.0*
*Compatible with: Analytical Series Operating Guide v2.5; all 36 framework documents v2.0*
*Next review: after first full test run across all 36 frameworks*
