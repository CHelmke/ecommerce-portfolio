# Example Remediation Tracker

The table below shows how I would turn an account-health issue into an owned workflow. All identifiers and scenarios are fictional.

| SKU / ASIN | Issue | Risk | Root cause to verify | Owner | Case / evidence | Status | Next action | Close criteria |
|---|---|---:|---|---|---|---|---|---|
| B0DEMO101 | Listing suppressed - image policy | High | Non-compliant main-image element | Marketplace Ops | CASE-10482 | Fix in progress | Replace image and monitor suppression status | Listing active and compliant image live |
| B0DEMO102 | Required attribute missing | Medium | Legacy setup missing structured field | Content VA | CASE-10491 | Needs review | Validate source spec and update attribute | Backend value confirmed and browse placement retained |
| B0DEMO103 | Related-image risk | High | Same creative template used on sibling ASINs | Designer | Evidence folder | Preventive review | Audit related listings before suppression occurs | Related main images pass QA checklist |
| B0DEMO104 | Variation child detached | High | Parent/child relationship error | Marketplace Ops | CASE-10502 | Case open | Provide evidence and follow Seller Support | Child visible under correct parent |
| B0DEMO105 | Material attribute inaccurate | Medium | Incorrect catalog value | Content VA | Source spec | Queued | Confirm material and correct field | Verified value visible in backend/PDP |

## Operating rule
A support case is not the end of the task. I keep an owner, next action, due date and verification condition until the live catalog result is confirmed.
