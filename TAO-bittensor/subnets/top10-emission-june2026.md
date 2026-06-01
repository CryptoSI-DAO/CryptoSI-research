# Top 10 Bittensor Subnets by Emission Priority — Fundamentals Report
## June 2026

> **Date:** June 1, 2026
> **Data Sources:** taostats.io (pruning rank, EMA), Bittensor Finney RPC (emission, neuron count, lockup, identity via `SubnetIdentitiesV3`), GitHub repos (fundamentals)
> **Researcher:** Spock for CryptoSI Research
> *Ranked by pruning rank from taostats.io (Rank 1 = highest emission priority). Each subnet scored on 8 factors (max 80 points) using the CryptoSI opportunity scorecard framework.*

---

## Market Context (June 2026)

| Metric | Value |
|--------|-------|
| **TAO Price** | $250.59 |
| **Market Cap** | $2.74B |
| **24h Volume** | $173.57M |
| **Circulating Supply** | ~10,968,129 TAO |
| **Block Reward** | 0.5 TAO/block (1,000,000,000 RAO — post-H1 halvening, Dec 15 2025) |
| **Daily Issuance** | ~3,600 TAO/day |
| **Next Halvening** | December 12, 2029 (H2 → 0.25) |
| **Total Subnets** | 129 (+1 from 128 in May) |

**Market delta from May:** TAO recovered from $277 → $250 (down ~10%), market cap stable at $2.74B, volume slightly down from $259M → $174M. One new subnet registered (128→129).

---

## Month-over-Month Changes

### Subnets Entering Top 10
| Subnet | Name | Notes |
|--------|------|-------|
| **SN59** | Babelbit | NEW — LLM-powered translation services. Entered at Rank 7 |
| **SN45** | Talisman AI | NEW — AI/LLM subnet (minimal description). Entered at Rank 8 |
| **SN32** | ItsAI | NEW — AI text detection (MGTD benchmark leader). Entered at Rank 10 |

### Subnets Leaving Top 10
| Subnet | Name | May Rank | Notes |
|--------|------|----------|-------|
| **SN92** | TensorClaw | 6 | Decentralized LLM API — dropped out despite strong fundamentals |
| **SN89** | InfiniteHash | 8 | BTC Mining bridge — dropped out despite 286K TAO locked |
| **SN111** | oneoneone | 10 | No identity — locked 250K TAO but nothing shipped |

### Notable On-Chain Changes

| Subnet | Change | Significance |
|--------|--------|-------------|
| **SN116 TaoLend** | Neurons 256→**31** (87.5% drop) ⚠️ | Massive neuron exodus — likely subnet restructuring or miners leaving |
| **SN116 TaoLend** | Locked 89,944→**710,884 TAO** (8x increase) | Despite neuron dump, lockup increased dramatically — large holder accumulating |
| **SN116 TaoLend** | Symbol changed ⵟ→**ъ** (Cyrillic) | Subnet rebrand or owner change |
| **SN116 TaoLend** | TAO emission inflow **8.48M RAO/block** | First time showing TAO inflow from root network |
| **SN116 TaoLend** | Alpha emission inflow **500M RAO/block** | New alpha emission — wasn't present in May |
| **SN80 Dogelayer** | TAO emission 800K→**1.84M RAO/block** (2.3x) | Growing root network confidence |
| **SN80 Dogelayer** | Alpha inflow 251M→**500M RAO/block** (doubled) | Emission model scaled up |
| **SN32 ItsAI** | Burn 500K→**1.19M RAO** (2.4x base) | Above-average burn cost — signals competitive registration |
| **SN40 Chunking** | Alpha inflow dropped to **0** | Was already at 0 in May — confirms no economic activity |

---

## Scorecard Summary

