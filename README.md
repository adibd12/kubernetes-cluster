# kubernetes-cluster

terraform init || exit 1
terraform validate || exit 1 && terraform plan
terraform apply -auto-approve
