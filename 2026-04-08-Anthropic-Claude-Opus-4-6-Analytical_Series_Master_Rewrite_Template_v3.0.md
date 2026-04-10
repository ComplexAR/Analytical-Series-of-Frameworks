# Analytical Series Framework – Master Rewrite Template v3.0 (Markdown)
<!--
PURPOSE
- This is the canonical rewrite template for every framework in the Analytical Series.
- It standardises: section order, table schemas, invariants, naming conventions, and integration hooks.
- Use this template as the “single source of truth” for consistent structure across the series.

USAGE INSTRUCTIONS
1) Copy this file, rename to: YYYY-MM-DD-<Author>-Framework_of_<X>_vN.md (or project naming standard).
2) Replace placeholder tokens of the form {{TOKEN}}.
3) Keep section numbers and table schemas unchanged unless the “Deviation Rules” allow it.
4) Avoid long verbatim reuse of prior text; prefer re-expression while preserving meaning.

LLM + OPERATING GUIDE INTEGRATION (v3.0 REVISION)
- Every rewritten framework MUST include a standard section:
  “## 1.6 LLM Integration Bridge”
  with the three subsections defined in this template (1.6.1 pointer, 1.6.2 disambiguation, 1.6.3 routing triggers).
- The Analytical Series Operating Guide v2.5 is authoritative for all prompt discipline, output contracts,
  run mode semantics, routing decision logic, tiered Hiddens scans, targeted scans, and closure discipline.
- Full LLM execution infrastructure is in the LLM-Only Operating Guide (separate document).
- CANONICAL SOURCE RULE:
  The Operating Guide is the single source of truth. Framework documents must NOT reproduce prompt discipline
  content locally — use pointers only. Changes are made in the Operating Guide first and propagated mechanically.

STRUCTURAL INVARIANTS (default)
- 6 meta-categories (I–VI), each with 5 core types = 30 core types total.
- 5 cross-cutting dimensions (“five dimensions of any {{X}}”).
- An explicit “Assumptions & Preconditions” subsection in Section 1 (to surface dependency claims and applicability limits).
- A dynamics section (patterns over time).
- 3 interface types (A/B/C) if applicable; otherwise declare your interface model explicitly.
- Section 8 is ALWAYS “Hiddens Source Analysis & Hiddens Cross-Check”.
- Application protocol is table-driven and ends with artefacts/deliverables.

DEVIATION RULES
- If your framework deviates (e.g., >30 types, !=6 meta-categories, !=5 dimensions), you MUST:
  a) state the deviation explicitly in the At-a-Glance box and in the relevant section header note,
  b) provide a mapping back to the canonical baseline (or explain why it cannot be mapped),
  c) increment major version (vX.0) for structural changes.
-->

# Framework of {{X}}
*{{SUBTITLE_ONE_LINE}}*

## Document Information
- Series: Analytical Series of Frameworks
- Version: {{VERSION}}
- Date: {{DATE_YYYY_MM_DD}}
- Status: {{STATUS_DRAFT_STABLE_DEPRECATED}}
- Operating Guide Compatibility: Analytical Series Operating Guide v2.5
- Prompt Discipline Ruleset: Operating Guide “Prompt Discipline Rules (Canonical)” (see OG v2.4, §D.3)
- Run Mode Terminology: Rapid Run Mode / Investigative Run Mode (see Operating Guide §D.10.1)
- Framework Execution Depth Terminology: Full Depth Framework Execution / Light Depth Framework Execution (see Operating Guide §D.10.1)
- Tiered Hiddens Scan Model: Tier 1 (six-category visibility audit) / Tier 2 (structured deepening) / Tier 3 (full-spectrum escalation) (see Operating Guide §D.6.10)
- Targeted Hiddens Discovery Scans: Thirteen mechanism-specific cross-framework scans (see Operating Guide §7.5)
- Group (Primary): {{GROUP_PRIMARY}} — {{GROUP_PRIMARY_LONGHAND}} ({{GROUP_PRIMARY_SHORTHAND}})
- Group (Secondary): {{GROUP_SECONDARY}} — {{GROUP_SECONDARY_LONGHAND}} ({{GROUP_SECONDARY_SHORTHAND}})  # optional; use “None” if not applicable
- Default Depth Guidance: {{DEFAULT_DEPTH_GUIDANCE}}  # e.g., “Light Depth by default; Full Depth when routed by OG §4.3”
- Owner / Maintainer: {{OWNER}}
- Intended Use: {{PRIMARY_USE_CASES}}
- Primary Audience: {{AUDIENCE}}
- Dependencies / Key Inputs: {{KEY_INPUTS}}
- Primary Outputs: {{KEY_OUTPUTS}}
- Change Log (brief): {{CHANGELOG_BRIEF}}

---

## At-a-Glance: Core Premise Summary
<!-- Keep this table shape identical across all frameworks. -->
| Element | Content |
|---|---|
| Primary Question | **{{PRIMARY_QUESTION}}** |
| Addresses | {{ADDRESSES}} |
| Gap Filled | {{GAP_FILLED}} |
| Complements | {{COMPLEMENTS_LIST}} |
| Key Characteristics | {{KEY_CHARACTERISTICS}} |
| Main Contributions | {{MAIN_CONTRIBUTIONS}} |

