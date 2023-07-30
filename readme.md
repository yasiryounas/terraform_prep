Terraform Instruction:

To download and install the terraform providers:
terraform init

To apply the configuration/plan
terraform apply

To destroy Terraform

terraform destroy

to destroy specific resource

terraform destroy -target aws_vpc.development-vpc

to check the state

terraform state list

to apply auto approve

terraform apply -auto-approve

to check the status

terraform plan