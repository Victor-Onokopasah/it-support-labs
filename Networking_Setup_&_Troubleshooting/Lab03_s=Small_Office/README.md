**Author:** Victor Onokopasah
**Lab:** 03 – SOHO-Network-Setup-Troubleshooting
**Date:** March 2025

## Lab 03: - SOHO-Network-Setup-Troubleshooting
Objective
Build a functional Small Office/Home Office (SOHO) network, configure IP settings, troubleshoot common connectivity issues, and demonstrate CLI-based diagnostics using industry-standard tools.

This exercise builds key networking administration skills in:

- Network topology design and device configuration
- IP address management (static/dynamic)
- DHCP/DNS configuration and troubleshooting
- Wi-Fi optimization and LAN connectivity validation
- Cross-platform CLI troubleshooting
  
## Key Skills
- Network topology planning (router/switch placement)
- IP configuration (static vs. dynamic addressing)
- DHCP scope setup and DNS resolution troubleshooting
- Wi-Fi performance optimization (channel selection)
- CLI-based network diagnostics (ping, tracert, ipconfig/ifconfig)
  
## Tools Used
- Hardware: Router (e.g., TP-Link Archer AX50), Ethernet switch (e.g., Netgear GS308), 2–3 computers/laptops, smartphones/tablets, optional Raspberry Pi
- Software/Utilities: Wi-Fi analyzer (NetSpot), terminal (CMD/Bash), port forwarding tester (CanYouSeeMe.org)
- Commands: ping, tracert, ipconfig (Windows), ifconfig, nslookup (Linux/macOS)
- Diagramming: draw.io (for topology diagram), Mermaid (for diagram‑as‑code in GitHub)

## Step 1: Network Topology Design  
> Core Layout:

![Network Topology Design](Images/topology-design.jpg)

> IP Ranges:
> - Router: 192.168.1.1 (Default Gateway)
> - Static IPs: 192.168.1.10 (Pi), 192.168.1.20 (Printer)
> - DHCP Scope: 192.168.1.100–200

> Extended Options:  
> - Mesh Node: Router → Mesh Node → Seamless Wi-Fi coverage across floors  
> - Powerline Adapter: Router → Powerline Adapter → Remote Room Adapter → Wired PC/Smart TV

  ## Step 2: Router Configuration

- Accessed router admin panel at `192.168.1.1`
- Configured SSID: **HomeNet_2025** with WPA2/WPA3 security
- Enabled DHCP scope: `192.168.1.100–200`
- Disabled UPnP for security

### Screenshots
- [Router Login](Images/router-login.jpg) *Router admin panel login page*
- [SSID Config](Images/router-ssid.jpg) *SSID configured as HomeNet_2025 with WPA2/WPA3*
- [DHCP Scope](Images/router-dhcp.jpg) *DHCP range set to 192.168.1.100–200*
- [UPnP Disabled](Images/router-upnp.jpg) *UPnP disabled for security best practice*

## Step 3: Device Connection & Initial Testing

- Connected PCs to switch via Ethernet
- Connected phones to Wi‑Fi (SSID: HomeNet_2025, WPA2/WPA3)
- Validated connectivity with commands:

```bash
ping 192.168.1.1     # Test router reachability
ping google.com      # Test internet connectivity
tracert google.com   # Identify network bottlenecks

### Screenshots
[Ping Router](images/ping-router.png)
[Ping Command](images/ping-google.png)
