# Enterprise-Office-Network (Overview)
This project simulates a real-world enterprise office network using Cisco packet tracer.

What did I build?

This project simulates a real-world enterprise office network using Cisco Packet Tracer.
It consists of two separate office LANs (Office A and Office B) connected to the internet through an edge router implementing NAT.
Office A hosts core network services (DHCP, DNS), while Office B relies on router-based DHCP.
All private IP traffic is translated to a public IP before accessing the internet.

## Network Architecture
- Office A: 192.168.10.0/24
- Office B: 192.168.20.0/24
- Public WAN: 203.0.113.0/30
- Edge Router performing PAT (NAT Overload)

## Technologies & Networking Skills Used

This project demonstrates hands-on experience with:
- IPv4 addressing & subnetting
- LAN & WAN design
- DHCP (Server-based & Router-based)
- DNS configuration
- Default gateway & static routing
- NAT (Inside / Outside, PAT)
- Cisco IOS CLI configuration
- Network testing (ping, NAT table verification)
- Troubleshooting connectivity issues

## How the Network Works.

1.End devices in both offices obtain IP addresses via DHCP.
2.Traffic from private networks is forwarded to the edge router.
3.The edge router translates private IPs to a public IP using NAT.
4.Traffic is forwarded to the ISP router and simulated internet.
5.Return traffic is translated back to the correct internal host.
