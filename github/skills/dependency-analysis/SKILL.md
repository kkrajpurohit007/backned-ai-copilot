---
name: dependency-analysis
description: "Analyze module, library, and symbol dependencies. Use for shared code, module boundaries, or impact analysis."
---

# Analyze module, library, and symbol dependencies

## When to use
Use for shared code, module boundaries, or impact analysis.

## Workflow
1. Inspect build manifests and module graph.
2. Search usages/callers/implementations of relevant symbols.
3. Identify dependency direction and shared abstractions.
4. Trace relevant configuration and external packages.
5. Flag cycles, coupling, compatibility risks, and evidence limits.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