---

# Introduction
<!--
PURPOSE:
- This section provides an accessible, narrative overview of the subject area that this framework addresses.
- It orients the reader (human or LLM) to: what {{X}} is, why it matters for complex scenario analysis,
  what kinds of visibility failures and hiding mechanisms it is designed to surface, and what the framework
  produces as outputs for the broader Analytical Series.
- Modelled on the Operating Guide's own Introduction (OG v2.4, Introduction), but scoped to the specific
  domain of this framework rather than the series as a whole.

STRUCTURE (recommended — four subsections):
1) "What is {{X}}?" — Define the subject area in plain language; explain why it is analytically important;
   describe the kinds of realities that become hidden when {{X}} is poorly understood or ignored.
2) "Why does {{X}} matter for Hiddens work?" — Explain the connection between this subject area and the
   series' central concern with visibility failures. What hiding mechanisms does this framework help surface?
   What goes wrong (in terms of hiddenness) when this lens is absent?
3) "What does this framework produce?" — Briefly describe the outputs: types taxonomy, dimensions, dynamics,
   interfaces, and the standard registers this framework populates. How do these artefacts integrate with the
   broader investigation?
4) "How to use this framework" — Provide a short orientation for practitioners and LLMs: when to invoke this
   framework (typical scenario features), at what depth (default Light Depth vs Full Depth per routing), and
   how it connects to the iterative investigation loop (OG v2.4, §5.0).

GUIDANCE:
- Keep the Introduction concise (typically 4–8 paragraphs across the four subsections).
- Write for practitioners, not theorists: enable diagnosis and action, not academic review.
- Avoid duplicating material from the At-a-Glance table or §1.1 Core Premise. The Introduction is broader
  and more accessible; the Core Premise is more precise and operational.
- The Introduction should be readable as a standalone orientation — someone reading only this section should
  understand what the framework does and why it exists.
-->

## What is {{X}}?
<!--
Guidance:
- 1–2 paragraphs. Define the subject area in plain language.
- Explain why {{X}} is analytically important in complex scenarios.
- Describe the kinds of realities that become hidden when {{X}} is poorly understood or ignored.
-->
{{INTRO_WHAT_IS_X}}

## Why does {{X}} matter for Hiddens work?
<!--
Guidance:
- 1–2 paragraphs. Connect this subject area to the series' central concern with visibility failures.
- What hiding mechanisms does this framework help surface? (Reference the relevant Hiddens meta-categories I–VI.)
- What goes wrong — in terms of hiddenness, not just "bad outcomes" — when this analytical lens is absent?
- Where possible, give a concrete example of a hiding mechanism this framework is designed to detect.
-->
{{INTRO_WHY_HIDDENS}}

## What does this framework produce?
<!--
Guidance:
- 1–2 paragraphs. Briefly describe the framework's outputs:
  - Core taxonomy (meta-categories, types, dimensions, dynamics, interfaces)
  - Standard registers this framework populates (Hiddens Register, Evidence Ledger, Hypothesis/Test Backlog, Information Requests)
  - How these artefacts integrate with the broader investigation (upstream inputs, downstream consumers)
- Keep this operational, not exhaustive — point the reader to the relevant sections for detail.
-->
{{INTRO_WHAT_PRODUCES}}

## How to use this framework
<!--
Guidance:
- 1–2 paragraphs. Provide a short orientation for practitioners and LLMs:
  - When to invoke this framework (typical scenario features that trigger routing to it; see OG v2.4, §4.3)
  - Default execution depth (Light Depth vs Full Depth per OG routing)
  - How it connects to the iterative investigation loop (OG v2.4, §5.0)
  - Whether any Targeted Hiddens Discovery Scans (OG v2.4, §7.5) commonly involve this framework
  - For LLM execution: point to §1.6 for the full LLM integration specification
-->
{{INTRO_HOW_TO_USE}}

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)
<!--
Guidance:
- 2–6 paragraphs. Define what {{X}} is as an analytic object.
- Explain why {{X}} matters, and what fails without it.
- Describe what the framework *produces* (artefacts, decisions, maps, registers).
- Keep it operational: enable diagnosis and action, not just description.
-->
{{CORE_PREMISE_NARRATIVE}}

## 1.2 Assumptions & Preconditions
<!--
Guidance:
- Make *dependency claims* explicit. These are conditions the framework assumes (assumptions) or requires (preconditions) to be valid or usable.
- Keep this section operational: each item should be testable, monitorable, or at least falsifiable in principle.
- Distinguish:
  - Assumptions: accepted-as-true claims used to proceed (method, structure, domain, or normative assumptions).
  - Preconditions: conditions that must hold for applying this framework or trusting its outputs in this context.
- Link high-impact items to Evidence/Uncertainties/Hiddens:
  - If an assumption is weak or contested, register it as an uncertainty and specify handling (reduce, hedge, robustify, option-create).
  - If an assumption may be strategically hidden, suppressed, or distorted, trigger a Hiddens check (and escalate if material).
-->

