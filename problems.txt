Sure! Here are several problem statements to help you practice AWS CloudFormation:

### Problem 1: Basic EC2 Instance Setup
**Objective:** Create a CloudFormation template to launch a basic EC2 instance.

**Requirements:**
- Create an EC2 instance in a specified VPC and subnet.
- Attach a security group to the instance allowing SSH access.
- Use a specified key pair for SSH access.

### Problem 2: Multi-Tier Architecture
**Objective:** Create a CloudFormation stack to deploy a multi-tier web application.

**Requirements:**
- Create a VPC with public and private subnets.
- Deploy an RDS instance in the private subnet.
- Deploy an EC2 instance in the public subnet to act as a web server.
- Configure the security groups to allow the EC2 instance to communicate with the RDS instance.
- Use an Elastic Load Balancer to distribute traffic to the EC2 instances.

### Problem 3: Auto Scaling and Load Balancing
**Objective:** Create a CloudFormation template to set up an auto-scaling group with a load balancer.

**Requirements:**
- Create an Auto Scaling group with a launch configuration.
- Set up an Elastic Load Balancer to distribute traffic to instances in the Auto Scaling group.
- Configure the Auto Scaling policies to scale based on CPU utilization.

### Problem 4: S3 Bucket with Lambda Trigger
**Objective:** Create a CloudFormation stack to set up an S3 bucket and a Lambda function triggered by object uploads.

**Requirements:**
- Create an S3 bucket.
- Deploy a Lambda function that processes objects uploaded to the S3 bucket.
- Set up the necessary permissions for the Lambda function to read from the S3 bucket.
- Configure the S3 bucket to trigger the Lambda function on object creation.

### Problem 5: VPC Peering
**Objective:** Create a CloudFormation template to set up VPC peering between two VPCs.

**Requirements:**
- Create two VPCs with CIDR blocks that do not overlap.
- Set up a VPC peering connection between the two VPCs.
- Configure the route tables to allow communication between the VPCs.

### Problem 6: IAM Roles and Policies
**Objective:** Create a CloudFormation template to set up IAM roles and policies.

**Requirements:**
- Create an IAM role with policies allowing read-only access to S3.
- Attach the IAM role to an EC2 instance.
- Verify that the EC2 instance can list objects in an S3 bucket but cannot modify or delete them.

### Problem 7: Serverless Application
**Objective:** Create a CloudFormation stack to deploy a serverless application using AWS Lambda and API Gateway.

**Requirements:**
- Create a Lambda function to process API requests.
- Set up an API Gateway to trigger the Lambda function.
- Configure the necessary IAM roles and policies for the Lambda function and API Gateway.

### Problem 8: RDS Instance with Backup
**Objective:** Create a CloudFormation template to deploy an RDS instance with automated backups.

**Requirements:**
- Create an RDS instance in a specified VPC and subnet.
- Enable automated backups with a specified retention period.
- Configure the security groups to allow access to the RDS instance only from specific IP addresses.

### Problem 9: CloudWatch Alarms and SNS Notifications
**Objective:** Create a CloudFormation stack to set up CloudWatch alarms and SNS notifications.

**Requirements:**
- Create a CloudWatch alarm that monitors CPU utilization of an EC2 instance.
- Set up an SNS topic to receive notifications from the CloudWatch alarm.
- Subscribe an email address to the SNS topic to receive notifications.

### Problem 10: Elastic Beanstalk Application
**Objective:** Create a CloudFormation template to deploy a web application using Elastic Beanstalk.

**Requirements:**
- Create an Elastic Beanstalk environment.
- Deploy a sample web application to the Elastic Beanstalk environment.
- Configure the environment to use a specified EC2 instance type and key pair.

These problem statements should help you gain hands-on experience with different aspects of AWS CloudFormation.