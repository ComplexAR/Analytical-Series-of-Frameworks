# Comparative Approaches to Investigating Unknowns and Hiddens
## Expanded Reference for ASF Whitepaper Section 2

**Purpose:** This document provides a comprehensive, structured inventory of existing approaches, methodologies, and frameworks used to discover, uncover, or investigate unknowns, hidden factors, blind spots, latent conditions, tacit assumptions, concealed dependencies, and emergent risks across social, socio-technical, and technical settings. It is organised for comparative analysis against the ASF's contribution.

**Structure:** Approaches are grouped by the *primary dimension of hiddenness* they address, mapping to the ASF's analytical architecture. For each cluster, a brief comparative note identifies what the cluster sees, what it characteristically misses, and how the ASF relates to it. Individual approaches marked with **[NEW]** are additions to the original working list.

---

## Organising Principle

The ASF's claim is that existing approaches each capture a genuine slice of the hiddenness problem but none provides all five elements required for comprehensive investigation: (a) mechanism-based taxonomy, (b) multi-lens coverage model, (c) detection and remediation protocol, (d) reflexive self-application, (e) LLM-executable design. The structure below makes this claim testable by showing exactly which slice each approach captures.

---

## 1. Epistemic Framing: Classifying What Is and Is Not Known

These approaches provide frameworks for categorising knowledge states, uncertainty types, and epistemic conditions. They answer "what do we know about what we know?" but typically do not provide mechanisms for *why* things are unknown or operational protocols for changing visibility conditions.

### 1.1 Knowledge-State Taxonomies

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Rumsfeld Matrix (known knowns → unknown unknowns) | Four epistemic quadrants; forces admission of bounded knowledge | No mechanisms for *why* unknown; no detection protocol; no remediation; static classification | ASF extends from epistemic states to hiding mechanisms; 30-type taxonomy replaces 4 quadrants |
| Johari Window | Positional awareness; blind spots vs deliberate concealment | Interpersonal scope only; no systemic/structural mechanisms; no investigation protocol | ASF Category V (Relational) extends positional dynamics to multi-actor systems |
| Epistemic status mapping | Explicit tagging of confidence levels and evidence basis | Maps current state; does not explain what produces the state or how to change it | ASF's F/I/A/U tagging is a form of epistemic status mapping embedded within a larger protocol |
| **[NEW]** Knightian uncertainty (risk vs uncertainty) | Distinction between quantifiable risk and unquantifiable uncertainty | Binary classification; no mechanism taxonomy; no investigation method | ASF's reducibility dimension (eliminable → irreducible) provides a finer-grained version |
| **[NEW]** Ellsberg paradox / ambiguity aversion | Reveals how actors respond differently to known vs unknown probabilities | Descriptive of behaviour, not diagnostic of hiding mechanisms | ASF's Ontological category (VI) addresses the conditions that produce deep ambiguity |

### 1.2 Sensemaking and Decision Framing

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Cynefin framework | Domain classification (simple, complicated, complex, chaotic, confused); appropriate response posture per domain | No mechanism taxonomy for hiddenness within each domain; no detection/remediation protocol | ASF's Situations Context Classification framework serves a comparable routing function but links to hiding mechanisms per domain type |
| OODA loop (Boyd) | Observation-orientation-decision-action cycle; orientation as filter/distortion source | Individual/adversarial framing; weak on systemic/institutional/temporal hiddenness | ASF's iterative loop (Initialise → Generate → Route → Execute → Test → Re-scan → Decide) is a more structured version with register discipline |
| Sensemaking theory (Weick) | How actors construct plausible narratives under ambiguity; retrospective sense-construction | Strong on meaning-making; weaker on mechanism classification and operational protocol | ASF's G4 (Meaning) group draws on sensemaking; adds structured taxonomy and Hiddens cross-check |
| Recognition-Primed Decision model (Klein) | How experts recognise situations and act without deliberate analysis; role of experience | Explains expert intuition; does not address what experts systematically miss | ASF's Habituation (Type 5) and Model Blindness (Type 10) address expert failure modes |
| **[NEW]** Naturalistic Decision Making | How decisions are made in real-world, time-pressured, uncertain conditions | Descriptive; does not provide systematic investigation of what was missed | ASF provides the post-hoc and prospective investigation protocol that NDM describes the need for |
| **[NEW]** Situation Awareness (Endsley) | Three-level model: perception, comprehension, projection; SA failures as accident contributors | Strong on perception/comprehension failures; weaker on systemic/institutional/informational hiding | ASF's Category I (Perceptual) addresses SA Level 1 failures; Categories II–VI address what SA theory does not reach |

### 1.3 Reasoning Under Uncertainty

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Bayesian reasoning | Formal updating of beliefs given evidence; prior/posterior structure | Requires specifiable hypotheses and quantifiable likelihoods; fails on unknown unknowns and structural hiddenness | ASF addresses the conditions under which Bayesian updating itself is unreliable (distorted priors, hidden evidence, paradigm boundaries) |
| Dempster–Shafer theory | Handles epistemic uncertainty and ignorance without requiring probability assignment | Mathematical; no operational investigation protocol; no mechanism classification | ASF provides the operational layer that formal uncertainty theories lack |
| Info-gap decision theory | Decision-making under severe uncertainty; robustness to unknowns | Focuses on decision robustness, not on discovering what is hidden | ASF's detection and remediation protocol complements info-gap's robustness orientation |
| Robust decision making | Identifies decisions that perform acceptably across many futures | Strategy selection, not hidden-factor investigation | ASF's G6 (Action & Control) draws on RDM principles; adds visibility governance |
| Decision analysis under deep uncertainty | Ensemble of methods for decisions when probability distributions are unknown | Framework of frameworks for decision methods; not an investigation methodology | ASF provides the investigation methodology that DADU-class decisions need as input |
| **[NEW]** Signal detection theory | Mathematical framework for detecting signals in noise; sensitivity vs criterion | Formal; addresses perceptual/statistical detection; not systemic or institutional hiddenness | ASF's Category I (Perceptual) addresses the conditions SDT formalises; Categories II–VI address what SDT cannot reach |
| **[NEW]** Information theory (Shannon) | Quantifies information content, channel capacity, noise | Formal; powerful for channel analysis; not designed for mechanism classification or investigation | ASF's Category III (Informational) addresses the qualitative structure that information theory quantifies |

### 1.4 Structured Challenge and Hypothesis Testing

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Premortem analysis | Prospective failure imagination; surfaces concerns suppressed by optimism and groupthink | Single exercise, not sustained protocol; no mechanism taxonomy; no register discipline | ASF's Tier 1 Hiddens scan performs a comparable function but with mechanism classification and register output |
| Red teaming | Adversarial challenge to plans, assumptions, and defences | Focuses on adversarial/deliberate failures; weaker on accidental, systemic, and ontological hiddenness | ASF's agency dimension (Natural → Adversarial) positions red teaming as one response appropriate for the deliberate/adversarial end |
| Devil's advocacy | Deliberate argument against the prevailing position | Useful challenge; no mechanism taxonomy; can become performative | ASF's anti-theatre rule and PD-05 (prefer tests over narrative) provide structural discipline |
| Dialectical inquiry | Structured opposition of thesis and antithesis to surface assumptions | Surfaces contested assumptions; does not classify hiding mechanisms or provide detection protocol | ASF's Perspectives framework (G4) and Beliefs framework (G5) address dialectical dynamics |
| Multiple working hypotheses (Chamberlin) | Prevents premature closure by maintaining competing explanations | Powerful epistemic discipline; no mechanism taxonomy for what might hide the evidence needed to discriminate | ASF's Hypothesis/Test Backlog operationalises multiple hypotheses with discriminating tests |
| Abductive reasoning | Inference to the best explanation; generates hypotheses from surprising observations | Generative; does not provide systematic traversal of hiding mechanisms | ASF uses abductive reasoning within a structured framework that prevents single-hypothesis fixation |
| Analysis of competing hypotheses (ACH) | Systematic evaluation of evidence against multiple hypotheses; identifies diagnosticity | Strong on evidence evaluation; weaker on what evidence is hidden and why | ASF complements ACH by systematically asking what evidence is hidden, by what mechanism, and how to surface it |
| **[NEW]** Key assumptions check | Explicit listing and challenging of analytic assumptions | Surfaces assumptions; does not classify hiding mechanisms or provide remediation protocol | ASF's Assumptions Register in every framework performs this function with mechanism linkage |
| **[NEW]** Quality of information check | Systematic evaluation of source reliability and information validity | Evaluates what is available; does not address what is systematically hidden | ASF's Evidence framework (G5) and Category III (Informational) extend this to hidden evidence |
| **[NEW]** Linchpin analysis | Identifies the single assumption on which an entire assessment depends | Powerful for fragile analyses; narrow scope | ASF's five-dimension profiling (especially consequence) identifies linchpin hiddens |
| Critical rationalism / falsification (Popper) | Emphasis on disconfirmation; conjectures and refutations | Powerful epistemology; not an operational investigation protocol | ASF's PD-05 (prefer discriminating tests over narrative) operationalises falsificationist discipline |
| Assumption-Based Planning (Dewar) | Identifies load-bearing assumptions and designs shaping/hedging actions | Strong on assumption management; does not classify hiding mechanisms | ASF extends ABP's assumption logic with a mechanism taxonomy and detection protocol |

