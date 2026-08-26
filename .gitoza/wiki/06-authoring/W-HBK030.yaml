---
title: Tables, code blocks, and Mermaid
status: published
tags:
  - handbook
  - authoring
  - editor
---

# Tables, code blocks, and Mermaid

Library pages (and ticket / case bodies) use Markdown. In edit mode the toolbar can insert **code** and **Mermaid** fences; tables edit visually in the rich editor.

## Table example

| Artifact | Stored under | View in Gitoza |
|----------|--------------|----------------|
| Ticket | `.gitoza/tasks/tickets/{project}/` | Tickets |
| Wiki page | `.gitoza/wiki/.../` | Library |
| Test case | `.gitoza/test/cases/{project}/` | Test Repository |
| Test run | `.gitoza/test/runs/{run_id}/` | Test Run |

## Code block example

```yaml
---
title: Example frontmatter
type: task
status: open
priority: medium
---
```

## Mermaid example

```mermaid
flowchart LR
  edit[Edit Markdown]
  table[Table]
  code[Code fence]
  mermaid[Mermaid fence]
  preview[Read mode renders]
  edit --> table
  edit --> code
  edit --> mermaid
  table --> preview
  code --> preview
  mermaid --> preview
```

## Try it

1. Open this page in **Library** and switch to **Edit**.
2. Place the cursor in the body and use **Insert Mermaid diagram** or **Insert code**.
3. Switch back to read mode to confirm the diagram renders.
4. See ticket [[GITO-EDIT01|Markdown tables and Mermaid]] for the same idea on a ticket.

Next: [[wiki:W-HBK031|Linking syntax]]
