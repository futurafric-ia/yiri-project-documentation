# Phase 4 - Gestion des données

## Objectif

Cette section décrit le cycle de vie des données au sein de l'écosystème YIRI, depuis leur collecte jusqu'à leur exploitation et leur archivage.

## Sources de données

Les données peuvent provenir de plusieurs sources :

- Applications web et mobiles YIRI
- Saisies utilisateurs
- Fichiers importés
- API externes
- Sources de données partenaires

## Collecte des données

Les données sont collectées via :

- Formulaires applicatifs
- Services API
- Processus automatisés d'importation
- Pipelines de traitement de données

## Stockage des données

### Base de données relationnelle

- **Service** : AWS RDS
- **Objectif** : stockage des données métiers
- **Gestion des accès** : via les rôles applicatifs

### Stockage de fichiers

- **Service** : Amazon S3
- **Objectif** : stockage des documents, médias et exports
- **Gestion** : des versions et des sauvegardes

## Traitement des données

### AWS Glue

Utilisation de AWS Glue pour :

- Extraction des données
- Transformation des données
- Chargement des données (ETL)
- Préparation des jeux de données analytiques

### Flux de traitement

Voici une représentation visuelle du cycle de vie de la donnée dans YIRI :

```mermaid
graph TD
    A[Sources de données] --> B[Collecte]
    B --> C[Validation]
    C --> D[Transformation - AWS Glue]
    D --> E[Stockage - RDS / S3]
    E --> F[Consommation par les applications]
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style D fill:#bbf,stroke:#333,stroke-width:2px
    style E fill:#bbf,stroke:#333,stroke-width:2px