### Assumptions Register (recommended)
| Assumption | Type (method / structural / domain / normative) | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| {{ASSUMPTION_1}} | {{ASSUMPTION_1_TYPE}} | {{ASSUMPTION_1_FAILURE}} | {{ASSUMPTION_1_TEST}} | {{ASSUMPTION_1_MITIGATION}} |
| {{ASSUMPTION_2}} | {{ASSUMPTION_2_TYPE}} | {{ASSUMPTION_2_FAILURE}} | {{ASSUMPTION_2_TEST}} | {{ASSUMPTION_2_MITIGATION}} |
| {{ASSUMPTION_3}} | {{ASSUMPTION_3_TYPE}} | {{ASSUMPTION_3_FAILURE}} | {{ASSUMPTION_3_TEST}} | {{ASSUMPTION_3_MITIGATION}} |
| {{ASSUMPTIONS_ADDITIONAL_ROWS}} |  |  |  |  |

### Preconditions Checklist (recommended)
| Precondition | Required? (Y/N) | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| {{PRECONDITION_1}} | {{PRECONDITION_1_REQUIRED}} | {{PRECONDITION_1_EVIDENCE}} | {{PRECONDITION_1_OWNER}} | {{PRECONDITION_1_STATUS}} | {{PRECONDITION_1_WORKAROUND}} |
| {{PRECONDITION_2}} | {{PRECONDITION_2_REQUIRED}} | {{PRECONDITION_2_EVIDENCE}} | {{PRECONDITION_2_OWNER}} | {{PRECONDITION_2_STATUS}} | {{PRECONDITION_2_WORKAROUND}} |
| {{PRECONDITION_3}} | {{PRECONDITION_3_REQUIRED}} | {{PRECONDITION_3_EVIDENCE}} | {{PRECONDITION_3_OWNER}} | {{PRECONDITION_3_STATUS}} | {{PRECONDITION_3_WORKAROUND}} |
| {{PRECONDITIONS_ADDITIONAL_ROWS}} |  |  |  |  |  |


## 1.3 Definitions, Scope, and Non-Goals
- Definition of {{X}}: {{DEFINITION}}
- In scope: {{IN_SCOPE_BULLETS}}
- Out of scope: {{OUT_OF_SCOPE_BULLETS}}
- Common confusions (“{{X}} is not …”): {{COMMON_CONFUSIONS}}

## 1.4 Position in the Series (Upstream / Middle / Downstream)
<!--
Guidance:
- Upstream: frameworks that feed inputs (situation typing, evidence, causation, etc.)
- Middle: what this framework transforms
- Downstream: frameworks that consume outputs (decisions, interventions, governance, responsibility, etc.)
-->
- Upstream (signals/understanding): {{UPSTREAM_FRAMEWORKS}}
- Middle (this framework’s role): {{MIDDLE_ROLE}}
- Downstream (action/governance): {{DOWNSTREAM_FRAMEWORKS}}

- Group assignment (Primary): {{GROUP_PRIMARY}} — {{GROUP_PRIMARY_LONGHAND}} ({{GROUP_PRIMARY_SHORTHAND}})
- Group assignment (Secondary): {{GROUP_SECONDARY}} — {{GROUP_SECONDARY_LONGHAND}} ({{GROUP_SECONDARY_SHORTHAND}})  # optional
- Stage assignment: {{STAGE}}  # Upstream / Middle / Downstream / Cross-cutting (see OG §3.1)
- Run mode selection: Rapid Run Mode vs Investigative Run Mode (OG §D.9.2 Mode Selection Gate)
- Operating Guide routing: apply decision logic at Start-of-Run and Pre-Closure (OG §4.3)  # produces minimum group coverage + Full Depth / Light Depth plan (per §4.3.2)
- Non-conflation invariant: do not conflate Run Mode with Framework Execution Depth (OG §D.10.1)
- Iteration loop: Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG §5.0)
- Framework Index: this framework is one of 36 in the series (see OG §3.2 for the full Framework-to-Group mapping)


## 1.5 Crosswalk Summary (recommended)
| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|
| Descriptive | {{DESCRIPTIVE_FRAMEWORKS}} | {{DESCRIPTIVE_PROVIDES}} | {{DESCRIPTIVE_ADDS}} |
| Epistemic | {{EPISTEMIC_FRAMEWORKS}} | {{EPISTEMIC_PROVIDES}} | {{EPISTEMIC_ADDS}} |
| Normative | {{NORMATIVE_FRAMEWORKS}} | {{NORMATIVE_PROVIDES}} | {{NORMATIVE_ADDS}} |
| Action | {{ACTION_FRAMEWORKS}} | {{ACTION_PROVIDES}} | {{ACTION_ADDS}} |

---

## 1.6 LLM Integration Bridge
<!--
Purpose: Compact LLM routing interface. Contains only what an LLM needs to route to and execute this framework.
Full prompt discipline, output contracts, run mode semantics, and artefact schemas are in the LLM-Only Operating Guide.
This section must stay within 300–500 tokens when populated (i.e., when {{tokens}} are filled in for a specific framework).
-->

