# PTP SLC Events

**We produce the nights people remember.**

Pound The Pavement Productions is Salt Lake City’s live-events, talent, and media company. You open the site, pick a show at GEM Nightclub or Sierra Event Center, buy a ticket, and — the next morning — download the photos.

No account. No app store. No jargon.

<p align="center">
  <img src="https://www.ptpevents.com/assets/logo.png" alt="PTP — Pound The Pavement Productions cracked-chrome wordmark" width="280">
</p>

<p align="center">
  <a href="https://www.ptpevents.com"><strong>Open the live site</strong></a>
  &nbsp;·&nbsp;
  <a href="https://linktr.ee/ptpslc"><strong>Get tickets</strong></a>
  &nbsp;·&nbsp;
  <a href="https://instagram.com/PTPSLC"><strong>Watch a night</strong></a>
  &nbsp;·&nbsp;
  <a href="docs/USAGE.md"><strong>How to use it</strong></a>
</p>

| Live site | Tickets | VIP / tables | Newsletter | Photos |
|---|---|---|---|---|
| [ptpevents.com](https://www.ptpevents.com) | Square + [Linktree](https://linktr.ee/ptpslc) | Text **(385) 602-7898** | [Weekend Access](https://ptpslc.substack.com) | Morning-after recap on the site |

---

## Why it exists

Most SLC nightlife pages are a flyer, a dead link, and a DM.

PTP runs the whole night: booking the artist, producing the room, selling the ticket, filming the night, and publishing the recap. The website is the public front door for that operation.

**In one sentence:** open [ptpevents.com](https://www.ptpevents.com), pick a date, check out, show up with ID.

---

## See the platform

These are live assets from the production site — not mockups.

### The front door

<p align="center">
  <img src="https://www.ptpevents.com/assets/crowd.jpg" alt="A full crowd under the PTP screen at GEM E.C. in Salt Lake City" width="920">
</p>

Home page line: *Live events, media & talent in Salt Lake City.* Next show is pinned under the logo. **Get Tickets** always goes to the current lineup.

### This is a PTP night

<p align="center">
  <img src="https://www.ptpevents.com/assets/clip.gif" alt="Live at a PTP event at GEM E.C. in Salt Lake City" width="520">
</p>

### Upcoming shows

| Fri Sep 18 | Sat Sep 19 | Fri Sep 25 | Fri Oct 23 |
|---|---|---|---|
| <img src="https://www.ptpevents.com/assets/flyers/cutdwn.jpg" alt="CUTDWN Live in SLC September 18" width="220"> | <img src="https://www.ptpevents.com/assets/flyers/jenny-69.jpg" alt="Jenny 69 Buchona Tour September 19" width="220"> | <img src="https://www.ptpevents.com/assets/flyers/dariel-amant.jpg" alt="Dariel Amant El Amante September 25" width="220"> | <img src="https://www.ptpevents.com/assets/flyers/oblivion.jpg" alt="OBLIVION Live in SLC October 23" width="220"> |
| CUTDWN · GEM E.C. · 18+ | Jenny 69 · GEM E.C. · 18+ | Dariel Amant · Aura Lounge · 21+ | OBLIVION · GEM E.C. · 18+ |

Drag the row on the site, or open **[Events](https://www.ptpevents.com/#events)**.

### Photos from the last night

<p align="center">
  <img src="https://www.ptpevents.com/assets/photos/oc-chris/01.jpg" alt="OC Chris live in SLC recap photo 1" width="280">
  <img src="https://www.ptpevents.com/assets/photos/oc-chris/03.jpg" alt="OC Chris live in SLC recap photo 3" width="280">
  <img src="https://www.ptpevents.com/assets/photos/oc-chris/04.jpg" alt="OC Chris live in SLC recap photo 4" width="280">
</p>

Unlock once with an email + number, then download full-resolution shots. Current featured recap: **OC Chris · Live in SLC**.

### How-to video

There is no separate “tutorial channel.” The official how-to is the night itself:

1. **[Watch PTP SLC on Instagram](https://instagram.com/PTPSLC)** — door-to-stage, same rooms the site sells.
2. **[Watch PTP SLC on X](https://x.com/PTPSLC)** — short promo clips for the next date.
3. **[Read the 5-step walkthrough](docs/USAGE.md)** — fan, VIP, artist, and brand paths in plain English.

---

## How to use it

Takes about a minute.

### 1. Open the site

Go to **[www.ptpevents.com](https://www.ptpevents.com)**.

Use **Home · Events · Photos · Weekend Access · Book**.  
`ptpslcevents.com` is not live. Always use `ptpevents.com`.

### 2. Pick a night

Tap a flyer or **See upcoming events**. Every card shows date, age rule, and room.

- Most GEM nights are **18+ with a 21+ bar**.
- Aura Lounge nights are **21+ only**.
- Bring ID. The site says so in the footer for a reason.

### 3. Buy the ticket

**Get Tickets** opens Square checkout, or [Linktree](https://linktr.ee/ptpslc) when a Square link is not up yet.

Tickets are **final sale**. If PTP cancels and does not reschedule, Square refunds the original card.

### 4. Sit, book, or partner

| You are | Do this |
|---|---|
| Fan | Buy GA. Show up. |
| VIP | Text **(385) 602-7898** or use **Book → Reserve a table**. |
| Artist / manager | **Book → Book talent** or email **ptpslc@gmail.com**. |
| Brand | **Book → Partner with us** — activations and pouring rights. |

### 5. Come back the next morning

Open **Photos**. Unlock the gallery. Subscribe to **[Weekend Access](https://ptpslc.substack.com)** if you want lineup + presale mail before it goes public.

Full walkthrough, screen by screen: **[docs/USAGE.md](docs/USAGE.md)**.

---

## What this repository is

This repo is the **operator record** for the PTP SLC website — what the product is, how a guest uses it, where tickets and photos live, and how Digital Currensy Inc. should change it without breaking the live night.

| Surface | URL | Role |
|---|---|---|
| Production site | [www.ptpevents.com](https://www.ptpevents.com) | Live public site |
| Apex domain | [ptpevents.com](https://ptpevents.com) | Same site |
| Ticket board | [linktr.ee/ptpslc](https://linktr.ee/ptpslc) | Weekly lineup dump |
| This GitHub repo | `DigitalCurrensy/PTP-SLC-WEBSITE` | Docs + citation data |
| Vercel project | `ptp-vercel-site` | Deploy target for the live HTML |

The live HTML is deployed from Vercel project **`ptp-vercel-site`**. It is **not** Git-linked to this repository today. Do not treat a push here as a site deploy.

### What this is not

- Not a basketball academy
- Not Sideline Stack, Hub Sports Media, or an “AGENTIC+SPA” wrapper
- Not a scrape, a payments rail, or a copy of another DCI product
- Not a guest database — emails and card numbers do not belong in git

---

## Tickets, photos, and lists

You do not log in.

1. Pick a show on the site.
2. Checkout is Square (merchant `MLN44S3JSC529`) or Linktree.
3. After the night, photos unlock on the site.
4. Weekend Access on Substack is the weekly lineup + presale list.

Citation copies of the public lineup live in [`data/events.json`](data/events.json) and [`data/venues.json`](data/venues.json). If those files disagree with the live site, **the live site wins**.

Deep dive: **[docs/DATA.md](docs/DATA.md)**.

---

## Rooms

| Room | Address as published | Typical night |
|---|---|---|
| GEM Event Center / GEM Nightclub | 122 W Pierpont Ave, Salt Lake City, UT 84101 | 18+ shows, 21+ bar |
| Aura Lounge | Same Pierpont block | 21+ only |
| Sierra Event Center | Salt Lake City | 2,000-capacity takeovers |

Some older Square pages print **134 W Pierpont Ave**. Same block. Confirm on the flyer before you go.

---

## Run the docs locally

This repository is documentation. There is no website runtime in the tree yet.

```bash
git clone https://github.com/DigitalCurrensy/PTP-SLC-WEBSITE.git
cd PTP-SLC-WEBSITE
```

When the live HTML is copied into this repo, serve it from the site root so `/config.js` and `/assets/` resolve:

```bash
python3 -m http.server 4173
# open http://127.0.0.1:4173
```

Do not open `index.html` as a `file://` URL. Asset paths will break.

How the live site is wired: **[docs/HOW-IT-WORKS.md](docs/HOW-IT-WORKS.md)** · **[docs/ARCHITECTURE.md](docs/ARCHITECTURE.md)**.

---

## Project map

```
README.md                 You are here — one-minute front door
docs/USAGE.md             Fan, VIP, artist, brand walkthrough
docs/HOW-IT-WORKS.md      What each page does
docs/DATA.md              Tickets, photos, lists — where they live
docs/ARCHITECTURE.md      Vercel, domains, what must not ship
data/events.json          Public lineup snapshot
data/venues.json          Rooms PTP actually uses
CHANGELOG.md              What changed in this repo
AGENTS.md                 How to edit this repo
MEMORY.md                 Decisions that must not regress
```

---

## Status

**Shipped on the live site:** home, events, photos, Weekend Access, book/partner, Square tickets, Instagram/TikTok/X/Kick links.

**True about this GitHub repo as of 2026-09-15:** documentation and citation data only. Source HTML still lives on Vercel, not on `main`.

**Open:**

- Point `ptpslcevents.com` at the same site or retire the domain
- Link this GitHub repo to Vercel project `ptp-vercel-site` *after* the HTML is committed — not before
- Production favicon is 404
- Talent/partner form endpoint is empty, so those forms do not persist until it is set

History: **[CHANGELOG.md](CHANGELOG.md)**.

---

## Contact

| Need | Where |
|---|---|
| Tickets | [ptpevents.com](https://www.ptpevents.com) · [linktr.ee/ptpslc](https://linktr.ee/ptpslc) |
| Tables / VIP | Text **(385) 602-7898** |
| Talent, brands, everything else | **ptpslc@gmail.com** |
| Night-of video | [instagram.com/PTPSLC](https://instagram.com/PTPSLC) |

© 2026 Pound The Pavement Productions · Salt Lake City, UT  
Site operated with Digital Currensy Inc.  
18+ / 21+ beverage zones · ID required
