<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop/Windows App
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>System Resources</h2>  

- CPU: 2+ cores
- RAM: 2GB minimum
- Storage: 10-20 GB free disk space

<h2>List of Prerequisites</h2>

- Create a Microsoft Azure account
- Microsoft Azure virtual machine (VM) running Windows 10 
- Remote Desktop/Windows App Connection
- Internet Information Services (IIS) installed and configured  
- PHP (version 7.3 or later) installed
- MySQL Server (version 5.5 or later) installed
- HeidiSQL (database management tool)  
- osTicket installation files 


<h2>Installation Steps</h2>
<p>
Begin by creating a Virtual Machine in Microsoft Azure using Windows 10. You will use Remote Desktop/Windows App to connect to your VM using the public IP address and login credentials.   
</p>
<p>
<img src="https://i.imgur.com/rI2fQBV.png" height="80%" width="80%" alt="Create VM on Azure"/>
</p>
<br />

<p>
On your VM, you will download the osTicket-installation files and all required components, including IIS with CGI, PHP, the Rewrite module, VC_redist and more.
</p>
<p>
<img src="https://i.imgur.com/tV3XUa0.png" height="80%" width="80%" alt="IIS,WWS with CGI"/>
</p>
<br />

<p>
Next, we will install MySQL, the database that powers osTicket by securely storing all backend data, including customer information and ticketing records. After SQL you should configure PHP manager and assign permissions.
</p>
<p>
<img src="https://i.imgur.com/K06MQd3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now download the osTicket installation files and move them to your IIS web directory. Then, complete the osTicket setup by accessing it through your web browser. You should be able to finish setup and enable necessary extensions.
</p>
<p>
<img src="https://i.imgur.com/9FoJ5jz.png" height="80%" width="80%" alt="osTicket installer"/>
</p>
<p>
<br />

<p>
You're almost done! Download the HeidiSQL application and connect it to your osTicket database. Congratulations, osTicket is now fully installed and ready to use.
</p>
<p>
<img src="https://i.imgur.com/jKnhGN0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>You are now ready to explore the system, create and assign tickets, complete and resolve tasks, or simply practice as an admin or end user within this powerful ticketing platform.</p>
<br />
