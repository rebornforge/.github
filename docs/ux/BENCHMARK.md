[Français](#français) · [English](#english)

## Français

# Comparaison documentaire

Consultation : **19 octobre 2026**. O = observation publique ; I = interprétation pour RebornForge. Les limites indiquées décrivent un risque de transposition, pas un défaut mesuré du site.

| Référence | O : constat et source | I : intérêt | I : limite et adaptation |
| --- | --- | --- | --- |
| B01 GitHub | Explore expose sujets, tendances et collections — [source](https://github.com/explore) | Plusieurs portes d’entrée de découverte | Popularité et dépôts techniques ne racontent pas l’histoire : proposer des sélections éditoriales sans classement par étoiles |
| B02 GitLab | Les sujets regroupent des projets, avec filtres et tri documentés — [source](https://docs.gitlab.com/user/project/project_topics/) | Catégories compréhensibles et recherche bornée | Ne pas exposer la complexité d’une forge ; vérifier quels filtres aident vraiment les lecteurs |
| B03 Product Hunt | Accueil structuré autour de lancements et résumés courts — [source](https://www.producthunt.com/) | Présentation rapidement parcourable | Nouveauté et compétition ne conviennent pas à la mémoire : cartes sobres, sans votes |
| B04 AlternativeTo | Catégories, plateformes, licences et relations d’alternatives visibles — [source](https://alternativeto.net/) | Métadonnées pour comparer | Une alternative n’est pas une continuation historique ; qualifier chaque relation |
| B05 Software Heritage | Mission de collecte et préservation du code source ; FAQ indexée décrit la recherche de dépôts — [mission](https://www.softwareheritage.org/mission/), [FAQ](https://www.softwareheritage.org/software-heritage-faq/) | Provenance et distinction archive/projet | Une archive ne prouve ni permission de reprise ni projet actif ; lien externe qualifié |
| B06 Wikipédia | Portail avec recherche et sélection de langue — [source](https://www.wikipedia.org/) | Langue explicite et accès direct | Ne pas supposer une traduction disponible ; signaler la langue source des contributions |
| B07 GOG Preservation | Page combinant programme et récits de préservation — [source](https://www.gog.com/en/gog-preservation-program) | Relier mémoire et activité de préservation | Ne pas reprendre les promesses de fonctionnement d’un distributeur : datation et portée des preuves |
| B08 Codeberg | Accès direct refusé par robots.txt — [URL tentée](https://codeberg.org/) | Aucune conclusion d’interface tirée | Référence communautaire à réexaminer si accès disponible |

GitHub/GitLab couvrent aussi les communautés open source. Wikipédia apporte une référence de connaissance collaborative ; GOG et Software Heritage apportent deux approches de préservation distinctes.

## Traçabilité et limites d’accès

B01, B03, B04, B06 et B07 : pages publiques ouvertes. B02 : première URL /user/project/explore/ inaccessible, remplacée par la documentation officielle des sujets, ouverte avec succès. B05 : ouverture de mission non concluante et FAQ en erreur 502 ; extraits indexés officiels disponibles par recherche. Les constats B05 restent limités à ces extraits. Aucun parcours d’archivage testé. B08 : accès refusé ; aucun contournement.

## Enseignements pour le MVP

- R01 : entrées simples et cartes lisibles — B01–B04 → US01–US02.
- R02 : distinguer original, archive, alternative et renaissance — B04–B05, B07 → US03–US04.
- R03 : langue explicite et absence de traduction honnête — B06 → US10.
- R04 : preuves consultables, dernière vérification et incertitudes — B05, B07 → US03, US12.
- R05 : réduire la charge de contribution — inférence issue des parcours du MVP, à tester → US05–US08.

Ces recommandations ne prouvent ni préférence utilisateur ni meilleure conversion. Elles n’emportent aucun choix graphique.

---

## English

# Desk comparison

Access date: **19 October 2026**. O means public observation; I means interpretation for RebornForge. Limits describe transfer risks, not measured defects.

| Reference | O: observation and source | I: opportunity | I: limitation and adaptation |
| --- | --- | --- | --- |
| B01 GitHub | Explore presents topics, trends and collections — [source](https://github.com/explore) | Multiple discovery entry points | Popularity/technical repositories do not tell history: use editorial selections without star rankings |
| B02 GitLab | Documented topics group projects with filters/sorting — [source](https://docs.gitlab.com/user/project/project_topics/) | Understandable categories and bounded search | Avoid forge complexity; test which filters help readers |
| B03 Product Hunt | Homepage organized around launches and short summaries — [source](https://www.producthunt.com/) | Scannable presentation | Novelty/competition differ from heritage: restrained cards without voting |
| B04 AlternativeTo | Visible categories, platforms, licenses and alternative relationships — [source](https://alternativeto.net/) | Comparative metadata | An alternative is not a historical continuation: qualify relationships |
| B05 Software Heritage | Source preservation mission; indexed FAQ describes repository search — [mission](https://www.softwareheritage.org/mission/), [FAQ](https://www.softwareheritage.org/software-heritage-faq/) | Provenance and archive/project distinction | Archive presence proves neither reuse permission nor activity: qualified external links |
| B06 Wikipedia | Search and language-selection portal — [source](https://www.wikipedia.org/) | Explicit language and direct entry | Never assume translation availability; identify contribution source language |
| B07 GOG Preservation | Program information and preservation stories — [source](https://www.gog.com/en/gog-preservation-program) | Connect history with preservation work | Do not copy distributor operability promises: date and scope evidence |
| B08 Codeberg | Direct access denied by robots.txt — [attempted URL](https://codeberg.org/) | No interface conclusion | Community reference to revisit if accessible |

GitHub/GitLab also cover open-source communities. Wikipedia adds collaborative knowledge; GOG and Software Heritage represent different preservation approaches.

## Access evidence and limits

B01/B03/B04/B06/B07 public pages opened. B02: initial /user/project/explore/ URL inaccessible; official topic documentation successfully opened instead. B05: mission opening inconclusive, FAQ returned 502; official indexed search excerpts available. B05 observations are limited to those excerpts. No archive journey tested. B08 denied access; no bypass.

## MVP implications

- R01: simple entry points and readable cards — B01–B04 → US01–US02.
- R02: separate original, archive, alternative and revival — B04–B05, B07 → US03–US04.
- R03: explicit language and honest missing-translation state — B06 → US10.
- R04: inspectable evidence, verification date and uncertainty — B05, B07 → US03, US12.
- R05: lower contribution burden — inference from MVP journeys, to test → US05–US08.

These establish neither user preference nor conversion improvements. No visual direction is selected.
