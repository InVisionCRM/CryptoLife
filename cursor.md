# CryptoLife — Cursor / automation

## Branch
Work on `cursor/game-detail-refinement-0fb6` (or current feature branch). Commit and push with `git push -u origin <branch>`.

## Before / after coding
1. Read `claude.md` and this file.
2. Read tail of `CHANGELOG.md`.
3. After changes: update changelog, re-read both docs, run a quick sanity check (open `index.html` logic mentally or grep for typos).

## Style
- Prefer 5–30 line diffs per idea.
- User-facing copy: lowercase, casual, crypto-native (matches existing toasts).
- Version string lives in `<title>`, `.game-info`, Settings → About.

## Changelog
Append dated bullets under `## Unreleased` in `CHANGELOG.md`; move to a version heading when bumping `v0.x`.
