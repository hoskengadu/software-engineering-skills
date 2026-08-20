---
name: testing-and-coverage
description: Design tests, raise meaningful coverage, and validate behavior changes with a risk-based strategy.
metadata:
  short-description: Testing and coverage guidance
---

# Testing and Coverage

Use this skill when the task involves unit tests, integration tests, coverage, or validation strategy.

## Test Strategy

- Map tests to observable behavior, not implementation details.
- Prioritize critical paths, boundaries, failure modes, and regressions.
- Prefer a few high-value tests over many redundant ones.
- Keep test setup understandable and maintainable.
- Ensure assertions are specific enough to catch real regressions.

## Coverage Guidance

- Increase coverage where the risk is highest.
- Do not chase percentage numbers without behavior value.
- If coverage cannot be improved, explain why and what compensating validation exists.

## Stack Selection

If the technology stack is not explicit, ask whether the testing guidance should follow `.NET`, `Java`, or `Python` conventions before continuing.

When the stack is known, use the matching specialized skill:

- `.NET` testing: `testing-and-coverage-dotnet`
- `Java` testing: `testing-and-coverage-java`
- `Python` testing: `testing-and-coverage-python`
