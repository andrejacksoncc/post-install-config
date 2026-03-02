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

- Explore the osTicket portal: Identify the difference between the admin/analyst login page and the end-user page.
- Understand admin vs. agent panels: Recognize where configuration (admin) and ticket working (agent) are done.
- Configure roles: Set up permission groups for different levels of access.
- Configure departments: Organize ticket visibility and assignment (e.g., help desk, IT, networking).
- Create teams: Group users across departments for collaboration.
- Adjust user settings: Allow users to submit tickets without registration (for the lab).
- Add agents and users: Create help desk workers (agents) and end users.
- Set SLAs: Define Service Level Agreements (ticket response/resolution timelines).
- Add help topics: Create categories for end users when submitting tickets.

<h2>Configuration Steps</h2>

<img width="80%" height="80%" alt="1" src="https://github.com/user-attachments/assets/f4b0b8ea-4cb0-4c63-8272-59c9585113a6" />

- Log into osTicket using your username and password.
</p>
<br />

<img width="80%" height="80%" alt="2" src="https://github.com/user-attachments/assets/3df8f684-28e4-4363-ad78-578d01e21e7d" />

- First page opens up to the Agent panel which is where the help desk agent deals with tickets.
</p>
<br />

<img width="730" height="118" alt="3" src="https://github.com/user-attachments/assets/414e994a-5fa3-432d-8a06-e07591af5dd0" />

- When you click on the "Admin Panel" button it will bring you to the Admin page. 
</p>
<br />

<img width="80%" height="80%" alt="4" src="https://github.com/user-attachments/assets/5b4a91b6-8ef1-421d-bb8c-91eda681c0e0" />


- Here you can configure settings on the backend.
</p>
<br />

<img width="80%" height="80%" alt="5" src="https://github.com/user-attachments/assets/48bbf49f-c8b5-40fa-b85e-78e1f6821ec5" />


- In the Admin panel, click on "Agents", "Roles", and then "Add new role".
</p>
<br />

<img width="80%" height="80%" alt="6" src="https://github.com/user-attachments/assets/8e625ffb-d574-4620-8399-bb7436896f29" />


- Call the new role "Supreme Admin". 
</p>
<br />

<img width="80%" height="80%" alt="7" src="https://github.com/user-attachments/assets/bc763cba-ea55-4e60-af53-a68e7a075570" />


- Click on "Permissions" and check every box giving permissions for everything.
</p>
<br />

<img width="80%" height="80%" alt="8" src="https://github.com/user-attachments/assets/d889f3e6-9f11-4eb2-a41a-65e6c6c91330" />


- Click "Tasks" and check every box.
</p>
<br />

<img width="80%" height="80%" alt="9" src="https://github.com/user-attachments/assets/a8976bd6-8f8b-452e-924a-a9d2e9810d2c" />


- Click "Knowledgebase", check every box and then click "Add Role".
</p>
<br />

<img width="80%" height="80%" alt="10" src="https://github.com/user-attachments/assets/516a27e7-ce4e-41e8-be6a-9ca1d490fcd6" />


- To configure departments go the "Departments" tab and click "Add New Department".
</p>
<br />

<img width="80%" height="80%" alt="11" src="https://github.com/user-attachments/assets/6acc61a6-de40-4993-b592-cd7df62fc3d3" />


- Make sure for the "Parent" tab you choose "Top Level Department"
- Name it "SysAdmins" and then click "Create Dept".
</p>
<br />

<img width="80%" height="80%" alt="11" src="https://github.com/user-attachments/assets/67f07b17-ff30-45ca-989b-c6b4300c164b" />


- To configure teams, go to the "Teams" tab and click "Add New Team".
</p>
<br />

<img width="80%" height="80%" alt="13" src="https://github.com/user-attachments/assets/1d6963d4-242f-49f0-be83-4cbb8dfb86b1" />


- Name it "Online Banking" then click "Create Team".
</p>
<br />

<img width="80%" height="80%" alt="14" src="https://github.com/user-attachments/assets/e67d4c0a-33cc-459e-852b-639701e02e64" />

- To allow anyone to create tickets, clcick "Settiings" and then "Users".
- UNCHECK: unregistered users can create tickets
</p>
<br />

<img width="80%" height="80%" alt="15" src="https://github.com/user-attachments/assets/ee2e8da0-b8fa-4941-a63b-cefb1ed42472" />


- To configure agents, click the "Agents" tab and press "Add New Agent".
</p>
<br />

<img width="80%" height="80%" alt="16" src="https://github.com/user-attachments/assets/55999968-2ee2-4363-b3a9-11fa2670edda" />


- Give the new agent a name, email address and username.
</p>
<br />

<img width="80%" height="80%" alt="17" src="https://github.com/user-attachments/assets/16951153-4494-4a5f-a4e9-01f9632834c3" />


