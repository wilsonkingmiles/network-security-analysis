# Network Security Analysis

A collection of authorized networking and security labs demonstrating packet analysis, service discovery, and wireless protocol analysis.

## Tools and concepts
- Wireshark
- Nmap
- `nslookup`
- TCP/IP
- HTTPS/TLS
- IEEE 802.11
- WPA2 / EAPOL
- Port and service/version detection
- OS-detection limitations
- Evidence documentation

## Included case studies
### HTTPS/TLS packet analysis
Captured and filtered HTTPS traffic, compared observed addresses with DNS resolution, and used Wireshark I/O graphs to interpret traffic patterns.

### Nmap service discovery
Used Nmap in an approved Kali lab environment for host discovery, default scripts, service/version detection, and OS-detection attempts. The scan found HTTP and HTTPS open while most ports were filtered.

### Wireless protocol analysis
Reviewed an authorized sample WPA2 capture containing 802.11 management, authentication, association, QoS, and EAPOL handshake traffic.

## Ethical scope
All scanning and packet analysis described here occurred in authorized academic environments or against provided sample captures. This repository is documentation of defensive learning, not instructions for unauthorized testing.
