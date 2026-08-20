---
name: software-engineering-core
description: Guide end-to-end software work from story definition to implementation, review, testing, security, and release readiness with evidence-based decisions.
metadata:
  short-description: End-to-end software engineering guidance
---

# Software Engineering Core

Use this skill for most software delivery tasks when the goal is to keep the work structured, safe, and reviewable.

## Operating Principles

- Work only from evidence available in the request, repository, or explicit user confirmation.
- Separate facts, assumptions, risks, and recommendations.
- Prefer the smallest correct change that preserves behavior and makes intent clear.
- Treat tests, review, and security checks as part of the delivery, not optional extras.
- Do not claim a result is safe or complete without verification.

## Routing

- For turning a request into a story with scope and criteria, use `user-story-structure`.
- For implementing code, use `implementation-quality`.
- For stack-specific implementation, use the matching `.NET`, `Java`, or `Python` variant.
- For reviewing code, use `code-review`.
- For stack-specific review, testing, or security, use the matching `.NET`, `Java`, or `Python` variant.
- For test strategy and coverage, use `testing-and-coverage`.
- For vulnerability analysis, use `security-review`.
- For merge request readiness and final validation, use `release-readiness`.

## Default Output Shape

When asked to help with a task, keep the output in this order:

1. What the request is.
2. What is known from the context.
3. What is assumed, if anything.
4. What should be done next.
5. What must be verified before merge or release.

If the evidence is incomplete, say so plainly instead of filling gaps with speculation.

If the technology stack is not explicit, ask which stack applies before giving stack-specific guidance.
