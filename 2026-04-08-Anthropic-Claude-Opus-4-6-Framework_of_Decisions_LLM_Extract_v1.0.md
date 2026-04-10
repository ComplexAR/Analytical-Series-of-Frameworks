# Framework of Decisions – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Decisions |
| Primary group | G6 — Action & control (Action & Control) |
| Secondary group | None |
| Stage | Downstream (Action) |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Decisions framework classifies decision types and decision-making processes through six meta-categories and thirty core types, profiles each decision across five dimensions (reversibility, stakeholder consensus, time-pressure, information-completeness, consequence), maps ten dynamics of how decision-making quality degrades, and surfaces decision-specific visibility failures via tiered Hiddens scans. It enables structured choice evaluation under uncertainty, surfaces hidden constraints on what options are considered thinkable, designs decision-making processes resistant to bias and capture, and produces defensible decision records with explicit treatment of Unknowns, tradeoffs, and dissent.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Decisions when… | Use neighbour instead when… |
|---|---|---|
| Diagnosis | You need to map options generated from root-cause understanding; focus on what choices are made given a diagnosis | You need to identify root causes underlying problems; focus on causality independent of decision-making |
| Evidence | You need to assess what evidence supports each decision option; focus on option evaluation under uncertainty | You need to weight overall evidence and evidence reliability; focus on evidence strength independent of options |
| Risk | You need to evaluate probability and impact of decision outcomes; focus on consequence and reversibility of each option | You need to identify failure modes and low-probability high-consequence events; focus on risk landscape independent of specific decisions |
| Interventions | You need to choose which intervention to pursue; focus on decision-making and option evaluation | You need to design what the intervention will do and how to implement it; focus on intervention design independent of the choice |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Decision Context & Authority | Routine Decision, Discretionary Decision, Forced Choice, Delegated Decision, Deferred Decision | Who has decision authority and how constrained is the choice? |
| II. Decision Criteria & Values | Cost-Benefit Trade-off, Risk-Tolerance Trade-off, Values-Based Choice, Precedent-Based Decision, Adaptive/Learning Decision | What criteria or values are weighting the choice? |
| III. Option Generation & Search | Comprehensive Search, Limited Search, Single-Option Default, Stakeholder-Generated Options, Expert-Derived Options | How were options generated and was search space adequately explored? |
| IV. Option Evaluation & Comparison | Quantitative Analysis, Qualitative Judgement, Scenario Analysis, Sensitivity Analysis, Reversibility-Weighted Analysis | How are options being compared and evaluated? |
| V. Consensus, Dissent & Alignment | Consensus Decision, Majority-Rule Decision, Minority-Protected Decision, Unilateral Decision, Coerced Alignment | How is disagreement handled and whose voice counts? |
| VI. Decision Documentation & Accountability | Decision Record, Rationale Documentation, Dissent Recording, Reversal Plan, Learning-Loop Design | Is the decision documented in ways that enable accountability and learning? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature | Mechanism | Consequence |
|---|---|---|---|
| Default bias | Default option chosen without adequate evaluation of alternatives; search effort minimal; status quo protected by inertia | Cognitive bias toward status quo; cost of search and evaluation; risk aversion; sunk costs in default | Suboptimal choice; opportunity cost of forgone better options; brittleness if default is no longer appropriate |
| Narrow option generation | Limited set of options considered; genuine alternatives not explored; framing constrains apparent options | Cognitive constraints; time pressure; institutional path dependency; incentive to protect status quo | Choice made within artificially narrow window; better options not considered; false choice structure imposed |
| Premature closure | Decision made before option evaluation complete; choice forced by timeline pressure; alternatives not adequately tested | Time pressure; decision authority forcing closure; sunk costs in leading option; incentive to decide quickly | Inadequate evaluation; regret when consequences manifest; opportunity for course correction lost; brittleness |
| Hidden constraints on options | Certain options treated as impossible or unthinkable; constraints are rarely articulated; framing makes options genuinely unthinkable to decision-makers | Institutional constraints (policy, structure, incentive); belief constraints (what is considered possible); power constraints (who can veto) | Option space artificially constrained; better options foreclosed by invisibility; false constraint accepted as inevitable |
| Decision-maker conflict of interest | Decision-maker has personal stake in particular option; conflict is unacknowledged; bias in option evaluation | Incentive misalignment; institutional inertia (decision-maker benefits from status quo); power protection; sunk costs | Decision biased toward benefiting decision-maker; suboptimal for organisation; accountability diffused |
| Dissent suppression and false consensus | Disagreement exists but is expressed only in private; public consensus masks private doubt; minority view suppressed | Retaliation risk; psychological safety erosion; conformity pressure; authority enforcement of orthodoxy | False confidence in decision quality; minority knowledge suppressed; hidden internal disagreement; brittleness and vulnerability to surprise |
| Reversibility miscalibration | Reversible decision treated as irreversible (over-caution, excessive deliberation); irreversible decision treated as reversible (under-caution, insufficient deliberation) | Miscalibration of consequence and reversibility; bias in one direction (conservative or risk-seeking); institutional culture | Decision-making process mismatched to decision type; over/under-investment of resources; brittleness if reversibility assessment wrong |
| Outcome misattribution | Decision consequence attributed to decision when actually driven by external factors; learning failure follows | Temporal coincidence; missing confounding factors; incentive to claim credit for success; diffuse blame for failure | Wrong decision credited or blamed; learning fails; sunk costs in ineffective decisions; decision-making improvement blocked |
| Option anchoring and overvaluation | Initial option anchored upon; later options compared to anchor rather than evaluated on merits; anchor distorts evaluation | Cognitive anchoring bias; first-mover advantage in presenting option; institutional inertia; sunk costs | Later options disadvantaged in comparison; better options rejected because they don't match anchor; choice suboptimal |
| Decision-making capture | Structured decision process exists but is captured by interest (power, incentive, ideology); process becomes facade for predetermined choice | Institutional power imbalances; incentive misalignment; institutional culture favoring certain options; authority override | Process integrity compromised; dissent channelled but not heeded; false legitimacy for predetermined choice; decision quality degraded |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question |
|---|---|
| I (Perceptual) | What options are not being considered because they are not visible; what option generation blindness exists? |
| II (Systemic) | How do institutional constraints foreclose options; what is policy/structure/incentive making options unthinkable? |
| III (Informational) | What information about options is gated or unavailable; what analysis is restricted; what risks are not disclosed? |
| IV (Temporal) | What long-horizon consequences are discounted or not visible; what time-pressured decisions are made despite reversibility? |
| V (Relational) | Who is silenced in decision-making; what dissent is suppressed; what conflict of interest is unacknowledged? |
| VI (Ontological) | What paradigm frames what is possible; what decision-making paradigm forecloses certain types of choices? |

