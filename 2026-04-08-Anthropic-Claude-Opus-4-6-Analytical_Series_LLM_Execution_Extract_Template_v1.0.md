# Analytical Series Framework – LLM Execution Extract Template (LLMET) v1.0

## Document Information
| Field | Value |
|---|---|
| Document name | Analytical Series Framework – LLM Execution Extract Template |
| Version | v1.0 |
| Date | 2026-04-08 |
| Status | Release |
| Purpose | Template for producing LLM Execution Extracts (Tier 2 documents) for each framework in the Analytical Series |
| Companion documents | MRT v3.0 (Tier 1 full-document template); LLM-Only Operating Guide v1.0 (Tier 3 runtime doctrine) |
| Token budget (completed extract) | 5,000–8,000 tokens per extract |
| Token ceiling (this template) | <2,000 tokens |
| Primary users | LLMs executing the Analytical Series at runtime; extract authors (use MRT as input source) |
| Usage constraint | Extracts are read-only at runtime; use the full MRT document for framework maintenance or extension |

---

## How to Use This Template

**What extracts are for:** LLM Execution Extracts compress a full framework document (~25,000 tokens) into a ~6,000-token runtime-optimised version. They contain everything an LLM needs to execute a framework during a scenario analysis; nothing it doesn't need. Extracts are loaded alongside the LLM-Only Operating Guide (~16k tokens) and scenario content, allowing multiple frameworks to fit in context at once.

**When to generate extracts:** After the full Tier 1 framework document (MRT) exists and has stabilised. Extracts are derivative documents; regenerate them when the parent MRT substantially changes.

**How to populate this template:** Read the full MRT document for the framework. For each section of this template, extract and compress the relevant material from the MRT—don't copy prose verbatim. Use tables and terse lists only; no explanatory prose in completed extracts (except Section 2's single operational paragraph). Every completed extract must be self-contained: an LLM reading only the extract should be able to execute the framework without referring back to the MRT.

**Cardinal rule:** Completed extracts contain **no prose except Section 2** (single-paragraph operational definition). All other sections are **tables and terse lists only**. This discipline is critical: token budget is enforced; every sentence counts.

---

# {{FRAMEWORK_NAME}} – LLM Execution Extract

<!-- HEADER: Replace {{TOKENS}} below. Use exactly one line per section. -->

## Section 1: Operational Header

| Field | Value |
|---|---|
| Framework name | {{FRAMEWORK_NAME}} |
| Primary group | {{GROUP_PRIMARY}} ({{GROUP_PRIMARY_SHORTHAND}}) |
| Secondary group | {{GROUP_SECONDARY}} ({{GROUP_SECONDARY_SHORTHAND}}) |
| Stage | {{STAGE}} |
| OG compatibility | Analytical Series Operating Guide v2.5 |
| Extract token ceiling | 6,000–8,000 tokens |
| MRT version | {{MRT_VERSION}} |
| Extract version | v1.0 |

---

## Section 2: Operational Definition

<!-- Single paragraph only: 3–5 sentences. What the framework is. Primary analytical question. Which registers it populates. Written for LLM execution. No table here. -->

{{OPERATIONAL_DEFINITION_PARAGRAPH}}

---

## Section 3: Near-Neighbour Disambiguation Table

<!-- 2–4 nearest frameworks only. Prevents mis-routing. Format: framework name | use THIS when… | use NEIGHBOUR when… -->

| Nearest neighbour | Use {{FRAMEWORK_NAME}} when… | Use neighbour instead when… |
|---|---|---|
| {{NEIGHBOUR_1}} | {{WHEN_USE_THIS_1}} | {{WHEN_USE_NEIGHBOUR_1}} |
| {{NEIGHBOUR_2}} | {{WHEN_USE_THIS_2}} | {{WHEN_USE_NEIGHBOUR_2}} |
| {{NEIGHBOUR_3}} | {{WHEN_USE_THIS_3}} | {{WHEN_USE_NEIGHBOUR_3}} |

<!-- Optional 4th row if needed; avoid 5+ rows (context budget). -->

---

## Section 4: Condensed Core Taxonomy

<!-- Compressed version of MRT §2–3. Table form only. Preserve full structure (I–VI + types) but omit prose explanations. -->

