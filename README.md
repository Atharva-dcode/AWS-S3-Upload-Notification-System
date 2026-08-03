## 📚 Learning Project

This project was developed as part of my AWS cloud learning journey to gain hands-on experience with event-driven architectures and serverless services.

I implemented the overall architecture, EC2 setup, Amazon S3 integration, IAM permissions, SNS configuration, PHP upload application, and deployment process. The AWS Lambda function used in this project was based on a sample implementation shared by a friend and was integrated for learning purposes.

This repository is intended for educational and portfolio purposes to demonstrate my understanding of AWS service integration and cloud workflows.
# AWS-S3-Upload-Notification-System
An event-driven AWS project that automatically sends email notifications when files are uploaded to Amazon S3 using EC2 (PHP), AWS Lambda (Python), Amazon SNS, and IAM.


<p align="center">
  <img src="SNS_Notification_img.png" alt="AWS Architecture" width="900">
  <br>
  <em>Upload Notification System Architecture</em> 
</p>

# 🚀 S3 Upload Notification System

An event-driven AWS project that automatically sends email notifications whenever a file is uploaded to an Amazon S3 bucket using Amazon EC2, AWS Lambda, Amazon SNS, and IAM.

---

## 📌 Overview

The **S3 Upload Notification System** is a cloud-based application that automates the process of notifying users after a successful file upload.

A PHP application hosted on an Amazon EC2 instance allows users to upload files to an Amazon S3 bucket using the AWS SDK for PHP. Once a file is uploaded, Amazon S3 triggers an **ObjectCreated** event, which invokes an AWS Lambda function written in Python. The Lambda function retrieves the uploaded file's metadata and publishes a notification to an Amazon SNS topic. Amazon SNS then sends an email notification to all subscribed users.

This project demonstrates event-driven architecture, serverless computing, cloud storage, and automated notifications using AWS services.

---

## 🔄 Workflow

1. User uploads a file through the PHP web application.
2. The application uploads the file to Amazon S3 using the AWS SDK for PHP.
3. Amazon S3 stores the file and generates an **ObjectCreated** event.
4. AWS Lambda is automatically triggered by the S3 event.
5. Lambda extracts the uploaded file's metadata.
6. Lambda publishes the details to an Amazon SNS topic.
7. Amazon SNS sends an email notification to all subscribed users.

---

## ☁️ AWS Services Used

- Amazon EC2
- Amazon S3
- AWS Lambda
- Amazon SNS
- AWS IAM
- AWS SDK for PHP

---

## ✨ Features

- File upload using PHP
- Secure storage with Amazon S3
- Automatic event-driven processing
- AWS Lambda integration
- Email notifications using Amazon SNS
- IAM-based access control
- Scalable serverless workflow

---

## 🛠️ Tech Stack

- PHP
- Python
- HTML
- AWS SDK for PHP
- Amazon EC2
- Amazon S3
- AWS Lambda
- Amazon SNS
- IAM

---

## 📧 Outcome

Whenever a user uploads a file, the system automatically triggers AWS Lambda, processes the uploaded file's metadata, and sends an email notification to all subscribed users through Amazon SNS without any manual intervention.

## Linkedin

https://www.linkedin.com/feed/update/urn:li:activity:7490111405367533569/
