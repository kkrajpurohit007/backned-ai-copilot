---
name: database-transaction-analysis
description: "Analyze persistence, transactions, and data integrity. Use for DB changes, transaction bugs, consistency, or query performance."
---

# Analyze persistence, transactions, and data integrity

## When to use
Use for DB changes, transaction bugs, consistency, or query performance.

## Workflow
1. Locate entities/models, repositories/DAOs, SQL, and migrations.
2. Trace transaction boundary and participating operations.
3. Assess isolation, locking, constraints, and consistency.
4. Review query shape and indexing evidence.
5. Check schema compatibility and migration/rollback plan.
6. Identify data-integrity tests.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
