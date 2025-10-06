# Microsoft Entra ID Security & Access Management Project

**Author:** Lauren C.  
**Goal:** Build a secure, well-structured identity and access management environment inside Microsoft Entra ID (formerly Azure Active Directory).

---

## Overview
This project highlights how I configured and secured user identities, passwords, and admin roles inside **Microsoft Entra ID** — Microsoft’s cloud-based identity platform.  
I designed this project to simulate a real-world environment where an organization needs strong controls for who can access what, how they authenticate, and how passwords are protected.

Every configuration aligns with best practices for **cybersecurity analysts and cloud administrators**, focusing on risk reduction, user empowerment, and compliance with identity security standards.

---

## Configurations & Features

### 1. Tenant Setup and Role Management
- Deployed a dedicated Microsoft Entra tenant.  
- Assigned key roles (Global Administrator, User Administrator) with the **principle of least privilege** in mind.  
- Used Role-Based Access Control (RBAC) to separate admin duties and reduce exposure risk.  

### 2. Self-Service Password Reset (SSPR)
- Enabled **SSPR** for users to reset passwords securely without admin assistance.  
- Configured verification through both **email** and **Microsoft Authenticator** for multi-layered identity checks.  
- Verified successful resets through:  
  [https://passwordreset.microsoftonline.com](https://passwordreset.microsoftonline.com)

### 3. Custom Banned Password Policy
- Implemented a **tenant-level banned password list** using Microsoft Entra Password Protection.  
- Blocked weak or predictable terms (like *Company2025*, *Welcome1*, *Password123*).  
- Tested policy enforcement through multiple password change scenarios.  
- Confirmed audit logging of password rejection events for monitoring and compliance.  

### 4. Login Security Banner
- Added a custom **sign-in banner** through Company Branding to increase user awareness:  
  > **Security Reminder:** Never share credentials. IT will never ask for your password via email or chat.  
- Reinforced consistent messaging across the organization’s login experience.

### 5. Conditional Access and MFA Integration
- Configured **Conditional Access policies** to control sign-ins by device, location, and risk level.  
- Enabled **Multi-Factor Authentication (MFA)** for all admin accounts and critical users.  
- Established policies to require MFA on unfamiliar devices and for privileged role activations.

---

## Skills Demonstrated
- Cloud Identity & Access Management (IAM)  
- Microsoft Entra ID / Azure AD Administration  
- Role-Based Access Control (RBAC)  
- Password Protection & Security Policy Enforcement  
- Multi-Factor Authentication (MFA) Setup  
- Conditional Access Policy Configuration  
- IT Security Communication & Awareness  

---

## Key Takeaways
- Strong identity controls are the foundation of every secure network.  
- Empowering users with secure self-service tools improves both security and efficiency.  
- Enforcing password policies and MFA dramatically reduces credential-based attacks.  
- Security awareness starts with clear communication — even a login banner can shift behavior.

---

## Tools Used
- [Microsoft Entra Admin Center](https://entra.microsoft.com)  
- [Azure Portal](https://portal.azure.com)  
- Microsoft 365 Admin Center  
- PowerShell (for administrative automation)  

---

## Project Outcome
This project successfully established a secure identity management environment in Microsoft Entra ID.  
It demonstrates a full understanding of modern access control, authentication management, and password protection — all critical components for cybersecurity operations in the cloud.

---

**Version:** Final  
**Completion Date:** October 2025
