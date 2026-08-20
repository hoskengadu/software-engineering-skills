---
name: release-readiness
description: Prepare work for merge request and release with a checklist covering evidence, tests, review, security, and rollback considerations.
metadata:
  short-description: Merge request and release readiness
---

# Release Readiness

Use this skill when the work is close to merge, needs a final quality pass, or must be summarized for review.

## Readiness Checklist

- The request is implemented and aligned with the stated scope.
- The change was validated with meaningful tests or checks.
- Known risks and tradeoffs are documented.
- Security-sensitive paths were reviewed.
- The final summary separates facts from assumptions.
- The reviewer has enough context to approve or request changes.

## Merge Request Guidance

- Keep the description factual and structured.
- Include what changed, why it changed, how it was validated, and any remaining risk.
- Avoid claiming zero risk unless the evidence truly supports it.
- If the branch is not ready, say what is still missing.
