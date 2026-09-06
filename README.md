# Factory Fixture

This repository is a public fixture for bounded autonomous engineering software factory runs.

It exists to validate and exercise autonomous engineering workflows that operate within explicit, bounded run constraints, such as:

- A declared repository contract and writable scope
- Required validation checks and non-goal boundaries
- Draft pull requests targeting a default branch, without merge or deployment authority
- Public, read-only model policies that propose changes for review

Because it is a public fixture, all content is suitable for public exposure. It intentionally contains no private context, dependencies, workflows, source code, or configuration beyond the repository contract that governs each run.

The fixture is designed to be simple, predictable, and safe: autonomous runs may propose changes only within the declared writable scope, and every run is validated against the repository's required checks before result publication.

Use this repository to smoke-test factory tooling, validate run semantics, and develop fixtures for bounded autonomous engineering software factory runs.
