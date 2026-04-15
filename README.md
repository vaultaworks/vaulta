# VAULTA — Autonomous Yield Infrastructure on Base

> Deposit USDC. Receive $vsUSD. Let AI compound your capital — 24/7, on-chain, transparent.

[![Testnet](https://img.shields.io/badge/Testnet-Base_Sepolia-00C853?style=flat-square)](https://sepolia.basescan.org)
[![Built on Base](https://img.shields.io/badge/Built_on-Base-0052FF?style=flat-square)](https://base.org)
[![Status](https://img.shields.io/badge/Status-Testnet_Live-brightgreen?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-gold?style=flat-square)](LICENSE)

---

## What is Vaulta?

Vaulta is a **non-custodial, AI-driven yield protocol** on Base. Users deposit USDC into one of three vaults, receive the yield-bearing `$vsUSD` token, and earn optimized returns — automatically — without managing positions, monitoring rates, or paying excessive gas.

The AI optimizer routes capital across **Morpho, Aerodrome, Ondo Finance, Centrifuge, and x402 agentic flows** — continuously rebalancing toward the highest risk-adjusted opportunity.

---

## Protocol Architecture

```
User → USDC Deposit
         ↓
    Vault Contract
         ↓
    $vsUSD Minted (1:1)
         ↓
    AI Optimizer Engine
    ┌────────────────────┐
    │  Morpho (lending)  │
    │  Aerodrome (LP)    │
    │  Ondo (RWA/T-bill) │
    │  Centrifuge (credit│
    │  x402 (agentic)    │
    └────────────────────┘
         ↓
    Yield Compounds → $vsUSD appreciates
         ↓
    User redeems anytime → USDC + yield
```

---

## Vault Products

| Vault | Risk | Est. APY | Primary Strategies |
|-------|------|----------|--------------------|
| **Stable Vault** | 🟢 Low | 8–14% | Morpho lending, Aerodrome USDC LP |
| **Boost Vault** | 🟡 Medium | 14–22% | RWA via Ondo, DeFi blend |
| **Alpha Vault** | 🔴 High | 25–40% | Perp funding, BTCFi, x402 |

> ⚠️ APY figures are estimates based on current protocol conditions. Not financial advice. Past performance does not guarantee future results.

---

## 2026–2027 Narrative Positioning

Vaulta sits at the intersection of the strongest on-chain narratives:

- **S-tier:** Agentic Commerce (x402), AI Finance, Tokenization
- **A-tier:** RWA, Stablecoins, Neobanks
- **B-tier:** x402, Perp Dex, BTCFi, Consumer DeFi

---

## Repository Structure

```
vaulta/
├── index.html          # Main landing page
├── app.html            # App / deposit interface
├── docs.html           # Documentation page
├── SKILL.md            # Full project context & design system
├── README.md           # This file
└── .github/
    └── ISSUE_TEMPLATE.md
```

---

## Local Development

No build step required. Pure HTML/CSS/JS.

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/vaulta.git

# Open locally
cd vaulta
open index.html

# Or serve with any static server
npx serve .
# → http://localhost:3000
```

---

## Roadmap

| Phase | Timeline | Status |
|-------|----------|--------|
| Testnet (Base Sepolia) | Q2 2026 | ✅ Live |
| Smart Contract Audit | Q2–Q3 2026 | 🔄 In Progress |
| Mainnet — Stable Vault | Q3 2026 | ⏳ Upcoming |
| Boost Vault + AI Dashboard | Q4 2026 | ⏳ Upcoming |
| Alpha Vault + x402 + DAO | Q1 2026 | ⏳ Planned |

---

## Tech Stack

- **Chain:** Base (Ethereum L2 by Coinbase)
- **Contracts:** Solidity ^0.8.20 + OpenZeppelin
- **Frontend:** Vanilla HTML/CSS/JS (no framework dependency)
- **Fonts:** Bebas Neue, Space Mono, DM Sans (Google Fonts)
- **Integrations:** Morpho, Aerodrome, Ondo Finance, Centrifuge, x402

---

## Security

- Non-custodial architecture — users retain key control
- Emergency pause via multisig circuit breaker
- All AI allocation decisions recorded on-chain
- No admin mint function — $vsUSD only minted 1:1 with USDC
- Audit planned pre-mainnet

---

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit changes (`git commit -m 'feat: add feature'`)
4. Push to branch (`git push origin feature/your-feature`)
5. Open a Pull Request

See [SKILL.md](./SKILL.md) for full design system and project context before contributing.

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

## Links

- 🌐 Website: [vaulta.fi](https://vaulta.fi) *(coming soon)*
- 🐦 Twitter: [@VaultaProtocol](https://twitter.com/VaultaProtocol)
- 💬 Discord: *(coming soon)*
- 📄 Docs: [docs.vaulta.fi](https://docs.vaulta.fi) *(coming soon)*
- 🔍 Testnet: [Base Sepolia](https://sepolia.basescan.org)

---

*Built on Base · Powered by AI · Non-custodial*
