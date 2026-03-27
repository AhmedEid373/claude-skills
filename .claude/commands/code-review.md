---
description: Expert code review — quality, patterns, performance, and security issues. Usage: /code-review <file path or feature to review>
---

Perform a thorough code review for: $ARGUMENTS

Read `engineering-team/code-reviewer/SKILL.md` and execute a full code review:
1. Code quality (readability, naming, structure)
2. Design patterns and architecture alignment
3. Performance issues (N+1 queries, unnecessary loops, memory leaks)
4. Security concerns (input validation, injection risks, auth checks)
5. Test coverage gaps
6. Provide actionable feedback with priority labels (HIGH/MED/LOW)

Ask which file or feature to review if $ARGUMENTS is empty.
