[Français](#français) · [English](#english)

## Français

# Profils de travail et parcours

Ces proto-personas prolongent les [hypothèses de phase 1](../product/USERS_AND_JOURNEYS.md). Aucun nom fictif, témoignage ou résultat d’entretien ne sert de preuve. Les besoins restent à valider.

| Profil | Objectif | Contraintes présumées | Réponse à tester |
| --- | --- | --- | --- |
| P01 Ancien utilisateur | Retrouver un projet par souvenir | Alias, dates imprécises, faible culture technique | Recherche alias, résumé historique avant technologie |
| P02 Documentaliste | Ajouter des faits fiables | Sources fragmentaires, droits inconnus | Champs connus/inconnus et prévisualisation |
| P03 Développeur | Comprendre et proposer une reprise | Plusieurs forks, permissions variables | Relations explicites et sources des permissions |
| P04 Créateur/ayant droit | Corriger ou retirer | Pas forcément de GitHub ; preuves privées | Signalement public minimal et limite du canal clairement dite |
| P05 Fondateur | Décider sans perdre le contexte | Charge de revue et traductions | Comparaison ciblée, motifs et historique des décisions |

## Parcours détaillés

| Parcours / US | Chemin heureux | Rupture et récupération |
| --- | --- | --- |
| J01 / US01–US03 | Accueil → Explorer → nom/alias → fiche → sources | Aucun résultat : retirer filtres puis proposer ; source morte : date et état sans remplacement inventé |
| J02 / US04 | Fiche historique → initiatives liées → initiative → dépôt/démo externe | Zéro initiative : l’indiquer sans fausse équipe ; droits incertains : ne pas promettre une reprise autorisée |
| J03 / US05–US07 | Contribuer → conditions/GitHub → connexion → type → sources et doublons → aperçu → soumettre → référence privée | Annulation OAuth : retour explicite ; doublon : comparer ou continuer avec justification ; erreur réseau : garder la saisie, sans confirmation trompeuse |
| J04 / US07–US08, US12 | Mes contributions → précisions demandées → réponse → nouvelle revue → décision | Session expirée : prévenir et conserver une saisie temporaire uniquement si faisable et expliquée ; proposition rejetée : motif, pas publication |
| J05 / US08 | Revue → cible/version/sources → comparaison → décision motivée | Version concurrente : recharger la comparaison avant décision ; accès non autorisé : refuser sans révéler les brouillons |
| J06 / US09 | Fiche → Signaler → avis public → issue GitHub | Sans compte : expliquer l’impossibilité actuelle et les instructions disponibles ; aucune adresse ou solution privée inventée |
| J07 / US10–US11 | Page → Français/English → contexte conservé → navigation clavier/mobile | Traduction absente : afficher la langue source et un avis ; jamais remplacer silencieusement par une fausse traduction |

## Émotions et erreurs de compréhension à vérifier

P01 peut confondre « oublié » et « téléchargeable » ; P03 peut lire Documented comme autorisé ; P04 peut publier une preuve sensible ; P02 peut abandonner au login. Ce sont des risques heuristiques, pas des observations de comportement.

Une revue de parcours est réalisée sur la cohérence du dossier ; aucun parcours applicatif n’existe encore. Les états ci-dessus deviennent des exigences de conception, à confronter au prototype.

---

## English

# Working profiles and journeys

These proto-personas extend [phase 1 hypotheses](../product/USERS_AND_JOURNEYS.md). No fictional names, quotes or interview findings serve as evidence. Needs remain to be validated.

| Profile | Goal | Assumed constraints | Response to test |
| --- | --- | --- | --- |
| P01 Former user | Rediscover from memory | Aliases, unclear dates, limited technical knowledge | Alias search and history before technology |
| P02 Documentalist | Add reliable facts | Fragmented sources and unknown rights | Known/unknown fields and preview |
| P03 Developer | Understand/propose a revival | Multiple forks and variable permissions | Explicit relations and permission evidence |
| P04 Creator/rights holder | Correct or remove | May lack GitHub; private evidence | Minimal public report and explicit channel limits |
| P05 Founder | Decide with context | Review/translation workload | Focused comparison, reasons and decision history |

## Detailed journeys

| Journey / US | Happy path | Break and recovery |
| --- | --- | --- |
| J01 / US01–US03 | Home → Explore → name/alias → record → sources | Empty: reset filters then propose; dead source: date/state without invented replacement |
| J02 / US04 | History → linked revivals → initiative → external repository/demo | No initiative: say so without fictional team; uncertain rights: no authorized-revival promise |
| J03 / US05–US07 | Contribute → terms/GitHub → sign-in → type → sources/duplicates → preview → submit → private reference | OAuth cancellation: explicit return; duplicate: compare or justify; network error: retain input without false confirmation |
| J04 / US07–US08, US12 | My contributions → clarification → response → review → decision | Expired session: explain and retain temporary input only if feasible and disclosed; rejection: reason, no publication |
| J05 / US08 | Review → target/version/sources → comparison → reasoned decision | Concurrent version: reload comparison; unauthorized access: deny without revealing drafts |
| J06 / US09 | Record → Report → public notice → GitHub issue | No account: explain current barrier and available instructions; no invented address/private workaround |
| J07 / US10–US11 | Page → Français/English → retained context → keyboard/mobile | Missing translation: show source language and notice; no silent fabricated translation |

## Comprehension and emotional risks to validate

P01 may confuse forgotten with downloadable; P03 may interpret Documented as authorized; P04 may expose private evidence; P02 may abandon at sign-in. These are heuristic risks, not observed behavior.

The package has a consistency walkthrough, not an application journey test. These states become design requirements for later prototype validation.
