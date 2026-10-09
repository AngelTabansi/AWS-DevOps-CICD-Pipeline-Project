# AWS DevOps CI/CD Pipeline Project

**Project Title:** CI/CD Pipeline Deployment Using AWS CodePipeline, CodeBuild and CodeDeploy

**By Angel**

## Project Overview

This project demonstrates the deployment of a web application using an automated Continuous Integration and Continuous Delivery (CI/CD) pipeline on AWS.

The pipeline integrates GitHub with AWS CodePipeline, CodeBuild, and CodeDeploy to automate the application deployment process to an Amazon EC2 instance.

## AWS Services and Tools Used

- **GitHub:** Source code repository.
- **Amazon EC2:** Hosts the deployed web application.
- **Amazon EC2 Security Groups:** Controls inbound and outbound network traffic.
- **AWS CodeDeploy:** Deploys application revisions to the EC2 instance.
- **AWS CodeBuild:** Builds the application and executes the configured build process.
- **AWS CodePipeline:** Coordinates the source, build/test, and deployment stages.

## Project Implementation

### Step 1: Git Repository

Used a GitHub repository to store the application source code and provide the source stage for the pipeline.

### Step 2: Amazon EC2 Instance

Launched an EC2 instance to host the web application targeted by the deployment process.

### Step 3: Security Group

Configured the EC2 security group to allow the network traffic required to access the deployed application.

### Step 4: AWS CodeDeploy

Created a CodeDeploy application and deployment group to manage application deployments to the EC2 instance.

### Step 5: AWS CodeBuild

Configured a CodeBuild project connected to the source repository and verified successful build executions.

### Step 6: AWS CodePipeline

Created a pipeline connecting the source, build/test, and deployment stages. Verified successful execution of the pipeline.

### Final Result

The deployment completed successfully, and the application was displayed in a web browser with the message:

**“Welcome to DevOps with AWS ANGEL”**

## Skills Demonstrated

- CI/CD pipeline configuration
- GitHub source control integration
- Amazon EC2 deployment
- AWS CodeBuild configuration
- AWS CodeDeploy configuration
- AWS CodePipeline orchestration
- Security group configuration
- Deployment troubleshooting and validation

## Project Evidence

The accompanying Word document contains screenshots of the GitHub repository, EC2 instance, security group, CodeDeploy application, CodeBuild project, successful CodePipeline execution, and the deployed website.

## Project Type

AWS DevOps Training Project
