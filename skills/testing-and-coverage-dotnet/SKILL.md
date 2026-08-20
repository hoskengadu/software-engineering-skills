---
name: testing-and-coverage-dotnet
description: Design and validate .NET tests with stack-specific guidance for reliable, meaningful coverage.
metadata:
  short-description: .NET testing guidance
---

# Testing and Coverage - .NET

Use this skill for `.NET` testing work.

## Testing Focus

- cover public behavior and domain rules with unit tests
- add integration tests for framework boundaries, persistence, and external dependencies when risk justifies it
- prefer deterministic async tests and explicit assertions
- validate exception paths, validation rules, and cancellation where applicable
