# Framework of Cognition – LLM Execution Extract v1.0

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | Framework of Cognition |
| Primary group | G3 — Agency (Agency) |
| Secondary group | G5 — Epistemics & error-control (Epistemics) |
| Stage | Core (Framework Group 3: Agency) |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | v1.0 |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

The Cognition framework identifies how agents' mental processes—mental models, cognitive biases, heuristics, attention allocation, bounded rationality, and reasoning structures—shape what is perceived, attended to, and concluded. It classifies cognitive processes into six meta-categories and thirty core types; maps how cognitive processes produce systematic perception gaps and judgment errors; and surfaces visibility failures created by model-based blindness, attention limits, and heuristic-driven errors. It populates the Hiddens Register, Evidence Ledger, and Hypothesis/Test Backlog with cognitive-mechanism analysis, enabling downstream frameworks to design interventions targeting the right cognitive process, not just information provision.

---

## Section 3: Near-Neighbour Disambiguation Table

| Nearest neighbour | Use Cognition when… | Use neighbour instead when… |
|---|---|---|
| Beliefs | You need to diagnose how agents perceive and reason *given* their mental models and cognitive constraints; focus is on formation mechanisms and perception gaps. | You need to analyse what agents hold as true and why belief content is entrenched; focus is on belief content and commitment, not perception formation. |
| Knowledge | You need to understand how agents' cognitive constraints (working memory, attention, bounded rationality) prevent knowledge from being used even when available. | You need to analyse what is known and distributed across agents; focus is on knowledge structure and distribution, not cognitive use barriers. |
| Evidence | You need to diagnose why available evidence is not changing perception or belief despite contradicting agents' current models; focus is on perception barriers. | You need to analyse what evidence exists and assess quality and gaps; focus is on evidence landscape, not cognitive barriers to perception. |
| Risk | You need to identify which cognitive processes (mental model misalignment, attention blindness, heuristic errors) generate material risks. | You need to analyse risk structure and probability/consequence; focus is on risk landscape, not cognitive mechanisms generating risk. |

---

## Section 4: Condensed Core Taxonomy

| Meta-category | Core types (names only) | Diagnostic question (1 sentence) |
|---|---|---|
| I Mental Models | Causal Model, System Structure Model, Normalcy Model, Expert Intuitive Model, Paradigm/Framework Model | What is the agent's internal representation of how systems work, and what does the model make invisible or impossible to perceive? |
| II Cognitive Biases | Confirmation Bias, Availability Bias, Anchoring Bias, Hindsight Bias, Motivated Reasoning | What systematic deviations from normative reasoning shape perception and judgment, and how do they entrench despite evidence? |
| III Heuristics and Substitution | Representativeness Heuristic, Availability Heuristic, Anchoring Heuristic, Substitution Heuristic, Recognition Heuristic | What mental shortcuts do agents use to simplify reasoning, and what predictable errors do they produce? |
| IV Attention Allocation | Selective Attention Filter, Salience-Driven Attention, Working Memory Limit, Automatization Blindness, Attentional Tunneling | What gets attended to and what remains peripheral or invisible, and how does selective attention constrain perception? |
| V Bounded Rationality | Satisficing Decision Rule, Information Incompleteness, Option Overload and Reduction, Framing Effect, Status Quo Bias and Default Effect | What constraints limit how much information agents can process and how many options they can evaluate? |
| VI Reasoning Processes | Hidden Premise Reasoning, Analogical Reasoning, Deductive Reasoning Validity, Inductive Reasoning Weakness, Intuitive Judgment Dominance | What reasoning structures (deductive, inductive, abductive, analogical, intuitive) do agents use, and what are their failure modes? |

---

