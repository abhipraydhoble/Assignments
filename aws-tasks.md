# AWS Tasks

## $${\color{orange}\textbf{1. Install AWS CLI on Ubuntu Machine}}$$
   - Install AWS CLI on your Ubuntu machine by following the steps from the official AWS documentation.
   - Verify the installation using the command `aws --version`.

## $${\color{orange}\textbf{2. Host CSS Template for Nginx and HTTPD Simultaneously on Same Linux Server}}$$
   - Install both Nginx and Apache HTTPD on a Linux server.
   - Configure Nginx to listen on port 80 and HTTPD to listen on port 81.
   - Set up each service to serve a different CSS template (or static website).

## $${\color{orange}\textbf{3. Create Image from Instance and Launch Another Instance}}$$
   - Create an AMI (Amazon Machine Image) from an existing EC2 instance.
   - Launch a new EC2 instance using the created AMI.

## $${\color{orange}\textbf{4. CloudWatch with Auto Scaling Group (ASG)}}$$
   - Create a launch template.
   - Create an Auto Scaling Group (ASG) with the desired capacity of 2 instances.
   - Create a CloudWatch alarm that triggers when the CPU utilization of an EC2 instance exceeds 50% for 5 minutes.
   - Set the autoscaling action for the alarm to send a notification using SNS.

## $${\color{orange}\textbf{5. Create and Configure Application Load Balancer (ALB)}}$$
   - Create an Application Load Balancer (ALB).
   - Configure the ALB to redirect traffic on port 80 to Apache HTTPD and on port 81 to Nginx.

## $${\color{orange}\textbf{6. Create IAM User with Only CLI Access}}$$
   - Create an IAM user with CLI access only (no console access).
   - Using this user, create an S3 bucket.

## $${\color{orange}\textbf{7. Create Volume and Mount It on EC2 Instance}}$$
   - Create an EBS volume.
   - Attach the volume to an EC2 instance and mount it on the server.

## $${\color{orange}\textbf{8. Store AMI in S3 Bucket}}$$
   - Create an AMI from an EC2 instance.
   - Store the AMI in an S3 bucket.

## $${\color{orange}\textbf{9. Host Static Website Using S3}}$$
   - Create an S3 bucket and enable static website hosting.
   - Upload your website files to the S3 bucket.

## $${\color{orange}\textbf{10. S3 Bucket Cross Region Access}}$$
   - Create an S3 bucket in one region and configure cross-region access to another region.

## $${\color{orange}\textbf{11. VPC Peering: Same Region and Different Region}}$$
   - Set up VPC peering between two VPCs in the same region.
   - Set up VPC peering between two VPCs in different regions.

## $${\color{orange}\textbf{12. VPC 3-Tier Architecture}}$$
   - Design and deploy a 3-tier architecture in AWS using VPC.
     - **Web Layer:** Public subnet with EC2 instances running web servers.
     - **Application Layer:** Private subnet with EC2 instances running the application.
     - **Database Layer:** Private subnet with RDS instances.

---

### $${\color{orange}\textbf{Additional AWS Networking Tasks:}}$$

## $${\color{orange}\textbf{1. Subnetting and Network Calculation (CIDR Range: 172.21.0.0/16)}}$$
   - Given the following network range `172.21.0.0/16`, calculate the subnet details for each CIDR from `/17` to `/23`.
     - Calculate the subnet mask, number of hosts, subnet range, and broadcast address for each subnet.

---
