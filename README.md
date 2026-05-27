# Enterprise Active Directory Infrastructure Lab

## Overview

This project simulates a small enterprise Active Directory environment using Windows Server 2022 and Windows 11 within a virtualized infrastructure. The lab focuses on enterprise identity management, centralized administration, RBAC, Group Policy, workstation management, and security hardening concepts commonly used in enterprise IT environments.

---

## Technologies Used

- Windows Server 2022
- Windows 11
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy Management
- NTFS Permissions
- SMB File Sharing
- RBAC (Role-Based Access Control)
- PowerShell
- UTM Virtualization

---

## Completed Infrastructure

### Phase 1 — Core Infrastructure
- Installed Windows Server 2022
- Configured Active Directory Domain Services
- Configured DNS
- Promoted server to Domain Controller
- Created enterprise domain: mokosa.local

### Phase 2 — Enterprise Organizational Structure
- Created Organizational Units (OUs)
- Created enterprise users and administrative accounts
- Implemented Security Groups for RBAC
- Organized departments:
  - IT Support
  - Security Operations
  - Cloud Operations
  - HR
  - Finance
  - Servers
  - Workstations
  - Admin Accounts

### Phase 3 — Group Policy & Security Hardening
- Configured workstation restriction policies
- Implemented Control Panel access restrictions
- Began centralized policy management using Group Policy Objects (GPOs)

### Phase 4 — Endpoint & Enterprise Operations Integration
- Configured Windows 11 enterprise workstation
- Configured static DNS communication between workstation and Domain Controller
- Successfully domain-joined Windows 11 workstation to mokosa.local
- Validated workstation-to-domain authentication workflows
- Implemented enterprise shared folder infrastructure
- Configured SMB shared network resources
- Implemented NTFS permissions and department-based RBAC access control
- Validated department access segmentation using Active Directory Security Groups
- Tested enterprise authentication and file access workflows across domain users

---

## Planned Expansion

- Shared drives, mapped network drives, and NTFS permissions
- Password policies, password reset workflows, and account lockout administration
- RBAC expansion and administrative delegation
- PowerShell administration and automation
- SIEM integration (Splunk / Microsoft Sentinel)
- Azure/AWS hybrid identity concepts
- Security monitoring, logging, and event forwarding
- Microsoft Defender security monitoring
- Attack simulation and detection engineering

---

## Screenshots

Screenshots and infrastructure diagrams will be added as the lab expands.

### Organizational Units

![Organizational Units](screenshots/organizational-units.png)

---

### Security Groups

![Security Groups](screenshots/security-groups.png)

---

### Enterprise Users

![Enterprise Users](screenshots/enterprise-users-it-support.png)

---

### Group Policy Management

![Group Policy Management](screenshots/group-policy-management.png)

---

### GPO Workstation Restrictions

![GPO Workstation Restrictions](screenshots/workstation-restriction-policydeepdive.png)

---

### Administrative Accounts

![Administrative Accounts](screenshots/admin-accounts.png)


### Successful Domain Join


### Enterprise DNS Resolution


### Enterprise Shared Resources


### RBAC NTFS Permissions


### Access Denied Validation


### Successful Department Access

