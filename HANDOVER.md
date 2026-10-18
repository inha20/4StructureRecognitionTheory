# Handover Guide — Structure Recognition Theory

**Repository:** 4StructureRecognitionTheory
**Version:** 2.2
**Date:** 2026-06-21
**Role:** Theoretical Hub of the Structure Recognition Research Program
**Updated by:** Session 31 (broken-reference correction after `inha20` theory-document consolidation)

---

## Purpose of This Document

This guide ensures that any future contributor — human or AI — can continue developing this repository without losing the conceptual thread that connects its contents.

---

## ⚠️ 2026-06-21 업데이트 안내 (Session 31)

이전 버전(v2.0, Session 26)은 `theory/StructureRecognitionTheory_v0.1–v0.3.md`, `CaseStudyConnections.md`, `research-notes/`, `future-papers/`, `research-history/`, `drafts/`가 이 저장소에 존재하는 것처럼 기술하고 있었으나, 실제로는 이 파일들이 이 저장소에서 삭제되어 있었고(2026-06-20~21), 내용 일부만 **`inha20` 저장소의 압축본 `StructureRecognitionTheory_Unified.md`** 등으로 이어져 있었으며, 이 문서가 그 사실을 반영하지 못해 발생한 불일치였습니다(연구자 확인, 2026-06-21). 이후 점검에서 `inha20` GitHub 저장소에는 `theory/` 폴더와 `*_Summary.md` 파일이 올라간 적이 없음이 확인되어 아래 항목을 정정했습니다.