| Meta-category | Core types (names only, no descriptions) | Diagnostic question (1 sentence) |
|---|---|---|
| I {{MC1_NAME}} | {{MC1_TYPE_1}}, {{MC1_TYPE_2}}, {{MC1_TYPE_3}}, {{MC1_TYPE_4}}, {{MC1_TYPE_5}} | {{MC1_DIAGNOSTIC_Q}} |
| II {{MC2_NAME}} | {{MC2_TYPE_1}}, {{MC2_TYPE_2}}, {{MC2_TYPE_3}}, {{MC2_TYPE_4}}, {{MC2_TYPE_5}} | {{MC2_DIAGNOSTIC_Q}} |
| III {{MC3_NAME}} | {{MC3_TYPE_1}}, {{MC3_TYPE_2}}, {{MC3_TYPE_3}}, {{MC3_TYPE_4}}, {{MC3_TYPE_5}} | {{MC3_DIAGNOSTIC_Q}} |
| IV {{MC4_NAME}} | {{MC4_TYPE_1}}, {{MC4_TYPE_2}}, {{MC4_TYPE_3}}, {{MC4_TYPE_4}}, {{MC4_TYPE_5}} | {{MC4_DIAGNOSTIC_Q}} |
| V {{MC5_NAME}} | {{MC5_TYPE_1}}, {{MC5_TYPE_2}}, {{MC5_TYPE_3}}, {{MC5_TYPE_4}}, {{MC5_TYPE_5}} | {{MC5_DIAGNOSTIC_Q}} |
| VI {{MC6_NAME}} | {{MC6_TYPE_1}}, {{MC6_TYPE_2}}, {{MC6_TYPE_3}}, {{MC6_TYPE_4}}, {{MC6_TYPE_5}} | {{MC6_DIAGNOSTIC_Q}} |

---

## Section 5: Condensed Dynamics

<!-- Compressed version of MRT §5. Table form only, no prose. ~8–12 key patterns. Format: pattern name | signature | mechanism (terse) | why it matters -->

| Dynamic pattern | Signature (what you observe) | Mechanism (why it happens) | Consequence |
|---|---|---|---|
| {{PATTERN_1_NAME}} | {{PATTERN_1_SIGNATURE}} | {{PATTERN_1_MECHANISM}} | {{PATTERN_1_CONSEQUENCE}} |
| {{PATTERN_2_NAME}} | {{PATTERN_2_SIGNATURE}} | {{PATTERN_2_MECHANISM}} | {{PATTERN_2_CONSEQUENCE}} |
| {{PATTERN_3_NAME}} | {{PATTERN_3_SIGNATURE}} | {{PATTERN_3_MECHANISM}} | {{PATTERN_3_CONSEQUENCE}} |
| {{PATTERN_4_NAME}} | {{PATTERN_4_SIGNATURE}} | {{PATTERN_4_MECHANISM}} | {{PATTERN_4_CONSEQUENCE}} |
| {{PATTERN_5_NAME}} | {{PATTERN_5_SIGNATURE}} | {{PATTERN_5_MECHANISM}} | {{PATTERN_5_CONSEQUENCE}} |
| (add 3–7 additional rows as needed) | | | |

---

## Section 6: Compact Hiddens Cross-Check Prompts

### 6a. Scan Questions by Meta-Category (I–VI)

<!-- One question per meta-category of THIS framework. Max 1 sentence each. These prompt the LLM to check for Hiddens across all six Hiddens meta-categories. -->

| Hiddens meta-category | Scan question (1 sentence max) |
|---|---|
| I (Perceptual) | {{HIDDENS_I_Q}} |
| II (Systemic) | {{HIDDENS_II_Q}} |
| III (Informational) | {{HIDDENS_III_Q}} |
| IV (Temporal) | {{HIDDENS_IV_Q}} |
| V (Relational) | {{HIDDENS_V_Q}} |
| VI (Ontological) | {{HIDDENS_VI_Q}} |

### 6b. Primary Hiding Mechanisms This Framework Detects

<!-- Terse list. 3–7 mechanism names. These are the specific kinds of visibility failures this framework is designed to surface. -->

- {{HIDING_MECHANISM_1}}
- {{HIDING_MECHANISM_2}}
- {{HIDING_MECHANISM_3}}
- {{HIDING_MECHANISM_4}}
- {{HIDING_MECHANISM_5}}

### 6c. Detection/Remediation Interface Pointers

<!-- When a Hidden of this type is detected, which other frameworks or registers to invoke. Format: hidden type / mechanism | invoke this framework | register/interface type | action -->

