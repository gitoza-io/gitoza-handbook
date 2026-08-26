---
title: Linking tickets and test cases
status: published
tags:
  - handbook
  - testing
---

# Linking tickets and test cases

Connect planning work (tickets) with test coverage (cases and runs).

## Tested by (cases → ticket)

On a **test case**, add ticket ids under **Requirement IDs**. On the **ticket detail**, Gitoza shows a **Tested by** list with those cases.

Example case snippet:

```yaml
---
title: Verify login error message
requirement_ids:
  - GITO-BUG001
---
```

Open [[GITO-BUG001]] and case **hb-verify-login** (suite **auth**) to see this link live. Other handbook cases link [[GITO-SRCH01]], [[GITO-WIKI01]], [[GITO-EDIT01]], and more.

## Covered by runs (run → ticket)

On a **test run**, set **Covers** (requirement ids) on the run summary. The ticket shows **Covered by runs**.

Create a run (see [[wiki:W-HBK021|Test Runs]]), cover [[GITO-LINK01]], and open that ticket’s **Covered by runs** section.

## Body links

In ticket or wiki Markdown bodies you can write:

- Ticket by id: [[GITO-PZWZHT]]
- Wiki by id: [[wiki:W-HBK001]]
- Labeled forms (outside tables): see [[wiki:W-HBK031|Linking syntax]]

Do not put `[[id|label]]` inside a Markdown table cell — the `|` is treated as a column separator. Use a bare `[[id]]` in the cell instead.

Back: [[wiki:W-HBK010|Tickets overview]]
