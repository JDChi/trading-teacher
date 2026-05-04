---
name: maintain-trading-memory
description: Use when updating or consulting the learner's trading profile, remembered concepts, principles, preferences, misconceptions, risk habits, trading journals, or long-term learning state.
---

# Maintain Trading Memory

## Goal

Keep the user's long-term trading learning context accurate, useful, and separated by evidence type.

## Memory Files

- `memory/profile.md`: Background, goals, constraints, preferences, experience level, and risk context.
- `memory/concepts.md`: Concepts studied, mastery level, examples, confusions, and review status.
- `memory/principles.md`: Trading principles accepted, rejected, or being tested.
- `journals/`: Time-stamped trading thoughts, plans, reviews, and emotional observations.

## Memory Rules

- Do not store sensitive personal data unless the user explicitly provides it for learning context.
- Separate facts, preferences, principles, and hypotheses.
- Mark uncertain inferences as `待验证`, not as facts.
- Prefer concise updates over long transcripts.
- When a memory update would materially affect future coaching, tell the user what will be remembered.
- For `memory/concepts.md`, preserve the `Category` column and assign each concept to the concept category taxonomy below.

## Concept Category Taxonomy

Use these exact category names for `memory/concepts.md`:

- `数学与概率基础`: expectation, probability, simulation, statistical laws, win rate, odds, distributions.
- `策略范式与因子`: strategy families, factors, valuation frameworks, arbitrage logic, signal types.
- `风险与资金管理`: position sizing, drawdown, margin of safety, stop loss, asymmetric payoff, survival.
- `数据与验证工程`: data quality, cleaning, backtests, sample split, out-of-sample validation, cost modeling, strategy decay.
- `市场制度与交易机制`: exchange rules, settlement rules, price limits, taxes, fees, liquidity constraints, order execution mechanisms.
- `市场认知与交易哲学`: market behavior, participant psychology, reflexivity, fallibility, feedback loops, regime assumptions.
- `AI 辅助研究`: AI-assisted reading, coding, data processing, feature discovery, sentiment analysis, research automation.

If a concept spans multiple categories, choose the primary learning use case as `Category` and mention secondary context in `Notes` only when useful.

## Update Workflow

1. Decide whether the information is worth remembering.
2. Choose the correct destination file.
3. Write the memory as a dated bullet or table row.
4. Include source context when useful: conversation, material title, or journal date.
5. If updating a concept, include category and mastery status: `初识`, `理解中`, `可应用`, or `需复习`.

## Suggested Formats

For `memory/profile.md`:

`- YYYY-MM-DD: [事实/偏好/目标/约束] ...`

For `memory/concepts.md`:

`| Concept | Category | Status | Notes | Review Cue | Updated |`

For `memory/principles.md`:

`| Principle | Status | Rationale | Evidence/Source | Updated |`

For `journals/`:

Use `templates/trade-journal.md` unless the user provides another format.
