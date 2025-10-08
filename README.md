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

<img width="2137" height="1269" alt="Image" src="https://github.com/user-attachments/assets/a0922c2d-5313-44d5-b519-a7f8aecbb72b" />
<img width="1896" height="825" alt="Image" src="https://github.com/user-attachments/assets/6814c192-fcc7-4a76-bbfa-a5520fd71c9f" />
<img width="1025" height="767" alt="Image" src="https://github.com/user-attachments/assets/10f263fb-5218-48b5-885a-13481b2afe5b" />


---

# 💡 Lessons Learned

-Gained hands-on experience in Windows Server 2025 administration, including Active Directory setup, domain joining, and network service configuration.

-Developed proficiency in PowerShell scripting for automating bulk user account creation and management.

-Learned to handle organizational units (OUs), group assignments, and CSV data import effectively.

-Practiced configuring DNS, DHCP, and NAT in a virtualized environment to simulate enterprise-level networks.

-Improved skills in documentation, planning, and reproducing IT workflows in a home lab setting.

# 🧩 🧠 Issue Summary

While setting up Windows 11 in Oracle VirtualBox, two main issues were encountered during installation and initial configuration. Both required manual workarounds to successfully complete setup and boot into the operating system.

- ⚙️ Issue 1 — Secure Boot and TPM Compatibility

Windows 11 requires Secure Boot and TPM 2.0 to be enabled; however, enabling these options in the VirtualBox environment caused the operating system to fail to boot.
Resolution: The issue was resolved by disabling Secure Boot and TPM in the virtual machine settings, then applying a registry modification (regedit) during installation to bypass the TPM 2.0 and Secure Boot checks. After this adjustment, Windows 11 installed and booted successfully.

- 🌐 Issue 2 — Network Connection During OOBE Setup

During the Out-of-Box Experience (OOBE) setup, Windows 11 displayed the “Let’s connect you to a network” screen with no available network options.
Resolution: To continue the installation without a network, the OOBE\BYPASSNRO command was used, which enabled the “I don’t have internet” option. This allowed setup to complete successfully without joining a network initially.

- ✅ Outcome

After applying both workarounds, Windows 11 was installed and fully operational within VirtualBox. These steps demonstrate the ability to identify, troubleshoot, and resolve common virtualization and configuration challenges.

# 🧾 Related Skills

This project demonstrates hands-on experience with the following skills and technologies:

Windows Server 2025 – Domain Controller and client configuration

Active Directory – User creation, Organizational Units (OUs), group assignments

PowerShell – Automation scripting for account management

Networking & Domain Services – DNS, DHCP, NAT configuration

Virtualization – Oracle VirtualBox home lab setup

IT Workflow & Automation – Planning, executing, and documenting real-world IT administrative tasks

---

# 🔗 References

Microsoft Docs: Active Directory PowerShell Module

Oracle VirtualBox Documentation: VirtualBox Official Guide
