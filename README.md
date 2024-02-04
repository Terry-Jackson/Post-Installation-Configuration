<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


</h2>

<br>
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
<br>

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
<br>

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles 
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
<br>

<h2>Configuration Steps</h2>
<br>

  ![Click on add new Roles 2](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/aeb4e700-f803-4e99-83ab-ce9d23b98934)

We will start by adding a new role. Click on Agents tab first and next add a new role.
</p>
<br />

<p>

  ![3](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/3ff39d4f-66ec-4162-a838-4a531c09de97)

On this step we will add (Supreme Admin) as a role. Then from there we will click onto permissions.
</p>
<br />

<p>

  ![4](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/405113a5-8d35-40bf-9eeb-5bc2d36a2e03)

</p>
<p>
You will see three more Tabs labeled Tickets, Task, and Knowledgebase. We will set the abilities for this role by checking the boxes. For this role and this project we are checking all the boxes within the Tickes, and Task tab.
</p>
<br />

![5](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/3d9e21a4-8326-4762-88ad-5ad12cd75f4c)

<br>
The Supreme Admin Role was successfully added.


<br>
<br>
<br>

![6](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/5dc690ec-527b-4343-a863-184317d740ac)
<br>

Click on the Departments Tab. From there we will click onto add new Department.

<br>


<br>

![7](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/44725b2e-6c77-4595-a71c-27f7a6c234bc)

<br>
The System Administrators department was successfully added.

<br>
<br>
<br>

![8](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/1850fdec-9bfe-4e08-ae97-381fb4ed56ab)
<br>
<br>
Next I am going to add a new Team by clicking onto Teams Tab. Then Click onto add new Team. 
<br>
<br>

![10](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/18949139-07d3-4d18-9ea7-6921e6ddacd9)
<br>
<br>
We have created a Level II support for this team.
<br>
<br>
<br>

![11](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/61ca4bde-6df6-4039-9f66-4553eeb227bf)
<br>
<br>
Click on settings and from there proceed to Users. Under Authentication Settings we will check on Require Registration and 
login to create tickets. Save the Changes.
<br>
<br>
<br>

![12](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/2e84e5a1-6c9c-404c-8f76-2f6d760e5777)
<br>
<br>

User settings were successfully updated.
<br>
<br>
<br>

![13](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/81e59da9-e8bb-4fdb-ad39-8e35de196a8f)
<br>
<br>
We are going to add a new agent now. Click on the add new agent Tab.
<br>
<br>
<br>

![14](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/2ca60510-fe49-46b6-990d-42fb1a369924)
<br>
<br>
We are creating a new admin account. Fill out the name and email address. Then we will go into and set the password.
<br>
<br>
<br>

![15](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/0e0dfc3a-2546-4afa-9cd2-0536c8dae2ef)
<br>
<br>
In this step we will set the password for the agent.
<br>
<br>
<br>

![16](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/11ee3ecd-4c10-4a7d-9b08-7f0dae91374c)
<br>
<br>
Click on the Access Tab. I will assign the Agent the departments they will have control over.
<br>
<br>
<br>
![17](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/1d296aa5-c4db-4c58-b3f4-4c1d8e4c29e6)
<br>
<br>
Lastly, I will assign this agent to a team and click create.
<br>
<br>
<br>
![pic18](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/3dd6b36c-bd13-4d7d-a583-487f7b0f0f17)
<br>
<br>
Now we are going to add a new User (customers).
<br>
<br>
<br>
![pic 19](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/e1e4e0f0-5918-4e6f-b074-3808024056a7)
<br>
<br>
On this tab we are going to input the User information and add them to the system.
<br>
<br>
<br>
![Pic20](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/6571c900-59c5-4150-aa3a-8d90a14f065d)
<br>
<br>
Moving on to set the severity levels for (SLA), Click on the manage tab. From there we will click on SLA.
<br>
<br>
<br>
![pic 21](https://github.com/Terry-Jackson/Post-Installation-Configuration/assets/155121596/3973f4f7-d55d-4165-905e-b5ad4910326d)
<br>
<br>
SLA-A severity is critial. Meaning system is down and has a grace period of one hour on 24/7 schedule.
<br>
SLA-B severity is moderate. Grace period of four hours on 24/7 schedule.
<br>
SLA-C This has a a grace period of eight hours. Monday - Friday 8AM - 5PM with U.S. Holidays
<br>
<br>






