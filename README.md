# AWS-S3-Cross-Region-Replication
Implementation of Amazon S3 Cross-Region Replication using AWS

## Overview
This project demonstrates Cross-Region Replication (CRR) using Amazon S3 in AWS.

The objective is to create two S3 buckets in different AWS Regions, configure replication between them, and verify automatic replication of uploaded objects.

## Student Details
- Name: Ananthula Sindhusha
- Roll Number: 2410030423
- Course: B.Tech CSE 3rd Year
- University: KL University

## Technologies Used
- Amazon Web Services (AWS)
- Amazon S3
- AWS IAM

## AWS Configuration

### Source Bucket
- Bucket Name: sanjana-source-klh
- Region: Hyderabad (ap-south-2)

### Destination Bucket
- Bucket Name: sanjana-destination-klh
- Region: US East (N. Virginia) (us-east-1)

## Implementation Steps
1. Created the source S3 bucket.
2. Enabled versioning on the source bucket.
3. Created the destination S3 bucket in another Region.
4. Enabled versioning on the destination bucket.
5. Configured Cross-Region Replication.
6. Created an IAM role for replication.
7. Uploaded the test file crr-test.txt.
8. Verified automatic replication in the destination bucket.

## Final Result
The test object uploaded to the source bucket was successfully replicated to the destination bucket in another AWS Region.

## Conclusion
Successfully demonstrated Amazon S3 Cross-Region Replication between two different AWS Regions.

## Author
Ananthula Sindhusha  
KL University
