# Framework of Ethics
*Normative analysis of moral claims, fairness questions, and ethical assumptions embedded in complex scenarios*

## Document Information
- Series: Analytical Series of Frameworks
- Version: v1.0
- Date: 2026-04-08
- Status: Draft
- Operating Guide Compatibility: Analytical Series Operating Guide v2.5
- Prompt Discipline Ruleset: Operating Guide "Prompt Discipline Rules (Canonical)" (see OG v2.5, §D.3)
- Run Mode Terminology: Rapid Run Mode / Investigative Run Mode (see Operating Guide §D.10.1)
- Framework Execution Depth Terminology: Full Depth Framework Execution / Light Depth Framework Execution (see Operating Guide §D.10.1)
- Tiered Hiddens Scan Model: Tier 1 (six-category visibility audit) / Tier 2 (structured deepening) / Tier 3 (full-spectrum escalation) (see Operating Guide §D.6.10)
- Targeted Hiddens Discovery Scans: Thirteen mechanism-specific cross-framework scans (see Operating Guide §7.5)
- Group (Primary): G4 — Meaning (MeaningVL)
- Group (Secondary): G5 — Epistemics (EpistemicsVL)
- Default Depth Guidance: Light Depth by default; Full Depth when routed by OG §4.3 (particularly in governance, accountability, or harm scenarios)
- Owner / Maintainer: Analytical Series Rewrite Project
- Intended Use: Surfacing hidden normative claims, identifying ethical blind spots, examining fairness and justice assumptions in institutional/technical design
- Primary Audience: Investigators, analysts, governance professionals, AI/technology ethics practitioners
- Dependencies / Key Inputs: Values register, Legitimacy analysis, Responsibility mapping, evidence about decision processes and distributional outcomes
- Primary Outputs: Ethical assumptions register, hidden justice claims, fairness breakdowns, normative design critiques
- Change Log (brief): v1.0 (2026-04-08) — initial composition following MRT v3.0, aligned with G4 Meaning group and post-Values/Legitimacy/Responsibility framing

---

## At-a-Glance: Core Premise Summary
| Element | Content |
|---|---|
| Primary Question | **What normative assumptions, moral claims, and questions of fairness and justice are embedded in this scenario, and which are hidden or unacknowledged?** |
| Addresses | Normative visibility in complex scenarios; ethical assumptions embedded in technical, institutional, and policy design; questions of distributive justice, procedural fairness, rights, and duties; tensions between stated and operative ethical frameworks |
| Gap Filled | Shifts analysis from what actors *value* (Values framework) and whether authority is *accepted* (Legitimacy) to what *ought* to be valued and whether acceptance is *warranted* on moral grounds; surfaces ethical blind spots and normative choices disguised as neutral or technical |
| Complements | Values (what actors actually hold as important), Legitimacy (whether authority is socially accepted), Responsibility (how accountability is assigned), Culture and Norms (shared moral conventions), Evidence and Belief (epistemic grounds for moral claims) |
| Key Characteristics | Prescriptive rather than descriptive; focuses on normative reasoning and justification; exposes hidden ethical trade-offs; examines fairness in distribution of benefits/burdens; interrogates ethical assumptions in design choices |
| Main Contributions | Systematic taxonomy of ethical types and dimensions; methods for surfacing value-neutral framing as containing normative choice; interfaces to governance and intervention design; integration with justice and rights frameworks |

---

# Introduction

## What is Ethics?

Ethics is the systematic study of what is right, fair, and just. Unlike Values—which describes what actors actually hold as important—Ethics engages the prescriptive question: what *ought* to be valued, and on what grounds? In complex scenarios, ethics concerns three central domains: (1) What moral claims and normative assumptions are embedded in decisions, designs, and policies? (2) Which ethical considerations are invisible, suppressed, or treated as neutral? (3) How are questions of fairness, justice, rights, and duties addressed or obscured?

Ethical analysis becomes critical precisely when technological, institutional, or policy choices appear neutral or purely technical. These choices almost always carry normative weight: they distribute benefits and harms, allocate rights and duties, encode assumptions about human dignity and fair process. When these assumptions remain hidden—framed as inevitable, neutral, or merely technical—they escape ethical scrutiny and correction. The Framework of Ethics is designed to surface this hiddenness and make ethical claims explicit and contestable.

## Why does Ethics matter for Hiddens work?

Ethical blind spots are among the most consequential and persistent forms of hiddenness in complex systems. They operate through several mechanisms. First, **value-neutral framing**: technical or procedural language ("algorithm," "policy," "standard") can conceal normative choices about who benefits and who bears costs. Second, **ethical assumptions built into design**: technologies and institutions often embed assumptions about fairness, autonomy, and desert that are treated as background and never questioned. Third, **distributional invisibility**: when costs and benefits are aggregated, dispersed, or embedded in statistical categories, who actually bears harm becomes hard to see. Fourth, **procedural compliance as ethical cover**: organizations may follow formal rules while violating substantive justice. Fifth, **normalisation of harm**: repeated exposure to unjust outcomes can make them seem inevitable or acceptable.

The Framework of Ethics helps expose these hiddenness mechanisms by asking: Where are normative assumptions built in? Who decided what is fair, and on what grounds? Which ethical considerations are being treated as settled? What happens if we make the contested moral claims explicit? What alternative normative frameworks are possible? By systematically interrogating ethical assumptions, this framework helps surface the hidden architecture of fairness and justice in scenarios.

## What does this framework produce?

This framework produces several key artefacts. First, an **ethical assumptions register**: mapping where normative claims, fairness assumptions, and justice concepts are embedded in decisions, designs, and institutional structures. Second, an **ethical types taxonomy** (30 core types across six meta-categories): justice, rights, duties, care, procedural fairness, and ethical reasoning patterns. Third, **dimension profiles** characterizing ethical issues along five cross-cutting dimensions: Universality, Urgency, Power Asymmetry, Tractability, and Stakeholder Perspective. Fourth, **ethical dynamics patterns**: how ethical positions transform over time, conflicts escalate, competing claims interact, and moral progress (or regress) emerges. Fifth, **ethical interfaces**: how normative claims connect to reasoning (justification), judgment (evaluation), and action (governance and intervention design). Sixth, integration with the **Hiddens Register**: identifying which ethical considerations are suppressed, which justice claims go unheard, and what mechanisms maintain that suppression.

## How to use this framework

Invoke this framework when scenarios involve: allocations of benefit and burden (distributive questions); roles, authorities, and accountability structures (justice in procedure and assignment); design choices that embed normative assumptions (technical ethics); conflicts between stated and operative values (double standards, hypocrisy); rights, dignity, and duties; or when prior analysis has surfaced ethical tensions without resolving them. In Rapid Run Mode, apply Light Depth: map major ethical claims, identify obvious blind spots, and flag ethical Hiddens for escalation. In Investigative Run Mode, apply Full Depth: systematically populate the types taxonomy, map ethical dynamics and interfaces, conduct tiered Hiddens scans for suppressed justice claims, and build a working model of ethical persistence and contestation. Invoke Targeted Hiddens Discovery Scans when Tier 1 indicates Narrative Capture (ethical narratives masking injustice) or Suppression (justice claims being actively silenced). Integrate ethics work upstream to Legitimacy, Values, and Culture; downstream to Responsibility, Decisions, and Governance. See §1.6 for LLM execution specifications.

---

# 1. Core Premise & Position in the Analytical Series

## 1.1 Core Premise (narrative)

Ethics is normative inquiry: the systematic examination of what is right, fair, and just, and the grounds on which moral claims can be made and contested. It differs from Values in a fundamental way. Values describes what actors actually hold as important, their priorities and concerns. Ethics asks the prescriptive question: what *should* be held as important, and why? Ethics also differs from Legitimacy. Legitimacy asks whether an authority is socially accepted as valid. Ethics asks whether that acceptance is *warranted* on moral grounds—whether the social acceptance rests on sound ethical justification or on power, manipulation, or moral confusion.

In complex scenarios, normative claims are often hidden, embedded in language, design, procedure, or institutional structure. A "neutral" algorithm may distribute opportunity unequally. A "rational" cost-benefit analysis may ignore justice concerns or rights violations. A "fair procedure" may enforce unjust rules consistently. A "market-efficient" allocation may leave vulnerable populations unprotected. The ethical claims embedded in these designs—what counts as fair, who has a right to what, what kinds of harm matter—often go unacknowledged and unexamined.

The Framework of Ethics systematically surfaces these hidden normative claims. It does this through a taxonomy of ethical types (what kinds of moral reasoning, justice concepts, and rights frameworks are in play), cross-cutting dimensions (how to characterize ethical positions along common axes), dynamics (how ethical claims change, conflict, and interact over time), and interfaces (how normative reasoning connects to judgment and action). It provides methods for recognizing value-neutral framing as containing normative choice, for distinguishing procedural fairness from substantive justice, for identifying who is excluded from moral consideration, and for making ethical assumptions explicit and contestable.

Ethics produces several operational outputs. An ethical assumptions register maps where normative claims are embedded. An ethical types taxonomy helps categorize the kinds of moral reasoning and justice concepts at play. Dimension profiles characterize ethical issues and positions. Ethical dynamics patterns reveal how moral claims change, conflict, and reinforce over time. Ethical interface maps show where normative reasoning connects to decision-making and governance. Hidden justice claims emerge through the Hiddens scan, revealing suppressed voices, erased considerations, and justice frameworks that conflict are being silenced. Together, these artefacts enable investigators and decision-makers to interrogate the moral architecture of scenarios, identify where ethical considerations are being overlooked or distorted, and design interventions that address justice concerns explicitly rather than leaving them hidden.

## 1.2 Assumptions & Preconditions

### Assumptions Register
| Assumption | Type | If false, what breaks? | How to test or monitor | Mitigation / fallback |
|---|---|---|---|---|
| Normative claims can be made explicit and examined independently of power dynamics | Methodological | The framework becomes merely descriptive of who holds power, not evaluative of moral warrant; ethical analysis collapses into political analysis | Ask: can moral justifications be articulated and critiqued separately from who advocates them? Can alternative ethical frameworks be articulated? | Document dissenting moral views; track whether ethical arguments can shift positions independent of power |
| Fairness and justice concepts, while contested, are intelligible across stakeholder groups | Normative | Analysis becomes impossible if stakeholders use entirely incommensurable moral languages; no common ground for negotiation | Identify whether disagreements are about values, facts, or fundamental moral frameworks; test whether reframing reveals common ground | Accept some incommensurability; focus on mapping disagreement structures and identification of framework conflicts |
| Ethical assessment can be partially separated from identity, culture, and community | Normative / structural | The framework cannot account for communal or situated ethics; appears to privilege universalist reasoning | Can participants articulate reasons for moral positions that transcend identity? Are there cross-cutting ethical principles? | Explicitly include culture, community, and relational ethics as sub-categories; track where universalist and communitarian reasoning diverge |
| Hidden ethical claims are detectable; suppression mechanisms can be identified | Methodological | Hiddens tier 1–3 scans become merely speculative; no basis for distinguishing plausible from imagined ethical blind spots | Evaluate: are there contradictions between stated and operative principles? Do outcomes reflect unstated trade-offs? Do stakeholders report unheard concerns? | Conservative approach: require multiple detection mechanisms before claiming suppression; distinguish degrees of confidence |
| Ethical reasoning improves outcomes; surfacing moral claims enables better governance | Domain/normative | Framework produces ethical discourse without changing decisions or accountability; remains advisory/academic | Do ethical frameworks change behavior? Do decision-makers adjust when hidden assumptions are surfaced? | Document decision changes; track whether ethical frameworks are integrated into governance mechanisms; accept possibility of irreducible ethical tragedy |

### Preconditions Checklist
| Precondition | Required? | Evidence / artefact | Owner | Verification status | Workaround if unmet |
|---|---|---|---|---|---|
| Scenario framing and key decisions identified | Y | Situation map, decision log, stakeholder roster | Investigator | Confirm in early briefing | Reconstruct post-hoc from available evidence and claims |
| Values and Legitimacy frameworks executed (upstream) | N (recommended) | Values register, legitimacy types table, justice claims identified | Values/Legitimacy analysts | Check prior framework outputs | Light Depth run: map ethical claims independently; understand Values/Legitimacy as separate outputs for integration later |
| Access to decision-makers or design documentation | N (but improves depth) | Interviews, meeting notes, design specs, policy documents | Investigator / stakeholders | Confirm availability | Infer ethical assumptions from outcomes and implicit choices; accept lower confidence on intent |
| Stakeholder diversity in analysis | N (but essential for justice work) | Participant list including affected populations, dissenting voices | Investigator | Check representation | Deliberately seek underrepresented perspectives; document exclusions as ethical finding |
| Time for Investigative Run Mode vs Rapid Run Mode constraint | N (affects depth) | Run mode selection, time box | Investigator | Confirm at start | Rapid: flag high-priority ethical questions for escalation; defer full Tier 2/3 scans |

