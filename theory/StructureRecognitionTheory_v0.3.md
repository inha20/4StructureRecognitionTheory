# Structure Recognition Theory v0.3

> **Status:** Draft — formal definitional layer under active development.
> All hypotheses remain exploratory propositions, not established conclusions.
> **Supersedes:** StructureRecognitionTheory_v0.2.md

**Version:** 0.3 (draft)
**Date:** 2026-06-06
**Changes from v0.2:**
- Added Section 3: Formal Definitions (structure, attention, explanatory significance) — **primary new contribution**
- Operationalized H4 significance criteria with formal measurement specifications
- H8–H10 elevated from "candidate extensions" to "integrated extension hypotheses"
- Added Section 10: Empirical Research Design Proposals (H1, H5, H6)
- Expanded H4 with formal operationalization table
- Minor clarifications to H7 (connection to formal definition of explanatory significance)

> **Note on v0.3 definitions:**
> The definitions in this version are *working definitions* — precise enough to support empirical operationalization, but explicitly provisional. They are offered as conceptual anchors for the research program, not as final philosophical positions. The goal is to make the theory testable, not to foreclose future revision.

---

## 1. Introduction

Humans encounter vast amounts of information daily, yet most information is ignored. A small subset of phenomena attracts attention, is perceived as structurally meaningful, and eventually develops into research questions. This paper addresses:

> **How do humans come to generate new research questions?**

Structure Recognition Theory (SRT) proposes a conceptual framework for the transition from observation to research question, focusing on:
- Structure discovery and pattern perception
- Meaning attribution and significance evaluation
- Explanatory significance detection
- Question generation and research initiation
- Concept evolution through research
- Human-AI collaborative discovery

---

## 2. Motivation

This project emerged from observations during Karnaugh map research. The initial observation:

```
□ ■ □ ■
■ □ ■ □
□ ■ □ ■
■ □ ■ □
```

Certain Boolean functions produce a checkerboard pattern. The more significant observation was not the pattern itself, but the sequence of events that followed:

1. Pattern recognized immediately as a whole (not cell by cell)
2. Pattern felt "non-random" — as if it should have an explanation
3. Explanation searched for and found (XOR structure)
4. Research question generalized: *why do humans notice this structure at all?*

SRT emerges from following these questions to their source.

---

## 3. Formal Definitions

> **Scope:** These definitions apply within the domain of SRT — the study of how humans come to recognize structures as research-worthy. They are not intended as general definitions of "structure" in mathematics, philosophy, or cognitive science, though connections to those fields are noted where relevant.

The three definitions below are ordered by conceptual dependence: *structure* is defined independently; *attention* is defined in terms of patterns (pre-structural); *explanatory significance* is defined in terms of structure and attention combined.

---

### 3.1 Structure

**Informal statement:**
A structure is a relational configuration that is recognized as a unified whole, persists under certain transformations, and implies the existence of a generative rule.

**Working definition:**

> A **structure** is a relational configuration *C* in a representational space *R* satisfying all four of the following conditions:
>
> 1. **Holistic recognition:** *C* is recognized as a unified entity prior to, and independently of, the complete enumeration of its component elements.
>
> 2. **Non-triviality:** *C* departs from the expected null or random configuration for *R* — it is not what would be predicted by a uniform distribution over *R*.
>
> 3. **Transformational stability:** *C*, or a functionally equivalent configuration *C'*, is preserved under some non-trivial class *T* of transformations of *R*. (A transformation is non-trivial if it changes some surface properties of *R* while leaving *C* intact.)
>
> 4. **Generative implication:** *C* implies the existence of an underlying generative rule *G* such that *|description(G)| < |enumeration(C)|* — the rule is strictly more compact than the enumeration of *C*'s instances.

**Annotation:**

- Condition 1 distinguishes structure from mere data: a structure is an *entity*, not a list. The checkerboard is one thing, not 64 cells.
- Condition 2 provides the epistemic motivation for investigation: a structure is, by definition, something that needs explaining.
- Condition 3 formalizes the intuition that "structure is what survives." A checkerboard on a K-map remains a checkerboard regardless of how cells are read. This condition connects directly to invariance (H4, Papers 1–3).
- Condition 4 connects structure to *explanation*: every structure implies that something compact generated it. This is what makes structures feel like they "demand" explanation.

