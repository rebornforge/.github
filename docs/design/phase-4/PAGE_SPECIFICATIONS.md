[Français](#français) · [English](#english)

## Français

# Pages et navigation

Ces spécifications expriment l’intention précise des maquettes ; aucun comportement n’est réellement exécuté. Chaque page reprend Explorer / Comprendre / Contribuer, Français/English et connexion ou profil privé selon session. Sur smartphone, menu accessible et recherche contextualisée.

| Page | Hiérarchie et action principale | Adaptation mobile / liens |
| --- | --- | --- |
| M01 Accueil | Mission, recherche, sélection fictive, explication préservation/renaissance ; Explorer | Hero plus court, cartes empilées ; proposer et comprendre restent accessibles |
| M02 Catalogue | Recherche, filtres groupés, tri, résultats, pagination | Bouton Filtres avec compte actif ; cartes verticales ; détail puis retour au contexte |
| M03 Recherche | Requête/alias, résultats, filtres actifs retirables, réinitialiser | Panneau de filtres avec appliquer/réinitialiser/fermer ; retour du focus |
| M04 Historique | Identité originale, résumé/histoire, sources/droits, initiatives, détails et historique éditorial | Même ordre ; données inconnues explicites ; corriger ou signaler sans téléchargement |
| M05 Initiative | Lien vers historique, identité indépendante, objectif, équipe connue ou absente, statut et preuves | Colonnes empilées ; exemples en pause et liens absents explicitement, pas fausse reprise autorisée |
| M06 Proposition | Type/cible, description, sources/droits, aperçu | Étapes logiques compactes ; brouillon distinct de soumission |
| M07 Connexion/profil | Avant : GitHub et explication ; après : identité minimale privée/déconnexion | Deux états clairement distincts ; lecture sans connexion, pas d’identifiant/mot de passe local |
| M08 Tableau de bord | Mes contributions, états/motifs, actions reprendre/répondre/consulter | Tableau converti en cartes avec libellés ; aucun flux social |
| M09 Contribution | Cible/version, avant/après, sources, demande privée de précision, réponse | Comparaison empilée original/proposition ; fiche publique inchangée pendant revue |
| M10 Modération | File, cible/version, preuves, comparaison, motif obligatoire et décision | File puis détail ; actions explicites, aucun droit obtenu par connexion seule |

## Schéma de navigation

Accueil → Explorer → résultats → historique → initiative ; retour à l’historique parent.
Depuis historique : correction ou signalement. Contribuer → conditions GitHub → connexion → formulaire → aperçu → confirmation privée → Mes contributions.
Depuis Mes contributions : brouillon ou demande de précisions → M09 → nouvelle revue.
Modérateur autorisé : M10, séparé des rubriques publiques. Menu mobile et erreurs transversales : M11/M12.

## Données et statuts

Noms Orbit Garden, Pixel Atlas, Signal Desk et compte de démonstration fictifs. Les dates, responsables, sources et liens inconnus ne doivent pas être inventés. Les références des images ne sont pas des preuves historiques. Sources d’exemple = références illustratives non vérifiées.

Conserver quatre axes : documentation historique, avancement de l’initiative, droits et publication. Les droits inconnus ne sont ni une licence ni une permission. M05 est une illustration de candidature en pause, pas une initiative autorisée en production.

## Dimensions de conception

Les planches sont des images de présentation. Le panneau smartphone illustre l’ordre et le regroupement, pas un viewport exécuté. Reflow cible à 320 pixels CSS ; contrôles tactiles principaux visés à 44 pixels ; minimum WCAG et exceptions à contrôler ensuite. Aucune grille définitive ou police sous licence choisie.

La future implémentation devra préserver les contenus, l’ordre de lecture et les actions des pages approuvées ; toute évolution visuelle significative sera soumise au fondateur.

---

## English

# Pages and navigation

Specifications express precise mockup intent; no behavior is executed. Shared navigation is Explore / Understand / Contribute, Français/English and sign-in/private profile by session. Smartphone uses an accessible menu and contextual search.

| Page | Hierarchy and main action | Mobile adaptation / links |
| --- | --- | --- |
| M01 Home | Mission, search, fictional selection, preservation/revival explanation; Explore | Shorter hero, stacked cards; submission/mission remain reachable |
| M02 Catalogue | Search, grouped filters, sort, results, pagination | Filters with active count; vertical cards; detail and contextual return |
| M03 Search | Query/alias, results, removable filters, reset | Apply/reset/close panel with focus return |
| M04 History | Original identity, summary/history, sources/rights, initiatives, details/editorial history | Same order; explicit unknowns; correction/report without downloads |
| M05 Initiative | Parent history, independent identity, objective, known/missing team, status/evidence | Stacked columns; on-hold example and missing links explicit, no false permission |
| M06 Submission | Type/target, description, sources/rights, preview | Compact logical steps; draft distinct from submission |
| M07 Sign-in/profile | Before: GitHub/explanation; after: minimal private identity/sign-out | Two explicit states; reading without sign-in, no local password form |
| M08 Dashboard | Own submissions, states/reasons, resume/respond/view | Tables become labeled cards; no social feed |
| M09 Contribution | Target/version, before/after, sources, private clarification and response | Stacked original/proposal; public record stable during review |
| M10 Moderation | Queue, target/version, evidence, comparison, required reason/decision | Queue then details; explicit actions; sign-in grants no role |

## Navigation map

Home → Explore → results → history → initiative; return to parent.
History links correction/report. Contribute → GitHub conditions → sign-in → form → preview → private confirmation → My contributions.
My contributions → draft/clarification → M09 → renewed review.
Authorized moderator: M10 outside public sections. Mobile menu/transversal errors: M11/M12.

## Data and statuses

Orbit Garden, Pixel Atlas, Signal Desk and demo identity are fictional. Unknown dates, maintainers, sources and links must not be invented. Image references are not historical evidence. Sample sources mean illustrative unverified references.

Keep four axes: historical documentation, initiative progress, rights and publication. Unknown rights are neither a license nor permission. M05 illustrates an on-hold candidate, not authorized production work.

## Design dimensions

Boards are presentation images. Smartphone panels illustrate order/grouping, not executed viewports. Target 320 CSS pixel reflow and 44 pixel primary touch controls; verify WCAG minimum/exceptions later. No final grid or licensed font selected.

Implementation must preserve approved content, reading order and actions; significant visual changes require founder review.
