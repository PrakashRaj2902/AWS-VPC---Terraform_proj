**# AWS-VPC---Terraform_proj**

This project demonstrates how to create an AWS Virtual Private Cloud (VPC) with both public and private subnets, a NAT gateway, and essential security configurations using Terraform. This setup is suitable for applications requiring both public-facing and private resources, with controlled internet access via the NAT gateway.

Project Overview

This Terraform project includes:
- Creation of a VPC with a specified CIDR block.
- Public and private subnets within the VPC.
- An Internet Gateway for public subnet internet access.
- A NAT Gateway for secure outbound access from private subnets.
- Security groups to control inbound and outbound traffic.
