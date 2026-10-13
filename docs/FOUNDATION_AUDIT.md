[Français](#français) · [English](#english)

## Français

# Audit des fondations et recommandations de sécurité

## Observations en lecture seule — 12 octobre 2026

La liste publique affichait un dépôt : rebornforge/.github. Les dépôts privés ne pouvaient pas être recensés exhaustivement. Avant la PR documentaire, main contenait uniquement un README de 130 octets et un commit initial.

La connexion s’identifiait comme enamaryn. Les listes d’appartenances et installations n’établissaient pas d’accès à RebornForge. Les métadonnées annonçaient admin et push, mais la vérification directe des permissions retournait 403 ; elles ne prouvaient pas une capacité d’administration.

La lecture de main indiquait protected: false ; la liste des rulesets était vide. La lecture détaillée des protections retournait 403. Aucun réglage n’a été changé.

Sources : [dépôt](https://github.com/rebornforge/.github), [branche](https://api.github.com/repos/rebornforge/.github/branches/main), [rulesets](https://api.github.com/repos/rebornforge/.github/rulesets). Observations limitées à leur date.

## Contrôles proposés, non activés

- PR obligatoires et revue du fondateur avec CODEOWNERS valide.
- Interdiction de push forcé et suppression ; restrictions appliquées aux administrateurs lorsque possible.
- Fusion automatique désactivée ; fusion réservée au fondateur.
- Approbations obsolètes invalidées et discussions résolues.
- Identité de contribution compatible : un auteur de PR ne peut pas approuver sa propre PR.
- Double authentification et moindre privilège.
- Évaluer un futur canal confidentiel ; le fondateur a choisi les issues publiques pour les signalements actuels.
- Ajouter des contrôles automatisés à permissions minimales seulement après autorisation et vérification ; ne pas exiger un contrôle inexistant.

Les protections de branches sont disponibles pour les dépôts publics des organisations GitHub Free. Certains réglages demandent un accès d’administration non établi.

Références : [protections](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches), [CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners), [fichiers communs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Dépôts recommandés

Utiliser .github ; différer les dépôts documentation et communauté jusqu’à justification. Dépôt applicatif, architecture et prototypage nécessitent leurs validations propres.

## Suivi des accès — 13 octobre 2026

Après configuration par le fondateur, RebornForge est apparue dans les installations et la création de docs/github-foundation a réussi. La [PR #1](https://github.com/rebornforge/.github/pull/1) a été ouverte en brouillon. Cela établit l’écriture documentaire, pas l’administration. Main est restée au commit initial et était toujours déclarée non protégée.

---

## English

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
- Assess future confidential reporting needs; the founder selected public issues for current reports.
- Introduce minimal-permission, pinned-action checks only when separately approved and verified. Do not require a nonexistent status check.

Public-repository branch protection is available for GitHub Free organizations. Some controls require administrative access unavailable through the current integration.

References: [branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches), [CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners), [shared community files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Repository recommendations

Use the existing public .github repository for the founding package. Defer separate docs and community repositories until their maintenance role is justified. The platform repository, architecture, and prototype technology require their own approvals.

## Access follow-up — 13 October 2026

After access configuration, RebornForge appeared in the installation listing and branch creation succeeded. [PR #1](https://github.com/rebornforge/.github/pull/1) was opened in draft. This establishes documentation-writing access, not administration access. Main remained at its initial commit and was still reported unprotected. No settings were changed.
