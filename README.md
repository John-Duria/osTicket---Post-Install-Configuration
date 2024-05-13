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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

Configure Roles
•	Navigate to Admin Panel -> Agents -> Roles:
o	Login to your osTicket Admin Panel (http://localhost/osTicket/scp/login.php).
o	Go to Agents in the top menu, then select Roles.
o	Click on Add New Role.
o	Create a role named Supreme Admin with appropriate permissions for administrative tasks.

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/0003b368-22cd-483e-9c6a-7b4723c07508)

For more information about osTicket Role - https://docs.osticket.com/en/latest/Admin/Agents/Roles.html 
2. Configure Departments
•	Navigate to Admin Panel -> Agents -> Departments:
o	Go to Agents in the top menu, then select Departments.
o	Click on Add New Department.
o	Create a department named System Administrators.

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/71a26cd3-9b7d-42b5-b8c2-a63714c122cc)

For more information about osTicket Departments - https://docs.osticket.com/en/latest/Admin/Agents/Departments.html 
3. Configure Teams
•	Navigate to Admin Panel -> Agents -> Teams:
o	Go to Agents in the top menu, then select Teams.
o	Click on Add New Team.
o	Create teams named Level I Support and Level II Support.

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/809ab3b0-e216-4465-96fa-fecc9d6e4673)

For more information about osTicket Teams - https://docs.osticket.com/en/latest/Admin/Agents/Teams.html 
4. Allow Anyone to Create Tickets
•	Navigate to Admin Panel -> Settings -> User Settings:
o	Go to Settings in the top menu, then select User Settings.
o	Under Registration Required, make sure this unchecked Require registration and login to create tickets.

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/94ed3fe7-0b48-40d1-aeea-79a880331dd2)

5. Configure Agents (Workers)
•	Navigate to Admin Panel -> Agents -> Add New:
o	Go to Agents in the top menu, then click Add New.
o	Create agent profiles for workers (e.g., Jane, John) and assign roles and teams.

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/a17fd6d2-5b4c-4780-a609-892c5157f4b5)

For more information about osTicket Agents - https://docs.osticket.com/en/latest/Admin/Agents/Agents.html 
6. Configure Users (Customers)
•	Navigate to Agent Panel -> Users -> Add New:
o	Go to Users in the top menu (Agent Panel), then click Add New.
o	Create user profiles for customers (e.g., Karen, Ken).

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/5e975a9e-385c-40c2-9abe-3fc0d224b111)

For more information about osTicket Users - https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html 
7. Configure SLA (Service Level Agreement)
•	Navigate to Admin Panel -> Manage -> SLA:
o	Go to Manage in the top menu, then select SLA.
o	Click on Add New SLA Plan.
o	Create SLA plans with different response times:
	Sev-A: 1 hour response, 24/7 coverage
	Sev-B: 4 hours response, 24/7 coverage
	Sev-C: 8 hours response, business hours coverage

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/e0c1c7da-f456-4357-96f0-8088339c3eab)

For more information about osTicket SLA - https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html 
8. Configure Help Topics
•	Navigate to Admin Panel -> Manage -> Help Topics:
o	Go to Manage in the top menu, then select Help Topics.
o	Click on Add New Help Topic.
o	Create help topics for different types of issues:
	Business Critical Outage
	Personal Computer Issues
	Equipment Request
	Password Reset

![image](https://github.com/John-Duria/osTicket---Post-Install-Configuration/assets/168502429/ce97738d-26f0-4722-9821-e2efc191c0c8)

For more information about osTicket Help Topics - https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html 