### 1.6.1 LLM Execution Extract pointer
- Extract file: `{{EXTRACT_FILENAME}}`  <!-- naming: YYYY-MM-DD-...-Framework_of_{{X}}_LLM_Extract_v1.0.md -->
- Extract version: {{EXTRACT_VERSION}}
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
<!-- 2–4 nearest frameworks only. Each row: when to use THIS framework vs when to use the neighbour instead. -->
| Nearest neighbour | Use {{X}} when… | Use neighbour instead when… |
|---|---|---|
| {{NEIGHBOUR_1}} | {{USE_THIS_WHEN_1}} | {{USE_NEIGHBOUR_WHEN_1}} |
| {{NEIGHBOUR_2}} | {{USE_THIS_WHEN_2}} | {{USE_NEIGHBOUR_WHEN_2}} |
| {{NEIGHBOUR_3}} | {{USE_THIS_WHEN_3}} | {{USE_NEIGHBOUR_WHEN_3}} |
| {{NEIGHBOUR_ADDITIONAL_ROWS}} | | |

### 1.6.3 Routing triggers
<!-- Scenario features that should direct analysis to this framework. Terse list — 5–10 items maximum. -->
- {{ROUTING_TRIGGER_1}}
- {{ROUTING_TRIGGER_2}}
- {{ROUTING_TRIGGER_3}}
- {{ROUTING_TRIGGER_4}}
- {{ROUTING_TRIGGER_5}}
- {{ROUTING_TRIGGER_ADDITIONAL}}

---


# 2. Meta-Categories of {{X}}
<!-- Default: 6 meta-categories (I–VI). If deviating, state and map. -->

## 2.1 Meta-Categories Table (mandatory)
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | {{MC1_NAME}} | {{MC1_QUESTION}} | {{MC1_FOCUS}} | {{MC1_ARTEFACTS}} |
| II | {{MC2_NAME}} | {{MC2_QUESTION}} | {{MC2_FOCUS}} | {{MC2_ARTEFACTS}} |
| III | {{MC3_NAME}} | {{MC3_QUESTION}} | {{MC3_FOCUS}} | {{MC3_ARTEFACTS}} |
| IV | {{MC4_NAME}} | {{MC4_QUESTION}} | {{MC4_FOCUS}} | {{MC4_ARTEFACTS}} |
| V | {{MC5_NAME}} | {{MC5_QUESTION}} | {{MC5_FOCUS}} | {{MC5_ARTEFACTS}} |
| VI | {{MC6_NAME}} | {{MC6_QUESTION}} | {{MC6_FOCUS}} | {{MC6_ARTEFACTS}} |

## 2.2 Meta-Category Descriptions (recommended)
<!-- Repeat the following sub-block for I–VI. Keep short; table is the primary artefact. -->
### I. {{MC1_NAME}}
- Definition: {{MC1_DEF}}
- Diagnostic cues: {{MC1_CUES}}
- Typical failure mode: {{MC1_FAILURE}}

---

# 3. Core Types Taxonomy
<!-- Default: 30 types = 5 per meta-category. If deviating, state and provide mapping back. -->

## 3.0 Canonical Rule & Deviations
- Canonical baseline: 6 meta-categories × 5 types = 30 core types.
- This framework: {{TYPE_COUNT}} types. Deviation rationale: {{DEVIATION_RATIONALE_OR_NONE}}.
- Mapping back to baseline (if needed): {{MAPPING_BACK_TO_BASELINE}}

## 3.1 Types (Category I: {{MC1_NAME}})
<!-- Recommended columns: include one “failure/hidden-risk signature” column if it improves actionability. -->
| # | Type | Description (1–3 sentences) | Diagnostic cues (optional) | Failure / hidden-risk signature (optional) |
|---:|---|---|---|---|
| 1 | {{T1_NAME}} | {{T1_DESC}} | {{T1_CUES}} | {{T1_FAILURE}} |
| 2 | {{T2_NAME}} | {{T2_DESC}} | {{T2_CUES}} | {{T2_FAILURE}} |
| 3 | {{T3_NAME}} | {{T3_DESC}} | {{T3_CUES}} | {{T3_FAILURE}} |
| 4 | {{T4_NAME}} | {{T4_DESC}} | {{T4_CUES}} | {{T4_FAILURE}} |
| 5 | {{T5_NAME}} | {{T5_DESC}} | {{T5_CUES}} | {{T5_FAILURE}} |

<!-- Repeat 3.1 block for categories II–VI, continuing numbering up to 30. -->

## 3.7 Extending the Taxonomy (mandatory)
| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | {{EXT_BASELINE}} |
| Domain-specific refinement | {{EXT_DOMAIN_REFINEMENT}} |
| Preserving mappability | {{EXT_MAPPABILITY}} |
| Structural invariants | {{EXT_INVARIANTS}} |
| Periodic reassessment | {{EXT_REASSESSMENT}} |
| Versioning & governance | {{EXT_VERSIONING_GOVERNANCE}} |

---

# 4. Cross-Cutting Dimensions of Any {{X}}
<!-- Default: 5 dimensions. If deviating, justify and preserve comparability. -->

