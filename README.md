# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. Setting up roles, departments, teams, and agents. Part 2 of 3
<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
</p>
<p>
<h2>Post-Install Configuration Objectives </h2>
</p>
<p>
1. Establish user and agent roles- Configure agents, teams, and permissions
</p>
<p>
2. Define Ticket Categories and Priorities- Set up help topics, ticket priorities, and SLAs to ensure requests are categorized correctly and handled based on urgency
</p>
<p>
3. Enable email and ticketing and notifications
</p>
<p>
4. Customize intake forms and workflow
</p>
<p>
5. Validate and secure the osTicket system- Test ticket submission, assignment, communication, and resolution workflows, securing the system by finalizing permissions

<h2>Configuration Steps</h2>

<p>
<img width="415" height="412" alt="screenshot19" src="https://github.com/user-attachments/assets/f365203a-dae0-4704-a994-59691c519796" />
</p>
<p>
Step 1: Now that we have the osTicket officially installed, we can go ahead and start getting familiar with the system. Shown above is the login page. We will be using the username: adminuser and password: Password1. Login http://localhost/osTicket/scp/login.php
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
<img width="722" height="282" alt="screenshot 31" src="https://github.com/user-attachments/assets/c3a45cab-843c-4199-95b0-c8b096feecf1" />
</p>
<p>
<img width="720" height="639" alt="screenshot 32" src="https://github.com/user-attachments/assets/b4b3092b-b594-4fd5-a38c-0777b6e2a7a0" />
</p>
<p>
<img width="485" height="291" alt="screenshot 33" src="https://github.com/user-attachments/assets/185f3fe0-2c4c-4193-82c8-568105f41f8e" />
</p>
<p>
Step 7: Creating our first agent under the name "Jane Doe," we will be setting her email to Jane@lognpacific.com, username: Jane, and password: Password1. Before moving on, make sure to uncheck both boxes in the password section.
</p>
<p>
<img width="723" height="429" alt="screenshot 34" src="https://github.com/user-attachments/assets/7ade2a9d-4e9e-4956-be73-e185da33bbf9" />
</p>
<p>
Step 8: Still setting up Jane's account, we're going to give her full access to everything by setting her role to "Supreme Admin" and department to "SysAdmin."
</p>
<p>
<img width="718" height="333" alt="screenshot 35" src="https://github.com/user-attachments/assets/2a67bd22-6432-4248-aaa2-42cc8ce6a0e8" />
</p>
<p>
Step 9: Finishing up Jane's account, we're going to set her team under "Online Banking."
</p>
<p>
<img width="717" height="552" alt="screenshot 36" src="https://github.com/user-attachments/assets/dc9009d2-159b-442a-b6b2-03f483c39063" />
</p>
<p>
<img width="487" height="292" alt="screenshot 37" src="https://github.com/user-attachments/assets/c7cb8a34-4979-4105-8c06-d3329cb0742f" />
</p>
<p>
<img width="725" height="428" alt="screenshot 38" src="https://github.com/user-attachments/assets/5705aea5-1aea-4529-869f-088c824cd280" />
</p>
<p>
Step 10: Creating our next agent under the name "John Doe," we will set his email to John@lognpacific.com, username: John, and Password: Password1. Same as Jane's be sure to make sure both boxes are unchecked in the password section. We will also set his department to "support" and his access to "view only."
</p>
<p>
<img width="723" height="320" alt="screenshot 40" src="https://github.com/user-attachments/assets/d81f4723-06d0-465f-af7c-00ead3f70e0c" />
</p>
<p>
After creating your name, Jane, and John, this is what your agents section should look like.
</p>
<p>
<img width="719" height="262" alt="screenshot 41" src="https://github.com/user-attachments/assets/61235f81-3e7e-47c0-a67e-81caa568bb58" />
</p>
<p>
Step 11: Now shifting gears over to the agents panel, we are going to create a couple of users.
</p>
<p>
<img width="483" height="297" alt="screenshot 42" src="https://github.com/user-attachments/assets/ca93ac54-2f36-418c-b91e-ad8250869d3c" />
</p>
<p>
<img width="724" height="308" alt="screenshot 43" src="https://github.com/user-attachments/assets/3fcabeeb-64cd-4c4e-83d2-1933792b41c0" />
</p>
<p>
Step 12: Starting with Karen, we are just going to add her name and email address (Karen@lognpacific.com).
</p>
<p>
<img width="725" height="277" alt="screenshot 57" src="https://github.com/user-attachments/assets/5a0c272f-36c3-4036-96ab-aba1ee1fcf5d" />
</p>
<p>
Step 13: After creating Karen, we are going to create Ken.
</p>
<p>
<img width="485" height="294" alt="screenshot 58" src="https://github.com/user-attachments/assets/40866788-0548-4447-86ca-ed53b0223468" />
</p>
<p>
Step 14: Just like Karen's, we are only going to fill out Ken's name and email address (Ken@lognpacific.com).
</p>
<p>
<img width="720" height="297" alt="screenshot 59" src="https://github.com/user-attachments/assets/e73df5cf-6eb8-457b-9537-0c911b99904c" />
</p>
<p>
After creating them both, this is what your users section should look like. 
</p>
<p>
<img width="732" height="274" alt="screenshot 44" src="https://github.com/user-attachments/assets/6c5ea0de-b579-45a0-86be-458c03c04c10" />
</p>
<p>
Step 15: Shifting back over to the admin panel, we are now going to configure our SLAs. Creating a Sev-A, Sev-B, and Sev-C.
</p>
<p>
<img width="731" height="541" alt="screenshot 45" src="https://github.com/user-attachments/assets/7870592e-8370-439b-b96c-e2548cb0627f" />
</p>
<p>
Step 16: Starting with Sev-A being the most crusial, we are going to set the grace period to 1 hr, and the schedule to 24/7.
</p>
<p>
<img width="729" height="537" alt="screenshot 47" src="https://github.com/user-attachments/assets/cd531da0-3af1-488c-ac99-d77b286964f6" />
</p>
<p>
Step 17: Now creating Sev-B, we are going to give the grace period 4 hrs and the schedule still 24/7.
</p>
<p>
<img width="727" height="538" alt="screenshot 49" src="https://github.com/user-attachments/assets/50e909be-56e3-457f-b46b-2a5d3ee8f30b" />
</p>
<p>
Step 18: And lastly, we're creating Sev-C with a grace period of 8 hrs, and the schedule being Mon-Fri 8am-5pm with U.S Holidays.
</p>
<p>
<img width="730" height="364" alt="screenshot 50" src="https://github.com/user-attachments/assets/4bcc1f4f-c42a-4a38-813c-e85490ca6387" />
</p>
<p>
Your SLA section should consist of all three now.
</p>
<p>
Step 19: TGhe last thing we are going to do for this section is add a few help topics.
</p>
<p>
<img width="734" height="514" alt="screenshot 52" src="https://github.com/user-attachments/assets/4eeb4abf-35c6-4445-9e00-7635c277b727" />
</p>
<p>
Step 20: The first topic will be "Business Critical Outage," making the parent topic "Report a Problem."
</p>
<p>
<img width="744" height="513" alt="screenshot 53" src="https://github.com/user-attachments/assets/952228fd-f613-460c-b022-1f5c312530fa" />
</p>
<p>
Step 21: Our next help topic will be "Personal Computer Issues" under "Report a Problem" as well.
</p>
<p>
<img width="728" height="517" alt="screenshot 54" src="https://github.com/user-attachments/assets/71c51f6a-fa86-4318-8c23-de1c00a27d28" />
</p>
<p>
Step 22: With the last topic being "Equipment Request," under "General Inquiry," this step will close out this section. If you have made it this far, I will see you in the next section :-)



