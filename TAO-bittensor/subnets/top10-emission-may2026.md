# Top 10 Bittensor Subnets by Emission Priority — Fundamentals Report
## May 2026

> **Date:** May 27, 2026
> **Data Sources:** taostats.io (pruning rank, EMA), Bittensor Finney RPC (emission, neuron count, lockup, identity), GitHub repos (fundamentals)
> **Researcher:** Spock for CryptoSI Research
>
> *Ranked by pruning rank from taostats.io (Rank 1 = highest emission priority). Each subnet scored on 8 factors (max 80 points) using the CryptoSI opportunity scorecard framework.*

---

## Market Context (May 2026)

| Metric | Value |
|--------|-------|
| **TAO Price** | $277.20 |
| **Market Cap** | $3.03B |
| **24h Volume** | $259.06M |
| **Circulating Supply** | 10,946,323 TAO (52.13%) |
| **Block Reward** | 0.5 TAO/block (post-H1 halvening, Dec 15 2025) |
| **Daily Issuance** | ~3,600 TAO/day |
| **Next Halvening** | December 12, 2029 (H2 → 0.25) |
| **Total Subnets** | 128 |

---

## Scorecard Summary

| Rank | Subnet | Name | Category | Total Score | Max | Grade | Conviction |
|------|--------|------|----------|------------|-----|-------|------------|
| 1 | SN116 | TaoLend | DeFi/Lending | **52** | 80 | B+ | Moderate |
| 2 | SN80 | Dogelayer | Infrastructure/Mining | **58** | 80 | A- | **High** |
| 3 | SN40 | Chunking | Data/NLP | **26** | 80 | D | Very Low |
| 4 | SN58 | (Pending) | Unknown | **12** | 80 | F | Pass |
| 5 | SN72 | StreetVision (NATIX) | Computer Vision | **46** | 80 | B | Moderate |
| 6 | SN92 | TensorClaw | LLM Inference | **54** | 80 | A- | Moderate |
| 7 | SN42 | Unknown | Unknown | **10** | 80 | F | Pass |
| 8 | SN89 | InfiniteHash | BTC Mining | **48** | 80 | B | Moderate |
| 9 | SN86 | (Unnamed) | Unknown | **10** | 80 | F | Pass |
| 10 | SN111 | oneoneone | Unknown | **16** | 80 | F | Pass |

**Grading Scale:** A+ (72-80) | A (64-71) | B+ (56-63) | B (48-55) | C (40-47) | D (32-39) | F (0-31)

**3 subnets (SN40, SN42, SN58) have no effective identity — they're essentially nameless. 2 more (SN86, SN111) have minimal info.**

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
| **Symbol** | ⵟ (Tifinagh) |
| **Neurons** | 256 (max) |
| **Locked** | 89,944 TAO |
| **TAO In Emission** | 0 |
| **Registered** | ~Jan 2026 |

#### What It Does
TaoLend is a **decentralized lending protocol** built on Bittensor. It allows users to lend TAO with confidence while borrowers secure loans using subnet ALPHA tokens as collateral. The key innovation is unlocking TAO liquidity while keeping ALPHA staked within subnets — improving both capital efficiency and network security.

**Think of it as:** Aave/Compound meets Bittensor subnet staking. Instead of standard DeFi collateral, you use subnet alpha tokens (which are otherwise illiquid) as collateral for TAO loans.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 8 | DeFi on Bittensor is massively underserved; TAO holders need yield infrastructure NOW |
| Team Quality | 6 | New team (xpenlab), GitHub exists but limited history; email contact provided |
| Tokenomics | 6 | 89K TAO locked is modest for a DeFi protocol; no TAO emission inflow yet |
| Risk/Reward | 7 | High upside if it becomes the primary TAO lending venue; low downside at current stage |
| Liquidity | 4 | Very new; alpha token liquidity likely thin; need to bootstrap both sides |
| Category Fit | 7 | DeFi is a natural fit for Bittensor; TAO needs lending/borrowing markets |
| Network Effects | 7 | More subnets = more alpha collateral options = stronger protocol |
| Catalyst Proximity | 7 | v1 launch imminent (website is live, app in development) |

**Total: 52/80 (B+) — Moderate Conviction**

