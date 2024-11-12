<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1: Set up Virtual Network and Subnet in Azure.
- Step 2: Deploy Virtual Machines and Configure Network Security Groups.
- Step 3: Install and Configure Wireshark.
- Step 4: Inspect Traffic and Log Observations.

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Traffic Inspection"/>
</p>
<p>
In this step, we analyze incoming and outgoing traffic to identify common protocols like HTTP/S and DNS requests, using Wireshark to observe data packets in real-time.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="NSG Configuration"/>
</p>
<p>
Next, we configure Network Security Groups to control traffic flow, setting specific rules for allowed protocols. This step secures the VMs and filters unwanted access.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Testing Connections"/>
</p>
<p>
Finally, we test the connections between VMs to confirm that security rules are correctly applied, ensuring that only allowed traffic passes through.
</p>
<br />
