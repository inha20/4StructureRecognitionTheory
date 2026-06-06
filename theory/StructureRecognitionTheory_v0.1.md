# Structure Recognition Theory v0.1

> **Status:** Early-stage position paper.
> Contents represent organized hypotheses and conceptual models, not established conclusions.

---

## 1. Introduction

Humans encounter vast amounts of information daily.
Yet most information is ignored, while a small subset of phenomena attracts attention,
is perceived as structurally meaningful, and eventually develops into research questions.

This paper addresses the following question:

> **How do humans come to generate new research questions?**

Existing literature has addressed problem solving, reasoning, and knowledge acquisition extensively.
However, the earlier stage — the transition from observation to research question — has received comparatively less attention.

This project proposes a conceptual framework for this transition, focusing on:
- Structure discovery
- Meaning attribution
- Explanatory significance detection
- Question generation

---

## 2. Motivation

This project began with observations made during Karnaugh map research.

The initial observation was simple:

```
□ ■ □ ■
■ □ ■ □
□ ■ □ ■
■ □ ■ □
```

Certain Boolean functions produce a checkerboard pattern.

The more interesting observation was not the pattern itself, but the question it immediately prompted:

> *Why is this pattern immediately noticeable?*

This question led to further questions:
- Why do humans recognize repetition?
- Why do humans recognize symmetry?
- Why do humans perceive these as meaningful?
- Why do humans treat them as objects of research?

Structure Recognition Theory emerges from following these questions to their common source.

---

## 3. From Pattern to Research

This project models the research generation process as follows:

```
Pattern
  ↓
Attention
  ↓
Structure
  ↓
Meaning
  ↓
Question
  ↓
Research
```

### Stage 1: Pattern

The environment contains many patterns — repetition, symmetry, periodicity, clustering.
Pattern alone does not constitute research.

### Stage 2: Attention

A subset of patterns attracts human attention.
Patterns that fail to attract attention do not develop into research.

### Stage 3: Structure

Attended patterns are reinterpreted as structures — that is, as instances of an underlying generative rule.

Example:
```
Pattern:   □ ■ □ ■ ...
Structure: Separation of even/odd weight layers
```

Humans seek not the shape itself, but the rule that produces the shape.

### Stage 4: Meaning

Once a structure is identified, humans attribute meaning to it:
"This may not be coincidental."
"There may be an explanation for this."

At this stage, structure becomes an object of explanation rather than mere observation.

### Stage 5: Question

Meaning attribution generates questions:
- Why does this structure appear?
- Under what conditions does it hold?
- What changes, and what is preserved?

### Stage 6: Research

Questions generate research programs: hypothesis formation, data collection, and validation.

---

## 4. Structure Discoverer Hypothesis

**Hypothesis H1 (exploratory):**
Humans may possess a comparative advantage in structure discovery.

```
AI strengths:          Human strengths:
Computation            Structure Discovery
Search                 Question Generation
Summarization          Meaning Attribution
Organization           Research Direction Selection
Visualization
```

This is proposed as a difference in characteristic roles, not as a claim about general capability.

*This hypothesis is currently exploratory and has not been systematically tested.*

---

## 5. Representation Transformation Hypothesis

**Hypothesis H2 (exploratory):**
Many problems become tractable not by reducing computation, but by transforming representation
so that structure becomes visible to human perception.

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

**Examples:**

| Domain | Original Form | Transformed Form | Effect |
|---|---|---|---|
| Boolean logic | Boolean expression | Karnaugh map | Symmetry becomes visible |
| Biology | Protein folding data | Foldit puzzle | Spatial reasoning becomes applicable |
| Data | Numerical tables | Visualization | Patterns become perceptible |

The common element is not that the problem becomes easier computationally,
but that structure becomes perceptible to humans.

*This hypothesis is supported by multiple case observations; systematic validation is pending.*

---

## 6. Attention and Significance Filters

Not every recognized structure becomes a research question.

**Hypothesis H3 — Attention Filter (exploratory):**
A prior selection process determines which patterns attract sustained attention.

**Hypothesis H4 — Significance Filter (exploratory):**
Among attended structures, a further filter determines which are perceived as significant.

Candidate criteria for significance:

- **Compression:** The structure reduces many observations to a short rule
- **Prediction:** The structure enables prediction of unobserved cases
- **Generalization:** The structure recurs across multiple domains
- **Explanation:** The structure points toward a generative cause

