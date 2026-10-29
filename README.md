# SME AIcoAssist — standalone test version

## What this is
A single-file web app a shop can open on its own phone. It covers the day-one
features from the Muse prototype:
shop setup, menu and prices, customer reply drafts in English / Mandarin /
Malay / Bahasa Indonesia (check and copy into WhatsApp yourself — nothing is
sent automatically), a social post drafter, a daily sales log with
best-sellers and a 7-day chart, reminders, and a customer menu view.
No payments, delivery booking, or full accounting in this version.

## Important limits — please read before sharing with shops
- **Data stays on the shop's own phone.** This test version saves data in the
  phone's browser (local storage). It does not sync to another phone, and
  Kent cannot see a shop's data from here. If a shop clears browser data or
  switches phones, its saved data will not follow unless a server version is
  built later.
- **This is a test version, not production-grade login security.** Passwords
  are hashed in the browser for this test only. Do not use it to store
  sensitive customer data, and do not charge shops until a proper server,
  privacy policy, terms, and data-protection setup are in place.
- **Reply drafts are templates using the shop's own saved facts.** Always
  check price, hours and delivery notes before sending.

## How to get a public link
This file alone is not yet a public link. To publish it, upload this folder
to a static host, for example:
- Netlify Drop — drag the folder in, get a link
- GitHub Pages / Vercel — upload the folder as a static site
- Your own hosting for singavibe.com, if you control it — upload
  index.html to a new page or subdomain

Once hosted, send shops that link. Each shop creates its own account on its
own phone and starts empty — no demo shop or fake sales are included.

## Next step if the test works
If shops keep using it after 2 weeks, the next build should be a server
version: real accounts that sync across phones, a way for Kent to support
shops, a privacy policy and terms, and only then pricing and payment.
