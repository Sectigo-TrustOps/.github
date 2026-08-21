# Contributing

Thank you for improving Sectigo TrustOps. Contributions should preserve the
portfolio's evidence, safety, and no-account developer-experience contracts.

## Before starting

1. Read the target repository's `README.md`, `AGENTS.md`, `SKILLS.md`, and
   repository-specific `CONTRIBUTING.md` when present.
2. Open an issue for a material behavior or contract change so scope and
   compatibility can be reviewed before implementation.
3. Keep credentials, private keys, tenant identifiers, and private topology
   out of issues, commits, fixtures, logs, workflow exports, and examples.

## Pull requests

- Work from a focused branch and keep unrelated changes out of the diff.
- Add tests that exercise success, partial evidence, bounds, and failure
  behavior appropriate to the change.
- Update task documentation, samples, generated contracts, and agent guidance
  in the same delivery when behavior changes.
- Run every local gate documented by the repository and record commands and
  results in the pull request.
- Never weaken a security, secret-leakage, completeness, or generated-drift
  check just to make a build pass.

Small fixes are welcome. A capability claim requires the stronger
cross-repository proof described by the
[delivery-readiness scorecard](https://sectigo-trustops.github.io/docs/docs/reference/delivery-readiness/).
