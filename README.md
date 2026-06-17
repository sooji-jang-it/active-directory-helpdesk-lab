# Active Directory Helpdesk Lab

## Overview
Active Directory home lab simulating a corporate Windows Server environment with a domain controller, user and group management, security groups, file sharing, and access control.

## Purpose
To practice real-world IT helpdesk and system administration skills in a controlled environment.

## Skills Covered
- Active Directory Domain Services (AD DS)
- User and Group Management
- Security Groups and Permissions
- File Sharing and Access Control
- Basic Windows Server administration

## Environment
- Windows Server (Domain Controller)
- Windows Client VM (Windows 10/11)

## Status
In Progress

## Lab Steps

### 1. Environment Setup
- Installed Windows Server (Domain Controller)
- Installed Windows 10/11 Client VM
- Configured both machines on the same network

### 2. Active Directory Installation
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created new forest: `corp.local`

### 3. User & Group Management
- Created multiple user accounts in Active Directory Users and Computers (ADUC)
- Created security groups for departments (IT, HR, Finance)
- Assigned users to appropriate groups

### 4. File Sharing & Permissions
- Created shared folder on server
- Configured NTFS permissions
- Tested access control using different user accounts
