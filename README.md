# AWS Highly Available Web Application

## 📌 Overview
This project demonstrates deploying a highly available and scalable web application on AWS using core cloud services.

The architecture ensures reliability, load distribution, and secure network configuration.

---

##  Architecture
User → Application Load Balancer → EC2 Instances → S3

---

## 🛠️ Services Used
- Amazon EC2
- Amazon VPC
- Application Load Balancer (ALB)
- Amazon S3
- IAM (Identity and Access Management)

---

## ⚙️ Implementation Steps

### 1. Network Setup
- Created VPC with public subnets
- Configured routing and internet access
<img width="1896" height="890" alt="vpc" src="https://github.com/user-attachments/assets/b5db40cf-7bc4-4760-bd58-9933d04d1e9e" />

### 2. Compute Setup
- Launched multiple EC2 instances
- Installed and configured Apache Web Server
<img width="1916" height="883" alt="instance1" src="https://github.com/user-attachments/assets/29093bb8-2413-428c-acca-30cb7fd7f7c3" />
<img width="1911" height="869" alt="instance2" src="https://github.com/user-attachments/assets/e77af3f7-8ab6-48e0-ae95-ad0835ad2a94" />

### 3. Load Balancing
- Configured Application Load Balancer
- Distributed traffic across EC2 instances
<img width="1908" height="874" alt="load-balancer" src="https://github.com/user-attachments/assets/aa99ec2e-ba33-4c3a-8c4d-925d928f281f" />
<img width="1916" height="858" alt="target-group" src="https://github.com/user-attachments/assets/a6ada6e6-65aa-4c54-bfb9-910ad007914d" />

### 4. Storage
- Created S3 bucket for static content
<img width="1918" height="866" alt="s3" src="https://github.com/user-attachments/assets/ad5c16a4-fa3f-4964-bf1e-111b240c739f" />

### 5. Security
- Configured Security Groups
- Managed access using IAM roles
<img width="1523" height="688" alt="security group" src="https://github.com/user-attachments/assets/13891ead-194f-4135-a858-46f446085afc" />


## 🌐 Application Output

- Page 1
<img width="1918" height="859" alt="server1" src="https://github.com/user-attachments/assets/73151eab-15c4-421e-81bf-380320eabb64" />


- Page 2
<img width="1919" height="858" alt="server2" src="https://github.com/user-attachments/assets/b15e652c-7a93-4681-a216-885862124b54" />

---

## 🎯 Features
- High availability using multiple EC2 instances
- Load balancing for traffic distribution
- Secure network isolation with VPC
- Scalable architecture
- Static file storage using S3

---

## 🚀 Conclusion
This project demonstrates the deployment of a scalable and highly available web application using AWS cloud services.
