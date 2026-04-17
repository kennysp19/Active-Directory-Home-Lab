# Active Directory Home Lab

## Overview
I built a hands-on Active Directory lab to simulate a real-world enterprise environment and develop foundational skills in identity and access management, user administration, and security monitoring.


## Objective
To understand how user accounts, permissions, and authentication work in a domain environment, and how these activities generate logs that can be monitored for security events.


## Lab Environment

**Virtualization Platform:**
- VirtualBox

**Systems Configured:**
- Windows Server 2022 (Domain Controller)
- Windows 10 (Client Machine)


<p align="center">
Network Diagram: <br/>
<img src="https://i.imgur.com/UkW3bQq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

**Steps Performed

<p align="center">
Installed Active Directory Domain Services <br/>
<img src="https://i.imgur.com/3EHoQLF.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<p align="center">
Domain Controller Configuration  <br/>
<img src="https://i.imgur.com/4SZHDBx.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>


<p align="center">
Installed and setup DHCP which allows windows client to get an IP address that will let them get on and browse the internet while being on this private internal network just like an office or school.   <br/>
<img src="https://i.imgur.com/8hbnKwa.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/8oTNkpt.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Kkk740v.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<p align="center">
Installed and configured RAS (Remote Access Server) so windows 10 client can access the internet while on the private virtual network with DC.<br/>
<img src="https://i.imgur.com/UvTZ1Bt.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xMtKjHH.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/QguaA44.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<p align="center">
Created Users, OUs (Organizational Units), and Security Groups.<br/>
  Organizational Units<br/>
  -IT -HR -Finance -Workstations<br/>
  Security Groups<br/>
  IT-ADMINS, HR-Users, Finance-Users<br/>
<img src="https://i.imgur.com/XXrWYvk.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<p align="center">
Joining client machine (Windows 10) to domain controller and making sure there is access to internet.<br/>
<img src="https://i.imgur.com/kyQIwO7.jpeg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/yM2xikd.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sptD0hG.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
