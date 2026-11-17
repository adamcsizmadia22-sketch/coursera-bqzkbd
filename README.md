# Continuous Integration and Continuous Delivery (CI/CD) Final Project

## Project Name
Coursera CI/CD Final Project

## Description
This project demonstrates the implementation of a Continuous Integration and Continuous Delivery (CI/CD) workflow using GitHub Actions and OpenShift Pipelines.

The project includes automated code quality checks, unit testing, container image building, and application deployment.

## Technologies Used
- Python 3.11
- GitHub Actions
- Flake8
- Nose
- OpenShift
- Tekton Pipelines
- Buildah

## CI/CD Workflow
The GitHub Actions workflow performs the following steps:

1. Checkout repository
2. Set up Python
3. Install dependencies
4. Run Flake8 linting
5. Run unit tests using Nose

## OpenShift Pipeline
The OpenShift Pipeline consists of the following tasks:

1. Cleanup
2. Git Clone
3. Flake8
4. Nose Tests
5. Buildah
6. Deploy using OpenShift Client

## Repository
GitHub: https://github.com/adamcsizmadia22-sketch/coursera-bqzkbd

## Project Status
CI workflow successfully executed using GitHub Actions.
