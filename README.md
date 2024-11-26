<h1>AWS - EBS</h1>


<h2> Objectives </h2>

- Create an Amazon EBS volume
- Attach an Amazon EBS volume to an Amazon EC2 instance
- Create a file system on an Amazon EBS volume
- Modify the size of an Amazon EBS volume
- Modify the volume type and performance characteristics of an Amazon EBS volume
- Create snapshots for an Amazon EBS volume
- Restore an Amazon EBS volume from a snapshot

<h2>Languages and Utilities Used</h2>

- <b>AWS</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Let's start by navigating to the EC2 Dashboard: <br/>
<img src="https://i.imgur.com/l8lAjdx.png" height="80%" width="80%" alt="Load-Balancer"/>
<br />
<br />
After that, click "Volumes" on the left side of the taskbar and view the existing volumes. Take note of the AZ that the volumes are current in. From there create a new volume:  <br/>
<img src="https://i.imgur.com/MXizzPu.png" height="80%" width="80%" alt="Load-Balancer"/>
<br />
<br />
Configure the volume setting: <br/>
<img src="https://i.imgur.com/sDOTzK4.png" height="80%" width="80%" alt="Load-Balancer"/>
<br />
<br />
Configure the volumes part 2 by adding a tag:  <br/>
<img src="https://i.imgur.com/R2jbFHA.png" height="80%" width="80%" alt="Load-Balancer"/>
<br />
<br />
Attach the Volume to the Ec2:  <br/>
<img src="https://i.imgur.com/amkh2hW.png" height="80%" width="80%" alt="Load-Balancer"/>
<br />
<br />
Configure the attach volume settings:  <br/>
<img src="https://i.imgur.com/SqvLL5P.png" height="80%" width="80%" alt="Load-Balancer"/>
<br />
<br />
<p align="center">
Check the state of the volume and confirm it's "in use": <br/>
<img src="https://i.imgur.com/sLCjOgA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigate to your EC2 instances and select New_App and connect to the Session manager:  <br/>
<img src="https://i.imgur.com/SJbsROC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
view the available storage in the EC2 Instance, create a file system on the EBS volume, and make and mount a new directory for the volume. After that create a text file and view the results: <br/>
<img src="https://i.imgur.com/txuVDSG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Modify the volume with new information:  <br/>
<img src="https://i.imgur.com/OEOBKVz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
List the block devices, view the storage, and resize the file system. Then confirm the change:  <br/>
<img src="https://i.imgur.com/lxnLMq3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Modify the App Logs volume:  <br/>
<img src="https://i.imgur.com/N49Qjqo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure the volume settings:  <br/>
<img src="https://i.imgur.com/koM9iHX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p align="center">
Create a snapshot: <br/>
<img src="https://i.imgur.com/WbmjOoz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure the snapshot settings:  <br/>
<img src="https://i.imgur.com/pPrMykf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Check the status: <br/>
<img src="https://i.imgur.com/4hUuNcx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a new volume for the snapshot:  <br/>
<img src="https://i.imgur.com/HId6i3a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Attach the volume:  <br/>
<img src="https://i.imgur.com/pgJPEwn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a directory, and mount the volume. From there list the block devices and resize the file system:  <br/>
<img src="https://i.imgur.com/QCmVMuk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
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
