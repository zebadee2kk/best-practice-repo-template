# Development Playbook

This document outlines the development standards and workflows for this project.

## 🛠️ Environment Setup
- **Required Tools**: 
  - Node.js LTS
  - Git
  - Docker (if applicable)
- **Local Config**: Copy `.env.example` to `.env` and fill in secrets.

## 🌿 Branching Strategy
We use a simplified **GitHub Flow**:
1. `main` is always production-ready.
2. Create feature branches from `main` (e.g., `feat/login-system` or `fix/button-alignment`).
3. Open a PR to `main` for review.
4. Merge using "Squash and Merge" to keep history clean.

## ✍️ Coding Standards
- **Linting**: Run `npm run lint` before committing.
- **Formatting**: We use Prettier. Auto-format on save is recommended.
- **Naming**: Use `camelCase` for variables and `PascalCase` for components.

## 🧪 Testing Strategy
- **Unit Tests**: Required for all business logic.
- **Integration Tests**: Required for critical paths.
- **Coverage**: Aim for >80% coverage.

## 📦 Commits
Follow [Conventional Commits](https://www.conventionalcommits.org/):
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `chore:` for maintenance
