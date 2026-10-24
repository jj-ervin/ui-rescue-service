# UI audit — Evidence and score record

Use for one agreed page/state. Scores summarize observed evidence; they do not certify usability, accessibility, conversion performance, or business impact.

## Audit context

- Client / project:
- Auditor:
- Audit date:
- Scope version: `v0.1`
- Exact page/state:
- Source URL / artifact / revision:
- Browser / OS:
- Viewports / zoom / device scale:
- Evidence folder or links:
- State/setup notes:

## 0–3/N/O rubric

| Mark | Meaning | Evidence requirement |
|---|---|---|
| `0` | Critical breakdown | Observable issue substantially obstructs the intended task or makes the presentation unusable in the reviewed condition. |
| `1` | Material weakness | Clear, repeated, or high-impact issue; substantial correction is warranted. |
| `2` | Functional with friction | The area works, but specific evidence shows inconsistency, ambiguity, or avoidable effort. |
| `3` | Strong in reviewed scope | No material issue was observed in the supplied evidence and conditions; this is not a universal guarantee. |
| `N` | Not observed / insufficient evidence | The area could not be assessed reliably with the supplied access, state, viewports, or materials. |
| `O` | Outside agreed scope | The area does not apply to the frozen service unit or belongs to a different specialist review. |

Do not treat `N` or `O` as zero or include them in averages. If a numeric summary is useful, report `points earned / points possible` only across scored rows, plus the count of `N` and `O` rows. Never use the total as a certification or before/after outcome unless matching evidence exists.

## Audit table

| Area | Score | Observable evidence | Likely user-facing consequence | Confidence / limitation | Evidence ID |
|---|---:|---|---|---|---|
| Visual hierarchy |  |  |  |  |  |
| Content clarity and primary action |  |  |  |  |  |
| Typography and readability |  |  |  |  |  |
| Spacing, alignment, and layout |  |  |  |  |  |
| Color and contrast indicators |  |  |  |  |  |
| Component and interaction consistency |  |  |  |  |  |
| Responsive behavior |  |  |  |  |  |
| Accessibility indicators |  |  |  |  |  |
| Trust, specificity, and generic-design signals |  |  |  |  |  |
| Functional preservation risks |  |  |  |  |  |

## Score summary

- Numeric points earned:
- Numeric points possible:
- `N` count:
- `O` count:
- Summary interpretation:

## Evidence log

Give each artifact a stable ID used by the audit table and findings report.

| Evidence ID | Type | Condition / viewport | Location | What it verifies | What it does not verify |
|---|---|---|---|---|---|
| E-01 | [Screenshot / DOM observation / behavior check] |  |  |  |  |

## Detailed observations

### Observation A-01 — [Short factual label]

- Area:
- Location:
- Evidence ID(s):
- Observed fact:
- Interpretation / hypothesis:
- Affected viewport/state:
- Severity: [Critical / High / Medium / Low]
- Confidence: [High / Medium / Low]
- Suggested direction, not yet approved:
- What remains unverified:

Duplicate the observation section for each material finding.

## Functional baseline

| Behavior | Baseline result | Evidence | Limitation |
|---|---|---|---|
|  | [Pass / Fail / Not tested] |  |  |

## Audit limitations

- Checks not performed:
- Missing viewports/states:
- Access or data limitations:
- Accessibility/performance/security/SEO boundaries:
- Evidence mismatches or unstable conditions:
- Other uncertainty:

## Auditor completion check

- [ ] Every score cites observable evidence or is marked `N`/`O`.
- [ ] Facts are separated from interpretations.
- [ ] No unperformed check is described as passed.
- [ ] No accessibility, conversion, or business outcome is claimed without suitable evidence.
- [ ] The audit covers only the frozen page/state.
