# Automated CI/CD Pipeline on AWS Using Bitbucket and Elastic Beanstalk
## Description

This project automates a CI/CD pipeline using AWS services to deploy application. It integrates Bitbucket, CodePipeline, CodeBuild, Elastic Beanstalk, and RDS to streamline code fetching, building, and deployment.

## Technologies

- Source Control: Bitbucket
- CI/CD Orchestration: AWS CodePipeline
- Build Automation: AWS CodeBuild
- Deployment: AWS Elastic Beanstalk
- Database: AWS RDS

## Workflow

- Code Migration: Source code moved from GitHub to Bitbucket
- Pipeline Setup: CodePipeline monitors Bitbucket for commits and triggers builds
- Build Process: CodeBuild compiles code into an artifact
- Deployment: Elastic Beanstalk deploys the artifact
- Database Configuration: AWS RDS hosts schemas and tables
     
## Key Features

- Fully automated build and deployment
- Scalable hosting with Elastic Beanstalk
- Real-time CI/CD integration with Bitbucket.
  

## Walk-through:

![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/diagramm.png) 
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/ec2.png) 
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/bitbucket.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/RDS.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/ELB.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/Build%20History.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/CodePipeline.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/test.png)
 ![First try](https://github.com/Vlad774/CICD_on_AWS/blob/main/Service_running.png)
