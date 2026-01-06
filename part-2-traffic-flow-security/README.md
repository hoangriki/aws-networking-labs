# Part 2 – VPC Traffic Flow and Security

## Project
NextWork Cloud – AWS Networks (High Track)

## Objective
Understand how network traffic flows within a VPC and how to secure AWS
resources using Security Groups and Network Access Control Lists (NACLs).

## What Was Explored

### Traffic Flow
- How traffic moves between subnets, route tables, and gateways
- How routing rules determine where packets are sent
- How internet-bound traffic flows through an Internet Gateway

### Security Groups
- Configured Security Groups to control inbound and outbound traffic
- Allowed only required ports and protocols
- Observed stateful behavior (return traffic is automatically allowed)

### Network ACLs
- Configured Network ACL rules at the subnet level
- Explicitly allowed and denied inbound and outbound traffic
- Observed stateless behavior (rules required for both directions)

## Key Concepts
- VPC traffic flow and routing
- Security Groups (stateful firewalls)
- Network ACLs (stateless firewalls)
- Difference between instance-level and subnet-level security
- How routing and security rules work together

## Outcome
After completing this part, traffic flow within the VPC is clearly understood,
and AWS security controls are in place to protect resources while allowing
necessary access.

## Next Step
Proceed to **Part 3: Creating a Private Subnet**.
