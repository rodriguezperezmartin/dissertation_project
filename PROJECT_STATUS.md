# Project Status — Start Here

**Last updated:** 2026-09-14

This is the single "load this first" file for the dissertation project. Read this before anything else to get fully oriented in one pass — no need to piece the story together from scattered files each session.

---

## 1. Where Things Stand Right Now
- **PhD status:** Year 1, Fall 2026 semester — currently in **PLCY 700: Foundations of Public Policy**
- **Target graduation:** Fall 2029 (full sequence in [roadmap/degree_plan.md](roadmap/degree_plan.md))
- **Courses completed:** none yet (first semester in progress)
- **Current week in PLCY 700:** Week 3 (book review discussion assignment submitted)

## 2. Dissertation Objective (Working)

**Goals drive the work, not the other way around.** Every choice about topic scope, methodology, and case studies is checked against these goals first (full detail: [dissertation/topic_overview.md](dissertation/topic_overview.md), §"Purpose & Personal Calling"):
1. Modernize healthcare infrastructure using an enterprise AI/MLOps background, particularly in emerging economies.
2. Establish digital infrastructure as a prerequisite for fiscal transparency, efficient health policy, and economic resilience.
3. Transition into government service/diplomacy (target: Foreign Service Officer or Chief Data Officer, Dept. of State or Dept. of Defense).
4. Global impact — help emerging economies achieve systemic modernization and financial independence.
5. Faith-driven motivation — using God-given skills to serve humanity's physical (healthcare) and spiritual needs.

**Working title:** Healthcare Digital Infrastructure as a Driver of Public Policy Outcomes in Emerging Economies

**Current leading research question (as of 2026-09-14):** To what extent does the implementation of predictive AI models and interoperable digital health architectures reduce reactive crisis spending in public health interventions within emerging economies? ("Leapfrog Advantage & AI Integration" angle)

**Original broader framing (2026-09-13, superseded as leading question but kept as context):** Does investing in systematic processes that enable nations to capture patient health data lead to better public health policy, and does that policy in turn improve citizens' quality of life and economic resilience?

**Core thesis:** Health should be framed as a driver of human capital and economic growth, not just a medical/humanitarian issue. Emerging economies can leapfrog legacy health IT constraints to build agile digital health infrastructure. The core gap: monitoring & evaluation (M&E) is almost always an afterthought in health policy interventions rather than designed in from the start.

Full detail: [dissertation/topic_overview.md](dissertation/topic_overview.md)
Question evolution over time: [dissertation/research_questions.md](dissertation/research_questions.md)

## 3. Methodology (Evolving)
**Primary approach:** analyze the research question using **existing empirical data** — published sources, historical policy interventions, and economic datasets — to measure how digital health/AI interventions shift government/NGO spending from reactive to proactive. This is the required, sufficient evidence base for the dissertation; the formal quantitative/qualitative methods will be finalized via the Research Methods & Tools courses (PLCY 805, 809, 810, 811, 812) in 2027-2028, followed by Research Concept (PLCY 885) and Dissertation I-IV in 2029. Likely a **mixed-methods** approach (quantitative health/economic indicators + qualitative policy case studies).

**Optional stretch goal:** if time permits, engineer a proof-of-concept (e.g., a first-world predictive model fine-tuned for a third-world context, a RAG framework, or a synthetic clinical data pipeline) to supplement — not replace — the empirical analysis. See [dissertation/topic_overview.md](dissertation/topic_overview.md) §"Dissertation Methodology Approach" for the full rationale.

## 4. Approach / Strategy
Every course assignment where topic choice is allowed is deliberately steered toward the dissertation focus area, so coursework compounds into the dissertation instead of being disconnected. Two literature tracks are kept separate:
- **[dissertation/literature_review/direct_sources/](dissertation/literature_review/direct_sources/)** — directly about the topic (currently: Weiss 1991, chosen for PLCY 700 Module 6 book review)
- **[dissertation/literature_review/indirect_sources/](dissertation/literature_review/indirect_sources/)** — coursework/methodology skill-building sources (currently: Marotta 2021)

Professor feedback and Liberty's implicit/explicit evaluation criteria are tracked centrally in [feedback_log/feedback_tracker.md](feedback_log/feedback_tracker.md).

## 5. Session Log
_Add a dated entry every session so future sessions pick up instantly. Keep each entry to 2-4 lines._

