# DevOps URL Shortener

This project is a fully automated DevOps stack built for the London (eu-west-2) AWS region.

## Quickstart

1. Install Terraform & AWS CLI
2. Configure AWS CLI: `aws configure` (choose eu-west-2)
3. Clone this repo
4. Run `make init` (init Terraform)
5. Run `make apply` (create VPC, subnet, and S3 bucket in London)
6. See your resources in AWS London
7. Create a Kafka topic request (see infra/kafka/requests/)
8. To destroy everything: `make destroy`