| Rank | Subnet | Name | Category | Total Score | Max | Grade | Conviction |
|------|--------|------|----------|------------|-----|-------|------------|
| 1 | SN116 | TaoLend | DeFi/Lending | **48** | 80 | B | Moderate ↓ |
| 2 | SN80 | Dogelayer | Infrastructure/Mining | **60** | 80 | A- | **High** |
| 3 | SN40 | Chunking | Data/NLP | **24** | 80 | D | Very Low |
| 4 | SN58 | Pending | Unknown | **10** | 80 | F | Pass |
| 5 | SN72 | StreetVision | Computer Vision | **44** | 80 | B- | Moderate |
| 6 | SN42 | Unknown | Unknown | **10** | 80 | F | Pass |
| 7 | SN59 | Babelbit | LLM/Translation | **38** | 80 | C- | Low |
| 8 | SN45 | Talisman AI | AI/LLM | **14** | 80 | F | Pass |
| 9 | SN86 | ⚒ | Unknown | **10** | 80 | F | Pass |
| 10 | SN32 | ItsAI | AI Detection | **34** | 80 | C- | Low |

**Grading Scale:** A+ (72-80) | A (64-71) | B+ (56-63) | B (48-55) | C+ (40-47) | C (32-39) | F (0-31)

**5 of 10 subnets score F. Only 2 (Dogelayer, TaoLend) score B or above. Quality of top-10 remains poor.**

---

## Scoring Framework

Each subnet scored on 8 factors (1-10 each, max 80):

| Factor | Weight | What We Measure |
|--------|--------|-----------------|
| **Market Timing** | 10 | Is now the right time for this subnet's category? |
| **Team Quality** | 10 | Known builders? Open source? Track record? |
| **Tokenomics** | 10 | Emission split, lockup, burn, alpha/TAO flows |
| **Risk/Reward** | 10 | Asymmetric upside vs downside |
| **Liquidity** | 10 | Can we enter/exit alpha positions easily? |
| **Category Fit** | 10 | How well does this fit the broader AI/crypto thesis? |
| **Network Effects** | 10 | Does adoption create compounding value? |
| **Catalyst Proximity** | 10 | Near-term catalysts? |

---

## Detailed Analysis: Each Subnet

---

### 🥇 Rank 1 — SN116: TaoLend

| Field | Value |
|-------|-------|
| **Name** | TaoLend |
| **Category** | DeFi / Lending Protocol |
| **Website** | https://taolend.io |
| **GitHub** | https://github.com/xpenlab/taolend |
| **Contact** | elsieyy@taolend.io |
| **Symbol** | ъ *(changed from ⵟ in May — Cyrillic Hard Sign)* |
| **Neurons** | **31** *(was 256 — 87.5% drop)* ⚠️ |
| **Locked** | **710,884 TAO** *(was 89,944 — 8x increase)* |
| **TAO In Emission** | **8,484,172 RAO/block** *(was 0)* |
| **α In Emission** | 500,000,000 RAO/block *(was 0)* |
| **α Out Emission** | 1,000,000,000 RAO/block *(was 0)* |
| **Registered** | Block 8,294,730 (~Jan 2026) |

#### What It Does
TaoLend is a **decentralized lending protocol** built on Bittensor. Users borrow TAO using subnet alpha tokens as collateral — unlocking TAO liquidity while keeping ALPHA staked. Think of it as Aave/Compound meets Bittensor subnet staking.

#### Key June Developments
⚠️ **This subnet is behaving very strangely.** The neuron count cratered from 256→31 (-87.5%) while lockup surged 8x (90K→711K TAO). The token symbol changed from Tifinagh ⵟ to Cyrillic ъ. New emission flows appeared (8.5M RAO TAO inflow + 500M RAO alpha inflow) that didn't exist in May.

This pattern suggests either: (a) a major subnet restructuring/upgrade, (b) a change in subnet ownership/operator, or (c) a deliberate emission maximization strategy by a large holder. The combination of neuron dump + massive lockup + new emissions is unusual.

#### Scorecard

