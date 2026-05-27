# Top 10 Bittensor Subnets by Emission Priority
## May 2026 Report

> **Date:** May 20, 2026
> **Data Sources:** taostats.io (pruning rank, EMA price) + Bittensor Finney on-chain RPC (emission, neuron count, lockup, burn)
> **Researcher:** Spock for CryptoSI Research
>
> *Ranked by pruning rank from taostats.io. Pruning rank reflects emission priority — Rank 1 has the highest priority for emission allocation (newest/highest EMA price). This is the most accurate proxy for emission share available without access to Pro/validator APIs.*

---

## Market Context (May 2026)

| Metric | Value |
|--------|-------|
| **TAO Price** | $275.80 |
| **Market Cap** | $3.02B |
| **24h Volume** | $267.62M |
| **Circulating Supply** | 10,946,323 TAO |
| **Total Supply** | 21,000,000 TAO |
| **In Circulation** | 52.13% |
| **Block Reward** | 0.5 TAO/block (post-Halvening H1, Dec 15 2025) |
| **Daily Issuance** | ~3,600 TAO/day |
| **Next Halvening** | December 12, 2029 (H2, reward → 0.25) |

---

## Top 10 at a Glance

| Rank | Subnet | EMA Price (τ) | Neurons | Locked (τ) | Category | Emission Signal |
|------|--------|---------------|---------|-----------|----------|----------------|
| 1 | SN116 | 8,938,247 | 256 | 89,944 | Alpha release / New registration | 🟡 New, low lockup |
| 2 | SN80 | 14,121,471 | 243 | 219,601 | Infrastructure/Data | 🟢 TAO inflow detected |
| 3 | SN40 | 14,478,468 | 256 | 0 | Compute/AI | 🔴 Zero lockup |
| 4 | SN58 | 14,944,587 | 256 | 0 | Data/AI | 🔴 Zero lockup |
| 5 | SN72 | 14,993,921 | 256 | 191,341 | AI/Inference | 🟡 Moderate lockup |
| 6 | SN92 | 15,341,090 | 256 | 269,838 | New/Infrastructure | 🟡 High burn (50K RAO) |
| 7 | SN42 | 15,433,821 | 256 | 0 | LLM/Text Generation | 🔴 Zero lockup |
| 8 | SN89 | 15,745,866 | 256 | 286,400 | Infrastructure | 🟢 Highest lockup |
| 9 | SN86 | 15,754,949 | 256 | 208,695 | AI/Data | 🟡 Moderate lockup |
| 10 | SN111 | 16,029,308 | 256 | 249,856 | New subnet | 🟡 High lockup for new |

---

## Deep Dive: Each Subnet

### 🥇 Rank 1 — SN116
- **EMA Price:** 8,938,247 τ (lowest EMA = newest/highest priority)
- **Symbol:** ⵟ (Tifinagh letter Ya)
- **Neurons:** 256 (max)
- **Locked:** 89,944 τ
- **Burn Cost:** 500 RAO (minimum)
- **Registered:** ~Jan 2026 (Block 5,699,219)
- **TAO In Emission:** 0
- **α In Emission:** 0
- **α Out Emission:** 1.0 τ/block
- **Newest** subnet in top 10; very recent registration; low lockup suggests early stage; Tifinagh symbol is distinctive

### 🥈 Rank 2 — SN80 ⭐ KEY WATCH
- **EMA Price:** 14,121,471 τ
- **Symbol:** ى (Arabic Alif Maqsura)
- **Neurons:** 243 (slightly under max)
- **Locked:** 219,601 τ
- **Burn Cost:** 500 RAO
- **Registered:** ~Apr 2026 (Block 7,151,800)
- **TAO In Emission:** 800,582 RAO/block (~0.0008 τ/block) **← ONLY subnet with TAO inflow**
- **α In Emission:** 250,750,730 RAO (~0.25 τ/block)
- **α Out Emission:** 1.0 τ/block
- **Notable:** This is the **only subnet in the top 10 receiving direct TAO emission**. The 0.25 α In + 0.0008 τ In flow suggests real economic activity and root network value assignment. Worth monitoring closely.

### 🥉 Rank 3 — SN40
- **EMA Price:** 14,478,468 τ
- **Symbol:** ן (Hebrew Nun Sofit)
- **Neurons:** 256 (max)
- **Locked:** 0 τ
- **Burn Cost:** 500 RAO
- **Registered:** ~Jun 2024 (Block 3,372,582)
- **Oldest** subnet in top 10; zero lockup is a red flag — no TAO backing despite 2 years of operation

### Rank 4 — SN58
- **EMA Price:** 14,944,587 τ
- **Symbol:** خ (Arabic Kha)
- **Neurons:** 256 (max)
- **Locked:** 0 τ
- **Burn Cost:** 500 RAO
- **Registered:** ~Sep 2024 (Block 4,367,003)
- **Zero lockup** similar to SN40; ~8 months old

