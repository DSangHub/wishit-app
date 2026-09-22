# wishit

Pick 3 from an A–Z list. AI finds it. Buy faster.

Not another marketplace. wishit is an **intent filter**: the shopper already chose three things, then jumps to Amazon, Walmart, Target, or Best Buy to check out on the retailer’s own cart.

**Live prototype:** open [`index.html`](index.html) in a browser, or enable GitHub Pages on this repo (Settings → Pages → Deploy from `main` / root).

## How it works

1. **Pick** — tap exactly 3 items from the A–Z catalog.
2. **Find** — the demo maps each pick to retailer search pages.
3. **Trigger** — one tap opens the store. Checkout stays on the retailer.

That is the pitch to stores: free high-intent traffic, not a competing shelf.

## Partner posture

- **Walmart** is hungrier for e-comm traffic and has an Affiliate / I/O catalog API plus pickup and same-day delivery.
- **Amazon** converts more easily (Prime habit, Login with Amazon, Associates / Creators API).
- Do **not** ask for Amazon/Walmart passwords. No official API writes to a shopper’s personal cart.
- Legal path: affiliate + product APIs + deep links. Optional: Login with Amazon for identity only.

## Repo

| File | What |
|---|---|
| `index.html` | Clickable prototype |
| `README.md` | This file |

Prototype only. Links are retailer searches, not scraped listings and not add-to-cart on the user’s account.

## Owner

[DSangHub](https://github.com/DSangHub)
