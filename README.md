# Engeniusam Resume - Cloud Resume Challenge

## Introduction

This project is part of the Cloud Resume Challenge, which aims to host a static website on AWS using services such as Amazon S3, AWS CloudFront, Amazon Route 53, and Amazon Certificate Manager. The challenge involves deploying a simple resume website built using HTML, CSS, and JavaScript, and ensuring it is accessible, secure, and performs well globally.

## Step-by-Step Guide

### MILESTONE 1 -> Deploying with the AWS Console 🚀

#### Review the Challenge Requirements
- **Action**: Thoroughly read through the requirements of the challenge.
- **Outcome**: Gained a clear understanding of the objectives and deliverables.

#### Explore AWS Documentation
- **Action**: Explored AWS documentation for Amazon S3, AWS CloudFront, Route 53, IAM, and Amazon Certificate Manager.
- **Outcome**: Acquired knowledge of the services, including best practices and configurations.

#### Build Your Architecture Diagram
- **Action**: Designed an architecture diagram using Lucidchart.
- **Components Included**: S3 bucket for static website hosting, CloudFront distribution for CDN, Route 53 for DNS management, and IAM roles/policies for access management.
- **Outcome**: Created a comprehensive architecture diagram representing the infrastructure.

![Architecture Diagram](https://github.com/user-attachments/assets/ccd5a229-2865-4b37-8bb2-404f44c41e0b)

#### Deploy Static Website
- **Action**: Deployed the HTML resume as an Amazon S3 static website.
- **Outcome**: Successfully hosted the resume online with S3.

#### Secure with HTTPS
- **Action**: Configured Amazon CloudFront to serve the S3 website over HTTPS.
- **Outcome**: Ensured the website is accessible securely via HTTPS.

#### DNS Configuration
- **Action**: Used Amazon Route 53 to point a custom DNS domain name to the CloudFront distribution.
- **Outcome**: The resume can now be accessed at `https://samuel-macharia-resume.tech/`.

##### Dark Mode Version

![dark mode](https://github.com/user-attachments/assets/3cd52933-8a91-41b6-8ca9-3c4a4241f535)

##### Light Mode Version
![light mode resume](https://github.com/user-attachments/assets/4202b054-c054-452c-b758-fbd71e0411de)

### Challenges Faced

- Encountered issues with SSL/TLS certificate validation when configuring Amazon CloudFront. Resolved by carefully following Amazon Certificate Manager documentation to correctly associate the certificate with the CloudFront distribution.
- Experienced challenges creating a new cloudfront resource in my AWS account. Resolved it by creating an EC2 instance and afterwards the AWS Support team which I had also sent a ticket to verify my account, verified it successfully

### Key Takeaways

- Learned the importance of securing websites with HTTPS and the role of CDN in reducing latency.
- Gained hands-on experience with AWS services, including S3, CloudFront, Route 53, and IAM.

### Resources

- AWS Documentation
- Lucidchart for architecture diagrams
- AWS tutorials on YouTube

## Outcome

Successfully deployed and secured a static resume website on AWS, making it accessible globally with minimal latency. This project not only showcased my technical skills but also provided valuable experience in using AWS services for web hosting.
