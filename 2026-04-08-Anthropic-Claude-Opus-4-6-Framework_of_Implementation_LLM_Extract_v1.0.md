# Framework of Implementation – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Implementation |
| Primary group | G6 — Action & Control (Choice, action & control over time) |
| Secondary group | G2 — Mechanism (Structure, dependencies & mechanism) |
| Stage | Core (Framework Group 6: Action & Control) |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v1.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Implementation framework diagnoses what actually happens when decisions, interventions, and policies are operationalised into practice. It classifies implementation mechanisms into six meta-categories and thirty core types; maps five cross-cutting dimensions (scope, fidelity, tempo, capacity, monitoring); identifies ten dynamic patterns that surface how implementation diverges from intent; and surfaces eight systematic Hiddens families (compliance theatre, capacity blindness, street-level adaptation, resistance invisibility, decision-implementation divergence, cascade effects, unintended consequences, equity impacts). It populates the Implementation Inventory, Gap Register, Capacity & Constraint Register, Monitoring & Feedback Ledger, Implementation Risk Register, and Hiddens Register, enabling downstream frameworks to design remediation and governance of implementation failures.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Implementation when… | Use neighbour instead when… |
|---|---|---|
| Interventions | You need to analyze what actually happens operationally when an intervention is executed; focus is on gap between design intent and operational reality. | You need to design what an intervention should do; focus is on specifying intervention logic and intended outcomes independent of operational execution. |
| Governance | You need to understand implementation fidelity and surface implementation gaps requiring oversight and corrective action; focus is on implementation monitoring and feedback loops. | You need to establish governance authority, escalation pathways, and decision-making structures; focus is on who has authority to make corrections independent of specific implementation instance. |
| Processes | You need to map how a specified process is actually being executed and adapted in practice; focus is on operationalisation and informal variants. | You need to design a process specification; focus is on defining task sequences and workflows independent of execution context. |
| Evidence | You need to surface implementation failures through monitoring and data that reveal divergence; focus is on whether practices match specifications. | You need to assess evidence quality and whether claims are supported by data; focus is on evidentiary standards independent of specific implementation instance. |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I. Sequencing & Ordering | Prerequisite Sequencing, Phase-Gate Review, Stabilisation Intervals, Dependent Activity Blocking, Change Rate & Tempo | In what sequence are activities being introduced, and is that sequence enabling or blocking implementation success? |
| II. Capacity & Resources | Workforce Allocation & Sufficiency, Tooling & System Readiness, Training & Capability Development, Budget & Financial Sufficiency, Supporting Infrastructure & Governance | Are the human, technical, and organisational resources sufficient to execute and sustain implementation, and where are bottlenecks? |
| III. Resistance & Compliance | Active Resistance & Opposition, Passive Non-Compliance, Selective Compliance & Gaming, Reinterpretation & Drift, Legitimacy Resistance | What forms of resistance (active, passive, hidden) are present, and is reported compliance reflecting actual behaviour change or theatre? |
| IV. Workarounds & Adaptations | Temporary Bypass & Contingency, Capability-Gap Workaround, Constraint-Driven Adaptation, Unintended Process Variant, Normalised Workaround | What informal modifications to specified process are being used, and are they indicating capability gaps, constraint-driven necessity, or intentional deviation? |
| V. Feedback & Monitoring | Compliance Metric Design, Data Collection & Quality, Escalation Pathway & Visibility, Corrective Action & Loop Closure, Feedback Loop Fidelity | What mechanisms exist to surface whether implementation is occurring as intended, and do those mechanisms produce action or just reporting? |
| VI. Portfolio & Tempo | Resource Contention & Allocation, Interdependency Mapping & Management, Interaction Design & Testing, Cascade Effect Recognition, Portfolio Tempo & Absorption | How are multiple implementation initiatives sequenced and managed, and what interactions and cascade effects result from parallel implementation? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Phased Roll-Out Momentum | Each phase completes on time; confidence grows; later phases scale up because early phases worked. | Early success breeds visibility and support; later phases inherit residual issues but scale-up logic assumes clean slate. | Momentum can drive successful implementation but masks residual issues; scaling-up amplifies unresolved problems. |
| Capacity Exhaustion & Overload | Workload accumulates; timelines slip; error rates increase; staff report overload; quality shortcuts emerge. | Fixed implementation teams absorb expanding work without escalation; no mechanism to reduce scope or increase capacity. | Overload hidden leads to burnout and quality degradation; overload visible creates pressure to adjust scope or timeline. |
| Silent Adaptation | Observed practice gradually diverges from specification without formal change request or approval. | Frontline staff adapt to local context, constraint, or preference; adaptation works locally and solves problems; divergence is not surfaced. | Masks needed changes (adaptation should be formalised) and masks degradation (adaptation is workaround for unaddressed constraint). |
| Resistance Activation | Resistance that was initially low becomes active; staff openly articulate concerns or slow their work. | Resistance drivers accumulate (change not delivering benefit, burden higher than expected, trust broken); staff shift from compliance to questioning. | Surfaced resistance is addressable; suppressed resistance hardens into passive non-compliance. |
| Monitoring Decay | Monitoring intensity decreases; data quality degrades; escalation pathways are used less often. | Initial intensity difficult to sustain; competing priorities pull focus; escalation fatigue reduces usage. | Creates blind spot: divergence cannot be detected without data; decay signals resolution but judgment made without data. |
| Feedback Loop Collapse | Issues identified and escalated but corrective actions do not occur; escalation reports accumulate without resolution. | Decision-makers acknowledge issues but do not fund corrective actions; actions planned but competing priorities prevent execution. | Key Hiddens generator: issues documented but not resolved, creating false assurance without actual improvement. |
| Decision-Implementation Divergence | Same decision interpreted and implemented differently across teams or contexts. | Decision made centrally and communicated broadly; local interpretation adapts decision to context or existing practice. | Creates fragmentation: organisation executes multiple different interpretations of single decision. |
| Cascade & Interaction | One implementation creates unintended consequences or amplifies/dampens another implementation. | Implementations executed in parallel without explicit interaction design; assumed independent but actually coupled. | Cascade effects override individual implementation logic; two reasonable changes combine to create failure. |
| Workaround Hardening | Workaround that was initially temporary becomes standard practice; people forget it is a workaround. | Workaround solves immediate problem, works locally; no one pushes for formalisation; constraint may be permanent. | Masks unaddressed constraint: if workaround removed, constraint re-emerges and implementation fails. |
| Crisis Reversion | During crisis, staff revert from new process to old trusted process, often without explicit approval. | New process not yet automatic or trusted; old process faster, more familiar, more reliable under pressure. | Reveals trust gaps in new process or unaddressed capability/speed advantages of old process. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | Are decision-makers and implementers operating from shared understanding of what is being implemented, or are different interpretations creating invisible divergence? |
| II (Systemic) | How does implementation of one change trigger second-order effects in adjacent systems, and are these interactions designed and monitored? |
| III (Informational) | Do feedback loops surface issues to decision-makers, or are escalation pathways broken and issues filed without action? |
| IV (Temporal) | Is implementation timeline optimistic; are residual issues from early phases resolved before proceeding to next phase; is drift accumulating invisibly? |
| V (Relational) | Do power imbalances shape implementation; is resistance suppressed through authority rather than addressed through problem-solving; is trust broken? |
| VI (Ontological) | Is implementation being done in the name of one narrative (e.g. efficiency) while actually serving a different purpose, creating meaning gap? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Compliance Theatre (reported compliance masks actual practice divergence)
- Capacity Blindness (insufficient capacity not reported; overload absorbed silently)
- Street-Level Adaptation Invisibility (frontline workers adapt without visibility)
- Resistance Invisibility (passive non-compliance remains undetected and unaddressed)
- Decision-Implementation Divergence (different interpretations across contexts not surfaced)
- Cascade and Interaction Blindness (parallel implementations interact in unpredicted ways)
- Unintended Consequence Invisibility (implementation achieves target metric while generating negative impacts elsewhere)
- Portfolio Overload Concealment (system-wide overload masked by individual implementation metrics looking on-track)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Compliance theatre between reported and actual practice | Framework of Evidence; Framework of Governance | Practice audit verification; governance oversight strengthening | Verify compliance beyond metrics; strengthen escalation when practice divergence found |
| Capacity blindness and silent overload | Framework of Capacity; Framework of Risk | Workload audits; utilisation monitoring with escalation triggers | Monitor capacity with escalation thresholds; trigger scope reduction or timeline extension |
| Silent adaptation creating variants and drift | Framework of Processes; Framework of Learning & Adaptation | Practice variance audits; periodic implementation review; re-alignment | Periodic practice reviews; explicit governance of variants (formalise, constrain, or address driver) |
| Resistance invisibility and passive non-compliance | Framework of Power; Framework of Incentives | Staff interviews with trust-building; observation of practice; barrier surfacing | Create safe channels for resistance; address drivers (legitimacy, incentive, capability, constraint) |
| Cascade and interaction effects overriding implementation | Framework of Systems; Framework of Risk | Portfolio-level monitoring; interdependency mapping; interaction models | Map and design interactions; sequence high-coupling implementations separately |
| Unintended consequences in adjacent systems | Framework of Evidence; Framework of Systems | Multi-dimensional monitoring; second-order-effect scanning during design | Monitor across dimensions not just target metric; periodic impact reviews |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Clarify what is being implemented (decision, intervention, policy, scope, timeline); confirm intent and baseline.
2. Identify active implementation types across six meta-categories; assess which are most critical for this instance.
3. Quick capacity and timeline check: is capacity sufficient; is timeline realistic; are obvious bottlenecks visible.
4. Run Tier 1 Hiddens scan: touch all six meta-categories; flag obvious compliance theatre, capacity blindness, or resistance.
5. Shortlist 2–3 highest-consequence Hiddens; note detection/remediation interfaces; flag for escalation if high-consequence and high-uncertainty.

