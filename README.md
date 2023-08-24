# Unveiling the Power of AWS 3-Tier Architecture with Terraform: Building a Resilient and Scalable VPC

---

## Architecture Diagram

![AWS 3 tier Architecture - VPC and Components](/architecture-diagram/AWS%203%20Tier%20Architecture.png)

---

## Introduction

In the realm of cloud infrastructure, the AWS 3-tier architecture has emerged as a steadfast approach for creating resilient, scalable, and secure applications. This repository serves as the gateway into the world of architecting such an environment, powered by the dynamic capabilities of Terraform.

This repository has meticulously crafted collection of Terraform manifest files that encapsulate the intricate layers of the AWS 3-tier architecture. Our focus is crystal clear: crafting a Virtual Private Cloud (VPC) that spans two Availability Zones (AZs), fortified with a public subnet for the all-important NAT Gateway, and dual private subnets tailored to house the core components - EC2 instances and RDS databases.

But the story doesn't end there. Our commitment to robustness drives us to replicate this architecture across both AZs, ensuring not only high availability but also robust disaster recovery mechanisms. Additionally, this guide chronicles the creation of Internet Gateways and Route Tables, crucial elements that bind the different tiers together into a harmonious whole.

The beauty of Terraform lies in its ability to translate infrastructure into code, enabling rapid, consistent, and auditable deployment. Inside this repository, the organized manifest files that bring our architectural vision to life. The architecture diagrams provide a visual guide to deepen developer's understanding of the flow and connections within this multi-layered setup.

This repository aims to cater to all. By navigating through the manifest files and diagrams, the intricacies of AWS 3-tier architecture implementation while mastering the art of orchestrating it with Terraform will be unravelled.

---

## Problem Statement and Solution

**Problem Statement:**

Building a robust and scalable cloud infrastructure on Amazon Web Services (AWS) demands a comprehensive understanding of architectural principles and efficient deployment techniques. Aspiring cloud architects often grapple with the challenge of designing a 3-tier architecture that ensures high availability, disaster recovery, and secure communication between different components. Navigating through the intricacies of creating a Virtual Private Cloud (VPC) spanning multiple Availability Zones (AZs), configuring public and private subnets, setting up a NAT Gateway, managing Internet Gateways, and establishing Route Tables can be overwhelming, especially for newcomers to AWS. Moreover, ensuring consistent replication of this architecture across multiple AZs adds another layer of complexity.

**Solution:**

This video tutorial is designed to be a definitive guide in overcoming the challenges of constructing an AWS 3-tier architecture using Terraform. By going through each step of the process, a scalable VPC that spans two AZs is created, comprising a public subnet for a NAT Gateway and private subnets housing EC2 instances and RDS databases. Furthermore, the critical task of replicating this architecture across both AZs is detailed, cementing its robustness and disaster recovery capabilities.

Our solution harnesses the power of Terraform, a cutting-edge infrastructure-as-code tool, to streamline the deployment process. This guide provides hands-on experience in writing and executing Terraform manifest files that orchestrate the entire architecture. The theoretical underpinnings of each compononent will be provided alongside real-world insights and best practices that seasoned cloud architects employ.

This tutorial deepens one's understanding of AWS 3-tier architecture. It also explains how to leverage Terraform's capabilities for consistent, repeatable, and efficient infrastructure deployment. This tutorial is suitable for AWS novices and even an experienced practitioners seeking to enhance their skills, this tutorial will equip them with the knowledge and confidence to architect and deploy complex cloud infrastructures that meet modern standards of scalability, security, and resilience.

---

## Terraform Commands

### Terraform Initialize

```shell
terraform init
```

---

### Terraform Validate

```shell
terraform validate
```

---

### Terraform plan

```shell
terraform plan
```

---

### Terraform Apply

```shell
terraform apply
```

---

### Terraform Destroy

```shell
terraform apply -destroy -auto-approve
```

---
