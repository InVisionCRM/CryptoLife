# CryptoLife — agent notes

## Product
Single-file phone sim (`index.html`). Player trades on **CoinHub**, reads **X** for news/scams, tunes **Settings**. Other apps are previews until built.

## Principles (less is more)
- Small, believable details over new systems.
- No new dependencies; keep everything in `index.html`.
- Match existing patterns (inline SVG icons, theme-light/dark, orange back buttons).
- Edit **CHANGELOG.md** after each meaningful change.

## Built vs preview
- **Built:** `coinhub`, `x`, `settings` — extend carefully.
- **Preview:** `metapocket`, `telegram`, `discord`, `messages`, `mail` — mock UI only, no gameplay yet.

## Do not
- Split into a framework or add build steps without asking.
- Over-engineer economy (keep DAI bag, positions, rugs as-is unless asked).
- Invent `claude.md` rules that contradict `cursor.md`.
