---
name: architecture-analysis
description: "Analyze architecture and quality attribute trade-offs. Use for system design, architectural changes, or service boundaries."
---

# Analyze architecture and quality attribute trade-offs

## When to use
Use for system design, architectural changes, or service boundaries.

## Workflow
1. Map components, boundaries, interfaces, data ownership, and integrations.
2. Ground diagrams in repository evidence.
3. Identify quality attributes and constraints.
4. Compare viable options and trade-offs.
5. Recommend simplest fit; document ADR if meaningful.
6. Mark inferred deployment/runtime details.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