| Factor | Score | Rationale | Δ May |
|--------|-------|-----------|-------|
| Market Timing | 8 | DeFi on Bittensor still underserved | — |
| Team Quality | 5 | xpenlab GitHub exists; no recent activity visible; symbol change is odd | ↓1 |
| Tokenomics | 6 | 711K TAO locked is strong signal; new emission flows are promising but unexplained | — |
| Risk/Reward | 6 | High upside but opacity about changes is concerning | ↓1 |
| Liquidity | 4 | 31 neurons is very thin; lending protocol needs depth | — |
| Category Fit | 7 | DeFi is natural Bittensor fit | — |
| Network Effects | 7 | More subnets = more collateral options | — |
| Catalyst Proximity | 5 | Emissions appeared but need explanation; where's the product? | ↓2 |

**Total: 48/80 (B) — Moderate Conviction ↓** *(was 52/B+)*

#### Bull Case
- 8x lockup increase shows serious capital commitment
- New TAO emission inflow (8.5M RAO) validates subnet value to root network
- If this is a successful lending protocol launch, it becomes Bittensor's primary DeFi primitive
- 5-10x if it captures TAO lending market

#### Bear Case
- **Neuron exodus is a red flag** — miners fleeing suggests the subnet economics don't work for participants
- Symbol change + ownership questions = possible rug/rebrand
- No publicly visible product update matching the on-chain activity
- Opacity about changes undermines trust
- Could be emission extraction with clever lockup theater

#### Verdict
**WATCH — but with elevated caution.** The fundamentals (lockup, emissions) improved on paper but the neuron crash and unexplained changes are concerning. Need to see a clear product update and community communication within 30 days.

---

### 🥈 Rank 2 — SN80: Dogelayer ⭐ TOP PICK

| Field | Value |
|-------|-------|
| **Name** | Dogelayer |
| **Category** | Infrastructure / PoW Mining Bridge |
| **Website** | https://dogelayer.ai |
| **GitHub** | https://github.com/dogelayer-ai/dogelayer |
| **Contact** | dev@dogelayer.ai |
| **Symbol** | ى |
| **Neurons** | 245 *(was 243)* |
| **Locked** | 219,601 TAO *(stable)* |
| **TAO In Emission** | **1,837,521 RAO/block** *(was 800,582 — 2.3x)* |
| **α In Emission** | **500,000,000 RAO/block** *(was 250,750,730 — doubled)* |
| **α Out Emission** | 1,000,000,000 RAO/block *(stable)* |
| **Registered** | Block 7,151,800 (~Apr 2026) |

#### What It Does
Dogelayer bridges **Scrypt miners (LTC/DOGE) to Bittensor**. Through merged mining, traditional crypto miners earn Alpha tokens via subnet validation while mining LTC/DOGE. Dual reward system: LTC/DOGE earnings + Bittensor alpha tokens.

#### Key June Developments
Strong growth across all emission metrics. TAO inflow up 2.3x, alpha inflow doubled. This is the **only subnet in the top 10 with consistent TAO emission inflow from the root network** — a clear signal thatDogelayer's validators are seen as productive by the root consensus.

#### Scorecard

| Factor | Score | Rationale | Δ May |
|--------|-------|-----------|-------|
| Market Timing | 9 | LTC/DOGE mining mature; bridge timing perfect | — |
| Team Quality | 8 | Open source, active, clear docs; GitHub growing | ↑1 |
| Tokenomics | 8 | TAO emission 2.3x, alpha doubled, 220K locked | ↑1 |
| Risk/Reward | 7 | Mining infrastructure limits downside | — |
| Liquidity | 6 | Mining pool model has natural liquidity | — |
| Category Fit | 8 | Infrastructure = Bittensor core thesis | — |
| Network Effects | 8 | More miners = more hashrate = flywheel proven | ↑1 |
| Catalyst Proximity | 7 | LTC halvening 2027 approaching; growing emissions | — |

**Total: 60/80 (A-) — High Conviction** *(was 58/A-)*

#### Bull Case
- **Only subnet with growing TAO emission inflow** in top 10 — root network validation is the strongest on-chain signal
- Dual reward model (LTC/DOGE + TAO/alpha) is unique and compelling
- 10-50x if it captures meaningful LTC/DOGE hashrate
- LTC halvening 22027 will push miners to seek alternative revenue

