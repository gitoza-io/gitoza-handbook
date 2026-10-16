---
title: Add cases with folder bulk-select and preview
status: active
priority: high
approve_status: approved
tags:
  - handbook
  - test-run
requirement_ids:
  - GITO-LINK01
---

# Add cases with folder bulk-select and preview

## Steps

1. Create or open a test run (for example **Handbook smoke**).
2. Right-click the run → **Add cases**.
3. Expand project **handbook.gitoza.test** → expand suite **auth**.
4. Check the **auth** suite checkbox to bulk-select its cases.
5. Click one case in the list and read the **Detail** panel (steps and expected result).
6. Click **Done (N)** and confirm cases appear under the run, grouped by suite.

## Expected Result

Cases are added while keeping project → suite structure. Preview helps confirm you picked the right tests before committing them to the run.

## Related

- [[wiki:W-HBK021|Test Runs]]
- [[wiki:W-HBK020|Test Repository]]
