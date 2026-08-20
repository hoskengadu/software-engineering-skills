---
name: code-review-dotnet
description: Review .NET and C# code for correctness, security, maintainability, test coverage, and regression risk with stack-aware checks.
metadata:
  short-description: .NET code review guidance
---

# Code Review - .NET

Use this skill for `.NET` and C# reviews.

## Review Checks

- verify async usage, cancellation, and exception flow
- check dependency lifetimes and disposal semantics
- inspect nullable handling and argument validation
- look for framework misuse, hidden state, and behavior changes in controllers, services, and handlers
- assess serialization, reflection, and file or network access for security risks
