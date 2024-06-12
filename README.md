# AWS S3 Static Website Hosting with GitHub Actions

## Overview
This repository serves as a demonstration of how to automate the deployment of a static website to AWS S3 using GitHub Actions. It highlights the integration of continuous deployment practices with AWS cloud services to facilitate efficient and scalable web hosting.

This is the [website](https/sechabam.co.za) and the functional repository can be found [here](https://github.com/xsechaba/sechabam-portfolio).

## Features
- **Automated Deployments**: Utilizes GitHub Actions to automate the workflow of deploying static files to AWS S3.
- **AWS S3 Hosting**: Demonstrates how to configure an S3 bucket for static website hosting.
- **Security and Permissions**: Includes examples of IAM policies and S3 bucket policies to secure and manage access appropriately.

## Repository Structure
- `.github/workflows/main.yml`: Contains the CI/CD pipeline configuration for deploying to AWS S3.
- `s3-bucket-policy.json`: Specifies the S3 bucket policy for public access.
- `IAM-Policy.json`: Defines the IAM policy for GitHub Actions.
- `docs/Deployment_Guide.md`: Provides a step-by-step guide to replicating the deployment process.
- `architectural_diagram/`: Includes the architectural diagram files.
- `LICENSE`: Specifies the terms of use for this project.

## Deployment Guide
For detailed instructions on how to set up and execute the deployment workflow, refer to the [Deployment Guide](docs/Deployment_Guide.md) included in this repository.

## Architectural Diagram
To understand the interactions between the different components used in this project, view the architectural diagram in the `architectural_diagram/` directory.

## Getting Started
To replicate this project:
1. Fork or clone this repository.
2. Follow the detailed steps in the `Deployment_Guide.md` to set up the AWS services and GitHub Actions.
3. Make modifications as required to suit your specific project needs.

## Contributions
Contributions to this project are welcome. Please feel free to fork the repository, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- AWS Documentation
- GitHub Actions Community
