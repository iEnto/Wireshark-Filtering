<h1>Wireshark Filtering</h1>

<h2>Description</h2>
The Project consists of locating all HTTPS and HTTP packets from a capture not containing a certain IP address.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Wireshark Filtering:</h2>
<br />
<p align="center">
Open Wireshark and start capturing: <br/>
<img src="https://i.imgur.com/SfJTYI1.jpg" height="80%" width="80%" alt="Shell"/>
<br />
<br />
Open Google and  DuckDuckGo:  <br/>
<img src="https://i.imgur.com/LBDONi4.jpg" height="80%" width="80%" alt="10 Packets"/>
<br />
<br />
Stop capturing, then add a filter to find packets that contain the tls handshake: <br/>
<img src="https://i.imgur.com/IrLYuKP.jpg" height="80%" width="80%" alt="Skyroute66"/>
<br />
<br />
Add filter to find all ip addresses containing the Destination for the tls handshake:  <br/>
<img src="https://i.imgur.com/ZUoOUMn.jpg" height="80%" width="80%" alt="Dump file"/>
<br />
<br />
This will filter for all HTTPS packets, with the exception for this ip address:  <br/>
<img src="https://i.imgur.com/BJzi8qK.jpg" height="80%" width="80%" alt="Bytes"/>
<br />
<br />
This will filter for all HTTPS and HTTP packets, with the exception for this ip address:  <br/>
<img src="https://i.imgur.com/RC3B0VP.jpg" height="80%" width="80%" alt="ls -al"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
