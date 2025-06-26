# Final-Manara-project
Aws cloud solution architect final project
# Scalable Web Application on AWS 🌐☁️

This project demonstrates the design and implementation of a **highly available, secure, and scalable web application architecture** on Amazon Web Services (AWS). It follows cloud computing best practices to ensure optimal performance, security, and cost efficiency.

## 🏗️ Architecture Overview

The system is built with the following components:

### 1. Virtual Private Cloud (VPC)
- **Purpose:** Create a secure and isolated network environment.
- **Benefits:** Enhanced security with network ACLs and better traffic management.

### 2. Internet Gateway (IGW)
- **Purpose:** Connects the VPC to the internet.
- **Benefits:** Enables public access while working with security groups for access control.

### 3. Public Subnets
- **Purpose:** Host publicly accessible services like web servers.
- **Benefits:** Improved availability and fault tolerance via distribution across AZs.

### 4. Auto Scaling Group (ASG) with Apache
- **Purpose:** Automatically adjust server count based on traffic.
- **Benefits:** Cost optimization and consistent performance during peak and low load.

### 5. Application Load Balancer (ALB)
- **Purpose:** Distribute traffic across EC2 instances.
- **Benefits:** Enhanced reliability, reduced bottlenecks.

### 6. Security Groups
- **Purpose:** Control inbound and outbound access.
- **Benefits:** Restricts direct server access and protects against unauthorized usage.

### 7. Automated Scaling Policy
- **Purpose:** Scale based on CPU utilization.
- **Benefits:** Dynamic adjustment of resources for performance and cost control.

### 8. Monitoring & Alerts
- **Tools:** Amazon CloudWatch & SNS.
- **Purpose:** Real-time health monitoring and alerts.
- **IAM Roles:** Grant EC2 access to AWS services securely without hardcoded credentials.

---

## ✅ Goals Achieved

- **High Availability:** Multi-AZ deployments for both compute and database layers.
- **Scalability:** Auto Scaling based on demand.
- **Security:** Public/private subnet segmentation with fine-grained access.
- **Cost Optimization:** Scales down during low demand and leverages managed services like RDS.


---
**Mostafa Adel Hemdan**  
Cloud & DevOps Enthusiast | Electrical Engineer | AWS Learner




