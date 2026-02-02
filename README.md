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
├── vasp-services.md             # Definition of 32 standard VASP services
├── VASP_Binance/                # Binance audit data
│   ├── report.json              # JSON audit report
│   ├── report.md                # Markdown summary report
│   └── evidence/                # Screenshot evidence
│       └── *.png
├── VASP_Bitget/                 # Bitget audit data
│   ├── report.json
│   ├── report.md
│   └── evidence/
├── VASP_Robinhood/              # Robinhood audit data
│   ├── report.json
│   ├── report.md
│   └── evidence/
├── VASP_Bitfinex/               # Bitfinex audit data
│   ├── report.json
│   ├── report.md
│   └── evidence/
├── VASP_Gateio/                 # Gate.io audit data
│   ├── report.json
│   ├── report.md
│   └── evidence/
└── VASP_Coinbase/               # Coinbase audit data
    ├── report.json
    ├── report.md
    └── evidence/
```

## 📈 Current Audits

| VASP | Services Found | Coverage | Date | Folder |
|------|---------------|----------|------|--------|
| Binance | 11/32 | 34.4% | 2026-01-31 | `VASP_Binance/` |
| Bitget | 14/32 | 43.8% | 2026-01-31 | `VASP_Bitget/` |
| Robinhood | 4/32 | 12.5% | 2026-01-31 | `VASP_Robinhood/` |
| Bitfinex | 11/32 | 34.4% | 2026-01-31 | `VASP_Bitfinex/` |
| Gate.io | 17/32 | 53.1% | 2026-02-01 | `VASP_Gateio/` |
| Coinbase | 11/32 | 34.4% | 2026-01-31 | `VASP_Coinbase/` |

## 🔍 Services Checked

See [vasp-services.md](./vasp-services.md) for the complete list of 32 standard VASP services being audited.

### Service Categories

- **Trading Services:** Spot, Margin, Futures, Options, Leveraged Tokens
- **Automation:** Trading Bots, Copy Trading, Grid Trading, Auto Investing
- **Financial:** OTC, P2P, Staking, Savings, Loans
- **DeFi & Yield:** Yield Farming, Liquidity Pools, Launchpad, Launchpool
- **NFT:** Marketplace, NFT Loans, NFT Staking
- **Payments:** Crypto Cards, Gift Cards
- **Institutional:** Custody, dApp Connectivity, Affiliate Programs
- **Tools:** Education, Tax Assistance, Gambling, Prediction Markets

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
cat VASP_Gateio/report.json | jq .

# View markdown summary
cat VASP_Gateio/report.md
```

### View Screenshots
```bash
# List all evidence for a VASP
ls VASP_Gateio/evidence/
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
