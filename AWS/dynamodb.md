# AWS DynamoDB

## Basics
- Managed NoSQL key-value database
- Highly scalable, low-latency

## Advanced Features
- Global tables (multi-region replication)
- Streams for event-driven architecture
- On-demand and provisioned capacity

## CLI Examples
aws dynamodb create-table --table-name Users --attribute-definitions AttributeName=UserID,AttributeType=S --key-schema AttributeName=UserID,KeyType=HASH --billing-mode PAY_PER_REQUEST
aws dynamodb list-tables
 
 
