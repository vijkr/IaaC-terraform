# Terraform code is used to provision the infrastructure.

This code deploys the following services on the AWS Platform: VPC, Public Subnet, Private Subnet, Internetgateway, Routetable, SubnetAssociation, EC2, and RDS. I haven't started working on ALB.

Steps for deploying the resources.

- Configure your awscli with the target AWS account's IAM accesskey and secretkey.
- This code was developed with Terraform 1.6.4.
- Clone the repository https://github.com/vijkr/IaaC-terraform.git and unzip the file.
- Navigate the Terraform directory.
- Run the following commands.


```bash
  terraform init
  terraform plan (will check what are the resources will deploy)
  terraform apply (proceed with Yes)
```