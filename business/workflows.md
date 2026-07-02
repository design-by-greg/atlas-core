# Workflows

## Objectif

Definir les workflows metier transversaux d'ATLAS.

## Regles officielles

Un workflow ATLAS doit etre clair, tracable, configurable et compatible avec plusieurs organisations.

Chaque workflow doit avoir un declencheur, des etapes, des statuts, des validations, des permissions, des automatisations possibles et un historique.

## Fonctionnement

Workflow commercial et operationnel de base :

1. Identification du contact.
2. Creation du projet.
3. Collecte du besoin.
4. Creation du devis.
5. Validation du devis.
6. Collecte des elements necessaires.
7. Validation graphique ou fonctionnelle si applicable.
8. Transformation en commande.
9. Preparation de la production.
10. Production ou execution.
11. Livraison ou cloture.
12. Suivi administratif selon le module concerne.

Ce workflow doit rester adaptable selon l'organisation et le type d'activite.

## Dependances

Les workflows dependent des modules contacts, projets, devis, commandes, production, catalogue, factures, portail client et notifications.

## Permissions

Chaque changement d'etape doit respecter les permissions de l'utilisateur.

Les actions sensibles doivent etre reservees aux roles autorises.

## Automatisations

Automatisations possibles : creation de taches, notification interne, notification client, generation de document, rappel, mise a jour de tableau de bord et archivage apres cloture.

## Points de vigilance

Ne pas creer un workflow different pour chaque cas particulier.

Ne pas automatiser une decision sensible sans validation.

Ne pas dupliquer les statuts entre modules sans justification.

## A confirmer

- Detail exact du passage devis vers commande.
- Conditions de creation automatique des factures.
- Variantes par type d'organisation.
