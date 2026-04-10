# Framework of Interventions – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Interventions |
| Primary group | G6 — Action & control (Action & Control) |
| Secondary group | None |
| Stage | Downstream (Action) |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v2.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Interventions framework classifies intervention types and intervention-design methods through six meta-categories and thirty core types, profiles each intervention across five dimensions (mechanism, reversibility, stakeholder impact, scalability, adaptation-readiness), maps ten dynamics of how interventions succeed or fail and how unintended consequences emerge, and surfaces intervention-specific visibility failures via tiered Hiddens scans. It enables intervention design targeted to diagnosed root causes, assessment of unintended consequences and side effects, stakeholder impact mapping, and adaptive scaling. It supports both direct interventions (changing specific mechanisms) and systemic interventions (redesigning structures, incentives, feedback loops).

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Interventions when… | Use neighbour instead when… |
|---|---|---|
| Diagnosis | You need to design what intervention will address a diagnosed root cause; focus on intervention mechanism and design | You need to identify root causes; focus on causality independent of intervention |
| Decisions | You need to evaluate intervention options and choose which to pursue; focus on option selection | You need to design what the chosen intervention will do; focus on intervention design independent of choice |
| Governance | You need to design governance, accountability, and monitoring for intervention; focus on intervention governance | You need to map governance structure and decision authority; focus on governance independent of specific interventions |
| Risk | You need to assess risks and unintended consequences of specific interventions; focus on consequence profile | You need to identify failure modes and hazards; focus on risk landscape independent of interventions |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Intervention Modality | Direct Behaviour Change, Structural Redesign, Incentive Redesign, Norm/Culture Change, Capability Building | What is the primary mechanism of change (behaviour, structure, incentive, culture, capability)? |
| II. Intervention Target Level | Individual/Personal Change, Team/Group Change, Organisational Change, System-Level Change, Institutional Change | At what level is the intervention targeted (individual, team, organisational, systemic, institutional)? |
| III. Intervention Scope & Universality | Universal Intervention, Targeted Intervention, Contextual Adaptation, Graduated Rollout, Pilot-Testing Intervention | Is the intervention uniform or customised to context? |
| IV. Intervention Reversibility | Reversible Intervention, Difficult-Reversal Intervention, One-Way Intervention, Pathway-Dependent Intervention, Lock-In Risk Intervention | How easy is the intervention to undo if it fails or proves harmful? |
| V. Intervention Coordination & Coupling | Standalone Intervention, Dependent Intervention (requires prior interventions), Coordinated Multi-Intervention, Coupled-Change Intervention, Cascade-Risk Intervention | Does the intervention depend on other changes or does it trigger cascades? |
| VI. Intervention Monitoring & Adaptability | Monitored Intervention, Adaptive Intervention, Trigger-Activated Adjustment, Escalation-Ready Intervention, Learning-Loop-Enabled Intervention | Is the intervention static or designed for monitoring and adaptation? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature | Mechanism | Consequence |
|---|---|---|---|
| Intervention-root-cause mismatch | Intervention targets proximal symptom while root cause unaddressed; symptom relief temporary; problem recurs; intervention declared failure | Diagnosis incomplete or misdiagnosed; intervention designed for symptom not root; proximal cause easier to address | Intervention "works" temporarily but recurrence undermines credibility; sunk costs in ineffective intervention; learning failure |
| Unintended consequences and side effects | Intervention produces intended effect but also negative side effects; coupled systems react; intervention gains offset by losses | System complexity and coupling not fully modelled; feedback loops unexpected; incentive structure changes enable new problems | Net benefit ambiguous; unintended consequences escalate; second-order interventions needed; intervention fatigue |
| Intervention resistance and adaptation | System responds to intervention by working around it or reverting to prior patterns; intervention is circumvented | Incentive misalignment (system prefers prior state); implicit resistance (people re-adapt); system regenerates problem despite intervention | Intervention energy dissipates; system returns to baseline; apparent intervention effect decays over time |
| Implementation failure | Intervention design sound but implementation inadequate; execution gaps; fidelity compromised | Resource constraints; implementer skill gaps; incentive misalignment; competing priorities | Design-reality gap; field conditions differ from assumptions; intervention achieves suboptimal effect; blame shifts to implementation |
| Dosage miscalibration | Intervention too weak to achieve effect; or too strong, producing unnecessary disruption or side effects | Dosage not empirically calibrated; uncertainty about effect size; risk aversion or pressure for quick change | Underdosing wastes intervention resources; overdosing produces backlash; learning curve to find adequate dosage |
| Stakeholder backlash | Intervention affects stakeholder interests; affected party resists; resistance escalates; intervention credibility undermined | Stakeholder impact not anticipated or disclosed; incentive harm uncompensated; power asymmetry; communication failure | Intervention blocked or circumvented; escalation to conflict; legitimacy damaged; opportunity for better-designed intervention lost |
| Lock-in and path dependence | Intervention creates conditions making reversal or adaptation difficult; initial choice constrains future options | Early-stage decision creates lock-in; sunk costs prevent reversal; infrastructure becomes dependent on intervention | Decision reversibility decreases over time; adaptation constrained; brittleness if assumptions violated; learning loop closed |
| Intervention sustainability failure | Intervention succeeds initially but fades over time; gains erode; infrastructure for maintenance inadequate | Attention and resource allocation shifts; new priorities arise; maintenance burden underestimated; incentive for sustainability inadequate | Temporary improvement; regression after withdrawal; sunk costs wasted; need for repeat interventions; demoralisation |
| Scaling failure | Intervention works at small scale but fails to scale; complexity and coordination difficulties emerge at scale | Scale-dependent dynamics emerge; coordination costs multiply; heterogeneity increases; contextual adaptation requirements increase | Small-scale success not replicable at scale; false confidence from pilot; scaled implementation disappoints; resources wasted |
| Cascade and coupling effects | Intervention in one domain triggers cascades in coupled domains; indirect effects amplify or undermine primary effect | System coupling not fully modelled; feedback loops emerge; network effects activate; side-effect domain emerges | Apparent single-domain intervention produces multi-domain change; indirect effects dominant; system-wide risk and opportunity emerge |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question |
|---|---|
| I (Perceptual) | What unintended consequences of the intervention are not anticipated; what side effects might emerge but are not perceived? |
| II (Systemic) | How does the intervention couple with other systems; what cascades or system reactions might it trigger; what structural dependencies does it create? |
| III (Informational) | What information about intervention risks or stakeholder impact is not disclosed; what monitoring data is hidden or inaccessible? |
| IV (Temporal) | What long-term consequences of the intervention are not visible; what time-lag effects or decay patterns are not monitored? |
| V (Relational) | Who is harmed by the intervention but remains silent; what stakeholder resistance is suppressed; what dissent is unheard? |
| VI (Ontological) | What intervention paradigm forecloses alternative intervention types; what is treated as the only way to intervene? |

