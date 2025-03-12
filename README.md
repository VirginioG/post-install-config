<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial provides detailed instructions for the post-installation configuration of the open-source help desk ticketing system, osTicket. It walks you through essential setup steps to ensure the system is fully functional and tailored to your organization's needs. Key areas covered include user roles, department configurations, and team setup to manage ticket routing efficiently. By following this guide, you'll configure everything from agent settings to service level agreements, ensuring a smooth and effective ticketing experience for both agents and customers.<br />


<h2>Video Demonstration</h2>

<a href=https://youtu.be/YH2zFxS_2uo?si=V8C6V_kT4PB5nFtW

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket System

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

osTicketing system Configurations:
-Ticket properties

-Agents

-Help Topics

-SLA

-Departments

-Roles/Permissions

-Users/Teams

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php

End Users osTicket URL:
http://localhost/osTicket 

  
Part 1: Configuration of Roles, Departments, and Teams

Configure roles to group permissions (Admin Panel -> Agents -> Roles). Example: "Supreme Admin."

Departments: Set up departments for ticket visibility and assignment (Admin Panel -> Agents -> Departments). Example: "SysAdmins."

Teams: Create teams by grouping agents from different departments (Admin Panel -> Agents -> Teams). Example: "Online Banking.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Part 2: Ticket Creation, Agents, and Users

Allow anyone to create tickets: Disable unregistered users from creating tickets (Admin Panel -> Settings -> User Settings). Enable registration and login for ticket creation.

Configure Agents: Add agents and assign them to departments (Admin Panel -> Agents -> Add New). Example: "Jane" (Dept: SysAdmins), "John" (Dept: Support).

Configure Users: Add customers (Agent Panel -> Users -> Add New). Example: "Karen," "Ken."
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Part 3: SLA Configuration and Help Topics

Configure SLA: Set up service level agreements with specific grace periods and schedules (Admin Panel -> Manage -> SLA). Example:

Sev-A (Grace Period: 1 hour, Schedule: 24/7)

Sev-B (Grace Period: 4 hours, Schedule: 24/7)

Sev-C (Grace Period: 8 hours, Business Hours)

Configure Help Topics: Define ticket categories for users to choose from when creating a ticket (Admin Panel -> Manage -> Help Topics). Example:

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset

Other

This setup helps define your team structure, user roles, SLA response times, and the categories available for users when submitting support tickets.
</p>
<br />
