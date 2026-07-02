# Security Tests

## Objectif

Definir les tests de securite officiels d'ATLAS.

## Regles officielles

La securite doit etre verifiee pour chaque module, workflow, permission, automatisation et assistant IA.

Les donnees d'une organisation doivent rester strictement separees des autres organisations.

## Fonctionnement

Les tests de securite doivent couvrir authentification, autorisation, isolation des organisations, acces aux donnees, actions sensibles, journaux, exports et actions IA.

Les tentatives d'acces non autorise doivent etre refusees et tracees si necessaire.

## Dependances

Les tests de securite dependent des permissions, roles, organisations, modules, API, IA et automatisations.

## Permissions

Chaque permission sensible doit etre testee avec des profils autorises, limites et non autorises.

## Automatisations

Les automatisations doivent etre testees pour verifier qu'elles n'executent pas d'action interdite.

## Points de vigilance

Ne pas oublier les acces indirects via API, portail client, notifications ou IA.

Ne pas exposer de donnees sensibles dans les messages ou exports.

## A confirmer

- Liste des scenarios de securite prioritaires.
- Niveau de journalisation attendu.
- Politique de tests d'intrusion future.
