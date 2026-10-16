---
title: Releases
status: published
tags:
  - handbook
  - tickets
  - releases
---

# Releases

**Releases** group tickets for a shippable version. Each release is a YAML file under the ticket project’s `releases/` folder.

## Disk layout

```text
.gitoza/tasks/tickets/Gitoza_handbook/
  GITO-PZWZHT.yaml
  releases/
    1.1.4.yaml
```

The release id is typically `{project}/{name}` (for example `Gitoza_handbook/1.1.4`). Tickets can set a `release:` field in frontmatter to appear on that release.

## Try it

1. Open **Releases** in the sidebar.
2. Select project **Gitoza_handbook** → release **1.1.4**.
3. Open ticket [[GITO-PZWZHT]] or [[GITO-TASK01]] and note the **release** field.
4. Read story [[GITO-REL01|Working with releases]] for a guided walkthrough.

## Related

- [[wiki:W-HBK010|Tickets overview]]
- [[wiki:W-HBK013|Search and filter tickets]]

Help: [gitoza.com/help](https://gitoza.com/help) → Workspace → Releases
