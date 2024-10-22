
---

# Advanced DevOps Practical

This repository is dedicated to the **Advanced DevOps Practical** where we explore the core tools and techniques required for building scalable and efficient infrastructure using Terraform, Kubernetes, AWS EC2, and more.

## Table of Contents

1. [Project Overview](#project-overview)
2. [All Installation PDFs](#useful-links)
3. [Installation](#installation)
   - [Terraform](#terraform)
   - [Kubernetes](#kubernetes)
4. [Code Quality Analysis (SonarQube)](#code-quality-analysis-sonarqube)
5. [For Viva](#for-viva)
6. [FAQs](#faqs)

---

## Project Overview

The **Advanced DevOps Practical** covers a wide range of DevOps technologies, including infrastructure as code (Terraform), container orchestration (Kubernetes), cloud services (AWS EC2, S3, Lambda), and CI/CD pipelines. This practical emphasizes hands-on exercises to help you implement and manage these technologies effectively.

---

## Installation

Here are the resources you will need to install and configure the tools required for this practical.

### Terraform

Terraform allows you to provision infrastructure in a repeatable and automated way using infrastructure as code (IaC).

- **Installation Guide**: [Terraform Installation Guide](https://www.youtube.com/watch?v=aHve0Ji13IY)

### Kubernetes

Kubernetes is a container orchestration tool that helps in managing containerized applications in a clustered environment.

- **Kubernetes Tutorial**: [Kubernetes Guide](https://youtu.be/05MNwC4XJBs?si=Li8adqlC5pSuUTEP)
- **Docker Alternative**: If VirtualBox doesn't work, you can install Docker and complete the exercise using this guide: [Docker Installation](https://youtu.be/mS26N5cLBe8?si=Y69TqfsQTD_0K3jd)

---


## Code Quality Analysis (SonarQube)

This section covers the installation of **SonarQube** and its integration with **Jenkins** for continuous code quality analysis.

### Installation Guides

#### SonarQube Installation on Windows
SonarQube is a popular tool for static code analysis that helps ensure code quality. Below is the guide to install SonarQube on Windows:

- **Video Tutorial**: [SonarQube Installation in Windows](https://youtu.be/CURSk7cto_0?si=ew624NZcuNGUbwBx)

### Integration Guides

#### SonarQube Integration with Jenkins

For continuous code analysis in Jenkins pipelines, you can integrate SonarQube with Jenkins. Follow these video tutorials for step-by-step guidance:

1. **Complete Integration of SonarQube with Jenkins - Part 1**  
   Set up SonarQube with Jenkins, configure plugins, and run initial tests.  
   - **Video Tutorial**: [SonarQube with Jenkins - Part 1](https://youtu.be/uMVflNm3e9Q?si=_S0z__Q1VyPJHV3r)

2. **Trigger SonarQube Analysis from Jenkins - Part 2**  
   Learn how to trigger SonarQube analysis from a Jenkins job and automate quality checks.  
   - **Video Tutorial**: [SonarQube with Jenkins - Part 2](https://youtu.be/sk36v_gEjxM?si=kp-w1X1MftFkrGmx)

---


## Useful Links

Here are some additional useful links for your reference:

- **All Installation PDFs**:
  - [Installation Guide Link 1](https://shorturl.at/5yZq6)
  - [Installation Guide Link 2](https://github.com/FLASH0707/AD)
  - [Google Drive Folder for Resources](https://drive.google.com/drive/folders/1OqD1e2j_3gW1ECSAXLZ0ctafUPiozh7r)

---

## For Viva

Make sure to familiarize yourself with these key concepts for your viva:

1. **EC2 (Elastic Compute Cloud)**: AWS offering for resizable compute capacity in the cloud.
2. **Difference between IaaS and IaC**:
   - **IaaS**: Provides virtualized computing resources over the internet.
   - **IaC**: Manages infrastructure using machine-readable configuration files.
3. **Key Pair Generation in EC2**: Used for secure SSH access to instances.
4. **Is Key Pair Required to Launch an Instance?**: Yes, for SSH access.
5. **S3 (Simple Storage Service)**: Object storage service in AWS.
6. **S3 Bucket Size**: No limit to bucket size; individual objects can be up to 5TB.
7. **Why Use Terraform?**: For automating infrastructure provisioning.
8. **Terraform Init Command**: Initializes a working directory containing Terraform configuration files.
9. **AWS Lambda**: Serverless computing service for running code in response to events.
10. **Who Uses IaaS?**: Developers, IT admins, startups, and enterprises.
11. **Is the User Required to Launch an Instance?**: Yes, to create a virtual server.
12. **Steps to Launch EC2**:
    - Open AWS EC2 dashboard, select AMI, configure instance details, add storage, and launch with a key pair.
13. **Short Form of Kubernetes**: **K8s**.
14. **Why Create S3 Bucket?**: To store and organize files, host websites, and perform backups.

---

## FAQs

### Q: What is EC2?
**A:** EC2 (Elastic Compute Cloud) is an AWS service that provides scalable computing capacity in the cloud.

### Q: What is the difference between IaaS and IaC?
**A:** 
- **IaaS (Infrastructure as a Service)** provides virtualized resources via the internet.
- **IaC (Infrastructure as Code)** automates the management of infrastructure through code.

### Q: Why is Terraform used in DevOps?
**A:** Terraform automates infrastructure management using configuration files, ensuring consistency and version control across different environments.

### Q: Is key pair required to launch an EC2 instance?
**A:** Yes, for secure SSH access to the instance.

---

