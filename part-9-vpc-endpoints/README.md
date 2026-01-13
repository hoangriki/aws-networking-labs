# Part 9 – VPC Endpoints

## Project
NextWork Cloud – AWS Networks (High Track)

## Objective
Configure **VPC Endpoints** to allow secure, private connectivity between your
VPC and supported AWS services — such as Amazon S3 and DynamoDB — *without*
sending traffic over the public internet.

## What Was Built and Explored

### VPC Endpoint Types
- **Gateway Endpoints** – used for services like Amazon S3 and DynamoDB
- Created gateway endpoints with appropriate route table associations

### Private Connectivity
- Ensured traffic between your VPC and AWS services remained within the
  Amazon network
- Avoided Internet Gateway, NAT Gateway, or public IPs when accessing services

### Testing
- Verified that instances in the VPC can access the AWS service via the endpoint
- Confirmed that traffic does not traverse the public internet

## Key Concepts
- **VPC Endpoints:** Private network pathways to supported AWS services
- **Gateway Endpoints:** Endpoints for services like S3 and DynamoDB
- Routing considerations for endpoint traffic
- Security and reduced exposure of network traffic

## Outcome
After completing this part:
- One or more VPC Endpoints are created and associated with route tables
- Resources in your VPC can securely access supported AWS services
- Traffic stays within the AWS backbone without public internet routing

## Conclusion
This completes the **NextWork Cloud AWS Networks (High Track)** — you have now:
- Built and configured a complete VPC architecture
- Applied security controls and routing
- Enabled monitoring and private connectivity to AWS services

Well done! 🎉
