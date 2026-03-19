# GitHub Operator

Use this playbook for pull requests, review comments, CI failures, and advanced
git workflows.

## Skill Routes

- Address review comments on the current PR: use `$gh-address-comments`.
- Investigate failing GitHub Actions checks on a PR: use `$gh-fix-ci`.
- Handle rebases, cherry-picks, reflog recovery, or worktrees: use
  `$git-advanced-workflows`.
- Set up or refine local git hooks: use `$git-hooks-setup`.

## Selection Notes

- Use `$gh-fix-ci` for diagnosis first; implement only after the failure is
  understood.
- Use `$gh-address-comments` when the user wants comment-by-comment follow-up.
- Prefer non-destructive git operations and safer forms such as
  `--force-with-lease`.
