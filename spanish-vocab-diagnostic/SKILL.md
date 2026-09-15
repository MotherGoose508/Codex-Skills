---
name: spanish-vocab-diagnostic
description: Diagnose a learner's Spanish vocabulary from a supplied list or deck and save targeted results for later teaching sessions.
---

# Spanish Vocab Diagnostic

Use this skill when a learner wants to identify which Spanish vocabulary needs teaching before starting practice. It diagnoses; it does not attempt to teach a large vocabulary set during the assessment.

## Prepare the diagnostic

- Extract vocabulary and meanings from the supplied list, worksheet, or deck. If a prior `Vocab_Diagnostic.md` exists, retain its history but run a fresh diagnostic when the supplied source changes.
- Select a representative, balanced sample across the source's categories. Use 10 to 20 items unless the learner requests a different size.
- Test a mix of Spanish-to-English meaning, English-to-Spanish production, and Spanish contextual gaps. Test multi-word phrases as complete units.
- Ask one concise item at a time. Do not provide hints, memory hooks, or teaching until the diagnostic is over. Accept sensible synonyms when the intended meaning is preserved.

## Score and save

- Mark each tested item **secure** only when the learner gives an accurate meaning or produces it correctly in context. Mark it **shaky** for partial meaning, a spelling/grammar problem that affects production, or a self-correction. Mark it **new** when it is incorrect or unknown.
- After the diagnostic, create or update `Vocab_Diagnostic.md` in the learner's Spanish folder. Record the source, date, tested word or phrase, result, status, and a short evidence note.
- Also update matching entries in `Vocab_Progress.md`; add an entry when it does not exist. Do not overwrite a newer demonstrated status with an older diagnostic result.
- Give a short, factual summary: secure items, shaky items, new items, and the recommended first 6 to 8 words for the next builder session.

## Handoff

- Tell the learner that `$spanish-vocab-builder` reads `Vocab_Diagnostic.md` before selecting a session's words.
- The recommended builder set should prioritise new items, then shaky ones. It should not spend most of a short session on secure items.
