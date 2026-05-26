# CryptoLife — agent guide (Claude)

## What this is

Single-file production sim: `index.html`. Phone UI with **built** apps (CoinHub, X, Settings) and **preview** apps (placeholders only — do not build full Telegram/Discord/etc. unless asked).

## Rules

- **No mock layers** — UI must reflect live `GAME` / `ASSETS` / `X.feed` state. No fake badges, dead buttons, or placeholder data that pretends to be real.
- **Less is more** — small, believable details beat new features. Previews stay previews.
- **Changelog** — append to `CHANGELOG.md` after every meaningful edit.
- **Read this file and `cursor.md`** before and after coding sessions.

## Economy

- Wallet/positions/trades/news/rugs are authoritative in `GAME` and `ASSETS`.
- X posts should tie to real news, launches, and symbols when possible.

## CoinHub

- Detail stats (volume, mcap, dossier) are **derived** from price history and token metadata (`flags`, `rugRisk`, age).
- Due diligence is a **read-only dossier**, not non-functional investigate buttons.

## X

- Only `X.unreadCount` drives the X home badge.
- Cashtags (`$SYMBOL`) link to CoinHub when the asset exists.
- Impersonator tweets get a visible warning in detail view.
