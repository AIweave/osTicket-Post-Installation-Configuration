<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configurations</h1>
This tutorial outlines some post-install configurations of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Post-Install Configuration Objectives</h2>

- Configure a "Supreme Administrator"
- Configure a "System Admininstrators" unit in Departments
- Configure a "Level I Support" and "Level II Support" team. 
- Configure three SLA metrics for responding to tickets.
- Configure a "Help Topics" for FAQ.
- Congfigure an "Agent" for ticket assignments.
  
<h2>Instructions</h2>

- **Configure a "Supreme Administrator"**
  - Click on the "Roles" tab:
    *Admin Panel -> Agents -> Roles*
    Supreme Admin

    (picture)

- **Configure a "System Admininstrators" unit in Departments.**
  - Configure Departments
    *Admin Panel -> Agents -> Departments*
    System Administrators

    (picture)

- **Configure a "Level I Support" and "Level II Support" team.**
  - Configure Teams
    *Admin Panel -> Agents -> Teams*
    Level I Support
    Level II Support

    (picture)

- Configure three SLA metrics for responding to tickets.
    - Configure SLA
    Admin Panel -> Manage -> SLA
    Sev-A (1 hour, 24/7)
    Sev-B (4 hours, 24/7)
    Sev-C (8 hours, business hours)

    (pic)

- **Configure a "Help Topics" for FAQ.**
  - Configure Help Topics
    Admin Panel -> Manage -> Help Topics

    (pic)

- **Congfigure an "Agent" for ticket assignments.**
   Configure Agents (workers)
    Admin Panel -> Agents -> Add New
    Jane
    John
