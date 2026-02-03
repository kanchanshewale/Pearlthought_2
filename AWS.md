## AWS – What I Learned Today
Overview

Today I learned about the AWS and Terraform and understood how Terraform can be used to launch AWS resources, especially an EC2 instance, using Infrastructure as Code instead of manual steps from the AWS console.

What I Understood About AWS

AWS provides cloud infrastructure where we can create servers, networking, and storage on demand. Instead of managing physical servers, AWS allows everything to be managed using services and APIs.

AWS Services I Learned Today
## IAM (Identity and Access Management)

I learned how AWS controls access using IAM.

Users, Groups, and Roles

Policies define permissions

IAM is required for Terraform to authenticate with AWS

## EC2 (Elastic Compute Cloud)

EC2 is a virtual server in AWS.

I learned about:

EC2 Instance

## AMI (Amazon Machine Image)

Instance Type

Key Pair (for SSH access)

Security Group (acts as a firewall)

This is the main service I used with Terraform.

## VPC 

I learned that all AWS resources run inside a VPC (Virtual Private Cloud).

Networking components I understood:

VPC

CIDR block

Public Subnet

Private Subnet

Route Table

Internet Gateway

NAT Gateway (high-level understanding)

## Security Group & NACL

Security Group works at the instance level and is stateful

NACL works at the subnet level and is stateless

Both are used to control inbound and outbound traffic.
