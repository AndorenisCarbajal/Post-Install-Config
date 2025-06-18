
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This outlines the post-install configuration of the open-source help desk ticketing system osTicket.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1: Configure Roles
- Item 2: Configure Teams
- Item 3: Allow anyone to create tickets
- Item 4: Configure Agents (workers)
- Item 5: Configure Users (customers)
- Item 6: Configure SLA
- Item 7: Configure Help Topics

<h2>Configuration Steps</h2>

<p align="center">
Configure Roles: <br/>
<img width="450" alt="1 Supreme Admin role with all permissions" src="https://github.com/user-attachments/assets/ba124b99-8a47-47ff-ba18-29d1f00c192f" />
</p>
<p> Click on Admin Panel, then click on Agents, and finally on Roles, allowing Suprime Admin to have access to all the permissions. This ensures that there is always a user with the ability to recover, configure, or troubleshoot the system.
<p>Admin Panel -> Agents -> Roles</p>
</p>
<p align="center">
Configure Departments: <br/>
Click on Admin Panel, then Roles, and finally Departments, allowing SysAdmin to see all tickets. This ensures efficient ticket routing, role-based access, and clear responsibilities.
<p>Admin Panel -> Agents -> Departments</p>
</p>
<p align="center">
Configure Teams: <br/>
<img width="450" alt="2 Configuring Teams(Assigning)" src="https://github.com/user-attachments/assets/15467554-d60f-4c78-b9b1-737aaa9c3547" />
</p>
<p>
To configure a team, go to Admin Panel, then agents, and finally teams, which completes the process of adding teams, which sets a group of agents from different departments with the helpdesk system to work together on a specific ticket.
<p>Admin Panel -> Agents -> Teams (Pull Agents from different Departments)</p>
</p>
<br />