### 6b. Primary Hiding Mechanisms

- Unintended consequences invisibility (side effects and cascades not anticipated)
- Root-cause-intervention mismatch (intervention targets symptom not root; success temporary)
- Stakeholder impact invisibility (whose interests are harmed; resistance suppressed)
- Implementation-design gap (execution differs from design; fidelity not monitored)
- Lock-in invisibility (path dependence and irreversibility not recognised until constrained)
- Scaling blindness (small-scale success not predictive of scale feasibility)
- Sustainability invisibility (maintenance requirements and fade-out not planned)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Root-cause-intervention mismatch suspected | Framework of Diagnosis; Framework of Interventions (redesign) | Symptom-vs-root-cause analysis; temporal outcome monitoring; recurrence testing | Verify root-cause diagnosis; redesign intervention if needed; add preventive components |
| Unintended consequences evident | Framework of Systems; Framework of Interventions (escalation/redesign) | Side-effect monitoring; stakeholder impact assessment; cascade analysis | Widen monitoring to coupled systems; assess net benefit; design offsetting interventions |
| Stakeholder resistance or backlash | Framework of Governance; Framework of Interests | Stakeholder impact audit; compensation design; communication/engagement redesign | Increase stakeholder voice; address incentive misalignment; improve communication |
| Scaling failure | Framework of Interventions (piloting/adaptation); Framework of Systems | Small-scale-to-scale analysis; complexity and coordination audit; adaptation design | Pilot-test at planned scale; identify scaling barriers; design contextual adaptation mechanisms |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal intervention; clarify intended mechanism (what is supposed to change), target (what is being changed), and reversibility.
2. Identify 2–3 high-risk unintended consequences; assess stakeholder impact (who benefits, who is harmed).
3. Run Tier 1 Hiddens scan: check for root-cause-intervention mismatch, unintended consequences, stakeholder impact invisibility, implementation-fidelity risk.
4. Design simple outcome monitoring: how will we know if the intervention worked; what would indicate failure or unintended consequences?
5. Flag any irreversible interventions or high-coupling interventions for escalation to governance and risk frameworks.

