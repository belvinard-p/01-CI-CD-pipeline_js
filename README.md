# Project Purpose

This is a **CI/CD learning project** for the IBM Skills Network course "Introduction to CI/CD" (CD0215EN). It demonstrates building a complete CI/CD pipeline using **Tekton** on Kubernetes.

## Application

A Node.js/Express **Counter API Service** - a simple REST API with:
- Security middleware (helmet, cors)
- Logging (morgan) and error handling
- Unit tests (Jest) and code linting (ESLint)

## CI/CD Labs (Progressive Learning)

1. **Base Pipeline** - Create a basic Tekton pipeline
2. **Git Triggers** - Add event listeners to trigger pipelines on git events
3. **Tekton Catalog** - Use pre-built tasks from Tekton Hub
4. **Unit Test Automation** - Integrate automated testing
5. **Build an Image** - Build and push Docker images
6. **Deploy to Kubernetes** - Deploy the application to a Kubernetes cluster

## Goal

Learn how to build production-ready CI/CD pipelines step-by-step, from basic task execution to full automated deployment with testing, containerization, and Kubernetes deployment using Tekton.
