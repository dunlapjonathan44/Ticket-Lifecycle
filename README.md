<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>

</p>
<p>
In this project, we’ll simulate helpdesk tickets and resolve them step-by-step. Before starting, ensure the Maintenance department is removed to prevent tickets from being routed there. Log in as an admin, go to Agents -> Departments, select Maintenance, click More, and delete it. Now, open a new ticket by visiting http://localhost/osTicket. For this example, create a ticket about a user named Karen, reporting that the company’s mobile/online banking system is down.
<br />

<p>
<img src="https://i.imgur.com/fVAXVHR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/2Fum3iK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
Since this is an online banking issue I will use agents that I created in the Post-Installation Configuration lab. John Doe is capable of working this ticket but Jane Doe is a member of the Online Banking team. Therefore she is the best agent to use in order to work this ticket to completion. I will now log on to the ticket portal using her credentials. Then click on the ticket and under the assign to tab select Jane Doe. If I were working this ticket I would post a reply to the client to let them know that I will have it resolved soon.

 Also since I spoke to Karen and have determined that this issue needs to resolved immediately I will change the SLA plan to Sev-A so that it will be resolved quickly.
  
  <img src="https://i.imgur.com/hUFo3y0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Next Jane discovered that the cause of the outage was the recent update, she resolved the issue and posts to the message board and closes the ticket.

<img src="https://i.imgur.com/idv3uJK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