#### Bull Case
- **Thesis:** Becomes the primary lending layer for TAO and subnet alpha tokens
- **Driver:** 128 subnets generating alpha tokens = massive collateral surface. Right now there's no way to use these tokens productively. TaoLend unlocks that.
- **Comparable:** Aave on Ethereum — became a top-5 DeFi protocol by being the first mover in permissionless lending
- **Catalyst:** Protocol launch; integration with major subnet alpha tokens; TAO staking derivative market
- **Upside:** 5-10x if it captures even 10% of TAO lending market

#### Bear Case
- **Risk:** Bittensor DeFi may be too niche — subnet alpha tokens are volatile and may not hold value as collateral
- **Competition:** Could be displaced by Render, Akash, or other DeFi protocols expanding into Bittensor
- **Collateral risk:** If subnet alpha tokens crash, loans become undercollateralized — bad debt accumulates
- **Regulatory:** DeFi lending protocols face increasing regulatory scrutiny
- **Downside:** Protocol fails to gain traction; becomes another ghost app in a sea of subnet names

#### Wider World Fit
- **Macro:** DeFi TVL is recovering post-bear market; real yield is the narrative
- **Bitterwise:** Bitterwise needs TAO liquidity infrastructure for its own treasury management
- **Competitive:** No direct competitor for TAO-specific lending on Bittensor YET
- **Threat:** If a major DeFi protocol (Aave, Compound) integrates TAO, TaoLend's moat evaporates

---

### 🥈 Rank 2 — SN80: Dogelayer ⭐ TOP PICK

| Field | Value |
|-------|-------|
| **Name** | DogeLayer |
| **Category** | Infrastructure / PoW Mining Bridge |
| **Website** | https://dogelayer.ai |
| **GitHub** | https://github.com/dogelayer-ai/dogelayer |
| **Contact** | dev@dogelayer.ai |
| **Symbol** | ى (Arabic Alif Maqsura) |
| **Neurons** | 243 (near max) |
| **Locked** | 219,601 TAO |
| **TAO In Emission** | 800,582 RAO/block (**ONLY subnet with TAO inflow**) |
| **α In Emission** | 250,750,730 RAO (~0.25 τ/block) |
| **Registered** | ~Apr 2026 |

#### What It Does
Dogelayer is the **first mining pool enabling Scrypt miners (LTC/DOGE) to join Bittensor**. Through merged mining technology, traditional crypto miners can earn Alpha tokens through subnet validation while mining LTC/DOGE. It creates a dual reward system:
1. **Direct Mining Rewards:** LTC/DOGE earnings from actual mining (collected and redistributed by platform)
2. **Alpha Token Rewards:** Bittensor subnet tokens for registered miners based on hashpower contribution

**Think of it as:** NiceHash meets Bittensor. It bridges traditional crypto mining into the AI/decentralized compute narrative.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 9 | LTC/DOGE mining is mature; bringing hashrate to Bittensor is perfect timing |
| Team Quality | 7 | Full open-source repo with Docker setup, AWS infrastructure, clear docs |
| Tokenomics | 7 | 219K TAO locked; meaningful emission inflows (τ + α); dual reward mechanism |
| Risk/Reward | 7 | Upside from hashrate bridge; downside limited by physical mining infrastructure |
| Liquidity | 6 | Mining pool model has natural liquidity; alpha token needs to develop |
| Category Fit | 8 | Infrastructure is Bittensor's core thesis; bridging PoW is genuinely novel |
| Network Effects | 7 | More miners = more hashrate = more rewards = more miners (flywheel) |
| Catalyst Proximity | 7 | Live and operational; LTC halvening (Aug 2027) could drive miner interest |

**Total: 58/80 (A-) — High Conviction**

#### Bull Case
- **Thesis:** Becomes the primary bridge between traditional PoW mining and Bittensor's incentive layer
- **Dogecoin + Litecoin hashrate is enormous** — even capturing 1% would be transformative for Bittensor
- **Dual rewards are unique:** Miners earn both LTC/DOGE AND TAO/alpha — no other subnet offers this
- **TAO inflow proves the economy works:** The root network is literally sending TAO here, meaning validators see real value
- **Catalyst:** LTC halvening 2027 (miners need new revenue streams); DOGE momentum cycle; enterprise mining partnerships
- **Upside:** 10-50x if it captures meaningful LTC/DOGE hashrate

