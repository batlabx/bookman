# 📚 Bookman — Lenny's Podcast Book Tracker

Every book recommended on [Lenny's Podcast](https://www.lennyspodcast.com/), extracted from daily summaries on [Real Good Summaries](https://batlab.substack.com).

## Stats

| Metric | Value |
|--------|-------|
| Total Books | 163 |
| Episodes Covered | 64 |
| Categories | 62 |
| Last Updated | 2026-09-26 |

## Files

- **[books.json](books.json)** — Full database with metadata, ratings, and links
- **[books.md](books.md)** — Human-readable list grouped by episode
- **[trends.md](trends.md)** — Category breakdown, top authors, and timeline

## How It Works

Bookman runs daily at 6:30 AM ET. It:
1. Checks [batlab.substack.com](https://batlab.substack.com) for new Lenny's Podcast summaries
2. Extracts books from the 📚 Recommended Books section
3. Enriches entries with Goodreads ratings and Amazon links
4. Deduplicates and updates this repository

## Contributing

Found a missing book or incorrect data? Open an issue or PR.

---

*Built with ❤️ by [BatlabAI](https://github.com/batlabx)*
