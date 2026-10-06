# GitOps Kubernetes Deployment with Argo CD

## Project Overview

Implemented a GitOps-based deployment workflow to deploy a custom Nginx web application on a Kubernetes cluster using Argo CD.

## What I Did

- Containerized a custom Nginx web application using Docker and pushed versioned images to Docker Hub.
- Created Kubernetes Deployment and NodePort Service manifests and deployed the application on a Kind cluster.
- Configured Argo CD to monitor the GitHub repository and automatically synchronize Kubernetes changes.
- Updated the application from Docker image `v1` to `v2` and verified the updated deployment and running pods.

## Technologies Used

Git, GitHub, Docker, Docker Hub, Kubernetes, Kind, kubectl, Argo CD, Nginx, AWS EC2, Linux, YAML
