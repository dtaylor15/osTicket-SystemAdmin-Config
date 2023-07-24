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

For this example I created a System Administration Department and made myself the manager. I provided this department with  full control of the ticketing system. I set my schedule to 24/7 to allow access during non-operation hours, for emergencies.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
