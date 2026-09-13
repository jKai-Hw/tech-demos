# Project Planning (tech-demos)

Use this skill when approved to build a weekday demo in this monorepo.

## Before coding

1. Choose a **kebab-case slug** for the app folder: `apps/<kebab-slug>/`.
2. Write **`apps/<kebab-slug>/PLAN.md`** with:
   - **Goal** — what the demo proves or explores (one paragraph).
   - **MVP scope** — smallest slice that demonstrates the idea; list in/out of scope.
   - **Stack** — prefer **Bun**; note any libraries or APIs.
   - **Run commands** — e.g. `bun install`, `bun run dev`, and how to open the app.
   - **Validation** — how you will capture a **screenshot** and **video** of the running app for the PR.

3. Implement **only** under `apps/<kebab-slug>/`. Do not touch other apps or unrelated root files.

## After implementation

- Ensure `bun install && bun run dev` works from the app directory.
- Open one PR with screenshot + video attached.
- Record the bookmark in `tracking/seen-bookmarks.json` under `built` (or `skipped` if abandoned).
