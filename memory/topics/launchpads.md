---
title: Launchpad revenue tracker (Base, Robinhood Chain, Ethereum)
description: Rolling daily revenue for token launchpads across Base, Robinhood Chain and Ethereum from DefiLlama, with trend notes. Used by revenue-alert to detect breakouts and decay.
tags: [launchpad, base, robinhood-chain, ethereum, revenue, defillama]
resource: https://defillama.com/fees
timestamp: 2026-11-23T17:45:00Z
---

# Launchpad Revenue Tracker

Daily protocol revenue (USD, DefiLlama `dataType=dailyRevenue`) for every protocol categorised
`Launchpad` / `NFT Launchpad` on the three monitored chains. Snapshot below is **2026-11-23 ~17:40 UTC**
(24h vs prior 24h). Update on each `revenue-alert` run — newest snapshot wins, older snapshots stay in git history for trend.

## Robinhood Chain (every launchpad here is new)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Pons V2 | $11,913 | $10,826 | +10% | $16,244 | $835,614 | **Bounced back above the $8k regime-change trigger** after touching $8,739 on Nov 22. Still ~84% of tracked RH launchpad revenue, trend still down: $43.7k (Nov 6) → $16.5k (Nov 21) → $8.7k (Nov 22) → $11.9k (Nov 23); 30d keeps shrinking |
| Binance Alpha | $1,268 | $1,434 | −12% | $1,100 | $24,838 | Steady-to-down, ~1.15× avg |
| Pons V1 | $504 | $816 | −38% | $904 | $51,761 | Legacy line, drifting down |
| Flap sh | $88.40 | $98.86 | −11% | $97 | $11,209 | Micro, flat |
| o1 Launchpad | $68.88 | $32.91 | +109% | $38 | $3,370 | Micro bounce off a near-zero base |
| Frontier | $52 | $62 | −16% | $69 | $47,620 | Bottomed, small |
| Agen.space | $51.14 | $35.86 | +43% | $34 | $429 | New-ish micro, slowly up |
| GlazeCorp Launchpad | $40.98 | $49.65 | −17% | $56 | $2,759 | Listed Nov 5, never got traction |
| Coinbarrel | $24.52 | $24.10 | +2% | $23 | $961 | Faded after Nov 4 listing |
| clanker | $11.86 | $48.29 | −75% | $34 | $1,531 | Micro |
| token.select | $8.86 | $21.03 | −58% | $17 | $1,059 | Micro |
| AGNT | $6.29 | $1.38 | +356% | $2 | $653 | Micro noise |
| Hookers | $3.75 | $53.21 | −93% | $8 | $343 | Micro, collapsed |
| Bags | $3.33 | $0.95 | +251% | $4 | $2,599 | Micro |
| EscapeHub Launchpad | $0.48 | $0.07 | +586% | $1 | $12 | New listing, still ~$0 |
| Sentry | $0.52 | $19.77 | −97% | $17 | $1,071 | Micro, collapsed |
| Pez Family | $0.14 | $6.77 | −98% | $7 | $437 | Micro, collapsed |
| StonkBrokers Safe Launch | $0 | $6.53 | −100% | $1 | $25,261 | Collapsed after an earlier burst |
| PAIR · basedbid · keep.coffee | $0 | $0 | — | ~$2–11 | $855–$1,512 | Idle / low-base only |
| New listings Polydash (6d) · Gmoon (2.9d) · Drakewell · Cobble | $0 | $0 | — | ~$0 | <$50 | All print zero — no traction |
| StonkBrokers suite · HoodPump · HoodMint · Prynt · NOXA Fun · bow.fun · rh.fun · Robin Labs · HookOS · ArrowPad · SolStocker · +~40 more | ~$0 | ~$0 | — | ~$0 | <$1.6k | Empty / idle |

