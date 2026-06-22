# AWS Static Website Hosting and Monitoring

## Project Overview

This project demonstrates hosting a static website on Amazon S3 using AWS Cloud services. The website is publicly accessible through the S3 Static Website Hosting feature. The project also includes S3 Bucket Versioning and IAM-based access control.

## Services Used

* Amazon S3
* AWS IAM
* AWS CloudWatch
* AWS Console

## Features

* Static Website Hosting using Amazon S3
* Public Website Access using Bucket Policy
* S3 Bucket Versioning
* IAM User Creation and Access Management
* Website Monitoring Concepts
* AWS Security Best Practices

## Project Architecture

```text
User
  |
Internet
  |
AWS S3 Bucket
  |
  +-- Static Website Hosting
  +-- Versioning
  |
IAM User
```

## Project Steps

### 1. Created S3 Bucket

* Created an S3 bucket in AWS.
* Uploaded website files.
* Enabled static website hosting.

### 2. Configured Bucket Policy

* Allowed public read access to website files.
* Configured permissions for static website hosting.

### 3. Enabled Bucket Versioning

* Enabled S3 Versioning.
* Uploaded multiple versions of index.html.
* Verified object versions.

### 4. IAM Configuration

* Created IAM User: devops-user
* Attached S3 access policy
* Implemented least-privilege access using custom IAM policy

## Screenshots

Project screenshots are available in the screenshots folder.

## Repository Structure

```text
aws-static-website-hosting/
│
├── README.md
├── index.html
├── architecture-diagram.png
└── screenshots/
    ├── bucket-created.png
    ├── bucket-objects.png
    ├── website-working.png
    ├── versioning-enabled.png
    └── iam-user.png
```

## Skills Demonstrated

* AWS S3
* IAM
* Static Website Hosting
* Bucket Policies
* Versioning
* Cloud Fundamentals
* Access Management


