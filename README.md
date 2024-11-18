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
- Create device groups in Defender Portal for each Country
- Create remediation actions in Defender Portal to monitor the remediation process
- Deploy improvement actions based on deployment rings
- Monitoring and Rollback if needed
- For compliance score, Assign improvement actions to related subject matter experts, upload evidences for actions which require manual testing












