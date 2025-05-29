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

| # | File Name | Description |
|---|-----------|-------------|
| 1 | `virtual machines.png` | Oracle VirtualBox showing both VMs: Domain Controller and Helpdesk Client |
| 2 | `DC lockscreen.png` | Lock screen of the Domain Controller |
| 3 | `DC home screen.png` | Desktop of the Domain Controller with system tools visible |
| 4 | `DC tools.png` | Core tools open: Active Directory Users and Computers, Group Policy Editor |
| 5 | `DC - Computers.png` | Domain-joined machines visible in the `Computers` container |
| 6 | `DC - OUs.png` | Custom Organizational Units (OUs) for Sales, Marketing, Engineering, HR |
| 7 | `DC - New user.png` | Created a new domain user with temporary password settings |
| 8 | `DC - User in group.png` | Added the new user to a specific group |
| 9 | `DC - New HR group.png` | Created a new security group for HR department |
|10 | `DC - HR group moved.png` | Moved the HR group to the HR Organizational Unit |
|11 | `DC - Group policy editor.png` | Navigated to Group Policy Management Editor |
|12 | `DC - Password policy change.png` | Updated password policy from 7 to 8 characters minimum |

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




