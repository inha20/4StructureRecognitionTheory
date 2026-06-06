# Structure Recognition Theory v0.2

> **Status:** Active development — early-stage position paper.
> All hypotheses are exploratory propositions, not established conclusions.
> **Supersedes:** StructureRecognitionTheory_v0.1.md

**Version:** 0.2
**Date:** 2026-06-06
**Changes from v0.1:**
- Added H8–H10 (Concept as Lens, Concept Evolution, Generative Concept) from drafts/Hypotheses_vNext.md
- Integrated Human-AI Research Continuity Theory (HARCT) perspective from Paper 5
- Expanded Human-AI collaboration section with research division of labor model
- Added Concept Evolution Cycle and its interaction with Research Generation Cycle
- Added cross-paper invariance pattern as cross-cutting finding
- Added section on program-level findings

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

## 3. The Research Generation Cycle

```
Pattern
  ↓ (observation)
Attention
  ↓ (selection)
Structure
  ↓ (interpretation)
Meaning
  ↓ (significance evaluation)
Explanatory Significance Detection
  ↓ (research threshold)
Question
  ↓ (systematic investigation)
Research
```

### Stage Notes

**Pattern → Attention:** The environment contains countless patterns. Only a subset attracts sustained attention. The Attention Filter (H3) governs this transition.

**Attention → Structure:** Attended patterns are reinterpreted as instances of an underlying generative rule, not merely as surface phenomena.

**Structure → Meaning:** Not all recognized structures are treated as meaningful. Meaning attribution involves an implicit judgment: "this may not be coincidental."

**Meaning → Explanatory Significance Detection:** The critical threshold. Research begins not when structure is recognized, but when a structure is perceived as having explanatory potential (H6). The human feels: "there must be a deeper reason for this."

**Explanatory Significance Detection → Question:** Once explanatory potential is detected, a research question forms: "what explains this structure?"

---

## 4. Core Hypotheses (H1–H10)

### H1. Structure Discoverer Hypothesis

**Claim:** Humans may have a comparative advantage in structure discovery.

```
AI: Computation, Search, Organization, Visualization
Human: Structure Discovery, Question Generation, Meaning Attribution
```

*Status: Exploratory. Not systematically tested.*

---

### H2. Representation Transformation Hypothesis

**Claim:** Many problems become tractable by changing representation so that structure becomes visible, not by reducing computation.

```
Problem
  ↓
Representation Transformation
  ↓
Visible Structure
  ↓
Human Recognition
  ↓
Insight
```

| Domain | Original Form | Transformed Form |
|---|---|---|
| Boolean logic | Expression A ⊕ B ⊕ C ⊕ D | Karnaugh map |
| Symmetric functions | Truth table | K-map (Gray Code) |
| Variable arrangements | Single K-map | 24 K-map variants |

*Status: Best-supported hypothesis. All three case studies (Papers 1–3) provide consistent evidence.*

---

### H3. Attention Filter Hypothesis

**Claim:** A prior selection process determines which patterns receive investigative attention.

```
Many Patterns → Attention Filter → Selected Structures → Meaning → Questions
```

*Status: Exploratory. Inferred from observation that many patterns were not investigated.*

---

### H4. Significance Filter Hypothesis

**Claim:** Among attended structures, an implicit filter evaluates whether a structure is worth investigating.

Candidate significance criteria (unvalidated):
- **Compression** — short rule explains many observations
- **Prediction** — structure enables prediction of unobserved cases
- **Generalization** — structure appears across multiple contexts
- **Explanation pull** — structure feels like it points to a causal explanation

**Cross-paper finding:** Invariance under transformation consistently passes the significance filter in Papers 1–3. This suggests invariance as a candidate significance criterion.

*Status: Exploratory. Candidate criteria proposed; not validated.*

---

### H5. Explanation Anticipation Hypothesis

**Claim:** Humans anticipate the existence of an explanation before discovering it.

```
Visible Regularity → Non-randomness feeling → Anticipation of explanation → Search → Explanation
```

The sense of non-randomness motivates the search. This is a motivational mechanism, distinct from the cognitive mechanism of structure discovery itself.

*Status: Exploratory. Consistent with all three case studies.*

---

### H6. Explanatory Significance Hypothesis

**Claim:** Research begins from detection of explanatory potential, not from structure discovery per se.

```
Visible Pattern → Hidden Structure → Perceived Explanatory Potential → Research Question
```

The threshold event is not "I see a structure" but "I see a structure that seems to require an explanation."

*Status: Exploratory. Consistent with all three case studies.*

---

### H7. Structure Discoverer Hypothesis — Mature Version

**Claim:** The core human advantage is the ability to evaluate which structures carry explanatory significance, not structure discovery per se.

*This is a revision of H1, incorporating H3–H6.*

