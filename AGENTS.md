# Cloud Agent Instructions

This repo is a **sticky monorepo** for weekday tech demos. Follow these rules when working here.

## Scope

- **Only modify files under `apps/<kebab-slug>/`** when building or updating a demo app.
- Do **not** add sample apps, root tooling changes, or unrelated refactors unless explicitly requested.
- **Never create a new GitHub repository** — all demos live in this monorepo.

## Planning

When approved to build a demo, read and follow `skills/project-planning/SKILL.md` (if present). Write `apps/<kebab-slug>/PLAN.md` before implementation.

## Stack & run

- Use **Bun** (`bun install`, `bun run dev`).
- Each app must be **self-contained** and runnable from its own folder without root-level setup beyond workspace install.

## Pull requests

- Open **one PR** per demo (or per scoped task).
- Attach **at least one screenshot AND one video** of the running app in the PR description.
- Do not merge your own PR unless explicitly asked.

## Tracking

- Update `tracking/seen-bookmarks.json` when a bookmark is proposed, built, or skipped so demos are not re-proposed.
