[Français](#français) · [English](#english)

## Français

# Phase 1 — Définition du produit

**État : cinq recommandations du MVP approuvées le 19 octobre 2026 (RF-008).** La phase UX est autorisée ; le développement et les phases suivantes restent soumis à validation.

## Proposition centrale

Permettre de retrouver un projet numérique oublié, comprendre son histoire et ses droits connus, puis proposer une contribution ou découvrir une initiative de renaissance indépendante. La valeur du MVP est la fiabilité des fiches et la facilité de contribution, pas le volume de fonctionnalités.

Recommandation : catalogue public, recherche simple, fiches historiques sourcées, fiches de renaissance légères, proposition et correction soumises à revue humaine. Lecture sans compte ; connexion GitHub proposée pour contribuer. Aucun hébergement de binaires ni de code tiers.

## Dossier de décision

1. [Périmètre et priorités](MVP_SCOPE.md).
2. [Profils et parcours](USERS_AND_JOURNEYS.md) — hypothèses à tester, sans recherche utilisateur inventée.
3. [Règles et informations métier](DOMAIN_RULES.md) — modèle conceptuel, sans choix de base de données.
4. [User stories et critères](BACKLOG.md).
5. [Contraintes, risques et validation](VALIDATION.md).
6. [Autorisation de phase](../decisions/RF-006-phase-1-authorization.md) et [arbitrage du MVP](../decisions/RF-007-mvp-proposal.md).

## Arbitrages approuvés

| Sujet | Recommandation | Alternative utile |
| --- | --- | --- |
| MVP | Catalogue + contributions revues + renaissance légère | Catalogue éditorial seul, moins coûteux mais moins communautaire |
| Contribution | Compte GitHub, sans imposer de connaissances Git | Issues GitHub uniquement, plus simples à exploiter mais moins accessibles |
| Publication | Toute création ou correction revue avant publication | Publication immédiate, déconseillée au démarrage |
| Renaissance | Pages simples et liens externes, sans gestion de forge | Reporter entièrement ces pages, au prix d’une démonstration partielle de la mission |
| Langues des contenus | FR/EN pour textes éditoriaux de lancement ; contributions dans une langue avec indication explicite | Traduction humaine obligatoire avant chaque publication, plus lente |

Les cinq recommandations ci-dessus sont approuvées, pas leurs alternatives. Les documents détaillés conservent leur formulation de cadrage ; RF-007 et RF-008 font foi sur le périmètre validé. La [recherche UX](../ux/README.md) poursuit ce cadrage.

Les choix de framework, hébergement, licence et fournisseur OAuth définitif restent pour leurs arbitrages respectifs. Le cadrage ne constitue pas une estimation ferme de coût ou délai.

---

## English

# Phase 1 — Product definition

**Status: five MVP recommendations approved on 19 October 2026 (RF-008).** UX research is authorized; development and later phases still require approval.

## Core proposal

Help people rediscover a forgotten digital project, understand its history and known rights, then propose a contribution or discover an independent revival. MVP value comes from trustworthy records and accessible contribution rather than feature volume.

Recommendation: public catalogue, simple search, sourced historical records, lightweight revival pages, and human-reviewed submissions and corrections. Reading requires no account; GitHub sign-in is proposed for contributors. No third-party code or binary hosting.

## Decision package

1. [Scope and priorities](MVP_SCOPE.md).
2. [Users and journeys](USERS_AND_JOURNEYS.md) — hypotheses to test, without invented user research.
3. [Domain rules](DOMAIN_RULES.md) — conceptual information model, not a database choice.
4. [Stories and acceptance criteria](BACKLOG.md).
5. [Constraints, risks and validation](VALIDATION.md).
6. [Phase authorization](../decisions/RF-006-phase-1-authorization.md) and [MVP decision](../decisions/RF-007-mvp-proposal.md).

## Approved founder decisions

| Topic | Recommendation | Useful alternative |
| --- | --- | --- |
| MVP | Catalogue + reviewed contributions + lightweight revivals | Editorial catalogue only: cheaper but less participatory |
| Contribution | GitHub account without requiring Git knowledge | GitHub issues only: easier to operate but less accessible |
| Publication | Review every new record and correction | Immediate publication: discouraged initially |
| Revival | Simple pages and external links without forge management | Defer pages entirely, demonstrating only part of the mission |
| Content languages | FR/EN launch editorial content; single-language contributions explicitly identified | Require human translation before every publication: slower |

The five recommendations above are approved, not their alternatives. Detailed documents retain their definition wording; RF-007/RF-008 establish the accepted scope. [UX research](../ux/README.md) follows this definition.

Framework, hosting, licensing and final OAuth provider choices remain subject to their own approvals. This definition is not a firm cost or schedule estimate.
