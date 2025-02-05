<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial provides a comprehensive overview of the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Ticket Lifecycle Stages</h2>

1. Intake
2. Assignment and Communication
3. Working the Issue
4. Resolution

<h2>Lifecycle Stages</h2>

<p>
The following stages illustrate the process that customers or end-users experience when submitting a ticket to the help desk.
  
<img src="https://i.imgur.com/pWVDBue.png" height="80%" width="80%" alt="Ticket Lifecycle Overview"/>
</p>
<p>
</p>
<br />

<p>
Once a ticket is submitted, the customer is notified to confirm that their request has been successfully received.

<img src="https://i.imgur.com/Iiq2Nkg.png" height="80%" width="80%" alt="Ticket Confirmation"/>
</p>
<p>
</p>
<br />

<p>
**1st: Intake**  
Upon logging into the system, the Help Desk Agent/Admin is presented with a dashboard showing available tickets. These tickets may be assigned or unassigned, with each ticket’s priority clearly indicated. A ticket's priority can be set by the Help Desk Agent or the queue manager responsible for managing the tickets. The information displayed includes the following:
- `Ticket Number`
- `Last Updated` timestamp
- `Subject`
- The user who created the ticket `(From)`
- The priority level
- The agent or team to whom the ticket is assigned `(Assigned To)`
  
<img src="https://i.imgur.com/IXUV9qY.png" height="80%" width="80%" alt="Ticket List"/>
</p>
<p>
</p>
<br />

<p>
**2nd: Working the Issue**  
When addressing a critical issue, such as `"entire mobile online banking being down"`, which qualifies as a business-impacting event, the priority of the ticket is updated from the default **"Normal"** to **"Emergency"**. The following steps illustrate the process of changing the priority and updating the ticket's notes:

<img src="https://i.imgur.com/XSU6WLu.png" height="80%" width="80%" alt="Priority Update"/>
</p>
<p>
</p>
<br />

<p>
The ticket has been reassigned to `Jane Doe` from the support team, who was initially unassigned. Additionally, the ticket has been transferred from the **Support Department** to the **System Administrators Department**.

<img src="https://i.imgur.com/Mx9LEYI.png" height="80%" width="80%" alt="Ticket Reassignment"/>
<img src="https://i.imgur.com/lwfOQvH.png" height="80%" width="80%" alt="Department Transfer"/>
</p>
<p>
</p>
<br />

<p>
The updated ticket indicates that it has been assigned to `Jane Doe`, with the priority changed to **Emergency**.

<img src="https://i.imgur.com/D5x8i9e.png" height="80%" width="80%" alt="Ticket Update"/>
</p>
<p>
</p>
<br />

<p>
**3rd: Resolution**  
After coordination with the `System Admin` team, confirmation has been received that the issue has been resolved. The ticket now includes comments detailing the resolution.

<img src="https://i.imgur.com/zFQdUV6.png" height="80%" width="80%" alt="Ticket Resolution"/>
</p>
<p>
</p>
<br />

<p>
Once the ticket has been successfully resolved, it is moved to the **closed** tickets column to indicate its resolution.

<img src="https://i.imgur.com/PM3LH5N.png" height="80%" width="80%" alt="Ticket Closed"/>
</p>
<p>
</p>
<br />
