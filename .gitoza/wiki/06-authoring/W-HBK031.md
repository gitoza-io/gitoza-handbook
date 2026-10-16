---
title: Linking syntax
status: published
tags:
  - handbook
  - authoring
  - linking
---

# Linking syntax

Bodies in tickets, wiki pages, and cases can link to other entities with double-bracket syntax. The shared editor toolbar **Insert link** searches tickets and wiki pages and inserts the correct snippet.

## Ticket links

**By id** (label defaults to the id):

- Live: [[GITO-BUG001]]
- Source: `` [[GITO-BUG001]] ``

**With a custom label** (use outside tables — the `|` inside `[[…]]` conflicts with Markdown table columns):

- Live: [[GITO-BUG001|Example bug — broken login redirect]]
- Source:

```text
[[GITO-BUG001|Example bug — broken login redirect]]
```

## Wiki links

Wiki targets need the `wiki:` prefix. Bare `[[…]]` is treated as a ticket id, not a wiki page.

**By page id:**

- Live: [[wiki:W-HBK001]]
- Source: `` [[wiki:W-HBK001]] ``

**With a custom label** (again, keep labeled links out of pipe tables):

- Live: [[wiki:W-HBK001|Welcome to the Gitoza Handbook]]
- Source:

```text
[[wiki:W-HBK001|Welcome to the Gitoza Handbook]]
```

## Tip for tables

In a GFM table cell, prefer a bare link such as [[GITO-BUG001]]. Put the human title in a neighboring column as plain text, or document the labeled form in a list / code fence like above.

## Try it

1. Open ticket [[GITO-WIKI01|Wiki links from tickets]] in **Edit**.
2. Click **Insert link**, search for this page, and insert a wiki link.
3. Click the rendered link in read mode — Gitoza should open **Library** on that page.
4. For case ↔ ticket coverage links, see [[wiki:W-HBK022|Linking tickets and test cases]].

```mermaid
flowchart LR
  body[Editor body]
  ticketLink["ticket id link"]
  wikiLink["wiki page link"]
  ticketsView[Tickets detail]
  libraryView[Library page]
  body --> ticketLink --> ticketsView
  body --> wikiLink --> libraryView
```
