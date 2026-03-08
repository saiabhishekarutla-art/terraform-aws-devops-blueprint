# AWS VPC Infrastructure with Terraform

In this project I practiced building AWS networking infrastructure using Terraform instead of manually creating resources in the AWS console.

The goal was to understand how Infrastructure as Code works and how Terraform manages cloud resources.

## What this project creates

The Terraform configuration provisions a small AWS networking setup that includes:

- A custom VPC
- A public subnet
- An Internet Gateway
- A route table
- Route table association for internet access

This setup represents the basic networking structure many AWS environments start with.

## Tools used

- Terraform
- AWS
- Git
- GitHub

## Terraform workflow used

I used the standard Terraform lifecycle while working on this project:

Initialize Terraform

```bash
terraform init
```

Review infrastructure plan

```bash
terraform plan
```

Deploy infrastructure

```bash
terraform apply
```

Destroy infrastructure after testing

```bash
terraform destroy
```

## What I learned

While working on this project I practiced:

- Writing Terraform configuration files
- Provisioning AWS infrastructure using code
- Understanding Terraform planning and state
- Managing infrastructure changes using Git and GitHub

This project helped me better understand how DevOps teams manage cloud infrastructure using Infrastructure as Code.

## Result

Successfully created and destroyed AWS VPC infrastructure using Terraform.

