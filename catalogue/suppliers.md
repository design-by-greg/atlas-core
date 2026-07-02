# Suppliers

## Objectif

Definir la structure officielle des fournisseurs dans ATLAS.

## Regles officielles

Un fournisseur est une entite externe qui fournit des produits, services, tarifs, medias, delais ou stocks.

Les fournisseurs doivent etre modelises de maniere generique.

## Fonctionnement

Chaque fournisseur doit pouvoir contenir des informations legales, contacts, catalogues associes, conditions tarifaires, delais, frais, fichiers importes, regles de mise a jour et historique.

Un fournisseur peut alimenter plusieurs catalogues.

## Dependances

Les fournisseurs dependent des produits, variantes, tarifs, stocks, medias et imports.

## Permissions

La creation, modification ou suppression d'un fournisseur doit etre reservee aux roles autorises.

## Automatisations

Les imports fournisseurs pourront mettre a jour les produits, tarifs, stocks et medias selon des regles controlees.

## Points de vigilance

Ne pas dupliquer un fournisseur pour chaque catalogue.

Ne pas ecraser des donnees validees sans controle.

## A confirmer

- Champs fournisseurs obligatoires.
- Regles de priorite entre donnees fournisseur et donnees internes.
