# Security Policy

## Supported Versions

Tymira Health actively maintains the current production release. Security patches are applied to the latest release only.

| Version | Supported          |
|---------|--------------------|
| Latest  | ✅ Yes              |
| Older   | ❌ No               |

## Reporting a Vulnerability

We take security issues seriously. Healthcare data and system integrity are of the highest importance to us.

**Please do not report security vulnerabilities through public GitHub issues, pull requests, or discussions.**

### How to Report

Report security vulnerabilities by emailing: **security@tymirahealth.com**

Include as much of the following as possible:

- A description of the vulnerability and its potential impact
- The affected component or repository
- Steps to reproduce or a proof-of-concept
- Any suggested mitigations you are aware of

### What to Expect

- **Acknowledgement:** We will acknowledge your report within **2 business days**.
- **Assessment:** We will provide an initial assessment of the vulnerability within **5 business days**.
- **Resolution:** We aim to resolve critical vulnerabilities within **14 days** and high-severity issues within **30 days**.
- **Disclosure:** We follow responsible disclosure. We will coordinate with you on the appropriate timing for public disclosure after a fix is available.

We will keep you informed of our progress throughout the process and credit you in our security advisories unless you prefer to remain anonymous.

## Security Standards

All Tymira Health systems are built with security as a first-class concern:

- **Multi-tenant isolation** — strict tenant data separation enforced at every layer
- **Role-Based Access Control (RBAC)** — enforced on every endpoint and action
- **Immutable audit trails** — all state-changing operations are logged
- **Database-layer integrity** — constraints enforced at the schema level
- **Encrypted communications** — TLS enforced for all data in transit
- **Structured environment isolation** — production, staging, and development environments are strictly separated

## Scope

This policy applies to all Tymira Health repositories under the [Tymira-Health](https://github.com/Tymira-Health) GitHub organization.
