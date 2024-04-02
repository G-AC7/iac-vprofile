[![vprofile IAC](https://github.com/G-AC7/iac-vprofile/actions/workflows/terraform.yml/badge.svg)](https://github.com/G-AC7/iac-vprofile/actions/workflows/terraform.yml)

# Terraform code 

## Maintain vpc & eks with terraform for vprofile project

## Tools required
Terraform version 1.6.3

### Steps
* terraform init
* terraform fmt -check
* terraform validate
* terraform plan -out planfile
* terraform apply -auto-approve -input=false -parallelism=1 planfile
####
#####
