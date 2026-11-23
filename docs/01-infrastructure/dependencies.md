## Dépendances cloud

- **AWS** : infrastructure principale provisionnée via Terraform.
- **AWS Glue** : utilisé pour le traitement et l'orchestration des données.
- **Terraform** : outil d'IaC (Infrastructure as Code) utilisé pour déployer les ressources.
- Autres services AWS (S3, RDS, Lambda, IAM, VPC...) : à identifier dans `terraform-module/`.