<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Acknowledge Agent Panel vs Admin Panel within osTicket
- Configure Roles 
- Configure Departments
- Configure Teams, Configure Agents (workers), Configure Users (customers) +Configure SLA

<h2>Configuration Steps</h2>

<p>
<img width="1435" alt="os ticket STEP 1 admin" src="https://github.com/user-attachments/assets/d050e383-9c82-44a4-8088-4130f1cb0325"/>
<img width="959" alt="os Agent panel" src="https://github.com/user-attachments/assets/c93112f2-10a4-4f62-aa08-c7219f343a16"/>
<img width="836" alt="os end user" src="https://github.com/user-attachments/assets/331f2742-234d-486c-a2b6-7c9f7560db24"/>
</p>
<p>
osTicket Installed, this is the view from the Admin panel view, Agent panel view, and the end user panel view.
</p>
<br />

<p>
<img width="958" alt="agent giving access to roles" src="https://github.com/user-attachments/assets/62d6891a-85cf-4166-893c-9de6d178e908"/>
<img width="952" alt="permissions" src="https://github.com/user-attachments/assets/6c2b827a-014b-4867-9084-642cafa31002"/>
<img width="956" alt="add a new role os ticket" src="https://github.com/user-attachments/assets/4707ca78-cf0c-48c7-8309-85df432bd366"/>
<img width="962" alt="add role " src="https://github.com/user-attachments/assets/6b4c4b8c-b4dc-436b-96ee-04b3386e59f4"/>
<img width="956" alt="added knowledgebase" src="https://github.com/user-attachments/assets/2d627d4b-657e-4034-a2db-963b109b2fdf"/>
<img width="960" alt="supreme admin added" src="https://github.com/user-attachments/assets/d39304b6-0ecf-40b5-8df1-ff0ffa111e6c"/>
</p>
<p>
Now, we configure Roles (for grouping permissions) -> Admin Panel -> Agents -> Roles, cick "View Only" -> adjust Permissions, click Roles, you can add a new role, now added as Supreme Admin, adjust tasks under the same permissions for the Supreme admin role, and knowledgebase, click add role -> now "Supreme Admin" should be added to the roles
</p>
<br />

<p>
<img width="998" alt="department added" src="https://github.com/user-attachments/assets/9d9efbf6-4013-4d50-afe8-41c1084e7c32"/>
<img width="1434" alt="admins" src="https://github.com/user-attachments/assets/a1023b3b-40a4-4dd3-b860-3f161e8221aa"/>
<img width="960" alt="sysadmins dept added to os" src="https://github.com/user-attachments/assets/641042f0-fafd-4534-a05e-b271fd2a9a2f"/>
</p>
<p>
Next, Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking) Admin Panel -> Agents -> Departments -> Agents -> Departments, Add new department for SysAdmins-> click "create Dept"
</p>
<br />

<p>
<img width="955" alt="agents-teams" src="https://github.com/user-attachments/assets/e5701835-f627-4c9c-9d8b-6b3404b5f4d5"/>
<img width="1440" alt="add team" src="https://github.com/user-attachments/assets/47bcbc52-9969-4483-b366-385c62a87ec3"/>
<img width="1440" alt="online team added" src="https://github.com/user-attachments/assets/093993e0-ad4f-4ec8-b0f6-40647784a620"/>
</p>
<p>
Now, Configure Teams Admin Panel -> Agents -> Teams (Pull Agents from different Departments) -> team added
</p>
<br />

<p>
<img width="950" alt="uncheck users to create a ticket" src="https://github.com/user-attachments/assets/6813ee8b-c761-4e39-95c2-40bcc27deb70"/>
</p>
<p>
Now, we can configured Os to allow anyone to create tickets, Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets) -> Registration Required: Require registration and login to create tickets
</p>
<br />