## Base (older cohort)

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| o1 Launchpad | $1,308 | $2,163 | −40% | $3,067 | $88,243 | 0.43× avg — the Nov 16 spike is still decaying |
| clanker | $791 | $367 | +116% | $611 | $60,614 | 1.29× avg — bounce, still small |
| Umia | $441 | $297 | +48% | $642 | $44,133 | 0.69× avg — recovering off a low |
| Binance Alpha | $244 | $299 | −18% | $270 | $15,665 | Low, flat |
| BaseStonk | $150 | $76.85 | +95% | $111 | $6,490 | 1.36× avg, small but above trend |
| ZORA Coins | $9.30 | $36 | −74% | $23 | $887 | Micro |
| EscapeHub Launchpad | $0.68 | $0 | — | $0 | $3 | New listing (Base), ~$0 |
| Liquid Protocol LaunchPad | $0.36 | $20.29 | −98% | $7 | $85 | Duplicate wiring — see next row |
| Rainbow Token Launchpad | $0.25 | $20.29 | −98% | $7 | $85 | Identical prints to Liquid Protocol — wiring duplicate, not activity |
| manifold.xyz (NFT) | $0 | $0.84 | −100% | $12 | $228 | Micro |
| Printr | $0 | $0 | — | $0 | $26 | **Faded** — the Nov 14-16 "new Base line" produced no follow-through |
| flaunch / Ape.Store / ZNS / sasa / Boardwalk / g8keep / Basecamp / Squeeze / Sprivio / Smithii / Peddles / basedbid / Bonker / +30 more | ~$0 | ~$0 | — | ~$0 | <$130 | Dead |

## Ethereum

| Protocol | 24h | prev | chg | 7d avg | 30d total | Trend |
|---|---|---|---|---|---|---|
| Binance Alpha | $2,648 | $2,250 | +18% | $1,578 | $73,496 | 1.68× avg, small but above trend |
| Stockereum | $1,888 | $410 | +360% | $948 | $68,719 | 1.99× avg — bounced; still decaying from its 30d peak |
| manifold.xyz (NFT) | $5.99 | $15 | −60% | $119 | $4,616 | Micro |
| fusi.ng | $1.93 | $0 | — | $3 | $1,131 | Negligible |
| clanker | $0 | $0.01 | −100% | ~$0 | $19 | Negligible |
| Printr | $0 | $0 | — | $0 | $45 | Faded |
| PinkSale | $0 | $0 | — | $50 | $818 | 30d carried by an earlier burst, now idle |
| Juicebox V1 / Fjord V1-V2 / GraFun / moto.fun / sTONks / Legion / Packed / HookOS / Peddles / basedbid / Smithii | ~$0 | ~$0 | — | ~$0 | <$1.4k | Dead |

## Read

- **Pons V2 recovered, so no regime change yet.** It bounced +10% to $11,913 (0.73× its 7d avg) one day after reaching $8,739 — the $8k trigger was not broken. Direction is still down over the month ($43.7k Nov 6 → $11.9k now) and it remains ~84% of tracked RH launchpad revenue, so it is still the single line that defines Robinhood Chain launchpad activity.
- **No breakout successor** on any chain as of 2026-11-23. Base's o1 is 0.43× its 7d avg and decaying; Umia's +48% is a 0.69× recovery, not a spike; ETH's Stockereum +360% is only 2.0× avg. The newest RH listings (Polydash, Gmoon, Drakewell, Cobble) and Base's EscapeHub all print ≈$0 — a full month of new launchpad listings across the three chains has produced no traction beyond Pons V2.
- **Base old guard still decaying** (o1 0.43×, Umia 0.69×), clanker's +116% is a 1.29× bounce off a low base. The Liquid/Rainbow duplicate-wiring artifact persists and should be ignored in totals.
- **Watch trigger:** a new launchpad line crossing ~$2k/day with a 7d avg under $500 (genuine breakout), or Pons V2 falling below ~$8k/day (regime change for Robinhood Chain activity). Neither hit this run — Pons V2 bounced the other way.

## Launchpad totals (rough, 24h)

| Chain | Tracked launchpad revenue | Largest line |
|---|---|---|
| Robinhood Chain | ~$14,150 | Pons V2 $11,913 (~84%) |
| Base | ~$2,950 | o1 Launchpad $1,308 |
| Ethereum | ~$4,540 | Binance Alpha $2,648 |
