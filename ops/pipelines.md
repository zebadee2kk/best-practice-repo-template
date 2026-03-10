# CI/CD Pipelines — <repo-name>

> ⚠️ **This is a template file.** Document the actual pipelines below and remove this notice.

## Pipelines Overview

| Workflow | File | Trigger | Purpose |
|----------|------|---------|--------|
| <name> | `.github/workflows/<file>.yml` | <trigger> | <purpose> |

## Pipeline Details

### <Pipeline Name>

- **Trigger:** <push / PR / schedule / manual>
- **Runs on:** ubuntu-latest / windows-latest
- **Steps:**
  1. <step>
  2. <step>
- **Secrets required:** `<SECRET_NAME>`
- **Artefacts produced:** <none / describe>

## Secrets Required

| Secret | Where Set | Purpose |
|--------|-----------|--------|
| `<SECRET_NAME>` | Repo settings → Secrets | <purpose> |

## Manual Triggers

All workflows support `workflow_dispatch` for manual runs from the GitHub Actions UI.
