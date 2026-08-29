# Overview

Shared workflow specification for humans and agents used across multiple
software projects.

The repository provides a single source of project-independent instructions
for organizing and performing development work without duplicating them across
individual repositories.

[`AGENTS.md`](./AGENTS.md) is the entry point to the specification.

# Installation

Add the repository to a project as a Git submodule:

```sh
git submodule add <repository-url> <path>
```

Reference the submodule specification from the project's root `AGENTS.md` so
that agents discover and apply it:

```md
Follow the workflow specification in `<path>/AGENTS.md`.
```

Project-specific instructions in the root `AGENTS.md` may specialize or
override the shared specification.