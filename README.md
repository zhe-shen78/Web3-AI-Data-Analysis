# Web3 + AI On-chain Data Research Portfolio 🚀

这是我的 Web3 数据分析实战仓库。我目前正在执行一个为期 14 天的“独立研究型”数据分析计划，专注于 **AI 赛道代币（RNDR, FET 等）** 的链上资金流向研究。

## 🎓 关于我
- **背景**：齐鲁工业大学 数据计算与应用专业 | 2025 数学建模省一等奖 🏆
- **技能**：SQL (Dune Analytics), Python (Pandas), 数据建模, 业务指标设计
- **GitHub**: [zhe-shen78](https://github.com/zhe-shen78)
- **联系方式**: [zhes01689@gmail.com](mailto:zhes01689@gmail.com)

## 📅 14 天执行计划 (进度: Day 4/14)
我正在按照 [14-Day-Plan](./Plan/14-Day-Plan.md) 逐步推进项目。目前已完成前四天的核心逻辑开发。

- [x] **Day 1-2**: 定义研究边界，完成 Dune 多源数据底座搭建。
- [x] **Day 3**: 开发地址清洗逻辑，成功剔除 CEX、合约地址及异常地址。
- [x] **Day 4**: 构建 **p80 净流入模型**，识别高胜率资金群体。
- [ ] **Day 5-7**: PnL 透视模型开发与 Dashboard 交付。
- [ ] **Day 8-14**: 引入 AI 情绪因子关联分析。

## 🛠️ 当前核心项目：Smart Money 追踪 (DuneSQL)
针对 AI 代币赛道，我构建了一套自动化识别“聪明钱”的 SQL 逻辑：
- **地址清洗**：精准剔除 CEX 交易所地址与非活跃地址。
- **分位模型**：采用 p80 净流入阈值过滤噪音。
- **多链支持**：同时支持 Ethereum (FET) 与 Solana (RNDR) 的链上数据。

[查看核心查询脚本](./Project-1-Smart-Money/Queries/smart_money_tracking.sql)
