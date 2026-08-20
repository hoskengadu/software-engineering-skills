---
name: implementation-quality-java
description: Support Java implementation with idiomatic structure, clean code, test discipline, and security-aware coding practices.
metadata:
  short-description: Java implementation guidance
---

# Implementation Quality - Java

Use this skill for Java work.

## Focus

- keep classes small and responsibilities narrow
- prefer clear method names and explicit invariants
- use dependency injection and layered boundaries where the project already follows them
- avoid leaking implementation details across modules
- validate inputs at boundaries and handle checked or runtime exceptions intentionally

## Testing

- use the project’s established test stack and conventions
- cover edge cases, null handling, and failure behavior
- keep tests deterministic and independent

## Review Signals

- watch for mutable shared state, resource leaks, and exception swallowing
- check for unsafe reflection, deserialization, and external input handling
