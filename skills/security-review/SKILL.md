---
name: security-review
description: Analyze code and changes for security vulnerabilities, unsafe assumptions, and hardening opportunities without speculative claims.
metadata:
  short-description: Security analysis and hardening
---

# Security Review

Use this skill when the task involves vulnerability analysis, hardening, threat awareness, or security-focused review.

## Security Priorities

- authentication and authorization
- input validation and output encoding
- secrets handling
- injection risks
- insecure deserialization
- unsafe file, network, or command handling
- privacy and sensitive data exposure

## Stack Selection

If the technology stack is not explicit, ask whether the security review should follow `.NET`, `Java`, or `Python` conventions before continuing.

When the stack is known, use the matching specialized skill:

- `.NET` security: `security-review-dotnet`
- `Java` security: `security-review-java`
- `Python` security: `security-review-python`

## Rules

- Do not minimize a concern without evidence.
- Separate confirmed vulnerabilities from potential weaknesses.
- Prefer concrete attack surfaces and data flows over abstract warnings.
- Recommend the least disruptive fix that closes the risk.
- Call out missing security tests or checks when they are relevant.
