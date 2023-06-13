<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04
- MAC OS 

<h2>High-Level Steps</h2>

- Create a Resource Group
- Create a Windows 10 Virtual Machine 
- Create a Linux (Ubuntu)
- Observe ICMP Traffic 
- Observe SSH Traffic
- Observe DHCP Traffic 
- Observe DNS Traffic
- Observe RDP Traffic 

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create a resource group in Azure, sign in to the Azure portal, navigate to the Resource Groups page, click on "Add," provide the basic details such as subscription, resource group name, and region, click on "Review + create," and then click on "Create" to create the resource group. Once created, you can start adding Azure resources to the resource group for better organization and management.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When creating a Windows 10 virtual machine in Azure, follow these steps. First, sign in to the Azure portal using your credentials. Then, navigate to the "Virtual machines" page. Click on "Add" to start creating a new virtual machine. In the Basics tab, provide details such as subscription, resource group, virtual machine name, region, and availability options. Choose the appropriate image for Windows 10, select the desired size, and configure the administrative account credentials. In the Networking tab, set up the virtual network, subnet, and public IP settings. Proceed to the Management and Advanced tabs to configure additional options if needed. Finally, review the settings and click on "Review + create." Once the validation passes, click on "Create" to deploy the Windows 10 virtual machine. Azure will start provisioning the resources, and you can monitor the progress from the portal. After the deployment is complete, you can connect to your Windows 10 virtual machine and start utilizing it for your desired purposes.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to the "Virtual machines" page and click on "Add" to initiate the creation process. In the Basics tab, provide details such as subscription, resource group, virtual machine name, region, and availability options. Choose the desired Ubuntu image from the Azure Marketplace, select the appropriate size, and configure the administrative account credentials. In the Networking tab, set up the virtual network, subnet, and public IP settings. Proceed to the Management and Advanced tabs to configure additional options if needed. Review the settings and click on "Review + create." Once the validation passes, click on "Create" to start the deployment of the Ubuntu virtual machine. Azure will begin provisioning the necessary resources, and you can monitor the progress from the portal. Once the deployment is complete, you can connect to your Ubuntu virtual machine and start utilizing it for your desired purpose.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
ICMP Traffic 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SSH Traffic 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
DHCP Traffic 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
DNS Traffic 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 RDP Traffic 
</p>
<br />
