# iacwtf
Introducing Infrastructure As Code With Terraform

```
stash-okta --profile stash-training --okta-profile stash-training
```

```bash
# Login via stash-cli (pick training-stash-employee)
stash-okta --profile default

# Show all bucket
aws s3 ls
```

### Notes
Terraform creates 10 resources in parallel.

### Commands

1. Download terraform, unzip, and move to `/usr/local/bin`
2. cd into terraform/hello_terraform
3. It will create a `terraform.tfstate`. Do not delete it. It will orphan any resources created.

```bash
# See version
$ terraform version

# First three steps
$ terraform init
$ terraform plan
$ terraform apply

# Terraform's view of the world
$ terraform state list
$ terraform output
$ terraform fmt
```
