# Class 13 – Creating Virtual Linux Server on AWS

This repository contains the recap and code from **Class 13** of the **IT & Japanese Language Course**, supported by **Plus W**, **Pak-Japan Centre**, **AOTS**, and **OEC**.

---

## ☁️ What We Learned Today

A hands-on journey into cloud computing using **Amazon Web Services (AWS)** and **Linux**. Here’s what we explored:

### 🌐 AWS & EC2 Basics
- Introduction to **AWS Services** (EC2, S3, RDS, Lambda, IAM)
- AWS Infrastructure: **Regions, Availability Zones & Edge Locations**
- Benefits of using **EC2** for scalable Linux hosting

### 🐧 Linux Distributions on AWS
- Comparing popular distros: **Ubuntu**, **Amazon Linux**, **CentOS**, **Rocky Linux**
- Use-case based selection of Linux images for EC2
- Package managers: `APT`, `YUM`, `DNF`

### 💸 Understanding AWS Pricing
- **Free Tier**: 750 hrs/month t2.micro or t3.micro instance
- Cost control tips: Use **AWS Budgets**, shut down unused instances

---

## 🚀 Hands-On Guide: Launching an EC2 Instance

### 🔧 EC2 Instance Setup Steps:
1. Sign up for AWS and enable Free Tier
2. Choose an **AMI** (Ubuntu, Amazon Linux, etc.)
3. Select instance type (`t3.micro`)
4. Configure storage, tags, and **Security Group** (allow SSH & HTTP)
5. Generate/download a **Key Pair** for secure access

### 🔐 Connecting via SSH
```bash
chmod 400 your-key.pem
ssh -i "your-key.pem" ubuntu@<Your-EC2-Public-IP>
```

> Tip: Use Git Bash on Windows or Terminal on macOS/Linux.

---

## 🛠️ Git & EC2

We also learned how to:
- Install **Git** on Linux
- Connect your EC2 instance via Git Bash
- Clone and manage Git repositories securely from your EC2 server

---

## 💬 Key Takeaways

> “Launching a server used to take hours — now, with AWS, it takes minutes.”  
> “Linux and cloud skills are a must for every modern developer.”

---