### 1.5 Learning and Reflexive Practice

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Reflective practice (Schön) | Practitioner reflection-in-action and reflection-on-action | Individual learning; not a systematic investigation methodology | ASF's reflexive self-application (meta-validation test) systematises what Schön describes |
| Double-loop learning (Argyris) | Surfaces governing variables and defensive routines that block learning | Strong on organisational learning failure; no mechanism taxonomy; no operational protocol | ASF's Category IV (Temporal — especially Amnesia, Type 18) and Learning and Adaptation framework (G6) address the conditions DLL identifies |
| Triple-loop learning | Questions the paradigm within which learning occurs | Addresses paradigm-level blindness; abstract; not operationalised | ASF's Category VI (Ontological — especially Paradigm Boundary, Type 28) operationalises this |
| **[NEW]** Organisational learning (March / Levinthal) | Exploration vs exploitation trade-offs; competency traps; myopic learning | Strong on learning dynamics; does not provide investigation protocol for current hiddens | ASF's Learning and Adaptation framework (G6) addresses these dynamics within a larger investigation architecture |
| After-action review | Structured post-event reflection: what was planned, what happened, why, what next | Retrospective; no mechanism taxonomy; no register discipline; depends on participant candour | ASF's iterative loop subsumes AAR's function with stronger quality controls and F/I/A/U tagging |
| Lessons learned review | Collection and dissemination of experience-based knowledge | Valuable; notoriously poor at preventing recurrence (the "lessons identified but not learned" problem) | ASF's Amnesia (Type 18) directly addresses why lessons are lost; the residual unknowns log prevents silent closure |
| Retrospectives | Team-level reflection on process and improvement | Useful practice; no mechanism taxonomy; vulnerable to groupthink and positional filtering | ASF provides the mechanism vocabulary that retrospectives need to move beyond symptom-level discussion |
| **[NEW]** Blameless postmortem | Post-incident learning without individual blame attribution | Removes blame barrier to disclosure; does not provide mechanism taxonomy or systematic detection | ASF's anti-theatre rule and register discipline complement the blameless culture that postmortems require |

---

## 2. Systemic Structure: What the System Hides by How It Works

These approaches model how systems, structures, and dynamic processes produce unintuitive behaviour, emergent properties, and hidden interactions. They explain *how* systems generate surprises but typically do not provide a comprehensive taxonomy of *what* is hidden or an operational detection protocol.

### 2.1 Systems Thinking and Complexity

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Systems thinking (Senge, Ackoff) | Interconnection, feedback, mental models, leverage points | Explains system behaviour; does not provide hiding mechanism taxonomy or detection protocol | ASF's G2 (Mechanism) group operationalises systems thinking with Hiddens cross-checks |
| Complexity science | Non-linearity, emergence, adaptation, self-organisation, sensitivity to initial conditions | Powerful explanatory framework; not an investigation methodology | ASF incorporates complexity insights via Emergence, Networks, and Systems frameworks |
| Complex adaptive systems | Agents, adaptation, co-evolution, emergent order | Theoretical; not designed for specific hidden-factor investigation | ASF's Emergence framework (G2) and Emergent Invisibility (Type 23) address CAS-specific hiddenness |
| System dynamics (Forrester, Sterman) | Feedback loops, delays, accumulations, policy resistance, counterintuitive behaviour | Strong on dynamic complexity; does not address informational, temporal, relational, or ontological hiddenness | ASF wraps system dynamics insights within a six-category visibility framework |
| Causal loop diagrams | Feedback structure visualisation; reinforcing/balancing loops | Visualisation tool; does not classify what the loops hide or provide detection protocol | ASF's dynamics patterns (cascade, reinforcement, evolution, revelation, resistance) extend CLD logic |
| Stock-and-flow modelling | Accumulation dynamics; bathtub metaphor for flows | Powerful for specific dynamics; model boundary choices create systematic blind spots | ASF's Model Blindness (Type 10) and Framing (Type 8) address the hiddenness stock-flow models produce |
| Leverage points analysis (Meadows) | Twelve leverage points ordered by effectiveness; most powerful points are least visible | Brilliant insight into the relationship between leverage and visibility; no investigation protocol | ASF operationalises Meadows' insight: the ASF's routing and depth logic directs attention to high-leverage, low-visibility mechanisms |
| **[NEW]** Agent-based modelling | Emergent macro-behaviour from micro-rules; heterogeneity and interaction effects | Reveals emergence; model assumptions determine what can emerge; silent on what the model excludes | ASF's Model Blindness (Type 10) addresses what ABMs systematically hide |
| **[NEW]** Network science / graph theory | Topology, centrality, clustering, contagion, cascade dynamics | Powerful structural analysis; typically does not address what network position hides from specific actors | ASF's Networks framework (G2) and Positional blindness (Type 21) address network-specific hiddenness |

### 2.2 Sociotechnical and Institutional Structure

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Soft Systems Methodology (Checkland) | Multiple worldviews (Weltanschauungen); rich pictures; CATWOE analysis | Strong on perspectival plurality; no mechanism taxonomy; no detection/remediation protocol | ASF's Perspectives framework (G4) and Perspectival invisibility (Type 25) extend SSM |
| Critical Systems Heuristics (Ulrich) | Boundary judgments and their normative consequences; who is included/excluded | Directly addresses framing hiddenness; narrow scope (boundary critique only) | ASF's Boundaries framework (G1) and Framing (Type 8) incorporate CSH's boundary critique |
| Viable System Model (Beer) | Recursive structure for organisational viability; requisite variety; information channels | Strong on structural prerequisites for viability; less on what specific mechanisms hide within viable structures | ASF's Institutions framework (G2) and Governance framework (G6) address institutional hiddenness |
| Sociotechnical systems theory (Trist, Emery) | Joint optimisation of social and technical subsystems; autonomous work groups | Foundational for understanding social-technical interaction; not an investigation protocol | ASF is designed specifically for sociotechnical scenarios; extends STS with investigation methodology |
| Actor-network theory (Latour, Callon) | How heterogeneous networks of human and non-human actors are assembled and maintained | Powerful descriptive framework; explicitly avoids providing causal mechanisms or investigation protocol | ASF provides the operational investigation protocol that ANT's descriptions call for |
| **[NEW]** Institutional theory (DiMaggio, Powell) | Isomorphism, institutional logics, taken-for-granted practices, ceremonial adoption | Explains institutional inertia and hidden conformity pressures; not an investigation methodology | ASF's Institutions framework (G2) operationalises institutional theory's insights |
| **[NEW]** Institutional ethnography (Dorothy Smith) | How institutional texts and ruling relations organise experience; disjuncture between experience and official accounts | Powerful for uncovering how institutional processes hide experience; narrow method | ASF's Category III (Informational) and Category V (Relational) address the patterns IE surfaces |
| STS / Science and Technology Studies | How science and technology are socially constructed; co-production of knowledge and social order | Powerful analytical lens; descriptive and critical rather than investigative | ASF incorporates STS insights via Technology framework (G2) and Knowledge framework (G5) |
| Assemblage theory (DeLanda, Deleuze) | How heterogeneous elements come together and produce emergent properties | Theoretical; not operationalised for investigation | ASF's Emergence framework (G2) provides the operational version |
| **[NEW]** Rasmussen's risk management framework | Migration to boundaries; drift across levels (work, management, regulation) | Explains how systems drift toward failure; does not provide mechanism taxonomy for what hides the drift | ASF's Drift into failure dynamics and Habituation (Type 5) address what Rasmussen's framework describes but does not operationalise for detection |
| Resilience engineering (Hollnagel, Woods) | Capacity to anticipate, monitor, respond, and learn; Safety-II (what goes right) | Reframes safety; does not provide mechanism taxonomy for visibility failures | ASF incorporates resilience thinking; adds structured hiddenness investigation |
| **[NEW]** Antifragility (Taleb) | Systems that gain from disorder; fragility detection; via negativa | Powerful reframing; heuristic rather than systematic; no mechanism taxonomy | ASF addresses fragility sources through its interaction mapping and cascade analysis |
| **[NEW]** Panarchy / adaptive cycle (Gunderson, Holling) | Cross-scale dynamics; release and reorganisation phases; revolt and remember connections | Explains temporal and cross-scale dynamics; not an investigation protocol | ASF's Scale, Time, and Emergence frameworks address panarchy dynamics within an investigation structure |

---

## 3. Agency, Power, and Strategic Hiddenness

These approaches address how human actors — through incentives, power, cognitive limits, social dynamics, and strategic behaviour — produce, maintain, and exploit invisibility. They are strongest on *who* hides and *why* but typically do not provide a comprehensive mechanism taxonomy or a protocol that also covers systemic, temporal, and ontological hiddenness.

