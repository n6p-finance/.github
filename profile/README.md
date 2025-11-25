# 🌌 **NapFi: The Operating System for Programmable Capital**

![Solidity](https://img.shields.io/badge/Solidity-0.8.23-blue)
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![Next.js](https://img.shields.io/badge/Next.js-15-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![Wagmi](https://img.shields.io/badge/Wagmi-2.x-yellow)
![MIT](https://img.shields.io/badge/License-MIT-purple)

**NapFi is a modular finance protocol for automated yield, creator monetization, and programmable capital coordination.**
Built on Base. Designed for DeFi, SocialFi, and RWA integrations.

Video Demo: https://youtu.be/5JH47tJAkMo                                                                                                                                                             
Documentation Team: https://drive.google.com/drive/folders/1bDG6IQNcB2Vny9x0r6311FvkFh4RpBTx

---

# ⭐ What Is NapFi?

NapFi transforms vaults into **programmable capital engines** capable of yield optimization, on-chain licensing, creator monetization, and agenda-driven capital allocation.

Think:
**Yearn x Story Protocol x SocialFi** → re-imagined as a unified ecosystem.

NapFi enables:

* 🧠 **Autonomous Yield Optimization**
* 🧩 **Composable Vault Architecture**
* 🏦 **RWA-ready On-Chain Registries**
* 🎨 **Creator Monetization via Tokenized Vault Licensing**
* 🎯 **Agenda-Based Capital Routing** (missions, legacies, relief funds, etc.)
* 📈 **Competitive Developer Strategy Marketplace**

NapFi’s vaults are not passive they are programmable, licensed, monetized, and boostable.

---

# 🗂 NapFi Ecosystem Repositories

## **1. napfi-sc Smart Contracts**

Next-gen modular vault architecture designed for automation, licensing, and multi-strategy routing.

**Includes:**

| Module                        | Purpose                                           |
| ----------------------------- | ------------------------------------------------- |
| **Registry**                  | Global index of vaults, metadata, creators        |
| **UnifiedVault**              | Core economic engine (PPS, deposits, withdrawals) |
| **Strategy Modules**          | Pluggable DeFi yield strategies                   |
| **Agenda Engine**             | Mission-based capital allocation                  |
| **VaultLicensing** (upcoming) | Borrowable vaults for creators & DAOs             |

**Deployments (Base Sepolia):**

* Registry: `0x2340F9643C18CEbfd7b6042AD8e23B205B286D78`
* Vault Implementations: `0x11761e6bDef98e8fa7216dEe36068eD922B24Aaa`

---

## **2. napfi-be Indexer & Backend API**

The analytical engine behind NapFi.

**Features:**

* Subgraph indexing
* APY computation
* Strategy performance metrics
* Agenda + Booster scoring system
* Creator + Vault metadata registry

Built with **Node.js, Subgraph, Postgres, Redis**.

---

## **3. napfi-frontend Unified Dashboard**

A seamless interface for:

* Vault discovery
* Creator monetization
* Agenda creation
* Booster utilities
* Strategy developer marketplace

Built on **Next.js 15, React 19, Wagmi v2, Viem, Tailwind, Xellar Kit**.

---

# 🧬 NapFi Core Concepts

## **1. Borrowable Vault Licensing**

Creators and organizations can temporarily license their vaults:

* Revenue splits
* Permission scopes
* Time-bounded control
* Revocable delegations

**This creates on-chain intellectual property for yield strategies.**

---

## **2. Agenda Vaults Intent-Based Capital**

Users can assign **Agendas** to a vault:

* Creator income
* Community treasury
* High-yield optimization
* Charity & relief missions
* Long-term legacy funds

Each agenda can attach **Booster NFTs** that influence yield routing and strategy selection.

---

## **3. Developer Strategy Marketplace**

A competitive environment where developers deploy strategies and earn:

* Performance fees
* Management fees
* Reputation boosts
* Agenda-based multipliers

Turning vaults into **decentralized strategy arenas**.

---

# 🧱 Architecture Overview

```
                 ┌───────────────────────┐
                 │       Registry         │
                 │  (Global Index Layer)  │
                 └───────────┬────────────┘
                             │
                             ▼
               ┌───────────────────────────┐
               │       Unified Vault       │
               │ (Yield + Licensing Logic) │
               └───────────┬───────────────┘
                           │
                           ▼
        ┌──────────────────────────────────────────┐
        │               Agenda Engine              │
        │   (Mission Routing + Booster System)     │
        └───────────┬──────────────────────────────┘
                    │
                    ▼
          ┌────────────────────────────┐
          │   Strategy Marketplace     │
          │ (Permissionless strategies)│
          └────────────────────────────┘
```

---

# ⚙️ Tech Stack

### **Smart Contracts**

* Solidity (0.8.23+)
* Foundry
* OpenZeppelin
* Viem ABI typing
* Inline Assembly (select modules)

### **Backend**

* Node.js + TypeScript
* Subgraph Indexer
* PostgreSQL
* Redis
* Event-driven processing

### **Frontend**

* Next.js 15
* React 19
* Tailwind + Shadcn
* Wagmi v2
* Viem
* Xellar Kit wallets

---

# 🛠 Deployment (Testnet)

**Base Sepolia**

| Component            | Address                                      |
| -------------------- | -------------------------------------------- |
| Registry             | `0x2340F9643C18CEbfd7b6042AD8e23B205B286D78` |
| Vault Implementation | `0x11761e6bDef98e8fa7216dEe36068eD922B24Aaa` |
| Governance Role      | `0x005684aC7C737Bff821ECCb377cC46e5A7dcB60D` |

---

# 🤝 Contributing

We welcome contributions across:

* DeFi strategy development
* Creator monetization tooling
* RWA integrations
* Frontend UX
* Smart contract audits

**PR Workflow**

```
1. Fork repository
2. Create a feature branch
3. Commit & push
4. Submit pull request
```

---

# 📄 License

NapFi is available under the **MIT License**.

---

# 🔗 Links

(coming soon)

* Website: https://napfiland.vercel.app/
* Documentation
* Twitter: https://x.com/nap_Finance
* Discord: https://discord.gg/7nceYeJ5
* LinkedIn: https://www.linkedin.com/company/napy-labs/?viewAsMember=true

Developer References:

* Base Docs
* Story Protocol Docs
* Viem Docs
* Next.js Docs

---

# ⚠️ Disclaimer

NapFi is in **TESTNET / BETA**.
Modules, parameters, and implementations are subject to change.
Not financial advice.

