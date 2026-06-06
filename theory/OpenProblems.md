# Open Problems

**Version:** 1.1  
**Date:** 2026-06-06  
**Status:** Living document — problems are added but never closed without researcher approval.

> This document provides a formal registry of unresolved questions in the Structure Recognition Research Program.
> Problems are distinguished from hypotheses: a hypothesis proposes a candidate answer;
> an open problem names a question that has no settled answer yet.

---

## How to Use This Document

- Add a problem when a question is identified that resists quick resolution
- Never mark a problem as "solved" in isolation — flag it as "candidate resolution proposed" and wait for researcher evaluation
- Problems are numbered for cross-reference but the numbers are not priority orderings

---

## Open Problem Registry

---

### OP-01: The Attention Selection Problem

**Statement:**
Not all patterns receive investigative attention. A prior selection process exists.
But the criteria governing this selection are unknown.

**Origin:** H3 (Attention Filter Hypothesis)

**What we observe:**
The checkerboard K-map pattern attracted attention and investigation.
Many other patterns (same visual complexity) did not.

**What we don't know:**
- Is attention selection based on visual salience?
- Is it based on some implicit estimate of explanatory payoff?
- Does familiarity (geometric forms, symmetry) influence which patterns are selected?
- Is the selection partly unconscious and partly deliberate?

**Candidate research approach:**
Comparative case study: patterns that received investigation vs. patterns that did not.
Identify what they share and what differs.

**Status:** Open. No systematic evidence yet.

---

### OP-02: The Significance Boundary Problem

**Statement:**
Some recognized structures pass a significance filter and become research questions.
Others do not, even when equally recognized.
The boundary conditions for this filter are unknown.

**Origin:** H4 (Significance Filter Hypothesis)

**Candidate criteria (unvalidated):**
- Compression: does the structure compress large information into a short rule?
- Prediction: does the structure enable prediction of unobserved cases?
- Generalizability: does the structure appear applicable across multiple domains?
- Explanation pull: does the structure feel like it *demands* a causal explanation?

**What we don't know:**
- Are these criteria necessary? Sufficient? Neither?
- Does the significance filter operate differently across domains?
- Can the filter be trained or improved?

**Status:** Open. Candidate criteria proposed but not validated.

---

### OP-03: The Explanation Anticipation Mechanism

**Statement:**
Before finding a structural explanation, humans appear to anticipate that one exists.
The mechanism underlying this anticipation is unknown.

**Origin:** H5 (Explanation Anticipation Hypothesis)

**What we observe:**
In Paper 1, the checkerboard was labeled "non-random" before the XOR connection was made.
In Paper 2, the recurring forms were considered "explicable" before Hamming Weight was identified.

**What we don't know:**
- Is the anticipation a genuine predictive sense or a post-hoc rationalization?
- What triggers it? Pattern regularity? Geometric simplicity? Frequency of occurrence?
- Is it tied to prior experience with similar structures (analogical reasoning)?
- Does this mechanism differ across individuals?

**Status:** Open. Observational evidence only; no mechanistic explanation.

---

### OP-04: The Representation Design Problem

**Statement:**
H2 claims that representation transformation can reveal structure.
But which transformations are *good* transformations?
The design principles for structure-revealing representations are unknown.

**Origin:** H2 (Representation Transformation Hypothesis)

**What we observe:**
- K-map (Gray code arrangement) makes checkerboard patterns visible
- Standard binary ordering does not make the same patterns visible
- The K-map was not designed to reveal checkerboard patterns — it was designed for grouping

**What we don't know:**
- Is there a principled method for finding structure-revealing representations?
- Is the match between representation and structure discoverable in advance?
- Or is the good representation found only after the structure is known?

**Status:** Open. The K-map case suggests representations can be discovered serendipitously.

---

### OP-05: The Invariance Significance Problem

**Statement:**
In Paper 3, invariance under variable rearrangement was deemed research-worthy
while the changes themselves were not. Why is invariance more significant than change?

**Origin:** H4, H6

**What we observe:**
The observation "some structural properties survive all 24 variable arrangements"
generated research questions. The observation "patterns change under rearrangement"
did not, despite being equally true.

**What we don't know:**
- Is invariance intrinsically more significant than change? Or is this context-dependent?
- Does the presence of change (24 arrangements all different) make the invariant
  properties *more* salient (contrast effect)?
- Is invariance a general criterion for significance, or specific to structural research?

**Status:** Open. Cross-paper pattern (see CaseStudyConnections.md) suggests
invariance as a candidate significance criterion.

---

### OP-06: The AI Structure Discovery Problem

**Statement:**
H1 claims humans have a comparative advantage in structure discovery.
But it is unclear whether AI *cannot* discover structures or simply *has not yet*.

**Origin:** H1, H7

**What we observe:**
In the research program, structure discovery (noticing patterns, generating questions)
was done by the human researcher.
AI contributed connections, frameworks, organization.

