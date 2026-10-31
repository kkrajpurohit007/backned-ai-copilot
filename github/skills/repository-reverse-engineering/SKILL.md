---
name: repository-reverse-engineering
description: "Reverse-engineer repository behavior from source evidence. Use when repository purpose, architecture, or behavior is unfamiliar."
---

# Reverse-engineer repository behavior from source evidence

## When to use
Use when repository purpose, architecture, or behavior is unfamiliar.

## Workflow
1. Start with repository discovery.
2. Identify runtime entry points and module boundaries.
3. Trace representative flows and shared abstractions.
4. Inspect configuration and tests as corroborating evidence.
5. Produce a map of responsibilities, dependencies, and flows.
6. Separate source facts from deployment/runtime assumptions.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