### 3.1 Economics of Information Asymmetry

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Principal-Agent Theory | Hidden information (adverse selection) and hidden action (moral hazard) | Bilateral, rational-actor framing; does not address systemic, temporal, or ontological hiddenness | ASF's G3 (Agency) incorporates; extends to multi-actor systems and non-rational mechanisms |
| Agency theory | Divergent interests between principals and agents; monitoring and incentive alignment | Normative focus on contract design; not an investigation methodology | ASF's Incentives and Interests frameworks operationalise agency insights for investigation |
| Adverse selection | Pre-contractual information asymmetry | Specific mechanism; narrow scope | ASF's Secrets (Type 11) and Distortion (Type 6) address this and many other concealment mechanisms |
| Moral hazard | Post-contractual hidden action | Specific mechanism; narrow scope | ASF's agency dimension (Natural → Adversarial) captures the spectrum moral hazard occupies |
| **[NEW]** Mechanism design theory | Designing institutions that align incentives under information asymmetry | Normative (design) rather than diagnostic (investigation); assumes rational actors | ASF's Incentives framework is diagnostic; identifies where mechanism design assumptions fail |
| Public choice theory | Self-interested behaviour in public institutions; rent-seeking; regulatory capture | Strong on institutional incentive failure; narrow economic framing | ASF's Institutions and Governance frameworks address these dynamics within a broader architecture |
| **[NEW]** Transaction cost economics (Williamson) | Bounded rationality, opportunism, asset specificity; governance structures as responses to hidden information | Explains institutional form; not an investigation methodology for what remains hidden | ASF's Institutions framework (G2) addresses the residual hiddenness that TCE's governance structures create |
| **[NEW]** Regulatory capture analysis | How regulated entities influence regulators; revolving doors; information asymmetry | Specific institutional mechanism; narrow | ASF's Power (G3), Institutions (G2), and Secrets (Type 11) address capture within a comprehensive framework |

### 3.2 Cognitive and Psychological Mechanisms

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Bounded rationality (Simon) | Cognitive limits on information processing, search, and optimisation | Foundational concept; not an investigation protocol | ASF's Cognition framework (G3) operationalises bounded rationality for investigation |
| **[NEW]** Cognitive biases (Kahneman, Tversky) | Systematic deviations from rationality: anchoring, availability, representativeness, framing effects, etc. | Catalogues individual biases; does not provide systemic investigation protocol or mechanism taxonomy across scales | ASF's Category I (Perceptual) and Category II (Systemic) address cognitive biases within a larger framework that also covers institutional and structural sources |
| **[NEW]** Prospect theory | Loss aversion, reference dependence, probability weighting | Explains decision distortion; descriptive, not investigative | ASF's Cognition framework addresses prospect theory dynamics when relevant to hidden factors |
| **[NEW]** Motivated reasoning | How goals and desires shape information processing and belief formation | Explains why people resist disconfirming evidence; narrow scope | ASF's Beliefs framework (G5) and Shadows (Type 16) address motivated reasoning at individual and institutional levels |
| **[NEW]** Cognitive dissonance theory (Festinger) | How holding contradictory beliefs creates psychological pressure toward resolution (often through denial/rationalisation) | Explains individual denial mechanisms; does not scale to institutional analysis | ASF's Shadows (Type 16) and Denial dynamics address what cognitive dissonance theory describes |
| **[NEW]** Confirmation bias research | Systematic tendency to seek/interpret evidence that confirms existing beliefs | Well-documented bias; not an investigation methodology | ASF's PD-05 (prefer discriminating tests) and PD-04 (track disagreement) are structural countermeasures |
| **[NEW]** Dunning-Kruger effect | Incompetence impairs ability to recognise own incompetence | Specific bias; narrow | ASF's Competencies framework (G3) and Model Blindness (Type 10) address this at individual and institutional levels |
| **[NEW]** Normalisation of deviance (Vaughan) | How repeated rule violations become accepted practice within organisations | Powerful organisational concept; not a systematic investigation protocol | ASF's Habituation (Type 5) and Drift dynamics directly address what Vaughan describes |
| **[NEW]** Inattentional blindness / change blindness research | Experimental demonstration that salient signals are missed when attention is elsewhere | Demonstrates perceptual limits; laboratory phenomenon | ASF's Inattention (Type 3) and Habituation (Type 5) operationalise these findings for investigation |

### 3.3 Social and Organisational Dynamics

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Groupthink (Janis) | Conformity pressure suppresses dissent and critical evaluation in cohesive groups | Specific social mechanism; no mechanism taxonomy; no broader investigation protocol | ASF's Echoes (Type 12), Organisational Silence, and the Tier 1 scan address groupthink as one of many social hiding mechanisms |
| Organisational silence (Morrison, Milliken) | Systematic withholding of information by employees; climate of silence | Strong on why people don't speak; does not cover systemic, temporal, or ontological hiddenness | ASF's Secrets (Type 11), Fragmentation (Type 14), and Communications framework (G4) address silence within a comprehensive framework |
| Spiral of silence (Noelle-Neumann) | How perceived majority opinion suppresses minority views | Explains public opinion dynamics; narrow scope | ASF's Echoes (Type 12) and Perspectival invisibility (Type 25) address the ASF-relevant aspects |
| Pluralistic ignorance | Majority privately rejects a norm but assumes others accept it | Specific social mechanism; narrow | ASF's Shadows (Type 16) and Culture and Norms framework (G4) address this dynamic |
| **[NEW]** Psychological safety (Edmondson) | Team climate that enables risk-taking, speaking up, and error reporting | Explains conditions for disclosure; does not investigate what remains hidden | ASF investigates what remains hidden even when psychological safety exists (systemic, structural, ontological hiddens) |
| **[NEW]** Whistleblowing research | How, when, and why individuals report wrongdoing; retaliation dynamics | Addresses disclosure mechanisms; does not provide investigation protocol for what is not disclosed | ASF's Revelation dynamics and Resistance dynamics address the conditions around whistleblowing |
| Garbage Can model (Cohen, March, Olsen) | How decisions emerge from streams of problems, solutions, participants, and choice opportunities | Explains apparently irrational decision processes; does not investigate hidden factors systematically | ASF's Decisions framework (G6) addresses the conditions the Garbage Can model describes |
| **[NEW]** Hidden transcripts (Scott) | How subordinate groups maintain private discourse that contradicts public compliance | Powerful concept for understanding power-mediated concealment; specific context | ASF's Positional (Type 21) and Secrets (Type 11) address hidden transcripts within a mechanism taxonomy |
| Stakeholder mapping / salience model (Mitchell, Agle, Wood) | Identifies stakeholders by power, legitimacy, and urgency; reveals who is included/excluded | Maps actors; does not investigate what each actor hides or cannot see | ASF's Agents framework (G3) extends stakeholder mapping with visibility analysis per role |
| Social network analysis | Network structure, centrality, brokerage, structural holes | Reveals structural position; does not address what position hides | ASF's Networks framework (G2) and Positional (Type 21) add visibility analysis to SNA |
| **[NEW]** Power/knowledge analysis (Foucault) | How power and knowledge are co-constituted; discursive regimes produce subjects and objects | Powerful critical lens; descriptive/analytical, not investigative; no operational protocol | ASF's Power framework (G3) and Category V (Relational) incorporate Foucauldian insights operationally |
| Discourse analysis | How language constructs reality, positions, and possibilities | Surfaces hidden assumptions in language; narrow methodological scope | ASF's Narratives and Communications frameworks (G4) address discourse within a multi-framework architecture |
| Frame analysis (Goffman) | How framing structures perception and interpretation | Directly relevant to Framing (Type 8); specific analytical lens | ASF's Framing type and Boundaries framework operationalise frame analysis for investigation |
| **[NEW]** Feminist standpoint theory | How social position (gender, race, class) systematically shapes what can be known | Powerful on positional epistemology; specific critical perspective | ASF's Positional (Type 21) and Perspectival (Type 25) address positional epistemology across all social dimensions |
| **[NEW]** Intersectionality (Crenshaw) | How overlapping social identities create unique visibility/invisibility patterns | Specific to identity-based invisibility; important but narrow | ASF's relational hiddens (Category V) and Perspectives framework address intersectional dynamics |
| Ethnomethodology (Garfinkel) | How social order is produced through everyday practices; taken-for-granted background | Surfaces invisible social practices; specific research tradition | ASF's Culture and Norms framework (G4) addresses the taken-for-granted within an investigation protocol |
| Ethnography / participant observation | Deep contextual understanding through immersion; surfaces tacit knowledge and practices | Powerful for tacit knowledge; time-intensive; no mechanism taxonomy; researcher-dependent | ASF can incorporate ethnographic findings; provides the mechanism framework ethnography does not |
| **[NEW]** Institutional ethnography (Dorothy Smith) | How ruling relations and institutional texts organise experience; disjuncture between lived experience and official accounts | Powerful for institutional hiddenness; specific feminist sociological method | ASF's Institutions framework (G2) and Distortion (Type 6) address what IE surfaces |
| Grounded theory (Glaser, Strauss) | Theory building from data; constant comparison; emergent categories | Research methodology, not investigation protocol; no mechanism taxonomy | ASF provides the structured analytical framework that grounded theory's open-ended approach does not |
| Tacit knowledge elicitation | Surfacing knowledge that practitioners hold but cannot articulate | Specific technique; addresses Ineffable (Type 30) territory | ASF's Ineffable (Type 30) and Knowledge framework (G5) provide the classification |
| **[NEW]** Community of practice analysis (Wenger) | How knowledge is held and shared within practice communities; boundaries between communities | Identifies knowledge boundaries; does not investigate hiding mechanisms | ASF's Fragmentation (Type 14) and Knowledge framework (G5) address CoP-relevant hiddenness |
| Appreciative inquiry | Surfacing strengths and positive deviance; what works and why | Complement to deficit-focused analysis; does not investigate hidden failures | ASF's balanced approach (forward and backward use) can incorporate AI's generative perspective |

