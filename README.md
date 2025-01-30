<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial explains the entire lifecycle of a ticket within the osTicket help desk system, covering ticket intake, categorization, assignment, escalation, troubleshooting, resolution, and closure to ensure an efficient and organized support process. <br />

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
<img width="664" alt="Screenshot 2025-01-27 at 15 46 14" src="https://github.com/user-attachments/assets/3dc113cb-2de1-4bd3-bea0-ca5d100944b0" />
</p>
<p>
This lab demonstrates the end-to-end workflow of creating, managing, and resolving tickets in osTicket, providing hands-on experience as both end-users and help desk professionals. The lab begins with some initial system adjustments, such as changing the SysAdmins Department to a top-level department and deleting (not archiving) the Maintenance Department.
</p>
<br />

<p>
<img width="582" alt="Screenshot 2025-01-27 at 15 49 47" src="https://github.com/user-attachments/assets/e9dd300f-1d7b-43ff-8fd7-5604d19c2ba1" />
</p>
<p>
As an end-user, a ticket was created with the issue: "the entire mobile/online banking system is down." This ticket was observed by the help desk agent John, who reviewed its properties, including priority, department, SLA, and assignee. The ticket properties were updated to Sev-A (1-hour SLA, 24/7 schedule) and assigned to the Online Banking Department. John then attempted to view the ticket again but was unable to access it due to department restrictions. The ticket was subsequently resolved by Jane.
</p>
<br />

<p>
<img width="711" alt="Screenshot 2025-01-27 at 15 57 04" src="https://github.com/user-attachments/assets/c99334d6-df4c-4e0c-a09f-11fd6384b032" />
</p>
<p>
Another ticket was created by the end-user with the issue: "the accounting department needs an Adobe upgrade; it’s broken." This ticket was observed by John, who updated its properties to Sev-B (4-hour SLA, 24/7 schedule) and assigned it to the Support Department. John worked the ticket to completion. Similarly, a third ticket was created for the issue: "the CFO’s laptop will no longer turn on." John updated the ticket properties to Sev-B and resolved it within the Support Department.
</p>
<br />

<p>
<img width="664" alt="Screenshot 2025-01-27 at 16 09 36" src="https://github.com/user-attachments/assets/eccd847d-f8bc-4fdf-8c11-b9597b0d5450" />
</p>
<p>
Once all tickets were created, their properties were updated, including escalating a ticket to Sev-A and assigning it to the SysAdmins Department. Observing this ticket became inaccessible to John due to departmental restrictions. Access was restored via the Admin Panel by assigning view permissions to John, allowing him to observe the escalated ticket in the Agent Panel. However, John was still unable to make changes, demonstrating the importance of access control in ticketing systems.
</p>
<br />
