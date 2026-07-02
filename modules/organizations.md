# Organizations

## Objectif

Definir le module organisations d'ATLAS.

## Regles officielles

Une organisation represente une entreprise, entite ou espace de travail isole.

ATLAS doit etre compatible multi-organisations et garantir la separation des donnees.

## Fonctionnement

Une organisation contient ses utilisateurs, roles, permissions, contacts, projets, catalogues, parametres, workflows et donnees metier.

## Dependances

Ce module depend des utilisateurs, roles, permissions, contacts, projets, catalogues et parametres.

## Permissions

Seuls les roles autorises peuvent creer, modifier ou administrer une organisation.

## Automatisations

Des automatisations peuvent initialiser les roles, permissions et parametres par defaut.

## Points de vigilance

Ne jamais melanger les donnees de plusieurs organisations.

## A confirmer

- Champs exacts de l'organisation.
- Regles de multi-tenant finalisees.
