# AWS Solution Architectures Portfolio

This repository contains real-world, end-to-end AWS architecture projects developed by Surya Ravichandran to simulate cloud solution architecture scenarios. Each project includes a fully designed architecture diagram, detailed technical proposal, cost and performance considerations, and deployment strategies.

### Purpose
To showcase hands-on cloud architecture expertise through practical examples of industry use cases, using AWS native services with a focus on:
- Scalability
- High availability
- Cost optimization
- Security
- Serverless design patterns

---

## Projects

### 1. BrightCart – Scalable Serverless E-Commerce Platform
**Use Case**: Modernize a legacy e-commerce system to support traffic spikes (e.g., Black Friday sales) with zero downtime.  

**Architecture Includes**: Amazon S3, CloudFront, Route 53, API Gateway, AWS Lambda, DynamoDB, Cognito, WAF, CloudWatch, SNS, CodePipeline.  

**Highlights**:
- Fully serverless and auto-scaling
- WAF and Cognito for layered security
- CI/CD via AWS CodePipeline and CodeBuild
- Realistic cost breakdown and optimization recommendations

[View Project Folder](./brightcart-ecommerce-architecture)

### 2. HealthSync – Real-Time Patient Monitoring System
**Use Case**: Build a cloud-native platform to ingest and analyze real-time biometric data from IoT-enabled wearables, trigger clinical alerts, and support long-term analytics and predictive healthcare insights —
all with high availability and HIPAA-aligned security. 

**Architecture Includes**: AWS IoT Core, Kinesis Data Streams, Lambda, API Gateway, Step Functions, EventBridge, SNS, SES, DynamoDB, S3 + Glacier, Glue, Athena, QuickSight, SageMaker, Route 53, CloudFormation, 
CodePipeline, WAF, KMS, IAM, CloudWatch, CloudTrail.

**Highlights**:
- Real-time event-driven architecture with IoT integration
- Multi-region disaster recovery using Route 53, Global Tables, and S3 CRR
- AI/ML layer with Amazon SageMaker for early health risk detection
- Fully serverless with end-to-end CI/CD using CodePipeline and CloudFormation
- HIPAA-style compliance with encryption, least privilege IAM, and full auditability

[View Project Folder](./HealthSync-Architecture)

---

## Author

**Surya Ravichandran**  
Cloud Solutions Architect | Data & Cloud Enthusiast  
[LinkedIn](https://www.linkedin.com/in/surya-ravichandran/) 

---

## License

This repo is for learning and demonstration purposes. You are welcome to fork and build upon the ideas.
