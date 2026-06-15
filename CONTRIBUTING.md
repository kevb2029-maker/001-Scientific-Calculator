# Contributing Guide

Thanks for taking the time to contribute. This document outlines the standards and process for contributing to this project.

## Code of Conduct

Be respectful, constructive, and inclusive. Harassment, discrimination, or hostile behaviour of any kind will not be tolerated.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone git@github.com:<your-username>/001-Scientific-Calculator.git`
3. Create a branch for your change: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Push to your fork and open a pull request

## Branch Naming

Use a short, descriptive name prefixed by type:

| Prefix | Use for |
|--------|---------|
| `feature/` | New functionality |
| `fix/` | Bug fixes |
| `docs/` | Documentation only |
| `style/` | Visual/CSS changes |
| `refactor/` | Code restructuring without behaviour change |

## Commit Messages

- Use the imperative mood: "Add factorial support", not "Added factorial support"
- Keep the first line under 72 characters
- Reference issues where relevant: `Fix divide-by-zero error (closes #12)`

## Pull Requests

- One PR per logical change — keep scope tight
- Fill out the PR description: what changed and why
- Link any related issues
- PRs must pass review before merging

## Code Style

- Plain HTML, CSS, and JavaScript only — no frameworks or build tools
- Keep everything in `index.html` unless the scope grows significantly
- Prefer readability over cleverness
- Remove dead code and commented-out blocks before submitting
- Test in Chrome, Firefox, and Safari before opening a PR

## Reporting Bugs

Open an issue and include:
- What you expected to happen
- What actually happened
- Steps to reproduce
- Browser and OS

## Suggesting Features

Open an issue before writing code. Describe the use case and why it belongs in a single-file calculator. This saves effort if the idea doesn't fit the project's scope.

## Versioning

This project follows [Semantic Versioning](https://semver.org):
- **MAJOR** — breaking change or full redesign
- **MINOR** — new feature, backwards compatible
- **PATCH** — bug fix or minor tweak

Update `CHANGELOG.md` with every change under the appropriate version heading.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