- Click "Set Password" and uncheck "Send the agent a password reset email".
- Create new password for the agent.
</p>
<br />

<img width="80%" height="80%" alt="18" src="https://github.com/user-attachments/assets/3be13e65-23af-4eea-87c1-e4b8fdea0baf" />


- Click the "Access" tab.
- Under "Primary Department", put them in the "SysAdmins" department and then give them the role of "Supreme Admin".
</p>
<br />

<img width="80%" height="80%" alt="19" src="https://github.com/user-attachments/assets/5821359c-a2b3-4b11-afcb-54df9fdc7d9f" />


- Click the "Teams" tab.
- Put them in the "Online Banking" team.
- Click "Create"
</p>
<br />

<img width="80%" height="80%" alt="20" src="https://github.com/user-attachments/assets/a221a57a-4f3c-4336-9482-651f7857fe32" />


- Create another agent different from the first.
</p>
<br />

<img width="80%" height="80%" alt="21" src="https://github.com/user-attachments/assets/bee6c4df-8722-4196-a89f-e84796c9decb" />


- Under "Access" put them in the "Support" department and give them the role of "View Only".
- Click "Create".
</p>
<br />

<img width="80%" height="80%" alt="22" src="https://github.com/user-attachments/assets/256a62cd-7b2a-4ca9-8d14-77d4da57bbbe" />


- To configure users switch to the "Agent Panel", click "Users" and then "Add User".
</p>
<br />

<img width="80%" height="80%" alt="23" src="https://github.com/user-attachments/assets/dde58add-7c54-4098-b6e3-6909c1133594" />


- Fill out the name and email address portion, and then click "Add User".
</p>
<br />

<img width="80%" height="80%" alt="24" src="https://github.com/user-attachments/assets/7fd7b76a-255c-4f5e-ae48-b026f42c73b4" />


- To configure SLA, Switch to the "Admin Panel", click "Manage", and then click "SLA".
- Click "Add New SLA Plan".
</p>
<br />

<img width="80%" height="80%" alt="25" src="https://github.com/user-attachments/assets/06c42c39-6bd4-4fc2-affe-e98f832dc2a7" />


- Name it Sev-A (Grace Period: 1 hour, Schedule: 24/7).
- Click "Add Plan".
</p>
<br />

<img width="80%" height="80%" alt="26" src="https://github.com/user-attachments/assets/dcadf50b-543a-44b8-8131-f9e75d1b5fae" />


- Add another SLA plan.
- Name it Sev-B (Grace Period: 4 hours, Schedule: 24/7).
- Click "Add Plan".
</p>
<br />

<img width="80%" height="80%" alt="27" src="https://github.com/user-attachments/assets/dd5c8d28-695b-4d23-ba18-16d11394c8d8" />


- Add another SLA plan.
- Name it Sev-C (Grace Period: 8 hours, Business Hours)
- Click "Add Plan".
</p>
<br />

<img width="80%" height="80%" alt="28" src="https://github.com/user-attachments/assets/6026ce65-d4ed-4974-aaf8-c5fe23e14c47" />


- To configure Help Topics, from the Admin Panel, clck "Manage" and then "Help Topics".
- Click "Add New Help Topic".
</p>
<br />

<img width="80%" height="80%" alt="29" src="https://github.com/user-attachments/assets/c271f9d9-f150-4e98-a5d0-8399db31ea1f" />


- Name it "Business Critical Outage".
- Parent Topic: Report a problem.
- Click "Add Topic"
</p>
<br />

<img width="80%" height="80%" alt="30" src="https://github.com/user-attachments/assets/ff0641b5-e4fa-4876-931c-2ab2a1bf4607" />


- Add another Help Topic.
- Name it "Personal Computer Issues".
- Parent Topic: Report a problem.
- Click "Add Topic"
</p>
<br />

<img width="80%" height="80%" alt="31" src="https://github.com/user-attachments/assets/b946db14-6960-4876-b080-70873c749fa0" />


- Add another Help Topic.
- Name it "Equipment Request".
- Parent Topic: General Inquiry.
- Click "Add Topic"
</p>
<br />

<img width="80%" height="80%" alt="32" src="https://github.com/user-attachments/assets/6ab587af-9ded-41cc-8359-65a2caab5b43" />


- Add another Help Topic.
- Name it "Password Reset".
- Parent Topic: Report a problem.
- Click "Add Topic"
</p>
<br />

<img width="80%" height="80%" alt="33" src="https://github.com/user-attachments/assets/c62ef9be-86b8-41a1-8acf-03adeb9a07a1" />


- Add another Help Topic.
- Name it "Other".
- Parent Topic: General Inquiry.
- Click "Add Topic"
</p>
<br />
