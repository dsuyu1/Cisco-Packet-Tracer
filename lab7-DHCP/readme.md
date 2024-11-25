# Lab #7: Utilizing DHCP to Assign IP Addresses to LAN
## Steps
<p align="center"><img src="https://i.imgur.com/bglBgxT.png"></p>
<p align="center"><i>Ref 1: Starting environment.</i></p>
<br>

To begin, I added a new server to act as our DHCP server. To configure it to act as a DHCP server, I went into services and assigned it a fictitious default gateway and DNS server.

<p align="center"><img src="https://i.imgur.com/IU96zv2.png"></p>
<p align="center"><i>Ref 2: The Services tab.</i></p>
<br>

With the configured DHCP server, IP addresses can now be dynamically assigned. Without it, if we tried assigning IPs dynamically, the devices would instead resort to using an APIPA address.

<p align="center"><img src="https://i.imgur.com/clXtngB.png"></p>
<p align="center"><i>Ref 3: Final environment.</i></p>
<br>
