# 🚀 AWS VPC Peering Project

## 📖 Overview

This project demonstrates how to establish communication between two AWS VPCs using VPC Peering. Two EC2 instances were deployed in separate VPCs, and connectivity was verified using Ping (ICMP).

---

## 🏗️ Architecture

![Architecture Diagram](architecture/aws-vpc-peering-diagram.svg)

---

## ⚙️ Services Used

- Amazon VPC
- Amazon EC2
- Internet Gateway
- Route Tables
- Security Groups
- VPC Peering

---

## 🌐 Network Configuration

| Resource | Configuration |
|-----------|-------------|
| VPC-1 | 10.0.0.0/16 |
| Public Subnet-1 | 10.0.1.0/24 |
| VPC-2 | 20.0.0.0/16 |
| Public Subnet-2 | 20.0.1.0/24 |
| EC2 Instances | App-1 & App-2 |

---

## 🔄 Implementation Steps

1. Created two custom VPCs.
2. Created public subnets in each VPC.
3. Attached Internet Gateways.
4. Configured Route Tables.
5. Launched EC2 instances.
6. Created a VPC Peering connection.
7. Added peering routes to route tables.
8. Configured Security Groups.
9. Verified connectivity using Ping.

---

## 📸 Screenshots

### VPC Peering Connection
![VPC Peering](screenshots/vpc-peering-active.png)

### Route Table Configuration
![Route Table](screenshots/route-table-vpc1.png)

### Connectivity Test
![Ping Success](screenshots/ping-success.png)

---

## ✅ Result

Successfully established communication between EC2 instances located in different VPCs through AWS VPC Peering.

---

## 👨‍💻 Author

**Jenish Patel**  
Cloud & DevOps Enthusiast ☁️# aws-vpc-peering-project
AWS VPC Peering project using EC2 instances and VPC networking.
