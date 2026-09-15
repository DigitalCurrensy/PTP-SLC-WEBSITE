# Changelog

All notable changes to this repository.

The live website changelog lives on Vercel (`ptp-vercel-site`). This file is only what landed in GitHub.

## 2026-09-15 — Premium docs pass

Replaced the placeholder README that called this repo an unbuilt academy.

Added:

- README.md — visitor front door with live site screenshots and a how-to path
- docs/USAGE.md — fan, VIP, artist, brand walkthrough
- docs/HOW-IT-WORKS.md — what each page does
- docs/DATA.md — tickets, photos, lists
- docs/ARCHITECTURE.md — Vercel, domains, deploy order
- data/events.json — public lineup snapshot
- data/venues.json — GEM / Aura / Sierra
- AGENTS.md — how to edit this repo
- MEMORY.md — decisions that must not regress

Removed from the front door:

- “PTP academy site that is not built”
- Pointers to the-hub-sports-media and sideline-stack
- AGENTIC+SPA language

Not in this commit:

- Live HTML / assets (still on Vercel, not Git-linked)
- Binary screenshot folder (`shots/`) — README hotlinks production assets instead
- In-repo demo mp4 — night-of video stays on Instagram @PTPSLC
