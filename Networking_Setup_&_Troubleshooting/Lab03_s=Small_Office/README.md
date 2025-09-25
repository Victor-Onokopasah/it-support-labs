Lab 02: Small Office/Home Office (SOHO) Network Setup & Troubleshooting
Author: Victor Onokopasah
Date: March 2025

Objective
Build a functional SOHO network, configure IP settings, and troubleshoot common connectivity issues using industry-standard tools (aligned with Cisco IT Essentials and IBM SkillsBuild).

Author: Victor Onokopasah
Lab 03: - SOHO-Network-Setup-Troubleshooting
Date: March 2025
Objective
Build a functional Small Office/Home Office (SOHO) network, configure IP settings, troubleshoot common connectivity issues, and demonstrate CLI-based diagnostics using industry-standard tools.

This exercise builds key networking administration skills in:

Network topology design and device configuration
IP address management (static/dynamic)
DHCP/DNS configuration and troubleshooting
Wi-Fi optimization and LAN connectivity validation
Cross-platform CLI troubleshooting
Key Skills
Network topology planning (router/switch placement)
IP configuration (static vs. dynamic addressing)
DHCP scope setup and DNS resolution troubleshooting
Wi-Fi performance optimization (channel selection)
CLI-based network diagnostics (ping, tracert, ipconfig/ifconfig)
Tools Used
Hardware: Router (TP-Link Archer AX50), Ethernet switch (Netgear GS308), 2–3 computers/laptops, smartphones/tablets
Software: Wi-Fi analyzer (NetSpot), terminal (CMD/Bash), port forwarding tester (CanYouSeeMe.org)
Commands: ping, tracert, ipconfig (Windows), ifconfig, nslookup (Linux/macOS)
Step 1: Network Topology Design
Sketch Diagram:
Draw a diagram (use draw.io) showing:
Router (WAN port → Modem/Internet)
Switch (LAN ports → Wired devices)
Devices (computers, phones, optional Raspberry Pi)
Assign IP ranges: 192.168.1.0/24 (Router: 192.168.1.1; Static IPs: 192.168.1.10 (Pi), 192.168.1.20 (Printer); DHCP Scope: 192.168.1.100–200).
Step 2: Router Configuration
Access Admin Panel:
Open browser, enter 192.168.1.1 (default router IP).
Basic Settings:
Set SSID: HomeNet_2024 (strong password).
Enable DHCP (scope: 192.168.1.100–200).
Disable UPnP (security best practice).
Step 3: Device Connection & Initial Testing
Connect Devices:
Wire computers to the switch.
Connect phones to Wi-Fi (verify signal strength).
