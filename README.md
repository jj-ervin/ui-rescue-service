# AI UI Rescue Service

A fixed-scope pilot service for evidence-first review and bounded visual cleanup of one webpage or UI state.

Status: **service documentation v0.1; pilot offer, not market validated**.

This service is separate from the [AI UI Rescue Kit](../../publishing/ui-rescue-prompt-pack/readme.md). The kit is a self-serve prompt product. This directory is an operator-facing service system for client intake, consent, audit evidence, change approval, quality assurance, and delivery.

## Pilot offers

| Offer | Pilot price | Included |
|---|---:|---|
| Website UI Review | **$79** | Desktop and mobile inspection of one agreed public webpage, with up to five prioritized findings and one brief written follow-up |
| Website UI Rescue | **$259** | A focused one-page review plus up to three explicitly approved, bounded visual fixes and one correction or clarification round |

These are **UNVALIDATED pilot prices**. They are working hypotheses for a limited pilot, not evidence of demand, conversion, profitability, or a permanent rate card. See [SERVICE-SCOPE.md](SERVICE-SCOPE.md) for the complete boundaries.

## Operating principles

- Start from observable evidence, not a generic redesign preference.
- Freeze the page, state, viewports, deliverables, and access boundary before work begins.
- Never edit a client system without explicit written approval and adequate access.
- Keep implementation isolated and reversible.
- Apply only the approved changes; new findings return to approval.
- Capture before/after evidence under matching conditions.
- Report what was tested, what was not tested, known limitations, and rollback instructions.
- Do not deploy or publish without separate explicit approval.

## Documents

- [SERVICE-SCOPE.md](SERVICE-SCOPE.md) — packages, inclusions, exclusions, and v0.1 scope freeze
- [PILOT-PLAN.md](PILOT-PLAN.md) — qualification, outreach, effort and conversion tracking, and stop/go criteria
- [RESEARCH-FOUNDATION.md](RESEARCH-FOUNDATION.md) — standards, professional guidance, evidence limits, and citation rules
- [STRATEGIC-HISTORY.md](STRATEGIC-HISTORY.md) — decisions that constrain the current pilot
- [INTAKE.md](INTAKE.md) — concise operational intake and qualification template
- [REVIEW-REPORT.md](REVIEW-REPORT.md) — concise client report for up to five findings
- [APPROVAL.md](APPROVAL.md) — concise authorization record for Offer B
- [DELIVERY-QA.md](DELIVERY-QA.md) — concise delivery, evidence, QA, failure, and handoff record
- [DELIVERY-WORKFLOW.md](DELIVERY-WORKFLOW.md) — evidence and approval gates from intake through handoff
- [CLIENT-INTAKE.md](CLIENT-INTAKE.md) — optional detailed internal intake worksheet
- [UI-AUDIT.md](UI-AUDIT.md) — observation record and 0–3/N/O scoring rubric
- [FINDINGS-REPORT.md](FINDINGS-REPORT.md) — client-facing, evidence-linked findings
- [IMPROVEMENT-PLAN.md](IMPROVEMENT-PLAN.md) — proposed bounded changes and acceptance checks
- [CHANGE-APPROVAL.md](CHANGE-APPROVAL.md) — explicit authorization and scope lock
- [QA-CHECKLIST.md](QA-CHECKLIST.md) — matching capture and regression checklist
- [DELIVERY-REPORT.md](DELIVERY-REPORT.md) — final changes, evidence, limitations, and rollback

Use the four concise operational templates for routine client delivery. The detailed worksheets remain available when the engagement needs more internal control. Copy templates into a client-specific working folder, retain decisions and evidence links, and mark unavailable checks honestly rather than deleting them. The client receives the concise report and relevant approval/delivery records, not the whole internal documentation system.

## Fictional example evidence

The prompt-pack repository contains an actual local test using the **fictional** Cedar & Stone Home Services page. Its [result](../../publishing/ui-rescue-prompt-pack/examples/site-b-cedar-stone/evidence/RESULT.md), [capture manifest](../../publishing/ui-rescue-prompt-pack/examples/site-b-cedar-stone/evidence/CAPTURE-MANIFEST.md), and matching before/after screenshots may be used as internal process evidence only.

It is not a client engagement, testimonial, market-validation result, accessibility certification, or proof that the pilot prices will sell. Do not present it as any of those things.

## Version boundary

Version 0.1 documents one narrow service. It does not start a new product cycle, add software infrastructure, promise deployment, or expand the existing UI Rescue experiments. Any change to price, page count, fix count, deliverables, or deployment responsibility requires an explicit versioned scope decision.
