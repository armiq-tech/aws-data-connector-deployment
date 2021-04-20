# Data Connector for SAP on AWS
  User Deployment Guide - AWS Marketplace : [Data Connector for SAP on AWS](https://aws.amazon.com/marketplace/pp/B08JCMQ9PT)
## Introduction
  ARMIQ Data Connector for SAP is an SAP add-on software, written in the Advanced Business Application Programming (ABAP) language, that enables SAP systems to integrate with AWS using IDoc & Hana client. By deploying AWS serverless infrastructure in AWS, enterprises can leverage AWS services as an extension of their SAP workloads using the same tools and programing language they already use.
     
  This guide will detail the steps to deploy the AWS Serverles PaaS service with AWS CDK. Also, we offer ABAP Program for SAP user.
   
## Prerequisites and Requirements
### Deploy application using IDE environment
  1. Recommend IDE Tool : [Visiual Studio Code (VS Code)](https://code.visualstudio.com/)
  2. Install the extension : [AWS Toolkit for Visual Studio Code](https://aws.amazon.com/ko/visualstudiocode/)
  3. Configure the AWS CLI with AWS Toolkit for VS Code.
  4. Establish the AWS credentials by using the AWS Toolkit for VS Code
  5. Install the AWS CDK command line interface
   
  **NOTE:** If you are setting up the AWS credentials with the extension tool for the first time, you can follow the documentation at <https://docs.aws.amazon.com/toolkit-for-vscode/latest/userguide/welcome.html> to configure the AWS credentials.
### Time
  The deployment will take about [30 Minutes], but configuration and testing could take up to [2 Hours].
### Product License
  Bring your own license (BYOL) - Subscribe throught the AWS Marketplace and apply an existing license. Generally appropriate for deployments with extremely heavy usage, abnormal access patterns, or other concerns. Please contact us directly to order a license at helpdesk@armiq.com. You can check our BYOL policy in product page, following site: <https://aws.amazon.com/marketplace/pp/B08JCMQ9PT>
### AWS Account
  You must have an AWS account set-up. If you don't, we recommend that you visit the following sithe: <https://aws.amazon.com/getting-started>
### AWS Identity and Access Management (IAM) Entity
  Create an IAM user or role. Your IAM user should have a policy that allows AWS CloufFormation actions. Do not use your root account to deploy the CloudFormation template. In addition to AWS CloudFormation actions, IAM users who create or delete stacks will alse require additional permissions that depend on the stack template. This deployment requires permissions to all services listed in the following section.   
  Reference: <https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/usingiam-template.html>

