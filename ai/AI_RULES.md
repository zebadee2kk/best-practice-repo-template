# AI Rules — <repo-name>

> ⚠️ **This is a template file.** Customise these rules for the specific repo and remove this notice.

These rules apply to ALL AI assistants (Claude, Copilot, Perplexity, Cursor, etc.) working in this repository.

## Non-Negotiable Rules

1. **Read before write** — always read file contents before modifying any existing file
2. **Never delete or truncate** existing documented content without explicit user approval
3. **No secrets in commits** — API keys, tokens, passwords must never appear in any committed file
4. **Update CHANGELOG.md** for any significant change using Keep a Changelog format
5. **Check PROJECT_STATUS.md** at the start of every session

## File Ownership Rules

| File/Folder | Rule |
|-------------|------|
| `src/` | Read before modify; never refactor without explicit ask |
| `ai/*.md` | Keep accurate and current |
| `CHANGELOG.md` | Append only (newest at top) |

## Naming Conventions

- Python files: `snake_case.py`
- Markdown files: `UPPER_CASE.md` for root docs, `kebab-case.md` for subfolders
- Scripts: `verb-noun.sh` or `verb_noun.py`

## Commit Message Format

```
<type>: <short description>

- bullet point of what changed
```

Types: `feat` | `fix` | `docs` | `chore` | `refactor` | `ci` | `security`

## Quality Standards

- All new Python functions must have docstrings
- All new scripts must be documented in `SCRIPTS.md` (if it exists)
- GitHub Actions workflows must include a `workflow_dispatch` trigger

## Repo-Specific Rules

<add any rules specific to this repository>
