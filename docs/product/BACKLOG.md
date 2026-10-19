[Français](#français) · [English](#english)

## Français

# Backlog et critères d’acceptation proposés

Ces critères sont des exigences à vérifier plus tard, pas des tests déjà réussis. Chaque US est P0 et référence le [périmètre](MVP_SCOPE.md). Les règles de [domaine](DOMAIN_RULES.md) s’appliquent partout.

| ID / Fonction | User story | Critères observables |
| --- | --- | --- |
| US01 / F01 | Comme visiteur, comprendre la mission | Accueil FR/EN ; liens vers catalogue, contribution et règles ; aucun nombre ou projet fictif présenté comme réel |
| US02 / F02 | Comme lecteur, retrouver un projet | Recherche nom/alias/résumé et filtres définis ; résultats publiés seulement ; pagination et tri stables ; état vide, erreur et réinitialisation ; droits inconnus filtrables sans prétendre à une licence |
| US03 / F03 | Comme lecteur, vérifier une histoire | Champs requis, sources consultables, incertitudes, auteurs et date de revue visibles ; distinction original/initiatives ; aucune date inventée ; URL absente ou retirée donne un état explicite sans contenu privé |
| US04 / F04 | Comme développeur, comprendre les reprises | Zéro, une ou plusieurs initiatives liées ; identité indépendante et permissions explicites ; Reborn justifié par lien et date ; aucun badge d’affiliation sans preuve |
| US05 / F05 | Comme contributeur, me connecter | Annulation/échec OAuth expliqués ; pas de compte mot de passe ; profil minimal ; déconnexion invalide la session ; connexion ne donne aucun rôle de modération ; aucun accès aux propositions d’autrui |
| US06 / F06 | Comme contributeur, proposer un projet | Champs obligatoires et URL validés ; doublons suggérés sur nom/alias sans rejet automatique ; brouillon explicite ; confirmation uniquement après enregistrement, avec identifiant ; erreur conserve le formulaire ; aucune publication immédiate |
| US07 / F06 | Comme contributeur, corriger ou proposer une initiative | Cible et version indiquées ; sources requises ; correction ne modifie pas immédiatement le public ; initiative liée à un historique existant ; suivi privé et motif de décision consultables |
| US08 / F07 | Comme fondateur, examiner | Accès interdit aux non-modérateurs ; revue avant/après et références ; précisions/refus/publication avec motif ; modification concurrente signalée avant écrasement ; décision et auteur tracés |
| US09 / F08 | Comme ayant droit, signaler | Lien d’issue avec contexte public ; avertissement de visibilité avant sortie ; aucune donnée sensible préremplie ; absence de compte GitHub expliquée ; retrait décidé par humain et contenu retiré absent du catalogue/recherche |
| US10 / F09 | Comme lecteur, changer de langue | FR par défaut ; EN sélectionnable ; navigation, erreurs, formulaires et statuts traduits ; choix conservé pendant le parcours ; contenu non traduit identifié avec retour à la langue source, sans fausse traduction |
| US11 / F01–F09 | Comme utilisateur clavier ou mobile, parcourir | Tous les parcours P0 utilisables au clavier ; focus visible ; formulaires étiquetés et erreurs associées ; aucun débordement horizontal à 320 px sauf contenu intrinsèque ; objectif WCAG 2.2 AA contrôlé avant livraison |
| US12 / F03,F07 | Comme lecteur, suivre une correction | Version publique stable pendant revue ; publication met à jour date et historique éditorial ; notes privées jamais exposées ; retrait ne révèle pas les preuves sensibles |

## Scénarios de recette minimaux

- Q1 : lecteur anonyme découvre et filtre des fiches FR/EN, dont une avec droits inconnus — US01–US03, US10–US11.
- Q2 : contributeur propose un doublon plausible, corrige les erreurs, soumet puis suit une demande de précisions — US05–US07.
- Q3 : utilisateur non autorisé tente publication, lecture d’un brouillon tiers et accès à la revue — US05, US08.
- Q4 : fondateur publie une correction puis retire une fiche ; catalogue et accès direct reflètent la décision — US03, US08–US09, US12.
- Q5 : deux initiatives distinctes apparaissent sur une histoire sans confusion d’affiliation ni de droits — US04.
- Q6 : erreur réseau, annulation de connexion, absence de résultats et changement de langue au clavier sur mobile — US02, US05–US06, US10–US11.

Utiliser des données fictives identifiées pour prototype et recette. Aucun référencement officiel de Xnova Reforged sans autorisation.

---

## English

# Proposed backlog and acceptance criteria

These are requirements for later verification, not passed tests. Every US is P0 and references the [scope](MVP_SCOPE.md). [Domain rules](DOMAIN_RULES.md) apply throughout.

| ID / Feature | User story | Observable criteria |
| --- | --- | --- |
| US01 / F01 | Visitor understands the mission | FR/EN home; catalogue, contribution and policy links; no fictional projects or metrics presented as real |
| US02 / F02 | Reader finds a project | Defined name/alias/summary search and filters; published results only; stable pagination/sorting; empty/error/reset states; unknown rights filter without implying a license |
| US03 / F03 | Reader verifies history | Required fields, accessible sources, uncertainty, creators and review date; original/initiative distinction; no invented dates; missing/withdrawn URLs show explicit states without private content |
| US04 / F04 | Developer understands revivals | Zero, one or multiple initiatives; explicit identity and permissions; Reborn supported by link/date; no affiliation badge without evidence |
| US05 / F05 | Contributor signs in | OAuth cancellation/failure explained; no password account; minimal profile; sign-out invalidates session; no moderator role from sign-in; no access to others' submissions |
| US06 / F06 | Contributor proposes a project | Required fields/URLs validated; name/alias duplicate suggestions without automatic rejection; explicit draft; confirmation/reference only after persistence; form retained on error; no immediate publication |
| US07 / F06 | Contributor corrects or proposes a revival | Target/version identified; sources required; corrections do not immediately alter public data; initiative links to existing history; private tracking and decision reason |
| US08 / F07 | Founder reviews | Non-moderators denied; before/after and sources; clarification/rejection/publication with reason; concurrent changes detected before overwrite; actor and decision recorded |
| US09 / F08 | Rights holder reports | Contextual issue link; public-visibility notice before leaving; no sensitive prefill; GitHub-account limitation explained; human withdrawal removes content from catalogue/search |
| US10 / F09 | Reader switches language | French default; English selectable; navigation/errors/forms/statuses translated; choice retained through journey; untranslated contributions identified with source-language fallback, never fake translation |
| US11 / F01–F09 | Keyboard/mobile user navigates | All P0 journeys keyboard-usable; visible focus; labeled forms and associated errors; no horizontal overflow at 320 px except intrinsic content; WCAG 2.2 AA objective checked before release |
| US12 / F03,F07 | Reader follows corrections | Stable public version during review; publication updates review date/editorial history; private notes never exposed; withdrawal never reveals sensitive evidence |

## Minimum acceptance scenarios

- Q1: anonymous discovery and filtering of FR/EN records including unknown rights — US01–US03, US10–US11.
- Q2: plausible duplicate proposal, error correction, submission and clarification tracking — US05–US07.
- Q3: unauthorized publication, another contributor's draft access and moderation access attempts — US05, US08.
- Q4: founder publishes a correction then withdraws a record; catalogue and direct access reflect this — US03, US08–US09, US12.
- Q5: two independent initiatives on one history without affiliation/rights confusion — US04.
- Q6: network error, cancelled sign-in, empty search and keyboard language switching on mobile — US02, US05–US06, US10–US11.

Use clearly identified fictional prototype/acceptance data. No official Xnova Reforged listing without authorization.