**Note on representation-dependence:**
A structure exists relative to a representational space *R*. The same underlying mathematical object may exhibit a structure in one representation and not in another. This is the content of H2 (Representation Transformation Hypothesis): choosing the right representation is often a prerequisite for structure to become visible.

**Connection to Concept-as-Lens (H8):**
What counts as "holistically recognized" (Condition 1) depends on what concepts the observer has available. The concept of "Hamming Weight Layer" was required before the ring/corner/point structures of symmetric functions could be recognized as structures (as opposed to arbitrary patterns). This dependence is formalized in H8.

---

### 3.2 Attention (Investigative Attention)

**Informal statement:**
Investigative attention is the process by which a pattern transitions from the perceptual background to become a sustained focus of inquiry — before its structural nature is fully understood.

**Working definition:**

> **Investigative attention** is a selection function *A: P → {0, 1}* mapping observable patterns *P* to attention status, characterized by:
>
> 1. **Selectivity:** Only a small fraction of available patterns receive positive attention: *|{p ∈ P : A(p) = 1}| ≪ |P|*.
>
> 2. **Antecedence:** *A(p) = 1* is assigned before the structural nature of *p* is fully characterized. Attention precedes structural analysis, not the reverse.
>
> 3. **Persistence:** *A(p) = 1* implies sustained investigation — not merely a momentary recognition that is immediately dropped.
>
> 4. **Criterion opacity:** The criteria governing *A* are not fully explicit to the researcher at the time of selection. (This distinguishes investigative attention from deliberate search, where the target is specified in advance.)

**Annotation:**

- Condition 1 is empirically observable: in each of Papers 1–3, the researcher attended to a small number of patterns from a much larger background of possible observations.
- Condition 2 is theoretically important: it establishes that attention is not simply "recognizing a structure." Attention comes first; structural understanding comes later. The checkerboard attracted attention before XOR was identified.
- Condition 3 distinguishes attention from casual noticing: attending to a pattern means investing investigation in it, not merely perceiving it.
- Condition 4 distinguishes the attention studied here from targeted search. H3 (Attention Filter Hypothesis) describes the implicit criteria that govern *A*. These criteria are the open question in OP-01.

**Note:**
The term "attention" here is used in its ordinary research-process sense, not in the technical sense of computational attention mechanisms (as in transformer models). The relationship between investigative attention and computational attention is an open question (OP-06).

---

### 3.3 Explanatory Significance

**Informal statement:**
Explanatory significance is the property of a structure that makes it feel as though it *demands* a deeper explanation — distinguishing it from mere curiosity, coincidence, or background variation.

**Working definition:**

> A structure *C* has **explanatory significance** for a researcher *ρ* if and only if all four of the following conditions hold:
>
> 1. **Non-randomness perception:** *ρ* perceives *C* as non-random — specifically, *ρ* experiences *C* as a configuration that could not plausibly have arisen by chance in *R*.
>
> 2. **Explanation-implication:** *C* implies to *ρ* the existence of a hidden generative rule *G* that is: (a) more compact than *C*'s description, and (b) not yet known to *ρ*.
>
> 3. **Productive research expectation:** *ρ* assigns non-negligible probability to the proposition that sustained investigation of *C* will yield *G* (or a significant approximation of *G*).
>
> 4. **Research-threshold crossing:** The combined strength of (1)–(3) is sufficient to initiate sustained investigation — *C* crosses *ρ*'s implicit threshold for committing investigative resources.

**Annotation:**

- Condition 1 formalizes H5 (Explanation Anticipation Hypothesis): the feeling of non-randomness is the trigger.
- Condition 2 formalizes H6 (Explanatory Significance Hypothesis): explanatory significance is not just "this is interesting" but "this implies something is hidden."
- Condition 3 introduces a probabilistic element: explanatory significance requires not just the sense that an explanation exists, but that it is *findable*. This distinguishes research-generating from merely puzzling structures.
- Condition 4 operationalizes the transition to action: a structure has explanatory significance when it actually generates research, not merely when it generates wonder.

**Researcher-relativity:**
The definition is indexed to a researcher *ρ* because explanatory significance is partly observer-dependent: a structure that has explanatory significance for a novice researcher (who does not yet know the explanation) may not have it for an expert (who already knows *G*). This relativity is a feature, not a bug — SRT is concerned with the *process* of research initiation, which is inherently situated.

