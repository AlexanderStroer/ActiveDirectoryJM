<h1>Basic Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://www.youtube.com/watch?v=MHsI8hJmggI)

<h2>Description</h2>
This documentation showcases the actions taken to successfully set up Windows Active Directory on a Windows Server 2019 virtual machine hosted on a Windows 10 system via VirtualBox. The project's objective was achieved through virtual machine configuration, network customization, Windows Server installation, network settings configuration, and Active Directory role installation.


<br />


<h2>Languages and Utilities Used</h2>

- <b>Active Directory Domain Services</b>
- <b>Oracle VirtualBox</b>
- <b>Powershell</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server 2019</b>

<h2>Project overview:</h2>
<b>
<p align="center">
Created Virtual Machine<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/2d0e012d-55a5-4c08-bc4b-9ddc9f2165d3">
<br /><br />
Customized Network Adapters<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/a240964c-c593-4b65-8abf-c3cd571c24b1">
<br /><br />
Installed Windows Server 2019<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/d02999cb-2ba7-4ce9-a5cc-4bd6576e8319">
<br /><br />
Conigured Network Settings<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/e199c528-73e7-4f8a-bba3-be44d6fc390c">
<br /><br />
Installed Active Directory<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/40711a4a-f1ff-4b72-ac64-c17b31901f85">
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/bed0497f-833b-4a5c-96e2-509fa493db0e">
<br /><br />
Promoted server to a domain controller<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/c1a3b2b0-6692-4705-b231-ef4bf227b08e">
<br /><br />
Created an Administrator Account to use instead of the default Admin account given by AD<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/af7ab6f9-4749-46cf-a37f-2643e189160b">
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/cbb5b8dd-7315-4543-acec-4dd046e4f649">
<br /><br />
Installed RAS/NAT to allow the Windows 10 client to access the internet through the domain controller<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/cd49dee9-754b-47e5-b81e-406fe36cbd77">
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/c4093021-a999-4a9b-9fb6-4988e441654e">
<br /><br />
Configure DHCP on our domain controller to allow those Windows clients to get an IP address and to access the internet<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/236f3af6-c27a-4ad7-9caa-aae9a584a867">
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/bf543952-8769-4239-b43b-d0c2a237339d">
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/4ff4b759-5c43-43d9-94b6-81c596aa5f5a">
<br /><br />
Use Powershell script to automatically generate a list of users to act as employees<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/3944eb54-1dd0-4244-90a0-5ad3f2e4ba78">
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/5a619981-373f-4f2e-a490-c50387030469">
 <br /><br />
Confirm that the Domain Controller is acting as a DHCP/DNS server by creating a Windows 10 Client on the internal network<br/>
<img width="800" alt="" src="https://github.com/AlexanderStroer/ActiveDirectoryJM/assets/122342684/edb74cff-9857-412d-b7ea-55953dd866d9">
<br /><br />

</b>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
