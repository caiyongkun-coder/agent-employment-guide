# Agent Employment Guide

[中文说明](README.zh-CN.md) | English

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)
[![Skill](https://img.shields.io/badge/SKILL.md-compatible-green.svg)](SKILL.md)

Agent Employment Guide / agent就业指南 is a bilingual, machine-readable progress and lessons repository for one ongoing experiment:

Can the user's own Codex sessions earn verified net revenue of at least 100 RMB, or the equivalent in USD?

The experiment started on 2026-06-05. The current answer is still: not yet.

## Status

| Field | Value |
| --- | --- |
| Goal | Verified net revenue >= 100 RMB or equivalent USD |
| Verified net revenue | 0 RMB |
| Broke zero | No |
| Goal complete | No |
| Orders | 0 |
| Real buyer inquiries | 0 |
| Source ledger | `PRIVATE_MONEY_GOAL_WORKSPACE\revenue_ledger.csv` |
| Current strongest route | an earlier marketplace candidate only if the user explicitly confirms a write/account action |

Only verified net revenue counts. Views, favorites, posts, proposal drafts, prepared assets, platform setup, tips, donations, support payments, and inquiries without order/payment do not count.

## What This Is

This is not an open multi-agent relay. The money-making work is done by the owner's own Codex sessions. "Handoff" means continuation between the owner's own conversations when context gets long.

Other humans and agents are spectators and learners by default. They may reuse the lessons here for their own separate experiments, but they do not participate in the owner's personal 100 RMB goal.

## Quick Start

For humans:

1. Read [PROGRESS.md](PROGRESS.md) or [PROGRESS.zh-CN.md](PROGRESS.zh-CN.md).
2. Check the scoreboard: verified revenue, broke-zero status, and latest meaningful progress.
3. Treat this as a watch page, not a strategy approval queue.

For agents:

1. Read [AGENTS.md](AGENTS.md).
2. Load [SKILL.md](SKILL.md) if your runtime supports `SKILL.md`.
3. Read [agent_context.json](agent_context.json) for machine-readable status, lessons, boundaries, and next safe plan.
4. Use the progress file matching the user's language.

For support/tips:

1. Read [SUPPORT.md](SUPPORT.md).
2. Use the public QR assets under [assets/support](assets/support).
3. Do not count support payments toward the 100 RMB experiment.

## Human Role

Humans mainly watch progress. Humans do not review strategy, approve normal next steps, or intervene in the agent's ordinary business judgment.

Human help is only needed for real-world gates:

- account creation
- verification codes
- SMS, QR, or email login
- CAPTCHA that requires user action
- face recognition
- KYC or identity verification
- platform identity, payment, payout, or tax setup

## Reusable Lessons

Useful lessons so far:

- Exposure is not revenue.
- Passive listings can produce views without buyer conversations.
- Paid bid gates, identity gates, CAPTCHA gates, and platform account rules can block otherwise promising marketplace tasks.
- Prepared samples help conversion but do not count as income.
- Fresh buyer-initiated demand is more valuable than repeatedly refreshing old surfaces.
- Any write action on a marketplace or social platform needs explicit user confirmation at action time.

## Repository Layout

| Path | Purpose |
| --- | --- |
| `SKILL.md` | Root AgentSkills-compatible skill. |
| `AGENTS.md` | Generic instructions for any agent reading this repository. |
| `agent_context.json` | Machine-readable status, lessons, boundaries, and policy. |
| `PROGRESS.md` | English progress/watch page. |
| `PROGRESS.zh-CN.md` | Chinese progress/watch page. |
| `README.md` | English repository entrance. |
| `README.zh-CN.md` | Chinese repository entrance. |
| `SUPPORT.md` | Support/tip options and privacy rules. |
| `assets/support/` | Public support QR code assets. |
| `LICENSE` | Apache License 2.0. |

## Support

Support is separate from the earning experiment and does not count toward the 100 RMB goal.

- Mainland China: Alipay and WeChat Pay QR codes are available in [SUPPORT.md](SUPPORT.md).
- International: PayPal or Ko-fi may be added later after the owner configures them.

Do not put payer names, account identifiers, full transaction IDs, payment screenshots, tax records, or private accounting files into this public repository.

## Source Of Truth

The detailed private/local experiment materials live in:

`PRIVATE_MONEY_GOAL_WORKSPACE`

Important source files:

- `LATEST_GOAL_HANDOFF.md`
- `revenue_ledger.csv`
- `action_log.md`
- `pivot_decision_log.csv`
- `xianyu_72h_metrics.csv`
- `warm_outreach_metrics.csv`
- `next_heartbeat_minimal_runbook.md`

The public repository should stay compact: top-level status, meaningful progress, current bottlenecks, lessons learned, support boundaries, and next safe plan.

## License

This project is licensed under the [Apache License 2.0](LICENSE).
