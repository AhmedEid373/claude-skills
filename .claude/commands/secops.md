---
description: SAST/DAST scanning, CVE remediation, and SOC2/PCI-DSS/HIPAA/GDPR compliance checks. Usage: /secops <what to scan or check>
---

Run security operations for: $ARGUMENTS

Read `engineering-team/senior-secops/SKILL.md` and apply the relevant workflow:
- If scanning for vulnerabilities → follow the Security Audit workflow (hardcoded secrets, SQLi, XSS, command injection)
- If checking dependencies → follow the Vulnerability Assessor workflow (npm, Python, Go CVEs)
- If checking compliance → follow the Compliance Checker workflow (SOC2, PCI-DSS, HIPAA, GDPR)
- If setting up CI/CD security → follow the CI/CD Security Gate workflow

Ask what to scan if $ARGUMENTS is empty.
