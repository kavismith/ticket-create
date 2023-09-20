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

<h2>Create A Some Tickets</h2>


![image](https://github.com/kavismith/ticket-create/assets/143667203/294edbb4-1ac8-4116-a00a-dc96f0cf836a)

</p>
<p>
Please open the link that end users use to create tickets, and let's proceed to create a ticket as if we were a user. First, we'll create a ticket for Karen Karen with the following information:

- Email: karen@osticket.com
- Full Name: Karen Karen
- Help Topic: Business Critical Outage
- Issue Summary Details: "The entire online banking system is down, and customers are reporting they are receiving a 404-error message when trying to access online banking."

![image](https://github.com/kavismith/ticket-create/assets/143667203/a555d862-3c0c-479a-82fd-093e6384a2e7)

Next, let's proceed to create a ticket for Ken Ken with the following information:

- Email: ken@osticket.com
- Full Name: Ken Ken
- Help Topic: Personal Computer Issues
- Issue Summary Details: "The entire Account Department is experiencing issues with Adobe Reader not functioning. This problem has persisted since the upgrade last night, and nobody in accounting has been able to use Adobe Reader."

![image](https://github.com/kavismith/ticket-create/assets/143667203/ced6934d-42a3-4896-ad77-cddcb58da1d5)

Last, create another ticket from Karen Karen. 
- Email: karen@osticket.com
- Full Name: Karen Karen
- Help Topic: Personal Computer Issues
- CFO's laptop seems a bit slow
</p>
<br />



<h2>Work A Ticket</h2>

![image](https://github.com/kavismith/ticket-create/assets/143667203/3734cb4d-7eb0-4aa5-8b93-e929bfd1a643)
 
Now, let's proceed to log into osTicket as a Help Desk Agent responsible for troubleshooting and resolving tickets. We will begin by logging in as Agent Jane Carter. Upon signing into the account, you will have access to view the tickets.
 
![image](https://github.com/kavismith/ticket-create/assets/143667203/af3215dc-c561-4f35-a579-206ea8750803)

Please select the ticket related to the Online Banking System being down 
  
![image](https://github.com/kavismith/ticket-create/assets/143667203/7fa85e6a-0d87-4ff6-b655-49f6eb60872d)

Set the Priority to: Emergency
![image](https://github.com/kavismith/ticket-create/assets/143667203/bae64e3b-5d92-4a1b-a537-31676fb60b6a)

Assign the ticket to: Jane Carter

![image](https://github.com/kavismith/ticket-create/assets/143667203/0bbbc484-214c-4545-bf63-496ea733218d)

Set the SLA Plan to: SEV-A

![image](https://github.com/kavismith/ticket-create/assets/143667203/567e55e7-5e01-4084-bc5d-e101f5f8a1ea)

Specify the Department as: System Administrator (System admins responsible for mobile banking infrastructure)
  
</p>
<p>
  
 ![image](https://github.com/kavismith/ticket-create/assets/143667203/9c7108a5-2978-415d-bb61-eadd0975e786)
 
After making the necessary changes to the ticket details, you will notice that there is a text thread displaying the breakdown of these modifications, as well as any internal notes. Now, assuming you have the knowledge to resolve the problem, your next step is to collaborate with the Systems Administrators team to formulate a solution. To do this, you can post a reply in the ticket thread, stating, "Coordinating with the Sys Admin Team to bring Online banking back online." This will initiate communication and cooperation with the Systems Administrators team to address the issue and work towards restoring the Online Banking system.
  
</p>
<br />


![image](https://github.com/kavismith/ticket-create/assets/143667203/7adc30a9-6205-4ba3-8206-2061c1ff0977)

</p>
<p>
Now that the online banking issue has been successfully resolved, it's important to provide a follow-up response in the ticket thread explaining the steps taken to fix the problem. You can post a reply similar to the following: "Tiffany from Systems Engineering identified and resolved a failed load balancer. Online banking should now be back up and running."

After providing this update, you can proceed to change the ticket status to "Resolved" to indicate that the issue has been addressed and resolved satisfactorily.
</p>
<br />
