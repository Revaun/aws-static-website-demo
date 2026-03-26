![AWS Static Website Demo Banner](Images/aws_static_website_demo.png)

# AWS Static Website Demo (Docker + LocalStack)

[![Deploy to S3](https://github.com/Revaun/aws-static-website-demo/actions/workflows/deploy.yml/badge.svg)](https://github.com/Revaun/aws-static-website-demo/actions/workflows/deploy.yml)

👉 [View the GitHub Repository](https://github.com/Revaun/aws-static-website-demo)

---

## 📸 Live Site Snapshot
Here’s Echo the Husky guarding the pipeline, served directly from S3:

![Live Site Screenshot](Images/Snapshots/live_site_preview.png)

---

## 🚀 Project Importance
- Hands‑on AWS security and DevOps demonstration.
- CI/CD pipeline integration with GitHub Actions.
- Recruiter‑ready documentation with snapshots and badges.
- Clear proof of troubleshooting and deployment skills.

---

🔗 [Live Preview](http://revaun-static-website-demo.s3-website.af-south-1.amazonaws.com)

Meet my Husky Echo — guarding the pipeline from build to deploy.  
This project demonstrates a complete workflow: local development, CI/CD automation, and cloud deployment.

---

## 📸 Deployment Proof

### Step 1 – Bucket Setup
![Bucket Creation](Images/Snapshots/01_bucket_creation.png)

### Step 2 – Files Uploaded
![Files Uploaded](Images/Snapshots/02_files_uploaded.png)

### Step 3 – Static Hosting Enabled
![Static Hosting Enabled](Images/Snapshots/03_static_hosting_enabled.png)

### Step 4 – Public Access Disabled
![Block Public Access Disabled](Images/Snapshots/04_block_public_access_disabled.png)

### Step 5 – Public Access Policy
![Bucket Policy Applied](Images/Snapshots/05_bucket_policy_applied.png)

### Step 6 – GitHub Actions Badge
![CI/CD Badge](Images/Snapshots/GitHub_Actions_badge.png)

### Step 7 – Final Result
Echo the Husky guarding the pipeline 🐕  
![Echo the Husky](Images/Snapshots/Echo_the_Husky_meets_AWS.png)

Proof of successful deployment in **af-south-1** region — Echo the Husky guarding the pipeline:

![Live Site Screenshot](Images/Snapshots/live_site_preview.png)

---

## 🚀 Project Importance (Detailed)
This demo highlights a complete AWS DevOps workflow:
- **Hands‑on security**: IAM policies and bucket access controls applied correctly.
- **CI/CD automation**: GitHub Actions pipeline deploying seamlessly to S3.
- **Local testing**: Docker + LocalStack integration for cost‑free validation.
- **Recruiter‑ready proof**: Snapshots and badges showing every step, plus a live site link recruiters can verify instantly.

Echo the Husky isn’t just a mascot — he represents reliability, guarding the pipeline from build to deploy in **af‑south‑1**.

---

## 🛠 How to Run Locally

Follow these steps to reproduce the demo on your own machine:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Revaun/aws-static-website-demo.git
   cd aws-static-website-demo


2. Start LocalStack with Docker
   Make sure Docker is running, then launch LocalStack:
   docker-compose up

3. Deploy locally
   Sync your static site files into the LocalStack S3 bucket:
   aws --endpoint-url=http://localhost:4566 s3 sync ./site s3://demo-bucket

4. Verify deployment
   Check the LocalStack dashboard or AWS CLI output.
   Open the site in your browser via the LocalStack endpoint.

5. CI/CD pipeline (optional)
   Push changes to GitHub and let GitHub Actions run the deploy.yml workflow to deploy automatically to your real S3 bucket in af-south-1.
   (Add How to Run Locally section to README)
