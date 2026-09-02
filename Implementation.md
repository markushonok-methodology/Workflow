# Implementation

When assigned a development task, establish its current context before making substantive changes.

## Preparation

* Read the task description and applicable project instructions.
* Ensure the task has a work note according to `<workflow>/WorkNote.*` before making substantive changes: read the existing note, or create one if none exists.
* Ensure the task description remains available for continuation and review. If its authoritative source may not remain available, preserve enough of the description in the work note before continuing.
* Inspect the relevant code, tests, and documentation.
* Identify requirements, constraints, and existing contracts that materially affect the task.

Do not silently resolve a material ambiguity that cannot be answered from the task or repository context. Record it in the work note and report it.

## Execution

Implement the requested outcome without expanding the task unnecessarily. Treat existing contracts as constraints unless the task intentionally changes them.

Maintain the work note throughout implementation. Record important requirements, constraints, decisions, rejected approaches, risks, unresolved questions, and other context whose loss would materially hinder continuation or review.

Do not leave durable project knowledge only in the work note. Preserve lasting knowledge in the appropriate code, tests, or documentation.

## Review Readiness

Before reporting the implementation as ready for review:

* run the verification required by applicable project instructions and the change itself;
* inspect the complete diff for unintended, incomplete, or unrelated changes;
* update the work note with context materially relevant to review;
* report unresolved risks, limitations, ambiguities, and verification failures.

Report the implementation as ready for review only when the requested work is complete and its result has been verified.