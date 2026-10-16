---
title: Auth regression — session refresh
status: active
priority: high
approve_status: approved
tags:
  - handbook
  - auth
  - regression
requirement_ids:
  - GITO-AUTH02
  - GITO-BUG001
---

# Auth regression — session refresh

## Steps

1. Sign in with valid credentials.
2. Hard-refresh the client.
3. Confirm the session remains (or capture the failure for [[GITO-AUTH02]]).
4. Compare with invalid-login messaging covered by `hb-verify-login` / [[GITO-BUG001]].

## Expected Result

Session handling matches product expectations; failures are tracked on the linked tickets.

## Tested by

This case lists **GITO-AUTH02** and **GITO-BUG001** under Requirement IDs so both tickets show it under **Tested by**.