#### Bear Case
- Centralized proxy architecture (AWS ELB) remains a single point of failure
- Competition from InfiniteHash (SN89) for mining hashrate
- LTC/DOGE price dependency
- Custodial withdrawal system (1-3 days)

#### Wider World Fit
- BTC/AI narrative is dominant; DogeLayer bridges old PoW to new AI economy
- Post-halvening miner economics across all PoW chains will drive demand for merged mining
- Most underrated infrastructure play in Bittensor

---

### 🥉 Rank 3 — SN40: Chunking

| Field | Value |
|-------|-------|
| **Name** | Chunking |
| **Category** | Data Processing / NLP |
| **GitHub** | https://github.com/VectorChat/chunking_subnet |
| **Symbol** | ן |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **TAO In Emission** | 0 |
| **α In Emission** | 0 *(dropped from 0 — no change)* |
| **Registered** | Block 3,372,582 (~Jun 2024) |

#### What It Does
Text chunking subnet — breaks large documents into smaller pieces for LLM processing. A fundamental NLP task (RAG preprocessing, embedding pipelines).

#### Key June Developments
No changes. Still 0 locked, 0 TAO inflow, 0 alpha inflow. This subnet is a pure emission extraction play that has existed since June 2024 with zero economic activity.

#### Scorecard

| Factor | Score | Rationale | Δ May |
|--------|-------|-----------|-------|
| Market Timing | 3 | Text commoditized; any LLM chunks text | — |
| Team Quality | 3 | Anonymous; VectorChat GitHub | — |
| Tokenomics | 2 | Zero lockup; zero flows | — |
| Risk/Reward | 2 | No asymmetry | — |
| Liquidity | 2 | Thin | — |
| Category Fit | 4 | Useful but not differentiating | — |
| Network Effects | 2 | None | — |
| Catalyst Proximity | 4 | Open source but not differentiated | — |

**Total: 24/80 (D) — Very Low Conviction** *(was 26/D)*

#### Verdict
**Pass.** 2 years on chain, zero economic activity, zero lockup. LangChain, LlamaIndex, and every LLM framework chunks text for free. No moat.

---

### Rank 4 — SN58: Pending/No Identity

| Field | Value |
|-------|-------|
| **Name** | Pending (no identity) |
| **Category** | Unknown |
| **Symbol** | خ |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **Registered** | Block 4,367,003 (~Sep 2024) |

#### What It Does
**Unknown.** Registered 9+ months ago, no identity, no website, no GitHub, no contact. Zero economic activity.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| All factors | 1-2 | No identity after 9 months = abandonment or emission grab |

**Total: 10/80 (F) — Pass**

#### Verdict
**Pass.** A subnet that can't set its identity in 9 months isn't worth analyzing.

---

### Rank 5 — SN72: StreetVision by NATIX

| Field | Value |
|-------|-------|
| **Name** | StreetVision |
| **Category** | Computer Vision / Physical AI / Mapping |
| **Website** | https://www.natix.network |
| **GitHub** | https://github.com/natixnetwork/streetvision-subnet |
| **Symbol** | ق |
| **Neurons** | 256 (max) |
| **Locked** | 191,341 TAO *(stable)* |
| **TAO In Emission** | 0 |
| **Registered** | Block 5,064,327 (~Nov 2024) |

#### What It Does
Decentralized computer vision for **roadwork/construction site detection** via NATIX's Internet of Cameras. Miners run binary classifiers; validators challenge with real + synthetic images. Dynamic 90-day model validity with decay.

#### Key June Developments
No significant changes. Lockup stable. Identity description updated slightly from May: *"Powered by NATIX's Internet of Cameras, StreetVision is advancing autonomous driving, Physical AI, and map-making."* Expanded positioning beyond just roadwork.

#### Scorecard

