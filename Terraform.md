## Terraform – What I Learned 

Today I learned the basics of Terraform and how it is used to automate AWS infrastructure instead of creating resources manually from the AWS console.

## What is Terraform

Terraform is an Infrastructure as Code (IaC) tool that allows us to define cloud resources using configuration files and manage them in an automated way.

## Why Terraform

I learned that Terraform is useful because:

Infrastructure can be created using code

The same code can be reused multiple times

Changes are tracked and predictable

It reduces manual work and human errors

Infrastructure as Code (IaC)

IaC means managing infrastructure using files instead of clicking in the UI.

## With Terraform:

Infrastructure definitions are written in .tf files

Resources are created automatically

Infrastructure can be stored in Git

Terraform with AWS

I learned how Terraform works with AWS using the AWS provider.

## Terraform uses:

AWS credentials for authentication

Provider block to connect to AWS

Resource block to create AWS services

## Terraform Files I Learned About

main.tf – main Terraform configuration

variables.tf – defines input variables

outputs.tf – shows useful values after execution

terraform.tfstate – keeps track of created resources

## Terraform Workflow

I practiced the basic Terraform workflow:

terraform init
Initializes the project and downloads required providers.

terraform plan
Shows what Terraform will create before applying changes.

terraform apply
Creates the AWS resources defined in the code.

terraform destroy
Removes all resources created by Terraform.

Launching EC2 Using Terraform 

## understood how an EC2 instance can be launched using Terraform by:

Defining the AWS provider

Writing an EC2 resource block

Applying the configuration using Terraform commands

This avoids manual EC2 creation from the AWS console.

AWS Services Used with Terraform Today

IAM (for access and permissions)

EC2 (compute)

VPC (network)

Subnet

Security Group
