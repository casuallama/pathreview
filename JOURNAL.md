## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/117

**Issue title:** API docs don't include example curl commands
 #117

**Tier:** [x] Tier 1  [ ] Tier 2  [ ] Tier 3

**Problem summary:**
The API documentation is missing example calls to the API endpoints. This lack
of documentation makes it difficult for developers to quickly test whether the
API is working. Adding example `curl` commands to `docs/API.md` would fix
this by giving developers something they can copy, run, and get a real
response from.

**Branch name:** docs/117-api-curl-examples

**Setup confirmation:** [x] App runs locally at localhost:5173

**Cohort ledger:** [x] Issue added to cohort ledger

## Week 8 — Reproduction & solution planning

**Reproduction commit link:** [link to commit documenting the reproduced issue]

**Reproduction summary:**
Reviewed `docs/API.md` and confirmed every listed endpoint (health, auth, profiles, reviews) is documented only as a method + path + one-line description, with no accompanying `curl` request or example response anywhere in the file — matching the gap described in issue #117 exactly. The fix is to add a runnable `curl` example (and expected response) under each endpoint.

**PLAN.md link:** [link to PLAN.md in your fork]

**Walkthrough video (recommended):** [link to your Loom video, ≤2 min — recommended, not graded]

**Blockers or open questions:**
[Anything you're still uncertain about going into Week 9, or leave blank]