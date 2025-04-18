# AWS ECS Terraform Project

This repository contains Terraform configuration for deploying applications to AWS ECS (Elastic Container Service).

## Prerequisites

- Terraform installed (version 1.0+)
- AWS CLI configured with appropriate credentials
- An AWS account with permissions to create ECS resources

## Project Structure

- `main.tf` - Main Terraform configuration file for ECS resources
- `provider.tf` - AWS provider configuration
- `variables.tf` - Input variables for the Terraform configuration

## Getting Started

1. Clone this repository
2. Initialize Terraform:
   ```
   terraform init
   ```
3. Review the planned changes:
   ```
   terraform plan
   ```
4. Apply the configuration:
   ```
   terraform apply
   ```

## Destroying Resources

To destroy all resources created by this Terraform configuration:
```
terraform destroy
```

## Note

Make sure to review and update variable values in `variables.tf` or through a `.tfvars` file before applying changes to your infrastructure. 