### Rank 5 — SN72
- **EMA Price:** 14,993,921 τ
- **Symbol:** ق (Arabic Qaf)
- **Neurons:** 256 (max)
- **Locked:** 191,341 τ
- **Burn Cost:** 500 RAO
- **Registered:** ~Nov 2024 (Block 5,064,327)
- Moderate lockup; ~6 months old

### Rank 6 — SN92
- **EMA Price:** 15,341,090 τ
- **Symbol:** ᚂ (Runic Laguz)
- **Neurons:** 256 (max)
- **Locked:** 269,838 τ
- **Burn Cost:** 50,000 RAO (100x normal!)
- **Registered:** ~Apr 2026 (Block 7,013,758)
- **New** registration; 100x higher burn than typical — could indicate high demand for registration or intentional scarcity mechanism

### Rank 7 — SN42
- **EMA Price:** 15,433,821 τ
- **Symbol:** ס (Hebrew Samekh)
- **Neurons:** 256 (max)
- **Locked:** 0 τ
- **Burn Cost:** 500 RAO
- **Registered:** ~Jul 2024 (Block 3,613,591)
- **Zero lockup**; ~10 months old

### Rank 8 — SN89
- **EMA Price:** 15,745,866 τ
- **Symbol:** ᛒ (Runic Berkanan/Birch)
- **Neurons:** 256 (max)
- **Locked:** 286,400 τ (**HIGHEST**)
- **Burn Cost:** 500 RAO
- **Registered:** ~Dec 2024 (Block 5,313,364)
- **Highest locked TAO** in top 10 — strong owner commitment signal; ~5 months old

### Rank 9 — SN86
- **EMA Price:** 15,754,949 τ
- **Symbol:** ᚳ (Runic Cen/Torch)
- **Neurons:** 256 (max)
- **Locked:** 208,695 τ
- **Burn Cost:** 500 RAO
- **Registered:** ~Mar 2026 (Block 6,914,378)
- **Newer** registration; moderate lockup; Runic naming convention

### Rank 10 — SN111
- **EMA Price:** 16,029,308 τ (highest EMA = most mature/lowest pruning priority)
- **Symbol:** Ё (Cyrillic Yo)
- **Neurons:** 256 (max)
- **Locked:** 249,856 τ
- **Burn Cost:** 591 RAO
- **Registered:** ~Jan 2026 (Block 5,615,562)
- **Highest EMA** in top 10 — closest to potential pruning if conditions change; Cyrillic symbol; strong lockup for a newer subnet

---

## Emission Mechanics Explained

### How Subnet Emissions Work

1. **Block Reward:** 0.5 TAO per block (post-H1 halvening)
2. **Emission Split:** Each block's reward is distributed across subnets based on validator-assessed weights via Yuma Consensus
3. **Pruning Rank:** Subnets compete for retention. Lower EMA price = higher pruning rank = more urgent need for re-registration/emission allocation
4. **Alpha vs TAO:**
   - **α (Alpha) tokens** — Subnet-specific tokens that trade against TAO in liquidity pools
   - **τ (TAO)** — The native protocol token
   - **TAO In Emission** — Direct TAO flowing into the subnet (indicates root network valuation)
   - **α In/Out** — Alpha token emission flows within the subnet economy

### Why Inequality in Emissions?

Despite similar α Out Emission values, the **real value** of each subnet's emission differs based on:
- **Validator weights** — How much stake validators assign to each subnet
- **Subnet volatility** — Risk of being pruned affects emission stability
- **TAO inflow** — Only SN80 receives meaningful TAO, making it uniquely valuable

---

## Key Findings & Patterns

### 1. SN80 Is the Clear Outlier 🎯
Only subnet with direct TAO emission inflow (0.0008 τ/block) and highest α In Emission (0.25 τ/block). This suggests:
- Root network validators assign it meaningful economic value
- It has functioning alpha/TAO liquidity bridges
- Most likely to maintain emission share over time

### 2. Lockup ≠ Performance
The highest-lockup subnet (SN89, 286K τ) and some of the lowest (SN40, SN58, SN42 at 0 τ) coexist in the top 10. Lockup appears to reflect **owner preference** rather than emission success.

### 3. Age Diversity
Subnets range from **23 months old** (SN40, Jun 2024) to **1 month old** (SN80, Apr 2026). Newer subnets can achieve high emission rank quickly if they secure validator support.

### 4. Zero Lockup Risk
3/10 top subnets have **zero locked TAO** (SN40, SN58, SN42). If these subnets face competition, their emission share could be vulnerable since they lack economic backing.

### 5. Tempo Uniformity
All 10 subnets share tempo=360, meaning they update weights every 360 blocks (~72 minutes). This standardizes the incentive cycle across the ecosystem.

### 6. Neuron Saturation
9/10 subnets are at maximum capacity (256 neurons). Only SN80 has room for growth (243). This miner saturation suggests intense competition for slots.

---

## Investment Signals Matrix