### 7b. Full Depth Execution (Complete framework run)

1. Map intervention design: intended mechanism, target level, scope (universal/contextual), reversibility, coordination requirements.
2. Classify intervention type (meta-categories I–VI); profile across five dimensions (mechanism, reversibility, stakeholder impact, scalability, adaptation-readiness).
3. Verify root-cause-intervention alignment: does intervention target root cause or symptom; would symptom-only intervention be insufficient?
4. Scenario-test unintended consequences: what coupled systems might the intervention affect; what cascades could emerge; what side effects are plausible?
5. Map stakeholder impact: who is affected; who benefits; who is harmed; how does incentive structure align with intervention success?
6. Run Tier 1 + Tier 2 Hiddens scan: for each high-consequence Hiddens (unintended consequences, stakeholder impact, lock-in risk, scaling blindness), design detection and remediation interfaces.
7. Design monitoring and adaptation: what metrics indicate intervention success and failure; what triggers escalation or reversal; what feedback loops enable learning?

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hypothesis/Test Backlog | Propose tests for intervention mechanism (does it work as intended), outcome evaluation, unintended-consequence detection, scaling assessment | For all identified Unknowns about intervention |
| Information Requests | Request monitoring data; request stakeholder-impact assessment; request implementation fidelity auditing | To support intervention success and failure detection |
| Risk Register | Add intervention-specific risks: unintended consequences, stakeholder backlash, lock-in, scaling failure, sustainability failure | For all identified high-consequence risks |

**Gate Question (pre-closure check):** Have we verified root-cause-intervention alignment, scenario-tested unintended consequences, assessed stakeholder impact, run Tier 1 Hiddens scan, designed outcome monitoring, and escalated high-risk interventions (irreversible, high-coupling, high-stakeholder-impact) to governance and risk frameworks?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs

- Diagnosis (root cause identifying appropriate intervention)
- Decisions (chosen intervention option)
- Risk (risks and consequences of intervention)
- Stakeholders (stakeholder map and interest assessment)
- Systems (system structure and coupling affecting intervention)

### 8b. Downstream Handoffs

- Framework of Governance (intervention governance, accountability, reversal authority)
- Framework of Learning & Adaptation (intervention monitoring and adaptive learning)
- Framework of Risk (monitoring intervention-specific risks and cascades)
- Framework of Metrics (metrics for intervention monitoring and success assessment)

### 8c. Targeted Scans

| Targeted Scan | Role of this framework |
|---|---|
| Unintended-Consequence & Coupling Scan (Family A, Scan 3) | Scenario-test intervention side effects; identify cascade risk; assess coupled-system impact |
| Stakeholder-Impact & Resistance Scan (Family B, Scan 7) | Map who is harmed; assess stakeholder resistance risk; design stakeholder engagement |
| Scaling & Adaptation Scan (Family C, Scan 5) | Test small-scale-to-scale transferability; identify contextual-adaptation requirements |

---

*LLM Execution Extract v1.0 – Interventions Framework (2026-04-08) – End of Extract*