- **이 저장소에 그대로 남아있는 전체 문서:** `theory/Hypotheses.md`, `theory/CoreQuestions.md`, `theory/OpenProblems.md`
- **`inha20`의 통합 요약 문서:** [`inha20/StructureRecognitionTheory_Unified.md`](https://github.com/inha20/inha20/blob/main/StructureRecognitionTheory_Unified.md) — 구 `SRT_Summary.md`, `Hypotheses_Summary.md`, `CoreQuestions_Summary.md` 세 요약본을 하나로 합친 문서 (공식 정의 3.1–3.3, H1–H10 요약, Level 0–8 질문 위계, OP-01–09 요약 포함 — 압축본이며 Q1–Q15 번호 체계는 없으므로 Q1–Q15는 이 저장소의 `theory/CoreQuestions.md` 참고)
- **이 저장소의 git 이력에서만 복원 가능한 내용:** `CaseStudyConnections.md`의 세부 버전(요약은 본 문서의 "How Papers 1–3 Connect to SRT" 표에 보존; 원문 `7c8ef5f^:theory/CaseStudyConnections.md`), `ResearchMap.md`(`d00a8c6^:theory/ResearchMap.md`; 질문 위계는 `theory/CoreQuestions.md`에 남아 있음), `research-notes/`의 개별 가설 해설 파일들(`ee7f2a5^:research-notes/`), `future-papers/`의 논문 아웃라인/로드맵(`8cd8d72^:future-papers/`), `research-history/`의 타임라인(`fa8fd2b^:research-history/`), `drafts/`(`f3042a5^:drafts/`), SRT 본문 v0.1–v0.3(`b47a27e^`, `fb99794^`, `677bf7e^`의 `theory/StructureRecognitionTheory_v0.1.md`, `_v0.2.md`, `_v0.3.md`). 별도 백업을 찾을 필요 없이 `git show <커밋>^:<경로>`로 읽을 수 있습니다.

이하 본문은 이 사실을 반영해 수정되었습니다.

---

## What This Repository Is

This repository develops **Structure Recognition Theory (SRT)**, a theoretical framework for understanding:

1. How humans discover structures
2. How humans assign meaning to them
3. How humans generate research questions
4. How concept evolution enables new observations

It is the **theoretical integration point** of a research program built on three empirical case studies (Papers 1–3). Paper 4 proposes the explanatory framework that accounts for why those phenomena became research-worthy.

---

## The Core Question (Two Levels)

**Program level:**
> **How do humans come to see something new?**

**Theory level:**
> **How do humans detect explanatory significance?**

This question evolved through these stages:

| Stage | Question | Conceptual Enabler |
|---|---|---|
| Initial | Why does this checkerboard appear? | Karnaugh map as visualization tool |
| Early | Why do humans recognize patterns as structures? | Distinction between *pattern* and *structure* |
| Middle | Why do humans discover structures? | Concept of *discovery* as distinct from *recognition* |
| Later | Why do certain structures feel worth investigating? | Concept of *significance filter* (H4) |
| Current | How do humans detect explanatory significance? | Concept of *explanatory significance* (H6) |
| Program-level | How do humans come to see something new? | Concept of *concept as lens* (H8) |

Do not bypass this evolution. The sequence is itself a research finding (Concept Evolution Cycle, H9).

---

## Current Theory State — SRT v0.3

**Compressed theory document (current authoritative summary):** [`inha20/StructureRecognitionTheory_Unified.md`](https://github.com/inha20/inha20/blob/main/StructureRecognitionTheory_Unified.md) — contains Definitions 3.1–3.3, the H1–H10 summary, H4 operationalization, and the §10 empirical research designs; the "Four-Paper Architecture (Architecture B)" is in [`inha20/SESSION_START.md`](https://github.com/inha20/inha20/blob/main/SESSION_START.md). The full v0.3 text (712 lines) exists only in git history (`677bf7e^:theory/StructureRecognitionTheory_v0.3.md`).
**Locally in this repository:** `theory/Hypotheses.md` (H1–H10 full text), `theory/CoreQuestions.md` (v2.0, Q1–Q15), `theory/OpenProblems.md` (v1.1, OP-01–09).
**Historical SRT draft versions (v0.1, v0.2, v0.3):** removed from this repository on 2026-06-21; recoverable from this repository's git history (`b47a27e^:theory/StructureRecognitionTheory_v0.1.md`, `fb99794^:theory/StructureRecognitionTheory_v0.2.md`, `677bf7e^:theory/StructureRecognitionTheory_v0.3.md`).

### Key additions in v0.3 (Session 11–12, 2026-06-06)
- **Section 3: Formal Definitions** — Structure, Attention, Explanatory Significance (Definitions 3.1–3.3)
- **H4 operationalization** — compression, prediction, generalization, explanation pull (4 formal criteria)
- **Section 10: Empirical Research Design Proposals** — H1, H5, H6 each have a testable paradigm
- **H8–H10 elevated** to integrated extension hypotheses

---

## The Hypotheses — H1–H10 (Current)

All are **exploratory**. None are established conclusions.

| # | Name | Core Claim | Status |
|---|---|---|---|
| H1 | Structure Discoverer | Human advantage in structure discovery over AI | Exploratory |
| H2 | Representation Transformation | Representation change enables structure discovery | Supported by observations |
| H3 | Attention Filter | Not all patterns receive investigative attention | Exploratory |
| H4 | Significance Filter | Implicit "worth investigating?" filter | Exploratory — formally operationalized in v0.3 |
| H5 | Explanation Anticipation | Humans feel explanation should exist before finding it | Exploratory |
| H6 | Explanatory Significance | Research begins from detecting explanatory potential | Exploratory |
| H7 | Mature Structure Discoverer | Core human role = detecting explanation opportunity | Exploratory revision of H1 |
| **H8** | **Concept-as-Lens** | **Concepts function as observation lenses — changing what is visible** | **통합 확장 가설 — SRT v0.3 승격** |
| **H9** | **Concept Evolution** | **Research generates concepts; concepts generate further research** | **통합 확장 가설 — SRT v0.3 승격** |
| **H10** | **Generative Concept** | **Concepts differ in their generativity** | **통합 확장 가설 — SRT v0.3 승격** |

**Critical rule:** These are all exploratory. Do not present any as established conclusions.

---

## Core Question Hierarchy — v2.0 (Q1–Q15, Level 0–8)

Full hierarchy documented in: `theory/CoreQuestions.md` v2.0 (this repository) / `inha20/StructureRecognitionTheory_Unified.md` §1 (compressed Level 0–8 table; no Q1–Q15 numbering)

| Level | Focus | Questions |
|---|---|---|
| 0 | Observation | Q0.1–Q0.4 |
| 1 | Structure | Q1.1–Q1.5 |
| 2 | Discovery | Q2.1–Q2.5 |
| 3 | Significance | Q3.1–Q3.6 |
| 4 | Question Generation | Q4.1–Q4.6 |
| 5 | Explanation | Q5.1–Q5.6 |
| 6 | Concept | Q6.1–Q6.5 |
| 7 | Expanded Perception | Q7.1–Q7.5 |
| 8 | New Discovery | Q8.1–Q8.5 |

---

## Open Problems — OP-01–OP-09

Formally documented in: `theory/OpenProblems.md` (this repository) v1.1

| ID | Problem |
|---|---|
| OP-01 | The Attention Selection Problem |
| OP-02 | The Significance Boundary Problem |
| OP-03 | The Explanation Anticipation Mechanism |
| OP-04 | The Representation Design Problem |
| OP-05 | Invariance as significance criterion |
| OP-06 | AI role in structure discovery |
| OP-07 | The Concept-as-Lens Problem (concept generativity, H10) |
| OP-08 | The Research Question Origin Problem |
| OP-09 | Definition 3.3 necessity conditions |

---

## Repository Structure (Actual Current State, verified 2026-06-21)

```
4StructureRecognitionTheory/
├── README.md                           ← Program overview, navigation
├── CHANGELOG.md                        ← Version history (current: v0.5.0)
├── HANDOVER.md                         ← This file (v2.1)
└── theory/                             ← Core theory documents kept locally
    ├── Hypotheses.md                   ← H1–H10 (full text)
    ├── CoreQuestions.md                ← v2.0 (Level 0–8, Q1–Q15)
    └── OpenProblems.md                 ← v1.1 (OP-01–OP-09)
```

> **Note:** SRT body text (v0.1–v0.3), `CaseStudyConnections.md`, `ResearchMap.md`, and the `research-notes/`, `future-papers/`, `research-history/`, `drafts/` directories described in older versions of this document do **not** exist in the current local repository. They were deleted on 2026-06-20/21: the SRT body survives only as the compressed `inha20/StructureRecognitionTheory_Unified.md`, the case-study mapping as the table below, and the question hierarchy / hypotheses inside `theory/CoreQuestions.md` and `theory/Hypotheses.md`; everything else is recoverable only from this repository's git history (commit list in the update notice above). Do not reference those old paths as if they were local files in this repository.

---

## How Papers 1–3 Connect to SRT

| Paper | Key Observation | Connects To |
|---|---|---|
| Paper 1: KMap Patterns | Checkerboard patterns recognized immediately | H2 (representation reveals structure), H5 (explanation anticipated) |
| Paper 2: Symmetric Functions | Patterns perceived before Hamming Weight computed | H1 (structure discovered before computation), H2 |
| Paper 3: Variable Rearrangement | Invariance sought over change | H4 (invariance as significance criterion), H6 (explanatory potential) |

---

## For AI Collaborators

**Before working in this repository, read in this order:**

1. `inha20/SESSION_START.md` ← single authoritative AI entry point for the whole research program, including the current task queue ("Active Queue") and repository health table (the former `ProjectDashboard.md` was merged into it)
2. `inha20/StructureRecognitionTheory_Unified.md` ← current compressed theory version (authoritative for the full SRT picture)
3. `theory/Hypotheses.md` (this repository) ← H1–H10 full text
4. `theory/CoreQuestions.md` (this repository) v2.0 ← full question hierarchy

Do not begin making changes until you understand the distinction between:
- **Empirical observations** (from Papers 1–3, fixed)
- **Exploratory hypotheses** (H1–H10, current working theories)
- **Open problems** (OP-01–OP-09, deliberately unresolved)

---

## Development Guidelines

### What to Add
- Theory expansions connecting H8–H10 to empirical observations
- Empirical research design refinements (Section 10, currently only in the compressed `inha20/StructureRecognitionTheory_Unified.md` §4 and in git history `677bf7e^`)
- New Open Problems when new unresolved questions arise
- Case study connections between Papers 1–3 and H8–H10

### What Not to Add
- Established conclusions where only hypotheses are warranted
- Restructuring that destroys the concept genealogy
- References to `research-notes/`, `future-papers/`, `research-history/`, or `drafts/` as if they exist locally in this repository — they do not (see note above)

### Version Control
- Significant theory additions → update `inha20/StructureRecognitionTheory_Unified.md` (the current authoritative compressed location) + CHANGELOG entry here
- Minor corrections → update CHANGELOG only
- Always document the session number and date

---

## Change Log

| Version | Date | Change |
|---|---|---|
| 2.2 | 2026-06-21 | **Session 33 경로 현행화** — AI 읽기 순서에서 미존재로 확인된 `management/SESSION_START.md`, `management/WorkOrderQueue.md`, `management/ProjectStatus.md`, `theory/SRT_Summary.md` 4개 경로 제거. 현행 루트 위치 파일인 `SESSION_START.md`, `ProjectDashboard.md`, `StructureRecognitionTheory_Unified.md`로 교체. |
| 2.1 | 2026-06-21 | **Session 31 broken-reference correction** — discovered that `theory/StructureRecognitionTheory_v0.1–v0.3.md`, `CaseStudyConnections.md`, `ResearchMap.md`, `research-notes/`, `future-papers/`, `research-history/`, `drafts/` referenced throughout this document do not exist locally; researcher confirmed these were consolidated into `inha20/theory/*_Summary.md`. All references corrected to point to the actual current locations; "Repository Structure" section corrected to match verified reality; AI reading order updated to current `management/SESSION_START.md` entry point (supersedes old `MasterHandoverDocument.md` / `AIHandoverInstructions.md` paths, which were themselves retired in Session 30's management-folder consolidation). |
| 2.0 | 2026-06-20 | **Session 26 전면 업데이트** — v1.0 (2026-06-05) 이후 20+ 세션 분량의 표류 수정: H8–H10 추가; SRT v0.3 반영; CoreQuestions v2.0 (Q1–Q15, Level 0–8) 반영; OpenProblems OP-01–OP-09 반영; 구 파일 구조 제거 및 실제 현재 구조로 교체; 참조 경로 현행화 (MasterHandoverDocument 위치, ANTIGRAVITY README); 두 수준의 핵심 질문 명시 |
| 1.0 | 2026-06-05 | Initial creation |

---

*Last Updated: 2026-06-21 (v2.2 — Session 33: AI reading order paths corrected to current root-level files)*
*Cross-reference: inha20/SESSION_START.md, inha20/StructureRecognitionTheory_Unified.md*
