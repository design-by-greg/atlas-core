# Regression Tests

## Objectif

Definir les tests de regression officiels d'ATLAS.

## Regles officielles

Toute evolution doit verifier qu'elle ne casse pas un comportement existant.

Les parcours critiques doivent etre proteges par des tests de regression.

## Fonctionnement

Les tests de regression doivent couvrir les modules principaux, les workflows, les permissions, les statuts, les validations, les automatisations et les interfaces critiques.

Une regression doit etre bloquante si elle touche la securite, les donnees, la facturation, les permissions ou un workflow majeur.

## Dependances

Les tests de regression dependent de la roadmap, des modules, workflows, QA, documentation et historique des bugs.

## Permissions

Les regressions de permissions doivent etre considerees comme critiques.

## Automatisations

Les tests de regression doivent etre automatises progressivement selon la criticite des modules.

## Points de vigilance

Ne pas valider une nouvelle fonction si elle casse un flux existant.

Verifier les effets indirects entre modules.

## A confirmer

- Suite minimale de regression V1.
- Criteres de blocage avant release.
