# Final Project Solution: AWS Cloud - Technical Expressions and Best Practices

## Overview
This project is a solution for deploying a scalable, secure, and highly available web application on AWS. It covers various AWS services and best practices to ensure the infrastructure is well-architected.

### Key Components:
1. **Network Infrastructure (IaC)**: Using AWS CloudFormation/Terraform to manage network environments.
2. **Web Application Hosting**: Deploying EC2 or ECS-based applications with Auto Scaling and Load Balancing.
3. **Static Storage**: Storing static content in S3, using CloudFront for global CDN distribution.
4. **Monitoring**: Integrating CloudWatch for real-time monitoring, alarms, and SNS notifications.
5. **Automatic Remediation**: Lambda-based remediation and Auto Scaling for web service health.
6. **Security**: IAM, security groups, and VPC configurations for secure access.
7. **Redirection to HTTPS**: Configuring ALB for HTTP to HTTPS redirection.
8. **EC2 to S3 Mount**: Mounting an S3 bucket onto an EC2 instance.
9. **API Gateway**: Exposing S3 content via RESTful APIs.

## Instructions
### Prerequisites
- AWS account with necessary permissions.
- AWS CLI, Terraform, or AWS CloudFormation knowledge.
  
### Setup
#### 1. **Network Infrastructure**
- Navigate to the `network-setup` folder.
- Follow the instructions in the README files to deploy the network using either CloudFormation or Terraform.

#### 2. **Deploy Web App**
- In the `web-app` folder, choose between EC2 or ECS and deploy the web application.

... [Add more instructions for each component]

## AWS Services Used
- EC2
- S3
- CloudFront
- IAM
- CloudWatch
- Lambda
- API Gateway
- Auto Scaling
- Load Balancer

