# AWS EC2 (Elastic Compute Cloud)

## Basics
- Virtual server in the cloud
- Key concepts:
  - AMI (Amazon Machine Image) – Pre-built OS
  - Instance Types – CPU, RAM configuration
  - Key Pair – SSH access
  - Security Groups – Firewall rules

## Advanced Features
- Elastic IP – Static public IP
- Multi-AZ deployment – High availability
- Auto Scaling Groups – Automatically scale instances
- Elastic Load Balancer – Distribute traffic

## CLI Examples
aws ec2 run-instances --image-id ami-123456 --instance-type t2.micro --key-name MyKey
aws ec2 stop-instances --instance-ids i-123456
aws ec2 describe-instances

## Mini Lab
- Launch EC2 instance, connect via SSH
- Attach EBS volume
- Enable auto scaling