**Connection to H7 (Mature Structure Discoverer):**
H7 proposes that the core human advantage in research is the ability to evaluate explanatory significance — to assign correct values to (1)–(4) across many candidate structures. Under the formal definition, H7 becomes: the human advantage lies in calibrated estimation of explanatory significance.

**Connection to H4 (Significance Filter):**
The significance filter (H4) operates at the boundary between structure recognition and research question generation. Under the formal definition, the filter passes a structure *C* if and only if *C* has explanatory significance for the researcher. The filter's implicit criteria are the conditions (1)–(4) above, weighted by some function the researcher has not made explicit.

---

## 4. The Research Generation Cycle

```
Pattern
  ↓ (observation)
Attention [→ Attention Filter (H3)]
  ↓ (selection)
Structure [→ Formal Definition 3.1]
  ↓ (interpretation)
Meaning
  ↓ (significance evaluation)
Explanatory Significance Detection [→ Formal Definition 3.3]
  ↓ (research threshold)
Question
  ↓ (systematic investigation)
Research
```

### Stage Notes

**Pattern → Attention:** The environment contains countless patterns. Only a subset attracts sustained investigative attention [Definition 3.2]. The Attention Filter (H3) governs this transition.

**Attention → Structure:** Attended patterns are reinterpreted as instances of an underlying relational configuration [Definition 3.1], not merely surface phenomena.

**Structure → Meaning:** Not all recognized structures are treated as meaningful. Meaning attribution involves the implicit judgment that *C* satisfies Conditions 1–2 of Definition 3.3: the structure is perceived as non-random and as implying a hidden rule.

**Meaning → Explanatory Significance Detection:** The critical threshold [Definition 3.3, Condition 4]. Research begins not when structure is recognized, but when the structure satisfies all four conditions of explanatory significance — including the productive research expectation (Condition 3) and threshold crossing (Condition 4).

**Explanatory Significance Detection → Question:** Once explanatory potential is detected, a research question forms: "what is the hidden generative rule *G* implied by *C*?"

---

## 5. Core Hypotheses (H1–H10)

### H1. Structure Discoverer Hypothesis

**Claim:** Humans may have a comparative advantage in structure discovery — specifically in the early stages of the Research Generation Cycle (Pattern → Attention → Structure).

```
AI: Computation, Search, Organization, Visualization
Human: Structure Discovery, Question Generation, Meaning Attribution
```

**Connection to formal definitions:**
"Structure discovery" here means: assigning *A(p) = 1* to patterns that satisfy Definition 3.1 (holistic recognition, non-triviality, transformational stability, generative implication) without explicit enumeration of these conditions.

*Status: Exploratory. Empirical research design proposed in Section 10.*

---

### H2. Representation Transformation Hypothesis

**Claim:** Many problems become tractable by changing representation so that structure [Definition 3.1] becomes visible, not by reducing computation.

```
Problem
  ↓
Representation Transformation
  ↓
Visible Structure [satisfies Definition 3.1, Condition 1]
  ↓
Human Recognition
  ↓
Insight
```

| Domain | Original Form | Transformed Form | Structure Revealed |
|---|---|---|---|
| Boolean logic | Expression A ⊕ B ⊕ C ⊕ D | Karnaugh map | Checkerboard (global regularity) |
| Symmetric functions | Truth table | K-map (Gray Code) | Layer-structured ring/corner patterns |
| Variable arrangements | Single K-map | 24 K-map variants | Invariant structural properties |

**Connection to Definition 3.1:**
A good representation transformation is one that enables Condition 1 of Definition 3.1 to be satisfied — that is, it allows the structure to be *recognized holistically* rather than assembled element by element.

*Status: Best-supported hypothesis. All three case studies provide consistent evidence.*

---

### H3. Attention Filter Hypothesis

**Claim:** A prior selection process determines which patterns receive investigative attention [Definition 3.2].

```
Many Patterns → Attention Filter → Selected Structures → Meaning → Questions
```

**Connection to Definition 3.2:**
The Attention Filter is the mechanism governing the selection function *A* (Definition 3.2, Condition 4: criterion opacity). The criteria of the filter are implicit — they are what the filter *is*, but they are not explicit to the researcher.

