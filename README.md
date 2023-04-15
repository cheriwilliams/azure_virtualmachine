<p align="center">
<img src="/>
</p>

<h1>Creating a Virtual Machine using Microsoft Azure</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

-Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- 
- 
- 
- 
- 
-  
- 

<h2>Actions and Observations</h2>

<p>
<img src=https://i.imgur.com/evLjJoU.jpg/>
</p>
<p>
The above image shows traffic being pinged from Windows 10 Virtual Machine to Ubuntu Virtual Machine. The traffic between the two machines was successful showing 4 packets sent and 4 packets received. 
</p>
<br />

<p>
<img src=https://i.imgur.com/8uRELl2.jpg/>
</p>
<p>
Incoming traffic has been disabled from the firewall in Azure. Network Security Group was utilized and the security rule was applied to deny traffic and the ping request stopped. 
</p>
<br />

<p>
<img src=https://i.imgur.com/JC9Alzl.jpg/>
</p>
<p>
In the above image, a significant amount of SSH (Secure Shell) traffic has spammed in Wireshark from the pwd command being entered into the command line. 
</p>
<br />

<p>
<img src=https://i.imgur.com/jAShtVx.jpg/>
</p>
<p>
While using the command ipconfig /renew, a new IP address can be issued for the VM. A small amount of DHCP (Dynamic Host Configuration Protocol) traffic was generated from that command. 
</p>
<br />

<p>
<img src=https://i.imgur.com/KmGufGo.jpg/>
</p>
<p>
The above image shows the command nslookup being prompted to find the IP addresss for www.google.com, DNS (Domain Name System) traffic is then generated in Wireshark from nslookup. 
</p>
<br />

<p>
<img src=/>
</p>
<p>
RDP (Remote Desktop Protocol) traffic was constantly coming through Wireshark because of the active running connection of the Windows VM. 
</p>
<br />
