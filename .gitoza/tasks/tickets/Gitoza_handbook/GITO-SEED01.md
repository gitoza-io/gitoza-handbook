---
title: Seed bug — ticket list loses project filter after sync
type: bug
status: open
priority: high
tags:
  - handbook
  - demo
  - ai-promo
  - tickets
reporter: Gitoza Handbook
---

# Seed bug — ticket list loses project filter after sync

> Demo seed for the **AI task-management** video.

## Problem

After **Confirm Changes / Sync**, the Tickets view sometimes shows tickets from **all projects** even though a single project folder was selected before sync.

## Steps to reproduce

1. Open **Tickets** and select project **Gitoza_handbook**.
2. Note the filtered list.
3. Sync (Confirm Changes) with a small edit.
4. Observe whether the project filter is still applied.

## Expected

Project selection (or folder focus) remains after sync.

## Actual

List briefly (or permanently) shows tickets outside the selected project until the user re-selects the folder.

## Notes

- Related wiki: [[wiki:W-HBK010|Tickets overview]] · [[wiki:W-HBK013|Search and filter tickets]]
- Do **not** close this ticket before recording; the Agent demo depends on finding it.
