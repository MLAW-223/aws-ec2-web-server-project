# ☁️ AWS EC2 Web Server Deployment Project

![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Linux](https://img.shields.io/badge/Linux-Amazon_Linux-blue)
![Apache](https://img.shields.io/badge/Web_Server-Apache-red)
![PHP](https://img.shields.io/badge/PHP-8.5-purple)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📖 Overview

This project demonstrates how to deploy a web server on Amazon EC2 using User Data automation.

The server automatically installs:

- Apache HTTP Server
- PHP
- MariaDB

The deployment was performed in AWS Skill Builder and tested using a live PHP application.

---

## 🛠 Technologies Used

| Service | Purpose |
|----------|----------|
| Amazon EC2 | Virtual Server |
| Amazon EBS | Storage |
| Amazon Linux 2023 | Operating System |
| Apache | Web Server |
| PHP | Application Runtime |
| MariaDB | Database |
| AWS Systems Manager | Secure Instance Access |

---

## 🏗 Architecture

```mermaid
flowchart LR

A[User Browser]
--> B[Amazon EC2]

B --> C[Apache]

C --> D[PHP]

D --> E[phpinfo.php]
```

---

## 🎯 Objectives

- Launch Amazon EC2 instance
- Configure networking
- Deploy software using User Data
- Access instance using Session Manager
- Resize EBS storage
- Change instance type
- Validate application functionality
- Terminate resources

---
