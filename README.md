# MyProjects

# Sunningdale Tech - Modern Mobile Device Management
## Project Description

Designed and deployed a unified device management solution using Microsoft Intune to secure and manage a mixed environment of Apple and Windows 10 devices. The project focused on simplifying device enrollment, enforcing compliance policies, and ensuring secure access to corporate resources while enhancing the end-user experience.

## Scope
- Windows 10, Windows 11
- Apple Devices (Corporate iPads)

## Tools and Technology Used
- Microsoft Intune
- Windows Autopatch
- Microsoft Defender for EndPoint
- Apple Business Manager

### Windows 10 and Windows 11

- Configure Automatic Enrollment
- Configure Entra Connect
- Configure Device Categories and Scope Tags
- Onboard Windows 10 Devices to Intune
- Configure Compliance Policies
- Configure EndPoint Protection Policies (BitLocker, Azure LAPS, Attack Surface Reduction, etc)
- Configure Microsoft Security Baselines (for Windows 10, Edge, Defender and M365 Apps)
- Configure integration with Microsoft Defender for EndPoint
- Implement Windows AutoPatch
- Add standard Apps and configure Company Portal
- Implement Role Based Access Control

### Corporate iPads
- Setup Apple Business Manager Account
- Setup MDM push certificate and integrate with Microsoft Intune
- Configure Enrollment Profiles
- Configure Compliance Policies
- Configure Device Restriction Policies, Update Policies
- Add applications from Volume Purchase Program (VPP) and sync to Intune
- Setup Company Portal
- Deploy apps, app configurations and app protection policies
  
---------------------

# Sunningdale Tech - Windows AutoPilot 

## Project Description
Implemented a Windows Autopilot solution to simplify and automate the provisioning of Windows 10/11 devices for a large-scale corporate environment. The project focused on streamlining the deployment process, reducing IT overhead, and enhancing the end-user experience by enabling ready-to-use devices right out of the box.

## Scope
- Windows 10 and later
  
## Tools and Technology Used
- Microsoft Intune
- Windows Autopilot
- Microsoft Entra (Azure Active Directory)

### Implementation Overview
- Configure Deployment Profiles
- Configure Enrollment Status Page
- Configure Intune Connector for Hybrid Joined Devices
- Configure Policy Sets 
- Contact Vendor for OEM Registration
- Register existing devices to AutoPilot
- Configure Windows Hello for Business
- Configure Seamless SSO for Entra Joined devices to access on-premise resources

---------------------

# Sunningdale Tech - Information Protection & Data Loss Prevention

## Project Description
Designed and implemented a comprehensive Information Protection and Data Loss Prevention (DLP) solution to safeguard sensitive organizational data and prevent unauthorized sharing or leakage. The project focused on classifying and protecting data across Microsoft 365 environments, ensuring compliance with industry regulations, and minimizing risks related to data breaches.

  
## Tools and Technology Used
- Microsoft Purview Information Protection
- Microsoft Purview Data Loss Prevention (DLP)

### Implementation Overview
- Work with business stakeholders for identifying sensitivity labels
- Configure and publish sensitivity labels and policies
- Configure auto labelling for specific Departments / Sites
- Configure data loss prevention policies
- Testing and monitoring
- Configuring alerts and fine tuning of policies
- End-User Enablement (Training and Adoption)

---------------------

# Sunningdale Tech - Power Platform Governance

## Project Description
Implemented a robust Power Platform Governance Framework for Sunningdale Tech using Microsoft’s Center of Excellence (CoE) Starter Kit. The project aimed to enhance visibility, control, and compliance across Power Apps, Power Automate, and other Power Platform components while fostering a culture of innovation and productivity within the organization.

## Tools and Technology Used
- Microsoft Power Platform
- Center of Excellence (CoE) Starter Kit

### Implementation Overview
- Setup and configure Center of Excellence toolkit
- Configure Power BI Dashboards for visibility across power platform environment
- Configure Pipelines, DLP Policies, Conditional access  
- Training session with App Makers regarding Power Platform Governance
- Migrate existing apps from Default Environment to proper environment 

---------------------

# Sunningdale Tech - Security and Compliance

## Project Description
Implemented a comprehensive security and compliance enhancement project to improve the organization’s Microsoft Secure Score and Compliance Score. This initiative focused on strengthening the security posture, ensuring adherence to regulatory requirements, and mitigating risks across Microsoft 365 environments and Azure resources.

## Tools and Technology Used
- Microsoft Purview Compliance Manager (Used SO/IEC 27001:2022 Assessment)
- Microsoft Defender for EndPoint
- Microsoft Defender for Identity
- PowerShell
- Graph API

