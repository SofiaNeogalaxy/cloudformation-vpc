# cloudformation-vpc
This repository contains an AWS CloudFormation template for building a Virtual Private Cloud (VPC) in Amazon Web Services (AWS). The template creates the following resources in your AWS account:

- VPC with a CIDR block of 10.0.0.0/16
- Two public subnets within the VPC, with CIDR blocks 10.0.1.0/24 and 10.0.2.0/24
- An Internet Gateway to allow communication with the Internet
- A route table to route traffic between the subnets and the Internet via the Internet Gateway
- Security group to allow secure access to instances in the public subnets via SSH (port 22)
- Association of the route table with the public subnets
This CloudFormation template is a starting point for building your infrastructure in AWS.
