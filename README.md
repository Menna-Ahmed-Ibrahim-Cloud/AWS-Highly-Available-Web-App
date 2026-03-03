# ☁️ Building a Highly Available & Scalable Web Application on AWS

This project demonstrates the implementation of a robust cloud infrastructure on AWS, completed during the **Digital Egypt Pioneers Initiative (DEPI)** supported by the Ministry of Communications and Information Technology.

## 🏗️ Architecture Overview
The system is built on a **Two-Tier Architecture** ensuring high availability and fault tolerance:
* **Networking:** Custom VPC with Public and Private subnets across multiple Availability Zones (Multi-AZ).
* **Compute:** EC2 instances managed by an **Auto Scaling Group** to handle traffic spikes.
* **Load Balancing:** An **Application Load Balancer (ALB)** to distribute incoming traffic evenly.
* **Database:** **Amazon RDS (MySQL)** deployed in a private subnet for secure data management.
* **Security:** Strict Security Groups and IAM roles to enforce the principle of least privilege.

## 🛠️ Skills Demonstrated
* Infrastructure as a Service (IaaS).
* Multi-AZ Deployment & High Availability.
* Scalability and Load Balancing.
* Cloud Security & Networking.
