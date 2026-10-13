# Foundation audit and security recommendations

## Read-only observations — 12 October 2026

The public organization listing showed one repository, rebornforge/.github. Private repositories could not be exhaustively established. Before this documentation change, main contained only a 130-byte README.md and one initial commit.

The connected GitHub identity was enamaryn. Membership and installation listings did not establish RebornForge access. Repository metadata reported admin and push permissions, but the direct collaborator permission check returned HTTP 403. These observations do not establish integration administration capability.

A later branch read returned protected: false for main, while the repository ruleset listing returned an empty array. The detailed branch-protection endpoint returned HTTP 403. Main is therefore reported unprotected by the readable branch endpoint at the time of this audit; security settings were not changed.

Sources: [repository](https://github.com/rebornforge/.github), [branch API](https://api.github.com/repos/rebornforge/.github/branches/main), [rulesets API](https://api.github.com/repos/rebornforge/.github/rulesets). These observations are time-bound.

## Proposed settings — not activated

- Require pull requests for main and founder review with valid per-repository CODEOWNERS.
- Prevent force pushes and branch deletion; apply protections to administrators where supported.
- Disable automatic merges and reserve merging for the founder.
- Dismiss stale approvals and require resolution of review conversations.
- Verify a workable contributor identity: the founder cannot approve a PR authored by the same GitHub account.
- Require two-factor authentication and minimize collaborator and integration privileges.
- Verify and publish a confidential security reporting channel.
- Introduce minimal-permission, pinned-action checks only when separately approved and verified. Do not require a nonexistent status check.

Public-repository branch protection is available for GitHub Free organizations. Some controls require administrative access unavailable through the current integration.

References: [branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches), [CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners), [shared community files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Repository recommendations

Use the existing public .github repository for the founding package. Defer separate docs and community repositories until their maintenance role is justified. The platform repository, architecture, and prototype technology require their own approvals.

## Access follow-up — 13 October 2026

After the founder configured access, the installation listing included rebornforge and creation of the dedicated docs/github-foundation branch succeeded. This verifies branch-writing access for this repository; it does not establish integration administration access. Main remained at its initial commit and was still reported unprotected. No security settings were changed.
