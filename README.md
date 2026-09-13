# tech-demos

**English** — Sticky monorepo for weekday tech demos picked from X bookmarks. Each demo lives in `apps/<slug>/` as a self-contained Bun app (`bun install && bun run dev`). Cloud agents add new apps only; `tracking/seen-bookmarks.json` tracks proposed, built, and skipped bookmarks to avoid duplicates. Deployment (optional, later): a single Cloudflare Pages project can host built demos.

**日本語** — X のブックマークから選んだ平日デモ用の sticky モノレポです。各デモは `apps/<slug>/` に独立した Bun アプリとして置きます（`bun install && bun run dev`）。Cloud Agent は新規アプリの追加のみ行い、`tracking/seen-bookmarks.json` で提案・作成済み・スキップを記録して重複提案を防ぎます。デプロイ（任意・将来）: ビルド済みデモを 1 つの Cloudflare Pages プロジェクトでホスト可能。

## Layout

```
apps/<slug>/          # one demo per folder
tracking/             # bookmark dedup state
skills/project-planning/
AGENTS.md             # cloud agent rules
```
