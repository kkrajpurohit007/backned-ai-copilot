---
name: business-logic-analysis
description: "Extract business rules and conditions from code. Use when business behavior must be understood or changed."
---

# Extract business rules and conditions from code

## When to use
Use when business behavior must be understood or changed.

## Workflow
1. Find domain entry points and rule-bearing methods.
2. Record predicates, thresholds, state changes, calculations, defaults, and errors.
3. Inspect called methods and relevant tests.
4. Translate each rule into plain language.
5. Identify edge cases and invariants.
6. Mark policy assumptions and unresolved questions.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
