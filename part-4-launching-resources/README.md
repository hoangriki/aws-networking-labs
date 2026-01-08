# Part 4 – Launching VPC Resources

## Project
NextWork Cloud – AWS Networks (High Track)

## Objective
Deploy actual AWS resources (EC2 instances) inside your previously created
VPC and subnets to understand how compute resources connect to your network and
how they interact with routing and security controls.

## What Was Built and Explored

### EC2 Instances
- Launched one or more **EC2 instances** within your VPC
- Placed instances into appropriate subnets (public and/or private)
- Selected instance types, AMIs, and security group assignments

### Networking Behavior
- Observed how routing tables and subnets determine access
- Verified that public subnet instances could access the internet via the
  Internet Gateway
- Saw how private subnet instances behave without direct internet routing

### Security
- Updated **Security Groups** to allow remote access (e.g., SSH or HTTP)
- Validated connectivity based on security rules

## Key Concepts
- Launching compute resources in a VPC
- Subnet placement and traffic behavior
- Security group application to EC2 instances
- Instance connectivity based on routing and network access

## Outcome
After completing this part:
- EC2 instances are deployed inside your AWS VPC
- Network behavior for these instances is understood
- Security groups are configured to allow intended access while restricting
  unwanted traffic

## Next Step
Proceed to **Part 5: Testing VPC Connectivity**.
