# FarmLink Ghana

FarmLink Ghana is a marketplace prototype for connecting smallholder farmers with buyers and coordinating produce delivery. It demonstrates a transaction from listing produce and placing an order through courier pickup, delivery confirmation, and farmer payout. Buyers can report a problem while payment is held for review.

## Try the demos

The three demos use sample farmers, buyers, crops, orders, and payments. Interactions are simulated; these pages do not process real payments or represent a live marketplace.

| Demo | Preview | What it shows |
| --- | --- | --- |
| Working prototype | [Open demo](https://abkarikari23.github.io/FarmLink-Ghana/farmlink-ghana-demo.html) | Core marketplace and delivery flow, with escrow handled by a licensed payment partner in production. |
| Payment-cost prototype | [Open demo](https://abkarikari23.github.io/FarmLink-Ghana/farmlink-ghana-demo-payments.html) | Adds an illustrative Paystack and Escrow Africa payment-cost model. Fees should be confirmed with the providers. |
| Bank-held escrow prototype | [Open demo](https://abkarikari23.github.io/FarmLink-Ghana/farmlink-ghana-demo-bank-escrow.html) | Explores a proposed Agricultural Development Bank (ADB) escrow arrangement. ADB has not agreed to it; the bank fees are assumptions pending a quote. |

## Product concept

- Farmers list produce such as tomatoes and maize, with sample farm and location details.
- Buyers browse produce and place orders.
- Couriers accept delivery jobs and update order progress from farm pickup to buyer delivery.
- Delivery can be confirmed with a code or QR flow. Disputes can hold funds for review and demonstrate possible refund, split, or payout outcomes.
- The pitch describes a narrow pilot around Techiman in Bono East, with the real region and crops to be confirmed with local aggregators.

The business model, pilot phases, technology options, and success measures are presented within the demos. All operational details and projections are proposals for discussion, not confirmed partnerships or results.

## GitHub Pages

The HTML demos in [`FounderPitch/`](FounderPitch/) are published as individual GitHub Pages at the preview links above. The GitHub Actions workflow deploys them when files in that folder change on `main`, or when run manually.

To enable publishing for this repository, set **Settings → Pages → Build and deployment → Source** to **GitHub Actions**. After the workflow completes, the demos are available at the links above.
