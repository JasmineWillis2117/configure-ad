<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>
  </p>
<br />


<h1>On-premises Active Directory Deployed in the Cloud (Azure) (In progress of completion)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />
  </p>
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

  </p>
<br />

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
  
    </p>
<br />

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup Domain Controller in Azure
- Setup Client-1 in Azure
- Install Active Directory
- Join Client-1 to your domain
- Setup Remote Desktop for non-administrative users on Client-1
- Create a bunch of additional users and attempt to log into client-1 with one of the users

  </p>
<br />

Bonus: 
- Dealing with Account Lockouts (Step-by-step) 
- Enabling and Disabling Accounts
- Observing Logs

    </p>
<br />


<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
  Dealing with Account Lockouts (Step-by-step)
  
- Get logged into dc-1, Selcet user acount to unlock 
- Observe that the account has been locked out within Active Directory
- Unlock the account, Reset the password, Attempt to login with it
</p>
<br />