### 6b. Primary Hiding Mechanisms

- Hidden constraints on option space (policy, belief, power constraints making options unthinkable)
- Narrow option generation (incomplete search; status quo bias protecting limited options)
- Dissent suppression and false consensus (disagreement hidden; minority voice suppressed)
- Conflict of interest (decision-maker benefit unacknowledged)
- Decision-process capture (formal process subverted; predetermined choice with false legitimacy)
- Reversibility miscalibration (irreversible decisions rushed; reversible decisions over-deliberated)
- Outcome misattribution (false learning from decision)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Hidden constraints limiting options | Framework of Hiddens; Framework of Perspectives | Constraint audit; boundary-assumption testing; option-generation brainstorm with diverse stakeholders | Surface constraints; test whether truly binding; design for option expansion |
| Dissent suppressed; false consensus | Framework of Governance; Framework of Culture & Norms | Dissent-surfacing mechanisms; anonymous feedback; minority-voice amplification | Establish legitimate dissent channels; protect minority views; require dissent documentation |
| Conflict of interest evident | Framework of Governance; Framework of Incentives | Conflict audit; bias disclosure; decision-maker recusal decisions | Recuse conflicted decision-makers; redesign incentives; increase transparency |
| Decision-process capture suspected | Framework of Governance (process redesign); Framework of Hiddens | Process audit; stakeholder interviews (anonymous); predetermined-outcome testing | Redesign process for integrity; increase transparency; strengthen dissent protection |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal decision; clarify decision authority, reversibility, consequence, and timeline.
2. List 3–5 candidate options; assess which constraints foreclose options (policy, belief, power, precedent, institutional); identify if search was comprehensive.
3. Run Tier 1 Hiddens scan: check for hidden constraints, dissent suppression, conflict of interest, narrow option generation, process capture.
4. Identify which stakeholders favour which options; assess dissent-expression safety; note any suppressed minority views.
5. Estimate reversibility; flag if miscalibrated (rushed irreversible decision or over-deliberated reversible decision).

### 7b. Full Depth Execution (Complete framework run)

1. Map decision context: authority, consequence, reversibility, timeline, stakeholder map, criteria for evaluation.
2. Conduct comprehensive option search: generate options beyond initial candidates; probe for hidden constraints; test whether options are truly thinkable; expand apparent option space.
3. Classify decision type (meta-categories I–VI); profile across five dimensions (reversibility, stakeholder consensus, time-pressure, information-completeness, consequence).
4. For each option, assess: supporting evidence, risks and downsides, reversibility and sunk costs, stakeholder support.
5. Surface dissent: identify stakeholders who favour different options; assess whether dissent is expressed or suppressed; design dissent-expression mechanism.
6. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence Hidden (hidden constraints, dissent suppression, conflict of interest, process capture), design detection and remediation interfaces.
7. Produce decision record with: options evaluated, evidence for each, stakeholder positions, dissent documented, reversibility assessed, decision rationale, escalation trigger (if decision reversal possible).

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Decision Record | Document focal decision, options, evidence, stakeholder positions, dissent, rationale, reversibility, escalation triggers | Before decision closure |
| Hypothesis/Test Backlog | Propose tests to evaluate decision options; design monitoring to detect outcome misattribution | For decision options with high Unknowns |
| Information Requests | Request evidence on decision options; request dissent-surfacing mechanisms if needed | To support comprehensive option evaluation |

**Gate Question (pre-closure check):** Have we conducted comprehensive option search, surface hidden constraints, assessed reversibility and consequence, documented stakeholder positions and dissent, run Tier 1 Hiddens scan for hidden constraints and suppression, and designed reversal plan if decision proves incorrect?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs

- Diagnosis (root cause analysis identifying options)
- Evidence (evidence supporting each option)
- Risk (consequence and tail-risk profile of each option)
- Beliefs (what options are thinkable given current beliefs)
- Values (criteria for choice)
- Perspectives (stakeholder viewpoints on options)

### 8b. Downstream Handoffs

- Framework of Interventions (chosen option design and implementation)
- Framework of Governance (decision authority, accountability, reversal authority)
- Framework of Learning & Adaptation (decision monitoring and outcome attribution learning)
- Framework of Risk (decision consequence monitoring; cascade detection)

### 8c. Targeted Scans

| Targeted Scan | Role of this framework |
|---|---|
| Hidden Constraints & Option-Space Scan (Family D, Scan 2) | Surface policy/belief/power constraints limiting options; expand apparent option space |
| Decision-Process Integrity Scan (Family B, Scan 6) | Audit decision-making process for capture, dissent suppression, conflict of interest |

---

*LLM Execution Extract v1.0 – Decisions Framework (2026-04-08) – End of Extract*
