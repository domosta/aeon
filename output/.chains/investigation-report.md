ℹ️ Investigation Report - ZyFAI (ZFI), Base

**Investigation Report - ZyFAI (ZFI), Base**

**First: the address you sent isn't a token.** `0xc6f63e4b…03d2` is the **Uniswap V3 ZFI/WETH 1% pool** - in fact the main ZFI trading venue (~$257k reserves). The token is **ZyFAI (ZFI)**: `0xd080ed3c74a20250a2c9821885203034acd2d5ae`. I ran all six checks on the real token.

**At a glance:** Rug **LOW** (1/14) · source verified · owner = 3-of-5 Gnosis Safe (not renounced) · **no** mint / blacklist / pause / fee / upgrade powers · honeypot **SELLABLE** · holders **HEALTHY** · LP **UNKNOWN** (V3, non-fungible) · deployer OK → nothing alarming

**Rug Scan - LOW (score 1/14).** Only signal that fired: owner not renounced (+1). Contract is a LayerZero **OFT** (`sharedDecimals`=6, `token()`=self). ~12.5 KB runtime bytecode contains no mint, blacklist, pause, fee/tax setter, limit or upgrade selector. Not a proxy (EIP-1967 impl slot = 0).

**Contract Audit - OK.** Verified on Basescan. Owner `0x891c2b1d…6dbf0` is a **Gnosis Safe v1.4.1, threshold 3 of 5**. Live owner-gated surface is limited to `transferOwnership`, `renounceOwnership`, `setPeer`, `setDelegate` - i.e. LayerZero bridge config, not a Base-side mint/drain. Caveat: no API key this run, so no source-level static pass; a hardcoded transfer tax can't be fully excluded.

**Deployer Trace - OK.** Creator `0x952835d1…e6bd`, Basescan label *"Zyfai: Deployer"* (Farcaster @fxonchain.eth), an EIP-7702-delegated EOA. It is the project's deployer wallet: other creations seen are protocol infra (`MorphoFlashloanCallbackModule`, `ERC1967Proxy`) - no serial token launches, no rugged deployments.

**Holder Concentration - HEALTHY.** Base supply 200,941,653 ZFI across 1,535 holders. After excluding staking/lock/LP contracts (stZFI 27.6%, rZFI 9.6%, pool 8.6%, vstZFI, pZFI), **EOA** concentration is top-1 **4.89%**, top-5 16.4%, top-10 22.6%. HHI ≈ 1,005 all-holders / ~73 EOA-only. Watch: the top two EOAs bought their whole stacks in the last 30 days.

**Honeypot - SELLABLE.** Simulated a halved-balance transfer via `eth_call` from 5 different top holders; all returned `true`. No sell restriction found (this is not a tax measurement).

**LP Lock - UNKNOWN.** Uniswap V3 concentrated liquidity, so LP is held as NFT positions and "locked LP %" doesn't apply. Custody must be checked at the position manager `0x03a520b32C04BF3bEEf7BEb72E919cf822Ed34f1`. **Worth knowing:** the WETH side is only ~$66k (36.96 ETH) of the $257k pool - thin exit liquidity for size. All other ZFI pools are negligible ($1.3k, $968, $2-4).

**Context & caveat.** ZyFAI is a real, live self-custodial DeFi yield agent (audited by Sherlock + Cecuro); price $0.01133, mcap ~$2.85M, 24h vol ~$31k. Third-party raters call it *high risk / speculative* on micro-cap + thin liquidity, not on contract risk. Cross-chain supply does **not** reconcile from public reads: Base 200.94M + ZKsync 500.00M vs docs' 499.37M total - likely bridged backing double-counted, unverified. Verify with the team before trusting FDV.

Pool you sent: https://basescan.org/address/0xc6f63e4bea6682aa502ed94c1301b56230fc03d2
Actual token: https://basescan.org/token/0xd080ed3c74a20250a2c9821885203034acd2d5ae

*Heuristic risk signals, not investment advice. A clean report is not a guarantee of safety.*