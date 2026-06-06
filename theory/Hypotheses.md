# Hypotheses

> All hypotheses below are **exploratory**.
> None should be treated as established conclusions.
> Hypotheses are extracted and organized from existing material; no new hypotheses have been introduced.

---

## H1. Structure Discoverer Hypothesis

**Claim:** Humans may possess a comparative advantage in structure discovery.

```
AI
├─ Computation
├─ Summarization
├─ Organization
└─ Visualization

Human
├─ Structure Discovery
├─ Question Generation
├─ Meaning Attribution
└─ Research Direction Selection
```

This represents a **difference in roles**, not a difference in overall capability.

**Status:** Exploratory. Currently no controlled evidence.

---

## H2. Representation Transformation Hypothesis

**Claim:** Some difficult problems become tractable not by reducing computation,
but by changing the problem's representation.

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

| Original Form | Transformed Form |
|---|---|
| Boolean expression | Karnaugh map |
| Protein folding data | Foldit puzzle |
| Numerical data | Visualization |
| Complex information | Structural diagram |

**Status:** Supported by multiple case observations; requires systematic validation.

---

## H3. Attention Filter Hypothesis

**Claim:** Humans do not investigate every pattern. A prior selection process occurs.

```
Many Patterns
    ↓
Attention Filter
    ↓
Selected Structures
    ↓
Meaning
    ↓
Questions
```

**Open question:** What determines which patterns pass the attention filter?

**Formal connection:** The attention filter is the mechanism governing the selection function *A* in Definition 3.2 (SRT v0.3). The filter's criteria correspond to Definition 3.2, Condition 4 (criterion opacity): the filter operates implicitly, without the researcher making its criteria explicit.

**Status:** Exploratory. See OP-01.

---

## H4. Significance Filter Hypothesis

**Claim:** Beyond attention, humans apply an implicit filter evaluating whether a structure is *worth investigating*.

```
Pattern
  ↓
Structure
  ↓
Significance Filter
  ↓
Question
```

**Possible conditions for passing the filter:**

- **Compression** — The structure compresses a large amount of information into a short rule
- **Prediction** — The structure enables prediction of unobserved cases
- **Generalization** — The structure appears applicable across multiple domains
- **Explanation pull** — The structure points toward a generative cause; the researcher anticipates finding one

**Formal connection:** The significance filter passes structure *C* if and only if *C* satisfies Definition 3.3 (Explanatory Significance, SRT v0.3). The four candidate criteria above correspond to operationalized measurement specifications in SRT v0.3, Section 5 (H4 table).

**Operationalized criteria (SRT v0.3):**

| Criterion | Formal operationalization |
|---|---|
| Compression | *comp(C) = 1 − (\|description(G)\| / \|enumeration(C)\|)* |
| Prediction | Accuracy on held-out test set above domain baseline |
| Generalization | *gen(C) = \|{domains d : C instantiated in d}\|* |
| Explanation pull | Pre-investigation confidence rating (1–10) |

**Status:** Exploratory. Formal operationalization proposed in SRT v0.3; criteria not yet empirically validated. See OP-02.

---

## H5. Explanation Anticipation Hypothesis

**Claim:** Humans anticipate the existence of an explanation before they discover it.

```
Visible Regularity
  ↓
Expectation of Explanation
  ↓
Search
  ↓
Explanation
```

People perceive that a pattern "does not seem random" *before* they have identified its cause.
The sense of non-randomness may precede — and motivate — the search for structure.

**Formal connection:** Explanation anticipation corresponds to satisfying Conditions 1 and 2 of Definition 3.3 (SRT v0.3) *before* Condition 4 is reached — the non-randomness is perceived and the explanation is implied, but sustained investigation has not yet been committed.

**Status:** Exploratory. Empirical research design proposed: SRT v0.3, Section 10.2 (Pre-Discovery Confidence Rating Paradigm). See OP-03.

---

## H6. Explanatory Significance Hypothesis

**Claim:** Research begins not from structure discovery per se,
but from the detection of *explanatory potential* in a structure.

```
Visible Pattern
  ↓
Hidden Structure
  ↓
Perceived Explanatory Potential
  ↓
Research Question
```

**Formal connection:** H6 is the primary motivation for Definition 3.3 (Explanatory Significance, SRT v0.3). The claim is that the transition to research is governed specifically by a structure satisfying all four conditions of Definition 3.3 — not by structure recognition (Definition 3.1) alone.

**Status:** Exploratory. Empirical research design proposed: SRT v0.3, Section 10.3 (Research Worthiness Judgment Paradigm).

