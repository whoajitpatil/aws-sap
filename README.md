# aws-sap
Repository for my learning path to Solution Architect - Professional

### **Week 1: AWS Basics and Compute (EC2, AMI, Security Groups)**
#### **Day 1: AWS Overview & EC2 Fundamentals**
- What is AWS, Regions, and Availability Zones
- Introduction to EC2, Types of Instances
- Launching an EC2 instance
- Hands-on: Spin up a t2.micro instance

#### **Day 2: AMI (Amazon Machine Images)**
- What is an AMI
- Types of AMIs (Public, Private, Marketplace)
- Creating and managing your own AMI
- Hands-on: Create and launch an EC2 instance from a custom AMI

#### **Day 3: Security Groups & Key Pairs**
- Role of Security Groups
- Best Practices for Security Groups
- Key pairs and SSH access
- Hands-on: Configure Security Groups and SSH into an instance

#### **Day 4: Advanced EC2 Topics**
- Elastic Load Balancers (ELB)
- Autoscaling Groups
- Instance Metadata and User Data
- Hands-on: Set up an Auto Scaling Group and test scaling policies

#### **Day 5: Networking with EC2**
- Elastic IPs
- ENI (Elastic Network Interfaces)
- Placement Groups (Cluster, Spread, Partition)
- Hands-on: Associate Elastic IPs and explore Placement Groups

---

### **Week 2: Networking (VPC, Route 53, CloudFront)**
#### **Day 6: VPC Basics**
- Components of VPC: Subnets, Route Tables, IGW
- Creating a custom VPC
- Hands-on: Set up a VPC with public and private subnets

#### **Day 7: Advanced Networking**
- NAT Gateways vs NAT Instances
- VPC Peering and Transit Gateway
- Hands-on: Connect two VPCs using Peering

#### **Day 8: Route 53**
- DNS Basics and Hosted Zones
- Route 53 Routing Policies (Simple, Weighted, Latency, Failover)
- Hands-on: Set up a domain name and configure failover routing

#### **Day 9: CloudFront**
- CDN basics and benefits
- Configuring CloudFront with S3 or a custom origin
- Hands-on: Set up a CloudFront distribution with a static website

---

### **Week 3: Storage Solutions (EBS, FSx ONTAP)**
#### **Day 10: EBS (Elastic Block Store)**
- Types of EBS volumes (gp3, io2, sc1, st1)
- Snapshots and AMI integration
- Hands-on: Attach and manage EBS volumes on an EC2 instance

#### **Day 11: FSx ONTAP**
- Overview of FSx services and ONTAP
- Creating and managing FSx ONTAP volumes
- Hands-on: Mount FSx ONTAP volumes to EC2 instances

#### **Day 12: S3 and Lifecycle Management**
- S3 bucket policies and security
- Versioning, Lifecycle Policies, and Glacier
- Hands-on: Configure lifecycle rules and cross-region replication

---

### **Week 4: AWS Containers and Serverless**
#### **Day 13: ECS (Elastic Container Service)**
- ECS vs EKS vs Fargate
- Cluster, Task Definitions, and Services
- Hands-on: Deploy a containerized app on ECS

#### **Day 14: AWS Lambda**
- Overview of Lambda and event triggers
- IAM roles for Lambda
- Hands-on: Build a Lambda function triggered by an S3 upload

#### **Day 15: EventBridge, SNS, and SQS**
- Event-driven architecture with EventBridge
- Differences between SQS and SNS
- Hands-on: Integrate SNS, SQS, and EventBridge in a simple workflow

---

### **Week 5: Monitoring, Optimization, and Security**
#### **Day 16: Monitoring and Cost Optimization**
- CloudWatch metrics and logs
- Budgets and cost optimization
- Hands-on: Set up an alarm for billing and monitor application metrics

#### **Day 17: Security and Identity**
- IAM roles, policies, and users
- AWS Organizations and SCPs
- Hands-on: Configure policies for least-privilege access

---

### **Week 6: Advanced Topics and Integration**
#### **Day 18-21: Project Implementation**
- Combine multiple services: EC2, FSx ONTAP, Lambda, S3, and Route 53
- Deploy a full-stack application or CI/CD pipeline
- Test high availability and failover scenarios

#### **Day 22-24: Case Studies**
- Study real-world architectures for:
  - Web Applications
  - Data Pipelines
  - Disaster Recovery
- Document learnings and identify best practices

#### **Day 25-30: Practice Exams and Final Touches**
- Take AWS certification practice exams
- Review weak areas
- Explore advanced topics or focus on preparing a specialized project

This curriculum balances conceptual understanding with hands-on practice, ensuring you're well-prepared for a Cloud Architect role. Let me know if you'd like deeper guidance on any specific topic!