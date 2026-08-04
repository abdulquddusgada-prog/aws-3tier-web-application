AWS 3-Tier Web Application

📌 Project Overview

This project demonstrates the deployment of a secure AWS 3-Tier WebApplication on AWS using Amazon VPC, EC2, Nginx, and Apache Tomcat. Itshowcases networking, Linux administration, deployment, troubleshooting,and GitHub version control.

🏗️ Architecture



Flow

Internet → Internet Gateway → Amazon VPC → Public Subnet → Amazon EC2(Amazon Linux) → Nginx → Apache Tomcat → Future: Amazon RDS (PrivateSubnet)

☁️ AWS Services Used

Amazon VPC

Public & Private Subnets

Internet Gateway

Route Tables

Security Groups

Amazon EC2

Amazon Linux

Nginx

Apache Tomcat 10

Git & GitHub

📂 Project Structure

aws-3tier-web-application/
├── architecture/
│   └── architecture-diagram.png
├── frontend/
│   └── index.html
├── screenshots/
│   ├── 01-vpc.png
│   ├── 02-subnets.png
│   ├── 03-route-tables.png
│   ├── 04-security-groups.png
│   ├── 05-ec2-instance.png
│   ├── 06-nginx-running.png
│   ├── 07-website.png
│   └── 08-ssh-terminal.png
└── README.md

🚀 Deployment Steps

Phase 1 -- Networking

Created a custom VPC

Created Public & Private Subnets

Configured Internet Gateway

Configured Route Tables

Phase 2 -- Security

Created Security Groups

Configured inbound/outbound rules

Phase 3 -- EC2

Launched Amazon Linux EC2

Connected through SSH

Phase 4 -- Application Setup

Installed Java 21

Installed Apache Tomcat 10

Verified Tomcat on port 8080

Phase 5 -- Web Server

Installed Git

Cloned GitHub repository

Installed and configured Nginx

Deployed frontend

Verified application using EC2 public IP

📸 Screenshots

Store screenshots inside the screenshots/ folder.

🛠️ Challenges Faced

SSH Authentication Issue

Problem: Incorrect PEM path caused SSH login failure.

Solution: Located the correct key and connected using the proper SSHcommand.

Nginx Port Conflict

Problem: Nginx failed with Address already in use.

Reason: Apache (httpd) was already using port 80.

Solution: Stopped and disabled Apache, then started Nginxsuccessfully.

Security Group Verification

Problem: Website was inaccessible.

Solution: Verified inbound rules for SSH (22) and HTTP (80).

Nginx Troubleshooting

Used:

sudo systemctl status nginx
sudo journalctl -xeu nginx.service

Resolved the port conflict and verified the service.

🎯 Skills Demonstrated

AWS VPC

EC2

Security Groups

Route Tables

Internet Gateway

Linux

Nginx

Apache Tomcat

SSH

Git

GitHub

Troubleshooting

🔮 Future Improvements

Application Load Balancer

Auto Scaling Group

Amazon RDS

Docker

Terraform

CI/CD Pipeline

CloudWatch Monitoring

👨‍💻 Author

Abdul Quddus

AWS Cloud & DevOps Learner

GitHub: https://github.com/abdulquddusgada-prog
