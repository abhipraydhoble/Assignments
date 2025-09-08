
```markdown
# AWS Tasks 

---

## 🧑‍💻 IAM
1. Enable MFA for an IAM user → Add MFA device using Google Authenticator and test login with OTP.  
2. Create IAM user with only CLI access → No console access, use CLI to create an S3 bucket.  

---

## 🖥️ EC2 & EBS
1. Install AWS CLI on Ubuntu and verify installation.  
2. Create Image (AMI) from Instance and launch another instance.  
3. Launch EC2 with custom security group (only your IP) → Restrict SSH to your IP.  
4. Create Volume and mount it on an EC2 instance.  
5. Recover EC2 access if key pair is lost → Detach root volume, attach to another instance, add new key, re-attach.  
6. Take EBS snapshot and restore a new volume → Backup and recover data.  
7. Store AMI in S3 bucket.  

---

## ☁️ S3
1. Host a static website on S3 → Upload `index.html`, enable hosting.  
2. Enable versioning and restore deleted objects.  
3. Enable S3 bucket versioning and upload multiple versions of the same file.  
4. Generate a pre-signed URL to share files temporarily.  
5. Enable server access logging in S3 → Track bucket/file access.  
6. Trigger Lambda on S3 upload to send email via SNS.  
7. S3 bucket cross-region access setup.  

---

## 📊 CloudWatch & Auto Scaling
1. Set up a CloudWatch alarm for EC2 CPU ≥ 50% → Send notification via SNS.  
2. CloudWatch with Auto Scaling Group (ASG) → Scale out/in when CPU exceeds 50%.  

---

## 🌐 VPC & Networking
1. VPC Peering → Same region and cross region.  
2. VPC 3-tier architecture → Web, App, DB layers.  
3. Explore VPC endpoint for S3 → Access from private EC2 without internet.  
4. Subnetting and network calculation (CIDR 172.21.0.0/16 → /17 to /23).  

---

## ⚖️ Load Balancing
1. Host CSS template on Nginx and HTTPD simultaneously on same server (Nginx → 80, Apache → 81).  
2. Create and configure Application Load Balancer (ALB) → Forward traffic on 80/81.  

---

## 🪄 Lambda
1. Trigger Lambda function on S3 upload → Send email via SNS.  
2. Schedule EC2 start/stop (optional simple automation).  

---
```
