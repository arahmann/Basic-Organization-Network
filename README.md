# Basic Organization Network Project

A simulated enterprise branch network designed in Cisco Packet Tracer.

## Features Implemented
- **VLAN Segmentation:** Departments split into separate VLANs (Management, IT, HR, Sales, Guest).
- **Inter-VLAN Routing:** Router-on-a-Stick (802.1Q encapsulation) for routing between departments.
- **Centralized DHCP:** Router configured to dynamically assign IP pools to all VLANs.
- **Shared Resources:** Centralized printer and local services accessible across subnets.

## Planned Enhancements
- [ ] Access Control Lists (ACLs) for traffic filtering and department isolation
- [ ] NAT/PAT & Default Routing for simulated ISP connectivity
- [ ] Port Security on Access Switches
