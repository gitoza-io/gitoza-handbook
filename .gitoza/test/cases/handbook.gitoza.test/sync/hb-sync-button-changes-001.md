---
title: Sync button visible when workspace has changes
status: active
priority: high
approve_status: approved
tags:
  - handbook
  - sync
  - git
requirement_ids:
  - GITO-SYNC02
---

# Sync button visible when workspace has changes

## Steps

1. On a **fork** of this handbook (upstream is read-only), open a remote-backed workspace.
2. Edit any artifact (ticket, wiki page, or test case) and wait for autosave.
3. Confirm the workspace shows unsynced local changes (for example **Drafting** / local-changes status).
4. Look at the workspace chrome (title bar / workspace actions).

## Expected Result

The **Sync** button is **visible** whenever the workspace has at least one unsynced local change ([[GITO-SYNC02]] AC-1).

## Related

- [[GITO-SYNC02|Git workspace sync with grouped diffs and conflict resolution]]
- [[wiki:W-HBK040|Sync and Confirm Changes]]
