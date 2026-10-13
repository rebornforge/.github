# Security policy

## Current scope

RebornForge is in its founding documentation phase. There is no supported application release or published vulnerability-response service yet.

## Reporting a vulnerability

Do not disclose exploitable details, credentials, or personal data in public issues or pull requests.

The founder selected [GitHub issues](https://github.com/rebornforge/.github/issues/new/choose) for reports. Submit only a high-level summary and the affected public component; do not include exploit instructions, secrets, or sensitive evidence. Public issues do not provide confidentiality. No private reporting channel is currently designated, and GitHub private vulnerability reporting has not been verified as enabled.

No response-time or remediation guarantee is made at this stage.

## Proposed handling process

The founder or an authorized human security contact will assess severity, limit access to sensitive evidence, coordinate a fix, verify it, and agree on disclosure timing. Reports affecting third-party projects should follow the relevant maintainer's security policy.

Never commit a secret. If a credential is exposed, authorized operators should revoke or rotate it at its source; removing it from Git history alone does not invalidate it. Repository-history rewriting requires approval.

## Recommended controls

Require pull requests for main, prevent force pushes and deletion, disable automatic merges, and require founder review through a compatible account workflow. Grant integrations only necessary repository access.

Future automation should use minimal permissions, maintained dependencies, pinned actions, and isolation from untrusted contributions. Backups and restoration must be tested before production.

These are recommendations, not claims that controls are enabled. See the [audit](docs/FOUNDATION_AUDIT.md).