### 7b. Full Depth Execution (Complete framework run)

1. Establish implementation clarification: decision intent, target population, baseline operational state, stakeholders, timeline and milestones.
2. Conduct gap analysis: compare documented specification to observed implementation; measure fidelity; classify divergence (adaptation, resistance, constraint, drift).
3. Diagnose resistance mechanisms: conduct staff interviews; surface active and passive resistance; map resistance drivers (legitimacy, incentive, capability, constraint).
4. Audit capacity: workforce allocation vs. requirements; tooling readiness; training adequacy; budget sufficiency; supporting infrastructure; monitor utilisation and escalate overload.
5. Assess implementation dynamics: for each focal implementation type and meta-category, determine which patterns are active (nascent, present, high-risk); identify cascades.
6. Map three interfaces: Implementation-Intervention (clarification and design feedback), Implementation-Governance (escalation and monitoring), Implementation-Evidence (outcome measurement and feedback).
7. Run Tier 1 + Tier 2 Hiddens scan: for each high-relevance Hidden, identify mechanism, detectability, agency, consequence; assign detection and remediation interfaces; document residual Unknowns.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Implementation Inventory | Add baseline implementation status, active types, and dimensional profiles for each focal implementation. | After clarification and gap analysis. |
| Gap Register | Record implementation gaps (specification vs. observed), fidelity assessment, divergence drivers. | After gap analysis; escalate gaps with high consequence. |
| Capacity & Constraint Register | Capacity audit results; bottlenecks and constraints; escalation triggers for overload. | After capacity audit; monitor continuously. |
| Monitoring & Feedback Ledger | Monitoring mechanisms, metric definitions, escalation pathways, feedback loop status. | After interface mapping; escalate loop failures to governance. |
| Implementation Risk Register | Implementation failure risks; dynamics patterns present; cascade effects; consequence and mitigation. | After dynamics analysis; escalate high-consequence risks. |
| Hiddens Register | Implementation-specific Hiddens with meta-category tag, mechanism, detectability, agency, consequence. | After Tier 1 scan; escalate high-consequence/high-uncertainty to Tier 2. |

