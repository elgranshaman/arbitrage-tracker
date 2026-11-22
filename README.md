# BTC price gap: Bitkub vs Kraken Pro

A single-page dashboard that compares the all-in cost of buying BTC on Bitkub (BTC/THB) with Kraken Pro (BTC/GBP), after fees.

**Live page:** https://elgranshaman.github.io/arbitrage-tracker/

- Live best asks from the public Bitkub and Kraken tickers, refreshed every 60 s (adjustable).
- GBP/THB mid-market rate from ExchangeRate-API, with Frankfurter as a fallback and for history.
- A 90-day daily backfill plus live samples stored in your browser (localStorage).
- Fees for each venue (Kraken maker or taker) are set in the page's Settings.

It is one static file, `index.html`, with no build step, server or API keys. Open it locally or use the GitHub Pages link above. The formulas, data sources and limitations are documented in the comment at the top of `index.html`.

Not financial advice; check prices on the exchange before you buy.
