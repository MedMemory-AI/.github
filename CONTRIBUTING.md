# 🤝 Contributing Guide

Thank you for your interest in contributing to MedMemory AI!

Whether you're fixing bugs, improving documentation, designing UI components, or building new features, every contribution is appreciated.

---

# 🚀 Getting Started

## 1. Fork the Repository

Fork the repository to your GitHub account.

```bash
git clone https://github.com/<your-username>/MedMemory.git
cd MedMemory
```

Add the upstream repository:

```bash
git remote add upstream https://github.com/MedMemory-AI/MedMemory.git
```

Verify remotes:

```bash
git remote -v
```

---

## 2. Create a Branch

Create a new branch for your work.

### Feature

```bash
git checkout -b feature/add-authentication
```

### Bug Fix

```bash
git checkout -b fix/upload-validation
```

### Documentation

```bash
git checkout -b docs/update-workflows
```

---

# 📝 Commit Conventions

Use clear and descriptive commit messages.

### Examples

```bash
feat: add JWT authentication

fix: resolve OCR parsing issue

docs: update local setup guide

refactor: simplify ingestion pipeline

test: add extraction service tests
```

### Recommended Prefixes

| Prefix | Description |
|----------|-------------|
| feat | New feature |
| fix | Bug fix |
| docs | Documentation |
| refactor | Code improvements |
| test | Tests |
| chore | Maintenance tasks |

---

# 🔄 Pull Request Process

1. Sync your fork with the latest changes.
2. Create a dedicated branch.
3. Make your changes.
4. Test locally.
5. Push your branch.
6. Open a Pull Request.

### Pull Request Checklist

- [ ] Code builds successfully
- [ ] Existing functionality remains unaffected
- [ ] Documentation updated if required
- [ ] Clear PR description included

---

# 🐛 Issue Workflow

Before creating a new issue:

- Search existing issues first.
- Check documentation.
- Verify the issue is reproducible.

### Good Issue Reports Include

- Problem description
- Steps to reproduce
- Expected behavior
- Actual behavior
- Logs or screenshots (if applicable)

---

# 💻 Coding Standards

## Python

Follow:

- PEP 8
- Type hints where possible
- Meaningful variable names
- Small, focused functions

Example:

```python
async def get_patient_documents(patient_id: str):
    ...
```

---

## FastAPI

- Keep routes thin.
- Place business logic in services.
- Use Pydantic models for validation.
- Use repositories for database access.

---

## Database

- Avoid raw SQL when possible.
- Use Prisma ORM.
- Keep schema changes backward compatible.

---

# 📚 Documentation Contributions

Documentation improvements are always welcome.

Examples:

- Fixing typos
- Improving setup instructions
- Architecture diagrams
- API documentation
- Tutorials and examples

Documentation lives under:

```text
docs/
```

After updating documentation, verify that MkDocs builds correctly.

---

# 💡 Contribution Ideas

Good first contributions:

- Documentation improvements
- UI enhancements
- API testing
- Bug fixes
- OCR improvements
- Medical extraction enhancements
- Workflow diagrams

---

# ❤️ Thank You

Every contribution helps improve MedMemory AI and makes the project more useful for patients, developers, and healthcare innovators.

We appreciate your support and contributions!
