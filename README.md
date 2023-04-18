<p align="center">
<img src=https://i.imgur.com/VJrNrnk.jpg/>
</p>

<h1>Creating a Virtual Machine using Microsoft Azure</h1>
This tutorial will show the process of creating a Windows 10 Virtual Machine using Microsoft Azure. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Create a Resource Group
- Create Virtual Machine

<h2>Actions and Observations</h2>

<p>
<img src=https://i.imgur.com/kou3MyF.jpg/>
</p>
<p>
The above image shows a Resource Group being created for the Virutal Machine. We have to choose the subscription for the Resource group and choose the name for the Resource group. Lastly we must choose the region that we want our data stored in. The region is usually based off of the location that we currently in. Click next to move towards the next step in the process.     
</p>
<br />

<p>
<img src=https://i.imgur.com/AKFIkuH.jpg/>
</p>
<p>
We passed the Validation for the Resource Group, now we have to click create and the Resource group will be created.   
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
