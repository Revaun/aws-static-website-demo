<img src="Images/aws_static_website_demo.png" alt="AWS Static Website Demo Banner" width="100%" height="400px" style="object-fit:cover; display:block;"/>

# AWS Static Website Demo (Docker + LocalStack)

[![Deploy to S3](https://github.com/Revaun/aws-static-website-demo/actions/workflows/deploy.yml/badge.svg)](http://revaun-static-website-demo.s3-website-af-south-1.amazonaws.com)  
🔗 [Live Preview](http://revaun-static-website-demo.s3-website-af-south-1.amazonaws.com)

Meet my Husky Echo — guarding the pipeline from build to deploy.  
This project demonstrates a complete workflow: local development, CI/CD automation, and cloud deployment.

---

## 📖 Overview
This repository showcases how to deploy a static website using **AWS S3**.  
It includes a simple HTML/CSS site (`index.html`, `style.css`) and demonstrates version control with GitHub, automated deployment with GitHub Actions, and local AWS simulation using Docker + LocalStack.

---

## 📸 Deployment Proof

This section documents the full deployment workflow — from bucket setup to live preview — with snapshots as evidence.

### Step 1 – Bucket Setup
![Bucket Creation](Images/Snapshots/01_bucket_creation.png)

### Step 2 – Static Hosting Enabled
![Static Hosting Enabled](Images/Snapshots/03_static_hosting_enabled.png)

### Step 3 – Public Access Policy
![Bucket Policy Applied](Images/Snapshots/05_bucket_policy_applied.png)

### Step 4 – Website Endpoint
![Website Endpoint](Images/Snapshots/06_website_endpoint.png)

### Step 5 – GitHub Actions Badge
![GitHub Actions Badge Snapshot](Images/Snapshots/07_github_actions_badge.png)

### Step 6 – Final Result
![Static Website Screenshot](Images/static_website.png)  
![Husky Guarding Pipeline](Images/Snapshots/17_site_with_images.png)

---

## 🚀 Tech Stack
- **AWS S3** – static website hosting  
- **GitHub Actions** – CI/CD pipeline  
- **Docker + LocalStack** – local AWS simulation  
- **HTML/CSS** – frontend styling
