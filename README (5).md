# OpenText Cybersecurity — Legacy Page Content Briefs

Content specs for the `/legacy/*` pages on cybersecurity.opentext.com, built from:
- 12-month GSC export (queries, pages, CTR, position)
- GA4 90-day traffic comparison (users, sessions, bounce/engagement rate)
- The existing internal content audit and page-level recommendations

Each brief assumes the dominant query intent for that brand based on the actual
GSC "Top queries" data (not guessed) — see each file's "Query intent" section
for the specific keyword volumes behind that assumption.

## Template assignment

Two templates, assigned by whether the acquired brand still has a live,
independently-marketed site for part of its audience:

| Brand | Template | Why |
|---|---|---|
| AppRiver | A — Absorbed | No separate site remains (appriver.com retired) |
| Zix | A — Absorbed | No separate site remains |
| CloudAlly | A — Absorbed | Single audience (SMB/MSP); already OpenText's best-performing legacy page — brief focuses on hierarchy, not a rewrite |
| Erado | A — Absorbed | B2B-only product, no consumer split |
| Pillr | A — Absorbed | B2B-only product, no consumer split |
| Webroot | B — Dual-brand split | webroot.com remains live for consumer antivirus |
| Carbonite | B — Dual-brand split | carbonite.com referenced as the consumer path in the existing FAQ |

**Assumption to verify before build:** Carbonite's dual-brand status is inferred
from the current page's FAQ (which links to carbonite.com for consumer
customers) rather than independently confirmed live. Check that carbonite.com
is still active and consumer-facing before finalizing Carbonite's brief.

## Template A — Absorbed Brand

For brands with no separate live marketing site. The page's whole job is:
confirm the visitor is in the right place, route them by task (login /
support / status / explore current product) as fast as possible, and keep
the acquisition backstory to one line instead of a full narrative.

Order: eyebrow context strip → hero (one sentence) → routing cards (4) →
one-line quick history → related resources (3) → footer.

## Template B — Dual-Brand Split

For brands where part of the audience still belongs on the brand's own site.
The page's first job, before anything else loads, is disambiguating which
audience the visitor is: consumer (leaves the site) vs. business/MSP (stays
and gets Template A's routing pattern below the fork).

Order: audience fork (2 panels, equal visual weight) → business-path hero →
routing cards (4) → one-line quick history → related resources (3) → footer.

## Files in this set

- `appriver.md`
- `zix.md`
- `cloudally.md`
- `erado.md`
- `pillr.md`
- `webroot.md`
- `carbonite.md`
