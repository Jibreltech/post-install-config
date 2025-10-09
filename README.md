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
