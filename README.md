https://roadmap.sh/projects/ec2-instance

# EC2-Instance
deploy a simple static website using AWS EC2 Instance with SSH key

The goal is to create an AWS account, set up a Linux server on AWS EC2, and deploy a simple static website

## STEP-1  (via GUI method)
Go to console :aws.amazon.com

## STEP-2
Create AWS account,
EC2 --> Instances -->Launch Instance

## STEP-3
Launching Instance with the below requirements:
Image: Ubuntu server AMI
Instance type:t2.micro.
VPC: default  Subnet: default
Security groups: Port(22) , Port(80)
Creating a SSH key pair## STEP-4
Assigning a Public IP.
