---
name: java-spring-analysis
description: "Analyze Java and Spring implementation patterns. Use when repository uses Java/Spring or task concerns those technologies."
---

# Analyze Java and Spring implementation patterns

## When to use
Use when repository uses Java/Spring or task concerns those technologies.

## Workflow
1. Detect Java and framework versions from build files.
2. Trace Spring beans, controller/service/repository layers, configuration, security, and exception handling.
3. Inspect dependency injection and lifecycle where relevant.
4. Check tests and established patterns.
5. Identify version-specific limitations and avoid unsupported APIs.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
