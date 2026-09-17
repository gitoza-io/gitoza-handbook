---
title: Git workspace sync with grouped diffs and conflict resolution
type: story
status: in_progress
priority: high
tags:
- handbook
- sync
- git
- demo
- ai-promo
reporter: Gitoza Handbook
---

# Git workspace sync with grouped diffs and conflict resolution

> Feature story for the **AI-generated test cases** demo. Covers Sync button visibility, grouped change review, Confirm Changes, fetch/rebase, conflict resolution, and push.

## User story

As a **contributor working in a Gitoza workspace connected to Git**, I want to **review every local change by entity group, confirm them, and sync with fetch/rebase plus conflict handling**, so that I can **push a clean update to the remote without leaving the app**.

## Scope

Applies to a remote-backed workspace (not Playground Save-only). Local edits may include test cases, test runs, config, tickets, and wiki pages.

## Acceptance criteria

### Sync button visibility

- [ ] **AC-1.** When the workspace has at least one unsynced local change, the **Sync** button is **visible** in the workspace chrome (title bar / workspace actions).
- [ ] **AC-2.** When the workspace has **no** unsynced local changes, **Sync** is **not visible** (or is hidden until new edits exist).

### Review UI after clicking Sync

- [ ] **AC-3.** Clicking **Sync** opens the change-review UI (Confirm Changes) and lists **all pending local changes**.
- [ ] **AC-4.** Changes are **grouped** by entity type. Groups include at least:
  - **Cases**
  - **Run**
  - **Config**
  - **Ticket**
  - **Wiki**
- [ ] **AC-5.** Empty groups are omitted or shown empty in a consistent way; populated groups show each changed item.
- [ ] **AC-6.** Selecting an item in the list shows that item’s **diff in the detail pane** (before vs after).

### Confirm and start sync

- [ ] **AC-7.** Clicking **Confirm Changes** (or equivalent confirm action) **starts the sync pipeline** for the reviewed changes.
- [ ] **AC-8.** The sync pipeline performs **fetch** then **rebase** onto the remote tracking branch before publishing local commits.

### Conflict resolution

- [ ] **AC-9.** If rebase (or merge) **encounters conflicts**, the UI enters a **conflict resolution** state instead of failing silently.
- [ ] **AC-10.** For each conflicted file or hunk, the user can choose **Keep mine** (local / ours) or **Keep shared** (incoming / theirs).
- [ ] **AC-11.** After all conflicts are resolved with Keep mine / Keep shared, sync **continues** (rebase completes).

### Push and workspace update

- [ ] **AC-12.** After a successful rebase (with or without conflicts), Gitoza **pushes** the result to the remote.
- [ ] **AC-13.** After push, the UI **updates** to reflect a clean workspace: diffs clear, Sync hides (AC-2), and the remote-backed content matches what was confirmed.

## Out of scope

- Playground **Save** (local-only commit) — see [[wiki:W-HBK040|Sync and Confirm Changes]]
- **Refresh / Force Full Reindex** — see [[wiki:W-HBK041|Refresh and reindex]]

## Notes for test design

Cover happy path (visible Sync → grouped list → detail diff → Confirm Changes → fetch/rebase → push → clean workspace) and at least one conflict path (Keep mine and Keep shared). Use a fork or writable remote; upstream handbook is read-only.

## References

- [[GITO-SYNC01|Practice the Sync workflow]]
- [[wiki:W-HBK040|Sync and Confirm Changes]]
- [[wiki:W-HBK041|Refresh and reindex]]
- [[wiki:W-HBK022|Linking tickets and test cases]]
