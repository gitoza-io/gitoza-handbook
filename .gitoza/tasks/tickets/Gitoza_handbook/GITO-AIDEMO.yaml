---
title: Document ticket lifecycle from open to release
type: task
status: done
priority: high
tags:
- handbook
- demo
- ai-promo
- workflow
reporter: Gitoza Handbook
---

# Document ticket lifecycle from open to release

> Demo seed for the **AI task-management** silent video.

## Goal

Explain the happy-path lifecycle of a handbook ticket so new contributors know when to change status and when to attach a release.

## Lifecycle (text only — diagram TBD)

1. **open** — ticket created, ready to pick up
2. **in_progress** — someone is actively working
3. **in_testing** — linked test cases / validation in progress
4. **done** — work accepted
5. Optionally link a **release** (e.g. `Gitoza_handbook/1.1.4`) when shipping

```mermaid
flowchart LR
  open[open]
  inProgress[in_progress]
  inTesting[in_testing]
  done[done]
  release[release]
  open --> inProgress
  inProgress --> inTesting
  inTesting --> done
  done -.->|optional| release
```

## Acceptance criteria

- [x] Clear Mermaid flowchart of the status transitions
- [x] Short note on when to set `release:`
- [x] Links to [[wiki:W-HBK011|Ticket types]] and [[wiki:W-HBK012|Releases]]

## References

- [[wiki:W-HBK010|Tickets overview]]
- [[GITO-TASK01|Example task — update handbook for v1.1.4]]
