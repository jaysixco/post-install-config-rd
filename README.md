# osTicket_postinstall

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<strong>Part 3 (Post Installation Setup)</strong>

<strong> Go to this link http://localhost/osTicket/scp/login.php (it will take you to the login page) </strong>

<strong> Login </strong>
- Type the username and password you created in the "Name the Helpdesk" section of the prerequisities and installation github <br>
- For me <br>
  - Username: Jay <br>
  - Password: Password1 <br>
<img width="268" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/42b477f0-c459-4439-b655-01dec786b5ea">

osTicket homepage: <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/17aa4caa-dd9d-4812-a673-82b110eb7767">

Admin panel: <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/8e629b45-b8ee-4f4e-90ac-5f20e2505d7c">
<br>

Agent panel: <br>
<img width="653" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/f27a3f73-91de-4fe1-bf6f-241a0e6e83ad">
<br>



<strong>Configure Roles </strong> <br>
Admin Panel -> Agents (the one next to "Emails" -> Roles <br>
Supreme Admin <br>
 - Click Add New Role> <br>
Name: Supreme Admin> <br>
Click Permissions Tab > <br>
Give them permission to do everything (check every box under every tab - Tickets, Tasks, Knowledgebase) <br>
Click Add Role
  
<strong> Configure Departments </strong> <br>
Admin Panel -> Agents -> Departments <br>
System Administrators <br>
 - Click Add New Department> <br>
Name: System Administrators> <br>
Click "Create Dept" <br>

  
<strong>Configure Teams </strong> <br>
Admin Panel -> Agents -> Teams <br>
 - Click Add New Team> <br>
Name: Level II Support> <br>
Members tab> <br>
Click ourselves (but don't click add? for some reason)> <br>
Create Team <br>
Level I Support <br> 
Level II Support <br>
  
<strong>Allow anyone to create tickets </strong> <br>
Admin Panel -> Click Settings -> Click Users <br>
Make sure "Registration Required: Require registration and login to create tickets" is unchecked <br>


<strong>Configure Agents (workers) </strong> <br>
Admin Panel -> Agents -> Add New <br>

Jane <br>

 - Name: Jane Doe <br>
Email Address: jane.doe@osticket.com <br>
Username: jane.doe <br>

 - <b> Set password> <br> </b>
Click "Set Password" > Uncheck the box next to "Send the agent a password reset email" > Type a password
Password: Password1 <br>
Uncheck "Require password change at next login"> <br>
Click Set

 - <b>Access Tab> <br> </b>
Click the Access Tab (under "Add New Agent" heading, to the right of "Accounts" tab) > <br>
Under Primary Department, click the arrow in the box that says, "Select Department" > Select System "Administrators" > click the arrow in the box that says, "Select Role" > Select "Supreme Admin"

 - <b>Teams tab> <br> </b>
Level II Support (dont click Add)> <br>
Click create <br>

John <br>
 - Name: John Doe <br>
Email Address: john.doe@osticket.com <br>
Username: john.doe <br>

 - <b>Set password> <br> </b>
Click "Set Password" > Uncheck the box next to "Send the agent a password reset email" > Type a password
Password: Password1 <br>
Uncheck "Require password change at next login"> <br>
Click Set

 - <b>Access Tab> <br> </b>
1st bar: Support <br>
2nd bar: View only <br>
Extended Access bar: Support> <br>
Click "Create"
  
<strong>Configure Users (customers) </strong>  <br>
Agent Panel -> Users -> Add New  <br>

<b> Karen  <br> </b>
 - Name: Karen@osticket.com <br>
Full name: Karen Karen> <br>
Add New

<b> Ken <br> </b>
 - Name: Ken@osticket.com <br>
Full name: Ken Ken> <br>
Add New
  
<strong>Configure SLA </strong>  <br>
Admin Panel -> Manage -> SLA  <br>

Sev-A (1 hour, 24/7)  <br>
- Format> <br>
Name: SEV-A <br>
Grace Period: 1 <br>
Schedule: 24/7 <br>

Just plug in with all the rest.

The example above is just an example, by the way, and really unreasonable in the real world. It's basically saying that if a ticket comes in at 10am on a Sunday, the issue must be resolved by 11am. Very unreasonable because some IT workers could still be in church.

Sev-B (4 hours, 24/7)  <br>
Sev-C (8 hours, business hours)

<strong>Configure Help Topics </strong> <br>
Admin Panel -> Manage -> Help Topics <br>

Add New> <br>
ALL you're doing is copy and pasting the names below into Topic bar, then clicking add below, and then save changes (<em>just experimented - you don't need to click save changes</em>). DON'T type or change or add anything else.

 - Business Critical Outage <br>
 - Personal Computer Issues <br>
 - Equipment Request <br>
 - Password Reset

</p>
<br />
