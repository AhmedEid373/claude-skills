---
description: Manage .env files, detect secret leaks, and set up secret rotation. Usage: /secrets <what to check or fix>
---

Help with secrets and environment variable management for: $ARGUMENTS

Read `engineering/env-secrets-manager/SKILL.md` and apply the relevant workflow:
- If auditing .env files → follow the .env Lifecycle Audit workflow
- If checking for leaks → follow the Secret Leak Detection workflow
- If integrating cloud secrets → follow the Cloud Secret Store Integration workflow (AWS, Azure, GCP)
- If setting up pre-commit hooks → follow the Pre-Commit Secret Detection workflow (gitleaks, detect-secrets)
- If rotating secrets → follow the Secret Rotation Workflow

Ask what to check if $ARGUMENTS is empty.
