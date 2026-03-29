# Enterprise Multi-Site VoIP Network

## Overview
This project is a multi-site enterprise network built in Cisco Packet Tracer. It simulates multiple connected locations with VoIP communication, VLAN segmentation, OSPF routing, NAT, DHCP, DNS, HSRP redundancy, and EtherChannel.

## Objectives
- Build a multi-site routed network
- Configure VLAN-based segmentation for voice, data, server, management, and native VLANs
- Implement OSPF between sites and ISP routers
- Configure NAT/PAT for outside connectivity
- Enable VoIP communication between multiple locations
- Implement gateway redundancy with HSRP
- Configure EtherChannel between switches

## Technologies Used
- Cisco Packet Tracer
- VLANs
- Router-on-a-stick
- OSPF
- NAT/PAT
- Static NAT
- DHCP
- DNS
- VoIP dial peers
- HSRP
- EtherChannel

## Topology

### Edge / Site Layout
<img width="1468" height="471" alt="image" src="https://github.com/user-attachments/assets/aadfcf58-45d2-459a-9570-455cf4c9200d" />

### Distribution / Multi-Site Connectivity
<img width="1483" height="923" alt="image" src="https://github.com/user-attachments/assets/a31bdb76-40e7-41fc-985b-282e01b869fa" />

### Core Network (Redundancy & High Availability)
<img width="1515" height="961" alt="image" src="https://github.com/user-attachments/assets/e639e128-82a0-43ef-8254-8e73d691037f" />





## Key Configurations
- OSPF for dynamic routing across sites
- Subinterfaces for inter-VLAN routing
- NAT overload and static NAT for internal services
- Dial peers for inter-site VoIP calling
- HSRP for gateway redundancy at the VOIP9000 site
- EtherChannel between access/distribution switches

## What I Learned
- How to design and troubleshoot multi-site networks
- How routing, segmentation, and voice services work together
- How redundancy improves network availability
- How enterprise services like DHCP, DNS, and NAT fit into network design

## Files Included

- [Download Packet Tracer Lab](lab/voip-phase4.pkt)
- [View Configuration File](configs/voip-configs.txt)
- Network topology screenshots (included above)
