[Français](#français) · [English](#english)

## Français

# États, formulaires et permissions

## Couverture des états

| ID | Surface | Retour et récupération attendus | Planche |
| --- | --- | --- | --- |
| S01 | Menu mobile | Ouvrir/fermer, langue, ordre clavier, retour focus | M11 |
| S02 | Chargement catalogue | Texte de chargement, aucune fausse liste publiée | M11 |
| S03 | Catalogue vide | Aucun projet publié ; proposer seulement si soumissions ouvertes | M11 |
| S04 | Recherche sans résultat | Garder requête/filtres ; réinitialiser | M11 |
| S05 | Erreur réseau | Réessayer sans perdre filtres ou saisie ; pas de confirmation | M11/M12 |
| S06 | Fiche retirée/introuvable | Message neutre, retour catalogue, aucune preuve sensible | M11 |
| S07 | Validation de formulaire | Résumé d’erreurs et erreurs associées aux champs ; conserver valeurs | M12 |
| S08 | Doublon possible | Comparer le projet existant ; continuer avec justification si distinct | M12 |
| S09 | Soumission réussie | Référence seulement après sauvegarde ; « non publiée » ; lien suivi | M12 |
| S10 | Connexion refusée/annulée | Retour explicite, aucune soumission ni publication ; réessai | M07, spécification textuelle |
| S11 | Session expirée | Reconnexion, avertir sur conservation de saisie selon mécanisme futur | M12 |
| S12 | Concurrence de revue | Nouvelle version détectée, recharger avant décision | M12 |
| S13 | Précisions/refus/publication | Motif et prochaine action privée ; état textuel | M08/M09/M10 |
| S14 | Sortie vers issues | Public et compte GitHub requis ; aucune donnée sensible ; retour possible | M12 |
| S15 | Traduction absente | Langue source et avis explicite ; pas de traduction fabriquée | Spécification textuelle |

## Formulaires

M06 : type de contribution et cible ; nom original/résumé/catégorie ; créateurs, dates inconnues admises ; source publique identifiable obligatoire avant soumission ; licence et droits avec valeur Inconnu ; aperçu. Pas de fichier joint. Champs facultatifs explicités. La sauvegarde de brouillon tolère l’incomplétude mais ne crée jamais une fiche publique.

M09 : référence de la cible et version, modification proposée, justification/source, réponse privée au modérateur. Les échanges ne sont ni commentaires publics ni messagerie générale.

M10 : décision, motif obligatoire et vérification des sources/permissions. « Publier » inactif tant que les préconditions ne sont pas réunies ; expliquer pourquoi, sans dépendre uniquement de l’apparence grisée. La vérification de droits ne se réduit pas à une case cochée.

## Focus et retours

Résumé d’erreurs atteignable et liens vers champs ; libellés persistants ; erreur expliquée sans couleur seule. Dialogues nommés, fermeture clavier et retour au déclencheur. Aucune animation obligatoire. Résultats et confirmation annoncés sans saut arbitraire du focus. L’image ne démontre pas ces comportements : à implémenter et tester au prototype/application.

## Confidentialité et langue

Anonyme : contenu publié seulement. Contributeur : ses propositions. Fondateur/modérateur autorisé : revue dans son mandat. Aucun accès par simple changement d’URL ou par GitHub seul. Les permissions doivent être contrôlées côté application ultérieure, pas par le seul masquage de liens.

FR/EN pour navigation, consignes, erreurs et états. Contribution mono-langue acceptée avec langue source et absence de traduction signalées. Les valeurs techniques des statuts restent stables ; labels traduits. Aucun formulaire n’envoie de données à cette phase.

---

## English

# States, forms and permissions

## State coverage

| ID | Surface | Feedback and recovery | Board |
| --- | --- | --- | --- |
| S01 | Mobile menu | Open/close, language, keyboard order, focus return | M11 |
| S02 | Catalogue loading | Loading text, no fictional published list | M11 |
| S03 | Empty catalogue | No published projects; invite proposals only if open | M11 |
| S04 | Empty search | Retain query/filters; reset | M11 |
| S05 | Network error | Retry retaining filters/input; no confirmation | M11/M12 |
| S06 | Withdrawn/not found | Neutral message, catalogue return, no private evidence | M11 |
| S07 | Form validation | Error summary/associated inline errors; retain values | M12 |
| S08 | Possible duplicate | Compare existing project; justify continuing if distinct | M12 |
| S09 | Submission success | Reference after persistence only; not published; tracking link | M12 |
| S10 | Sign-in refused/cancelled | Explicit return, no submission/publication; retry | M07 plus text specification |
| S11 | Expired session | Reconnect; explain input-retention behavior when defined | M12 |
| S12 | Concurrent review | Detect new version; reload before decision | M12 |
| S13 | Clarify/reject/publish | Private reason and next step, text state | M08/M09/M10 |
| S14 | Issue exit | Public/GitHub-account notice; no sensitive data; return | M12 |
| S15 | Missing translation | Source language/notice; no fabricated translation | Text specification |

## Forms

M06: type/target; original name/summary/category; creators and unknown dates permitted; identifiable public source required before submission; license/rights with Unknown; preview. No uploads. Optional fields identified. Incomplete drafts never publish.

M09: target/version, proposed change, reason/source, private response. Exchanges are neither public comments nor general messaging.

M10: decision, mandatory reason and source/permission review. Publishing unavailable until prerequisites met; explain why without relying only on grey styling. Rights verification is not a checkbox.

## Focus and feedback

Reachable error summary/field links; persistent labels; no color-only errors. Named dialogs, keyboard dismissal/focus return. No required animation. Announce results/confirmation without arbitrary focus jumps. Images do not prove behavior; implement/test at prototype/application stages.

## Privacy and language

Anonymous: published content only. Contributor: own submissions. Authorized founder/moderator: scoped review. No URL-changing or GitHub-only privilege escalation. Later application permissions require enforcement, not merely hidden links.

FR/EN navigation/instructions/errors/states. Single-language contributions explicitly identify source language/missing translation. Technical status values remain stable with translated labels. No form transmits data at this stage.
