# Permissions

## Objectif

Definir les principes officiels des permissions dans ATLAS.

## Regles officielles

Les permissions controlent l'acces aux donnees et aux actions.

Elles doivent etre compatibles avec un SaaS multi-entreprises.

Aucun utilisateur ne doit acceder a des donnees hors de son organisation sans autorisation explicite.

## Fonctionnement

Les permissions doivent couvrir :

- lecture ;
- creation ;
- modification ;
- suppression ;
- validation ;
- export ;
- configuration ;
- automatisation ;
- administration.

Les permissions doivent pouvoir etre appliquees par module, role, organisation et contexte.

## Dependances

Les permissions dependent des organisations, utilisateurs, roles, modules, workflows, validations et journaux d'activite.

## Permissions

Le principe central est le moindre privilege.

Chaque utilisateur doit recevoir uniquement les droits necessaires a son travail.

Les droits sensibles doivent etre controles : facturation, paiement, suppression, export, configuration, acces IA et automatisations.

## Automatisations

Une automatisation ne doit jamais executer une action qu'un utilisateur humain equivalent n'aurait pas le droit de faire.

Toute action automatisee doit conserver une trace.

## Points de vigilance

Ne pas rendre les permissions trop vagues.

Ne pas creer des droits trop larges.

Ne pas melanger droits internes et acces portail client.

## A confirmer

- Matrice complete des permissions par module.
- Permissions minimales par role par defaut.
- Regles d'heritage entre organisation, role et utilisateur.
