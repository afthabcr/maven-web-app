# End-to-End CI/CD Automation using Jenkins, Docker & Amazon EKS

## Project Overview

Designed and implemented a CI/CD pipeline to automate the build, containerization and deployment of a Java-based Maven web application using Jenkins, Docker and Kubernetes on Amazon Elastic Kubernetes Service (EKS).

The project demonstrates how DevOps tools can be integrated to streamline application delivery, reduce manual deployment steps and manage containerized applications in a cloud environment.

---

## Technology Stack

-Cloud: AWS EC2, Amazon EKS
-CI/CD: Jenkins
-Build Tool: Apache Maven
-Containerization: Docker
-Container Registry: Docker Hub
-Orchestration: Kubernetes
-Version Control: Git & GitHub
-Operating System: Ubuntu Linux
-AWS Tools: AWS CLI, eksctl, kubectl

---

## Architecture

GitHub → Jenkins → Maven Build → Docker Image → Docker Hub → Amazon EKS → Kubernetes Service → Web Application.

---

## Key Implementation Areas

-Configured Jenkins on an AWS EC2 Ubuntu instance.
-Integrated GitHub with Jenkins for source code management.
-Configured Maven for automated Java application builds.
-Created a Dockerfile to containerize the application.
-Built and managed Docker images.
-Configured Amazon EKS for Kubernetes-based application deployment.
-Created Kubernetes Deployment and Service manifests.
-Exposed the application using a Kubernetes LoadBalancer service.

---

## Key Learnings

1.CI/CD pipeline configuration and automation.
2.AWS EC2 and EKS infrastructure management.
3.Docker image creation and container management.
4.Kubernetes deployments, pods and services.
5.IAM roles and AWS permissions.
6.Linux administration and command-line operations.
7.Troubleshooting deployment and connectivity issues.

---

## Project Structure

```text
.
├── Dockerfile
├── Jenkinsfile
├── k8s-deploy.yml
├── pom.xml
├── src/
└── README.md
```

---

## Jenkins Pipeline Stages

- Tool Installation
- Clone Repository
- Maven Build
- Docker Image Build
- Kubernetes Deployment

---


## Skills Demonstrated

- Jenkins CI/CD Pipeline
- Docker Containerization
- Kubernetes Deployment
- Amazon EKS Administration
- Git & GitHub
- Apache Maven
- AWS EC2
- IAM Configuration
- Docker Hub Integration
- Linux Administration
- AWS CLI
- kubectl
- eksctl

---

## Challenges Faced

- Configuring IAM Roles for AWS services
- Connecting Jenkins to Amazon EKS
- Managing Kubernetes configuration
- Building Docker images through Jenkins
- Deploying applications using Kubernetes manifests
- Verifying application accessibility through AWS Load Balancer

---

## Project Outcome

Successfully implemented a fully automated CI/CD pipeline that deploys a Maven web application from GitHub to Amazon EKS using Jenkins, Docker, and Kubernetes.

---

## Author

**Afthab CR**

GitHub: https://github.com/afthabcr
