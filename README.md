# AWS-HA-WebApp
Highly available AWS web application architecture using VPC, ALB, EC2 Auto Scaling, RDS Multi-AZ, S3 and CloudWatch.


# AWS High Availability Web Application

A production-style AWS infrastructure project focused on high availability, fault tolerance, scalability, security, and monitoring.

The environment was built across multiple Availability Zones using an Application Load Balancer, EC2 Auto Scaling, private application subnets, Multi-AZ RDS, S3, and CloudWatch.

## Business Challenge

The goal was to design a web application infrastructure that could:

- Remain available if an EC2 instance fails
- Distribute traffic across multiple application servers
- Automatically scale based on load
- Keep application servers and the database private
- Survive a database Availability Zone failure
- Provide centralized monitoring and alerting
- Separate the web, application, and database layers using network and security boundaries

The architecture was also tested through controlled failure scenarios instead of only verifying that resources were successfully deployed.
