# AWS CloudWatch

## Basics
- Monitor metrics, logs, and events
- Alarm setup for notifications

## Advanced Features
- Custom metrics
- Dashboards
- Logs Insights queries

## CLI Examples
aws cloudwatch put-metric-alarm --alarm-name HighCPU --metric-name CPUUtilization --namespace AWS/EC2 --statistic Average --period 300 --threshold 80 --comparison-operator GreaterThanThreshold --evaluation-periods 2 --alarm-actions arn:aws:sns:us-east-1:123456:MyTopic

 # AWS CloudTrail

## Basics
- Records AWS API calls for auditing
- Logs stored in S3

## Advanced Features
- Multi-region trails
- Integration with CloudWatch

## CLI Examples
aws cloudtrail create-trail --name MyTrail --s3-bucket-name my-trail-bucket
aws cloudtrail start-logging --name MyTrail
 
