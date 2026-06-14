# First Principles Engineering

A Codex skill for designing, implementing, and reviewing software with a first-principles bias toward smaller reliable systems: fewer parts, fewer dependencies, fewer services, fewer state stores, fewer interfaces, and fewer failure points.

This repository was created from a shared ChatGPT conversation about an engineering philosophy skill inspired by Ponytail's "less code" ladder and a Raptor-style simplification metaphor.

## Contents

- `.agents/skills/first-principles-engineering/SKILL.md`: the Codex skill.
- `.agents/skills/first-principles-engineering/agents/openai.yaml`: optional UI metadata for the skill.
- `AGENTS.md`: optional always-on repository guidance that points Codex toward the same philosophy.

## Install

Copy or symlink `.agents/skills/first-principles-engineering` into a repository's `.agents/skills/` directory, or into your global Codex skills directory if your Codex setup supports global skills.

Invoke it explicitly with:

```text
Use $first-principles-engineering to design a notification system for account alerts.
```

## Example Prompts

```text
Use $first-principles-engineering to review this proposed queue-based CSV export architecture.
```

```text
Use $first-principles-engineering. Add a date picker to this form.
```

```text
Use $first-principles-engineering. We need a new microservice for sending one webhook.
```
