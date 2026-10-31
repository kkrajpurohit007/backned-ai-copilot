---
name: aws-infrastructure-analysis
description: "Analyze AWS and deployment configuration from repository evidence. Use when AWS, containers, CI/CD, or infrastructure is involved."
---

# Analyze AWS and deployment configuration from repository evidence

## When to use
Use when AWS, containers, CI/CD, or infrastructure is involved.

## Workflow
1. Inspect IaC, manifests, pipelines, Dockerfiles, and app integrations.
2. Identify configured resources and connectivity.
3. Analyze IAM, secrets, network boundaries, scaling, availability, and monitoring.
4. Separate proven configuration from runtime inference.
5. Never reveal secret values or deploy/change infrastructure without approval.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
