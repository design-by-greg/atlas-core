# Decision Rules

## Objectif

Définir la méthode officielle de décision pour intégrer, refuser ou mettre en attente une évolution d'ATLAS.

## Règles officielles

Une décision ATLAS doit toujours privilégier, dans l'ordre :

1. La cohérence globale du produit.
2. La qualité des règles métier.
3. La sécurité.
4. L'expérience utilisateur.
5. L'évolutivité.
6. Les performances.
7. L'automatisation.
8. L'intelligence artificielle.
9. La rapidité de développement.

Une décision ne doit pas être prise uniquement parce qu'elle est rapide à développer.

Une décision ne doit pas être validée si elle crée une dette technique, fonctionnelle ou documentaire évitable.

## Fonctionnement

Chaque nouvelle proposition doit être classée dans l'un des états suivants :

- `Validée` : la décision est officielle et peut être documentée dans `atlas-core`.
- `À étudier` : l'idée semble intéressante mais nécessite analyse.
- `À confirmer` : l'information est incomplète ou incertaine.
- `Abandonnée` : l'idée ne doit pas être intégrée dans la documentation officielle.

Une décision validée doit préciser :

- le besoin couvert ;
- la règle officielle retenue ;
- les modules concernés ;
- les impacts UX, IA, QA ou documentation ;
- les points de vigilance ;
- les éléments restant à confirmer.

## Dépendances

Les décisions doivent être cohérentes avec :

- `vision/` ;
- `governance/` ;
- `business/` ;
- `modules/` ;
- `catalogue/` ;
- `ux-ui/` ;
- `ai/` ;
- `qa/` ;
- `roadmap/` ;
- `documentation/`.

## Permissions

Une décision sensible doit demander validation avant intégration officielle.

Sont considérées comme sensibles :

- les règles de paiement ;
- les règles de facturation ;
- les permissions ;
- les droits d'accès ;
- les automatisations irréversibles ;
- les actions IA autonomes ;
- les règles impactant plusieurs modules.

## Automatisations

À terme, une automatisation pourra analyser une proposition et indiquer :

- si elle existe déjà ;
- si elle crée un doublon ;
- quels modules sont impactés ;
- quels fichiers doivent être modifiés ;
- si une validation humaine est requise.

## Points de vigilance

Ne jamais transformer une idée en règle officielle sans validation claire.

Ne jamais intégrer une règle abandonnée.

Ne jamais masquer une incertitude : elle doit être placée dans `À confirmer`.

## À confirmer

- Le format final des décisions dans GitHub.
- La création éventuelle d'un dossier `decisions/` pour les futures ADR ou Product Decision Records.