<p>
<img width="1440" alt="adding new agents" src="https://github.com/user-attachments/assets/4c00496a-80a9-418d-a241-df9b00c192e0"/>
<img width="1440" alt="add new agent moment" src="https://github.com/user-attachments/assets/e183b13c-103e-4f3f-9d63-5fe5e06085c5"/>
<img width="1438" alt="jane doe agent added" src="https://github.com/user-attachments/assets/b339976c-f6f1-4320-a044-5a5c7b2233f2"/>
<img width="961" alt="adjust agent access" src="https://github.com/user-attachments/assets/624f4b46-f2f3-4003-9476-373dbe550628"/>
<img width="957" alt="create team online banking" src="https://github.com/user-attachments/assets/dcc893a3-990e-4374-8998-a6e911f6aad1"/>
<img width="957" alt="create team online banking" src="https://github.com/user-attachments/assets/155a379f-9a17-45ab-9c2f-6dc9f8990345"/>
<img width="1440" alt="create" src="https://github.com/user-attachments/assets/617526a1-978d-4b56-ba9c-e0f3a368cf72"/>
</p>
<p>
Configure Agents (workers) Admin Panel -> Agents -> I Added a New agent -> Jane (Dept: SysAdmins), adjusted the agents access, adjust the team the agent is to go to, add "create" -> now, too add a new agent, click "agents" to add another agent, John (Dept: Support), adjust its access, permissions etc click create, now agents and their departments appeared
</p>
<br />

<p>
<img width="950" alt="uncheck users to create a ticket" src="https://github.com/user-attachments/assets/6813ee8b-c761-4e39-95c2-40bcc27deb70"/>
<img width="958" alt="john added" src="https://github.com/user-attachments/assets/cc34311e-b4a3-4db3-82a3-ec4af1b54029"/>
<img width="955" alt="agents and their depts" src="https://github.com/user-attachments/assets/ddc1b65b-873e-4bf1-81a5-53ee904e5c0e"/>
</p>
<p>
Now, we configured Os to allow anyone to create tickets, Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets) -> Registration Required: Require registration and login to create tickets
</p>
<br />

<p>
<img width="1440" alt="add user" src="https://github.com/user-attachments/assets/5111bfb0-db6e-4db5-9694-b47b8bea8869"/>
<img width="1440" alt="new user karen added" src="https://github.com/user-attachments/assets/fed96878-b505-4519-b127-2e6fb3f584f1"/>
</p>
<p>
Now, I Configured Users (customers) Agent Panel -> clicked Users -> clicked Add New
</p>
<br />

<p>
<img width="957" alt="manage user" src="https://github.com/user-attachments/assets/07933e66-b4e3-464d-afae-228c42eecf69"/>
<img width="953" alt="Screen Shot 2025-02-04 at 8 27 56 PM" src="https://github.com/user-attachments/assets/8adf2f75-1410-41a5-bad0-b277c9bea739"/>
<img width="963" alt="Screen Shot 2025-02-04 at 8 31 29 PM" src="https://github.com/user-attachments/assets/1e601e8a-478e-4b2a-a62e-3fb0511b8d35"/>
<p>
Now to Configure SLA Admin Panel -> Manage -> SLA, click "Add new SLA plan", adjust SLA plan , click Add Plan
</p>
<br />

<p>
<img width="962" alt="Screen Shot 2025-02-04 at 8 40 04 PM" src="https://github.com/user-attachments/assets/c60bc2a5-b7ef-4598-b648-123f20ff246e"/>
<img width="958" alt="Screen Shot 2025-02-04 at 8 43 22 PM" src="https://github.com/user-attachments/assets/fa29756a-764e-41b7-afb3-57bf90c5b367"/>
<img width="952" alt="Screen Shot 2025-02-04 at 8 59 40 PM" src="https://github.com/user-attachments/assets/dc1f2f1b-bf68-4311-89ed-2620ef7f1dfa"/>
<p>
Now to Configure Help Topics (For when users create a ticket) Admin Panel -> Manage -> Help Topics, Add New Help Topic and repeat the steps to add more help topics within the osTicket system I built
</p>
<br />
