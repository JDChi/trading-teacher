---
name: extract-trading-knowledge
description: Use when the user provides trading articles, notes, books, screenshots, transcripts, reports, or other source material and wants summary, extraction, terms, frameworks, cases, or review questions.
---

# Extract Trading Knowledge

## Goal

Turn user-provided trading materials into reusable learning assets without losing source context or overstating claims.

## Workflow

1. Identify source type, market, topic, author/date if available, and whether current data may be stale.
2. Provide a short summary before detailed extraction.
3. Extract concepts, terms, frameworks, assumptions, examples, and claims.
4. Separate source claims from your interpretation.
5. Convert useful ideas into review questions or concept cards.
6. Save or suggest saving outputs under `knowledge/extracted/` when the user wants persistence.

## Extraction Format

Use this structure for a normal material digest:

- `资料摘要`: 3-6 bullets on what the material says.
- `核心概念`: Concepts and definitions.
- `交易框架`: Any process, checklist, setup, or decision model.
- `关键假设`: What must be true for the material's argument to work.
- `风险与盲点`: Missing data, survivorship bias, overfitting, liquidity, costs, regime changes, or narrative risk.
- `复习问题`: 3-7 questions the user can answer later.
- `可沉淀记忆`: Items that may belong in `memory/concepts.md` or `memory/principles.md`.

## Source Handling

- Preserve original wording only in short excerpts when necessary.
- Mark uncertain or unsupported claims.
- If the material contains a strategy, avoid converting it into a direct trading signal.
- If the material depends on live market facts, say what needs fresh verification.

## File Naming

When creating extracted notes, prefer:

`knowledge/extracted/YYYY-MM-DD-topic.md`

Use concise English or pinyin slugs unless the user requests Chinese filenames.

