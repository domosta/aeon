---
title: Launchpad revenue tracker (Base, Robinhood Chain, Ethereum)
description: Rolling daily revenue for token launchpads across Base, Robinhood Chain and Ethereum from DefiLlama, with trend notes. Used by revenue-alert to detect breakouts and decay.
tags: [launchpad, base, robinhood-chain, ethereum, revenue, defillama]
resource: https://defillama.com/fees
timestamp: 2026-11-16T08:05:00Z
---

# Launchpad Revenue Tracker

Daily protocol revenue (USD, DefiLlama `dataType=dailyRevenue`) for every protocol categorised
`Launchpad` / `NFT Launchpad` on the three monitored chains. Snapshot below is **2026-11-16 ~07:55 UTC**
(24h vs prior 24h). Update on each `revenue-alert` run — newest snapshot wins, older columns stay for trend.

## Robinhood Chain (chain live ~Nov 2026 — every launchpad here is new)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Pons V2 | $12,776 | $15,208 | −16% | $18,962 | $1,143,375 | Peak $43.7k on Nov 6 → −71% in 9d; still ~74% of all tracked launchpad revenue |
| Pons V1 | $1,101 | $1,079 | +2% | $1,659 | $58,616 | Flat, legacy line of the Pons team |
| Binance Alpha | $847 | $1,544 | −45% | $1,522 | $17,136 | Cooled with the RH volume |
| Flap sh | $217 | $113 | +92% | $169 | $17,604 | Micro, but the only RH launchpad growing |
| GlazeCorp Launchpad | $46.58 | $48.98 | −5% | $48 | $2,368 | Listed Nov 5, never got traction |
| Frontier | $64 | $169 | −62% | $229 | $47,203 | 30d peak long gone |
| Coinbarrel | $0.63 | $47.36 | −99% | $28 | $1,298 | Faded after Nov 4 listing |
| hood.fun / rh.fun, bow.fun, HoodMint, ArrowPad, HoodPump, Robin Labs | ~$0 | ~$0 | — | — | <$100 | Empty shells; listed but zero fee flow |

## Base (older cohort)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| clanker | $2,186 | $506 | +332% | $3,354 | $61,422 | Bounce off a trough, **not** a breakout — 0.65× avg, series choppy $219–$12.8k |
| Umia | $745 | $2,486 | −70% | $1,518 | $47,188 | Decaying |
| o1 Launchpad | $439 | $881 | −50% | $1,289 | $110,376 | At 12% of its 30d pace — fastest decay of the Base cohort |
| Binance Alpha | $151 | $472 | −68% | $380 | $18,438 | Low |
| BaseStonk | $83.29 | $364 | −77% | $228 | $8,223 | Low |
| ZORA Coins | $26 | $12 | +117% | $14 | $1,490 | Micro |
| manifold.xyz (NFT) | $16 | $14 | — | $12 | $206 | Micro |
| Printr | $25 | $0 | new | — | $27 total | **New, day 2** — first new Base launchpad line in weeks, below threshold |
| flaunch / Ape.Store / ZNS / sasa / Boardwalk | ~$0 | ~$0 | — | — | <$500 | Dead |

## Ethereum

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Binance Alpha | $996 | $3,258 | −69% | $1,666 | $76,327 | Decaying |
| Stockereum | $875 | $4,996 | −82% | $2,919 | $98,265 | Hard decay from its 30d peak |
| manifold.xyz (NFT) | $7.27 | $7.83 | — | $28 | $4,113 | Micro |
| Printr | $45 | $0 | new | — | $60 total | New, 2 days |
| clanker (ETH) | $0.01 | $0 | — | $0.02 | $97 | Negligible |
| fusi.ng / PinkSale / Juicebox V1 / sTONks | $0 | $0 | — | ~$0 | <$1.4k | Dead |

## Read

- **Nothing is rotating.** Pons V2 on Robinhood Chain still dominates (~74% of tracked launchpad revenue) and is down 71% in nine days. The Base old guard (clanker, o1, Umia, Binance Alpha) is in slow decay, and clanker's +332% print is mean reversion off a $506 day.
- **No breakout successor** on any chain as of 2026-11-16 — the newest lines (Printr 2 days / $27 lifetime; GlazeCorp $2.4k lifetime) are noise. Launchpad fee revenue is concentrating into decline rather than moving to a new venue.
- **Watch trigger:** a new launchpad line crossing ~$2k/day with a 7d avg under $500 (i.e. a genuine breakout), or Pons V2 falling below ~$8k/day (regime change for Robinhood Chain activity).
