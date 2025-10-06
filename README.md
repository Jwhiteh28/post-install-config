<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial explains the steps for post-install setup of the osTicket help desk platform.<br />


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
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<p align="center">
<h1>Configuration Roles</h1>
</p>

<strong>Admin Panel > Agents > Roles</strong>
<br />

<p>
- Here I created and define my own role in this example.
<img src="https://i.imgur.com/FWgxxdV.png" width="600" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/feiJDXI.png" width="600" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/pIu2VTD.png" width="600" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/gsDobYL.png" width="600" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/eR3Z0Bc.png" width="600" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
  <h1>Configure Departments</h1>
</p>

<strong>Admin Panel > Agents > Departments</strong>
<p>
System Administrators:
</p>
<br />
<p>
- Add a New Department
<img src="https://i.imgur.com/aVMeqIJ.png" width="600" alt="Disk Sanitization Steps"/>
<p>
  Click "Create Dept"
</p>
</p>
<br />

<p align="center">
  <h1>Configure Teams</h1>
</p>

<strong>Admin Panel > Agents > Teams</strong>
<p>
Online Banking:
</p>
<br />
<p>
  Teams is when you want to create a group of people who are from different departments. In this example, Online Banking
</p>
<p>
<img src="https://i.imgur.com/Bn83uzQ.png" width="600" alt="Disk Sanitization Steps"/>
</p>
<br />

<p align="center">
  <h1>Allow anyone to create a ticket</h1>
</p>

<strong>Admin Panel > Settings > User Settings</strong>
<p>
  Make sure "Require registration and login to create tickets" is NOT selected:
</p>
<br />
<p>
  <img src="https://i.imgur.com/hOtxnPp.png" width="600" alt="Disk Sanitization Steps"/>
</p>

<p align="center">
  <h1>Configure Agents (employees)</h1>
</p>

<strong>Admin Panel > Agents > Add New</strong>
<p>
  
</p>
<br />
<p>
  <img src="https://i.imgur.com/9tudr8k.png" width="600" alt="Disk Sanitization Steps"/>
</p>
<p>
  John Doe:
  <img src="https://i.imgur.com/jOWxskB.png" width="600" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/VABZ8p8.png" width="600" alt="Disk Sanitization Steps"/>
  <p>
    Both agents have all access but Patrick is in support and John is in Online Banking
  </p>
</p>
<br />

<p align="center">
  <h1>Configure End Users (customers)</h1>
</p>


<strong>Agent Panel > Users > Add New</strong>
<p>
Kyle (end user):
</p>
<br />
<p>
  <img src="https://i.imgur.com/l8Zw848.png" width="600" alt="Disk Sanitization Steps"/>
</p>
<p>
  Repeat this step for any internal end users
</p>
<br />
