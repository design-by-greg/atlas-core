# Anti-Duplication Rules

## Objectif

Empêcher la création de doublons fonctionnels, documentaires ou métier dans ATLAS.

Ces règles garantissent que le produit reste simple, cohérent, maintenable et évolutif.

## Règles officielles

Avant toute nouvelle règle, fonctionnalité, module ou automatisation, il faut vérifier si un équivalent existe déjà.

Une règle métier ne doit être définie qu'une seule fois.

Une donnée ne doit avoir qu'une source de vérité.

Une fonctionnalité ne doit pas être recréée dans un autre module si elle peut être généralisée, partagée ou configurée.

## Fonctionnement

Chaque proposition doit passer par une vérification anti-doublon :

1. Rechercher si le besoin existe déjà dans un module.
2. Rechercher si une règle similaire existe dans `business/`.
3. Rechercher si une règle catalogue ou UX couvre déjà le besoin.
4. Vérifier si la fonctionnalité peut être une extension d'un module existant.
5. Vérifier si une configuration suffit au lieu d'un nouveau développement.
6. Documenter la décision si une nouvelle règle est réellement nécessaire.

## Dépendances

Ces règles concernent tous les dossiers de `atlas-core`.

Elles sont particulièrement importantes pour les statuts, permissions, rôles, workflows, automatisations, notifications, règles catalogue, assistants IA et composants UX/UI.

## Permissions

Une modification créant potentiellement un doublon doit être mise en attente jusqu'à clarification.

Une décision peut être intégrée seulement si elle précise pourquoi l'existant ne suffit pas.

## Automatisations

À terme, une IA de gouvernance pourra vérifier automatiquement les doublons de fichiers, doublons de règles, statuts incompatibles, incohérences de permissions et contradictions entre modules.

Cette IA ne devra jamais modifier seule les règles officielles sans validation.

## Points de vigilance

Les doublons les plus dangereux sont :

- deux statuts différents pour le même état métier ;
- deux modules propriétaires de la même donnée ;
- deux workflows parallèles pour un même processus ;
- deux permissions avec un sens proche ;
- une règle spécifique qui contourne une règle générale ;
- une documentation qui contredit une autre.

## À confirmer

- La méthode de revue officielle avant fusion dans GitHub.
- La future nomenclature des statuts transversaux.
