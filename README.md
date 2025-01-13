# AWSPracticeLabs
**Beginner Level Labs
Lab 1: Launch Your First EC2 Instance**
Objective: Understand the basics of EC2.
Steps:
Launch an EC2 instance using the AWS Management Console.
Connect to the instance via SSH.
Install a web server (Apache or Nginx) and host a simple "Hello World" HTML page.
Configure security groups to allow HTTP and SSH traffic.
Skills Practiced: EC2, Security Groups, SSH.
**Lab 2: Secure S3 Bucket with IAM Policies**
Objective: Learn how to manage access to an S3 bucket.
Steps:
Create an S3 bucket and enable versioning.
Write an IAM policy to allow read-only access to a specific IAM user.
Test access using the AWS CLI.
Skills Practiced: S3, IAM, AWS CLI.
**Lab 3: Create a Basic VPC**
Objective: Design a simple network using VPC.
Steps:
Create a VPC with a CIDR block (e.g., 10.0.0.0/16).
Add two subnets: one public and one private.
Launch an EC2 instance in each subnet.
Attach an Internet Gateway and a NAT Gateway.
Test connectivity between the instances.
Skills Practiced: VPC, Subnets, Gateways.
**Lab 4: Automate EC2 Deployment with CloudFormation**
Objective: Use CloudFormation templates to deploy resources.
Steps:
Write a CloudFormation template to create an EC2 instance with a security group.
Use the AWS Management Console or CLI to deploy the stack.
Validate the resources created by the stack.
Skills Practiced: CloudFormation, EC2, CLI.
Intermediate Level Labs
**Lab 5: Configure an Application Load Balancer**
Objective: Distribute traffic across multiple instances.
Steps:
Launch two EC2 instances in different availability zones.
Deploy a web application on both instances.
Create an Application Load Balancer (ALB) and register the instances.
Test load balancing by accessing the ALB DNS name.
Skills Practiced: Load Balancer, EC2, Availability Zones.
**Lab 6: Set Up an Auto Scaling Group**
Objective: Implement scaling for high availability.
Steps:
Create a launch template or configuration for EC2 instances.
Configure an Auto Scaling Group with a minimum of 2 instances and a maximum of 5.
Set up scaling policies based on CPU utilization.
Simulate traffic to observe scaling behavior.
Skills Practiced: Auto Scaling, Load Balancer, CloudWatch.
**Lab 7: Implement Bucket Policies and Lifecycle Rules**
Objective: Manage S3 bucket access and storage lifecycle.
Steps:
Create an S3 bucket and enable server-side encryption.
Add a bucket policy to allow access from a specific IP range.
Configure a lifecycle rule to move objects to S3 Glacier after 30 days.
Test access and lifecycle rule behavior.
Skills Practiced: S3, Bucket Policies, Lifecycle Rules.
**Lab 8: Automate Infrastructure with AWS CLI**
Objective: Use the AWS CLI to create and manage resources.
Steps:
Launch an EC2 instance using the AWS CLI.
Create an S3 bucket and upload files using the CLI.
Configure an IAM role for the EC2 instance to access the S3 bucket.
Test S3 access from the EC2 instance.
Skills Practiced: AWS CLI, EC2, S3, IAM.
Advanced Level Labs
**Lab 9: Multi-Tier Architecture with High Availability**
Objective: Build a multi-tier architecture.
Steps:
Deploy a web server in the public subnet and a database in the private subnet.
Use an Application Load Balancer for the web server.
Configure Auto Scaling for the web tier.
Secure the database tier with proper security group rules.
Skills Practiced: VPC, Load Balancer, Auto Scaling, RDS.
**Lab 10: Disaster Recovery Using S3 Cross-Region Replication**
Objective: Ensure data durability and availability across regions.
Steps:
Create two S3 buckets in different regions.
Enable versioning and cross-region replication.
Upload files to the primary bucket and verify replication.
Test recovery by accessing data from the secondary bucket.
Skills Practiced: S3, Cross-Region Replication.
**Lab 11: CI/CD Pipeline with CloudFormation and CodePipeline**
Objective: Automate deployment of a web application.
Steps:
Create a CloudFormation template to deploy an application stack.
Set up a CodePipeline with stages for source, build, and deploy.
Test the pipeline with changes to the source code.
Skills Practiced: CloudFormation, CodePipeline, Automation.
**Lab 12: Monitor and Optimize Resources**
Objective: Use CloudWatch to monitor AWS resources.
Steps:
Enable detailed monitoring for EC2 instances.
Create CloudWatch alarms for CPU utilization and disk usage.
Set up notifications using SNS.
Use CloudWatch Logs to analyze application logs.
Skills Practiced: CloudWatch, SNS, Logs.
Tips for Success
Start Small:
Begin with beginner labs and gradually progress to more complex scenarios.
Document Your Work:
Write step-by-step guides for each lab and save them in a portfolio (e.g., GitHub).
Use Free Resources:
Leverage the AWS Free Tier to practice without incurring costs.
