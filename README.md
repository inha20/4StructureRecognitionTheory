> **보관된 이전 연구 노트.** 이 저장소는 저자의 이전 연구 노트이며, 내용은 [7번 논문](https://github.com/inha20/7KarnaughGroupClassification)(수학)과 [8번 논문](https://github.com/inha20/8StructuralThinkingAndHumanAICollaboration)(이론과 사례)으로 정리·정정되었습니다. 일부 서술과 옛 포털에는 정정 전 내용이 있을 수 있으니 인용은 7·8번을 사용해 주세요.

# Structure Recognition Theory

**Theoretical Hub — Structure Recognition Research Program**

> How do humans come to see something new?

---

## Abstract

This repository develops a theoretical framework for understanding how humans discover structures, assign meaning to them, generate research questions, and initiate research programs. Originating from empirical observations of Karnaugh map visual patterns, symmetric Boolean functions, and variable rearrangement invariance, Structure Recognition Theory (SRT) proposes ten exploratory hypotheses (H1–H10) addressing the research generation process and its second-order effects: from perceiving a difference, to attending to structure, to detecting explanatory significance, to formulating a research question, and to how completed research expands a researcher's perceptual field (H8–H10, integrated expansion hypotheses). The framework also models Human-AI collaborative discovery as a division of cognitive labor. **Current version: SRT v0.3** (formal definitions for Structure, Attention, and Explanatory Significance; H4 operationalized; empirical research design included).

---

## Keywords

structure recognition, structure discovery, human cognition, research generation, concept evolution, human-AI collaboration, Boolean function, Karnaugh map, pattern discovery, explanatory significance, research worthiness, meaning attribution

---

## Overview

This repository develops a theoretical framework for understanding how humans discover structures, assign meaning to them, generate research questions, and initiate research programs.

The project originated from empirical observations of Karnaugh maps, symmetric Boolean functions, and variable rearrangement invariance, and has evolved into a broader investigation of:

- Structure discovery and meaning attribution
- Research question generation
- Concept evolution
- Human-AI collaborative discovery

---

## Core Research Question

> How do humans discover structures, assign meaning to them, generate questions, and initiate research?

---

## Research Generation Framework

```
Difference
→ Attention
→ Structure
→ Meaning
→ Research Worthiness
→ Question
→ Research
```

## Concept Evolution Framework

```
Phenomenon
→ Concept
→ Expanded Perception
→ New Observation
→ New Concept
```

These two cycles are proposed to interact as part of a unified research generation process.

---

## Research Program

This repository is part of a broader research program:

| Repository | Focus | Role |
|---|---|---|
| Repository 1 | Karnaugh Map Visual Pattern Analysis | Empirical observations |
| Repository 2 | Symmetric Boolean Function Visual Patterns | Structural examples |
| Repository 3 | Variable Rearrangement Invariance | Invariance-related observations |
| **Repository 4** | **Structure Recognition Theory** | Central theoretical framework |

Repository 4 serves as the **theoretical hub** of the program.
Repositories 1–3 provide empirical material; this repository proposes explanatory frameworks.

### Research Branches

| Branch | Focus |
|---|---|
| 1. Karnaugh Map Research | Visual pattern recognition, Boolean representations |
| 2. Symmetric Boolean Functions | Variable-exchange invariance, weight-layer structures |
| 3. Variable Rearrangement Invariance | Structural preservation, invariant properties |
| 4. Structure Recognition Theory | Structure discovery, meaning attribution, question generation |
| 5. Human-AI Collaboration | Comparative strengths, collaborative discovery |
| 6. AI Collaboration Education | Human-AI role division, educational frameworks |
| 7. Structure-Based Elementary Mathematics | Pattern, structure, and meaning in elementary mathematics |
| Paper 6. Boolean Function Space Theory | Function-space classification, S4 orbit structure |

---

## Repository Structure

```
.
├── README.md
├── HANDOVER.md
├── CHANGELOG.md
├── index.html
└── theory/                    Core theory documents (full versions, kept in this repository)
    ├── Hypotheses.md          H1–H10, full text
    ├── CoreQuestions.md       v2.0 — Q1–Q15, Level 0–8
    └── OpenProblems.md        v1.1 — OP-01–OP-09
```

> **통합 안내 (2026-06-21 확인, Session 31; 이후 점검으로 정정):** SRT 본문(v0.1–v0.3), `CaseStudyConnections.md`, `ResearchMap.md`, `research-notes/`, `future-papers/`, `research-history/`, `drafts/`는 2026-06-20~21에 이 저장소에서 삭제되었습니다. [`inha20`](https://github.com/inha20/inha20) 저장소에는 `theory/` 폴더나 `*_Summary.md` 파일이 올라간 적이 없으며, 내용은 일부만 다음 위치로 이어져 있습니다: SRT 본문의 압축본은 [`inha20/StructureRecognitionTheory_Unified.md`](https://github.com/inha20/inha20/blob/main/StructureRecognitionTheory_Unified.md)(공식 정의 3.1–3.3, H1–H10 요약, H4 연산화, 실증 연구 설계), `CaseStudyConnections.md`는 [`HANDOVER.md`](HANDOVER.md)의 "How Papers 1–3 Connect to SRT" 표(압축본), `ResearchMap.md`의 질문 위계와 `drafts/`의 Level 6–8은 [`theory/CoreQuestions.md`](theory/CoreQuestions.md), `research-notes/`의 가설 진술과 `drafts/`의 H8–H10은 [`theory/Hypotheses.md`](theory/Hypotheses.md)에 요약·반영되어 있습니다. 그 밖의 내용(`future-papers/`, `research-history/` 등)과 모든 원문 전체는 이 저장소의 git 이력에서만 확인할 수 있습니다(삭제 직전 커밋 목록은 [`HANDOVER.md`](HANDOVER.md) 상단 "업데이트 안내" 참고). 이 저장소에는 통합 이전부터 있던 `Hypotheses.md`, `CoreQuestions.md`, `OpenProblems.md`(전체 버전)만 그대로 남아 있습니다. 아래 "Core Theory Documents" 섹션을 참고하세요.

---

## Key Research Areas

H1–H10에 대한 개별 해설 문서(과거 `research-notes/` 하위의 개념별 파일들)는 [`theory/Hypotheses.md`](theory/Hypotheses.md) 한 문서로 요약되어 있습니다(개별 해설 원문은 삭제되어 git 이력 `ee7f2a5^`에서만 확인할 수 있습니다). 카테고리별로 다음 가설들을 다룹니다:

- **Structure Discovery:** H1 (Structure Discoverer), H2 (Representation Transformation)
- **Research Generation:** H3 (Attention Filter), H4 (Significance Filter), H5 (Explanation Anticipation), H6 (Explanatory Significance), H7 (Mature Structure Discoverer)
- **Concept Evolution:** H8 (Concept-as-Lens), H9 (Concept Evolution), H10 (Generative Concept)
- **Human-AI Collaboration:** H1·H7(인간–AI 역할 구분 가설) 및 `5HumanAIResearchCollaboration` 저장소 참고

개념 계보(Concept Genealogy)의 압축본은 [`inha20/SESSION_START.md`](https://github.com/inha20/inha20/blob/main/SESSION_START.md)의 "Concept Genealogy" 절에서 관리됩니다(7단계 전체 서술본은 삭제되어 `Research-Portfolio` 저장소의 git 이력 `15f97ad^:ConceptGenealogy.md`에서만 확인할 수 있습니다).

---

## Future Papers

이 저장소의 `future-papers/` 폴더(SRT 논문 아웃라인·로드맵)는 2026-06-20에 삭제되었고 원문은 git 이력 `8cd8d72^`에서만 확인할 수 있습니다. 현재 남아 있는 후속 연구 개요는 [`inha20/HumanAICollaborationProposal_Outline.md`](https://github.com/inha20/inha20/blob/main/HumanAICollaborationProposal_Outline.md)(Paper 4 × Paper 5 교차 연구 제안서 초안)이며, 프로그램 전체의 작업 현황(Active Queue)과 저장소 상태 표(Repository Health)는 [`inha20/SESSION_START.md`](https://github.com/inha20/inha20/blob/main/SESSION_START.md)에서 확인할 수 있습니다.

---

## Core Theory Documents

**이 저장소에 전체 버전으로 남아 있는 문서:**

- [Hypotheses](theory/Hypotheses.md) — H1–H10 organized hypotheses (H8–H10: second-order integrated expansion)
- [Core Questions](theory/CoreQuestions.md) — Research question hierarchy (v2.0, Q1–Q15, Level 0–8)
- [Open Problems](theory/OpenProblems.md) — OP-01–OP-09
- [CHANGELOG](CHANGELOG.md) — Version history

**압축되어 `inha20` 저장소에 요약본으로 남아 있는 문서** (SRT 본문 v0.1–v0.3의 압축본; 전문은 이 저장소의 git 이력 `b47a27e^`, `fb99794^`, `677bf7e^`):

- [SRT Unified Summary](https://github.com/inha20/inha20/blob/main/StructureRecognitionTheory_Unified.md) — 공식 정의 3.1–3.3, H1–H10 요약, H4 연산화, 실증 연구 설계(§10), Level 0–8 질문 위계, OP-01–OP-09 요약 포함 (구 SRT·Hypotheses·Core Questions 요약본 세 개를 합친 단일 문서이며 Q1–Q15 번호 체계는 없으므로 Q1–Q15와 전문은 이 저장소의 `theory/` 문서 참고)

> Paper 1–3과 SRT의 연결(구 `CaseStudyConnections.md`)은 [`HANDOVER.md`](HANDOVER.md)의 "How Papers 1–3 Connect to SRT" 표에 보존되어 있습니다.

---

## Current Status

This repository represents an **active early-stage theoretical framework**.

All hypotheses should be treated as:
- exploratory propositions
- conceptual models
- research directions

rather than established conclusions.

---

## Long-Term Vision

To develop a unified framework connecting:

- Structure Discovery
- Meaning Attribution
- Question Generation
- Concept Evolution
- Human-AI Collaboration
- AI Collaboration Education

---

---

## Research Program Links

This repository is part of the **Structure Recognition Research Program**.

| Repository | Role |
|---|---|
| [Research-Portfolio](https://github.com/inha20/Research-Portfolio) | Program Hub |
| [1KMapStructureInvariance](https://github.com/inha20/1KMapStructureInvariance) | Empirical Case Study 1 |
| [2SymmetricBooleanFunctionMinorThesis](https://github.com/inha20/2SymmetricBooleanFunctionMinorThesis) | Empirical Case Study 2 |
| [3VariableRearrangementInvarianceMinorThesis](https://github.com/inha20/3VariableRearrangementInvarianceMinorThesis) | Empirical Case Study 3 |
| [4StructureRecognitionTheory](https://github.com/inha20/4StructureRecognitionTheory) | Theoretical Hub ← You are here |

**AI 단일 진입점:** [SESSION_START.md](https://github.com/inha20/inha20/blob/main/SESSION_START.md)

---

## Author

Choi Jonghun
Independent researcher · 2nd-year student at Inha Technical College
