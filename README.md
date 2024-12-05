<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Install Active Directory
- Create a Domain Admin user within the domain
- Join Client-1 to domain
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/PeDzcdm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating the Domain Controller and setting up a client PC, I logged into the DC and installed the Active Directory Domain Services. After which, I promoted it as a DC by setting up a new forest.
</p>
<br />

<p>
<img src="https://i.imgur.com/7fBzax6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Active Directory User and Computers, I created 2 Organizational Units named "_EMPLOYEES" and "_ADMINS". I then added a user to the Domain Admins, setting a username and password and adding the user to the domain's security group.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
