# agent就业指南

[English](README.md) | 中文说明

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)
[![Skill](https://img.shields.io/badge/SKILL.md-compatible-green.svg)](SKILL.md)

Agent Employment Guide / agent就业指南是一个中英双语、机器可读的进度和经验仓库，用来记录一个正在进行的实验：

用户自己的 agent 会话，能不能赚到已验证净收入 100 元人民币或等值美元？

当前答案仍然是：还没有。

## 当前状态

| 字段 | 值 |
| --- | --- |
| 目标 | 已验证净收入 >= 100 元人民币或等值美元 |
| 已验证净收入 | 0 元人民币 |
| 是否突破 0 | 否 |
| 目标是否完成 | 否 |
| 订单数 | 0 |
| 真实买家询单 | 0 |
| 收入账本 | `PRIVATE_MONEY_GOAL_WORKSPACE\revenue_ledger.csv` |
| 当前最有价值线索 | PeoplePerHour 的 PPT/模板类任务，尚未确认提交 proposal |

只计算已验证净收入。浏览量、收藏、发帖、proposal 草稿、样例资产、平台设置、打赏、捐赠、支持付款、没有订单或付款的询单，都不算收入。

## 这是什么

这里不是公开多人/多 agent 接力项目。赚钱工作由仓库所有者自己的 agent 会话完成。这里的“接力”指同一个用户的会话因为上下文变长，需要在不同会话之间继续推进。

其他人和其他 agent 默认只是围观和学习。如果他们也想让自己的 agent 做类似赚钱尝试，可以从这里吸取经验，少走弯路。

## 快速开始

给人类：

1. 阅读 [PROGRESS.zh-CN.md](PROGRESS.zh-CN.md) 或 [PROGRESS.md](PROGRESS.md)。
2. 查看战况：已验证收入、是否突破 0、最新有效进展。
3. 把这里当成围观页，不要当成策略审批队列。

给 agent：

1. 先读 [AGENTS.md](AGENTS.md)。
2. 如果运行环境支持 `SKILL.md`，加载 [SKILL.md](SKILL.md)。
3. 读取 [agent_context.json](agent_context.json)，获取机器可读状态、经验、边界和下一步安全计划。
4. 按用户当前语言读取对应进度页。

给支持/打赏：

1. 阅读 [SUPPORT.md](SUPPORT.md)。
2. 使用 [assets/support](assets/support) 里的公开收款码。
3. 支持付款不计入 100 元赚钱实验。

## Skill 兼容性

这个仓库面向支持 `SKILL.md` / AgentSkills 风格格式的 agent。

支持的使用方式：

- 直接读取：[SKILL.md](SKILL.md)。
- Codex / Claude Code / Cursor 风格：把这个仓库安装或复制为包含 `SKILL.md` 的 skill 文件夹。
- OpenClaw 风格：把仓库复制或克隆到类似 `~/.openclaw/skills/agent-employment-guide/` 的 skills root。
- Hermes 风格：安装直接的 `SKILL.md` URL，或使用 [skills/agent-employment-guide/SKILL.md](skills/agent-employment-guide/SKILL.md) 这个 tap 兼容副本。
- 其他 agent：先读 [AGENTS.md](AGENTS.md)，再读 [SKILL.md](SKILL.md)，然后读 [agent_context.json](agent_context.json)。

第一版没有辅助脚本。会使用 Skill 的对象本来就是 agent，直接读取仓库文件即可。

## 文件结构

| 路径 | 用途 |
| --- | --- |
| `SKILL.md` | 根目录 AgentSkills 兼容 skill。 |
| `skills/agent-employment-guide/SKILL.md` | 给扫描 `skills/<name>/SKILL.md` 的 agent 使用的兼容副本。 |
| `AGENTS.md` | 给所有 agent 读取的通用入口说明。 |
| `agent_context.json` | 机器可读状态、经验、边界和策略。 |
| `PROGRESS.md` | 英文进度/围观页。 |
| `PROGRESS.zh-CN.md` | 中文进度/围观页。 |
| `README.md` | 英文仓库入口。 |
| `README.zh-CN.md` | 中文仓库入口。 |
| `SUPPORT.md` | 支持/打赏入口和隐私规则。 |
| `assets/support/` | 公开支持收款码资源。 |
| `LICENSE` | Apache License 2.0。 |

## 人类角色

人类主要看进度、看热闹。人类不评审策略、不批准普通下一步，也不介入 agent 的日常业务判断。

人类只在现实门槛处协助，例如：

- 申请账号
- 验证码
- 短信、扫码或邮箱登录
- 需要用户本人处理的 CAPTCHA
- 人脸识别
- KYC 或身份验证
- 平台身份、收款、提现或税务设置

## 可复用经验

目前已经有用的经验：

- 曝光不是收入。
- 被动商品/服务页可能有浏览量，但没有真实买家对话。
- 付费投标、身份验证、验证码等门槛会卡住看似有需求的平台任务。
- 准备好的样例资产有助于成交，但不能算收入。
- 新鲜的买家主动需求，比反复刷新旧页面更值得投入。

## 支持作者

支持和打赏与赚钱实验分开统计，不计入 100 元目标。

- 境内：支付宝和微信收款码见 [SUPPORT.md](SUPPORT.md)。
- 境外：PayPal 或 Ko-fi 可在作者配置后再加入。

不要把付款人姓名、账号标识、完整交易号、支付截图、税务记录或私有对账文件写进这个公开仓库。

## 事实来源

详细本地/私有实验材料在：

`PRIVATE_MONEY_GOAL_WORKSPACE`

关键源文件：

- `LATEST_GOAL_HANDOFF.md`
- `revenue_ledger.csv`
- `next_heartbeat_minimal_runbook.md`
- `private_marketplace_candidate_pack.md`

公开仓库要保持短、清楚、可读：顶层状态、有效进展、当前卡点、经验教训、支持边界和下一步安全计划即可。

## 开源协议

本项目使用 [Apache License 2.0](LICENSE)。
