# Assignment 3: RDS MySQL Instance Setup

This repository contains the CloudFormation template for deploying an RDS MySQL instance on AWS. Below are the screenshots documenting each step of the deployment process.

---

## 1. AWS CLI Deployment

![AWS CLI Deployment](./screenshots/cli.png)

_Description:_  
Shows the use of AWS CLI to deploy CloudFormation stacks for networking, EC2, and RDS resources.

---

## 2. CloudFormation Stacks Overview

![CloudFormation Stacks Overview](./screenshots/stacks.png)

_Description:_  
Displays the CloudFormation console with all deployed stacks for networking, EC2, and RDS.

---

## 3. Networking Stack Outputs

![Networking Stack Outputs](./screenshots/networking-outputs.png)

_Description:_  
Shows the output values (VPC ID, Subnet IDs) from the networking stack, used for EC2 and RDS configuration.

---

## 4. VPC, Subnet, and Internet Gateway

![VPC, Subnet, and Internet Gateway](./screenshots/networking-vpc-subnet-igw.png)

_Description:_  
Displays the created VPC, public subnets, and attached Internet Gateway.

---

## 5. EC2 Instance Details

![EC2 Instance Details](./screenshots/ec2.png)

_Description:_  
Shows the deployed EC2 instance, including instance ID, public IP, and security group.

---

## 6. RDS Instance Details

![RDS Instance Details](./screenshots/rds.png)

_Description:_  
Displays the RDS MySQL instance, endpoint, and configuration.

---

**Note:**  
All screenshots are located in the `./screenshots/` directory.
