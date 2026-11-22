# Contract

## Capability
Recommend least-privilege MCP scopes from declared tool actions and flag wildcard or administrative access.

## Input root
`findings` with fields: tool, severity, users_affected, confidence.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
