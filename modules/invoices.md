# Invoices

## Objectif

Definir le module factures d'ATLAS.

## Regles officielles

Une facture represente un document administratif et financier.

Elle doit etre generee selon des regles metier validees.

## Fonctionnement

Une facture contient client, lignes, montants, taxes, statut, paiement, documents et historique.

## Dependances

Quotes, orders, contacts, organizations, payments futurs et customer portal.

## Permissions

Creation, modification, annulation et export sont reservees aux roles autorises.

## Automatisations

Generation, envoi, relance et suivi peuvent etre automatises sous conditions.

## Points de vigilance

Ne pas creer de facture sans evenement ou regle validee.

## A confirmer

- Moment exact de creation facture.
- Regles de paiement.
