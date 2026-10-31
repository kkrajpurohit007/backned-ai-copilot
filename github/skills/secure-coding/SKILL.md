---
name: secure-coding
description: "Perform defensive backend security analysis. Use for security-sensitive code, API authorization, data handling, or review."
---

# Perform defensive backend security analysis

## When to use
Use for security-sensitive code, API authorization, data handling, or review.

## Workflow
1. Identify trust boundaries and sensitive data.
2. Check authentication and authorization at object/action level.
3. Inspect validation, injection, SSRF, secrets, token lifecycle, crypto, and logging.
4. Map findings to code evidence and realistic impact.
5. Recommend mitigations and security tests.
6. Redact secrets and avoid unsafe exploit detail.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
