# Case Study Connections

## Papers 1–3 → H1–H7 Mapping

**Version:** 1.0  
**Date:** 2026-06-06  
**Status:** Structural mapping only — all connections are exploratory, not confirmed conclusions.

> This document makes explicit the connections between empirical observations from Papers 1–3
> and the exploratory hypotheses H1–H7. All connections represent research leads, not validated claims.

---

## Summary Table

| Paper | Key Observation | Primary Hypothesis Connections |
|---|---|---|
| Paper 1: KMap Patterns | Checkerboard recognized as a whole before cells are processed | H2, H5 |
| Paper 1: KMap Patterns | Exceptions detected against an established structure | H3, H4 |
| Paper 2: Symmetric Functions | Pattern perceived before Hamming Weight computed | H1, H2 |
| Paper 2: Symmetric Functions | Ring/point/corner forms repeat across different Exactly-k functions | H5, H6 |
| Paper 3: Variable Rearrangement | Same logical function produces visually distinct K-maps | H2 |
| Paper 3: Variable Rearrangement | Invariance was sought before the nature of the invariant was known | H4, H6 |
| Paper 3: Variable Rearrangement | Rearrangement as a tool to reveal hidden structure | H2, H3 |

---

## Paper 1 — KMap Structure Invariance

### Core Observation
Boolean functions of specific types (particularly XOR, XNOR) produce a checkerboard pattern
in Karnaugh map visualization.

### Observation → Hypothesis Connections

#### Connection to H2 (Representation Transformation)

The Boolean expression `A ⊕ B ⊕ C ⊕ D` does not visually suggest a checkerboard.
The Karnaugh map representation makes this structure immediately visible.

```
Boolean expression  →  Karnaugh map
(structure hidden)     (structure revealed)
```

**Exploratory claim:** The checkerboard did not become research-worthy until
the Karnaugh map made it visible. This supports H2: representation transformation
can reveal structures that were not tractable in the original form.

#### Connection to H5 (Explanation Anticipation)

The checkerboard was recognized as non-random before its cause (XOR structure) was identified.

**Exploratory claim:** Humans felt that the pattern "should have an explanation"
before they found that the explanation was XOR. This anticipation of explanation
is consistent with H5.

#### Connection to H3 (Attention Filter)

Not all Karnaugh map patterns received equivalent investigative attention.
The checkerboard passed an implicit attention filter; many other patterns did not.

**Open question (from H3):** What distinguishes patterns that pass the attention filter?
Is it regularity? Simplicity? Geometric familiarity?

#### Connection to H4 (Significance Filter)

Among recognized patterns, the checkerboard generated research questions.
Other visible patterns did not generate equivalent research interest.

**Open question:** What made the checkerboard pass the significance filter?
Candidate answers: visual salience, mathematical cleanness (XOR has a single concise formula),
unusual appearance for a combinational function.

---

## Paper 2 — Symmetric Boolean Function Visual Patterns

### Core Observation
Symmetric Boolean functions (Exactly-k, XOR, XNOR) produce recurring visual forms
(point, corner, ring, checkerboard) in Karnaugh maps.
The Hamming Weight Layer structure appears to generate these forms.

### Observation → Hypothesis Connections

#### Connection to H1 (Structure Discoverer)

The Hamming Weight Layer structure was not computed from a formula; it was perceived visually.
A researcher noticed that certain forms repeat, and then worked backward to find their generator.

```
Visual pattern recognized
    ↓
Structural explanation sought
    ↓
Hamming Weight Layer identified as generator
```

**Exploratory claim:** This is structure discovery in the H1 sense — 
recognition precedes computation, and the recognized structure motivates the search for explanation.

#### Connection to H2 (Representation Transformation)

The Hamming Weight Layer structure is not directly visible in a Boolean truth table.
The Karnaugh map makes it visible by spatially organizing minterms.

**Exploratory claim:** The same logical information is present in both representations,
but the Karnaugh map enables recognition of structure that was structurally opaque in table form.

#### Connection to H5 (Explanation Anticipation)