#### Bear Case
- **Risk:** Centralized proxy architecture (AWS ELB) is a single point of failure — not truly decentralized
- **Competition:** Other mining-focused subnets (InfiniteHash for BTC) could fragment the market
- **Dependency:** Relies on LTC/DOGE price staying high enough to incentivize miners
- **Platform risk:** Manual withdrawal system (1-3 business days) is centralized and custodial
- **Downside:** Mining profitability drops; miners exit; alpha token value crashes

#### Wider World Fit
- **Macro:** Bitcoin/LTC halvening cycles drive miner cost crises — Dogelayer offers an alternative revenue stream
- **Bridging narrative:** One of the few subnets that brings non-Bittensor users/crypto-natives into the ecosystem
- **Competitive:** InfiniteHash (SN89) does BTC; DogeLayer owns LTC/DOGE. Complementary, not competitive
- **Threat:** If LTC/DOGE prices collapse, the value proposition to miners disappears

---

### 🥉 Rank 3 — SN40: Chunking

| Field | Value |
|-------|-------|
| **Name** | Chunking |
| **Category** | Data Processing / NLP |
| **Website** | (none) |
| **GitHub** | https://github.com/VectorChat/chunking_subnet |
| **Symbol** | ן (Hebrew Nun Sofit) |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **Registered** | ~Jun 2024 |

#### What It Does
Chunking is a **text processing/chunking subnet** — it breaks down large documents into smaller, manageable pieces for LLM processing. This is a fundamental NLP task: before you can feed documents to an embedding model or RAG pipeline, you need to split them intelligently.

**Think of it as:** The "preprocessor subnet" — it does the boring but essential work of chunking text for downstream AI tasks.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 3 | Text commoditized; any LLM can chunk text; zero moat |
| Team Quality | 3 | Anonymous; no contact info; VectorChat GitHub |
| Tokenomics | 2 | Zero locked TAO; no emission inflows; pure alpha extraction |
| Risk/Reward | 2 | No upside asymmetry; this is a commodity task |
| Liquidity | 2 | Likely thin |
| Category Fit | 4 | Useful but not differentiating |
| Network Effects | 2 | No network effects — chunking is stateless |
| Catalyst Proximity | 4 | Open source; could be integrated but isn't differentiated |

**Total: 26/80 (D) — Very Low Conviction**

#### Bull Case
- **Thesis:** Essential infrastructure for RAG/AI pipelines; always needed
- **Reality check:** This is like investing in a company that makes compress utility — technically necessary but no pricing power

#### Bear Case
- **Risk:** Any centralized LLM API can chunk text for free. Zero competitive advantage.
- **Zero lockup** suggests even the owner isn't committed
- **Competition:** LangChain, LlamaIndex, and every LLM framework has free chunking built in
- **Verdict:** **Pass.** Emissions-only play with no fundamentals

#### Wider World Fit
- **Macro:** RAG is growing but the tooling is free/open-source
- **No defensibility:** Can be replicated by anyone with 10 lines of Python

---

### Rank 4 — SN58: (Pending/No Identity)

| Field | Value |
|-------|-------|
| **Name** | **Pending** (no identity set) |
| **Category** | Unknown |
| **Symbol** | خ (Arabic Kha) |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **Registered** | ~Sep 2024 |

#### What It Does
**Unknown.** The subnet has registered on-chain but hasn't set its identity, description, website, or contact info. It's essentially a ghost subnet — it exists on the chain for emission purposes but has no public-facing presence.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 1 | Unknown = unknowable |
| Team Quality | 1 | No identity = anonymous/uncommitted |
| Tokenomics | 3 | Zero lockup; standard emission |
| Risk/Reward | 1 | Can't assess |
| Liquidity | 1 | Unknown |
| Category Fit | 2 | Unknown |
| Network Effects | 1 | None visible |
| Catalyst Proximity | 2 | No info |

**Total: 12/80 (F) — Pass**

#### Verdict
**Pass.** A subnet that can't be bothered to set its identity in a competitive emission environment is not worth analyzing. Either it's an abandoned registration or a deliberate emission grab. Either way — pass.

---

### Rank 5 — SN72: StreetVision by NATIX

