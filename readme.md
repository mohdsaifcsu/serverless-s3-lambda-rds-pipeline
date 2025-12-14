# Cloud-Based Serverless Data Flow (AWS S3 → Lambda → RDS)

Event-driven pipeline where uploads to S3 trigger AWS Lambda processing and store results in RDS.
Built with secure IAM permissions, scalable separation of storage/compute, and CloudWatch logging.

## Tech
AWS S3, AWS Lambda, RDS, IAM, CloudWatch

## What it does
- Detects new objects in S3
- Processes/validates/transforms file content in Lambda
- Writes outputs to an RDS table
- Logs metrics and errors to CloudWatch

## How to run
(Add your deployment steps: SAM/CDK/Terraform + env vars/secrets)