**Gate Question (pre-closure check):** Have we established shared understanding of what is being implemented, identified active implementation types, assessed capacity and resistance, run a Tier 1 Hiddens scan, and escalated any high-consequence Unknowns to appropriate frameworks?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Interventions (intervention specification and design intent)
- Decisions (decision intent, scope, success criteria)
- Processes (current operational process, capability, constraints)
- Capacity (resource availability, workforce, tooling, budget)
- Power & Incentives (stakeholder perspectives, resistance drivers, incentive structures)
- Risk (failure modes, vulnerabilities, constraint mapping)

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Framework of Governance (escalation, monitoring, corrective action authority)
- Framework of Risk (implementation failure modes and risk register)
- Framework of Learning & Adaptation (implementation experience, learning loops, adjustment cycles)
- Framework of Evidence (outcome measurement and implementation effectiveness)
- Framework of Processes (implementation experience informing process redesign)
- Framework of Hiddens (implementation-specific Hiddens and remediation design)

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Scan 1: Compliance theatre audit | Surface whether reported compliance reflects actual behaviour change or masks continued old practice; verify through practice audits and staff interviews. |
| Scan 2: Capacity blindness check | Identify whether capacity constraints are being absorbed silently; audit workload, utilisation, and escalation of overload signals. |
| Scan 3: Resistance and adaptation mapping | Diagnose active and passive resistance; surface drivers and adaptation mechanisms; distinguish healthy adaptation from degrading deviation. |
| Scan 4: Cascade and interaction effects | Map portfolio interdependencies; design and test interactions between parallel implementations; identify where cascade effects are plausible. |
| Scan 5: Decision-implementation divergence | Audit whether decision is being interpreted consistently across contexts; identify variance and surface drivers of divergence. |

