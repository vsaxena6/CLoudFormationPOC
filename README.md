# 3-tier Web-application
# Description
This project defines a CloudFormation Template that can deploy a 3-tier web app on AWS.
# Architecture
The CloudFormation Template would deploy a stack that would create the following resources:
1. VPC with public and private subnets.
2. Internet Gateway for the VPC.
3. Security Groups.
4. Application Load Balancer listening to HTTP web traffic.
5. EC2 instances for serving web traffic behind the Application Load Balancer.
6. RDS instance as database server.
7. A bastion host.
# Input Parameters
# Web Servers
  1. AMI Id
  2. Instance Type
  3. Key Pair name
