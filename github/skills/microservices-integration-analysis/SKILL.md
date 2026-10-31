---
name: microservices-integration-analysis
description: "Trace service-to-service and messaging interactions. Use for distributed flows, API contracts, events, or integration failures."
---

# Trace service-to-service and messaging interactions

## When to use
Use for distributed flows, API contracts, events, or integration failures.

## Workflow
1. Identify clients, producers, consumers, contracts, and configuration keys.
2. Trace request/event lifecycle and data transformations.
3. Inspect timeout, retry, circuit-breaker, idempotency, ordering, and DLQ behavior.
4. Assess contract and deployment compatibility.
5. Map failure modes and observability.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
