# Architecture AWS

## Objectif

Documenter l'architecture cloud (AWS) de l'écosystème YIRI, les services utilisés et la manière dont ils sont déployés.

## Comptes AWS utilisés

| Compte | Identifiant | Usage | Statut |
|--------|-------------|-------|--------|
| À confirmer | À confirmer | À confirmer | À vérifier |

## Services AWS identifiés

| Service | Usage | Statut |
|---------|-------|--------|
| À confirmer | À confirmer | À vérifier |

## Ressources déployées

- À compléter après analyse de `yiri-aws-data-infrastructure`.

## Schéma d'architecture

```mermaid
graph TD
    A[Utilisateurs] --> B[Frontend / CDN]
    B --> C[API / Backend]
    C --> D[(Bases de données)]
    C --> E[Services de traitement]

    

code docs/01-infrastructure/environments.md