## Section 5: Condensed Dynamics

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| Mental Model Entrenchment | Model becomes increasingly resistant to revision despite contradicting evidence; agent interprets new evidence as confirming model. | Confirmation bias applied to model; model's past success makes agent confident; identity fusion with model; sunk costs block revision. | Model lock-in prevents adaptation to changed reality; agent continues reasoning from outdated model; persistent blindness and false confidence. |
| Bias Reinforcement Cycle | Bias produces action; action produces evidence seemingly confirming bias; evidence strengthens bias. | Self-fulfilling prophecy; confirmation bias applied to consequences of biased action; agent sees evidence confirming bias. | Biases entrench through action-consequence feedback; agent becomes more confident despite objective misalignment; cycles are resistant to information provision. |
| Attention Capture Escalation | Salient event captures attention; attention narrows; peripheral information is lost; narrow attention makes problem worse; escalation continues. | Attentional tunneling + stress-induced narrowing + loss of situational awareness + poor decisions from incomplete information. | Escalation converts manageable problem into crisis; tunnel vision prevents corrective action; attention narrowing accelerates failure. |
| Heuristic Substitution Chains | Agent uses heuristic for one judgment; heuristic error produces misestimate; downstream judgments compound error; chain of errors from single substitution. | Representativeness or availability heuristic error; probability misjudgment drives resource allocation; allocation produces outcome confirming initial wrong estimate. | Single heuristic error cascades; each downstream step seems reasonable but compounds original error; outcome appears to confirm reasoning. |
| Expert Blind Spot Persistence | Expert automated reasoning prevents seeing what expert takes for granted; expert resists revision because reasoning is implicit; expert becomes increasingly confident. | Automation renders reasoning invisible; confidence without deliberation; resistance to feedback; expertise reinforces automatization. | Expert confidently makes errors in edge cases or changed contexts; expert cannot learn from feedback; expertise becomes liability in novel situations. |
| Novice Option Expansion | Novice, lacking domain knowledge, considers options expert would discard; considers unconventional approaches; some produce surprising success. | Novice does not "know" what is impossible; considers paths expert would never try; some options are better for changed contexts. | Novice can find novel solutions expert would miss; leveraging novice options requires careful evaluation and combination with expert judgment. |
| Framing Cascade | Initial framing shapes attention and option set; option set shapes reasoning; reasoning shapes decision; decision outcomes reinforce original framing. | Framing effects produce different choice; choice commits resources; outcomes confirm framing; framing appears validated by experience. | Arbitrary initial framing can lock in suboptimal path; reframing is hard because path-dependent costs make change costly. |
| Paradigm Lock-In | Paradigm boundaries make certain hypotheses unthinkable; unthinkable hypotheses are not tested; absence of testing is treated as evidence paradigm is correct. | Paradigm excludes hypotheses; hypotheses untested; absence of evidence for hypotheses becomes evidence for paradigm. | Paradigm can lock out critical realities outside paradigm boundaries; learning is impossible until paradigm shift occurs. |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | What mental models do agents use to perceive this situation, and what does each model make invisible or impossible to notice? |
| II (Systemic) | How do agents' cognitive processes interact with each other and with system structure to create cascading perception failures? |
| III (Informational) | What information is available to agents but filtered out by attention limits, cognitive biases, or mental model mismatch? |
| IV (Temporal) | How do mental model entrenchment, bias reinforcement cycles, and expertise automation increase over time as agents gain confidence? |
| V (Relational) | How do cognitive processes create asymmetric perception or judgment between agents, enabling some to see what others cannot? |
| VI (Ontological) | What categories and frameworks do agents use to make sense of reality, and what alternatives remain unthinkable within those categories? |

### 6b. Primary Hiding Mechanisms This Framework Detects

- Model-Based Blindness (what mental models exclude from perception becomes invisible)
- Expertise Automatization Blindness (what expert takes for granted cannot be articulated or questioned)
- Attention Allocation Invisibility (what is not attended to is peripheral or forgotten)
- Heuristic-Driven Error Invisibility (errors from mental shortcuts are systematic but appear random to agent)
- Bias Entrenchment Through Confirmation (evidence filtered by confirmation bias becomes increasingly distorted from reality)
- Bounded Rationality Constraints (limits on working memory, option evaluation, and information processing force satisficing without awareness)

### 6c. Detection/Remediation Interface Pointers

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| Mental model misalignment with current reality | Framework of Realities; Framework of Diagnosis | Reality ground-truthing; model validation testing | Compare model predictions to current outcomes; revise model through explicit articulation and testing |
| Expert blind spot preventing seeing edge-case failures | Framework of Expertise; Framework of Risk | Expert-novice pairing; perspective-taking; outsider review | Pair expert with novice; require expert to articulate reasoning; periodic outside expert review |
| Attention blindness from automation or salience misalignment | Framework of Processes; Framework of Situations | Attention-management protocol; stimulus-response redesign | Widen attention through deliberate check protocols; rotate focus periodically; assign monitoring roles |
| Cognitive bias in high-consequence judgment (confirmation, anchoring, availability) | Framework of Evidence; Framework of Decisions | Decision-quality audit; bias-awareness training; decision-support systems | Slow decisions; require multiple perspectives; use decision checklist and evidence standards |
| Heuristic substitution errors in probability or outcome prediction | Framework of Predictions; Framework of Metrics | Forecast error analysis; prediction mechanism audit | Decompose heuristic; test whether simpler/more accurate method is available |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

