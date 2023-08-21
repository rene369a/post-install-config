<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



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
<img width="1670" alt="Screenshot 2023-08-19 at 1 46 39 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/d685ba49-0357-49d6-8be2-8454c0821958">
</p>
<p>
- Configure Users (customers)

  - AgentPanel->Users->AddNew
  - Swith to the Agent Panel up top
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 47 54 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/6c628361-2ff1-4f16-ac33-996df6031247">
</p>
<p>
- Create a new user
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 50 05 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/8f38b051-0870-4307-a086-fe73cd5034cc">
</p>
<br />

<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 52 29 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/2fdc924b-b510-4c94-bdad-e96514883cd4">
</p>
<p>
- Configure SLA

  - AdminPanel->Manage->SLA
    - Sev-A (1 hour, 24/7)
    - Sev-B (4 hours, 24/7)
    - Sev-C (8 hours, business hours)
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 53 42 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/ba6e0ec2-c81c-4455-8984-c4fe62941abf">
<img width="1670" alt="Screenshot 2023-08-19 at 1 54 44 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/2ca13045-10f3-4015-aca6-1bcae650db19">
  <img width="1670" alt="Screenshot 2023-08-19 at 1 55 41 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/a8f3b910-ac3a-4153-8ba2-2f52ff92299e">
</p>
<br />

<p>
<img width="1670" alt="Screenshot 2023-08-19 at 1 58 18 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/058ad63f-561f-4c2b-9632-c4e139f41e7b">
</p>
<p>
- Configure Help Topics

  - AdminPanel->Manage->HelpTopics
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 1 59 33 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/65912662-92f8-4154-bb70-d8bdeb216eeb">
<img width="1670" alt="Screenshot 2023-08-19 at 2 00 11 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/70d4ed47-0bdc-4f8a-8a28-d6a7aa1c2152">
<img width="1670" alt="Screenshot 2023-08-19 at 2 00 56 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/ded892b9-0738-4684-92e8-afa5b02b8c4e">
<img width="1670" alt="Screenshot 2023-08-19 at 2 01 44 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/3efea74e-d6cf-4448-95b4-a3a313f28103">
</p>
<br />


<p>
- That concludes our osTcket post-install configuration.
</p>
<p>
  <img width="1670" alt="Screenshot 2023-08-19 at 2 03 45 PM" src="https://github.com/rene369a/post-install-config/assets/142533276/e768785c-b554-4291-8cf8-d19d17a5fc19">
</p>
<br />
