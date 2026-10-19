# Contributing guide

Thanks for helping out! This short guide covers the basics of how we work on this repo.

## Branch naming

Create feature branches off `main` using the pattern `feature/<short-description>` (for example `feature/contributing`). Use `fix/` for bug fixes and `docs/` for documentation-only changes. Keep branch names lowercase, hyphenated, and short.

## Commit message style

Write commits as `type(scope): summary` - for example `docs(readme): clarify install steps`. Use the imperative mood ("add", not "added"), keep the summary under 72 characters, and put any longer explanation in the body, separated by a blank line.

## How to open a PR

1. Push your branch to the remote.
2. Open a pull request from your branch into `main`.
3. Fill in the PR template: what changed, why, and how to verify it.
4. Request at least one reviewer, and make sure CI passes before merging.
5. Address review feedback with follow-up commits, and never rewrite history once a review is in progress.
