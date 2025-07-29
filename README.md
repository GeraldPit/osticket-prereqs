# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Account: Accesss to Microsoft Azure for creating virture machines
- Advanced computer skills: Comfort with using Windows, navigating folders, installling software
- Hardware & Software knowledge & lessons: Understanding of hardware basics, operating systems and basic networking
- Virtual Machine Basics: Knowing how to log into a VM using Remote Desktop


<h2>Installation Steps</h2>
1.Create a virtual MAchine VM 
~use windows 10 VM
~Set resources(2-4 vCPU's 8GB RAM)
~Create a username and password




2.Connect to the VM via Remote Desktop
~Use public IP address and RDP credentials

3.Download OS Ticket installation 
~Download and extract the provided os Ticket installation files onto the VM's desktop 



4.Enable IIS (Internet Information Services) with CGI 
~Open Control Panel-Programs-Turn Windows features on or off
~Enable IIS and CGI under Application Development Features




5.Install PHP manager and Rewrite Module
~Use the installers from the lab files folder 

6.Create PHP Folder
~Make C:\PHP ~Extract provided PHP files into it 



7.Install C++ Redistributeable 
~Run installer from the files 


8.Install MySQL 5.5 
~Choose typical Setup ~Set both username and password 

9.Restart PHP in IIS 
~Use PHP Manager in IIS to register C:\PHP\php-cgi.exe

10.Restart IIS 

11.Install osTIcket
~Extract the osTicket upload folder to C:\inetpub\wwwroot
~Rename "upload" folder to "osTicket"

12.Restart IIS Again

13.Test osTicket in Browser 
~Navigate to http://127.0.0.1/osTicket in Microsoft edge 

14.Enable PHP Extensions 
~In IIS, enable imap,intl,and opcache via PHP manager 

15.Rename Config File & Set Permissions 

16.Create osTicket Database

17.Complete osTicket Web Setup
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
