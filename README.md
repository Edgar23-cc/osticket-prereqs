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
- Item 3: Once you have done step 1 and 2 download/install  vc redist.x86.exe and My SQL 5.5.62. Once you have download set it as Typical setup, Launch configeration wizard( this option will appear after download), Standard configuration, the password would be Password1 or Root. Than open IIS but as an admin you want to register the PHP folder from within IIS. When is done you want reload the IIS app. Download osTicket and Extract/Copy the file named UPLOAD to c:-> inetpub-> wwwroot and rename it to osTicket and than reload IIS again.
- Item 4: Once you are done reloading the IIS You want to go in the IIS app and go to sites -> default website -> osTicket  on the right you want to click on "Browse *.80" that will open the osTicket installer page. The next you want to do is go back to IIS app and double click on PHP Manager to enable the following extensions: php_imap.dll, php_intl.dll and  php_opcache.dll all this extensions would be in “Enable or disable an extension” and reload the IIS app.
- Item 5: After you are done with step 4 you can go to "File Explorer-> Windows(C:) -> inetpub -> wwwroot -> osTicket -> include -> ost-sampleconfig.php and rename "ost-sampleconfig.php to ost-config.php". When you finish you want disable inheritance -> remove all and add a new permission -> Everyone -> All than click "**Apply**" and "**OK**". Once you done that you can go back your osTicket installer and hit continue that is where you can do your basic step like name your helpdesk name and create an email. Now you should be downloading Heidi SQL create a new session root and whatever password you have chosen such as _password1_ or _root_ than you want want to create a database and name it "**osTicket**". Continue setting up Osticket use the information used when you where creating the database when have done that you simply click "**Install Now"**. 


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
  
<img src="https://i.imgur.com/lIQlFk8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
     After OsTicket v1.15.8 was installed in IIS
    
<img src="https://i.imgur.com/nIrRSOA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
  OstIcket Installer Not Installed
  
  <img src="https://i.imgur.com/foeIzYz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  OsTicket Installer Installed
  
   <img src="https://i.imgur.com/TFSD8Gu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
    
  Extensions Enabled
    
   <img src="https://i.imgur.com/KaLBBP4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
    
</p>
<br />

Whenever you get to installing the osticket in your IIS app you will see like the first image above and when finish you will see just like the second image. Before you install the osticket check if some of the recommendation are enable. If finish install it and proceed setting up your credential with the database you created in Heidi SQL and you may install it so you can begin to use the app.

<p>

  Administrator's Panel
  
<img src="https://i.imgur.com/aXJyamQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>

 Agent's Panel
 
<img src="https://i.imgur.com/CGxB9oP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
The Admin can manage their tickets/agents and give them assignment to work through the day but the Agents have see what is priorty to get that done first.
</p>
<br />
