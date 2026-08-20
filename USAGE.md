# Quick Usage Guide

## Choose the right skill

- `software-engineering-core` for the full workflow
- `user-story-structure` to turn a request into a clear story
- `implementation-quality` for implementation guidance
- `code-review` for reviewing code or merge requests
- `testing-and-coverage` for test strategy and coverage
- `security-review` for vulnerability and hardening analysis
- `release-readiness` for final merge preparation

## Stack-specific skills

When the work depends on a language stack, use the matching profile:

- `.NET`: `implementation-quality-dotnet`, `code-review-dotnet`, `testing-and-coverage-dotnet`, `security-review-dotnet`
- `Java`: `implementation-quality-java`, `code-review-java`, `testing-and-coverage-java`, `security-review-java`
- `Python`: `implementation-quality-python`, `code-review-python`, `testing-and-coverage-python`, `security-review-python`

## Recommended flow

1. Structure the request.
2. Confirm the target stack if needed.
3. Implement with the stack-specific guidance.
4. Review the change.
5. Add or adjust tests.
6. Run the security pass.
7. Prepare the merge request.
