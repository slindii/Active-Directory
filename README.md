# Active-Directory Lab
## Overview
This project involved setting up an Active Directory server for SAM Company with four branches. The goal was to centralize user management, enforce department-specific policies, and ensure secure network operations.

## Objectives
- Set up and configure an Active Directory (AD) server the SAM company.
- Manage user accounts and departmental access across four branches.
- Implement server administration policies (folder permissions, Run command restrictions, disk quotas).
- Ensure secure and efficient network connectivity between branches.

## Skills Learned
- Installing and configuring Active Directory.
- Creating and managing user accounts and groups.
- Applying Group Policy Objects (GPOs) to enforce department-specific rules.
- Setting up shared folders with controlled access.
- Using PowerShell commands alongside GUI for server tasks.
- Configuring remote access and disk quotas.

## Tools Used
- Windows Server 2019 (GUI + PowerShell)
- Active Directory Domain Services (AD DS)
- Group Policy Management
- Remote Desktop Services
- Disk Management & Quotas
- Subnetting 

## Steps
- Installed Windows Server 2019 and enabled Active Directory Domain Services.
- Created organizational units (OUs) for each department.
- Configured user accounts with login credentials for each department.
- Set up shared folders with restricted access (department-only + IT full access).
- Applied Group Policy to disable the “Run” function for some departments.
- Enabled IT privileges
- Deployed servers, images, and apps automatically to client machines.
- Documented the network layout and subnetting plan (Class C range).
- Recorded PowerShell commands used for each task as reference.

<img width="900" height="500" alt="image" src="https://github.com/user-attachments/assets/417a87a5-d1a6-48bd-8f96-4655e12f6778" />


## Reflection  
Working on this project was my first experience setting up and managing an Active Directory server. I learned how to create and organize user accounts, apply group policies, and configure departmental access in a real-world scenario. It taught me the importance of planning network structures, documenting processes, and balancing GUI with PowerShell for efficiency. Most importantly, I gained confidence in server administration and problem-solving, which I can now apply to future IT projects.

#### The lab was set up on a virtualbox.