The repeat appearances of ring/corner/point forms across different Exactly-k functions
generated an expectation that a common explanation must exist — before the
Hamming Weight Layer was identified as that explanation.

**Exploratory claim:** Repetition across different functions signals that a common
structural cause exists. Humans detect this signal before identifying the cause.

#### Connection to H6 (Explanatory Significance)

The question "why do these patterns repeat?" arose because the repetition
seemed to carry explanatory potential, not merely because it was observed.

**Exploratory claim:** The research began from detection of explanatory significance,
not simply from observation of the pattern. The pattern was observed first;
research began when it *seemed worth explaining*.

---

## Paper 3 — Variable Rearrangement Invariance

### Core Observation
Rearranging input variables of a Boolean function produces dramatically different
Karnaugh map visualizations, while the logical function itself remains unchanged.
The central research question became: what structural properties survive rearrangement?

### Observation → Hypothesis Connections

#### Connection to H2 (Representation Transformation)

Variable rearrangement is a representation transformation. The same logical object
appears in 24 different visual forms (4! = 24 arrangements).

```
Logical function  →  Visual representation A  ≠  Visual representation B ≠ ...
(unchanged)           (AB/CD arrangement)           (AC/BD arrangement)
```

**Exploratory claim:** Different representations of the same logical object
reveal different structural properties. No single arrangement reveals all structure.
Variable rearrangement is a tool for revealing what was hidden in any single arrangement.

#### Connection to H3 (Attention Filter) and H4 (Significance Filter)

The question "what is preserved?" emerged rather than "what changed?"

The change in visual representation was obvious and not intrinsically interesting.
The invariance — what survived transformation — was deemed more significant.

**Exploratory claim:** The significance filter was directed toward invariance, not change.
This suggests that structural persistence across transformations is a candidate criterion
for passing the significance filter.

#### Connection to H6 (Explanatory Significance)

The observation that some structural properties survive all 24 arrangements seemed to
*call for an explanation* — it did not merely describe a fact.

**Exploratory claim:** The invariance observation was deemed research-worthy because
it carried explanatory potential: if something survives all transformations, there must be
a structural reason why.

---

## Cross-Paper Connection: The Invariance Theme

A recurring theme across all three papers is the interplay between
**change** and **invariance**:

| Paper | What changes | What is invariant |
|---|---|---|
| Paper 1 | Cell-by-cell reading | Whole-pattern structure (checkerboard recognized immediately) |
| Paper 2 | Specific bit values | Weight Layer structure (same layer pattern for all Exactly-k) |
| Paper 3 | Visual representation (24 arrangements) | Logical function; structural properties (1-cell count, etc.) |

This convergence across three independent studies suggests that
**invariance under transformation** may be a candidate criterion for
what passes the significance filter (H4).

---

## Open Connections (Not Yet Mapped)

The following aspects of Papers 1–3 have not yet been clearly connected to specific hypotheses:

| Observation | Candidate Connection | Status |
|---|---|---|
| D₄ group structure of K-map variable arrangements | H4 (algebraic structure → significance) | Unexplored |
| Gray Code requirement for pattern visibility | H2 (representation design choice matters) | Unexplored |
| Human recognition of exception against structure (Paper 1) | H7 (detecting where structure breaks = detecting explanatory potential) | Unexplored |
| Ring structures collapsing to corner at boundary conditions | H5 (anticipation of explanation when forms behave differently at limits) | Unexplored |

---

## For Future Development

When new observations from Papers 1–3 are made, record them here using:

1. **Observation statement** — what was actually seen, without interpretation
2. **Candidate hypothesis connection** — which hypothesis this connects to, and how
3. **Open question generated** — what question this raises
4. **Status** — exploratory / partially supported / open question only

Do not mark any connection as "confirmed" without explicit researcher approval.

---

*Created: 2026-06-06*  
*Cross-reference: CaseStudies.md, Hypotheses.md, HANDOVER.md*  
*Status: Exploratory structural mapping — all connections are research leads, not conclusions.*
