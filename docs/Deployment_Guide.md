# Deployment Guide for AWS S3 Static Hosting with GitHub Actions

## Overview
This guide details the steps used to automate the deployment of a static website to AWS S3 using GitHub Actions.

## Steps:

1. **Setting up GitHub Repository**
   - Create a new repository or use an existing one.
   - Add your static files like HTML, CSS, and JavaScript.

2. **Configuring GitHub Actions**
   - Create a workflow file `.github/workflows/main.yml`.
   - Configure the workflow to install AWS CLI, configure credentials, and sync files to the S3 bucket.

3. **AWS S3 Bucket Setup**
   - Create an S3 bucket through the AWS Management Console.
   - Configure the bucket for static website hosting.
   - Apply the bucket policy for public access as defined in `s3-bucket-policy.json`.

4. **DNS Configuration with AWS Route 53**
   - Create a hosted zone and configure the DNS records to point your domain to the S3 bucket.
   - Document the changes in Route 53 that link to your S3 bucket’s static website endpoint.

5. **Security Configuration**
   - Detail the IAM policies required for GitHub Actions to interact securely with AWS services, documented in `IAM-Policy.json`.

6. **Testing and Validation**
   - Steps to validate the deployment process and ensure the website is accessible via the custom domain.

## Conclusion
This guide serves as a detailed walkthrough for setting up a CI/CD pipeline that deploys a static website to AWS S3, utilizing GitHub Actions for automation.
