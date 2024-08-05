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

<h2>List of Prerequisites</h2>

- Item 1: Download/Install and enable Internet Information Services (IIS) with CGI, Common HTTP features and IIS Management console.
- Item 2: Download/Install PHP Manager for IIS, Rewrite Module and create a folder in directory C:\PHP. When that is done you install put in PHP 7.3.8 to that folder.If you can't download the PHP 7.3.8 you can try downloading it through Google Chrome you might have to download it.
- Item 3: Once you have done step 1 and 2 download/install  vc redist.x86.exe and My SQL 5.5.62. Once you have download set it as Typical setup, Launch configeration wizard( this option will appear after download), Standard configuration, the password would be Password1. Than open IIS but as an admin you want to register the PHP folder from within IIS. When is done you want reload the IIS app. Download osTicket and Extract/Copy the file named UPLOAD to c:-> inetpub-> wwwroot and rename it to osTicket reload IIS again
- Item 4
- Item 5

<h2>Installation Steps</h2>

Internet Informantion Service (IIS) 

<p>
<img src="https://i.imgur.com/97XiUuW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>

Created folder, Named PHP and Inserted PHP 7.3.8
    
<img src="https://i.imgur.com/68ohkbJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When your done installing and enable the IIS you can search 127.0.0.1 that will give the same page as the picture above. That how you will know done it correctly. As soon that you created that folder you should have something like the picture that is above. If don't how to do it you want go to File Explorer-> This PC-> Windows(C:)-> PHP on your Virtual Machine.
</p>
<br />

<p>
  
  Before OsTicket v1.15.8 was installed in IIS
  
<img src="https://i.imgur.com/aPhuo2G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
     After OsTicket v1.15.8 was installed in IIS
    
<img src="https://i.imgur.com/nIrRSOA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
