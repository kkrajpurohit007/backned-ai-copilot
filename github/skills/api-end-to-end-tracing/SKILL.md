---
name: api-end-to-end-tracing
description: "Trace API request-to-response behavior. Use for endpoint analysis, API changes, and debugging."
---

# Trace API request-to-response behavior

## When to use
Use for endpoint analysis, API changes, and debugging.

## Workflow
1. Locate route/controller/router and HTTP method/path.
2. Trace request DTO, parsing, validation, authentication, authorization.
3. Follow service/domain calls and meaningful branches.
4. Trace persistence, transactions, external calls, and messages.
5. Follow error mapping and response serialization.
6. Include success, alternate, and failure paths.
7. Produce a sequence diagram and evidence table.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
