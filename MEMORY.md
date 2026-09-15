# MEMORY.md — decisions that must not regress

Last earned loop: 2026-09-15 premium docs pass.

## Locked decisions

- **Product is Pound The Pavement Productions**, not a PTP academy and not a sports-media pointer.
- **Canonical site is https://www.ptpevents.com.** Vercel project `ptp-vercel-site`. GitHub `PTP-SLC-WEBSITE` is not the deploy source today.
- **`ptpslcevents.com` is dead DNS.** Do not advertise it.
- **No first-party database.** Square + Linktree + Substack + Gmail/SMS + static assets.
- **`config.js` is the only operator file on the live site.** `leadEndpoint` is `""`.
- **Tickets are final sale** on Square unless the event is cancelled with no new date.
- **VIP is SMS, not checkout.** (385) 602-7898.
- **Age policy is per event.** Most GEM nights 18+ with 21+ bar. Aura Lounge nights are 21+ only.
- **Venue address on live flyers:** 122 W Pierpont Ave, SLC 84101. Some Square pages say 134 W Pierpont. Document both; do not silently pick one.
- **No how-to YouTube owned by PTP.** Night-of video lives on Instagram @ptpslc. Do not embed unrelated “Pound the Pavement” videos.

## Earned loops — 2026-09-15

- The live site was already a product. The defect was a jargon README that called this repo a missing academy.
- Multi-agent pushes on the same new path 409. One writer.
- MCP cannot set GitHub description / topics.
- Live flyer / photo URLs can be hotlinked from ptpevents.com until `shots/` exists in git.
- Do not Git-link this repo to Vercel until the HTML is on `main`. An empty docs repo would wipe production.
