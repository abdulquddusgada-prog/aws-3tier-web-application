# AWS 3-Tier Web Application

## 📌 Project Overview

This project demonstrates the deployment of a simple AWS 3-Tier Web Application using AWS networking and compute services. The goal is to build a secure and scalable architecture following cloud best practices.

---

## 🏗️ Architecture

Client
↓
Internet Gateway
↓
Public Subnet
↓
Nginx Web Server (EC2)
↓
Tomcat Application Server
↓
Database (RDS - Upcoming)

---

## ☁️ AWS Services Used

- Amazon VPC
- Public & Private Subnets
- Internet Gateway
- Route Tables
- Security Groups
- Amazon EC2
- Amazon Linux 2023
- Apache Tomcat 10
- Nginx
- Git & GitHub

---

## 📂 Project Structure

```text
aws-3tier-web-application/
│
├── frontend/
│   └── index.html
│
├── screenshots/
│   └── phase5/
│
└── README.md
```

---

# ✅ Phase 1

- Created Custom VPC
- Created Public and Private Subnets
- Configured Internet Gateway
- Configured Route Tables

---

# ✅ Phase 2

- Created Security Groups
- Configured Inbound and Outbound Rules

---

# ✅ Phase 3

- Launched Amazon Linux EC2 Instance
- Connected using SSH

---

# ✅ Phase 4

- Installed Java 21 (Amazon Corretto)
- Installed Apache Tomcat
- Verified Tomcat on Port 8080

---

# ✅ Phase 5

Successfully completed Web Server setup.

### Completed Tasks

- Installed Git
- Cloned GitHub Repository
- Installed and Configured Nginx
- Deployed Frontend Application
- Verified Application using Public IP
- Captured deployment screenshots
- Updated GitHub Repository

---

## 🌐 Application URL

```
http://35.154.97.40
```

> **Note:** This URL uses the EC2 public IP and may change if the instance is stopped and started without an Elastic IP.

---

## 📸 Screenshots

Screenshots are available inside:

```text
screenshots/phase5/
```

---

## 🚀 Upcoming Phases

- Phase 6 – Application Load Balancer (ALB)
- Phase 7 – Auto Scaling Group
- Phase 8 – Amazon RDS Integration
- Phase 9 – CI/CD using GitHub Actions
- Phase 10 – Monitoring with CloudWatch

---

## 👨‍💻 Author

**Abdul Quddus**

AWS Cloud & DevOps Learner

GitHub:
https://github.com/abdulquddusgada-prog
