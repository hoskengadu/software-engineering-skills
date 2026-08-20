---
name: implementation-quality
description: Support implementation with clean code, SOLID design, consistent style, defensive coding, and evidence-based changes.
metadata:
  short-description: High-quality implementation guidance
---

# Implementation Quality

Use this skill for coding tasks where the main risk is poor implementation quality, hidden regressions, or unnecessary complexity.

## Implementation Rules

- Inspect the existing code and surrounding patterns before editing.
- Preserve public behavior unless the user explicitly requests a change.
- Choose the simplest design that satisfies the requirement.
- Keep functions, classes, and modules focused.
- Prefer explicit names over clever abstractions.
- Avoid speculative generalization.
- Add comments only when they clarify non-obvious intent or constraints.

## Validation Mindset

- Add or update tests for behavior changes.
- Check edge cases, nullability, input validation, and error handling.
- Verify that the change fits the existing architecture and coding style.
- If a refactor is needed, separate it from behavior changes when possible.

## Stack Selection

If the user has not specified the target technology, ask whether the work should follow `.NET`, `Java`, or `Python` conventions before proceeding with stack-specific advice.

When the stack is known, use the matching specialized skill:

- `.NET` work: `implementation-quality-dotnet`
- `Java` work: `implementation-quality-java`
- `Python` work: `implementation-quality-python`
