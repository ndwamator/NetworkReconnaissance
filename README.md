<h1>Network Reconnaissance using Nmap</h1>


<h2>Description</h2>
A hands-on security assessment of an AnyDesk service running on port 7070 in a virtual lab environment.
The project covers port scanning, enumeration,application idetification, vulnerability assessment, and security recommendations using Kali Linux and Windows.
<br />


<h2>Utilities Used</h2>

- <b>Nmap</b> 
- <b>Kali Linux</b>

<h2>Environments Used </h2>

- <b>Oracle vitual Box</b> 

<h2>Program walk-through: Reconnaissance(Phase 1):</h2>

<p align="center">
Opening Oracle Virtual Box Manager: <br/>
<img src="https://i.imgur.com/VxXI8fB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Kali Linux: <br/>
<img src="https://i.imgur.com/1mrL5Nc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ping Scan: Check if system is alive: <br/>
<img src="https://i.imgur.com/1YcepJX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Port Scanning:Checking for open ports:  <br/>
<img src="https://i.imgur.com/LYkljAJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Selected Open Ports Scanning: <br/>
<img src="https://i.imgur.com/Y7CE1gR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<h2>Program walk-through:Enumeration(Phase 2):</h2>

<p align="center">
Checking application running on port 7070 using linux:  <br/>
<img src="https://i.imgur.com/JsjZtVy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Retriving name using SSL Certificate name:  <br/>
<img src="https://i.imgur.com/1EcIDvs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Checking which appplication is running on port 7070 using Windows:  <br/>
<img src="https://i.imgur.com/rtc4FRZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Firewall Action is Allow port 7070 is reachable from the kali machine:  <br/>
<img src="https://i.imgur.com/A5qGaJn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>

<h2>Program walk-through:Application Identification(Phase 3):</h2>

<p align="center">
Application Version:  <br/>
<img src="https://i.imgur.com/A1BusET.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Vulnerability Checking:  <br/>
<img src="https://i.imgur.com/VcS4cvJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Program walk-through:Findings:</h2>

<p align="center">
The findings showed that the target system was reachable, had an accessible service running on port 7070, and had a firewall rule allowing communication to that port. The enumeration process provided useful information about the service, including its application name and version. The final vulnerability checking stage was then used to determine whether the identified application contained any known security weaknesses. These findings demonstrate how reconnaissance, enumeration, and application identification can be used together to understand a target system and identify potential security risks in a controlled environment.  <br/>












