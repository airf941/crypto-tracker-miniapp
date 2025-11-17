
# Base Pump & On-chain Monitor MiniApp

This MiniApp displays Base chain top gainers, top losers, pump alerts, and attempts to fetch DEX/whale data from Dexscreener when contract addresses are available via CoinGecko.

## How to deploy

1. Create a public GitHub repo named `crypto-tracker-miniapp` under your account `airf941`.
2. Upload the files from this package (index.html, style.css, miniapp.json, icon.png).
3. Enable GitHub Pages on the `main` branch (root folder).
4. Visit: https://airf941.github.io/crypto-tracker-miniapp/

## Notes & Limitations

- CoinGecko must expose contract addresses for tokens for Dexscreener to find on-chain pairs.
- Dexscreener token endpoints vary by chain; the app tries several token address formats.
- Both APIs have rate limits; please use reasonable refresh intervals (>=5s recommended).
