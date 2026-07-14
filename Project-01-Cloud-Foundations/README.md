# Project 01 — Cloud Foundations

## Objective
Set up a properly secured AWS account foundation least-privilege IAM access, CLI authentication, and cost controls then provision, connect to, and maintain a Linux server (EC2) using the same practices a production environment would require. The goal was not just to launch a server, but to understand why each security and operational decision matters, and to be able to debug real AWS errors independently.

## Topics Covered
- IAM (root account hardening, least-privilege user creation, policy attachment)
- AWS CLI installation and authentication
- EC2 (AMIs, instance types, security groups, key pairs)
- Regional architecture in AWS (why AMIs are region-specific)
- SSH (key-based authentication to a remote Linux host)
- Linux server administration (`apt update/upgrade`, kernel management, reboot handling)
- Cost hygiene (identifying and terminating unused resources)
- Systems recon (`hostnamectl`, `df -h`, `free -h`) and interpreting virtualization at the OS level
