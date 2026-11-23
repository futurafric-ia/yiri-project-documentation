# Dépendances

## Dépôts liés

- Liste des dépôts et de leurs liens : À confirmer après analyse.

## Bases de données

- Type de bases de données utilisées : À confirmer
- Fournisseur (Supabase, AWS RDS, etc.) : À confirmer

## Services cloud

- Services AWS utilisés : À confirmer
- Autres services (Lovable Cloud, Supabase, etc.) : À confirmer

## API externes

- À compléter après analyse.

## Dépendances entre composants

```mermaid
graph LR
    A[yiri-data-collection] --> B[(Base de données)]
    B --> C[Yiri]
    C --> D[annotation-yiri]
    C --> E[yiri-data-studio]
    C --> F[yiri-sync-studio]