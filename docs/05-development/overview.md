# Phase 6 - Développements

## Objectif

Cette phase décrit l'ensemble des développements réalisés dans le cadre du projet YIRI, les technologies utilisées, l'organisation du code source et les bonnes pratiques de développement.

## Architecture de développement

Le projet est organisé en plusieurs composants :

- Frontend
- Backend
- Services de données
- Infrastructure AWS
- Pipelines de traitement
- Services d'intelligence artificielle

## Environnements de développement

### Développement (DEV)

Environnement utilisé par les développeurs pour les nouvelles fonctionnalités.

### Staging

Environnement de validation avant mise en production.

### Production

Environnement accessible aux utilisateurs finaux.

## Gestion du code source

### Dépôts Git

Les développements sont gérés à travers des dépôts Git dédiés :

- Documentation
- Infrastructure AWS
- Backend
- Frontend
- Services Data

### Branches

Organisation recommandée :

```text
main
develop
feature/*
hotfix/*
release/*