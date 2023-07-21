# OSticketPostInstallation
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

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (Customers)
- Configure SLA
<h2>Configuration Steps</h2>

<p>
<a href="https://imgbox.com/QJjCAd7n" target="_blank"><img src="https://thumbs2.imgbox.com/83/cd/QJjCAd7n_t.png" alt="image host"/></a></p>
<p>
Step 1: Using OSticket, navigate to the admin Panel, then agents, and then roles. Enable a supreme admin by checking all the permissions.
<p>
<a href="https://imgbox.com/dzyK7NyF" target="_blank"><img src="https://thumbs2.imgbox.com/73/f6/dzyK7NyF_t.png" alt="image host"/></a></p>
<p>
Step 2: Navigate to departments, going through the admin panel in os ticket, click agents, then departments. Click create new department and create a department called System administrators. </p>
<br />

<p>
<a href="https://imgbox.com/KAr9CfH0" target="_blank"><img src="https://thumbs2.imgbox.com/f4/18/KAr9CfH0_t.png" alt="image host"/></a></p>
<p>
Step 3: Go into Admin panel, under agents, then navigate to teams. Create two teams, one named "level 1 support" and the other "level 2 support". </p>
<br />
<a href="https://imgbox.com/ywhrH5Jw" target="_blank"><img src="https://thumbs2.imgbox.com/60/79/ywhrH5Jw_t.png" alt="image host"/></a>
Step 4: This step will allow anyone to create tickets. In the admin panel, go to settings, then user settings, make sure that the "registration required: Require registration login to create tickets" is unchecked.
<a href="https://imgbox.com/eQWMuQva" target="_blank"><img src="https://thumbs2.imgbox.com/fb/0b/eQWMuQva_t.png" alt="image host"/></a>
Step 5: In the admin panel, under agents click "add new", hear you can create new agents to use osticket to troubleshoot problems that are received via ticket.
<a href="https://imgbox.com/5ZfcXDdT" target="_blank"><img src="https://thumbs2.imgbox.com/32/ee/5ZfcXDdT_t.png" alt="image host"/></a>
Step 6: In the Agent Panel, under user click "add new", this gives you the ability to create new users.
<a href="https://imgbox.com/BeCEGR29" target="_blank"><img src="https://thumbs2.imgbox.com/dd/1c/BeCEGR29_t.png" alt="image host"/></a>
Step 7: SLA stands for "service level agreement", this is defined as a contract between a service provider and a customer. In the admin panel, under manage click "SLA", here you can create new SLA's and adjust specific details of each SLA such as total time to complete. 
<a href="https://imgbox.com/g9tV6lX9" target="_blank"><img src="https://thumbs2.imgbox.com/16/33/g9tV6lX9_t.png" alt="image host"/></a>
Step 8: In the admin panel, under manage click "help topics", here you can add help topics such as "personal computer issues" or "password reset", in order to allow users to help themselves.
