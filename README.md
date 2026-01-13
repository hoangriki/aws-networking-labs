# AWS Networking Labs

Hands-on AWS networking projects following the **NextWork Cloud – AWS Networks (High track)**.
This repository documents my learning, architecture decisions, and lessons learned while building
and testing real AWS VPC networking components.

## 🎯 Objectives
- Build strong fundamentals in AWS networking
- Design and secure VPC architectures
- Understand traffic flow, routing, and connectivity
- Prepare for AWS Solutions Architect Associate (SAA)
- Build cloud experience relevant to DevOps & Cloud Engineering roles

## 🧠 Topics Covered
- Amazon VPC and CIDR design
- Subnets (public & private)
- Routing, Internet Gateways, NAT
- Security Groups & Network ACLs
- VPC traffic flow & connectivity testing
- VPC Peering
- VPC Flow Logs & monitoring
- Private access to AWS services (S3, VPC Endpoints)

## 📁 Repository Structure
Each folder represents a project from the NextWork AWS Networks track.

aws-networking-labs/
├── part-0-introduction/
├── part-1-build-vpc/
├── part-2-traffic-flow-security/
├── part-3-private-subnet/
├── part-4-launching-resources/
├── part-5-testing-connectivity/
├── part-6-vpc-peering/
├── part-7-vpc-flow-logs/
├── part-8-s3-from-vpc/
└── part-9-vpc-endpoints/


Each part contains:
- A README explaining the objective and outcome
- Architecture notes and decisions
- Diagrams and screenshots where applicable

## 📈 Progress
- [x] Part 0 – Introduction & AWS Setup
- [x] Part 1 – Build a Virtual Private Cloud
- [x] Part 2 – VPC Traffic Flow and Security
- [x] Part 3 – Creating a Private Subnet
- [x] Part 4 – Launching VPC Resources
- [x] Part 5 – Testing VPC Connectivity
- [x] Part 6 – VPC Peering
- [x] Part 7 – VPC Monitoring with Flow Logs
- [x] Part 8 – Access S3 from a VPC
- [x] Part 9 – VPC Endpoints

## 🛠 Tools & Technologies
- AWS (VPC, EC2, IAM, S3, CloudWatch)
- AWS Console
- Git & GitHub

## 📌 Notes
This repository focuses on **learning and architecture**, not production workloads.
Infrastructure as Code (Terraform) may be added later to extend these labs toward
DevOps best practices.

## 🚀 Future Improvements
- Rebuild VPC using Terraform
- Add CI validation for Terraform plans
- Implement multi-account VPC peering
