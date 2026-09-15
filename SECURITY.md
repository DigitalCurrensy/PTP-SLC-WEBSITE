# Security

This repository is public documentation for [ptpevents.com](https://www.ptpevents.com).

It is not a payment processor, guest database, or ticket API.

## What belongs here

- Public lineup copy
- Public venue names and published addresses
- Links to the live site, Square checkout pages, Linktree, and social accounts

## What does not belong here

- API keys, tokens, passwords, `.env` files, PEM keys
- Square dashboard credentials or webhook secrets
- Guest emails, phone numbers, or gallery-unlock lists
- Card data
- Artist riders, guarantees, or unpublished deals
- Internal deploy IDs, cloud project IDs, or private repo names

If you find any of the above in this repository or in git history, do not open a public issue with the secret in the body.

## Report a problem

Email **ptpslc@gmail.com** with:

1. What you found
2. Where you found it (file path or URL)
3. Whether you believe it is already live on ptpevents.com

Do not attach guest lists or card data to a GitHub issue.

## Payments

Tickets are sold by Square on Square-hosted checkout pages. A ticket URL in `data/events.json` is a public checkout link, not a credential.

## Photos

Recap photos are published by PTP on the live site. This repo only links those public files. Do not commit unpublished originals or identifiable shots of minors.
