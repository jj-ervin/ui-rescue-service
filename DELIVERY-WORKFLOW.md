# AI UI Rescue Service — Delivery workflow

Use this workflow with [SERVICE-SCOPE.md](SERVICE-SCOPE.md). Each gate produces a durable record; a later step does not retroactively supply an earlier approval.

## 1. Qualify and freeze intake

Complete [CLIENT-INTAKE.md](CLIENT-INTAKE.md).

Confirm:

- selected offer and acknowledged UNVALIDATED pilot price;
- one exact page/state, business goal, and intended audience;
- authorized source/access and any privacy restrictions;
- viewport and browser conditions;
- known functional behavior that must be preserved;
- environment allowed for review and, if applicable, implementation; and
- explicit statement that deployment is excluded unless separately approved.

**Gate:** Both parties confirm the intake and v0.1 boundary. If the target cannot be reproduced or reviewed lawfully and safely, stop and document the reason.

## 2. Preserve the baseline

Record the URL, commit/revision when available, timestamp, browser, viewport dimensions, zoom/device scale when known, page state, and any setup steps. Capture authorized screenshots and behavior notes before proposing changes.

Do not alter the baseline. Use a branch, duplicate, preview, staging environment, or other isolated checkpoint for implementation work.

**Gate:** The baseline is reproducible enough to compare, or its limitations are recorded and accepted.

## 3. Perform the evidence-first audit

Complete [UI-AUDIT.md](UI-AUDIT.md).

For every scored area:

1. cite an observable element, location, or capture;
2. describe the user-facing consequence as a hypothesis, not a fact beyond the evidence;
3. assign 0–3, N, or O using the defined rubric; and
4. separate verified behavior from inference and untested concerns.

**Gate:** Every material finding has evidence and every unavailable check is marked honestly.

## 4. Report findings and propose changes

Prepare [FINDINGS-REPORT.md](FINDINGS-REPORT.md) and [IMPROVEMENT-PLAN.md](IMPROVEMENT-PLAN.md). Rank findings by observed severity, confidence, effort, and dependency. For Offer B, identify no more than five candidate fixes, each with a precise boundary and acceptance check.

Do not start implementation while the proposed list is still changing.

**Gate:** The client has received the audit and understands which conclusions remain unverified.

## 5. Obtain change approval

For Offer B, complete [CHANGE-APPROVAL.md](CHANGE-APPROVAL.md). The client accepts, rejects, or defers each proposed fix and confirms the final list. Record the approved environment and files/components when known.

Audit-only engagements end after the report and clarification round; no change approval is implied.

**Gate:** Written approval exists for each implementation item. Anything not explicitly approved remains unchanged.

## 6. Implement in isolation

Create a reversible checkpoint and implement only the approved fixes. Keep unrelated code, content, behavior, dependencies, routes, and experiments unchanged.

If implementation reveals a necessary unapproved change:

- stop that item;
- record the discovery and its effect;
- propose a revised boundary; and
- obtain new written approval before continuing.

**Gate:** The working diff maps only to approved items and contains a rollback path.

## 7. Run QA and matching comparison

Complete [QA-CHECKLIST.md](QA-CHECKLIST.md). Capture after-screenshots using the same agreed page state, viewport dimensions, browser/device conditions, zoom, content, and crop/full-page method as the baseline whenever technically possible.

Verify affected behavior and relevant regressions. Never convert “not tested” into “passed.” A visual check does not establish accessibility conformance, performance improvement, or business impact.

**Gate:** Each acceptance check is passed, failed, or explicitly not performed, and mismatched evidence conditions are disclosed.

## 8. Deliver without silently deploying

Complete [DELIVERY-REPORT.md](DELIVERY-REPORT.md) with:

- final approved and implemented list;
- branch, revision, files/components, or artifact location;
- matching before/after evidence;
- test results and limitations;
- known issues and deferred items; and
- rollback/restoration steps.

Handoff is not deployment. Do not merge, publish, or deploy unless the client separately approves the exact target and action in writing.

**Gate:** The client can inspect the result, understand its limitations, and restore the prior state.

## 9. Close the engagement

Record acceptance, requested corrections within the included review round, or unresolved items. Remove or return temporary access as agreed. Do not turn completion into an automatic retainer, broader redesign, or new development cycle.
