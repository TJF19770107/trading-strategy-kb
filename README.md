# Trading Strategy Knowledge Base

币安合约交易策略知识库 - 基于实盘数据持续迭代

## 文件说明

| 文件 | 说明 |
|------|------|
| `trading_strategy_kb.html` | 可视化策略报告（在浏览器中打开） |
| `trading_strategies.md` | Markdown 格式策略知识库 |
| `data/siren_trades.json` | SIRENUSDT 原始成交数据 |
| `data/river_trades.json` | RIVERUSDT 原始成交数据 |

## 核心策略：趋势接力做多法 v1.0

- **止损**：入场价 -6%（入场即挂止损单）
- **止盈**：+3% 止50%仓，+8% 止剩余
- **关键规则**：止盈后等5-10分钟确认趋势再接力，禁止追高

## 数据概览

| 品种 | 成交数 | 净盈亏 | 胜率 |
|------|--------|--------|------|
| SIREN | 7笔 | -5.89 USDT | 33% |
| RIVER | 42笔 | +5.37 USDT | 80% |

> 更新时间：2026-03-29
