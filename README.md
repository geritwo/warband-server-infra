# Mound and Blade Warband Server AWS Infrastructure

Creates AWS ECS resources from CloudFormation. 
- ECR Repository
- ECS Cluster, Task Definition and Service

## Prerequisites

Create IAM user for AWS operations and add to repo secrets as:
- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_DEPLOY_BUCKET

## How to use

GitHub Actions will depoy the resources in your account whenever master is updated.
