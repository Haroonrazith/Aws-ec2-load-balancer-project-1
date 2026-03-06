Aws-ec2-load-balancer-project
# AWS EC2 Load Balancer Project

This project demonstrates how to deploy multiple EC2 web servers
and distribute traffic using an AWS Application Load Balancer.

## Architecture

User → Load Balancer → EC2 Instances

## Services Used

- Amazon EC2
- Application Load Balancer
- Target Groups
- Apache Web Server
- Linux

## Steps Performed

1. Created two EC2 instances
2. Installed Apache web server
3. Created different index pages for each server
4. Created Target Group
5. Configured Application Load Balancer
6. Attached EC2 instances to Target Group
7. Verified traffic distribution

## Output

Refreshing the load balancer DNS alternates between:

Server 1  

Server 2
