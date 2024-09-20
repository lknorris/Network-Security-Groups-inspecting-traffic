<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1: Create a resource group and VMs. One VM will be Windows 10, and the other will be Linux Ubuntu.
- Step 2: within the Windows 10 VM, download Wireshark.
- Step 3: Once Wireshark is installed, create a new packet.
- Step 4: After setting up your packet, filter any traffic and observe the changes.

<h2>Actions and Observations</h2>

![Network-security-groups-P1](https://github.com/user-attachments/assets/173a3f11-9ff1-4c72-ae6f-bc7c016e7028)

Creating my resource groups and VM's. I'm using Windows 10 and Linux Ubuntu as my virtual machines.
</p>
<br />

![Security Traffic-installing wireshark inside VM  p2](https://github.com/user-attachments/assets/cf099626-35b2-4d3d-ad8c-6991b7aa80e3)

Downloading wireshark on my Windows 10 VM, and setting up a packet capture.
</p>
<br />

![P3  network traffic -filtering imcp with wireshark](https://github.com/user-attachments/assets/ea838373-1656-416a-a762-7337a88ab1bd)

Now that I have my packet set up, I can filter IMCP, SSH, and DHCP traffic. I can also go into Azure, block any traffic I want within the firewall, and observe that change.
</p>
<br />
