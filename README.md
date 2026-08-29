# AWS Three-Tier Architecture Lab

## Project Status
🚧 In Progress

## Overview
This project documents my hands-on deployment of a three-tier web architecture on AWS using separate presentation, application, and database tiers.

The goal of this lab is to gain practical experience with AWS networking, EC2, subnet segmentation, routing, security groups, Linux administration, and application connectivity.

## VPC Network Architecture

I created a custom AWS VPC using the `10.0.0.0/16` CIDR range with one public subnet and two private subnets. Separate route tables control traffic between the tiers, while an Internet Gateway provides public connectivity and a NAT Gateway allows resources in the private subnets to initiate outbound connections.

![AWS VPC Resource Map](screenshots/02-vpc-resource-map.png)

Presentation Tier → Application Tier → Database Tier

## AWS Services
- Amazon VPC
- Amazon EC2
- Public and Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups

## Build Documentation
Documentation and screenshots will be added as the environment is deployed.

## Lessons Learned
To be completed after the project.
