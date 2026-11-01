# Cisco Packet Tracer – Networking Labs

This repository contains practical networking labs created using **Cisco Packet Tracer** as part of my CCNA learning journey.

## Lab 01: Basic LAN Connectivity

### Objective
Build a simple Local Area Network (LAN) and verify communication between two PCs through a network switch.

### Network Topology
- 2 PCs
- 1 Network Switch
- Ethernet connections

### IP Addressing

| Device | IP Address | Subnet Mask |
|---|---|---|
| PC1 | 192.168.1.1 | 255.255.255.0 |
| PC2 | 192.168.1.2 | 255.255.255.0 |

### Configuration Steps
1. Add two PCs and one switch in Cisco Packet Tracer.
2. Connect both PCs to the switch using Ethernet cables.
3. Assign IP addresses to both PCs.
4. Verify network connectivity using the ping command.

### Connectivity Verification

Test connectivity from PC1 to PC2:

```bash
ping 192.168.1.2
```

**Result:** Successful connectivity between both PCs.

### Skills Practiced
- LAN fundamentals
- Network topology
- ![Lab 01 Network Topology](lab-01-topology.png)
- Switch connectivity
- IPv4 addressing
- Subnet masks
- Basic network troubleshooting
- Ping connectivity testing

### Project File
`packetTracer-Lab-01.pkt`

---

**Tool:** Cisco Packet Tracer  
**Learning Path:** CCNA  
**Author:** Arsalan Younis
