# Cisco Packet Tracer Labs

Hands-on Cisco Packet Tracer practice labs covering core CCNA-level networking topics, built while studying Cybersecurity at Asia Pacific University (APU). Labs 01 to 09 include a `.pkt` file you can open and explore. Lab 10 is a written case study with configs and troubleshooting notes.

![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7)
![Labs](https://img.shields.io/badge/labs-10%20completed-brightgreen)
![Level](https://img.shields.io/badge/level-CCNA-blue)

## Skills Demonstrated

- **Switching:** VLANs, trunking (802.1Q), port security, EtherChannel (PAgP)
- **Routing:** OSPF, RIPv2, static routing and redistribution, inter-VLAN routing (router-on-a-stick and Layer 3 SVI)
- **Redundancy:** HSRP first-hop redundancy
- **Services:** DHCP and DHCP relay, SSH secure remote access
- **Wireless:** WLC and WLAN configuration
- **Security and VPN:** Standard ACLs, GRE tunnels
- **Troubleshooting:** Reading `show` output to find addressing, ACL direction and tunnel errors

## Labs

| # | Lab | Topics |
|---|-----|--------|
| 01 | [SSH Configuration](01-ssh-config) | Domain name, RSA keys, local users, VTY lines |
| 02 | [VLAN Configuration](02-vlan-config) | VLAN creation, access port assignment |
| 03 | [Inter-VLAN and Trunk](03-intervlan-trunk) | 802.1Q trunking, router-on-a-stick |
| 04 | [DHCP](04-dhcp) | Remote DHCP and relay across subnets |
| 05 | [OSPF](05-ospf) | Dynamic routing with OSPF |
| 06 | [Port Security](06-port-security) | MAC limiting, violation modes |
| 07 | [Layer 3 Inter-VLAN Routing](07-layer3-intervlan) | SVIs on a Layer 3 switch |
| 08 | [HSRP](08-hsrp) | Active/standby gateway redundancy |
| 09 | [WLC and WLAN](09-wlc-wlan) | Wireless controller and WLAN setup |
| 10 | [GRE VPN, HSRP, RIP, PAgP and ACL](10-gre-hsrp-rip-pagp) | GRE tunnel, RIP redistribution, EtherChannel, ACL, troubleshooting write-up |

## Repository Structure

```
Cisco-Packet-Tracer-Labs/
├── 01-ssh-config/
├── 02-vlan-config/
├── ...
├── 09-wlc-wlan/
├── 10-gre-hsrp-rip-pagp/
│   ├── README.md
│   └── topology.png
└── README.md
```

## How to Use

1. Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Open the `.pkt` file inside any lab folder (labs 01 to 09).
3. Inspect the topology and run `show running-config` or `show ip route` on the devices.
4. For lab 10, read the README in the folder.

## Related Projects

- [Enterprise-Network-Design](https://github.com/tanmay1802-art/Enter
