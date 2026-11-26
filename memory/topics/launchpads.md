---
title: Launchpad revenue tracker (Base, Robinhood Chain, Ethereum)
description: Rolling daily revenue for token launchpads across Base, Robinhood Chain and Ethereum from DefiLlama, with trend notes. Used by revenue-alert to detect breakouts and decay.
tags: [launchpad, base, robinhood-chain, ethereum, revenue, defillama]
resource: https://defillama.com/fees
timestamp: 2026-11-26T14:40:00Z
---

# Launchpad Revenue Tracker

Daily protocol revenue (USD, DefiLlama `dataType=dailyRevenue`) for every protocol categorised
`Launchpad` / `NFT Launchpad` on the three monitored chains. Snapshot below is **2026-11-26 ~14:40 UTC**
(24h vs prior 24h). Update on each `revenue-alert` run — newest snapshot wins, older snapshots stay in git history for trend.

## Robinhood Chain (every launchpad here is new)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Pons V2 | $19,708 | $15,310 | +29% | $15,377 | $766,676 | **Decisively back above the ~$8k trigger — strongest print since early Nov.** Path: $43.7k (Nov 6) → $8.7k (Nov 22) → $11.9k (Nov 23) → **$19.7k (Nov 26)**. ~89% of tracked RH launchpad revenue |
| Binance Alpha | $1,556 | $1,017 | +53% | $1,191 | $28,494 | Bounced to 1.31× avg |
| Pons V1 | $493 | $623 | −21% | $725 | $48,696 | Legacy line, drifting down |
| o1 Launchpad (RH) | $84 | $24 | +258% | $39 | $3,195 | Micro bounce off a near-zero base |
| Flap sh | $49 | $236 | −79% | $123 | $9,771 | Micro, fading |
| Frontier | $43 | $130 | −67% | $83 | $47,123 | Bottomed, small |
| GlazeCorp Launchpad | $40 | $42 | −5% | $53 | $2,886 | Listed Nov 5, never got traction |
| Agen.space | $34 | $44 | −23% | $49 | $568 | New-ish micro |
| QHooks | $25 | $32 | −22% | $29 | $931 | Micro |
| Coinbarrel | $15 | $16 | −11% | $24 | $979 | Faded after Nov 4 listing |
| token.select | $9 | $11 | −24% | $13 | $922 | Micro |
| EasyA Kickstart | $8 | $5 | +85% | $4 | $115 | New-ish micro |
| Sentry | $5 | $7 | −22% | $10 | $969 | Micro |
| LetsCash | $5 | $1 | +402% | $4 | $666 | Micro |
| clanker (RH) | $3 | $9 | −64% | $23 | $1,433 | Micro |
| Sushi Launchpad | $3 | $0 | — | $2 | $202 | New listing, ~$0 |
| Pez Family / bow.fun / AGNT / Sapling / Bags | ≤$2 | — | — | ≤$2 | <$3.2k | Micro / collapsed |
| New listings Polydash · Gmoon · Drakewell · Cobble · EscapeHub · Hookr · Paboxo | $0 | $0 | — | ~$0 | <$50 | All print zero — no traction |
| StonkBrokers suite · HoodPump · HoodMint · Prynt · NOXA Fun · rh.fun · Robin Labs · HookOS · ArrowPad · SolStocker · DOTT · Quiver · Diggers · Peeps · +~50 more | ~$0 | ~$0 | — | ~$0 | <$1.6k | Empty / idle |

## Base (older cohort)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| o1 Launchpad | $3,321 | $6,401 | −48% | $2,747 | $83,929 | 1.21× avg but the Nov 16 spike keeps decaying |
| clanker | $1,536 | $1,030 | +49% | $1,402 | $67,272 | 1.10× avg — steady small |
| Binance Alpha | $430 | $209 | +106% | $264 | $14,563 | 1.63× avg, small bounce |
| Umia | $215 | $85 | +153% | $522 | $39,934 | 0.41× avg — still well below trend |
| Flap sh | $193 | $481 | −60% | $102 | $1,252 | Micro |
| BaseStonk | $108 | $17 | +542% | $101 | $5,924 | Micro bounce |
| ZORA Coins | $18 | $25 | −28% | $25 | $843 | Micro |
| Boardwalk | $5 | $4 | +28% | $1 | $15 | Micro |
| EscapeHub Launchpad | $4 | $0 | — | $1 | $8 | New listing (Base), ~$0 |
| Liquid Protocol LaunchPad | $3 | $21 | −84% | $11 | $108 | Duplicate wiring — see next row |
| Rainbow Token Launchpad | $3 | $21 | −84% | $11 | $108 | Identical prints to Liquid Protocol — wiring duplicate, not activity |
| manifold.xyz (NFT) | $1 | $0 | — | $7 | $224 | Micro |
| Printr | $0 | $0 | — | $0 | $26 | **Faded** — no follow-through |
| PinkSale / Fjord V2 / Ape.Store / Basecamp / g8keep / flaunch / FastJPEG / Smithii / basedbid / +30 more | ~$0 | ~$0 | — | ~$0 | <$130 | Dead |

## Ethereum

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Binance Alpha | $960 | $633 | +52% | $1,455 | $75,279 | 0.66× avg — bounce off a low, still under trend |
| Stockereum | $650 | $352 | +85% | $843 | $65,990 | 0.77× avg — bounce, still decaying from its 30d peak |
| manifold.xyz (NFT) | $19 | $28 | −32% | $24 | $4,594 | Micro |
| fusi.ng | $0 | $0 | — | $0 | $352 | Negligible |
| PinkSale / Juicebox V1 / Fjord V2 / GraFun / clanker / Smithii / 1776.MEME / Legion / basedbid / sTONks / HookOS / Boardwalk / Packed / Peddles / moto.fun / Ferzan Factory / ALPHA Launchpad / QHooks | ~$0 | ~$0 | — | ~$0 | <$1.1k | Dead |

## Read

- **Pons V2 re-established itself.** It bounced to $19,708 (+29%), 1.28× its 7d avg, well clear of the ~$8k regime-change trigger it nearly touched on Nov 22 ($8,739). Direction over the month is still down ($43.7k Nov 6 → $19.7k now) but the $8–12k floor held and it is ~89% of tracked RH launchpad revenue — still the single line that defines Robinhood Chain launchpad activity.
- **Still no breakout successor** on any chain as of 2026-11-26. Base's o1 is 1.21× avg but −48% d/d and decaying; Umia's +153% is a 0.41× recovery; ETH's Binance Alpha/Stockereum bounces are 0.66×/0.77× avg. The newest RH listings (Polydash, Gmoon, Drakewell, Cobble, EscapeHub, Hookr, Paboxo) and Base's EscapeHub all print ≈$0 — a full month of new launchpad listings across the three chains has produced no traction beyond Pons V2.
- **Base old guard still soft** (o1 decaying, Umia 0.41× avg); clanker's $1,536 is steady at 1.10× avg. The Liquid/Rainbow duplicate-wiring artifact persists and should be ignored in totals.
- **Watch trigger:** a new launchpad line crossing ~$2k/day with a 7d avg under $500 (genuine breakout), or Pons V2 falling below ~$8k/day (regime change for Robinhood Chain activity). Neither hit this run — Pons V2 moved the other way, up.

## Launchpad totals (rough, 24h)

| Chain | Tracked launchpad revenue | Largest line |
|---|---|---|
| Robinhood Chain | ~$22,100 | Pons V2 $19,708 (~89%) |
| Base | ~$5,840 | o1 Launchpad $3,321 |
| Ethereum | ~$1,630 | Binance Alpha $960 |
