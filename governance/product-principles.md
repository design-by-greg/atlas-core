# Product Principles

## Objectif

Définir les principes produit officiels qui guident toutes les décisions d'ATLAS.

Ces principes garantissent que le produit reste cohérent, générique, maintenable et compatible SaaS multi-entreprises.

## Règles officielles

ATLAS est un ERP SaaS modulaire conçu pour devenir une plateforme commercialisable.

Aucune fonctionnalité ne doit être pensée exclusivement pour Design by Greg.

Toute fonctionnalité doit être :

- utile à plusieurs types d'organisations ;
- configurable plutôt que spécifique ;
- compatible multi-entreprises ;
- cohérente avec les modules existants ;
- documentable ;
- testable ;
- maintenable.

La simplicité est prioritaire sur l'empilement fonctionnel.

La qualité est prioritaire sur la rapidité de livraison.

## Fonctionnement

Avant de valider une fonctionnalité, il faut vérifier :

1. Le besoin est réel.
2. La fonctionnalité n'existe pas déjà.
3. La solution ne crée pas de doublon.
4. La règle est suffisamment générique.
5. La règle peut être configurée plutôt que codée en dur.
6. La fonctionnalité respecte l'architecture modulaire.
7. La fonctionnalité apporte une valeur claire à l'utilisateur final.
8. La fonctionnalité reste compréhensible et exploitable au quotidien.

## Dépendances

Ces principes s'appliquent à tous les domaines :

- gouvernance ;
- règles métier ;
- modules ;
- UX/UI ;
- IA ;
- QA ;
- roadmap ;
- documentation ;
- développement.

## Permissions

Seules les décisions alignées avec ces principes peuvent être intégrées dans `atlas-core`.

Une idée non validée doit rester dans une section `À confirmer` ou dans une documentation de réflexion, mais ne doit pas devenir une règle officielle.

## Automatisations

Les futures automatisations doivent respecter quatre conditions :

- être explicables ;
- être contrôlables ;
- être traçables ;
- être sécurisées.

Aucune automatisation ne doit réaliser une action sensible ou irréversible sans validation utilisateur.

## Points de vigilance

Éviter :

- les règles spécifiques à un seul métier ;
- les exceptions codées en dur ;
- les doublons entre modules ;
- les modules trop dépendants les uns des autres ;
- les fonctionnalités séduisantes mais peu utiles ;
- les décisions rapides créant une dette future.

## À confirmer

- Le format exact des fiches de décision produit futures.
- Le niveau de validation requis selon la criticité d'une décision.
