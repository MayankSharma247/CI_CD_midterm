# CI_CD_midterm

This project demonstrates a CI/CD pipeline using GitHub Actions to automate testing, building, and deploying a Dockerized application.

## Features

- Automated CI/CD pipeline with GitHub Actions
- Unit testing using Jest
- Docker image build and push to Docker Hub
- Node.js application setup

## Tech Stack

- **Node.js** (v14)
- **Jest** (for testing)
- **Docker** (for containerization)
- **GitHub Actions** (for CI/CD automation)

##  Getting Started

### 1️⃣ Prerequisites

Ensure you have the following installed:

- Node.js (v14 or higher)
- Docker
- Git
- NPM (Node Package Manager)

# Steps

## Install dependencies:
npm install

## Run unit tests using Jest:
npm test

## Building & Running with Docker
docker build -t ci-cd-demo-app .

## To run the container:
docker run -p 3000:3000 ci-cd-demo-app



