# Claude Code Memory Starter (free) — a CLAUDE.md template for non-developers

<a href="https://www.producthunt.com/products/claude-code-memory-starter?launch=claude-code-memory-starter" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1329256&theme=light" alt="Claude Code Memory Starter on Product Hunt" width="250" height="54" /></a>

**Launched on Product Hunt on Nov 25, 2026.** Questions, feedback, or what you'd add to a non-developer's `CLAUDE.md` — tell us in the [launch comments](https://www.producthunt.com/products/claude-code-memory-starter?launch=claude-code-memory-starter).

Plain files that stop Claude Code from forgetting your decisions, your corrections, and your paused work.
Made for people who use Claude Code for **business work, not code**: owners, freelancers, marketers, operators.
No installer, no scripts. Works on Windows, macOS, and Linux. Setup takes about 5 minutes.

## What's inside
| File | What it does |
|---|---|
| `CLAUDE.md` | Working rules Claude reads at the start of every session: plain answers, "done only after checking", ask before send/delete/pay/publish, record decisions and lessons. |
| `OPEN-ITEMS.md` | A ledger for paused work. Every item records *why* it stopped, so nothing silently disappears. |
| `LESSONS.md` | Where corrections go. "No, that's wrong" becomes a one-line rule Claude reads next time. |

## Examples by role
Ready-made "About me" + extra rules you can paste into `CLAUDE.md`:
- [Small business owner](examples/small-business-owner.md) — contracts, quotes, client emails, reports
- [Freelancer / consultant](examples/freelancer-consultant.md) — proposals, meeting notes, client follow-ups
- [Marketer / creator](examples/marketer-creator.md) — drafts, captions, campaigns, research

## Why this works
- Claude Code starts every session with a fresh context. `CLAUDE.md` is the one file it always reads, so that's where the rules live.
- Long rules files get skimmed. Keep one line per rule and move details into separate notes.
- Most lost work isn't failed work, it's *stalled* work. Writing down **why** something stopped is what brings it back.
- Being corrected twice for the same thing is the real failure. A lessons file makes corrections stick.

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