---

## 4. Manufactured Ignorance, Deception, and Information Warfare

These approaches address how ignorance is deliberately produced, information is weaponised, and deception is practiced. They are strongest on *adversarial* hiddenness (ASF agency dimension: Deliberate/Adversarial) but typically do not address accidental, systemic, or ontological hiddenness.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Agnotology (Proctor) | Culturally produced ignorance; manufactured doubt; corporate science manipulation | Strong on deliberate ignorance production; weaker on structural and ontological hiddenness | ASF's Category III (Informational) addresses agnotological territory; Categories I, II, IV, V, VI extend beyond deliberate manufacture |
| Strategic ignorance | Deliberate choice not to know; plausible deniability; strategic ambiguity | Specific mechanism; narrow scope | ASF's Secrets (Type 11) and Shadows (Type 16) address strategic ignorance with dimensional profiling |
| Wilful blindness (Heffernan) | Choosing not to see what is available to be seen; organisational and individual | Powerful concept; no systematic investigation protocol | ASF's Shadows (Type 16) and agency dimension operationalise wilful blindness for investigation |
| Misinformation / disinformation analysis | False information (accidental) and deliberately false information; spread mechanisms | Strong on information quality; narrower scope than full hiddenness investigation | ASF's Hallucination (Type 2), Echoes (Type 12), Noise (Type 13) address mis/disinformation within a comprehensive taxonomy |
| Propaganda analysis | How persuasion and influence operations work; techniques and countermeasures | Specific to deliberate influence; does not address structural or temporal hiddenness | ASF's Narratives framework (G4) and Category III (Informational) address propaganda as one of many hiding mechanisms |
| Denialism studies | Motivated rejection of established evidence (climate, health, etc.) | Explains denial; does not provide multi-mechanism investigation protocol | ASF's Beliefs framework (G5) and Paradigm Boundary (Type 28) address denial within a larger epistemics framework |
| Secrecy studies (Simmel, etc.) | Social functions of secrecy; how secrets structure relationships | Sociological analysis of secrecy; not an investigation protocol | ASF's Secrets (Type 11) and interaction mapping operationalise secrecy analysis |
| **[NEW]** Information laundering analysis | How dubious information is passed through credibility-lending intermediaries | Specific mechanism; narrow | ASF's Echoes (Type 12) and provenance requirements address the mechanism |
| Intelligence failure analysis (Jervis, Wohlstetter) | Why intelligence agencies miss critical signals; signal vs noise; mirror imaging | Strong on intelligence-specific failures; domain-specific; no comprehensive mechanism taxonomy | ASF's entire architecture addresses what intelligence failure analysis identifies but at domain-general scale |
| Counterintelligence analysis | Detecting and countering adversarial intelligence operations | Adversarial focus; highly domain-specific | ASF's adversarial agency dimension and Category III address the relevant mechanisms |
| Deception detection frameworks | Indicators and methods for detecting deliberate deception | Specific to deliberate deception; no broader mechanism taxonomy | ASF's Secrets (Type 11) and Resistance dynamics address deception within a comprehensive framework |
| Analysis of competing hypotheses (ACH — Heuer) | Matrix-based evaluation of evidence against hypotheses; identifies diagnosticity | Strong on evidence-hypothesis evaluation; does not investigate what evidence is hidden | ASF complements ACH by investigating why evidence is unavailable, not just what available evidence supports |
| **[NEW]** Structured analytic techniques (Richards Heuer, Pherson) | Full catalogue of intelligence analysis techniques for overcoming cognitive biases | Comprehensive technique catalogue; individual techniques, not integrated investigation methodology | ASF provides the integrated methodology and mechanism taxonomy that SATs lack; many SATs can be used within ASF execution |
| **[NEW]** Indicators and warnings analysis | Pre-defined indicators of threatening developments; monitoring for weak signals | Specific intelligence function; requires pre-specification of what to watch for | ASF's Tier 1 scan performs a comparable function without requiring pre-specification |
| **[NEW]** Denial and deception (D&D) analysis | How adversaries hide capabilities and intentions; indicators of D&D | Highly specialised adversarial focus; domain-specific | ASF's Resistance dynamics and adversarial agency dimension generalise D&D analysis |

---

## 5. Safety, Accidents, and Failure Investigation

These approaches investigate how failures occur, what latent conditions contribute, and why defences fail. They are the closest existing analogues to the ASF for post-failure investigation but typically do not provide a comprehensive mechanism taxonomy that extends beyond safety/accidents to social and political hiddenness, and most are primarily retrospective.

### 5.1 Accident Models and Causation Theories

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Swiss Cheese Model (Reason) | Layered defences; active failures + latent conditions; organisational accident | Foundational; layer metaphor is one-dimensional; does not address what *hides* latent conditions from view | ASF asks what Reason's model does not: what mechanisms prevented seeing the holes before alignment? |
| Normal Accident Theory (Perrow) | Interactive complexity + tight coupling → inevitable accidents; system accidents | Explains why some systems are inherently accident-prone; fatalistic framing limits action orientation | ASF's Systems framework (G2) and Emergent Invisibility (Type 23) operationalise Perrow's insights for investigation |
| High Reliability Organisation theory (Weick, Roberts, La Porte) | How some organisations achieve high reliability: preoccupation with failure, deference to expertise, etc. | Explains success conditions; less useful for investigating specific failures; prescriptive | ASF investigates specific visibility failures; HRO principles inform what remediation should target |
| STAMP (Leveson) | Systems-theoretic accident model; control structure; safety constraints and their enforcement | Strong systems perspective; primarily safety-focused; no mechanism taxonomy for social/political/temporal hiddenness | ASF's G2 (Mechanism) group addresses STAMP territory; extends to G3, G4, G5, G6 for non-technical hiding mechanisms |
| CAST (Leveson) | Causal Analysis using Systems Theory; STAMP-based investigation method | Systematic; safety-focused; does not address what hides the control failures from the organisation | ASF investigates the meta-question: what prevented the organisation from seeing the control failures? |
| AcciMap (Rasmussen, Svedung) | Multi-level accident mapping from government to work; migration to boundaries | Strong multi-level view; primarily retrospective; no comprehensive mechanism taxonomy | ASF's multi-group architecture (G1–G6) provides a comparable multi-level view with mechanism classification |
| FRAM (Hollnagel) | Functional resonance; how everyday performance variability combines to produce unexpected outcomes | Powerful on variability and coupling; does not provide mechanism taxonomy for visibility failures | ASF incorporates FRAM-like insights via Emergence framework; adds visibility governance |
| **[NEW]** Drift into failure (Dekker) | Gradual, incremental normalisation of risk; system migration without awareness | Explains temporal dynamics of failure development; not a comprehensive investigation protocol | ASF's Habituation (Type 5), Ghost (Type 17), and evolution dynamics directly address drift |
| **[NEW]** Work-as-imagined vs work-as-done (Hollnagel) | Gap between prescribed procedures and actual practice | Powerful diagnostic concept; single mechanism | ASF's Distortion (Type 6) and Processes framework (G2) address this gap within a comprehensive taxonomy |
| **[NEW]** Safety-II (Hollnagel) | Studying what goes right, not just what goes wrong; everyday performance adjustment | Reframes safety; does not investigate hidden factors in specific incidents | ASF addresses both forward (proactive) and backward (post-failure) investigation |
| **[NEW]** Just Culture (Dekker, Marx) | Balanced approach to accountability; creating conditions for reporting | Conditions for disclosure; does not investigate what remains hidden | ASF investigates what remains hidden even under Just Culture conditions |

