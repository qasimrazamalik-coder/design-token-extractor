# Contract

## Capability
Extract reusable color, spacing, typography and radius tokens from authorized UI inventories and detect inconsistent values.

## Input root
`items` with fields: value, property, component.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
