<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configurations</h1>

This tutorial outlines post-installation configurations of the open-source help desk ticketing system osTicket.<br />

**Must Know** - The "Instructions" assumes that you have installed osTicket and are logged in as an employee. 

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Post-Install Configuration Objectives</h2>

- Configure a "Supreme Administrator".
- Configure a "System Admininstrators" unit in Departments.
- Configure a "Level I Support" team. 
- Configure a SLA metric for ticket assignments.
- Configure a "Help Topic" for FAQ.
- Configure an "Agent" for ticket assignments.
  
<h2>Instructions</h2>

- **Configure a "Supreme Administrator".**
  - Click on "Admin Panel" tab:

    *Agents -> Roles -> Add New Role*

    ![Screen Shot 2023-07-24 at 3 40 15 PM](https://github.com/AIweave/osTicket-Post-Installation-Configuration/assets/121763338/56dcfdd3-1eea-4396-92ad-3cd5fcf60e0b)

- **Configure a "System Admininstrators" unit in Departments.**
  - Click on "Admin Panel" tab:
    
    *Agents -> Departments -> Add New Department*

    ![Screen Shot 2023-07-24 at 3 39 34 PM](https://github.com/AIweave/osTicket-Post-Installation-Configuration/assets/121763338/5382a09e-05f3-4909-9875-7cfae8d754e5)

- **Configure a "Level I Support" and "Level II Support" team.**
  - Click on "Admin Panel" tab:
    
    *Agents -> Teams -> Add New Team*

    ![Screen Shot 2023-07-24 at 3 41 14 PM](https://github.com/AIweave/osTicket-Post-Installation-Configuration/assets/121763338/fab83500-4697-457d-ae7e-34a50b3b469e)

- **Configure three SLA metrics for responding to tickets.**
  - Click on "Admin Panel" tab:
  
    *Manage -> SLA -> Add New SLA Plan*

    ![Screen Shot 2023-07-24 at 3 42 24 PM](https://github.com/AIweave/osTicket-Post-Installation-Configuration/assets/121763338/3e477c58-5463-4bbe-9d1e-436b2170d948)


- **Configure a "Help Topics" for FAQ.**
  - Click on "Admin Panel" tab:
    
    *Manage -> Help Topics -> Add New Help Topic*

    ![Screen Shot 2023-07-24 at 3 44 16 PM](https://github.com/AIweave/osTicket-Post-Installation-Configuration/assets/121763338/f6e3dfaf-bc12-4cef-a22b-40b07b37c0ce)


- **Congfigure an "Agent" for ticket assignments.**
  - Click on "Admin Panel" tab:
    
    *Agents -> Agents -> Add New Agent*

    ![Screen Shot 2023-07-24 at 3 45 32 PM](https://github.com/AIweave/osTicket-Post-Installation-Configuration/assets/121763338/d5678a23-84ac-4f28-87da-e8f927141c86)
