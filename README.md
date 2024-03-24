<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This page outlines the prerequisites and installation of the open-source help desk ticketing system osTicket on as a broad overview.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Install and Configure IIS
- Set Up PHP
- Install and Configure MySQL
- Download and Deploy osTicket
- Finalize Setup and Cleanup
<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/ZRuz74t.png" height="80%" width="80%" alt="Enabling IIS"/>
</p>
<p>
To run osTicket on IIS (Internet Information Services), you need to enable certain IIS features that support the application's operations. Here's a brief explanation:

CGI: This feature allows IIS to interface with external applications that generate web pages dynamically, which is necessary for PHP processing, a core requirement for osTicket.

Common HTTP Features: These are a set of basic features that support web server functionality, including:

Default Document: Enables IIS to serve a default document (like index.php) when a client requests a directory.

Directory Browsing: Allows users to see the contents of a directory on the web server.

Static Content: Enables the serving of static web pages and files.

IIS Management Console: This is the GUI interface for managing IIS settings and configurations, which is helpful for setting up and managing your osTicket site.
</p>
<br />

<p>
<img src="https://i.imgur.com/rJl8PJy.png" height="80%" width="80%" alt="PHP Manager"/>
</p>
<p>
Setting Up PHP: Registering PHP within IIS to interpret PHP scripts.
  
Configuring PHP: Adjusting settings and enable necessary extensions through the PHP Manager.

Restarting IIS: Applying changes by restarting the web server.

Eensuring that IIS can support osTicket's operations.
</p>
<br />

<p>
<img src="https://i.imgur.com/tWumhDW.png" height="80%" width="80%" alt="OsTicket Post install"/>
</p>
<p>
Here is the osTicket helpdesk system interface with incoming support tickets listed, indicating that the installation and setup process has been successful and the system is now operational. The tickets displayed are open issues submitted by users, which can now be managed, assigned, and resolved within the osTicket platform. It's a good sign that things are up and running as users are actively engaging with the service.
</p>
<br />
