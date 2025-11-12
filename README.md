# 8Byte DevOps Engineer Assignment — Part 2: CI/CD Pipeline

This repository contains the CI/CD automation for the 8Byte DevOps Engineer assignment.

### Tech Stack
- **CI/CD:** Jenkins
- **Build Tool:** Maven
- **Containerization:** Docker
- **Registry:** Docker Hub
- **Hosting:** AWS EC2
- **Scans:** OWASP Dependency-Check & Trivy
- **Notifications:** Slack + Email

### Pipeline Overview
- Build and test Java (Spring Boot) app
- Run dependency & image vulnerability scans
- Build and push Docker image
- Deploy to **staging (Jenkins host)** and **production (EC2)**
- Manual approval before production deploy

---

### Documentation
- [APPROACH.md](./APPROACH.md)
- [CHALLENGES.md](./CHALLENGES.md)
