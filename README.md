# Proxima AI — Career Intelligence Platform

Proxima AI is an AI-powered resume analyzer and career intelligence platform built to help students and job seekers understand their career readiness. It analyzes resumes, identifies role-based skill gaps, generates placement readiness scores, creates personalized learning paths, saves career reports, and allows users to track learning progress over time.

---

## 🚀 Key Features

- Resume upload and analysis
- Role-based skill gap detection
- Placement readiness score
- Personalized learning path generation
- Career intelligence report
- Saved reports using MongoDB and AWS S3
- Dashboard to view previous saved reports
- Learning progress tracker
- Secure authentication using Clerk
- Delete functionality for analyses and saved reports

---

## 🛠️ Tech Stack

**Frontend:** React, Vite, Tailwind CSS, Framer Motion  
**Backend:** Node.js, Express.js  
**Database:** MongoDB, Mongoose  
**Authentication:** Clerk  
**Cloud Storage:** AWS S3  
**Tools:** Git, GitHub, VS Code  

---

## ☁️ Cloud Integration

Proxima AI uses **AWS S3** to store generated career intelligence reports securely in cloud object storage. MongoDB stores report metadata, while the complete report data is saved in a private S3 bucket.

This demonstrates practical cloud concepts such as:

- Object storage
- IAM-based access
- Backend-to-cloud integration
- Secure report storage
- Application data separation

---

---

## ☁️ AWS Cloud Deployment Roadmap

Proxima AI is being improved as a cloud-hosted full-stack application to demonstrate practical AWS and DevOps skills.

### Planned Cloud Architecture

- Frontend deployment using **Amazon S3 + CloudFront**
- Backend deployment on **Amazon EC2**
- Reverse proxy setup using **Nginx**
- Process management using **PM2**
- Saved career reports stored in **AWS S3**
- Metadata stored in **MongoDB**
- Monitoring and logs using **Amazon CloudWatch**
- Infrastructure provisioning using **Terraform**
- CI/CD automation using **GitHub Actions**

### Infrastructure as Code

The project includes an `infra/` directory for Terraform-based AWS infrastructure provisioning.

Planned Terraform resources include:

- EC2 instance for backend hosting
- Security Group for controlled access
- SSH Key Pair for server access
- IAM permissions for AWS service integration
- Output values such as public IP and instance details

This improves the project from a normal full-stack application into a production-style cloud application with deployment, automation, monitoring, and infrastructure management.

## 👥 Team Project

This project was developed as a final-year B.Tech CSE group project under the GitHub organization **proxima-ai-team**.

### Team Members

- Chayan Bez
- MD Jahid Alam
- Tushar Pal
- Sovandev Panchadhyaee
- Chandra Dalal

### Project Guide

- Saurabh Banerjee

### Institution

NSHM Knowledge Campus Durgapur  
B.Tech CSE, MAKAUT

---

## 🙋 My Contributions

As a contributor to Proxima AI, my major work included:

- Integrated AWS S3 for storing generated career intelligence reports
- Implemented saved career reports using MongoDB metadata and AWS S3 object storage
- Built the dashboard section to view previous career reports
- Developed the saved career report page
- Added the learning progress tracker with skill completion checklist
- Implemented delete functionality for resume analyses and saved reports
- Improved the “Why Proxima AI” comparison section
- Worked on role-based career intelligence flow and UI improvements
