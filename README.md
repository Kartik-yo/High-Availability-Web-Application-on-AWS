# High-Availability Web Application on AWS

## Overview
This project involves the design and implementation of a high-availability multi-tier web application on AWS. The application utilizes a variety of AWS services to ensure scalability, reliability, and fault tolerance.

## Features
- **Multi-Tier Architecture**: Designed with separate layers for frontend, backend, and database.
- **High Availability**: Deployed using multiple Availability Zones with load balancing.
- **Automation**: Infrastructure as Code (IaC) implemented using Terraform for consistent and repeatable deployments.
- **Monitoring**: Integrated observability tools for real-time monitoring and logging.

## AWS Services Used
- **Compute**: EC2 instances with auto-scaling groups.
- **Storage**: S3 buckets for static assets and backups.
- **Database**: RDS (Relational Database Service) for a managed database solution.
- **Networking**: Load Balancer for distributing traffic across multiple servers.
- **Infrastructure Management**: Terraform for provisioning and managing infrastructure.

## Project Structure
- **terraform/**: Contains Terraform configuration files for setting up AWS resources.
- **frontend/**: Source code for the web application's frontend.
- **backend/**: Source code for the web application's backend.
- **scripts/**: Automation scripts for deployment and monitoring.

## How to Deploy
1. Clone the repository:
   ```bash
   git clone https://github.com/Kartik-yo/High-Availability-Web-Application-on-AWS.git
   cd High-Availability-Web-Application-on-AWS

2. Configure AWS credentials.
3. Deploy infrastructure using Terraform:
```
terraform init
terraform apply
```
4. Deploy the application to the provisioned infrastructure.
   
## Monitoring
- CloudWatch: Monitors application and infrastructure performance.
- Prometheus & Grafana: For detailed metrics and dashboards.

## Learnings and Outcomes
- Implemented a scalable and fault-tolerant application on AWS.
- Automated infrastructure management with Terraform.
- Gained hands-on experience with AWS best practices and services.
