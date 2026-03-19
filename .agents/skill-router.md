# Skill Router

Use this file to choose the minimum useful set of `$skills` for a request.

## Routing Rules

- Prefer one primary `$skill`; add a second only when it covers a distinct gap.
- Do not stack overlapping writing or review `$skills` without a clear reason.
- If the task is repo-specific and simple, use no extra `$skills`.
- If the user asks for a capability the environment may already support, check
  local skills first before reaching for `$find-skills`.

## Common Routes

- Restructure agent instructions: use `$agent-md-refactor`.
- Need a design before implementing: use `$brainstorming`, then
  `$writing-plans`.
- Ask "is there a skill for X?": use `$find-skills`.
- Create or revise a skill: use `$skill-creator` for structure and
  `$writing-skills` for quality and validation.
- Install a new skill from a repo or curated list: use `$skill-installer`.
- OpenAI docs, APIs, models, or upgrades: use `$openai-docs`.

## Examples

- "Refactor this `AGENTS.md`" -> `$agent-md-refactor`
- "Plan a new feature" -> `$brainstorming`
- "Implement the approved plan" -> `$writing-plans`
- "Find a skill for changelog generation" -> `$find-skills`
