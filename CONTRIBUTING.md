# Contributing to George Popa's Projects

Thank you for your interest in contributing! I welcome contributions from the community.

## Getting Started

### Prerequisites
- Python 3.9+
- Git
- GitHub account

### Development Setup

1. **Fork the repository**
   ```bash
   # Visit the repo and click "Fork"
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/[repo-name].git
   cd [repo-name]
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or for bug fixes:
   git checkout -b fix/your-bug-name
   ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   pip install -r requirements-dev.txt  # if available
   ```

## Code Style & Standards

### Python Code
- **Formatter**: Black
- **Linter**: Flake8
- **Type Hints**: Recommended

```bash
# Format your code
black .

# Check for linting issues
flake8 .
```

### Commit Messages

Use conventional commits:

```
feat: Add new feature
fix: Fix a bug
docs: Update documentation
refactor: Refactor code
test: Add tests
chore: Update dependencies
```

Example:
```
feat: Add multi-language support to translator

This commit adds support for Spanish, German, and French translations
with automatic language detection.
```

## Making Changes

1. **Create meaningful commits**
   ```bash
   git commit -m "feat: Add new feature description"
   ```

2. **Keep commits atomic** - One feature per commit

3. **Test your changes**
   ```bash
   pytest tests/
   ```

4. **Update documentation** if needed
   - Update README.md
   - Add docstrings to new functions
   - Update CHANGELOG if available

## Submitting Changes

1. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Create a Pull Request (PR)**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill in the PR template

3. **PR Guidelines**
   - Clear title: `feat: Add [feature name]`
   - Describe what your PR does
   - Link related issues: `Fixes #123`
   - Provide test coverage
   - Include screenshots if UI changes

## PR Review Process

Once submitted:
- I'll review your PR
- Provide feedback or request changes
- Once approved, your PR will be merged
- Your contribution will be credited

## Reporting Issues

### Bug Reports

Include:
- Description of the bug
- Steps to reproduce
- Expected behavior
- Actual behavior
- Environment info (OS, Python version, etc.)
- Error messages/logs

### Feature Requests

Describe:
- What you want to achieve
- Why it's useful
- Possible implementation approach (optional)

## Code of Conduct

- Be respectful and inclusive
- No harassment or discrimination
- Constructive feedback only
- Help each other learn

## Questions?

Feel free to:
- Open an issue with the `question` label
- Start a discussion in the repo
- Comment on related issues/PRs

---

**Thank you for contributing!** 🙏