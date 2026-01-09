# Part 5 – Testing VPC Connectivity

## Project
NextWork Cloud – AWS Networks (High Track)

## Objective
Verify that the network and security configurations in your VPC allow expected
communications between resources and external endpoints. This ensures your VPC
resources (such as EC2 instances) can reach each other and the internet as needed.

## What Was Tested

### Instance-to-Instance Connectivity
- Tested communication between EC2 instances in different subnets (public and
  private)
- Verified successful connections based on routing and subnet placement

### Internet Connectivity
- Tested connectivity from a public subnet instance to the internet
- Verified responses and routing through the Internet Gateway

### Security Rules Validation
- Observed how Security Groups affect reachability
- Confirmed that only allowed ports/protocols are reachable

### Tools Used
- `ping` (where allowed)
- `curl`, `wget`, or browser testing for external connectivity
- SSH session to verify remote access

## Key Concepts
- Connectivity testing between networked resources
- Verifying routing and security settings
- Understanding how firewall controls impact reachability

## Outcome
After completing this part:
- You confirmed that resources within your VPC can communicate with each other
  as intended
- Internet access for public subnet resources was verified
- Security configurations were validated for intended access

## Next Step
Proceed to **Part 6: VPC Peering**.
