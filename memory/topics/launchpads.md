---
title: Launchpad revenue tracker (Base, Robinhood Chain, Ethereum)
description: Rolling daily revenue for token launchpads across Base, Robinhood Chain and Ethereum from DefiLlama, with trend notes. Used by revenue-alert to detect breakouts and decay.
tags: [launchpad, base, robinhood-chain, ethereum, revenue, defillama]
resource: https://defillama.com/fees
timestamp: 2026-11-21T07:10:00Z
---

# Launchpad Revenue Tracker

Daily protocol revenue (USD, DefiLlama `dataType=dailyRevenue`) for every protocol categorised
`Launchpad` / `NFT Launchpad` on the three monitored chains. Snapshot below is **2026-11-21 ~07:05 UTC**
(24h vs prior 24h). Update on each `revenue-alert` run — newest snapshot wins, older snapshots stay in git history for trend.

## Robinhood Chain (every launchpad here is new)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Pons V2 | $16,470 | $23,908 | −31% | $17,343 | $929,333 | Recovered from the $12.8k Nov 16 print, but 30d total now $929k (was $1.14M on Nov 16) — the early-Nov peak ($43.7k Nov 6) is rolling out of the window. Still ~79% of tracked RH launchpad revenue |
| Binance Alpha | $1,394 | $1,144 | +22% | $1,145 | $22,627 | Steady, ~2× its Nov 16 level |
| Pons V1 | $1,179 | $831 | +42% | $1,027 | $53,715 | Legacy line, mildly up |
| Frontier | $112 | $91 | +23% | $86 | $47,531 | Bottomed, small |
| Flap sh | $107 | $127 | −16% | $121 | $12,285 | Micro |
| GlazeCorp Launchpad | $62 | $95 | −35% | $57 | $2,670 | Listed Nov 5, never got traction |
| o1 Launchpad | $58 | $47 | +24% | $45 | $3,506 | RH line, micro |
| Sentry | $37 | $5.46 | +581% | $18 | $1,190 | Newer line, spiky micro |
| Coinbarrel | $17.63 | $7.11 | +148% | $25 | $1,176 | Faded after Nov 4 listing |
| Pez Family | $14.67 | $1.49 | +885% | $11 | $444 | Micro, no traction |
| Bags | $8.19 | $1.40 | +485% | $9 | $2,628 | Micro |
| StonkBrokers Safe Launch | ~$0 | ~$0 | — | ~$0 | $25,255 | 30d carried by an earlier burst, now idle |
| Sapling / PAIR / brand-new shells (ArrowPad, HoodPump, DOTT, HoodMint, Prynt, NOXA Fun, bow.fun, rh.fun, Robin Labs, HookOS) | ~$0 | ~$0 | — | ~$0 | <$1.6k | Empty / idle |

## Base (older cohort)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| o1 Launchpad | $1,276 | $3,465 | −63% | $2,811 | $118,956 | Bounced hard on Nov 16 ($439 → $3,465), gave it back; still ~45% of its 30d pace |
| Umia | $1,084 | $900 | +20% | $1,146 | $47,538 | Stabilised near its 30d run-rate after the Nov decay |
| clanker | $446 | $1,429 | −69% | $941 | $60,940 | Still well below the Nov 16 bounce print ($2,186) |
| Binance Alpha | $295 | $198 | +49% | $312 | $16,715 | Low |
| BaseStonk | $123 | $115 | +7% | $146 | $6,926 | Low |
| ZORA Coins | $41 | $27 | +52% | $22 | $986 | Micro |
| manifold.xyz (NFT) | $0 | $47 | −100% | $17 | $241 | Micro |
| Printr | $0 | $0 | — | $3.6 | $26 | **Faded** — the Nov 14-16 "new Base line" produced no follow-through |
| Liquid Protocol LaunchPad / Rainbow Token Launchpad | $4.37 each | $0.47 | +830% | $2.9 | $41 | Identical prints — looks like a wiring duplicate, not activity |
| flaunch / Ape.Store / ZNS / sasa / Boardwalk / g8keep / Basecamp | ~$0 | ~$0 | — | ~$0 | <$130 | Dead |

## Ethereum

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Binance Alpha | $1,697 | $1,200 | +41% | $1,720 | $74,957 | Steady |
| Stockereum | $522 | $1,461 | −64% | $1,649 | $78,671 | Still decaying from its 30d peak |
| manifold.xyz (NFT) | $49 | $30 | +63% | $119 | $4,693 | Micro |
| fusi.ng | $25 | $0 | — | $3.8 | $1,143 | Micro burst |
| Printr | $0 | $0 | — | $6.4 | $60 | Faded |
| clanker (ETH) | $0.01 | $0.02 | −50% | ~$0 | $33 | Negligible |
| PinkSale / Juicebox V1 / Fjord / GraFun / moto.fun / sTONks | ~$0 | ~$0 | — | ~$0 | <$1.4k | Dead |

## Read

- **Nothing rotated.** Pons V2 (RH) still dominates (~79% of tracked launchpad revenue) and simply recovered to its ~$16-17k run-rate after the Nov 16 trough; the 30d total shrank only because the early-Nov peak rolled off. Base's old guard (o1, Umia, clanker) is flat-to-decaying, and the Nov 14-16 "newcomer" Printr has faded to zero on both Base and ETH.
- **No breakout successor** on any chain as of 2026-11-21. The newest lines with any print (Sentry, Pez Family, Coinbarrel on RH) are micro noise; no line has crossed the ~$2k/day breakout bar with a 7d avg under $500.
- **Watch trigger:** a new launchpad line crossing ~$2k/day with a 7d avg under $500 (genuine breakout), or Pons V2 falling below ~$8k/day (regime change for Robinhood Chain activity). Neither hit this run.
