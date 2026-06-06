# Changelog

All notable changes to this repository are documented here.

---

## v0.4.0 — 2026-06-06

### Added

**theory/StructureRecognitionTheory_v0.3.md** — Draft SRT paper; primary new contribution is the formal definitional layer

- **Section 3: Formal Definitions** (primary contribution)
  - Definition 3.1 (Structure): 4-condition working definition — holistic recognition, non-triviality, transformational stability, generative implication
  - Definition 3.2 (Attention): 4-condition working definition — selectivity, antecedence, persistence, criterion opacity
  - Definition 3.3 (Explanatory Significance): 4-condition working definition — non-randomness perception, explanation-implication, productive research expectation, research-threshold crossing
- **Section 10: Empirical Research Design Proposals**
  - 10.1: Competitive Discovery Paradigm (H1)
  - 10.2: Pre-Discovery Confidence Rating Paradigm (H5)
  - 10.3: Research Worthiness Judgment Paradigm (H6)
- H4 operationalized: compression, prediction, generalization, explanation pull — each with formal measurement specification
- H8–H10 elevated from "candidate extensions" to "integrated extension hypotheses"; integrated with Definitions 3.1–3.3

### Changed

**theory/Hypotheses.md** — H8, H9, H10 added; Definition cross-references added to H3–H7

**theory/OpenProblems.md** — OP-09 added: Definition 3.3 necessity conditions problem

**theory/CoreQuestions.md** — Footer updated to cross-reference SRT v0.3

---

## v0.3.0 — 2026-06-06

### Changed

**theory/CoreQuestions.md** — Major expansion: v1.0 → v2.0

- Level hierarchy extended: Level 0–5 → Level 0–8
  - Level 6 (Concept): what makes a concept effective as an observation lens
  - Level 7 (Expanded Perception): how concept acquisition changes what is observable
  - Level 8 (New Discovery): how the concept evolution cycle generates new discovery cycles
- Each level now includes: sub-questions, connected hypotheses (H1–H10), connected open problems (OP-01–OP-08), and explicit relation to adjacent levels
- Full Question Inventory expanded: Q1–Q10 → Q1–Q15
  - Q11–Q15: meta-theoretical questions (significance filter operationalization, domain-generality of explanatory significance detection, invariance-significance relationship, concept generativity measurement, concept evolution acceleration)
- Cross-Level Questions table added (questions that span multiple levels)
- Program History as Question Evolution table added — shows how each refinement of the central question required a new concept
- Integrated sources: `drafts/CoreQuestions_vNext.md` (Levels 6–8 adopted), `SRT v0.2` (H8–H10), `OpenProblems v1.0` (OP-01–OP-08)
- Program-level central question added: "How do humans come to see something new?" (supersedes theory-level question as program framing)

---

## v0.2.0 — 2026-06-03

### Added

**research-notes/** — Working hypotheses organized into six categories:
- `cognition/` — attention-selection-hypothesis, attention-meaning-question-model, meaning-attribution-hypothesis, research-worthiness-hypothesis, research-generation-model
- `structure/` — difference-hypothesis, structure-discovery-hypothesis, structure-discoverer-hypothesis
- `representation/` — representation-transformation-hypothesis
- `concept/` — concept-as-lens-hypothesis, concept-genealogy
- `ai/` — human-ai-collaboration-model, ai-analogue-of-intuition
- `meta/` — core-concepts-map, research-program-architecture

**future-papers/**
- structure-recognition-theory-outline.md (15-chapter expanded framework)
- structure-recognition-theory-roadmap.md (long-term development stages)

**research-history/**
- personal-structure-discovery-timeline.md

### Changed

- README.md updated to reflect full research program architecture, repository structure, and navigation links
- Core theory documents moved to `theory/`
- Draft and vNext documents moved to `drafts/`

### Structure

```
.
├── README.md
├── CHANGELOG.md
├── .gitignore
├── theory/
├── research-notes/
│   ├── cognition/
│   ├── structure/
│   ├── representation/
│   ├── concept/
│   ├── ai/
│   └── meta/
├── future-papers/
├── research-history/
└── drafts/
```

---

## v0.1.0 — Initial Release

### Added

- README.md
- ResearchMap.md
- CoreQuestions.md
- Hypotheses.md (H1–H7)
- CaseStudies.md
- ConceptEvolution.md
- StructureRecognitionTheory_v0.1.md
- vNext candidate documents (ResearchMap, CoreQuestions, Hypotheses, README, FutureIntegration)
