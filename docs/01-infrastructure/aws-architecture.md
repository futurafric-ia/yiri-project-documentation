# Architecture AWS

## Objectif

Documenter l'infrastructure AWS utilisée par les projets YIRI ainsi que les composants déployés via Terraform.

## Services AWS identifiés

| Service | Utilisation | Statut |
|---------|-------------|--------|
| AWS Glue | Traitement et orchestration des données (ETL) | Identifié (module Terraform présent) |
| Terraform (HCL) | Gestion de l'infrastructure en tant que code (IaC) | Identifié (langage du dépôt) |
| À compléter | À compléter après analyse des modules | À analyser |

## Ressources déployées

- **Terraform** : le dépôt est écrit à 100 % en HCL, confirmant l'usage de Terraform pour provisionner l'infrastructure.
- **AWS Glue** : présence confirmée d'un module Terraform dédié (commit « Ajout du module Glue Terraform »).
- Le dossier `terraform-module/` contient les modules d'infrastructure (à détailler).
- Ressources AWS en cours d'analyse (S3, IAM, RDS, Lambda, VPC, EC2... à confirmer).

## Architecture réseau

En cours d'analyse à partir des modules Terraform (VPC, subnets, security groups à identifier dans le dossier `terraform-module/`).

## Sécurité et accès

En cours d'analyse à partir des configurations Terraform (rôles IAM, policies, secrets à identifier).

## Sources analysées

- Dépôt : [yiri-aws-data-infrastructure](https://github.com/futurafric-ia/yiri-aws-data-infrastructure)
- Branche : `main`
- Dossier clé : `terraform-module/`
- Langage : HCL (Terraform) à 100 %
- État de l'analyse : En cours