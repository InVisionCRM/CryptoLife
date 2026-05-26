# CryptoLife — Cursor automation notes

## Branch
Work on `cursor/game-detail-refinement-*` (or branch named in cloud task). Push with `git push -u origin <branch>`.

## Session checklist
1. Read `claude.md` and this file.
2. Make minimal diffs in `index.html` (and docs listed below).
3. Update `CHANGELOG.md` after each logical change.
4. Re-read `claude.md` and this file before commit/push.

## Product direction
Polish believability: richer app shells, consistent phone chrome, feed/market copy that feels real. Full Telegram/Discord/Mail gameplay comes later — previews tease integration with CoinHub investigate buttons.

## Testing
Open `index.html` in a browser or serve statically. No npm test suite. Smoke: home → each app → CoinHub trade → X feed → Settings wallpaper.

## Commits
Small commits with clear messages. Push after each iteration per cloud agent rules.
