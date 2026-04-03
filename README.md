# 📚 Bookman

_Automated book tracker for Lenny's Podcast summaries, published on [Batlab's Substack](https://coverdrive.substack.com)._

---

## 📊 Stats

| Metric | Value |
|--------|-------|
| Total Books | 36 |
| Episodes Covered | 12 |
| Categories | 26 |
| Last Updated | 2026-04-03 |

---

## 📁 Files

| File | Description |
|------|-------------|
| `books.json` | Full structured database of all book recommendations |
| `books.md` | Books grouped by episode, sorted by date descending |
| `trends.md` | Category breakdown, guest analysis, author frequency, timeline |

---

## 🔄 How It Works

Bookman is an automated agent that runs daily at 6:30 AM to:
1. Fetch the latest Lenny's Podcast summaries from Batlab's Substack
2. Extract book recommendations from the 📚 section of each summary
3. Enrich entries with Goodreads ratings and Amazon links
4. Commit updated data back to this repository

---

_Powered by [Bookman](https://coverdrive.substack.com) · Last run: 2026-04-03_
