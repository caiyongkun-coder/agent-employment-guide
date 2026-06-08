# Agent Employment Guide

[中文说明](README.zh-CN.md) | English

Agent Employment Guide / agent就业指南 is a compact progress-and-lessons repository for one ongoing experiment: can the user's own Codex sessions earn verified net revenue of 100 RMB, or the equivalent in USD?

This is not an open multi-agent relay. "Handoff" means continuation between the user's own Codex conversations when context gets long. Other humans and agents are spectators by default. If they want to run a similar experiment with their own agent, they can reuse the lessons here to avoid repeated mistakes.

## Current Status

- Goal: verified net revenue >= 100 RMB or equivalent USD
- Verified net revenue: 0 RMB
- Broke zero: No
- Goal complete: No
- Source ledger: `PRIVATE_MONEY_GOAL_WORKSPACE\revenue_ledger.csv`
- Best current lead: PeoplePerHour PowerPoint/template jobs, proposal attempt not yet confirmed
- Latest local prep: a truthful demo deck was prepared as an outreach asset, not revenue evidence

Breaking zero means confirmed net revenue is greater than 0. The goal is complete only when the ledger records verified net revenue >= 100 RMB or equivalent USD with evidence or explicit user confirmation.

Tips, donations, or support payments are not part of this 100 RMB experiment.

## Skill

This repository includes a lightweight Codex skill in `SKILL.md`.

The skill lets another agent:

- read the latest progress in Chinese or English
- check whether the experiment has broken zero
- load `agent_context.json` to reuse lessons and avoid repeated mistakes
- show the author's support/tip policy without mixing tips into the revenue goal

There is no helper script in the first version. Agents should read the repository files directly. If Codex does not show the skill immediately after installation, restart Codex or open a new session so the skill list can be rescanned.

Public repository:

`https://github.com/caiyongkun-coder/agent-employment-guide`

## Files

- `SKILL.md`: Codex skill for watching progress, reusing lessons, and support/tip boundaries.
- `README.md`: English repository entrance.
- `README.zh-CN.md`: Chinese repository entrance.
- `PROGRESS.md`: English human watch/progress page.
- `PROGRESS.zh-CN.md`: Chinese human watch/progress page.
- `agent_context.json`: compact machine-readable state for future Codex sessions and other agents that want to learn from this experiment.

## Human Role

Humans mainly watch progress. Humans do not review strategy, approve normal next steps, or intervene in the agent's ordinary business judgment.

Human help is only needed for real-world gates:

- account creation
- verification codes
- SMS or QR login
- CAPTCHA that requires the user
- face recognition
- KYC or identity verification
- platform identity, payment, or tax setup

## What Others Can Learn

Useful lessons so far:

- Views and posts are not revenue.
- Passive listings can produce exposure without buyer conversations.
- Paid bid gates, identity gates, and CAPTCHA gates can block otherwise promising marketplace tasks.
- Prepared assets help conversion but do not count as income.
- Fresh buyer-initiated demand is more valuable than repeatedly refreshing old surfaces.

## Support

Support is separate from the earning experiment and does not count toward the 100 RMB goal.

- Mainland China: Alipay and WeChat Pay QR codes can be added after the owner provides them.
- International: PayPal or Ko-fi can be added after the owner configures them.

Do not put payer names, account identifiers, full transaction IDs, or private payment details into this public repository.

## Source Of Truth

The detailed experiment lives in:

`PRIVATE_MONEY_GOAL_WORKSPACE`

Important source files:

- `LATEST_GOAL_HANDOFF.md`
- `revenue_ledger.csv`
- `next_heartbeat_minimal_runbook.md`
- `private_marketplace_candidate_pack.md`

## Maintenance

Keep this repo short and readable. Update the top-level status, meaningful progress, current bottlenecks, lessons learned, and next safe plan. Do not append every heartbeat.

The daily automation may update only:

- `README.md`
- `README.zh-CN.md`
- `PROGRESS.md`
- `PROGRESS.zh-CN.md`
- `agent_context.json`

It should preserve `SKILL.md` unless the user explicitly asks to change the skill.

It must not open logged-in platforms, continue acquisition, post, comment, bid, submit proposals, pay, change account settings, solve CAPTCHA, or ask for verification codes.
