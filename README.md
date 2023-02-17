<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket -Preconditions and Installation</h1>
This tutorial outlines the Preconditions and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=WRr7XhbUlJg)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>
 
- Create Resource Group/Virtural Machine in Azure  
- Remote Desktop 
- Downlaod Lab Files for OsTciket 
- Windows Explore  
- 

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
<img src=https://i.imgur.com/5ktL9J6.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/JOcEUx5.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/Hyza6FN.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/Idrvhov.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We're going to add another PHP file to the Windows C PHP file next. Once downloaded, navigate to Downloads in Windows Explorer and right-click the new PHP file to select Extract All. Then, click browser, navigate to Windows C, and select the PHP folder that we created; once that updates and appears, simply click the extract button to download everything into that file.
</p>
<br />

<p>
<img src=https://i.imgur.com/v1hjqd3.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/KEDqDQ2.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that, I'm going to download the File VC-Redist, make sure it's downloaded in Windows Explore, and then click it to install it on the computer.
</p>
<br />

<p>
<img src=https://i.imgur.com/kgidnr4.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/Y7voSDK.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/U3URWK9.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The MySQL file will then be downloaded, and I'll use Windows Explore to install it on the PC. then I will set up the MySQL credentials. I'll create a Root username and password after that.
</p>
<br />

<p>
<img src=https://i.imgur.com/rAI4ZVd.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/oFX67se.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/2VsmQPE.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/MGG5XF6.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I'll then perform some configuration work in IIS as an administrator. Then I'll click the START button and type IIS, but first I'll right-click it and open it as an administrator. I'll notice a handful of the early installations we made when it opens, and then I'll click the PHP icon. I'm going to hit Register New PHP Version now that I'm in PHP. I'm going to open Windows Explore, click the three small dots on the right, navigate to Windows C, choose PHP.cgi, and then click OK.
</p>
<br />

<p>
<img src=https://i.imgur.com/uog7JKd.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/9BIcYK8.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/OIXiuo5.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/p9BgWK4.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/dr6FD4R.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/TIyZatQ.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/q0lWual.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/GITmfP3.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I'll download osTikcet from the installation files, then extract and copy the "upload" folder into C;inetpub/wwwroot. Next, I open Windows Explorer, navigate to Downloads, and then click the osTicket file that was downloaded.   Access another window explore and navigate to Window C, then the Intepub folder, and finally the www-root folder. Then I'll drag the Upload folder from the osTicket file to the www-root folder. Now I'm going to rename the Upload folder to OsTicket.
</p>
<br />

<p>
<img src=https://i.imgur.com/zV9yyOf.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/qrUlMXZ.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/zV9yyOf.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I'm going to open IIS again, click Vm-osTicket, then Sites, then OsTicket folder, then browser, and it should open us up on a website browser with the OsTicket showing; if it doesn't, you'll have to start over because one step was missed.
</p>
<br />

<p>
<img src=https://i.imgur.com/qrUlMXZ.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/0wWCo6M.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/LTQZM6z.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/QYIS15t.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/rPGvZeu.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now I'm going to fix all the extensions that aren't working, so first I'm going to go back into IIS and click On sites, then osTicket, and then double click PHP manager. Then I'll click Enable, Disable, or Add Extension. Following that, I'll enable the following extensions: php imap.dll, php intl.dll, and php opache.dll. After that, you can return to the OsTicket browser and refresh it, and all of the Xs should be gone.
</p>
<br />

<p>
<img src=https://i.imgur.com/2ayQ6rL.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/FtkHITq.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/BDgnuem.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/80dCAzp.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/h8OccZt.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/KZWTzaB.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/KZWTzaB.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We'll now switch to Window C, return to the wwwroot folder, click osTicket, then scroll down and change ost-samplecomfig.php to OsTicketconfig.php. Finally, right-click the renamed folder and select Properties from the menu that appears. After that, I go to security, select advance, choose Disable Inheritances, and then click Remove All Inheritances. Then you will add permissions, choose Principle, type in Everyone, and then choose Basic Permissions, giving Everyone Complete Control.
</p>
<br />

<p>
<img src=https://i.imgur.com/KWDCGvq.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/vrljKlG.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/DfoDVZc.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src=https://i.imgur.com/Z82PTlC.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/pmWeMBh.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/fSrE0Rs.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/qVKmkFs.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I'll now return to the OSTicket browser, click Continue, create a username, and then provide the necessary data. While downloading HeidiSQL, make sure it downloads to Windows Explore. Then, click the HeidiSQL icon to launch the setup process and finish the process. Once installed, HeidiSQL will appear, and when you click Create, a new Data Base for the OsTicket will be created. We will type in the Root Password we created before. To open Heidi, right-click Unnamed, select Create New, select Database, give it the name OsTicket, and then click Okay. Return to the OsTicket browser and enter the data base information you created at the bottom of the page and click continue.
</p>
<br />


<p>
<img src=https://i.imgur.com/jpB8kyz.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/lwagduP.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/lUe1Bdw.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, return to the wwwroot file, navigate to the OsTicket folder, and then click on the include folder. From there, select everyone in the Advance section, remove Full Control from the Basic permission, and only apply Reading and Execute  click "Apply." then return to the website's page in your browser and enter localhost/osTicket/scp/login.php. The username and password you created for OsTicket should then allow you to log in.
</p>
<br />
