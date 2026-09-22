# wishit

Pick 3 from an A–Z list. AI finds it. Buy faster.

Not another marketplace. wishit is an **intent filter**: the shopper already chose three things, then jumps to Amazon, Walmart, Target, or Best Buy to check out on the retailer’s own cart.

**Live prototype:** open [`index.html`](index.html) in a browser, or enable GitHub Pages on this repo (Settings → Pages → Deploy from `main` / root).

## How it works

1. **Connect** — optional CTAs: *Connect your Amazon account* and *Connect your Walmart account?*
2. **Pick** — tap exactly 3 items from the A–Z catalog.
3. **Find** — maps each pick to retailer search pages. Connected stores get the highlighted **Buy faster** button.
4. **Trigger** — checkout stays on the retailer.

### What connect means

| Store | Real integration | wishit gets | wishit never gets |
|---|---|---|---|
| Amazon | Login with Amazon | Name, email, zip | Cart, orders, cards, password |
| Walmart | Affiliate + zip / store preference | Faster routing, pickup/local stock | Cart write, payment, password |

That is the pitch to stores: free high-intent traffic, not a competing shelf.

## Partner posture

- **Walmart** is hungrier for e-comm traffic and has an Affiliate / I/O catalog API plus pickup and same-day delivery.
- **Amazon** converts more easily (Prime habit, Login with Amazon, Associates / Creators API).
- Do **not** ask for Amazon/Walmart passwords. No official API writes to a shopper’s personal cart.

## Repo

| File | What |
|---|---|
| `index.html` | Clickable prototype |
| `README.md` | This file |

Prototype only. Connect state is saved in the browser (`localStorage`). Links are retailer searches, not scraped listings.

## Owner

[DSangHub](https://github.com/DSangHub)
