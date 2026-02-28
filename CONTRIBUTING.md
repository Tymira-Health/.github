# Contributing to Tymira Health Projects

Thank you for your interest in contributing to Tymira Health. We build healthcare infrastructure that practitioners depend on — contributions must meet our standards for quality, governance, and safety.

## Code of Conduct

By participating in any Tymira Health project you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How to Contribute

### Reporting Issues

- Use the repository's issue tracker and select the appropriate issue template.
- Provide a clear, descriptive title and a complete description of the problem.
- Include steps to reproduce, expected behaviour, and actual behaviour.
- For security vulnerabilities, **do not open a public issue** — follow the [Security Policy](SECURITY.md) instead.

### Proposing Changes

1. **Open an issue first** to discuss the proposed change before writing code.
2. Fork the repository and create a branch from `main` using the naming convention:
   - `feature/<short-description>` for new features
   - `fix/<short-description>` for bug fixes
   - `chore/<short-description>` for maintenance tasks
3. Write clear, focused commits with descriptive messages.
4. Ensure all existing tests pass and add tests for new behaviour.
5. Open a pull request targeting `main` and fill in the PR template completely.

### Pull Request Standards

- All PRs must be linked to an issue.
- Descriptions must explain **what** changed and **why**.
- Code must conform to the architectural standards documented in the repository.
- PRs that introduce breaking changes must be clearly labelled and justified.
- All CI checks must pass before a PR can be merged.
- At least one maintainer review is required before merging.

## Coding Standards

We follow strict engineering standards across all Tymira Health projects:

- **Domain-Driven Design (DDD)** — respect bounded contexts and domain models.
- **Clean / Onion Architecture** — maintain strict separation of concerns.
- **Database-Layer Integrity** — constraints must be enforced at the schema level.
- **Lookup-Driven Modeling** — avoid hardcoded enums; use governed taxonomy tables.
- **Audit Readiness** — all state-changing operations must produce an auditable record.
- **RBAC Enforcement** — every endpoint and action must be protected by role-based access controls.
- **Multi-Tenant Isolation** — no cross-tenant data access is ever acceptable.

## Commit Message Format

Use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <short summary>

[optional body]

[optional footer]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

## Questions

If you have a question that is not covered here, please open a discussion in the relevant repository.