---

## H7. Structure Discoverer Hypothesis — Mature Version

*A revision of H1, incorporating developments from H3–H6.*

```
Human
  ↓
Structure Discovery
  ↓
Significance Evaluation
  ↓
Question Generation
  ↓
Research
```

The core human advantage may not be pattern recognition per se, but the ability to
**evaluate which structures carry explanatory significance**.

This reframes the human role from *structure discoverer* to
*explanation opportunity detector*.

**Formal connection:** Under SRT v0.3, H7 can be stated precisely: the human comparative advantage is calibrated and reliable estimation of whether a structure *C* satisfies Definition 3.3 (Explanatory Significance) — across diverse domains, without explicit enumeration of the four conditions.

**Connection to HARCT (Paper 5):** In long-term Human-AI collaboration, the human retained research direction and goal selection. This is consistent with H7: the human's core contribution is evaluating which structures satisfy Definition 3.3 and sustaining investigation toward them.

**Status:** Exploratory (revision of H1). Empirical research design proposed: SRT v0.3, Section 10.1 (Competitive Discovery Paradigm). See OP-06.

---

## H8. Concept-as-Lens Hypothesis *(Integrated Extension)*

*From SRT v0.3 — elevated from candidate hypothesis to integrated extension hypothesis.*

**Claim:** Concepts function as observation lenses: a change in concept may produce a change in what can be *recognized as a structure* (Definition 3.1, Condition 1: holistic recognition).

```
Existing Concept
      ↓
Enables holistic recognition of certain structures [Definition 3.1]
      ↓
New Concept acquired
      ↓
Enables holistic recognition of previously unrecognizable structures
```

**Examples:**
- Without "Hamming Weight Layer": ring/corner/point patterns are visible as *patterns* but not recognized as *structures* (Condition 3 of Definition 3.1 is not yet perceived)
- With "structural invariance": the question "what is preserved under rearrangement?" becomes structurally formulable

**Formal connection:** Definition 3.1, Condition 1 (holistic recognition) depends on the observer's conceptual repertoire. H8 states that this dependence is systematic and directional: acquiring a concept expands the set of configurations satisfying Condition 1 for that observer.

**Status:** Integrated extension hypothesis (elevated from candidate in SRT v0.3). Not yet empirically tested. See OP-07.

---

## H9. Concept Evolution Hypothesis *(Integrated Extension)*

*From SRT v0.3 — elevated from candidate hypothesis to integrated extension hypothesis.*

**Claim:** Research generates concepts, and concepts (via H8) generate further research through expanded perception.

```
Research
  ↓ (output)
Concept
  ↓ (H8: expanded recognition)
New structures become visible [Definition 3.1, Condition 1 now satisfied]
  ↓ (Definition 3.3: significance detection)
New Research Questions
  ↓
New Research
```

**Formal connection:** H9 describes how Definition 3.1, Condition 1 (holistic recognition) is a variable over time — it expands as the researcher's conceptual repertoire grows through H8. Each completed research cycle potentially adds a concept that enables new structures to be recognized, which enables new instances of Definition 3.3 (explanatory significance detection), which enables new research.

**Evidence:** The Concept Genealogy (Research-Portfolio-main/ConceptGenealogy.md, Steps 1–7) documents H9 in operation over this research program's history.

**Status:** Integrated extension hypothesis (elevated from candidate in SRT v0.3). Consistent with program history. Formal test not yet designed.

---

## H10. Generative Concept Hypothesis *(Integrated Extension)*

*From SRT v0.3 — elevated from candidate hypothesis to integrated extension hypothesis.*

**Claim:** Concepts differ in their generativity — some expand perception more broadly and durably than others (via H8 and H9).

**Candidate operationalization:**

| Criterion | Measurement |
|---|---|
| Perception expansion | Count structures satisfying Definition 3.1 Condition 1 before and after concept acquisition |
| Research yield | Count research questions traceable to the concept via H9 cycle |
| Transferability | Count independent domains in which the concept applies |
| Durability | Years of continued productive use |
| Depth | Expert judgment on structural depth of phenomena revealed |

**Examples in this program:**
- "Structural invariance": high generativity — directly generated Paper 3, contributed to SRT framework, connects to Papers 1–2 in retrospect
- "Hamming Weight Layer": medium generativity — essential for Paper 2, more domain-specific
- "Concept-as-Lens" (H8): potentially very high generativity — if valid, applies across all scientific domains

**Status:** Integrated extension hypothesis (elevated from candidate in SRT v0.3). Operationalization proposed; not yet validated. See OP-07, Q14.
