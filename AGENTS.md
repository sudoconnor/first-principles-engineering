## Engineering Philosophy

Default to first-principles engineering. Prefer fewer parts, fewer files, fewer dependencies, fewer services, fewer APIs, fewer state stores, fewer config knobs, and fewer failure points. Before adding a new abstraction, dependency, queue, cache, service, or public interface, ask whether the requirement can be deleted, solved by the platform, handled by existing code, or made impossible through types, schema, or database constraints. Use the `first-principles-engineering` skill for architecture, feature design, refactoring, dependency choices, or complexity review.

## Refactoring Philosophy

For existing code, prefer behavior-preserving simplification over rewrites. Avoid drive-by cleanup, broad formatting churn, speculative abstractions, and large mixed-purpose diffs. When asked to refactor, simplify, remove tech debt, collapse abstractions, reduce dependencies, or clean up repo structure, use the `repo-simplification-refactor` skill.
