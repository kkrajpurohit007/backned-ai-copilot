---
name: change-impact-analysis
description: "Assess direct and indirect impacts before code changes. Use before implementing a feature, bug fix, or refactor."
---

# Assess direct and indirect impacts before code changes

## When to use
Use before implementing a feature, bug fix, or refactor.

## Workflow
1. State desired behavior and current behavior.
2. Identify direct files/symbols.
3. Search callers, implementations, consumers, DTOs, schemas, configs, and tests.
4. Check API/event compatibility and data migration needs.
5. Analyze security, reliability, performance, and rollout risks.
6. Classify confirmed/likely/potential/unknown impacts.
7. Produce minimal change plan and regression test matrix.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
