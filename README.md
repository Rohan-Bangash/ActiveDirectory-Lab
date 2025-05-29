# ActiveDirectory-Lab
Screenshots from my Virtual Active Directory lab environment.

# IT Virtual Lab Environment Project

## Overview

This project simulates a real-world enterprise IT environment using Oracle VirtualBox. It includes a **Windows Server 2019 Domain Controller** and a **Windows 10 Helpdesk Client**, both configured in a domain-based network. The lab demonstrates hands-on IT administration tasks such as user and group management, Active Directory structuring, and Group Policy changes — all commonly handled in helpdesk and sysadmin roles.

---

## Environment Details

- **Virtualization Tool:** Oracle VirtualBox
- **Server VM:** Windows Server 2019 (Domain Controller)
- **Client VM:** Windows 10 (joined to domain)
- **Domain Name:** `rohan.org`
- **Use Case:** Emulating a small business IT environment with centralized user management and desktop support.

---

## Key Tasks Performed

- Set up and configured a **Windows Server 2019 Domain Controller**
- Joined a **Windows 10 client machine** to the domain
- Created multiple **Organizational Units (OUs)** for departments: Sales, Marketing, Engineering, and Human Resources
- Created new **Active Directory users**, assigned them to groups, and set temporary passwords with forced resets
- Created a new **HR security group**, added users, and moved the group to the HR OU
- Opened **Group Policy Management Editor** and updated the domain-wide password policy (minimum password length from 7 to 8 characters)

---

## Screenshot Walkthrough

Each screenshot demonstrates key actions and configurations from the project.

## Screenshot Walkthrough

| Screenshot File                          | Description                                                                |
|------------------------------------------|----------------------------------------------------------------------------|
| 01-virtual machines.png                  | Overview of the VirtualBox environment showing all VMs.                    |
| 02-DC lockscreen.png                     | Lock screen of the Domain Controller (DC) VM.                              |
| 03-DC home screen.png                    | Logged-in desktop of the Domain Controller.                                |
| 04-DC tools.png                          | Administrative tools view on the DC.                                       |
| 05-DC - Computers.png                    | 'Computers' container in Active Directory Users and Computers (ADUC).      |
| 06-DC - Users.png                        | Viewing the 'Users' container in ADUC.                                     |
| 07-DC - SalesOU.png                      | Custom 'Sales' Organizational Unit created in ADUC.                        |
| 08-DC - create a new user.png            | Creating a new user within an OU.                                          |
| 09-DC - create users password.png        | Setting a temporary password and requiring change on next login.           |
| 10-DC - create a new user 2.png          | Confirmation of new user creation.                                         |
| 11-DC - add a member to a group.png      | Starting the process to add a user to a group.                             |
| 12-DC - add a member to a group 2.png    | Searching for the user (Hector).                                           |
| 13-DC - add a member to a group 3.png    | Selecting the user (Hector).                                               |
| 14-DC - add a member to a group 4.png    | Finalizing adding the user to the group.                                   |
| 15-DC - create a new group.png           | Creating a new group named "Human Resources".                              |
| 16-DC - move HR group to OU.png          | Moving the HR group into its appropriate OU.                               |
| 17-DC - create human resources OU.png    | Creating the new Human Resources Organizational Unit.                      |
| 18-DC - move HR group to OU 2.png        | Continued step of moving HR group into the HR OU.                          |
| 19-DC - move HR group to OU 3.png        | Final view of HR group inside HR OU.                                       |
| 20-group policy - password policy.png    | Viewing default password policy settings.                                  |
| 21-DC - Group Policy Management.png      | Group Policy Management Console opened.                                    |
| 22-DC - Group Policy Management 2.png    | Viewing the Default Domain Policy.                                         |
| 23-DC - Group Policy Management 3.png    | Viewing the Password Policy.                                               |
| 24-DC - Group Policy Management 4.png    | Navigating password policy section.                                        |
| 25-DC - Group Policy Management 5.png    | Checking the minimum password length (currently set to 7 characters)       |
| 26-DC - Group Policy Management 6.png    | Adjusting minimum password length from 7 to 8 characters.                  |

---

## Why This Project Matters

This lab shows not just familiarity with Windows Server, but actual practice with:
- **User lifecycle management**
- **Group and OU structuring for scalability**
- **Policy enforcement via GPO**
- **Simulating IT support tasks**

It proves readiness for Tier 1/Tier 2 support and system administration work.

---

## How This Was Built

- Oracle VirtualBox to host VMs
- Internal networking configuration (NAT/Host-only Adapter)
- Manual installation of Windows ISOs
- Configuration of Active Directory, DNS, DHCP, and client joining
- Screenshots taken during live configuration sessions

---

## Future Enhancements

- Add PowerShell scripting for automation tasks
- Configure roaming profiles or folder redirection
- Set up WSUS or SCCM for patch management simulation

---

## Author

**Rohan Bangash**  
Recent IT graduate | Aspiring Helpdesk & Sysadmin Pro  
GitHub: [github.com/Rohan-Bangash](https://github.com/Rohan-Bangash)




