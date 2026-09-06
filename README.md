# Factory Fixture

This repository is a public fixture for bounded autonomous engineering software factory runs. It serves as a stable, minimal reference target that autonomous agents and factory pipelines can exercise in a controlled and repeatable way.

## Purpose

This fixture is intentionally small and public so that fully automated engineering software factory runs can:

- Demonstrate end-to-end execution against a known, safe repository.
- Validate bounded behavior with restricted write scope and no private context.
- Exercise draft pull request flows that review proposed changes before any merge.
- Provide a low-risk base for reproducibility and comparison across runs.

## Scope

Changes contributed to this fixture are kept minimal and are reviewed through the normal pull request process. No merge, deployment, or default-branch write authority is assumed by the fixture itself. Any proposed change is authored as a draft pull request targeting main so reviewers can validate it before it is merged.
