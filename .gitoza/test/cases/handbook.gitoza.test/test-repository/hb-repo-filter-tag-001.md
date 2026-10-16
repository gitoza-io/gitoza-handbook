---
title: Filter cases by tag in Test Repository
status: active
priority: medium
approve_status: approved
tags:
  - handbook
  - test-repository
  - search
requirement_ids:
  - GITO-SRCH01
  - GITO-TAGS01
---

# Filter cases by tag in Test Repository

## Steps

1. Open **Test Repository** → project **handbook.gitoza.test**.
2. Open **Filter cases** and add **Tag** = `test-run`.
3. Confirm cases from suite **test-run** appear (for example **Create a test run inline**).
4. Clear chips and search free text `checkout` — confirm **Checkout smoke test** is listed.
5. Select a result and confirm the Detail panel loads.

## Expected Result

Search chips and free-text filter narrow the case list. The same panel works in Test Repository and in Add cases to run.

## Related

- [[GITO-SRCH01|Search and filter walkthrough]]
- [[GITO-TAGS01|Using tags on tickets]]
- [[wiki:W-HBK020|Test Repository]]
