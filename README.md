>>>Hashicorp terraform installation

sudo yum install -y yum-utils shadow-utils

sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo

sudo yum -y install terraform


>>>check the version 

terraform --version

Terraform runs on 4 commands
terraform init  ->initialize
terraform plan  ->Dry run
terraform apply
terraform destroy
