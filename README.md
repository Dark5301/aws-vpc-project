# 🚀 Custom AWS VPC for Scalable Bug Bounty Automation

This project demonstrates a secure, scalable AWS Virtual Private Cloud (VPC) architecture designed to serve as a cloud-based base environment for automated bug bounty workflows.

## 📌 Project Overview

This AWS VPC setup includes:

- **1 Public Subnet** — for hosting a Bastion Host (EC2 instance with SSH access)
- **1 Private Subnet** — for internal tools like recon or exploit engines
- **Internet Gateway** — for outbound internet access
- **NAT Gateway** — allowing private subnet to access the internet securely
- **Route Tables** — correctly configured for secure traffic flow

> 🛠️ Deployed using the AWS Console (no Terraform/CDK used)

## 🔐 Why This Architecture?

Bug bounty and red teaming often require scalable infrastructure to:

- Run automated recon and scanning tools
- Deploy exploit servers in isolated networks
- Store results securely in non-exposed environments
- Rotate and manage access via bastion hosts or jump boxes

This architecture lays the foundation for such a setup.

## 🧠 Skills Demonstrated

- VPC and Subnet Design
- Secure Cloud Networking Principles
- NAT and Bastion Host Configuration
- EC2 Deployment and Access Control
- Internet vs Private Route Table Isolation

## 🎯 Use Cases

- Automating **bug bounty** workflows using Python/Bash tools
- Running **custom exploit engines** in isolated environments
- Red team infrastructure setups
- Cloud labs for OSINT, scanning, or enumeration tools

## 📸 Architecture Diagram

<img width="1024" height="1024" alt="ChatGPT Image Aug 5, 2025, 02_33_39 PM" src="https://github.com/user-attachments/assets/3d65aab1-4451-43af-99bc-d5332786345f" />

## 📜 License

This project is licensed under the MIT License.

