# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="415" height="412" alt="screenshot19" src="https://github.com/user-attachments/assets/f365203a-dae0-4704-a994-59691c519796" />
</p>
<p>
Step 1: Now that we have the osTicket officially installed, we can go ahead and start getting familiar with the system. Shown above is the login page. We will be using the username: adminuser and password: Password1. Login  http://localhost/osTicket/scp/login.php
</p>
<p>
<img width="722" height="323" alt="screenshot 21" src="https://github.com/user-attachments/assets/8d7725d8-1aee-45f2-b01c-f0d0e4ed0387" />
</p>
<p>
<img width="724" height="448" alt="screenshot 22" src="https://github.com/user-attachments/assets/0db72afd-9534-42c0-902e-baf8846c7547" />
</p>
<p>
Step 2: We're going to start off by creating a new role under the name of "Supreme Admin" in the "definition" column.
<p>
<img width="720" height="545" alt="screenshot 23" src="https://github.com/user-attachments/assets/de868e80-b0ac-437f-915f-e1faa69ad1b0" />
</p>
<p>
<img width="720" height="438" alt="screenshot 24" src="https://github.com/user-attachments/assets/71a4ab62-64c7-4b7f-adf5-39e05f67b8cd" />
</p>
<p>
Step 3: Next, we're going assign this role full access before adding it. Be sure to check every box in the "tickets" and "tasks" section under the "permissions" column, then click "add role."
</p>
<p>
<img width="728" height="267" alt="screenshot 25" src="https://github.com/user-attachments/assets/e50eaf54-dc9b-46d5-ba63-1680ccec5e8b" />
</p>
<p>
<img width="725" height="605" alt="screenshot 26" src="https://github.com/user-attachments/assets/2cf244cd-ade9-4ae6-a6c2-d5ffd69be125" />
</p>
<p>
<img width="715" height="613" alt="screenshot 27" src="https://github.com/user-attachments/assets/80cd1b15-b39e-4dae-9f59-3265c9e862fb" />
</p>
<p>
Step 4: Now, we're going to add a new department under the name of "SysAdmins" by going under agents -> Departments -> Add Department. Be sure to set the Parent setting to "Top Level Department." Leaving the rest as is, click "create Department."
</p>
<p>
<img width="738" height="269" alt="screenshot 28" src="https://github.com/user-attachments/assets/20f94a06-011c-4c6b-aa70-5746943a9971" />
</p>
<p>
<img width="723" height="527" alt="screenshot 29" src="https://github.com/user-attachments/assets/0a826ccd-a157-4141-9d2d-5286cc5f0950" />
</p>
<p>
Step 5: We are now going to configure a team under the name "Online Banking." Admin Panel -> Agents -> Teams -> Add New Team. Make sure you click "Create Team" before proceeding.
</p>
<p>
<img width="722" height="529" alt="screenshot 30" src="https://github.com/user-attachments/assets/b910f295-8e07-4243-aeec-fbca428d1ce5" />
</p>
<p>
Step 6: We're going to allow anyone to create tickets by going to Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets).
</p>
<p>



