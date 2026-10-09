# terraform3

Infraestructura como código (Terraform + Azure) para el entorno QA:
Resource Group, Log Analytics, Application Insights, App Service Plan (F1) y Linux Web App (Node.js).

## Uso
```bash
cp terraform.tfvars.example terraform.tfvars   # pon tu subscription_id real
az login
terraform init
terraform plan
terraform apply
```
