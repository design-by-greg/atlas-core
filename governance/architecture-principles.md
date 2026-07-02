# Architecture Principles

## Objectif

Définir les principes d'architecture fonctionnelle qui garantissent la stabilité, l'évolutivité et la maintenabilité d'ATLAS.

## Règles officielles

ATLAS repose sur une architecture modulaire.

Chaque module doit pouvoir évoluer indépendamment sans compromettre la stabilité du logiciel.

Les modules doivent communiquer entre eux sans créer de dépendances fortes.

Toute nouvelle fonctionnalité doit respecter l'architecture existante.

Aucun développement ne doit contourner les règles communes pour répondre à un besoin isolé.

## Fonctionnement

Les modules doivent être conçus comme des briques métier autonomes.

Chaque module possède :

- ses responsabilités ;
- ses règles métier ;
- ses statuts ;
- ses permissions ;
- ses validations ;
- ses automatisations éventuelles ;
- ses dépendances explicites.

Une dépendance entre modules doit être justifiée par un flux métier réel.

Exemple de dépendances acceptables :

- une commande peut dépendre d'un devis validé ;
- une facture peut dépendre d'une commande ou d'un paiement ;
- un projet peut regrouper des contacts, assets, devis, commandes et productions ;
- le portail client peut exposer des informations issues de plusieurs modules sans en devenir propriétaire.

## Dépendances

Les dépendances doivent être documentées dans chaque fichier de module.

Une donnée ne doit avoir qu'une source principale.

Un module peut lire une donnée d'un autre module, mais ne doit pas la dupliquer inutilement.

## Permissions

L'architecture doit permettre :

- plusieurs organisations ;
- plusieurs utilisateurs ;
- plusieurs rôles ;
- plusieurs permissions ;
- plusieurs catalogues ;
- plusieurs fournisseurs ;
- plusieurs langues à terme ;
- plusieurs devises à terme.

Toute règle doit être compatible avec ce modèle SaaS multi-entreprises.

## Automatisations

Les automatisations doivent être transversales lorsque cela est pertinent, mais ne doivent pas créer de couplage fort entre les modules.

Chaque automatisation doit indiquer :

- son déclencheur ;
- son action ;
- sa condition ;
- son niveau de validation ;
- sa trace dans l'historique.

## Points de vigilance

Ne pas créer :

- de logique spécifique à une seule organisation ;
- de dépendance circulaire entre modules ;
- de duplication de statuts ;
- de tables ou entités redondantes ;
- de workflows parallèles qui font la même chose ;
- d'automatisations opaques.

## À confirmer

- La cartographie technique finale entre modules applicatifs et modules documentaires.
- Les conventions de nommage définitives pour les entités métier.