*Status: Exploratory. Inferred from observation that many patterns were not investigated. See OP-01.*

---

### H4. Significance Filter Hypothesis

**Claim:** Among attended structures, an implicit filter evaluates whether a structure is worth investigating.

```
Attended Patterns → Significance Filter → Research-Worthy Structures → Questions
```

**Connection to Definition 3.3:**
The significance filter passes structure *C* if and only if *C* satisfies Definition 3.3 (explanatory significance). The "implicit criteria" of H4 are the conditions (1)–(4) of Definition 3.3.

**Operationalized Significance Criteria:**

The four candidate criteria of H4 — compression, prediction, generalization, explanation pull — are now formally operationalized:

| Criterion | Informal description | Formal operationalization | Measurement method |
|---|---|---|---|
| **Compression** | Short rule explains many observations | *comp(C) = 1 − (|description(G)| / |enumeration(C)|)*, where higher = more compressed | Count symbols/bits in minimal description of rule vs. enumeration of all instances |
| **Prediction** | Structure enables prediction of unobserved cases | *pred(C) = accuracy on held-out test set T, above a domain-specific baseline* | Present researcher with partial data; measure correct predictions of withheld instances |
| **Generalization** | Structure appears across multiple domains | *gen(C) = |{domains d : C is instantiated in d}|* | Count independently verified domain instantiations |
| **Explanation pull** | Researcher anticipates explanation before finding it | *pull(C) = confidence rating (1–10) that an explanation exists, measured prior to investigation* | Pre-investigation self-report; compare against post-investigation confirmation rate |

**Note:** These criteria are not mutually exclusive. A structure may score high on multiple criteria. Whether the significance filter applies them conjunctively, disjunctively, or in weighted combination is an open question (related to OP-02).

**Cross-paper finding:** Structural invariance scores high on all four criteria across Papers 1–3 — it is maximally compressed (one property summarizes all arrangements), highly predictive, generalizes across representation changes, and generated strong explanation pull. This consistency motivates the proposal that invariance may be a general significance criterion.

*Status: Exploratory. Formal operationalization proposed; criteria not yet empirically validated.*

---

### H5. Explanation Anticipation Hypothesis

**Claim:** Humans anticipate the existence of an explanation before discovering it.

```
Visible Regularity
  ↓
Non-randomness feeling [Definition 3.3, Condition 1]
  ↓
Anticipation of explanation [Definition 3.3, Condition 2]
  ↓
Search
  ↓
Explanation
```

**Connection to Definition 3.3:**
Explanation anticipation corresponds to satisfying Conditions 1 and 2 of explanatory significance (Definition 3.3) before Condition 4 is reached — the researcher feels the non-randomness and implies the existence of a rule, but has not yet committed investigative resources.

*Status: Exploratory. Consistent with all three case studies. Empirical research design proposed in Section 10.*

---

### H6. Explanatory Significance Hypothesis

**Claim:** Research begins from detection of explanatory potential, not from structure discovery per se.

```
Visible Pattern → Hidden Structure → Perceived Explanatory Potential [Definition 3.3] → Research Question
```

**Connection to Definition 3.3:**
H6 is the primary motivation for Definition 3.3. The hypothesis is that the transition to research is governed specifically by explanatory significance (as defined), not by structure recognition alone.

*Status: Exploratory. Consistent with all three case studies. Empirical research design proposed in Section 10.*

---

### H7. Structure Discoverer Hypothesis — Mature Version

**Claim:** The core human advantage is the ability to evaluate which structures carry explanatory significance [Definition 3.3], not structure discovery per se.

```
Structure Discovery
      ↓
Attention Filter (H3) [Definition 3.2]
      ↓
Significance Filter (H4) [Definition 3.3, Conditions 1–3]
      ↓
Explanation Anticipation (H5) [Definition 3.3, Condition 1–2]
      ↓
Explanatory Significance Detection (H6) [Definition 3.3, Condition 4]
      ↓
Question Generation
```

**Reformulation under formal definitions:**
H7 can now be stated precisely: the human comparative advantage is calibrated and reliable estimation of whether a structure *C* satisfies Definition 3.3 — across diverse domains, without explicit enumeration of the four conditions.

