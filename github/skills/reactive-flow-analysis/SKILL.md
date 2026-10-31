---
name: reactive-flow-analysis
description: "Analyze reactive execution and publisher semantics. Use for Reactor, WebFlux, reactive streams, or async pipeline issues."
---

# Analyze reactive execution and publisher semantics

## When to use
Use for Reactor, WebFlux, reactive streams, or async pipeline issues.

## Workflow
1. Trace publisher construction and subscription boundaries.
2. Explain operator semantics and sequencing.
3. Identify blocking calls, scheduler changes, shared mutable state, cancellation, and backpressure.
4. Trace error propagation and context.
5. Check transaction semantics.
6. Recommend StepVerifier-based tests where applicable.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
