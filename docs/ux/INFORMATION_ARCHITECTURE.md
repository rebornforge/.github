[Français](#français) · [English](#english)

## Français

# Architecture de l’information proposée

Règles fonctionnelles, non maquette validée. Couverture de F01–F09 ; aucun ajout au MVP.

## Navigation et plan

| Entrée | Contenu et accès | Liens contextuels |
| --- | --- | --- |
| Accueil | Mission, sélection éditoriale réelle ou état vide, recherche | Explorer ; Comprendre ; Contribuer |
| Explorer | Catalogue, recherche, filtres et tri | Fiche historique ; filtre « avec initiative » |
| Fiche historique | Identité → résumé/histoire → sources et droits → initiatives → détails techniques/historique éditorial | Initiative ; corriger ; signaler |
| Initiative | Nom et historique parent → objectif/équipe → état et preuves → liens externes | Retour à l’historique ; proposer une correction |
| Comprendre | Mission, statuts, droits, règles de contribution | Guide ; signalement via issues |
| Contribuer | Choix projet/correction/initiative, explication de GitHub et revue | Connexion ; formulaire ; aperçu |
| Mes contributions | Privé : propositions, état et motifs | Modifier brouillon ; répondre aux précisions |
| Profil minimal | Privé : identité affichée et déconnexion | Mes contributions |
| Revue | Accès modérateur uniquement | File ; comparaison ; décision motivée |

Le nom RebornForge renvoie à l’accueil. Langue et connexion/profil sont des commandes distinctes des rubriques. Le footer relie gouvernance, sécurité, assistance et droits. Les URL sont à définir en architecture ; les brouillons ne doivent pas être exposés via navigation ou recherche.

## Recherche et filtres

Nom, alias et résumé ; catégories, technologies, décennie connue, droits, statut historique selon F02. Le filtre « avec initiative » est un accès aux relations déjà prévues par F03–F04, pas un nouveau moteur. Les filtres avancés sont regroupés sans masquer les valeurs actives. Compteur, tri et suppression de chaque filtre restent visibles. En revenant d’une fiche, restaurer la recherche et la position si possible.

Desktop : liste/cartes avec contrôles proches des résultats. Mobile : bouton « Filtres » avec nombre actif, panneau contrôlable au clavier, actions appliquer/réinitialiser et retour au déclencheur. Aucun choix de grille, couleur ou police n’est adopté.

## Hiérarchie des fiches

Ne pas afficher les quatre axes comme une rangée de badges équivalents. Projet : état documentaire + mention de droits, puis détails sourcés. Initiative : avancement propre + date et preuve. Publication et échanges privés sont réservés à la contribution/revue.

Les relations utilisent des libellés explicites : « Projet historique », « Initiative indépendante », « Archive externe », « Dépôt associé ». Aucun bouton « Télécharger » au MVP. Les liens externes indiquent leur destination et restent utilisables sans ouverture forcée d’onglet.

## Formulaire guidé

1. Type et cible ; 2. identité/résumé ; 3. sources, droits et inconnues ; 4. aperçu et soumission.
Des étapes logiques sont proposées, pas quatre pages imposées. Champs facultatifs clairement marqués ; dates inconnues possibles ; doublons présentés comme comparaison. Différencier « Enregistrer le brouillon » et « Soumettre à la revue ». Confirmation seulement après enregistrement réussi.

## Traduction

Commandes de langue par nom, sans drapeau. Texte éditorial de lancement bilingue ; contribution mono-langue admise avec mention de langue et traduction absente. Ne pas remplacer les titres originaux des projets par une traduction trompeuse.

---

## English

# Proposed information architecture

Functional rules, not approved mockups. Covers F01–F09 without extending the MVP.

## Navigation and map

| Entry | Content and access | Context links |
| --- | --- | --- |
| Home | Mission, real editorial selection or empty state, search | Explore; Understand; Contribute |
| Explore | Catalogue, search, filters and sorting | History record; “with initiative” filter |
| Historical record | Identity → summary/history → sources/rights → initiatives → technical/editorial details | Initiative; correct; report |
| Initiative | Name/parent history → objective/team → state/evidence → external links | Parent history; correction |
| Understand | Mission, statuses, rights and contribution rules | Guide; issue reporting |
| Contribute | Project/correction/initiative, GitHub and review explanation | Sign-in; form; preview |
| My contributions | Private submissions, states and reasons | Edit draft; clarify |
| Minimal profile | Private displayed identity and sign-out | My contributions |
| Review | Moderator-only | Queue; comparison; reasoned decision |

RebornForge links home. Language and sign-in/profile controls are distinct from sections. Footer links governance, security, support and rights. URLs belong in architecture; drafts must not leak through navigation/search.

## Search and filters

Name, aliases and summary; category, technology, known decade, rights and historical status under F02. “With initiative” exposes existing F03–F04 relationships, not a new engine. Group advanced filters without hiding active values. Keep count, sort and per-filter removal visible. Restore search and position when returning from a record where feasible.

Desktop: list/cards and nearby controls. Mobile: Filters button with active count, keyboard-operable panel, apply/reset and focus return. No grid, color or typeface is selected.

## Record hierarchy

Avoid four equivalent badge rows. History: documentation state and rights notice, followed by evidence. Initiative: its own progress, date and proof. Publication/private exchanges belong only in contribution/review.

Use explicit relations: Historical project, Independent initiative, External archive, Associated repository. No MVP Download button. Label external destinations without forcing new tabs.

## Guided form

1. Type/target; 2. identity/summary; 3. sources/rights/unknowns; 4. preview/submit.
These are logical groups, not four mandatory pages. Mark optional fields, allow unknown dates and show duplicate comparisons. Distinguish Save draft from Submit for review. Confirm only after successful persistence.

## Translation

Use language names, not flags. Bilingual launch editorial content; single-language contributions with explicit language/missing-translation notices. Preserve original project titles without misleading translation.
