# AWS-CloudFormation-CICD-Project-with-Glue-Jobs

This project consists of a CloudFormation stack that sets up a CI/CD pipeline for deploying Glue Jobs with the necessary IAM permissions and job descriptions. The stack automates the provisioning of AWS resources required for the pipeline.

## Prerequisites

Before deploying the CloudFormation stack, ensure you have the following:

1. An AWS account with appropriate permissions to create and manage CloudFormation stacks, IAM roles, Glue jobs, and related resources.
2. A GitHub repository containing the source code for your Glue Jobs.


## Stack Details

This CloudFormation stack consists of the following components:

CodePipelineCFT: Creates the CI CD Pipeline to deploy all these stacks.

Common Stack: Creates the necessary IAM permissions for all Glue jobs to run.
    
Upwork Stack: Creates Glue jobs, triggers, and workflows specific to Upwork.

Guru Stack: Creates Glue jobs, triggers, and workflows specific to Guru.

You can modify these stacks or add additional stacks as per your project requirements. Each stack encapsulates the relevant Glue jobs and their associated resources.
