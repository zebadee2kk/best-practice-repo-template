# Security Playbook

Operational guidelines for keeping the project secure.

## 🛡️ Proactive Measures
- **Dependency Scanning**: Handled by Dependabot. Review PRs weekly.
- **Static Analysis**: CodeQL runs on every PR. Zero warnings allowed in `main`.
- **Secret Scanning**: GitHub Secret Scanning is enabled. Never commit `.env` files.

## 🚨 Incident Response
1. **Report**: Report vulnerabilities to the security email (see [SECURITY.md](../../SECURITY.md)).
2. **Triage**: Maintainers will confirm the bug within 24h.
3. **Fix**: Develop a patch in a private fork/branch.
4. **Release**: Merge fix to `main` and tag a new release.
5. **Disclose**: Publish a Security Advisory.

## 🔒 Best Practices
- Use Least Privilege for CI tokens.
- Mask all secrets in CI logs.
- Regularly audit 3rd party actions used in workflows.
