# Codex Skills

A collection of personal Codex skills for active learning and evidence-based IB revision.For AAHL maths, HL Physics, HL Dt, SL English Lang Lit, SL Spanish B, and SL History

## Skills

| Skill | Course | Purpose |
| --- | --- | --- |
| [`feynman-teachback`](./feynman-teachback/) | Any subject | Learner-led explanation, gap repair, transfer, and concise reteaching |
| [`ib-practice-question-creator`](./ib-practice-question-creator/) | Current IB courses | Original 2027-course practice questions, sets, and evidence-based marking |
| [`ib-dt-revision`](./ib-dt-revision/) | Design Technology HL | Technical knowledge, application, case studies, evaluation, and exam-style responses |
| [`ib-english-revision`](./ib-english-revision/) | English A: Language and Literature SL | Text knowledge, analysis, comparison, and exam writing |
| [`ib-history-revision`](./ib-history-revision/) | History SL | Factual knowledge, causation, perspectives, sources, and exam arguments |
| [`ib-physics-revision`](./ib-physics-revision/) | Physics HL | Concepts, derivations, calculations, data analysis, and exam-style reasoning |
| [`ib-spanish-revision`](./ib-spanish-revision/) | Spanish B SL | Retrieval, comprehension, speaking, writing, vocabulary, and grammar |

## Shared resources

The IB skills use [`ib-revision-shared`](./ib-revision-shared/) for the common tutoring framework, learner profile, evidence schema, and revision record. Keep this directory beside the skill directories so their relative references continue to work.

```text
Codex-Skills/
|-- feynman-teachback/
|-- ib-practice-question-creator/
|-- ib-dt-revision/
|-- ib-english-revision/
|-- ib-history-revision/
|-- ib-physics-revision/
|-- ib-spanish-revision/
`-- ib-revision-shared/
```

Each installable skill contains:

- `SKILL.md` — behavior and subject-specific instructions.
- `agents/openai.yaml` — display metadata and the default invocation prompt.

## Installation

Clone the complete repository into your Codex skills directory. The complete checkout is required because every subject skill reads files from `ib-revision-shared`.

```powershell
git clone <repository-url> "$env:CODEX_HOME\skills\Codex-Skills"
```

Restart Codex after installing or updating the skills.

## Personal data

`ib-revision-shared/profile.yaml` contains learner-specific course context, and `revision-record.json` is designed to accumulate personal revision evidence. Keep the repository private unless you intentionally remove or anonymize that information.
