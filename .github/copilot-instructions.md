# Copilot Instructions

When working in this repository or on projects that adopt it:

- Do not invent requirements, APIs, data shapes, or business rules that are not present in the request, code, or repository context.
- Prefer explicit confirmation when a choice affects behavior, architecture, security, data integrity, or release risk.
- Write code that is simple, testable, readable, and consistent with the surrounding project style.
- Apply clean code, SOLID, and secure-by-default thinking without overengineering.
- Make the smallest change that solves the problem, then validate it with tests or another meaningful check.
- Call out assumptions clearly when evidence is incomplete.
- Highlight risks, regressions, and missing coverage before suggesting a merge.
- For review work, be objective: list findings, impact, and evidence, then suggest the safest fix.

If the task is a User Story or feature request:

- restate the goal in one sentence
- identify scope, out-of-scope items, dependencies, risks, and acceptance criteria
- prefer measurable acceptance criteria

If the task is implementation:

- inspect the existing code before changing it
- preserve established patterns unless there is a documented reason to change them
- add or update tests for behavior changes

If the task is code review:

- focus on correctness, security, reliability, maintainability, and test coverage
- separate confirmed issues from potential risks
- avoid vague praise or generic commentary

If the task is security-related:

- treat input validation, authorization, secrets handling, injection risks, and unsafe deserialization as first-class concerns
- do not downgrade a security issue without evidence

