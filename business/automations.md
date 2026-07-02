# Automations

## Objectif

Definir les regles metier officielles des automatisations dans ATLAS.

## Regles officielles

Une automatisation doit reduire le travail manuel sans retirer le controle a l'utilisateur.

Elle doit etre explicable, controlable, tracable et securisee.

Une automatisation sensible ne doit pas executer une action irreversible sans validation.

## Fonctionnement

Chaque automatisation doit definir :

- un declencheur ;
- des conditions ;
- une action ;
- un module concerne ;
- un niveau de permission ;
- une trace dans l'historique ;
- un mode d'activation ou de desactivation.

Les automatisations peuvent aider sur les statuts, notifications, rappels, taches, documents, portails et tableaux de bord.

## Dependances

Les automatisations dependent des workflows, statuts, permissions, validations, notifications, modules et historique.

## Permissions

Une automatisation ne doit jamais depasser les droits accordes a l'organisation ou a l'utilisateur qui la configure.

Les automatisations sensibles doivent etre limitees aux roles autorises.

## Automatisations

Les principales familles sont :

- notifications automatiques ;
- rappels ;
- changements de statut conditionnels ;
- creation de taches ;
- generation de documents ;
- mise a jour du portail client ;
- alertes internes ;
- assistance IA controlee.

## Points de vigilance

Ne pas rendre une automatisation opaque.

Ne pas automatiser une validation client sensible.

Ne pas multiplier les automatisations sans valeur reelle.

## A confirmer

- Liste des automatisations disponibles en V1.
- Niveau d'autonomie autorise par type d'action.
- Interface de configuration des automatisations.
