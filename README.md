# Engineering Codex Skills

Codex skills for designing, implementing, reviewing, and refactoring software with a first-principles bias toward smaller reliable systems: fewer parts, fewer dependencies, fewer services, fewer state stores, fewer interfaces, and fewer failure points.

This repository was created from shared ChatGPT conversations about engineering philosophy skills inspired by Ponytail's "less code" ladder and a Raptor-style simplification metaphor.

## Contents

- `.agents/skills/first-principles-engineering/SKILL.md`: the Codex skill.
- `.agents/skills/repo-simplification-refactor/SKILL.md`: a behavior-preserving refactor skill for existing repos.
- `.agents/skills/first-principles-engineering/agents/openai.yaml`: optional UI metadata for the skill.
- `AGENTS.md`: optional always-on repository guidance that points Codex toward the same philosophy.

## Install

Copy or symlink one of the folders under `.agents/skills/` into a repository's `.agents/skills/` directory, or into your global Codex skills directory if your Codex setup supports global skills.

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

```text
Use $repo-simplification-refactor in inspection mode. Find the best first Raptor-style simplification pass in this repo. Do not edit files yet.
```

```text
Use $repo-simplification-refactor in surgical mode. Collapse this interface with one implementation if it is safe. Preserve behavior and run the focused tests.
```
