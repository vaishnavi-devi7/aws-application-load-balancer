# aws-application-load-balancer
Demonstrates how an AWS Application Load Balancer distributes traffic across multiple EC2 instances (Server-1 and Server-2). Includes live HTML pages to show which server handled the request.

# AWS Application Load Balancer Demo

## Overview
This project demonstrates how an AWS Application Load Balancer (ALB) distributes incoming traffic across multiple EC2 instances. Two EC2 servers are configured with Nginx serving different HTML pages.

## Services Used
- AWS Application Load Balancer
- AWS EC2
- Security Groups
- Nginx Web Server

## Deployment Steps
1. Launch two EC2 instances (Server-1 & Server-2)
2. Install Nginx and upload HTML pages for each server
3. Configure security groups to allow HTTP (port 80)
4. Create an Application Load Balancer and attach both servers
5. Access ALB DNS name in browser to test traffic distribution

## Outcome
Requests to the ALB are routed to Server-1 or Server-2 automatically, demonstrating load balancing across multiple instances.

## Technologies
AWS EC2, AWS ALB, Nginx, Security Groups

## Repository Link
🔗 https://github.com/yourusername/aws-application-load-balancer
