# 📚 Bookman

Automated book tracker for [Lenny's Podcast](https://www.lennyspodcast.com/), powered by Batlab's Cowork agent.

Every book recommendation from Lenny's Podcast daily summaries on [coverdrive.substack.com](https://coverdrive.substack.com) is extracted, enriched, and tracked here.

## Stats

| Metric | Value |
|--------|-------|
| 📚 Total Books | 55 |
| 🎙️ Episodes Covered | 22 |
| 📁 Categories | 32 |
| 🗓️ Last Updated | 2026-04-09 |

## Files

- `books.json` — Full database of all book entries
- `books.md` — Books grouped by episode with Amazon links
- `trends.md` — Category breakdown, guest analysis, timeline

## How It Works

A scheduled Cowork agent runs daily at 6:30 AM and:
1. Checks for new Lenny's Podcast summaries on Substack
2. Extracts book recommendations from the 📚 section
3. Deduplicates and increments `times_recommended` for repeat picks
4. Commits updated files to this repo

---
*Built with [Batlab Cowork](https://coverdrive.substack.com)*
