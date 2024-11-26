# Lab #10: Configuring Routers with RIP
## Steps
Routing Information Protocol (RIP) is a routing protocol that uses hop count as a routing metric to find the best path between the source and the destination network. 

<p align="center"><img src="https://i.imgur.com/IA53eXQ.png"></p>
<p align="center"><i>Ref 1: Initial environment.</i></p>
<br>

We can review each router's configuration and edit their RIP routing settings. 

<p align="center"><img src="https://i.imgur.com/p7NqdeV.png"></p>
<p align="center"><i>Ref 2: Configuring router RIP settings</i></p>
<br>

After pinging PC #2 from PC #1, we lose some data from our ping due to network convergence. The routers needed some time to update their configuration settings, however, we were successfully able to communicate with no packet loss after the second ping command.

<p align="center"><img src="https://i.imgur.com/hqxCm1S.png"></p>
<p align="center"><i>Ref 3: Pinging PC #2 from PC #1.</i></p>
<br>

We can use `tracert` to find the packet's path to get to PC #2. The output shows that the packet was not sent through Router 3 but instead hopped to Router 2. RIP uses the shortest path.

<p align="center"><img src="https://i.imgur.com/pkbolT5.png"></p>
<p align="center"><i>Ref 4: Final environment.</i></p>
<br>