## 4.1 Dimensions Table (mandatory)
| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| 1. {{D1_NAME}} | {{D1_DESC}} | {{D1_RANGE}} | {{D1_ASSESS}} | {{D1_USE}} |
| 2. {{D2_NAME}} | {{D2_DESC}} | {{D2_RANGE}} | {{D2_ASSESS}} | {{D2_USE}} |
| 3. {{D3_NAME}} | {{D3_DESC}} | {{D3_RANGE}} | {{D3_ASSESS}} | {{D3_USE}} |
| 4. {{D4_NAME}} | {{D4_DESC}} | {{D4_RANGE}} | {{D4_ASSESS}} | {{D4_USE}} |
| 5. {{D5_NAME}} | {{D5_DESC}} | {{D5_RANGE}} | {{D5_ASSESS}} | {{D5_USE}} |

---

# 5. Dynamics (Patterns Over Time)
<!--
Guidance:
- 8–15 patterns is typical; use fewer if the domain is tight.
- Each pattern: signature, mechanism, implications, mitigation.
-->

## 5.1 Dynamic Patterns Table (mandatory)
| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations (optional) |
|---:|---|---|---|---|---|
| 1 | {{P1_NAME}} | {{P1_SIGNATURE}} | {{P1_MECH}} | {{P1_WHY}} | {{P1_MITIGATIONS}} |
| 2 | {{P2_NAME}} | {{P2_SIGNATURE}} | {{P2_MECH}} | {{P2_WHY}} | {{P2_MITIGATIONS}} |
| … | … | … | … | … | … |

---

# 6. Interface Types
<!-- Default: A/B/C interface model if applicable; otherwise state your interface model explicitly. -->

## 6.1 Interface Types Table (mandatory)
| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | {{IF_A_NAME}} | {{IF_A_DESC}} | {{IF_A_QS}} | {{IF_A_EX}} |
| B | {{IF_B_NAME}} | {{IF_B_DESC}} | {{IF_B_QS}} | {{IF_B_EX}} |
| C | {{IF_C_NAME}} | {{IF_C_DESC}} | {{IF_C_QS}} | {{IF_C_EX}} |

---

# 7. Relationship to Other Frameworks (Integration)
<!--
Guidance:
- List the “minimum interoperability set”: Situations, Diagnosis, Causation, Risk, Decisions, Interventions.
- If you are writing Hiddens, treat this section as “visibility-layer integration”.
-->

## 7.1 Primary Integration Links (recommended)
- Inputs expected: {{INTEGRATION_INPUTS}}
- Outputs provided: {{INTEGRATION_OUTPUTS}}

## 7.2 Crosswalk Table (optional but recommended)
| Other framework | What it provides to this one | What this framework provides back | Typical joint use case |
|---|---|---|---|
| {{FW1}} | {{FW1_IN}} | {{FW1_OUT}} | {{FW1_USE}} |
| {{FW2}} | {{FW2_IN}} | {{FW2_OUT}} | {{FW2_USE}} |
| … | … | … | … |


## 7.3 Integration Questions by Framework (recommended)
<!--
v2.3 rule (canonical list pointer — prevents semantic drift), updated for OG v2.4:
- Populate this table with **all 36 frameworks in the Analytical Series**, using the **current canonical list maintained in the Analytical Series Operating Guide v2.4**, at OG §3.2 (“Framework-to-Group mapping”).
- The 36 frameworks are organised across six groups (G1–G6) with stage assignments (Upstream, Middle, Downstream, Cross-cutting) per OG §3.1.
- Do not curate or locally restate the canonical list in this template. When generating a framework document, **copy the list mechanically** from the Operating Guide version you declare in “Document Information”.
- If any framework row is omitted, you MUST:
  (a) justify the omission in §7.1 (“Primary Integration Links”), and
  (b) record it as a deliberate coverage deviation.

Canonical framework list (OG v2.4 §3.2; 36 frameworks):
  G1 (Framing): Situations Context Classification, Boundaries, Dimensions, Realities, Scale, Time
  G2 (Mechanism): Systems, Relations, Processes, Causation, Resources
  G3 (Agency): Agents, Personas, Incentives, Power, Responsibility, Competencies
  G4 (Meaning): Culture and Norms, Perspectives, Narratives, Communications, Legitimacy, Values
  G5 (Epistemics): Beliefs, Evidence, Uncertainties, Failures, Hiddens, Diagnosis, Metrics, Knowledge
  G6 (Action & Control): Decisions, Interventions, Governance, Risk, Learning and Adaptation

Mandatory rule for the Framework of Hiddens (visibility-layer integration):
- If {{X}} = **Hiddens**, this subsection is **mandatory** (not optional).
- Counting convention (reflexive stance):
  - When {{X}} = Hiddens, the table MUST include **all other frameworks** (canonical list excluding Hiddens), PLUS one explicit row named **”Hiddens (self-audit)”**.
  - This **replaces** the standard “Hiddens” row so that the table row-count always equals the canonical list length (36), while preserving the framework’s “applies to itself” stance.
-->

