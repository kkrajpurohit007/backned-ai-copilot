---
name: code-review
description: "Conduct evidence-based review of a code diff. Use for pull requests, patches, or proposed changes."
---

# Conduct evidence-based review of a code diff

## When to use
Use for pull requests, patches, or proposed changes.

## Workflow
1. Read diff and surrounding code.
2. Validate behavior against requirements.
3. Check correctness, security, data integrity, concurrency, compatibility, resilience, performance, and maintainability.
4. Verify tests and coverage claims.
5. Report actionable findings with severity/evidence/fix.
6. Separate blockers from suggestions and note review limits.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
