# BrightCart – Scalable Serverless E-Commerce Platform on AWS

This project demonstrates a full-scale, real-world AWS serverless architecture for **BrightCart Retail Group**, a fictional online retailer looking to modernize its e-commerce platform. The architecture is designed to be secure, scalable, highly available, and cost-optimized — capable of handling traffic spikes like Black Friday with zero downtime.

---

## Architecture Diagram

![Architecture Diagram](./architecture.png)

---

## Project Deliverables

- `architecture.png` – High-level AWS architecture diagram
- `proposal.docx` – Formal technical proposal explaining architecture, security, cost analysis, and enhancements
- `README.md` – Project overview and documentation (this file)

---

## Objectives

- Replace legacy monolith with modern AWS-native components
- Enable seamless auto-scaling for large traffic surges
- Improve load speeds via global CDN caching
- Ensure security and compliance (JWT auth, WAF, encryption)
- Deploy updates efficiently with CI/CD
- Deliver excellent uptime and observability with low cost

---

##  AWS Services Used

| Category       | AWS Services                                                                 |
|----------------|------------------------------------------------------------------------------|
| **Frontend**    | Amazon S3 (static site hosting), Amazon CloudFront (CDN), Amazon Route 53   |
| **Security**    | AWS WAF, AWS Shield, Amazon Cognito, IAM                                     |
| **API Layer**   | Amazon API Gateway, AWS Lambda                                               |
| **Database**    | Amazon DynamoDB                                                              |
| **Monitoring**  | Amazon CloudWatch, AWS X-Ray, Amazon SNS                                     |
| **CI/CD**       | AWS CodePipeline, AWS CodeBuild                                              |

---

## Cost Summary (Sample Estimate)

| Service          | Monthly Estimate |
|------------------|------------------|
| Amazon S3        | $1.15            |
| CloudFront       | $50              |
| API Gateway      | $19              |
| Lambda           | ~$2              |
| DynamoDB         | ~$3              |
| Cognito          | $0 (under 50k MAUs) |
| WAF              | $16              |
| CloudWatch + SNS | ~$10             |
| CodePipeline     | ~$2              |
| **Total**        | **~$100/month**  |

---

## Security Features

- **Cognito-based JWT auth**
- HTTPS (TLS 1.2+) enforced via ACM
- AWS WAF rules to block common web exploits
- IAM least privilege across all roles
- S3 + DynamoDB encryption at rest
- CloudWatch + GuardDuty monitoring
- IAM Access Analyzer to detect misconfigurations

---

## Future Roadmap

- Multi-region DR setup using DynamoDB Global Tables + Route 53 failover
- Product search with Amazon OpenSearch
- Real-time recommendations using Amazon Personalize
- Lambda@Edge for geolocation-based personalization
- DAX for DynamoDB read optimization
- CloudWatch Synthetics for canary testing

---

## Learning Objectives

This project showcases:

- Serverless web app architecture
- Real-world authentication flows with Amazon Cognito
- CI/CD pipelines for Lambda + static sites
- API Gateway integrations with Lambda and throttling
- Budget-conscious AWS design

---

## Author

**Surya Ravichandran**  
Cloud Solutions Architect & Analytics Enthusiast  
suryaravichandran0108@gmail.com
[LinkedIn](https://www.linkedin.com/in/surya-ravichandran/)  

---

## License

This project is part of a public cloud architecture portfolio for educational and demonstration purposes. You are welcome to fork or reuse with credit.
