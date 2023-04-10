<p align="center">
<img src="https://i.imgur.com/ZOUm27S.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration and Usage</h1>
This tutorial outlines the post-install configuration and some of the usage of the open-source help desk ticketing system. We will essentialy show here how we can work in osTicket system as an Admin by creating users, departments, setting up and giving permission levels.on one hand and how we can actually act as a profesional helpdesk responding to tickets and resolving issues on the other hand.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket (Help Desk Ticketing System)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps:</p>
</p>
</p>
Please, note that all the bellow manip are as Admin.</p>
</p>
Step 1. Configure Roles: </p>

* Admin Panel -> Agents -> Roles <p>
* Let's create for testing purposes the role: "Supreme Admin" and assign permissions
<p>
<img src="https://i.imgur.com/AwHdoR1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/9BNByGM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p> 
Step 2. Configure the Departments: </p>
 
* Admin Panel -> Agents -> Departments <p>
* Let's create for testing purposes the department: "System Administrators"
<img src="https://i.imgur.com/XpDoBW6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 3. Configure Teams: </p>

* Admin Panel -> Agents -> Teams <p>
* Let's create for testing purposes a New Team: "Level II Support"
<img src="https://i.imgur.com/dteHRmL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 4. Allow anyone to create tickets: </p>

* Admin Panel -> Settings -> Users -> Users Settings <p>
* Registration Required: Require registration and login to create tickets
<p>
<img src="https://i.imgur.com/oAKkhUb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Step 5. Configure Agents (Workers who will work on the tickets): </p>

* Admin Panel -> Agents -> Add New Agent <p>
* New Agent created: Jane Doe
<p>
<img src="https://i.imgur.com/VyGVYrg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step 6. Configure Users Directory (customers): </p>

* Agent Panel -> Users -> User Directory -> Add User <p>
* New User created: Asia Asia
<p>
<img src="https://i.imgur.com/rYSWIzS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
 Step 7. Configure SLA (Service Level Agreements): </p>

* Admin Panel -> Manage -> SLA -> Add New SLA <p>
* For testing purposes, let's create three SLA: <p>
Sev-A (1 hour, 24/7)<p>
Sev-B (4 hours, 24/7)<p>
Sev-C (8 hours, business hours)<p>
<p>
<img src="https://i.imgur.com/Rnk8p2N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Step8. Configure Help Topics: </p>

* Admin Panel -> Manage ->Help Topics -> Add New Help Topic <p>
* For the purposes of testing create four topics:<p>
Business Critical Outage<p>
Personal Computer Issues<p>
Equipment Request<p>
Password Reset<p>
<p>
<img src="https://i.imgur.com/KAkwRZ3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/q35AGpu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
 Step9. Allow anyone to create tickets: </p>

* Admin Panel -> Settings -> Users -> Users Settings <p>
* Registration Required: Require registration and login to create tickets
<p>
<br />
