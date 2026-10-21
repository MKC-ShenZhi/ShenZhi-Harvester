# AGENTS.md

## Repository Purpose

ShenZhi-Harvester is a repository for collecting and
maintaining existing academic data crawling projects.

The current priority is asset consolidation, not
framework unification or large-scale refactoring.

## Repository Rules

1. Each top-level project directory is independently maintained.
2. Preserve existing project structures and implementations.
3. Do not refactor unrelated projects.
4. Do not introduce shared frameworks without explicit instructions.
5. Do not modify data collection strategies unless requested.
6. Do not modify or expose credentials and sensitive configurations.

## Development Guidelines

- Read the target project's README before making changes.
- Keep modifications scoped to the requested project.
- Prefer minimal changes over architectural redesign.
- Document important changes when necessary.
- Do not assume that every archived project is runnable.

## Integration

Future integration may introduce common interfaces,
data schemas, scheduling, and shared utilities.

Do not implement these prematurely.