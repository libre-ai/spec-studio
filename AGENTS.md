# Spec Studio Canonical Agent Rules

## Purpose

Spec Studio turns product teams' scattered conversations into versioned decisions, specifications, and traceable handoffs, so every acceptance is recorded instead of lost in transit. It is the couche-1 spec workshop of the constellation, contract-first by design.
Doctrine lives upstream: https://raw.githubusercontent.com/libre-ai/governance/main/docs/README.md

## Domain doctrine

- No product truth outside this repository — spec packages and their acceptances are versioned here, never elsewhere.
- No anonymous editing — author/approver separation is enforced end-to-end.
- Bricks and contracts this repo depends on (`libre-ai/data`, `libre-ai/web-platform`, `libre-ai/testing`, `libre-ai/contracts`) are consumed pinned, never redefined here.

## Commands

- `bun install` — install workspace dependencies.
- `bun run test` — install and run the `apps/specifications` test suite.
- `bun run lint` — `biome ci .`.
- `bun run check` — the aggregate gate chain (toolchain, tests, secret scan, personal-data boundary, lint) — run before pushing.

## Working here

- Security > quality > performance > completeness, in that order on conflict.
- Check real state before editing: `git status --short` and `bun run test`.
- English for code, comments and this file; French stays the human conversation language elsewhere.
- Never commit a machine-local absolute filesystem path; use repo-relative paths or `~` instead.
