# VINCONNECT site changelog

Source of truth for site changes. Live site: https://vinconnect.com.au
Repo: https://github.com/Vinconnect1982/vinconnect-website

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

Entry shape:

```
## YYYY-MM-DD — short title
Status: Shipped | Agreed, not shipped | Reverted
Who: name or agent
Paths: /page
What changed:
- one fact
Do not:
- one thing the next agent must not invent or undo
```

## Do not publish

Work orders, invoices, customer names or addresses, Circl job numbers, licence or insurance numbers, unconfirmed prices, speeds, job counts, or a warranty that has not been written down here.

VINCONNECT is not affiliated with Starlink, SpaceX, Ubiquiti, TP-Link, Mercusys or UGREEN.

---

## 2026-10-07 — Starlink installation page rebuild agreed

Status: Agreed, not shipped
Who: Vince, with the site audit
Paths: /services/starlink-installation

The live page is still the 27 September version. Do not describe this rebuild as published. Last public commit before this note was 27 September 2026.

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
- Meta title: Starlink Installation South-East Melbourne | VINCONNECT
- Meta description: Starlink installation from $300 single-storey, $550 double-storey. Mount, sealed cable entry and router setup. Travel included. Cranbourne, southeast Melbourne, Peninsula and Gippsland.

Standard install includes the sky check, agreed mount, visible clipped cable, one sealed entry with a brush plate, drip loop, router on that wall near power, setup, test and a short walk-through. About 2–3 hours if the site matches the booking. Kit stays sealed until the installer opens it. An adult must be there.

Not included unless written into the booking: kit and plan, concealed cable, extra holes, shed Wi-Fi, cameras, electrical work, tree lopping, roof repairs, and a mount we supply.

Do not add Mbps. Do not invent a mount price. Double-storey is $550 total.

Reuse these diagrams:

- /images/mounts/mount-j-hockey-stick-dark-800.webp
- /images/mounts/mount-tripod-dark-800.webp
- /images/mounts/mount-wall-dark-800.webp

Draw two new diagrams in the same dark grid style. One is the standard install path. One is included versus not included. Do not put caravan diagrams on this page.

Photos: eight to twelve real jobs from /projects, grouped by tile, Colorbond, flat roof or fascia, double-storey, rental, and one commercial roof. Suburb and mount type only.

Six on-page answers, each two lines, a guide link, and the same price button:

1. Tile or Colorbond. Guides: /resources/choosing-a-starlink-mount and /starlink/roof-wall-and-tripod
2. Trees. Guide: /resources/trees-and-starlink
3. Buy the kit first. Guide: /resources/starlink-delivery-installation
4. What is not included. Guides: /customer-help/standard-install-scope and /install-terms-and-conditions
5. Blackout. Guide: /resources/starlink-power-outage
6. Rental, new build, or house and shed. Guides: /vinready, /resources/house-or-shed, /resources/external-or-concealed-cabling, /resources/fixed-wireless-vs-starlink

Rename Latest pings to Recent notes, or drop it once the FAQ is on the page.

---

## 2026-09-27 — Plain copy, and four image experiments reverted

Status: Shipped
Who: Vince DeStefano
Paths: camera, Starlink and suburb pages

Camera, Starlink and suburb pages now say what the work is. They do not tell the reader which page to use, and they do not call the page a conversation.

Reverted the same day. Do not treat these as live:

- Show the real kit on the marketing images.
- Show the Starlink panel on real roof mounts.
- Use the real Starlink Standard dish at the right size.
- Ground the blue connection line on the equipment it joins.

Finished job photos were not replaced by marketing scenes.

---

## 2026-09-26 — One pricing engine

Status: Shipped
Who: Vince DeStefano
Paths: estimator, stored quote, admin, PDF, email

Price the installed work, not an equipment figure. The kit is not the quote.

- Single-storey package $300. Travel included.
- Double-storey supplement $250. Public total $550. Do not list both.
- Cabinet placement is the same $150 as moving the router.
- Internal walls stay a starting allowance.
- An existing dish is a service visit and still needs a quote.

---

## 2026-09-24 — VINREADY published

Status: Shipped
Who: Vince DeStefano
Paths: /vinready

Builder product for Starlink-ready new homes.

- Builder cost and margin stay in the gated PDF. Not on the public page.
- The pack is shown only after the form.
- Pages follow the builder pack: same photos, same section order, light layout.
- Dish sits on a fascia pole above the gutter, clear of the roof. Not mid-roof.
- Pack uses Australian job photos and a rectangular dish.
- Latest project photos and Event Link images went out with this publish.

---

## 2026-09-23 — Estimator mounts and branded PDF

Status: Shipped
Who: Vince DeStefano
Paths: /estimate

- Mount choices are in the estimator.
- A branded estimate PDF is sent.
- If server mail is blocked, enquiry email can send from the browser.

---

## 2026-09-22 — Site launch and foundation

Status: Shipped
Who: Vince DeStefano
Paths: public site

Repo history starts with "Initial VINCONNECT website source". There is no older commit.

- Phone 0408 559 555. Email vince@vinconnect.com.au. Based in Cranbourne.
- Coverage: southeast Melbourne, Western Port, Mornington Peninsula, Phillip Island, Bass Coast and Gippsland.
- Direct installs are first. Circl is not the front door.
- Referral offer published. One month free for an eligible new customer. Install price is separate from the kit. https://starlink.com/?referral=RC-DF-12576466-54681-7&app_source=share
- Menu slimmed. Event Link and VIN Gear have their own nav items.
- Homepage coverage box replaced with a Victoria network map. Service-area hub uses it. Path: /service-areas
- Estimator aligned to published install prices. Travel is calculated on the server.
- Privacy wording corrected. Path: /privacy
- Project heroes rebuilt from real installations. Invented heroes removed. Path: /projects
- Nyora uses the real roof-mount photo. Somerville tripod filename corrected.
- First guides published: trees, new homes, acreage, cabling, dish placement.
- Transparent logo restored. Google, Facebook and Instagram links added.
- Facebook: https://www.facebook.com/people/Vinconnect-Starlink-Solutions/61589183530269/
- Copy speaks plainly. A box is not a button. Do not say an enquiry was emailed if it was not.

---

## Internal only

Do not describe these to a customer.

- Dark control room on /admin. Dashboard is not cached.
- Quote status, photos and follow-up are stored on the live site.
- Command Centre plan is in docs/COMMAND_CENTRE.md. The plan commit did not by itself change the public site.
