<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
This project consists of creating an Active Directory home lab environment using Oracle VM Virtual Box. The purpose of this project is to gather hands on experience with building out an an Active Directory environment that simulates a real-world corporte environment. It is also meant to further enhance my understanding of how Active Directory and Windows Networking works. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server 2019</b>
- <b>Oracle VM Virtualbox</b>

<h2>Lab walk-through:</h2>

<p align="center">
Creating the Domain on my Domain Controller: <br/>
<img src="https://i.imgur.com/QKJ6c02.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Creating Admin OU on DC:  <br/>
<img src="https://i.imgur.com/N9UueaY.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Signing into DC using newly created Admin account: <br/>
<img src="https://i.imgur.com/jjoUsAZ.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Setting up remote access for client connectivity:  <br/>
<img src="https://i.imgur.com/bNp4I2m.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Configuring DHCP:  <br/>
<img src="https://i.imgur.com/1HcdY7c.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Using the Domain Controller for DNS:  <br/>
<img src="https://i.imgur.com/JyFzkkM.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Script for creating generic users:  <br/>
<img src="https://i.imgur.com/SzVVkrz.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Generic users created:  <br/>
<img src="https://i.imgur.com/HmSMFlJ.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Creating a new client to simulate a corporate environment:  <br/>
<img src="https://i.imgur.com/9a52Pm8.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Joined the client computer to the domain:  <br/>
<img src="https://i.imgur.com/XM4A0GK.png" height="80%" width="80%" alt="AD"/>
<br />
<br />
Signing into the client computer using one of the generated user credentials:  <br/>
<img src="https://i.imgur.com/nHN9Myd.png" height="80%" width="80%" alt="AD"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
