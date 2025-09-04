# AWS Lambda

## Basics
- Run code without servers
- Triggered by events (S3, API Gateway, DynamoDB)

## Advanced Features
- Layers for dependencies
- VPC integration
- Environment variables
- Concurrency settings

## CLI Examples
aws lambda create-function --function-name MyLambda --runtime python3.9 --role arn:aws:iam::123456:role/MyRole --handler lambda_function.lambda_handler --zip-file fileb://function.zip

