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

**Reproduction commit link:** https://github.com/casuallama/pathreview/commit/a2bec6874f3386d7827f7981b14838c5743334aa

**Reproduction summary:**
Reviewed `docs/API.md` and confirmed every listed endpoint (health, auth, profiles, reviews) is documented only as a method + path + one-line description, with no accompanying `curl` request or example response anywhere in the file — matching the gap described in issue #117 exactly. The fix is to add a runnable `curl` example (and expected response) under each endpoint.

**PLAN.md link:** https://github.com/casuallama/pathreview/blob/docs/117-api-curl-examples/PLAN.md

**Walkthrough video (recommended):** 

**Blockers or open questions:**
Should I also document PUT /profiles/{profile_id} and GET /reviews/{review_id}/status?

## Week 9 — Solution building & PR submission

### Check-in 1 (mid-week)

**Current progress:**
I have not implemented anything. Still getting around to working on this project.

**Next steps:**
Setting up environment well, I did not do that last assignment because it was a documentation issue so I didn't see the need to. And then implementing my changes to the API docs.

**Blockers:**

---

### Check-in 2 (end of week)

**PR link:** https://github.com/ascherj/pathreview/pull/793

**Branch:** docs/17-api-curl-examples

**What you built:**
I added the curl examples to the API documentation.

**Tests added or updated:**
Did not touch any test files.

**Self-review confirmation:** [x] make check passes  [x] make test-unit passes

**Draft PR feedback received from:** none