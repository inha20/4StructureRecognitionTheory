# Hypothesis-to-Case Study Mapping

**Version:** 1.0
**Date:** 2026-06-06
**Status:** Exploratory — all connections are research leads, not validated claims.
**Direction:** H1–H7 → Supporting Case Observations (Papers 1–3)

> This document is the reverse complement of `CaseStudyConnections.md`.
> CaseStudyConnections.md maps: Paper Observation → Hypothesis
> This document maps: Hypothesis → Supporting Paper Observations
>
> Use both documents together for complete cross-referencing.

---

## How to Read This Document

Each hypothesis entry lists:
- **Core Claim** — the exploratory proposal
- **Supporting Observations** — specific observations from Papers 1–3 that are consistent with the hypothesis
- **Strongest Case** — which paper/observation provides the clearest illustration
- **Gaps** — what empirical evidence would strengthen or challenge the hypothesis
- **Status** — current evidential standing

---

## H1 — Structure Discoverer Hypothesis

**Core Claim:** Humans may have a comparative advantage in structure discovery over AI.

| Paper | Supporting Observation |
|---|---|
| Paper 2 | Pattern (ring/corner/point) was recognized visually before the Hamming Weight connection was computed |
| Paper 2 | The question "why do these patterns repeat across different Exactly-k functions?" arose from visual inspection, not calculation |
| Paper 1 | The checkerboard was recognized globally before individual cells were read |

**Strongest Case:** Paper 2 — the ring/corner/point pattern was recognized before its generator (Hamming Weight Layers) was known. This is a clean case where structure discovery preceded explanation.

**What would strengthen H1:** Controlled comparison of human vs. AI performance on novel Boolean function visualization tasks. AI provided with the same visual stimulus: does it notice the repeating pattern?

**What would challenge H1:** Demonstration that AI systems consistently discover structures that humans miss in equivalent visual representations.

**Gap:** H1 is based on the observation that, in this research program, structure discovery happened to be done by the human. It is not clear whether this is a fundamental asymmetry or an artifact of how AI was used.

**Status:** Exploratory. Consistent with observations; no controlled evidence.

---

## H2 — Representation Transformation Hypothesis

**Core Claim:** Some problems become tractable not by reducing computation, but by changing representation so that structure becomes visible.

| Paper | Supporting Observation |
|---|---|
| Paper 1 | Boolean expression `A ⊕ B ⊕ C ⊕ D` does not visually suggest checkerboard; Karnaugh map makes it immediately visible |
| Paper 2 | Truth table does not make Hamming Weight Layer patterns visible; Karnaugh map (Gray Code arrangement) does |
| Paper 3 | Rearranging variables is a representation transformation that reveals invariants not visible in a single arrangement |
| Paper 3 | 24 variable arrangements of the same function produce 24 different Karnaugh maps — each revealing different structural aspects |

**Strongest Case:** Paper 1 — the XOR checkerboard is invisible in the Boolean expression form and immediately visible in the Karnaugh map. The representation change is crisp and the structural gain is measurable.

**Cross-paper pattern:** All three papers use the Karnaugh map as a structure-revealing representation. This suggests H2 is the hypothesis most consistently supported across the research program.

**What would strengthen H2:** Formal characterization of which representation transformations are structure-revealing and which are not. Identification of the property that makes Gray Code ordering (vs. standard binary ordering) more structure-revealing for Boolean functions.

**Gap:** The cases all involve the same representation transformation (Karnaugh map). Cross-domain generalization has not been directly tested.

**Status:** Supported by multiple case observations. Strongest evidentiary standing among H1–H7.

---

## H3 — Attention Filter Hypothesis

**Core Claim:** Not all patterns receive investigative attention; a prior selection process determines which patterns are investigated.

| Paper | Supporting Observation |
|---|---|
| Paper 1 | Checkerboard patterns received intensive study; many other K-map patterns (with equivalent visual complexity) did not |
| Paper 2 | Ring, corner, and point patterns received investigation; many other Exactly-k patterns did not |
| Paper 3 | The question "what is preserved under rearrangement?" was investigated; the change itself was not the research focus |

**Strongest Case:** Paper 1 — many Boolean functions produce non-random Karnaugh map patterns. Only the checkerboard (and related XOR/XNOR structures) became research questions in Paper 1. What distinguished these from the others?

