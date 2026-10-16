---
title: Record Pass and Fail with folder badge rollup
status: active
priority: high
approve_status: approved
tags:
  - handbook
  - test-run
requirement_ids:
  - GITO-LINK01
---

# Record Pass and Fail with folder badge rollup

## Steps

1. Open a run that includes cases from suite **auth** (add them first if needed).
2. Expand the run → select suite **auth** → pick **Verify login error message**.
3. Click **Pass** on one case and **Fail** on another in the same suite.
4. Watch the badge pills on the **auth** folder row in the run tree.
5. Open **Run summary** (select the run, no case selected) and confirm passed/failed counts match.

## Expected Result

Results update immediately on each case. Folder badges and run summary reflect progress without a separate save step.

## Related

- [[wiki:W-HBK021|Test Runs]]
- [[GITO-LINK01|Tested by and Covered by runs]]
