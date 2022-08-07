# lambda-intance-info

Requirements

    To get instance information use lambda function

Instance tagname

        Service = "Data"

Ubuntu

    $ wget https://releases.hashicorp.com/terraform/0.13.5/terraform_0.13.5_linux_amd64.zip
    $ unzip terraform_0.13.5_linux_amd64.zip
    $ sudo mv terraform /usr/local/bin

Reference:

    https://www.terraform.io/downloads.html

variables:

    accessKey           =""
    secretKey           =""
    region              ="eu-west-1"
    lambdaname          ="lambda-aws-ec2-info"

commands

    1. terraform version
    2. terraform init
    3. terraform plan -var-file=config.tfvars
    4. terraform apply -var-file=config.tfvars
    5. terraform destroy -var-file=config.tfvars
