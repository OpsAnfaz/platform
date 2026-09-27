# Contributing to OpsAnfaz

Thank you for your interest in contributing to OpsAnfaz.
Please read this guide carefully before submitting any contribution.

## Commit style

All commits must follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

| Type | When to use |
|------|-------------|
| `feat:` | New functionality |
| `fix:` | Bug fix |
| `chore:` | Maintenance tasks |
| `docs:` | Documentation changes |
| `infra:` | Infrastructure changes |

Examples:
- `feat: add VPC module for OpsAnfaz network layer`
- `infra: configure remote backend in S3`
- `docs: update architecture diagram in README`

## Areas of contribution

Contributions are welcome in the following areas:

- `/infra` — Terraform modules and AWS infrastructure
- `/apps` — Web application and frontend
- `/docs` — Architecture documentation and diagrams
- `.github/workflows` — CI/CD pipeline improvements

If you want to propose a new framework, library, or tool,
open an Issue first to discuss it before submitting code.

## Pull Requests

Before submitting a PR, make sure it meets the following requirements:

- An Issue must be opened and referenced before any PR is created
- The commit messages follow the Conventional Commits style defined above
- The contribution targets one of the areas listed above
- The PR description clearly explains what was changed and why

PRs that do not meet these requirements will not be reviewed.

## Code of conduct

All contributors are expected to maintain a formal and professional
tone in issues, pull requests, and any project communication.
Constructive feedback is encouraged — disrespectful or unconstructive
comments will not be tolerated.