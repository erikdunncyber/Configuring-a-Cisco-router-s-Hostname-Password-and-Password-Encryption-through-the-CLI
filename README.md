<h1>Packet Tracer - Configuring a Cisco router's Hostname, Password, and Password Encryption through the CLI</h1>

<p align="center">
I created a simple LAN with 3 PCs connected to a switch, connected to a router: <br/>
<img src="https://i.imgur.com/qiDAbcX.png" height="80%" width="80%"/>
<br />
<br />
I accessed the CLI of the router and entered Privleged Exec mode by entering "enable". Through Privleged Exec mode I enter Global Configuration mode by entering "configure terminal". To change the router's hostname I enter the command "hostname MyRouter". Now the router's hostname is MyRouter: <br/>
<img src="https://i.imgur.com/WneCOsk.png" height="80%" width="80%" />
<br />
<br />
To add a password I'll enter "enable password CCNA". Now the password to access Privleged Exec mode on this router is CCNA: <br/>
<img src="https://i.imgur.com/t3qsniP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To verify if the password was set correctly, I'll access the running configuration of this router. To do this I'll enter "show running-config" into the CLI. The running configuration shows that the password was set to CCNA:  <br/>
<img src="https://i.imgur.com/NFBTD8U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

