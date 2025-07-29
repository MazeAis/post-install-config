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

- Configure Admin and Agent access
- Define roles, departments, and teams
- Set up agent and user accounts
- Establish SLAs and Help Topics
- Organize ticket routing and visibility

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/zIWlMyx.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://i.imgur.com/j9p4P9O.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is a preview of both the Admin and Agent Views

After osTicket is set up, IT administrators and support staff use the Admin Panel (http://localhost/osTicket/scp/login.php) to manage system settings, organize departments, assign roles, set response timelines (SLAs), and handle incoming support tickets.

End users access a separate client portal (http://localhost/osTicket) where they can submit and track their support requests, helping streamline the support process on both ends.
</p>
<br />

<p>
<img src="https://i.imgur.com/Z3g3kwC.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Admin Panel, osTicket lets you organize and manage your support staff efficiently:

Under Agents > Roles, you can create roles (e.g., Supreme Admin) to define what permissions and actions each agent is allowed to perform.

Go to Agents > Departments to group agents into categories like SysAdmins or Support, which helps control who sees and handles different types of tickets.

Use Agents > Teams to build cross-functional groups (e.g., Online Banking) by combining agents from various departments to collaborate on specific issues or areas.

This structure makes it easy to scale and manage support operations.
</p>
<br />

<p>
<img src="https://i.imgur.com/3nuWeQM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Admin Panel, go to Agents > Add New to create support staff accounts—for example, Jane (assigned to SysAdmins) and John (assigned to Support). Agents are the team members who handle incoming support tickets.

To add end users (customers), switch to the Agent Panel, navigate to Users > Add New, and create user profiles—like Karen and Ken—who will be submitting helpdesk requests through the client portal.
</p>
<br />

<p>
<img src="https://i.imgur.com/6maWH9H.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Admin Panel, go to Manage > SLA to set up Service Level Agreements (SLAs) like Sev-A, Sev-B, and Sev-C. Each SLA defines how quickly a ticket should be responded to, helping the team prioritize urgent issues.

Next, navigate to Manage > Help Topics to create categories such as Password Reset or Business Critical Outage. These options help users describe their issue more clearly and ensure tickets are routed to the right support team faster.
</p>
<br />


### ✅ Summary

This project involves setting up and configuring osTicket on a Windows 10 virtual machine in Microsoft Azure.

Key highlights include:

- Creating and managing user roles and permissions for support staff

- Organizing teams and departments to help manage and route support tickets

- Adding support agents and end users who submit help requests

- Setting up Service Level Agreements (SLAs) to ensure timely responses

- Creating help topics to categorize and prioritize tickets efficiently

This work demonstrates practical skills in managing IT support tools, organizing support teams, and improving service workflows—important for IT support and operations roles.
