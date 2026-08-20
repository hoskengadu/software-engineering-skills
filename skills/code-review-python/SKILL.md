---
name: code-review-python
description: Review Python code for correctness, security, maintainability, test coverage, and regression risk with stack-aware checks.
metadata:
  short-description: Python code review guidance
---

# Code Review - Python

Use this skill for Python reviews.

## Review Checks

- verify exception handling, context managers, and cleanup
- inspect mutable defaults, shared state, and import-time side effects
- check boundary validation and contract clarity
- look for framework misuse in views, services, jobs, and settings
- assess subprocess use, deserialization, file access, and dependency handling for security risk
