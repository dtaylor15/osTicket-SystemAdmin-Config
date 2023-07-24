<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - System Administration Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- [osTicket Documentation (View Panel)](https://docs.osticket.com/en/latest/index.html)

## Operating Systems Used

- Windows 10</b> (21H2)
- MacOS Ventura 13.0.1

## List of System Administration Configurations

1. [Helpdesk Roles]
2. [Helpdesk Departments]
3. [Helpdesk Teams]
4. [Helpdesk Agents]
5. [Helpdesk SLA (Service Level Agreements)]
6. [Helpdesk Help Topics]
7. [Helpdesk Users]

## Configuration Steps

### Configure Helpdesk Roles
>**Note:**
>osTicket Roles are a specific set of permissions assigned to helpdesk employees based on the department they are associated with. Organizations can create an unlimited number of roles.

<p>

https://github.com/dtaylor15/osTicket-SystemAdmin-Config/assets/101889571/9d68abda-7acb-46f6-9eb0-0c0c4544b6ab

</p>

<p>
Login with the Admin User credentials configured during installation. 
  
Arrive at Roles: Admin panel -> Agents -> Add new role -> Name the role -> Set the appropriate permissions based on your organization.
</p>
<br />

### Configure Helpdesk Departments
>**Note:**
> Tickets are routed through departments in the helpdesk. Several settings can be configured for each department.

<p>
<img width="501" alt="config_departments" src="https://github.com/dtaylor15/osTicket-SystemAdmin-Config/assets/101889571/7e2dd3b2-5a5a-40b8-9cee-32ced8d912e3">

</p>

<p>
Arrive at Departments: Admin panel -> Agents -> Department -> Complete fields based on your organization. 

For this example, I created a System Administration Department and made myself the manager. I provided this department with  full control of the ticketing system. I set my schedule to 24/7 to allow access during non-operation hours, for emergencies.
</p>
<br />

### Configure Helpdesk Teams
>**Note:**
>Teams organizes helpdesk employees from various departments enabling them to address specific issues or users via Help Topics or Ticket Filters.

<p>
<img width="958" alt="ost_teams" src="https://github.com/dtaylor15/osTicket-SystemAdmin-Config/assets/101889571/ecce4b04-77ba-4a73-9ee3-ff08290e39f8">

<img width="682" alt="addteams" src="https://github.com/dtaylor15/osTicket-SystemAdmin-Config/assets/101889571/2f04a73b-0ce8-4977-80a1-9e33c0d18674">

</p>

<p> Arrive at Teams: Admin panel -> Agents -> Add new team -> Name your team -> Save changes

For this example, I added two teams: Level 1 suppport and Level 2 support (not shown).
</p>
<br />

### Configure Helpdesk Agents
>**Notes**
>osTicket Agents are the helpdesk employees. They service each ticket submitted to the system.

<p> 

https://github.com/dtaylor15/osTicket-SystemAdmin-Config/assets/101889571/10c18eca-d9ef-44f5-be29-867fa3dad46e
</p>

<p> Arrive at Agents: Admin panel -> Agents -> Add new agent -> Enter employee creditials -> Set password -> Set -> Access -> Configure department -> Configure Permissions and Teams applicable to your organization.

For this example, I set a passowrd for this sample agent so I can log in and tutorial a ticket lifecycle. However, standard operations in many organizations require the agent to set their own password at intial log in. <p/>