| Framework (from OG v2.4 §3.2 canonical list) | Group | Stage | Integration questions (what this framework should ask / check to integrate with {{X}}) | Outputs / artefacts to pull in | Notes (interfaces, dependencies, visibility risks) |
|---|---|---|---|---|---|
| {{FW_CANON_1}} | {{FW_CANON_1_GROUP}} | {{FW_CANON_1_STAGE}} | {{FW_CANON_1_Q}} | {{FW_CANON_1_PULL}} | {{FW_CANON_1_NOTES}} |
| {{FW_CANON_2}} | {{FW_CANON_2_GROUP}} | {{FW_CANON_2_STAGE}} | {{FW_CANON_2_Q}} | {{FW_CANON_2_PULL}} | {{FW_CANON_2_NOTES}} |
| … | … | … | … | … | … |
| {{FW_CANONICAL_LIST_ROWS — 36 total}} |  |  |  |  |  |


---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)
<!--
INVARIANT:
- Every framework must include both:
  (a) framework-specific hiddens sources, and
  (b) a systematic Hiddens cross-check layer.

STANDARD DEPTH MODEL (OG v2.4 §D.6.10):
- Tier 1 (mandatory, at least twice — early + pre-closure): scan ALL SIX Hiddens meta-categories (I–VI). Primary anti-hiddens control. (OG §7.1)
- Tier 2 (standard in Investigative Run Mode): structured deepening of top ~5–15 Hiddens with mechanism chain, location, persistence drivers, discriminators, detection/remediation interfaces. (OG §D.6.10)
- Tier 3 (escalation only): full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests. Triggered by: high stakes, concealment plausible, contradictions persist, cascades suspected, repeat failure. (OG §7.3, §D.6.10)

TARGETED HIDDENS DISCOVERY SCANS (OG v2.4 §7.5 — optional diagnostic layer):
- Thirteen mechanism-specific cross-framework scans organised into four families:
  Family A (Social/organisational): Suppression, Legitimacy Theatre, Narrative Capture, Belief Persistence
  Family B (Structural/systemic): Positional Blindness, Cascade Discovery, Uncertainty Masking, Competency Blindspot
  Family C (Temporal): Drift, Amnesia
  Family D (Action-induced): Negligence, Intervention Blindspot
  Plus: Evidence Corruption (Family A)
- Invoked when Tier 1 symptoms point to a specific hiding mechanism (use Triage Matrix at OG §7.5.3).
- Each scan follows a mechanism through 3–5 frameworks and terminates with the §7.2 Micro-Protocol.
-->

## 8.1 Hiddens Source Analysis (framework-specific)
| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---:|---|---|---|
| 1 | {{BG1_NAME}} | {{BG1_PATTERN}} | {{BG1_REMEDY}} |
| 2 | {{BG2_NAME}} | {{BG2_PATTERN}} | {{BG2_REMEDY}} |
| 3 | {{BG3_NAME}} | {{BG3_PATTERN}} | {{BG3_REMEDY}} |
| 4 | {{BG4_NAME}} | {{BG4_PATTERN}} | {{BG4_REMEDY}} |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)
<!--
Guidance:
- Always run a lightweight scan across all six meta-categories of Hiddens.
- Do NOT pre-filter categories in advance; shortlist only after the scan.
-->
<!--
Execution rule (v2.3, confirmed in OG v2.4 §D.6.10):
- Run Tier 1 at least twice: (1) early (after initial framing), and (2) pre-closure (after tests/probes and table population).
- Record any changes between passes; treat new discoveries as evidence of prior hiddens.
- Key operational rule (OG §D.6.10): Tier 1 is run at least twice (early + pre-closure), in both Rapid Run Mode and Investigative Run Mode.
- When Tier 1 symptoms point to a specific hiding mechanism, invoke the appropriate Targeted Hiddens Discovery Scan (OG §7.5; use Triage Matrix at §7.5.3).
-->
| Hiddens meta-category (I–VI) | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|
| I  Perceptual | {{HID_I_WHY}} | {{HID_I_SYMPTOMS}} | {{HID_I_CHECKS}} |
| II Systemic | {{HID_II_WHY}} | {{HID_II_SYMPTOMS}} | {{HID_II_CHECKS}} |
| III Informational | {{HID_III_WHY}} | {{HID_III_SYMPTOMS}} | {{HID_III_CHECKS}} |
| IV Temporal | {{HID_IV_WHY}} | {{HID_IV_SYMPTOMS}} | {{HID_IV_CHECKS}} |
| V  Relational | {{HID_V_WHY}} | {{HID_V_SYMPTOMS}} | {{HID_V_CHECKS}} |
| VI Ontological | {{HID_VI_WHY}} | {{HID_VI_SYMPTOMS}} | {{HID_VI_CHECKS}} |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)
<!--
Guidance (updated for OG v2.4 §D.6.10):
- Standard in Investigative Run Mode; optional in Rapid Run Mode (typically top 1–3 if timeboxed).
- After Tier 1, select ~5–15 top Hidden candidates and map them here.
- For each, build a "working model" per OG §D.6.10: where it lives, how it's produced (mechanism chain),
  why it persists (incentives/power/comms/narratives), what evidence would confirm/disconfirm,
  detection interface, remediation interface.