| When this type of Hidden emerges | Invoke this framework | Interface type | Action |
|---|---|---|---|
| {{HIDDEN_TYPE_1}} | {{FRAMEWORK_POINTER_1}} | {{INTERFACE_TYPE_1}} | {{REMEDIATION_ACTION_1}} |
| {{HIDDEN_TYPE_2}} | {{FRAMEWORK_POINTER_2}} | {{INTERFACE_TYPE_2}} | {{REMEDIATION_ACTION_2}} |
| {{HIDDEN_TYPE_3}} | {{FRAMEWORK_POINTER_3}} | {{INTERFACE_TYPE_3}} | {{REMEDIATION_ACTION_3}} |

---

## Section 7: LLM Execution Protocol

### 7a. Light Depth Execution (Scan-level)

<!-- What the LLM does at scan depth. 3–5 specific, terse actions. -->

1. {{LIGHT_ACTION_1}}
2. {{LIGHT_ACTION_2}}
3. {{LIGHT_ACTION_3}}
4. {{LIGHT_ACTION_4}}

### 7b. Full Depth Execution (Complete framework run)

<!-- What the LLM does at full depth. 5–8 specific, terse actions. -->

1. {{FULL_ACTION_1}}
2. {{FULL_ACTION_2}}
3. {{FULL_ACTION_3}}
4. {{FULL_ACTION_4}}
5. {{FULL_ACTION_5}}
6. {{FULL_ACTION_6}}

### 7c. Register Updates and Gate Question

| Register | Update type | Trigger |
|---|---|---|
| Hiddens Register | {{HIDDENS_UPDATE}} | {{HIDDENS_TRIGGER}} |
| Evidence Ledger | {{EVIDENCE_UPDATE}} | {{EVIDENCE_TRIGGER}} |
| Hypothesis/Test Backlog | {{HYPOTHESIS_UPDATE}} | {{HYPOTHESIS_TRIGGER}} |
| Information Requests | {{INFO_REQ_UPDATE}} | {{INFO_REQ_TRIGGER}} |

**Gate Question (pre-closure check):**
{{GATE_QUESTION}}

---

## Section 8: Cross-Framework Routing Pointers

### 8a. Upstream Inputs (frameworks commonly feeding into this one)

<!-- Terse list of framework names or groups. -->

- {{UPSTREAM_FRAMEWORK_1}}
- {{UPSTREAM_FRAMEWORK_2}}
- {{UPSTREAM_FRAMEWORK_3}}

### 8b. Downstream Handoffs (frameworks commonly consuming this framework's outputs)

<!-- Terse list of framework names or groups. -->

- {{DOWNSTREAM_FRAMEWORK_1}}
- {{DOWNSTREAM_FRAMEWORK_2}}
- {{DOWNSTREAM_FRAMEWORK_3}}

### 8c. Targeted Scans (OG §7.5 scans that invoke this framework)

<!-- Reference by scan name (not number). Format: scan name | component role -->

| Targeted Scan | Role of this framework |
|---|---|
| {{SCAN_NAME_1}} | {{ROLE_1}} |
| {{SCAN_NAME_2}} | {{ROLE_2}} |
| {{SCAN_NAME_3}} | {{ROLE_3}} |

---

## Template Metadata

- **Instructions for extract authors:** Use the MRT for {{FRAMEWORK_NAME}} as your source document. Compress each section of the MRT into the corresponding section of this extract; prioritise actionable content for LLM execution. Test the extract by asking: "If an LLM had only this extract and the OG, could it execute this framework correctly?" If not, expand the relevant section.

- **Completed extract verification checklist:**
  - [ ] Operational header is complete and accurate.
  - [ ] Section 2 is a single paragraph (3–5 sentences); no table.
  - [ ] Sections 3–8 contain only tables and terse lists; no prose.
  - [ ] All {{TOKENS}} are filled with concrete framework-specific content.
  - [ ] Condensed taxonomy preserves full I–VI structure and all 30 types (or justified deviation).
  - [ ] Hiddens cross-check pointers are specific (reference actual frameworks or registers).
  - [ ] Total token count (with {{TOKENS}} filled) is 5,000–8,000 tokens.

- **Token budget reminder:** Completed extracts must fit within 6,000–8,000 tokens. If you exceed this ceiling, compress further: reduce dynamic patterns to the most critical 5–8; reduce disambiguation neighbours to 2–3; trim interface pointer tables to the top 2–3 highest-consequence mechanisms.

- **Versioning:** When the parent MRT updates (vX → vX+1), regenerate the extract and increment its version (v1.0 → v1.1 for patch; v1.0 → v2.0 if framework structure changes). Record the MRT version in the Operational Header.

---

*Template document ends. This template is valid and ready for use across all 50 frameworks in the Analytical Series.*
