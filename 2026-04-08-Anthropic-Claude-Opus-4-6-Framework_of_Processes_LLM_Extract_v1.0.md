# Framework of Processes – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Processes |
| Primary group | G2 — Structure, dependencies & mechanism (Mechanism) |
| Secondary group | G3 — Social structure & dynamics (Social) |
| Stage | Core |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Processes framework maps the sequence and flow of activities that constitute work, decision-making, or change in a scenario; classifies process types across six meta-categories (Design, Execution, Decision, Communication, Adaptation, Transformation); characterizes processes along five dimensions (structure, pace, clarity, formality, effectiveness); analyzes process dynamics (bottlenecks, delays, rework, deviation); and surfaces process-level Hiddens (informal workarounds, shadow processes, process deviation, effectiveness gaps). It populates the Evidence Ledger, Execution Register, and Intervention Register with process bottleneck analysis and redesign guidance, enabling identification of process improvement opportunities and hidden process disruption.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Processes when… | Use neighbour instead when… |
|---|---|---|
| Systems | You need to understand how activity sequences flow through system structure; focus is on activity flow and process design. | You need to analyze system-level feedback loops and emergent behavior independent of specific activity sequences. |
| Time | You need to understand temporal sequencing and duration of process steps; focus is on temporal process structure. | You need to analyze temporal dynamics, lags, and thresholds independent of process design. |
| Technology | You need to understand how technology shapes or enables process design; focus is on process-technology affordance. | You need to classify and analyze technology independent of specific process contexts. |
| Communications | You need to understand how processes require or generate information flow; focus is on communication within processes. | You need to analyze communication content, clarity, and effectiveness independent of process structure. |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Design & Planning | Requirements Gathering, Design, Prototyping, Specification, Planning, Resource Allocation | What processes define what work should be done and how? |
| II. Execution & Operations | Task Execution, Material Handling, Quality Control, Monitoring, Problem Response, Completion | What processes carry out the actual work? |
| III. Decision & Authorization | Criteria Setting, Option Evaluation, Decision Authority, Approval, Escalation, Waiver | What processes determine what decision is made and who decides? |
| IV. Communication & Coordination | Information Sharing, Escalation, Cross-Functional Coordination, Feedback, Consensus-Building, Alignment | What processes enable coordination and information flow? |
| V. Adaptation & Improvement | Learning, Feedback Integration, Continuous Improvement, Testing, Adjustment, Iteration | What processes enable learning and process change? |
| VI. Transformation & Transition | Change Management, Cutover, Training, Legacy Decommission, Data Migration, Stabilization | What processes manage change or transition? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Bottleneck & Queue Buildup | Work accumulates upstream of slow step; queue grows; throughput limited by bottleneck; frustration rises. | Capacity mismatch; downstream step is slower than upstream input; no buffering possible; prioritization breaks down. | Delay; rework; quality loss; missed deadlines; stress. |
| Rework & Iteration Loop | Work rejected at quality gate or downstream; reworked; cycle repeats; productivity gains erased. | Quality standard misunderstood or not met first pass; feedback slow; correction expensive; pressure to move forward overrides quality. | Productivity loss; cost overrun; hidden rework; frustration. |
| Shadow Process & Workaround | Official process too slow, burdensome, or unfit; actors devise informal workaround; shadow process emerges. | Official process designed for different conditions or by different logic; actors closer to reality; flexibility needed but official process rigid. | Process deviation; compliance risk; lack of audit trail; sustainability questions. |
| Process Deviation & Gaming | Actors drift from official process; adapt based on local learning or incentive optimization. | Official process treated as starting point not strict requirement; local intelligence creates effective variants; metrics drive deviation. | Process fragmentation; inconsistent outcomes; control loss; learning suppressed. |
| Gate Blockage & Permission Lag | Work waits for authorization or approval; gating function creates delay; queue backs up. | Authority scattered; approval criteria unclear; gate-keeper capacity insufficient; risk aversion; process design assumes instantaneous decision. | Delay; bottleneck at gate; frustration; game-playing to preempt rejection. |
| Handoff Failure & Loss | Information or work loses fidelity at handoff between teams/systems; downstream task starts with incomplete/wrong input. | Handoff boundaries not explicit; information not formally transferred; context not translated; trust low; priority misaligned. | Rework; delay; quality loss; blame-shifting; low cross-team collaboration. |
| Effectiveness Gap | Process runs smoothly but fails to achieve intended outcome; effort expended but goals unmet. | Process design doesn't match outcome requirements; success metrics unaligned with goals; learning feedback absent; unmeasured externalities. | Mission failure despite process compliance; frustration; search for blame; process redesign needed. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What process steps or bottlenecks are salient vs invisible from common positions; what informal processes operate below visibility? |
| II (Systemic) | How do processes couple with institutions, incentives, and systems; what emergent process failures arise from structure? |
| III (Informational) | What process documentation is available vs missing; what information is lost at handoffs? |
| IV (Temporal) | What process steps are slow or introduce hidden delays; what temporal mismatches exist between process pace and need? |
| V (Relational) | Whose process design is dominant; whose process preferences are suppressed; what power asymmetries hide in process control? |
| VI (Ontological) | What process types or steps are not recognized in official model; what shadow processes emerge from official gaps? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Bottleneck Invisibility (process constraint operates below attention until buildup reaches crisis)
- Shadow Process Emergence (informal workarounds hidden from official model and metrics)
- Handoff Failure (information loss and context translation failures at team boundaries)
- Process Deviation (actors adjust official process; compliance appears maintained but actual process varies)
- Effectiveness Gap (process runs smoothly but fails to achieve intended outcome)
- Gate Blockage (authorization delays and approval bottlenecks hidden in queue buildup)
- Rework Invisibility (quality failures and iteration loops unmeasured and suppressed)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Bottleneck or queue buildup | Framework of Evidence; Framework of Metrics | Process timing analysis; queue depth tracking; bottleneck identification | Measure queue sizes; identify constraint step; redesign for throughput. |
| Shadow process or workaround | Framework of Hiddens; Framework of Communications | Actual vs official process mapping; workflow observation | Observe actual process; understand workaround logic; assess sustainability. |
| Handoff failure or information loss | Framework of Communications; Framework of Systems | Handoff point audit; information flow testing; handoff criteria clarity | Design explicit handoff protocol; test information transfer; build verification. |
| Process deviation and gaming | Framework of Governance; Framework of Evidence | Deviation pattern analysis; incentive structure audit | Understand deviation drivers; realign incentives or official process. |
| Effectiveness gap | Framework of Diagnosis; Framework of Outcomes | Goal-process alignment audit; outcome measurement; external factor analysis | Clarify goals; measure outcomes vs outputs; identify external constraints. |
| Gate blockage or authorization delay | Framework of Governance; Framework of Decisions | Gate criteria clarity; decision authority mapping; approval process redesign | Clarify gating criteria; distribute authority; establish approval SLA. |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Map focal process: list main steps, sequence, major inputs/outputs; identify process type (I–VI) and scope.
2. Assess 2–3 key process properties: Structure (linear, iterative, conditional), Pace (slow/normal/fast), Clarity (clear/ambiguous/undefined).
3. Run Tier 1 Hiddens scan: touch all six meta-categories; flag obvious bottlenecks, shadow processes, or handoff failures.
4. Shortlist 2–3 highest-consequence process gaps (bottleneck, deviation, ineffectiveness); note if process redesign is needed; flag for escalation.

