# AWS Static Website Demo (Docker + LocalStack)

![AWS](https://img.shields.io/badge/AWS-S3-orange)
![Docker](https://img.shields.io/badge/Docker-LocalStack-blue)
![CI/CD](https://img.shields.io/badge/GitHub-Actions-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

Hands‑on demo of deploying a static website to AWS S3, tested locally with **Docker + LocalStack**, and integrated with GitHub workflows.

---

## 📖 Overview
This project demonstrates how to deploy a static website using AWS S3.  
It includes a simple HTML page (`index.html`) and a stylesheet (`style.css`) with gradient background and modern typography.  
The workflow highlights version control with Git & GitHub, local AWS simulation with Docker + LocalStack, and CI/CD integration.

---

## 🛠 Technologies Used
- **HTML5** for the static site  
- **CSS3** for styling  
- **Git & GitHub** for version control and collaboration  
- **Docker + LocalStack** for local AWS simulation  
- **AWS S3** as the intended deployment target  

---

## 🚀 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Revaun/aws-static-website-demo.git
   cd aws-static-website-demo
2. Run LocalStack with Docker
   docker run -d -p 4566:4566 -p 4571:4571 localstack/localstack
3. Deploy to LocalStack S3
   awslocal s3 mb s3://static-website-demo
   awslocal s3 cp index.html s3://static-website-demo/
   awslocal s3 cp style.css s3://static-website-demo/
4. Verify Deployment
   awslocal s3 ls s3://static-website-demo/

   📂 Project Structure
   aws-static-website-demo/
   │
   ├── index.html
   ├── style.css
   └── README.md

   🔄 Updates

   Added style.css with gradient background and modern typography.

   Linked stylesheet in index.html.

   ✅ Outcome

   This demo proves that:

   A static website can be deployed to AWS S3.

   LocalStack + Docker provides a safe, cost‑free environment for testing AWS deployments.

   GitHub workflows ensure version control and CI/CD integration.


    🔖 Repo Description

   Hands‑on demo of deploying a static website to AWS S3 using Docker + LocalStack, with GitHub workflows for CI/CD.  
   Tags: AWS, S3, Docker, LocalStack, CI/CD, DevOps
