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
![Step 1](https://github.com/user-attachments/assets/9ab2b742-2753-4ec0-b6c0-e45ae58a4680)
![Step 2](https://github.com/user-attachments/assets/a8992442-6c10-4351-8936-64b2b0d50754)
![Step 3](https://github.com/user-attachments/assets/22900e1c-a495-48dc-8498-aa6500e55d1a)
![Step 4A](https://github.com/user-attachments/assets/84d764da-c370-45af-b7dc-892cbd888ab0)
![Step 4B](https://github.com/user-attachments/assets/d041e3f0-aaee-4ad8-9b5d-effd3f1b0d13)

