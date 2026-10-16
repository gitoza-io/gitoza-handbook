---
title: Tested by and Covered by runs
type: bug
status: in_testing
priority: high
tags:
  - handbook
  - linking
reporter: Gitoza Handbook
---

# Tested by and Covered by runs

This ticket shows **reverse links** from test artifacts back to planning work.

## Tested by (cases)

Test cases list this ticket id in **Requirement IDs**. Open this ticket detail — section **Tested by** should include:

- **hb-checkout-smoke** (Checkout smoke test) under suite **checkout**
- Cases under suite **test-run** such as **Create a test run inline** and **Add cases with folder bulk-select and preview**

Case **hb-verify-login** links to [[GITO-BUG001]] instead — compare the two tickets.

## Covered by runs

Test runs can list ticket ids under **Covers**. Create a run in **Test Run**, add `hb-checkout-smoke`, set **Covers** to this ticket id, then reopen this ticket and check **Covered by runs**.

See [[wiki:W-HBK021|Test Runs]] for the create-a-run walkthrough.

## Why link?

Linking connects *what you plan* (tickets) with *what you verify* (cases and runs) without duplicating ids in ticket YAML.

See: [[wiki:W-HBK022|Linking tickets and test cases]]

```mermaid
flowchart LR
  ticket[GITO-LINK01 ticket]
  case[hb-checkout-smoke case]
  run[Your test run]
  case -->|requirement_ids| ticket
  run -->|Covers| ticket
```
