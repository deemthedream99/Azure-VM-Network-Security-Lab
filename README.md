# Virtual Machine Network Security Lab

## Overview
This lab demonstrates how to set up and analyze network traffic between virtual machines (VMs) in Microsoft Azure. It covers creating Windows and Linux VMs, capturing and analyzing network traffic using Wireshark, and configuring Network Security Groups (NSGs) to control traffic flow.
## Components
- Azure Resource Group – Manages all resources in the lab.
- Windows 10 VM – Used for remote access, network monitoring, and testing.
- Ubuntu (Linux) VM – Acts as a target system for networking experiments.
- Azure Virtual Network (VNet) & Subnet – Ensures both VMs communicate on the same private network.
- Wireshark – Used to capture and analyze ICMP, SSH, DHCP, DNS, and RDP traffic.
- Network Security Group (NSG) – Controls inbound and outbound traffic to the Ubuntu VM.

## Steps Taken
1. Logged into [Azure Portal](https://portal.azure.com/#home).
2. Created a Resource Group for managing lab resources.
3. Created a Windows 10 Virtual Machine (VM):
  - Assigned it to the previously created Resource Group.
  - Allowed Azure to create a new Virtual Network (VNet) and Subnet.
4. Created a Linux (Ubuntu) Virtual Machine:
  - Assigned it to the same Resource Group and Virtual Network as the Windows VM.
  - Chose Username/Password for authentication.
5. Verified that both VMs are in the same VNet/Subnet.

## Verification Screenshots
![Users and Computers](https://github.com/deemthedream99/Active-Directory-VirtualBox-Lab/blob/main/Users%20and%20Computers.png?raw=true) 
![Computer Description](https://github.com/deemthedream99/Active-Directory-VirtualBox-Lab/blob/main/Computer%20Description.png?raw=true)
![Windows 10](https://github.com/deemthedream99/Active-Directory-VirtualBox-Lab/blob/main/Windows%2010.png?raw=true)
