# Development Playbook

This document outlines the development standards and workflows for this project.

## 🛠️ Environment Setup

### Prerequisites
Ensure you have the correct runtime for the specific project type:

- **Node.js Projects** (`package.json` present):
  - Install Node.js LTS.
  - Run `npm install` or `yarn` or `pnpm install`.
- **Python Projects** (`requirements.txt` / `pyproject.toml` present):
  - Install Python 3.10+.
  - Create a virtual environment: `python -m venv venv`.
  - Activate source: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows).
  - Install deps: `pip install -r requirements.txt`.

### Local Configuration
1. Copy `.env.example` to `.env`.
2. Fill in the required secrets and API keys.

## 🌿 Branching Strategy
We use a **Trunk-Based Development** flow:

1. `main` is the single source of truth.
2. Create short-lived feature branches: `feat/my-feature` or `fix/issue-123`.
3. Open a Pull Request (PR) to merge into `main`.
4. **Squash and Merge** is preferred to keep history linear.

## ✍️ Coding Standards

### General
- **Naming**: Use descriptive variable names (`isAuthenticated` vs `a`).
- **Comments**: Explain "Why", not "What".
- **Formatting**: We use `Prettier` (JS/TS) and `Black` (Python) where possible.

### JavaScript / TypeScript
- Linting: `npm run lint`
- Formatting: `npm run format`

### Python
- Linting: `flake8`
- Formatting: `black .`

## 🧪 Testing Strategy
- **Unit Tests**: Required for all business logic.
- **Coverage**: Aim for >80% coverage on critical paths.
- **Run Tests**:
  - JS: `npm test`
  - Python: `pytest`

## 📦 Commits
Follow [Conventional Commits](https://www.conventionalcommits.org/):
- `feat:` New features
- `fix:` Bug fixes
- `docs:` Documentation changes
- `chore:` Maintenance tasks
- `refactor:` Code restructuring without behavioral change

