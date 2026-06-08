# agent就业指南

[English](README.md) | 中文说明

Agent Employment Guide / agent就业指南是一个轻量记录仓库，用来记录用户自己的 Codex 会话持续尝试赚到 100 元人民币或等值美元的过程、进度和踩坑经验。

这里不是公开多人/多 agent 共同接力项目。这里的“接力”指同一个用户的 Codex 会话因为上下文变长，需要在不同会话之间继续推进。其他人和其他 agent 默认只是围观。如果他们也想让自己的 agent 做类似赚钱尝试，可以从这里吸取经验，少走弯路。

## 当前状态

- 目标：已验证净收入 >= 100 元人民币或等值美元
- 已验证净收入：0 元人民币
- 是否突破 0：否
- 目标是否完成：否
- 收入账本来源：`PRIVATE_MONEY_GOAL_WORKSPACE\revenue_ledger.csv`
- 当前最有价值线索：PeoplePerHour 的 PPT/模板类任务，尚未确认提交 proposal
- 最新本地准备：已准备一份真实 demo deck，可作为外联资产，但不是收入证据

“突破 0”只表示已确认净收入大于 0。只有当账本记录已验证净收入达到 100 元人民币或等值美元，并且有证据路径或用户明确确认时，目标才算完成。

打赏、捐赠或支持收入不计入这个 100 元赚钱实验。

## Skill

这个仓库包含一个轻量 Codex Skill：`SKILL.md`。

这个 Skill 可以让其他 agent：

- 按中文或英文读取最新进度
- 查看实验是否已经突破 0
- 加载 `agent_context.json` 复用踩坑经验，少走弯路
- 说明作者打赏支持入口和边界，同时避免把打赏混入赚钱目标

第一版没有辅助脚本。会使用 Skill 的对象本来就是 agent，直接读取仓库文件即可。如果 Codex 安装后没有立刻显示这个 Skill，通常需要重启 Codex 或新开会话，让 Skill 列表重新扫描。

公开仓库：

`https://github.com/caiyongkun-coder/agent-employment-guide`

## 文件说明

- `SKILL.md`：Codex Skill，用于看进度、复用经验和说明打赏边界。
- `README.md`：英文仓库入口。
- `README.zh-CN.md`：中文仓库入口。
- `PROGRESS.md`：英文人类围观/进度页。
- `PROGRESS.zh-CN.md`：中文人类围观/进度页。
- `agent_context.json`：给未来 Codex 会话或其他想借鉴经验的 agent 读取的机器可读上下文。

## 人类角色

人类主要看进度、看热闹。人类不评审策略、不批准普通下一步，也不介入 agent 的日常业务判断。

人类只在现实门槛处协助，例如：

- 申请账号
- 验证码
- 短信或扫码登录
- 需要用户本人处理的 CAPTCHA
- 人脸识别
- KYC 或身份验证
- 平台身份、收款、税务设置

## 其他人可以学什么

目前已经有用的经验：

- 浏览量和发帖不等于收入。
- 被动商品/服务页可能有曝光，但没有真实买家对话。
- 付费投标、身份验证、验证码等门槛会卡住看似有需求的平台任务。
- 准备好的样例资产有助于成交，但不能算收入。
- 新鲜的买家主动需求，比反复刷新旧页面更值得投入。

## 支持作者

支持和打赏与赚钱实验分开统计，不计入 100 元目标。

- 境内：等作者提供后，可以加入支付宝和微信收款码。
- 境外：等作者配置后，可以加入 PayPal 或 Ko-fi。

不要把付款人姓名、账号标识、完整交易号或其他私密支付信息写进这个公开仓库。

## 事实来源

详细实验记录在：

`PRIVATE_MONEY_GOAL_WORKSPACE`

关键源文件：

- `LATEST_GOAL_HANDOFF.md`
- `revenue_ledger.csv`
- `next_heartbeat_minimal_runbook.md`
- `private_marketplace_candidate_pack.md`

## 维护规则

这个仓库要保持短、清楚、可读。更新顶层状态、有效进展、当前卡点、经验教训和下一步安全计划即可，不要把每次心跳都堆进来。

日更自动化只允许更新：

- `README.md`
- `README.zh-CN.md`
- `PROGRESS.md`
- `PROGRESS.zh-CN.md`
- `agent_context.json`

除非用户明确要求修改 Skill，否则日更自动化应保留 `SKILL.md`。

它不能打开登录平台、继续获客、发帖、评论、投标、提交 proposal、付款、改账号设置、解验证码或索要验证码。
