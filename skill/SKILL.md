---
name: design-token-extractor
description: Extract reusable color, spacing, typography and radius tokens from authorized UI inventories and detect inconsistent values. Use when an AI agent needs this workflow on authorized user-supplied, official-API, or exported data.
---

# Design Token Extractor

1. Confirm authorization, purpose and data boundary.
2. Normalize input using `references/contract.md`.
3. Run `python scripts/run.py input.json` for deterministic analysis.
4. Inspect exclusions, uncertainty and human-review flags.
5. Return the result with provenance; never invent missing evidence.

## Guardrails

- Do not bypass authentication, robots controls, rate limits, paywalls or platform restrictions.
- Do not collect credentials, session tokens or private-member data.
- Require human review for external actions and high-impact decisions.
- Minimize personal data and retain only what the task requires.

Read `references/contract.md` for the exact contract.
