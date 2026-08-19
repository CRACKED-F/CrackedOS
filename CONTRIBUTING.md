# Contributing to CrackedOS

First off, thank you for taking the time to contribute! 🎉

This document explains how to propose changes, report bugs, and get your work
merged. Following these guidelines helps maintainers review your contribution
faster and keeps the project healthy for everyone.

By participating in this project, you agree to abide by our
[Code of Conduct](CODE_OF_CONDUCT.md).

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Commit Messages](#commit-messages)
- [Pull Requests](#pull-requests)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Coding Standards](#coding-standards)
- [Community](#community)

## Ways to Contribute

There are many ways to help, and not all of them involve writing code:

- Report a bug or a security issue.
- Suggest a new feature or improvement.
- Improve documentation.
- Triage issues and help others.
- Submit a fix or a new feature as a pull request.

## Getting Started

1. **Fork** the repository and clone your fork locally:

   ```bash
   git clone https://github.com/<your-username>/CrackedOS.git
   cd CrackedOS
   ```

2. **Add the upstream remote** so you can keep your fork in sync:

   ```bash
   git remote add upstream https://github.com/CRACKED-F/CrackedOS.git
   ```

3. **Create a branch** for your work (never work directly on `master`):

   ```bash
   git checkout -b feat/short-description
   ```

## Development Workflow

1. Keep your branch focused — one logical change per pull request.
2. Sync with upstream regularly to avoid large merge conflicts:

   ```bash
   git fetch upstream
   git rebase upstream/master
   ```

3. Make your changes and add tests where it makes sense.
4. Run the test suite and linters locally before you push.
5. Push your branch and open a pull request.

## Commit Messages

Write clear, descriptive commit messages. We recommend the
[Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>(optional scope): <short summary>

<optional body explaining what and why>
```

Common types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`.

Example:

```
fix(boot): prevent kernel panic on missing config
```

## Pull Requests

- Fill out the pull request template completely.
- Reference any related issues (for example, `Closes #123`).
- Keep pull requests small and focused; large ones are hard to review.
- Ensure CI passes and there are no merge conflicts.
- Be responsive to review feedback — maintainers may request changes.
- By submitting a pull request, you confirm that your contribution is your own
  work and that you license it under the project's [LICENSE](LICENSE).

A maintainer will review your pull request as soon as possible. Please be
patient; this is often maintained by volunteers.

## Reporting Bugs

Before opening a bug report, please:

1. Search [existing issues](https://github.com/CRACKED-F/CrackedOS/issues) to
   avoid duplicates.
2. Use the **Bug Report** issue template.
3. Include clear steps to reproduce, expected vs. actual behavior, and your
   environment (OS, version, hardware where relevant).

## Suggesting Features

1. Search existing issues and discussions first.
2. Use the **Feature Request** issue template.
3. Explain the problem you want to solve, not only the solution you have in
   mind. This helps us find the best approach together.

## Coding Standards

- Match the existing code style of the files you touch.
- Keep functions small and readable; comment non-obvious logic.
- Add or update tests for the behavior you change.
- Update documentation when your change affects users.

## Community

- Be respectful and constructive in all interactions.
- Assume good intent and help newcomers where you can.
- If you are unsure about anything, open a discussion or ask in an issue.

Thank you for helping make CrackedOS better! 💚
