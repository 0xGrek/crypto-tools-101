# Crypto Tools 101

> 101 automation tools across 10+ blockchains and 9 CEX exchanges — built pre-vibe-coding era.

<div align="left">

![Python](https://img.shields.io/badge/Python-1a1a1a?style=flat-square&logo=python&logoColor=cccccc)
![ccxt](https://img.shields.io/badge/ccxt-1a1a1a?style=flat-square&logoColor=cccccc)
![web3.py](https://img.shields.io/badge/web3.py-1a1a1a?style=flat-square&logo=ethereum&logoColor=cccccc)
![asyncio](https://img.shields.io/badge/asyncio-1a1a1a?style=flat-square&logoColor=cccccc)
![Solana](https://img.shields.io/badge/Solana-1a1a1a?style=flat-square&logo=solana&logoColor=cccccc)

</div>

---

## Overview

A complete automation toolkit built from scratch across 2023–2024, covering everything from CEX withdrawal bots to multi-chain wallet generators. Written before AI coding assistants could produce working code — every line is hand-engineered.

The collection spans 13 categories and addresses the full lifecycle of crypto operations: account setup, chain interaction, arbitrage, farming, and monitoring.

---

## Architecture

```
crypto-tools-101/
├── cex/              — CEX API wrappers (9 exchanges via ccxt)
├── wallets/          — Multi-chain wallet generation & management
├── defi/             — DEX interaction scripts (15+ EVM chains)
├── nft/              — NFT minting, listing, bulk transfer
├── airdrop/          — Airdrop claimers, eligibility checkers
├── farming/          — Liquidity farming, yield strategies
├── monitoring/       — Price alerts, wallet watchers
├── utils/            — Proxy rotation, anti-detect, account mgmt
└── scripts/          — Standalone one-off automation scripts
```

Each tool is self-contained with its own config file. No shared state between tools — each runs independently.

---

## Key Features

- **9 CEX integrations** — Binance, OKX, Bybit, Gate, Bitget, MEXC, KuCoin, Coinex, Huobi
- **Multi-chain wallet ops** — generation, funding, sweeping across 6 chains
- **DEX farming** — automated LP provision, harvest, and compounding
- **NFT tooling** — bulk mint, list, transfer across EVM and SOL
- **Airdrop infrastructure** — eligibility checks, claim bots, Sybil patterns
- **Anti-detect operations** — 1,000+ account management with proxy rotation

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3.10+ |
| CEX | ccxt library |
| EVM chains | web3.py, ethers.js |
| Solana | solders, solana-py |
| TON | tonsdk |
| HTTP | httpx, aiohttp |
| Storage | SQLite, JSON configs |

---

## Metrics

- **101** tools total
- **10+** blockchains: ETH, BNB, ARB, OP, BASE, SOL, BTC, TON, SUI, Aptos + 15 EVM L2s
- **9** CEX APIs automated
- **13** tool categories
- Built 2023–2024, pre-vibe-coding

---

More at [0xgrek.com](https://0xgrek.com/projects/crypto-tools-101)

---

MIT License
