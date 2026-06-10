# AWS IAM Basics

## What is IAM?

Identity and Access Management (IAM) allows administrators to control who can access AWS resources and what actions they can perform.

## Core Components

### Users
Represents an individual person.

### Groups
Collection of users with similar permissions.

### Roles
Temporary permissions that can be assumed.

### Policies
JSON documents that define permissions.

## Principle of Least Privilege

Users should receive only the permissions necessary to perform their job.

## Real World Example

A developer may need:

- EC2 access
- CloudWatch access

But may not need:

- Billing access
- IAM administrator access