# VASP Audit Data Repository

A comprehensive collection of VASP (Virtual Asset Service Provider) audit reports, evidence, and service analysis data.

## 📊 Overview

This repository contains automated audit data for cryptocurrency exchanges and trading platforms, documenting their available services with visual evidence.

## 📁 Repository Structure

```
vasp-audit-data/
├── README.md                    # This file
├── LICENSE                      # License
├── .gitignore                   # Git ignore rules
├── data/
│   ├── services/
│   │   └── vasp-services.md     # Definition of 32 standard VASP services
│   ├── reports/                 # JSON audit reports
│   │   ├── binance_*.json
│   │   ├── bitget_*.json
│   │   ├── robinhood_*.json
│   │   ├── bitfinex_*.json
│   │   └── gateio_*.json
│   └── evidence/                # Screenshot evidence (PNG)
│       └── [vasp]_[service]_*.png
├── audits/                      # Markdown summary reports
│   ├── binance.md
│   ├── bitget.md
│   ├── robinhood.md
│   ├── bitfinex.md
│   └── gateio.md
└── scripts/                     # Utility scripts
    └── generate-summary.js
```

## 📈 Current Audits

| VASP | Services Found | Coverage | Date |
|------|---------------|----------|------|
| Binance | 11/32 | 34.4% | 2026-01-31 |
| Bitget | 14/32 | 43.8% | 2026-01-31 |
| Robinhood | 4/32 | 12.5% | 2026-01-31 |
| Bitfinex | 11/32 | 34.4% | 2026-01-31 |
| Gate.io | 17/32 | 53.1% | 2026-02-01 |

## 🔍 Services Checked

The audit checks for 32 standard VASP services:

### Trading Services
- Spot Trading
- Margin Trading
- Futures
- Options
- Leveraged Tokens

### Automation & Copy Trading
- Trading Bots
- Copy Trading
- Grid Trading
- Auto Investing (DCA)

### Financial Services
- OTC Desk
- P2P Platform
- Crypto Staking
- Saving Accounts
- Crypto Loans
- Cloud Mining

### DeFi & Yield
- Yield Farming
- Liquidity Pools
- Launchpad
- Launchpool
- Airdrops

### NFT Services
- NFT Marketplace
- NFT Loans
- NFT Staking

### Payment & Cards
- Crypto Debit/Credit Cards
- Gift Card / Red Envelope

### Institutional & Business
- Custody Services
- dApp Connectivity
- Referral/Affiliate Programs

### Education & Tools
- Educational Services
- Learn and Earn
- Tax Assistance
- Gambling
- Prediction Markets

## 📸 Evidence

Each service verification includes:
- URL of the service page
- Screenshot with visual evidence
- Timestamp of the audit
- Confidence level (HIGH/MEDIUM/LOW)

## 🛠️ Usage

### View Audit Report
```bash
# Read a specific VASP report
cat data/reports/gateio_2026-02-01.json | jq .

# View markdown summary
cat audits/gateio.md
```

### Generate Statistics
```bash
node scripts/generate-summary.js
```

## 🤖 Audit Methodology

Audits are performed using automated browser scanning with:
- **Tool:** Playwright with Chromium
- **Process:** Systematic navigation and keyword matching
- **Verification:** Visual evidence via screenshots
- **Timing:** Network idle + 5s wait for proper content loading

## 📄 License

MIT License - See LICENSE file for details

## 📝 Notes

- Services marked as "not found" may exist but are not prominently advertised
- Some services may be region-locked or require authentication
- Coverage percentage indicates the portion of standard VASP services offered
- All timestamps are in ISO 8601 format (UTC)

## 🔗 Related

- [VASP Analyst Skill](https://github.com/clawdbot/skills/vasp-analyst) - The tool used to generate these audits