**Open Question (OP-01):** What determines which patterns pass the attention filter? Candidate factors:
- Visual salience (symmetry, regularity, familiarity of form)
- Implicit estimate of explanatory payoff
- Simplicity of the pattern (checkerboard is maximally simple and globally structured)
- Prior exposure (checkerboard is a culturally familiar form)

**Gap:** The attention filter hypothesis is inferred from the observation that many patterns were not investigated. But no systematic catalog of "patterns that were NOT investigated" exists to compare against "patterns that WERE investigated."

**Status:** Exploratory. Consistent with observations; inference from absence.

---

## H4 — Significance Filter Hypothesis

**Core Claim:** Among attended structures, an implicit filter evaluates whether a structure is "worth investigating."

| Paper | Supporting Observation |
|---|---|
| Paper 1 | Checkerboard passed significance filter: "this should have an explanation" → research question generated |
| Paper 2 | Repeating pattern across multiple functions passed filter: "why does this recur?" → research question generated |
| Paper 3 | Invariance passed significance filter; pattern change under rearrangement did not |

**Candidate Significance Criteria (unvalidated):**

| Criterion | Paper 1 | Paper 2 | Paper 3 |
|---|---|---|---|
| Compression | ✓ Checkerboard = one short rule | ✓ Layers = one short explanation | ✓ Invariant = one preserved property |
| Prediction | ✓ XOR → checkerboard, predictable | ✓ Exactly-k → specific layer | Partial |
| Generalization | ✓ Appears in all 4-variable XOR | ✓ Appears in all Exactly-k | ✓ Appears across all 24 arrangements |
| Explanation pull | ✓ Strong — feels explicable | ✓ Strong — repetition implies cause | ✓ Strong — invariance implies structure |

**Cross-paper pattern:** Invariance under transformation consistently passes the significance filter in all three papers. This supports "invariance as a significance criterion" as a candidate principle.

**Connection to OP-02:** Significance Boundary Problem — the boundary conditions of the significance filter are not yet identified.

**Status:** Exploratory. Candidate criteria proposed; not validated.

---

## H5 — Explanation Anticipation Hypothesis

**Core Claim:** Humans anticipate the existence of an explanation before they discover it.

| Paper | Supporting Observation |
|---|---|
| Paper 1 | Checkerboard labeled "non-random" and "should have an explanation" before XOR connection was identified |
| Paper 2 | Repeating ring/corner/point forms treated as "explicable" before Hamming Weight Layer was found |
| Paper 3 | Invariance under all 24 arrangements was perceived as "requiring an explanation" before the structural reason was known |

**Proposed Mechanism:**
```
Visible Regularity
      ↓
Non-randomness feeling
      ↓
Anticipation of explanation
      ↓
Research begins
```

**Strongest Case:** Paper 1 — the sequence is clearly documentable: checkerboard observed → non-randomness felt → explanation searched → XOR found.

**What this adds beyond H3/H4:** H3 is about which patterns receive attention; H4 is about which pass the significance filter. H5 is about the *motivational mechanism* — the feeling that an explanation exists *before* finding it. This feeling may be what drives the investigation.

**Connection to OP-03:** The mechanism behind explanation anticipation is unknown. Is it based on pattern regularity? Geometric simplicity? Prior experience with similar structures?

**Status:** Exploratory. Consistent with case observations; mechanism unknown.

---

## H6 — Explanatory Significance Hypothesis

**Core Claim:** Research begins from detection of explanatory potential, not from structure discovery per se.

| Paper | Supporting Observation |
|---|---|
| Paper 1 | Research began when the checkerboard was perceived as having explanatory potential (not merely when it was noticed) |
| Paper 2 | Research began when recurring patterns were perceived as explicable through a common cause |
| Paper 3 | Research question ("what is preserved?") arose from perception that invariance has an explanation, not merely from observation of the phenomenon |

**Distinction from H4:**
- H4 is about whether a structure passes a significance filter (worthiness)
- H6 is about whether the research begins from detecting explanatory potential specifically

Under H6, the key event is not "this seems significant" but more specifically "this seems *explicable*."

**Implications:**
- Pattern recognition is not sufficient to generate research
- Structure recognition is not sufficient
- Detection of explanatory potential is the threshold event

**Strongest Case:** Paper 3 — the research question "what is preserved?" is explicitly a question about explanation ("there must be a structural reason that something survives all 24 transformations"). The research began from detecting explanatory potential, not merely from observing the invariance.