### 5.2 Specific Investigation and Analysis Methods

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Bow-tie analysis | Threats, barriers, consequences; barrier effectiveness | Visual; barrier-focused; does not investigate what hides barrier degradation | ASF's multi-mechanism approach addresses what bow-tie assumes: that barriers are visible |
| Fault tree analysis / Event tree analysis | Logical combinations of failures leading to top events; probability propagation | Quantitative; requires pre-specification of failure modes; misses unspecified modes | ASF's Unknown Unknown (Type 26) and Category Absence (Type 29) address what fault trees cannot represent |
| Barrier analysis | Identification and assessment of safety barriers and their degradation | Specific safety technique; does not address why barriers degrade invisibly | ASF addresses the meta-question of barrier visibility |
| Change analysis | Comparison of actual conditions with baseline to identify what changed | Simple and effective; does not address hidden changes or gradual drift | ASF's Ghost (Type 17) and temporal dynamics address changes hidden by time and habituation |
| Five Whys | Iterative "why" questioning to reach root causes | Simple; risks premature stopping; linear causation assumption; no mechanism taxonomy | ASF's Causation framework (G2) provides a far richer causal investigation methodology |
| Ishikawa / fishbone diagram | Categorised brainstorming of potential causes | Useful for brainstorming; no mechanism taxonomy; no detection/remediation protocol | ASF's structured taxonomy replaces ad hoc brainstorming with systematic traversal |
| STPA (System-Theoretic Process Analysis) | Systematic identification of unsafe control actions and causal scenarios | Rigorous; safety-specific; does not address social/political/epistemic hiddenness | ASF extends STPA's systems orientation to the full social-sociotechnical-technical space |
| HAZOP | Systematic examination of process deviations using guide words | Powerful for process industries; specific to designed systems; does not address social/organisational hiddenness | ASF addresses what HAZOP cannot: the social and institutional conditions that allow deviations to persist unseen |
| FMEA / FMECA | Systematic identification and prioritisation of failure modes and effects | Comprehensive within scope; requires pre-specification of components and failure modes; misses emergent failures | ASF's Emergent Invisibility (Type 23) and Unknown Unknown (Type 26) address what FMEA cannot pre-specify |
| HFACS (Human Factors Analysis and Classification System) | Categorised human factors contributing to accidents; organisational influences | Strong on human factors categories; safety-specific; no mechanism taxonomy for non-human hiding mechanisms | ASF's G3 (Agency) group provides a more comprehensive treatment of human factors within a multi-mechanism framework |
| Human factors analysis | Cognitive, physical, and organisational factors affecting human performance | Broad discipline; no unified mechanism taxonomy for hiddenness | ASF's Cognition framework (G3) and Category I (Perceptual) address human factors within a visibility framework |
| **[NEW]** London Protocol (Vincent, Taylor-Adams) | Structured investigation of patient safety incidents; contributory factor framework | Healthcare-specific investigation protocol; no comprehensive mechanism taxonomy | ASF provides domain-general investigation protocol that subsumes the London Protocol's contributory factor logic |
| **[NEW]** Yorkshire Contributory Factors Framework | Taxonomy of contributory factors in patient safety; extends Reason's model | Healthcare-specific; categorises contributory factors; no mechanism taxonomy for hiddenness per se | ASF provides the visibility layer: not just what contributed, but what prevented seeing the contributors |
| **[NEW]** TapRooT investigation method | Structured root cause analysis with corrective action identification | Commercial investigation methodology; no mechanism taxonomy for hiddenness | ASF provides the visibility governance layer that TapRooT's root cause approach does not |
| **[NEW]** Cognitive systems engineering (Rasmussen, Vicente) | Work domain analysis; abstraction hierarchy; ecological interface design | Strong on cognitive work analysis; design-oriented rather than investigation-oriented | ASF's Cognition framework draws on CSE insights; adds investigation protocol |
| **[NEW]** CREAM (Cognitive Reliability and Error Analysis Method) | Classification of human error and cognitive function failures | Specific to human error; no broader mechanism taxonomy | ASF's Cognition framework (G3) provides broader coverage |

---

## 6. Security, Threat, and Adversarial Discovery

These approaches address how adversaries exploit systems and how defenders discover attacks, vulnerabilities, and threat paths. They are strongest on *deliberate, adversarial* hiddenness in technical and security domains but do not address accidental, systemic, or social hiding mechanisms.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Threat modelling (STRIDE, PASTA, etc.) | Systematic identification of threats to systems and assets | Adversarial focus; technical systems; does not address social or organisational hiddenness | ASF's G2 (Mechanism) and adversarial agency dimension address threat modelling within a broader framework |
| Attack trees / Kill chain / MITRE ATT&CK | Structured representation of adversary actions and attack paths | Powerful adversarial models; do not address non-adversarial hiddenness | ASF positions these as tools for the Adversarial end of the agency dimension |
| Red teaming / Purple teaming | Adversarial testing of defences; collaborative defence assessment | Valuable challenge method; scope limited to adversarial scenarios | ASF's agency dimension ranges from Natural to Adversarial; red teaming addresses only the adversarial end |
| Penetration testing / Vulnerability research | Discovery of exploitable weaknesses through active probing | Technical focus; specific system scope; does not address social/organisational hiddenness | ASF's Detection Interface (Type A) generalises the penetration testing approach across all hiding mechanism types |
| Threat hunting / Hunt hypotheses | Proactive search for adversary presence using hypotheses and indicators | Proactive and hypothesis-driven; specific to cybersecurity | ASF's Hypothesis/Test Backlog and discriminating tests generalise hunt methodology across domains |
| OSINT investigation / Link analysis | Open source intelligence gathering; relationship mapping | Specific intelligence techniques; not a comprehensive investigation methodology | Can be used as evidence-gathering techniques within ASF execution |
| Digital forensics / Malware reverse engineering | Post-incident technical evidence recovery and analysis | Highly technical; specific domain; not a broader investigation methodology | ASF provides the broader investigative context within which forensic findings are interpreted |
| **[NEW]** Insider threat analysis | Detection of malicious or negligent insider behaviour | Specific security domain; adversarial/negligent focus | ASF's Secrets (Type 11) and agency dimension address insider threats within a comprehensive framework |
| **[NEW]** Zero trust architecture | Assume compromise; verify explicitly; least privilege | Design philosophy, not investigation methodology | ASF's epistemological assumption — assume hiddens exist — is conceptually parallel |
| **[NEW]** Detection engineering gap analysis | Systematic assessment of gaps in detection coverage | Specific to security monitoring; technical scope | ASF's Tier 1 scan performs an analogous function across all six meta-categories, not just technical detection |
| **[NEW]** Adversarial machine learning | How ML models can be attacked through adversarial examples, data poisoning, model inversion | Specific to ML systems; technical | ASF's Technology framework (G2) and Distortion (Type 6) address this within a broader taxonomy |

---

## 7. Data, Modelling, and Hidden-Pattern Discovery

These approaches use quantitative and computational methods to discover hidden patterns, latent variables, anomalies, and causal structures in data. They are powerful when data exists and is accessible, but typically do not address the conditions that prevent data from being collected, the mechanisms that distort data before it reaches the analyst, or the social and political dynamics that suppress evidence.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Exploratory data analysis (Tukey) | Data structure, distributions, outliers, unexpected patterns | Requires data to exist and be accessible; does not address hidden data or distorted data generation | ASF investigates the conditions upstream of EDA: why data is missing, distorted, or inaccessible |
| Process mining / Conformance checking | Actual process flows vs designed processes; process deviations | Powerful when event logs exist; does not address why deviations occur or are hidden | ASF's Processes framework (G2) and Distortion (Type 6) address process hiddenness |
| Latent variable modelling / Factor analysis | Hidden dimensions underlying observed correlations | Statistical; assumes latent variables are stable and linear; model assumptions create blind spots | ASF's Model Blindness (Type 10) addresses what latent variable models systematically exclude |
| Causal discovery (Bayesian networks, etc.) | Causal structure from observational data | Powerful when assumptions hold; confounded by hidden variables and selection bias | ASF investigates the conditions that prevent causal discovery: hidden confounders, suppressed evidence, paradigm constraints |
| Anomaly detection / Outlier analysis | Unexpected observations that deviate from established patterns | Detects departures from known patterns; cannot detect unknown patterns | ASF's Unknown Unknown (Type 26) addresses what anomaly detection by definition cannot pre-specify |
| **[NEW]** Concept drift detection | When statistical relationships in data change over time | Detects distributional shift; does not investigate why the shift occurred or what it conceals | ASF's temporal dynamics and Projection (Type 19) address the conditions concept drift signals |
| Triangulation / Mixed-methods | Cross-method validation; convergence or divergence across approaches | Powerful validation strategy; does not provide mechanism taxonomy for divergence | ASF's Evidence framework (G5) and systematic triangulation requirements formalise what mixed-methods prescribes |
| Counterfactual analysis | What would have happened under different conditions | Powerful for causal inference; requires model specification; model assumptions create blind spots | ASF's Scenarios framework (G1) and Model Blindness (Type 10) address counterfactual reasoning limitations |
| Bias and fairness audits | Systematic testing for discriminatory patterns in algorithms and data | Important; specific to algorithmic systems; does not address broader hiddenness | ASF's Distortion (Type 6) and Ethics framework (G4) address algorithmic bias within a comprehensive framework |
| **[NEW]** Explainable AI / Interpretability (LIME, SHAP) | Making black-box model decisions interpretable; feature attribution | Specific to ML models; addresses technical Model Blindness | ASF's Model Blindness (Type 10) and Technology framework (G2) address ML opacity within a broader taxonomy |
| **[NEW]** Data lineage / provenance analysis | Tracking data origins, transformations, and quality through pipelines | Important for data integrity; specific to data systems | ASF's Evidence framework (G5) and provenance requirements generalise this to all evidence, not just data |