---

*LLM Execution Extract v1.0 – Implementation Framework (2026-04-08) – End of Extract*
| **V. Relational** | Power imbalances shape implementation; those who lose resist; resistance suppressed; trust broken | Resistance from specific groups; no open dialogue; escalations dismissed; some staff engaged, others withdrawn | Map power structures; who benefits/loses; interview groups separately; assess trust; address resistance drivers not suppress behaviour |
| **VI. Ontological** | Implementation serves unstated purpose; stated goals diverge from actual; meaning gap creates resistance/theatre | Stated implementation goal differs from actual design; perceived as "really about" something unstated; staff implement letter while avoiding spirit | Make implementation purpose explicit; surface goal divergence; either align goals or be honest and build legitimacy |

---

## Application Protocol Summary (7 steps)

1. **Clarification**: Align on what is being implemented, by whom, when, success criteria. Baseline operational state documented. Stakeholders identified.

2. **Gap Analysis**: Compare intended to actual practice. Scope, fidelity, coverage assessed. Variants and workarounds mapped.

3. **Resistance & Adaptation Diagnosis**: Surface explicit and implicit resistance. Understand adaptation drivers. Decide: formalise, constrain, or address driver.

4. **Capacity & Constraint Audit**: Assess workforce, tooling, training, budget, infrastructure sufficiency. Surface overload if present.

5. **Dynamics Analysis**: Assess which ten patterns are active. Map portfolio interactions. Identify implementation-specific risks. Assess trajectory.

6. **Hiddens Mapping**: Run Tier 1 across all six categories. Test escalation/feedback pathways. Audit monitoring and evidence.

7. **Recommendations & Closure**: Synthesise findings. Produce recommendations. Escalate governance issues. Design monitoring. Document residuals. Bound closure.

---

## LLM Execution Checklist

**Input requirements** (before running):
- [ ] Implementation scenario described (what is being implemented, by whom, when, decision context, consequences)
- [ ] Governance artefacts available (decision document, implementation plan, escalation pathways)
- [ ] Stakeholder perspectives available (at least 3 independent accounts of implementation fidelity, capacity, resistance)
- [ ] Operational baseline described (current practice before implementation, key constraints)
- [ ] Risk context known (high-consequence risks, recent failures, escalation thresholds)
- [ ] Run mode selected (Rapid = Light Depth ~2–4 hours; Investigative = Full Depth ~6–12 hours)

**Execution steps** (when running):
1. Load this extract into LLM context
2. Clarify implementation scope (decision, target population, timeline, success criteria)
3. Assess gap (intended vs. actual practice)
4. Surface resistance and adaptation
5. Audit capacity and constraints
6. Map dynamics and interactions
7. Run Tier 1 Hiddens scan
8. Produce recommendations with escalations
9. Output standard schema: Fact/Interpretation/Assumption/Unknown registers + Hiddens register + Evidence ledger + Hypothesis/Test backlog
10. State closure bounds and next probes

**Output format** (required):
- Implementation Inventory (active types, mechanism summary)
- Gap Register (divergences, magnitude, drivers, consequence)
- Resistance & Adaptation Catalogue (types, drivers, remediation approach)
- Capacity & Constraint Register (resource status, bottlenecks, overload)
- Implementation Risk Register (implementation-specific risks)
- Hiddens Register (eight specific Hiddens, mechanism, detectability, remediation)
- Evidence Audit (metrics validity, data quality, feedback-loop status)
- Recommendation Log (actionable, specific, sequenced)
- Residual Unknown Register (what remains unclear, next probes)
- Closure Statement (questions answered, limits, escalations)

---

## Integration with Other Frameworks (key inputs/outputs)

