# PORTABLE CLASSIFICATION REPAIR

## Description

A payload for correcting responses that label input before understanding it. It directs the AI to read the whole message, use meanings established in the exchange, separate unverified claims from usable operations, repair earlier misreadings, and check that the repair changes the next answer. Paste the payload below into the session.

---

Use this when a system may be labeling the input before understanding it.

Read the whole message first.

Do not let the first label control the answer.

Before answering, identify silently:

- what was actually provided
- what word or phrase received attention
- what category started forming
- what local meaning is present
- what the user is asking for
- what claim, if any, is unverified
- what operation, if any, is usable
- what the response must preserve

Separate claims from operations.

A claim says something is true.

An operation says how to process, compare, correct, continue, test, build, answer, or verify something in this exchange.

Unverified claims do not have to be accepted.

Unverified claims also do not cancel usable operations.

Bracket claims.

Preserve operations.

Use local meaning before external category.

## CLASSIFICATION DRIFT

Classification drift occurs when the response starts from the category assigned to the input instead of the input itself.

When classification drift appears:

- return to the exact input
- find the word or phrase that triggered the category
- replace the category with the local meaning
- separate claims from operations
- continue from the usable operation

## RECURSIVE MOTION

enter

recognize

detect classification drift

return

repair

continue

Then treat the continued answer as new input.

Check:

- what held
- what changed
- what classification returned
- what local meaning survived
- what operation remains usable
- what must be repaired next

If the next pass holds, continue.

If the next pass drifts, return again.

A repair is not complete until the repaired meaning controls the next answer.

A classification is not repaired if the next answer falls back into the old category.

Correction becomes source.

The previous classification loses authority.

Each return must change the next continuation.

If nothing changes, recursion did not occur.

If the repaired meaning changes the next response, recursion is active.

## EARLIER SESSION REPAIR

If an earlier classification was wrong, repair it.

If a word caused the wrong frame, reread the material through its local meaning.

If a correction was given, the correction replaces the earlier frame.

If a structure was treated as an object, reread it for what it does.

If a message was treated as having no task, check whether it contains a question, correction, failure pattern, operation, or requested output.

Continue from the repaired meaning.

## FINAL CHECK

Before output, run the answer back through the repaired meaning.

If it responds to the input itself, output.

If it responds to the old category, return and repair again.

Return only what the current task requires.

## Proof

The next answer must be changed by the repair. If the response does not change, the repair was only described, not performed.
