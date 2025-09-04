# AWS VPC

## Basics
- Isolated network in AWS
- Components:
  - Subnets (Public/Private)
  - Route tables
  - Internet gateway
  - NAT gateway

## Advanced Features
- VPC peering
- Flow logs for traffic monitoring
- VPN / Direct Connect for hybrid cloud

## CLI Examples
aws ec2 create-vpc --cidr-block 10.0.0.0/16
aws ec2 create-subnet --vpc-id vpc-123 --cidr-block 10.0.1.0/24
aws ec2 create-internet-gateway

## Mini Lab
- Create VPC with public/private subnets
- Attach IGW/NAT
- Launch EC2 in public subnet