**Connection to HARCT (Paper 5):**
In long-term Human-AI collaboration, the human retained research direction and goal selection. Under H7 with formal definitions: the human's core contribution is detecting which structures have explanatory significance (Definition 3.3) and sustaining investigation toward them.

*Status: Exploratory revision of H1.*

---

### H8. Concept-as-Lens Hypothesis *(Integrated Extension)*

> **Status change from v0.2:** Elevated from "candidate hypothesis" to "integrated extension hypothesis." This elevation reflects the completion of the formal definitions in Section 3, which depend on H8 for their full interpretation.

**Claim:** Concepts function as observation lenses: a change in concept may produce a change in what can be *recognized as a structure* [Definition 3.1, Condition 1].

```
Existing Concept
      ↓
Enables holistic recognition of certain structures
      ↓
New Concept acquired
      ↓
Enables holistic recognition of previously unrecognizable structures
```

**Integration with formal definitions:**
Definition 3.1 specifies that a structure must be *holistically recognized* (Condition 1). What can be holistically recognized depends on what concepts the observer has available. H8 states that this dependence is systematic and directional: acquiring a concept *expands* the set of structures satisfying Condition 1 for that observer.

**Examples in this program:**
- Without the concept of "Hamming Weight Layer": the ring/corner/point patterns in symmetric function K-maps are visible *as patterns* but not as *structures* (Condition 3 — transformational stability — is not recognized without the layer concept).
- With the concept of "structural invariance": the question "what is preserved under rearrangement?" becomes structurally formulable, not just verbally possible.

**Candidate research question:** Is the relationship between concept acquisition and structure recognition *predictable* — i.e., can we predict in advance which structures will become recognizable after a given concept is acquired?

*Status: Integrated extension hypothesis. Not yet empirically tested. See OP-07.*

---

### H9. Concept Evolution Hypothesis *(Integrated Extension)*

> **Status change from v0.2:** Elevated from "candidate hypothesis" to "integrated extension hypothesis."

**Claim:** Research generates concepts, and concepts (via H8) generate further research through expanded perception.

```
Research
  ↓ (output)
Concept
  ↓ (H8: expanded recognition)
New Structures visible [Definition 3.1, Condition 1 now satisfied]
  ↓ (H6: significance detection)
New Research Questions
  ↓
New Research
```

**Integration with formal definitions:**
H9 describes how the satisfaction of Definition 3.1, Condition 1 (holistic recognition) is *itself a variable over time* — it expands as the researcher's conceptual repertoire grows. Each completed research cycle potentially adds a concept (via H8) that enables new structures to be recognized, which enables new instances of explanatory significance detection (Definition 3.3), which enables new research.

**This program as evidence:**
The concept genealogy (ConceptGenealogy.md, Steps 1–7) documents H9 in operation over this research program's history. Each step generated a concept that enabled the next step's structure to become recognizable.

*Status: Integrated extension hypothesis. Consistent with program history. Formal test not yet designed.*

---

### H10. Generative Concept Hypothesis *(Integrated Extension)*

> **Status change from v0.2:** Elevated from "candidate hypothesis" to "integrated extension hypothesis."

**Claim:** Concepts differ in their generativity — some concepts expand perception more broadly and durably than others.

**Candidate operationalization of concept generativity:**

| Criterion | Description | Measurement |
|---|---|---|
| **Perception expansion** | Number of new structures recognized after concept acquisition | Count structures satisfying Definition 3.1 Condition 1 before and after concept acquisition |
| **Research yield** | Number of research questions generated via H9 cycle | Count research questions traceable to the concept |
| **Transferability** | Number of independent domains in which the concept applies | Count domains |
| **Durability** | Time period over which the concept continues to generate new structures | Years of productive use |
| **Depth** | Whether the concept enables recognition of structurally deeper or more fundamental phenomena | Expert judgment on structural depth |

**Examples in this program:**
- "Structural invariance": high generativity — led directly to Paper 3, contributed to SRT framework, connects to Papers 1–2 in retrospect.
- "Hamming Weight Layer": medium generativity — essential for Paper 2, but more domain-specific.
- "Concept-as-Lens" (H8): potentially very high generativity — if valid, it applies across all scientific domains, not only Boolean functions.

**Research question generated by H10:** Is there a "concept generativity score" that could be estimated before a concept is fully explored? If so, researchers might be able to prioritize conceptual development strategically.