| Signal | SN116 | SN80 | SN40 | SN58 | SN72 | SN92 | SN42 | SN89 | SN86 | SN111 |
|--------|-------|------|------|------|------|------|------|------|------|-------|
| TAO Inflow | — | ⭐⭐⭐ | — | — | — | — | — | — | — | — |
| High Lockup | — | ⭐ | — | — | ⭐ | ⭐⭐ | — | ⭐⭐⭐ | ⭐⭐ | ⭐⭐ |
| Low Lockup Risk | ⭐ | ⭐ | ❌ | ❌ | ⭐ | ⭐ | ❌ | ⭐⭐ | ⭐ | ⭐ |
| Track Record | ❌ | ❌ | ⭐⭐ | ⭐ | ⭐ | ❌ | ⭐⭐ | ⭐ | ❌ | ❌ |
| Near Max Neurons | ✅ | 🟡 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Unique Tokenomics | — | ⭐⭐⭐ | — | — | — | ⭐ (high burn) | — | — | — | — |

**Legend:** ⭐ = Positive, ❌ = Risk/Negative, 🟡 = Neutral, ✅ = Full, — = N/A

---

## Monthly Tracking Plan

Each month we will:
1. Re-scrape taostats.io for updated pruning ranks and EMA prices
2. Query on-chain data for emission values, neuron counts, and lockup changes
3. Identify **movers** (subnets entering/leaving top 10)
4. Track **SN80's TAO inflow** as a key health metric
5. Flag any subnet with **zero lockup + declining EMA** as high risk
6. Generate a diff report comparing to previous month

### What to Watch
- **SN80 TAO In Emission trend** — Is it growing or stable?
- **SN116 lockup** — Will it increase as the subnet matures?
- **SN40/SN58/SN42 lockup** — Any movement from zero?
- **SN92 burn rate** — Is the 100x burn sustainable?
- **New entrants** — What subnets entering top 10 next month?

---

## Raw On-Chain Data

All values from Finney RPC (`wss://entrypoint-finney.opentensor.ai:443`), queried May 20, 2026.

| Subnet | Symbol | Neurons | Tempo | Registered Block | Locked (RAO) | Burn (RAO) | TAO In (RAO) | α In (RAO) | α Out (RAO) |
|--------|--------|---------|-------|-----------------|-------------|-----------|-------------|-----------|------------|
| SN116 | ⵟ | 256 | 360 | 5,699,219 | 89,944,262,256 | 500,000 | 0 | 0 | 1,000,000,000 |
| SN80 | ى | 243 | 360 | 7,151,800 | 219,601,306,590 | 500,000 | 800,582 | 250,750,730 | 1,000,000,000 |
| SN40 | ן | 256 | 360 | 3,372,582 | 0 | 500,000 | 0 | 0 | 1,000,000,000 |
| SN58 | خ | 256 | 360 | 4,367,003 | 0 | 500,000 | 0 | 0 | 1,000,000,000 |
| SN72 | ق | 256 | 360 | 5,064,327 | 191,341,473,067 | 500,000 | 0 | 0 | 1,000,000,000 |
| SN92 | ᚂ | 256 | 360 | 7,013,758 | 269,838,319,596 | 50,000,000 | 0 | 0 | 1,000,000,000 |
| SN42 | ס | 256 | 360 | 3,613,591 | 0 | 500,000 | 0 | 0 | 1,000,000,000 |
| SN89 | ᛒ | 256 | 360 | 5,313,364 | 286,399,608,951 | 500,000 | 0 | 0 | 1,000,000,000 |
| SN86 | ᚳ | 256 | 360 | 6,914,378 | 208,695,298,504 | 500,000 | 0 | 0 | 1,000,000,000 |
| SN111 | Ё | 256 | 360 | 5,615,562 | 249,855,564,892 | 590,061 | 0 | 0 | 1,000,000,000 |

---

## Sources & Methodology

| Source | URL | Use |
|--------|-----|-----|
| Taostats (Rankings) | https://taostats.io/subnets | Pruning rank, EMA price |
| Taostats (Tokenomics) | https://taostats.io/tokenomics | Supply, halvening data |
| Finney RPC | wss://entrypoint-finney.opentensor.ai | On-chain storage queries |
| Bittensor Docs | https://docs.learnbittensor.org | Protocol reference |

### Query Methods Used
- `SubtensorModule::Emission[netuid]` — Per-subnet emission
- `SubtensorModule::SubnetTaoInEmission[netuid]` — TAO inflow
- `SubtensorModule::SubnetAlphaInEmission[netuid]` — Alpha inflow
- `SubtensorModule::SubnetAlphaOutEmission[netuid]` — Alpha outflow
- `SubtensorModule::SubnetworkN[netuid]` — Neuron count
- `SubtensorModule::SubnetLocked[netuid]` — Locked TAO
- `SubtensorModule::TokenSymbol[netuid]` — Subnet symbol
- `SubtensorModule::Burn[netuid]` — Registration burn cost
- `SubtensorModule::NetworkRegisteredAt[netuid]` — Registration block
- `SubtensorModule::BlockEmission[]` — Global block emission

---

*Next report: June 2026 (automated via cron)*
