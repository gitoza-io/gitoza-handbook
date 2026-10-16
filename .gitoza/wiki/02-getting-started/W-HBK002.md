---
title: Connect a repository
status: published
tags:
  - handbook
  - getting-started
---

# Connect a repository

Gitoza works on a **Git repository** on branch **`gitoza`**. This handbook repo is public, so you can clone it over **HTTPS** without setting up SSH first.

## Steps in Gitoza

1. Open **Connect Repository** (or **Add workspace** from the sidebar).
2. Choose **HTTPS** and paste:
   ```text
   https://github.com/gitoza-io/gitoza-handbook.git
   ```
3. Connect. Gitoza clones a local copy and indexes the `.gitoza/` folder.

## Branch `gitoza`

Gitoza uses the **`gitoza`** branch for all test and planning files. When you sync changes, they go to `origin/gitoza`.

## Need SSH later?

SSH is optional for reading a public repo. Use SSH when you push to **your fork** or a private team repo. See **Help → Documentation** in Gitoza or [gitoza.com/help](https://gitoza.com/help).

Next: [[wiki:W-HBK003|Playground vs this handbook]]