## 1.3 Definitions, Scope, and Non-Goals

**Definition of Ethics:** The systematic study of what is right, fair, and just, including the grounds on which moral claims can be justified, contested, or changed. Ethics engages normative questions (what *ought* to be) and examines hidden normative assumptions embedded in scenarios, designs, and institutions.

**In scope:**
- Distributional justice (who gets what, and on what grounds)
- Procedural fairness (are rules, decisions, and allocations made fairly)
- Rights and dignity (what entitlements and protections are owed to people)
- Duties and obligations (what is owed by whom, to whom, and why)
- Ethical assumptions embedded in technical design (algorithms, systems, policies)
- Ethical blind spots (moral considerations systematically overlooked or suppressed)
- Conflicts between stated values and operative practices (double standards, hypocrisy)
- Justice reasoning frameworks (utilitarian, rights-based, care-based, relational, capabilities-based, etc.)
- Ethical dimensions of responsibility, accountability, and intervention design
- Hidden or suppressed justice claims and silenced moral voices

**Out of scope:**
- Empirical description of what values actors hold (use Values framework)
- Analysis of whether authority is socially accepted (use Legitimacy framework)
- Mechanisms of accountability assignment (use Responsibility framework)
- Descriptive mapping of shared moral conventions (use Culture and Norms framework)
- Technical evaluation of whether procedures are followed correctly (use Processes framework)
- Meta-ethical theory (what makes something a moral claim at all)
- Religious or spiritual frameworks as primary analytic lens (map as alternative justice reasoning, but not primary framework)

**Common confusions:**
- *Ethics is not Values.* Values describes what actors hold as important (descriptive); ethics evaluates what ought to be valued (prescriptive).
- *Ethics is not Legitimacy.* Legitimacy asks whether authority is accepted; ethics asks whether acceptance is warranted on moral grounds.
- *Ethics is not Cultural relativism.* This framework does not assume all ethical systems are equally valid; it asks for justification and examines consequences.
- *Ethics is not procedure-compliance.* Following rules consistently does not ensure fairness or justice if the rules themselves are unjust.
- *Ethics is not utilitarian outcome-maximization.* This framework examines multiple justice frameworks, including rights, dignity, care, and relational ethics.

## 1.4 Position in the Series (Upstream / Middle / Downstream)

**Upstream (signals/understanding):**
- Values (what actors actually hold as important; ethics interrogates whether those values are justified)
- Legitimacy (whether authority is accepted; ethics asks whether acceptance is warranted)
- Culture and Norms (shared moral conventions; ethics evaluates those conventions)
- Evidence and Belief (empirical grounds for moral claims; ethics examines how evidence is framed and what moral conclusions are drawn)
- Perspectives (stakeholder viewpoints; ethics examines whose perspectives are heard and which are suppressed)

