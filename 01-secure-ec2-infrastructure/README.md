# 01 - Secure EC2 Infrastructure (Traditional Architecture)

## Project Overview

This project focuses on building a secure traditional AWS infrastructure using EC2, VPC, IAM, and logging services.  

The goal is to understand foundational AWS networking, Linux server management, and cloud security best practices before moving to advanced cloud-native architectures.

This project is being built as part of a structured AWS Cloud Security learning path.

---

## Objectives

- Secure AWS account foundation (MFA, IAM, budget alerts)
- Enable account-level logging using CloudTrail
- Build custom VPC (no default VPC usage)
- Deploy Linux EC2 instance securely
- Implement least-privilege IAM roles
- Restrict network exposure using Security Groups
- Monitor and analyze logs
- Document security decisions and lessons learned

---

## Planned Architecture

Internet  
↓  
Custom VPC  
↓  
Public Subnet  
↓  
EC2 (Linux Web Server)  
↓  
IAM Role (no hardcoded credentials)  
↓  
CloudTrail + S3 Logging  

More components will be added in later phases (monitoring, detection, hardening).

---

## Security Principles Applied

- Root account protected with MFA
- IAM admin user used for daily operations
- Budget alert configured to prevent unexpected billing
- Logging enabled before infrastructure deployment
- Least privilege approach for IAM roles
- No hardcoded credentials inside EC2

---

## Skills Being Developed

- AWS account governance
- IAM fundamentals
- VPC networking
- Linux server administration
- Cloud logging and monitoring
- Infrastructure hardening

---

## Status

Project initialized.  
Account security configured.  
GitHub documentation structure created.  
CloudTrail setup pending.
