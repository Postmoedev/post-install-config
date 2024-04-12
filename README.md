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

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow Ticket Creation
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3>Configure Roles</h3>
- <b>Navigate to Admin Panel -> Agents -> Roles</b>
- <b>Create "Supreme Admin" role</b>

<h3>Configure Departments</h3>
- <b>Navigate to Admin Panel -> Agents -> Departments</b>
- <b>Create "System Administrators" department</b>

<h3>Configure Teams</h3>
- <b>Navigate to Admin Panel -> Agents -> Teams</b>
- <b>Create "Level I Support" and "Level II Support" teams</b>

<h3>Allow Ticket Creation</h3>
- <b>Navigate to Admin Panel -> Settings -> User Settings</b>
- <b>Uncheck "Require registration and login to create tickets"</b>

<h3>Configure Agents (workers)</h3>
- <b>Navigate to Admin Panel -> Agents -> Add New</b>
- <b>Add agents: Jane and John</b>

<h3>Configure Users (customers)</h3>
- <b>Navigate to Agent Panel -> Users -> Add New</b>
- <b>Add users: Karen and Ken</b>

<h3>Configure SLA</h3>
- <b>Navigate to Admin Panel -> Manage -> SLA</b>
- <b>Set SLA levels:
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)</b>

<h3>Configure Help Topics</h3>
- <b>Navigate to Admin Panel -> Manage -> Help Topics</b>
- <b>Create help topics:
Business Critical Outage,
Personal Computer Issues,
Equipment Request, and
Password Reset</b>


