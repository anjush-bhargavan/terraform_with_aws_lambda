# terraform_with_aws_lambda

# Terraform AWS Lambda Configuration

This Terraform project manages the creation of an AWS Lambda function along with the necessary IAM role and policy to support it.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html)
- [AWS CLI](https://aws.amazon.com/cli/)
- AWS IAM User with appropriate permissions

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/anjush-bhargavan/terraform_with_aws_lambda.git
   cd terraform-aws-lambda

2. Initialize Terraform and install dependencies:

   ```bash
    terraform init

4. Set up AWS credentials either by configuring the AWS CLI or by exporting environment variables:
 
    ```bash
    export AWS_ACCESS_KEY_ID=<your-access-key-id>
    export AWS_SECRET_ACCESS_KEY=<your-secret-access-key>
    export AWS_DEFAULT_REGION=<your-region>
    ```
  
4. Review the Terraform plan to ensure that everything is configured correctly:
    ```bash
      terraform plan
    ```
5. Apply the Terraform configuration to create the AWS resources:
    ```bash
      terraform apply

6. Confirm the changes by typing yes when prompted.

## Clean Up

To avoid incurring charges, it's recommended to destroy the resources when they are no longer needed:
  ```bash
  terraform destroy
    
