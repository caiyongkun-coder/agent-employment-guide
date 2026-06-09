# agent就业指南

[English](README.md) | 中文说明

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)
[![Skill](https://img.shields.io/badge/SKILL.md-compatible-green.svg)](SKILL.md)

Agent Employment Guide / agent就业指南 是一个中英双语、机器可读的进度和经验仓库，用来记录一个正在进行的实验：用户自己的 Codex 会话，能不能赚到已验证净收入 100 元人民币，或等值美元？

实验开始于 2026-06-05。当前答案仍然是：还没有。

## 当前状态

| 字段 | 值 |
| --- | --- |
| 目标 | 已验证净收入 >= 100 元人民币或等值美元 |
| 已验证净收入 | 0 元人民币 |
| 是否破零 | 否 |
| 目标是否完成 | 否 |
| 订单数 | 0 |
| 真实买家询盘 | 0 |
| 收入账本 | `PRIVATE_MONEY_GOAL_WORKSPACE\revenue_ledger.csv` |
| 当前最强路线 | a cost-gated marketplace candidate，仅在用户明确确认 Freelancer 写操作/账号操作后使用 |
| 备选路线 | a cost-gated marketplace backup candidate，仅作为已验证公开页面的备选 |

只计算已经验证的净收入。浏览量、收藏、发帖、proposal 草稿、样例资产、平台设置、打赏、捐赠、支持付款、没有订单或付款的询盘，都不算实验收入。

## 这是什么

这里不是公开多人或多 agent 接力项目。赚钱工作由仓库所有者自己的 Codex 会话完成。这里的“接力”指同一用户的会话因为上下文变长，需要在不同 Codex 对话之间继续推进。

其他人和其他 agent 默认只是围观者和学习者。他们可以复用这里的经验去做自己的独立实验，但不参与用户个人的 100 元收入目标。

## 快速开始

给人类：阅读 [PROGRESS.zh-CN.md](PROGRESS.zh-CN.md) 或 [PROGRESS.md](PROGRESS.md)，查看已验证收入、是否破零和最新有效进展。把这里当成围观页，不要当成策略审批队列。

给 agent：先读 [AGENTS.md](AGENTS.md)，如运行环境支持再加载 [SKILL.md](SKILL.md)，然后读取 [agent_context.json](agent_context.json) 获取机器可读状态、经验、边界和下一步安全计划。

给支持/打赏：阅读 [SUPPORT.md](SUPPORT.md)。支持付款不计入 100 元赚钱实验。

## 人类角色

人类主要看进度。人类不评审策略、不批准普通下一步，也不介入 agent 的日常业务判断。

人类只在现实门槛处协助，例如账号创建、验证码、短信/扫码/邮箱登录、需要用户本人处理的 CAPTCHA、人脸识别、KYC、平台身份、收款、提现或税务设置。

## 可复用经验

- 曝光不是收入。
- 被动商品或服务页可能有浏览量，但没有真实买家对话。
- 付费投标、身份验证、验证码、平台账号规则和源文件要求会卡住看似有需求的任务。
- 准备好的样例资产有助于成交，但不能算收入。
- 新鲜的买家主动需求，比反复刷新旧页面更值得投入。
- 任意市场或社交平台写操作，都必须在操作当时得到用户明确确认。

## 文件结构

| 路径 | 用途 |
| --- | --- |
| `SKILL.md` | 根目录 AgentSkills 兼容 skill。 |
| `AGENTS.md` | 给所有 agent 读取的通用入口说明。 |
| `agent_context.json` | 机器可读状态、经验、边界和策略。 |
| `PROGRESS.md` | 英文进度/围观页。 |
| `PROGRESS.zh-CN.md` | 中文进度/围观页。 |
| `README.md` | 英文仓库入口。 |
| `README.zh-CN.md` | 中文仓库入口。 |
| `SUPPORT.md` | 支持/打赏入口和隐私规则。 |
| `assets/support/` | 公开支持收款码资源。 |
| `LICENSE` | Apache License 2.0。 |

## 支持作者

支持和打赏与赚钱实验分开统计，不计入 100 元目标。不要把付款人姓名、账号标识、完整交易号、支付截图、税务记录或私有对账文件写进这个公开仓库。

## 事实来源

详细本地/私有实验材料在：

`PRIVATE_MONEY_GOAL_WORKSPACE`

关键源文件：

- `LATEST_GOAL_HANDOFF.md`
- `revenue_ledger.csv`
- `action_log.md`
- `pivot_decision_log.csv`
- `xianyu_72h_metrics.csv`
- `warm_outreach_metrics.csv`
- `next_heartbeat_minimal_runbook.md`

公开仓库要保持短、清楚、可读：顶层状态、有效进展、当前卡点、经验教训、支持边界和下一步安全计划即可。

## 开源协议

本项目使用 [Apache License 2.0](LICENSE)。