**Status:** Exploratory. Consistent with all three case studies.

---

## H7 — Structure Discoverer Hypothesis (Mature Version)

**Core Claim:** The core human advantage is not structure discovery per se, but the ability to evaluate which structures carry explanatory significance.

*H7 is a revision of H1, incorporating the developments of H3–H6.*

```
Human
  ↓
Structure Discovery (H1 claim)
  ↓
Attention Filter (H3)
  ↓
Significance Evaluation (H4)
  ↓
Explanation Anticipation (H5)
  ↓
Explanatory Significance Detection (H6)
  ↓
Question Generation
  ↓
Research
```

**H7 Reframing:**

H1 proposed: "Humans are better at structure discovery."

H7 proposes: "The deeper advantage is not in noticing structures, but in detecting *which structures are worth turning into research questions*."

This is a more precise claim:
- AI may discover (or generate) structures
- But evaluating which discovered structures carry explanatory potential — and therefore should become research — may be specifically human

| Paper | H7 Supporting Observation |
|---|---|
| Paper 1 | Not all K-map patterns became research; specifically the ones with explanatory potential (XOR structure) did |
| Paper 2 | Not all Boolean function patterns became research; the repeating patterns with a common cause did |
| Paper 3 | The focus on invariance (explanatory potential) rather than change was a human selection |

**Relationship to HARCT (Paper 5):**
Paper 5 documents that in long-term Human-AI collaboration, humans retained research direction and goal selection. This is consistent with H7: the human's irreplaceable contribution is not producing content but selecting *which structures are worth pursuing*.

**Status:** Exploratory revision of H1. Consistent with all three case studies and with Paper 5 observations.

---

## Summary Table: Hypotheses vs. Case Studies

| Hypothesis | Paper 1 | Paper 2 | Paper 3 | Strongest Case |
|---|---|---|---|---|
| H1 (Structure Discoverer) | Partial | ✓ | Partial | Paper 2 |
| H2 (Representation Transformation) | ✓✓ | ✓✓ | ✓✓ | All three (strongest overall) |
| H3 (Attention Filter) | ✓ | ✓ | ✓ | Paper 1 |
| H4 (Significance Filter) | ✓ | ✓ | ✓✓ | Paper 3 |
| H5 (Explanation Anticipation) | ✓✓ | ✓ | ✓ | Paper 1 |
| H6 (Explanatory Significance) | ✓ | ✓ | ✓✓ | Paper 3 |
| H7 (Mature Structure Discoverer) | ✓ | ✓ | ✓ | Cross-paper pattern |

Legend: ✓✓ = strongest illustration | ✓ = consistent | Partial = partially consistent

---

## Cross-Hypothesis Connections

```
H1 (humans discover structures)
      ↓
H3 (not all patterns receive attention)
      ↓
H4 (not all attended patterns are deemed significant)
      ↓
H5 (humans anticipate explanation before finding it)
      ↓
H6 (research begins from explanatory potential detection)
      ↓
H7 (mature: human advantage = explanatory significance evaluation)
```

H2 (representation transformation) runs parallel to this chain:
- Representation transformation is the mechanism that makes structures available to H1
- Without the Karnaugh map, the structures in Papers 1–3 would not have been detectable

---

## For Future Hypothesis Development

When new observations from Papers 1–3 or Paper 4 case studies are made:

1. Check which existing hypothesis (H1–H7) it is most consistent with
2. Record the observation in `CaseStudyConnections.md` (Paper → Hypothesis direction)
3. Update the relevant hypothesis entry in this document (Hypothesis → Paper direction)
4. If the observation fits no existing hypothesis, add it to `OpenProblems.md`

**Current Hypothesis Gaps:**

| Gap | Description |
|---|---|
| Between H3 and H4 | The relationship between attention selection and significance filtering is not formalized |
| H1 vs. H7 | The precise difference between "structure discovery" (H1) and "explanatory significance detection" (H7) needs sharper definition |
| H5 mechanism | The cognitive mechanism behind explanation anticipation has no model |
| H2 generalization | All H2 evidence comes from Boolean function / Karnaugh map context; cross-domain generalization unverified |

---

*Created: 2026-06-06*
*Cross-reference: CaseStudyConnections.md, Hypotheses.md, OpenProblems.md, HANDOVER.md*
*Direction: Hypothesis → Supporting Observations (reverse of CaseStudyConnections.md)*
