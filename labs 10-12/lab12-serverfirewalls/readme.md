# Lab #12: Configuring Server Firewalls to Block ICMP Request
## Steps

<p align="center"><img src="https://i.imgur.com/qnCveoR.png"></p>
<p align="center"><i>Ref 1: Initial environment.</i></p>
<br>

In this lab, I'm going to set up a firewall on our network's web server that blocks ICMP requests from devices on the network. To do this, I can go into the server's Desktop settings and make changes to the firewall.

<p align="center"><img src="https://i.imgur.com/22gGcmD.png"></p>
<p align="center"><i>Ref 2: Unconfigured firewall.</i></p>
<br>

We can try pinging our server to check to see if the firewall successfully blocks ICMP requests.

<p align="center"><img src="https://i.imgur.com/csS03Zh.png"></p>
<p align="center"><i>Ref 3: We've successfully added the firewall and we can no longer ping our web server (website.com).</i></p>
<br>