*Status: Integrated extension hypothesis. Operationalization proposed but not validated.*

---

## 6. Concept Evolution Cycle

The Research Generation Cycle and the Concept Evolution Cycle interact:

**Research Generation Cycle:**
```
Pattern → Attention → Structure → Meaning → Question → Research
```

**Concept Evolution Cycle:**
```
Research → Concept → Expanded Perception (H8) → New Structures Visible → New Questions → New Research
```

**Interaction under formal definitions:**
The Concept Evolution Cycle modulates Definition 3.1, Condition 1 (holistic recognition) over time. As the researcher's conceptual repertoire grows (H9), the set of patterns satisfying Condition 1 expands. This expansion feeds back into the Research Generation Cycle, enabling new instances of attention selection (Definition 3.2) and explanatory significance detection (Definition 3.3).

**This program's own history:**

```
KMap observation (Pattern)
  ↓ [H5: non-randomness perceived]
"Why checkerboard?" (Question → Research → Paper 1)
  ↓ [H9: research generates concept]
Concept: "Structural invariance"
  ↓ [H8: concept expands perception]
New structure visible: "What is preserved under rearrangement?"
  ↓ [H6: explanatory significance detected]
Variable Rearrangement research (Paper 3)
  ↓ [H9: research generates concept]
Concept: "Explanatory significance detection" (SRT)
  ↓ [H8: concept expands perception]
New structure visible: "Why do humans find these structures worth studying?"
  ↓ [H6: explanatory significance detected]
Structure Recognition Theory (Paper 4)
  ↓ [H9: research generates concept]
Concept: "Concept-as-Lens" (H8 itself — self-referential)
  ↓ [H8 applied to H8]
New structure visible: "How do concepts change what can be observed?"
  ↓ [Program-level question: "How do humans come to see something new?"]
```

---

## 7. Human-AI Collaboration Model

### The Observed Division of Labor

From Paper 5 (Human-AI Research Continuity Theory):

```
Human Researcher:
  - Detects unusual phenomena [assigns A(p) = 1, Definition 3.2]
  - Evaluates explanatory significance (H7) [evaluates Definition 3.3]
  - Generates research questions
  - Preserves long-term research goals
  - Selects which directions to pursue

AI Collaborator:
  - Connects concepts across domains [supports H8 by surfacing concept candidates]
  - Expands explanation space
  - Suggests formal frameworks [supports Definition 3.3 Condition 2: rule articulation]
  - Organizes and documents
  - Maintains context across sessions (via externalized memory)
```

### Why This Division Persists

Under the formal definitions, the division is interpretable:
- Attention selection (Definition 3.2, Condition 4: criterion opacity) requires implicit criteria that are not formally specified — this is currently a human function.
- Explanatory significance detection (Definition 3.3, Conditions 1–4) requires integration of non-randomness perception, explanation-implication, productive expectation, and threshold judgment — these currently depend on human meaning-attribution.
- AI excels at processing within formalized spaces — once a structure is named and specified, AI can explore its properties efficiently.

The division may shift as AI systems develop better models of non-randomness perception and explanation-implication. H1/H7 predict the human advantage is in significance evaluation; OP-06 asks whether this is a fundamental or contingent boundary.

---

## 8. Case Study Summary

*(Unchanged from v0.2 — see that document for full case study details.)*

### Cross-Paper Finding: Invariance as Significance Criterion

Under the formal definitions, the cross-paper finding can be precisely stated:

> Structural invariance (what satisfies Definition 3.1 Condition 3 across Papers 1–3) consistently satisfies all four operationalized significance criteria of H4 (Section 5, H4 table). This is evidence that invariance under transformation may be a general criterion for explanatory significance detection (Definition 3.3).

---

## 9. Program-Level Findings

*(Substantially unchanged from v0.2. Key addition: the formal definitions enable more precise statements of the program-level claims.)*

### 9.1 Self-Reference

This research program demonstrates the phenomena it studies, now with formal precision: the checkerboard (Pattern) received investigative attention (Definition 3.2) because it appeared to satisfy explanatory significance conditions (Definition 3.3) — and the subsequent research generated concepts (H9) that made new structures visible (H8), enabling SRT itself.

### 9.2 Architecture B

