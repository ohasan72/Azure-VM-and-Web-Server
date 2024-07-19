# Azure VM-and Web Server
Create a Virtual Machine and Deploy a Web Server 
<h1>Azure VM and Web Server</h1>

 <h2>About this  Project</h2>
<b> I will create a Virtual Machine in Azure to deploy a web server, specifically a Nextcloud server. Instead of using just the presets, I will explore how the basic architecture of Azure works, by creating a Virtual Machine, connecting it to a subnet, protected by inbound and outbound rules thanks to Network Security Groups, in a Virtual Network.  also I will use Bastion to connect to the machine via SSH, without exposing an external port to the Internet, and then installing a simple Nextcloud server and make the Virtual Machine available to you by opening a public IP and a DNS label.  </b> 

<h2>Description</h2>

-<b> Create a Resource Group </b>
-<b> Create a Virtual Network and a subnet </b>
-<b> Protect a subnet using a Network Security Group</b>
-<b> Deploy Bastion to connect to a Virtual Machine</b>
-<b> Create an Ubuntu Server Virtual Machine</b>
-<b> Install Nextcloud by connecting via SSH using Bastion</b>
-<b> Publish an IP</b>
-<b> Create a DNS label</b> 

<h2>Skills you'll practice</h2>

- <b>Virtual Machine</b> 
- <b>Azure</b>
- <b>Bastion</b>
- <b>Virtual Networks</b>

<h2>Environments Used </h2>

- <b>Azure portal</b> 

<h2>Program walk-through:</h2>

<p align="center">
project images: <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/93/7b3b3df5504a5bbb6f876f50cf9864/azurevmtask1.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/1f/da8c00bf574a9fba6f18bafa0828c2/azurevmtask2.png"/>
<br />
<br />
project images <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/ac/7ef5de5201493fa7f56fd417683df6/azurevmtask3.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/27/13c8730869415fad77759316e29b33/azurevmtask4.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/60/3f774fbe3744279ab2f779616350f5/azurevmtask5.png"/>
<br />
<br />
project images  <br/>
<img src="https://d15cw65ipctsrr.cloudfront.net/38/027fc7dfd946a3a8fcd3d18332391b/azurevmtask6.png"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
