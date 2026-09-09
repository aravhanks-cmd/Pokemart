# PokéMarket

A mobile-style Pokémon trading-card marketplace — browse live card prices, buy,
sell, and bid in real-time auctions. Built as a single self-contained HTML file:
no build step, no dependencies, works offline, and installs as a PWA on your
phone's home screen.

## Run it

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000 on your phone or desktop
```

On a phone, use your browser's **Add to Home Screen** to run it full-screen
like a native app.

## Features

- **Market** — 16 real cards across sets (Base Set, Evolving Skies, 151, …) with
  market price, 24h trend, rarity, and PSA grade. Search and filter by energy type.
- **Top movers** — horizontal strip of the biggest 24h price swings, each with a
  live sparkline.
- **Card detail** — a slide-up sheet with a 30-day price chart, spread (low/high),
  Buy Now, and watchlist.
- **Auctions** — live listings with real countdown timers and bidding. Placing a
  bid can get you outbid by rival collectors; win before the clock runs out.
- **Sell** — list any card you own as a fixed-price "Buy now" or a 24h auction.
- **Portfolio** — net worth, collection value with profit/loss, holdings,
  watchlist, and **owner earnings** (your 3% platform commission on every sale).
- Dark & light themes (follows your device, with a manual toggle).

## Notes

All prices, balances, and trades are **demo data** persisted in your browser's
`localStorage` — buying, selling, and bidding all work locally. Use **Reset demo
data** in the Portfolio tab to start over. Card art uses styled placeholders
rather than official card images.
