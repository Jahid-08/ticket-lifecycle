<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- OsTicket


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img width="621" alt="image" src="https://github.com/user-attachments/assets/510f4711-ca03-4aae-ad98-0c52d3e70107" />
<img width="629" alt="image" src="https://github.com/user-attachments/assets/e630a24e-07a7-4b20-97d7-01dcf67476e7" />
</p>
<p>
  
**Simulating Ticket Intake**

We will simulate ticket intake by submitting a ticket from an **end user** to the **support team.**  

To start, go to the landing page where end users submit tickets:  

[http://localhost/osTicket](http://localhost/osTicket)  

From there, we will submit a ticket as a user to observe the process.  

</p>
<br />

<p>
<img width="757" alt="image" src="https://github.com/user-attachments/assets/bc39becc-3a0a-4e8e-973c-bd10d3fa968a" />
  <img width="720" alt="image" src="https://github.com/user-attachments/assets/7947f24b-d52c-44fd-8dde-616815018831" />
</p>

 **Viewing the Ticket as an Agent**

Next, we will log into the portal as one of the agents we created, **John**, to review the submitted ticket.  

Upon logging in, we can see the ticket created by the user **Karen**. As **John**, we will observe the ticket properties to ensure all details are correctly set.  

<p>
<br />

<p>
<img width="712" alt="image" src="https://github.com/user-attachments/assets/5fa03cda-b87c-45aa-87ae-ebbb539acc08" />
</p>
<p>
  
**Setting Ticket Properties**  

Next, we will update the properties of the ticket.  

1. **Update the SLA** to **Sev-A**, the highest priority. This is appropriate since no users can access the online banking portal.  
2. **Update the Help Topic** to **"Report a Problem / Business Critical Outage."**  
3. **Assign the ticket** to the **"Online Banking"** team which we already created.  

As changes are made, updates will populate in the Ticket Thread, tracking modifications for visibility among those with access.  

</p>
<br />

<p>
<img width="492" alt="image" src="https://github.com/user-attachments/assets/25d75a75-0db3-461d-b5d1-e48f975d231a" />
  <br/>
<img width="476" alt="image" src="https://github.com/user-attachments/assets/b0732eff-4e36-41da-a247-0fdc83ba5043" />
</p>
<p>
  
**Ticket Resolution Overview**

We have now simulated working through a ticket as an agent.  

In the **Ticket Thread**, you can see a record of all actions taken. This provides a high-level overview of the ticket-handling process, demonstrating how tickets are managed from submission to resolution. We are now also going to resolve the ticket by setting the status to **Resolve**. After that, the ticket should then dissapear.

</p>
<br />

<p>
<img width="680" alt="image" src="https://github.com/user-attachments/assets/f7258195-c649-4ce4-a072-9ec1590f2b51" />
</p>
<p>
  
## Simulating Another Ticket Process  ##

Next, we will go through another ticket workflow:  

1. **Submit a ticket** as **Ken**.  
2. **Observe and work the ticket** as **John**.

This will demonstrate another hypothetical process from ticket creation to resolution.  
</p>
<br />

<p>
<img width="409" alt="image" src="https://github.com/user-attachments/assets/c26bb586-6253-47fe-a4d9-805d94279e0b" />
<img width="389" alt="image" src="https://github.com/user-attachments/assets/7028e054-e43d-4955-b243-777e7b514747" />
  <br/>
  <img width="264" alt="image" src="https://github.com/user-attachments/assets/4c10de57-9d06-447d-8de9-dbe983cfda02" />

</p>
<p>
  
## Working the Ticket as John  

We will log in as **John** to view and work the ticket.  

### Updates Made:  
- **SLA updated to Sev-B**  
- **Ticket assigned to John**  

John will now continue working the ticket to completion.  
</p>
<br />

<p>
</p>
<p>
  
## Ticket Workflow Summary  ##

These were a few examples of a simple ticket workflow. While there are endless possible scenarios, these quick examples demonstrate the overall process of handling tickets from submission to resolution.  
</p>
<br />
