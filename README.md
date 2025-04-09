# 🚀 Terraform AWS Lab Guide

This repository contains all hands-on exercises and configuration files based on the **Terraform Lab Guide for AWS**. The goal is to help understand and practice Terraform fundamentals and real-world AWS infrastructure provisioning using Infrastructure as Code (IaC) principles.

## 📚 What You’ll Learn

- Installing and configuring Terraform on Windows
- Working with Terraform in Visual Studio Code
- Initializing and configuring the AWS provider
- Managing AWS authentication securely
- Creating and managing AWS resources:
  - VPCs and subnets
  - EC2 instances
  - Using variables, locals, outputs, and sensitive data
  - Working across multiple regions using aliases
  - Switching between environments using workspaces
- Using **Vault** to manage sensitive secrets
- Importing existing AWS resources into Terraform
- Using **Terraformer** to discover and manage real AWS infrastructure
- Building reusable infrastructure using **modules**

## 🛠 Technologies Used

- [Terraform](https://www.terraform.io/)
- [AWS](https://aws.amazon.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [HashiCorp Vault](https://www.vaultproject.io/)
- [Terraformer](https://github.com/GoogleCloudPlatform/terraformer)

## 📁 Project Structure

```bash
.
├── main.tf                   # Main configuration file
├── provider.tf               # AWS and Vault providers configuration
├── variables.tf              # Input variables declaration
├── terraform.tfvars          # Variable values
├── outputs.tf                # Output values
├── resource.tf               # AWS resources (VPC, Subnets, EC2, etc.)
├── modules/                  # Modularized infrastructure code
│   ├── ec2_instance/
│   ├── s3_bucket/
│   ├── dynamodb_table/
│   ├── security_group/
│   ├── vpc_endpoints/
│   └── network/
└── README.md                 # Project documentation (this file)
 
