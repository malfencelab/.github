# Contributing to Malfence

First off — **thank you** for taking the time to contribute! 🛡️

Malfence is an open-source cybersecurity lab. Every PR, issue, and discussion helps us build better defensive tools for everyone.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Workflow](#development-workflow)
- [Commit Style](#commit-style)
- [Pull Request Checklist](#pull-request-checklist)
- [Security Issues](#security-issues)

---

## Code of Conduct

This project adheres to the [Malfence Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold it. Report unacceptable behavior to `conduct@malfence.com`.

## How Can I Contribute?

### 🐛 Reporting Bugs
- Search [existing issues](https://github.com/malfencelab) first.
- Use the **Bug Report** template.
- Include reproduction steps, expected vs actual behavior, and your environment.

### ✨ Suggesting Features
- Open a **Feature Request** issue.
- Explain the problem before the solution.

### 🔧 Code Contributions
- Pick an issue labeled `good first issue` or `help wanted`.
- Comment on it to claim it before starting work.

### 📖 Documentation
- Typos, clarifications, examples — all welcome.
- Docs live in the [`docs`](https://github.com/malfencelab/docs) repository.

---

## Development Workflow

1. **Fork** the repository.
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/<repo>.git
   cd <repo>
   ```
3. **Create a branch**:
   ```bash
   git checkout -b feat/my-change
   ```
4. **Make your changes** with tests where applicable.
5. **Run the project's tests and linters** (see each repo's README).
6. **Commit** using [Conventional Commits](#commit-style).
7. **Push** and open a **Pull Request** against `main`.

---

## Commit Style

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <subject>

<body>

<footer>
```

**Types:** `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `chore`, `ci`, `build`, `revert`

**Examples:**
```
feat(scanner): add YARA rule loader
fix(mail): handle empty MIME parts
docs(readme): clarify install steps
```

---

## Pull Request Checklist

Before requesting a review:

- [ ] Branch is up to date with `main`
- [ ] Tests pass locally
- [ ] Linter / formatter clean
- [ ] New code is covered by tests (when reasonable)
- [ ] Public API changes are documented
- [ ] PR description explains **what** and **why**
- [ ] Linked the relevant issue (`Closes #123`)

---

## Security Issues

**Do not open public issues for security vulnerabilities.**

See [SECURITY.md](SECURITY.md) for our responsible disclosure process. Email `security@malfence.com`.

---

Thank you for helping make security tools accessible to everyone. 💙
