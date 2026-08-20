---
name: implementation-quality-dotnet
description: Support .NET implementation with idiomatic C#, clean architecture, reliable tests, and security-aware coding practices.
metadata:
  short-description: .NET implementation guidance
---

# Implementation Quality - .NET

Use this skill for `.NET` and C# work.

## Focus

- favor explicit types, readable async flows, and clear dependency boundaries
- keep domain logic out of controllers, handlers, and UI glue
- prefer nullable-awareness and argument validation where the contract requires it
- use dependency injection consistently and avoid hidden side effects
- protect against injection, unsafe deserialization, and improper file or network handling

## Testing

- use the project’s established test framework and assertion style
- cover behavior, edge cases, and error paths
- keep tests isolated and deterministic

## Review Signals

- look for async deadlocks, blocking calls, and improper cancellation handling
- verify disposal, lifetime, and exception handling semantics
