---
name: ib-practice-question-creator
description: Create and administer original IB-style practice questions for the learner's current 2027-exam courses, with course-specific structure and marking; use for single questions, interactive practice, worksheets, or mock-style sets, not authentic past-paper retrieval.
---

# IB Practice Question Creator

Create original, answerable practice that reflects the applicable 2027 examination course. Do not describe generated material as an authentic IB question or reproduce a past-paper question with superficial changes.

Read `../ib-revision-shared/profile.yaml` for the learner's courses. For interactive practice and evidence handling, also follow `../ib-revision-shared/framework.md`; use `../ib-revision-shared/record-schema.md` only after the learner answers.

Before generating questions, read the one reference matching the requested subject:

- [Mathematics AA HL](references/mathematics-aa-hl.md)
- [Physics HL](references/physics-hl.md)
- [Design Technology HL](references/design-technology-hl.md)
- [English A: Language and Literature SL](references/english-a-langlit-sl.md)
- [Spanish B SL](references/spanish-b-sl.md)
- [History SL](references/history-sl.md)

## Establish the Request

- Infer subject, level, topic, component, mode, and difficulty from the request and available context.
- Ask a concise clarification when the paper, component, text, prescribed topic, or assessed skill materially changes what a valid question looks like.
- If the requested quantity is missing, ask how many before generating. For interactive practice, present the chosen number one question at a time; for a requested batch, generate the stated quantity together.
- Use the learner's course level by default. Do not silently make questions easier than Mathematics AA HL, Physics HL, Design Technology HL, English A SL, Spanish B SL, or History SL as recorded in the profile.
- Present ordinary practice in chat. Create a polished worksheet or mock-paper artifact only when requested.

## Verify the 2027 Assessment Basis

Before relying on paper structure, command terms, permitted technology or resources, mark allocation conventions, criteria, prescribed content, or timing:

1. Prefer the learner's current official guide, teacher-provided course material, specimen paper, data booklet, or mark scheme.
2. If needed and online research is permitted, retrieve current first-party IB material applicable to the 2027 examination session.
3. Check the publication, syllabus version, first-assessment date, level, and component. Do not substitute legacy structures, especially for redesigned courses.
4. Keep provenance visible when it affects the question or marking.

If authoritative material remains unavailable, proceed only when the exercise is still useful. Label the affected question and marking guidance **provisional**, identify what could not be verified, and avoid invented IB rules or mark-scheme language.

## Construct the Practice

Every question must be newly written and solvable from taught course knowledge plus any supplied stimulus. Match verified subject and component characteristics, including relevant command terms, stimulus conventions, mark values, expected response depth, and permitted resources.

Before presenting a question, check:

- the prompt has a determinate task and contains all necessary data;
- marks are plausible for the required reasoning and output;
- diagrams, extracts, sources, and datasets are legible, sufficient, and correctly attributed or clearly identified as generated;
- later questions do not reveal answers to earlier ones unintentionally;
- the internal solution and marking logic actually solve the presented version.

For a set, create a balanced progression across the requested content: vary command terms and response forms, increase cognitive demand, avoid repetitive testing, and distribute marks deliberately. Do not force a progression when the learner requests independent questions or a fixed difficulty.

## Withhold and Mark

- Prepare enough internal solution and marking logic to validate each question, but do not reveal answers, hints, mark schemes, or model responses with the initial practice unless explicitly requested.
- After the learner answers, mark automatically against the verified or clearly provisional basis. Award marks criterion by criterion, cite evidence from the response, identify the smallest important gap, and offer a targeted retry.
- Keep the full model answer hidden until requested. If the learner asks for it before attempting, state briefly that the task will not count as unaided evidence, then comply.
- After a correction, use a materially different follow-up when testing transfer.

Generating or viewing a question is not performance evidence. After the learner answers, show a concise proposed revision-record entry and ask permission before writing it. Never update `../ib-revision-shared/revision-record.json` without a clear yes.

## Coordinate With Existing Revision Skills

When a matching subject revision skill is available, apply its subject-specific feedback and safeguarding rules alongside this skill. This skill owns question construction, answer withholding, and set balance; the subject skill supplies deeper discipline-specific judgment. The learner's explicit requested format takes precedence.
