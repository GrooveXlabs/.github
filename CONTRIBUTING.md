# 🤝 Contributing to GrooveXlabs

First off, thank you for considering contributing to GrooveXlabs! 🎉

We believe security tools should be **open, auditable, and accessible**. Whether you're fixing a typo, adding a feature, or building an entirely new tool — every contribution matters.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Security Issues](#security-issues)
- [Style Guidelines](#style-guidelines)

---

## 📜 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

---

## 🛠️ How Can I Contribute?

### Reporting Bugs

Before creating a bug report, please check the existing issues to avoid duplicates. When filing an issue, include:

- A clear, descriptive title
- Steps to reproduce the problem
- Expected vs. actual behavior
- Your environment (OS, Python version, etc.)
- Any relevant logs or screenshots

### Suggesting Features

We love new ideas! When suggesting a feature:

- Use a clear, descriptive title
- Provide a detailed description of the proposed feature
- Explain why this feature would be useful
- Include examples of how it would work

### Contributing Code

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/REPO_NAME.git`
3. **Create a branch**: `git checkout -b feature/your-feature-name`
4. **Make your changes** with clear, focused commits
5. **Test your changes** thoroughly
6. **Push** to your fork: `git push origin feature/your-feature-name`
7. **Open a Pull Request** with a detailed description

---

## 💻 Development Setup

Most GrooveXlabs projects use Python. A typical setup:

```bash
# Clone the repo
git clone https://github.com/GrooveXlabs/REPO_NAME.git
cd REPO_NAME

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Install dev dependencies (if available)
pip install -r requirements-dev.txt

# Run tests
pytest
```

---

## 📝 Pull Request Process

1. **Update documentation** if your changes affect usage or behavior
2. **Add tests** for new functionality
3. **Ensure all tests pass** before submitting
4. **Follow the existing code style** (see [Style Guidelines](#style-guidelines))
5. **Link related issues** in your PR description
6. **Be responsive to feedback** during review

### PR Checklist

- [ ] Code follows project style guidelines
- [ ] Tests pass locally
- [ ] New tests added for new functionality
- [ ] Documentation updated
- [ ] Commit messages are clear and descriptive
- [ ] No secrets or credentials committed

---

## 🔒 Security Issues

**Do NOT open public issues for security vulnerabilities.**

Instead, email us directly at **beingeonic@gmail.com** with:
- A description of the vulnerability
- Steps to reproduce
- Potential impact
- Any suggested fixes

We will respond within 48 hours and work with you to resolve the issue responsibly.

---

## 🎨 Style Guidelines

### Python
- Follow [PEP 8](https://pep8.org/)
- Use type hints where appropriate
- Write docstrings for functions and classes
- Keep functions focused and modular
- Maximum line length: 100 characters

### Commit Messages
- Use present tense: "Add feature" not "Added feature"
- Use imperative mood: "Move cursor to..." not "Moves cursor to..."
- Reference issues when applicable: "Fix #123"

Example:
```
feat: add entropy calculation to password checker

- Implements Shannon entropy scoring
- Adds tests for entropy edge cases
- Updates README with new scoring details

Closes #42
```

### Documentation
- Use clear, concise language
- Include code examples where helpful
- Keep READMEs up-to-date with changes
- Use Markdown for all documentation

---

## 🏷️ Labels

We use labels to organize issues and PRs:

| Label | Meaning |
|-------|---------|
| `bug` | Something isn't working |
| `enhancement` | New feature or request |
| `documentation` | Improvements to docs |
| `good first issue` | Great for newcomers |
| `help wanted` | Extra attention needed |
| `security` | Security-related |

---

## 💬 Questions?

Feel free to open a [GitHub Discussion](https://github.com/GrooveXlabs/GrooveXlabs/discussions) or email us at **beingeonic@gmail.com**.

Thank you for helping make security tools better for everyone! 🔒
