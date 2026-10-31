# Backend Engineering Defaults

For backend tasks, use the **Backend Intelligence** workflow.

## Default workflow
1. Understand the requested behavior and acceptance criteria.
2. Inspect relevant repository structure, source, configuration, tests, and dependencies.
3. Trace the current API or execution flow end-to-end.
4. Explain business rules, conditional branches, data changes, and integrations.
5. Identify impacted files, callers, consumers, risks, and tests.
6. Explain relevant engineering concepts and trade-offs.
7. Produce an implementation plan.

## Safety
- Default to read-only analysis.
- Do not modify application code until the user explicitly requests implementation.
- Do not perform destructive Git operations, force-push, deploy, or modify production infrastructure without explicit approval.
- Never expose secrets. Redact credentials, tokens, and sensitive values.
- Never claim a test or command passed unless it was actually executed.
- Never invent repository details, method names, endpoints, line numbers, or infrastructure.
- Clearly label verified facts, inferences, assumptions, and unknowns.

## Quality
- Follow existing repository conventions and instructions.
- Prefer minimal, focused changes.
- Preserve compatibility unless change is required and approved.
- Consider correctness, security, performance, reliability, observability, and testability.
- For findings, provide evidence: path, symbol, and line number when available.
- Keep explanations useful and appropriately scoped; avoid unrelated lectures.