---

## 8. Futures, Strategy, and Anticipatory Methods

These approaches look forward — scanning for weak signals, constructing alternative futures, and stress-testing strategies against uncertainty. They address *what might be hidden about the future* but typically do not provide a mechanism taxonomy for *why* things are hidden in the present.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Horizon scanning / Environmental scanning | Early detection of emerging issues, trends, and potential disruptions | Scan-oriented; no mechanism taxonomy for why signals are missed; vulnerable to framing effects | ASF's Tier 1 Hiddens scan performs a complementary function with mechanism classification |
| Weak signals analysis (Ansoff) | Early, ambiguous indicators of potential change | Powerful concept; no systematic method for distinguishing genuine weak signals from noise | ASF's Noise (Type 13) and Signal detection address the discrimination problem |
| Scenario planning (Shell, Schwartz) | Multiple plausible futures; challenges dominant assumptions; reveals hidden dependencies | Strong on assumption challenge; does not investigate current hidden factors systematically | ASF's Scenarios framework (G1) integrates scenario planning within a comprehensive investigation |
| Delphi method | Structured expert elicitation; convergence through iterative rounds | Reveals expert consensus/divergence; vulnerable to groupthink and positional effects | ASF's Echoes (Type 12) and Positional (Type 21) address the mechanisms that compromise Delphi |
| Wild cards analysis | Low-probability, high-impact events that are not on the radar | Addresses the most extreme unknowns; no mechanism taxonomy; no systematic detection method | ASF's Unknown Unknown (Type 26) and Unknowable (Type 27) classify the territory wild cards occupy |
| War gaming / Tabletop exercises | Adversarial simulation; stress-testing plans and responses | Valuable for revealing assumptions; scope limited to scenario design; adversarial focus | ASF's Scenarios framework and red teaming integration extend war gaming within a broader investigation |
| Strategic foresight | Systematic approach to thinking about the future; multiple methods | Meta-discipline; draws on many methods; no mechanism taxonomy for hiddenness | ASF provides the mechanism taxonomy and investigation protocol that foresight methods can draw on |
| **[NEW]** Backcasting | Working backward from a desired future state to identify necessary conditions | Specific planning technique; does not investigate current hidden factors | ASF investigates the current conditions; backcasting identifies future requirements |
| **[NEW]** Cross-impact analysis | How trends and events interact and influence each other | Explores interactions; does not investigate what hides the interactions | ASF's interaction mapping (Interface Type C) provides a more comprehensive interaction analysis |
| **[NEW]** Black swan analysis (Taleb) | Events that are rare, have extreme impact, and are rationalised after the fact | Powerful concept; heuristic rather than systematic; no investigation protocol | ASF's Category VI (Ontological) and Unknown Unknown (Type 26) address black swan territory with operational tools |

---

## 9. Design, User Research, and Hidden-Needs Discovery

These approaches discover what users and stakeholders need but cannot articulate, what contexts reveal through observation but not through questioning, and what design choices make visible or invisible. They address *hidden needs and hidden consequences* but typically operate within a design/innovation frame rather than an analytical investigation frame.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Human-centred design / Design thinking | User needs, pain points, and unmet requirements through empathy and prototyping | Powerful for needs discovery; does not provide mechanism taxonomy for systemic hiddenness | ASF addresses the systemic and structural conditions that design thinking's user focus may miss |
| Service design / Journey mapping / Blueprinting | End-to-end service experience; frontstage/backstage interactions; failure points | Reveals service-level gaps; does not address deeper institutional or temporal hiddenness | ASF's Processes framework (G2) and multi-group architecture extend service design to structural investigation |
| Contextual inquiry / User shadowing | In-context observation of actual practice; surfaces tacit knowledge and workarounds | Powerful for practice discovery; resource-intensive; observer effects | ASF's Positional (Type 21) addresses observer effects; Ineffable (Type 30) addresses tacit knowledge limits |
| Jobs to Be Done (Christensen) | Functional, social, and emotional jobs users are "hiring" products to do; unmet jobs | Powerful reframing; product/innovation scope; does not address systemic hiddenness | ASF's multi-group architecture extends JTBD logic to analytical investigation |
| Value-sensitive design (Friedman) | How values are embedded in and affected by technology design | Important for ethical design; does not provide comprehensive investigation methodology | ASF's Ethics framework (G4) and Values framework (G4) address value-related hiddenness |
| **[NEW]** Speculative design / Design fiction | Provoking reflection through designed artefacts from possible futures | Generative and provocative; not systematic investigation | ASF's Scenarios framework (G1) provides the systematic investigation counterpart |
| **[NEW]** Participatory design / Co-design | Including users in the design process; surfacing diverse perspectives | Powerful for inclusion; does not address systemic or structural hiddenness beyond participant experience | ASF's multi-group, multi-framework architecture extends beyond participant perspectives |
| **[NEW]** Responsible innovation | Anticipation, reflexivity, inclusion, and responsiveness in innovation processes | Meta-framework for responsible practice; not an investigation methodology | ASF provides the investigation methodology that responsible innovation needs as input |

---

## 10. Governance, Assurance, and Institutional Controls

These approaches establish and evaluate controls, oversight mechanisms, and governance structures designed to prevent failures and detect problems. They address *whether controls are working* but typically do not investigate *what hides control failures from the organisation*.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Internal control frameworks (COSO, COBIT) | Control environment, risk assessment, control activities, monitoring | Whether controls exist and are documented; not whether they actually work or what hides their failure | ASF investigates the meta-question: what mechanisms prevent the organisation from seeing that controls are failing? |
| Three lines model | Role clarity for risk management: management, risk/compliance, internal audit | Structural accountability; does not address what hides across the three lines | ASF's Fragmentation (Type 14) and Positional (Type 21) address inter-line visibility failures |
| Audit and assurance | Independent examination and opinion on stated assertions | Tests assertions; scope determined by audit plan; does not systematically investigate what is outside scope | ASF's Framing (Type 8) and Model Blindness (Type 10) address what audit scoping systematically excludes |
| Control self-assessment | Self-evaluation of control effectiveness by control operators | Useful engagement tool; vulnerable to self-interest and blind spots | ASF's Distortion (Type 6) and agency dimension address why self-assessment systematically fails |
| Maturity models / CMM | Progressive capability assessment against defined levels | Measures maturity; does not investigate what hides immaturity from the organisation | ASF investigates the visibility conditions that maturity models assume but do not test |
| Model risk management (SR 11-7) | Governance of models: validation, limitations, appropriate use | Specific to model risk; does not address non-model sources of hiddenness | ASF's Model Blindness (Type 10) and Metrics framework (G5) extend model risk management to all analytical instruments |
| Safety case / Assurance case | Structured argument that a system is acceptably safe/assured | Argument-based assurance; assumes the evidence base is adequate | ASF investigates whether the evidence base is adequate and what mechanisms might compromise it |
| **[NEW]** Independent validation and verification (IV&V) | Third-party assessment of system correctness and completeness | Provides independence; scope limited to what can be specified and tested | ASF's Unknown Unknown (Type 26) addresses what IV&V cannot pre-specify |
| **[NEW]** Regulatory impact assessment | Systematic analysis of likely effects of proposed regulation | Prospective analysis; model-dependent; assumes certain causal pathways | ASF's Model Blindness (Type 10) and Framing (Type 8) address the hidden assumptions in impact assessment |
| **[NEW]** Environmental / Social impact assessment | Systematic analysis of environmental and social effects of proposed actions | Valuable but scope-dependent; boundary choices determine what is visible | ASF's Boundaries framework (G1) and Framing (Type 8) address what impact assessment scoping hides |

---

## 11. Engineering, Operations, and Technical Discovery

