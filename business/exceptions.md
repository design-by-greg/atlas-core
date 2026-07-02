# Exceptions

## Objectif

Definir la gestion officielle des exceptions metier dans ATLAS.

## Regles officielles

Une exception est un cas particulier qui sort du workflow normal.

Une exception doit etre geree sans casser la coherence du produit.

Elle ne doit pas devenir une regle globale sans validation.

## Fonctionnement

Une exception doit indiquer :

- le module concerne ;
- le motif ;
- l'utilisateur responsable ;
- la decision prise ;
- l'impact ;
- la trace dans l'historique ;
- le retour possible au workflow normal.

Les exceptions peuvent concerner une annulation, un retard, un refus, une erreur, une correction, un cas client particulier ou une action manuelle autorisee.

## Dependances

Les exceptions dependent des workflows, statuts, permissions, validations, notifications et historique.

## Permissions

Les exceptions doivent etre limitees aux roles autorises.

Une exception sensible doit etre justifiee et tracee.

## Automatisations

Une exception peut declencher une alerte, une tache, une notification ou un blocage temporaire.

Une automatisation ne doit pas masquer une exception.

## Points de vigilance

Ne pas multiplier les exceptions pour contourner les regles.

Ne pas transformer un cas specifique en fonctionnement standard.

Ne pas permettre une exception non tracee.

## A confirmer

- Typologie officielle des exceptions.
- Niveau de justification requis par type d'exception.
- Visibilite des exceptions dans les tableaux de bord.
