
<div align="center">
  <br />
  <img src="public/banner.webp" alt="CloudBase Banner" />
  <br /><br />

  <img src="https://img.shields.io/badge/ReactJS-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900" />
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" />
  <img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" />
  <img src="https://img.shields.io/badge/ALB-FF9900?style=for-the-badge&logo=awselasticloadbalancing&logoColor=white" />

  <h1>CloudBase</h1>
  <h3>Cloud-Native Database Management Platform</h3>

  <p>
    CloudBase is a cloud-native Database-as-a-Service (DBaaS) platform
    for provisioning, managing, and operating multi-tenant databases
    on AWS with a strong focus on scalability, security, and automation.
  </p>
</div>

---

## 📌 Overview

CloudBase enables users to manage projects, provision databases, control access,
and perform backups through a centralized cloud dashboard built on AWS best practices.

---

## 🧱 System Architecture (AWS)

<img src="public/aws.webp" alt="AWS Architecture Diagram" />

### Key Characteristics

- Multi-AZ VPC architecture
- Public subnets for ALB, NAT Gateway, Bastion Host
- Private subnets for backend services and databases
- Auto Scaling Group for backend services
- S3 for static frontend hosting and database backups

---

## 🛠️ Technology Stack

### Frontend
- ReactJS
- Axios
- Tailwind CSS
- Deployed on Amazon S3 (Static Hosting)

### Backend
- Spring Boot
- RESTful APIs
- JWT Authentication
- EC2 Auto Scaling Group

### Infrastructure
- AWS VPC (Multi-AZ)
- Application Load Balancer
- NAT Gateway
- Bastion Host
- MariaDB / MySQL
- Amazon S3 (Frontend & Backups)

---

## ✨ Core Features

- Authentication & Authorization
- Project & Database Management
- Database Member Invitation & Role Control
- Backup, Restore & Audit Logs
- Table & Data Management
- SQL Import & Export

---

## 👥 Contributors

| Name          | Role       | GitHub                                       |
| ------------- | ---------- | -------------------------------------------- |
| Pham Anh Pha  | Frontend & Cloud Architecture | [@anhphapap](https://github.com/anhphapap)   |
| Nguyen Ho Vu  | Backend & Cloud Architecture | [@hoofdux243](https://github.com/hoofdux243) |

---

## 📄 License

This project is developed for educational and cloud learning purposes.
