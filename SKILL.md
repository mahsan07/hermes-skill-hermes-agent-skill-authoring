---
name: hermes-skill-hermes-agent-skill-authoring
description: Create focused Hermes SKILL.md packages with valid metadata and reusable workflows. Use when a user asks for this workflow or a closely related task.
---

# Hermes Agent Skill Authoring

Author compact, reusable Hermes `SKILL.md` packages. Keep triggering metadata precise and move optional detail into directly linked references or scripts.

## Workflow

1. Gather concrete user requests that should trigger the skill and define non-goals.
2. Choose a lowercase hyphenated name under 64 characters.
3. Write YAML frontmatter containing only `name` and `description`; put all trigger conditions in `description`.
4. Write imperative workflow instructions with explicit safety boundaries and verification.
5. Add scripts only for deterministic repeated work and references only for detail that need not load every time.
6. Validate frontmatter, naming, links, and representative examples.
7. Remove personal names, private endpoints, credentials, and environment-specific assumptions before sharing.

Keep the core body under 500 lines and avoid README-like process history inside the skill itself.
