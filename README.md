# Packet Tracer Labs - Practical Network Engineering

This repository contains my hands-on Cisco Packet Tracer labs. These are not theoretical exercises — they are complete, working network implementations built from scratch.

## What This Is
- Real, configured `.pkt` files you can open in Cisco Packet Tracer.
- Documentation of what works and why.
- A log of my progression from basic switching to complex routing and security.

## Labs Included

### 1. **Enterprise LAN Foundation**
- **File:** `enterprise-lan-basics.pkt`
- **What I built:** Multi-switch topology with VLANs (10, 20, 99), trunking, and inter-VLAN routing.
- **Skills proven:** VLAN configuration, 802.1Q trunking, Layer 3 switching, DHCP scoping.
- **Verification:** Full ping connectivity across subnets.

### 2. **OSPF & Dynamic Routing Lab**
- **File:** `ospf-multi-area.pkt`
- **What I built:** Multi-area OSPF with Area 0, Area 1, ABR, and virtual links.
- **Skills proven:** OSPF adjacency, route summarization, LSA types, cost manipulation.
- **Verification:** `show ip ospf neighbor`, `show ip route` outputs included.

### 3. **Network Security Stack**
- **File:** `security-acls-port-security.pkt`
- **What I built:** Layered security: ACLs (standard/extended), port security, SSH-only access.
- **Skills proven:** Traffic filtering, mitigation of ARP spoofing, device hardening.
- **Verification:** ACL hit counters, secured login, blocked unauthorized traffic.

### 4. **Advanced Services: DHCP, DNS, HSRP**
- **File:** `advanced-services.pkt`
- **What I built:** Redundant gateway with HSRP, enterprise DHCP with IP helper, internal DNS.
- **Skills proven:** Service redundancy, protocol tuning, failover testing.
- **Verification:** DHCP leases, HSRP active/standby roles, DNS resolution.

## How to Use
1. Download Cisco Packet Tracer (if you don't have it).
2. Clone this repo: `git clone https://github.com/YOURUSERNAME/packet-tracer-labs.git`
3. Open any `.pkt` file in Packet Tracer.
4. See the configurations with `show run` on devices.

## Why This Exists
I built this to:
- Move from "knowing" to "doing."
- Create a public record of my practical skills.
- Help others see what a working config looks like.

## Notes
- These labs are built for learning and demonstration.
- They are not production designs but reflect real protocols and configurations.
- Feedback and issues are welcome.

---

*Last updated: [DATE]*
