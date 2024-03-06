<h1> Windows Server (Hyper-V) </h1>


<h2>Description</h2>
In this lab I will walk you through modifying the storage settings in Hyper-V. Virtual machines typically take up a large amount of space on your storage devices. This makes managing storage very important for the organization of virtual machines and ensuring the virtual machines do not take up all the space on the operating system partition.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Server 2019</b>
- <b>PowerShell</b>
- <b>Hyper-V Manager</b>

<h2>Program Screenshots:</h2>

<p align="center">
Created folders to configure the storage locations for the virtual machines and disks: <br/>
<img src="https://i.imgur.com/zYtP8oi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured HyperV Manager to use folders as default storage location:  <br/>
<img src="https://i.imgur.com/ZFBTvmg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure the Enhanced Session Mode Policy to Allow enhanced session mode: <br/>
<img src="https://i.imgur.com/pxWiORg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify Settings through Powershell:  <br/>
<img src="https://i.imgur.com/3hcoXsW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
