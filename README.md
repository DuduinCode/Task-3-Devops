# Task 3 - DevOps Internship

## Objective
Provision a Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- AWS EC2 (Ubuntu)

## Steps
1. Initialized Terraform using `terraform init`
2. Planned infrastructure using `terraform plan`
3. Applied configuration using `terraform apply`
4. Verified Docker container running on port 8080
5. Destroyed infrastructure using `terraform destroy`
6. Used `terraform state list` to check tracked resources

## Output
Docker container running nginx on port 8080.

## Commands Used
```bash
terraform init
terraform plan
terraform apply
terraform destroy
terraform state list
