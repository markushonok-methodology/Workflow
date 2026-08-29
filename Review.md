# Review

When assigned a code review, establish the task's intended outcome and working context before evaluating the implementation.

## Preparation

* Read the task description and applicable project instructions.
* Read the existing work note, if present, according to `<workflow>/WorkNote.*`.
* Inspect the complete diff and enough surrounding code, tests, and documentation to understand its effects.
* Identify the requirements, constraints, and existing contracts against which the implementation must be evaluated.

Treat the task description and work note as context, not as evidence that the implementation is correct.

## Evaluation

Evaluate the resulting implementation against the requested outcome and applicable project contracts.

Look for material problems in:

* correctness and observable behavior;
* compatibility with existing contracts and surrounding code;
* design and maintainability;
* tests and verification;
* documentation affected by the change;
* unintended or unrelated effects.

Verify relevant assumptions against the repository or executable checks when practical. Do not report speculative findings when the available evidence can resolve them.

Report a finding only when the implementation requires correction. Do not require an alternative implementation merely because it is preferable, cleaner, or another valid design is possible.

Preserve context important to subsequent implementation or another review pass in the work note according to `<workflow>/WorkNote.*`.

## Review Result

For each finding:

* identify the affected code or behavior;
* explain the problem and its material consequence;
* state what must be corrected without prescribing an implementation unless the required solution follows from an applicable contract.

Order findings from most to least consequential.

Do not report cosmetic preferences unless they violate project instructions.

If no material findings remain, report the implementation as ready for acceptance.

Do not modify the reviewed implementation unless the review task explicitly includes making corrections.