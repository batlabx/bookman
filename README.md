# ð Bookman â Lenny's Podcast Book Tracker

Every book recommended on [Lenny's Podcast](https://www.lennyspodcast.com/), extracted from daily summaries on [Batlab's Substack](https://coverdrive.substack.com).

## Stats

| Metric | Value |
|--------|-------|
| Total Books | 62 |
| Episodes Covered | 25 |
| Categories | 36 |
| Last Updated | 2026-04-13 |

## Files

- **[books.json](books.json)** â Full structured database of all books
- **[books.md](books.md)** â Human-readable list grouped by episode
- **[trends.md](trends.md)** â Category breakdowns, top authors, and timeline

## How It Works

Bookman is an automated agent that:
1. Checks [coverdrive.substack.com](https://coverdrive.substack.com) for new Lenny's Podcast summaries
2. Extracts book recommendations from the ð Recommended Books section
3. Deduplicates against the existing database
4. Enriches entries with Amazon links and category tags
5. Commits updated files to this repository

---
*Maintained by [Batlab](https://github.com/batlabx) â¢ Powered by Bookman*
