
### 🌐 Connect VPC



---
# 🌐 VPC Peering

## Overview

VPC Peering is a networking connection between two Virtual Private Clouds (VPCs) that enables resources in each VPC to communicate with one another using private IP addresses.

This concept is commonly used when organizations need secure communication between different cloud environments without routing traffic through the public internet.

## Architecture

![Connect VPC](../../../notes/connect-vpc.png)

## Objective

The goal of this activity was to understand how VPC Peering enables private communication between separate VPCs while maintaining security and network isolation.

## AWS Services Used

* Amazon VPC
* Route Tables
* Security Groups
* CIDR Blocks
* VPC Peering Connection

## Key Concepts Learned

### Private Connectivity

VPC Peering allows traffic to flow directly between VPCs using private IP addresses.

### Secure Communication

Traffic remains within the AWS network instead of traversing the public internet.

### Route Configuration

Route tables must be updated to direct traffic through the peering connection.

### Network Design

Proper CIDR planning is required because overlapping IP address ranges are not supported.

## Benefits of VPC Peering

* Low-latency communication
* Secure private networking
* No need for VPNs or Internet Gateways
* Simplified network architecture
* Cost-effective connectivity

## Skills Gained

* AWS Networking Fundamentals
* VPC Design
* Route Table Configuration
* Cloud Network Security
* Private Cloud Connectivity

## Learning Source

Completed through **AWS Cloud Quest: Cloud Practitioner** as part of my cloud networking learning journey.

## References

* AWS VPC Peering Documentation
* AWS Cloud Quest Learning Modules

## Personal Comment

* This one is easy since you will just need to create a 'bridge' for three VPC's since in default a VPC can't talk to other VPC
* My Planning skills have also been put in the good use since it required VPC's to have no packet loss (data loss).

---
