# AI Context — <repo-name>

> **Read this first.** This file tells any AI assistant exactly what this repository is, what it does, and how to work with it effectively.
>
> ⚠️ **This is a template file.** Replace all `<placeholder>` values and remove this notice when using.

## Repository Purpose

<2-3 sentences describing what this repo does, who uses it, and why it exists.>

## Architecture Overview

```
<repo-name>/
├── ai/                    ← AI assistant context files (YOU ARE HERE)
├── src/                   ← <description>
├── docs/                  ← <description>
├── tests/                 ← <description>
├── .github/               ← CI/CD workflows and templates
├── PROJECT_STATUS.md      ← Current project status
├── ARCHITECTURE.md        ← System architecture detail
├── CHANGELOG.md           ← Change history
└── SECURITY.md            ← Security policy
```

## Key Relationships

| Repo | Relationship |
|------|-------------|
| `portfolio-management` | Governance hub — tracks this repo's status and compliance |
| `best-practice-repo-template` | This repo was created from this template |
| `<related-repo>` | <describe relationship> |

## Existing Tooling

- **`<tool/script>`** — <what it does>

## What Still Needs Building

- [ ] <item>
- [ ] <item>

## Working with This Repo

- **Language:** <Python 3.11+ / PowerShell 7+ / etc.>
- **Package manager:** <pip / npm / etc.>
- **Key commands:**
  ```bash
  # Install dependencies
  <install command>

  # Run tests
  <test command>

  # Run main script
  <run command>
  ```
- **Required env vars:** `<VAR_NAME>` — <what it's for>

## AI Assistant Instructions

1. **Read before write** — always read existing files before modifying them
2. **Check `PROJECT_STATUS.md`** at the start of every session
3. **Check `ai/AI_RULES.md`** for repo-specific rules
4. **Update `ai/AI_HANDOVER.md`** at the end of each significant work session
5. <add any repo-specific instructions here>
