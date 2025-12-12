# Secure Secrets Vault on Azure – Project Documentation
 
# Project Overview

This project demonstrates end-to-end deployment of a secure secrets management system using Microsoft Azure.
The solution includes a locked-down Virtual Network, secure private endpoints, Network Security Groups, and Azure Key Vault integrated with a hardened virtual machine.

#  Architecture Components

1.Virtual Network (VNet)
Central India region
Private and public subnets
Custom route and DNS configurations

2. Virtual Machine
Secure VM inside private subnet
Used to retrieve secrets from Key Vault
NSGs applied for inbound/outbound control

3. Azure Key Vault
Private endpoint enabled
Secrets stored securely
RBAC applied for controlled access

4. Network Security Groups
Restricted inbound (no public access)
Allow vault traffic only from VM subnet

5. Private Endpoint
Ensures Key Vault is accessible only inside VNet
Blocks all public network access


## Skills Demonstrated

Azure Infrastructure Deployment
Cloud Security Architecture
VNet Isolation and Segmentation
IAM & RBAC Access Policies
Key Vault Private Networking
NSG & Firewall Configuration
Secure Secret Retrieval

 # Outcome
 Successfully built an enterprise-grade secure vault solution demonstrating cloud security, networking, identity, and infrastructure design capabilities.
