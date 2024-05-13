
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Resource Group for Active Directory
- Create a Domain Virtual Machine (Windows Server)
- Create the Client Virtual Machine (Windows 10)
- Install Active Directory on Domain Server
- Create Organizational Units and Users in Active Directory


<h2>Deployment and Configuration Steps</h2>
Create Resource Group for Active Directory

![image](https://github.com/Traviskthomas/configure-ad/assets/166442537/7b200155-31dd-4709-8167-ec4e5274a397)

Create a Domain Virtual Machine (Windows Server)

![image](https://github.com/Traviskthomas/configure-ad/assets/166442537/c4cf1bb8-6770-48c7-83bf-a9941a0bc414)




Create the Client Virtual Machine (Windows 10)

![image](https://github.com/Traviskthomas/configure-ad/assets/166442537/102fe072-4bed-463c-8f99-8ec654bfb6d1)

![image](https://github.com/Traviskthomas/configure-ad/assets/166442537/7554fd50-e5f4-42bb-b7f5-db669d05c1eb)

![image](https://github.com/Traviskthomas/configure-ad/assets/166442537/bcb96f16-b19a-42a1-a4b4-0b6dba194c1c)

Install Active Directory on Domain Server

![image](https://github.com/Traviskthomas/configure-ad/assets/166442537/301b709c-ea2e-4055-a98c-99517564a3f5)

  -Restart and then log back into Dc-1 as user: mydomain.com\(username)

  ![image](https://github.com/Traviskthomas/configure-ad/assets/166442537/1974c486-eb5c-49ea-9505-522fc87366ed)



