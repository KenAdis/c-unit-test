# C Unit Test Exercise

This repository contains a simple C project with unit tests, designed to demonstrate Docker-based testing and GitHub Actions for CI.

## 🚀 Features

- Unit tests for C code
- Dockerfile for consistent test environment
- GitHub Actions workflow to automate testing on push


## 🛠 GitHub Actions Workflow

On every `push`, the GitHub Actions workflow:
- Checks out the repository
- Builds the Docker image
- Runs the test suite inside the container


