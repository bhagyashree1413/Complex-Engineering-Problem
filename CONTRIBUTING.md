# Contributing Guidelines

Thank you for contributing! Please follow these steps so that reviews stay quick and the history stays clean.

## How to Contribute
1. Fork the repository and clone your fork.
2. Create a new branch from `main` using the naming rules below.
3. Make your changes and test them locally.
4. Commit using the commit message convention.
5. Push your branch and open a pull request against `main`.
6. Address review comments. A maintainer merges after approval.

## Branch Naming Convention
| Type | Pattern | Example |
|------|---------|---------|
| Feature | `feature/<short-description>` | `feature/student-login` |
| Bug fix | `bugfix/<short-description>` | `bugfix/fix-null-email` |
| Documentation | `docs/<short-description>` | `docs/update-readme` |
| Hotfix | `hotfix/<short-description>` | `hotfix/payment-error` |

Never commit directly to `main`.

## Commit Message Convention
Format: `<type>: <short summary in present tense>`

| Type | Use for |
|------|---------|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation changes |
| `style` | Formatting only, no code change |
| `refactor` | Code change that is not a fix or feature |
| `test` | Adding or updating tests |
| `chore` | Build or tooling changes |

Examples:
- `feat: add student registration form`
- `fix: correct email validation regex`
- `docs: add installation steps to README`

## Pull Request Checklist
- [ ] Branch name follows the convention
- [ ] Commits follow the message convention
- [ ] Code runs and tests pass locally
- [ ] Documentation updated if needed
- [ ] Linked the related issue (e.g., `Closes #12`)

## Reporting Issues
Use the templates in `.github/ISSUE_TEMPLATE` for bug reports and feature requests.
