# Stock Rules

## Objectif

Definir les regles de gestion du stock dans ATLAS.

## Regles officielles

Le stock doit etre rattache a la bonne source : fournisseur, organisation, entrepot, produit ou variante selon le contexte.

Le stock fournisseur et le stock interne doivent etre distingues.

## Fonctionnement

Les informations de stock peuvent inclure quantite, disponibilite, delai, source, date de mise a jour et niveau de fiabilite.

Le stock peut etre informatif ou bloquant selon la configuration.

## Dependances

Les stocks dependent des fournisseurs, produits, variantes, commandes, production et imports.

## Permissions

La modification manuelle du stock doit etre reservee aux roles autorises.

## Automatisations

Les stocks peuvent etre mis a jour par import fournisseur ou mouvement interne.

Une alerte peut etre declenchee en cas de stock faible, indisponible ou incoherent.

## Points de vigilance

Ne pas confondre stock fournisseur et stock disponible pour une organisation.

Ne pas garantir une disponibilite sans source fiable.

## A confirmer

- Niveau de gestion stock en V1.
- Regles de reservation de stock.
- Gestion multi-entrepots future.
