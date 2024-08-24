<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation (In Progress) </h1>
This project outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (22H2)

<h2>List of Prerequisites</h2>

- Enabled IIS (Internet Information Services)
- Installed and registered PHP in IIS
- Installed C++ redistributable
- Installed MySQL with HeidiSQL client
- Configured permissions and installed osTicket

<h2>Installation Steps</h2>

In this first part of this tutorial we are going to setup a local server with IIS (Internet Information Services) in Windows. If all you need to know is how to set this up you can stop after we've pulled up the broswer and navigated to our local IP address. 

In the second part we will setup the free ticketing system osTicket running on the IIS server.

Let's get into it.

First hit Windows Key + R to bring up the "Run" dialog box. In the field type "optionalfeature" and hit enter. This will bring up the "Windows Features" window. 

Alternatively, we can right-click on the Start button and click 'Run,' then type "optionalfeatures" and hit enter. 
<br />


![run optional features](https://github.com/timsherrell/osticket-prereqs/blob/main/optionalfeatures1.gif)

This will bring up the Windows Features window where we will choose the options necessary to install IIS. 

From here, check the box next to Internet Information Services and click the '+' next to it to expand it. Expand Application Development Features click the CGI box, then collapse Application Development Features again by hitting the '-' next to it. Exapnd Common HTTP Features, make sure all the boxes are checked. 

Click OK. 

![IIS Installation](https://github.com/timsherrell/osticket-prereqs/blob/main/ISS%20install.gif)

Internet Information Services should be working now. We can check by opening a browser and navigating to 127.0.0.1 in the address bar. This should bring up the Internet Information Services website. If it doesn't you may need to uninstall and reinstall again by going back to Windows Features, unclicking and reclicking everything again. 

![localhost IIS](https://github.com/timsherrell/osticket-prereqs/blob/main/Loopback.gif)

<p>
  <img src="https://github.com/timsherrell/osticket-prereqs/assets/144177449/2c26b2bf-dcb0-48f7-af7e-ffacf21aeb30" />
</p>
<p>
Enabled Internet Information Services web server 
</p>
<br />

<p>
<img src="https://github.com/timsherrell/osticket-prereqs/assets/144177449/08f24a02-75db-4f55-b816-06fc68034d61" />
</p>
<p>
Installed C++ Redistributable
</p>
<br />

<p>
  <img src="https://github.com/timsherrell/osticket-prereqs/assets/144177449/dbdb59b5-4c7b-40f1-90ad-e17c736d55ee" />
</p>
<p>
  <img src="https://github.com/timsherrell/osticket-prereqs/assets/144177449/83378b0b-b5e3-4557-8b42-f6b66f0a68a2" />
</p>
<p>
  Installed and registered PHP in IIS
</p>
<br />

<p>
<img src="https://github.com/timsherrell/osticket-prereqs/assets/144177449/4944daf1-b712-4324-9ca6-667789536aad"/>
</p>
<p>
  <img src="https://github.com/timsherrell/osticket-prereqs/assets/144177449/d13a8e73-7628-4878-ae31-d171d642d5f3" />
</p>
<p>
Installed MySQL server and HeidiSQL for osTicket database
</p>
<br />

<p>
  <img src="https://github.com/timsherrell/osticket-prereqs/assets/144177449/5d9754b6-7243-4011-9224-a7418664b961" />
</p>
Installed osTicket
<p>
  
</p>
