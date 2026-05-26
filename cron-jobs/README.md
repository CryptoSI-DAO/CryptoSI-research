# Cron Job Specifications

> Specifications for automated monitoring agents.
> These jobs are designed to be executed by a separate monitoring agent that writes findings back to this repo.

## Execution Model

- Jobs run on a schedule defined in each spec
- Output is committed back to the appropriate folder (`notes.md` or dedicated report files)
- The executing agent should NOT make investment decisions — only report data
- All findings should include a timestamp and data source

## Active Jobs

| Job ID | Ecosystem | Frequency | Status | Last Run |
|--------|-----------|-----------|--------|----------|
| <!-- --> | <!-- --> | <!-- --> | <!-- --> | <!-- --> |

## Job Spec Template

```yaml
---
id: job-name
ecosystem: TAO-bittensor | Hype
frequency: daily | hourly | weekly
description: "What this job monitors"

metrics:
  - name: "metric_name"
    source: "API or data source"
    alert_condition: "when to flag"

output:
  path: "folder/file.md"
  format: "append_new_section"

alerting:
  enabled: true
  threshold: "what triggers an alert"
  destination: "where to send alerts"
---
```

## TAO/Bittensor Jobs

### TAO-001: Daily Network Snapshot
- **Frequency:** Daily
- **What:** Capture key network metrics (price, staking, emissions, subnet count)
- **Output:** Appends to `TAO-bittensor/notes.md` under "Daily Snapshots"
- **Source:** Taostats API, CoinGecko API

### TAO-002: Subnet Emission Tracker
- **Frequency:** Daily
- **What:** Track emission changes across top 20 subnets
- **Output:** `TAO-bittensor/subnets/emission-report.md`
- **Alert:** Any subnet with >20% emission change

### TAO-003: New Subnet Monitor
- **Frequency:** Every 6 hours
- **What:** Detect newly registered subnets
- **Output:** Alerts only — new subnets are notable
- **Alert:** Any new subnet registration

### TAO-004: Whale Movement Tracker
- **Frequency:** Every 4 hours
- **What:** Monitor large TAO transactions (>100 TAO)
- **Output:** `TAO-bittensor/notes.md` under "Whale Activity"
- **Source:** Taostats/Subscan

### TAO-005: Governance & Proposals
- **Frequency:** Daily
- **What:** Track governance proposals, voting outcomes
- **Output:** `TAO-bittensor/notes.md` under "Governance"

## Hyperliquid Jobs

### HYPE-001: Daily Ecosystem Snapshot
- **Frequency:** Daily
- **What:** HYPE price, volume, TVL, active traders
- **Output:** Appends to `Hype/notes.md` under "Daily Snapshots"
- **Source:** Hypurrscan, DefiLlama API, CoinGecko API

### HYPE-002: New HIP-1 Token Launches
- **Frequency:** Every 2 hours
- **What:** Detect new spot token launches on Hyperliquid
- **Output:** `Hype/notes.md` under "New Launches"
- **Alert:** Any new HIP-1 token

### HYPE-003: HIP-2 / NFT Launch Monitor
- **Frequency:** Every 1 hour
- **What:** Track new NFT launches via pumps.fun or similar
- **Output:** `Hype/notes.md` under "NFT Activity"
- **Alert:** Volume spikes or notable launches

### HYPE-004: HyperEVM Deployments
- **Frequency:** Every 6 hours
- **What:** New smart contract deployments on HyperEVM
- **Output:** `Hype/notes.md` under "HyperEVM Activity"

### HYPE-005: Builder Code Revenue
- **Frequency:** Weekly
- **What:** Track top builder codes by revenue
- **Output:** `Hype/ecosystem-map.md` — Yield Opportunities table

### HYPE-006: Whale Tracker
- **Frequency:** Every 4 hours
- **What:** Large HYPE movements, whale wallet changes
- **Output:** `Hype/notes.md` under "Whale Activity"
- **Alert:** Transactions >$100K equivalent

## Cross-Ecosystem Jobs

### CROSS-001: Portfolio Dashboard Update
- **Frequency:** Daily
- **What:** Update all active positions with current P&L
- **Output:** Updates `opportunities.md` in each ecosystem

### CROSS-002: Macro Correlation Check
- **Frequency:** Daily
- **What:** BTC/ETH price, fear & greed index, funding rates
- **Output:** `notes.md` in relevant ecosystem

## API Reference

### Key Data Sources

| Source | Use | Auth |
|--------|-----|------|
| CoinGecko API | Price data | Free, no auth |
| Taostats API | Bittensor on-chain data | Free tier |
| Hypurrscan | Hyperliquid on-chain data | Free |
| DefiLlama API | TVL, protocol metrics | Free |
| Subscan | Polkadot/Bittextrin explorer | Free tier |

### Rate Limits

| Source | Limit |
|--------|-------|
| CoinGecko (free) | 10-30 calls/min |
| DefiLlama | Fair use |
| Taostats | Check docs |
