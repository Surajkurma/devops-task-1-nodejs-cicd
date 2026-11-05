# Node.js Demo App - CI/CD Pipeline

## Project Overview
A simple Node.js application with an automated CI/CD pipeline
using GitHub Actions and Docker.

## Technologies Used
- Node.js
- Git and GitHub
- GitHub Actions
- Docker
- Docker Hub

## CI/CD Workflow
1. Developer pushes code to GitHub.
2. GitHub Actions checks out the source code.
3. Node.js environment is configured.
4. Dependencies are installed.
5. Automated tests are executed.
6. Docker Hub authentication is performed.
7. Docker image is built and pushed to Docker Hub.

## Docker Hub Image
surajkurma/nodejs-demo-app:latest

## Run Locally

```bash
npm install
npm test
npm start