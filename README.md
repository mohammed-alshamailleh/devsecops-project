# DevSecOps Project

## Overview

This project demonstrates DevSecOps practices by integrating security scanning into a CI/CD pipeline using GitHub Actions and Trivy.

The pipeline automatically builds a Docker image and performs vulnerability scanning to identify security risks before deployment.

---

## Technologies Used

* Docker
* GitHub Actions
* Trivy
* Nginx
* Git
* GitHub

---

## Project Structure

devsecops-project/

├── app/

│   ├── index.html

│   └── Dockerfile

├── .github/

│   └── workflows/

│       └── security-scan.yml

├── screenshots/

├── docs/

└── README.md

---

## Security Pipeline

1. Push code to GitHub.
2. Build Docker image.
3. Run Trivy vulnerability scan.
4. Generate security findings.
5. Report vulnerabilities.

---

## Features

* Automated Security Scanning
* Docker Image Analysis
* Vulnerability Detection
* GitHub Actions Automation
* DevSecOps Workflow Integration

---

## Learning Outcomes

* DevSecOps Fundamentals
* Container Security
* Vulnerability Management
* Trivy Scanner
* Secure CI/CD Pipelines
* GitHub Actions Security Automation

---

## Future Improvements

* Docker Hub Integration
* Kubernetes Security Scanning
* Secrets Detection
* Security Gates
* Policy Enforcement

