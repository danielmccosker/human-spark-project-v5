# Contributing

## Development model (spec-driven)

1. Create or update a spec in `specs/` from `specs/templates/spec-template.md`.
2. Create or update an ADR in `docs/adr/` from `docs/adr/0000-template.md` if architecture/approach changes.
3. Obtain **human approval** for spec/ADR before implementation (record links in PR template).
4. Implement using AI-assisted workflows (no hand-written production code).
5. Run automated verification:
   - unit tests
   - integration tests
   - end-to-end tests
   - coverage >= 80%
6. Open/update PR with required checklist evidence.

## Required standards

- Commit messages and PR titles MUST follow Conventional Commits.
- Human code review is not required in this workflow.
- Automated review and CodeQL security analysis are required checks.
- Test failures or coverage below 80% MUST block merge.

## References

- Caveman skill: https://github.com/JuliusBrussee/caveman
- Context mode: https://github.com/mksglu/context-mode
- Conventional Commits: https://www.conventionalcommits.org/en/v1.0.0/
