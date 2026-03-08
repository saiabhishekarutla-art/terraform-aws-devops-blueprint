# Terraform AWS DevOps Blueprint

This project demonstrates how to provision AWS infrastructure using Terraform as Infrastructure-as-Code.

The goal of this project was to practice building cloud infrastructure programmatically instead of manually through the AWS console.

## What this project does

- Configures the AWS provider using Terraform
- Creates an AWS VPC using a CIDR block
- Uses Infrastructure-as-Code to manage cloud resources
- Demonstrates the Terraform workflow:
  - terraform init
  - terraform plan
  - terraform apply
  - terraform destroy

## Tech Stack

- Terraform
- AWS (VPC)
- AWS CLI
- Git
- GitHub

## Project Files

`main.tf`  
Contains the Terraform configuration for creating the AWS VPC.

`.gitignore`  
Prevents Terraform state files from being pushed to GitHub.

`.terraform.lock.hcl`  
Locks the Terraform provider version for consistent deployments.

## Key Learning

While working on this project I practiced:

- configuring AWS CLI credentials
- provisioning infrastructure using Terraform
- managing infrastructure lifecycle (create → update → destroy)
- following best practices by excluding Terraform state files from Git

## Result

Successfully created and destroyed AWS VPC infrastructure using Terraform.
