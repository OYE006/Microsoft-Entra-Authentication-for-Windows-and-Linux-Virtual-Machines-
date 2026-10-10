# Microsoft-Entra-Authentication-for-Windows-and-Linux-Virtual-Machines(VM)

Scenario:

The company has decided that Microsoft Entra ID should be used to login to virtual machines for remote access. This lab will show how this can be setup for Windows and Linux virtual machines.

## Login to Windows Virtual Machines in Azure with Microsoft Entra ID

### Create a Windows Virtual Machine with Microsoft Entra ID login enabled

  - Go to the Azure portal at: https://portal.azure.com
  - Select + Create a resource.

    <img width="758" height="287" alt="image" src="https://github.com/user-attachments/assets/12fd3491-e096-4ba0-98c5-d914085589ad" />

  - Type Windows 11 in the Marketplace search bar, then Enter.
  - Find the Microsoft Windows 11 box, then select the Create and choose Windows 11 Enterprise, version 25H2 from the menu that opens.
  - Create the VM with the necessary information which include Subscription type, Resource Group, Virtual machine name, Region, Availability options, Security Type, Size, setting Username
    and Password and Confirming you have a license
    
    <img width="780" height="419" alt="image" src="https://github.com/user-attachments/assets/d66596b6-531c-4d06-80d5-90c628dc7272" />

  - On the Management tab, under Microsoft Entra ID section, select the Login with Microsoft Entra ID checkbox.
