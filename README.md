# Gitoza Handbook

Official Gitoza handbook — learn tickets, wiki, test cases, and runs in Git. Clone this repository, open it in [Gitoza](https://gitoza.com), and follow along inside the app.

**Clone (HTTPS, no SSH required for public read):**

```text
https://github.com/gitoza-io/gitoza-handbook.git
```

Connect Gitoza to this repo on branch **`gitoza`**.

## Read-only upstream

This repository is maintained by the Gitoza team. **Do not push** changes here. To keep your own copy, [fork](https://github.com/gitoza-io/gitoza-handbook/fork) on GitHub and connect Gitoza to your fork instead.

## Where to start in Gitoza

| Area | Entry point |
|------|-------------|
| **Library** (Wiki) | Open **Library** → folder **02-getting-started** → page *Welcome to the Gitoza Handbook* (`W-HBK001`) |
| **Tickets** | Open **Tickets** → project **Gitoza_handbook** → ticket **Welcome — start here** (`GITO-PZWZHT`) |
| **Test Repository** | Project **handbook.gitoza.test** → suites under **getting-started**, **auth**, **checkout**, **linking**, **wiki**, **test-run**, **test-repository** |
| **Test Run** | Create your own run from the handbook cases (none is pre-committed) |

## Handbook map

### Library (Wiki)

Folders are numbered so they sort in reading order:

- **01-overview** — Gitoza at a glance (product map)
- **02-getting-started** — Welcome, connect a repo, Playground vs handbook, app layout, Dashboard
- **03-tickets** — Tickets overview, types, releases, search and filters
- **04-testing** — Test Repository, Test Runs, linking tickets and cases
- **05-sync** — Sync / Confirm Changes, Refresh and reindex
- **06-authoring** — Tables, code blocks, Mermaid, linking syntax

### Tickets (project `Gitoza_handbook`)

- **Welcome hub** — `GITO-PZWZHT`
- **Type examples** — `GITO-BUG001`, `GITO-STOR01`, `GITO-TASK01`, `GITO-SPIKE1`
- **Feature walkthroughs** — tags, search/filters, parent/child, releases, wiki links, editor, sync, dashboard
- **Filter samples** — done / cancelled / in_testing / backlog / high priority tickets for search demos

### Test cases (project `handbook.gitoza.test`)

Suites include **getting-started**, **auth**, **checkout**, **linking**, **wiki**, **test-run**, and **test-repository**. Cases set **Requirement IDs** so ticket **Tested by** lists populate. The **test-run** suite walks through create run → add cases (bulk-select, search, preview) → Pass/Fail → Sync. Add your own runs when you want execution screenshots or demos.

Written for Gitoza v1.1.x. More topics: [gitoza.com/help](https://gitoza.com/help)
