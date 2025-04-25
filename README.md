# AWS-IAM-Policy-Validation-Automation
This repository demonstrates how to integrate **IAM policy validation** into your **CI/CD pipeline** using **GitHub Actions** and **AWS IAM Access Analyzer**.

## 🖼️ CI/CD Design Overview
![CI/CD IAM Policy Validation Flow](./cicd-iam-policy-validation.png)

## ✅ Prerequisites

- An AWS account with:
  - IAM Access Analyzer enabled
  - An IAM role configured for GitHub OIDC access
  - A reference policy stored in S3
- GitHub repository with appropriate secrets configured