*The criteria above are candidate proposals, not validated claims.*

---

## 7. Explanation Anticipation Hypothesis

**Hypothesis H5 (exploratory):**
Humans anticipate the existence of an explanation before they discover it.

```
Visible Regularity
  ↓
Expectation of Explanation
  ↓
Search
  ↓
Explanation
```

Observation: In all three case studies (Sections 8–10), the perception of non-randomness
preceded identification of the underlying cause.

This suggests the following revised model of curiosity:

> Humans are curious not simply about interesting phenomena,
> but about phenomena that *appear explicable*.

*This hypothesis is derived from case study observations. Further research is required.*

---

## 8. Case Study Analysis

### 8.1 Karnaugh Map Checkerboard Pattern

**Observation:**
The checkerboard pattern is recognized globally before individual cells are processed.
Exceptions to the pattern are detected rapidly.

**Connection to theory:**
This case provides evidence for H1 (global structure recognition precedes computation)
and H5 (expectation of explanation precedes identification of cause).

### 8.2 Symmetric Boolean Function Patterns

**Observation:**
Exactly-k functions repeatedly generate point, corner, and ring patterns.
These patterns correlate with Hamming Weight Layers,
but humans perceive the patterns before computing the Weight Layer.

**Connection to theory:**
This case provides evidence for H2 (representation reveals structure)
and H1 (structure recognition precedes computation).

### 8.3 Variable Rearrangement Invariance

**Observation:**
Variable rearrangement produces large visual changes while preserving logical meaning.
The salient research question was "what is preserved?" rather than "what changed?"

**Connection to theory:**
This case suggests humans preferentially seek invariance over change,
consistent with H4 (invariance as a significance criterion) and H6 (explanatory potential).

---

## 9. Toward a Unified Principle

The three case studies suggest a common underlying pattern:

```
Karnaugh Map    → Visible Pattern → Expectation of Explanation → Question
Symmetric Func. → Visual Regularity → Expectation of Explanation → Question
Rearrangement   → Preserved Invariance → Expectation of Explanation → Question
```

**Proposed principle:**

> Humans do not primarily research data.
> Humans research structures.
> More precisely: humans research *what structures might explain*.

The object of curiosity is not the pattern itself, but the generative principle behind it.

---

## 10. Research Question Generation Hypothesis

**Hypothesis H6 (exploratory):**
Research begins not from structure discovery, but from detection of explanatory potential.

```
Visible Pattern
  ↓
Hidden Structure
  ↓
Perceived Explanatory Potential
  ↓
Research Question
```

This extends the model: the key step is not recognizing that structure exists,
but recognizing that the structure *could be explained by something more fundamental*.

---

## 11. Human-AI Collaboration Interpretation

The case studies suggest a consistent pattern of collaboration:

```
Human:   "This pattern seems unusual."  →  Identifies potential significance
AI:      Connects to formal concepts     →  Expands explanation space
Human:   Selects the direction of inquiry
```

This suggests:
- Humans contribute: structure significance detection, research direction selection
- AI contributes: computation, concept connection, scale

*This interpretation is derived from observed collaboration patterns and remains speculative.*

---

## 12. Central Question

The evolution of research questions across this project:

| Stage | Question |
|---|---|
| Initial | Why does this checkerboard appear? |
| Intermediate | Why do humans recognize patterns as structures? |
| Later | Why do humans discover structures? |
| Current | Why do certain structures feel worth investigating? |

The current central question of Structure Recognition Theory:

> **How do humans detect explanatory significance?**

This question connects structure recognition theory, human-AI collaboration,
and the theory of research question generation into a unified inquiry.

---

## 13. Open Questions

The following questions are unresolved:

**Q1.** Why do certain structures attract attention while others do not?

**Q2.** Why do certain structures feel meaningful?

**Q3.** What is the relationship between structure discovery and intuition?

**Q4.** Does AI discover structures, or does it generate them?

**Q5.** Where do research questions originate?

**Q6.** Can the significance filter be made explicit?

**Q7.** Is explanatory significance detection teachable?

---

## 14. Current Status

This document is **not a completed theory**.

Current state:
- Observations organized
- Hypotheses proposed
- Case studies collected and connected to hypotheses

Structure Recognition Theory has the potential to develop from its origins
in Karnaugh map, symmetric Boolean function, and variable rearrangement research
into a unified theory explaining how humans discover structures
and transform them into research questions.

All hypotheses in this document require further empirical validation.
