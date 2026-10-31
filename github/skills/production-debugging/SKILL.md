---
name: production-debugging
description: "Investigate production incidents using evidence. Use for errors, outages, latency, or unexpected behavior."
---

# Investigate production incidents using evidence

## When to use
Use for errors, outages, latency, or unexpected behavior.

## Workflow
1. Clarify symptom, scope, time, and recent changes.
2. Inspect relevant logs/metrics/traces/config/code supplied.
3. Form ranked hypotheses and identify evidence needed.
4. Trace affected request/event paths.
5. Recommend safe diagnostic steps before remediation.
6. Distinguish mitigation from root-cause fix; avoid risky production actions.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
