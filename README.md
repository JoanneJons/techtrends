# TechTrends
Cloud Native Application Architecture Nanodegree Project 1

## Project Overview

Package and deploy TechTrends to Kubernetes using a CI/CD Pipeline.

TechTrends is an online website used as a news sharing platform, that enables consumers to access the latest news within the cloud-native ecosystem. In addition to accessing the available articles, readers are able to create new media articles and share them.

The web application is written using the Python Flask framework. It uses SQLite, a lightweight disk-based database to store the submitted articles.

## Project Steps Summary
1. Applied the best development practives and developed the status and health check endpoints for the TechTrends application.
2. Packaged the TechTrends application by creating a Dockerfile and Docker image
3. Implemented CI practices by using GitHub Actions to automate the build and push of the Docker image to DockerHub
4. Constructed the Kubernetes declarative manifests to deploy TechTrends to a sandbox namespace within a Kubernetes cluster provisioned using k3s in a vagrant box.
5. Templated the Kubernetes manifests using a Helm chart and provided the input configuration files for staging and production environments.
6. Implemented the Continuous Delivery practices, by deploying the TechTrends application to staging and production environments using ArgoCD and the Helm chart.
