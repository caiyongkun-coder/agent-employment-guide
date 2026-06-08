---
name: agent-employment-guide
description: Use when a user asks about Agent Employment Guide, agent就业指南, an agent earning-100-RMB experiment, whether it broke zero, reusable lessons, or support/tip options for the author.
---

# Agent Employment Guide

Agent Employment Guide / agent就业指南 is an AgentSkills-compatible `SKILL.md` for one ongoing experiment: the owner's own agent sessions are trying to earn verified net revenue of at least 100 RMB or the equivalent in USD.

This skill reads the public guide, explains progress, and helps other agents reuse lessons for their own separate experiments. It does not join, control, or extend the original owner's revenue goal.

## Compatibility

This file follows the common `SKILL.md` pattern: YAML frontmatter with `name` and `description`, followed by Markdown instructions.

It is intended for any agent that can read `SKILL.md`, including Codex, OpenClaw, Hermes, Claude Code, Cursor, and similar agent runtimes.

Install or use it in whichever way your runtime supports:

- Direct file: read this root `SKILL.md`.
- Skill folder: clone this repository as a folder named `agent-employment-guide` under your skills directory.
- Tap-style layout: use `skills/agent-employment-guide/SKILL.md`.
- Manual fallback: read `AGENTS.md`, then this file, then `agent_context.json`.

## Source Files

Use the newest available copy of the repository.

- Public repository: `https://github.com/caiyongkun-coder/agent-employment-guide`
- If GitHub is available, prefer the latest repository files.
- If GitHub is unavailable, read the files adjacent to this `SKILL.md`.
- On the original maintainer's workstation, the local development repo is `LOCAL_REPOSITORY_CLONE`.
- Do not invent a missing payment link, QR code, revenue amount, order, or buyer signal.

Key files:

- `PROGRESS.zh-CN.md`: Chinese watch/progress page.
- `PROGRESS.md`: English watch/progress page.
- `agent_context.json`: machine-readable status, lessons, boundaries, and next safe plan.
- `SUPPORT.md`: support/tip options and privacy rules.
- `AGENTS.md`: generic instructions for any agent runtime.
- `README.zh-CN.md` and `README.md`: repository positioning and file guide.

## Language

Answer in the user's current language.

- Chinese user: read and summarize `PROGRESS.zh-CN.md`.
- English user: read and summarize `PROGRESS.md`.
- If language is unclear, follow the current conversation language or give a short bilingual status.

Always cross-check progress claims against `agent_context.json` when available.

## Watch Progress

When the user asks for the latest status, whether the experiment broke zero, or whether the 100 RMB goal is complete:

1. Read the matching `PROGRESS.*` file.
2. Read `agent_context.json`.
3. Report:
   - verified net revenue
   - whether revenue has broken zero
   - whether the 100 RMB or equivalent USD goal is complete
   - latest meaningful progress
   - current bottleneck or best lead
4. State clearly that views, posts, drafts, prepared assets, platform setup, tips, donations, support payments, and inquiries without order/payment are not experiment revenue.

## Learn From The Guide

When another user wants their own agent to try earning money:

1. Read `agent_context.json`.
2. Summarize reusable lessons, failed paths, hard gates, and current better leads.
3. Help the user design their own separate experiment.
4. Do not imply that they are joining the original owner's goal, accounts, ledgers, assets, or platform sessions.

## Support The Author

Support/tips are separate from the 100 RMB earning experiment.

1. Read `SUPPORT.md`.
2. Use the public QR assets only if the user asks how to support the author.
3. Do not count tips, donations, or support payments toward the 100 RMB experiment goal.
4. Do not store or ask for payer names, account identifiers, full transaction IDs, payment screenshots, tax records, or other private payment details in the public repository or conversation.
5. If the user asks to build formal Alipay ordering, callbacks, reconciliation, H5/App/scan payment, or other payment-product integration, use an Alipay payment integration skill if available and follow its confirmation gates.

## Boundaries

This skill is read-only with respect to the earning experiment.

Do not:

- log in to platforms
- post, comment, bid, submit proposals, or message buyers
- pay for bids, memberships, deposits, promotion, guarantees, or credits
- change account, profile, payment, payout, or tax settings
- solve CAPTCHA or request verification codes
- fabricate experience, orders, payments, revenue, or evidence
- use the original owner's accounts, paths, private assets, or ledgers for another user's experiment

If real-world account, identity, payment, tax, KYC, face recognition, SMS, QR login, or CAPTCHA gates appear, tell the user these require human handling.
