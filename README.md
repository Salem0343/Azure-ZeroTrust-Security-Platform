## Azure Zero-Trust Cloud Security Lab

# Overview

This project implements an enterprise-grade cloud security architecture in Microsoft Azure based on Zero Trust principles.

It demonstrates how a cloud environment can be designed, exposed, monitored, attacked, and secured using native Azure security services.

---

# Key Components

- Microsoft Entra ID (IAM, MFA, RBAC, Conditional Access)
- Virtual Network (VNet) with segmented subnets
- Network Security Groups (NSG) for traffic control
- Azure Key Vault for secure secrets management
- Microsoft Defender for Cloud (threat detection & posture management)
- Microsoft Sentinel (SIEM for monitoring and incident response)
- VPN Gateway design (hybrid connectivity)
- Private access architecture (no direct exposure)

---

# Architecture

The environment follows a layered security model:

Internet → Controlled Access → Segmented Network → Private Resources → Monitoring & Detection

- Public access is restricted and controlled
- Critical resources are deployed in private subnets
- Secrets are stored securely in Key Vault
- All activity is monitored through Defender and Sentinel

---

# Security Principles

This project is built using:

- Zero Trust Architecture
- Defense in Depth
- Least Privilege Access
- Network Segmentation
- Secure Identity Management

---

# Attack Simulation

The project includes realistic attack scenarios:

- Port scanning
- SSH brute-force attempts
- Unauthorized access attempts

All activities generate logs that are analyzed by Defender and Sentinel.

---

# Detection & Response

- Microsoft Defender identifies suspicious behavior
- Microsoft Sentinel correlates events and creates incidents
- Alerts are investigated and responded to using:
  - NSG rules
  - Access restrictions
  - Security hardening

---

# Outcome

The project demonstrates:

- Secure cloud architecture design
- Threat detection and monitoring
- Incident response workflow
- Security hardening after attack

---

# Skills Demonstrated

- Cloud Security Architecture (Azure)
- Identity & Access Management (Entra ID)
- Network Security (NSG, VNet, segmentation)
- SIEM operations (Microsoft Sentinel)
- Threat detection and incident response
- Secrets management (Key Vault)
