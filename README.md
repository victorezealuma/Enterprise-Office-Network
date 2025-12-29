# Enterprise-Office-Network (Overview)
This project simulates a real-world enterprise office network using Cisco packet tracer.

What did I build?

This project simulates a real-world enterprise office network using Cisco Packet Tracer.
It consists of two separate office LANs (Office A and Office B) connected to the internet through an edge router implementing NAT.
Office A hosts core network services (DHCP, DNS), while Office B relies on router-based DHCP.
All private IP traffic is translated to a public IP before accessing the internet.

# Network Architecture
Office A: 192.168.10.0/24
Office B: 192.168.20.0/24
Public WAN: 203.0.113.0/30
Edge Router performing PAT (NAT Overload)
