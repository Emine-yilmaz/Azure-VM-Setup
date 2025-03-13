# Azure-VM-Setup
Azure Virtual Machine Setup (Free Account)
This guide explains how to create a basic Windows Server Virtual Machine (VM) using a free Azure account.

🛠 Steps
## Create a Resource Group
Go to Resource Groups in the Azure Portal.
Create a new Resource Group (e.g., MyResourceGroup).
![Creating a research group](https://github.com/Emine-yilmaz/Azure-VM-Setup/blob/main/researchgroup.png)
## Set Up a Virtual Network (VNet)
Go to Virtual Networks and create a new network.
Configure it with a default subnet.
![set up a virtual network](https://github.com/Emine-yilmaz/Azure-VM-Setup/blob/main/virtualnetwork.png)
# Deploy a Windows Virtual Machine
Go to Virtual Machines → Create → Azure Virtual Machine.
Choose a free-tier eligible Windows Server.
Enable Public IP for RDP access.
Place the VM in the previously created VNet.
![Linux virtual machine](https://github.com/Emine-yilmaz/Azure-VM-Setup/blob/main/vm-linux.png)
# Attach a Data Disk
While the VM is running, go to the Disks tab.
Add a new data disk and save the changes.
![Data Disk](https://github.com/Emine-yilmaz/Azure-VM-Setup/blob/main/disk.png)
# Connect via RDP
Copy the VM’s Public IP Address.
Use Remote Desktop (RDP) to connect and log in.

![connected via RDP](https://github.com/Emine-yilmaz/Azure-VM-Setup/blob/main/connectRDP.png)
# (Optional) Clean Up Resources
Delete the Resource Group to remove all resources.
# Notes
Make sure to stay within the free-tier to avoid charges!
Use strong passwords for security.
Shut down the VM when not in use to prevent unnecessary costs.
