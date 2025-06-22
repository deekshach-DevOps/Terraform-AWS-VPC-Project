# Terraform AWS VPC Project

This project provisions a basic web server infrastructure on AWS using Terraform, including:

- VPC, Subnet, Route Table, Internet Gateway
- Security Group allowing ports 22, 80, 443
- Elastic IP and Network Interface
- EC2 instance running Apache2 with a custom HTML page

## Requirements
- AWS CLI configured
- Terraform installed
- A key pair in AWS (named `terra-key`)

## How to Use
```bash
terraform init
terraform plan
terraform apply
 
Author
Deeksha Choudhary


Add and push again:
```bash
git add README.md
git commit -m "Add README"
git push
