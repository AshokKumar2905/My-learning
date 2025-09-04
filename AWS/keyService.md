# AWS Secrets Manager

## Basics
- Securely store credentials, API keys
- Automatic rotation

## CLI Examples
aws secretsmanager create-secret --name MySecret --secret-string '{"username":"admin","password":"Pass1234"}'

 
# AWS KMS

## Basics
- Create and manage encryption keys
- Integrates with S3, EBS, RDS, etc.

## CLI Examples
aws kms create-key --description "My encryption key"
aws kms list-keys

 
