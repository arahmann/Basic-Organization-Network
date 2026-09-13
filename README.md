# Basic Organization Network Project

A simulated enterprise branch network designed and implemented in Cisco Packet Tracer.

## Architecture & Features Implemented
- **VLAN Segmentation:** Multi-department isolation (Management, IT, HR, Sales, Guest).
- **Inter-VLAN Routing:** Configured Router-on-a-Stick (802.1Q encapsulation) for secure routing between subnets.
- **Dynamic IP Allocation:** Centralized router DHCP pools serving host addresses dynamically per VLAN.
- **Shared Enterprise Resources:** Centralized file sharing and network printing accessible across departments.
- **Internet Edge Routing:** Default static routing configured between Edge Router and Public ISP gateway.
- **Network Address Translation (NAT/PAT):** Dynamic NAT overload (PAT) implemented on the edge interface to map private internal IP space to a routable ISP address for external web access.

## Future Enhancements
- [ ] Implement Access Control Lists (ACLs) for department-level traffic filtering and guest isolation.
- [ ] Configure Port Security and DHCP Snooping on access switches to prevent unauthorized access.
- [ ] Add ASA Firewall for stateful inspection and edge security.

## How to Test
1. Open \`Basic Organization Network Project.pkt\` in Cisco Packet Tracer.
2. Verify DHCP assignment across departmental client PCs.
3. Test intra-VLAN and inter-VLAN ping reachability.
4. Access the simulated Public ISP Web Server from any internal host to verify PAT translation.