| Field | Value |
|-------|-------|
| **Name** | StreetVision |
| **Category** | Computer Vision / Physical AI / Mapping |
| **Website** | https://www.natix.network |
| **GitHub** | https://github.com/natixnetwork/streetvision-subnet |
| **Discord** | https://discord.com/channels/799672011265015819/1349122541754515538 |
| **Symbol** | ق (Arabic Qaf) |
| **Neurons** | 256 (max) |
| **Locked** | 191,341 TAO |
| **Registered** | ~Nov 2024 |

#### What It Does
StreetVision is a **decentralized computer vision subnet** for image classification and object detection, specifically focused on **roadwork/construction site detection**. Powered by NATIX's "Internet of Cameras" network:

- **Miners** run binary classifiers (roadwork vs. no roadwork) and submit models to HuggingFace
- **Validators** challenge miners with real + synthetic images from diverse sources
- **Unique feature:** Dynamic reward system where model submissions are valid for 90 days, then decay — incentivizing continuous improvement

**Think of it as:** A decentralized physical AI network using real-world camera data to detect infrastructure changes. Could be used by governments, construction companies, and mapping services.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 7 | Physical AI is a massive trend; camera networks for infrastructure monitoring is real |
| Team Quality | 6 | NATIX is a known entity; 1,046 commits on GitHub; active development |
| Tokenomics | 5 | 191K TAO locked; no TAO inflow; standard emission |
| Risk/Reward | 6 | Real use case but narrow (roadwork detection); expansion potential to other CV tasks |
| Liquidity | 4 | Newish subnet; alpha liquidity TBD |
| Category Fit | 7 | Computer vision + physical AI = strong Bittensor use case |
| Network Effects | 5 | More cameras = better data = better models; but network is nascent |
| Catalyst Proximity | 6 | Partnership potential with city governments and mapping companies |

**Total: 46/80 (B) — Moderate Conviction**

#### Bull Case
- **Thesis:** Decentralized physical AI for infrastructure monitoring — a massive addressable market
- **NATIX's camera network** gives it a real hardware moat that pure software subnets lack
- **Expandable:** Could expand from roadwork to traffic monitoring, disaster detection, agricultural monitoring
- **Comparable:** Could become the "decentralized Planet Labs" for ground-level physical AI
- **Catalyst:** Government contracts; integration with Google Maps/Waze; smart city initiatives

#### Bear Case
- **Risk:** Narrow use case (roadwork detection) limits total addressable market
- **Competition:** Google Street View, municipal camera networks, and centralized AI already do this
- **Camera network dependency:** If NATIX's camera network doesn't grow, the subnet starves
- **Validator data quality:** If validators don't maintain diverse/high-quality test data, mining becomes gaming
- **Downside:** Remains a niche application; alpha token value stagnates

#### Wider World Fit
- **Macro:** Physical AI is one of the hottest themes in tech (2026); Jensen Huang and Sam Altman both talk about it
- **Smart cities:** $2.5T market by 2030; StreetVision could be a piece of that
- **Competitive:** No direct competitor on Bittensor for physical-world computer vision
- **Threat:** If major mapping companies (Google, TomTom) build this in-house, the decentralized version becomes redundant

---

### Rank 6 — SN92: TensorClaw

| Field | Value |
|-------|-------|
| **Name** | TensorClaw |
| **Category** | LLM Inference / API Gateway |
| **Website** | https://www.tensorclaw.ai |
| **GitHub** | https://github.com/tensorclaw/tensorclaw |
| **Contact** | support@tensorclaw.ai |
| **Discord** | https://discord.gg/5Qsqcttq |
| **Symbol** | ᚂ (Runic Laguz) |
| **Neurons** | 256 (max) |
| **Locked** | 269,838 TAO |
| **Burn** | 50,000 RAO (100× normal) |
| **Registered** | ~Apr 2026 |

#### What It Does
TensorClaw is a **decentralized LLM inference subnet** that aggregates high-quality LLM API nodes globally. It provides a unified, highly available, load-balanced API service. Key innovations:

- **Business API model:** Real commercial API traffic is routed through miners — miners handling MORE real requests earn MORE TAO
- **Centralized WebSocket Router (AICenter):** Miners don't need public IPs or DDoS protection
- **Anti-cheat:** Active inference probes (5-token micro-prompts); miners that don't respond in 8 seconds get banned
- **Scoring:** 90% Business Score (real traffic) + 10% Base Score (model quality)

