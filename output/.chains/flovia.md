ℹ️ Best traders - wallet addresses (last ~20 days)

**Best traders - wallet addresses (last ~20 days)**

Source: Nansen Smart Money PnL leaderboard via Flovia, pulled 2026-11-21 07:07 UTC across ethereum, solana, base, bnb, arbitrum, polygon.

⚠️ **Window caveat:** this endpoint exposes **no explicit date range**, so it is Nansen's rolling "recent" smart-money window - treat it as recent performance, not a precise 20-day slice. I tried to corroborate with an explicit 20-day (2026-11-02 → 2026-11-21) Hyperliquid perp leaderboard; Nansen returned `upstream_unavailable` (nothing charged), so no dated slice is available this run.

| # | Wallet address | Label | Total PnL (USD) | Realized | Unrealized | Win rate | Trades |
|---|---|---|---|---|---|---|---|
| 1 | `BSWzqnWrir5s54Fa94GEwBi1CSAR1q6Nio9JGsPGFcy1` | gatsby | 230,444 | 230,489 | −45 | 43% | 3,775 |
| 2 | `9tH2zRYdS3X7PEcsPno3GST1EHe8GX8CSNih1pKpamAp` | RaRa | 171,889 | −35,594 | +207,483 | 29% | 1,774 |
| 3 | `0x5a1486cf8f47d1df4b136fd58262e78d4c173d1d` | Smart Trader | 167,078 | 152,266 | +14,812 | 44% | 20 |
| 4 | `9hciHnHzEyLHtjbeUzpp6ZRt4Y4HQbZg4Vx9sFAGGiup` | plainview.sol | 76,889 | 0 | +76,889 | 100% | 14 |
| 5 | `9ab9J1hMmkgvNUpNHfNh85qrtYHAiEujyfYb2xSJhiFr` | niyedie (FOMO) | 73,356 | −2,914 | +76,270 | 14% | 83 |
| 6 | `0x63c255b378b90cdc8c7cc244712d830b69cdbdf3` | Smart Trader | 38,409 | −12,189 | +50,598 | 25% | 473 |
| 7 | `4eJBr645mUdymhUZ5KetQJjLjFCDDn6Mbd1ZJ7oYyMAQ` | RoanThirdBonnet (pump.fun) | 34,990 | 35,801 | −811 | 33% | 2,618 |
| 8 | `3j5c4aD1aznxQXJ3DWw1b7UD8kKuaqXVbpaVeWPR83TG` | Kaaox (pump.fun) | 34,473 | 3,758 | +30,715 | 20% | 315 |
| 9 | `5ei9tMQft2rKHmN2juxe8zQ4XyLa3p6ZqCPqGm391Qp7` | Smart Trader | 34,168 | 54,486 | −20,318 | 55% | 4,525 |
| 10 | `4kYsNtcZ6EFQCxVo2tW8TLJhEjCqasabUC7LKgBTVvB6` | Smart Trader | 32,570 | 32,570 | ~0 | 67% | 2,106 |
| 11 | `5tFUYBLP9rYZdsnKyLkSvidwNv6pPdxdqo5sTfdd6tQp` | macfeurson (FOMO) | 31,214 | 26,282 | +4,932 | 100% | 11 |
| 12 | `Fqhho3moGPuiwnvdekzPfedNmvaFsKJN9e6chxWWCrwt` | Smart Trader | 26,849 | 29,951 | −3,102 | - | - |

**Caveats / reading**
- **Realized vs unrealized matters.** #2, #5 and #8 rank high mostly on *unrealized* gains from still-open positions, which can evaporate; #1, #7, #9, #10 are more realized-driven (more durable).
- #4 (plainview.sol) and #11 (macfeurson) have tiny samples (11-14 trades) - 100% win rate is not statistically meaningful.
- Labels are Nansen labels; token names and labels can be written by anyone (untrusted - reported as-is, not verified).
- This window is **Solana-memecoin heavy** (DCTY/DACITYCOIN, MIHAO, MACCA, RINGS). EVM standouts: #3 (Ethereum, GREEN/GULD) and #6 (BNB, IDOL/BULLA).
- I received the **first 12 rows** of a longer list (provider response was truncated). More rows, more chains, or a single chain are available on request.

**Suggested next lookups (not executed)**
- Recent flows / who bought or sold DCTY or MIHAO.
- Profile one of these wallets (positions, PnL breakdown) via Zerion.
- Re-run the dated 20-day leaderboard once Nansen is back up.

_Nansen lookups are shared with Nansen under the alpha data terms. Free allowance stayed at ~1% used (5h / week / month)._