# Part 6 – VPC Peering

## Project
NextWork Cloud – AWS Networks (High Track)

## Objective
Establish connectivity between two separate Virtual Private Clouds (VPCs) using
**VPC Peering**. This allows resources in different VPCs to communicate
privately without traversing the public internet.

## What Was Built and Explored

### VPC Peering Connection
- Created a **VPC Peering connection** between two VPCs
- Configured the peering request in the source VPC
- Accepted the peering request in the target VPC

### Routing Updates
- Updated route tables in each VPC to enable traffic flow
  across the peering connection
- Verified that routes to the peer VPC’s CIDR block were present

### Communication Tests
- Tested connectivity (e.g., ping, SSH) between resources (EC2 instances)
  in the peered VPCs
- Confirmed private traffic flow through the peering connection

## Key Concepts
- **VPC Peering:** Private network connection between two VPCs
- **Routing updates:** Adding routes so each VPC knows how to reach the other
- **Cross-VPC communication:** Traffic without public internet routing

## Outcome
After completing this part:
- A VPC Peering connection is established between two VPCs
- Route tables are configured to enable bi-directional traffic
- Network resources in separate VPCs can communicate securely

## Next Step
Proceed to **Part 7: VPC Monitoring with Flow Logs**.
