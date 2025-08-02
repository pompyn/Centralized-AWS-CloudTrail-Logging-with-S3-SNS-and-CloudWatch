# Centralized-AWS-CloudTrail-Logging-with-S3-SNS-and-CloudWatch
Project Title:
Centralized AWS CloudTrail Logging with S3, SNS, and CloudWatch

Project Summary:
Configured AWS CloudTrail to deliver management event logs to Amazon S3, notify subscribers through Amazon SNS, and stream logs to Amazon CloudWatch. This setup provides centralized logging, automated alerts, and monitoring for critical events in AWS environments.

Key Skills Demonstrated:

AWS CloudTrail setup and trail creation

S3 bucket configuration for secure log storage

Creation and subscription to Amazon SNS topics

IAM role creation and trust policy configuration

Log streaming to CloudWatch Log Groups

Event verification through SNS and log analysis

Components Configured:

Component	Name / ID
Trail Name	management-events
S3 Bucket	aws-cloudtrail-logs-53395961
SNS Topic	aws-cloudtrail-logs-53395961
Log Group	aws-cloudtrail-logs-53395961
IAM Role	LabTrailRole-53395961

Screenshots Included:

CloudTrail trail overview

S3 bucket with CloudTrail logs

Confirmed SNS email alert

CloudWatch log entries

IAM role details

Takeaway:
This project reinforced best practices in cloud security logging, automation of alerting, and managing permissions for log delivery. It showcases the ability to build audit-friendly infrastructure and demonstrates a foundational understanding of AWS monitoring tools.

### CloudTrail Trail Configuration

![Trail Details](https://github.com/pompyn/Centralized-AWS-CloudTrail-Logging-with-S3-SNS-and-CloudWatch/raw/main/assets/detailed-view-management-events-trail.png)

---

### S3 Bucket for Log Storage

![S3 Bucket](./assets/s3-bucket-cloudtrail-logs.png)

---

### SNS Subscription Confirmation

![SNS Subscription](./assets/amazon-sns-subscription.png)

---

### CloudWatch Logs Group

![Log Group](./assets/aws-cloudtrail-logs.png)

---

### CloudWatch Alarm Email Notification

![Alarm Email](./assets/aws-alarm-event_counter.png)

---

### Alarm Status Dashboard

![Alarm Status](./assets/aws-event-alarm-status.png)

---

### Alarm Event Graph

![Event Counter Graph](./assets/aws-alarm-event-counter-graph.png)

---

### Alarm Configuration Details

![Alarm Details](./assets/aws-alarm-event-counter-details.png)