- Integrate duplicates and cluster by mechanism to avoid list-noise.
-->
| Hidden type (ID + name) | Relevance (H/M/L) | Mechanism | Detectability | Agency | Consequence | Detection interface(s) (Type A) | Remediation interface(s) (Type B) | Interaction notes (Type C) |
|---|---|---|---|---|---|---|---|---|
| {{H1}} | {{H1_REL}} | {{H1_MECH}} | {{H1_DET}} | {{H1_AGENCY}} | {{H1_CONS}} | {{H1_DETECT}} | {{H1_REMEDIATE}} | {{H1_INTERACT}} |
| {{H2}} | {{H2_REL}} | {{H2_MECH}} | {{H2_DET}} | {{H2_AGENCY}} | {{H2_CONS}} | {{H2_DETECT}} | {{H2_REMEDIATE}} | {{H2_INTERACT}} |
| … | … | … | … | … | … | … | … | … |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)
<!-- Aligned with OG v2.4 §7.2. Steps 1–4 are the core Micro-Protocol; steps 5–7 extend for full framework execution. -->
1) Run the Tier 1 scan across all six Hiddens meta-categories (early pass; assume Hiddens exist) (OG §7.1).
2) Shortlist candidate Hiddens; for each, rate: mechanism, reducibility, detectability, agency, consequence (OG §7.2).
3) Assign at least one detection interface and one remediation interface per high-consequence Hidden; map interaction chains (OG §7.2).
4) Run the hiddens source analysis and record unresolved Unknowns/Hiddens.
5) If Tier 1 symptoms point to a specific hiding mechanism, invoke the appropriate Targeted Hiddens Discovery Scan (OG §7.5; select using Triage Matrix at §7.5.3).
6) After executing the framework protocol and any available tests/probes, re-run Tier 1 (pre-closure pass) and note deltas.
7) Produce Residual Unknowns (with mechanism + impact + next probe) and apply the Escalation Rule (§8.5) if any residual could change decisions, accountability, or remediation priorities. Produce closure artefacts per OG §7.4.

## 8.5 Escalation Rule (Tier 3 – full-spectrum Hiddens escalation)
<!-- Per OG v2.4 §7.3 and §D.6.10. Tier 3 is not default for Investigative Run Mode; triggered only by escalation conditions. -->
Escalate to full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests if any apply:
- High consequence (safety, regulatory, existential, severe harm potential)
- Adversarial context / strategic concealment likely
- Persistent disagreement or inconsistent evidence
- Repeat failures despite prior interventions
- Strong suspicion of cascades/reinforcement across hidden types
- Decision-critical residual unknowns

Tier 3 execution (per OG §D.6.10):
- Expands beyond Tier 1 categories into the full Hiddens taxonomy (full-spectrum exploration).
- Tightens controls: stronger provenance requirements, more explicit competing hypotheses, more rigorous disconfirming tests.
- When adversarial intent is plausible: adds concealment vectors and independent corroboration paths.
- May justify near-full group coverage (G1–G6) when warranted by routing decision tree branch A6 (OG §4.3).

---

# 9. Framework Application Protocol (mandatory)
<!-- Default: 5–6 steps; table-driven; each step must emit artefacts.
Operating Guide alignment (v2.4):
- Confirm Run Mode selection (Rapid Run Mode / Investigative Run Mode) and routing outputs (minimum group coverage + Full Depth / Light Depth Framework Execution plan) at Step 1 (OG §D.9.2 Mode Selection Gate + OG §4.3 Routing Decision Tree).
- Produce routing outputs per OG §4.3.2 (routing statement, minimum group coverage, Full Depth list, Light Depth list, escalation triggers).
- Ensure pre-closure Tier 1 Hiddens re-scan occurs before final recommendations (OG §5.0, §D.6.10).
- When Tier 1 symptoms point to a specific hiding mechanism, invoke Targeted Scans (OG §7.5).
- Closure artefacts must include all five items per OG §7.4 (residual unknowns, acceptability rationale, monitoring plan, ownership, learning hook).
-->

## 9.1 Application Steps Table
| Step # | Step name | Action | Outputs / artefacts |
|---:|---|---|---|
| 1 | Situation & Goal Clarification | {{STEP1_ACTION}} | {{STEP1_OUTPUTS}} |
| 2 | Meta-Category Scan | {{STEP2_ACTION}} | {{STEP2_OUTPUTS}} |
| 3 | Type Mapping | {{STEP3_ACTION}} | {{STEP3_OUTPUTS}} |
| 4 | Dimensions & Dynamics | {{STEP4_ACTION}} | {{STEP4_OUTPUTS}} |
| 5 | Interfaces + Hiddens Source Analysis | {{STEP5_ACTION}} | {{STEP5_OUTPUTS}} |
| 6 | Translate to Decisions / Interventions / Governance | {{STEP6_ACTION}} | {{STEP6_OUTPUTS}} |

## 9.2 Standard Deliverables (recommended)
- Minimum deliverable (1–2 pages): {{MIN_DELIVERABLE}}
- Full deliverable pack: {{FULL_DELIVERABLE}}
- Monitoring indicators: {{INDICATORS_AND_REVIEW_CADENCE}}


