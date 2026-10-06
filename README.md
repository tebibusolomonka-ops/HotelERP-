# Meridian Hospitality OS — frontend prototype

A connected, client-facing React and JavaScript demonstration for a fictional Ethiopian hospitality group. It runs entirely in the browser; operational changes are stored in `localStorage`.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. Use `npm run build` to create a production bundle.

## Demo paths

- **Hotel journey:** Reservations → Sara Bekele → Check in → Room 315 → Room Service / Minibar / Spa / Restaurant charge → Check Out → Housekeeping.
- **Restaurant journey:** Restaurant → Table 4 → Seat guests → Create order → Kitchen → Request bill → mixed payment or room charge → Mark clean.
- **Digital menu:** Digital Menu → Table 8 → Special Tibs → simulated 3D preview → Place order → Kitchen.
- **Purchasing:** Sell Special Tibs to trigger low Beef stock → Purchasing → Approve → Place order → Receive goods → Inventory movement.
- **Events:** Events → Create inquiry and package → Confirm with deposit → Start → Add charge → mixed final payment.
- **End of day:** Cashier → reconcile → Night Audit → close date → Reports.

The top bar switches demo roles and properties. Settings → **Reset demo data** restores the original dataset after a walkthrough.

## Prototype boundaries

Payments, key issuance, 3D food viewing, notifications and external integrations are simulated. This repository contains no backend, payment processor, database, messaging service, AR engine or Odoo installation. A production implementation can connect these UI workflows to Odoo Community and separate hospitality modules through APIs rather than changing Odoo core.
