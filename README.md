# ATLAS Core

## Objectif

`atlas-core` est la source de vérité officielle du projet ATLAS.

Ce dépôt centralise les décisions produit, métier, UX, IA, QA, roadmap, documentation et gouvernance du projet.

Les conversations ChatGPT restent des espaces de réflexion. GitHub devient la mémoire propre, stable et exploitable.

## Règles officielles

ATLAS est un ERP SaaS modulaire, intelligent et évolutif.

Il doit être conçu comme une plateforme commercialisable auprès d'entreprises de toutes tailles et de tous secteurs, et jamais comme un logiciel spécifique à Design by Greg.

Toute décision doit respecter les priorités suivantes :

1. Cohérence globale du produit.
2. Qualité des règles métier.
3. Sécurité.
4. Expérience utilisateur.
5. Évolutivité.
6. Performances.
7. Automatisation.
8. Intelligence artificielle.
9. Rapidité de développement.

## Fonctionnement

Chaque dossier contient une partie officielle de la mémoire ATLAS :

- `vision/` : vision produit, stratégie, positionnement SaaS, roadmap long terme.
- `governance/` : principes, arbitrages, règles anti-doublon et règles de décision.
- `business/` : règles métier transversales.
- `modules/` : documentation fonctionnelle par module.
- `catalogue/` : structure des données catalogue.
- `ux-ui/` : règles d'expérience utilisateur et d'interface.
- `ai/` : fonctionnement des assistants IA.
- `qa/` : stratégie qualité et tests.
- `documentation/` : documentation utilisateur, administrateur et développeur.
- `roadmap/` : versions, priorisation et modèle économique.

## Dépendances

Ce dépôt doit rester indépendant du code applicatif.

Il sert de référence fonctionnelle, produit et documentaire pour les futures implémentations.

## Permissions

Les modifications doivent être contrôlées.

Toute évolution importante doit pouvoir être reliée à une décision validée dans les conversations ATLAS ou à une demande explicite de l'utilisateur.

## Automatisations

À terme, ce dépôt pourra alimenter :

- les prompts des agents IA ATLAS ;
- la documentation produit ;
- les tests QA ;
- les spécifications fonctionnelles ;
- les validations avant développement.

## Points de vigilance

Ne pas mélanger ce dépôt avec le code de développement.

Ne pas intégrer d'idées abandonnées.

Ne pas dupliquer une règle existante dans plusieurs fichiers.

## À confirmer

- Process exact de validation des futures modifications GitHub.
- Organisation éventuelle entre branches, pull requests et releases documentaires.