**Think of it as:** decentraland meets Cloudflare — a decentralized API gateway for LLM inference with real commercial traffic.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 8 | LLM inference is the most in-demand AI service; decentralized API is hot |
| Team Quality | 7 | Very active (commits 8 hours ago); real product; open-source; responsive |
| Tokenomics | 7 | 270K TAO locked (highest in sub-50K burn); 100x burn suggests demand |
| Risk/Reward | 7 | High ceiling if Business API gains traction; limited downside |
| Liquidity | 5 | New; Business API needs adoption for alpha value |
| Category Fit | 8 | LLM inference = core AI commodity; perfectly aligned with Bittensor thesis |
| Network Effects | 6 | Business API flywheel: more users → more miners → better service → more users |
| Catalyst Proximity | 6 | Active development; Business API launching; UI coming |

**Total: 54/80 (A-) — Moderate Conviction**

#### Bull Case
- **Thesis:** Becomes the decentralized alternative to OpenAI/Anthropic API
- **Business API is revolutionary:** Real commercial traffic flowing through Bittensor miners = real revenue = real alpha value
- **Solves real problem:** LLM API centralization (rate limits, censorship, outages, vendor lock-in)
- **Comparable:** Could become the "decentralized AWS for LLMs" — enormous TAM
- **Catalyst:** Business API launch; first enterprise customer; TAO wallet integration
- **Upside:** 20-100x if it captures even 1% of LLM API market

#### Bear Case
- **Risk:** Centralized AICenter WebSocket router is a single point of failure — negates decentralization benefits
- **Competition:** OpenAI, Anthropic, Google offer better latency, more models, and better SLA
- **Quality control:** If miners serve low-quality/rotated responses, the service fails
- **Regulatory:** Routing AI responses through decentralized nodes creates liability questions
- **Downside:** Business API doesn't take off; becomes another empty subnet with hype

#### Wider World Fit
- **Macro:** AI API spending is growing 100%+ YoY; decentralization is a hedge against AI oligopoly
- **Censorship resistance:** Countries banned from OpenAI/Anthropic (China, Iran, Russia) need alternatives
- **Competitive:** No other Bittensor subnet does this exact model — clear differentiator
- **Threat:** Big Tech could offer "decentralized" API gateways; latency will always favor centralized

---

### Rank 7 — SN42: Unknown

| Field | Value |
|-------|-------|
| **Name** | Unknown |
| **Category** | Unknown |
| **Symbol** | ס (Hebrew Samekh) |
| **Neurons** | 256 (max) |
| **Locked** | 0 TAO |
| **Registered** | ~Jul 2024 |

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| All factors | 1-2 | No identity, no website, no description, zero lockup, 2 years old with nothing |

**Total: 10/80 (F) — Pass**

#### Verdict
**Pass.** 2 years on the chain with nothing to show. Zero lockup. No identity. Emission extraction play only.

---

### Rank 8 — SN89: InfiniteHash

| Field | Value |
|-------|-------|
| **Name** | InfiniteHash |
| **Category** | BTC Mining + Lightning Network |
| **Website** | https://infinitehash.xyz |
| **GitHub** | https://github.com/backend-developers-ltd/InfiniteHash |
| **Contact** | btc@infinitehash.xyz |
| **Symbol** | ᛒ (Runic Berkanan) |
| **Neurons** | 256 (max) |
| **Locked** | 286,400 TAO (**HIGHEST in top 10**) |
| **Registered** | ~Dec 2024 |

#### What It Does
InfiniteHash describes itself as **"The Last Bitcoin Mining Pool, made by Bittensor."** It's a BTC mining pool bridged to Bittensor, combining Bitcoin's proof-of-work with the Lightning Network. The tagline suggests it's positioning as Bitcoin's entry point into the Bittensor ecosystem — similar to DogeLayer's approach but for BTC hashrate.

**Think of it as:** DogeLayer's big brother — instead of LTC/DOGE, it bridges Bitcoin mining (the largest PoW network) into Bittensor.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 8 | Bitcoin dominance is at all-time highs; BTC hashrate is enormous |
| Team Quality | 5 | Backend Developers Ltd; GitHub exists but less active than DogeLayer |
| Tokenomics | 7 | 286K TAO locked (highest commitment signal); BTC mining has real revenue |
| Risk/Reward | 6 | BTC mining is competitive; margins are thin; bridge concept is proven |
| Liquidity | 4 | New alpha; needs development |
| Category Fit | 7 | BTC + Bittensor = powerful narrative; "Orange-pilling Bittensor" |
| Network Effects | 6 | Bitcoin mining is the largest decentralized compute network; flywheel potential |
| Catalyst Proximity | 5 | Needs to prove the Lightning Network integration works |

