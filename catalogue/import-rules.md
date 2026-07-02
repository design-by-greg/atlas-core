# Import Rules

## Objectif

Definir les regles officielles d'import catalogue dans ATLAS.

## Regles officielles

Les imports doivent mettre a jour les donnees fournisseur sans creer de doublons ni remplacer des informations controlees sans validation.

Chaque import doit etre tracable.

## Fonctionnement

Un import peut concerner fournisseurs, produits, variantes, couleurs, tailles, prix, stocks et medias.

Chaque import doit prevoir la source, le format, la date, les correspondances, les erreurs, les donnees creees, les donnees modifiees et les donnees ignorees.

## Dependances

Les imports dependent des fournisseurs, produits, variantes, prix, stocks, medias et regles de validation.

## Permissions

L'import doit etre reserve aux roles autorises.

La publication des changements peut demander une validation distincte.

## Automatisations

Les imports pourront etre manuels, planifies ou semi-automatiques.

Les changements sensibles doivent rester controlables avant publication.

## Points de vigilance

Ne pas creer de doublons lors d'un import.

Ne pas remplacer des donnees internes sans arbitrage.

Ne pas publier automatiquement des donnees incertaines.

## A confirmer

- Formats d'import supportes en V1.
- Strategie de mapping fournisseur.
- Regles de validation avant publication.
