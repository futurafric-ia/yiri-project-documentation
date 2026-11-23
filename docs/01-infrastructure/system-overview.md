# Vue d'ensemble de l'écosystème YIRI

Ce document présente la cartographie globale de l'écosystème YIRI, les liens entre les différents dépôts et les flux de données principaux.

> **Note :** Certains liens sont déduits de l'analyse préliminaire et restent à confirmer lors de l'analyse détaillée de chaque dépôt.

## Cartographie des flux et dépendances

```mermaid
graph TD
    A[yiri-data-collection] --> B[(Bases de données)]
    B --> C[Yiri - Plateforme d'annotation]
    
    C --> D[annotation-yiri]
    C --> E[yiri-data-studio]
    C --> F[yiri-sync-studio]
    
    D --> G[yiri-lingua-hub]
    
    G --> H[yiri_module_tts_tokenizer]
    G --> I[yiri-module-tts]
    
    subgraph Infrastructure
        J[yiri-aws-data-infrastructure]
    end
    
    subgraph Hors ligne
        K[yiri-offline]
    end