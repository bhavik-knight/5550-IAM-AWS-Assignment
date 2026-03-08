# AWS Academy IAM Lab: Secure Infrastructure Deployment

This repository contains the documentation and evidence for the AWS Academy IAM Lab assignment as part of the **MCDA 5550 - AWS Part** course.

## Project Overview
The primary objective of this project was to demonstrate the secure deployment of a cloud application using **AWS Identity and Access Management (IAM)**. The lab focuses on implementing internal service-to-service communication between Amazon EC2 and Amazon S3 without the reliance on insecure, hardcoded credentials.

## Key Learning Objectives
*   **IAM Fundamentals**: Understanding the relationship between IAM Users, Groups, Roles, and Policies.
*   **Principle of Least Privilege (PoLP)**: Configuring the `EMR_EC2_DefaultRole` to grant minimal necessary permissions for EC2 instances.
*   **Secure Infrastructure**: Deploying an EC2 instance in a dedicated VPC/Subnet and managing it via EC2 Instance Connect.
*   **Data Protection**: Configuring private S3 buckets and enforcing "Block Public Access" while allowing authorized role-based access.
*   **Shared Responsibility**: Analyzing the security boundaries between the cloud provider (AWS) and the user.

## Repository Structure
*   `final_iam_lab_report.md`: The complete, consolidated evidence report submitted for the assignment.
*   `architecture_diagram.png`: Visual representation of the VPC, Subnet, EC2, and S3 interaction.
*   `*.png`: Supplementary screenshots of the AWS Management Console and terminal execution evidence.

## Student Information
- **Name**: Bhavik Kantilal Bhagat
- **ANumber**: A00494758
- **Date**: March 2026
