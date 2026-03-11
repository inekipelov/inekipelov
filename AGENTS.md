# Repository Guidelines

Keep this repo lightweight—`README.md` is the public profile, and this guide is
the only other root file. Everything else should live in `docs/` with any
supporting images under `assets/<topic>/`.

## Project Structure & Module Organization
- Root: `README.md`, `AGENTS.md`, and other visitor-facing Markdown only.
- Long-form notes: `docs/<topic>.md`; reuse relative links.
- Media: compress images below ~500 KB and store in `assets/<topic>/`.
- Badges: match the existing Shields.io style and brand colors.

## Build, Test, and Development Commands
- `npx markdownlint README.md AGENTS.md` — catch formatting drift before
  pushing.
- `npx markdown-link-check README.md` — verify outbound links remain valid;
  run for other files when you add many links.
- `open README.md` — quick macOS preview to confirm emoji and badge rendering.

## Coding Style & Naming Conventions
- GitHub-flavored Markdown with ATX headings and sentence-case titles.
- Hyphen bullets; fenced code blocks for commands and snippets.
- Wrap text near 80 characters to keep diffs readable.
- Filenames: lowercase with hyphens (e.g., `profile-update.md`); avoid spaces.
- Keep prose concise and visitor-focused; avoid unused sections.

## Testing Guidelines
- Manually open README in GitHub preview to spot badge or layout issues.
- For link-heavy edits, run `npx markdown-link-check path/to/file.md`.
- Verify new assets render and stay within size guidance; rename descriptively.

## Commit & Pull Request Guidelines
- Commits: imperative, capitalized subjects under 72 characters (e.g., `Add
  resume link to README.md`); group related edits together.
- PRs: state intent, list manual checks (lint, link validation, previews), and
  link related issues or discussions.
- Include screenshots when badge ordering or visuals change; flag follow-up
  tasks to keep the profile curated.

## Security & Housekeeping
- Do not commit secrets, personal access tokens, or machine-specific settings.
- Prefer relative links and avoid external assets that may break over time.
- Keep the root clutter-free; unused drafts belong in `docs/` or should be
  removed before merging.
