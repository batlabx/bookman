# 📚 Bookman — Lenny's Podcast Book Tracker

Automatically tracks every book recommended on [Lenny's Podcast](https://www.lennysnewsletter.com/podcast), extracted from daily summaries on [Batlab's Substack](https://batlab.substack.com).

## Stats

| Metric | Count |
|---|---|
| Total Books | 133 |
| Episodes Covered | 52 |
| Categories | 49 |
| Last Updated | 2026-07-18 |

## Files

- **[books.json](books.json)** — Full structured database of all book recommendations
- **[books.md](books.md)** — Human-readable list grouped by episode
- **[trends.md](trends.md)** — Category breakdown, top guests, and timeline

## How It Works

A scheduled agent runs daily at 6:30 AM, checks for new Lenny's Podcast summaries on Batlab's Substack, extracts book recommendations from the 📚 section, enriches entries with Goodreads ratings and Amazon links, and commits updates here automatically.
