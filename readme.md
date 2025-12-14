# Cloud-Based Serverless Data Flow (AWS S3 → Lambda → RDS)

Event-driven pipeline where uploads to S3 trigger AWS Lambda processing and store results in RDS.
Built with secure IAM permissions, scalable separation of storage/compute, and CloudWatch logging.


---
## Project Structure

aws-s3-lambda-rds-dataflow/
├─ lambda/
│  ├─ handler.py
│  ├─ requirements.txt
│  └─ README.md
├─ infra/
│  ├─ template.yaml   (SAM)  OR  cdk/terraform files
│  └─ README.md
├─ sample_data/
├─ docs/
├─ .gitignore
└─ README.md

---

## Tech
AWS S3, AWS Lambda, RDS, IAM, CloudWatch


## What it does
- Detects new objects in S3
- Processes/validates/transforms file content in Lambda
- Writes outputs to an RDS table
- Logs metrics and errors to CloudWatch

## How to run
(Add your deployment steps: SAM/CDK/Terraform + env vars/secrets)



