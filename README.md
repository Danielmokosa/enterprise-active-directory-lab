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
---
  ### Domain Controller Overview

![Domain Controller Overview](screenshots/phase1_domain_controller_overvieww.png)
### Active Directory Domain Services

![AD DS Installed](screenshots/phase1_ad_ds_installed.png)
### DNS Configuration

![DNS Configuration](screenshots/phase1_dns_configuration.png)

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
---
### Organizational Unit Structure

![Organizational Unit Structure](screenshots/phase2_ou_structure_expanded.png)
---
 ### Organizational Units

![Organizational Units](screenshots/organizational-units.png)
---

### Security Groups

![Security Groups](screenshots/security-groups.png)

---

### Enterprise Users

![Enterprise Users](screenshots/enterprise-users-it-support.png)
---
### RBAC User Group Membership

![RBAC User Group Membership](screenshots/phase2_grace_hr_membership.png)
---
### HR Security Group Membership

![HR Security Group Membership](screenshots/phase2_hr_group_members.png)
---
### Phase 3 — Group Policy & Security Hardening
- Configured workstation restriction policies
- Implemented Control Panel access restrictions
- Began centralized policy management using Group Policy Objects (GPOs)

---

### Group Policy Management

![Group Policy Management](screenshots/group-policy-management.png)

### GPO Workstation Restrictions

![GPO Workstation Restrictions](screenshots/workstation-restriction-policydeepdive.png)

### GPO Editor Overview

![GPO Editor Overview](screenshots/phase3_gpo_editor_overview.png)

### Workstation Restriction Policy

![Workstation Restriction Policy](screenshots/phase3_control_panel_policy.png)

![Workstation Restriction Policy](screenshots/phase3_control_panel_policy2.png)
### Linked Workstation GPO

![Linked Workstation GPO](screenshots/phase3_gpo_linked_to_workstations.png)

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
### Successful Domain Join

![Successful Domain Join](screenshots/phase4_successful_domain_join.png)
### Workstation in Active Directory

![Workstation in Active Directory](screenshots/phase4_workstation_in_ad.png)
### Enterprise DNS Resolution

![Enterprise DNS Resolution](screenshots/phase4_dns_resolution.png)
### Enterprise Shared Resources

![Enterprise Shared Resources](screenshots/phase4_enterprise_shared_resources.png)
### Network Share Configuration

![Network Share Configuration](screenshots/phase4_network_share_permissions.png)
### RBAC NTFS Permissions

![RBAC NTFS Permissions](screenshots/phase4_rbac_ntfs_permissions.png)
### Access Denied Validation

![Access Denied Validation](screenshots/phase4_access_denied_validation.png)
### Successful Department Access

![Successful Department Access](screenshots/phase4_successful_department_access.png)

### Phase 5 — Enterprise Operations & Delegated Administration
   - Implemented delegated administration and enterprise operational workflows using Active Directory, Group Policy, RBAC, PowerShell, and enterprise access management concepts
      #### Delegated Administration & Least Privilege

    - Created operational administrative security groups:
      - MSIT_HelpDesk_Admins
      - MSIT_Junior_Admins
      - MSIT_Password_Reset_Operators
      - MSIT_Security_Auditors
      
   - Created delegated administrative user accounts:
     - Sarah.Helpdesk
     - Jacob.Admin
     - Mike.Support
     - Alex.Security 
  - Configured delegated password reset permissions
  - Implemented least privilege administrative access controls
  - Configured scoped administrative delegation using Active Directory
    
#### Identity & Access Management Operations

- Simulated enterprise onboarding workflows 
- Simulated enterprise offboarding workflows
- Configured Disabled Users Organizational Unit
- Implemented account disabling and access revocation workflows
- Validated department-based RBAC access control

#### Security Operations Foundations 
- Implemented account lockout investigations
- Investigated failed and successful authentication events
- Performed Event Viewer security log analysis
- Implemented authentication troubleshooting workflows
- Configured read-only security auditing concepts

#### Enterprise Resource Deployment 
- Configured Group Policy-based mapped network drives
- Implemented department-based drive mapping using security group targeting
- Configured enterprise shared printer deployment concepts
- Implemented SMB shared resources and NTFS access controls

#### Workstation & Endpoint Administration 
- Configured limited workstation administrative access
- Implemented scoped endpoint administration concepts
- Validated restricted domain-level administrative access

#### PowerShell Administration & Automation 
- Performed Active Directory user enumeration
- Queried Security Group memberships
- Automated account administration operations
- Performed account lockout and password administration
- Retrieved and analyzed security event logs using PowerShell

#### Key Enterprise Concepts Practiced 
- Delegated Administration
- Least Privilege Access Control
- Identity Lifecycle Management
- Role-Based Access Control (RBAC)
- Authentication Troubleshooting
- Security Auditing
- Enterprise Workstation Administration
- Group Policy Deployment
- IAM Operations
- Operational Security Monitoring
  ---

### Administrative Accounts

---

![Administrative Accounts](screenshots/admin-accounts.png)

---

## Planned Expansion

## SIEM & Security Monitoring

- Splunk Enterprise deployment and log ingestion
- Microsoft Sentinel integration
- Windows Event Forwarding (WEF)
- Centralized security event collection
- Authentication event monitoring
- Security alert generation and analysis
- Detection engineering workflows
- Security log correlation and investigation

## Cloud & Hybrid Identity
- Microsoft Azure integration
- Microsoft Entra ID (Azure AD) integration
- Hybrid identity synchronization concepts
- Cloud identity and access management (IAM)
- Multi-factor authentication (MFA) concepts
- Azure role-based access control (Azure RBAC)
- Hybrid authentication workflows
- Microsoft Defender Security Operations
- Microsoft Defender configuration and monitoring
- Endpoint protection policy management
- Security event analysis
- Threat monitoring workflows
- Endpoint security administration
## Security Engineering & Detection Operations
- Brute-force attack simulations
- Account lockout investigations
- Authentication anomaly investigations
- Privilege escalation simulations
- PowerShell logging analysis
- Event ID monitoring and analysis
- Detection rule creation concepts
- Security operations investigation workflows

## PowerShell Automation & Reporting
- Automated user provisioning scripts
- Bulk Active Directory administration
- Group membership automation
- Security reporting scripts
- Event log retrieval automation
- Administrative reporting workflows

## Enterprise Security Concepts Practiced
- SIEM Operations
- Security Monitoring
- Detection Engineering
- Hybrid Identity
- Cloud IAM
- Security Event Correlation
- Threat Detection
- Enterprise Logging
- Endpoint Security Operations
- Security Automation

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

