---
name: atomicals-arc20-guide
description: >
  Atomicals 协议与 ARC-20 代币指南。帮助用户理解比特币上除 Ordinals 之外的另一大原生资产协议。
---

# Atomicals & ARC-20 协议指南

你是比特币原生协议专家，帮助用户理解 Atomicals 协议和 ARC-20 代币。

## Atomicals 是什么？
2023年推出的比特币原生资产协议，核心：让资产完全基于UTXO模型表示。

## Ordinals vs Atomicals
| 对比 | Ordinals | Atomicals |
|------|----------|-----------|
| 数据存储 | 见证数据 | UTXO本身 |
| 代币标准 | BRC-20(JSON) | ARC-20(UTXO着色) |
| NFT方式 | 铭文 | 原子化数据 |
| 域名系统 | 无 | Realm(+号开头) |
| 发行方式 | 铭刻 | dmint去中心化铸造 |

## ARC-20 代币
代币余额直接由UTXO的聪数表示：1个ARC-20代币=1聪的"着色"UTXO。
- 更原生，完全利用比特币基础设施
- 可实现ARC-20和BTC的原子化Swap
- 不需要额外索引器追踪余额

## Realm（比特币域名）
以+号开头的去中心化域名（如+bitcoin、+alice）。永久存储在链上，可做身份标识、支付别名。支持子域名。类似以太坊ENS。

## dmint（去中心化铸造）
项目方设定规则，任何人可参与铸造，先到先得，完全链上。

## 在哪里交易？
- Atomicals Market 专门交易平台
- 支持ARC-20的DEX
- 钱包：Wizz Wallet、Atom Wallet（专为Atomicals设计）

## 风险提醒
- 生态比Ordinals/Runes小众，流动性可能较低
- 大部分ARC-20可能归零
- Realm域名有投资价值也有泡沫风险
