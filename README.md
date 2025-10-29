🍔 Zomato DevOps Project

This project replicates a production-grade deployment pipeline for a Zomato-style food delivery application — containerized, automated, and deployed using modern DevOps tooling.

🚀 Project Overview

The goal of this project is to design and deploy a microservice-based Zomato clone using AWS infrastructure and DevOps best practices.
It demonstrates how CI/CD, Infrastructure as Code, and Docker/Kubernetes come together to deliver scalable cloud applications.

🧱 Architecture

Frontend: React.js or Node.js web app for user interaction

Backend: Express.js API managing restaurant, menu, and order data

Database: MySQL or MongoDB (hosted via AWS RDS or Docker volume)

Containerization: Docker images for each service

Orchestration: Kubernetes (K8s) cluster for high availability

CI/CD: Jenkins pipeline integrated with GitHub Webhooks

Security & Scanning: Trivy and Docker Scout for image vulnerability scanning

Monitoring: Prometheus & Grafana stack

Cloud: AWS (EC2, ECR, RDS, S3, IAM, and Route 53)

⚙️ DevOps Workflow

Developer commits code to GitHub

Jenkins pipeline triggers build → Docker image created → Pushed to AWS ECR

Kubernetes deployment applies manifests via kubectl or Helm

Trivy & Docker Scout scan for vulnerabilities before production deployment

Monitoring stack observes performance and alerts

🧰 Tools & Technologies

AWS | Docker | Kubernetes | Terraform | Jenkins | Trivy | GitHub Actions | MySQL | Node.js | React.js

📊 Key Highlights

Built CI/CD pipelines for containerized application deployment

Automated vulnerability scanning using Trivy and Docker Scout

Deployed highly available Kubernetes cluster on AWS

Configured Jenkins with SonarQube for code quality checks

Demonstrated end-to-end DevOps flow from code commit → deploy → monitor
