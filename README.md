<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users
- Configure SLA's
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Go to http://localhost/osTicket/scp/login.php
</p>
<p>
<img src="https://i.imgur.com/9CdRWkX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Log in with username and password created during osTicket setup.
</p>
<p>
<img src="https://i.imgur.com/rMLsHyW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h3>Configure Roles</h3>

<p>
Go to Admin Panel
</p>
<p>
<img src="https://i.imgur.com/PTrHaYo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Select Agents
</p>
<p>
<img src="https://i.imgur.com/BOcqq5Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Select Roles -> Add New Role
</p>
<p>
<img src="https://i.imgur.com/X6zNPcl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Add Role title and notes if needed
</p>
<p>
<img src="https://i.imgur.com/Gyu2lJC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Set permissions under Permission tab then Add Role (or Save Changes)
</p>
<p>
<img src="https://i.imgur.com/TmTV41C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>Configure Departments</h3>

<p>
In Admin Panel under Agents, click on Departments (next to Roles)
</p>
<p>
<img src="https://i.imgur.com/wHDHAoX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Click Add New Department and define department name and other information/settings then click Create Dept
</p>
<p>
<img src="https://i.imgur.com/OpuWNaf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>Configure Teams</h3>

<p>
In Admin Panel under Agents, click on Teams (next to Roles)
</p>
<p>
<img src="https://i.imgur.com/YimmoHb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Click Add New Team and define team information 
</p>
<p>
<img src="https://i.imgur.com/2Y4r9fN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Select Members and asigns agents if needed then click Create Team
</p>
<p>
<img src="https://i.imgur.com/t3jmACC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>Allow anyone to create tickets</h3>

<p>
In Admin Panel click Settings then Users and ensure Registration Required checkbox is unchecked
</p>
<p>
<img src="https://i.imgur.com/gVOVZw7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>Configure Agents</h3>

<p>
In Admin Panel click Agents then Add New Agent
</p>
<p>
<img src="https://i.imgur.com/PIW8sBA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Enter agents information
</p>
<p>
<img src="https://i.imgur.com/xVOJ8ZA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Assign agent access (department/s and role/s)
</p>
<p>
<img src="https://i.imgur.com/j5oHS95.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Assign agent permissions
</p>
<p>
<img src="https://i.imgur.com/0SJwpAU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Assign agent to a team then click Create
</p>
<p>
<img src="https://i.imgur.com/Zk4I6nP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>Configure Users</h3>

<p>
Go to Agent Panel
</p>
<p>
<img src="https://i.imgur.com/ZSRp9k1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Click Users
</p>
<p>
<img src="https://i.imgur.com/ocmcFSq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Click Add User and fill in information then click Add User
</p>
<p>
<img src="https://i.imgur.com/k0wPCRc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>Configure SLA's</h3>

<p>
Go to Admin Panel then click Manage
</p>
<p>
<img src="https://i.imgur.com/QhVGSN9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Click SLA then Add New SLA Plan
</p>
<p>
<img src="https://i.imgur.com/sXiMVpe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Define SLA then click Add Plan
</p>
<p>
<img src="https://i.imgur.com/nxhH4gX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>Configure Help Topics</h3>

<p>
In Admin Panel click Manage then Help Topics
</p>
<p>
<img src="https://i.imgur.com/hg9JtNr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Click Add New Help Topic and add details then click Add Topic
</p>
<p>
<img src="https://i.imgur.com/cP3RE52.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h3>osTicket Documentation</h3>

<p>
Any extra informatio needed can be found at https://docs.osticket.com/en/latest/
</p>
<p>
<img src="https://i.imgur.com/UBRcc5A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
