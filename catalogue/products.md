# Products

## Objectif

Definir la structure officielle des produits dans le catalogue ATLAS.

## Regles officielles

Un produit est une reference commerciale ou technique pouvant etre proposee, configuree, vendue ou utilisee dans un projet.

Un produit ne doit pas dupliquer les donnees de ses variantes.

## Fonctionnement

Un produit contient le nom, la description, la categorie, le fournisseur, les catalogues, les techniques compatibles, les variantes, les medias, les prix, les delais et le statut d'activation.

Les produits doivent etre reutilisables par plusieurs organisations lorsque le contexte SaaS le permet.

## Dependances

Les produits dependent des fournisseurs, variantes, couleurs, tailles, techniques, prix, stocks, medias et imports.

## Permissions

La gestion des produits doit etre limitee aux roles autorises.

Les utilisateurs commerciaux peuvent consulter les produits actifs selon leurs droits.

## Automatisations

Un produit peut etre cree ou mis a jour via import fournisseur, avec controle avant publication si necessaire.

## Points de vigilance

Ne pas stocker au niveau produit une information propre a une variante.

Ne pas creer plusieurs produits identiques pour des differences mineures.

## A confirmer

- Champs obligatoires produit.
- Regles de publication produit.
- Gestion des produits propres a une organisation.