| Factor | Score | Rationale | Δ May |
|--------|-------|-----------|-------|
| Market Timing | 7 | Physical AI remains hot | — |
| Team Quality | 6 | NATIX known; active GitHub | — |
| Tokenomics | 5 | 191K locked; no TAO inflow | — |
| Risk/Reward | 6 | Real use case; narrow focus | — |
| Liquidity | 4 | Alpha liquidity thin | — |
| Category Fit | 7 | CV + Physical AI = strong | — |
| Network Effects | 5 | Camera network growing but nascent | — |
| Catalyst Proximity | 5 | Partnership potential but slow burn | ↓1 |

**Total: 44/80 (B-) — Moderate Conviction** *(was 46/B)*

#### Bull Case
- NATIX's camera network provides a real hardware moat
- Expandable from roadwork → traffic → disaster → agriculture monitoring
- "Decentralized Planet Labs" for ground-level Physical AI

#### Bear Case
- Narrow use case limits TAM
- Google Street View, municipal cameras already do this
- No TAO emission inflow after 6+ months

---

### Rank 6 — SN42: Unknown

| Field | Value |
|-------|-------|
| **Name** | Unknown |
| **Category** | Unknown |
| **Symbol** | ס |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **Registered** | Block 3,613,591 (~Jul 2024) |

#### Scorecard
| Factor | Score | Rationale |
|--------|-------|-----------|
| All factors | 1-2 | No identity, 2+ years old, zero lockup, nothing shipped |

**Total: 10/80 (F) — Pass**

#### Verdict
**Pass.** Two years, nothing.

---

### Rank 7 — SN59: Babelbit 🆕

| Field | Value |
|-------|-------|
| **Name** | Babelbit |
| **Category** | LLM / Translation Services |
| **Website** | https://babelbit.ai |
| **GitHub** | https://github.com/babelbit/babelbit_subnet |
| **Contact** | mk@babelbit.ai |
| **Symbol** | د |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **TAO In Emission** | 0 |
| **Registered** | Block 4,401,833 (~Sep 2024) |

#### What It Does
**"Harnessing the predictive power of LLMs to deliver state-of-the-art translation services."** Uses LLMs for translation within the Bittensor framework. Miners presumably compete on translation quality; validators evaluate outputs.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 6 | Machine translation is massive; DeepL/Google compete here |
| Team Quality | 4 | Contact provided; GitHub exists; limited track record |
| Tokenomics | 2 | Zero lockup; no emission inflows; pure alpha |
| Risk/Reward | 4 | Commodity service; zero moat vs Google/DeepL |
| Liquidity | 3 | New to top 10; likely thin |
| Category Fit | 5 | LLM-based translation fits Bittensor thesis |
| Network Effects | 3 | Competing against trillion-dollar translation APIs |
| Catalyst Proximity | 7 | Already registered 9 months; should ship soon |

**Total: 38/80 (C-) — Low Conviction**

#### Bull Case
- Translation is a proven use case for LLMs with massive TAM
- If it achieves DeepL-level quality, there's a market for uncensored/decentralized translation
- First-mover in translation-specific subnet

#### Bear Case
- Google Translate, DeepL, and every LLM API offers translation for free
- Zero lockup suggests team confidence is low
- No TAO emission inflow after 9 months = root network doesn't see value
- **Completely commoditized task**

#### Verdict
**Low-conviction watch.** Entered top 10 due to pruning rank mechanics (age-based), not fundamentals. Needs TAO inflow or significant lockup to be taken seriously.

---

### Rank 8 — SN45: Talisman AI 🆕

| Field | Value |
|-------|-------|
| **Name** | Talisman AI |
| **Category** | AI / LLM |
| **Website** | https://ai.talisman.xyz |
| **GitHub** | https://github.com/Team-Rizzo/talisman-ai |
| **Contact** | tai@rizzo.network |
| **Symbol** | פ |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **Registered** | Block 3,633,154 (~Jul 2024) |

#### What It Does
**Unknown.** On-chain identity has a logo (Reddit-style community icon) but no description. The subnet name "Talisman AI" and website `ai.talisman.xyz` suggest an AI/LLM product, but there's no description, no contact, and no documented purpose. GitHub exists (Team-Rizzo organization).

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| All factors | 1-3 | No description; registered 11 months; zero lockup; vague |

