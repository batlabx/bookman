# Bookman 📚

Every book recommended on Lenny's Podcast, tracked and enriched automatically.

| Stat | Count |
|------|-------|
| Total Books | 143 |
| Episodes Covered | 55 |
| Categories | 52 |
| Last Updated | 2026-07-30 |

## Files

- **[books.json](books.json)** — Full database with Goodreads ratings, Amazon links, and metadata
- **[books.md](books.md)** — Human-readable list grouped by episode
- **[trends.md](trends.md)** — Category breakdowns, most featured authors, and timeline

## How It Works

Bookman runs daily at 6:30 AM, checks for new Lenny's Podcast summaries on [Real Good Summaries](https://batlab.substack.com), extracts book recommendations from the 📚 section, enriches them with Goodreads ratings, and commits updates to this repo.
