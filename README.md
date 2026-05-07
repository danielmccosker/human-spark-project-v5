# human-spark-project-v5

This repository is configured for **spec-driven AI-assisted engineering**.
Specifications are the source of truth and implementation follows approved specs/ADRs.

## Methodology

- Specs-first: write/update specs before implementation.
- Human approval required for specs and ADRs before implementation.
- No hand-written code or human code review in the delivery path.
- Automated code review + CodeQL + verification gates are required for merge.
- Verification requires unit, integration, and E2E tests with minimum 80% coverage.

## Core references

- Caveman skill: https://github.com/JuliusBrussee/caveman
- Context mode: https://github.com/mksglu/context-mode
- Conventional Commits 1.0.0: https://www.conventionalcommits.org/en/v1.0.0/

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for full contribution flow and gates.