### Implementation Overview
- Analyze Recommended Actions (Defender Portal - Exposure Management) and Improvement Actions (Purview - Compliance Manager)
- List out 10 to 20 actions and have recurring meeting with respective subject matter experts for deciding which actions to implement, take risk or make exceptions
- Propose remediation actions, deployment rings and roll back plans
- Assign improvement actions to related subject matter experts, upload evidences for actions which require manual testing
- Create device groups in Defender Portal for each Country
- Create remediation actions in Defender Portal to monitor the remediation process
- Deploy improvement actions based on deployment rings
- Monitoring and Rollback if needed
  
---------------------

# Sunningdale Tech - Golden Image for Windows 10

## Project Description
Designed and implemented a Windows 10 Golden Image Deployment solution using Microsoft Deployment Toolkit (MDT) and Windows Deployment Services (WDS). This project aimed to standardize Windows 10 installations across the organization, streamline device provisioning, and ensure consistency in configurations and security compliance.


## Tools and Technology Used
- Microsoft Deployment Toolkit
- Windows Deployment Services
- DHCP Server
- Windows Server


### Implementation Overview
- Install and configure WDS Server
- Prepare Deployment Workbench (Deployment Share, Driver Repository, Selection Profiles, Bootstrap.ini, Boot Images, Win PE drivers, etc)
- Configure DHCP server for PXE boot
- Prepare Reference Image in Hypver-V
- Capture the reference image and put into deployment share
- Import required drivers for each device model
- Configure Task Sequence
- Test Golden Image
- Create Standalone media for flexible OS deployment without PXE
  

---------------------

# Sunningdale Tech - SysAid ITSM

## Project Description
Implemented and customized the SysAid IT Service Management (ITSM) solution to streamline IT operations, enhance service delivery, and improve incident and request management efficiency. The project aimed to align IT processes with business objectives while adhering to ITIL (Information Technology Infrastructure Library) best practices.


## Tools and Technology Used
- SysAid ITSM Solution
- Microsoft Entra ID
- Microsoft Teams Admin Center


### Implementation Overview
- Setup and configure SysAid ITSM Solution
- Configure SSO integration with Microsoft Entra ID
- Configure Categories for Incidents, Tickets and Changes
- Configure Companies and Groups
- Onboard Administrators
- Configure ticket routing
- Deploy SysAid Agent to EndPoints
- Configure Chat Bot and integrate with Microsoft Teams
- Configure Service Catalog
- Configure and customize Self Service Portal for end-users
- Configure knowledge base and FAQs
- Configure workflows for approvals and change management
- List and import CMDB 
---------------------

# Sysnet System and Solutions - Infrastructure migration (For one of the Financial Companies in Singapore)

## Project Description
Executed a large-scale infrastructure migration project to modernize IT systems, improve performance, and ensure scalability. The scope included migrating Active Directory (AD), DFS File Share, Exchange Server, and SQL Server to newer platforms, minimizing downtime and ensuring seamless user experience.


## Tools and Technology Used
- Microsoft Active Directory
- DFS File Server with Kemp Load Balancer
- Microsoft Exchange Server
- Microsoft SQL Server
- Windows Server Failover Cluster


### Implementation Overview (Active Directory)
- Perform health check for existing environment
- Propose migration and upgrade plan to customer
- Adding additional domain controllers
- Transfer FSMO roles
- Decommission of old domain controllers and objects
- Upgrade Forest and Domain functional levels
- Monitoring and Support

  ### Implementation Overview (Exchange Server 2013 to 2019)
- Perform health check for existing environment
- Propose migration and upgrade plan to customer
- Install Latest CU for existing Exchange Servers
- Prepare active directory environment
- Install and Configure new Exchange Server 2019
- Configure Virtual Directories, Database Availability Group, Connetors, etc
- Migrate exchange certificates to new Exchange Server
- Configure mailflow for new exchange servers
- Migrate Mailboxes
- Test mailflow and High Availability 
- Decommision of old Exchange 2013 Servers
- Renew Exchange Server Certificate

### Implementation Overview (File Server with DFS)
- Perform health check for existing environment
- Propose migration and upgrade plan
- Install and configure new DFS servers
- Work with network team in configuring Kemp Load Balancer for DFS Server
- Configure DFS Namespace
- Schedule data transfer from existing DFS server to new Servers using robocopy
- Verify all data are migrated to new DFS Servers (Used WinMerge tool to compare two DFS Servers)
- Test High Availability and Load Balancing
- Cutover and cleanup for old DFS Servers

### Implementation Overview (Microsoft SQL Server)
- Perform health check for existing environment
- Propose migration and upgrade plan
- Install and configure new SQL Servers
- Configure Windows Server Failover Cluster
- Configure SQL Server Always On Availability
- Perform Database Migration
- Testing and Validation
- Decommission of old SQL Servers

---------------------









