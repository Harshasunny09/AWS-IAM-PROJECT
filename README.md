# AWS IAM Security Project

This project demonstrates hands-on AWS security fundamentals using Identity and Access Management (IAM). The goal was to understand how access control, permissions, and security boundaries are implemented in real AWS environments.

## Project Overview
In this project, I used AWS IAM to securely manage user access to AWS resources. The setup focused on creating IAM users and groups, writing JSON-based IAM policies, and restricting access to resources based on environment tags such as development and production.

## What I Built
- Created IAM users and user groups for controlled access
- Designed JSON-based IAM policies following least-privilege principles
- Restricted EC2 access based on resource tags (Env = development)
- Explicitly denied tag modification to prevent privilege escalation
- Configured an AWS account alias for simplified console login
- Tested permissions using real EC2 actions and the IAM Policy Simulator

## AWS Services Used
- AWS Identity and Access Management (IAM)
- Amazon EC2
- IAM Policy Simulator

## Key Learnings
- IAM policies control access using Effect, Action, and Resource
- Resource tags can be used to enforce environment-level security
- Explicit deny rules help prevent unauthorized privilege escalation
- IAM Policy Simulator allows safe testing without impacting real resources
- Managing access through user groups is more scalable than individual users

## Purpose
This project was completed to build strong AWS security fundamentals and understand how real-world organizations manage access to development and production environments while preparing for the AWS Solutions Architect Associate certification.

## Author
Harshavardhan Sagiri
