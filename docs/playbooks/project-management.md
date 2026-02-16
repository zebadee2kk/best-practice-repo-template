# Project Management Playbook

How we track work, manage priorities, and coordinate contributions.

## 📝 GitHub Issues
- **Every task has an issue.** No work should be done without a tracking issue.
- **Labels**:
  - `priority: high/med/low`
  - `type: bug/feat/doc`
  - `status: in-progress/blocked`
  - `good first issue`: Ideal for new contributors.

## 🗺️ Milestones & Roadmap
- We work in 2-week "sprints" tracks via Milestones.
- Major releases are tracked in the [Roadmap](../../ROADMAP.md).

## 🧐 PR Reviews
- **Approval**: At least one approval from a CODEOWNER is required.
- **AI-assisted PRs**: Require a human sponsor and at least one additional reviewer.
- **Tone**: Be helpful and respectful. Goal is code quality, not "winning".
- **Timeline**: Aim to review PRs within 48 hours.

## 🔒 Branch Protection (Repo Settings)
- **Protected branches**: `main`, `release/*`
- **Required reviews**: CODEOWNER review + required checks
- **No direct pushes**: PRs only, squash merge
- **Status checks**: CI, security scan, lint/test as applicable

## 🗓️ Communication
- **Async First**: Use GitHub Issues/Discussions for most things.
- **Sync**: Weekly sync on [Insert Day/Time] (if applicable).