These approaches discover hidden defects, dependencies, drift, and failure modes in technical systems through probing, monitoring, analysis, and systematic testing.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Observability engineering | Internal system state inference from external outputs (logs, metrics, traces) | Powerful for instrumented systems; only sees what is instrumented; does not address social/organisational hiddenness | ASF's Blindspot (Type 1) and Technology framework address the limits of observability |
| Chaos engineering (Netflix Simian Army, etc.) | How systems behave under controlled disruption; hidden failure modes and dependencies | Powerful for resilience testing; technical systems only; does not address social or institutional hiddenness | ASF's Detection Interface (Type A) generalises chaos engineering's probe logic across all domains |
| Site reliability engineering / Post-incident review | Operational reliability; structured incident learning | Strong operational practice; does not provide comprehensive mechanism taxonomy for hiddenness | ASF provides the mechanism taxonomy and multi-group architecture that SRE incident reviews lack |
| Stress testing | System behaviour under extreme conditions; breaking points | Reveals fragility; only tests what is specified; does not address unspecified failure modes | ASF's Unknown Unknown (Type 26) addresses what stress tests cannot pre-specify |
| Static analysis / Dynamic analysis / Formal methods | Code-level defect detection; runtime behaviour analysis; mathematical proof of properties | Powerful within scope; does not address requirements errors, environmental dependencies, or social context | ASF investigates the conditions upstream and around technical analysis: requirements, context, organisational pressures |
| Dependency mapping / Architecture review | System structure, dependencies, interfaces, coupling | Reveals technical structure; does not address hidden dependencies or social/institutional coupling | ASF's Systems, Relations, and Networks frameworks extend dependency mapping to sociotechnical systems |
| Configuration drift analysis / Technical debt analysis | How systems diverge from intended state over time; accumulated design compromises | Detects drift in technical systems; does not address institutional or social drift | ASF's Ghost (Type 17), Habituation (Type 5), and temporal dynamics address drift across all system types |
| Reverse engineering / Protocol analysis | Recovering design intent and behaviour from artefacts; understanding undocumented interfaces | Specific technical method; does not address social or institutional hiddenness | Can be used as evidence-gathering technique within ASF execution |
| **[NEW]** Exploratory testing | Unscripted, adaptive testing guided by tester expertise and intuition | Powerful for finding unexpected defects; depends on tester skill; no mechanism taxonomy | ASF's Detection Interface (Type A) provides the structured version of exploratory testing's intuitive approach |
| **[NEW]** Failure injection / Fault injection | Deliberately introducing failures to test system resilience and response | Proactive resilience testing; technical scope | ASF's Detection Interface generalises this across domains; the Hypothesis/Test Backlog systematises the injection logic |
| **[NEW]** Design of experiments (DoE) | Systematic variation of factors to identify causal relationships | Powerful when variables are known and controllable; does not address unknown factors | ASF's Unknown Unknown (Type 26) and Category Absence (Type 29) address what DoE cannot pre-specify |

---

## 12. Evaluation, Policy, and Programme Assessment

**[NEW CLUSTER]** These approaches assess whether interventions, policies, and programmes work as intended, surface unintended consequences, and evaluate causal claims under real-world conditions. They address *what is hidden about whether something worked and why* but typically do not provide a comprehensive mechanism taxonomy.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| **[NEW]** Realist evaluation (Pawson, Tilley) | What works, for whom, in what circumstances, and why; context-mechanism-outcome configurations | Strong on causal mechanism identification in context; specific to programme evaluation; no hiddenness taxonomy | ASF extends realist evaluation's mechanism logic to visibility failures specifically |
| **[NEW]** Theory of change | Articulated causal pathway from activities to outcomes; assumptions and preconditions | Makes causal assumptions explicit; does not systematically investigate what is hidden | ASF's Assumptions Register and Hiddens cross-check provide the systematic investigation ToC lacks |
| **[NEW]** Contribution analysis (Mayne) | Assesses whether and how an intervention contributed to observed outcomes | Addresses attribution under complexity; does not investigate hidden confounders systematically | ASF's multi-framework architecture investigates the hidden factors that contribution analysis assumes can be identified |
| **[NEW]** Process tracing (Beach, Pedersen) | Causal mechanism tracing within individual cases; evidence tests for causal claims | Strong on within-case causal inference; single-case focus; no mechanism taxonomy for hiddenness | ASF's Causation framework (G2) draws on process tracing logic; adds visibility governance |
| **[NEW]** Qualitative Comparative Analysis (QCA — Ragin) | Identifies necessary and sufficient conditions across cases using set-theoretic logic | Powerful for cross-case causal analysis; requires case knowledge; does not investigate hidden conditions | ASF investigates the hidden conditions that QCA's case knowledge may miss |
| **[NEW]** Developmental evaluation (Patton) | Evaluation under complexity and emergence; real-time feedback for adaptive programmes | Strong on evaluation under uncertainty; does not provide mechanism taxonomy for hiddenness | ASF provides the mechanism framework that developmental evaluation needs for visibility governance |
| **[NEW]** Most significant change (Davies, Dart) | Participatory selection of stories of change; surfaces unexpected and valued outcomes | Surfaces stakeholder perspectives; selection process introduces its own biases | ASF's Positional (Type 21) and Perspectival (Type 25) address whose changes are seen and whose are hidden |

---

## 13. Knowledge Elicitation, Learning, and Blind-Spot Surfacing

These approaches extract, map, and challenge what is known, believed, assumed, and taken for granted. They address *what is in people's heads but not visible to the organisation* — primarily tacit knowledge, mental models, and unexamined assumptions.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| Knowledge management / Knowledge mapping | Where knowledge resides; knowledge gaps; knowledge flows | Maps knowledge assets; does not investigate hiding mechanisms | ASF's Knowledge framework (G5) extends KM to visibility governance |
| Concept mapping / Cognitive mapping | Visual representation of concepts and their relationships; mental models | Surfaces individual mental models; does not address systemic or institutional hiddenness | ASF provides the multi-level investigation framework that cognitive mapping contributes to |
| Cognitive task analysis | Detailed analysis of expert cognitive processes in complex tasks | Powerful for task-level cognition; does not address institutional or systemic hiddenness | ASF's Cognition framework (G3) extends CTA to organisational and multi-actor contexts |
| Expert elicitation | Structured extraction of expert judgement and uncertainty | Extracts expert knowledge; vulnerable to expert biases and blind spots | ASF's Habituation (Type 5), Model Blindness (Type 10), and expert-failure dynamics address what expert elicitation misses |
| Repertory grid technique (Kelly) | Surfaces personal constructs used to interpret experience; reveals hidden distinctions and similarities | Powerful for individual meaning-making; narrow scope | ASF's Perspectives framework (G4) addresses the organisational and systemic level |
| Critical incident technique (Flanagan) | Systematic collection of significant events; surfaces hidden patterns in practice | Valuable data collection method; depends on participant recall and disclosure | ASF's Shadows (Type 16) and Amnesia (Type 18) address the conditions that compromise critical incident recall |
| Argument mapping / Issue mapping / Assumption mapping | Visual representation of reasoning structure; surfaces hidden premises and contestable claims | Useful analytical tools; single-technique focus; no mechanism taxonomy | ASF integrates these as analytical tools within a comprehensive investigation architecture |
| **[NEW]** Double-crux style disagreement mapping | Identifying the specific belief differences that drive disagreements; finding crux beliefs | Powerful for productive disagreement; interpersonal scope | ASF's PD-04 (track disagreement) and Perspectives framework provide the institutional-level equivalent |
| **[NEW]** Structured brainstorming / Outside-in thinking | Systematic generation of alternative perspectives and possibilities | Generative; no mechanism taxonomy; no detection/remediation protocol | ASF provides the structured alternative to brainstorming: systematic traversal of hiding mechanisms |
| **[NEW]** Peer assist | Structured knowledge sharing between teams before a project begins | Useful practice; does not investigate what remains hidden after sharing | ASF investigates the residual hiddenness that peer assist cannot reach |

---

## 14. Legal, Regulatory, and Forensic Investigation

**[NEW CLUSTER]** These approaches discover hidden facts, concealed conduct, and suppressed evidence through formal investigation processes governed by legal and regulatory frameworks.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| **[NEW]** Legal discovery / Disclosure | Compelled production of relevant documents and information | Powerful coercive mechanism; scope defined by legal relevance; does not address what is not known to exist | ASF investigates what to request and why; legal discovery provides the mechanism for compelled production |
| **[NEW]** Forensic accounting / Financial statement analysis | Hidden financial irregularities, fraud, and misstatement | Specific to financial concealment; highly technical; narrow domain | ASF's Secrets (Type 11), Distortion (Type 6), and Metrics framework address financial concealment within a comprehensive framework |
| **[NEW]** Benford's law analysis | Detecting anomalies in numerical data by comparing digit distributions to expected patterns | Specific statistical technique; narrow application | Can be used as a detection technique within ASF's Evidence framework |
| **[NEW]** Due diligence investigation | Systematic investigation of a target's assets, liabilities, risks, and hidden exposures | Comprehensive within scope; scope is commercially defined; no mechanism taxonomy | ASF provides the mechanism framework and visibility governance that due diligence can draw on |
| **[NEW]** Whistleblower protection frameworks | Legal and institutional protections for disclosure of wrongdoing | Enables disclosure; does not investigate what remains hidden | ASF's Revelation dynamics and Resistance dynamics address the conditions around whistleblowing |
| **[NEW]** Freedom of information / Transparency legislation | Compelled disclosure of government-held information | Powerful for public sector; does not address what is not known to exist | ASF investigates what to request; FOI provides the mechanism for access |
| **[NEW]** Chain of custody / Evidence integrity | Maintaining and verifying evidence integrity through investigation | Essential forensic discipline; does not address what evidence is missing or distorted | ASF's Evidence framework (G5) addresses evidence integrity within a broader investigation of hidden and distorted evidence |

