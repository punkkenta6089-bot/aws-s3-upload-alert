# AWS S3 Upload Notification System

## Overview

This project detects file uploads to Amazon S3 and automatically sends email notifications using AWS Lambda and Amazon SNS.

The system is built using an event-driven architecture where an S3 upload triggers a Lambda function that sends a notification via SNS.

---

## Architecture

S3 (File Upload)
↓
Lambda (Trigger)
↓
SNS (Notification)
↓
Email

---

## AWS Services Used

- Amazon S3
- AWS Lambda
- Amazon SNS
- AWS IAM
- Amazon CloudWatch

---

## Features

- Detects when files are uploaded to an S3 bucket
- Automatically triggers a Lambda function
- Sends email notifications using SNS
- Secure permissions using IAM roles
- Logs execution in CloudWatch

---

## What I Learned

- Event-driven architecture in AWS
- Configuring IAM roles and permissions
- Creating Lambda triggers from S3
- Sending notifications using SNS
- Monitoring logs with CloudWatch

---

## Future Improvements

- Store upload metadata in DynamoDB
- Add CloudWatch alarms
- Integrate Slack notifications

---

## Architecture Diagram

![Architecture](architecture.png)
