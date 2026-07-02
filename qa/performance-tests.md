# Performance Tests

## Objectif

Definir les tests de performance officiels d'ATLAS.

## Regles officielles

ATLAS doit rester rapide et fluide pour un usage quotidien.

Les performances doivent etre verifiees sur les modules critiques et les listes volumineuses.

## Fonctionnement

Les tests de performance doivent couvrir temps de chargement, recherche, filtres, tableaux, imports, exports, tableaux de bord, API et automatisations.

Les seuils doivent etre adaptes au contexte SaaS multi-entreprises.

## Dependances

Les tests de performance dependent des modules, API, base de donnees, UX, imports, automatisations et volumes de donnees.

## Permissions

Les tests doivent verifier que les controles de permission ne degradent pas excessivement les temps de reponse.

## Automatisations

Les tests de performance peuvent etre automatises pour detecter les regressions.

## Points de vigilance

Ne pas tester uniquement avec peu de donnees.

Ne pas oublier les imports et les tableaux avec filtres.

## A confirmer

- Seuils de performance V1.
- Volumes de donnees de reference.
- Strategie de tests de charge future.
