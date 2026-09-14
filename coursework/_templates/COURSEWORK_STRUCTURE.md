# Coursework Structure Standard

This is the canonical folder/file structure to use for **every course and every week**, going forward. Apply this automatically when new courses or weeks are created — do not wait to be asked.

## Course Level
```
coursework/<COURSE_CODE>/
├── course_overview.md      # ONE per course — quick-scan study guide
└── weekNN/                 # one folder per week, lowercase, zero-padded (week01, week02, ... week12)
```

`course_overview.md` contains:
- Instructor, institution, credits, semester
- Course description
- Aggregate learning objectives (rolled up across all completed weeks)
- Weekly Map table (week → topic/focus → status → link to that week's study guide)
- Dissertation tie-ins (which weeks/sources feed the dissertation)
- Links to `feedback_log/feedback_tracker.md` and the repo `README.md`

## Week Level
```
weekNN/
├── learning_objectives.md   # the ONE overview/study guide for this week
├── assignments/             # markdown conversions of assignments, quizzes, discussion posts/replies
├── feedback/                # markdown conversions of professor feedback
└── original_src_files/      # archived original uploads (docx, pdf, etc.) — nothing else goes here
```

Rules:
1. **One overview file per week** — `learning_objectives.md`. It contains: Overview, Learning Outcomes, and a **Quick Links** section pointing to that week's `assignments/`, `feedback/`, `original_src_files/`, and back up to `course_overview.md`.
2. **`assignments/`** holds anything the student produced or analyzed as part of a graded/completed activity — discussion posts, replies, quiz findings/analysis, papers — always converted to markdown (using [assignment_apa7_template.md](assignment_apa7_template.md)), even if it reads like a "study aid."
3. **`feedback/`** holds professor feedback, converted to markdown.
4. **`original_src_files/`** holds the original uploaded file for anything in `assignments/` or `feedback/` (docx, pdf, etc.), so the markdown version can cite it as `**Source:**`. If a week has no uploads yet, keep an empty folder (with `.gitkeep`) so the structure stays visible.
5. Filenames inside `weekNN/` subfolders **drop the week number** (e.g. `assignments/book_review_discussion.md`, not `week3_book_review_discussion.md`) since the folder path already encodes the week.

## When Adding a New Course
1. Create `coursework/<COURSE_CODE>/course_overview.md` from this pattern.
2. Create `weekNN/` folders as weeks start, each with the four items above.
3. Update the repo `README.md` index and `PROJECT_STATUS.md` Session Log.

## Maintenance
See `PROJECT_STATUS.md` §7 "Standing Maintenance Rule" for what to update automatically whenever new coursework is added.