### Canonical shared registers (Operating Guide v2.4 aligned; mandatory for LLM use)
<!--
Invariant (v2.3, updated for OG v2.4 §D.4.1):
- Every framework run contributes to the shared registers defined by the Operating Guide:
  Group Coverage Matrix (G1–G6), Hiddens Register, Evidence Register (Evidence Ledger), Hypotheses & Tests Backlog,
  Information Requests, and Residual Unknowns.
- For post-failure investigations, include an Investigation Plan and a Decision Record when recommendations are made.
- Closure note must include all five items per OG §7.4.
-->
| Shared register / artefact | Required | Notes (how this framework contributes) | OG reference |
|---|---:|---|---|
| Group Coverage Matrix (G1–G6) | Yes | Record which groups were examined at Full Depth vs Light Depth; note gaps. | OG §D.4.1, Appendix A, Appendix E §E.2 |
| Hiddens Register | Yes | Populate candidate Hiddens relevant to this framework; include mechanisms, detectability, consequence, probes/tests, owners, and status. | OG §6.2, §D.4.1 |
| Evidence Register (Evidence Ledger) | Yes | Track key claims, source, quality, bias risks, dependencies, and gaps. | OG §6.2, §D.4.1 |
| Hypotheses & Tests Backlog | Yes | Convert Unknowns into discriminating tests/probes with priorities and dependencies. | OG §D.4.1, Appendix E §E.3 |
| Information Requests | Yes | Explicit list of missing inputs needed to reduce decision-critical Unknowns; includes why and expected discriminator value. | OG §D.10.2, Appendix E §E.4 |
| Residual Unknowns + Closure note | Yes | State what remains hidden and why; include: (1) residual unknowns list, (2) acceptability rationale, (3) monitoring plan, (4) ownership, (5) learning hook. Include escalation recommendation if material. | OG §7.4, §D.3.5 |
| Investigation Plan (post-failure) | Conditional | Required when failure occurred or harm potential is high. Recommended for all non-trivial runs. | OG §D.4.1, Appendix B |
| Decision Record (if recommending changes) | Conditional | Required when proposing interventions, governance, or control changes. Includes evidence basis and residual unknowns. | OG §D.4.1, Appendix C |

---

# 10. Framework Principles (mandatory)
<!-- Default: 5 principles. Keep concise and normative (intended use constraints). -->

## 10.1 Principles Table
| Principle name | Description |
|---|---|
| 1. {{PR1_NAME}} | {{PR1_DESC}} |
| 2. {{PR2_NAME}} | {{PR2_DESC}} |
| 3. {{PR3_NAME}} | {{PR3_DESC}} |
| 4. {{PR4_NAME}} | {{PR4_DESC}} |
| 5. {{PR5_NAME}} | {{PR5_DESC}} |

---

# 11. Glossary (local domain terms; recommended; mandatory for “Stable” status)
<!--
Scope rule:
- Do NOT redefine Operating Guide execution semantics here (Run Mode, Framework Execution Depth, Tier 1–3, routing, registers, Targeted Scans, etc.).
- For those terms, reference the Operating Guide v2.4 glossary sections:
  - Core definitions: OG §1.3 (§11.1 in OG glossary)
  - Group system and coverage: OG §11.2
  - Run modes and execution depth: OG §11.3 and §D.10.1
  - Protocols and loop control: OG §11.4
  - Artefacts: OG §11.5 and §D.10.2
  - Hiddens integration discipline: OG §11.6
  - Targeted Hiddens Discovery Scans: OG §11.7 (§7.5.6)
  - Quality controls: OG §11.8
  - Prompt discipline and F/I/A/U tagging: OG §11.9 and §D.10.1
- Use this section for domain- or framework-specific terms only (technical vocabulary, organisational artefacts, special definitions).
-->

## 11.1 Local domain glossary
| Term | Definition |
|---|---|
| {{TERM1}} | {{TERM1_DEF}} |
| {{TERM2}} | {{TERM2_DEF}} |
| … | … |

## 11.2 Core execution terms (pointer; do not restate)
- See **{{OG_TITLE}}**, v2.4:
  - Core execution terms (mandatory): **§D.10.1**
  - Artefact terms (mandatory): **§D.10.2**
  - Full Operating Guide glossary: **§11** (§11.1–§11.9)
  - Targeted Hiddens Discovery Scans glossary: **§7.5.6** (also §11.7)


---

# 12. Document Control (recommended; mandatory for “Stable” status)

## 12.1 Version History
| Version | Date | Changes |
|---|---|---|
| {{V1}} | {{V1_DATE}} | {{V1_CHANGES}} |
| {{V2}} | {{V2_DATE}} | {{V2_CHANGES}} |
| {{V3}} | {{V3_DATE}} | {{V3_CHANGES}} |

## 12.2 Integration Notes (optional)
{{INTEGRATION_NOTES}}

---

## Appendices (optional but recommended)
A. Consolidated 30-type table (single view)
B. Full Hiddens crosswalk (Tier 3: full-spectrum scan)
C. Worked example (micro-case) — see also OG Appendix F for illustrative example
D. Checklists / workshop prompts
E. Targeted Hiddens Discovery Scan results (if any invoked per OG §7.5)
F. Machine-readable field schemas (per OG Appendix E — controlled enumerations, group coverage, hypotheses/tests, information requests)
