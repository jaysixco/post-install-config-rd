# osTicket_postinstall

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Summary</h1>
In this tutorial we are going to *configure osTicket.<br />

<em> *Configure means to set up an operation in a particular way. </em>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Google Chrome

<h2>Operating Systems Used </h2>

- Windows 11</b> (22H2)


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

osTicket homepage; click "Admin Panel" to get to the Admin Panel <br> <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/17aa4caa-dd9d-4812-a673-82b110eb7767">
<br>

Admin panel: <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/8e629b45-b8ee-4f4e-90ac-5f20e2505d7c">
<br>

Agent panel: <br>
<img width="653" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/f27a3f73-91de-4fe1-bf6f-241a0e6e83ad">
<br>

Admin-Agents Panel:
<img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/9c9fa47e-c065-4a42-bf32-ed3656077480">
<br>

Admin Panel Dashboard:
<img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/6e3d6e1d-260a-42b7-b222-90e20608bd0f">
<br>



<strong>Configure Roles </strong> <br>
Starting at the Admin Panel -> click Agents (the one next to "Emails" -> <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/8e629b45-b8ee-4f4e-90ac-5f20e2505d7c">
<br>
Click Roles <br>
<img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/9032925b-0910-4aa0-9cfd-9f04f23607bc">
<br>
<strong> Create Supreme Admin </strong><br>
Click Add New Role> <br>
<img width="646" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/09ae8c92-6549-461d-9c51-b7fa56d4ba77">
<br>
For "Name:" type Supreme Admin (1), then click "Permissions" tab (2)> <br>
<img width="646" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/f8300d07-dab4-4cce-9cbf-73f59eaab42d">
<br>
Give them permission to do everything (check every box under every tab - Tickets, Tasks, Knowledgebase) <br>

Check every box under Tickets <br>
<img width="647" alt="tickets (1)" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/932559e2-10bc-463c-afb8-126350d9041d">

Check every box under Tasks <br>
<img width="647" alt="tasks (2)" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/fab506f7-4662-47b5-9f95-05e2c369d189">

Check every box under Knowledgebase and then click "Add Role" <br>
<img width="647" alt="knowledgebase (3) then click add role" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/55ddb2f8-3964-4f8f-ad5a-57e32b3114fc">
<br>
<br>

<strong> Configure Departments </strong> <br>
Starting at the Admin Panel -> click Agents (the one next to "Emails" -> <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/8e629b45-b8ee-4f4e-90ac-5f20e2505d7c">
<br>
Click "Departments" <br>
<img width="648" alt="departments page" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/5b8a4ae0-d001-4d3c-991a-3e27114c99ef">
<strong> Create System Administrators </strong><br>
Click Add New Department> <br>
<img width="645" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/929eed21-5d9a-45e6-90bc-5a504c5944b3"> <br>
For "Name:" type "System Administrators"> <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/6810b7bf-664c-4a85-b089-ac9da3bf0ab0">
Scroll down and Click "Create Dept" <br>
<img width="646" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/afa40ac4-b1e7-447b-b450-07d48e54ea84"> <br>

  
<strong>Configure Teams </strong> <br>
Starting at the Admin Panel -> click Agents (the one next to "Emails" -> <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/8e629b45-b8ee-4f4e-90ac-5f20e2505d7c">
<br>
Click "Teams" <br>
<img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/ddd9a107-ef8f-497b-a18d-27ad07698ec6">
<br>
Click "Add New Team"> <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/3a93c453-6465-4080-a9e3-316036d5bda1">
 <br>
For "Name:" type "Level II Support"(1) then click "Members" tab (2)> <br>
<img width="646" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/9de99252-3818-4cde-8aba-38496ad21cd2"> 
<br>
Click the dropdown menu arrow (1), click our name (2), then click "Create Team" (3) <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/e6a2d019-25da-47f1-b34a-c0f649e72112">
 <br>

  
<strong> Allow anyone to create tickets </strong> <br>
Click "Settings" tab (1), then click "Users" -> <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/8e629b45-b8ee-4f4e-90ac-5f20e2505d7c">
<br>
Make sure "Registration Required: Require registration and login to create tickets" is unchecked, then create "Save Changes" <br>
<img width="648" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/b2477d6c-79f3-4e0c-b519-a44aa9f2d9b5">
<br>


<strong>Configure Agents (workers) </strong> <br>
In the Admin Panel, click "Agents" tab (1), then click "Add New Agent" (2) <br>
<img width="650" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/ee9c3419-8190-4122-adf5-ec4ba2d36654">
<br>

<strong> Create an account for Agent Jane </strong> <br>
For "Name:" type "Jane Doe" (1) <br>
For "Email Address:" type "jane.doe@osticket.com" (2) <br>
For "Username:" type "jane.doe" (3) <br>
Then click "Set password" (4) <br>
<img width="643" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/493a3b4d-0ba2-4a0a-aa28-2823226a4879">
<br>

 - <b> Set Agent Password> <br> </b>
Uncheck the box next to "Send the agent a password reset email" > <br>
For "Password:" type "Password1" (or whatever password you want)  <br>
Retype the password you typed <br>
Uncheck "Require password change at next login"> <br>
Click "Set" <br>
<img width="437" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/a653f390-2632-42c7-9303-1ef32ad66260">
<br>

 - <b>Access Tab> <br> </b>
Click the Access Tab (1), then for the first box select "System "Administrators" (2); then for the second box select "Supreme Admin" (3). When you're done, click "Create" (4) <br>
<img width="644" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/58d2f6af-c636-4efc-93aa-0c03f194ce56">
<br>


 - <b>Teams tab> <br> </b>
Click the "Teams" tab, then click "Level II Support", then click "Save changes" <br>
<img width="650" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/e151bdfd-94bd-4919-95c8-da414e30cd40">
<br>

<strong> Create an account for Agent John </strong> <br>
In the Admin Panel, click "Agents" tab (1), then click "Add New Agent" (2) <br>
<img width="650" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/ee9c3419-8190-4122-adf5-ec4ba2d36654">
<br>
For "Name:" type "John Doe" (1) <br>
For "Email Address:" type "john.doe@osticket.com" (2) <br>
For "Username:" type "john.doe" (3) <br>
Then click "Set password" (4) <br>
<img width="722" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/cb126ec1-8217-4190-bd9e-c4b130aa5604">\
<br>

 - <b> Set Agent Password> <br> </b>
Uncheck the box next to "Send the agent a password reset email" > <br>
For "Password:" type "Password1" (or whatever password you want)  <br>
Retype the password you typed <br>
Uncheck "Require password change at next login"> <br>
Click "Set" <br>
<img width="437" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/a653f390-2632-42c7-9303-1ef32ad66260">
<br>

 - <b>Click the "Access" Tab (1) > <br> </b>
For the first box, select "Support" (2) <br>
For the second box, select "View only" (3) <br>
For the third box, select "Support" (4) <br>
Click "Create" (4) <br>
<img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/ca713807-cdea-4bbc-9130-bed469404012">
<br>
  
<strong>Configure Users (customers) </strong>  <br>
Click "Agent Panel" -> 
<img width="650" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/98a93c30-744e-4f35-921a-ce0076677bd5">
<br>
Click the "Users" tab then click "Add New" <br>
<img width="644" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/5cbf4289-b22c-4fda-afa1-b50c8a438dd3">
<br>

<b> Karen  <br> </b>
Email Address: Karen@osticket.com <br>
Full name: Karen Karen> <br>
Click "Add User" <br>
<img width="436" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/2fef0f2e-480e-4783-a202-c79f1ec4d309">
<br>

<b> Ken <br> </b>
Email Address: Ken@osticket.com <br>
Full name: Ken Ken> <br>
Click "Add User" <br>
<img width="437" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/27abd9b5-ff5c-441d-af51-b737a6578bf7">
<br>
  
<strong>Configure SLA </strong>  <br>
Admin Panel -> "Manage" tab -> "SLA"  <br>
<img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/7468d45c-e972-4205-8f14-b95d7f88b04f">
<br>
Click "Add New SLA Plan" <br>
<img width="643" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/3e633145-ec71-4a9d-9ae7-d26abd83d119">
<br>

Sev-A (1 hour, 24/7)  <br>
Format> <br>
Name: SEV-A <br>
Grace Period: 1 <br>
Schedule: 24/7 <br>
Scroll down and click "Add plan" <br>
<img width="648" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/27fbf6ea-8d28-4a56-a6e7-a1325359189a">
<br>

Just plug in with all the rest.

The example above is just an example, by the way, and really unreasonable in the real world. It's basically saying that if a ticket comes in at 10am on a Sunday, the issue must be resolved by 11am. Very unreasonable because some IT workers could still be in church.

Sev-B (4 hours, 24/7)  <br>
Format> <br>
Name: SEV-B <br>
Grace Period: 4 <br>
Schedule: 24/7 <br>
Scroll down and click "Add plan" <br>
<img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/7db0d869-c0e5-4d53-940f-ce6d4d782cb8">
<br>

Sev-C (8 hours, business hours) <br>
Format> <br>
Name: SEV-C <br>
Grace Period: 8 <br>
Schedule: Monday - Friday 8am-5pm with U.S. Holidays <br>
Scroll down and click "Add plan" <br>
<img width="647" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/07f78d2d-7a5a-486a-99fd-b03bda27b429">

<strong>Configure Help Topics </strong> <br>
Admin Panel -> "Manage" tab -> Click "Help Topics" -> then click "Add New Help Topic" <br>
<img width="644" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/953860a7-ff86-4c43-b1a3-756fab6396cf">
<br>
<br>
For "Topic:" type "Business Critical Outage" (1), click "Add Topic (2), click "Help Topics (3) <br><br>
 <img width="649" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/58633327-b91b-4b0e-8997-747f25ac0637">
<br>
Click "Add New Help Topic" <br>
<img width="644" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/953860a7-ff86-4c43-b1a3-756fab6396cf">
<br>
For "Topic:" type "Personal Computer Issues" (1), click "Add Topic (2), click "Help Topics (3) <br>
 <img width="650" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/ed85be1e-bb94-44e4-af0d-3314b8cbbc93">
<br>
Click "Add New Help Topic" <br>
<img width="644" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/953860a7-ff86-4c43-b1a3-756fab6396cf">
<br>
For "Topic:" type "Equipment Request" (1), click "Add Topic (2), click "Help Topics (3) <br>
 <img width="644" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/022055f9-4dcf-432d-8335-ce006c4ff73f">
<br>
Click "Add New Help Topic" <br>
<img width="644" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/953860a7-ff86-4c43-b1a3-756fab6396cf">
<br>
For "Topic:" type "Password Reset" (1), click "Add Topic (2) <br>
 <img width="654" alt="image" src="https://github.com/jaysixco/post-install-config-rd/assets/160427311/05f775ae-62cc-41b1-9ac0-b2bb50fb44d2">
<br>
</p>
<br />
