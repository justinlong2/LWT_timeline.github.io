---
layout: default
title: Project Schedule
nav_exclude: true
---

# Project Implementation Schedule

| Phase | Task | Start Date | End Date | Status |
| :--- | :--- | :---: | :---: | :--- |
| **Phase 1: First Expert Review** | Feedback Integration | 03-01 | 04-01 | 🟡 In Progress |
| | Expert Review Preparation | 03-15 | 04-06 | 🟡 In Progress |
| | Expert Review Recruitment (1) | 03-01 | 04-01 | 🟡 In Progress |
| | Expert Review (1) | 04-07 | 04-21 | ⚪ Pending |
| | Revisions based on Expert Review (1) | 04-21 | 05-11 | ⚪ Pending |
| **Phase 2: LWT Async Review** | LWT Critical Review | 05-11 | 05-14 | ⚪ Pending |
| | LWT signs off | 05-14 | 05-15 | ⚪ Pending |
| **Phase 3: LWT Revision** | Instructure Revises Materials | 05-15 | 06-15 | ⚪ Pending |
| | LWT signs off | 06-15 | 06-17 | ⚪ Pending |
| | Expert Review Doc Finalized | 06-15 | 06-17 | ⚪ Pending |
| **Phase 4: Second Expert Review** | Expert Review (2) | 06-18 | 06-30 | ⚪ Pending |
| | Revisions based on Review (2) | 07-01 | 07-30 | ⚪ Pending |
| | LWT signs off | 07-30 | 07-31 | ⚪ Pending |
| **Phase 5: Finalization** | LWT Production | 07-01 | 07-31 | ⚪ Pending |
| | LWT Pouring Stage | 08-01 | 09-01 | ⚪ Pending |

> **Notes:**
> - **First ER:** Focuses on construct map and test blue print.
> - **Second ER:** Focuses on items and test booklet.

---

## Project Timeline (Gantt Chart)

<div style="overflow-x: auto;">

```mermaid
%%{init: {'theme': 'base', 'gantt': {'leftPadding': 150}}}%%
gantt
    title Project Schedule 2026
    dateFormat YYYY-MM-DD
    axisFormat %b %d

    section Phase 1: Expert Reviews
    Feedback Integration                  :active, p1, 2026-03-01, 2026-04-01
    Expert Review Preparation             :active, p2, 2026-03-15, 2026-04-06
    Expert Review Recruitment (1)         :active, p3, 2026-03-01, 2026-04-01
    Expert Review (1)                     :p4, 2026-04-07, 2026-04-21
    Revisions (1)                         :p5, 2026-04-21, 2026-05-11

    section Phase 2: LWT Async Review
    LWT Critical Review                   :p6, 2026-05-11, 2026-05-14
    LWT signs off                         :p7, 2026-05-14, 2026-05-15

    section Phase 3: LWT Revision
    Instructure Revises Materials         :p8, 2026-05-15, 2026-06-15
    LWT signs off                         :p9, 2026-06-15, 2026-06-17
    ER Doc Finalized                      :p10, 2026-06-15, 2026-06-17

    section Phase 4: Second Expert Review
    Expert Review (2)                     :p11, 2026-06-18, 2026-06-30
    Revisions (2)                         :p12, 2026-07-01, 2026-07-30
    LWT signs off                         :p13, 2026-07-30, 2026-07-31

    section Phase 5: Finalization
    LWT Production                        :p14, 2026-07-01, 2026-07-31
    LWT Pouring Stage                     :p15, 2026-08-01, 2026-09-01
