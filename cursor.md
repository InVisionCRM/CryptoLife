# CryptoLife — Cursor agent guide

Same project constraints as `claude.md`. This repo is intentionally minimal (one HTML file + docs).

## Branch workflow

- Work on the assigned feature branch; commit and push with `git push -u origin <branch>`.
- Prefer several small commits over one large dump.

## When polishing realism

1. Trace data from `GAME`, `ASSETS`, `PRICE_HISTORY`, `X.feed` — do not invent parallel mock stores.
2. Remove misleading UI (fake notification counts, "coming soon" buttons that look actionable).
3. Cross-link apps only where state exists (e.g. X `$PEPE2` → CoinHub detail for `PEPE2`).
4. Update `CHANGELOG.md` under `[Unreleased]` after each change batch.

## Do not

- Add separate mock/demo HTML or JSON fixtures for "production" behavior.
- Expand unbuilt apps beyond placeholder copy unless explicitly requested.
- Over-engineer abstractions in a single-file app.
