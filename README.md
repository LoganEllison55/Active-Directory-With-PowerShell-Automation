# Active-Directory-With-PowerShell-Automation
The purpose of this project was to design and deploy a complete Windows domain environment from scratch, featuring automated user account creation through PowerShell scripting. The environment includes configuration of DNS, DHCP, and NAT services, as well as domain joining of client systems — all built and tested within a virtualized home lab setup to simulate real-world IT administrative tasks.

---

# 🎯 Purpose & Goals

The goal of this project was to gain hands-on experience building and managing a Windows Server domain environment from the ground up. This included practicing real-world IT administrative tasks such as domain configuration, user management, and network service deployment.

Key objectives:

-Develop and automate user account provisioning with PowerShell scripting.

-Configure and manage core network services including DNS, DHCP, and NAT.

-Simulate enterprise-level infrastructure within a virtualized home lab environment using Oracle VirtualBox.

-Strengthen practical skills in system administration, automation, and Active Directory management.

---

# ⚙️ Tools & Technologies Used

This project leverages a range of IT tools and technologies to simulate real-world system administration and automation workflows:

-Operating System: Windows Server 2025 (Domain Controller & Client Systems)

-Scripting & Automation: PowerShell (user account creation, group assignments, OU management)

-Virtualization: Oracle VirtualBox (for creating a full home lab environment)

-Networking & Domain Services: DNS, DHCP, NAT configuration, domain joining

-Directory & User Management: Active Directory, Organizational Units (OUs), group policies

---

# 🧩 Project Setup / Steps

Follow these steps to reproduce the Windows Server 2025 Home Lab environment and automation workflow:

1. Set up the virtual environment:

  -Install Oracle VirtualBox and create virtual machines for the Windows Server 2025 Domain Controller and client systems.

2. Configure Windows Server 2025 as a Domain Controller:

  -Install Active Directory Domain Services (AD DS).

  -Set up the domain and organizational structure (OUs) for testing user account management.

3. Configure core network services:

  -Set up DNS, DHCP, and NAT to enable proper network communication between domain controller and client VMs.

4. Prepare user data:

  -Create a CSV file containing the user information (name, username, group assignments, etc.) for bulk account creation.

5. Automate user creation:

  -Run the PowerShell script to import the CSV file and automatically create Active Directory user accounts.

  -Assign users to the correct OUs and groups as specified in the CSV.

6. Verify accounts and domain functionality:

  -Check that all users are created correctly in Active Directory.

  -Ensure that client systems can join the domain and authenticate properly.

---

# 🧠 Features / What It Does

-Automates bulk user account creation in Active Directory using PowerShell and CSV input.

-Assigns users to the appropriate Organizational Units (OUs) and groups automatically.

-Configures a full Windows Server 2025 domain environment with DNS, DHCP, and NAT services.

-Simulates real-world IT administrative tasks, including domain joining of client systems.

-Provides a virtualized home lab for testing and learning enterprise network and system administration skills.

---
📸 Screenshots / Visuals
(Work In Progress)
---

# 🧩 Lessons Learned / Challenges

-Gained hands-on experience in Windows Server 2025 administration, including Active Directory setup, domain joining, and network service configuration.

-Developed proficiency in PowerShell scripting for automating bulk user account creation and management.

-Learned to handle organizational units (OUs), group assignments, and CSV data import effectively.

-Practiced configuring DNS, DHCP, and NAT in a virtualized environment to simulate enterprise-level networks.

-Improved skills in documentation, planning, and reproducing IT workflows in a home lab setting.

# 🧾 Related Skills

This project demonstrates hands-on experience with the following skills and technologies:

Windows Server 2025 – Domain Controller and client configuration

Active Directory – User creation, Organizational Units (OUs), group assignments

PowerShell – Automation scripting for account management

Networking & Domain Services – DNS, DHCP, NAT configuration

Virtualization – Oracle VirtualBox home lab setup

IT Workflow & Automation – Planning, executing, and documenting real-world IT administrative tasks

---

# 🔗 References / Credits (Optional)

Microsoft Docs: Active Directory PowerShell Module

Oracle VirtualBox Documentation: VirtualBox Official Guide

All work in this project was completed independently as a hands-on learning and portfolio development exercise.
