# Annotation

## Objectif

L'annotation consiste à enrichir les données brutes avec des informations structurées afin de permettre leur utilisation dans les systèmes d'intelligence artificielle, les traitements automatiques et le développement de ressources linguistiques pour les langues locales.

## Cas d'utilisation

L'annotation est utilisée pour :

- L'entraînement des modèles de traitement automatique du langage naturel (NLP)
- La traduction automatique entre le français et les langues locales
- La classification de contenus textuels, audio et visuels
- La reconnaissance d'entités nommées
- L'analyse sémantique
- La transcription et l'alignement linguistique
- L'évaluation et l'amélioration des performances des modèles IA

## Langues concernées

Les campagnes d'annotation portent principalement sur les langues locales suivantes :

- Dioula
- Baoulé
- Bété
- Sénoufo
- Yacouba

D'autres langues pourront être intégrées en fonction des besoins du projet.

## Types de données annotées

### Données textuelles

Exemples :

- Mots
- Expressions
- Phrases
- Conversations
- Documents
- Traductions
- Corpus linguistiques

### Données audio

Exemples :

- Enregistrements vocaux
- Conversations audio
- Prononciations
- Discours
- Contenus multilingues

### Données images

Exemples :

- Images illustratives
- Documents numérisés
- Supports pédagogiques
- Images associées à des descriptions textuelles

## Types d'annotations

Voici une représentation visuelle des différents types d'annotations réalisées sur les langues locales ivoiriennes :

```mermaid
graph TD
    subgraph Classification & Linguistique
        A1["Phrase : 'I ni ce'<br/>Langue : Dioula<br/>Catégorie : Salutation<br/>Sens : Bonjour"]
        A2["Phrase : 'N'djé'<br/>Langue : Baoulé<br/>Catégorie : Salutation<br/>Sens : Bonjour"]
    end

    subgraph Traduction
        B1["Français : Comment vas-tu ?<br/>Dioula : 'I ka kéné wa ?'"]
        B2["Français : Merci<br/>Bété : 'Kôssô'"]
    end

    subgraph Transcription Audio
        C1["Audio : 'I ni sogoma'<br/>Transcription : 'I ni sogoma'<br/>Langue : Dioula<br/>Traduction : Bonjour"]
    end

    subgraph Annotation d'Images
        D1["Image : Femme vendant des fruits<br/>Langue : Sénoufo<br/>Description : Marché traditionnel<br/>Catégorie : Commerce local"]
    end

    subgraph Reconnaissance d'Entités
        E1["Texte : 'Je viens de Korhogo'<br/>Langue : Français<br/>Entité : Korhogo (Ville)"]
        E2["Texte : 'N bô la Korhogo'<br/>Langue : Dioula<br/>Entité : Korhogo (Ville)"]
    end

    style A1 fill:#f9f,stroke:#333
    style A2 fill:#f9f,stroke:#333
    style B1 fill:#bbf,stroke:#333
    style B2 fill:#bbf,stroke:#333
    style C1 fill:#bfb,stroke:#333
    style D1 fill:#fbf,stroke:#333
    style E1 fill:#ffb,stroke:#333
    style E2 fill:#ffb,stroke:#333