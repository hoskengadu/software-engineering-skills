---
name: implementation-quality-python
description: Support Python implementation with readable, testable, secure code, explicit boundaries, and practical error handling.
metadata:
  short-description: Python implementation guidance
---

# Implementation Quality - Python

Use this skill for Python work.

## Focus

- prefer explicit, readable code over clever shortcuts
- keep modules and functions small and easy to test
- validate external input at boundaries
- use type hints and dataclasses where they improve clarity in the project context
- avoid dynamic behavior that reduces traceability unless clearly justified

## Testing

- use the project’s established test framework and conventions
- cover edge cases, error handling, and contract behavior
- keep fixtures minimal and deterministic

## Review Signals

- look for unsafe file operations, shell execution, deserialization, and dependency usage
- check for hidden global state and import-time side effects
