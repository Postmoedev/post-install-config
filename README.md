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

- <b>Create "Supreme Admin" role(enable all permissions)</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/29b2761b-78d9-4320-8775-38a439901fd9)

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/86671ea1-6848-4fc9-910a-012b5aa013fe)

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/00298474-ec58-4011-865c-fb8ee8fab366)

<h3>Configure Departments</h3>
- <b>Navigate to Admin Panel -> Agents -> Departments</b>

- <b>Create "System Administrators" department</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/b4866a29-c58e-4c30-98e9-3f0c501b4101)

<h3>Configure Teams</h3>
- <b>Navigate to Admin Panel -> Agents -> Teams</b>

- <b>Create "Level II Support" team</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/2792db1a-5d82-48ac-91a4-7fbe4175af12)

<h3>Allow Ticket Creation</h3>
- <b>Navigate to Admin Panel -> Settings -> User Settings</b>

- <b>Make sure "Require registration and login to create tickets" is unchecked</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/6d626c0c-a91e-41e2-be7a-c1b207b0a034)

<h3>Configure Agents (workers)</h3>
- <b>Navigate to Admin Panel -> Agents -> Add New</b>

- <b>Add agent: Jane doe</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/59cab6ba-ffc0-4593-8a2f-129bf0c8bfa1)

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/ac12c4d4-cc53-4110-ba66-cfd4a746f021)

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/abb9ba03-d9d0-47d1-82df-1f2e0151c6f9)

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/a3fdae79-086d-4783-a3ea-c8a5970cd6c3)

<h3>Configure Users (customers)</h3>
- <b>Navigate to Agent Panel -> Users -> Add New</b>

- <b>Add user: Ken</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/721ae8a1-aabf-4c43-b30d-77cacf1e252f)

<h3>Configure SLA</h3>
- <b>Navigate to Admin Panel -> Manage -> SLA</b>

- <b>Set SLA levels:
Sev-A (1 hour, 24/7)

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/755609c1-0fec-4f0a-b093-5089871980b2)

- <b>Sev-B (4 hours, 24/7)</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/568e80b9-353a-4774-881a-57df3f9e7c4b)

- <b>Sev-C (8 hours, business hours)</b>

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/6caa3b55-c85d-463d-8b5c-12f53f7ed0a6)

<h3>Configure Help Topics</h3>
- <b>Navigate to Admin Panel -> Manage -> Help Topics</b>

- <b>Create help topics:
Business Critical Outage,
Personal Computer Issues,
Equipment Request, and
Password Reset</b>

<b>Example:</b>
![image](https://github.com/Postmoedev/post-install-config/assets/150564271/6b33976d-ca2e-4ef8-8f1f-f2dc46fb1bc2)

![image](https://github.com/Postmoedev/post-install-config/assets/150564271/fd93a7ca-2644-453d-9e75-e29dd77ea234)

