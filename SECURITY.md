# Security Policy

Malfence builds security tools. We take security in our own projects seriously.

## Supported Versions

| Project | Supported |
| --- | --- |
| `malfence` | latest minor release |
| `maildfence` | latest minor release |
| All other repos | latest `main` |

## Reporting a Vulnerability

**Please do not file public GitHub issues for security vulnerabilities.**

Instead, report privately by either:

1. 📧 **Email** — `security@malfence.com` (PGP key on [malfence.com/security](https://malfence.com/security))
2. 🔒 **GitHub Private Vulnerability Reporting** — Use the **"Report a vulnerability"** button on the relevant repo's Security tab.

### What to Include

- A description of the vulnerability
- Steps to reproduce
- Affected versions / commits
- Impact assessment (what an attacker could do)
- Your name / handle for credit (or request anonymity)

### What to Expect

| Step | Timeline |
| --- | --- |
| Acknowledgement | within 48 hours |
| Initial triage | within 5 business days |
| Fix / mitigation | depends on severity (target: ≤ 90 days) |
| Public disclosure | coordinated with reporter |

We follow **coordinated disclosure**: we won't publish details until a fix is available, and we'll credit you in the advisory (unless you prefer to remain anonymous).

## Scope

In scope:
- All code in repositories under `github.com/malfencelab`
- Build artifacts and releases we distribute

Out of scope:
- Vulnerabilities in third-party dependencies (please report upstream)
- Issues requiring physical access to a user's device
- Social engineering of Malfence staff

## Safe Harbor

We will not pursue legal action against researchers who:
- Make a good-faith effort to comply with this policy
- Avoid privacy violations and destruction of data
- Give us reasonable time to fix before disclosure

Thank you for helping keep Malfence and its users safe. 🛡️
