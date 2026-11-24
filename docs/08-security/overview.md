# Sécurité

## Objectif

Cette phase décrit les mesures de sécurité mises en place pour protéger les données, les applications, les infrastructures et les utilisateurs du projet YIRI.

## Principes de sécurité

La stratégie de sécurité repose sur les principes suivants :

- Confidentialité
- Intégrité
- Disponibilité
- Traçabilité
- Contrôle des accès

## Sécurité de l'infrastructure

### Hébergement AWS

L'infrastructure est hébergée sur AWS. Les mesures de protection incluent :

- Isolation des ressources
- Contrôle des accès
- Gestion des rôles
- Journalisation des activités
- Chiffrement des données

## Gestion des identités et des accès

### AWS IAM

Les accès aux ressources AWS sont gérés via IAM.

Objectifs :

- Gestion des utilisateurs
- Gestion des groupes
- Attribution des rôles
- Application du principe du moindre privilège

### Principe du moindre privilège

Chaque utilisateur dispose uniquement des accès nécessaires à ses missions.

Exemple :

```text
Développeur
→ Accès aux environnements DEV

Administrateur
→ Accès complet à l'infrastructure

Utilisateur métier
→ Accès aux fonctionnalités métier