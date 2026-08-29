# Workflow Specification

This repository defines project-independent guidance for organizing and performing development work.

The guidance applies to both human and agent participants unless explicitly scoped otherwise.

Do not replace it with conventions imposed by particular tools, platforms, agents, or project-management systems.

## Instruction Precedence

The rules of this repository are general defaults.

Project-specific instructions take precedence over them. More local project instructions may further specialize rules for individual workflows or subsystems.

## Paths

Documentation uses the following abstract paths:

* `<project>` — the root directory of the project being worked on.
* `<workflow>` — the directory containing this specification's `AGENTS.md`.

## Navigation

Do not load all documentation unnecessarily. Read only the documents relevant to the current task.

Navigation entries use `<workflow>/<Topic>.*` to refer to the files associated with a topic.

The `<workflow>/<Topic>.md` file is the primary normative source.

Other files with the same stem may provide supporting material relevant to the topic.

* `<workflow>/Implementation.*` — task implementation, verification, and preparation for review.
* `<workflow>/Review.*` — code review and reporting of findings.
* `<workflow>/WorkNote.*` — ephemeral working context used during implementation and review.