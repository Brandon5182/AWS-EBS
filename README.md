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
After that, click "Volumes" on the left side of the taskbar and view the existing volumes. Take note of the AZ that the volumes are current in. From there create a new volume.  <br/>
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

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
