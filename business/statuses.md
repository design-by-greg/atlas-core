# Statuses

## Objectif

Definir les principes de gestion des statuts dans ATLAS.

## Regles officielles

Un statut represente un etat metier clair et utile.

Chaque statut doit appartenir a un module ou a un workflow identifie.

Un statut ne doit pas etre duplique sous plusieurs noms si le sens est identique.

## Fonctionnement

Les statuts doivent permettre de suivre l'avancement d'un element : projet, devis, commande, production, facture ou demande client.

Chaque statut doit preciser :

- son nom ;
- son module ;
- sa signification ;
- les transitions autorisees ;
- les permissions requises ;
- les automatisations declenchees ;
- les conditions de sortie.

## Dependances

Les statuts dependent des workflows, roles, permissions, validations, notifications et automatisations.

## Permissions

Tous les utilisateurs ne peuvent pas modifier tous les statuts.

Les statuts critiques comme valide, annule, facture, livre ou cloture doivent etre limites aux roles autorises.

## Automatisations

Un changement de statut peut declencher une notification, une tache, une generation de document, une mise a jour de portail client ou une entree dans l'historique.

## Points de vigilance

Ne pas creer trop de statuts.

Ne pas melanger statut metier, priorite et categorie.

Ne pas permettre une transition incoherente.

## A confirmer

- Liste finale des statuts par module.
- Transitions autorisees pour chaque workflow.
- Statuts visibles dans le portail client.
