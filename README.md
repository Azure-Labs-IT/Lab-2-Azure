# Lab-2-Azure
Creating of Simple Virtual Machines on Azure
<h1>Azure Virtual Machine Creation and Deployment</h1>

<h2>Description</h2>
How to Create Simple Functional Virtual Machine(s) on Azure
<br />


<h2>Utilities Used</h2>

- <b>Azure</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> (25H2)

<h2>Prerequisites </h2>

- <b>Pre-Created Resource Group</b> (See Lab 1: <a href="https://github.com/Azure-Labs-IT/Lab-1-Azure/blob/main/README.md"> How to create Resource Group</a>)
- <b>An Azure Account/Subscription</b>

<h2>Labs walk-through:</h2>

<p align="center">
Log-in to Azure (no need if you're already logged in) and on the top search bar search for "Virtual Machines". Once it appears on the drop-down options, click on it: <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/1%20Search%20for%20VM.png" height="80%" width="80%" alt="Search for Vitual Machine"/>
<br />
<br />
</p>

<p align="center">
Click on "➕Create" this will open a drop-down. On that drop-down click on Virtual Machine this will take you to a screen where you can create a Virtual machine to your own specificiation and liking  
<b>(If you are running your account on a free trial please keep in mind that some options/specifications for your virtual machine are only available for paid/paying users)
</b> 
 <br />
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/2%20Click%20Create%20VM.png" height="80%" width="80%" alt="Create Account"/>
<br />
<br />
</p>

<p align="center">
Assign your Virtual Machine to a Resource Group and Azure Subscription if you have more than one:  <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/3%20Assign%20VM%20to%20Resource%20Group.png" height="80%" width="80%" alt="Assign VM to resource Group and Subscription"/>
<br />
<br />
</p>

<p align="center">
Name your Virtual Machine, I would suggest giving it a name that indicates the OS it will be using, for example if you're creating a Windows OS Virtual Machine naming it something like "WindowsVM" would be a good idea(this is in the case you have multple VMs with different OS on each, otherwise name it what you want): <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/4%20Name%20VM%20based%20on%20the%20OS%20version%20you%20want%20to%20use%20or%20preferred%20name.png" height="80%" width="80%" alt="Name VM based on OS"/>
<br />
<br />
</p>

<p align="center">
Choose an Ooperating System(OS) your Virtual Machine will be using. If the Virtual Machine is for personal use I would suggest choosing an operating system you are used to, for me that would be Windows but it may differ from person to person. Alternatively you can choose a different OS as practice to familairize yourself with that Operating System and it's shortcuts and overal functionality:  <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/5%20Choose%20OS%20version%20for%20VM%20under%20image%20options.png" height="80%" width="80%" alt="Choose OS for VM"/>
<br />
<br />
</p>

<p align="center">
Choose your Virtual Machine RAM/Size. This option heavily impacts the speed of the Virtual Machine, I suggest 8GB at minimum as lower RAM sizes tend to be a bit slow: <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/6%20Choose%20RAM%20size%20I%20suggest%20at%20minimum%208GB%20as%20lower%20sizes%20tend%20to%20be%20a%20bit%20slow.png" height="80%" width="80%" alt="Choose RAM"/>
<br />
<br />
</p>

<p align="center">
Input the login details and username for the Virtual Machine ,these will be used for user login on the Virtual Machine.I highly suggest writing this info in a notepad or somewhere so you can remember :  <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/7%20Input%20login%20details%20and%20username%20I%20highly%20suggest%20writing%20this%20info%20in%20a%20notepad%20so%20you%20can%20remember.png" height="80%" width="80%" alt="Input VM login Details and note them down"/>
<br />
<br />
</p>

<p align="center">
Now click Next at the bottom of the page/screen until you get to the Networking info/tab of the Virtual Machine you are creating:  <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/8%20Click%20Next%20until%20you%20get%20to%20the%20Networking%20info.png" height="80%" width="80%" alt="Click next until Networking Tab"/>
<br />
<br />
</p>

<p align="center">
You can choose to create a custom network for the Virtual Machine or leave it predefined:  <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/9%20Leave%20Virtual%20Network%20or%20create%20your%20own.png" height="80%" width="80%" alt="Leave Virtual Network as predefined"/> <br/>
</p>

<p align="center">
If you choose to create a Network, you will have to configure it's subnet mask as well:<br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/9%20Create%20Virtual%20Network.png" height="80%" width="80%" alt="Create custom Virtual Network"/>
<br />
<br />
</p>

<p align="center">
After the Network Tab click next until you reach review and create, you will have to wait a bit for Azure to validate your Virtual Machine specs. Once it's done you can click Create:  <br/>
<img src="https://github.com/Azure-Labs-IT/Lab-2-Azure/blob/main/10%20After%20Clicking%20Review%20and%20Create%20%20wait%20a%20bit%20for%20Azure%20to%20validate%20and%20then%20click%20Create%20this%20will%20deploy%20the%20VM.png" height="80%" width="80%" alt="Validate and Create VM"/>
<br />
<br />
</p>

<b> And you're done now ,you can now use the Virtual Machine as you please(remember you pay as you use): </b>  <br/>
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