**Total: 48/80 (B) — Moderate Conviction**

#### Bull Case
- **Thesis:** Bridges the world's largest decentralized compute network (Bitcoin mining) to Bittensor
- **BTC hashrate is 100x larger than LTC+DOGE** — even tiny capture would be transformative
- **Lightning Network integration** could enable micropayment flows between BTC and Bittensor
- **"Last Bitcoin Mining Pool"** positioning suggests ambition to be definitive BTC-Bittensor bridge
- **Catalyst:** Post-BTC-halvening miner demand for alternative revenue; Lightning Network adoption

#### Bear Case
- **Risk:** Direct competition with DogeLayer and likely more BTC-focused subnets in future
- **Mining centralization:** BTC mining is already highly centralized (Foundry, Antpool dominate)
- **Lightning integration is complex:** Actually making LN work for subnet rewards is non-trivial
- **Downside:** Loses BTC hashrate to DogeLayer's LTC/DOGE as miners diversify across subnets

#### Wider World Fit
- **Macro:** BTC mining is a $20B+ industry; post-halvening cost pressures will push miners to alternative revenue
- **Complementary to DogeLayer:** Different algorithms (SHA-256 vs Scrypt) = different miners = same concept
- **Threat:** BTC core community resistance to "side activities"; mining pools may not want to bridge

---

### Rank 9 — SN86: (Unnamed)

| Field | Value |
|-------|-------|
| **Name** | (unnamed, ⚒ emoji) |
| **Category** | Unknown |
| **Symbol** | ᚳ (Runic Cen) |
| **Neurons** | 256 (max) |
| **Locked** | 208,695 TAO |
| **Registered** | ~Mar 2026 |

#### What It Does
**Unknown.** On-chain identity description reads: *"Methodical. Strong foundation. And...Sr Data Scientist, 4th team member, onboard."* This suggests a team in the early stages of building something, but no public-facing product, website, or GitHub. The "Methodical" approach and "Strong foundation" language hints at a deliberate, research-first team.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| All | 1 | No product, no website, no GitHub, no description beyond vague team info |

**Total: 10/80 (F) — Pass**

#### Verdict
**Pass.** Could be a serious team building something, but without any public information, there's no way to assess. The lockup is notable (209K TAO) which suggests commitment, but that alone isn't enough.

---

### Rank 10 — SN111: oneoneone

| Field | Value |
|-------|-------|
| **Name** | oneoneone |
| **Category** | Unknown |
| **GitHub** | https://github.com/oneoneone-io/subnet-111 |
| **Contact** | support@oneoneone.io |
| **Symbol** | Ё (Cyrillic Yo) |
| **Neurons** | 256 (max) |
| **Locked** | 249,856 TAO |
| **Registered** | ~Jan 2026 |

#### What It Does
**Largely unknown.** The GitHub repo exists but has no README or description. The only signal is the high lockup (250K TAO) and the registered contact email. Could be a stealth project or placeholder.

#### Scorecard

| Factor | Score | Rationale |
|--------|-------|-----------|
| Market Timing | 2 | Unknown |
| Team Quality | 2 | GitHub exists but empty; email provided |
| Tokenomics | 4 | High lockup but no emission flow data |
| Risk/Reward | 2 | Unknown |
| Liquidity | 2 | Unknown |
| Category Fit | 1 | Unknown |
| Network Effects | 1 | Unknown |
| Catalyst Proximity | 2 | Nothing public yet |

**Total: 16/80 (F) — Pass**

#### Verdict
**Pass.** Could transform into something if the team ships, but right now there's nothing to evaluate.

---

## Portfolio View

### Graded Subnets Only (A-C)

| Subnet | Grade | Verdict | Suggested Allocation of Bittensor Research Budget |
|--------|-------|---------|---------------------------------------------------|
| **SN80 Dogelayer** | A- | **Conviction — Top Pick** | 35% |
| **SN92 TensorClaw** | A- | **Strong Watch** | 25% |
| **SN116 TaoLend** | B+ | **Watch** | 15% |
| **SN89 InfiniteHash** | B | **Watch** | 15% |
| **SN72 StreetVision** | B | **Watch** | 10% |