1. Identify focal agents and key cognitive processes (top 3–5) that are diagnosis-critical: which agents perceive ambiguously, attend selectively, or reason under constraints?
2. For each focal agent, map one or two dominant mental models that shape perception; note what the model makes invisible or impossible to perceive.
3. Assess whether cognitive biases or heuristics are active (confirmation bias, availability bias, representativeness heuristic, anchoring); identify high-consequence error patterns.
4. Run Tier 1 Hiddens scan: touch all six Hiddens meta-categories lightly; flag perceptual blindspots (what agents don't see), attention gaps (what is peripheral), and reasoning constraints (what bounded rationality prevents).
5. Shortlist 2–3 highest-consequence cognitive Hiddens; note whether they are reversible (correctable through awareness) or persistent (require structural intervention); escalate if high-consequence and high-uncertainty.

### 7b. Full Depth Execution (Complete framework run)

1. Inventory focal agents; profile each agent's mental models (causal, system structure, normalcy, expert intuition, paradigm); compare models to current reality; map model-reality alignment gaps.
2. Classify cognitive processes for each agent: assign each process to one or more core types (I–VI); assess which types are high-consequence in this scenario.
3. For each high-consequence cognitive process, assess five cross-cutting dimensions: Scope (narrow vs broad domain), Systematicity (predictable vs idiosyncratic), Reversibility (correctable vs persistent), Contextuality (context-dependent vs context-invariant), Automaticity (deliberate vs automatic); record dimension profiles.
4. Analyse all eight dynamic patterns; assess which are active or nascent (mental model entrenchment, bias reinforcement cycles, attention capture escalation, heuristic chains, expert blind spot persistence, novice option expansion, framing cascades, paradigm lock-in); identify which create cascades and compound effects.
5. Map three interface types: Perception Interface (what agents notice and miss based on mental models and attention), Reasoning Interface (what reasoning structure guides judgment and what constraints limit reasoning), Intervention Interface (what cognitive interventions would work with this mechanism).
6. Run Tier 1 + Tier 2 Hiddens scan (structured deepening): for each high-relevance Hidden (model-based blindness, expertise blindness, attention blindness, bias entrenchment, bounded rationality constraint, reasoning failure), identify mechanism, detectability, agency, consequence; assign detection and remediation interfaces.
7. Document unresolved Unknowns; apply Escalation Rule if any Unknown could change decisions or affect vulnerability; generate Residual Unknowns register and closure artefacts.

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | Add cognitive-process Hiddens with mechanism, detection pathway, consequence, reversibility; tag by meta-category I–VI. | Tier 1 scan completion; escalate high-consequence/high-uncertainty Hiddens to Tier 2. |
| Evidence Ledger | Record cognitive process classification, dimension assessments, mental model fit to reality, dynamic pattern presence, evidence quality, inference vs observation. | After cognitive inventory and dimensional profiling; note gaps requiring mental model testing or behavioral observation. |
| Hypothesis/Test Backlog | Add hypotheses about cognitive processes driving perception gaps; propose tests (mental model interviews, prediction tasks, think-aloud protocols, behavioral observation, outcome tracking). | Identified Unknowns; residual Hiddens from Tier 1 scan; escalation decisions. |
| Information Requests | Request access to agents for mental model elicitation; request behavioral data (decisions made, outcomes observed, error patterns); request baseline for comparison with ground truth. | To reduce Unknowns and validate cognitive diagnosis; coordinate with Evidence and Expertise frameworks. |

**Gate Question (pre-closure check):** Have we identified focal agents, mapped their dominant mental models and cognitive processes, assessed model-reality alignment, run a Tier 1 Hiddens scan across all six meta-categories, and escalated high-consequence cognitive Unknowns to appropriate frameworks (Hiddens, Evidence, Risk, Diagnosis)?

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

- Situations Context Classification (what situation type triggers which cognitive processes?)
- Boundaries (where are agents' perceptual boundaries; do agents perceive boundaries correctly?)
- Evidence (what information is available to agents; do agents perceive available evidence?)
- Knowledge (what knowledge is distributed; what knowledge do agents use or fail to use?)
- Experiences (what is agents' past exposure; how does experience shape mental models?)
- Expertise (what domains are agents expert in; where are expert blind spots and novice blindness?)

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

- Framework of Hiddens (cognitive mechanisms generating hiddens; remediation design)
- Framework of Diagnosis (cognitive barriers preventing self-diagnosis; diagnosis interventions)
- Framework of Decisions (cognitive constraints requiring decision redesign; decision support systems)
- Framework of Interventions (cognitive interventions targeting mental model revision, attention management, bias awareness, reasoning improvement)
- Framework of Risk (cognitive processes generating material risks; vulnerability from cognitive misalignment)
- Framework of Realities (comparing agents' mental models to current reality; identifying model-reality gaps)

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

| Targeted Scan | Role of this framework |
|---|---|
| Scan 2: Mental model misalignment with reality audit | Surface agents' dominant mental models; compare to current reality; identify model-reality gaps and perception failures. |
| Scan 4: Expert blind spot and novice blindness mapping | Identify where expert automatization creates blindness; where novice perspective reveals what experts miss. |
| Scan 6: Attention allocation and selective perception audit | Identify what agents attend to and miss; how attention allocation creates perception gaps; where attention needs widening. |
| Scan 7: Heuristic-driven error and bias detection | Identify which cognitive biases and heuristics are active; what systematic error patterns they produce; which errors are high-consequence. |
| Scan 10: Bounded rationality and reasoning constraint analysis | Identify cognitive constraints (working memory, option overload, information processing limits); how constraints force satisficing. |

---

*LLM Execution Extract v1.0 – Cognition Framework (2026-04-08) – End of Extract*
5. **Automaticity** — Deliberate/effortful vs automatic/implicit (can agent articulate reasoning?)

---

## Ten Cognitive Dynamics (patterns over time)

1. **Mental Model Entrenchment** — model becomes resistant to revision despite disconfirming evidence
2. **Bias Reinforcement Cycle** — bias produces action; action produces evidence confirming bias
3. **Attention Capture Escalation** — salient event captures attention; narrowing makes problem worse
4. **Heuristic Substitution Chains** — single heuristic error cascades through downstream judgments
5. **Expert Blind Spot Persistence** — expert automated reasoning prevents seeing assumptions
6. **Novice Option Expansion** — novice considers unconventional options expert would discard
7. **Framing Cascade** — initial framing locks in option set and reasoning path
8. **Paradigm Lock-In** — paradigm boundaries make hypotheses unthinkable; unthinkable = untested

---

## Three Interface Types

| Type | Name | Use for |
|---|---|---|
| A | **Perception Interface** | Observe/measure what agents perceive vs miss; mental model fit; bias activation; selective attention patterns |
| B | **Reasoning Interface** | Diagnose reasoning validity; heuristic use; bounded rationality constraints; hidden premises |
| C | **Intervention Interface** | Design cognitive interventions targeting right mechanism (mental model revision, bias awareness, attention widening, reasoning support) |

---

## Hiddens Source Analysis (5 framework-specific generators)

1. **Mental Model Invisibility Blindness** — analysis assumes agents perceive available info; misses that models determine visibility
2. **Expert Blind Spot Underestimation** — assumes expertise = accurate perception; misses what experts have automated
3. **Bias Underestimation as Error** — treats biases as information deficit when they are systematic reasoning features
4. **Attention Allocation Invisibility** — assumes available info = attended info; misses selective attention and working memory limits
5. **Bounded Rationality Denial** — assumes rational agents can process infinite info; expects optimisation not satisficing

---

## Tier 1 Hiddens Scan (early + pre-closure; all 6 categories invariant)

| Meta-category | Why active here? | Symptoms | Default checks |
|---|---|---|---|
| **I — Perceptual** | Mental models misaligned with reality | Agents miss anomalies; confident despite gaps; surprised by expected events | Map mental models; test predictions; anomaly detection tasks |
| **II — Systemic** | Cognitive blindness embedded in roles/expertise | Expertise prevents questioning; consensus closes inquiry; role-based blindness | Map expertise hierarchy; test psychological safety for questioning |
| **III — Informational** | Biases filter information systematically | Selective evidence-seeking; dismissal of disconfirming evidence; framing-dependent conclusions | Test evidence uptake; present disconfirming evidence; map filters |
| **IV — Temporal** | Mental models locked to past contexts | Beliefs based on outdated info; slow adaptation; models persist past applicability | Timeline model origins; compare to current reality; temporal drift check |
| **V — Relational** | Cognitive processes maintained through social enforcement | Perception varies public vs private; authority dominates; questioning is costly | Compare anonymous vs public perception; map epistemic trust; assess safety |
| **VI — Ontological** | Paradigm boundaries make realities unthinkable | Certain questions not asked; hypotheses rejected a priori; boundaries invisible | Expose paradigm through alternatives; test admissibility rules; paradigm-challenge sessions |

---

## Tier 2 Hiddens Crosswalk (top ~5–10 candidates)

For each high-consequence Hidden:
- **Mechanism** — how it is produced/maintained
- **Detectability** — how observable/testable
- **Detection Interface** — how to surface it (Type A)
- **Remediation Interface** — how to address it (Type B)
- **Interaction notes** — interaction chains (Type C)

Common Cognition Hiddens to investigate:
- **C-Mental-Model-Lock-In** (1/2/3/4/5) — outdated model; confirmation bias entrenchment; paradigm lock
- **C-Expert-Blind-Spot** (4) — automated reasoning invisibility; edge case failure
- **C-Confirmation-Bias** (6) — selective evidence; persistence despite awareness
- **C-Attention-Allocation-Failure** (16–20) — salient overattended; peripheral invisible
- **C-Mental-Model-Mismatch** (1/2/3) — model-reality divergence; intervention failure

---

## Tier 3 Escalation Triggers

Escalate to full-spectrum Hiddens taxonomy if:
- High consequence (safety, regulatory, existential; strategy at risk)
- Expert blind spot plausible (decisions by experts in edge cases)
- Mental model misalignment likely (models based on past; reality changed)
- Persistent perception gaps (agents continue to miss available info)
- Multiple cognitive biases cascade (confirmation + availability + motivated reasoning interact)
- Decision-critical residual unknowns remain

---

## Application Steps (7-step protocol)

1. **Situation & Cognition Clarification** — routing decision, Run Mode, Depth selection
2. **Mental Model Surfacing & Validation** — interviews, prediction tasks, anomaly tests; model-reality comparison
3. **Cognitive Bias & Heuristic Mapping** — identify active biases/heuristics; profile along 5 dimensions
4. **Attention & Expertise Dynamics** — map attention allocation; expert/novice blindness; automatization
5. **Bounded Rationality & Reasoning** — cognitive constraints; reasoning processes; error patterns
6. **Hiddens Scanning & Tier 2 Deepening** — Tier 1 scan; shortlist candidates; Tier 2 working models; invoke Targeted Scans if indicated
7. **Integration & Closure** — handoff to Diagnosis/Decisions/Interventions; residual Unknowns; closure artefacts (5-item closure per OG §7.4)

---

## Standard Deliverables

**Minimum (2–4 pages):**
- Mental model inventory + model-reality misalignment
- Top 3–5 cognitive biases/heuristics + consequence
- Expert-novice blindness comparison (if relevant)
- Top 3–5 Hiddens + remediation interfaces
- Recommendations + monitoring indicators

**Full pack:**
- Complete cognitive process inventory (all 30 types if Full Depth)
- Mental model map (model structure, gaps, consequences)
- Cognitive bias cascade (how biases reinforce each other)
- Attention map (attended, peripheral, salience drivers)
- Expertise map (expert/novice blindness, automatization)
- Bounded rationality constraint analysis
- Reasoning process analysis (structures, validity, errors)
- Hiddens Register (populated)
- Tier 2 crosswalk (top candidates, mechanisms, interfaces)
- Targeted Scans findings (if any invoked)
- Hypothesis/Test Backlog
- Residual Unknowns + Closure note (all 5 items)
- Monitoring plan (leading indicators, review cadence)

---

## Integration with 36 Canonical Frameworks

**Upstream inputs:**
- Evidence (agents must perceive and reason about available evidence)
- Knowledge (agents use knowledge given cognitive constraints)
- Beliefs (formation mechanisms; cognitive processes shape beliefs)
- Experiences (experience shapes mental models and expertise)
- Emotions (emotions shape attention and judgment)

**Downstream outputs:**
- Diagnosis (cognitive blindness explains diagnosis difficulty)
- Decisions (cognitive constraints inform decision design)
- Interventions (cognitive mechanisms guide intervention targeting)
- Hiddens (cognitive blindness populated in Hiddens Register)
- Risk (cognitive processes generate risks)

**Key integration questions:**
- What mental models do agents use? Where are they misaligned with reality?
- What cognitive biases are decision-critical?
- What expertise creates both capability and blindness?
- What attention allocation issues are material?
- What cognitive constraints limit decision-making?
- What cognitive processes generate Hiddens?

---

## Five Framework Principles

1. **Cognition is mechanism, not error** — Biases, heuristics, attention limits are how minds work; treat as mechanisms to work with
2. **Mental models determine visibility** — Perception determined by frameworks; information outside model's categories is invisible
3. **Expertise creates complementary blindness** — Experts automated (fast, accurate but blind); novices explicit (slow but see what experts miss)
4. **Attention is selective and limited** — Working memory ~5–9 items; design for actual limits, not idealised unlimited attention
5. **Cognitive blindness requires cognitive intervention** — Information provision insufficient; must target mechanism (mental model revision, bias awareness, attention widening)

---

## Execution Rules (Operating Guide aligned)

- **Run Mode:** Rapid (Light Depth, top 3–5 processes) vs Investigative (Full Depth, all 30 types)
- **Depth:** Light (default) escalates to Full when: high consequence, perception gaps decision-critical, expert blind spots plausible, mental model lock-in evident, multiple biases cascade
- **Tier 1 Scan:** Mandatory early + pre-closure (both Rapid and Investigative)
- **Tier 2:** Standard in Investigative; optional top 1–3 in Rapid
- **Tier 3:** Escalation only (high consequence, persistent gaps, cascades, residual Unknowns decision-critical)
- **Targeted Hiddens Scans:** When Tier 1 symptoms point to specific mechanism — typically Positional Blindness Scan (expertise), Paradigm Boundary Scan (mental models), Cascade Scan (multiple biases)
- **Closure:** All 5 items per OG §7.4 (residual unknowns, acceptability, monitoring, ownership, learning hook)

---

## Key Terms (local)

- **Automatization** — unconscious processing of frequent tasks; invisible reasoning, blindness to assumptions
- **Base-Rate Neglect** — ignoring population-level information when judging probability (representativeness error)
- **Bounded Rationality** — cannot evaluate infinite options, process unlimited info, compute perfect probability
- **Causal Model** — agent's representation of what causes what; determines intervention beliefs
- **Cognitive Bias** — systematic reasoning deviation from normality (predictable, not low-ability)
- **Cognitive Blindness** — invisible to agents due to how minds work (model-based, attention, expert, novice blindness)
- **Confirmation Bias** — selective seek/attend/remember confirming evidence; filter disconfirming
- **Expert Blind Spot** — what experts cannot see (automated, take for granted, optimised to exclude)
- **Framing Effect** — how problem presented affects choice (same decision → different choice)
- **Heuristic** — mental shortcut (efficient, error-prone); availability, representativeness, anchoring, etc.
- **Hindsight Bias** — outcomes appear more predictable in hindsight than beforehand
- **Inattentional Blindness** — fail to perceive stimulus because attention is focused elsewhere
- **Mental Model** — agent's internal representation of how system/domain works
- **Mental Model Lock-In** — resistance to revision despite contradicting evidence
- **Model-Based Blindness** — anomalies outside model are perceptually unavailable
- **Motivated Reasoning** — shift evidential standards based on preferred conclusions
- **Novice Blindness** — cannot perceive implications experts understand implicitly
- **Satisficing** — choose option meeting minimum criteria; do not search for optimal
- **Working Memory** — holds ~5–9 items during reasoning; capacity limit produces errors

---

**LLM Extract version:** v1.0  
**Date:** 2026-04-08  
**Status:** Draft  
**Companion:** Framework_of_Cognition_v1.0.md (full document)  
**Operating Guide:** v2.4 compatible
