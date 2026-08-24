---
title: Example bug — broken login redirect
type: bug
status: open
priority: high
tags:
  - handbook
  - auth
reporter: Gitoza Handbook
---

# Example bug — broken login redirect

## When to pick type **bug**

Use **bug** when something does not work as expected — a defect in existing behavior.

## Description

After entering valid credentials, some users land on a blank page instead of the dashboard.

## Acceptance criteria

- Login with valid credentials redirects to the dashboard
- No blank page or console errors
- Error message shown when credentials are invalid

## Test coverage

Case **hb-verify-login** links to this ticket. Open this ticket detail and check **Tested by**.

See also: [[wiki:W-HBK011|Ticket types]]

```mermaid
flowchart LR
  user[User logs in]
  check{Valid credentials?}
  dashboard[Dashboard]
  error[Show error message]
  user --> check
  check -->|yes| dashboard
  check -->|no| error
```
