# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

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
<img width="1882" height="879" alt="Screenshot 2025-07-29 at 8 58 06 PM" src="https://github.com/user-attachments/assets/77fcf43f-fe39-45c0-9f25-cf457302ad4a" />




2.Connect to the VM via Remote Desktop
~Use public IP address and RDP credentials
<img width="1020" height="710" alt="Screenshot 2025-07-29 at 9 09 33 PM" src="https://github.com/user-attachments/assets/88627d87-d5c8-4e33-83a7-150392b8d664" />


3.Download OS Ticket installation 
~Download and extract the provided os Ticket installation files onto the VM's desktop 



4.Enable IIS (Internet Information Services) with CGI 
~Open Control Panel-Programs-Turn Windows features on or off
~Enable IIS and CGI under Application Development Features
<img width="1263" height="856" alt="Screenshot 2025-07-29 at 9 28 35 PM" src="https://github.com/user-attachments/assets/38ec6c80-f802-43d0-bfcb-074ec98ad92c" />




5.Install PHP manager and Rewrite Module
~Use the installers from the lab files folder 
<img width="578" height="466" alt="Screenshot 2025-07-29 at 9 34 49 PM" src="https://github.com/user-attachments/assets/e9cb680e-94b3-4d31-bf4a-8694b659eefe" />


6.Create PHP Folder
~Make C:\PHP ~Extract provided PHP files into it 
<img width="785" height="395" alt="Screenshot 2025-07-29 at 9 36 43 PM" src="https://github.com/user-attachments/assets/3d01ee7a-aa66-421a-a346-1d452055a94f" />




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
<img width="1920" height="1032" alt="Screenshot 2025-07-29 at 9 40 04 PM" src="https://github.com/user-attachments/assets/fdba1748-68be-4270-a2b0-ec21bbe8f596" />


14.Enable PHP Extensions 
~In IIS, enable imap,intl,and opcache via PHP manager 

15.Rename Config File & Set Permissions 

16.Create osTicket Database

17.Complete osTicket Web Setup
<img width="1337" height="670" alt="Screenshot 2025-07-30 at 9 01 24 PM" src="https://github.com/user-attachments/assets/fcaa64b2-ea28-4c21-a7b2-fa2d77266ee4" />

