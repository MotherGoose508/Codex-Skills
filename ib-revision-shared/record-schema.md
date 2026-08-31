# Revision Record Schema

`revision-record.json` is a compact evidence log, not a transcript or timetable.

Each entry uses:

- `id`: stable short identifier.
- `date`: local date in `YYYY-MM-DD` form.
- `subject`: one of `english`, `spanish`, `history`, `physics`, or `design_technology`.
- `topic`: concise syllabus topic, text, technique, or skill.
- `task_type`: concise description such as `concept_explanation`, `paper_2_plan`, or `calculation`.
- `unaided_evidence`: brief factual account of the initial performance.
- `hints_used`: integer count.
- `misconceptions`: short list of demonstrated gaps, not speculative labels.
- `correction_evidence`: brief description of what the learner corrected.
- `status`: `unassessed`, `developing`, `retest_due`, or `secure`.
- `next_action`: one concrete revision task.
- `retest_on`: local date or `null`.
- `source_basis`: brief note identifying supplied notes, official criteria, or provisional general knowledge.

Mark `secure` only after successful delayed retrieval on a materially different task. Update an existing concept entry when that gives a clearer evidence trail; append a new entry when the task tests a distinct skill or misconception.

