# Cloud-Native CI/CD & GitOps Deployment

**Graduate DevOps Project | GitLab CI/CD • Docker • AWS ECR/EKS • Kubernetes • Kustomize • Argo CD**

This repository documents a cloud-native CI/CD and GitOps deployment project completed in a temporary WGU lab environment.

The project involved building, testing, containerizing, and deploying a multi-component web application through an automated GitLab CI/CD pipeline. Container images were stored in Amazon Elastic Container Registry (ECR), application workloads were deployed to Amazon Elastic Kubernetes Service (EKS), and Argo CD synchronized Kubernetes configuration using a GitOps workflow.

> **Project Status:** Completed graduate project  
> **Environment Status:** The original WGU lab and AWS infrastructure were temporary and are no longer active.  
> **Source Availability:** This repository is a portfolio case study containing project documentation, selected configuration examples, architecture information, and sanitized deployment evidence rather than the complete original lab repository.

---

## Project Overview

The project used a food-truck web application consisting of an Angular frontend and a Node.js backend.

The delivery workflow automated the major stages of software delivery:

1. Compile the frontend and prepare the backend
2. Run automated tests and linting
3. Build Docker container images
4. Push images to container registries
5. Update Kubernetes image references with Kustomize
6. Synchronize the desired deployment state through Argo CD
7. Deploy the application to Amazon EKS

The completed pipeline demonstrated an end-to-end workflow from source-code changes through automated testing, containerization, registry storage, GitOps configuration updates, and Kubernetes deployment.

---

## Technologies

- GitLab
- GitLab CI/CD
- Docker
- Amazon ECR
- Amazon EKS
- Kubernetes
- Kustomize
- Argo CD
- Angular
- Node.js
- Jest
- ESLint
- AWS Application Load Balancer
- Horizontal Pod Autoscaling
