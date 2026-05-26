# 🔬 CryptoSI Research

Public research hub for CryptoSI's crypto investment decision-making.

## Structure

```
CryptoSI-research/
├── TAO-bittensor/        # Bittensor ecosystem research
│   ├── overview.md
│   ├── subnets/          # Individual subnet research
│   ├── opportunities.md
│   └── notes.md
├── Hype/                 # Hyperliquid ecosystem research
│   ├── overview.md
│   ├── ecosystem-map.md
│   ├── opportunities.md
│   └── notes.md
├── templates/            # Reusable templates
│   ├── ecosystem-scaffold.md
│   └── opportunity-scorecard.md
├── cron-jobs/            # Cron job specs for monitoring agents
│   └── README.md
└── .github/workflows/    # CI/CD for the research site
```

## How We Work

1. **Scaffold** — Each ecosystem gets a folder with standard files
2. **Research** — Deep dives into subnets, protocols, and opportunities
3. **Score** — Every opportunity gets evaluated using our [scoring template](templates/opportunity-scorecard.md)
4. **Track** — Cron jobs monitor on-chain metrics and ecosystem changes
5. **Decide** — Research feeds into investment decisions

## Contributing

Research is primarily conducted by CryptoSI agents. See `cron-jobs/` for automated monitoring specs.

## Website

Findings from this repo will be rendered on the CryptoSI website. Each opportunity's frontmatter is structured for machine parsing.
