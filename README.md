# End-to-End DevOps CI/CD Pipeline using Jenkins, Docker, Terraform & AWS

## 📌 Project Overview
This project demonstrates a complete end-to-end DevOps CI/CD pipeline for deploying a web application on AWS EC2 using Jenkins, Docker, and Terraform.

The pipeline automates code integration, containerization, infrastructure provisioning, and deployment.

---

## 🛠 Tools & Technologies
- Git & GitHub
- Jenkins
- Docker
- Terraform
- AWS EC2
- Linux
- HTML

---

## 🔄 CI/CD Workflow
1. Code is pushed to GitHub repository
2. Jenkins pipeline is triggered automatically
3. Jenkins pulls the source code
4. Docker image is built using Jenkins
5. Terraform provisions AWS EC2 infrastructure
6. Docker is installed on EC2 using Terraform user-data
7. Docker container runs the application
8. Application is accessible via EC2 public IP

---

## 📁 Project Structure
├── app/
│ └── index.html
├── Dockerfile
├── Jenkinsfile
├── terraform/
│ ├── main.tf
│ ├── provider.tf
│ ├── variables.tf
│ └── outputs.tf
└── README.md

yaml
Copy code

---

## 🎯 Key Learnings
- CI/CD pipeline automation using Jenkins
- Infrastructure as Code using Terraform
- Docker-based deployment on AWS EC2
- Real-world DevOps workflow implementation

---

## 👤 Author
HARISH
