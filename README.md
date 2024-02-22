<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket - Post-Install Configurations</h1>
This tutorial demonstrates the necessary changes I made to configure osTicket so it can be used as a proper ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)


<h2>Configuration Steps</h2>
<p>After the installation of osTicket, I am now moving on to configuring the ticketing system. I've navigated between the admin and agent panels as each offers distinct settings. To initiate the configuration for the Supreme Admin role, I clicked on the 'Admin' option at the top right of the osTicket page. Once the page loads, I will proceed to 'Agents' and then 'Roles,' where I've created the Supreme Admin role and assigned all relevant permissions.</p>
<p align="center">
<img src="https://i.imgur.com/WYgZTPT.png" height="60%" width="60%" />
</p>
<p align="center">
<img src="https://i.imgur.com/wwnVuhF.png" height="60%" width="60%" />
</p>
<p>Next, I will establish a new department specifically for System Administrators. Within the Admin panel, I have navigated to the agent’s menu and go on to create a new department in osTicket.</p>
<p align="center">
<img src="https://i.imgur.com/s0GB5Yc.png" height="60%" width="60%" />
</p>
<p align="center">
<img src="https://i.imgur.com/RA5msSU.png" height="60%" width="60%" />
</p>
<p>I am creating a new level II support team to supplement the level I support team that was already made in osTicket. To create a new team, I access the admin panel, go to the agents menu, click on 'Teams,' and add the new teams.</p>
<p align="center">
<img src="https://i.imgur.com/47wKBUt.png" height="60%" width="60%" />
</p>
<p>New agents are now being created so that they can handle incoming tickets in the queue. To create these agents, I have clicked the admin panel, opened the agents menu, and selected 'Add New Agent.' I have created account credentials for the new agents, namely Jane and John Doe.</p>
<p align="center">
<img src="https://i.imgur.com/pf3Y8uM.png" height="60%" width="60%" />
</p>
<p>I am now establishing new users who will be responsible for creating tickets, by allowing agents to receive and triage them. To start this, I clicked on the Agents panel, and opened the Users menu. I have clicked on 'Add User,' and set up the required account credentials for each new user. Specifically, I have created accounts for Karen and Ken in this instance.</p>
<p align="center">
<img src="https://i.imgur.com/Yn6eMDu.png" height="60%" width="60%" />
</p>
<p>Finally,To categorize tickets based on their impact levels, it is necessary to establish Service Level Agreements (SLAs). To create new SLAs, I accessed the admin panel, opened the manage menu, and clicked on 'SLA.' I then proceeded to create the required SLAs. In this instance, I've created SEV-A, B, and C to classify tickets that require resolution within 1 hour, 4 hours, and 8 hours, respectively.</p>
<p align="center">
<img src="https://i.imgur.com/p8chd1c.png" height="60%" width="60%" />
</p>
<p>Thanks for stopping by!</p>
