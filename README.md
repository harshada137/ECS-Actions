# ECS-Actions

A GitHub Actions project to automate workflows for deploying applications to **AWS Elastic Container Service (ECS)** using GitHub Actions.

This repository includes:
- A Dockerfile for containerizing the action
- Workflow definitions under `.github/workflows`
- JavaScript code implementing custom logic
- Tests for validating the action
- CI/CD pipeline integration

---

## 🧠 Overview

This project implements a custom ECS deployment *GitHub Action* or workflow that:
- Builds and packages your application Docker image
- Pushes the image to Amazon ECR
- Updates ECS Task Definition and deploys the new version of your service

> GitHub Actions allow you to automate delivery pipelines directly from your repo. ECS integrates seamlessly with Actions for continuous deployment. :contentReference[oaicite:1]{index=1}

---

## 🚀 Features

✔️ Automated image build and push  
✔️ Deployment to AWS ECS via workflow  
✔️ Customizable via GitHub Secrets  
✔️ Includes test scripts (`test.js`)  
✔️ Supports Docker-based actions

---
