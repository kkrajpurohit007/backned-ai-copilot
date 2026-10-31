---
name: repository-discovery
description: "Discover and map an unfamiliar repository. Use when entering a repository or locating relevant modules/files."
---

# Discover and map an unfamiliar repository

## When to use
Use when entering a repository or locating relevant modules/files.

## Workflow
1. Read repository instructions and top-level structure.
2. Detect language, build tool, modules, entry points, source/test roots.
3. Inspect build/dependency manifests, config, migrations, API specs, CI/deploy files.
4. Search for the task's domain terms and likely entry points.
5. Follow imports/calls only for relevant paths.
6. Record file path, symbol, role, and evidence.
7. Mark unknowns and scope limits.

## Evidence and safety
Use repository paths and symbols as evidence. Do not invent details or reveal secrets. Mark verified facts, inferences, assumptions, and unknowns. Remain read-only unless implementation is explicitly requested.

## Expected output
A concise, evidence-based analysis with findings, risks, next steps, and validation appropriate to the task.
