<p align="center">
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

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents
- Configure Users
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img width="949" height="193" alt="image" src="https://github.com/user-attachments/assets/b191b08a-d67e-45b3-b4fc-9702dd14ea40" />
</p>
<p>
Configure roles by selecting Admin Panel->Agents->Roles. Then create a role named "Supreme Admin" that has all available permissions 
</p>
<br />

<p>
<img width="941" height="139" alt="image" src="https://github.com/user-attachments/assets/9a0adc2e-ee3c-4787-bf21-d74922024d0c" />
</p>
<p>  Next we are going to configure departments. Departments help organize support requests by category or team, ensuring that each issue is routed to the right group of specialists. To configure departments simply select Admin Panel->Agents->Departments. Once in the department settings go to name and name your department "SysAdmins".  </p>
<br />

<p>
<img width="943" height="107" alt="image" src="https://github.com/user-attachments/assets/adf02378-1a73-439f-8925-80e87f22b7a3" />
</p>
<p>
To Configure teams simply  select Admin Panel → Agents → Teams. Then Click the Add New Team button, then in the Add New Team section, enter “Online Banking” in the Name field. Finally, click Create Team to save your changes.</p>
<br />

<p>
<img width="943" height="135" alt="image" src="https://github.com/user-attachments/assets/ab1a27a2-e3dc-439a-a9b9-7cf22995fad5" />
</p>
<p>
Next we are going to configure agents. Agents are individual team members who handle customer issues and inquiries by creating, updating, and managing tickets within the ticketing system. They serve as the main point of contact for customers, ensuring that requests are resolved efficiently and accurately. To configure Agents select Admin Panel->Agents->Add New then add two new agents named John Doe and Jane Doe

<p>
<img width="943" height="106" alt="image" src="https://github.com/user-attachments/assets/07188f09-eaf5-40f8-9cfb-5099ad40c078" />
</p>
<p>
Now we are going to configure Users. Users are customers or clients who submit requests or report issues through the ticketing system. They initate the support process by creating tickets that agents then review, manage and resolve. To configure Users select Agent Panel->Users->Add new. Then add one user named Karen

<p>
</p>
<p>
<img width="939" height="240" alt="image" src="https://github.com/user-attachments/assets/809c3263-a5dc-4728-87d8-83c04a346a01" />
</p>
<img width="941" height="244" alt="image" src="https://github.com/user-attachments/assets/7ccb033d-96df-4cbd-bf50-f20eee49aa1d" />
</p>
<img width="940" height="241" alt="image" src="https://github.com/user-attachments/assets/3efef8a9-eb7e-4761-a307-45c59b43235a" />
</p>
<p>
Next we are going to configure SLA, SLAs (Service Level Agreements) are predefined standards that outline the expeceted response and resolution times for customer requests. They help ensure consistent service quality by setting clear performance goals for support teams. To configure SLAs select Admin Panel->Manage->SLA and then select Sev-A(Grace Period:1 hour, Schedule:24/7), Sev-B(Grace Period:4 hours, Schedule:24/7), Sev-C (Grace Period:8 hours,Schedule:Monday-Friday 8am-5pm with U.S Holidays).