**What we don't know:**
- Is the human advantage due to biological constraints of AI systems?
- Or is it an artifact of how AI systems are currently prompted and used?
- Does AI have an "analogue of intuition" that could support structure discovery?
- Would a differently designed AI system discover structures differently?

**Status:** Open. H7 reformulates the question but does not answer it.

---

### OP-07: The Concept-as-Lens Problem

**Statement:**
New concepts appear to enable the discovery of structures not previously visible.
The mechanism by which a concept "opens" new perception is unknown.

**Origin:** ConceptEvolution.md (Concept-as-Lens Hypothesis)

**What we observe:**
After the concept of "structural invariance" was available, researchers could ask
questions that were not formulable before the concept existed.

**What we don't know:**
- Does the concept create new categories of perception, or merely new vocabulary?
- Are all concepts equally generative, or do some function better as lenses?
- Can concept-as-lens be operationalized for deliberate discovery?

**Status:** Open. See ConceptEvolution.md for further analysis.

---

### OP-08: The Research Question Origin Problem

**Statement:**
Research questions arise from interactions between observations, concepts, and significance evaluations.
The precise mechanism is not understood.

**Origin:** H6, CoreQuestions.md Q4

**What we observe:**
Research questions in this program emerged from:
- Noticing an unusual pattern (Papers 1–3)
- Finding that standard concepts did not explain it
- Anticipating that an explanation exists

**What we don't know:**
- Is this sequence generalizable to other research programs?
- What role does prior knowledge play vs. surprise?
- Is research question generation a skill that can be improved?

**Status:** Open. This problem is central to the program's meta-theoretical goal.

---

### OP-09: The Definition 3.3 Necessity Conditions Problem

**Statement:**
Definition 3.3 (Explanatory Significance, SRT v0.3) is formulated with four conditions
as jointly necessary and sufficient.
But whether the four conditions are *individually necessary* — or whether a weaker or
alternative set could substitute — is an open question with direct implications for the
theory's empirical testability.

**Origin:** SRT v0.3, Section 11 (Q8); H4 (Significance Filter); H6 (Explanatory Significance)

**What we observe:**
In the three case studies (Papers 1–3), all four conditions appear to have been satisfied
in each instance that generated sustained research:
- **Condition 1** (Non-randomness perception): patterns were experienced as non-random before structural analysis.
- **Condition 2** (Explanation-implication): an underlying rule was anticipated before it was found.
- **Condition 3** (Productive research expectation): researchers expected investigation to be fruitful.
- **Condition 4** (Research-threshold crossing): sustained investigation was initiated.

**What we don't know:**
- Are all four conditions *individually necessary*? Could a structure have explanatory significance while failing to satisfy one condition?
- Is Condition 4 (research-threshold crossing) a logical consequence of Conditions 1–3 together, or an independent requirement?
- Do the conditions apply conjunctively, disjunctively, or in weighted combination?
- Is the definition *too strong* — does it exclude genuinely research-worthy structures by requiring all four conditions simultaneously?
- Is the definition *too weak* — can all four conditions be satisfied by a structure that does not, in practice, generate productive research?
- Could there be a deeper necessary condition that the four-condition formulation is tracking only approximately?

**Relation to OP-02:**
OP-02 (Significance Boundary Problem) addresses the *empirical* boundary of the significance filter
— what determines whether a structure passes the filter in practice.
OP-09 is more specific and formal: it addresses the *logical structure of Definition 3.3 itself*
— whether the definition correctly captures necessary and sufficient conditions for explanatory
significance, independently of how the filter is applied.

**Candidate research approach:**
Identify or construct cases in which exactly one of the four conditions is absent.
Ask whether explanatory significance (and sustained investigation) still occurred.
If a structure generates research while failing Condition 3 (productive research expectation is low),
for example, this would constitute evidence that Condition 3 is not individually necessary.

**Status:** Open. Raised in SRT v0.3, Section 11. No empirical test yet designed.

---

## Problems Marked as "Candidate Resolution Proposed"

*None yet.*

---

## Problems That Were Closed (With Reason)

*None yet. No problem should be marked closed without researcher approval.*

---

## Notes on Problem Addition

When adding a new problem:

```
### OP-[next number]: [Short Name]

**Statement:** [Clear, precise statement of what is unknown]

**Origin:** [Which hypothesis, observation, or document raised this]

**What we observe:** [Empirical grounding]

**What we don't know:** [Specific unknowns, as a list]

**Candidate research approach:** [Optional — how one might investigate this]

**Status:** Open / Candidate resolution proposed / [other]
```

---

*Created: 2026-06-06*  
*Cross-reference: Hypotheses.md, CoreQuestions.md, CaseStudyConnections.md, HANDOVER.md*  
*Scope: Structure Recognition Research Program — Problems are program-level, not paper-level*