### 7b. Full Depth Execution (Complete framework run)

1. Process inventory: identify all focal processes; for each, map steps, sequence, ownership, authority, decision gates, handoff points, success criteria.
2. Process profile: for each critical process, assess across dimensions (structure, pace, clarity, formality, effectiveness); note deviations from intent.
3. Bottleneck analysis: measure or estimate throughput at each step; identify capacity constraints; assess queue buildup and delay impact.
4. Shadow process mapping: identify informal workarounds; understand why they exist; assess sustainability and risk.
5. Handoff analysis: map information transfer at process boundaries; assess fidelity loss; identify missing context or translation.
6. Effectiveness audit: measure process outcomes against stated goals; identify effectiveness gaps; assess whether process is measuring right things.
7. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence process Hidden, identify mechanism, detectability, consequence; propose process-improvement tests.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add process-level Hiddens with meta-category tag (Design, Execution, Decision, Communication, Adaptation, Transformation); mechanism; consequence. | After Tier 1 scan; escalate bottlenecks and effectiveness gaps. |
| Evidence Ledger | Record process structure, throughput, quality metrics, outcomes; note measurement gaps and hidden processes. | After process inventory and bottleneck analysis. |
| Hypothesis/Test Backlog | Add hypotheses about process bottlenecks, shadow processes, effectiveness gaps; propose process-timing and output tests. | Identified process Unknowns; escalation decisions. |
| Information Requests | Request process timing data; request actual vs official process comparison; request outcome data and customer feedback. | To reduce process Unknowns; coordinate with Evidence and Communications frameworks. |

**Gate Question (pre-closure check):** Have we mapped focal processes, identified bottlenecks and shadow processes, assessed effectiveness against goals, run a Tier 1 Hiddens scan, and designed process improvements?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Situations Context Classification (what situation types involve what processes?)
- Systems (what system structure enables or constrains processes?)
- Technology (what technology affordances shape process design?)
- Time (what temporal constraints or dependencies apply?)

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Framework of Hiddens (shadow process emergence, bottleneck invisibility; Tier 2 scans)
- Framework of Communications (process-enabled information flow; handoff design)
- Framework of Decisions (decision-gate design within processes)
- Framework of Evidence (process metrics and outcome measurement)
- Framework of Risk (process failure risk; bottleneck cascade risk)
- Framework of Interventions (process redesign and improvement)
- Framework of Learning & Adaptation (process learning and continuous improvement)

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Scan 1: Shadow process and workaround discovery | Identify informal processes outside official model. |
| Scan 4: Bottleneck and queue analysis | Identify throughput constraints and delay points. |
| Scan 6: Handoff failure and information loss | Identify process boundaries where fidelity is lost. |
| Scan 8: Effectiveness gap and goal-process misalignment | Identify where process compliance doesn't achieve outcomes. |

---

*LLM Execution Extract v1.0 – Processes Framework (2026-04-08) – End of Extract*
