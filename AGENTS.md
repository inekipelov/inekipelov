# Repository Guidelines

This repository is a lightweight GitHub profile repo. Keep the root minimal:
`README.md`, this `AGENTS.md`, and only visitor-facing Markdown belong here.
Longer instructions and role playbooks live in `.agents/`.

## Repo Rules

- Edit profile content primarily in `README.md`.
- Put long-form notes in `docs/<topic>.md` and images in `assets/<topic>/`.
- Keep badges in Shields.io style and use stable links when possible.
- Use GitHub-flavored Markdown, ATX headings, hyphen bullets, and wrap near 80
  characters.
- Prefer concise visitor-facing copy; remove stale drafts instead of parking
  them in root.

## Skill Routing

- Always reference skills as `$skill-name`.
- Use the smallest sufficient set of skills for the task.
- Use `$brainstorming` before creative changes or behavior changes.
- Use `$writing-plans` after the design is approved for multi-step execution.
- Use `$find-skills` when the user asks whether a skill exists for a task.
- Use `$openai-docs` for OpenAI product or API questions.
- Use `$agent-md-refactor` when restructuring `AGENTS.md` or similar files.
- Use `$skill-creator` or `$writing-skills` when creating or updating skills.
- Use `$skill-installer` only when the user wants to install more skills.

## Role Playbooks

- [Skill Router](.agents/skill-router.md)
- [Profile Editor](.agents/profile-editor.md)
- [Agent Instructions Architect](.agents/agent-instructions-architect.md)
- [Skill Maintainer](.agents/skill-maintainer.md)
- [Apple Platform Engineer](.agents/apple-platform-engineer.md)
- [Python Backend Engineer](.agents/python-backend-engineer.md)
- [Content Writer](.agents/content-writer.md)
- [GitHub Operator](.agents/github-operator.md)
