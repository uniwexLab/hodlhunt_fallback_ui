# HodlHunt — client (single-page)

Single HTML client for HodlHunt. No build step required for deployment.

**Open the app:** [GitHub Pages](https://uniwexlab.github.io/hodlhunt_fallback_ui/index.standalone.html) · [Source](https://github.com/uniwexLab/hodlhunt_fallback_ui/index.standalone.html)

## Security: no backdoors

This page is a single file: **index.standalone.html**. It contains all HTML, CSS, and JavaScript inline. You can:

- Open the file in any text editor and read the full source.
- Paste the file (or its `<script>` contents) into any AI (e.g. ChatGPT, Claude) and ask it to check for backdoors, data exfiltration, or suspicious network calls.
- Use browser DevTools to inspect network requests and confirm only Solana RPC and explorer links are used.

There are no external scripts, no analytics, no hidden trackers. Your private key is used only in the browser to sign transactions and is never sent anywhere except to the Solana network via the RPC you choose.

## How to use

1. Open **index.standalone.html** in a browser (local file or [on GitHub Pages](https://uniwexlab.github.io/hodlhunt_fallback_ui/)).
2. Paste your wallet **private key** (base58 or JSON array) and click **Log in**.
3. Select **RPC** in the header (default: PublicNode).
4. **My fish** — list of your fish; click **Go to fish** to open a card.
5. In the fish card you can **Feed**, **Transfer**, **Sell**, or **Hunt** (enter prey ID, then **Hunt** or **Auto-hunt** with a check interval in seconds).
6. Use **Create fish** to create a new fish (name + SOL deposit).
7. Language: **RU** / **EN** in the header.

All operations require signing in the browser; no keys leave your device except as part of signed Solana transactions sent to the selected RPC.
