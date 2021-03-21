### 10. AWS Fundamentals - section intro

#

### 11. AWS Regions and AZs

- most AWS services are Region-scoped
- [AWS global infrastructure](https://aws.amazon.com/about-aws/global-infrastructure)

#

### 12. IAM Introduction

- users, groups, and roles
- users -> groups
  - groups are given permissions, users are put into groups
- roles are given to machines/services to permissions
- Policies are used to define what each user, group, or role can/cannot do
- IAM has global scope
- policies are in JSON
- give users the least privilege principle
- IAM Federation
  - big enterprises can use their own directory to login
  - uses SAML standard (Active Directory)
- one IAM user per physical person
- one IAM role per application
- never write IAM creds in code
- never use root acct except for initial setup

#

### 13. IAM Hands-On

- nothing new

#

### 14. About the EC2 Console Changes

- nothing new

#

### 15. EC2 Introduction

- nothing new

#

### 16. SSH Overview

- nothing new
- can use SSH, except for win<10. then you need to use putty
- can use EC2 instance connect no matter what

#

### 17. How to SSH using Linux or Mac

- connect to a machine remotely - port 22
- command: ssh -i yourfile.pem ec2-user@machine.ip.address
- chmod 400 to fix permissions

#

### 18. How to SSH using Windows

- nothing new

#

### 19. How to SSH using Windows 10

- nothing new

#

### 20. SSH Troubleshooting

- help file

#

### 21. EC2 Instance Connect

- browser based connection

#

### 22. Introduction to Security Groups

- are stateful: if inbound traffic is allowed, then the outbound is automatically allowed
- can set inbound and outbound rules
- ephemeral ports: watch [pytholic's video](https://www.youtube.com/watch?v=p0XCg5VhKQA) for explanation of security groups and ephemeral ports
- can only allow traffic, can't explicitly deny

#

### 23. Security Groups Deep Dive

- operate on AWS instances/services
- can be attached to multiple instances
- locked down to a region
- all inbound traffic is blocked
- all outbound traffic is allowed

#

### 24. Private vs Public vs Elastic IP

- when you stop then start an instance, it can change it's public IP

#

### 25. Private vs Public vs Elastic IP Hands On

- nothing to add

#

### 26. Install Apache on EC2

- ssh into instance
- run yum updates
- yum install httpd to install apache
- dont forget to allow port 80
- nothing else to add

#

### 27. EC2 User Data

- launch commands when machine starts
- automate boot tasks
- updates
- software
- common files from internet
- script runs at first boot
- in advanced details when creating an EC2 instance

#

### Quiz 1: Iam and EC2 midway quiz

- 12/13 correct

#

### 28. EC2 Instance Launch Types

#

### 29. EC2 Instance Launch Types Hands On

#

### 30. EC2 Elastic Network Interfaces

#

### 31. ENI - Extra Reading

#

### 32. EC2 Good Things to Know Checklist

#

### Quiz 2: EC2 Final Quiz

#
