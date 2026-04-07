# 📚 Bookman — Lenny's Podcast Book Tracker

> Automatically tracking every book recommended on [Lenny's Podcast](https://www.lennyspodcast.com/), summarized daily by [Batlab](https://coverdrive.substack.com).

## 📊 Stats

| Metric | Value |
|--------|-------|
| Total Books | 53 |
| Episodes Covered | 21 |
| Categories | 32 |
| Latest Episode | 2026-04-07 |
| Last Updated | 2026-04-07 |

## 📁 Files

- [`books.json`](books.json) — Full structured database of all books
- [`books.md`](books.md) — Human-readable list grouped by episode
- [`trends.md`](trends.md) — Category breakdown, top guests, timeline

## 🤖 How It Works

Bookman is a Claude-powered agent that:
1. Checks [coverdrive.substack.com](https://coverdrive.substack.com) daily for new Lenny's Podcast episode summaries
2. Extracts every book from the 📚 Recommended Books section
3. Enriches entries with category tags and Amazon links
4. Commits updates to this repo automatically

_Powered by [Batlab AI](https://coverdrive.substack.com) · Updated 2026-04-07_
