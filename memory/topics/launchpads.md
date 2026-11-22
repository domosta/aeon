---
title: Launchpad revenue tracker (Base, Robinhood Chain, Ethereum)
description: Rolling daily revenue for token launchpads across Base, Robinhood Chain and Ethereum from DefiLlama, with trend notes. Used by revenue-alert to detect breakouts and decay.
tags: [launchpad, base, robinhood-chain, ethereum, revenue, defillama]
resource: https://defillama.com/fees
timestamp: 2026-11-22T18:05:00Z
---

# Launchpad Revenue Tracker

Daily protocol revenue (USD, DefiLlama `dataType=dailyRevenue`) for every protocol categorised
`Launchpad` / `NFT Launchpad` on the three monitored chains. Snapshot below is **2026-11-22 ~18:03 UTC**
(24h vs prior 24h). Update on each `revenue-alert` run — newest snapshot wins, older snapshots stay in git history for trend.

## Robinhood Chain (every launchpad here is new)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Pons V2 | $8,739 | $17,539 | −50% | $16,717 | $879,916 | **0.52× its 7d avg — first time within 10% of the $8k regime-change trigger.** Still ~80% of tracked RH launchpad revenue, but the 30d total keeps shrinking ($929k → $880k) as the early-Nov peak ($43.7k Nov 6) rolls off |
| Binance Alpha | $825 | $1,325 | −38% | $1,129 | $24,061 | Steady-to-down, ~0.73× avg |
| Pons V1 | $816 | $1,179 | −31% | $989 | $52,839 | Legacy line, drifting down |
| PAIR | $75 | $0 | — | $1.31 | $1,437 | Low-base spike off a near-zero 7d avg — not a breakout |
| Frontier | $62 | $112 | −45% | $70.7 | $47,575 | Bottomed, small |
| Flap sh | $59.67 | $94.91 | −37% | $118.5 | $11,698 | Micro |
| GlazeCorp Launchpad | $43.37 | $60.31 | −28% | $57 | $2,720 | Listed Nov 5, never got traction |
| Agen.space | $40.66 | $38.17 | +7% | $30.8 | $390 | New-ish micro, slowly up |
| o1 Launchpad | $32.42 | $44.70 | −27% | $37.8 | $3,440 | RH line, micro |
| Coinbarrel | $30.28 | $67.48 | −55% | $21.8 | $1,079 | Faded after Nov 4 listing |
| clanker | $22.88 | $35.24 | −35% | $35.5 | $1,624 | Micro |
| token.select | $16.84 | $11.86 | +42% | $18.4 | $1,427 | Micro |
| Sentry | $15.29 | $36.23 | −58% | $19.4 | $1,178 | Newer line, spiky micro |
| Hookers | $6.45 | $0.65 | +892% | $8.00 | $364 | Micro |
| LetsCash | $2.60 | $6.28 | −59% | $7.19 | $801 | Micro |
| Bags | $0.95 | $8.19 | −88% | $5.44 | $2,624 | Micro, collapsed |
| Pez Family | $0.64 | $16.29 | −96% | $7.49 | $438 | Micro, collapsed |
| **New listings** EscapeHub Launchpad (5.7d) · Polydash (5.0d) · Gmoon (1.9d) | $0 | $0 | — | ~$0 | <$15 | All three print zero — no traction |
| StonkBrokers Safe Launch / Sapling / ArrowPad / HoodPump / DOTT / HoodMint / Prynt / NOXA Fun / bow.fun / rh.fun / Robin Labs / HookOS | ~$0 | ~$0 | — | ~$0 | <$1.6k | Empty / idle |

## Base (older cohort)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| o1 Launchpad | $2,163 | $1,305 | +66% | $2,994 | $95,430 | Bounced, but 0.72× its 7d avg — the Nov 16 spike is still decaying |
| Umia | $328 | $1,570 | −79% | $833 | $45,029 | Gave back the Nov 21 bounce; 0.39× avg |
| clanker | $326 | $371 | −12% | $921 | $60,816 | 0.35× avg — well below its 30d pace |
| Binance Alpha | $213 | $283 | −25% | $287 | $16,287 | Low |
| BaseStonk | $143 | $114 | +25% | $105 | $6,531 | 1.36× avg, small but above trend |
| Liquid Protocol LaunchPad | $46.04 | $4.25 | +983% | $5.78 | $59.88 | Duplicate wiring — see next row |
| Rainbow Token Launchpad | $46.02 | $4.25 | +983% | $5.78 | $59.90 | Identical prints to Liquid Protocol — wiring duplicate, not activity |
| ZORA Coins | $36 | $41 | −12% | $25.9 | $924 | Micro |
| manifold.xyz (NFT) | $0.84 | $0 | — | $15.2 | $241 | Micro |
| Printr | $0 | $0 | — | $3.60 | $26 | **Faded** — the Nov 14-16 "new Base line" produced no follow-through |
| flaunch / Ape.Store / ZNS / sasa / Boardwalk / g8keep / Basecamp / Squeeze / Sprivio / Smithii / Peddles / basedbid | ~$0 | ~$0 | — | ~$0 | <$130 | Dead |

## Ethereum

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Binance Alpha | $829 | $1,365 | −39% | $1,576 | $75,121 | 0.53× avg — down hard |
| Stockereum | $307 | $448 | −31% | $994 | $70,217 | Still decaying from its 30d peak |
| manifold.xyz (NFT) | $15 | $49 | −69% | $120 | $4,686 | Micro |
| clanker | $0.18 | $0.02 | — | ~$0 | $21 | Negligible |
| Printr | $0 | $0 | — | $6.43 | $48 | Faded |
| PinkSale | $0 | $0 | — | $50.3 | $818 | 30d carried by an earlier burst, now idle |
| fusi.ng / Juicebox V1 / Fjord / GraFun / moto.fun / sTONks / Legion / Packed / HookOS / Peddles / basedbid / Smithii | ~$0 | ~$0 | — | ~$0 | <$1.4k | Dead |

## Read

- **Pons V2 is the story.** It halved d/d to $8,739 — 0.52× its 7d avg and the closest it has come to the $8k regime-change trigger. It still carries ~80% of tracked RH launchpad revenue, but the trend is one-way down: $43.7k (Nov 6) → $23.9k (Nov 20) → $16.5k (Nov 21) → $8.7k (Nov 22). If it breaks $8k, that is a genuine regime change for Robinhood Chain activity, not noise.
- **No breakout successor** on any chain as of 2026-11-22. PAIR's $75 print is a low-base micro; Base's o1 bounce is still 0.72× its 7d avg. The three launchpads listed in the last week (EscapeHub, Polydash, Gmoon) all print $0.
- **Base old guard is decaying in unison** (Umia 0.39×, clanker 0.35×, o1 0.72×). ETH's Binance Alpha and Stockereum are both well under trend. The Liquid/Rainbow duplicate-wiring artifact persists and should be ignored in totals.
- **Watch trigger:** a new launchpad line crossing ~$2k/day with a 7d avg under $500 (genuine breakout), or Pons V2 falling below ~$8k/day (regime change for Robinhood Chain activity). Neither hit this run — Pons V2 is within 10% of the second.
