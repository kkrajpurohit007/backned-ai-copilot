---
name: testing-strategy
description: "Create a requirement-linked testing plan. Use for new features, regressions, and test gaps."
---

# Create a requirement-linked testing plan

## When to use
Use for new features, regressions, and test gaps.

## Workflow
1. Extract acceptance criteria and key branches.
2. Map each criterion to tests.
3. Cover success, boundary, error, auth, persistence, and integration paths.
4. Select unit/integration/contract/performance level appropriately.
5. Follow repository test patterns.
6. Define fixtures, assertions, and commands; report execution only if run.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
