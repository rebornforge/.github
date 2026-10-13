[Français](#français) · [English](#english)

## Français

# Politique de sécurité

## Périmètre actuel

RebornForge est en phase documentaire. Aucune version applicative prise en charge ni service de réponse aux vulnérabilités n’est encore publié.

## Signaler une vulnérabilité

Ne publiez pas de détails exploitables, secrets ou données personnelles dans les issues ou PR.

Le fondateur a choisi les [issues GitHub](https://github.com/rebornforge/.github/issues/new/choose). Fournissez seulement un résumé général et le composant public concerné, sans instructions d’exploitation ni preuves sensibles. Les issues ne sont pas confidentielles. Aucun canal privé n’est désigné et l’activation du signalement privé GitHub n’a pas été vérifiée.

Aucun délai de réponse ou de correction n’est garanti.

## Traitement proposé

Le fondateur ou un responsable humain autorisé évalue la gravité, limite l’accès aux preuves sensibles, coordonne et vérifie une correction, puis organise la divulgation. Les projets tiers relèvent de la politique de leurs mainteneurs.

Ne commitez jamais de secret. Un secret exposé doit être révoqué ou renouvelé à sa source par un opérateur autorisé ; son retrait de l’historique ne l’invalide pas. Réécrire l’historique nécessite une autorisation.

## Contrôles recommandés

Exiger des PR pour main, interdire les push forcés et suppressions, désactiver les fusions automatiques et exiger une revue du fondateur compatible avec les comptes utilisés. Limiter les accès des intégrations.

Les futures automatisations devront avoir des permissions minimales, des dépendances maintenues, des actions épinglées et une isolation des contributions non fiables. Sauvegardes et restauration devront être testées avant production.

Il s’agit de recommandations, pas de protections déclarées actives. Consultez l’[audit](docs/FOUNDATION_AUDIT.md).

---

## English

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
