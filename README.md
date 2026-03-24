# ð Bookman

**Every book recommended on [Lenny's Podcast](https://www.lennyspodcast.com/), curated and enriched automatically.**

Bookman is an autonomous agent that watches the daily [Lenny's Podcast summaries on Batlab](https://coverdrive.substack.com), extracts every book recommendation, and enriches each entry with Goodreads ratings, Amazon links, and category tags. This repo is the single source of truth â updated daily.

---

## ð Stats

| Metric | Count |
|--------|-------|
| Total Books | 35 |
| Episodes Covered | 11 |
| Categories | 26 |
| Last Updated | 2026-03-24 |

## ðï¸ Data Files

| File | Description |
|------|-------------|
| [`books.json`](books.json) | Complete book database â all fields, machine-readable |
| [`books.md`](books.md) | Human-readable book list grouped by episode |
| [`trends.md`](trends.md) | Most recommended books, category breakdown, guest patterns |

## ð Book Schema

Each book entry in `books.json` contains:

```json
{
  "id": "never-split-the-difference-chris-voss",
  "title": "Never Split the Difference",
  "author": "Chris Voss",
  "category": "Negotiation & Communication",
  "guest": "Jacob Warwick",
  "episode_title": "The Tactical Playbook for Getting 20-40% More Comp",
  "episode_date": "2026-03-16",
  "source_url": "https://coverdrive.substack.com/p/...",
  "goodreads_rating": 4.36,
  "goodreads_url": "https://www.goodreads.com/book/show/...",
  "amazon_url": "https://www.amazon.com/s?k=...",
  "times_recommended": 1,
  "added_at": "2026-03-22"
}
```

## ð·ï¸ Categories

Books are auto-tagged into categories like Business & Startups, Science Fiction, Self-Help & Psychology, Leadership & Management, Technology & Programming, History & Classics, and more.

## ð How It Works

1. **Daily trigger** â Bookman runs after the Lenny's Podcast daily summarizer completes
2. **Extract** â Parses the latest summary for the ð Recommended Books section
3. **Deduplicate** â Checks against existing entries; increments `times_recommended` for repeats
4. **Enrich** â Fetches Goodreads rating and generates Amazon search links
5. **Categorize** â Auto-tags each book into a thematic category
6. **Commit** â Pushes updated `books.json`, `books.md`, and `trends.md` to this repo

## ð¤ Powered By

Built as a [Cowork](https://claude.com) skill by Batlab. Runs on Claude with the Bookman skill and a scheduled task.

---

*"A reader lives a thousand lives before he dies. The man who never reads lives only one." â George R.R. Martin*
