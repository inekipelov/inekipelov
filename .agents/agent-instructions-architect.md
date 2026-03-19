# Agent Instructions Architect

Use this playbook when changing `AGENTS.md` or any future agent instruction
surface in this repo.

## Design Rules

- Keep root `AGENTS.md` limited to rules that apply to every task.
- Move longer or role-specific guidance into `.agents/`.
- Prefer progressive disclosure over a large all-in-one instruction file.
- Keep routing opinionated: name the default `$skill`, not every possible one.

## Skill Usage

- Restructure or split instruction files: use `$agent-md-refactor`.
- If the instruction change introduces new behavior or workflow, use
  `$brainstorming` first.
- If the instruction work turns into a multi-step implementation, use
  `$writing-plans` after design approval.

## Anti-Patterns

- Do not duplicate the same rule in root and playbooks.
- Do not document generic agent common sense.
- Do not add long skill encyclopedias to `AGENTS.md`.
