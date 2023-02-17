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
