<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=WRr7XhbUlJg)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>
 
- Create Virtural Machine in Azure  
- Remote Desktop 
- Downlaod Files for OsTciket 
- Create Admin account for OsTicket 
- Run a new PHP 

- <h2>Installation Steps</h2>

<p>
<img src=https://i.imgur.com/DZJZ37P.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I will first go to PortalAzure.com to connect into Azure, then I will create a Recourse group and give it the name RG-osTicket.
</p>
<br />

<p>
  <img src=https://i.imgur.com/jaBq0D9.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I will proceed to construct a virtual machine after creating the resource group. Then I'll add the virtual machine VM-Osticket and the resource Group we made with the name RG-oTicket. I'll then pick the US-3 Region where I am located. Then select a Windows 10 image for the virtual computer. Create a Username and Password next, after which the networking will be conducted, click the Create button.
</p>
<br />

<p>
<img src=https://i.imgur.com/A8tAyVT.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that I've clicked the virtual machine, I can access its settings, copy the public IP address, and then launch remote desktop on my computer and input the public IP address.
</p>
<br />
<p>
<img src=https://i.imgur.com/q2jXQij.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once logged in to the remote desktop, I'll enable IIS (Internet Information Services) in Windows 10 with CGI, which is a web server that enables this computer to host websites because osTicket runs off websites. I'll now select RUN from the menu by right-clicking the Windows symbol in the lower-left corner, type in control, and select Programs.
</p>
<br />

<p>
<img src=https://i.imgur.com/SoCUYoX.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/dSC0aer.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As soon as I click Programs, I choose the option to Turn Windows Features On or Off. I next click Internet Information Services, expand it with the plus sign, expand World Wide Services, and finally extend Application Development Features. then click the CGi Box icon, and it should install.
</p>
<br />

<p>
<img src=https://i.imgur.com/bkOiXnT.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once that was set up, I opened a browser window and typed in 127.0.0.1, the local host page, as a quick test. When it opens, it signifies you done everything correctly and everything is working.
</p>
<br />

<p>
<img src=https://i.imgur.com/V0Ngani.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/WbZbrsI.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/GXCY1by.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then, by clicking the link and selecting the download option, I'll download all the files that need to be downloaded, starting with the PHP manger IIS File. When that downloads, I'll open the Windows Explore window at the bottom of my screen, select Downloads, and check to see if the PHP file has already been downloaded there. Here is where all the files that need to be downloaded will go. You will double-click the PHP Manger IIS file to install it on your computer once it has been downloaded to Windows Explore.
</p>
<br />

<p>
<img src=https://i.imgur.com/0XdtXoB.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/rSaOIwb.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I'll then download the Rewrite Module and check to see if it has uploaded using Windows Explore. As soon as I see that it has been received, I'll double-click it to install it on the computer.
</p>
<br />

<p>
<img src=https://i.imgur.com/ynjogbl.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/9HQEoa8.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step will be to create a directory for PHP by going to Windows Explore and typing C into the search box. This will take me to Windows C, where I will create a new folder and call it PHP before completing the process.
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
