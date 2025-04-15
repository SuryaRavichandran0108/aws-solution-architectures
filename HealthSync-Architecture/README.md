# HealthSync – Real-Time Patient Monitoring System

This project presents a full-stack, cloud-native, serverless architecture for a fictional healthcare platform called **HealthSync**. It collects and analyzes real-time biometric data from IoT-enabled wearable devices, processes and alerts clinicians in real-time, stores patient data securely for long-term access, and provides analytics and AI-driven predictive insights.

## 📌 Project Highlights
- **Real-time Ingestion** via AWS IoT Core and Kinesis
- **Event-driven Processing** using Lambda, EventBridge, and Step Functions
- **Immediate Notification System** through SNS, SES, and Slack (via Chatbot)
- **Scalable Data Storage** using DynamoDB and Amazon S3 with Glacier for archival
- **Historical Analytics Layer** with Glue Catalog, Athena, and QuickSight
- **AI/ML Extension** using Amazon SageMaker for predictive healthcare modeling
- **Multi-Region Disaster Recovery** with Route 53, Global Tables, and CRR
- **CI/CD & Infrastructure as Code** through CodePipeline, CodeBuild, and CloudFormation
- **Security-first Design** including IAM, KMS, WAF, and CloudTrail

## 📁 Folder Contents
- `architecture.png` – Final architecture diagram
- `case-study.pdf` – Full documentation with problem statement, architecture decisions, and detailed explanations
- `README.md` – Project summary (this file)

## 🔒 Compliance Ready
This architecture is designed with HIPAA-style security considerations including encryption at rest, strict IAM boundaries, audit logging, and secure data flow practices.

---

For more cloud architecture projects like this, visit [your GitHub profile or portfolio link here].
