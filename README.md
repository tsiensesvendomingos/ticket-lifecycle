<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. This should also exemplify a day at the helpdesk where a user would create a ticket raising their problem. A manager then looks at submitted tickets to determine the actual severity of the ticket and sets its SLA appropriately for the helpdesk staff they assign to  take care of the problem within the set SLA time.  <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working on the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
When one of my users runs into a business-related problem, be it an outage or a computer issue, they would raise a ticket to the helpdesk to have them look at it. They would have to navigate to the helpdesk page. For this ticketing system, they would go to http://localhost/osTicket/, where they can open tickets and check the status of tickets they raised.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/ticket-lifecycle/assets/138411730/4986e6b9-2d68-48e5-bf69-891c71df5156" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
We'll create some tickets to simulate the workflow in the staff portal. For this ticket, the manager of a bank this helpdesk services reported that her customers are having problems accessing their bank info via mobile banking. 
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/ticket-lifecycle/assets/138411730/ed4e446e-0457-4a02-ad9f-a7b1feef6ba8" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Agents will be able to see live tickets in the agent panel. Queue managers will assign priority tickets to the appropriate agents as well as assign proper SLAs.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/ticket-lifecycle/assets/138411730/8f3f50a5-06b2-460c-b389-88e482af8cc1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Once the Quene Manager gets to your ticket, they will review it and determine its priority and what IT department should look into. They will then assign it to a staff member of that department and give it its appropriate SLA Plan.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/ticket-lifecycle/assets/138411730/a5575543-16df-41b0-bbac-4c4e6295d7ea" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Let's say that the root of the problem was found. In this case, the ticket assignee, Jane, can follow up with the customer with the solution that was found and implemented. When it is determined that there is nothing else to do for this ticket, it can be marked as "Resolved" closing the ticket.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/ticket-lifecycle/assets/138411730/27110af5-9fb3-42c3-b959-ce36cf0db69c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
We can then look at the resolved tickets in our 'Closed' tickets.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/ticket-lifecycle/assets/138411730/004c31ab-c5c2-4454-8b22-103d5069c710" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
