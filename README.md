
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
<p align="center">
Allow anyone to create tickets: <br/>
<img width="450" alt="3 Uncheck-Allowing unregistered users to create tickets" src="https://github.com/user-attachments/assets/e24683ee-106d-4e75-92f1-2f6a483f2104" />
</p>
<p>
In this Process, we will allow anyone to create a ticket. Go to Admin Panel, settings, and then to user settings, which will allow you to uncheck unregistered users, allowing them permission to create a ticket. 
<p>Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
</p>
<p align="center">
Configure Agents (workers): <br/>
<img width="450" alt="4 Added Agents (workers)" src="https://github.com/user-attachments/assets/0a719ead-c355-4e1f-b7c6-e4794e4bb4df" />
</p>
<p>
To configure an agent, it properly ensures they have the correct permissions, department access, and roles to do their job effectively. Same process go the Admin Panel, click on agent, and then add a new worker and just fill out the info.
<p>Admin Panel -> Agents -> Add New</p>
</p>
<p align="center">
Configure Users (customers): <br/>
<img width="450" alt="5 Configuring Access Levels to Users (Costumers)" src="https://github.com/user-attachments/assets/962ddefa-18f6-4680-920d-65044046c094" />
</p>
<p>
Go to Agent Panel and then Users, and add a new user. This allows you to manage their profiles, view ticket history, organize them into organizations, and ensure smooth communication.
<p>Agent Panel -> Users -> Add New</p>
</p>



</p>