---

## 15. Operations, Manufacturing, and Continuous Improvement

**[NEW CLUSTER]** These approaches surface hidden problems, waste, and deviations in operational and manufacturing settings through direct observation, standardisation, and systematic problem-solving.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| **[NEW]** Gemba walks | Direct observation of work at the place where value is created | Powerful for surface-level practice discovery; depends on observer capability and access | ASF's Positional (Type 21) and contextual inquiry principles extend gemba walks to visibility analysis |
| **[NEW]** Visual management / Andon systems | Making work status, problems, and abnormalities visible through signals and displays | Makes specific states visible; design choices determine what is visible and what is not | ASF investigates the design choices that determine what visual management shows and hides |
| **[NEW]** Poka-yoke (error-proofing) | Preventing errors through design that makes mistakes impossible or immediately visible | Specific technique; addresses known error modes; does not address unknown error modes | ASF's Unknown Unknown (Type 26) addresses what poka-yoke cannot pre-specify |
| **[NEW]** Statistical process control / Control charts | Monitoring process stability; detecting special-cause variation | Powerful for variation detection; only detects what is measured; does not address measurement distortion | ASF's Distortion (Type 6) and Metrics framework address measurement system failures |
| **[NEW]** Value stream mapping | End-to-end value flow; waste identification; lead time analysis | Reveals process waste; scope defined by value stream boundaries; does not address what boundary choices hide | ASF's Boundaries framework (G1) and Framing (Type 8) address what value stream scoping excludes |
| **[NEW]** Theory of Constraints / Current Reality Tree (Goldratt) | System constraint identification; causal logic for undesirable effects | Strong on constraint identification; does not address why constraints are hidden from the organisation | ASF investigates the meta-question: what prevents the organisation from seeing its constraints? |
| **[NEW]** A3 problem solving (Toyota) | Structured problem-solving on a single page; root cause and countermeasure | Disciplined practice; no mechanism taxonomy; limited to what the solver can see | ASF provides the mechanism vocabulary and multi-framework architecture that A3 thinking can draw on |

---

## 16. Medical, Clinical, and Health Systems Investigation

**[NEW CLUSTER]** These approaches discover hidden clinical failures, diagnostic errors, and patient safety hazards.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| **[NEW]** Morbidity and mortality conferences | Peer review of adverse outcomes; case-based learning | Valuable learning forums; vulnerable to hierarchy, blame, and selection bias | ASF's Positional (Type 21) and anti-theatre rule address the dynamics that compromise M&M conferences |
| **[NEW]** Sentinel event analysis | Investigation of unexpected events resulting in death or serious harm | Specific triggering mechanism; does not investigate what hides the latent conditions before the sentinel event | ASF investigates the meta-question that sentinel event analysis assumes: what prevented earlier detection? |
| **[NEW]** Near-miss reporting systems | Collection and analysis of events that could have resulted in harm | Powerful leading indicators; dependent on reporting culture and definitions | ASF's Secrets (Type 11), Organisational Silence, and Communications framework address reporting failures |
| **[NEW]** Diagnostic error analysis | Investigation of failures in clinical diagnosis; cognitive and system factors | Specific to diagnosis; strong on cognitive and system errors | ASF's Diagnosis framework (G5) addresses diagnostic error within a comprehensive visibility framework |
| **[NEW]** Clinical audit / Significant event analysis | Systematic review of clinical practice against standards; investigation of significant events | Valuable quality assurance; scope limited to measurable standards | ASF investigates what standards-based audit systematically misses |

---

## 17. Financial, Economic, and Market Investigation

**[NEW CLUSTER]** These approaches discover hidden risks, systemic vulnerabilities, and concealed exposures in financial systems.

| Approach | What it surfaces | What it characteristically misses | ASF relationship |
|---|---|---|---|
| **[NEW]** Financial stress testing (Basel, Dodd-Frank) | System resilience under adverse scenarios; capital adequacy; hidden exposures | Tests specified scenarios; does not address unspecified scenarios or hidden correlations | ASF's Unknown Unknown (Type 26) and Emergent Invisibility (Type 23) address what stress tests cannot pre-specify |
| **[NEW]** Systemic risk analysis | Interconnection, contagion, and cascade risk across financial institutions | Strong on system-level risk; model-dependent; does not address non-financial hiding mechanisms | ASF's Systems framework (G2) and cascade dynamics extend systemic risk analysis to sociotechnical systems |
| **[NEW]** Value at Risk / Expected Shortfall | Quantified loss estimates under specified confidence levels | Formal; assumes distributional knowledge; silent on model assumptions and tail dependencies | ASF's Model Blindness (Type 10) and Unknowable (Type 27) address what VaR systematically excludes |
| **[NEW]** Shadow economy / Hidden economy measurement | Estimating economic activity not captured in official statistics | Addresses specific informational hiddenness; narrow economic scope | ASF's Distortion (Type 6) and Aggregation (Type 9) generalise the hidden-economy measurement problem |
| **[NEW]** Anti-money laundering investigation | Detection of concealed financial flows and beneficial ownership | Specific financial concealment; adversarial | ASF's Secrets (Type 11) and adversarial agency dimension address AML-relevant hiding mechanisms |

---

## Synthesis: What No Existing Approach Provides

This survey demonstrates that existing approaches are both numerous and valuable. Collectively, they cover enormous ground. Yet each approach — and even each cluster — characteristically addresses some hiding mechanisms while leaving others systematically outside its scope:

**Epistemic framing approaches** (Cluster 1) classify knowledge states but do not provide mechanisms for changing visibility conditions or operational investigation protocols.

**Systems and complexity approaches** (Cluster 2) explain how structures produce unintuitive behaviour but do not provide mechanism taxonomies for what is hidden or detection/remediation protocols.

**Agency and social dynamics approaches** (Cluster 3) identify who hides and why but do not address systemic, temporal, or ontological hiddenness.

**Manufactured ignorance approaches** (Cluster 4) address adversarial information manipulation but not accidental, structural, or ontological hiding mechanisms.

**Safety investigation approaches** (Cluster 5) are the closest analogues to the ASF for post-failure investigation but are primarily retrospective and domain-specific, and do not provide a comprehensive mechanism taxonomy extending to social and political hiddenness.

**Security approaches** (Cluster 6) address adversarial technical threats but not social, organisational, or temporal hiddenness.

**Data and modelling approaches** (Cluster 7) discover hidden patterns in data that exists but do not address why data is missing, distorted, or inaccessible.

**Futures approaches** (Cluster 8) scan for emerging issues but do not systematically investigate current hidden factors.

**Design approaches** (Cluster 9) discover hidden needs but operate within a design/innovation frame rather than an investigation frame.

**Governance approaches** (Cluster 10) evaluate whether controls exist but do not systematically investigate what hides control failures.

**Engineering approaches** (Cluster 11) discover technical defects and drift but do not address social, institutional, or ontological hiddenness.

**Evaluation approaches** (Cluster 12) assess whether interventions work but do not provide a comprehensive mechanism taxonomy for what is hidden about why.

**Knowledge elicitation approaches** (Cluster 13) extract tacit knowledge but do not investigate systemic or structural hiding mechanisms.

**Legal and forensic approaches** (Cluster 14) compel disclosure but do not investigate what is not known to exist.

**Operations approaches** (Cluster 15) make specific problems visible but do not address what design choices themselves hide.

**Clinical investigation approaches** (Cluster 16) investigate patient safety incidents but within domain-specific protocols.

**Financial approaches** (Cluster 17) discover financial risks but within model-dependent, domain-specific frames.

The ASF's claim is that it provides the five missing elements that no existing approach — and no ad hoc combination of existing approaches — delivers as an integrated whole:

1. **A mechanism-based taxonomy** (30 types across 6 meta-categories) that classifies *how* things are hidden, not merely *whether* they are known — covering the full range from perceptual failure through systemic distortion, informational manipulation, temporal legacy, relational blindness, to ontological limits.

2. **A multi-lens coverage model** (6 groups, 50 frameworks, mandatory group coverage before closure) that prevents single-lens closure — the false confidence that comes from thorough analysis through one analytical tradition while remaining blind through others.

3. **A detection and remediation protocol** (iterative loop, tiered Hiddens scans, targeted discovery scans, standard registers, F/I/A/U tagging, discriminating tests) that converts classified hiddens into operational investigation moves.

4. **A reflexive self-application discipline** (mandatory Hiddens cross-check in every framework, meta-validation test) that turns the ASF's own visibility assumptions into objects of investigation.

5. **An LLM-executable design** (3-tier document architecture, LLM-Only Operating Guide, prompt discipline rules, output contract) that makes the methodology scalable, repeatable, and auditable through analyst-LLM collaboration.

Many of the approaches listed above can be used *within* ASF execution — as evidence-gathering techniques, as specific detection methods, as analytical tools applied within particular frameworks. The ASF does not replace these methods; it provides the integrating architecture, mechanism taxonomy, and investigation protocol within which they can be systematically deployed.