```
Structure Discovery
      ↓
Attention Filter (H3)
      ↓
Significance Filter (H4)
      ↓
Explanation Anticipation (H5)
      ↓
Explanatory Significance Detection (H6)
      ↓
Question Generation
```

H7 reframes H1: the human advantage is not noticing structures (AI may do this) but selecting which structures are worth turning into research.

**Connection to HARCT (Paper 5):** In long-term Human-AI collaboration, the human retained research direction and goal selection. This is consistent with H7: the human's core contribution is evaluating which structures are worth pursuing.

*Status: Exploratory revision of H1.*

---

### H8. Concept-as-Lens Hypothesis

*From drafts/Hypotheses_vNext.md — candidate extension hypothesis.*

**Claim:** Concepts function as observation lenses: a change in concept may produce a change in what can be observed.

```
Existing Concept
      ↓
Enables perception of certain structures
      ↓
New Concept
      ↓
Enables perception of previously unnoticed structures
```

Examples:
- The concept of "Hamming Weight Layer" made previously invisible patterns in symmetric functions visible
- The concept of "structural invariance" made the question "what is preserved?" formulable

*Status: Candidate hypothesis. Not yet integrated into main theory.*

---

### H9. Concept Evolution Hypothesis

*From drafts/Hypotheses_vNext.md — candidate extension hypothesis.*

**Claim:** Research generates concepts, and concepts generate further research through expanded perception.

```
Research
  ↓
Concept
  ↓
Expanded Perception (H8)
  ↓
New Observations
  ↓
New Questions
  ↓
New Research
```

This creates the Concept Evolution Cycle (see Section 5).

*Status: Candidate hypothesis. Consistent with program history.*

---

### H10. Generative Concept Hypothesis

*From drafts/Hypotheses_vNext.md — candidate extension hypothesis.*

**Claim:** Concepts differ in their generativity — some generate more future research, questions, and observations than others.

Candidate criteria for concept generativity:
- Compression (short concept, many phenomena)
- Predictive power (concept enables new predictions)
- Transferability (concept applies across domains)
- Visibility enhancement (concept reveals previously invisible structures)
- Research yield (number of research questions generated)

*Status: Candidate hypothesis. Needs operationalization.*

---

## 5. Concept Evolution Cycle

The Research Generation Cycle and the Concept Evolution Cycle interact:

**Research Generation Cycle:**
```
Pattern → Attention → Structure → Meaning → Question → Research
```

**Concept Evolution Cycle:**
```
Research → Concept → Expanded Perception → New Observations → New Questions → New Research
```

**Interaction:**
These two cycles reinforce each other. A research program generates concepts (H9); those concepts enable perception of new patterns (H8); new patterns feed back into the Research Generation Cycle.

**This program's own history as an example:**

```
KMap observation (Pattern)
  ↓
"Why checkerboard?" (Question → Research)
  ↓
Concept: "Structural invariance" (Concept)
  ↓
Can now ask: "what is preserved?" (Expanded Perception)
  ↓
Variable Rearrangement research (New Observations)
  ↓
"What explains the invariance?" (New Question)
  ↓
Structure Recognition Theory (New Research)
  ↓
Concept: "Explanatory significance detection" (Concept)
  ↓
Can now study: "how do humans evaluate research worthiness?" (Further Expansion)
```

The research program itself demonstrates the Concept Evolution Cycle.

---

## 6. Human-AI Collaboration Model

### The Observed Division of Labor

From Paper 5 (Human-AI Research Continuity Theory):

```
Human Researcher:
  - Detects unusual phenomena
  - Evaluates explanatory significance (H7)
  - Generates research questions
  - Preserves long-term research goals
  - Selects which directions to pursue

AI Collaborator:
  - Connects concepts across domains
  - Expands explanation space
  - Suggests formal frameworks
  - Organizes and documents
  - Maintains context across sessions (via externalized memory)
```

### Why This Division Persists

The division is not accidental. It reflects a deeper asymmetry:

- Structure discovery (H1) appears to require perception of non-randomness (H5) and judgment of explanatory potential (H6)
- These involve meaning attribution that is currently harder to formalize
- AI excels at processing and connecting within formalized spaces
- Humans contribute the judgment that a pattern *should* have an explanation

### The Collaboration Sequence

```
Human: "This pattern seems unusual."
      ↓
AI: Connects it to known structures and frameworks
      ↓
Human: Selects which connection feels meaningful
      ↓
AI: Expands the selected direction
      ↓
Human: Evaluates whether expansion matches the original intuition
```

This sequence appears repeatedly in the research program history.

---

## 7. Case Study Summary

### Paper 1 — KMap Structure Invariance

**Core observation:** XOR/XNOR functions produce checkerboard patterns in Karnaugh maps.

