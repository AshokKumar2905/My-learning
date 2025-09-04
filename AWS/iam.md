# AWS IAM

## Basics
- Manage users, roles, and permissions
- Best practices:
  - Least privilege
  - Enable MFA
  - Roles for services

## Advanced Features
- Service-linked roles
- IAM policies in JSON
- Temporary credentials via STS

## CLI Examples
aws iam create-user --user-name DevUser
aws iam attach-user-policy --user-name DevUser --policy-arn arn:aws:iam::aws:policy/AdministratorAccess
aws iam create-role --role-name MyEC2Role --assume-role-policy-document file://trust-policy.json

