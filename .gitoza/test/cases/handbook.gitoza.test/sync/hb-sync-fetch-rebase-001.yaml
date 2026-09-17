---
title: Sync pipeline performs fetch then rebase
status: active
priority: high
approve_status: approved
tags:
  - handbook
  - sync
  - git
  - rebase
requirement_ids:
  - GITO-SYNC02
---

# Sync pipeline performs fetch then rebase

## Steps

1. On a **fork** with a writable remote, ensure the remote tracking branch may have newer commits (optional: push a small change from another clone first).
2. Make a local edit in Gitoza, click **Sync**, then **Confirm Changes**.
3. Observe the sync progress / Git operations.

## Expected Result

The pipeline **fetches** from the remote and **rebases** local commits onto the remote tracking branch before publishing ([[GITO-SYNC02]] AC-8).

## Related

- [[GITO-SYNC02|Git workspace sync with grouped diffs and conflict resolution]]
- [[wiki:W-HBK040|Sync and Confirm Changes]]
