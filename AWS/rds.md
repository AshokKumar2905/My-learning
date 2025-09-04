# AWS RDS

## Basics
- Managed relational database service
- Supports MySQL, PostgreSQL, Aurora, Oracle, SQL Server

## Advanced Features
- Multi-AZ deployment
- Read replicas
- Automated backups and snapshots
- Encryption at rest and in transit

## CLI Examples
aws rds create-db-instance --db-instance-identifier mydb --db-instance-class db.t3.micro --engine mysql --master-username admin --master-user-password password
aws rds describe-db-instances
 
