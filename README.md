<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

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


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/PeDzcdm.png" height="80%" width="80%" alt="Installing the Active Directory Domain Services"/>
</p>
<p>
After creating the Domain Controller and setting up a client PC, I logged into the DC and installed the Active Directory Domain Services. After which, I promoted it as a DC by setting up a new forest.
</p>
<br />

<p>
<img src="https://i.imgur.com/7fBzax6.png" height="80%" width="80%" alt="Creating Organizational Units"/>
</p>
<p>
In Active Directory User and Computers, I created 2 Organizational Units named "_EMPLOYEES" and "_ADMINS". I then added a user to the Domain Admins, setting a username and password and adding the user to the domain's security group.
</p>
<br />

<p>
<img src="https://i.imgur.com/4UuI2n3.png" height="80%" width="80%" alt="Joining the Client VM"/>
  <img src="https://i.imgur.com/x2pgDkx.png" height="80%" width="80%" alt="Verifying"/>
</p>
<p>
I logged into the Client VM and joined it to the domain controller then verified that it was in the Active Directory Domain Users and Computers.
</p>
<br />
