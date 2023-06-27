<p align="center">
<img src="https://i.imgur.com/O5ShSW1.jpg">
</p>

<h1>Creating a Virtual Machine using Microsoft Azure</h1>
This tutorial will show the process of creating a Windows 10 Virtual Machine using Microsoft Azure. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Create a Resource Group
- Create a Virtual Machine

<h2>Actions and Configuration</h2>

<p>
<img src="https://i.imgur.com/sZ3rv4B.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above image shows a Resource Group being created for the Virutal Machine. We have to choose the subscription for the Resource group and choose the name for the Resource group. If you only have one subscription, it will already be pre-selected for you. Lastly we must choose the region that we want our resources stored in. The region is usually the location you are currently in. Click Next to move towards the next step in the process.     
</p>
<br />

<p>
<img src="https://i.imgur.com/aXDocun.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We passed the Validation for the Resource Group, now we have to click "Create", which will be at the bottom of the screen and the Resource group will be created.   
</p>
<br />

<p>
<img src="https://i.imgur.com/wnWeOgm.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Our resource group has been created as shown above, now we can move onto creating the Windows 10 Virtual Machine.  
</p>
<br />

<p>
<img src="https://i.imgur.com/alpGSXH.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This page shows where we can create the VM, click Azure Virtual Machine to create the VM. 
</p>
<br />

<p>
<img src="https://i.imgur.com/8hRMnZv.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we are in the section where we are actually creating the VM in Azure. We want to choose the Resource Group that we previously created and we can then name the VM machine. For the region, it is important to choose the same location we chose for our Resource group. For availability options, we want to click the "no infrastructure" option. Security should be standard and for our image, we are creating a Windows 10 Virtual Machine. VM architecture will be pre-selected when we select the Windows 10 machine. 
</p>
<br />

<p>
<img src=https://i.imgur.com/7bBTt61.jpg/>
</p>
<p>
In the above image we are finishing up the last few steps of creating the VM. We have to choose the size of 2 vcpus or 4 vcpus so that the machine can run efficiently. Create a username and password for login. Click the selected boxes, and confirm the licensing agreement at the bottom. Now we can click Review and create and wait for the validation to pass.    
</p>
<br />

<p>
<img src=https://i.imgur.com/Fle7AiV.jpg/>
</p>
<p> 
The validation has passed, now we can click create and the VM will start creating. 
</p>
<br />

<p>
<img src=https://i.imgur.com/WfHXFKy.jpg>
</p>
<p>
This process shows the VM being created, it may take a few minutes to complete.
</p>
<br />

<p>
<img src=https://i.imgur.com/4C5TNxe.jpg/>
</p>
<p>
This image shows the final step in the process of creating the Windows 10 VM.   
</p>
<br />
