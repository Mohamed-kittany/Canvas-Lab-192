# AWS VPC and EC2 Lab Setup

## Overview
This project contains an AWS CloudFormation template to create a fully functional Amazon Virtual Private Cloud (VPC) and an Amazon EC2 instance. This lab setup is designed for educational purposes to demonstrate the configuration and management of AWS resources.

![15](https://github.com/Mohamed-kittany/Canvas-Lab-192-CloudFormation/assets/161580792/a686291d-7fbd-4d3f-9393-305197f9537b)

## Template Components
- **Amazon VPC**: A virtual network dedicated to your AWS account.
- **Internet Gateway**: Connects the VPC to the internet.
- **Security Groups**: Configured to allow SSH access from any IP address.
- **Private Subnet**: A subnet that does not assign public IP addresses to instances.
- **Amazon EC2 Instance**: A `t3.micro` instance within the private subnet.

