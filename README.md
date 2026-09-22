# CSE 321 — Statistical Inference and Computation

Akdeniz University · Computer Engineering (English)

**An open study archive for this course.** Lecture notes, both textbooks, practice
sets, past exam photographs, and the problem sets the instructor hands out before
each exam.

The instructor's slides are headed "CSE 321 Introduction to Probability Theory",
which is the lecturer's own title for the material. The taught schedule is the one
in [`resources/lecture-notes/00-course-info.pdf`](resources/lecture-notes/00-course-info.pdf),
and that is what [`weeks/`](weeks/) follows.

## Course

**Instructor:** Alper Bilge, PhD, Associate Professor · abilge@akdeniz.edu.tr
No office hours; reachable on MS Teams.
**Time:** Fridays 08:30-12:30 · **Location:** BB04

| Component | Weight |
|-----------|--------|
| Midterm | 40% |
| Final | 60% |

## Topics

The course is organized as eight topics, not fourteen weekly slots.

| # | Topic | Note |
|---|-------|------|
| 1 | Statistics, data, and statistical thinking | [weeks/01](weeks/01-statistics-and-statistical-thinking.md) |
| 2 | Methods for describing sets of data | [weeks/02](weeks/02-describing-sets-of-data.md) |
| 3 | Probability | [weeks/03](weeks/03-probability.md) |
| 4 | Discrete random variables | [weeks/04](weeks/04-discrete-random-variables.md) |
| 5 | Continuous random variables | [weeks/05](weeks/05-continuous-random-variables.md) |
| 6 | Sampling distributions | [weeks/06](weeks/06-sampling-distributions.md) |
| 7 | Inferences from one sample: confidence intervals | [weeks/07](weeks/07-confidence-intervals.md) |
| 8 | Inferences from one sample: tests of hypothesis | [weeks/08](weeks/08-hypothesis-testing.md) |

Topics 1-6 are the midterm scope; 7-8 are added for the final.

## How to study with this repository

**1. Open the topic you are on** in [`weeks/`](weeks/). Each note gives the goals,
the concepts with their actual formulas, what to read, and what to practice.

**2. Follow the reading links** — they open the book at the exact page:

> [McClave & Sincich — Ch. 6 (sampling distributions)](resources/books/mcclave-sincich-statistics-13e.pdf#page=312)

Each topic links three things: the official textbook, the supplementary Walpole,
and the instructor's own lecture note for that chapter.

**3. Practice with [`exams/prep/`](exams/prep/) first.** `problems-for-midterm.pdf`
and `problems-for-final.pdf` come from the instructor — they are the closest thing
to knowing what will be asked.

**4. Then [`exams/practice/`](exams/practice/)** for extra sets from other courses
and universities, and [`exams/`](exams/README.md) for photographs of real papers.

**5. Write under your own `## Notes — <Name> (<term>)` heading** at the bottom of
each topic note. Everything above that heading is shared; below it is yours — see
[Taking notes](#taking-notes).

## Layout

```
README.md        This page
course-info.md   Resource map (textbook page offsets, topic → chapter), Turkish ↔ English glossary
weeks/NN-*.md    One file per topic: the shared plan on top, everyone's notes below
exams/           Photographs of real papers, prep/ (the instructor's pre-exam problem sets), practice/ (practice exams from elsewhere)
resources/       books/ (McClave & Sincich official, Walpole supplementary), lecture-notes/ (the instructor's slides, chapter by chapter), supplement/ (topic summaries, descriptive statistics through hypothesis testing)
```

## Taking notes

Open the topic, scroll to the bottom, write under your own heading:

```markdown
## Notes — <Name> (<term>)
### Lecture
### Worked out by hand
### Questions
### Exam-worthy
```

Add your heading below the existing ones and never edit someone else's section —
different sections merge in git without conflicts.

## Who changes what

| What | Who edits it | When |
|------|-------------|------|
| Top of `weeks/NN-*.md` (goals, reading, practice) | **anyone** | Only when the course itself changes — a new topic, a better reading, a correction. Never for personal notes. |
| `## Notes — <you>` in a week file | **only you** | Every week. This is your notebook. |
| `course-info.md`, `exams/README.md` | **anyone** | When you learn something durable: a new exam pattern, a better source. |
| `assignments/<term>-<you>-*` | **only you** | Your assignments, projects, submissions, if the course has them. Use a lowercase, hyphenated name — `efe-kurucay`, not `Efe Kuruçay`. Only work you produced yourself belongs here. |
| `resources/<term>/` | **anyone in that term** | Slides, syllabus and lab sheets the instructor issued that term — the same for everyone taking the course then. |
| `exams/` | **anyone** | When you get hold of a new paper — blank or answered. Exam papers never go under `assignments/`. Put the writer's surname in the filename (`2025-final-answered-altungoz.pdf`). |

Two students in different years never touch the same file except to improve the
shared plan — which is the point.

## Terms

| Term | Instructor | Schedule | Midterm | Final | Notes |
|------|-----------|----------|---------|-------|-------|
| Fall 2026-2027 | TBD — fill in during week 1 | TBD | TBD | TBD | Efe — in every week file |

## Contributing

Taking the course now? Add a row for your term to the table above naming the
instructor and dates, write your notes in the week files, and put your papers and
photographs in [`exams/`](exams/README.md). Keep the top of each `weeks/` file and
`course-info.md` general — they are the shared plan and should improve every year.
