<p align="center">
<img src="https://i.imgur.com/KzJbWRS.png" height="45%" width="45%" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This demonstration outlines the post-install configuration of the open-source help desk ticketing system "osTicket".<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- [osTicket Documentation](https://docs.osticket.com/en/latest/index.html)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<h3>&#9312; Prerequisites and Installation</h3>

_This tutorial assumes you have already established a virtual machine with the prerequisite files installed for working osTicket._ </br>
_Credentials and configurations that will be used in this tutorial can be found in the ["Prerequisites and Installation"](https://github.com/JTYKolesar/osticket-prereqs) demonstration._ </br>
_* NOTE: The osTicket system might randomly logout your account, so just login again if that happens._
<hr>

<h3>&#9313; Configuration: Admin Panel</h3>

- On the web browser (Microsoft Edge), go to the Help Desk Login Page and sign into your osTicket Help Desk credentials (this example uses username **ostuser / ostuser@email.com**).
  - Help Desk Login Page -- http://localhost/osTicket/scp/login.php
<p>
<img src="https://i.imgur.com/2NAyZo5.jpg" height="100%" width="=100%" alt="Disk Sanitization Steps"/>
</p>

_We're going to access the "Admin Panel" and create Roles, Departments, and Teams:_
- Currently at the Agent Panel, click on "Admin Panel" at the top-right of the window.
<p>
<img src="https://i.imgur.com/dByQbR1.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Click on the "Agents" tab > "Roles" > "Add New Role".
<p>
<img src="https://i.imgur.com/mjTZZ5h.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- In the Definition tab, type any Role name of your choice (this example uses **Supreme Admin**).
  - _This role will be given all permissions._
- Then, click on the Permissions tab.
<p>
<img src="https://i.imgur.com/U8vxJEe.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- In the Permissions tab, under the Tickets category, checkmark ALL boxes.
  - Go through both Tasks and Knowledgebase categories and checkmark ALL boxes as well.
- Once done, click "Add Role".
<p>
<img src="https://i.imgur.com/iJGy3L6.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

_Now we've created a Supreme Admin role with all permissions granted. Next, we'll create a Department._
- Currently in the Agents tab, under Roles category, click on "Departments" category.
- Click "Add New Department".
<p>
<img src="https://i.imgur.com/vdafrXs.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Create a Department name of your choice (this example uses **System Administrators**).
- Skip everything else for now and click "Create Dept".
<p>
<img src="https://i.imgur.com/Uoji0y5.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>(ﾉ^ヮ^)ﾉ*:・ﾟ✧ COMPLETE! ✧ﾟ・:*╰(^ヮ^╰)</h1>
