# Claude Code Memory Starter (free)

Two plain files that stop Claude Code from forgetting your decisions and losing paused work.
No installer, no scripts. Works on Windows, macOS, and Linux. Setup takes about 5 minutes.

## What's inside
| File | What it does |
|---|---|
| `CLAUDE.md` | Working rules Claude reads at the start of every session: plain answers, "done only after checking", ask before send/delete/pay/publish, record decisions and lessons. |
| `OPEN-ITEMS.md` | A ledger for paused work. Every item records *why* it stopped, so nothing silently disappears. |
| `LESSONS.md` | Where corrections go. "No, that's wrong" becomes a one-line rule Claude reads next time. |

## Setup (5 minutes)
1. Open the folder you use with Claude Code (your project folder).
2. Copy `CLAUDE.md`, `OPEN-ITEMS.md`, and `LESSONS.md` into it.
   - Already have a `CLAUDE.md`? Paste the contents of ours at the end of yours.
3. Open `CLAUDE.md` and fill in the three lines under **About me**.
4. Start a new Claude Code session and type:
   `Read CLAUDE.md and OPEN-ITEMS.md, then tell me what's waiting on me.`

That's it. From now on:
- When work pauses, say "park this" — Claude adds a line to `OPEN-ITEMS.md` with the reason.
- When you correct Claude, it adds a line to `LESSONS.md`.
- Start each session with "What's waiting on me?"

## What this starter does NOT do
These are manual. You have to remember to ask.
- No automatic reminder at session start
- No automatic capture of corrections
- No knowledge vault, no one-line routines (/start, /handoff, /restore, /distill)

If you want all of that to happen on its own, the paid version does it:
**Knowhowseller Lite** — a one-click Windows installer with hooks that show waiting items at every session start, capture corrections automatically, keep an Obsidian knowledge vault, and add one-line routines.
https://metaro.gumroad.com/l/lite

## License
See [LICENSE](LICENSE).
Free to use and modify for yourself and your team. Please don't resell it.
Questions: support@knowhowseller.com
