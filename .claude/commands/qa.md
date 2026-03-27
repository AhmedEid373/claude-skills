---
description: Generate unit, integration, and E2E tests for React/Next.js apps. Usage: /qa <what to test>
---

Generate tests for: $ARGUMENTS

Read `engineering-team/senior-qa/SKILL.md` and apply the relevant workflow:
- If generating unit tests → follow the Jest + React Testing Library workflow
- If analyzing coverage gaps → follow the Coverage Analyzer workflow (Istanbul/LCOV reports)
- If scaffolding E2E tests → follow the Playwright E2E Scaffolder workflow (Next.js routes)
- If mocking APIs → follow the MSW (Mock Service Worker) workflow

Ask what to test if $ARGUMENTS is empty.
