
# Cloud Engineering Challenge

## Diagram

<img src="./Diagram.jpg">

## Features
1. VPC and subnets
2. Security groups
3. Load balancer
4. EC2 running Apache

## What is this?
A minimalistic production-ready environmnet in Terraform for running a rudimentary web-application that returns a "Hello Graylog!" string upon a GET https request.

## What is Terraform?
[Terraform](https://www.terraform.io) is an infrastructure as a code tool that helps manage our cloud resources.

## How it works?
I installed Apache in the EC2 instance and edited the ```index.html``` so whenever we do a GET request, it returns "Hello Graylog!" 

## How to install and run this?
If you plan on using this in your environmnet, you need to follow these steps: 
1. Install terraform using these steps [here](https://learn.hashicorp.com/tutorials/terraform/install-cli)
2. Clone this repository if you haven't already
3. Configure your AWS user by running ```aws configure``` in CLI
4. Follow the Terraform workflow by running ```terraform init```, ```terraform validate```, ```terraform plan```, ```terraform apply``` in CLI
5. To teardown infrastructure, run ```terraform destroy``` in CLI


## Credit
1. [Terraform documentation](https://www.terraform.io/docs)

## License

[MIT License](https://github.com/Tobiajet/Cloud-Challenge/blob/main/LICENSE)
