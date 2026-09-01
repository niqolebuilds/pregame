# Pregame Tape

A standing sweep of viral animal and AI memes on social media, cross-referenced against on-chain launch data, hunting for the legit name behind a meme before a coin gets built on it.

## What it tracks

For every candidate: **narrative strength**, and — once it's actually tokenized — **bundling %**, **dev wallet** history, **liquidity/TVL**, **holder count**, and **chart structure**, all read against the current **market conditions** (BTC trend, overall risk appetite, Solana/pump.fun launch volume). A "Reference plays" table and a playbook of go/no-go signals are calibrated against known outcomes (cashcat, ansem, $GOAT, Fartcoin, $PNUT, $MOODENG, and the ones that rugged or died).

Picks that fail diligence after the fact (rug, collapse, or a correction) stay visible on the page marked "Failed diligence" rather than being quietly removed — that transparency is a deliberate feature, not a bug.

## Structure

- `index.html` — the whole site, a single self-contained page (styles inline, no build step)
- `.nojekyll` — serve the repo as-is on GitHub Pages, no Jekyll processing

## Publishing (GitHub Pages)

Serve the repo root: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**. Once enabled, the page is live at `https://<owner>.github.io/pregame/`.

## Refresh cadence

Refreshed automatically every 8 hours by a multi-agent web-search sweep (three parallel research agents plus an on-chain diligence pass), which commits and pushes the updated `index.html` straight to this repo.

## Status

Educational/research tool, not financial advice. Memecoins are extremely high-risk and the large majority go to zero or get rugged — see the disclaimer on the page itself.
