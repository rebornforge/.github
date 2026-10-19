[Français](#français) · [English](#english)

## Français

# Principes, états et accessibilité

Recommandations de conception à valider. Objectif WCAG 2.2 AA, pas déclaration de conformité.

## Principes

UX01 : expliquer la valeur sans vocabulaire Git pour lire ou proposer. UX02 : montrer la provenance près des affirmations. UX03 : rendre toute incertitude explicite. UX04 : informer des contraintes GitHub avant connexion. UX05 : préserver le contexte après erreur. UX06 : distinguer brouillon, soumission et publication. UX07 : rendre la langue et les relations visibles. UX08 : privilégier la découverte sans concours de popularité.

Ces principes déclinent R01–R05 du [benchmark](BENCHMARK.md) et US01–US12 du [backlog](../product/BACKLOG.md).

## États obligatoires

| Surface | États et retour attendu |
| --- | --- |
| Catalogue | Chargement annoncé ; erreur avec réessai ; zéro fiche vs zéro résultat distingués ; suppression des filtres |
| Fiche | Inconnu explicitement affiché ; source indisponible signalée ; retiré/introuvable sans révéler contenu privé |
| Connexion | Annulation, refus et session expirée expliqués ; aucune publication involontaire |
| Formulaire | Brouillon, validation par champ, résumé d’erreurs, enregistrement en cours et confirmé ; saisie conservée après échec selon faisabilité expliquée |
| Soumission | Pending review, Needs information, Rejected, Published traduits ; motif et prochaine action |
| Revue | Décision en cours, version concurrente, refus d’accès ; pas de double décision silencieuse |
| Langue | FR/EN interface ; contenu source indiqué si traduction absente |
| Issue externe | Avis « public, compte GitHub requis » ; résumé non sensible seulement |

## Accessibilité à spécifier dans les maquettes

Selon la [référence WCAG 2.2](https://www.w3.org/WAI/WCAG22/quickref/) : contraste du texte normal 4,5:1 (exceptions prévues par la norme), grand texte 3:1 et composants pertinents 3:1 ; couleur jamais seule porteuse de sens. Titres structurés, landmarks et lien d’évitement. Labels persistants, consignes avant saisie, erreurs identifiées et associées ; annonces de résultats sans déplacement forcé du focus.

Navigation au clavier sans piège, ordre cohérent et focus visible. Un élément focalisé ne doit pas être entièrement masqué par un contenu créé par l’auteur, selon [2.4.11](https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum.html). Éviter que barres fixes cachent les erreurs. Cibles d’au moins 24×24 pixels CSS ou respect des exceptions du critère [2.5.8](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html) ; viser 44×44 pour les commandes tactiles principales, comme préférence de conception et non minimum AA universel.

Reflow à 320 pixels CSS, zoom texte et interface ; contenus intrinsèquement bidimensionnels traités séparément. Dialogues : nom, fermeture accessible, gestion et retour du focus. Pas d’animation indispensable ; respecter les préférences de réduction du mouvement. Déclarer langue de page et changements de langue ; ne pas confondre absence de traduction et erreur réseau.

## Vérifications futures

Maquettes : contrastes, tailles et ordre de lecture. Prototype : clavier, focus, erreurs et mobile. Application : audit manuel, lecteur d’écran et outils automatisés complémentaires. Aucun de ces tests n’a encore été exécuté sur RebornForge ; la lecture de WCAG ne remplace pas un audit.

---

## English

# Principles, states and accessibility

Design recommendations awaiting approval. WCAG 2.2 AA is an objective, not a compliance claim.

## Principles

UX01: explain value without Git vocabulary for reading/submission. UX02: place provenance near claims. UX03: show uncertainty. UX04: explain GitHub constraints before sign-in. UX05: preserve error context. UX06: distinguish draft/submission/publication. UX07: expose language and relations. UX08: discovery without popularity contests.

These apply R01–R05 from the [benchmark](BENCHMARK.md) and US01–US12 from the [backlog](../product/BACKLOG.md).

## Required states

| Surface | States and recovery |
| --- | --- |
| Catalogue | Announced loading; retryable error; no records vs no matches; reset filters |
| Record | Explicit unknowns; unavailable source; withdrawn/not found without private content |
| Sign-in | Explained cancellation/refusal/expiry; no accidental publication |
| Form | Draft, field errors, error summary, saving/confirmed; retain input after failure with explained feasibility |
| Submission | Translated Pending review, Needs information, Rejected, Published; reason/next step |
| Review | Pending decision, concurrent version, access denied; no silent double decision |
| Language | FR/EN interface; source language when untranslated |
| External issue | Public/GitHub-account notice; non-sensitive summary only |

## Accessibility for mockups

Under the [WCAG 2.2 reference](https://www.w3.org/WAI/WCAG22/quickref/): normal text contrast 4.5:1 with standard exceptions, large text 3:1, relevant components 3:1; never color alone. Structured headings, landmarks, skip link. Persistent labels, upfront instructions, identified/associated errors; announce results without forcing focus.

Keyboard navigation without traps, coherent order and visible focus. Focused controls must not be entirely hidden by author-created content under [2.4.11](https://www.w3.org/WAI/WCAG22/Understanding/focus-not-obscured-minimum.html). Avoid sticky bars hiding errors. At least 24×24 CSS pixel targets or applicable exceptions under [2.5.8](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html); prefer 44×44 for primary touch controls as design guidance, not a universal AA minimum.

320 CSS pixel reflow and text/interface zoom, with inherently two-dimensional content handled separately. Dialog names, accessible close controls, focus management/return. No essential animation; honor reduced motion. Declare page and passage languages; distinguish untranslated content from network failure.

## Later verification

Mockups: contrast, sizing and reading order. Prototype: keyboard, focus, errors and mobile. Application: manual/screen-reader audit supplemented by automated tools. None of these tests has yet been run on RebornForge; reading WCAG is not an audit.