**SRT connections:**
- H2: K-map representation makes structure visible (not the Boolean expression)
- H5: Checkerboard was perceived as "non-random" before XOR was identified
- H6: Research began from detection of explanatory potential, not merely pattern observation

---

### Paper 2 — Symmetric Boolean Functions

**Core observation:** Symmetric functions produce recurring ring/corner/point patterns. Hamming Weight Layers explain the structure.

**SRT connections:**
- H1: Pattern recognized visually before the Hamming Weight calculation
- H2: K-map (Gray Code arrangement) reveals layer structure invisible in truth tables
- H5: Recurring forms created expectation of a common explanation
- H6: Research generated because the repetition implied a hidden explanatory structure

---

### Paper 3 — Variable Rearrangement Invariance

**Core observation:** Variable rearrangement produces dramatically different visual patterns while the logical function is preserved.

**SRT connections:**
- H2: Different arrangements = different representations revealing different structures
- H4: Invariance passed significance filter; change did not
- H6: Research focused on what is preserved, because invariance felt like it demanded an explanation
- H7: Human selected invariance over change as the research-worthy direction

---

### Cross-Paper Finding: Invariance as Significance Criterion

A pattern consistent across all three papers:

| Paper | What changes | What is invariant | Research focus |
|---|---|---|---|
| Paper 1 | Cell-by-cell reading | Global pattern (checkerboard) | Why does this pattern appear? |
| Paper 2 | Specific Exactly-k values | Layer pattern type | Why do these forms recur? |
| Paper 3 | Visual representation (24 arrangements) | Logical function; structural properties | What is preserved? |

**Proposed principle:** Invariance under transformation may be a general significance criterion — structures that persist under change feel like they demand structural explanation.

---

## 8. Program-Level Findings

### 8.1 Self-Reference

This research program demonstrates the phenomena it studies. Paper 5 makes this explicit: the research program is studying itself. The checkerboard observation (Paper 1) generated the concept of structural invariance (Paper 3), which generated Structure Recognition Theory (Paper 4), which generated the Human-AI collaboration study (Paper 5).

### 8.2 Architecture B

The program has a layered architecture (Architecture B, adopted 2026-06-05):

```
Papers 1–3: Empirical Foundation Layer (observations)
Paper 4: Theoretical Integration Layer (SRT framework)
Paper 5: Methodological Meta-layer (HARCT — studying the process)
```

### 8.3 Concept Genealogy

The program's concept history demonstrates the Concept Evolution Cycle (H8, H9):

```
Pattern (KMap checkerboard)
  ↓
Layer Structure (Hamming Weight)
  ↓
Equivalence (same structure, different variables)
  ↓
Structural Invariance (preserved under transformation)
  ↓
Structure Recognition Theory (meta-question)
  ↓
Human-AI Collaboration Model
```

Each concept in this chain made the next concept visible.

---

## 9. Open Questions

**Q1.** Why do certain structures attract attention while others of equivalent visual complexity do not?

**Q2.** What is the mechanism behind explanation anticipation (H5)?

**Q3.** Is invariance a universal significance criterion, or specific to structural research?

**Q4.** Does AI have an analogue of explanatory significance detection?

**Q5.** Can the Concept Evolution Cycle be used deliberately to accelerate research?

**Q6.** What makes a concept generative (H10)?

**Q7.** How does the human-AI division of labor change as AI systems become more capable?

For full problem registry, see `theory/OpenProblems.md`.

---

## 10. Central Research Question

The question has evolved through successive refinements:

| Stage | Question |
|---|---|
| Initial | Why does this checkerboard appear? |
| Early | Why do humans recognize patterns as structures? |
| Middle | Why do humans discover structures? |
| Later | Why do certain structures feel worth investigating? |
| **Current** | **How do humans detect explanatory significance?** |

This current question integrates the full chain: from structure recognition (H1, H2) through attention and significance filters (H3, H4) to explanation anticipation (H5) and explanatory significance detection (H6, H7).

---

## 11. Current Status and Next Steps

**v0.2 reflects:**
- H1–H7 (main theory) + H8–H10 (candidate extensions)
- Full case study integration (Papers 1–3)
- Concept Evolution Cycle
- Human-AI collaboration model (informed by Paper 5 HARCT)
- Cross-paper invariance finding

**For v0.3:**
- Formal definitions of key concepts (structure, attention, explanatory significance)
- Operationalization of H4 significance criteria
- Empirical research design proposals for testing H1, H5, H6
- Integration of H8–H10 after further evaluation

All contents remain exploratory. The theory is a framework for investigation, not a collection of established results.

---

*Cross-reference: Hypotheses.md, CaseStudyConnections.md, HypothesisToCase.md, OpenProblems.md, CoreQuestions.md*
*Paper 5 (HARCT): 5HumanAIResearchCollaboration-main/paper.md*
*Previous version: StructureRecognitionTheory_v0.1.md*