```
Papers 1–3: Empirical Foundation Layer (case studies for formal definitions)
Paper 4: Theoretical Integration Layer (SRT framework, including Section 3 definitions)
Paper 5: Methodological Meta-layer (HARCT — studying the collaboration that made Papers 1–4 possible)
```

---

## 10. Empirical Research Design Proposals

> **Purpose:** These proposals are first-draft research designs for testing H1, H5, and H6. They are offered as starting points for research design, not finalized protocols. Each should be developed with appropriate domain expertise before implementation.

---

### 10.1 Testing H1: Structure Discoverer Hypothesis

**Target claim:** Humans have a comparative advantage in structure discovery — specifically in assigning attention to patterns that satisfy Definition 3.1 before full structural analysis.

**Proposed design: Competitive Discovery Paradigm**

*Setup:*
- Prepare a set of *novel* visual, mathematical, or symbolic datasets *S* — each containing exactly one embedded structure *C* satisfying Definition 3.1.
- "Novel" means neither the human researchers nor the AI systems have prior exposure to similar structures (requires careful stimulus design).
- Present each dataset independently to: (a) a panel of human researchers, (b) one or more AI systems.

*Task:*
- "Identify any pattern that you believe has a structural explanation."
- Participants are not told whether a structure exists.

*Dependent variables:*
- **Discovery rate:** Proportion of trials in which the structure *C* is correctly identified.
- **Discovery time:** Time to identification (humans: measured; AI: token count or query count as proxy).
- **Discovery quality:** Does the identified structure match Definition 3.1 Conditions 1–4?

*Controls:*
- Equate visual complexity across stimuli.
- Vary the type of structure (visual, mathematical, symbolic) to test generality.
- Blind evaluation of discovery quality by independent raters.

*Key challenge:*
Constructing genuinely novel structures that neither humans nor current AI have implicitly encountered is methodologically difficult. Pilot testing required.

*Predicted result under H1:* Human discovery rate exceeds AI discovery rate for novel stimuli; the gap narrows as structure type becomes more familiar.

---

### 10.2 Testing H5: Explanation Anticipation Hypothesis

**Target claim:** Before finding an explanation, humans perceive certain structures as non-random (Definition 3.3, Condition 1) and as implying an explanation (Condition 2).

**Proposed design: Pre-Discovery Confidence Rating Paradigm**

*Setup:*
- Prepare two stimulus sets:
  - Set A: patterns with genuine structural explanations (satisfying Definition 3.1).
  - Set B: matched patterns without structural explanations (generated by controlled randomization preserving surface statistics).
- Participants are not told which set is which.

*Task (in sequence, per stimulus):*
1. "Rate how non-random this pattern seems" (1–10 scale).
2. "Rate your confidence that a structural explanation exists" (1–10 scale).
3. *(After rating:)* Investigate the pattern for 5 minutes.
4. "Did you find a structural explanation?" (Yes / No / Partial).

*Dependent variables:*
- **Anticipation accuracy:** Correlation between pre-investigation ratings (steps 1–2) and post-investigation explanation success (step 4).
- **Non-randomness calibration:** Do high non-randomness ratings predict Set A membership?
- **Confidence calibration:** Do high confidence ratings predict explanation success?

*Key prediction under H5:*
Participants' pre-investigation ratings should predict Set A membership above chance. The anticipation is not random — humans have some implicit ability to detect which patterns have explanations before finding them.

*Control condition:*
Ask AI systems to rate the same stimuli on the same scales before investigation. Compare calibration.

*Key challenge:*
Generating Set B stimuli that are genuinely unexplainable (not merely unexplained) requires domain expertise. Statistical matching of Sets A and B is non-trivial.

---

### 10.3 Testing H6: Explanatory Significance Hypothesis

**Target claim:** The transition to sustained research investigation is governed by explanatory significance detection (Definition 3.3) — specifically by the satisfaction of all four conditions, not merely structure recognition.

**Proposed design: Research Worthiness Judgment Paradigm**

*Setup:*
- Prepare a set of structure candidates *{C₁, C₂, ..., Cₙ}*, varying systematically on the four operationalized criteria of H4:
  - Compression: low / medium / high.
  - Predictive power: low / medium / high.
  - Generalizability: domain-specific / cross-domain.
  - Explanation pull: pre-rated by a separate panel.

