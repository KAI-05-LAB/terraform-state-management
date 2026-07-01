# Terraform State Management

## Objective

This project demonstrates updating AWS infrastructure using Terraform and understanding Terraform state management.

## Infrastructure

- AWS VPC
- Public Subnet
- Security Group

## Infrastructure Changes

Compared to the previous task:

- Updated VPC name
- Updated subnet name
- Added HTTPS (443) rule to the security group

## Terraform Commands

Initialize Terraform

```bash
terraform init
```

Validate Configuration

```bash
terraform validate
```

Preview Changes

```bash
terraform plan
```

Apply Changes

```bash
terraform apply
```

View State

```bash
terraform show
```

List State Resources

```bash
terraform state list
```

Destroy Infrastructure

```bash
terraform destroy
```

## What is Terraform State?

Terraform stores information about the infrastructure it manages in a state file (`terraform.tfstate`). The state file helps Terraform determine what changes need to be made when infrastructure is updated.

## What I Learned

- Infrastructure updates using Terraform
- Terraform state management
- AWS networking resources
- Infrastructure versioning
- Infrastructure as Code (IaC)

## Challenges Faced

Understanding Terraform state management and how Terraform tracks infrastructure changes was initially challenging. Learning about state files, planning changes, and updating resources helped me understand infrastructure lifecycle management.
