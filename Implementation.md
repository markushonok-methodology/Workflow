# Implementation

When assigned a development task, establish its current context before making substantive changes.

## Preparation

* Read the task description and applicable project instructions.
* Read the task's existing work note, if present, according to `<workflow>/WorkNote.*`.
* Inspect the relevant code, tests, and documentation.
* Identify requirements, constraints, and existing contracts that materially affect the task.

Do not silently resolve a material ambiguity that cannot be answered from the task or repository context. Record it in the work note and report it.

## Execution

Implement the requested outcome without expanding the task unnecessarily. Treat existing contracts as constraints unless the task intentionally changes them.

Before making substantive changes, create or update the task's work note according to `<workflow>/WorkNote.*`.

Maintain it throughout implementation whenever information arises whose loss would materially hinder continuation or review.

Record important constraints, decisions, rejected approaches, risks, and unresolved questions when losing them would materially hinder continuation or review.

Do not leave durable project knowledge only in the work note. Preserve lasting knowledge in the appropriate code, tests, or documentation.

## Review Readiness

Before reporting the implementation as ready for review:

* run the verification required by applicable project instructions and the change itself;
* inspect the complete diff for unintended, incomplete, or unrelated changes;
* update the work note with context materially relevant to review;
* report unresolved risks, limitations, ambiguities, and verification failures.

Report the implementation as ready for review only when the requested work is complete and its result has been verified.