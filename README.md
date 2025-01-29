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

- Set Up A domain controller 
- Connect new PC to the Domain Controller
- Create 10000 Users
- Practice Logging into new users
- Dealing with Account Lockouts + Disabling and Enabling users + Observing Logs

<h2>Deployment and Configuration Steps</h2>

<p>
  <img width="1440" alt="Client 1 DNS change to Domain " src="https://github.com/user-attachments/assets/08070ed8-658d-4027-a8a6-8511be290c17" />
</p>
<p>
After creating the domain controller (DC) we must make sure its private IP address is static and doesn't change. This screenshot shows the process of changing a client's Domain Name System address to our domain controller's private IP address to allow all searches to go through our DC. We then Initiate Active Directory services on the Domain Controller allowing it to activate with the client's PC also being able to access it.
</p>
<br />

<p>
<img width="1244" alt="Connecting client one to new active directory domain" src="https://github.com/user-attachments/assets/64226bef-1b21-4b91-948d-44d2bd24cb73" />
</p>
<p>
To officially connect the new client to the active directories domain, we need to ask the domain if we can join it and then properly join with an admin's login. Where after a short restart we will officially be part of the Active Directories domain allowing us to configure permissions and policies concerning accounts on the domain.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
