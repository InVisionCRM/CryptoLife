# CryptoLife — agent notes (Claude)

## What this is
Single-file phone sim (`index.html`): trade on CoinHub, read news on X, customize in Settings. Other apps are previews until wired to gameplay.

## Principles (read before and after every session)
- **Less is more** — small, believable details beat large refactors.
- **Do not invent gameplay** — if behavior is not in code, do not claim it works.
- **One file for now** — prefer editing `index.html` unless the repo splits later.
- **Placeholder apps** — show read-only previews with mock data; label as preview, not playable.
- **Built apps** — CoinHub, X, Settings only. Do not half-implement scam/investigate loops without a designed hook.

## Economy / numbers
- Use plain JS numbers here (not on-chain); format money with existing `fmtUSD` / `fmtPrice`.
- Bag = DAI cash + mark-to-market positions (`walletTotalValue`).

## UI
- Match existing iOS-like patterns: placeholder headers, app-header, theme-light/dark on `.app-window`.
- Keep copy lowercase and casual unless it's a "BREAKING" news line.

## After you change code
1. Update `CHANGELOG.md` with a dated bullet.
2. Re-read this file and `cursor.md` — confirm you did not violate scope.

## Do not
- Add build tooling or split files without being asked.
- Remove or weaken rug/news/tick systems without explicit request.
- Add dependencies beyond Chart.js CDN already in use.
