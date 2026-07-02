# Validations

## Objectif

Definir les regles de validation metier dans ATLAS.

## Regles officielles

Une validation confirme qu'une action, une etape ou un document peut avancer dans le workflow.

Les validations doivent etre tracables, explicites et liees a des permissions.

## Fonctionnement

Les validations peuvent concerner les devis, les commandes, les elements client, les validations graphiques, la production, la livraison, la facture, une action IA sensible ou une automatisation sensible.

Chaque validation doit enregistrer l'utilisateur, la date, l'objet valide et le contexte.

## Dependances

Les validations dependent des workflows, statuts, permissions, notifications, portail client et historique.

## Permissions

Seuls les roles autorises peuvent valider une etape sensible.

Certaines validations peuvent etre internes, d'autres externes via le portail client.

## Automatisations

Une validation peut declencher un changement de statut, une notification, la creation d'une commande, la generation d'un document ou une mise a jour du portail client.

Une automatisation ne doit pas simuler une validation humaine sensible.

## Points de vigilance

Ne pas confondre consultation et validation.

Ne pas permettre une validation sans trace.

Ne pas valider automatiquement une action irreversible sans accord explicite.

## A confirmer

- Liste exacte des validations obligatoires par module.
- Regles de validation client via portail.
- Niveau de preuve attendu pour chaque validation.
