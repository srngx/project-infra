# Modern Web Application Deployment on AWS

![img](https://notes.sarangwandile.xyz/Images/%7B883A14DE-BEE5-4FD3-8A74-300D5DBC3900%7D.png)
## Project Overview

This project demonstrates a comprehensive cloud-native approach to deploying a full-stack web application using modern DevOps practices. The application features an Angular frontend hosted on AWS S3, with a Spring Boot backend running on Amazon EKS (Elastic Kubernetes Service), and data persistence managed through Amazon RDS.

## Repositories Involved

- **Frontend:** https://github.com/srngx/project-frontend
- **Backend:** https://github.com/srngx/project-backend
- **Terraform Infra:** https://github.com/srngx/project-infra

## Architecture

### Infrastructure Components

- **Frontend:** Angular application hosted on AWS S3
- **Backend:** Spring Boot application deployed on Amazon EKS
- **Database:** MySQL on Amazon RDS
- **CI/CD:** Jenkins pipelines for automated deployment

### Technology Stack

- **Frontend:** Angular, HTML, CSS, JavaScript
- **Backend:** Spring Boot (Java)
- **Database:** MySQL
- **Infrastructure:** AWS (S3, EKS, RDS)
- **DevOps Tools:** Jenkins, Docker, Kubernetes, Terraform
- **Version Control:** Git with feature branch workflow

## Key Implementation Highlights

### Infrastructure as Code

The project utilizes Terraform to provision and manage the AWS infrastructure, enabling reproducible deployments and infrastructure version control.

### Containerized Backend

The Spring Boot application is containerized using Docker and deployed to Kubernetes, providing scalability and resilience.

### Automated CI/CD Pipelines

Separate Jenkins pipelines handle the build and deployment processes for both frontend and backend components:

- Backend pipeline: Code pull, Maven build, Docker image creation, and Kubernetes deployment
- Frontend pipeline: Code pull, npm build, and S3 deployment

### Branching Strategy

The project implements a structured branching strategy with feature, development, and main branches to support collaborative development and controlled releases.

## Deployment Process

1. Infrastructure provisioning with Terraform
2. Database initialization and schema setup
3. Backend service deployment to Kubernetes
4. Frontend application build and deployment to S3
5. Configuration of network connectivity between services

## Project Benefits

- **Scalability:** Kubernetes orchestration allows for easy scaling of backend services
- **Cost Efficiency:** Serverless frontend hosting minimizes infrastructure costs
- **Automation:** CI/CD pipelines reduce manual deployment effort and potential errors
- **Maintainability:** Separation of concerns with distinct repositories for frontend and backend
- **Resilience:** Load-balanced backend services ensure high availability

-- The whole Writeup of this project can be found here --> [https:/notes.sarangwandile.xyz/](https://notes.sarangwandile.xyz/Projects/Modern-Web-Application-Deployment-on-AWS)
