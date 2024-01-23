# Project Name

## Infrastructure Setup using Terraform

This project contains Terraform scripts for setting up the following infrastructure:

1. AWS VPC with subnets in different availability zones.
2. AWS Security Groups for Kubernetes cluster.
3. AKS (Amazon Kubernetes Service) cluster.
4. S3 bucket for storing application logs.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed.
- AWS credentials configured.

## How to Use

1. Clone this repository.

2. Modify variables in `variable.tf` to suit your requirements.

3. Run the following commands in the terminal:

  ```
  terraform init
  ```
  
  ```
  terraform validate
  ```
  
  ```
  terraform plan
  ```
  
  ```
  terraform apply
  ```