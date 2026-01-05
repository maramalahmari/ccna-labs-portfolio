# IP Addressing Plan – Boson Challenge Lab 1

## IPv4 Addressing

### WAN Link (Global Unicast)
- Network: 203.0.113.0/30
- Subnet Mask: 255.255.255.252

| Device  | Interface | IP Address |
|-------|----------|-----------|
| Router1 | Serial0/0 | 203.0.113.1/30 |
| Router2 | Serial0/0 | 203.0.113.2/30 |

### LAN Network (RFC 1918)
- Network: 192.168.100.0/28
- Subnet Mask: 255.255.255.240
- Default Gateway: 192.168.100.1

| Device | Interface | IP Address |
|------|----------|-----------|
| Router1 | FastEthernet1/0 | 192.168.100.1 |
| Router2 | FastEthernet1/0 | 192.168.100.2 |
| DSW1 | VLAN 1 | 192.168.100.3 |
| DSW2 | VLAN 1 | 192.168.100.4 |
| ASW1 | VLAN 1 | 192.168.100.5 |
| ASW2 | VLAN 1 | 192.168.100.6 |
| ASW3 | VLAN 1 | 192.168.100.7 |
| Host1 | Ethernet | 192.168.100.8 |
| Host2 | Ethernet | 192.168.100.9 |
| Host3 | Ethernet | 192.168.100.10 |

### Loopback Interfaces
| Device | Interface | IP Address |
|------|----------|-----------|
| Router1 | Loopback0 | 192.168.100.16/32 |
| Router2 | Loopback0 | 192.168.100.17/32 |

## IPv6 Addressing
- Prefix: 2001:DB8:3445:ABDE::/64

| Device | Interface | Addressing Method |
|------|----------|------------------|
| Router1 | FastEthernet1/0 | Static |
| Router2 | FastEthernet1/0 | Static |
| DSW1 | VLAN 1 | SLAAC (EUI-64) |
| DSW2 | VLAN 1 | SLAAC (EUI-64) |
| Hosts | Ethernet | SLAAC |
