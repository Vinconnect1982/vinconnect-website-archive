# VINCONNECT site changelog

Source of truth for site changes. Live site: https://vinconnect.com.au
Main repo: https://github.com/Vinconnect1982/vinconnect-website
The old repo vinconnect-website-source is being moved into it. Never use -source as the base.

Every person and every AI agent working on this site must use this file.

## Before you change anything

1. Read this file from the top.
2. Check the latest entry. If someone else has shipped or agreed a change you were about to make, do not overwrite it.
3. If the live page and this file disagree, this file says which one is newer. Do not guess.

## After you change anything

1. Add a new entry at the top of the log, under the rule and above older entries.
2. Say whether it is shipped or only agreed.
3. Name the page or path, the date, and who made it.
4. Do not delete or rewrite older entries.
5. Commit the file in the same change as the work. A site change with no log entry is not finished.

## Standing rules

- Sharp corners only. No rounded or pill buttons.
- Never put "Illustrative" or a similar label on an image. Existing mount diagrams may still carry that footer until they are redrawn. Do not add it to new work.
- Never invent prices, speeds, warranties, insurance, job counts, street addresses, or Google ratings.
- Never describe /admin, quote status, or Command Centre to a customer.

---

## 2026-10-07 — Agent rules: main repo, sharp corners, no Illustrative label

Status: Agreed, not shipped as a page change
Who: Vince
Paths: AGENTS.md, docs/SITE-CHANGELOG.md

Work only in Vinconnect1982/vinconnect-website. Do not use vinconnect-website-source as the base.
New pages and buttons use sharp corners. Do not add rounded or pill buttons.
Do not label images Illustrative.

---

## 2026-10-07 — Starlink installation page rebuild agreed

Status: Agreed, not shipped
Who: Vince, with the site audit
Paths: /services/starlink-installation

The live page is still the 27 September version. Do not describe this rebuild as published.

What is wrong with the live page:

- It is a pricing note, not a decision page.
- The only scene is the generated sunset render at /scenes/starlink-home.webp. Remove it from this page.
- No real install photos, no trust line, and install day is not described.
- Extras are buried in a paragraph. Double-storey is explained twice. Say $550 once.
- No on-page FAQ. Objections sit under Helpful guides and a block called Latest pings. Ping is internal language.
- Check My Install Price repeats about six times. The form does not ask storeys, roof type, or whether the kit has arrived.
- Footer text lists UniFi, Starlink, Mercusys and UGREEN. Scrolling logos are TP-Link, Omada, Hikvision and HiLook.
- Property planner sits in the middle of a simple roof install. Move it down.

Keep:

- $300 single-storey, $550 double-storey. Travel for the address is included in the price shown before booking.
- VINCONNECT charges for the install, not the kit. Dish, router and plan stay in the customer's name.
- Tile: under-tile J-mount, no tiles drilled. Colorbond: tripod tied to existing roof screws, no new holes. Fascia checked before use.
- Sealed entry and brush plate. Primary action remains Check My Install Price at /estimate.

Agreed page order:

1. Hero. Price, area, travel included, kit stays in their name. One real install photo.
2. Which roof is yours. Reuse the three mount diagrams. Do not redraw them.
3. Matching real photos. Two per mount type.
4. New diagram: standard install path.
5. Price table, then the estimator button.
6. Still deciding. Six short answers on the page.
7. More than one building. Property planner sits here.
8. Form only for an odd roof, a factory, a relocate, or someone who will not use the estimator.

Hero copy:

- Eyebrow: Starlink installation
- H1: Starlink installed properly. From $300.
- Sub: We mount the dish, seal the cable entry and set up the router where you use it. Based in Cranbourne. Southeast Melbourne, the Peninsula, Phillip Island, Bass Coast and Gippsland. Any travel for your address is included in the price you see before you book.
- Trust line: Independent installer. Not a Starlink or SpaceX contractor. Kit, account and monthly plan stay in your name. Price shown before you book.
- Buttons: Check My Install Price, then 0408 559 555. Cut extra price buttons to hero, after the price table, and footer.

Do not add Mbps. Do not invent a mount price. Double-storey is $550 total.
Reuse /images/mounts/mount-j-hockey-stick-dark-800.webp, mount-tripod-dark-800.webp and mount-wall-dark-800.webp. Draw two new diagrams in the same dark grid style, without an Illustrative label. Do not put caravan diagrams on this page.
Photos: eight to twelve real jobs from /projects. Suburb and mount type only.

Six on-page answers, each two lines, a guide link, and the same price button:

1. Tile or Colorbond. Guides: /resources/choosing-a-starlink-mount and /starlink/roof-wall-and-tripod
2. Trees. Guide: /resources/trees-and-starlink
3. Buy the kit first. Guide: /resources/starlink-delivery-installation
4. What is not included. Guides: /customer-help/standard-install-scope and /install-terms-and-conditions
5. Blackout. Guide: /resources/starlink-power-outage
6. Rental, new build, or house and shed. Guides: /vinready, /resources/house-or-shed, /resources/external-or-concealed-cabling, /resources/fixed-wireless-vs-starlink

Rename Latest pings to Recent notes, or drop it once the FAQ is on the page.

Older shipped entries from 22–27 September 2026 remain in force: plain copy, one pricing engine, VINREADY, estimator mount choices, real project photos, Victoria coverage map, and the referral offer. Four marketing-image experiments on 27 September were reverted. Do not treat those as live.