**Total: 14/80 (F) — Pass**

#### Verdict
**Pass.** Cannot evaluate what doesn't describe itself. Zero lockup after 11 months suggests low commitment.

---

### Rank 9 — SN86: ⚒

| Field | Value |
|-------|-------|
| **Name** | ⚒ (no name) |
| **Category** | Unknown |
| **Symbol** | ᚳ |
| **Neurons** | 256 (max) |
| **Locked** | **208,695 TAO** *(3rd highest in top 10)* |
| **Registered** | Block 6,914,378 (~Mar 2026) |

#### What It Does
**Minimal information.** Description: *"Methodical. Strong foundation. And...Sr Data Scientist, 4th team member, onboard."* No website, no GitHub. Despite having the 3rd-highest lockup in the top 10 (209K TAO), there's zero public-facing product.

#### Scorecard

| Factor | Score | Rationale | Δ May |
|--------|-------|-----------|-------|
| All | 1 | No product, no website, no GitHub, vague description | — |

**Total: 10/80 (F) — Pass** *(was 10/F)*

#### Verdict
**Pass.** High lockup is curious and suggests commitment, but there's nothing to evaluate. If this team ships something, the lockup signals they're serious — but today, there's nothing to analyze.

---

### Rank 10 — SN32: ItsAI 🆕

| Field | Value |
|-------|-------|
| **Name** | ItsAI |
| **Category** | AI Text Detection |
| **Website** | https://its-ai.org/en |
| **GitHub** | https://github.com/It-s-AI/llm-detection |
| **Contact** | support@its-ai.org |
| **Symbol** | ח |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **Burn** | **1,192,808 RAO** *(2.4x base rate of 500K)* |
| **Registered** | Block 2,515,294 (~Mar 2024) |

#### What It Does
**"Focused on high-quality AI detection for texts. Recognised as the most accurate AI detector by MGTD benchmark."** ItsAI detects whether text was generated by AI — a rapidly growing need as AI-generated content floods the internet. MGTD benchmark recognition is a genuine credibility signal.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 7 | AI detection is exploding; universities, publishers, employers all need this |
| Team Quality | 4 | GitHub exists; MGTD benchmark recognition; contact provided; limited history |
| Tokenomics | 2 | Zero lockup; no emission inflows; 2.4x burn is notable but not fundamental |
| Risk/Reward | 4 | Real market need but competing with Turnitin, GPTZero, etc. |
| Liquidity | 3 | New to top 10; likely thin |
| Category Fit | 5 | AI detection fits Bittensor thesis but isn't differentiated |
| Network Effects | 3 | Detection gets better with more data but moats are unclear |
| Catalyst Proximity | 5 | MGTD recognition is credible; needs enterprise/education partnerships |

**Total: 34/80 (C-) — Low Conviction**

#### Bull Case
- AI content detection is a **$1B+ market** (Turnitin, GPTZero, Originality.ai all growing)
- MGTD benchmark recognition provides credibility
- Universities, publishers, and employers are mandated to detect AI content
- Zero lockup at this stage is normal for older subnets (registered 2024)

#### Bear Case
- **Turnitin, GPTZero, Originality.ai** are already dominant; decentralized detection has no clear advantage
- Zero lockup after 2+ years is concerning
- No TAO emission inflow = root network sees limited value
- AI detection is an arms race; miners need continuous model updates
- Regulatory landscape for AI detection is unclear

#### Verdict
**Low-conviction watch.** The MGTD benchmark credential is the most interesting signal in this subnet. But zero lockup after 2 years and no TAO inflow suggest limited execution. If the team lands an education sector contract, reassess.

---

## Portfolio View

### Graded Subnets Only (A-C)

