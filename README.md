# CI/CD Pipeline Project

## Introduction

This repository contains a automation build using bash,AWS EC2-Linux, Nginx and cron tabs. The tool automates the delployment of the sample one page website to a server running on AWS using Nginx. The pipeline checks for any new commits in the GitHub repository, clones the lastest code and deplyos it to the server.

## Features

-**Automated Deployment**: Automatically deploys the lastes code to the server whenever new commits are detected.

-**Error Handling**: Gracefully handles errors during the deployment process.

-**Scalability**: Can be extended to include additional features and services.

-**Configuration Management**: Reads configuration files and extracts key-value pairs for easy management.

## Prerequisites:

Before we begins, ensure we have met the following requirements:
- You have an [AWS] (https://www.aws.amazon.com/) or Linux machine.
- You have installed [Python 3](https://www.python.org/).
- You have installed [Nginx] (https://nginx.com/).
- You have a GitHub personal access tocken with repo premissions.

## Installation
1. **Clone the repository:**
```bash
git clone https:github.com/yourusername/repo_name
cd simple-html-project
```
2. **Install



echo "# CI-CD-pipeline-project01" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:bhushanbharat05/CI-CD-pipeline-project02.git
git push -u origin main

git remote add origin git@github.com:bhushanbharat05/CI-CD-pipeline-project01.git
git branch -M main
git push -u origin main
