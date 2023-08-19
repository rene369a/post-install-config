<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Mac OS (user)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 01 07 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/aec0b173-ea41-463d-bcd4-bd1ec4589d7d">
</p>
<p>
- Login to osTicket with the username and password we created.

  - Login page: (http://localhost/osTicket/scp/login.php)
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 04 58 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/15b82509-b04f-47e3-9721-1ea3a679350c">
</p>
<p>
- This is the Admin Panel, where we can start our configuration of osTicket
</p>
<br />

<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 11 41 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/3e420016-32e9-4cec-8f71-2acac5ef0aac">
</p>
<p>
- Configure Roles

  - AdminPanel->Agents->Roles
  - Name: SupremeAdmin ->Allow all Permissions, Add Role
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 14 08 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/db8a8f1f-f744-4a0d-ab55-7c10b63c7874">
<img width="1670" alt="Screenshot 2023-08-19 at 1 15 01 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/173454b8-2294-4895-af5d-ec2e71bbe542">
</p>
<br />

<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 17 40 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/1dd2d23f-f95e-43b7-8a5c-91988f3847c2">
</p>
<p>
- Configure Departments

  - AdminPanel->Agents->Departments
  - Name: SystemAdministrators
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 18 14 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/6b932388-7556-4300-9caa-6e7bb77ea587">
</p>
<br />

<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 27 01 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/8735e960-c38c-4a06-ae70-ada615f03837">
</p>
<p>
- Configure Teams

  - AdminPanel->Agents->Teams
  - Name: Level II Support
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 29 27 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/2a21fa71-8454-4472-b768-2b833d082622">
</p>
<br />

<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 31 46 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/16a1c608-7d62-4a49-bb3d-0ed4a76ce27d">
</p>
<p>
- Let's allow anyone to create tickets

  - Make sure "Registration Required" not checked.
</p>
<br />

<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 34 08 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/ea80cc04-ee30-4796-af35-7a2cb9163cd7">
</p>
<p>
- Configure Agents (workers)

  - AdminPanel->Agents->AddNew
</p>
<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 42 09 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/64f9ccfb-5140-4ab6-b2bb-977e405b0542">
</p>
<p>
- Create a username and password

  - Allow Access
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 36 20 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/a29c290c-e00d-47b6-849d-12e24ff40e01">
<img width="1670" alt="Screenshot 2023-08-19 at 1 36 43 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/83405da7-87a6-403e-a4a6-bd8769d031d6">
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
