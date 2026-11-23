# Inventaire des dépôts YIRI

## Objectif

Identifier les dépôts du projet YIRI, leur rôle, leurs technologies,
leurs responsables et leurs liens avec les autres composants.

## État de cet inventaire

Liste initiale issue du cadrage de la mission.
L'existence, les URL et le rôle des dépôts restent à vérifier.
Le statut de l'analyse documentaire ne décrit pas l'état du projet.

## Dépôts candidats

| Dépôt | URL vérifiée | Rôle confirmé | Technologies | Responsable | Analyse documentaire |
|---|---|---|---|---|---|
| Yiri | https://github.com/futurafric-ia/yiri | Plateforme d’annotation en langues ivoiriennes permettant la gestion et l’annotation de données linguistiques. | TypeScript
React
Vite
shadcn-ui
Tailwind CSS
Supabase
PLpgSQL
Node.js / npm  | FuturAfric  | README analysé. Technologies principales identifiées. Présence des dossiers src/ et supabase/. Analyse détaillée de l’architecture, des fonctionnalités et de la base de données à poursuivre |
| yiri-data-studio | https://github.com/futurafric-ia/yiri-data-studio | Application web du projet YIRI développée avec React et TypeScript, intégrant une base de données Supabase et des fonctionnalités liées à la gestion et à l’annotation des données. | TypeScript
React
Vite
Tailwind CSS
Shadcn/UI
Supabase
Drizzle ORM
Node.js / npm |FuturAfric  | Première analyse réalisée. README consulté, technologies principales identifiées, architecture détaillée à approfondir. |
| yiri-sync-studio |https://github.com/futurafric-ia/yiri-sync-studio | Plateforme communautaire dédiée aux langues ivoiriennes (français, dioula, baoulé, nouchi) accessible sur community.yiri.africa.  | React 19
TypeScript
Vite
TanStack Start
Tailwind CSS v4
PLpgSQL
Backend Lovable Cloud | FuturAfric  | En cours |
| yiri-data-collection | https://github.com/futurafric-ia/yiri-data-collection | Collecte automatisée de données à travers des scripts destinés à alimenter les corpus et les jeux de données du projet YIRI. | À approfondir (présence confirmée de scripts d'automatisation de collecte de données) | FuturAfric | Description du dépôt identifiée. Le dépôt est dédié à la collecte automatisée de données. Analyse détaillée du code, des sources de données et des technologies en cours. |
| yiri-module-tts | https://github.com/futurafric-ia/yiri-module-tts | Module de synthèse vocale (Text-To-Speech - TTS) du projet YIRI permettant la génération de parole à partir de textes dans les langues prises en charge par la plateforme. | À approfondir (module IA/TTS identifié, technologies exactes à confirmer) | FuturAfric | Dépôt identifié et URL vérifiée. Le dépôt semble dédié aux fonctionnalités de synthèse vocale (TTS) de l'écosystème YIRI. Analyse détaillée du code, des modèles IA, des dépendances et des pipelines de traitement en cours. |
| yiri_module_tts_tokenizer | https://github.com/futurafric-ia/yiri_module_tts_tokenizer | Module de tokenisation utilisé dans le pipeline de synthèse vocale (TTS) du projet YIRI. Il participe à la préparation et à la transformation des données textuelles avant leur traitement par les modèles de synthèse vocale. | À approfondir (module de traitement linguistique identifié, technologies exactes à confirmer) | FuturAfric | Dépôt identifié et URL vérifiée. Le dépôt semble dédié à la tokenisation et au prétraitement des textes pour les composants TTS de l'écosystème YIRI. Analyse détaillée du code, des algorithmes de tokenisation et des dépendances en cours. |
| yiri-aws-data-infrastructure | https://github.com/futurafric-ia/yiri-aws-data-infrastructure | Dépôt dédié à l'infrastructure AWS du projet YIRI. Il centralise la configuration, le déploiement et la gestion des ressources cloud nécessaires au fonctionnement de l'écosystème YIRI. | AWS
Infrastructure as Code (à confirmer)
Terraform / HCL (à confirmer après analyse détaillée) |FuturAfric | Dépôt identifié et URL vérifiée. Analyse préliminaire réalisée. Le dépôt semble dédié à l'infrastructure cloud du projet YIRI. L'identification des services AWS, des architectures de déploiement et des configurations techniques est en cours. |
| yiri-offline | https://github.com/futurafric-ia/yiri-offline | pplication YIRI conçue pour fonctionner en mode hors ligne, permettant l'utilisation et la gestion des fonctionnalités du projet sans dépendance permanente à une connexion Internet.  |TypeScript
React
Vite
Node.js
JavaScript
CSS
HTML | FuturAfric | Dépôt identifié et URL vérifiée. Analyse préliminaire réalisée. Présence d'une application frontend basée sur TypeScript et React. Architecture fonctionnelle détaillée, mécanismes de synchronisation et gestion des données hors ligne à approfondir. |

