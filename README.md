# AWS Resource Listing Automation Script

## 📌 Overview

This project is a Bash automation script that lists AWS resources by service and region using the AWS CLI.

It was built to strengthen my Linux, Bash scripting, and Cloud/DevOps automation skills.

---

## 🚀 Features

- Accepts AWS region and service as arguments
- Validates AWS CLI installation
- Verifies AWS CLI configuration
- Uses case statements for service-based logic
- Supports multiple AWS services

---

## 🛠 Supported AWS Services

- EC2
- RDS
- S3
- CloudFront
- VPC
- IAM
- Route53
- CloudWatch
- CloudFormation
- Lambda
- SNS
- SQS
- DynamoDB
- EBS

---

## 📂 Project Structure

```
aws-resource-list/
│
├── aws_resource_list.sh
└── README.md
```

---

## ⚙️ Prerequisites

- Linux or macOS environment
- AWS CLI installed
- AWS CLI configured (`aws configure`)
- Valid IAM credentials

---

## ▶️ Usage

```bash
chmod +x aws_resource_list.sh
./aws_resource_list.sh <aws_region> <aws_service>
```

### Example:

```bash
./aws_resource_list.sh us-east-1 ec2
```

---

## 💡 What I Learned

- Bash scripting fundamentals
- Argument validation
- Case statement logic
- AWS CLI automation
- Linux command-line tooling
- AWS service structure and resource inspection

---

## 🎯 Future Improvements

- Add logging functionality
- Add JSON formatting options
- Add support for listing all services at once
- Implement error handling improvements

---

## 👨🏾‍💻 Author

**Olowookere Damilola**  
AWS Certified Solutions Architect – Associate  
Cloud / DevOps Engineer
This is my first shell project
