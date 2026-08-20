---
name: code-review
description: Review code for correctness, security, maintainability, test coverage, and regression risk with concrete findings and evidence.
metadata:
  short-description: Technical code review guidance
---

# Code Review

Use this skill when reviewing code, merge requests, or diffs.

## Review Priorities

1. Correctness
2. Security
3. Reliability
4. Maintainability
5. Test coverage
6. Performance only when evidence suggests it matters

## Review Rules

- Focus on confirmed issues first.
- For each finding, explain the impact and point to the evidence.
- Distinguish bugs from style preferences.
- Be precise about behavior, not generic.
- Call out missing tests when they matter to the changed behavior.
- If no findings are present, say so and mention residual risks or gaps.

## Stack Selection

If the technology stack is not explicit, ask whether the review should follow `.NET`, `Java`, or `Python` conventions before giving stack-specific guidance.

When the stack is known, use the matching specialized skill:

- `.NET` review: `code-review-dotnet`
- `Java` review: `code-review-java`
- `Python` review: `code-review-python`
