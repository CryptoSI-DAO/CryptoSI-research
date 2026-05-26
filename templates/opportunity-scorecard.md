# Opportunity Scorecard Template

> Every investment opportunity gets scored using this framework.
> Designed for both human readability and machine parsing (YAML frontmatter → website).

---

## YAML Frontmatter Schema

```yaml
---
id: unique-opportunity-id
ecosystem: TAO-bittensor | Hype
name: "Opportunity Name"
type: staking | token | nft | DeFi | infrastructure | ecosystem
status: pipeline | active | exited | passed | watching
conviction: very-low | low | moderate | high | very-high
date_identified: YYYY-MM-DD
date_actioned: YYYY-MM-DD | null
last_reviewed: YYYY-MM-DD

# Scoring (1-10 each)
scores:
  market_timing: 0
  team_quality: 0
  tokenomics: 0
  risk_reward: 0
  liquidity: 0
  time_alignment: 0
  network_effects: 0
  catalyst_proximity: 0

# Derived
total_score: 0
max_score: 80
score_percentage: 0

# Position sizing
suggested_allocation_pct: 0    # % of portfolio
risk_level: low | medium | high | very-high
time_horizon: short | medium | long  # short <3mo, medium 3-12mo, long 12mo+

# Tracking
entry_price: 0
current_price: 0
pnl_pct: 0
taostats_url: ""              # or hypurrscan, etc.
tags: []
---
```

## Scoring Criteria (Each 1–10)

### 1. Market Timing (1–10)
*Is now the right time for this play?*

| Score | Meaning |
|-------|---------|
| 1–3 | Early/uncertain or late/overplayed |
| 4–6 | Reasonable timing, some uncertainty |
| 7–9 | Strong timing, market conditions favorable |
| 10 | Impeccable timing, catalyst imminent and market primed |

### 2. Team Quality (1–10)
*How strong is the team behind this?*

| Score | Meaning |
|-------|---------|
| 1–3 | Anonymous, unproven, or red flags |
| 4–6 | Known entity, decent track record |
| 7–9 | Strong team with relevant experience, shipping product |
| 10 | Top-tier builders, consistent delivery, well-connected |

### 3. Tokenomics (1–10)
*How sound is the economic model?*

| Score | Meaning |
|-------|---------|
| 1–3 | Inflationary dump, misaligned incentives, no value accrual |
| 4–6 | Acceptable but not exciting, some concerns |
| 7–9 | Well-designed, clear value accrual, sustainable emissions |
| 10 | Exceptional tokenomics, strong sink mechanisms, aligned incentives |

### 4. Risk/Reward (1–10)
*What's the asymmetric upside?*

| Score | Meaning |
|-------|---------|
| 1–3 | Limited upside, significant downside |
| 4–6 | Moderate risk/reward, roughly balanced |
| 7–9 | Strong upside relative to downside |
| 10 | Near-asymmetrical — massive upside, limited downside |

### 5. Liquidity (1–10)
*Can we enter/exit without major slippage?*

| Score | Meaning |
|-------|---------|
| 1–3 | Very thin liquidity, difficult to position |
| 4–6 | Adequate for small positions |
| 7–9 | Deep liquidity, easy entry/exit |
| 10 | Deepest liquidity in class, institutional grade |

### 6. Time Alignment (1–10)
*Does this fit our investment timeline?*

| Score | Meaning |
|-------|---------|
| 1–3 | Wrong timeline (need money back soon, this is long-term) |
| 4–6 | Tolerable mismatch |
| 7–9 | Good alignment with available capital timeline |
| 10 | Perfect alignment — capital timeframe matches opportunity |

### 7. Network Effects (1–10)
*Does this benefit from growing adoption?*

| Score | Meaning |
|-------|---------|
| 1–3 | Network effects are weak or non-existent |
| 4–6 | Some network effects present |
| 7–9 | Strong network effects, flywheel visible |
| 10 | Dominant network effect, winner-take-most dynamics |

### 8. Catalyst Proximity (1–10)
*How soon is the next major catalyst?*

| Score | Meaning |
|-------|---------|
| 1–3 | No identifiable catalyst in the foreseeable future |
| 4–6 | Catalyst exists but timeline uncertain |
| 7–9 | Clear catalyst within 1-3 months |
| 10 | Catalyst is imminent (days/weeks) |

## Interpretation Guide

| Total Score | Recommendation |
|-------------|----------------|
| 0–20 | **Pass**. Not worth pursuing at this time. |
| 21–35 | **Watch**. Interesting but not actionable. Add to watchlist. |
| 36–50 | **Small Position**. Worth a measured allocation. |
| 51–65 | **Meaningful Position**. Strong opportunity, size appropriately. |
| 66–80 | **Conviction Play**. Allocate aggressively within risk limits. |

## Example Filled Scorecard

```yaml
---
id: hype-staking-2025q2
ecosystem: Hype
name: "HYPE Native Staking"
type: staking
status: pipeline
conviction: high
date_identified: 2025-05-26
date_actioned: null
last_reviewed: 2025-05-26

scores:
  market_timing: 7
  team_quality: 9
  tokenomics: 7
  risk_reward: 7
  liquidity: 9
  time_alignment: 8
  network_effects: 8
  catalyst_proximity: 6

total_score: 61
max_score: 80
score_percentage: 76

suggested_allocation_pct: 5
risk_level: low
time_horizon: medium

entry_price: 0
current_price: 0
pnl_pct: 0
taostats_url: ""
tags: ["yield", "blue-chip-ecosystem", "low-risk"]
---
```

## Decision Workflow

```
┌─────────────────────┐
│  Identify Opportunity │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Score All 8 Factors │
│  (1-10 each)        │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Calculate Total     │
│  (max 80)           │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐     ┌──────────────────────┐
│  Total < 36?         │────▶│  Watchlist / Pass     │
└──────────┬──────────┘     └──────────────────────┘
           │ No
           ▼
┌─────────────────────┐
│  Size Position Based │
│  on Score + Conviction│
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Set Review Cadence  │
│  & Exit Criteria     │
└─────────────────────┘
```
