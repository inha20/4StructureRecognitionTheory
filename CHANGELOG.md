# Changelog

All notable changes to this repository are documented here.

---

## v0.5.0 — 2026-06-21 (Session 31)

### Fixed

**레퍼런스 불일치 수정** — `README.md`, `HANDOVER.md`, `index.html`이 공통적으로 `theory/StructureRecognitionTheory_v0.1–v0.3.md`, `CaseStudyConnections.md`, `ResearchMap.md`, `research-notes/`, `future-papers/`, `research-history/`, `drafts/`가 이 저장소에 존재하는 것처럼 기술하고 있었으나, 실제로는 존재하지 않았음. 연구자 확인 결과, 해당 문서들은 `inha20` 저장소의 `theory/` 폴더에 세 개의 요약 문서(`SRT_Summary.md`, `Hypotheses_Summary.md`, `CoreQuestions_Summary.md`)로 압축·통합되어 있었음(통합 시점 미상).

- `README.md` — Repository Structure, Core Theory Documents, Key Research Areas, Future Papers 섬 전면 수정하여 실제 존재하는 파일과 `inha20/theory/` 요약 문서를 구분해 명시
- `HANDOVER.md` — v2.0→v2.1; "Repository Structure", "Current Theory State" 섬을 검증된 실제 상태로 교체; AI 읽기 순서를 현재 `inha20-main/management/SESSION_START.md` 단일 진입점으로 갱신(구버전 `MasterHandoverDocument.md` 경로는 Session 30에서 이미 폐기됨)
- `index.html` — 깨진 "SRT v0.3" GitHub 링크 및 "Current Theory State" 표 수정

**원인:** `inha20`로의 이론 문서 통합 작업(2026-06-06경 추정) 이후, 이 저장소 자체의 문서들이 새 위치를 반영하도록 갱신되지 않은 채 남아있었음("통합 마무리 작업 미완료", 연구자 표현).

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
