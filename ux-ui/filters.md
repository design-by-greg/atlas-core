# Filters

## Objectif

Definir les regles officielles des filtres dans ATLAS.

## Regles officielles

Les filtres doivent permettre de retrouver rapidement l'information utile sans complexifier l'interface.

Les filtres doivent etre coherents entre les modules.

## Fonctionnement

Les filtres courants peuvent concerner : statut, date, utilisateur, organisation, client, fournisseur, priorite, module, categorie et montant.

Les filtres frequents doivent pouvoir etre sauvegardes si necessaire.

## Dependances

Les filtres dependent des tableaux, modules, statuts, permissions et donnees disponibles.

## Permissions

Un filtre ne doit pas permettre d'acceder a des donnees non autorisees.

## Automatisations

Des vues filtrees peuvent etre proposees automatiquement selon le role ou les actions en attente.

## Points de vigilance

Ne pas multiplier les filtres inutiles.

Ne pas rendre les filtres differents d'un module a l'autre sans raison.

## A confirmer

- Filtres par defaut par module.
- Regles de vues sauvegardees.
