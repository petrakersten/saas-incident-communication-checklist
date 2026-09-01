# SaaS Incident Communication Checklist

A compact, vendor-neutral checklist for reviewing customer-facing outage updates before a rehearsal or publication.

This repository is a free proof asset. It does not send messages, collect incident data, or replace legal, security, breach-notification, compliance, or root-cause review.

## Four-stage update sequence

1. Investigating
   - Name the affected service or customer group.
   - State the observed impact, not a guessed cause.
   - Separate what is known from what is still unknown.
   - Give a specific next-update time.
2. Identified
   - State the contributing issue only when evidence supports it.
   - Describe the action underway without promising an unproved recovery time.
   - Repeat current customer impact and the next-update time.
3. Monitoring
   - State what changed and what evidence is being watched.
   - Avoid saying "resolved" while recovery is still being verified.
   - Tell customers whether they need to act.
4. Resolved
   - Give the restoration time and final observed impact.
   - State any remaining customer action or follow-up.
   - Link to a post-incident review only when one will actually be published.

## Six-question quality check

Score each item 0 (missing), 1 (partial), or 2 (clear).

- Scope: Is the affected service or audience explicit?
- Impact: Can a customer understand what they cannot do?
- Evidence: Are facts separated from assumptions and unknowns?
- Action: Does the update say what the team is doing now?
- Timing: Is there a specific next-update time or final restoration time?
- Tone: Is the language factual, plain and empathetic without unsupported certainty?

A low score is a prompt to gather facts, not permission to invent them.

## Fictional worked example

Weak: "We are aware of an issue and should have it fixed shortly."

Stronger investigating update: "Some customers cannot export invoices from the web app. Existing invoices remain available. We are investigating the export queue and have not yet confirmed the cause. We will post another update by 14:30 UTC."

Why it is stronger: affected action, current impact, unknown cause and next-update time are explicit. It does not promise an unproved restoration time.

## Free authoritative alternatives

- [Atlassian incident communication templates](https://www.atlassian.com/incident-management/incident-communication/templates)
- [Atlassian Statuspage free plan](https://www.atlassian.com/software/statuspage)
- [PagerDuty postmortem template](https://response.pagerduty.com/after/post_mortem_template/)
- [Google SRE postmortem practices](https://sre.google/workbook/postmortem-culture/)

## Need a complete rehearsal?

The [SaaS Incident Communications Drill & Evidence Kit](https://saas-outage-update-rubric.pcp-slice0-20260720.workers.dev/go/github) is a US$29 editable 60-minute exercise with timed injects, four update stages, scoring and a dated evidence receipt. It is an optional paid download; this checklist remains usable without it.

## Licence

Creative Commons Attribution 4.0 International for this repository's original checklist text and fictional example. External sources retain their own terms.
