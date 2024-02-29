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

- Logging into OsTicket
- Setup and Configuration

  
  

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/JNmMLwR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For now we'll get to running osTicket. 
  However, you will need to : 
  Open Heidi SQL
Create a new session, root/Password1
Connect to the session
Create a database called “osTicket”

Continue Setting up osticket in the browser
MySQL Database: osTicket
MySQL Username: root
MySQL Password: Password1
Click “Install Now!”
Use this link to get to osTicket http://localhost/osTicket/scp/login.php

<br />

<p>
<img src="https://imgur.com/HeBssxs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You can configure Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin


<br />

<p>
<img src="https://imgur.com/beagSMS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments
Admin Panel -> Agents -> Departments
System Administrators

<br />


<p>
<img src="https://imgur.com/ub9uJqh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support


<br />



<p>
<img src="https://imgur.com/zqHh3Wz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John



<br />



<p>
<img src="https://imgur.com/qbIS4Dq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken


<br />



<p>
<img src="https://imgur.com/nj0HytB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)


<br />



<p>
<img src="https://imgur.com/MW419YK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset



<br />