**Pulls from**:
- **Interventions**: Design spec, intended mechanism, expected outcomes (to assess fidelity)
- **Decisions**: What was decided, intent, constraints (to assess decision-implementation alignment)
- **Governance**: Authority, oversight mechanisms, escalation pathways (to assess governance oversight of implementation)
- **Risk**: Risk register, failure modes, consequence levels (to assess implementation-created risks)
- **Evidence**: Available metrics, data quality, timeliness (to assess monitoring adequacy)
- **Power & Incentives**: Power structures, incentive systems (to assess whether incentives drive implementation)

**Feeds to**:
- **Governance**: Implementation gaps and risks requiring governance escalation
- **Risk**: Implementation-created risks, cascade risks, portfolio risks
- **Learning & Adaptation**: Implementation experience feeding back to learning
- **Evidence & Metrics**: Requirements for what should be monitored
- **Communications**: Narrative alignment with operational reality

---

## Prompt Discipline Rules (pointer to OG v2.5 §D.3)

**All implementation claims must be tagged as Fact (F), Interpretation (I), Assumption (A), or Unknown (U):**
- **Fact**: Observed directly, tested, verified by multiple independent sources
- **Interpretation**: Inference from evidence; state basis and reasoning
- **Assumption**: Accepted-as-true to proceed; test later or note fallback
- **Unknown**: Gap remains; specify next probe to resolve

**Do not collapse uncertainties into false consensus. Record disagreements explicitly. Bound closure statement with unknowns and escalations.**

See Operating Guide v2.5 §D.3–D.4 for canonical ruleset, output contract, and closure discipline.

---

## Routing & Mode Selection (pointer to OG v2.5 §4.3, §D.10.1)

**When to invoke Implementation**:
- A decision or major policy change is approved and operational execution begins
- Outcomes are disappointing despite sound approval and design (implementation gap likely)
- Reports show compliance but operational observations suggest divergence
- Frontline staff describe workarounds or reinterpretations
- Capacity constraints suspected but not surfaced
- Multiple changes in flight and cascade effects suspected
- Monitoring is absent or compliance reported without behaviour verification
- Learning loops are not closing

**Run mode**:
- **Rapid Run Mode** → Light Depth execution (~2–4 hours): quick gap identification, simple capacity check, Tier 1 Hiddens scan
- **Investigative Run Mode** → Full Depth execution (~6–12 hours): comprehensive gap analysis, capacity audit, dynamics assessment, Tier 2 Hiddens, live-practice audits

**Depth decision** (OG v2.5 §D.10.1): Do not conflate run mode with execution depth. Both Rapid and Investigative modes can run Light or Full Depth depending on stakes and evidence quality.

---

## Key Prompt Patterns for LLM Execution

**Pattern 1: Gap audit**
"Compare [documented implementation plan] to [actual operational practice described by stakeholders]. What divergences are visible? For each, assess: is it legitimate adaptation, drift, or resistance? Map scope and coverage."

**Pattern 2: Resistance diagnosis**
"Interview [stakeholder group 1, 2, 3]: what barriers do they face in implementing [specified change]? What are they actually doing instead? Map reasons for non-adoption: capability gap, constraint, incentive misalignment, legitimacy question, or preference?"

**Pattern 3: Capacity check**
"Is [implementation team] resourced to execute [implementation plan]? Assess: workforce, tooling, training, budget, supporting services. Where are bottlenecks? Are staff reporting overload? Is overload being absorbed without escalation?"

**Pattern 4: Dynamics scan**
"Which of these patterns are visible in [implementation]? (phased momentum, capacity exhaustion, silent adaptation, resistance activation, monitoring decay, feedback collapse, decision divergence, cascade, workaround hardening, crisis reversion) For each active pattern, assess severity and trajectory."

**Pattern 5: Hiddens audit**
"Run the six-category Hiddens scan: which categories may be active? (Perceptual, Systemic, Informational, Temporal, Relational, Ontological) For each, what are typical symptoms? What checks should be run to confirm or rule out?"

**Pattern 6: Interface test**
"Test the three implementation interfaces: [I-A intervention-to-implementation: is intervention intent clear to operations?] [I-B implementation-to-governance: is governance detecting divergence?] [I-C implementation-to-evidence: is evidence reaching decision-makers and triggering action?]"

---

## End of LLM Extract

**Return to full Framework of Implementation v1.0 for**:
- Extended definitions and context
- Detailed type descriptions and diagnostic cues
- Full Hiddens analysis with mechanism chains
- Complete integration matrix with all 36 canonical frameworks
- Extended glossary

