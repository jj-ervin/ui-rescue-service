# QA checklist — AI UI Rescue Service

Complete after approved implementation and before delivery or any separately authorized deployment.

## QA context

- Client / project:
- QA date / reviewer:
- Scope version: `v0.1`
- Exact page/state:
- Baseline revision/checkpoint:
- Candidate revision/artifact:
- Approved proposal IDs:
- Browser / OS:
- Viewports / zoom / device scale:
- Evidence folder:

Use `Pass`, `Fail`, `Not tested`, or `Not applicable`. Add evidence for every `Pass`; explain every other result.

## Scope and diff control

- [ ] Candidate work is isolated from the preserved baseline.
- [ ] Every changed file/component maps to an approved proposal.
- [ ] No unapproved page, state, content, feature, dependency, framework, or infrastructure was added.
- [ ] The implementation contains no client credentials or unrelated private data.
- [ ] A working rollback/restoration method exists.

## Approved-change verification

| Proposal | Acceptance check | Result | Evidence | Notes / limitation |
|---|---|---|---|---|
| P-01 |  |  |  |  |

## Matching screenshot record

Before/after captures should use the same page content and state, browser/device conditions, viewport width and height, zoom/device scale, and capture method. If any condition differs, explain why comparison remains useful and what it cannot prove.

| Evidence pair | Before | After | Viewport/state | Conditions match? | Difference / limitation |
|---|---|---|---|---|---|
| S-01 |  |  |  |  |  |

- [ ] Before evidence predates implementation and identifies the baseline.
- [ ] After evidence identifies the candidate revision/artifact.
- [ ] Screenshots are not cropped or selected in a misleading way.
- [ ] Any mismatch in content, viewport, state, or capture method is disclosed.

## Visual and responsive checks

| Check | Result | Evidence / notes |
|---|---|---|
| Primary hierarchy matches the approved treatment |  |  |
| Text remains readable without unintended clipping/overlap |  |  |
| Spacing/alignment is stable at each agreed viewport |  |  |
| Images/icons retain expected aspect and quality |  |  |
| No unintended horizontal overflow |  |  |
| Responsive layout preserves content and controls |  |  |
| Focus/hover/active states affected by the fixes remain visible and coherent |  |  |
| Reduced-motion behavior checked when motion was changed |  |  |

## Functional regression checks

| Behavior from intake/baseline | Expected | Result | Evidence / notes |
|---|---|---|---|
|  |  |  |  |

Check as applicable:

- navigation and in-page anchors;
- buttons and links;
- forms and validation without submitting real/private data;
- keyboard order and visible focus for affected controls;
- theme, role, language, or state relevant to the frozen unit;
- browser console errors introduced by the change; and
- loading/resource failures relevant to changed assets.

## Claims boundary

- Accessibility conformance audit performed: [ ] Yes, evidence:  [ ] No
- Automated accessibility check performed: [ ] Yes, tool/result:  [ ] No
- Screen-reader check performed: [ ] Yes, setup/result:  [ ] No
- Performance measurement performed: [ ] Yes, method/result:  [ ] No
- User/comprehension testing performed: [ ] Yes, method/result:  [ ] No
- Conversion/business-impact evidence collected: [ ] Yes, method/result:  [ ] No

Do not claim any unchecked category as established.

## Defects, corrections, and retest

| ID | Defect / mismatch | Severity | Correction | Retest result | Evidence |
|---|---|---|---|---|---|
| Q-01 |  |  |  |  |  |

## QA disposition

- [ ] Ready for client review in the isolated environment.
- [ ] Not ready; blockers are listed below.
- [ ] Ready for separately authorized deployment.
- [ ] Deployment not authorized / not in scope.

Blockers, known issues, and unperformed checks:

-

Reviewer / date:
