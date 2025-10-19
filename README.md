Task 4 - CI/CD Pipeline
Overview

This task demonstrates automation of the build and deployment process using a CI/CD pipeline in GitHub Actions.

Technologies Used

GitHub Actions

Docker

Kubernetes

Pipeline Workflow

Triggered on every push to the main branch

Maven build to compile and test the Java project

Docker build and push to Docker Hub

Kubernetes deployment using YAML manifests

Benefits

Continuous integration ensures code reliability

Continuous deployment automates rollout to the Kubernetes cluster

Simplifies version control and rollback management
