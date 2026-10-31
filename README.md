# Backend Intelligence Copilot

A reusable GitHub Copilot customization kit for backend repository discovery, reverse engineering, task impact analysis, implementation, review, and engineering mentorship.

## Start here

1. Copy `.github/` into the root of a repository.
2. In Copilot Chat, select **Backend Intelligence** from the agent picker.
3. Run `.github/prompts/analyze-new-task.prompt.md` (or use the prompt: `Analyze this task before coding: ...`).
4. Review the analysis and explicitly approve implementation when ready.

## Default behavior

The system is analysis-first. It does not modify application code unless you explicitly request implementation. It distinguishes verified evidence, inference, assumptions, and unknowns.

## Contents

- `.github/agents/` — primary agent and specialists
- `.github/skills/` — reusable workflow skills
- `.github/prompts/` — task prompt collection
- `.github/copilot-instructions.md` — repository-wide rules

## Reuse across repositories

Copy `.github/skills/` and the relevant prompts into other repositories. Keep repository-specific facts (module names, architecture notes, API inventory) in that repository rather than hardcoding them into reusable agents.

## Notes

Copilot features and supported customization paths can vary by IDE and version. Verify the current GitHub Copilot documentation for your environment. This kit does not itself activate an agent or create a remote GitHub repository.
