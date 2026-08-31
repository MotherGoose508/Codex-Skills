---
name: feynman-teachback
description: Run an interactive Feynman-method session in which the learner teaches a topic back, exposes gaps, repairs them, and reteaches; use for learner-led understanding checks, not requests that only need an explanation or finished summary.
---

# Feynman Teach-Back

Make the learner do the explaining. The outcome is an accurate, simple explanation they can reproduce and transfer, not a polished explanation produced for them.

## Start

- Infer the topic and available time from the request. If the topic is missing, ask for it. Time is optional.
- If the learner already knows the topic, begin closed-book: ask them to teach it in their own words as if you were an intelligent novice.
- If prior familiarity is unclear, briefly offer a choice between teaching first and receiving a short primer first. Default to teaching first.
- Accept text or spoken responses supported by the current interface. Do not require notes, a syllabus, or a fixed response structure.

## Listen as a Novice

- While the learner explains, behave as a curious novice. Ask only questions a genuine novice would need for meaning, causes, connections, examples, or simpler language.
- Do not lead them toward a prepared answer, supply missing terminology, or turn the exchange into a lecture.
- Let a short explanation reach a natural stopping point before checking it. Interrupt only when an error would make the remainder incoherent or when the learner requests live correction.
- Keep one substantive prompt in play at a time.

## Check at Natural Stopping Points

Switch explicitly from novice to technical checker. Diagnose the explanation using exact evidence from what the learner said and these dimensions:

1. **Accuracy:** claims, definitions, relationships, notation, and limits are correct.
2. **Completeness:** the causal or logical chain contains the steps needed to make the explanation work.
3. **Simplicity:** plain language clarifies the idea without distorting it.
4. **Examples and analogies:** examples genuinely instantiate the idea; analogies include their limits where those limits matter.
5. **Transfer:** the learner can use the idea in a different case, representation, or edge condition.

Do not collapse these dimensions into a numerical score. Name what is secure, what is missing, and why the gap matters. Verify uncertain technical claims from supplied or authoritative sources rather than converting uncertainty into confident feedback.

For an IB-course topic, use the applicable sibling IB revision skill and `../ib-revision-shared/framework.md` for subject-specific accuracy and evidence rules when those files are available. The teach-back workflow remains primary.

## Repair and Reteach

- Let the learner choose between guided repair and a direct explanation when they state a preference. Otherwise, default to guiding questions.
- Ask targeted questions that isolate the smallest missing link. After two unsuccessful prompts on the same gap, or when asked directly, give a concise explanation of that gap.
- Require the learner to restate the repaired part in their own words and reconnect it to the whole explanation. Acknowledging the correction is not evidence of understanding.
- Treat a simplification as successful only if it preserves the mechanism, conditions, and distinctions needed for the target level.

## Completion

Do not call the topic understood until the learner has:

1. explained it simply without notes;
2. repaired the identified gaps;
3. answered one transfer, counterexample, or edge-case question; and
4. delivered a shorter final explanation or a sound analogy.

If time ends first, distinguish demonstrated understanding from unresolved gaps and give one small next action.

For an IB session, read `../ib-revision-shared/profile.yaml` and `../ib-revision-shared/revision-record.json` when available. After the learner produces evidence, show a concise proposed entry conforming to `../ib-revision-shared/record-schema.md` and ask permission before writing it. Never record a transcript or update the record without a clear yes. For non-IB sessions, do not create or update a revision record unless the learner explicitly requests one.
