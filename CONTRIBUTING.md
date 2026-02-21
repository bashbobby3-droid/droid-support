# 🤝 Contributing to droid-project

First off — **thank you for considering contributing!** Every contribution, no matter the size, helps make droid-project better for everyone. We genuinely appreciate your time and effort.

This guide will walk you through everything you need to know to get started.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Your First Code Contribution](#your-first-code-contribution)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Style Guide](#style-guide)
- [Getting Help](#getting-help)

---

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it — it helps us keep this a welcoming and respectful community for everyone.

---

## How Can I Contribute?

There are many ways to contribute beyond writing code:

- 🐛 **Report bugs** — Help us find and fix issues
- 💡 **Suggest features** — Share ideas for improvements
- 📖 **Improve documentation** — Clearer docs help everyone
- 🔍 **Review pull requests** — Help us maintain quality
- 🧪 **Write tests** — Increase coverage and reliability
- 💬 **Answer questions** — Help others in issues and discussions

---

## Reporting Bugs

Found a bug? We want to hear about it! Before opening an issue, please:

1. **Search existing issues** to avoid duplicates
2. **Check the latest version** to see if it's already been fixed

When reporting, please include:

- A clear, descriptive title
- Steps to reproduce the issue
- What you expected to happen vs. what actually happened
- Your environment (OS, Python version, etc.)
- Any relevant logs or screenshots

> 🔒 For **security vulnerabilities**, please do **not** open a public issue. Instead, follow our [Security Policy](SECURITY.md).

---

## Suggesting Features

We're always open to new ideas! To suggest a feature:

1. Check existing issues and discussions to see if it's already been proposed
2. Open a new issue with the label `enhancement`
3. Describe the problem your feature would solve
4. Outline your proposed solution and any alternatives you considered

The more context you provide, the easier it is for us to evaluate and prioritize!

---

## Your First Code Contribution

Not sure where to start? Look for issues labeled:

- `good first issue` — Great for newcomers
- `help wanted` — We'd love some assistance here

### Setting Up Your Development Environment

```bash
# 1. Fork the repository on GitHub, then clone your fork
git clone https://github.com/YOUR-USERNAME/droid-project.git
cd droid-project

# 2. Add the upstream remote
git remote add upstream https://github.com/bashbobby3-droid/droid-project.git

# 3. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt
pip install -r requirements-dev.txt  # If available

# 5. Create a new branch for your work
git checkout -b feature/your-feature-name
```

---

## Pull Request Guidelines

When you're ready to submit your work:

1. **Keep PRs focused** — One feature or fix per pull request
2. **Write clear commit messages** — Describe *what* and *why*, not just *how*
3. **Add or update tests** — Make sure your changes are covered
4. **Update documentation** — If your change affects behavior, update the docs
5. **Pass all checks** — Ensure tests and linting pass before submitting

### Commit Message Format

```
type: short description (max 72 chars)

Optional longer description explaining the context and reasoning.
```

Common types: `feat`, `fix`, `docs`, `test`, `refactor`, `chore`

Example:
```
feat: add progress percentage to issue tracker

Added a computed field that calculates completion percentage based on
resolved vs total issues within a project scope.
```

### Submitting Your PR

1. Push your branch to your fork
2. Open a pull request against the `main` branch
3. Fill out the PR template completely
4. Link any related issues using `Closes #issue-number`
5. Be responsive to feedback — we'll do our best to review promptly!

---

## Style Guide

We follow standard Python conventions to keep the codebase consistent and readable.

- **Formatter:** [Black](https://black.readthedocs.io/) — run `black .` before committing
- **Linter:** [Flake8](https://flake8.pycqa.org/) — run `flake8 .` to check
- **Docstrings:** Google style
- **Type hints:** Encouraged for all new functions

---

## Getting Help

Stuck? That's totally okay — we've all been there.

- Open an [issue](https://github.com/bashbobby3-droid/droid-support/issues) and tag it `question`
- Start a [discussion](https://github.com/bashbobby3-droid/droid-support/discussions) for broader conversations

We're a friendly bunch and happy to help. 😊

---

Thank you again for being here — we're excited to build something great together! 🚀
