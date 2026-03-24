# Web3 + AI On-chain Data Research Portfolio 🚀

This repository documents an intensive 14-day research plan focusing on **AI-sector tokens (RNDR, FET, etc.)** and on-chain capital flow modeling.

## 📊 Project Overview
The goal of this initiative is to build a "Smart Money" tracking system and a robust risk signal framework. It leverages **Dune Analytics** and **Python** to bridge raw blockchain data with actionable market insights.

## 📅 14-Day Research Roadmap (Progress: Day 4/14)
I am following a structured [Execution Plan](./Plan/14-Day-Plan.md) to ensure data validity and methodology consistency:
- [x] **Day 1-2**: Scope definition & multi-source data infrastructure on Dune.
- [x] **Day 3**: Data cleaning pipeline (Filtering CEXs, contract addresses, and abnormal bots).
- [x] **Day 4**: Developed **p80 Net-Flow Model** to isolate high-conviction capital.
- [ ] **Day 5-7**: PnL profiling & Dashboard visualization.
- [ ] **Day 8-14**: Sentiment factor integration & cross-validation.

## 🛠️ Core Module: Smart Money Tracking (DuneSQL)
The tracking logic identifies significant movers by:
- **Noise Reduction**: Precision filtering of centralized exchange (CEX) wallets and non-individual addresses.
- **Percentile Modeling**: Utilizing **80th percentile (p80)** net-flow thresholds to filter out noise and focus on major participants.
- **Cross-Chain Coverage**: Simultaneously monitoring Ethereum (FET) and Solana (RNDR) ecosystems.

[View SQL Implementation](./Project-1-Smart-Money/Queries/smart_money_tracking.sql)

## 🎓 Academic Background
- **Qilu University of Technology**: Data Science & Application.
- **Award**: 1st Prize, 2025 Provincial Mathematical Modeling Contest 🏆.

---
*Contact: [zhes01689@gmail.com](mailto:zhes01689@gmail.com)*