| Subnet | Grade | Verdict | Suggested Allocation of Bittensor Research Budget |
|--------|-------|---------|---------------------------------------------------|
| **SN80 Dogelayer** | A- | **Conviction — Top Pick** | 40% |
| **SN116 TaoLend** | B | **Watch (with caution)** | 20% |
| **SN72 StreetVision** | B- | **Watch** | 15% |
| **SN59 Babelbit** | C- | **Weak Watch** | 10% |
| **SN32 ItsAI** | C- | **Weak Watch** | 10% |
| **Exploration Budget** | — | **New/unknown** | 5% |

### The Anomalies

| Subnet | Status | Action |
|--------|--------|--------|
| SN116 TaoLend | ⚠️ Neuron crash + 8x lockup + symbol change | **Monitor closely** — something major happened; could be restructuring or red flag |
| SN86 ⚒ | No identity, no GitHub, 209K TAO locked | Watch — high lockup is curious; if team ships, reassess |
| SN40 Chunking | 2 years old, zero lockup | Monitor for identity change |
| SN58 Pending | 9+ months, no identity | Pass until identified |
| SN42 Unknown | 2+ years, nothing | Pass |
| SN45 Talisman AI | 11 months, no description | Pass |

---

## Key Takeaways

### What's Actually Interesting

Out of 10 top subnets by emission priority, **only 2 have genuine fundamentals worth tracking:**

1. **Dogelayer (SN80)** — Bridges real-world mining to Bittensor. THE ONLY subnet with growing TAO emission inflow. Dual reward model validated by root network. Escalating conviction.
2. **TaoLend (SN116)** — First-mover in TAO lending, but June data is contradictory (neuron crash vs. 8x lockup increase). Need clarity.

StreetVision, ItsAI, and Babelbit are **borderline** — real concepts but no TAO inflow to validate them.

### What's Noise — And It's Getting Worse

**Half the top 10 (5/10) are emission extraction plays** with no product, no team visibility, and zero economic value. This is unchanged from May. The pruning rank system continues to reward age and registration over actual utility.

Three subnets that were in May's top 10 dropped out (TensorClaw, InfiniteHash, oneoneone). Two of those (TensorClaw, InfiniteHash) had *better fundamentals* than most of the new entrants. This is the pruning rank paradox playing out in real-time.

### The Pruning Priority Paradox — Confirmed