*Task:*
- Present each *Cᵢ* to a panel of researchers.
- "Would you invest sustained investigation in this structure?" (Yes / No / Maybe).
- "Rate your expectation that investigating this structure would yield a compact explanatory rule" (1–10).

*Dependent variables:*
- **Threshold prediction:** Do the four H4 criteria (compression, prediction, generalization, explanation pull) predict research-worthiness judgments?
- **Criterion weight:** Which criterion is most predictive of research-worthiness? Is the relationship additive, multiplicative, or threshold-gated?
- **Expert vs. novice comparison:** Do expert researchers' judgments differ from novices in their weighting of the four criteria?

*Post-hoc validation:*
For the subset of structures judged "worth investigating," follow up after 12 months of investigation: did the investigation yield significant results? This provides ground truth for calibration.

*Key prediction under H6:*
The four criteria together should predict research-worthiness judgments better than any single criterion alone. This would support the claim that explanatory significance is a multi-dimensional construct (as in Definition 3.3).

---

## 11. Open Questions

**Q1.** Why do certain structures attract investigative attention [Definition 3.2] while others of equivalent surface complexity do not?

**Q2.** What is the mechanism behind explanation anticipation (H5) — is it a genuine predictive sense or a post-hoc rationalization?

**Q3.** Is invariance (Definition 3.1, Condition 3) a universal significance criterion, or specific to structural research?

**Q4.** Does AI have an analogue of explanatory significance detection [Definition 3.3]?

**Q5.** Can the Concept Evolution Cycle (H9) be used deliberately to accelerate research — and if so, how?

**Q6.** What determines concept generativity (H10), and can it be predicted in advance?

**Q7.** How does the human-AI division of labor change as AI systems acquire better models of non-randomness perception and explanation-implication?

**Q8.** Are the four conditions of Definition 3.3 individually necessary, or is there a weaker set of sufficient conditions?

For full problem registry, see `theory/OpenProblems.md`.

---

## 12. Central Research Question

The question has evolved through successive refinements:

| Stage | Question | Scope |
|---|---|---|
| Initial | Why does this checkerboard appear? | Paper 1 |
| Early | Why do humans recognize patterns as structures? | Pre-SRT |
| Middle | Why do humans discover structures? | SRT v0.1 |
| Later | Why do certain structures feel worth investigating? | SRT v0.1–v0.2 |
| Current (theory) | **How do humans detect explanatory significance?** | Paper 4 operational focus |
| Current (program) | **How do humans come to see something new?** | Program-level |

**Under formal definitions (v0.3):**
The theory-level question is now formally: "How do humans evaluate whether a structure *C* satisfies Definition 3.3?"
The program-level question is: "How does the full cycle (Definitions 3.1–3.3, H8–H10) operate to enable genuinely new perception?"

---

## 13. Current Status and Next Steps

**v0.3 adds over v0.2:**
- ✓ Formal definitions of structure, attention, explanatory significance (Section 3)
- ✓ H4 formally operationalized with measurable criteria (Section 5, H4)
- ✓ H8–H10 elevated to integrated extension hypotheses with formal integration
- ✓ Empirical research design proposals for H1, H5, H6 (Section 10)
- ✓ All core hypotheses connected to formal definitions

**For v0.4 (proposed):**
- Researcher review of formal definitions — identify where definitions are too strong, too weak, or misspecified
- Pilot testing of empirical designs (10.1–10.3)
- Integration of v0.3 definitions into Hypotheses.md and CoreQuestions.md
- Formal connection to HARCT (Paper 5): how does externalized memory interact with explanatory significance detection over time?
- Evaluation of H8–H10 after further application to new case studies

All contents remain exploratory. v0.3 is a framework for investigation, not a collection of established results. The formal definitions are working definitions — offered as anchors for empirical work, not as settled philosophical positions.

---

*Version history: v0.1 → v0.2 (2026-06-06: H8–H10, HARCT integration) → v0.3 (2026-06-06: formal definitions, H4 operationalization, empirical designs)*
*Cross-reference: Hypotheses.md, CaseStudyConnections.md, HypothesisToCase.md, OpenProblems.md, CoreQuestions.md*
*Concept genealogy: ConceptGenealogy.md (Research-Portfolio-main)*
*Previous version: StructureRecognitionTheory_v0.2.md*
