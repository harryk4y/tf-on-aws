In this workshop, Terraform was used as the Infrastructure as Code (IaC) tool to deploy a highly available Wordpress application in a single region. It will be configured to leverage a Multi-AZ (data replication across multiple AZs) MySQL database and an auto-scaler based on CPU utilization for web hosting.


This is from a tf on aws workshop - [click here for the link to workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/41c5a1b6-bd3e-41f4-bd46-85ab7dc6dad4/en-US/0-introduction)


<h4> Architecture </h4>

![architecture](img/p06-00-architecture.png)  

<br />  
<br>

The AWS Services that are used in this workshop are:

<b> AWS Identity and Access Management  (AWS IAM) </b> - securely manage identities and access to AWS services and resources  
<b> Amazon Virtual Private Cloud  (Amazon VPC) </b> - define and launch AWS resources in a logically isolated virtual environment  
<b> Amazon Elastic Compute Cloud  (Amazon EC2) </b>- provides scalable computing capacity  
<b> Amazon Relational Database Service  (Amazon RDS) </b> - fully managed, open-source cloud database service that allows you to easily operate and scale your relational database  
<b> Amazon Simple Storage Service  (Amazon S3) </b> - object storage service offering industry-leading scalability, data availability, security, and performance  
<b> Amazon Elastic File System  (Amazon EFS) </b> - serverless, fully elastic file storage  
<b> AWS Simple Systems Manager  (SSM) </b> - operations hub for your AWS applications and resources and a secure end-to-end management solution  
<b> AWS Secrets Manager </b>  - manage, retrieve, and rotate database credentials, tokens, API keys, and other secrets  
<b> AWS Certificate Manager  (ACM) </b> - provision and manage SSL/TLS certificates with AWS services and connected resources  
<b> Amazon CloudFront </b> - content delivery network (CDN) service built for high performance, security, and developer convenience  
