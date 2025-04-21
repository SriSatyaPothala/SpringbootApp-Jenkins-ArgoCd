# END TO END CI/CD IMPLEMENTATION OF A SPRING BOOT APPLICATION
  This project demonstrates the implementation of a complete CI/CD pipeline for a springboot application using Jenkins, Docker, SonarQube, ArgoCD, and Kubernetes, with integration to AWS Services.

## Tech Stack
  - Jenkins
  - Maven
  - SonarQube
  - Docker
  - ArgoCD
  - Kubernetes
  - GitHub
  - AWS

## Prerequisites
  - Install Jenkins on an EC2
  - Install necessary plugins: Docker pipeline, Maven, Sonarqube Scanner, Git
  - Install Docker on EC2
  - DockerHub account with credentials configured in Jenkins
  - Install SonarQube server locally or on VM
  - Configure Sonarqube server credentials in Jenkins
  - ArgoCD installed and configured
  - Kubernetes Cluster(Minikube is sufficient for practice purpose)
  - GitHub access with credentials configured in Jenkins

## How to run
*** 
 1. Clone the Repository
 2. Set up Jenkins and configure credentials
 3. Set up ArgoCD and link it to the manifests/ directory
 4. Push a commit to trigger the pipeline
 5. Monitor Jenkins pipeline and ArgoCD dashboard.
***

### Jenkins Highlights
- Uses Docker Agent
- Environment variables pulled from Jenkins Credentials
- SonarQube Analysis
- Docker Build and Push
- Shell script to update deployment manifest

### Achievements
- Automated the full CI/CD  process from commit to deployment
- Secured and scalable pipeline with best practices in DevOps
- Used GitOps approach for production-like deployment workflow.
