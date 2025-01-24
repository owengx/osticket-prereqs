<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Project Summary</h2>

- Create an Azure Account and Virtual Machine running Windows 10 and at least 4 vCPUs
- Log into the virtual machine by pulling its public IP address and utilizing it to remote desktop into
- Download the OsTicket installation files onto your rdp session
- Proceed through the OsTicket installation wizard
- Continue setting up OsTicket within the browser

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/BRoqTlN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When creating our virtual machine we will select the subscription type, resource group, region, and size of our VM. It is important to take note of the size as it determines factors such as processing power, memory, and storage capacity. 
</p>
<br />

<p>
<img src="https://i.imgur.com/jEwd7bo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the VM has been created, we will take the public IP address and start a remote desktop session. Copy and paste the IP into your session and somewhere else on your computer as it will be utilized later. Open the provided OS ticket installation files in our remote desktop session and begin the installation by extracting the contents.
</p>
<br />

<p>
<img src="https://i.imgur.com/2mNDsYV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install / Enable IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI.
Proceed through the setup wizard. After setup is complete continue setting up Osticket in your browser. You have now installed OsTicket
</p>
<br />

<p>
<img src="https://i.imgur.com/7GhLLRo.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If you completed all the necessary steps properly, you should be greeted with a login page for OsTicket similar to the following image. Good luck!
</p>
<br />