The subnets ranked highest for emission priority are mostly the **newest** ones — not the most valuable. TensorClaw (SN92) had:
- 270K TAO locked (2nd highest in May's top 10)
- 100x burn rate (highest commitment signal)
- A live Business API product with real commercial traffic
- Active GitHub commits (8 hours before the May report)

...and it dropped out of the top 10 in June due to EMA price mechanics. Meanwhile, Babelbit (zero lockup, no product description, commoditized task) entered at Rank 7. This is the structural flaw in emission-based ranking.

### Monthly Tracking Recommendations

1. **Watch SN116 closely** — Neuron crash + lockup surge + symbol change needs explanation within 30 days
2. **SN80 TAO inflow growth** — Continued growth validates the thesis; any decline would be concerning
3. **Monitor SN32 ItsAI** — MGTD benchmark recognition is credible; look for enterprise/education partnerships
4. **Monitor SN86** — 209K TAO locked with no product suggests building in stealth; if they reveal, it could be significant
5. **Ignore SN40, SN42, SN45, SN58** — Dead weight
6. **Watch for TensorClaw and InfiniteHash re-entry** — Both dropped out despite strong fundamentals

---

## Raw On-Chain Data

From Finney RPC, queried June 1, 2026. Block: 8,310,526.

| Subnet | Name | Symbol | Neurons | Locked (τ) | Burn (RAO) | TAO In (RAO/blk) | α In (RAO/blk) | α Out (RAO/blk) | Reg Block |
|--------|------|--------|---------|-----------|-----------|-----------------|---------------|----------------|----------|
| SN116 | TaoLend | ъ | **31** | **710,884** | 500,000 | **8,484,172** | **500,000,000** | 1,000,000,000 | 8,294,730 |
| SN80 | Dogelayer | ى | 245 | 219,601 | 500,000 | **1,837,521** | **500,000,000** | 1,000,000,000 | 7,151,800 |
| SN40 | Chunking | ן | 256 | 0 | 500,000 | 0 | 0 | 1,000,000,000 | 3,372,582 |
| SN58 | Pending | خ | 256 | 0 | 500,000 | 0 | 0 | 1,000,000,000 | 4,367,003 |
| SN72 | StreetVision | ق | 256 | 191,341 | 500,000 | 0 | 0 | 1,000,000,000 | 5,064,327 |
| SN42 | Unknown | ס | 256 | 0 | 500,000 | 0 | 0 | 1,000,000,000 | 3,613,591 |
| SN59 | Babelbit | د | 256 | 0 | 500,000 | 0 | 0 | 1,000,000,000 | 4,401,833 |
| SN45 | Talisman AI | פ | 256 | 0 | 500,000 | 0 | 0 | 1,000,000,000 | 3,633,154 |
| SN86 | ⚒ | ᚳ | 256 | 208,695 | 500,000 | 0 | 0 | 1,000,000,000 | 6,914,378 |
| SN32 | ItsAI | ח | 256 | 0 | **1,192,808** | 0 | 0 | 1,000,000,000 | 2,515,294 |

**Unit note:** Bittensor uses RAO (1 TAO = 10⁹ RAO). All emission values are per-block.

---

## Comparison Data: May vs June

| Field | May 2026 | June 2026 | Δ |
|-------|----------|-----------|---|
| TAO Price | $277.20 | $250.59 | -9.6% |
| Market Cap | $3.03B | $2.74B | -9.6% |
| 24h Volume | $259.06M | $173.57M | -33.0% |
| Total Subnets | 128 | 129 | +1 |
| Block Emission | 1B RAO/blk | 1B RAO/blk | No change |
| Total Issuance | ~10.95B RAO | ~10.97B RAO | +20M RAO |
| Top 10 Avg Score | 30.0 | 28.2 | -1.8 (worse) |

### Month-over-Month Subnet Metrics

| Subnet | Name | May→June Neurons | May→June Locked | May→June TAO In | May→June α In |
|--------|------|------------------|-----------------|-----------------|---------------|
| SN116 | TaoLend | 256→**31** ⚠️ | 90K→**711K** | 0→**8.48M** | 0→**500M** |
| SN80 | Dogelayer | 243→245 | 220K→220K | 801K→**1.84M** | 251M→**500M** |
| SN40 | Chunking | 256→256 | 0→0 | 0→0 | 0→0 |
| SN58 | Pending | 256→256 | 0→0 | 0→0 | 0→0 |
| SN72 | StreetVision | 256→256 | 191K→191K | 0→0 | 0→0 |
| SN42 | Unknown | 256→256 | 0→0 | 0→0 | 0→0 |

*(SN59, SN45, SN32 are new to top 10; SN92, SN89, SN111 dropped out)*

---

## Sources

| Source | URL |
|--------|-----|
| Taostats (Rankings) | https://taostats.io/subnets |
| Taostats (Tokenomics) | https://taostats.io/tokenomics |
| Finney RPC | wss://entrypoint-finney.opentensor.ai:443 |
| TaoLend | https://taolend.io / https://github.com/xpenlab/taolend |
| Dogelayer | https://dogelayer.ai / https://github.com/dogelayer-ai/dogelayer |
| Chunking | https://github.com/VectorChat/chunking_subnet |
| StreetVision | https://www.natix.network / https://github.com/natixnetwork/streetvision-subnet |
| Babelbit | https://babelbit.ai / https://github.com/babelbit/babelbit_subnet |
| Talisman AI | https://ai.talisman.xyz / https://github.com/Team-Rizzo/talisman-ai |
| ItsAI | https://its-ai.org/en / https://github.com/It-s-AI/llm-detection |
| MGTD Benchmark | MGTD AI Text Detection Benchmark |

---

*Previous report: [May 2026](top10-emission-may2026.md)*
*Next report: July 2026 (automated via cron)*