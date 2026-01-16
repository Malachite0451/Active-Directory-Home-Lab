# Active Directory Home Lab

## Overview
This project is a fully functional Active Directory home lab designed to simulate a real-world corporate IT environment. The goal of this lab was to gain hands-on experience with Windows Server administration, identity and access management, Group Policy, file services, networking fundamentals, and remote desktop support operations.

The environment includes a domain controller providing Active Directory, DNS, and DHCP services, multiple domain-joined Windows workstations, and a dedicated file server. Access is managed using role-based security groups following the principle of least privilege. Group Policy is used to enforce security settings, map network drives, control Remote Desktop access, and standardize workstation behavior.

A remote support workflow was implemented to mirror real desktop support operations. Support users can securely connect to workstations using Remote Desktop, review system and application logs via delegated Event Viewer access, and troubleshoot common user issues without requiring administrative privileges or server access.

## Lab Environment
- **Hypervisor:** Oracle VirtualBox  
- **Servers:** Windows Server 2025 (Active Directory, DNS, DHCP, File Server)  
- **Workstations:** Windows 11 Pro  
- **Scale:** 2 servers, 5 domain-joined workstations  

## Core Components
- Active Directory, DNS, and DHCP services  
- Group Policy design and enforcement  
- File server with NTFS permissions  
- Role-based access control (RBAC)  
- Secure Remote Desktop support workflow  

## Security & Access Model
High-level explanation of RBAC, least privilege, and GPO scoping.

## Remote Support Workflow
How support users access workstations and troubleshoot issues.

## Documentation
Links to detailed design and configuration notes.

## Skills Demonstrated
- Active Directory domain administration and user management  
- Organizational Unit (OU) design and delegation  
- Role-Based Access Control (RBAC) using security groups  
- Group Policy Object (GPO) creation, scoping, and troubleshooting  
- Domain password and account lockout policy configuration  
- Centralized drive mapping using Group Policy Preferences  
- NTFS permissions and SMB file share management  
- Windows File Server deployment and administration  
- DNS configuration and domain name resolution  
- DHCP server configuration and scope management  
- Windows Server domain joining and role installation  
- Secure Remote Desktop (RDP) access configuration via Group Policy  
- Delegated Event Viewer log access using least-privilege principles  
- Workstation and server access separation (support vs admin roles)  
- Network connectivity troubleshooting (DNS, SMB, authentication)  
- Remote desktop support workflows and user troubleshooting  
- Enterprise-style security hardening and policy enforcement  
- Documentation and technical communication of system design  
