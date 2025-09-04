# AWS EFS

## Basics
- Shared file storage for EC2
- Can be mounted on multiple instances

## Advanced Features
- Performance modes (General Purpose / Max I/O)
- Throughput modes (Bursting / Provisioned)
- Encryption at rest and in transit
- Access points

## CLI Examples
aws efs create-file-system --creation-token MyEFS
aws efs create-mount-target --file-system-id fs-123 --subnet-id subnet-123 --security-groups sg-123