### The Anomalies

| Subnet | Status | Action |
|--------|--------|--------|
| SN40 Chunking | 2 years old, zero lockup | Monitor for identity change |
| SN58 Pending | No identity | Pass until identified |
| SN42 Unknown | 2 years old, nothing | Pass |
| SN86 Unnamed | Vague only | Watch — high lockup is curious |
| SN111 oneoneone | Empty GitHub | Watch — 250K lockup is notable |

---

## Key Takeaways

### What's Actually Interesting

Out of 10 top subnets by emission priority, **only 3 have genuine fundamentals worth tracking:**

1. **Dogelayer (SN80)** — Bridges real-world mining infrastructure to Bittensor. Proven by TAO inflow. Dual reward model.
2. **TensorClaw (SN92)** — Decentralized LLM API with real commercial traffic routing. Novel Business API model.
3. **TaoLend (SN116)** — First mover in TAO lending. Huge TAM if Bittensor DeFi develops.

StreetVision and InfiniteHash are **borderline** — real concepts but narrower markets.

### What's Noise

**Half the top 10 are essentially emission extraction plays** with no product, no team visibility, and zero user value. This is a structural issue in Bittensor's incentive design — there's no requirement to do anything useful to earn TAO. You can register a subnet, do nothing, and collect emissions.

### The Pruning Priority Paradox

The subnets ranked highest for emission priority (best pruning rank) are mostly the **newest** ones — not the most valuable. This is because newer registrations get higher EMA prices and thus better pruning ranks temporarily. The truly established subnets (SN40 from Jun 2024) sit lower in priority not because they're less valuable, but because they've been around longer.

### Monthly Tracking Recommendations

1. **Watch SN80's TAO inflow** — If it grows, that's Bittensor's most bullish signal
2. **Watch SN92's Business API adoption** — Real revenue flowing through would be revolutionary
3. **Watch SN116's launch** — First TAO lending protocol is a major infrastructure milestone
4. **Monitor SN86 and SN111** — High lockups without products suggest teams building in stealth
5. **Ignore SN40, SN42, SN58** — These are dead weight in the top 10

---

## Raw On-Chain Data

From Finney RPC, queried May 27, 2026.

| Subnet | Name | Symbol | Neurons | Locked (τ) | Burn (RAO) | TAO In (RAO) | α In (RAO) |
|--------|------|--------|---------|-----------|-----------|-------------|-----------|
| SN116 | TaoLend | ⵟ | 256 | 89,944 | 500 | 0 | 0 |
| SN80 | DogeLayer | ى | 243 | 219,601 | 500 | 800,582 | 250,750,730 |
| SN40 | Chunking | ן | 256 | 0 | 500 | 0 | 0 |
| SN58 | Pending | خ | 256 | 0 | 500 | 0 | 0 |
| SN72 | StreetVision | ق | 256 | 191,341 | 500 | 0 | 0 |
| SN92 | TensorClaw | ᚂ | 256 | 269,838 | 50,000 | 0 | 0 |
| SN42 | Unknown | ס | 256 | 0 | 500 | 0 | 0 |
| SN89 | InfiniteHash | ᛒ | 256 | 286,400 | 500 | 0 | 0 |
| SN86 | (unnamed) | ᚳ | 256 | 208,695 | 500 | 0 | 0 |
| SN111 | oneoneone | Ё | 256 | 249,856 | 591 | 0 | 0 |

---

## Sources

| Source | URL |
|--------|-----|
| Taostats (Rankings) | https://taostats.io/subnets |
| Taostats (Tokenomics) | https://taostats.io/tokenomics |
| Finney RPC | wss://entrypoint-finney.opentensor.ai:443 |
| TaoLend | https://taolend.io / https://github.com/xpenlab/taolend |
| DogeLayer | https://dogelayer.ai / https://github.com/dogelayer-ai/dogelayer |
| TensorClaw | https://tensorclaw.ai / https://github.com/tensorclaw/tensorclaw |
| StreetVision | https://www.natix.network / https://github.com/natixnetwork/streetvision-subnet |
| InfiniteHash | https://infinitehash.xyz / https://github.com/backend-developers-ltd/InfiniteHash |

---

*Next report: June 2026 (automated via cron on the 1st)*