**Middle (this framework's role):**
- Systematic excavation of normative claims embedded in scenarios
- Identification of ethical blind spots and suppressed justice claims
- Examination of fairness in distribution, procedure, and rights
- Mapping of ethical tensions and conflicts between frameworks
- Interface between moral reasoning and governance decision-making

**Downstream (action/governance):**
- Responsibility (how to assign accountability on ethical grounds)
- Decisions (how to choose between ethically contested options)
- Governance (how to institutionalize ethical reasoning and justice considerations)
- Interventions (how to design remedies that address ethical harms)
- Learning and Adaptation (how to improve ethical reasoning over time)

**Group assignment (Primary):** G4 — Meaning (MeaningVL)

**Group assignment (Secondary):** G5 — Epistemics (EpistemicsVL) [for integration with Evidence, Beliefs, Uncertainties, and Hiddens work]

**Stage assignment:** Cross-cutting (ethics informs and is informed by all groups)

**Run mode selection:** Rapid Run Mode (Light Depth ethical scan; flag high-impact questions) vs Investigative Run Mode (Full Depth; systematic Tier 1–3 Hiddens scans, stakeholder mapping, justice framework analysis)

**Operating Guide routing:** Apply decision logic at Start-of-Run and Pre-Closure per OG §4.3. Ethics routing typically triggered when scenarios involve allocation of benefits/burdens, rights/duties conflicts, design embedded values, or prior discovery of ethical tensions.

**Non-conflation invariant:** Do not conflate Run Mode with Framework Execution Depth (OG §D.10.1)

**Iteration loop:** Initialise → Generate → Route → Execute → Test → Re-scan → Decide/Close (OG §5.0). Ethics execution often occurs in Route phase to inform downstream group selection; re-scanned pre-closure to capture new ethical Hiddens surfaced by testing.

**Framework Index:** This framework is one of 36 in the series (see OG §3.2 for full Framework-to-Group mapping)

## 1.5 Crosswalk Summary

| Cluster | Representative frameworks | What they provide | What this framework adds / asks |
|---|---|---|---|---|
| Descriptive (What is) | Values, Culture and Norms, Perspectives, Beliefs | What actors actually hold as important; shared conventions; stakeholder viewpoints; epistemic grounds | Shifts from description to prescription: what *ought* to be valued? Are stated values justified? Whose moral voice is missing? |
| Epistemic (How we know) | Evidence, Beliefs, Uncertainties, Diagnosis | What evidence supports claims; what actors believe; what remains unknown; diagnosis of problems | Questions the moral assumptions embedded in evidence interpretation; examines what counts as valid moral knowledge; surfaces uncertainty about ethical claims |
| Normative (What should be) | Legitimacy, Responsibility, Governance | Whether authority is accepted and legitimate; how accountability is assigned; governance structures | Examines whether legitimacy is *warranted* on moral grounds; questions how responsibility *should* be assigned; evaluates governance mechanisms for justice |
| Action (What to do) | Decisions, Interventions | Choice between options; design of remedies | Ensures ethical reasoning explicitly informs decisions; surfaces ethical trade-offs; requires justice considerations in intervention design |

## 1.6 LLM Integration Bridge

### 1.6.1 LLM Execution Extract pointer
- Extract file: `2026-04-08-Anthropic-Claude-Opus-4-6-Framework_of_Ethics_LLM_Extract_v1.0.md`
- Extract version: v1.0
- Load this extract (not this full document) when executing this framework in LLM context.

### 1.6.2 Near-neighbour disambiguation
| Nearest neighbour | Use Ethics when… | Use neighbour instead when… |
|---|---|---|
| Values | You need to examine what *ought* to be valued, or critique values as unjustified or harmful. Ethics evaluates normative warrant. | You are mapping what stakeholders *do* value, their actual priorities and concerns. Values is descriptive. |
| Legitimacy | You are questioning whether an authority's acceptance rests on sound moral grounds (ethical legitimacy). | You are asking only whether an authority is socially *accepted* (social/political legitimacy). Legitimacy is about acceptance, not warranted acceptance. |
| Responsibility | You are interrogating the *normative grounds* for assigning accountability—what principles justify who should be held responsible? | You are examining *how* accountability is *actually* assigned—the mechanisms and incentive structures. Responsibility is about attribution. |
| Culture and Norms | You are evaluating shared moral conventions against external ethical standards, or surfacing suppressed justice claims within communities. | You are documenting shared conventions descriptively, understanding how groups construct meaning. Culture is descriptive. |

### 1.6.3 Routing triggers
- Scenarios involve allocation of benefits/burdens (distributive justice questions)
- Decision or design choice has normative implications that appear "neutral" or "technical"
- Conflict between stated values and operative practices (double standards, hypocrisy)
- Rights, dignity, autonomy, or justice concerns explicitly raised by stakeholders
- Procedural fairness questioned or substantive justice at stake
- Prior analysis (Values, Legitimacy, Responsibility) has surfaced ethical tensions
- Vulnerable populations, marginalized communities, or excluded groups involved
- Ethical assumptions embedded in institutional or technical design need surfacing

---

# 2. Meta-Categories of Ethics

## 2.1 Meta-Categories Table
| Category | Meta-category | Core question | Primary focus | Typical artefacts/examples |
|---:|---|---|---|---|
| I | Distributional Justice | Who receives what benefits/burdens, and on what grounds? | Fair allocation of resources, opportunities, and harms across populations | Wage gaps, healthcare access, pollution exposure, educational opportunity, risk distribution |
| II | Rights and Dignity | What entitlements and protections are owed to people, and why? | Rights claims (formal and substantive), dignity protection, autonomy and self-determination | Freedom of expression, bodily integrity, due process, access to justice, cultural respect |
| III | Procedural Fairness | Are decisions made fairly, and do procedures respect those affected? | Process legitimacy, voice in decisions, access to information, opportunity to contest | Notice and comment, stakeholder inclusion, transparency, appeals and remedies |
| IV | Relational and Care Ethics | How do relationships and interdependencies shape obligations? What is owed in contexts of vulnerability and care? | Connection, responsibility arising from relationships, care for dependents, relational autonomy | Family obligations, professional care duties, community mutual aid, vulnerability responsiveness |
| V | Ethical Reasoning and Frameworks | What ethical reasoning patterns and justice frameworks are in play? | Competing moral justifications, utilitarian vs. rights-based reasoning, capabilities vs. welfare approaches | Consequentialist reasoning, deontological duties, virtue ethics, social contract theory |
| VI | Ethical Blind Spots and Suppression | What ethical considerations are hidden, suppressed, or normalized out of view? | Moral assumptions made invisible, justice claims silenced, ethical frameworks erased | Value-neutral framing hiding normative choice, distributional invisibility, procedural compliance masking injustice |

## 2.2 Meta-Category Descriptions

### I. Distributional Justice
- **Definition:** Analysis of who receives benefits (resources, opportunities, recognition, power) and who bears costs (harm, burden, risk, exclusion), and on what grounds these distributions are made and justified. Asks: Are distributions fair? Do they reflect legitimate differences in contribution or need? Or do they reproduce historical injustice or systematic advantage/disadvantage?
- **Diagnostic cues:** Disparities in outcomes across groups; concentration of benefits in some populations and harms in others; invisible costs borne by marginalized groups; justifications for inequality that rest on unexamined assumptions; gaps between claimed principles (equal opportunity) and actual distribution
- **Typical failure mode:** Aggregate framing obscures who bears what; focus on average outcomes hides whether some groups benefit while others are harmed; historical injustices treated as inevitable or irrelevant; distributions justified by merit claims without examining whether merit was fairly assessed

### II. Rights and Dignity
- **Definition:** Analysis of what entitlements, protections, and claims people have a right to, and what respect is owed to human dignity. Examines formal rights (legal protections) and substantive rights (actual ability to exercise them), and questions whether stated rights are honored in practice.
- **Diagnostic cues:** Assertions that something is a right; stakeholder claims of violation or disrespect; gaps between formal rights and actual exercise; dignity concerns (being treated as less than fully human); concerns about autonomy, bodily integrity, self-determination
- **Typical failure mode:** Rights stated but not enforced; formal equality ignoring substantive inequality; dignity treated as secondary to efficiency or cost; autonomy respected in principle but undermined in practice; rights of vulnerable populations routinely overridden

### III. Procedural Fairness
- **Definition:** Analysis of whether decisions affecting people are made through fair procedures, and whether those affected have voice, access to information, and ability to contest decisions. Asks: Is the process transparent? Are affected parties heard? Can decisions be appealed? Are rules applied consistently to all?
- **Diagnostic cues:** Lack of notice or opportunity to be heard; decisions made by affected parties with conflicts of interest; information asymmetries (some parties know more than others); no mechanism to contest or appeal; rules enforced selectively; informal power dynamics overriding formal procedures
- **Typical failure mode:** Procedural compliance used as cover for substantive injustice; fairness in process assumed to justify unfair outcomes; formal rules applied to those with least power while discretion used for the privileged; opacity in decision-making; stakeholder voice non-binding or ignored

### IV. Relational and Care Ethics
- **Definition:** Analysis of obligations arising from relationships, interdependencies, and vulnerability. Examines care duties (to dependents, community), mutual obligations (what we owe to those on whom we depend), and relational autonomy (self-determination that is embedded in and respects relationships).
- **Diagnostic cues:** Vulnerability (dependence on others for basic needs, voice, survival); care relationships (children, elderly, ill, imprisoned); interdependencies (we rely on others; they on us); relational harms (betrayal, abandonment, disconnection); justice frameworks based on mutual care rather than abstract rights
- **Typical failure mode:** Individualist framing ignoring interdependence and care; vulnerability instrumentalized or invisibilized; care work unpaid and undervalued; relational obligations dismissed as particularist or unimportant; independence/autonomy emphasized while dependence is hidden

### V. Ethical Reasoning and Frameworks
- **Definition:** Analysis of the different moral reasoning patterns and justice frameworks in use: what kinds of ethical arguments are being made, what justifies them, and where frameworks conflict. Includes consequentialist (outcomes matter), deontological (duties matter), virtue (character matters), care-based (relationships matter), capabilities (what people can do and be matters), and relational approaches.
- **Diagnostic cues:** Explicit justifications for moral claims; disagreements rooted in framework differences (not just disagreements about facts); reference to principles, duties, consequences, virtues, relationships, or capabilities; appeals to different sources of moral authority (law, tradition, reason, emotion, relationship, community)
- **Typical failure mode:** Single framework treated as obviously correct; competing frameworks not acknowledged; framework conflicts resolved by power rather than argument; certain ways of reasoning treated as rational while others are dismissed as emotional or subjective; moral reasoning driven underground into unstated assumptions

### VI. Ethical Blind Spots and Suppression
- **Definition:** Analysis of what ethical considerations are hidden, actively suppressed, or normalized out of view. Examines how ethical claims become invisible (value-neutral framing, technical language), how justice concerns are silenced (lack of voice, suppressed accounts), and how moral reasoning is erased (treated as settled, irrelevant, or irrational).
- **Diagnostic cues:** Ethical claims made explicit by some stakeholders but treated as settled or irrelevant by power holders; justice frameworks articulated by marginalized groups but not heard in decision-making; normative choices described in technical language; stakeholders report moral concerns being dismissed; historical injustices treated as background rather than live questions; ethical frameworks that conflict with organizational interests are suppressed
- **Typical failure mode:** Value-neutral framing ("it's technical") conceals normative choice; distributional harms invisible when framed at aggregate level; procedural compliance obscures substantive injustice; relational obligations treated as sentiment rather than moral claim; dissenting justice frameworks not given serious consideration; suppression normalized (stakeholders no longer voice concerns because they know they won't be heard)

---

# 3. Core Types Taxonomy

## 3.0 Canonical Rule & Deviations
- **Canonical baseline:** 6 meta-categories × 5 types = 30 core types.
- **This framework:** 30 core types (full canonical structure).
- **Mapping back to baseline:** Complete alignment with canonical structure; all six categories populated with five types each.

## 3.1 Types (Category I: Distributional Justice)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 1 | Need-Based Distribution | Allocation of resources based on what people require to meet basic needs or achieve threshold sufficiency. Assumes justice requires prioritizing urgent needs and reducing severe deprivation. | What needs are recognized? Are basic thresholds (food, shelter, healthcare, education) being met? Are needs-based claims treated as legitimate? | Needs that are not recognized; deprivation framed as personal responsibility or choice; thresholds set so high that most don't meet them; some groups' needs treated as less urgent |
| 2 | Merit-Based Distribution | Allocation of benefits based on effort, achievement, or contribution. Assumes people are entitled to returns on their effort and that rewards should reflect merit fairly assessed. | How is merit defined and measured? Is the measuring process fair? Do people have equal opportunity to develop merit? Are effort and contribution recognized? | Merit defined to favor already-advantaged groups; measurement systems biased; equal opportunity absent; contribution of some groups systematized out of view (care work, community contribution); desert claims unexamined |
| 3 | Equality-Based Distribution | Allocation that prioritizes equal shares, equal treatment, or equal opportunity, assuming people have equal moral standing and should not be systematically disadvantaged. | Are people treated as equals? Does unequal distribution require justification? Are equal opportunity claims examined? Are historical disadvantages factored in? | Formal equality masking substantive inequality; equal treatment of unequals; equal opportunity claims without addressing barriers; historical injustices treated as background; some groups treated as less equal |
| 4 | Entitlement and Rights-Based Distribution | Allocation based on what people are entitled to (by law, agreement, property, or prior claim), and protection of rights to resources or opportunities. | What claims are recognized as entitlements? Do people have formal and substantive rights to resources? Are property rights balanced against rights to survival/flourishing? | Rights asserted without examining grounds; entitlements of some groups protected while others' are not; formal rights without substantive ability to exercise them; property rights treated as absolute while rights to basic goods are conditional |
| 5 | Collective Good and Common Benefit Distribution | Allocation prioritizing benefits that serve the collective or common good, assuming justice sometimes requires distributing according to shared purpose or community welfare rather than individual entitlement. | Is common benefit defined? Who decides what counts as common good? Does allocation serve genuine collective purpose or disguised private interest? | Common good rhetoric masking private advantage; common benefit defined to benefit already-privileged groups; voices excluded from defining what serves community; majority imposing costs on minorities in the name of common good |

## 3.2 Types (Category II: Rights and Dignity)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 6 | Formal Legal Rights | Entitlements formally recognized in law: constitutional protections, statutory rights, contractual agreements, international human rights instruments. Assumes law should protect people from harm and secure basic freedoms. | What rights are formally recognized? Are they enforceable? Is there independent adjudication? Do all people have equal access to legal protection? | Rights stated in law but not enforced; unequal access to justice; informal power overriding formal rights; rights of marginalized groups denied in practice even if stated in law |
| 7 | Substantive Rights and Capabilities | Actual ability to exercise rights and achieve valued freedoms: not just freedom from interference, but ability to participate, develop capacities, pursue meaningful goals. Rights to education, health, political participation, economic opportunity. | Can people actually exercise claimed rights? Are barriers (poverty, discrimination, disability, geography) addressed? Do capabilities differ across groups? | Formal rights without substantive ability to exercise them; gaps between right and capacity (e.g., right to participate without providing information, access, support for people with disabilities); capabilities systematically lower for some groups |
| 8 | Dignity and Respect Rights | Protection from degradation, disrespect, and treatment as less than fully human. Includes autonomy (self-determination), privacy, cultural respect, freedom from arbitrary power, recognition as an equal moral agent. | Are people treated with respect? Is autonomy protected or overridden? Are cultural identities respected? Is arbitrary power constrained? Are people recognized as moral equals? | Treatment as less than human (e.g., racial caricature, infantilization); autonomy overridden without consent; privacy violated; cultural disrespect; arbitrary power over some populations; non-recognition of moral equality |
| 9 | Negative Rights (Freedom from) | Rights to be free from interference: freedom from violence, torture, arbitrary detention, forced labor, discrimination, coercion, privacy violation. Focuses on protection from harm and wrongdoing. | Are people protected from violence and coercion? Is arbitrary power constrained? Are protected categories respected (race, gender, religion, etc.)? Is freedom of choice protected? | Violence and coercion used against some populations; discrimination normalized; arbitrary power exercised over vulnerable groups; forced behavior justified as inevitable or deserved; protection unequally enforced |
| 10 | Positive Rights (Entitlements to) | Rights to provision of goods and services: food, shelter, healthcare, education, work, legal protection. Reflects view that justice requires meeting basic needs and enabling people to flourish, not just refraining from harm. | Are basic needs addressed? Is healthcare accessible? Is education provided? Is economic support available? Are entitlements equal or stratified by group? | Basic entitlements conditional on market or family provision; some populations systematically denied; entitlements framed as charity rather than right; adequacy of provision varies by group; entitlements treated as optional |

## 3.3 Types (Category III: Procedural Fairness)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 11 | Voice and Participation | Opportunity for affected people to be heard, have input, and participate in decisions affecting them. Assumes those affected should have a say in how decisions are made. | Are affected parties consulted? Is consultation meaningful or performative? Can stakeholders shape decisions or only comment? Does participation include marginalized voices? | Participation limited to already-powerful; consultation where feedback is ignored; token participation without real influence; barriers to participation for marginalized groups (language, accessibility, time, trust); decisions made before consultation |
| 12 | Transparency and Information Access | Availability of relevant information about decisions, rules, reasoning, and outcomes. Assumes people need information to participate meaningfully and to contest unfair decisions. | Is information publicly available? Is reasoning disclosed? Do people know what rules apply and why? Can they access information easily? Is information withheld? | Information kept secret; reasoning undisclosed; rules applied but not published; information asymmetries (some parties know more); technical language obscuring decisions; information selectively shared |
| 13 | Impartiality and Absence of Conflict of Interest | Decisions made by neutral parties without personal stake in outcomes, and free from bias or favoritism. Assumes those with conflicts should recuse themselves. | Do decision-makers have conflicts of interest? Are rules applied consistently across all people? Is favoritism evident? Are decisions reviewed by neutral parties? | Decision-makers with clear conflicts participate; selective enforcement (rules applied to some but not others); favoritism evident; bias in application; informal power dynamics overriding neutrality |
| 14 | Appeal and Remedy | Opportunity to contest decisions, seek review, and obtain remedy if wronged. Assumes people need recourse if they believe a decision was unfair. | Can decisions be appealed? Is there independent review? Are remedies available? Can people challenge unfair outcomes? Is remedy adequate? | No mechanism to appeal; appeals available only to wealthy or well-connected; appeal processes biased; remedies inadequate or withheld; retaliation against those who contest decisions |
| 15 | Rule of Law and Consistent Application | Rules are general, knowable, stable, and applied consistently to all. Assumes arbitrary power is constrained when rules are clear and evenly applied. | Are rules published and stable? Are they applied consistently? Is there equal access to justice? Is discretion constrained? Do the same rules apply to all? | Rules applied selectively; discretion used to favor some and disadvantage others; rules changed arbitrarily; different rules for different populations; equal rules applied to unequals, obscuring inequality |

## 3.4 Types (Category IV: Relational and Care Ethics)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 16 | Care and Attentiveness | Responsibility arising from relationships and vulnerability. Those who care for dependents (children, elderly, ill) have obligations to respond with attention and responsiveness. | What relationships involve care? Are caregivers responsive to needs? Is care provided or withheld? Do relationships involve attentive concern? Are vulnerable people's needs addressed? | Care withheld or inadequate; vulnerable people neglected; responsiveness missing; care work invisible or unpaid; institutional care depersonalized; relationships treated as instrumental rather than intrinsic |
| 17 | Interdependence and Mutual Obligation | Mutual obligations arising from interdependence: we rely on others; they rely on us. Justice requires recognizing and honoring mutual obligations, not acting as if independence is possible or desirable. | How do people depend on each other? Are mutual obligations acknowledged? Do obligations flow in both directions? Are relationships of dependence respected? | Dependence hidden or denied; obligations flow one direction (dominant group controls dependent); dependence instrumentalized; mutual obligations not recognized; independence fetishized at cost of relationship |
| 18 | Solidarity and Community | Obligations to community members arising from shared membership, common vulnerability, and mutual identity. Justice includes standing with others, supporting collective interests, and recognizing claims that arise from community. | Do people identify as community members? Are communal obligations recognized? Is solidarity expressed? Do collective interests matter in decisions? Are marginalized community members included? | Community defined to exclude some; solidarity withheld from certain groups; collective interests served only if aligned with dominant interests; marginalized communities left to fend for themselves |
| 19 | Responsiveness to Vulnerability | Particular obligation toward those who are vulnerable: unable to meet their own needs, at risk of harm, or dependent. Justice requires protecting the vulnerable and responding to their specific circumstances. | Who is vulnerable? Are they protected? Are special needs recognized and met? Is response adequate and respectful? Are vulnerable populations stigmatized or abandoned? | Vulnerability stigmatized; needs of vulnerable groups ignored; responsiveness inadequate; vulnerable people blamed for their vulnerability; vulnerability used to justify control rather than protection |
| 20 | Relational Autonomy and Self-Determination | Self-determination that is embedded in and respects relationships and interdependencies. Not independence but autonomy-in-relationship: having meaningful choice while recognizing that self is constituted through relationships. | Can people make choices about their own lives? Are choices respected even if they reflect relational values? Is autonomy compatible with interdependence? Can people pursue goals that involve others? | Autonomy demands that ignore relationships; self-determination removed; choices overridden; people forced to choose between relationship and autonomy; relational values dismissed as lack of autonomy |

## 3.5 Types (Category V: Ethical Reasoning and Frameworks)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 21 | Consequentialist Reasoning | Moral evaluation based on outcomes: an action is right if it produces good consequences and wrong if it produces bad. Focuses on results, welfare, utility, or flourishing. Different from utilitarianism (which adds the requirement that good be maximized overall). | Are consequences considered? Is outcome welfare central? Do arguments focus on what will happen, what will be produced? Are good outcomes pursued? | Consequences ignored; harms treated as acceptable if procedure is fair; outcomes matter but unequally (some people's welfare weighted more); good outcomes for some pursued at cost to others |
| 22 | Deontological Reasoning | Moral evaluation based on duties, rights, and rules: an action is right if it honors duties and respects rights, regardless of consequences. Focuses on what is owed, what is required, what violates entitlements. | Are duties emphasized? Are rights treated as inviolable? Do arguments appeal to what is required or owed? Are principles stated? | Duties recognized selectively; rights of some groups treated as less important; duties imposed on some but not others; principles stated but inconsistently applied; consequences dismissed even when extreme |
| 23 | Virtue-Based Reasoning | Moral evaluation based on character, virtues, and excellences: an action is right if it expresses good character and reflects virtues like courage, honesty, compassion, justice. Focuses on what kind of person or community we are becoming. | What character is valued? Are virtues modeled? Is excellence pursued? Is character development supported? Does action reflect good character? | Character of some groups presumed flawed; virtue denied to some populations; virtues of marginalized groups not recognized; character judgments biased; communities prevented from developing excellence |
| 24 | Care-Based Reasoning | Moral evaluation based on relationships, care, and responsiveness: an action is right if it expresses care, maintains relationships, and responds to needs and vulnerability. Focuses on interdependence and particular obligations. | Are relationships and care central? Is responsiveness emphasized? Are particular obligations recognized? Do arguments appeal to caring for vulnerable others? | Care dismissed as sentimental; relationships treated as instrumentally rather than intrinsically valuable; particular obligations not recognized; vulnerability invisible; marginalized people's care work unvalued |
| 25 | Relational and Social Contract Reasoning | Moral evaluation based on reciprocal agreements, mutual commitment, and fair terms of association: an action is right if it respects agreements and upholds fair social contracts that all could reasonably accept. Focuses on what terms are fair to all parties. | Are agreements acknowledged? Is reciprocity emphasized? Are terms of association fair? Could all reasonably accept the terms? Do all parties have voice in defining terms? | Agreements made without voices of affected parties; reciprocity flows one direction; terms unfairly weighted toward powerful; coercive "agreements" framed as contracts; social contracts exclude vulnerable groups |

## 3.6 Types (Category VI: Ethical Blind Spots and Suppression)
| # | Type | Description | Diagnostic cues | Failure / hidden-risk signature |
|---:|---|---|---|---|
| 26 | Value-Neutral Framing | Normative choices presented as technical, neutral, inevitable, or natural rather than as moral claims requiring justification. Language like "the algorithm," "the market," "efficiency," "the way things are done" conceals that choices about fairness and justice were made. | Does language purport to be neutral? Are values embedded in technical description? Are design choices presented as inevitable? Are ethical alternatives not mentioned? Is a particular framework treated as "the way it has to be"? | Technical language hiding normative choice; design presented as determined by technology rather than as choice; alternatives not mentioned; ethical dimensions not acknowledged; moral assumptions treated as facts |
| 27 | Distributional Invisibility | Benefits and harms dispersed, aggregated, or spread so that who actually gains and who bears costs becomes hard to see. Harms may be small for each individual but large in aggregate; benefits concentrated in ways that are obscured. | Are distributions disaggregated (can you see who gets what)? Are harms visible or dispersed? Are some populations systematically concentrated among those bearing costs? Are aggregate framing obscuring individual experience? | Aggregate statistics hiding disparities; costs spread to avoid visibility; small harms to many treated as acceptable; concentrated gains treated as natural; burdens of marginalized populations invisible |
| 28 | Ethical Assumptions Made Invisible | Moral claims embedded in design, procedure, or institution are treated as background, natural, or inevitable rather than as choices that can be questioned. | Are ethical assumptions visible? Can they be stated and challenged? Are underlying values made explicit? Is one framework presented as obviously correct? Are alternatives mentioned? | Ethical assumptions not articulated; single framework treated as obviously correct; alternatives not considered; assumptions treated as facts; people unaware of what is assumed; dissenting views not heard |
| 29 | Suppression and Silencing | Justice claims, ethical frameworks, or moral voices actively suppressed, excluded from consideration, or rendered inaudible. May include not giving voice to affected parties, dismissing certain ways of moral reasoning as invalid, or punishing those who raise ethical concerns. | Are some voices excluded? Are certain ways of moral reasoning treated as illegitimate? Are those who raise ethical concerns retaliated against? Do some ethical frameworks dominate while others are suppressed? | Affected parties without voice; some moral frameworks treated as irrational or invalid; dissenting voices punished; ethical concerns dismissed; suppression normalized (people stop raising concerns because they know they won't be heard) |
| 30 | Ethical Corruption and Normalization of Harm | Unjust practices normalized through repetition or acceptance: what is harmful becomes routine, expected, accepted as "the way things are." May involve gradual expansion of harmful practices, reframing of harm as acceptable, or lost memory of when things were different. | Are harmful practices normalized? Are people accepting what was previously contested? Has concern faded over time? Is harm reframed as necessary or inevitable? Are people habituated to injustice? | Gradual acceptance of harm; moral outrage fading; harm reframed as natural or necessary; justifications developed for what was previously resisted; institutional memory of injustice lost; habituation to unjust systems |

## 3.7 Extending the Taxonomy

| Aspect | Guidance on extension |
|---|---|
| Canonical baseline | The 30-type structure (6 meta-categories × 5 types) is canonical and should be preserved unless deviating is essential. Extensions should add depth within categories rather than creating new categories. |
| Domain-specific refinement | Specific sectors (healthcare, technology, government, finance) may develop specialized sub-types within meta-categories. Document these as sub-types (e.g., "Healthcare equity" under "Need-Based Distribution"). |
| Preserving mappability | When creating domain-specific variants, maintain traceable mapping back to the core 30 types. Prevent proliferation of variants; consolidate where possible. |
| Structural invariants | Do not create new meta-categories without explicit deviation statement and major version upgrade (v→vX.0). Extensions within categories preserve comparability across frameworks. |
| Periodic reassessment | Review taxonomy annually or when major new ethical frameworks (e.g., framework justice, disability justice) emerge. Update via new minor version (vX.Y) if types require clarification without structural change. |
| Versioning & governance | Taxonomy extensions documented in version history. Changes to core 30 types require stakeholder review and explicit justification in Document Control. Framework owner maintains canonical list. |

---

# 4. Cross-Cutting Dimensions of Any Ethics Issue

## 4.1 Dimensions Table

| Dimension name | Description | Indicative values / range | How to assess quickly | Analytic use |
|---|---|---|---|---|
| 1. Universality | Extent to which an ethical claim is treated as universal (applying to all) vs. particular (specific to certain groups or contexts). Tension between universalist justice (same standards for all) and contextual/relational ethics (different obligations in different relationships). | Universal — Contextual | Does the claim apply to everyone or only to certain groups? Is the same standard applied to all? Are exceptions justified by particular relationships or circumstances? | Identify whether ethics are treated as universal principles or context-dependent; examine how universality claims are used to mask particularity and vice versa |
| 2. Urgency | How pressing or acute is the ethical claim? Ranges from crisis-level (immediate serious harm, rights violation) to chronic/systemic (persistent but less visible injustice). Related to consequences (how severe) and reversibility (can harm be fixed later). | Crisis / Acute — Chronic / Systemic | Are harms acute or have they persisted? Is harm reversible if delayed? Are people at immediate risk? Can the issue wait or is action needed now? | Prioritize ethical work; identify which injustices are treated as urgent and which are deferred; examine whether urgency is fairly assigned across groups |
| 3. Power Asymmetry | Extent of power differential between parties in an ethical relationship. Ranges from equal power (peers) to severe asymmetry (vulnerable populations under control of powerful actors). Power asymmetries complicate fairness and consent. | Equal / Symmetric — Asymmetric / Severe | Are parties equal in power to shape decisions? Can vulnerable people resist? Are decisions made by parties with power over others? Is coercion involved? | Examine whether power asymmetries are addressed in fairness mechanisms; identify where weak parties' voices are overridden; assess whether procedures account for vulnerability |
| 4. Tractability | How solvable is the ethical problem? Can the injustice be fixed, prevented, or mitigated through available means? Ranges from straightforward (clear cause, available remedy) to intractable (deeply systemic, no obvious remedy). | Tractable / Solvable — Intractable / Tragic | Is there a clear cause of injustice? Are remedies available? Can the problem be addressed with available resources? Is the issue deeply systemic and embedded? | Identify which injustices are treated as solvable and which are dismissed as inevitable; examine whether intractable problems are pursued or abandoned |
| 5. Stakeholder Perspective | Whose ethical framework is being used to assess the issue? Ranges from marginalized/affected voices (those who experience injustice) to powerful/distant perspectives (those who define injustice from a distance). | Marginalized / Affected — Powerful / Distant | Whose perspective is informing ethical analysis? Are affected people included? Are diverse stakeholders heard? Is ethical reasoning coming from those experiencing the injustice? | Map which stakeholders' ethical views are heard and which are suppressed; examine whether ethics are defined by those experiencing harm or by distant powerful actors |

---

# 5. Dynamics (Patterns Over Time)

## 5.1 Dynamic Patterns Table

| # | Dynamic pattern | Signature | Mechanism | Why it matters | Typical mitigations |
|---:|---|---|---|---|---|
| 1 | Ethical Escalation | Ethical concern grows in visibility and consequence; moral claims once treated as settled or minor become pressing. | Stakeholder persistence; accumulation of evidence of harm; moral awakening; reframing of issue; social movements | Ethical issues that were invisible or dismissed can become decision-critical; signals moral progress or breakdown | Amplifying affected voices; creating mechanisms for moral concerns to be heard; building legitimacy of ethical claims |
| 2 | Ethical Retreat and Normalization | Harm becomes normalized; moral outrage fades; what was contested becomes accepted as "the way things are." | Habituation to injustice; loss of memory of alternative; institutional capture; suppression of dissent; reframing of harm as necessary | Dangerous: unjust systems become invisible once people accept them; moral sensitivity dulls; ethical vigilance erodes | Maintain historical memory; protect dissident voices; interrupt routinization of harm; support moral communities that resist normalization |
| 3 | Framework Conflict and Incompatibility | Different ethical frameworks (utilitarian vs. rights-based, individual vs. communal) generate incompatible conclusions. Conflicts may be irreducible. | Stakeholders operate from different meta-frameworks; consequences vs. duties; efficiency vs. dignity; individual rights vs. common good | Conflicts may hide genuine moral disagreement; resolution by power rather than argument; irresolvable conflicts need to be faced rather than denied | Map framework conflicts explicitly; ensure all frameworks have voice; accept tragic choices; develop hybrid approaches; acknowledge reasonable disagreement |
| 4 | Power Capture of Ethical Reasoning | Actors with power redefine ethical terms to serve their interests, or selectively invoke ethical frameworks when convenient. | Dominant groups control language and framing; ethical terminology (fairness, responsibility, freedom) redefined to protect interests; double standards in application | Ethical reasoning becomes tool of oppression; justice language used to justify injustice; manipulation of moral sentiment | Independent voice in ethical reasoning; cross-checking with marginalized stakeholders; tracking how ethical language is used; exposing selectivity and double standards |
| 5 | Ethical Trade-off Transformation | Ethical tensions that initially seemed simple (rights vs. efficiency) become more complex; stakeholders discover hidden dimensions; trade-offs shift over time. | Learning about consequences; changed values; stakeholder perspectives shifting understanding; integration of new information | Initial framings prove incomplete; new options emerge; what seemed zero-sum becomes more complex | Temporal openness in ethical analysis; revisiting trade-offs as understanding deepens; integration of new evidence; willingness to revise positions |
| 6 | Responsibility Diffusion and Drift | Accountability for ethical failure drifts: no one is held responsible because responsibility is distributed. Passive structures replace active wrongdoing. | Collective decision-making without individual responsibility; passive systems (structural injustice); diffused decision chains; institutional buffer between action and consequence | Ethical accountability vanishes; injustice persists without anyone being responsible; structural injustice feels impersonal | Clear chains of accountability; assignment of responsibility for addressing injustice; refusal of passive diffusion; creating mechanisms that make responsibility stick |
| 7 | Hidden Justice Cascade | One justice concern surfaces; upon investigation, deeper structures of injustice are revealed; what seemed like isolated wrong is symptom of systemic problem. | Systemic injustice; multiple overlapping harms; interdependencies among injustices; suppression of whole landscapes of wrong | Small concerns reflect major problems; fixing surface issue without addressing root injustice; missing opportunities for systemic correction | Investigate cascades; look beyond individual cases; examine systemic patterns; address root injustices rather than symptoms; connect related concerns |
| 8 | Ethical Rehabilitation and Learning | Over time, communities, institutions, or individuals develop moral capacities: ethical sensitivity increases, justice frameworks deepen, moral imagination expands. | Deliberative engagement with ethical issues; exposure to perspectives of those harmed; moral education; institutional learning; moral communities | Possibility of doing better; ethical development not fixed; moral progress possible through commitment and learning | Support moral growth; create deliberative spaces; protect dissident voices; build institutions that learn from failures; maintain moral commitment even through failures |
| 9 | Ethical Regression and Corruption | Moral capacities erode: ethical sensitivity decreases, justice frameworks narrow, moral imagination shrinks. Regression to simpler, crueler justice frames. | Habituation to harm; suppression of dissent; lost memory; institutional corruption; moral panic; dehumanization of outsiders | Moral capacities not guaranteed; ethical regression can occur; history is not progressive; requires active commitment to maintain | Vigilance against dehumanization; protection of moral communities; maintenance of moral memory; refusal to accept narrowing of justice; solidarity with vulnerable |
| 10 | Competing Justice Frameworks Emergence | What seemed like one justice problem contains multiple justice frameworks: different stakeholders operate from incommensurable ethical premises. | Multicultural contexts; religious and secular frameworks; individual and communal justice; temporal differences (immediate justice vs. long-term reconciliation) | Conflicts may be deeper than disagreement about facts; resolution requires bridging frameworks or accepting pluralism | Explicit mapping of frameworks; respectful engagement across difference; willingness to accept some irresolvable tensions; hybrid approaches where possible |
| 11 | Moral Momentum and Moral Exhaustion | Moral energy focused on injustice can build momentum (attention, resources, solidarity) or exhaust stakeholders (fatigue, burnout, withdrawal). | Sustained moral commitment; activation of moral communities; accumulation of evidence; public attention and resources vs. depletion of activist energy; competing demands | Moral change requires sustained energy; can be created or dissipated; institutional structures affect whether momentum is possible | Distribute burden of moral work; create sustainable moral institutions; support moral communities; protect activists from burnout; maintain long-term commitment despite setbacks |
| 12 | Ethical Accountability Paradox | Those most responsible for ethical harm often have least exposure to its consequences. Accountability structures that work at individual level fail at collective level. | Diffusion of power and decision-making; distance between decision-makers and those harmed; information asymmetries; power to avoid exposure | Injustice can persist without felt responsibility; moral sensitivity of decision-makers remains low; accountability becomes separated from consequence | Create mechanisms that expose decision-makers to consequences; demand transparency and voice; reduce distance between decision and harm; hold institutions accountable |

## 5.2 Dynamics Detail (selected high-impact patterns)

### Pattern 1: Ethical Escalation
**Mechanism:** Moral claims that initially are dismissed or treated as settled ("that's just how business works," "we can't help it") gradually gain traction, visibility, and consequence through stakeholder persistence, accumulation of evidence, and moral reframing. Example: child labor laws moved from viewed as impossible to economically necessary to accepted norm.

**Implication:** Some ethical concerns become visible and consequential over time; others remain suppressed. Understanding what enables escalation helps identify both successful justice movements and persistent injustices that remain invisible.

**Testing:** Are there ethical concerns that have gained prominence recently? Which justice claims remain suppressed despite evidence? What enables some voices to be heard and others to remain silent?

### Pattern 7: Hidden Justice Cascade
**Mechanism:** Investigation of one justice concern (e.g., wage theft in low-wage industry) reveals deeper structural injustices (e.g., systematic exploitation of undocumented workers, gender discrimination, health and safety violations). What seemed like isolated wrong is symptom of larger systemic pattern.

**Implication:** Addressing surface-level injustice without understanding systemic roots leaves core problems unaddressed. Missing cascade means missing opportunity for systemic correction.

**Testing:** When a justice concern surfaces, ask: what other injustices share root causes? Who else is affected? What systemic patterns does this instance reflect? Are similar concerns being raised in adjacent domains?

---

# 6. Interface Types

## 6.1 Interface Types Table

| Type | Name | Description | Key questions | Typical examples |
|---|---|---|---|---|
| A | Detection / Diagnosis Interface | How are ethical concerns identified and brought into view? Where do ethical claims originate? How do justice issues become visible? | Who names the ethical problem? How is it articulated? What enables ethical concerns to be heard? What silences them? | Stakeholder complaints, activist organizations, investigative journalism, research, legal challenges, moral communities raising concerns |
| B | Judgment / Evaluation Interface | How are ethical claims evaluated and assessed? What frameworks are used to judge what is fair, just, right? How are trade-offs navigated? | What counts as evidence of injustice? What makes a claim legitimate? How are competing frameworks weighed? Who decides? | Adjudication processes, ethics review boards, deliberative forums, moral reasoning in decision-making, stakeholder dialogue |
| C | Action / Remediation Interface | How do ethical insights translate into governance changes, intervention design, accountability mechanisms? How are normative conclusions operationalized? | How are ethical conclusions translated to decisions? Who implements remedies? Are affected parties involved? Is remedy adequate? | Policy change, institutional redesign, accountability mechanisms, remediation programs, stakeholder oversight, monitoring of compliance |

---

# 7. Relationship to Other Frameworks (Integration)

## 7.1 Primary Integration Links

**Inputs expected:**
- From Values: stakeholder value profiles, priority registers, areas of tension between stated and operative values
- From Legitimacy: authority structures, social acceptance bases, areas where acceptance is questioned
- From Culture and Norms: shared moral conventions, practices, community frameworks
- From Evidence and Beliefs: empirical findings about distributions, claims of justice/injustice, epistemic grounds for moral assertions
- From Perspectives: stakeholder viewpoints, minoritized voices, dissenting moral frameworks
- From Hiddens: prior discovery of suppressed information, invisible structures, places where visibility fails

**Outputs provided:**
- Ethical assumptions register: normative claims embedded in scenario
- Ethical types mapping: taxonomy of moral reasoning in use
- Hidden justice claims: ethical concerns suppressed or silenced
- Ethical interfaces: connections to governance and accountability
- Ethical dynamics: how moral frameworks change and interact over time
- Recommendations for addressing ethical blind spots

## 7.2 Crosswalk Table

| Other framework | What it provides to Ethics | What Ethics provides back | Typical joint use case |
|---|---|---|---|---|
| Values | Stakeholder priorities, what actors hold as important | Normative evaluation: are stated values justified, mutually compatible, fairly distributed? | Examining whether values are good values; whether everyone's values are respected; fairness in value allocation |
| Legitimacy | Authority structures, social acceptance basis | Evaluation of whether acceptance is warranted on moral grounds; justice grounds for legitimacy | Assessing not just if authority is accepted but if acceptance is justified; ethical basis for governance |
| Responsibility | Who is held accountable, assignment of responsibility | How responsibility *should* be assigned on normative grounds; what makes assignment fair | Moving from how accountability is assigned to how it *ought* to be assigned; integrating justice into accountability |
| Culture and Norms | Shared conventions, community moral frameworks | Critical evaluation: are conventions just, inclusive, adaptive? What justice frameworks are suppressed? | Examining whether community norms are fair; whether norms exclude justice concerns; integrating diverse moral frameworks |
| Evidence | Empirical claims, data, research findings | Normative interpretation of evidence: what counts as justice concern, what evidence is relevant to ethical claims | Translating empirical findings (disparity in outcomes) into ethical claims (injustice); examining what counts as evidence of unfairness |
| Perspectives | Stakeholder viewpoints, diverse voices, minoritized positions | Examination of whether all perspectives are heard; which frameworks are silenced; how to integrate marginalized ethical voices | Ensuring affected populations' moral views are central to analysis; surfacing suppressed ethical perspectives |
| Hiddens | Hidden information, invisible structures, visibility failures | Identification of hidden ethical concerns, suppressed justice claims, ethical assumptions made invisible | Complementary hiddenness work: ethical hiddens (justice concerns suppressed) layer onto other hiddenness mechanisms |

## 7.3 Integration Questions by Framework

| Framework | Group | Stage | Integration questions | Outputs / artefacts to pull in | Notes |
|---|---|---|---|---|---|
| Situations Context Classification | G1 | Upstream | What normative framings are embedded in how the situation is defined? Who decided what counts as the problem? Are there alternative ethical framings? | Situation definitions; alternative framings; stakeholder disagreements about what the problem is | Ethical analysis should inform situation framing; surface normative choices disguised as neutral categorization |
| Boundaries | G1 | Upstream | What are the boundaries of ethical concern? Who is included in moral consideration? Are boundaries fair or do they exclude vulnerable populations? | Boundary definitions; included/excluded populations; justifications for boundaries | Examine whether boundaries are drawn fairly; whether excluded populations have voice; whether boundaries should be redrawn |
| Dimensions | G1 | Upstream | How do dimensional frameworks embed ethical assumptions about what matters? Are all dimensions morally relevant? | Dimensional characterizations; what is treated as important; what is invisible | Ethical analysis should inform what gets measured; surface ethical choices in dimensional selection |
| Realities | G1 | Upstream | What ethical realities (frameworks, justice concerns, moral claims) exist in the scenario? Which are recognized and which suppressed? | Stakeholder reality framings; ethical frameworks in play; suppressed realities | Ensure ethical realities are mapped alongside other reality frameworks; surface ethical ontologies |
| Scale | G1 | Upstream | What ethical implications follow from different scales? Are harms at some scales treated as mattering less? Is scale used to hide injustice? | Scale framings; impacts at different scales; distributional patterns at different scales | Ethical analysis should examine whether scale choices hide or reveal injustice; whether small individual harms aggregating are treated as mattering |
| Time | G1 | Upstream | How do ethical obligations change with time? Are justice concerns treated differently in short vs. long term? Are historical injustices treated as irrelevant? | Temporal framings; what obligations are past, present, future focused; how history is treated | Examine whether temporal framing hides or reveals injustice; whether past injustices are addressed or forgotten; whether future generations are considered |
| Systems | G2 | Middle | What ethical implications follow from systemic structure? How does system design embed ethical assumptions? Are harms distributed via system structure? | System diagrams; how structure shapes outcomes; distributional patterns within system; system assumptions | Examine system for embedded ethical assumptions; identify whether system structure perpetuates injustice; assess whether alternative designs could be more fair |
| Relations | G2 | Middle | What ethical obligations arise from relationships and interdependencies? Are relational harms addressed? Do procedures respect relationships? | Relationship maps; dependencies; ethical obligations arising from relationships; relational harms | Ethical analysis should integrate relational ethics; examine whether procedural justice respects relationships; surface care obligations |
| Processes | G2 | Middle | How do processes embed ethical assumptions? Are procedural rules fair? Do processes respect those affected? Are consequences distributed fairly? | Process descriptions; rules; who participates; who is affected; outcomes | Examine processes for procedural fairness; assess whether affected parties have voice; evaluate whether outcomes are fair |
| Causation | G2 | Middle | What are the ethical implications of different causal framings? Are causal stories used to blame victims? Do they hide systemic causation? | Causal models; who is blamed; what is treated as cause vs. effect; alternative causal framings | Examine whether causal analysis hides injustice; whether blame is fairly assigned; whether systemic causes are acknowledged |
| Resources | G2 | Middle | How are resources distributed? Are distributions fair? Are needs-based claims recognized? Who has voice in resource decisions? | Resource inventories; distribution patterns; allocation decisions; stakeholder disagreements | Examine fairness of resource distribution; assess whether allocation procedures are fair; identify who benefits and who bears costs |
| Agents | G3 | Middle | How are different agents morally evaluated? Are judgments fair? Do all agents have standing? Are marginalized agents' perspectives heard? | Agent descriptions; stakeholder lists; how agents are characterized; whose perspective is centered | Examine whether ethical analysis includes all morally relevant agents; whether marginalized agents are included; whether characterizations are fair |
| Personas | G3 | Middle | Whose perspectives are represented in persona development? Are marginalized populations included? How do personas embed ethical assumptions? | Personas; whose stories are told; who is centered; what assumptions are embedded | Examine whether ethics analysis includes affected populations' personas; whether marginalized voices are represented; whether ethical concerns are surfaced |
| Incentives | G3 | Middle | What ethical implications follow from incentive structures? Do incentives align with fairness goals? Do they perversely incentivize injustice? | Incentive structures; what they reward and punish; distributional effects; whether aligned with fairness goals | Examine incentives for ethical implications; assess whether they drive injustice; consider alternative incentive designs |
| Power | G3 | Middle | How is power distributed? Does power asymmetry affect fairness? Are vulnerable populations' voices overridden? How can power imbalances be addressed? | Power maps; asymmetries; voice in decisions; whose interests prevail; power-based injustices | Ethical analysis must examine power; assess whether fairness mechanisms account for power asymmetry; identify how power enables injustice |
| Responsibility | G3 | Middle | How is accountability assigned? Is assignment fair? Do the responsible face consequences? Are marginalized populations blamed unfairly? | Responsibility assignments; who is held accountable; who escapes; accountability gaps | Examine whether responsibility assignments are fair; whether accountability avoids power asymmetry; whether systemic accountability is addressed |
| Competencies | G3 | Middle | What competencies are required for ethical reasoning? Who has access to ethical deliberation? Are some voices excluded from ethical judgment? | Competency profiles; who is treated as qualified to speak on ethics; barriers to participation | Examine whether ethical deliberation is inclusive; whether competency claims are used to exclude voices; whether moral reasoning is accessible |
| Culture and Norms | G4 | Middle | What shared moral conventions are in place? Are they fair and inclusive? What justice frameworks are embedded in culture? | Cultural norms; moral conventions; shared values; what is treated as normal; whose culture is centered | Examine whether cultural norms are fair; whether marginalized moral frameworks are represented; whether culture enables or disables justice |
| Perspectives | G4 | Middle | Whose perspectives are included in analysis? Are marginalized and dissenting voices heard? Which ethical frameworks are silenced? | Stakeholder perspectives; whose viewpoints are centered; dissenting views; marginalized voices | Ensure ethical analysis includes affected populations' moral viewpoints; surface suppressed ethical frameworks; give voice to ethical dissenters |
| Narratives | G4 | Middle | What ethical narratives are in circulation? Do narratives center justice or obscure it? Are alternative justice narratives possible? | Narrative framings; what stories are told; whose stories are suppressed; narrative gaps | Examine narratives for justice implications; identify justice narratives that are suppressed; surface alternative moral framings |
| Communications | G4 | Middle | How are ethical claims communicated? Are justice voices given platform? Is ethical reasoning accessible? Are ethical messages distorted? | Communication patterns; whose voices are amplified; barriers to ethical communication; message distortion | Examine whether ethical discourse is possible; whether marginalized voices can be heard; whether ethical reasoning is distorted in communication |
| Legitimacy | G4 | Middle | Is authority's acceptance justified on moral grounds? Are legitimacy claims fair? Are marginalized populations' moral objections heard? | Legitimacy bases; who accepts authority; on what grounds; moral objections; contested legitimacy | Ethics should evaluate whether legitimacy is warranted; whether acceptance rests on sound ethical grounds; whether dissent is respectfully addressed |
| Values | G4 | Middle | What values are prioritized? Are all stakeholders' values respected? Are value distributions fair? | Value registers; stakeholder values; tensions; priorities; whose values matter | Examine fairness of value respect; whether value pluralism is honored; whether marginalized values are included |
| Beliefs | G5 | Cross-cutting | What moral beliefs underlie ethical positions? Are beliefs justified? Whose beliefs are treated as valid? | Stakeholder beliefs about justice, fairness, rights; what grounds beliefs; contested beliefs | Examine whether moral beliefs are justified; whether all stakeholders' moral beliefs are heard; whether some are suppressed |
| Evidence | G5 | Cross-cutting | What counts as evidence of injustice? How is evidence interpreted ethically? Are some justice concerns treated as unsupported? | Evidence registers; what is treated as proof of unfairness; gaps in evidence; disagreements about what counts | Examine what counts as evidence of injustice; whether evidence is fairly interpreted; whether justice claims are dismissed without evidence |
| Uncertainties | G5 | Cross-cutting | What ethical uncertainties persist? How are decisions made despite moral uncertainty? Are affected parties' moral concerns treated as unknowns? | Uncertainty registers; what is not known; moral disagreements; contested claims; areas of doubt | Examine how moral uncertainty is handled; whether affected parties' concerns are dismissed as uncertain; whether humility about ethics is possible |
| Failures | G5 | Cross-cutting | What ethical failures have occurred? How are they analyzed and learned from? Are responsibility frameworks applied ethically? | Failure analyses; what went wrong; who was harmed; how responsibility is assigned; learning | Examine failures for ethical dimensions; assess whether responsibility assignments are fair; ensure learning integrates ethics |
| Hiddens | G5 | Cross-cutting | What ethical concerns are hidden? What justice claims are suppressed? What moral frameworks are invisible? | Hiddens registers; what is not visible; suppression mechanisms; ethical blind spots; silenced voices | Complementary work: identify ethical hiddens (justice concerns, moral frameworks suppressed) as layer of broader hiddenness work |
| Diagnosis | G5 | Cross-cutting | How are ethical problems diagnosed? Are diagnoses fair to all stakeholders? Do marginalized groups have voice in problem definition? | Diagnostic framings; what is treated as the problem; alternative diagnoses; whose perspective shapes diagnosis | Ensure ethical analysis informs diagnosis; examine whether diagnoses are fair; whether marginalized groups' moral concerns shape problem definition |
| Metrics | G5 | Cross-cutting | What do metrics measure? Do they measure justice or obscure it? Are metric choices ethically justified? | Metrics used; what is measured and not measured; distributional patterns in metrics; fairness of metric choice | Examine whether metrics support justice assessment; whether they hide or reveal injustice; whether metric choices embed ethical assumptions |
| Knowledge | G5 | Cross-cutting | What counts as knowledge about justice? Whose knowledge is respected? Are marginalized groups' moral knowledge heard? | Epistemic claims; what is treated as known; knowledge gaps; whose knowledge is recognized; epistemologies in conflict | Examine whether ethical knowledge is inclusive; whether marginalized groups' moral knowledge is valued; whether multiple epistemologies are integrated |
| Decisions | G6 | Downstream | How do ethical considerations enter decision-making? Are justice concerns addressed? Are marginalized voices heard? | Decision frameworks; what factors are considered; how tradeoffs are made; whose perspectives matter; decision gaps | Ensure ethical analysis informs decisions; assess whether ethics are integrated; whether marginalized perspectives shape choices |
| Interventions | G6 | Downstream | How are interventions designed to address ethical concerns? Are remedies fair to all stakeholders? Do affected parties have voice in remedy design? | Intervention designs; what is changed; distributional effects; stakeholder participation; remedy adequacy | Examine interventions for ethical implications; assess whether remedies address justice; whether affected populations are involved in design |
| Governance | G6 | Downstream | How are ethical considerations institutionalized in governance? Is governance fair? Are marginalized populations heard? | Governance structures; decision-making mechanisms; accountability; voice; fairness of process | Examine governance for ethical integration; assess whether procedural fairness is built in; whether marginalized groups have meaningful voice |
| Risk | G6 | Downstream | What ethical risks arise in scenarios? Are justice concerns treated as risks? Who bears risk unfairly? | Risk registers; what is at risk; who is vulnerable; distribution of risk exposure; fairness of risk allocation | Examine risks for ethical dimensions; assess whether justice concerns are recognized as risks; whether risk distribution is fair |
| Learning and Adaptation | G6 | Downstream | How do systems learn from ethical failures? Are justice frameworks improved over time? Are marginalized groups' moral knowledge incorporated? | Learning mechanisms; what is learned; feedback loops; whether ethics improves; stakeholder participation in learning | Examine whether ethical learning occurs; whether marginalized perspectives improve moral reasoning; whether systems adapt toward greater justice |

---

# 8. Hiddens Source Analysis & Cross-Check (mandatory)

## 8.1 Hiddens Source Analysis (framework-specific)

| # | Generator name | Pattern (how analysis fails) | Remedy (how to correct) |
|---:|---|---|---|
| 1 | Value-Neutral Framing Blindness | Technical or procedural language ("the algorithm," "market efficiency," "standard practice") hides that normative choices were made. Analyst accepts technical framing without interrogating embedded values. | Make technical choices explicit: who designed them? What alternatives existed? What values guided the design? What would alternative designs look like? |
| 2 | Stakeholder Exclusion | Ethical analysis proceeds without including affected populations' moral frameworks. Conclusions reflect powerful actors' ethics, not those who experience injustice. | Systematically include affected populations in ethical deliberation. Give voice to marginalized moral frameworks. Examine whose perspective is centered. |
| 3 | Single-Framework Dominance | One ethical framework (e.g., utilitarian efficiency) treated as obviously correct; competing frameworks (rights, dignity, care, community) not considered. Analyst unaware that frameworks exist or possible. | Identify competing frameworks explicitly. Map where they conflict. Give each framework voice. Accept that some tensions may be irreducible. |
| 4 | Distributional Invisibility | Aggregate statistics hide who specifically gains and who bears costs. Analyst misses concentration of benefits or dispersion of harms across populations. | Disaggregate outcomes. Track distributions by demographic group. Make visible who is concentrated among winners and losers. |
| 5 | Blame Attribution Bias | Historical injustices or systemic harms attributed to individual failures ("laziness," "bad choices") rather than structural causes. Analyst uncritically accepts blame narratives. | Examine causal framings. Question blame attribution. Identify systemic and historical roots. Consider whose interests blame narratives serve. |

## 8.2 Hiddens Six-Category Scan (Tier 1 – invariant)

| Hiddens meta-category | Why it may be active here | Typical symptoms | Default checks to run |
|---|---|---|---|---|
| I  Perceptual | Ethical concerns are cognitively difficult to see; justice frameworks unfamiliar; moral language opaque to decision-makers | Decision-makers unaware injustice exists; framing prevents recognition of harm; ethical frameworks not on decision-makers' "radar" | Ask: Is the ethical concern visible to decision-makers? Can it be articulated in their language? What would make it recognizable? |
| II Systemic | Ethical blindness embedded in institutional structure; procedures that seem fair perpetuate injustice; rules applied consistently to unequals | Procedures followed but outcomes unjust; systemic patterns producing injustice; no individual wrongdoing but collective harm | Examine system structure for embedded fairness assumptions. Do fair procedures produce unjust outcomes? Is systemic justice possible? |
| III Informational | Justice concerns invisible due to lack of information; affected populations lack voice to raise ethical claims; information asymmetries hide distributions | Affected parties unaware of harm; decision-makers unaware of impact; suppression of information about disparities; silence from affected populations | Examine information flows. Are affected parties aware? Can they raise concerns? Is information about distributions available? Who has what information? |
| IV Temporal | Historical injustices treated as settled or irrelevant; justice concerns seen as temporary rather than persistent; long-term harm invisible in short-term framing | Ethical concern treated as "that was then"; harm assumed to decay over time; future justice concerns treated as speculative; moral memory lost | Ask: Are historical injustices addressed or forgotten? Is harm persistent? Are future generations considered? What ethical obligations span time? |
| V  Relational | Care obligations, interdependencies, relational harms invisible; ethics reduced to individual rights; community and relationship ethics suppressed | Relationships treated as instrumental; care work invisible; mutual obligations not recognized; relational harms ignored; individuals treated as independent | Map relationships and interdependencies. What care obligations exist? Are relational harms visible? Do procedures respect relationships? |
| VI Ontological | Ethical concepts treated as settled (justice defined one way, fairness determined, rights fixed) rather than contested; alternative justice frameworks not recognized | Single definition of fairness used; justice treated as singular concept; moral disagreement not acknowledged; marginalized frameworks suppressed; ethical pluralism denied | Surface ethical framework plurality. What are alternative justice conceptions? Whose frameworks are excluded? What would other ethical ontologies reveal? |

## 8.3 Hiddens Crosswalk (Tier 2 – structured deepening layer)

| Hidden type | Relevance | Mechanism | Detectability | Agency | Consequence | Detection interface | Remediation interface | Interaction notes |
|---|---|---|---|---|---|---|---|---|
| HID-E-001: Value-neutral framing hides normative choice | H | Technical language ("efficiency," "market," "rational") used to present design choices as determined rather than chosen | Moderate: examine design documentation, designer intent, alternative designs considered | Systemic: embedded in institutions and professional norms; may not require active concealment | High: normative choices framed as neutral, escape ethical scrutiny; accountability obscured | Interview designers; examine design process; note language choices; compare to alternatives | Explicit statement of value choices; alternative design options; transparent decision-making on ethical dimensions | Often combined with stakeholder exclusion (affected parties not involved in design decisions) |
| HID-E-002: Stakeholder exclusion from ethical deliberation | H | Affected populations not included in decisions about what is fair; powerful actors define justice unilaterally | High: absence of affected voices is visible once you look for them; stakeholder lists reveal who is included/excluded | Systemic and sometimes strategic: exclusion maintained through access barriers, communication gaps, social hierarchies | High: excluded populations' moral frameworks are missing; decisions reflect limited ethical perspective; legitimacy undermined | Stakeholder mapping; voice-in-decision analysis; whose moral perspectives are heard; inclusion barriers | Genuine stakeholder participation; accessibility of deliberation; mechanisms for affected populations to shape decisions | Often reinforces other hiddens (those excluded can't detect or challenge injustices) |
| HID-E-003: Distributional invisibility | H | Benefits and harms dispersed or aggregated so that who specifically wins and loses is not visible | Moderate-to-High: disaggregation reveals patterns but requires deliberate analysis; aggregate framing hides intentionally or unintentionally | Systemic: aggregate reporting is standard practice; often not strategic concealment but structural invisibility | High: systemic injustices (concentration of benefits, dispersion of harms) invisible; moral urgency lost when framed at aggregate level | Disaggregated outcome data; demographic breakdowns; distributional mapping; comparison of winners and losers | Disaggregated reporting; impact assessments by group; distribution-conscious policy-making; transparency about who bears costs | Connected to procedural blindness: fair processes can produce unjust distributions |
| HID-E-004: Single ethical framework dominance | M | One framework (utilitarian, libertarian, communitarian) treated as obviously correct; competing frameworks not mentioned or actively suppressed | Low-to-Moderate: frameworks often made implicit rather than explicit; surfacing alternatives requires philosophical sophistication | Systemic: professional training, institutional culture, power distribution; may be strategic when dominant framework serves powerful interests | Medium: limited ethical reasoning; some considerations ignored; possibilities for hybrid approaches missed | Philosophical analysis; stakeholder framework mapping; examination of whose framework wins; evidence of framework suppression | Explicit pluralism in framework treatment; genuine engagement with competing frameworks; space for hybrid approaches; acceptance of tragic choices | Often combined with stakeholder exclusion: marginalized populations' frameworks suppressed before being heard |
| HID-E-005: Historical injustice erasure | M | Past injustices treated as irrelevant, settled, or overcome; present disparities attributed to current choices rather than historical causes | Moderate: historical erasure visible through historical comparison and institutional memory, but requires work to recover | Systemic: forgetting is default; requires active memory work to prevent erasure | Medium-to-High: present injustices justified by rejecting historical claims; remedies for past wrongs deemed unnecessary; moral reckoning prevented | Historical research; stakeholder memory; institutional genealogy; comparison of present to past distributions | Historical acknowledgment; reckoning with injustice; remedies for historical harms; institutional memory preservation; truth-telling | Connected to normalization: repeated injustices become accepted as "how things are" |
| HID-E-006: Procedural compliance as ethical cover | M | Procedures followed consistently but rules themselves are unjust; formal fairness masking substantive injustice | Moderate: requires examining outcomes against justice standards, not just procedure compliance | Systemic: procedures designed by and for powerful actors; may embed injustice intentionally or through prior exclusion | High: procedural legitimacy lends false ethical cover; rules followed despite producing injustice; reform seems to require accepting procedural framework | Outcome analysis; substantive justice assessment; examination of rule design; stakeholder experience vs. formal process | Procedural reform to address substantive justice; stakeholder voice in rule design; outcome monitoring; willingness to change unjust rules | Often combined with stakeholder exclusion: those excluded from rule design are subject to unjust rules |

## 8.4 Embedded Hiddens Micro-Protocol (standard prompts)

1. Run the Tier 1 scan across all six Hiddens meta-categories (early pass; assume Hiddens exist and identify which are plausible here) per OG §7.1.
2. Shortlist candidate Hiddens from ethical domain; for each, rate: mechanism, reducibility, detectability, agency, consequence. Focus on high-consequence Hiddens (HID-E-001 through HID-E-006 above are starting list).
3. Assign at least one detection interface and one remediation interface per high-consequence ethical Hidden; map interaction chains and stakeholder dependencies.
4. Run the ethical hiddens source analysis and record unresolved Unknowns/Hiddens (ethical concerns that remain invisible despite analysis).
5. If Tier 1 symptoms point to a specific hiding mechanism (e.g., Narrative Capture of justice language to mask injustice; Suppression of marginalized moral frameworks), invoke the appropriate Targeted Hiddens Discovery Scan per OG §7.5 using Triage Matrix at §7.5.3.
6. After executing the full ethics framework protocol and any available tests/probes, re-run Tier 1 (pre-closure pass) and note deltas: What new ethical Hiddens were discovered? Were prior candidates confirmed or disconfirmed?
7. Produce Residual Unknowns (ethical concerns that remain hidden despite investigation, with mechanism + impact + next probe needed) and apply the Escalation Rule (§8.5) if any residual ethical Hidden could change decisions, governance design, or accountability assignments.

## 8.5 Escalation Rule (Tier 3 – full-spectrum Hiddens escalation)

Escalate to full-spectrum Hiddens taxonomy run with stricter evidence/provenance and stronger disconfirming tests if any of the following apply:

- **High consequence:** Safety/existential/severe harm implications (e.g., hidden injustice affecting vulnerable populations' survival or liberty)
- **Adversarial context:** Concealment of injustice is plausible because powerful actors benefit from the injustice being hidden
- **Persistent disagreement:** Stakeholders adamantly disagree about what is fair, suggesting deep ethical framework conflicts or suppression of competing frameworks
- **Repeat failures:** Injustices recur despite prior interventions, suggesting systemic roots not being addressed
- **Cascades suspected:** One justice concern appears to reflect deeper systemic injustice across multiple dimensions
- **Decision-critical residual:** Unresolved ethical concern could change governance design, responsibility assignment, or intervention strategy

When Tier 3 is invoked:
- Expand beyond framework-specific Hiddens into full Hiddens framework taxonomy (apply all six meta-categories I–VI with full depth)
- Tighten controls: require stronger evidence, multiple independent detection paths, explicit disconfirming tests
- Map ethical Hiddens against all 36 framework ecosystem: ethics concern may have visibility consequences in Evidence, Perspectives, Narratives, Communications, Responsibility, Governance, etc.
- Consider whether Near-Group coverage (G4 + adjacent G5 and G6) or Full-Group coverage (G1–G6) is warranted by routing decision tree
- Produce detailed Tier 3 ethical Hiddens register with mechanisms, persistence drivers, detection methods, and remediation requirements

---

# 9. Framework Application Protocol

## 9.1 Application Steps Table

| Step # | Step name | Action | Outputs / artefacts |
|---:|---|---|---|
| 1 | Situation & Goal Clarification | Confirm what ethical question(s) need answering. Who are key stakeholders? What decisions depend on ethical clarity? Map decision dependencies. | Ethical question register; stakeholder roster; decision tree linking to ethics inputs |
| 2 | Meta-Category Scan | Survey all six meta-categories (distributional justice, rights, procedural fairness, relational ethics, reasoning frameworks, blind spots). Identify which are most relevant to scenario. | Meta-category relevance map; preliminary high-priority categories; stakeholder disagreements by category |
| 3 | Type Mapping | For top 2–3 meta-categories, map core types. Identify which ethical concepts are in play (e.g., merit-based distribution, rights-based reasoning, relational care). Note conflicts. | Ethical types table; which types are central; framework tensions; stakeholder disagreements on type prioritization |
| 4 | Dimensions & Dynamics | Characterize ethical issues along five dimensions (universality, urgency, power asymmetry, tractability, stakeholder perspective). Identify how ethical positions have changed or could change over time (dynamics patterns). | Dimension profile table; ethical dynamics summary; areas of agreement and persistent disagreement |
| 5 | Interfaces + Hiddens Source Analysis | Map detection interfaces (how ethics concerns are raised), judgment interfaces (how are they evaluated), action interfaces (how do they translate to decisions). Run Tier 1 Hiddens scan. Identify suppressed justice claims. | Interface map; Hiddens register (Tier 1 + Tier 2 if investigative); detection/remediation chains mapped |
| 6 | Translate to Decisions / Interventions / Governance | Synthesize ethical analysis into governance recommendations. What decisions/design changes would address ethical concerns? Who should be involved? What monitoring is needed? | Recommendations; governance implications; responsibility assignments; monitoring plan for continued ethical vigilance |

## 9.2 Standard Deliverables

**Minimum deliverable (1–2 pages):**
- Ethical question register (key normative issues identified)
- High-priority ethical types and dimensions
- Top 3–5 hidden justice claims or ethical blind spots
- One-paragraph governance implication

**Full deliverable pack:**
- Completed ethics framework outputs: meta-categories mapped, types populated, dimension profiles, dynamics patterns identified
- Ethical assumptions register: what normative claims underlie scenario; which are justified, which contested, which hidden
- Stakeholder ethical framework map: whose moral voice is heard, whose suppressed, where frameworks conflict
- Hiddens register (Tier 1 + Tier 2): ethical concerns suppressed, justice claims silenced, mechanisms of ethical invisibility
- Interface map: how detection, judgment, remediation connect; who is involved at each stage
- Governance recommendations: how to institutionalize ethical reasoning; how to ensure affected populations have voice; monitoring mechanisms

**Monitoring indicators and review cadence:**
- Stakeholder voice (are affected populations participating in decisions?)
- Distributional outcomes (is fairness in allocation being monitored?)
- Procedural fairness (are fair processes in place? Are they experienced as fair?)
- Ethical framework pluralism (are competing frameworks being heard?)
- Ethical learning (is the system improving its moral reasoning over time?)
- Review: monthly (if decisions are frequent), quarterly (standard), annually (for long-term initiatives)

### Canonical shared registers (Operating Guide v2.5 aligned; mandatory for LLM use)

| Shared register / artefact | Required | Notes (how Ethics contributes) | OG reference |
|---|---:|---|---|
| Group Coverage Matrix (G1–G6) | Yes | Ethics is G4 (Meaning) + G5 (Epistemics) secondary; integration with all groups when normative implications are decision-critical | OG §D.4.1, Appendix A, Appendix E §E.2 |
| Hiddens Register | Yes | Populate ethical Hiddens (justice claims suppressed, ethical frameworks invisible, moral voices silenced); include detection/remediation interfaces; escalate Tier 3 if consequential | OG §6.2, §D.4.1 |
| Evidence Register (Evidence Ledger) | Yes | Track claims about fairness, justice, distributions; note whose moral perspectives support/dispute claims; identify knowledge gaps in ethical assessment | OG §6.2, §D.4.1 |
| Hypotheses & Tests Backlog | Yes | Convert ethical uncertainties into discriminating tests: e.g., "Is the distribution process fair?" = test with affected populations; "Is the rule just?" = test with those subject to rule | OG §D.4.1, Appendix E §E.3 |
| Information Requests | Yes | Explicit list of ethical information missing (stakeholder perspectives, historical data on distributions, alternative designs, precedents) needed to reduce decision-critical ethical uncertainty | OG §D.10.2, Appendix E §E.4 |
| Residual Unknowns + Closure note | Yes | State what ethical concerns remain unresolved; include: (1) residual ethical unknowns, (2) acceptability rationale for proceeding despite unknowns, (3) monitoring plan for ongoing ethical vigilance, (4) ownership of ethics governance, (5) learning hook for future improvement | OG §7.4, §D.3.5 |
| Investigation Plan (post-failure) | Conditional | Required if ethical harm occurred or injustice is suspected. Recommended for scenarios involving vulnerable populations, significant resource allocation, or rights conflicts. | OG §D.4.1, Appendix B |
| Decision Record (if recommending changes) | Conditional | Required when ethics analysis leads to governance, intervention, or responsibility assignment changes. Include normative grounds for recommendations, residual ethical uncertainties, and monitoring plan. | OG §D.4.1, Appendix C |

---

# 10. Framework Principles

## 10.1 Principles Table

| Principle name | Description |
|---|---|
| 1. Moral Seriousness | Ethics is not merely academic; moral claims matter because people's lives, dignity, and flourishing are at stake. Analysis must be rigorous and consequential, not detached. |
| 2. Stakeholder Inclusion | Affected populations' moral voices must be included, not just in final consultation but from problem definition onward. Those experiencing injustice are moral experts on that injustice. |
| 3. Framework Pluralism | Multiple justice frameworks (utilitarian, rights-based, care, communitarian, relational, capabilities) are legitimate; conflicts between them are real and sometimes tragic, not errors to be eliminated. |
| 4. Normative Visibility | Ethical assumptions, normative choices, and moral claims embedded in designs, procedures, and institutions must be made explicit and open to ethical scrutiny and contestation. |
| 5. Interdependence | Justice is not only about fair distribution to independent individuals; it includes recognition of interdependence, mutual obligation, relational ethics, and collective good. Vulnerability and care matter morally. |

---

# 11. Glossary (local domain terms)

## 11.1 Local domain glossary

| Term | Definition |
|---|---|
| Distributive Justice | Fair allocation of benefits (resources, opportunities, recognition) and burdens (costs, harms, exclusion) across populations; includes need-based, merit-based, equality-based, rights-based, and collective-good approaches |
| Procedural Fairness | Fairness in how decisions are made: voice, transparency, impartiality, appeal rights, rule of law; distinct from substantive justice (fair outcomes) |
| Rights | Entitlements and protections people have a moral claim to; includes formal legal rights, substantive capabilities, dignity protections, negative (freedom from) and positive (entitlements to) rights |
| Relational Ethics | Ethical obligations arising from relationships, interdependencies, and care; includes care duties, mutual obligations, communal bonds, responsiveness to vulnerability; contrasts with individualist ethics |
| Ethical Framework | A coherent system of moral reasoning (utilitarian, deontological, virtue, care-based, social contract, capabilities approach, relational); specifies what makes an action right and justifies moral claims |
| Ethical Blind Spot | Moral consideration systematically absent or suppressed in a scenario; injustice invisible due to value-neutral framing, stakeholder exclusion, single-framework dominance, or normalization of harm |
| Suppression / Silencing | Active or structural exclusion of justice claims, ethical frameworks, or moral voices from consideration; includes lack of platform, dismissal as irrational, retaliation against dissenters |
| Normative Claim | An assertion about what is right, fair, just, good, or owed; may be explicit or embedded in design, procedure, or language; distinct from factual or descriptive claims |
| Ethical Assumptions | Normative premises built into decisions, designs, institutions that are treated as background/settled rather than as contestable choices requiring justification |
| Hidden Justice Claim | A moral concern or ethical perspective that exists but is not visible in decision-making: stakeholders have concerns that are not heard, frameworks that are not considered, voices that are suppressed |

## 11.2 Core execution terms (pointer; do not restate)

- See **Analytical Series Operating Guide**, v2.5:
  - Core execution terms (mandatory): **§D.10.1**
  - Artefact terms (mandatory): **§D.10.2**
  - Full Operating Guide glossary: **§11** (§11.1–§11.9)
  - Targeted Hiddens Discovery Scans glossary: **§7.5.6** (also §11.7)

---

# 12. Document Control

## 12.1 Version History

| Version | Date | Changes |
|---|---|---|
| v1.0 | 2026-04-08 | Initial composition following MRT v3.0. Six meta-categories (30 core types), five cross-cutting dimensions, twelve dynamic patterns, A/B/C interface types fully populated. Tier 1/2/3 Hiddens structure complete. Integration questions for all 36 frameworks. Framework positioned as G4 (Meaning) primary + G5 (Epistemics) secondary. Designed for both Rapid Run Mode (Light Depth) and Investigative Run Mode (Full Depth). Emphasis on surfacing hidden normative claims, justice invisibility mechanisms, ethical blind spots. Includes worked hiddens analysis (six framework-specific sources, Tier 2 crosswalk with six key ethical Hiddens), escalation logic. Status: Draft (ready for stakeholder review and testing). |

## 12.2 Integration Notes

**Design philosophy:**
This framework is positioned to ask the question that Values cannot: not "what do actors value?" but "what *should* be valued, and on what grounds?" It examines normative assumptions hidden in scenarios, unearths suppressed justice claims, and surfaces ethical blind spots. It integrates closely with Legitimacy (which asks "is authority accepted?" while Ethics asks "is acceptance warranted on moral grounds?"), Responsibility (which assigns accountability while Ethics asks how accountability *should* be assigned), and the full breadth of the Analytical Series (every framework embeds normative assumptions that Ethics can surface).

**Key integration points:**
- Upstream from Decisions, Interventions, Governance: ethical analysis informs how decisions should be made, what interventions address justice, what governance structures honor fairness
- Complementary to Hiddens framework: ethical Hiddens (justice claims suppressed, moral frameworks invisible) are one layer of broader hiddenness work
- Cross-cutting with all groups: every framework involves normative claims; ethics can be invoked at any routing decision point
- Reflexive: can be applied to its own assumptions (is the 30-type taxonomy fair? Whose justice frameworks does it include/exclude?)

**Distinguishing Ethics from near-neighbours:**
- *vs. Values:* Values describes what actors actually hold as important (descriptive); Ethics evaluates what *ought* to be valued (prescriptive). Values asks "what is?" Ethics asks "what should be?"
- *vs. Legitimacy:* Legitimacy asks whether authority is socially *accepted*; Ethics asks whether acceptance is *justified* on moral grounds. Legitimacy is about social facts; Ethics is about moral warrant.
- *vs. Culture and Norms:* Culture describes shared conventions; Ethics evaluates them against standards. Culture is descriptive; Ethics is critical.
- *vs. Responsibility:* Responsibility assigns accountability (how is it done); Ethics evaluates whether assignment is just (how *should* it be done).

---

# Appendices

## Appendix A: Consolidated 30-Type Table (Single View)

| Category | Type # | Type Name | Description (abbreviated) | Meta-category |
|---|---:|---|---|---|
| I | 1 | Need-Based Distribution | Allocation based on requirements for basic needs and threshold sufficiency | Distributional Justice |
| I | 2 | Merit-Based Distribution | Allocation based on effort, achievement, contribution fairly assessed | Distributional Justice |
| I | 3 | Equality-Based Distribution | Allocation prioritizing equal shares, treatment, or opportunity | Distributional Justice |
| I | 4 | Entitlement and Rights-Based Distribution | Allocation based on legal, moral, or prior entitlements | Distributional Justice |
| I | 5 | Collective Good and Common Benefit Distribution | Allocation prioritizing collective/common purpose over individual entitlement | Distributional Justice |
| II | 6 | Formal Legal Rights | Constitutional, statutory, contractual protections formally recognized | Rights and Dignity |
| II | 7 | Substantive Rights and Capabilities | Actual ability to exercise rights and achieve valued freedoms | Rights and Dignity |
| II | 8 | Dignity and Respect Rights | Protection from degradation, disrespect, arbitrary power; autonomy and self-determination | Rights and Dignity |
| II | 9 | Negative Rights (Freedom From) | Rights to be free from violence, coercion, discrimination, privacy violation | Rights and Dignity |
| II | 10 | Positive Rights (Entitlements To) | Rights to provision of goods/services: food, shelter, healthcare, education, work | Rights and Dignity |
| III | 11 | Voice and Participation | Opportunity for affected parties to be heard and shape decisions | Procedural Fairness |
| III | 12 | Transparency and Information Access | Availability of information about decisions, rules, reasoning, outcomes | Procedural Fairness |
| III | 13 | Impartiality and Absence of Conflict of Interest | Decisions by neutral parties without personal stake or bias | Procedural Fairness |
| III | 14 | Appeal and Remedy | Opportunity to contest decisions and obtain remedy if wronged | Procedural Fairness |
| III | 15 | Rule of Law and Consistent Application | Rules general, knowable, stable, applied consistently to all | Procedural Fairness |
| IV | 16 | Care and Attentiveness | Responsibility from relationships and vulnerability; responsive caregiving | Relational and Care Ethics |
| IV | 17 | Interdependence and Mutual Obligation | Mutual obligations arising from interdependence; relational obligations | Relational and Care Ethics |
| IV | 18 | Solidarity and Community | Obligations from shared community membership and collective identity | Relational and Care Ethics |
| IV | 19 | Responsiveness to Vulnerability | Particular obligation toward vulnerable; protection and respectful response | Relational and Care Ethics |
| IV | 20 | Relational Autonomy and Self-Determination | Self-determination embedded in relationships; autonomy-in-relationship | Relational and Care Ethics |
| V | 21 | Consequentialist Reasoning | Moral evaluation based on outcomes and consequences; welfare and flourishing | Ethical Reasoning and Frameworks |
| V | 22 | Deontological Reasoning | Moral evaluation based on duties, rights, rules regardless of consequences | Ethical Reasoning and Frameworks |
| V | 23 | Virtue-Based Reasoning | Moral evaluation based on character, virtues, excellences; what kind of person/community we become | Ethical Reasoning and Frameworks |
| V | 24 | Care-Based Reasoning | Moral evaluation based on relationships, care, responsiveness, interdependence | Ethical Reasoning and Frameworks |
| V | 25 | Relational and Social Contract Reasoning | Moral evaluation based on reciprocal agreements and fair terms of association | Ethical Reasoning and Frameworks |
| VI | 26 | Value-Neutral Framing | Normative choices presented as technical, neutral, inevitable rather than as moral claims | Ethical Blind Spots and Suppression |
| VI | 27 | Distributional Invisibility | Benefits/harms dispersed or aggregated so who bears what is obscured | Ethical Blind Spots and Suppression |
| VI | 28 | Ethical Assumptions Made Invisible | Moral claims embedded in design treated as background rather than contestable | Ethical Blind Spots and Suppression |
| VI | 29 | Suppression and Silencing | Justice claims, ethical frameworks, moral voices actively excluded from consideration | Ethical Blind Spots and Suppression |
| VI | 30 | Ethical Corruption and Normalization of Harm | Unjust practices normalized through repetition; moral concern fades | Ethical Blind Spots and Suppression |

## Appendix B: Full Hiddens Crosswalk (Tier 3 Expansion)

[Six Tier 2 Hiddens from §8.3 above represent initial identification. Full Tier 3 escalation would expand each Hidden across:
- All six Hiddens meta-categories (I–VI Perceptual, Systemic, Informational, Temporal, Relational, Ontological)
- All 36 frameworks: visibility consequences in Evidence, Perspectives, Narratives, Communications, Responsibility, Governance, etc.
- Stronger evidence and disconfirming tests for each
- Complete mechanism chains showing how ethical Hiddens persist
- Detection and remediation interfaces for each

This full Tier 3 work produces a stand-alone Appendix document; template provided in OG §D.6.10.]

## Appendix C: Worked Example (Micro-Case)

**Scenario:** An organization is redesigning its benefits distribution process. Current system allocates bonuses based on performance metrics. Some stakeholders raise concerns about fairness: metrics may be biased, some groups consistently lower, distributional gaps widening.

**Ethical analysis:**
- **Meta-category relevance:** Distributional Justice (primary), Rights and Dignity (secondary—concerns about equal treatment), Procedural Fairness (how metrics are chosen)
- **Types activated:** Merit-Based Distribution (how is merit measured?), Equality-Based Distribution (are there systematic gaps?), Voice and Participation (did affected groups help design metrics?)
- **Dimensions:** Power Asymmetry (high—management controls metric design); Stakeholder Perspective (low—few marginalized voices heard); Tractability (medium—metrics could be redesigned)
- **Hidden concerns (Tier 1 scan):**
  - Perceptual: Are metrics presented as neutral/objective? (likely; math obscures normative choice)
  - Systemic: Do metrics embed bias? (likely; historical metrics may reflect prior biases)
  - Informational: Do affected groups know how they're measured? (unclear; rarely taught)
  - Distributional: Are disparities visible? (aggregate bonuses reported; broken down by group? Probably not)
  - Relational: Were affected groups involved in metric design? (unlikely; top-down process)
  - Ontological: Is merit defined one way? (yes; measurement-based only; alternative merit concepts—collaboration, community contribution—invisible)

**Remediation:** 
- Make metric design explicit as a normative choice
- Involve affected groups in redesigning metrics
- Monitor distributions by demographic group
- Consider multiple dimensions of merit
- Allow voice and appeals in evaluation process

---

## Appendix D: Checklists and Workshop Prompts

**Ethical Analysis Quick-Check (Light Depth):**
- [ ] What normative claims are embedded in this scenario? (name them)
- [ ] Whose moral voice is missing? (identify excluded stakeholders)
- [ ] What justice framework(s) are in use? (utilitarian, rights, care, communitarian, etc.?)
- [ ] Are there conflicts between frameworks? (name the tensions)
- [ ] What is being treated as settled/inevitable that could be questioned? (ethical blind spots)
- [ ] If affected populations had voice, what would they say? (infer suppressed concerns)

**Deep Ethical Deliberation Questions (Full Depth / Investigative):**
1. Distributional: Who gets what and who bears what? Is distribution fair by which standard(s)? Who decided? On what grounds?
2. Procedural: Were those affected consulted? Do they have information and voice? Can they appeal?
3. Rights: What rights are at stake? Are they protected or violated? Whose rights matter less?
4. Relational: What care and interdependencies are involved? Are they honored or instrumentalized? Are vulnerable groups protected?
5. Frameworks: What ethical reasoning patterns are in use? Where do they conflict? Whose framework dominates?
6. Hiddens: What ethical concerns are invisible? Which justice claims are silenced? What assumptions are hidden?
7. Governance: How can this organization institutionalize ethical reasoning? How can affected populations have ongoing voice?

---

## Appendix E: Machine-Readable Field Schemas (OG Appendix E aligned)

[Field schemas for structured capture of Ethics framework outputs, ready for integration with Evidence Register, Hiddens Register, Hypotheses & Tests Backlog, Information Requests. Includes:
- Ethical type enumeration (30 canonical types with unique IDs E-I-01 through E-VI-05)
- Ethical Hidden schema (ID, mechanism, detectability, agency, consequence, detection interface, remediation interface)
- Stakeholder ethical framework mapping (stakeholder ID, frameworks held, priority weights, suppression evidence)
- Distributional outcome schema (outcome category, group breakdowns, fairness assessment by framework, residual unknowns)
- Governance ethics integration schema (decision point, ethical question, framework consultation, voice inclusion, monitoring)

Full schemas provided in supplementary machine-readable format; contact framework owner.]

---

# End of Framework of Ethics v1.0

**Status:** Draft (ready for stakeholder review, pilot testing, integration testing with other frameworks, and field validation)

**Next steps for v1.1:**
- Stakeholder review and feedback (affected populations, ethics professionals, governance practitioners)
- Pilot testing in 3–5 real scenarios (different sectors, different ethical domains)
- Integration testing with full 36-framework ecosystem
- Refinement of Tier 2 Hiddens crosswalk based on field experience
- Validation of dimensional characterizations
- Documentation of use patterns and lessons learned
