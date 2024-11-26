# Lab #8: DNS and Web Server Configuration
## Steps
<p align="center"><img src="https://i.imgur.com/QfFQzY3.png"></p>
<p align="center"><i>Ref 1: Starting environment.</i></p>
<br>

In the last lab, I created a DHCP server to dynamically assign IP addresses to the devices in our network. In this lab, I will build upon that and set up a DNS and HTTP web server on the same DHCP server. This server will
then serve a three-fold purpose! Let's get started.

Previously, we gave our server a DNS server value of 8.8.8.8. However, since we want this server to act as a DNS server, we have to change the 8.8.8.8 IP to its IP address, 192.168.200.5. 
We also need to change the DNS server value under the Services tab.

For all our devices, we need to run  `ipconfig /renew` since we want them to no longer use the old DNS server, but the new 192.168.200.5 DNS server.

Now that all the configured devices point to 192.168.200.5 as their DNS server, we can start the service. The domain name `website.com` will point to DNS server.

<p align="center"><img src="https://i.imgur.com/7Yd1PHN.png"></p>
<p align="center"><i>Ref 2: Configuring DNS settings.</i></p>
<br>

We can now access our web server over HTTP using the web browser feature.

<p align="center"><img src="https://i.imgur.com/F9EG7Tk.png"></p>
<p align="center"><i>Ref 3: Accessing the web server.</i></p>
<br>

We can also ping `website.com` from the command line now that the domain name maps to the DNS server's IP address using the A record.

<p align="center"><img src="https://i.imgur.com/qQ5iQ6t.png"></p>
<p align="center"><i>Ref 4: Final environment.</i></p>
<br>
