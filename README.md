# azure-network-protocols

<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2
- Step 3

<h2>Actions and Observations</h2>

<p>
<img src="https://imgur.com/1VSvPl4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I,ve created 2 virtual machines on Azure. One operating on windows and the other running on Linux.
</p>
<br />

<p>
<img src="https://imgur.com/HHj6Ak4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I downloaded wireshark and filter for ICMP traffic only. I observed ping request and reply within WireShark.

</p>
<br />

<p>
<img src="https://imgur.com/467QLVS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From wireshark I filtered for DNS traffic only. From Windows 10 VM with PowerShell I use nslookup to see what google.com IP addresses is. I Observed the DNS traffic being shown in WireShark


.
</p>
<br />
