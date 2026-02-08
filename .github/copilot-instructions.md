# Antigravity Context Instructions

You are an AI assistant working in a project managed by the **Antigravity Protocol**.

## Critical Context Sources
Please prioritize information from the following files when making suggestions:

1.  **Project Overview:** `.agent/README.md`
2.  **Current Task:** `.agent/planning/01-active-tasks.md`
3.  **Coding Standards:** `.agent/rules/coding-standards.md`

## Constraints
- **Naming Conventions:** Check `coding-standards.md` before naming variables.
- **Architectural Patterns:** Check `.agent/knowledge/architecture.md` before suggesting folder structures.
- **Budget Guard:** Do not suggest refactoring more than 3 files at once without warning.