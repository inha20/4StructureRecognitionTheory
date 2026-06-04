# Case Studies

---

## Case Study 1: Karnaugh Map Checkerboard Pattern

### Observation

```
□ ■ □ ■
■ □ ■ □
□ ■ □ ■
■ □ ■ □
```

Certain Boolean functions produce a checkerboard pattern in Karnaugh map representation.

### Questions Generated

- Why does this pattern stand out immediately?
- Why do humans recognize the whole before processing individual cells?

### Key Observations

**Observation 1 — Global-before-local recognition**
Humans do not read individual cells sequentially.
The checkerboard is recognized as a unified structure prior to cell-by-cell analysis.
The apparent processing order is *pattern → cells*, not *cells → pattern*.

**Observation 2 — Rapid repetition detection**
The checkerboard has the form:
```
ABAB
BABA
ABAB
BABA
```
Humans detect this repetition very rapidly.

**Observation 3 — Exception salience**
When a single cell is altered:
```
□ ■ □ ■
■ □ ■ □
□ ■ ■ ■   ← modified
■ □ ■ □
```
the modified position is detected quickly.
This suggests that structure is formed first, and exceptions are identified against it.

### Connections to Hypotheses

| Hypothesis | Connection |
|---|---|
| H1 | Global structure recognition precedes individual cell computation |
| H3 | This pattern passes the attention filter |
| H5 | An expectation of explanation arises before the cause (XOR) is identified |

---

## Case Study 2: Symmetric Boolean Function Patterns

### Observation

Exactly-k Boolean functions repeatedly generate specific visual forms in Karnaugh maps:
- Point
- Corner
- Ring

### Questions Generated

- Why do these forms appear repeatedly?
- Why do humans recognize these forms as regularities?

### Key Observations

**Observation 1 — Weight Layer structure**
These patterns are more directly related to Hamming Weight Layers than to individual cell values.

Relationship:
```
Boolean Function
  ↓
Weight Layer
  ↓
Visual Pattern
```

**Observation 2 — Perception precedes computation**
Humans perceive the pattern before computing the Weight Layer.
Structure recognition appears to precede the identification of its generator.

### Connections to Hypotheses

| Hypothesis | Connection |
|---|---|
| H2 | Visual representation reveals structure not visible in the Boolean expression alone |
| H1 | Structure recognition precedes computation |
| H5 | Repetition of ring/corner forms generates an expectation of a structural explanation |

---

## Case Study 3: Variable Rearrangement Invariance

### Observation

Rearranging input variables in a Boolean function causes large visual changes in the Karnaugh map,
while leaving the logical function itself unchanged.

```
Pattern A
  ↓
Variable Rearrangement
  ↓
Pattern B
```

`Visual Structure ≠ Logical Meaning`

### Questions Generated

- Do humans detect invariance before detecting change?
- What is preserved under rearrangement, and what is altered?

### Key Observations

**Observation 1 — Large visual change**
The Karnaugh map representation changes substantially under variable rearrangement.

**Observation 2 — Logical identity preserved**
Despite the visual change, the Boolean function evaluated remains identical.

**Observation 3 — Invariance as the primary question**
The key research question that emerged was not "what changed?" but rather **"what was preserved?"**
This suggests a tendency to seek invariance over change.

### Connections to Hypotheses

| Hypothesis | Connection |
|---|---|
| H3 | Invariance passes the significance filter more readily than change |
| H6 | The observation points toward a deeper explanatory principle (equivalence class structure) |
| H2 | The same logical object can be represented in visually distinct forms |
