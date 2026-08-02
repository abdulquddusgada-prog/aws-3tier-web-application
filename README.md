# ☁️ AWS 3-Tier Web Application

A production-style **AWS 3-Tier Web Application** designed and deployed using AWS cloud services and DevOps best practices.

---

## 📌 Project Overview

This project demonstrates how to build a secure and scalable 3-tier architecture on AWS.

The application is deployed on Amazon EC2 using Nginx and is designed with custom networking components including public/private subnets, route tables, Internet Gateway, NAT Gateway, and Security Groups.

---

# 🏗️ Architecture

```
                 Internet
                     │
             Internet Gateway
                     │
             Public Route Table
                     │
         ┌────────────────────┐
         │                    │
         │   Public Subnet    │
         │                    │
         │    EC2 + Nginx     │
         └────────────────────┘
                     │
              NAT Gateway
                     │
         ┌────────────────────┐
         │                    │
         │   Private Subnet   │
         │                    │
         │ Backend / Database │
         └────────────────────┘
```

---

# 🚀 AWS Services Used

| Service | Purpose |
|----------|---------|
| Amazon VPC | Custom Network |
| Public Subnet | Web Tier |
| Private Subnet | Application Tier |
| Internet Gateway | Internet Access |
| NAT Gateway | Outbound Internet |
| Route Tables | Traffic Routing |
| Security Groups | Firewall |
| Amazon EC2 | Web Server |
| Nginx | Web Server |
| Amazon Linux 2023 | Operating System |

---

# 💻 Technologies

- AWS
- Linux
- Nginx
- Git
- GitHub

---

# 📂 Project Structure

```
aws-3tier-web-application
│
├── architecture/
├── frontend/
│   └── index.html
│
├── screenshots/
│
├── README.md
└── .gitignore
```

---

# 📸 Screenshots

## AWS Infrastructure

- VPC
- Public & Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups

## EC2 Deployment

- EC2 Instance
- SSH Login
- Nginx Running
- Custom Homepage

---

# ✅ Completed

- Custom VPC
- Public Subnet
- Private Subnet
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Amazon EC2
- Amazon Linux 2023
- Nginx Installation
- Static Website Deployment
- GitHub Repository

---

# 🚧 Upcoming Features

- Spring Boot Backend
- Amazon RDS MySQL
- Application Load Balancer
- Auto Scaling Group
- CloudWatch Monitoring
- GitHub Actions CI/CD
- IAM Roles
- Route 53
- SSL Certificate

---

# 🎯 Skills Demonstrated

- AWS Networking
- Linux Administration
- EC2 Management
- Nginx Configuration
- Git & GitHub
- Cloud Security
- Infrastructure Deployment

---

# 👨‍💻 Author

**Abdul Quddus**

AWS Cloud & DevOps Engineer (Fresher)

GitHub:
https://github.com/abdulquddusgada-prog

---

## ⭐ If you like this project, don't forget to star the repository.
