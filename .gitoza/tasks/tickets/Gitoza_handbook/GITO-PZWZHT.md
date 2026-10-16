---
title: Welcome — start here
priority: high
release: Gitoza_handbook/1.1.4
reporter: Gitoza Handbook
status: open
tags:
- Handbook
- Getting-started
type: task
---

# Welcome — start here

This ticket is the **table of contents** for the Gitoza Handbook project. Use it as a map while you explore the app.

## What this handbook covers

- **Library** (wiki) — numbered folders under `.gitoza/wiki/` (`01-overview` … `06-authoring`)
- **Tickets** — types, tags, parents, releases, search, linking, editor samples
- **Test Repository** — sample cases in project `handbook.gitoza.test`
- **Test Run** — add your own runs when you are ready to demo execution

## Suggested reading order

```mermaid
flowchart TD
  start[Start here]
  overview[01-overview]
  gettingStarted[02-getting-started]
  tickets[03-tickets]
  testing[04-testing]
  sync[05-sync]
  authoring[06-authoring]
  cases[Test Repository cases]
  start --> overview
  overview --> gettingStarted
  gettingStarted --> tickets
  tickets --> testing
  testing --> sync
  sync --> authoring
  authoring --> cases
```

## Quick links — Library

- [[wiki:W-HBK000|Gitoza at a glance]]
- [[wiki:W-HBK001|Welcome to the Gitoza Handbook]]
- [[wiki:W-HBK004|App layout and navigation]]
- [[wiki:W-HBK011|Ticket types]]
- [[wiki:W-HBK013|Search and filter tickets]]
- [[wiki:W-HBK030|Tables, code blocks, and Mermaid]]
- [[wiki:W-HBK040|Sync and Confirm Changes]]

## Type examples

| Type  | Ticket              |
| ----- | ------------------- |
| bug   | [[GITO-BUG001]] |
| story | [[GITO-STOR01]] |
| task  | [[GITO-TASK01]] |
| spike | [[GITO-SPIKE1]] |

## Feature walkthroughs

- [[GITO-TAGS01|Using tags on tickets]]
- [[GITO-SRCH01|Search and filter walkthrough]]
- [[GITO-PARNT1|Parent tickets]] → child [[GITO-CHLD01]]
- [[GITO-LINK01|Tested by and Covered by runs]]
- [[GITO-REL01|Working with releases]]
- [[GITO-WIKI01|Wiki links from tickets]]
- [[GITO-EDIT01|Markdown tables and Mermaid]]
- [[GITO-SYNC01|Practice the Sync workflow]]
- [[GITO-DASH01|Explore the Dashboard]]

## Status / filter samples

- Done: [[GITO-DONE01]] · Cancelled: [[GITO-DONE02]] · In testing: [[GITO-REG001]] · Backlog: [[GITO-BACK01]] · High priority: [[GITO-HIGH01]]

## Keep your own copy

This upstream handbook is **read-only**. Fork the repo on GitHub to edit and sync your own version.
