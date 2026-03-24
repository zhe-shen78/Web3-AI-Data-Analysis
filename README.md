# Web3 + AI On-chain Data Research Portfolio 🚀

This repository documents an intensive 14-day research plan focusing on **AI-sector tokens (RNDR, FET, etc.)** and on-chain capital flow modeling.

## 📊 Project Overview
The goal of this initiative is to build a "Smart Money" tracking system and a robust risk signal framework. It leverages **Dune Analytics** and **Python** to bridge raw blockchain data with actionable market insights.

## 📅 14-Day Research Roadmap (Progress: Day 8/14 - Strategic Pivot)
I am following a structured [Execution Plan](./Plan/14-Day-Plan.md). Due to external API/platform status, I have strategically pivoted to **Project 2 (AI Sentiment Analysis)** while keeping the foundational logic of Project 1 (Smart Money Tracking).

- [x] **Day 1-4**: Completed Dune SQL infrastructure for Smart Money tracking (Solana & Ethereum).
- [ ] **Day 5-7**: (Pending Platform Reinstatement) PnL profiling & Dashboard.
- [x] **Day 8 (In Progress)**: **Strategic Shift to AI Sentiment Analysis**. Building a data pipeline to scrape and quantify off-chain sentiment factors (X/Twitter, Reddit, etc.).
- [ ] **Day 9-14**: Sentiment scoring with LLMs & cross-validation with on-chain flow data.

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
