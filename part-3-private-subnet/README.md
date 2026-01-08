# Part 3 – Creating a Private Subnet

## Project
NextWork Cloud – AWS Networks (High Track)

## Objective
Segment the network within your VPC by creating a **private subnet** — a subnet
that doesn’t have direct internet access — and understand how traffic and security
behave differently compared to a public subnet.

## What Was Built and Explored

### Private Subnet
- Created a subnet inside your VPC that is **not directly reachable from the internet**.
- Ensured the subnet does not have an associated route to an Internet Gateway.

### Routing
- Validated that without internet routing, resources in the private subnet cannot
  access the internet directly.
- Prepared the architecture for future secure communication and NAT setups.

### Security & Use Cases
- Learned use cases for private subnets (e.g., backend services, databases).
- Observed how security groups and NACLs behave in a subnet without internet routing.

## Key Concepts
- Difference between **public** and **private** subnets
- How routing determines access to external networks
- Use cases for isolating resources
- Importance of security layering within VPCs

## Outcome
After completing this part, you have:
- A private subnet configured inside your VPC
- A clear understanding of how traffic behaves in a subnet without direct
  internet access
- A foundation for implementing NAT gateways, secure backend systems, and more

## Next Step
Proceed to **Part 4: Launching VPC Resources**.
