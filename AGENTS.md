# AGENTS.md — how to change PTP SLC Events

Operating file for humans and coding agents. Read before editing.
Paired with MEMORY.md.

## Product identity

Pound The Pavement Productions (PTP) produces live events, books talent, and publishes night-after media in Salt Lake City.

- Live site: https://www.ptpevents.com
- Tickets: https://linktr.ee/ptpslc
- This GitHub repo is the public record + operator docs. It is not currently the Vercel deploy source.

## Repo rules

1. Do not invent a website runtime, CMS, academy, or payments rail in this repo.
2. Do not point readers at Hub Sports Media, Sideline Stack, or AGENTIC+SPA. Wrong product.
3. Do not list `ptpslcevents.com` as live. It does not resolve. Canonical host is `ptpevents.com`.
4. Do not claim this GitHub repo deploys the site until it is linked to Vercel project `ptp-vercel-site`.
5. Operator content lives in live `config.js` (`window.PTP.events`, `window.PTP.galleries`, `window.PTP.leadEndpoint`). First event = Next event.
6. Tickets stay on Square merchant `MLN44S3JSC529` or Linktree. Do not store card data.
7. `leadEndpoint` is empty on production. Do not document forms as “saved to a Sheet” until a Google Apps Script URL is set.
8. Gallery unlock emails and phone numbers stay out of git. No PII fixtures.
9. Photo files on the live host are `assets/photos/{slug}/01.jpg` (zero-padded). Do not document `1.jpg`.
10. README is the one-minute front door. Patch IDs belong only in CHANGELOG.md.
11. Never link a file in README until that file is on `main`, or land the link and the file in the same commit.
12. One writer per path per session. Confirm with `get_file_contents` before retrying a blocked push.
13. GitHub About / description / topics are Settings-only. Give the user paste-ready copy.
14. Favicon is 404 on production. Note it; do not invent a brand mark.
15. Default to docs-only unless the user asked to import the Vercel site source into this repo.

## File ownership

| Path | Owns |
|---|---|
| README.md | Visitor front door |
| docs/USAGE.md | How-to walkthrough |
| docs/HOW-IT-WORKS.md | Product logic in plain language |
| docs/ARCHITECTURE.md | Deploy, cache, integrations |
| docs/DATA.md | Events / venues / gallery contract |
| data/events.json | Snapshot of live lineup (not the runtime) |
| data/venues.json | GEM / Aura / Sierra |
| CHANGELOG.md | History |
| AGENTS.md | This contract |
| MEMORY.md | Decisions that must not regress |

## Out of scope unless the user asks

Importing the Vercel folder into git · wiring `leadEndpoint` · DNS for `ptpslcevents.com` · building a first-party ticket API · youth-academy features.
