# Bookman — Lenny's Podcast Book Tracker

Automatically tracks every book recommended on [Lenny's Podcast](https://www.lennyspodcast.com/), extracted from daily summaries on [Batlab's Substack](https://coverdrive.substack.com/).

## 📊 Stats

| Metric | Value |
|--------|-------|
| **Total Books** | 65 |
| **Episodes Covered** | 28 |
| **Categories** | 36 |
| **Last Updated** | 2026-04-22 |

## 📁 Files

- [`books.json`](books.json) — Complete database with metadata, ratings, and links
- [`books.md`](books.md) — Human-readable list grouped by episode
- [`trends.md`](trends.md) — Category breakdown, most featured authors, timeline

## 🤖 How It Works

"Bookman runs daily at 6:30 AM, checks for new Lenny's Podcast summaries on Substack, extracts book recommendations" from the designated section, enriches them with ratings and vendor links, and commits changes to the repository.
