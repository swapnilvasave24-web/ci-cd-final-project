# ci-cd-final-project

## Project Overview

This project demonstrates a Continuous Integration and Continuous Delivery (CI/CD) pipeline for a Python application using GitHub Actions, Tekton Pipelines, and OpenShift.

## Objectives

- Automate code quality checks using flake8.
- Run unit tests using nose.
- Define reusable CI/CD tasks using Tekton.
- Build a container image using Buildah.
- Deploy the application on OpenShift.

## Technologies Used

- Python
- Git and GitHub
- GitHub Actions
- flake8
- nose
- Tekton Pipelines
- Buildah
- Red Hat OpenShift Container Platform

## Project Structure

```text
ci-cd-final-project/
├── .github/
│   └── workflows/
│       └── workflow.yml
├── .tekton/
│   └── tasks.yml
├── README.md
└── application source and test files
```

## CI/CD Workflow

1. Clean the workspace.
2. Clone the source repository.
3. Run code linting with flake8.
4. Execute unit tests with nose.
5. Build the container image using Buildah.
6. Deploy the application to OpenShift.

## Project Status

The workflow and pipeline should be validated through actual GitHub Actions and OpenShift runs. Successful execution should be confirmed using the corresponding workflow logs and pipeline run details.
