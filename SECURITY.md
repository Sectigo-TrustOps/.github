# Security policy

## Report privately

Do not open a public issue for a suspected vulnerability, exposed credential,
private key, sensitive tenant detail, or abuse path.

Use [GitHub private vulnerability reporting](https://github.com/Sectigo-TrustOps/.github/security/advisories/new)
and include:

- the affected repository, version, commit, or deployment;
- the security impact and required preconditions;
- minimal reproduction steps or a proof of concept;
- any evidence that a credential or private key may be exposed; and
- a safe way to contact you for follow-up.

Do not include live customer credentials or private certificate material when
a redacted or locally generated reproduction is sufficient.

## Scope

Security reports are accepted for supported code on each repository's default
branch and for current published releases. Unsupported historical releases,
third-party services, and vulnerabilities that require disclosure of secrets
without demonstrating product impact may be redirected or closed.

The maintainers will coordinate validation, remediation, release, and public
disclosure through the private advisory. Public disclosure should wait until a
fix or documented mitigation is available.
