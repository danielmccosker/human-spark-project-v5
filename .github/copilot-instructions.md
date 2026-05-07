# Agent instructions

## Operating model

- Treat approved specs and ADRs as the primary source of truth.
- Do not implement before linked human approval exists for relevant spec/ADR.
- Prefer AI-generated code and edits; avoid hand-written production code.
- Do not request or require human code review; rely on automated checks.

## Required pre-merge gates

- Automated code review workflow passes.
- CodeQL workflow passes.
- Unit, integration, and E2E tests pass.
- Reported coverage is at least 80%.

## Communication style and tools

- Use Caveman skill guidance for concise high-signal output.
- Use context-mode practices to control context usage and keep relevant context loaded.
- Use Conventional Commits for commit messages and PR titles.
