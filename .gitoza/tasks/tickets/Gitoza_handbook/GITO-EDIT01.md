---
title: Markdown tables and Mermaid
type: task
status: open
priority: medium
tags:
  - handbook
  - editor
reporter: Gitoza Handbook
---

# Markdown tables and Mermaid

Tickets support the same Markdown features as Library pages: tables, fenced code, and Mermaid diagrams.

## Table

| Control | Where |
|---------|--------|
| Insert code | Editor toolbar |
| Insert Mermaid | Editor toolbar |
| Insert link | Editor toolbar |

## Mermaid

```mermaid
flowchart TD
  ticket[Ticket body]
  wiki[Wiki page W-HBK030]
  render[Read mode]
  ticket --> render
  wiki --> render
```

## Code

```yaml
type: task
status: open
tags:
  - editor
```

Open the dedicated showcase page: [[wiki:W-HBK030|Tables, code blocks, and Mermaid]].
