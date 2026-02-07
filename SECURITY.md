# Security Policy

This policy applies to all repositories under the [github.com/lagbase](https://github.com/lagbase) organization.

## Reporting a Vulnerability

If you discover a security vulnerability in any Lagbase project, please report it responsibly.

**Do NOT:**
- Open a public GitHub issue
- Post about it on social media
- Exploit the vulnerability

**Do:**
- Email us at [hello@lagbase.com](mailto:hello@lagbase.com) with subject "SECURITY: [repo-name]"
- Include detailed steps to reproduce
- Give us reasonable time to respond (48 hours)

## What We Consider Security Issues

- XSS vulnerabilities
- CSRF vulnerabilities
- Data exposure or leakage
- Authentication/authorization bypasses
- Injection attacks (SQL, command, etc.)
- Sensitive data in client-side code or logs
- Dependency vulnerabilities (critical/high severity)
- DLA fingerprint integrity bypass

## What We Don't Consider Security Issues

- Missing security headers on static marketing sites
- Rate limiting on unauthenticated endpoints (pre-launch)
- Clickjacking on non-sensitive pages
- Theoretical attacks without proof of concept

## Response Timeline

- **Acknowledgment:** Within 48 hours
- **Initial assessment:** Within 7 days
- **Fix timeline:** Depends on severity (critical: 24-48h, high: 7 days, medium: 30 days)

## Recognition

We appreciate security researchers who help keep Lagbase safe. We maintain a hall of fame for responsible disclosures.

---

Thank you for helping keep Lagbase secure.

**Contact:** [hello@lagbase.com](mailto:hello@lagbase.com)
**Website:** [lagbase.com](https://lagbase.com)
**Twitter:** [@lagaboratory](https://x.com/lagaboratory)
