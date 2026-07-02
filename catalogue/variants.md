# Variants

## Objectif

Definir la structure officielle des variantes produit dans ATLAS.

## Regles officielles

Une variante represente une version precise d'un produit.

Les differences comme taille, couleur, reference fournisseur, prix ou stock doivent etre portees par la variante lorsque cela est pertinent.

## Fonctionnement

Une variante peut contenir : reference interne, reference fournisseur, couleur, taille, prix, stock, poids, dimensions, delai, statut et media specifique.

Un produit peut avoir plusieurs variantes.

## Dependances

Les variantes dependent des produits, couleurs, tailles, prix, stocks, fournisseurs et imports.

## Permissions

La modification des variantes doit etre limitee aux roles autorises.

## Automatisations

Les variantes peuvent etre creees ou mises a jour par import fournisseur avec controle de correspondance.

## Points de vigilance

Ne pas creer un produit different pour chaque variante.

Ne pas dupliquer les prix ou stocks si la variante est la bonne source.

## A confirmer

- Champs variantes obligatoires.
- Regles de correspondance entre reference fournisseur et reference interne.