- **2026-09-13:** Repo structure established (`coursework/`, `dissertation/`, `roadmap/`, `program_info/`, `feedback_log/`). README index created. Fixed GitHub SSH auth (repo now pushes correctly via `github.com-personal` host alias).
- **2026-09-14:** Logged PLCY 700 Week 3 discussion assignment + 2 replies + Dr. Boykin's feedback. Split literature review into `direct_sources/` vs `indirect_sources/`. Uploaded first source PDF (Marotta, 2021). Created this status file.
- **2026-09-14:** Reorganized `coursework/PLCY700/` so each week is self-contained (`weekNN/assignments/`, `weekNN/feedback/`) instead of one shared `assignments/`/`feedback/` per course. Moved Week 3 files accordingly and renamed them (dropped redundant `week3_` prefix since it's implied by the folder path). Standardized week folder names to lowercase, zero-padded (`week01`, `week02`, `week03`). Updated all cross-references in README, feedback tracker, and literature review bibliographies.
- **2026-09-14:** Added a course-level study aid layer: `coursework/<COURSE>/course_overview.md` (quick-scan course guide with aggregate objectives, weekly map, dissertation tie-ins) linking down to each week's `learning_objectives.md` (detailed study guide), which in turn links to that week's assignments/feedback. Filled in for PLCY 700.
- **2026-09-14:** Full repo audit — verified all cross-references/links across README, PROJECT_STATUS, coursework, dissertation, and feedback files are correct (no broken links found). Added a "Purpose & Personal Calling" section to `dissertation/topic_overview.md` capturing career/life/faith-driven goals (healthcare infrastructure modernization, government service/diplomacy — Foreign Service Officer/Chief Data Officer, global impact, faith motivation) so the dissertation topic is explicitly anchored to and driven by these goals rather than the reverse.
- **2026-09-14:** Added Week 3 study aid — `walliman_research_methodology_study_aid.md` (converted from uploaded docx) covering levels of measurement, statements vs. arguments, deductive/inductive reasoning, and logical fallacies. Linked from `week03/learning_objectives.md` and noted in `course_overview.md`'s weekly map.
- **2026-09-14:** Corrected placement — the Walliman study aid is actually quiz findings/analysis, so it belongs in `week03/assignments/`, not the week root. Moved it there and fixed links. Rule going forward: each week has exactly one `learning_objectives.md` (the week's overview/study guide); anything derived from a quiz, discussion, or other graded/completed activity goes in that week's `assignments/`.
- **2026-09-14:** Added `original_src_files/` as a standard per-week subfolder — all original uploaded files (docx, etc.) are archived there, keeping `assignments/` and `feedback/` as clean, markdown-only, git-friendly conversions. Moved the two existing Week 3 docx files there and updated references.
- **2026-09-14:** Applied the full week structure (`assignments/`, `feedback/`, `original_src_files/`) to `week01` and `week02` for consistency. Created [coursework/_templates/COURSEWORK_STRUCTURE.md](coursework/_templates/COURSEWORK_STRUCTURE.md) as the canonical, documented standard for every course/week going forward — apply automatically to new courses/weeks without being asked.
- **2026-09-14:** Created `week04` folder structure and `learning_objectives.md` from Dr. Boykin's Module 4 announcement: literature review assignment (10 academic sources, organized topically, APA citations), learning outcomes (evaluate literature, develop research questions, policy agendas, distributive/regulatory/redistributive policy). Flagged as a strong opportunity to align the Week 4 literature review directly with the dissertation topic. Updated `course_overview.md` weekly map + aggregate objectives.
- **2026-09-14:** Created `week05` (placeholder) and `week06` folder structures. Logged the Module 6 book review book selection in `week06/learning_objectives.md`: Weiss (1991), *Organizations for Policy Analysis: Helping Government Think*, chosen for its alignment with the dissertation's digital healthcare infrastructure/data-driven policy focus.
- **2026-09-14:** Replaced Week 4's preliminary assignment note with the official "Literature Assessment and Research Question" instructions and full grading rubric (100+ pts across 7 criteria) in `week04/learning_objectives.md`. Logged the rubric's evaluation criteria — notably the "3+ items = advanced" pattern on content criteria — into `feedback_log/feedback_tracker.md`.
- **2026-09-14:** Selected Week 4 Literature Assessment topic: "Leapfrog Advantage & AI Integration" — predictive AI + interoperable digital health architectures reducing reactive crisis spending in emerging economies. Logged as a refined research question candidate in `dissertation/research_questions.md`, updated `week04/learning_objectives.md` with the full rationale and search strategy (keywords, 3 focus areas for the 10-source search via Jerry Falwell Library), and updated `course_overview.md` dissertation tie-ins.
- **2026-09-14:** Confirmed the "Leapfrog Advantage & AI Integration" question as the **current leading research question** (not just a candidate) across `research_questions.md`, `topic_overview.md`, `PROJECT_STATUS.md`, and `README.md`. Original broader framing kept as historical context in the evolution log.
- **2026-09-14:** Clarified dissertation methodology scope (worked through with Gemini as research assistant): the dissertation's primary, required evidence base is **existing empirical/published data** analyzed to prove the economic case; building an engineering proof-of-concept (fine-tuned AI model, RAG framework, synthetic data pipeline) is an optional **stretch-goal bonus**, not a substitute. Added "Dissertation Methodology Approach" section to `topic_overview.md`, updated `PROJECT_STATUS.md` §3 and Next Actions, and added a methodology note to `research_questions.md`.
- **2026-09-17:** Confirmed all 10 Week 4 Literature Assessment sources collected (PDFs in `direct_sources/files/`, list finalized in `week04/original_src_files/Selection of Online Academic Journals.docx`). Logged all 10 into `dissertation/literature_review/direct_sources/annotated_bibliography.md`. Drafted rubric-aligned analysis: `week04/assignments/rubric_notes_outline.md` (notes mapped to each grading criterion) and `week04/assignments/literature_assessment_findings.md` (themes, weaknesses, implications, and a draft research question). Key finding: none of the 10 sources measure economic/financial outcomes directly, and Beaulieu & Bentahar (2021, healthcare supply chain digitalization) is the closest existing precedent to the dissertation's reactive-to-proactive spending mechanism.
- **2026-09-17:** Extracted page-numbered text from all 10 source PDFs (via PyMuPDF) and added direct, page-cited supporting quotes (4 per finding) throughout `literature_assessment_findings.md` for every theme, weakness, and implication — so the final 2,000-2,500 word paper can be drafted from quotes/citations already on hand rather than re-reading full PDFs. Flagged that Handtke (PLOS ONE) and the Joseph health migrations article lack fixed print pagination; full citation details for those two still need verification directly from the PDFs.
- **2026-09-19:** Final Week 4 paper (`Final_Literature_Review_Assignment.docx`) uploaded and converted to `assignments/final_literature_review.md`; added a complete, verified APA 7 reference list (DOIs extracted directly from each PDF, not guessed) replacing the "(pending)" placeholder, and fixed the "[Insert Year]" placeholder for Alraja (2022). **Flag:** the final paper's in-text citations only reference 9 of the 10 selected sources — Joseph (health migrations) is never cited in the body text, so it's correctly omitted from the APA reference list, but this may fall short of the assignment's "10 sources" requirement unless Joseph is worked into the prose before submission.

## 6. Next Actions
- [ ] Continue PLCY 700 Week 3 replies grading / Week 4 materials once released
- [ ] Acquire Weiss (1991) PDF/copy for `direct_sources/files/`
- [ ] Begin drafting Module 6 book review (Weiss) once course reaches that point
- [ ] Keep feeding professor feedback into `feedback_log/feedback_tracker.md` as it arrives
- [ ] Choose a Week 4 literature review topic aligned with the dissertation focus (healthcare digital infrastructure / DPI / M&E) and source 10 peer-reviewed articles
- [ ] Search for and source 10 peer-reviewed articles for the Week 4 "Leapfrog Advantage & AI Integration" topic (keywords: predictive AI public health, interoperable health systems, technology leapfrogging emerging markets, healthcare resource allocation, crisis spending) — **done, all 10 collected**
- [ ] Log each Week 4 literature review source into `dissertation/literature_review/direct_sources/annotated_bibliography.md` as it's read — **done**
- [ ] Draft Week 4 Literature Assessment (2,000-2,500 words, APA) covering 3+ common themes, 3+ gaps/weaknesses, 3+ research implications, ending in a testable/falsifiable research question — **final draft complete with references**; still need to (a) decide whether to work Joseph (health migrations) into the prose to satisfy the 10-source requirement, (b) paste the finalized reference list into the actual Word doc before submission, (c) verify word count is within 2,000-2,500
- [ ] Verify/complete APA citations for sources missing full author/year/journal details (Sharp, Joseph, "Challenges to Implementing AI," Coombs) directly against their PDFs
- [ ] (Stretch/Bonus, not required) Explore building a proof-of-concept — e.g., a fine-tuned predictive model or RAG pipeline for third-world clinical data — only after the empirical analysis approach is on track

## 7. Standing Maintenance Rule (Do This Automatically — Don't Wait to Be Asked)
Folder/file structure for all coursework follows [coursework/_templates/COURSEWORK_STRUCTURE.md](coursework/_templates/COURSEWORK_STRUCTURE.md) — the canonical spec. Apply it to every new course and week without being asked.

Whenever an assignment, reply, or feedback item is added/completed for a given week, update **without being explicitly told**:
1. `coursework/<COURSE>/weekNN/learning_objectives.md` — mark the week's status/content current, confirm Quick Links point to the new file(s).
2. `coursework/<COURSE>/course_overview.md` — update that week's row in the Weekly Map table (status, topic) and the aggregate objectives list if new ones were introduced.
3. `feedback_log/feedback_tracker.md` — add a row if new professor feedback came in.
4. `dissertation/literature_review/direct_sources/` or `indirect_sources/` — add a bibliography entry if a new source was read.
5. `README.md` — add links for any newly created files/folders.
6. This file's **Session Log** (§5) and **Next Actions** (§6) — add a dated entry and refresh the to-do list.

---

## Full Navigation
See [README.md](README.md) for the complete repository index.
