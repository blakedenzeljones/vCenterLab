<h1>vCenter Lab</h1>

 ### 

<h2>Description</h2>
This lab's objective is to configure a virtualized lab environment using VMware vCenter to practice VM lifecycle management, HA/DRS features, and vSwitch networking.
<br />


<h2>Languages and Utilities Used</h2>

- <b>vCenter</b> 

<h2>Environments Used </h2>

- <b>Linux</b> (Ubuntu/RHEL)
- <b>Windows Server 2022

<h2>Program walk-through:</h2>

<p align="center">
VM Provisioning and Templates <br/>

 ### Tasks Performed:
- Deployed and Configured VMs
- Created new Linux web server VM
- Built a Linux VM template
- Created a saved search for powered-off VMs
  
*Caption: Creating and managing VMs and templates*
<img src="https://i.imgur.com/lHiQPx3.png" height="80%" width="80%" alt="vCenter Lab"/>
<br />
<br />
<p align="center">
Tagging and Organization  <br/>

   ### Tasks Performed:
- Created Tag and assigned a VM to it

*Caption: Tagging VM “Blake-web-serv01" for web tier classification*
<img src="https://i.imgur.com/egWcW8X.png" height="80%" width="80%" alt="vCenter Lab"/>
<br />
<br />
<p align="center">
HA and DRS Cluster Configuration <br/>

### Tasks Performed:
-	Enabled High availability with VM and app monitoring
-	Configured automatic datastore selection and host failover
-	Enabled DRS in partially automated mode

*Caption: HA/DRS cluster settings in RegionA01-Comp01*
<img src="https://i.imgur.com/qLxWozB.png" height="80%" width="80%" alt="vCenter Lab"/>
<img src="https://i.imgur.com/V5SvxFe.png" height="80%" width="80%" alt="vCenter Lab"/>
<br />
<br />
<p align="center">
Monitoring and Alerts  <br/>

### Tasks Performed:
- Created alarm to monitor host CPU >80%(warning) and >90%(critical)

*Caption: Custom CPU usage alert thresholds*
<img src="https://i.imgur.com/zWifMHe.png" height="80%" width="80%" alt="vCenter Lab"/>
<br />
<br />
<p align="center">
VM Migration  <br/>

### Tasks Performed:
- Migrated 3 VMs to another host in the cluster

*Caption: Live VM migration in vSphere Client*
<img src="https://i.imgur.com/k2f7dt0.png" height="80%" width="80%" alt="vCenter Lab"/>
<br />
<br />
<p align="center">
Networking Configuration  <br/>

### Tasks Performed:
-	Added NIC to virtual switch
- Viewed and validated port group properties

*Caption: Configured vSwitch and port group settings*
<img src="https://i.imgur.com/VMuQlFi.png" height="80%" width="80%" alt="vCenter Lab"/>
<img src="https://i.imgur.com/mJqRZxh.png" height="80%" width="80%" alt="vCenter Lab"/>
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
