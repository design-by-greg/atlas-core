# Notifications

## Objectif

Definir les regles officielles des notifications dans ATLAS.

## Regles officielles

Une notification doit informer la bonne personne, au bon moment, pour une action utile.

Les notifications doivent etre pertinentes, configurables et eviter la surcharge.

## Fonctionnement

Les notifications peuvent etre internes ou externes.

Elles peuvent concerner :

- changement de statut ;
- validation requise ;
- document disponible ;
- action client attendue ;
- retard ;
- anomalie ;
- tache assignee ;
- rappel ;
- evenement important du workflow.

Chaque notification doit avoir un destinataire, un contexte, un niveau d'importance et une trace si necessaire.

## Dependances

Les notifications dependent des workflows, statuts, validations, permissions, automatisations, utilisateurs et portail client.

## Permissions

Une notification ne doit jamais exposer une information a un utilisateur non autorise.

Les notifications client doivent respecter les droits du portail client.

## Automatisations

Les notifications peuvent etre declenchees automatiquement par un changement de statut, une validation, une echeance, une anomalie ou une action utilisateur.

## Points de vigilance

Ne pas envoyer trop de notifications.

Ne pas notifier des utilisateurs non concernes.

Ne pas exposer des donnees sensibles dans un message externe.

## A confirmer

- Canaux de notification disponibles en V1.
- Parametrage des preferences utilisateur.
- Liste exacte des evenements notifiables.
