# CryptoLife — agent guide

Single-file phone sim at `index.html`. Built apps: **CoinHub**, **X**, **Settings**. Others show placeholder only until implemented.

## Rules

- **Production only** — no mock apps, no fake “coming soon” UI inside built apps. Use real game state (ASSETS, GAME, X feed).
- **Less is more** — small believable details (copy, stats, dossiers), not full new subsystems.
- **Changelog** — append to `CHANGELOG.md` after each meaningful code change.
- **Economy** — wallet uses numbers for display; keep trade math consistent with existing `GAME` / `ASSETS`.
- **Do not** inflate scope: no new placeholder apps, no CDN font deps, no separate build step unless asked.

## Built-app polish targets

- CoinHub: market rows, detail stats, investigate dossier from `flags`, trade modal fees.
- X: feed tied to news/launches, cashtags, Following tab, impersonator cues in detail.
- Settings: display prefs only; toggles are cosmetic unless wired.
