# AWS EC2 Monitoring and Alerting using Cloudwatch

**overview**
This project demonstrates setting up monitoringand alerting for an EC2 instance using AWS CloudWatch and SNS.The goal is to simulate real-world productin monitoring and proactive incident management.

**AWS Resources**
1.EC2 Instance
2.CloudWatch Metrix and Alarms
3.Amazin SNS (email Notification)

**steps Implemented**
1.Launches EC2 instance in AWS
2.Enables Cloudwatch monitoring for CPU utilization.
3.Created a CloudWatvh alaram for 50% CPU Usage in a minute.
4.Configured an SNS topic tos end Email alerts.
5.Generated CPU load using an open-source stress script to validtae alerts.

**validation**
Email alert received via SNS
