
IncidentPulse is a real-time enterprise-style DevOps project designed to simulate how organizations manage production incidents, incident evidence, remediation documents, and operational audits using Linux and AWS.

---

## Project Overview

This project demonstrates secure file handling, role-based access control, automation, encrypted storage, and scalable cloud infrastructure following real-world DevOps practices.

The system allows:
- Engineers to upload incident evidence securely  
- Incident leads to manage runbooks and remediation documents  
- Audit teams to review logs and compliance records  

---

## Features

- Secure evidence upload using FTP with TLS
- Role-based access control using Linux permissions and ACLs
- Automated backups and archival using cron jobs
- Encrypted storage using LUKS
- Logical Volume Management (LVM) for storage scalability
- AWS S3 storage with lifecycle policies
- Highly available architecture using Load Balancer and Auto Scaling
- Metadata storage using RDS MySQL
- CloudFront secure distribution
- Lambda and API Gateway integration

---

## Technologies Used

### Linux
- User and group management
- File permissions and ACLs
- FTP with TLS
- NFS configuration
- Cron jobs
- LVM
- LUKS encryption

### AWS
- EC2
- S3
- IAM
- VPC
- RDS (MySQL)
- Application Load Balancer
- Auto Scaling Group
- CloudFront
- Lambda
- API Gateway

---

## Architecture Workflow

1. Users access the portal hosted on EC2.
2. Engineers upload incident evidence securely.
3. Files are validated and stored.
4. Backups and archival are automated.
5. Metadata is stored in RDS.
6. Runbooks are distributed securely using CloudFront.

---

## Directory Structure (Example)



incidentpulse-devops-portal/
│
├── linux-setup/
├── automation/
├── aws/
├── database/
├── architecture/
└── docs/



---

## Learning Outcomes

- Linux system administration in production-like environments
- Secure storage and access control
- Cloud infrastructure design on AWS
- Automation and monitoring
- Real-world DevOps workflow simulation

---

## Challenges Faced

- Managing Linux permissions across multiple roles
- Configuring secure FTP with restrictions
- Designing VPC networking and routing
- Automating storage expansion
- Integrating multiple AWS services securely

---

## Conclusion

IncidentPulse successfully demonstrates a secure, scalable, and automated incident management system using Linux and AWS. The project provides hands-on experience with enterprise-level DevOps practices and cloud infrastructure design.

---

## Author

Shrusti P Chavan  
DevOps / Cloud Enthusiast
